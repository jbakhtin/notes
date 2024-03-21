# Map в Golang

## Полезные ссылки
1. [Николай Тузов - "Как на самом деле устроен тип Map в Golang? | Golang под капотом" на YouTube](https://www.youtube.com/watch?v=P_SXTUiA-9Y&)
2. [Исходники Go map на GitHub](https://github.com/golang/go/blob/master/src/runtime/map.go)

Map это хэш таблица.

### Операции с Map

В данном листинге представлены основные операции со структурой map и их преобразование на более низком уровне.
``` go
val := map[key]     // func mapaccess1(*maptype, *hmap, unsafe.Pointer) unsafe.Pointer
val, ok := map[key] // func mapaccess1(*maptype, *hmap, unsafe.Pointer) (unsafe.Pointer, bool)
map[key] = val      // func mapassign(*maptype, *hmap, unsafe.Pointer) unsafe.Pointer
delete(map, key)    // func mpdelete(*maptype, *hmap, unsafe.Pointer)
``` 

#### Что такое maptype?
[Исходник maptype](https://github.com/golang/go/blob/master/test/fixedbugs/issue4879.dir/a.go)

#### Что такое hmap?
``` go
// A header for a Go map.
type hmap struct {
	// Note: the format of the hmap is also encoded in cmd/compile/internal/reflectdata/reflect.go.
	// Make sure this stays in sync with the compiler's definition.
	count     int // # live cells == size of map.  Must be first (used by len() builtin)
	flags     uint8
	B         uint8  // log_2 of # of buckets (can hold up to loadFactor * 2^B items)
	noverflow uint16 // approximate number of overflow buckets; see incrnoverflow for details
	hash0     uint32 // hash seed

	buckets    unsafe.Pointer // array of 2^B Buckets. may be nil if count==0.
	oldbuckets unsafe.Pointer // previous bucket array of half the size, non-nil only when growing
	nevacuate  uintptr        // progress counter for evacuation (buckets less than this have been evacuated)

	extra *mapextra // optional fields
}
```