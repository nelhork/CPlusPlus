# Понятие алгоритма:
Алгоритм - это конечный, четко определенный набор инструкций, который выполняется для решения определенной задачи или класса задач.

## Свойства алгоритма:
1. `Результативность`: алгоритм должен приводить к получению желаемого результата при выполнении.
2. `Корректность`: алгоритм должен давать правильный результат для всех возможных входных данных.
3. `Точность`: алгоритм должен быть точным и не оставлять места для неоднозначности в его выполнении.
4. `Понятность`: алгоритм должен быть понятным для исполнителя или программиста, который будет его выполнять или реализовывать.
5. `Дискретность`: алгоритм должен состоять из конечного числа шагов, каждый из которых должен быть явно определен и выполним.
6. `Массовость`: алгоритм должен быть применим для решения класса задач, а не только для одной конкретной задачи.

## Типы алгоритмов:
A. `Линейный алгоритм`: это последовательный набор инструкций, выполняющийся один раз без повторений или ветвлений.
Пример:
1. Установите счетчик в 1 и обнулите сумму.
2. Добавьте текущее число к сумме.
3. Увеличьте счетчик на 1.
4. Повторяйте шаги 2-3, пока счетчик не достигнет 10.
5. Разделите сумму на общее количество чисел для получения среднего значения.

B. `Разветвленный алгоритм`: это алгоритм, который содержит условия ветвления и может иметь разные пути выполнения в зависимости от условий.
Пример:
1. Если число равно 0, выведите "Число равно нулю".
2. Если число больше 0, выведите "Число положительное".
3. Если число меньше 0, выведите "Число отрицательное".

C. `Циклический алгоритм`: это алгоритм, который может выполняться многократно в зависимости от определенных условий и содержит циклы или повторяющиеся операции.
Пример:
1. Установите счетчик в 1.
2. Пока счетчик меньше или равен 5, выведите счетчик.
3. Увеличьте счетчик на 1.
4. Вернитесь к шагу 2.

# Блок-схемы
Понятие. `Блок-схема` - это графическое представление алгоритма. 
Использование. Она используется для визуального представления последовательности шагов выполнения задачи.
## Основные элементы блок-схемы:
`Прямоугольники`: Представляют основные шаги алгоритма или процесса.
`Ромбы`: Используются для обозначения условий или решений, которые влияют на ход выполнения алгоритма.
`Овалы`: Используются для обозначения начала и конца алгоритма или процесса.
`Стрелки`: Показывают направление выполнения шагов и связи между разными частями алгоритма.

# Использование CodeBlocks
Среда программирования (интегрированная среда разработки, или IDE) - это программное обеспечение, которое обеспечивает комплексный набор инструментов для разработки программного обеспечения. Она предназначена для облегчения процесса написания, отладки и выполнения кода. `Code::Blocks` - это одна из популярных свободных сред программирования, специально предназначенных для разработки приложений на языках C, C++ и Fortran.

