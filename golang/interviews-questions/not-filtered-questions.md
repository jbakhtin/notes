
Вопросы по истории языка:
1. Кем был создан язык, какие его особенности?
2. Какие Преимущества У Go Перед Другими Языками?
3. Расскажите чем вам нравится язык Golang, какие есть недостатки?
4. Что такое Голанг?
5. Почему вы должны изучать голанг? В чем преимущества Golang перед другими языками программирования?
6. Почему Golang надежен?
7. Почему был разработан язык Go?
8. Who developed Golang?
9. Is Golang quick?
10. Что такое Golang и какие основные принципы лежат в его основе?
11. Какие основные особенности Golang отличают его от других языков программирования?
12. Каковы преимущества использования Golang?
13. Каковы основные различия между Golang и Python?
14. What are the benefits of using Go compared to other languages?
15. What makes Go compile quickly?
16. What does it mean when people say Go has a “rich standard library”?
17. Why should one learn Golang? What are the advantages of Golang over other languages?
18. Why is Golang fast compared to other languages?
19. _Go_ — императивный или декларативный? А в чем разница?
20. What are design patterns?
21. Поддерживает ли Golang наследование?
22. Каким образом в Golang реализовано наследование?
23. What makes Go so fast?
24. What is a unique benefit of Go’s compiler?
25. Какие технологические преимущества языка _Go_ вы можете назвать?
26. Какие технологические недостатки языка _Go_ вы можете назвать?

Вопросы на знание принципов ООП:
1. Что такое ООП? Как это сделано в Golang?
2. . Как устроено инвертирование зависимостей?
3. Что Такое Шаблоны Проектирования?
4. Дайте Объяснение Объектно-Ориентированной Архитектуре Голанга.
5. Why is Go often called a “Post-OOP” language?
6. Почему встраивание — не наследование?
7. Разрешает Ли Golang Наследование?

Среда выполнения:
1. Как Настраиваются Рабочие Среды И Параметры В Golang?
2. Опишите рабочее пространство в Go.
3. Что означает переменная окружения PATH?
4. What is the purpose of a GOPATH environment variable?
5. How do you implement command-line arguments in Go?
6. What does GOROOT point to?
7. How is GoPATH different from GoROOT variables in Go?
8. Нужно Ли Иметь Переменные GOPATH И GOROOT, И Если Да, То Почему?

Типы данных:
1. Как устроены строки в Go?
2. Что можешь рассказать про `map`?
3. Что такое `type switch`?
4. Что такое дженерики?
5. Какие Типы Преобразования Поддерживает Golang?
6. Опишите Назначение И Действие Утверждения Типа.
7. Что Такое Тип Структуры?
8. Какие Типы Данных Поддерживает Golang?
9. Что Вы Подразумеваете Под Статическим Объявлением Типа Переменной В Golang?
10. What are the data types in Go?
11. What data types does Golang use?
12. How do you check a variable type at runtime?
13. How do untyped constants interact with Go’s typing system?
14. Is it possible to declare variables of different types in a single line of code in Golang?
15. What do you understand by Type Assertion in Go?
16. How will you check the type of a variable at runtime in Go?
17. Что такое _type switch_?
18. Как реализовать в _Go_ тип-сумму, который может содержать в себе значения _int64|float64|complex_? Как реализовать для такого типа метод _Add(int64)_?

Строки:
1. Что Такое Строковые Литералы?
2. Что из себя представляет тип данных string в языке Golang? Можно ли изменить определенный символ в строке? Что происходит при склеивании строк?
3. Вытекающий вопрос — как эффективно склеивать множество строк?
4. Что такое строковые литералы?
5. Что такое строка в GoLang?
6. What are string literals?
7. How do you concatenate strings?
8. Format a string without printing it?
9. What do you understand by Golang string literals?
10. Can you format a string without printing?

Руны:
1. Опишите Руну.
2. Что такое руна в голанге?
3. What do you understand by byte and rune data types? How are they represented?

