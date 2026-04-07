/* Вычислить Z = (V1 + V2 + V3)/3 , где V  объемы шаров с радиусом r1,r2 и r3 соответственно.
Обьем шара вычислить по формуле V=4/3 * π * r3*/
#include <bits/stdc++.h>

#include <cmath>

using namespace std;

float volume (int r)

return 4.0/3*3.14*pow(r,3);

3

4G+

81

int main()

float r1, r2, r3,z;

cout <<"Введите г1, r2, r3";

cin >> r1 >> r2 >> r3;

z = (volume (r1)+ volume (r2)+ volume(r3 ))/3;

cout << "2 =" << z;

return 0;

3
