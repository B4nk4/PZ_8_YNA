# PZ_8_YNA


## Задание 1
```
#include <iostream>

using namespace std;

int main() {
    // Настройка корректного отображения русского языка в консоли
    setlocale(LC_ALL, "Russian");

    int number; // Объявляем переменную для хранения числа
    cin >> number; // Считываем число с клавиатуры

    // Ваш код:
    if (number > 0)
    {
        cout << "Положительное";
    }


    return 0;
}
```


## Задание 2
```
#include <iostream>

using namespace std;
int main() {
    int number; // Объявляем переменную для хранения числа
    cin >> number; // Считываем число с клавиатуры

    // Ваш код:
    if (number == 10)
    {
        cout << "Число равно 10";
    }
    else 
        cout << "Число не равно 10";


    return 0; // Завершаем программу
}
```


## Задание 3
```
#include <iostream>

using namespace std;
int main() {
    int number;
    cin >> number;

    // Ваш код
    if (number >= 0)
        cout << "Число не отрицательное";
    else
        cout << "Число отрицательное";



    return 0;
}
```



## Задание 4
```
#include <iostream>

using namespace std;

int main() {
    int a, b; // Объявляем две переменные
    cin >> a >> b; // Считываем два числа сразу
    if (a > b)
    
        cout << "Большее число: " << a; 
    
    else if (b > a)
    
        cout << "Большее число: " << b;
    
    else
        cout << "Числа равны";
    // Ваш код:



    return 0;
}
```



## Задание 5
```
#include <iostream>

using namespace std;

int main() {
    int number;
    cin >> number;

    // Ваш код:
    if (1 <= number && number <= 10)
        cout << "Число принадлежит диапазону";
    else
        cout << "Число не принадлежит диапазону";


    return 0;
}
```


## Задание 6
```
#include <iostream>

using namespace std;

int main() {
    int number;
    cin >> number;

    // Ваш код:
    if (1 <= number && number <= 5)
        cout << "Число принадлежит одному из диапазонов";
    else if (10 <= number && number <= 15)
        cout << "Число принадлежит одному из диапазонов";
    else
        cout << "Число не принадлежит указанным диапазонам";


    return 0;
}
```


## Задание 7
```
#include <iostream>

using namespace std;

int main() {
    int number;
    cin >> number;

    // Ваш код:
    if (number < 100 && number % 2 == 0 && number >=0)
        cout <<"Подходит";

    return 0;
}
```



