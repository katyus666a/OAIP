# ОАИП 4-ая и 5-ая лабораторная работа.

LAB.5.P1 - код 1-го задания 5-ой лабораторной работы.
LAB.5.P2 - код 2-го задания 5-ой лабораторной работы.
LAB.4 - 4-ой лабораторной работы.

Условия 4-ой лабораторной работы:
Написать программу формирования ОПЗ и расчета полученного
выражения. Разработать удобный интерфейс ввода исходных данных и вывода
результатов. Язык программирования С++. Работу программы проверить на
конкретном примере (табл. 1). (ВАРИАНТ 9)

Условия 5-ой лабораторной работы:
А. Ввести массив из п целых чисел из заданного диапазона. Создать хеш-
таблицу из М элементов. Осуществить поиск элемента в хеш-таблице. Вы-
вести на экран исходный массив, хеш-таблицу и результат поиска. Задание выбрать в соответствии с номером варианта в табл. 1. (ВАРИАНТ 9)

В. Объявить и ввести массив структур из п элементов. Создать хеш-
таблицу из М элементов. Осуществить поиск элемента по ключу в хеш-
таблице. Вывести на экран исходный массив, хеш-таблицу и все поля найденной структуры. Задание выбрать в соответствии с номером
варианта в табл. 2. (ВАРИАНТ 9)

Алгоритм шагов для LAB.5.P1:
1. Включение необходимых заголовочных файлов:   - iostream для ввода/вывода данных.
   - list для использования стандартного контейнера list.   
2. Определение константы TABLE_SIZE, которая определяет размер хеш-таблицы.
3. Определение хеш-функции hashFunction, которая принимает ключ и возвращает индекс в хеш-таблице.
4. Определение функции insert, которая принимает хеш-таблицу и ключ, и вставляет ключ в соответствующий список в хеш-таблице.
5. Определение функции search, которая принимает хеш-таблицу и ключ, и выполняет поиск ключа в списке, соответствующему его хешу в хеш-таблице.
6. В функции main:
   - Установка локали для вывода сообщений на русском языке с помощью setlocale.   - Создание массива arr размером 8 элементов.
   - Создание хеш-таблицы table с помощью списка размером TABLE_SIZE.   
7. Заполнение массива arr случайными числами из заданного диапазона с помощью цикла for и функции rand.   
8. Заполнение хеш-таблицы table с помощью цикла for и функции insert.
9. Вывод исходного массива arr с помощью цикла for и объекта cout.
10. Вывод хеш-таблицы table с помощью вложенных циклов for, объекта cout и итератора it.
11. Ввод элемента key для поиска с помощью объекта cin.
12. Вызов функции search для поиска элемента key в хеш-таблице table.
13. Вывод соответствующего сообщения о результате поиска с помощью объекта cout.
14. Возврат 0 из функции main, обозначающий успешное выполнение программы.
Демонстрация кода:
https://1drv.ms/v/s!AgLRl5i9yERW3SZjX2qC3P9wGrpy?e=QfVQzF

Алгоритм шагов для LAB.5.P2:
1. Включение необходимых заголовочных файлов:   - iostream для ввода/вывода данных.
   - list для использования стандартного контейнера list.   - string для использования строковых объектов.
2. Определение константы TABLE_SIZE, которая определяет размер хеш-таблицы.
3. Определение структуры Surname, содержащей поля name (фамилия), place (место) и score (очки).
4. Определение хеш-функции hashFunction, которая принимает место и возвращает индекс в хеш-таблице.
5. В функции main:
   - Создание массива name размером 5 элементов типа Surname и заполнение его данными.   - Создание хеш-таблицы hashTable с помощью списка размером TABLE_SIZE.
6. Заполнение хеш-таблицы hashTable с помощью цикла for и функции push_back.
7. Вывод исходного массива name с помощью цикла for и объекта cout.
8. Вывод хеш-таблицы hashTable с помощью вложенных циклов for, объекта cout и итератора it.
9. Ввод значения score для поиска с помощью объекта cin.
10. Вычисление хеша для значения score с помощью функции hashFunction.
11. Создание флага found для отслеживания нахождения искомого элемента.
12. Поиск элемента с заданным score в списке, соответствующем хешу, с помощью цикла for и итератора it.
13. Если элемент найден, вывод информации о найденном элементе с помощью объекта cout. Иначе, вывод сообщения о том, что фамилия не найдена.
14. Возврат 0 из функции main, обозначающий успешное выполнение программы.
Демонстрация кода:
https://1drv.ms/v/s!AgLRl5i9yERW3Sghf0qAwdEvAvDp?e=9HcJ7R
