# Отчет по практической работе №1

## Задание

Задания на первую практическую работу представлены в таблице 1.

Таблица 1 - Задания
| Номер | Задание |
| ------------- | ------------- |
|  1  | Написать программу, печатающую в stdout фразу "Hello, World!" на отдельной строке.  |
| 2  | Написать программу, принимающую на вход два числа, разделённые пробелом, и суммирующую их. Ввод чисел производить из stdin, вывод результата - в stdout. Вводимые числа не превосходят по модулю 2147483647.  |
| 3 | Написать программу, принимающую на вход числа x и y, разделённые пробелом, и вычисляющую x в степени y. Ввод чисел производить из stdin, вывод результата - в stdout. Вводимые числа не превосходят по модулю 2147483647. Реализовывать возведение в степень через цикл/рекурсию не допускается. |

## Ход работы
Листинг первой программы: 
```C
#include <stdio.h>
int main() 
{
    printf("Hello, World!\n");
    return 0;
}
```
На рисунке 1 представлен результат работы программы.

<p align="center">

  <img width="400" height="150" src="https://sun9-3.userapi.com/impg/HoZTerTgtxzHgJvhB0hkGSWP85fFEUE9kiz8wQ/nHhqWvcBvQ4.jpg?size=389x154&quality=96&sign=eb51e12d56b4e4a6ad489587dec9b748&type=album">

</p>
Рисунок 1 - Результат работы первой программы

Листинг кода второй программы:
```C
#include <stdio.h>

int main() {
    double a, b, c;
    (void)scanf( "%lf %lf", &a, &b);
    c = a + b;
    printf("%lf\n", c);
    return 0;
}

```
На рисунке 2 представлен результат работы программы.

<p align="center">

  <img width="400" height="200" src="https://sun9-29.userapi.com/impg/W8EAXJUsx-ynJgIVJDsS5XQhqtqDl5yfPAavWg/c2qTi4xWCw8.jpg?size=397x170&quality=96&sign=3aafde99426dac89bb134b2aed365928&type=album">

</p>
Рисунок 2 - Результат работы второй программы

Листинг кода третьей программы:
```C
#include <stdio.h>
#include <math.h>

int main() {
    double a, b;
    (void)scanf("%lf %lf", &a, &b);
    printf("%lf\n", pow(a, b));
    return 0;
}

```
На рисунке 3 представлен результат работы программы.
<p align="center">

  <img width="400" height="200" src="https://sun9-23.userapi.com/impg/88pILV8g87LBAfo4Sk9JfHhbTJd9TUeVHzLnsQ/6CbpcJM0VWM.jpg?size=388x179&quality=96&sign=31829e7981cf8ae0f2879dad45ce9481&type=album">

</p>

Рисунок 3 - Результат работы третьей программы

Все программы работают корректно, значит код написан верно.

## Работа с gitlab
После загрузки все программы должны пройти pipeline проверку, она прошла успешно. Результаты проверки можно увидеть на рисунке 4.
<p align="center">

  <img width="200" height="400" src="https://sun9-27.userapi.com/impg/GHO2vEUouX070R-TKkMvGe2dBnz-FaF7lYpX8g/MYds6ne9RuI.jpg?size=328x609&quality=96&sign=372e61ed2cf13ea751e8e390131308c8&type=album">

</p>
Рисунок 4 - Результаты pipeline проверки

## Результат
В ходе выполнения практической работы были получены навыки работы с основной языка С, были написаны три программы, которые были проверены тестированием. Оно показало корректность их работы.