Слайсы:
1. В чём ключевое отличие слайса (среза) от массива?
2. Как работает `append` в слайсе?
3. Какое у слайса zero value? Какие операции над ним возможны?
4. Что Такое Слайсы В Go?
5. Что такое slice? Расскажите внутреннее устройство
6. Как работает функция append? Как происходит аллокация нового массива при использовании функции append?
7. Сколько байт занимает в памяти структура slice?
8. Что такое slice, как устроены и чем отличаются от массивов?
9. Что такое len и capacity в slice Go?
10. Что такое слайсы? Сложность. [Внутренняя структура Навыки — менторская программа](https://www.youtube.com/@Skills_mentor/videos)
11. Print all permutations of a slice characters or string
12. Reverse the order of a slice
13. What is the easiest way to check if a slice is empty?
14. What is the difference between C arrays and Go slices?
15. What is “slice” in Go?
16. How can we copy a slice and a map in Go?
17. How can you sort a slice of custom structs with the help of an example?
18. Write a Go code to compare two slices of a byte.
19. Какое у _slice zero value_? Какие операции над ним возможны?
    1. помнит ли кандидат, что вообще можно делать со слайсом, и как ведут себя операции на граничных значениях. Почему это важно? «Почему это важно?» — был бы отличный вопрос для интервью, если бы я придумал, как его корректно задавать.
    2. каков будет результат _append([]string(nil), ""_)? А _append([]string(nil), []string(nil)..._)? А почему? А _range append([]string(nil), []string(nil)..._) как отработает?


Список источников с вопросами
- https://habr.com/ru/articles/658623/
1. ~~Кем был создан язык, какие его особенности?
2. ~~Что такое ООП? Как это сделано в Golang?
3. ~~Как устроено инвертирование зависимостей?
5. ~~Как устроены строки в Go?
6. ~~В чём ключевое отличие слайса (среза) от массива?
7. Как вы отсортируете массив структур по алфавиту по полю `Name`?
8. ~~Как работает `append` в слайсе?
9. ~~Какое у слайса zero value? Какие операции над ним возможны?
10. ~~Что можешь рассказать про `map`?
    1. Как растет `map`?
    2. Что там про поиск?
    3. Есть ли у `map` такие же методы как у слайса: `len`, `cap`?
    4. Какие типы ключей разрешены для ключа в `map`?
    5. Может ли ключом быть структура? Если может, то всегда ли?
    6. Race condition. Потокобезопасна ли мапа?
11. Что такое интерфейс?
    1. Как устроен Duck-typing в Go?
    2. Интерфейсный тип
    3. Пустой `interface{}`
    4. На какой стороне описывать интерфейс — на передающей или принимающей?
12. Что такое замыкание?
13. Что такое сериализация? Зачем она нужна?
14. ~~Что такое `type switch`?
15. Какие битовые операции знаешь?
16. Дополнительный блок фигурных скобок в функции
17. Что такое захват переменной?
18. Как работает `defer`?
19. Как работает `init`?
20. Сколько можно возвращать значений из функции?
21. Дженерики — это про что?
    1. Параметризованные функции
    2. Параметризованные типы
22. Память и управление ей
    1. Что такое `heap` и `stack`?
    2. Где выделяется память под переменную? Можно ли этим управлять?
    3. Как работает Garbage Collection (`GC`) в Go?
23. Какое поведение по умолчанию используется в Go при передаче в функцию?
24. Что можешь рассказать про escape analysis?
25. Сoncurrency (конкурентность)
    1. Как устроен мьютекс?
        1. В чем отличие `sync.Mutex` от `sync.RWMutex`?
    2. Что такое `synс.Map`?
    3. Какие ещё примитивы синхронизации знаешь?
    4. Какие типы каналов существуют?
    5. Что можно делать с закрытым каналом?
    6. Расскажи про планировщик (горутин)
    7. Что такое горутина?
        1. В чем отличия горутин от потоков ОС?
        2. Где аллоцируется память для горутин?
        3. Как завершить много горутин?
    8. Кейсы использования контекста
    9. Как задетектить гонку?
26.  Тестирование
     1. TDT, Table-driven tests (табличное тестирование)
     2. Имя пакета с тестами
     3. Статические анализаторы (линтеры)
     4. Ошибка в бенчмарке
     5. Что про функциональное тестирование?
27. Профилирование (`pprof`)
    1. Пример использования `pprof`
    2. Так как же профилировщик работает в принципе?
28.  Компилятор
     1. Из каких этапов состоит компиляция?
     2. Статическая компиляция/линковка — что это, и в чем особенности?
     3. Какие директивы компилятора знаешь?

- https://hashdork.com/ru/самые-популярные-вопросы-на-собеседовании-в-golang/
1. ~~Опишите Голанг
2. ~~Какие Преимущества У Go Перед Другими Языками?
3. Что Такое Fmt В Программировании На Golang?
4. Что Такое Интерфейсы Go?
5. ~~Что Такое Строковые Литералы?
6. ~~Как Настраиваются Рабочие Среды И Параметры В Golang?
7. Опишите Пакеты Golang?
8. ~~Какие Типы Данных Поддерживает Golang?
9. ~~Что Вы Подразумеваете Под Статическим Объявлением Типа Переменной В Golang?
10. Что Такое Объявление Динамической Переменной В Golang?
11. Как Я Могу Использовать Пользовательские Пакеты В Языке Программирования GO?
12. Что Такое Горутина? Как Вы Можете Положить Этому Конец?
13. ~~Опишите Руну.
14. Что Такое Идиома Go Для Представления Перечислений?
15. Как Проверяется Тип Переменной Во Время Выполнения?
16. Опишите Каналы Go.
17. Объясните Методы Голанга.
18. Что Такое Гонка Данных?
19. Что Такое Сборка Мусора В Go?
20. Опишите Этапы Тестирования С Помощью Golang.
21. ~~Что Такое Слайсы В Go?
22. Что Такое Динамическая Память?
23. Что Такое Замыкание Функций?
24. Что Означает Оператор Goto Голанга?
25. Что Такое Lvalue И Rvalue В Golang?
26. Какие Конструкции Циклов Существуют В Go?
27. ~~Что Такое Шаблоны Проектирования?
28. Какой Пакет Golang Лучше Всего Подходит Для Простых Операций С Файлами? Какие Дополнительные Пакеты Golang Используются Для Работы С Файлами?
29. ~~Дайте Объяснение Объектно-Ориентированной Архитектуре Голанга.
30. ~~Какие Типы Преобразования Поддерживает Golang?
31. ~~Опишите Назначение И Действие Утверждения Типа.
32. ~~Что Такое Тип Структуры?
33. Объясните Резервный Массив Значения Среза.
34. ~~Нужно Ли Иметь Переменные GOPATH И GOROOT, И Если Да, То Почему?
35. ~~Разрешает Ли Golang Наследование?
36. Как Выглядит CGo В Golang?
37. Какой Тип Указателя В Golang?

- https://parshinpn.ru/ru/blog/golang-interview
1. Общие вопросы:
    1. Вопросы по предыдущим местам работы. Причины ухода с текущего места, ожидания от будущего работодателя.
    2. Вопросы по soft skills. Например, опишите вашего идеального руководителя или кем вы видите себя через 5 лет.
    3. ~~Расскажите чем вам нравится язык Golang, какие есть недостатки?
    4. Расскажите, что происходит, когда пользователь набирает в адресной строке браузера, например, google.ru.
2. Слайсы
    1. ~~Что такое slice? Расскажите внутреннее устройство
    2. ~~Как работает функция append? Как происходит аллокация нового массива при использовании функции append?
    3. ~~Сколько байт занимает в памяти структура slice?
3. interfaces
    1. Что такое интерфейс? Расскажите внутреннее устройство.
    2. Пример кода на понимание внутреннего представления интерфейсов.
    3. Пример кода с интерфейсом и value/pointer receiver.
4. multithreading
    1. Что такое горутина? В чем отличие горутин от потоков операционной системы?
    2. Как работает планировщик горутин?
    3. Кооперативная многозадачность vs вытесняющая многозадачность.
    4. Какие вы знаете способы синхронизации между горутинами в Go?
    5. Задача на многопоточность. Обычно просили реализовать свой worker pool, который сможет принимать на вход задачи и обрабатывать их параллельно.
5. channels
    1. Что такое каналы в Go и как они устроены? Какие виды каналов вы знаете?
    2. Что происходит при записи или чтении в/из nil канала, закрытого канала, буферизированного/небуферизированного канала?
    3. Что такое select и как он работает?
6. map
    1. Что это за структура данных, какие ее преимущества?
    2. Что происходит при конкурентной записи в map?
    3. Какие типы данных могут быть использованы в качестве ключа map?
7. обработка ошибок
    1. Назовите два способа работы с ошибками в Go?
    2. Как можно обработать панику?
    3. Как можно определить место возникновения ошибки?
8. другое
    1. Что такое контекст и в каких случаях его стоит использовать?
    2. Как работает garbage collector?
    3. Что такое escape analysis и как он работает?
    4. Что такое defer?
9. Базы данных
    1. Что такое ACID?
    2. Какие виды изоляции транзакций вы знаете? На одном собеседовании попросили привести пример SQL запроса, который будет выполнен на уровне Repetable Read, но вернет ошибку на уровне Serializable ([ответ](https://postgrespro.ru/docs/postgrespro/9.5/transaction-iso#xact-serializable)).
    3. Назовите известные вам виды индексов. Отличия между hash и b-tree индексами. Как устроен b-tree индекс (хорошее [видео](https://www.youtube.com/watch?v=aZjYr87r1b8) на эту тему)?
    4. Построение индексов на запросы (стоит вспомнить что такое селективность). Пример запроса: `SELECT a, b FROM table WHERE a = 0 AND b > 1 ORDER BY c`
    5. Шардирование и репликация данных.
10. Сети
    1. Достаточно знать особенности и отличия транспортных протоколов TCP и UDP. Один раз спросили каким образом происходит преобразование IP адреса в MAC адрес узла: рассказываем про протокол ARP и arping.
11. Архитектура
    1. Здесь уже вариативность вопросов большая. Например, приходилось проектировать пользовательскую ленту Facebook, сервис сокращения ссылок с нагрузкой на чтение и запись в 300000 RPS. Обычно в разговоре затрагиваются темы проектирования отказоустойчивых, масштабируемых решений, способы хранения данных (репликация и шардирование), кэширование данных, мониторинги и логирование, API.
    2. В интернете можно найти много видео и материалов на тему подготвки и прохождения архитектурных секций. Рекомендую их изучить, чтобы быть готовыми.

- https://github.com/goavengers/go-interview/tree/master/docs/golang#2
1. ~~Что из себя представляет тип данных string в языке Golang? Можно ли изменить определенный символ в строке? Что происходит при склеивании строк?
2. ~~Вытекающий вопрос — как эффективно склеивать множество строк?
3. Как задать направление канала?
4. Напишите собственную функцию Sleep, используя time.After
5. Что такое буферизированный канал? Как создать такой канал с ёмкостью в 20 сообщений?
6.  Напишите программу, которая меняет местами два числа (x := 1; y := 2; swap(&x, &y) должно дать x=2 и y=1)
7. Какое будет значение у переменной x после выполнения программы?
8. Какое значение примет выражение (true && false) || (false && true) || !(false && false)?
9. Как работает Garbage Collection в Go?
10. Что такое interface, как они работают в Go?
11. ~~Что такое slice, как устроены и чем отличаются от массивов?
12. ~~Что такое len и capacity в slice Go?
13. Возможно ли предугадать, что GC отработает за константное время N?
14. Что будет, если создать канал и отправить туда запись, но у него нет читателей?

- https://hackr.io/blog/golang-interview-questions-and-answers
1. Basic Go Interview Questions and Answers
    1. ~~Что такое Голанг?
    2. ~~Почему вы должны изучать голанг? В чем преимущества Golang перед другими языками программирования?
    3. ~~Почему Golang надежен?
    4. Что такое пакеты Golang?
    5. Принимает ли Golang во внимание ‘случаи’?
    6. Что такое указатели в Golang?
    7. Что означает программа Golang goroutine?
    8. ~~Опишите рабочее пространство в Go.
    9. ~~Что такое строковые литералы?
    10. ~~Что означает переменная окружения PATH?
    11. ~~Что такое строка в GoLang?
    12. Что такое объявление статического типа переменной Go?
    13. ~~Почему был разработан язык Go?
    14. Что такое интерфейсы Go?
    15. How are channels used in Golang, and what are Go channels?
    16. Что такое вариационные функции в Go?
    17. What is the constant variable in Go?
    18. Какие различные типы операторов доступны в Go?
2. Intermediate Go Interview Questions and Answers
    1. Differentiate between const and read-only keywords.
    2. What is garbage collection in Go?
    3. What is heap memory?
    4. ~~What are the data types in Go?
    5. Declare multiple variables in a single line in Go.
    6. Write a program to remove non-alphanumeric characters from a string.
    7. !!What are slices in Go?
    8. Write a simple text on the console in Go.
    9. What is a structure in Go?
    10. What are timers and tickers in Go?
    11. What is Regex?
    12. What is the goto statement in Golang?
    13. ~~What are design patterns?
    14. What is the switch statement?
    15. Does Go support automatic type conversion?
    16. What is the scope of a variable?
    17. Explain the distinction between methods and functions in Golang.
3. Advanced Golang Interview Questions for Experienced Developers
    1. What are Golang's built-in supports?
    2. Why do we use the break statement in Golang?
    3. Why do we use the continue statement in Golang?
    4. How do you conduct testing in Golang?
    5. Can we compare two structures in Go?
    6. What is a select statement in Golang?
    7. ~~Who developed Golang?
    8. ~~Поддерживает ли Golang наследование?
    9. Do exceptions exist in Go?
    10. Do optional parameters exist for Go?
    11. ~~Что такое руна в голанге?
    12. What are closures for functions?
    13. How does CGo look in Golang?
    14. Что такое ‘lvalue’ и ‘rvalue’ в Go?
    15. ~~Is Golang quick?
- https://itanddigital.ru/bloghrconsulting/tpost/n2hx78z0e1-20-voprosov-dlya-sobesedovaniya-golang-r
1. ~~Что такое Golang и какие основные принципы лежат в его основе?
2. ~~Какие основные особенности Golang отличают его от других языков программирования?
3. ~~Каковы преимущества использования Golang?
4. ~~Каковы основные различия между Golang и Python?
5. Каковы основные пакеты в стандартной библиотеке Golang?
6. Что такое goroutine и какие преимущества она предоставляет?
7. Какие механизмы синхронизации доступны в Golang?
8. Что такое пул горутин (goroutine pool) и в чем его преимущества?
9. Что такое defer в Golang и как он работает?
10. Что такое интерфейсы (interfaces) в Golang и как они используются?
11. ~~Каким образом в Golang реализовано наследование?
12. Как обрабатываются ошибки в Golang?
13. Что такое пакеты (packages) в Golang и как они используются?
14. Как можно обработать сигналы (signals) в Golang?
15. Какие инструменты доступны для тестирования в Golang?
16. Какие есть инструменты для профилирования производительности в Golang?
17. Каковы принципы работы с базами данных в Golang?
18. Как можно создать веб-сервер с использованием Golang?
19. Как можно обработать JSON-данные в Golang?
20. Какие рекомендации по безопасности нужно учитывать при разработке Golang приложений?
- https://vc.ru/u/1389654-machine-learning/694157-15-voprosov-s-sobesedovaniy-golang-iz-linkedin-assessment-podrobnye-poyasneniya
1. Что нужно, чтобы две функции были одного типа?
2. Что возвращает функция len(), если ей передаётся строка в кодировке UTF-8?
3. Каково значение Read?
4. Как вы скажете go test вывести запущенные тесты?
5. Что делает блок sync.Mutex, пока он заблокирован?
6. Каков идиоматический способ приостановить выполнение текущей области до тех пор, пока не будет возвращено произвольное количество подпрограмм?
7. Каков побочный эффект использования time.After в утверждении select?
8. Какие ограничения есть на тип var для компиляции i := myVal.(int)?
9. Как правильно передать это как тело запроса HTTP POST?
10. Каким должно быть идиоматическое имя для интерфейса с одним методом и сигнатурой Save() error?
11. Какова чувствительность к регистру по умолчанию для функции JSON Unmarshal?
12. Где полезен встроенный метод recover?
13. В чём разница между time пакетами Time.Sub() и методами Time.Add()?
14. Каков риск использования нескольких тегов полей в одной структуре?
15. Если вы перебираете карту в цикле for range, в каком порядке будет осуществляться доступ к парам ключ:значение?
- https://www.youtube.com/watch?v=_rTuAY7b1RE
1. Что такое транзакции? Уровни изоляции транзакций? Нормали (Postgres 15 изнутри)
2. Индексы, Работа с операциями explain
3. Kafka консюмер, продюсер и тд (офф Плей лист Кафки на ютубе)
4. http, rest api, сравнить http и https, сравнить https и http2, протоколы прикладного уровня, tcp и udp, гарантия доставки и последовательности, процесс устнавления tcp соединения
5. Многопоточность
    1. race condition
    2. dead lock
    3. sync пакет
        1. митекс
        2. рвмютекс
        3. Синк мапы, зачем нужна, если обычную мапу можно обернуть в мютекс
6. Интерфейсы
    1. type assertion
    2. из чего состоит
    3. сравнение с nil [вопросы на миллион долларов](https://www.youtube.com/watch?v=eOyxRI8FQm4)
7. Горутины и каналы (Аксиомы каналов го)
    1. Почему горутины легковесные?
    2. Сравнение горутин и системных тредов
    3. Что такое context swith?
    4. что такое стек и куча?
    5. Где аллоцируется стек?
    6. Как рабоатет шедуллер (Планировшик задачь)
    7. Что такое вытесняющая и кооперативная многозадачность?
8. Что такое мапа?
    1. Сложность
    2. Внутренняя структура
    3. Что может быть ключем мапы?
    4. Почему не горантирован порядок обхода?
    5. Что такое эвакуация данных?
    6. Что такое баккет?
    7. Что такое экстра баккет?
    8. Что такое коллизия?
    9. Что происходит когда случается много коллизий?[Как на самом деле устроен тип Map в Golang?](https://www.youtube.com/watch?v=P_SXTUiA-9Y)
    10. ~~Что такое слайсы? Сложность. [Внутренняя структура Навыки — менторская программа](https://www.youtube.com/@Skills_mentor/videos)

- https://www.educative.io/blog/50-golang-interview-questions
1. ~~What are the benefits of using Go compared to other languages?
2. ~~What are string literals?
3. ~~What data types does Golang use?
4. What are packages in a Go program?
5. What form of type conversion does Go support? Convert an integer to a float.
6. What is a goroutine? How do you stop it?
7. ~~How do you check a variable type at runtime?
8. ~~How do you concatenate strings?
9. Intermediate Golang Questions
    1. Explain the steps of testing with Golang.
    2. What are function closures?
    3. How do we perform inheritance with Golang?
    4. Explain Go interfaces. What are they and how do they work?
    5. What are Lvalue and Rvalue in Golang?
    6. What are the looping constructs in Go?
    7. Can you return multiple values from a function?
10. Coding challenges with Golang
    1. Implement a Stack (LIFO)
    2. ~~Print all permutations of a slice characters or string
    3. Swap the values of two variables without a temporary variable
    4. Implement min and max behavior
    5. ~~Reverse the order of a slice
    6. ~~What is the easiest way to check if a slice is empty?
    7. ~~Format a string without printing it
11. Golang Concurrency Questions
    1. Explain the difference between concurrent and parallelism in Golang
    2. Merge Sort
    3. Sum of Squares
12. More Golang Questions
    1. 26. What is a workspace?
    2. What is CGO? When would you want to use it?
    3. What is shadowing?
    4. ~~What is the purpose of a GOPATH environment variable?
    5. How are pointers used in Go?
    6. What types of pointers does Go have
    7. ~~Why is Go often called a “Post-OOP” language?
    8. Does Go have exceptions? How does Go handle errors?
    9. When would you use a break statement in Go?
    10. ~~How do untyped constants interact with Go’s typing system?
    11. What is the difference between `=` and `:=` in Go?
    12. ~~What is the difference between C arrays and Go slices?
    13. Does Go support method overloading?
    14. ~~What makes Go so fast?
    15. ~~How do you implement command-line arguments in Go?
    16. How does Go handle dependencies?
    17. ~~What is a unique benefit of Go’s compiler?
    18. What is in the src directory?
    19. Name one Go feature that would be helpful for DevOps.
    20. ~~What does GOROOT point to?
    21. ~~What makes Go compile quickly?
    22. Implement a binary search tree data structure in Go.
    23. ~~What does it mean when people say Go has a “rich standard library”?
    24. What is an advantage of Go evaluating implicit types at compile time?
    25. Describe the crypto capabilities of Go.

- https://www.interviewbit.com/golang-interview-questions/
1. Golang Interview Questions for Experienced
    1. ~~What is Golang?
    2. ~~Why should one learn Golang? What are the advantages of Golang over other languages?
    3.  What are Golang packages?
    4.  Is Golang case sensitive or insensitive?
    5.  What are Golang pointers?
    6. ~~What do you understand by Golang string literals?
    7.  What is the syntax used for the for loop in Golang? Explain.
    8.  What do you understand by the scope of variables in Go?
    9.  What do you understand by goroutine in Golang?
    10.  Is it possible to return multiple values from a function in Go?
    11. ~~Is it possible to declare variables of different types in a single line of code in Golang?
    12. ~~What is “slice” in Go?
    13.  What are Go Interfaces?
    14. ~~Why is Golang fast compared to other languages?
    15.  How can we check if the Go map contains a key?
    16.  What are Go channels and how are channels used in Golang?
2.  Golang Interview Questions for Experienced
    1.  What do you understand by each of the functions demo_func() as shown in the below code?
    2. ~~Can you format a string without printing?
    3. ~~What do you understand by Type Assertion in Go?
    4. ~~How will you check the type of a variable at runtime in Go?
    5.  Is the usage of Global Variables in programs implementing goroutines recommended?
    6.  What are the uses of an empty struct?
    7. ~~How can we copy a slice and a map in Go?
    8. ~~How is GoPATH different from GoROOT variables in Go?
    9.  In Go, are there any good error handling practices?
    10.  Which is safer for concurrent data access? Channels or Maps?
    11. ~~How can you sort a slice of custom structs with the help of an example?
    12.  What do you understand by Shadowing in Go?
    13.  What do you understand by variadic functions in Go?
    14. ~~What do you understand by byte and rune data types? How are they represented?
3.  Golang Programs
    1.  Write a Go program to swap variables in a list?
    2.  Write a GO Program to find factorial of a given number.
    3.  Write a Go program to find the nth Fibonacci number.
    4.  Write a Golang code for checking if the given characters are present in a string.
    5. ~~Write a Go code to compare two slices of a byte.

- https://habr.com/ru/companies/oleg-bunin/articles/521582/
1. ~~_Go_ — императивный или декларативный? А в чем разница?
    1.  знакомство с разными подходами к реализации бизнес-логики.
    2. _SQL_ — императивный или декларативный? А _Dockerfile_? А файл настройки _github actions_?
2. ~~Что такое _type switch_?
    1. знакомство с нашим (скудным) инструментарием работы с системой типов в _runtime_.
    2. как реализовать в _Go_ тип-сумму, который может содержать в себе значения _int64|float64|complex_? Как реализовать для такого типа метод _Add(int64)_?
3. Как сообщить компилятору, что наш тип реализует интерфейс?
    1. хорошо ли кандидат понимает, на чем основана концепция интерфейсов в _Go_.
    2. что такое _duck typing_? К чему он применяется в _Go_?
4. Как работает _append_?
    1. знаком ли кандидат с базовыми концепциями управления памятью в _Go_. Самыми базовыми.
    2. как бы вы реализовали разреженный массив в _Go_? А без использования _map_?
5. ~~Какое у _slice zero value_? Какие операции над ним возможны?
    1. ~~помнит ли кандидат, что вообще можно делать со слайсом, и как ведут себя операции на граничных значениях. Почему это важно? «Почему это важно?» — был бы отличный вопрос для интервью, если бы я придумал, как его корректно задавать.
    2. ~~каков будет результат _append([]string(nil), ""_)? А _append([]string(nil), []string(nil)..._)? А почему? А _range append([]string(nil), []string(nil)..._) как отработает?
6. Как устроен тип _map_?
    1. насколько интересно кандидату, как именно ложатся в память наши байтики. _Map_, возможно, самая важная из стандартных структур данных, и весьма замысловато устроенная. Она сложная, она эффективная, она обладает встроенным _race condition_ детектором… Неужели не любопытно?!
    2. какая _hash_-функция используется в _map_ в _Go_? Что такое _bucket_?
7. Каков порядок перебора _map_?
    1. понимает ли кандидат, как отражается устройство структуры данных на ее свойствах. Ну или — читал ли кандидат документацию на базовые типы и запомнил ли неочевидно-важное из нее…
    2. как получить одно случайное значение из _map_?
8. Что будет, если читать из закрытого канала?
    1. читал ли кандидат документацию или сразу бросился кодить. Если читал — запомнил ли очевидно-важное.
    2. сколько значений возвращает одно чтение из канала? А почему _range_-чтение из канала возвращает одно?
9. Что будет, если писать в закрытый канал?
    1. читал ли кандидат документацию или сразу бросился кодить. Если читал — запомнил ли очевидно-важное.
    2. можно ли закрывать канал со стороны читателя? А если очень надо — как быть?
10. Как вы отсортируете массив структур по алфавиту по полю _Name_?
11. Что такое сериализация? Зачем она нужна?
12. Сколько времени в минутах займет у вас написание процедуры обращения односвязного списка?
13. Где следует поместить описание интерфейса: в пакете с реализацией или в пакете, где этот интерфейс используется? Почему?
14. Предположим, ваша функция должна возвращать детализированные _Recoverable_ и _Fatal_ ошибки. Как это реализовано в пакете _net_? Как это надо делать в современном _Go_?
15. Главный недостаток стандартного логгера?
16. Есть ли для _Go_ хороший _orm_? Ответ обоснуйте.
17. Какой у вас любимый линтер?
18. Можно ли использовать один и тот же буфер _[]byte_ в нескольких горутинах?
19. Какие типы мьютексов предоставляет _stdlib_?
20. Что такое _lock-free_ структуры данных, и есть ли в _Go_ такие?
21. Способы поиска проблем производительности на проде?
22. Стандартный набор метрик _prometheus_ в _Go_ -программе?
23. Как встроить стандартный профайлер в свое приложение?
24. _Overhead_ от стандартного профайлера?
25. ~~Почему встраивание — не наследование?
26. Какие средства обобщенного программирования есть в _Go_?
27. ~~Какие технологические преимущества языка _Go_ вы можете назвать?
28.  ~~Какие технологические недостатки языка _Go_ вы можете назвать?

- [Гитхаб изучение конкурентного программирования](https://github.com/golang/go/wiki/LearnConcurrency)
- https://github.com/hoanhan101/algo
- https://dave.cheney.net/2014/03/19/channel-axioms
- https://go.dev/blog/slices-intro
- https://go.dev/blog/slices
- https://grpc.io/
- https://github.com/AlexanderGrom/go-patterns
- https://github.com/mridul-sahu/golang-concurrency-patterns
- https://dave.cheney.net/2016/08/20/solid-go-design
- https://microservices.io/

https://gobyexample.com/
https://golangify.com/


[[Общие вопросы]]