#include <iostream>

using namespace std;

// Здесь должна быть определена функция f(x), например:
// float f(float x) { return x * x; }

int main() // главная функция
{
    float a, b, h, x;
    cout << "a = ";
    cin >> a;
    cout << "b = ";
    cin >> b;
    cout << "h = ";
    cin >> h;
    cout << "x\tf(x)\n"; // выводим заголовок таблицы

    // перебираем все числа из отрезка [a, b] с шагом h
    for (x = a; x <= b; x += h)
        // выводим на экран значение x и значение функции в точке x
        cout << x << "\t" << f(x) << endl;

    return 0;
}
