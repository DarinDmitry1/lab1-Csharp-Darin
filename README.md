# lab1-C#-Darin
Лабораторная работа №1.
2 курс ИТ-15 Дарьин Дмитрий
Каждая задача оформлена в виде отдельного метода в классе Tasks
1. Дробная часть числа
Программа вычисляет дробную часть вещественного числа.
Используется приведение к целому типу и вычитание.
Проверяется корректность ввода данных.
<img width="180" height="39" alt="image" src="https://github.com/user-attachments/assets/8471e803-0f1b-45f4-aa59-a22614b52931" />
<img width="232" height="46" alt="image" src="https://github.com/user-attachments/assets/cc3b66a5-aa0c-435c-89aa-9d762a3fa3bd" />

2. Код символа (ASCII)
Определяется числовой код введённого символа.
Используется неявное приведение типа char к int.
Реализована проверка пустого ввода.
<img width="166" height="44" alt="image" src="https://github.com/user-attachments/assets/b174482c-6e71-4725-8a49-be8944de35e1" />
<img width="180" height="46" alt="image" src="https://github.com/user-attachments/assets/06fd3d52-1c4e-40c4-a121-fe7efa6b7245" />

3. Проверка двузначного числа
Программа определяет, является ли число двузначным.
Учитываются как положительные, так и отрицательные числа.
Результат выводится в текстовом виде.
<img width="196" height="34" alt="image" src="https://github.com/user-attachments/assets/372cede1-4667-403f-9368-0fef6bb9d0c2" />
<img width="175" height="44" alt="image" src="https://github.com/user-attachments/assets/c3925f52-b2f5-4ecf-ad8e-e270bb54238f" />

4. Проверка попадания в диапазон
Проверяется, входит ли число в диапазон [a, b].
Границы диапазона могут вводиться в любом порядке.
Используются функции Min и Max.
<img width="485" height="42" alt="image" src="https://github.com/user-attachments/assets/780efda0-9c25-464b-b49b-33f5c2f746e4" />
<img width="485" height="40" alt="image" src="https://github.com/user-attachments/assets/da0776bf-3de7-4dfe-b71e-37c97e612aa9" />

5. Равенство трёх чисел
Определяется, равны ли между собой три введённых числа.
Используется логическое сравнение значений.
Выводится результат проверки.
<img width="290" height="46" alt="image" src="https://github.com/user-attachments/assets/a5d2eddc-9e91-4cd2-8660-4c1deb085edd" />
<img width="299" height="34" alt="image" src="https://github.com/user-attachments/assets/bababcc1-3747-4420-bae0-91641b2f7483" />

6. Модуль числа
Программа находит модуль целого числа.
Реализовано без использования стандартной функции Math.Abs.
Применяется тернарный оператор.
<img width="170" height="44" alt="image" src="https://github.com/user-attachments/assets/423b13d2-265b-4f17-9dbd-8293ce72cb04" />
<img width="163" height="38" alt="image" src="https://github.com/user-attachments/assets/1bb8f2ff-07fb-4b92-a5b1-1c5b971a06ec" />

7. Делимость на 3 или 5
Проверяется, делится ли число на 3 или 5, но не на оба сразу.
Используется логическая операция XOR.
Результат выводится пользователю.
<img width="214" height="41" alt="image" src="https://github.com/user-attachments/assets/d62deb70-3640-4cab-aebf-f6f33de26c7d" />
<img width="369" height="46" alt="image" src="https://github.com/user-attachments/assets/692ae685-7535-4a0a-863a-e8d6c1a93ca3" />

8. Максимум из трёх чисел
Находится наибольшее из трёх целых чисел.
Используется пошаговое сравнение значений.
Возвращается максимальный элемент.
<img width="309" height="43" alt="image" src="https://github.com/user-attachments/assets/5e1e18f1-d14d-401c-8adf-e3686073ee15" />
<img width="304" height="31" alt="image" src="https://github.com/user-attachments/assets/773d9dff-df94-4df1-8064-b1122263ef22" />

