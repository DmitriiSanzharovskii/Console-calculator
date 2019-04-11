# Консольный калькулятор
Данный калькулятор позволяет выполнить некоторые простые арифметические вычисления:
1. Сложение 
2. Вычитание
3. Умножение
4. Деление
5. Возведение числа в степень
6. Нахождение процента от числа
## Порядок начала работы после запуска программы:
1. Пользователь вводит первое число
2. Ввод арифметического знака
3. Ввод второго числа
4. Для вывода результата нажать клавишу ENTER
### Описание кода:
Подключение библиотек:
```cpp 
#include"pch.h"
#include<iostream>
```
Подключение пространства имен:
```cpp
using namespace std
```
Объявление переменных:
```cpp 
double calculate[4];            // массив 
char symbhol;
```
Чтобы программа не закрывалась после первого вычисления, используется цикл:
```cpp
while (cin >> calculate[0] >> symbhol >> calculate[1]) 
```
Программа реализована с помощью оператора множественного выбора:
```cpp
switch (symbhol)
			{                            
			case '+':
				calculate[3] = calculate[0] + calculate[1];

				cout << calculate[0] << " + " << calculate[1] << " = " << calculate[3] << endl; break; // Результат сложения (сумма)
 ```       
        
        
        
        
        
