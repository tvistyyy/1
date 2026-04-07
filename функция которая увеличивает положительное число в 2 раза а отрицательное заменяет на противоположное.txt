/*Написать функцию, которая увелич ивает положительное число в 2 раза а отрицательное заменяет на противоп оложное*/

#include <bits/stdc++.h>

#include <iostream>

#include <cmath>

using namespace std;

void f(float&x)

{

x = (x>= 0)? x*2: x;
}

{

int main()

float a;

cout <<"Введите а: " << endl;

cin >> a;

f(a);

cout << "a =" << a;

return 0;

}