9. Сумма с условием
Вычисляется сумма двух чисел.
Если сумма находится в диапазоне от 10 до 19, возвращается 20.
Реализована проверка диапазона.
<img width="254" height="38" alt="image" src="https://github.com/user-attachments/assets/9b7eba5d-3a1b-456b-ad85-5587c542733a" />
<img width="309" height="40" alt="image" src="https://github.com/user-attachments/assets/411c4cf0-23e2-4e36-9b21-811eea48ba3c" />

10. День недели по номеру
По номеру от 1 до 7 определяется день недели.
Используется оператор switch.
Обрабатываются некорректные значения.
<img width="242" height="35" alt="image" src="https://github.com/user-attachments/assets/670041e9-532a-4feb-8d77-87f360520a40" />
<img width="262" height="45" alt="image" src="https://github.com/user-attachments/assets/9f4d50dd-24c1-4414-91ec-79bec2e089b6" />

11. Список чисел от 0 до x
Формируется строка из чисел от 0 до x.
Используется цикл for.
Результат возвращается в виде строки.
<img width="162" height="40" alt="image" src="https://github.com/user-attachments/assets/0c7bdb2c-4fe1-4e1d-9a08-f1fc15d904da" />
<img width="172" height="44" alt="image" src="https://github.com/user-attachments/assets/6bd9c7c8-5654-4d07-81e1-bfe3c36090eb" />

12. Чётные числа от 0 до x
Выводятся все чётные числа в заданном диапазоне.
Счётчик увеличивается на 2.
Результат представлен строкой.
<img width="158" height="40" alt="image" src="https://github.com/user-attachments/assets/e93e7040-1175-4598-8c97-125052d44fce" />
<img width="1034" height="594" alt="image" src="https://github.com/user-attachments/assets/a5dcb215-3dca-496b-8d46-d4a52c9cc0a4" />

13. Количество цифр в числе
Определяется длина числа в цифрах.
Число преобразуется в строку.
Возвращается количество символов.
<img width="196" height="42" alt="image" src="https://github.com/user-attachments/assets/6ca85bb1-4cac-4f3c-9781-a0a00359e71f" />
<img width="292" height="37" alt="image" src="https://github.com/user-attachments/assets/c53d7523-d4bb-4e9e-a66b-d374fb468b73" />

14. Квадрат из звёздочек
Рисуется квадрат заданного размера.
Используются вложенные циклы.
Вывод осуществляется в консоль.
<img width="243" height="138" alt="image" src="https://github.com/user-attachments/assets/1a9f1fe5-28cb-42f0-8022-62292e6980ee" />
большие значения лучше не вводить)

15. Прямоугольный треугольник
Строится треугольник, выровненный по правому краю.
Используются строки из пробелов и символов *.
Высота задаётся пользователем.
<img width="282" height="138" alt="image" src="https://github.com/user-attachments/assets/a7130897-0eb2-4ce0-8468-bc4e120e419b" />
и тут тоже

16. Первое вхождение элемента
В массиве ищется первое вхождение заданного числа.
Возвращается индекс элемента или -1.
Используется линейный поиск.
<img width="480" height="63" alt="image" src="https://github.com/user-attachments/assets/b508ce88-6eb5-4ad7-a0f4-0f3c8e5034d0" />


17. Максимум по модулю
Находится элемент массива с наибольшим модулем.
Сравнение выполняется с помощью Math.Abs.
Обрабатывается непустой массив.
<img width="378" height="36" alt="image" src="https://github.com/user-attachments/assets/eb70a6db-f237-414b-b16b-83775a66cd78" />

18. Вставка массива
Один массив вставляется в другой по заданной позиции.
Корректируются выходящие за границы индексы.
Формируется новый массив.
<img width="369" height="81" alt="image" src="https://github.com/user-attachments/assets/b98f71f4-6904-4c56-8185-097777ff6d9d" />

19. Реверс массива
Создаётся массив, записанный в обратном порядке.
Используется обращение индексов.
Исходный массив не изменяется.
<img width="312" height="44" alt="image" src="https://github.com/user-attachments/assets/e1f85e32-e952-4f1a-ac06-583119eb17a7" />

20. Все вхождения элемента
Находятся индексы всех вхождений числа в массиве.
Используется список для накопления результатов.
Результат возвращается в виде массива.
<img width="255" height="53" alt="image" src="https://github.com/user-attachments/assets/16554cbc-746a-4cb8-90f5-e4c80c997771" />