Простой алгоритм работы с Code::Blocks, который поможет вам начать работу с этой средой разработки:
1. Установите Code::Blocks: Перейдите на официальный веб-сайт Code::Blocks (http://www.codeblocks.org/), загрузите соответствующую версию для вашей операционной системы и установите ее на свой компьютер.
2. Запустите Code::Blocks: После установки запустите приложение, чтобы начать работу.
3. Создайте новый проект: Выберите опцию File > New > Project из меню. Выберите тип проекта в зависимости от вашей цели разработки, например, `"Console Application"` для создания консольного приложения на языке C++.
4. Напишите код: Введите свой код в окне редактора, которое появится после создания проекта.
5. Сохраните файл: Не забудьте регулярно сохранять ваш код, чтобы избежать потери данных в случае сбоев системы.
6. Соберите проект: Нажмите на кнопку "Build" (Сборка), чтобы скомпилировать ваш код.
7. Запустите программу: После успешной компиляции нажмите кнопку "Run" (Запуск), чтобы запустить вашу программу и убедиться, что она работает должным образом.
8. Отладка: В случае необходимости выполните отладку вашего кода, используя функционал отладчика, доступный в среде Code::Blocks.
9. Сохраните проект: Не забудьте сохранить свой проект для будущей работы над ним.

## Что такое компиляция?
Компиляция - это процесс преобразования исходного кода на C++ в машинный код или объектные файлы. Компилятор C++ (например, GNU Compiler Collection (GCC) или Clang) преобразует код, написанный на языке C++, в низкоуровневый объектный код, который может быть понятен процессору компьютера. На этапе компиляции происходит проверка синтаксиса, анализ кода на наличие ошибок и создание промежуточных объектных файлов.

## Что такое линковка?
Линковка - это процесс объединения всех объектных файлов, библиотек и других зависимостей, необходимых для создания исполняемого файла. Линковщик (linker) берет все объектные файлы, сгенерированные на этапе компиляции, и связывает их в один исполняемый файл. Линковка также включает разрешение всех внешних ссылок и символов, используемых в программе.

# Первая программа C++
Пример простой программы "Hello, World!" на C++:
```C++
#include <iostream>

int main() {
    // Вывод строки "Hello, World!" на экран
    std::cout << "Hello, World!" << std::endl;

    // Возвращаем 0, что означает успешное завершение программы
    return 0;
}
```
Что означает каждая строка в программе?
```C++
#include <iostream>
```
Это директива препроцессора. Она говорит компилятору включить содержимое библиотеки <iostream>. Эта библиотека предоставляет функциональность ввода/вывода через стандартные потоки (например, std::cout для вывода на консоль).
*Пояснение*: в разработке программного обеспечения есть код, написанный программистом для решения определенной задачи. Этот код обычно расположен в исходных файлах программы, которые программист создает и поддерживает.
Есть также код, написанный другими программистами и организациями, которые решают общие задачи. Такие блоки кода оформлены в виде библиотек, заголовочных файлов и т.д.
Программист может включить эти готовые компоненты в свой код с помощью директив препроцессора.
Препроцессор - программа (часть компилятора), обрабатывающая исходный код программы перед передачей его компилятору.
Директива препроцессора - это инструкция, которая указывает препроцессору, как обрабатывать код перед компиляцией. Все директивы начинаются с `#`.
Директива `#include` включает содержимое файла в программу.
`iostream` - часть стандартной библиотеки C++, которая предоставляет готовые классы и функци для работы с вводом-выводом, строками и т.д.

Стандартные потоки - каналы передачи данных между программой и внешней средой (например, консолью).
```C++
int main() {
```
Это начало определения функции main(). Функция main() является точкой входа в программу. В C++, программа начинает выполнение с этой функции.
Главная причина, почему используют `main`:
- точка входа: когда программа запускается, операционная система ищет именно эту функцию, чтобы начать выполнение.
```C++
std::cout << "Hello, World!" << std::endl;
```
Эта строка использует объект `std::cout` для вывода строки "Hello, World!" на стандартный вывод (обычно консоль). `<<` - оператор вставки, а `std::endl` добавляет символ новой строки и приводит к сбросу буфера вывода.
*Пояснение*: стандартный ввод - это поток данных, программа получается входные данные. Обычно он связан с клавиатурой, поэтому программа считывает данные с клавиатуры.
Стандартный вывод - поток, в который программа отправляет данные для вывода. Обычно он связан с консолью, поэтому программы использует его для вывода результатов.
Для упрощения работы со стандартными потоками, в C++ используется абстракция этих потоков (объекты `std::cin`, `std::cout`). Таким образом, программист работает с объектами, а не напрямую с низкоуровневыми деталями ввода-вывода. Это упрощает и делает его читабельным.
`<<` - это оператор вывода данных в поток. 
`"Hello, World!"` - это строковый литерал.
`std::endl` - это также объект вывода. Основная функциональность - добавление новой строки к потоку.
Таким образом, выражение std::cout << "Hello, World!" << std::endl; говорит программе вывести строку "Hello, World!" в консоль, а затем перейти на новую строку. Весь этот код написан с использованием механизма потоков (streams), который предоставляет гибкий способ взаимодействия с вводом и выводом данных в C++
```C++
return 0;
```
Эта строка завершает функцию main() и возвращает значение 0. Возвращение 0 означает успешное завершение программы. В ОС часто используется этот код возврата для указания, что программа завершилась без ошибок.
Пояснение: `return 0` сообщает операционной системе, что программа завершилась без ошибок.
```C++
}
```
Это закрывающая фигурная скобка, обозначающая конец блока кода функции main().
```C++
// Вывод строки "Hello, World!" на экран
```
Это строка с комментарием к программе: Комментарии — это заметки к программе, которые предназначены исключительно для программиста. Компилятор игнорирует их.

## Использование управляющих символов в выводе
Объект вывода `std::cout` предоставляет средства для вывода данных какое-либо устройство вывода (консоль). `Управляющие символьные последовательности` используются для изменения формата вывода.
`\n`: Новая строка (переход на следующую строку):
```C++
std::cout << "Строка 1\nСтрока 2\n";
```
`\t`: Горизонтальная табуляция (переход на следующую позицию табуляции).
```C++
std::cout << "Текст до табуляции\tТекст после табуляции\n";
```
`\r`: возврат каретки (перемещение курсора в начало строки)
```C++
std::cout << "Строка 1\rСтрока 2\n";
```
`\b`: Возврат на один символ назад (backspace).
```C++
std::cout << "ABC\bD\n"; // Выведет "ABD"
```
`\\`: Обратная косая черта (сама по себе).
```C++
std::cout << "Путь к файлу: C:\\Проект\\файл.txt\n";
```
`\'`: Одинарная кавычка (сама по себе).
```C++
std::cout << "Одинарная кавычка: '\''\n";
```
`\"`: Двойная кавычка (сама по себе).
```C++
std::cout << "Строка в кавычках: \"Пример\"\n";
```

# Стандартная библиотека C++
Стандартная библиотека C++ (Standard Template Library, STL) — это коллекция шаблонных классов и функций, предоставляемых в рамках стандарта C++. Она включает несколько компонентов, каждый из которых предоставляет различные возможности:

1. #### `Input/Output Stream Library (iostream)`: Включает в себя классы для стандартного ввода (std::cin) и вывода (std::cout), работу с файлами (std::ifstream, std::ofstream), и другие возможности ввода-вывода.

2. `Standard Template Library (STL)`: Это обширная библиотека, включающая контейнеры (например, векторы, списки, множества), алгоритмы (например, сортировка, поиск), итераторы, адаптеры и функциональные объекты.

3. `Algorithms Library (algorithm)`: Содержит общие алгоритмы, такие как сортировка, поиск, трансформации и другие.

4. `Numerics Library (numeric)`: Предоставляет математические функции и алгоритмы, такие как вычисление суммы элементов, численное интегрирование и другие.

5. `Containers Library (container)`: Содержит контейнеры данных, такие как векторы, списки, стеки, очереди и многие другие.

6. `Iterators Library (iterator)`: Предоставляет итераторы, которые являются обобщенными объектами, используемыми для обхода элементов в контейнерах или последовательностях.

7. #### `Strings Library (string)`: Включает в себя класс std::string для работы со строками, а также функции для их манипулирования.

8. `Memory Allocation and Management (memory)`: Содержит умные указатели (std::shared_ptr, std::unique_ptr) и некоторые алгоритмы для управления памятью.

9. `C Standard Library (cstdlib)`: Включает в себя функции для работы с языком C, такие как malloc, free, и другие.

`cin (console input)` и `cout (console output)`: Эти объекты являются частью Input/Output Stream Library (iostream). `cin` представляет стандартный входной поток (обычно клавиатура), а `cout` представляет стандартный выходной поток (обычно экран). Они используются для ввода и вывода данных. Например:

```C++
Copy code
#include <iostream>

int main() {
    int x;
    std::cout << "Enter a number: ";
    std::cin >> x;
    std::cout << "You entered: " << x << std::endl;

    return 0;
}
```
Префикс `std::` в C++ используется для указания, что класс, функция или объект принадлежит стандартной библиотеке языка C++. Это соглашение позволяет избежать конфликтов имен между частными именами, определенными в вашем коде, и именами из стандартной библиотеки.

Стандартная библиотека C++ определена в пространстве имен std. Префикс `std::` является частью этого пространства имен и предотвращает неоднозначность, когда имена из вашего кода совпадают с именами из стандартной библиотеки.

Пример:
```C++
#include <iostream>

int main() {
    int x = 42;

    // без использования префикса std:: - это приведет к ошибке
    cout << "Value of x: " << x << endl;

    // с использованием префикса std::
    std::cout << "Value of x: " << x << std::endl;

    return 0;
}
```
Если вы используете `using namespace std;`, как в примере выше, то это означает, что вы импортируете все имена из пространства имен std, и вам не нужно писать `std::` перед каждым именем. Однако, использование `using namespace std;` может привести к конфликтам имен в больших программах, поэтому некоторые программисты предпочитают избегать этой директивы и явно указывать префикс `std::` перед каждым объектом из стандартной библиотеки.

# Типы данных
Отрицательные числа в двоичной системе представляются с использованием дополнительного кода. Дополнительный код создается путем инвертирования всех битов числа и добавления единицы к полученному результату. Рассмотрим процесс создания дополнительного кода на примере 8-битного двоичного числа.

Инвертирование битов (получение обратного кода):

Пусть у нас есть число 5 в двоичной системе: 00000101.
Инвертирование всех битов дает обратный код: 11111010.
Добавление единицы:

Прибавление 1 к обратному коду: 11111010 + 1 = 11111011.
Таким образом, число -5 в двоичной системе с использованием 8-битного дополнительного кода представлено как 11111011.

# Операторы объявления и переменные, оператор присваивания
Программа на C++ - это совокупность функций, а функция - совокупность операторов.
```C++
int main() {
    int number; // оператор объявления
    number = 5; // оператор присваивания
    std::cout << "This is ";
    std::cout << number; // отображение значения переменной
}
```
оператор объявления выделяет в памяти место для хранения информации типа int. Вся работа по выделению области памяти и присвоению ей идентификатора выполняется компилятором. С момента объявления значение будет идентифицироваться с заданным ему именем. Все переменные в C++ требуют объявления.
Оператор присваивания присваивает значение выбранной области памяти. `=` - это операция присваивания.
Особенность: операцию присваивания можно использовать последовательно.
```C++
int first;
int second;
int third;
third = second = first = 100;
```
Присвоение происходит в направлении справа налево, сначала будет инициализирована переменная first, затем second, затем third.

## Еще одно назначение cout
в примере выше `std::cout << number` выводит не слово number, а значение переменной number. Таким образом, объект `cout` используется как со строками, так и с числами.
Кроме того, возможно объединение нескольких операторов cout, cin.
```C++
cout << "Эта строка содержит ";
cout << " число ";
cout << number;
```
можно заменить
```C++
cout << "Эта строка содержит "
     << " число "
     << number;
```
Точно так же с `cin`:
```C++
int first, second, third;
cin >> first;
cin >> second;
cin >> third;
```
можно заменить
```C++
int first, second, third;
cin >> first >> second >> third;
```
# Функции
В C++ имеются две разновидности функций: с возвращаемыми значениями и без них.
### Определение функции:
```C++
// Пример определения функции
int add(int a, int b) {
    return a + b;
}
```
`int`: Тип возвращаемого значения функции. В данном случае, функция `add` возвращает целочисленное значение.

`add`: Имя функции.

`(int a, int b)`: Список параметров, которые принимает функция. В данном случае, функция принимает два целочисленных параметра `a` и `b`.

`return a + b;` Возвращаемое значение функции. Функция возвращает сумму `a` и `b`.
### Вызов функции:
```C++
// Пример вызова функции
int result = add(3, 4);
```
Функцию `add` можно вызвать с аргументами 3 и 4.

Результат выполнения функции будет присвоен переменной `result`.
### Прототип функции:
```C++
// Прототип функции
int add(int a, int b);
```
Прототип предварительно объявляет функцию, указывая её тип возвращаемого значения, имя и параметры. Это позволяет компилятору понять, как использовать функцию до её полного определения.
### Аргументы по умолчанию:
```C++
// Пример функции с аргументами по умолчанию
int multiply(int a, int b = 2) {
    return a * b;
}
```
Параметр `b` имеет значение по умолчанию (2). Если при вызове функции не указано значение для b, будет использовано значение по умолчанию.
### Перегрузка функций:
```C++
// Пример перегрузки функций
int sum(int a, int b) {
    return a + b;
}

double sum(double a, double b) {
    return a + b;
}
```
В C++ можно определить несколько функций с одним именем, но с разными типами параметров (перегрузка функций).
### Рекурсия:
```C++
// Пример рекурсивной функции
int factorial(int n) {
    if (n <= 1) {
        return 1;
    } else {
        return n * factorial(n - 1);
    }
}
```
Рекурсивная функция вызывает саму себя. В данном случае, функция вычисляет факториал числа n.
### Встроенные функции:
C++ также предоставляет ряд встроенных функций, таких как множество стандартных библиотечных функций для работы со строками, массивами и другими структурами данных.

Важно отметить, что эти основы являются только начальной точкой, и существует много других аспектов функций в C++.

# Операторы if/else
Операторы `if` и `else` позволяют вам написать условные конструкции в вашем коде, что позволяет программе принимать решения на основе различных условий.

Оператор `if`:
Оператор if используется для выполнения блока кода только в том случае, если определенное условие истинно (true). Синтаксис оператора if следующий:

```C++
if (условие) {
    // Код, который выполнится, если условие истинно
}
```

```C++
#include <iostream>

int main() {
    int x = 10;

    if (x > 5) {
        std::cout << "x больше 5." << std::endl;
    }

    return 0;
}
```
В этом примере, если переменная x больше 5, будет выведено сообщение "x больше 5".

Оператор `else`:
Оператор else используется в сочетании с if и выполняется, когда условие if ложно (false). Синтаксис оператора else:

```C++
if (условие) {
    // Код, который выполнится, если условие истинно
} else {
    // Код, который выполнится, если условие ложно
}
```
Пример:
```C++
#include <iostream>

int main() {
    int x = 3;

    if (x > 5) {
        std::cout << "x больше 5." << std::endl;
    } else {
        std::cout << "x не больше 5." << std::endl;
    }

    return 0;
}
```
В этом примере, если переменная x не больше 5, будет выведено сообщение "x не больше 5".

Операторы `else if`:
Оператор else if позволяет проверить дополнительные условия, если предыдущие условия были ложными. Вы можете использовать несколько else if после if. Пример:

```C++
#include <iostream>

int main() {
    int x = 5;

    if (x > 5) {
        std::cout << "x больше 5." << std::endl;
    } else if (x < 5) {
        std::cout << "x меньше 5." << std::endl;
    } else {
        std::cout << "x равен 5." << std::endl;
    }

    return 0;
}
```
Этот код сначала проверяет, больше ли x 5, затем меньше ли 5, и, наконец, если оба условия ложны, выводится, что x равен 5.

Еще один пример:
```C++
#include <iostream>

int main() {
    setlocale(LC_ALL, "Russian");
    int score;
    std::cout << "Введите балл студента: ";
    std::cin >> score;

    if (score <= 100 && score >= 90) {
        std::cout << "Оценка: отлично" << std::endl;
    } else if (score < 90 && score >= 70) {
        std::cout << "Оценка: хорошо" << std::endl;
    }
    else if (score < 70 && score >= 60) {
        std::cout << "Оценка: удовлетвворительно" << std::endl;
    }
    else if (score == 0) {
        std::cout << "Крайне неудовлетворительно" << std::endl;
    }
    else {
        std::cout << "Оценка: неудовлетворительно" << std::endl;
    }

    return 0;
}
```
