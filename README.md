# -1400
Коды для решения задач из сборника
// ConsoleApplication6.cpp : Этот файл содержит функцию "main". Здесь начинается и заканчивается выполнение программы.
//

#include <iostream>
#include <cmath>
#include <string>
#include <iomanip>
using namespace std;

int main() {
    // Задания 1.1 - 1.13
    cout << "=== Задания 1.1 - 1.13 ===" << endl;

    // 1.1
    cout << "1.1: " << 31 << " " << 18 << " " << 79 << endl;

    // 1.2
    cout << "1.2: " << 47 << "  " << 52 << "  " << 150 << endl;

    // 1.3
    cout << "1.3: " << endl << 50 << endl << 10 << endl;

    // 1.4
    cout << "1.4: " << endl << 5 << endl << 10 << endl << 21 << endl;

    // 1.5
    cout << "1.5: " << endl << 1 << endl << 2 << endl;

    // 1.6
    double pi = 3.1415926;
    cout << "1.6: " << fixed << setprecision(3) << pi << endl;

    // 1.7
    double e = 2.71828;
    cout << "1.7: " << fixed << setprecision(1) << e << endl;

    // 1.8
    int num1;
    cout << "1.8: Введите число: ";
    cin >> num1;
    cout << "Вы ввели число " << num1 << endl;

    // 1.9
    int num2;
    cout << "1.9: Введите число: ";
    cin >> num2;
    cout << num2 << " - вот какое число Вы ввели" << endl;

    // 1.10
    string name1;
    cout << "1.10: Введите имя: ";
    cin >> name1;
    cout << name1 << endl;

    // 1.11
    string team;
    cout << "1.11: Введите название команды: ";
    cin >> team;
    cout << team << " - это чемпион!" << endl;

    // 1.12
    string name2;
    cout << "1.12: Введите имя: ";
    cin >> name2;
    cout << "Привет, " << name2 << "!" << endl;

    // 1.13
    int num3;
    cout << "1.13: Введите число: ";
    cin >> num3;
    cout << num3 - 1 << " " << num3 + 1 << endl;

    // Задания 1.14 - 1.17
    cout << "\n=== Задания 1.14 - 1.17 ===" << endl;

    // 1.14
    int a1, b1, c1;
    cout << "1.14: Введите три числа: ";
    cin >> a1 >> b1 >> c1;
    cout << a1 << "  " << b1 << "  " << c1 << endl;

    // 1.15
    int a2, b2, c2, d2;
    cout << "1.15: Введите четыре числа: ";
    cin >> a2 >> b2 >> c2 >> d2;
    cout << a2 << " " << b2 << " " << c2 << " " << d2 << endl;

    // 1.16
    int t, v, x, y;
    cout << "1.16: Введите t, v, x, y: ";
    cin >> t >> v >> x >> y;
    cout << "а) 5 10" << endl;
    cout << "б) 100 " << t << endl;
    cout << "в) " << x << " 25" << endl;
    cout << "7 см" << endl;
    cout << "1949 " << v << " " << x << " " << y << endl;

    // 1.17
    int a3, b3, x3, y3;
    cout << "1.17: Введите a, b, x, y: ";
    cin >> a3 >> b3 >> x3 >> y3;
    cout << "а) 2 кг" << endl;
    cout << "б) " << a3 << " 1" << endl;
    cout << "в) " << x3 << " " << y3 << endl;
    cout << "13 17" << endl;
    cout << "19 " << b3 << endl;
    cout << "5 " << y3 << endl;

    // Задания 2.1 - 2.12
    cout << "\n=== Задания 2.1 - 2.12 ===" << endl;

    // 2.1а
    double x1;
    cout << "2.1а: Введите x: ";
    cin >> x1;
    cout << "y = " << 17 * x1 * x1 - 6 * x1 + 13 << endl;

    // 2.1б
    double a4;
    cout << "2.1б: Введите a: ";
    cin >> a4;
    cout << "y = " << 3 * a4 * a4 + 5 * a4 - 21 << endl;

    // 2.2
    double a5;
    cout << "2.2: Введите a: ";
    cin >> a5;
    cout << "y = " << (a5 * a5 + 10) / sqrt(a5 * a5 + 1) << endl;

    // 2.3а
    double a6;
    cout << "2.3а: Введите a: ";
    cin >> a6;
    cout << "y = " << sqrt(2 * a6 + sin(abs(3 * a6)) / 3.56) << endl;

    // 2.3б
    double x2;
    cout << "2.3б: Введите x: ";
    cin >> x2;
    cout << "y = " << sin(x2 * x2) / (1 + cos(x2)) << endl;

    // 2.4
    double side;
    cout << "2.4: Введите сторону квадрата: ";
    cin >> side;
    cout << "Периметр: " << 4 * side << endl;

    // 2.5
    double radius1;
    cout << "2.5: Введите радиус: ";
    cin >> radius1;
    cout << "Диаметр: " << 2 * radius1 << endl;

    // 2.6
    const double R = 6350.0;
    double height;
    cout << "2.6: Введите высоту: ";
    cin >> height;
    cout << "Расстояние до горизонта: " << sqrt(2 * R * height + height * height) << " км" << endl;

    // 2.7
    double edge;
    cout << "2.7: Введите длину ребра куба: ";
    cin >> edge;
    cout << "Объем: " << edge * edge * edge << endl;
    cout << "Площадь боковой поверхности: " << 4 * edge * edge << endl;

    // 2.8
    double radius2;
    cout << "2.8: Введите радиус: ";
    cin >> radius2;
    cout << "Длина окружности: " << 2 * M_PI * radius2 << endl;
    cout << "Площадь круга: " << M_PI * radius2 * radius2 << endl;

    // 2.9а
    double x3, y4;
    cout << "2.9а: Введите x и y: ";
    cin >> x3 >> y4;
    cout << "z = " << 2 * x3 * x3 * x3 - 3.44 * x3 * y4 + 2.3 * x3 * x3 - 7.1 * y4 + 2 << endl;

    // 2.9б
    double a7, b4;
    cout << "2.9б: Введите a и b: ";
    cin >> a7 >> b4;
    cout << "x = " << 3.14 * (a7 + b4) * (a7 + b4) * (a7 + b4) + 2.75 * b4 * b4 - 12.7 * a7 - 4.1 << endl;

    // 2.10
    int num4, num5;
    cout << "2.10: Введите два числа: ";
    cin >> num4 >> num5;
    cout << "Среднее арифметическое: " << (num4 + num5) / 2.0 << endl;
    cout << "Среднее геометрическое: " << sqrt(num4 * num5) << endl;

    // 2.11
    double volume, mass;
    cout << "2.11: Введите объем и массу: ";
    cin >> volume >> mass;
    cout << "Плотность: " << mass / volume << endl;

    // 2.12
    double population, area;
    cout << "2.12: Введите население и площадь: ";
    cin >> population >> area;
    cout << "Плотность населения: " << population / area << " чел/км²" << endl;

    // Задания 2.13 - 2.22
    cout << "\n=== Задания 2.13 - 2.22 ===" << endl;

    // 2.13
    double a8, b5;
    cout << "2.13: Введите a и b (a ≠ 0): ";
    cin >> a8 >> b5;
    cout << "x = " << -b5 / a8 << endl;

    // 2.14
    double katet1, katet2;
    cout << "2.14: Введите катеты: ";
    cin >> katet1 >> katet2;
    cout << "Гипотенуза: " << sqrt(katet1 * katet1 + katet2 * katet2) << endl;

    // 2.15
    double R1, r1;
    cout << "2.15: Введите внешний и внутренний радиусы: ";
    cin >> R1 >> r1;
    cout << "Площадь кольца: " << M_PI * (R1 * R1 - r1 * r1) << endl;

    // 2.16
    double katet3, katet4;
    cout << "2.16: Введите катеты: ";
    cin >> katet3 >> katet4;
    double gipotenuza = sqrt(katet3 * katet3 + katet4 * katet4);
    cout << "Периметр: " << katet3 + katet4 + gipotenuza << endl;

    // 2.17
    double osn1, osn2, height2;
    cout << "2.17: Введите основания и высоту: ";
    cin >> osn1 >> osn2 >> height2;
    double bokovaya = sqrt(height2 * height2 + ((osn2 - osn1) / 2) * ((osn2 - osn1) / 2));
    cout << "Периметр трапеции: " << osn1 + osn2 + 2 * bokovaya << endl;

    // 2.18
    double x4, y5;
    cout << "2.18: Введите x и y: ";
    cin >> x4 >> y5;
    double z = (x4 + (2 + y5) / (x4 * x4)) / (y5 + 1 / sqrt(x4 * x4 + 10));
    double q = 7.25 * sin(x4) - abs(y5);
    cout << "z = " << z << ", q = " << q << endl;

    // 2.19
    double a9, b6;
    cout << "2.19: Введите a и b: ";
    cin >> a9 >> b6;
    double x5 = (2 / (a9 * a9 + 25) + b6) / sqrt(b6 + (a9 + b6) / 2);
    double y6 = (abs(a9) + 2 * sin(b6)) / (5.5 * a9);
    cout << "x = " << x5 << ", y = " << y6 << endl;

    // 2.20
    double e1, f, g, h;
    cout << "2.20: Введите e, f, g, h: ";
    cin >> e1 >> f >> g >> h;
    double a10 = pow(sqrt(e1 - 3 / f), 3) + g;
    double b7 = sin(e1) + pow(cos(h), 2);
    double c3 = (33 * g) / (e1 * f - 3);
    cout << "a = " << a10 << ", b = " << b7 << ", c = " << c3 << endl;

    // 2.21
    double e2, f1, g1, h1;
    cout << "2.21: Введите e, f, g, h: ";
    cin >> e2 >> f1 >> g1 >> h1;
    double a11 = (e2 + f1 / 2) / 3;
    double b8 = abs(h1 * h1 - g1);
    double c4 = sqrt(pow(g1 - h1, 2) - 3 * sin(e2));
    cout << "a = " << a11 << ", b = " << b8 << ", c = " << c4 << endl;

    // 2.22
    double x6, y7;
    cout << "2.22: Введите два числа: ";
    cin >> x6 >> y7;
    cout << "Среднее арифметическое модулей: " << (abs(x6) + abs(y7)) / 2 << endl;
    cout << "Среднее геометрическое модулей: " << sqrt(abs(x6) * abs(y7)) << endl;

    return 0;
}#include <iostream>
#include <cmath>
#include <vector>
using namespace std;

// 2.23 Периметр и диагональ прямоугольника
void rectangle() {
    double a, b;
    cout << "Введите стороны прямоугольника: ";
    cin >> a >> b;
    cout << "Периметр: " << 2 * (a + b) << "\nДиагональ: " << sqrt(a * a + b * b) << endl;
}

// 2.24 Арифметические операции
void arithmetic() {
    double x, y;
    cout << "Введите два числа: ";
    cin >> x >> y;
    cout << "Сумма: " << x + y << "\nРазность: " << x - y
        << "\nПроизведение: " << x * y << "\nЧастное: " << x / y << endl;
}

// 2.25 Параллелепипед
void parallelepiped() {
    double a, b, c;
    cout << "Введите длины сторон параллелепипеда: ";
    cin >> a >> b >> c;
    cout << "Объем: " << a * b * c
        << "\nПлощадь боковой поверхности: " << 2 * (a * c + b * c) << endl;
}

// 2.26 Расстояние между точками
void distancePoints() {
    double x1, y1, x2, y2;
    cout << "Введите координаты двух точек (x1 y1 x2 y2): ";
    cin >> x1 >> y1 >> x2 >> y2;
    cout << "Расстояние: " << sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2)) << endl;
}

// 2.27 Периметр трапеции
void trapezoidPerimeter() {
    double a, b, h;
    cout << "Введите основания и высоту трапеции: ";
    cin >> a >> b >> h;
    double side = sqrt(pow((b - a) / 2, 2) + h * h);
    cout << "Периметр: " << a + b + 2 * side << endl;
}

// 2.28 Площадь трапеции
void trapezoidArea() {
    double a, b, angle;
    cout << "Введите основания и угол (в градусах): ";
    cin >> a >> b >> angle;
    double h = ((b - a) / 2) * tan(angle * M_PI / 180);
    cout << "Площадь: " << (a + b) * h / 2 << endl;
}

// 2.29 Треугольник по координатам
void triangle() {
    double x1, y1, x2, y2, x3, y3;
    cout << "Введите координаты вершин треугольника (x1 y1 x2 y2 x3 y3): ";
    cin >> x1 >> y1 >> x2 >> y2 >> x3 >> y3;

    double a = sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2));
    double b = sqrt(pow(x3 - x2, 2) + pow(y3 - y2, 2));
    double c = sqrt(pow(x1 - x3, 2) + pow(y1 - y3, 2));
    double p = a + b + c;

    cout << "Периметр: " << p << "\nПлощадь: "
        << 0.5 * abs((x2 - x1) * (y3 - y1) - (x3 - x1) * (y2 - y1)) << endl;
}

// 2.30 Площадь четырехугольника
void quadrilateral() {
    vector<pair<double, double>> points(4);
    cout << "Введите координаты 4 вершин (x y): ";
    for (int i = 0; i < 4; i++)
        cin >> points[i].first >> points[i].second;

    double area = 0;
    for (int i = 1; i < 3; i++) {
        double x1 = points[0].first, y1 = points[0].second;
        double x2 = points[i].first, y2 = points[i].second;
        double x3 = points[i + 1].first, y3 = points[i + 1].second;
        area += 0.5 * abs((x2 - x1) * (y3 - y1) - (x3 - x1) * (y2 - y1));
    }
    cout << "Площадь четырехугольника: " << area << endl;
}

// 2.31 Стоимость покупки
void purchase() {
    double price_c, price_p, price_a;
    double w_c, w_p, w_a;

    cout << "Введите стоимость 1 кг (конфет, печенья, яблок): ";
    cin >> price_c >> price_p >> price_a;
    cout << "Введите вес покупки (конфет, печенья, яблок): ";
    cin >> w_c >> w_p >> w_a;

    cout << "Общая стоимость: "
        << price_c * w_c + price_p * w_p + price_a * w_a << endl;
}

// 2.32 Стоимость компьютеров
void computers() {
    double monitor, system_block, keyboard, mouse;
    cout << "Введите стоимость комплектующих (монитор, системный блок, клавиатура, мышь): ";
    cin >> monitor >> system_block >> keyboard >> mouse;

    double total = monitor + system_block + keyboard + mouse;
    int n;
    cout << "Введите количество компьютеров: ";
    cin >> n;

    cout << "Стоимость " << n << " компьютеров: " << total * n << endl;
}

// 2.33 Средний возраст
void age() {
    double tanya, mitya;
    cout << "Введите возраст Тани и Мити: ";
    cin >> tanya >> mitya;

    double avg = (tanya + mitya) / 2;
    cout << "Средний возраст: " << avg
        << "\nОтклонение Тани: " << abs(tanya - avg)
        << "\nОтклонение Мити: " << abs(mitya - avg) << endl;
}// 2.34 Встреча автомобилей
void meeting() {
    double v1, v2, s;
    cout << "Введите скорости и расстояние: ";
    cin >> v1 >> v2 >> s;
    cout << "Время до встречи: " << s / (v1 + v2) << " ч" << endl;
}

// 2.35 Расстояние между автомобилями
void carsDistance() {
    double v1, v2, s;
    cout << "Введите скорости и начальное расстояние: ";
    cin >> v1 >> v2 >> s;
    cout << "Расстояние через 30 мин: " << s + (v1 - v2) * 0.5 << " км" << endl;
}

// 2.36 Конвертер температур
void temperature() {
    double celsius;
    cout << "Введите температуру в Цельсиях: ";
    cin >> celsius;
    cout << "Фаренгейт: " << celsius * 1.8 + 32
        << "\nКельвин: " << celsius + 273.15 << endl;
}

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");

    while (true) {
        cout << "\nВыберите задачу (23-36) или 0 для выхода:\n";
        int choice;
        cin >> choice;

        switch (choice) {
        case 23: rectangle(); break;
        case 24: arithmetic(); break;
        case 25: parallelepiped(); break;
        case 26: distancePoints(); break;
        case 27: trapezoidPerimeter(); break;
        case 28: trapezoidArea(); break;
        case 29: triangle(); break;
        case 30: quadrilateral(); break;
        case 31: purchase(); break;
        case 32: computers(); break;
        case 33: age(); break;
        case 34: meeting(); break;
        case 35: carsDistance(); break;
        case 36: temperature(); break;
        case 0: return 0;
        default: cout << "Неверный выбор!" << endl;
        }
    }
}

#include <iostream>
using namespace std;

// =============== ЗАДАЧА 3.21 ===============
int main_3_21() {
    cout << "Задача 3.21: Дано трехзначное число. Найти число, полученное при прочтении его цифр справа налево." << endl;
    
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int a = n / 100;        // первая цифра
    int b = (n / 10) % 10;  // вторая цифра
    int c = n % 10;         // третья цифра
    
    int reversed = c * 100 + b * 10 + a;
    cout << "Число справа налево: " << reversed << endl;
    
    return 0;
}

// =============== ЗАДАЧА 3.22 ===============
int main_3_22() {
    cout << "Задача 3.22: Дано трехзначное число. В нем зачеркнули первую слева цифру и приписали ее в конце." << endl;
    
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int a = n / 100;        // первая цифра
    int bc = n % 100;       // последние две цифры
    
    int result = bc * 10 + a;
    cout << "Первая цифра в конце: " << result << endl;
    
    return 0;
}

// =============== ЗАДАЧА 3.23 ===============
int main_3_23() {
    cout << "Задача 3.23: Дано трехзначное число. В нем зачеркнули последнюю справа цифру и приписали ее в начале." << endl;
    
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int c = n % 10;         // последняя цифра
    int ab = n / 10;        // первые две цифры
    
    int result = c * 100 + ab;
    cout << "Последняя цифра в начале: " << result << endl;
    
    return 0;
}

// =============== ЗАДАЧА 3.24 ===============
int main_3_24() {
    cout << "Задача 3.24: Дано трехзначное число. Найти число, полученное при перестановке первой и второй цифр." << endl;
    
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int a = n / 100;        // первая цифра
    int b = (n / 10) % 10;  // вторая цифра
    int c = n % 10;         // третья цифра
    
    int result = b * 100 + a * 10 + c;
    cout << "После перестановки 1 и 2 цифр: " << result << endl;
    
    return 0;
}

// =============== ЗАДАЧА 3.25 ===============
int main_3_25() {
    cout << "Задача 3.25: Дано трехзначное число. Найти число, полученное при перестановке второй и третьей цифр." << endl;
    
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int a = n / 100;        // первая цифра
    int b = (n / 10) % 10;  // вторая цифра
    int c = n % 10;         // третья цифра
    
    int result = a * 100 + c * 10 + b;
    cout << "После перестановки 2 и 3 цифр: " << result << endl;
    
    return 0;
}

// =============== ЗАДАЧА 3.26 ===============
int main_3_26() {
    cout << "Задача 3.26: Дано трехзначное число, в котором все цифры различны. Получить шесть чисел, образованных при перестановке цифр." << endl;
    
    int n;
    cout << "Введите трехзначное число с разными цифрами: ";
    cin >> n;
    
    int a = n / 100;        // первая цифра
    int b = (n / 10) % 10;  // вторая цифра
    int c = n % 10;         // третья цифра
    
    cout << "Все перестановки:" << endl;
    cout << a << b << c << endl;  // abc
    cout << a << c << b << endl;  // acb
    cout << b << a << c << endl;  // bac
    cout << b << c << a << endl;  // bca
    cout << c << a << b << endl;  // cab
    cout << c << b << a << endl;  // cba
    
    return 0;
}

// =============== ЗАДАЧА 3.27 ===============
int main_3_27() {
    cout << "Задача 3.27: Написать программу, в которой рассчитывается:" << endl;
    cout << "а) сумма цифр 4-значного числа" << endl;
    cout << "б) сумма цифр 5-значного числа" << endl;
    
    // а) для 4-значного числа
    int n4;
    cout << "Введите 4-значное число: ";
    cin >> n4;
    
    int sum4 = 0;
    int temp = n4;
    while (temp > 0) {
        sum4 += temp % 10;
        temp /= 10;
    }
    cout << "а) Сумма цифр 4-значного числа: " << sum4 << endl;
    
    // б) для 5-значного числа
    int n5;
    cout << "Введите 5-значное число: ";
    cin >> n5;
    
    int sum5 = 0;
    temp = n5;
    while (temp > 0) {
        sum5 += temp % 10;
        temp /= 10;
    }
    cout << "б) Сумма цифр 5-значного числа: " << sum5 << endl;
    
    return 0;
}

// =============== ЗАДАЧА 3.28 ===============
int main_3_28() {
    cout << "Задача 3.28: Дано четырехзначное число. Найти:" << endl;
    cout << "а) число, полученное при прочтении его цифр справа налево" << endl;
    cout << "б) число при перестановке пар цифр" << endl;
    cout << "в) число при перестановке второй и третьей цифр" << endl;
    cout << "г) число при перестановке двух первых и двух последних цифр" << endl;
    
    int n;
    cout << "Введите четырехзначное число: ";
    cin >> n;
    
    // Способ 1: с выделением цифр
    int a = n / 1000;       // первая цифра
    int b = (n / 100) % 10; // вторая цифра
    int c = (n / 10) % 10;  // третья цифра
    int d = n % 10;         // четвертая цифра
    
    // а) число справа налево
    int reversed = d * 1000 + c * 100 + b * 10 + a;
    cout << "а) Число справа налево: " << reversed << endl;
    
    // б) перестановка 1-2 и 3-4 цифр
    int result_b = b * 1000 + a * 100 + d * 10 + c;
    cout << "б) После перестановки пар: " << result_b << endl;
    
    // в) перестановка 2-3 цифр
    int result_c = a * 1000 + c * 100 + b * 10 + d;
    cout << "в) После перестановки 2 и 3 цифр: " << result_c << endl;
    
    // г) перестановка двух первых и двух последних цифр (способ 1)
    int result_d1 = c * 1000 + d * 100 + a * 10 + b;
    cout << "г) После перестановки двух пар цифр (способ 1): " << result_d1 << endl;
    
    // г) без выделения цифр (способ 2)
    int result_d2 = (n % 100) * 100 + (n / 100);
    cout << "г) После перестановки двух пар цифр (способ 2): " << result_d2 << endl;
    
    return 0;
}

// =============== ЗАДАЧА 3.29 ===============
int main_3_29() {
    cout << "Задача 3.29: Дано натуральное число n (n > 9). Найти:" << endl;
    cout << "а) число единиц в нем" << endl;
    cout << "б) число десятков в нем" << endl;
    
    int n;
    cout << "Введите натуральное число (n > 9): ";
    cin >> n;
    
    // а) число единиц
    int units = n % 10;
    cout << "а) Число единиц: " << units << endl;
    
    // б) число десятков
    int tens = (n / 10) % 10;
    cout << "б) Число десятков: " << tens << endl;
    
    return 0;
}

// =============== ЗАДАЧА 3.30 ===============
int main_3_30() {
    cout << "Задача 3.30: Дано натуральное число n (n > 99). Найти:" << endl;
    cout << "а) число десятков в нем" << endl;
    cout << "б) число сотен в нем" << endl;
    
    int n;
    cout << "Введите натуральное число (n > 99): ";
    cin >> n;
    
    // а) число десятков
    int tens = (n / 10) % 10;
    cout << "а) Число десятков: " << tens << endl;
    
    // б) число сотен
    int hundreds = (n / 100) % 10;
    cout << "б) Число сотен: " << hundreds << endl;
    
    return 0;
}

// =============== ГЛАВНАЯ ФУНКЦИЯ ===============
int main() {
    cout << "Выберите задачу для выполнения:" << endl;
    cout << "21 - Обратное трехзначное число" << endl;
    cout << "22 - Первую цифру в конец" << endl;
    cout << "23 - Последнюю цифру в начало" << endl;
    cout << "24 - Перестановка первой и второй цифр" << endl;
    cout << "25 - Перестановка второй и третьей цифр" << endl;
    cout << "26 - Все перестановки трехзначного числа" << endl;
    cout << "27 - Сумма цифр 4- и 5-значных чисел" << endl;
    cout << "28 - Операции с четырехзначным числом" << endl;
    cout << "29 - Число единиц и десятков" << endl;
    cout << "30 - Число десятков и сотен" << endl;
    
    int choice;
    cout << "Введите номер задачи (21-30): ";
    cin >> choice;
    
    switch (choice) {
        case 21: main_3_21(); break;
        case 22: main_3_22(); break;
        case 23: main_3_23(); break;
        case 24: main_3_24(); break;
        case 25: main_3_25(); break;
        case 26: main_3_26(); break;
        case 27: main_3_27(); break;
        case 28: main_3_28(); break;
        case 29: main_3_29(); break;
        case 30: main_3_30(); break;
        default: cout << "Неверный выбор!" << endl;
    }
    
    return 0;
}
// Задача 3.41
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    int n;
    cout << "Введите n (1 ≤ n ≤ 999, последняя цифра не 0): ";
    cin >> n;
    
    if (n < 1 || n > 999 || n % 10 == 0) {
        cout << "Неверный ввод!" << endl;
        return 1;
    }
    
    int x;
    if (n < 10) {
        x = n * 100;
    } else if (n < 100) {
        int a = n / 10;
        int b = n % 10;
        x = b * 100 + a * 10;
    } else {
        int c = n / 100;
        int b = (n / 10) % 10;
        int a = n % 10;
        x = a * 100 + b * 10 + c;
    }
    
    cout << "Число x = " << x << endl;
    
    return 0;
}
// Задача 4.11
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    double v_kmh, v_ms;
    cout << "Введите скорость в км/ч: ";
    cin >> v_kmh;
    cout << "Введите скорость в м/с: ";
    cin >> v_ms;
    
    double v_kmh_to_ms = v_kmh * 1000 / 3600;
    
    if (v_kmh_to_ms > v_ms) {
        cout << "Скорость " << v_kmh << " км/ч больше" << endl;
    } else if (v_kmh_to_ms < v_ms) {
        cout << "Скорость " << v_ms << " м/с больше" << endl;
    } else {
        cout << "Скорости равны" << endl;
    }
    
    return 0;
}
// Задача 4.12
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    double r, a;
    cout << "Введите радиус круга: ";
    cin >> r;
    cout << "Введите сторону квадрата: ";
    cin >> a;
    
    double circle_area = M_PI * r * r;
    double square_area = a * a;
    
    if (circle_area > square_area) {
        cout << "Площадь круга больше" << endl;
    } else if (circle_area < square_area) {
        cout << "Площадь квадрата больше" << endl;
    } else {
        cout << "Площади равны" << endl;
    }
    
    return 0;
}
// Задача 4.13
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    double m1, v1, m2, v2;
    cout << "Введите массу и объем первого тела: ";
    cin >> m1 >> v1;
    cout << "Введите массу и объем второго тела: ";
    cin >> m2 >> v2;
    
    double density1 = m1 / v1;
    double density2 = m2 / v2;
    
    if (density1 > density2) {
        cout << "Плотность первого материала больше" << endl;
    } else if (density1 < density2) {
        cout << "Плотность второго материала больше" << endl;
    } else {
        cout << "Плотности равны" << endl;
    }
    
    return 0;
}
// Задача 4.14
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    double r1, u1, r2, u2;
    cout << "Введите сопротивление и напряжение первого участка: ";
    cin >> r1 >> u1;
    cout << "Введите сопротивление и напряжение второго участка: ";
    cin >> r2 >> u2;
    
    double i1 = u1 / r1;
    double i2 = u2 / r2;
    
    if (i1 < i2) {
        cout << "Меньший ток протекает по первому участку" << endl;
    } else if (i1 > i2) {
        cout << "Меньший ток протекает по второму участку" << endl;
    } else {
        cout << "Токи равны" << endl;
    }
    
    return 0;
}
// Задача 4.15
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    double a, b, c;
    cout << "Введите коэффициенты a, b, c (a ≠ 0): ";
    cin >> a >> b >> c;
    
    if (a == 0) {
        cout << "Это не квадратное уравнение!" << endl;
        return 1;
    }
    
    double d = b * b - 4 * a * c;
    
    if (d >= 0) {
        cout << "Уравнение имеет вещественные корни" << endl;
    } else {
        cout << "Уравнение не имеет вещественных корней" << endl;
    }
    
    return 0;
}
// Задача 4.16
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    double a, b, c;
    cout << "Введите коэффициенты a, b, c (a ≠ 0): ";
    cin >> a >> b >> c;
    
    if (a == 0) {
        cout << "Это не квадратное уравнение!" << endl;
        return 1;
    }
    
    double d = b * b - 4 * a * c;
    
    if (d >= 0) {
        double x1 = (-b + sqrt(d)) / (2 * a);
        double x2 = (-b - sqrt(d)) / (2 * a);
        cout << "Корни уравнения: x1 = " << x1 << ", x2 = " << x2 << endl;
    } else {
        cout << "Уравнение не имеет вещественных корней" << endl;
    }
    
    return 0;
}
// Задача 4.17
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    int birth_year, birth_month, current_year, current_month;
    cout << "Введите год и месяц рождения: ";
    cin >> birth_year >> birth_month;
    cout << "Введите текущий год и месяц: ";
    cin >> current_year >> current_month;
    
    int age = current_year - birth_year;
    if (current_month < birth_month) {
        age--;
    }
    
    cout << "Возраст: " << age << " полных лет" << endl;
    
    return 0;
}
// Задача 4.18
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    double s_circle, s_square;
    cout << "Введите площадь круга: ";
    cin >> s_circle;
    cout << "Введите площадь квадрата: ";
    cin >> s_square;
    
    double r = sqrt(s_circle / M_PI);
    double a = sqrt(s_square);
    
    if (2 * r <= a) {
        cout << "Круг поместится в квадрате" << endl;
    } else {
        cout << "Круг не поместится в квадрате" << endl;
    }
    
    if (a * sqrt(2) <= 2 * r) {
        cout << "Квадрат поместится в круге" << endl;
    } else {
        cout << "Квадрат не поместится в круге" << endl;
    }
    
    return 0;
}
// Задача 4.19
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    double s_circle, s_triangle;
    cout << "Введите площадь круга: ";
    cin >> s_circle;
    cout << "Введите площадь равностороннего треугольника: ";
    cin >> s_triangle;
    
    double r = sqrt(s_circle / M_PI);
    double a = sqrt((4 * s_triangle) / sqrt(3));
    
    if (2 * r <= a * sqrt(3) / 2) {
        cout << "Круг поместится в треугольнике" << endl;
    } else {
        cout << "Круг не поместится в треугольнике" << endl;
    }
    
    if (a * sqrt(3) / 3 <= r) {
        cout << "Треугольник поместится в круге" << endl;
    } else {
        cout << "Треугольник не поместится в круге" << endl;
    }
    
    return 0;
}
// Задача 4.20
#include <iostream>
#include <algorithm>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    double x1_l, y1_l, x1_r, y1_r;
    double x2_l, y2_l, x2_r, y2_r;
    
    cout << "Введите координаты левого нижнего и правого верхнего углов первого прямоугольника: ";
    cin >> x1_l >> y1_l >> x1_r >> y1_r;
    cout << "Введите координаты левого нижнего и правого верхнего углов второго прямоугольника: ";
    cin >> x2_l >> y2_l >> x2_r >> y2_r;
    
    double min_x = min(x1_l, x2_l);
    double min_y = min(y1_l, y2_l);
    double max_x = max(x1_r, x2_r);
    double max_y = max(y1_r, y2_r);
    
    cout << "Минимальный охватывающий прямоугольник:" << endl;
    cout << "Левый нижний угол: (" << min_x << ", " << min_y << ")" << endl;
    cout << "Правый верхний угол: (" << max_x << ", " << max_y << ")" << endl;
    
    return 0;
}
// Задача 4.21
#include <iostream>
#include <algorithm>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    double x1, y1, w1, h1;
    double x2, y2, w2, h2;
    
    cout << "Введите координаты левого нижнего угла и размеры (ширина, высота) первого прямоугольника: ";
    cin >> x1 >> y1 >> w1 >> h1;
    cout << "Введите координаты левого нижнего угла и размеры (ширина, высота) второго прямоугольника: ";
    cin >> x2 >> y2 >> w2 >> h2;
    
    double x1_r = x1 + w1;
    double y1_r = y1 + h1;
    double x2_r = x2 + w2;
    double y2_r = y2 + h2;
    
    double min_x = min(x1, x2);
    double min_y = min(y1, y2);
    double max_x = max(x1_r, x2_r);
    double max_y = max(y1_r, y2_r);
    
    cout << "Минимальный охватывающий прямоугольник:" << endl;
    cout << "Левый нижний угол: (" << min_x << ", " << min_y << ")" << endl;
    cout << "Правый верхний угол: (" << max_x << ", " << max_y << ")" << endl;
    
    return 0;
}
// Задача 4.22
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    int m, n;
    cout << "Введите m и n: ";
    cin >> m >> n;
    
    if (n == 0) {
        cout << "Деление на ноль!" << endl;
        return 1;
    }
    
    if (m % n == 0) {
        cout << "Частное: " << m / n << endl;
    } else {
        cout << m << " на " << n << " нацело не делится" << endl;
    }
    
    return 0;
}
\\Задача 4.23
#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru_RU.UTF-8");
    
    int a, n;
    cout << "Введите число n: ";
    cin >> n;
    cout << "Введите число a: ";
    cin >> a;
    
    if (a == 0) {
        cout << "Делитель не может быть нулем!" << endl;
        return 1;
    }
    
    if (n % a == 0) {
        cout << a << " является делителем " << n << endl;
    } else {
        cout << a << " не является делителем " << n << endl;
    }
    
    return 0;
}
Вот все задачи с 4.24 по 4.69, каждая оформлена как отдельная программа:

\\ 4.24:


#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите натуральное число: ";
    cin >> n;
    
    if (n % 2 == 0) {
        cout << "а) Число " << n << " четное" << endl;
    } else {
        cout << "а) Число " << n << " нечетное" << endl;
    }
    
    if (n % 10 == 7) {
        cout << "б) Число " << n << " оканчивается цифрой 7" << endl;
    } else {
        cout << "б) Число " << n << " не оканчивается цифрой 7" << endl;
    }
    
    return 0;
}


\\4.25:


#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите целое число: ";
    cin >> n;
    
    int nextEven;
    if (n % 2 == 0) {
        nextEven = n + 2;
    } else {
        nextEven = n + 1;
    }
    
    cout << "Следующее четное число после " << n << " = " << nextEven << endl;
    
    return 0;
}

\\4.26:

#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите двузначное число: ";
    cin >> n;
    
    int first = n / 10;
    int second = n % 10;
    
    if (first > second) {
        cout << "а) Первая цифра (" << first << ") больше второй (" << second << ")" << endl;
    } else if (first < second) {
        cout << "а) Вторая цифра (" << second << ") больше первой (" << first << ")" << endl;
    } else {
        cout << "а) Цифры равны" << endl;
    }
    
    if (first == second) {
        cout << "б) Цифры одинаковые" << endl;
    } else {
        cout << "б) Цифры разные" << endl;
    }
    
    return 0;
}

\\4.27:


#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите двузначное число: ";
    cin >> n;
    
    int first = n / 10;
    int second = n % 10;
    
    int square = n * n;
    int sumCubes = first * first * first + second * second * second;
    int quadrupleSum = 4 * sumCubes;
    
    if (square == quadrupleSum) {
        cout << "Ответ: ДА, квадрат числа равен учетверенной сумме кубов его цифр" << endl;
    } else {
        cout << "Ответ: НЕТ, квадрат числа НЕ равен учетверенной сумме кубов его цифр" << endl;
    }
    
    return 0;
}


//4.28:

#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите двузначное число: ";
    cin >> n;
    
    int first = n / 10;
    int second = n % 10;
    int sum = first + second;
    
    cout << "Сумма цифр: " << first << " + " << second << " = " << sum << endl;
    
    if (sum >= 10 && sum <= 99) {
        cout << "а) Сумма цифр является двузначным числом" << endl;
    } else {
        cout << "а) Сумма цифр НЕ является двузначным числом" << endl;
    }
    
    int a;
    cout << "Введите число а для сравнения: ";
    cin >> a;
    
    if (sum > a) {
        cout << "б) Сумма цифр (" << sum << ") больше числа а (" << a << ")" << endl;
    } else if (sum < a) {
        cout << "б) Сумма цифр (" << sum << ") меньше числа а (" << a << ")" << endl;
    } else {
        cout << "б) Сумма цифр (" << sum << ") равна числу а (" << a << ")" << endl;
    }
    
    return 0;
}

// 4.29:

#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите двузначное число: ";
    cin >> n;
    
    int first = n / 10;
    int second = n % 10;
    int sum = first + second;
    
    if (sum % 3 == 0) {
        cout << "а) Сумма цифр кратна 3" << endl;
    } else {
        cout << "а) Сумма цифр НЕ кратна 3" << endl;
    }
    
    int a;
    cout << "Введите число а: ";
    cin >> a;
    
    if (a == 0) {
        cout << "б) Деление на 0 невозможно!" << endl;
    } else if (sum % a == 0) {
        cout << "б) Сумма цифр кратна числу " << a << endl;
    } else {
        cout << "б) Сумма цифр НЕ кратна числу " << a << endl;
    }
    
    return 0;
}


// 4.30:

#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int first = n / 100;
    int third = n % 10;
    
    if (first == third) {
        cout << "Число " << n << " является палиндромом (перевертышем)" << endl;
    } else {
        cout << "Число " << n << " НЕ является палиндромом" << endl;
    }
    
    return 0;
}

//4.31:

#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int first = n / 100;
    int second = (n / 10) % 10;
    int third = n % 10;
    
    if (first > third) {
        cout << "а) Первая цифра (" << first << ") больше последней (" << third << ")" << endl;
    } else if (first < third) {
        cout << "а) Последняя цифра (" << third << ") больше первой (" << first << ")" << endl;
    } else {
        cout << "а) Первая и последняя цифры равны" << endl;
    }
    
    if (first > second) {
        cout << "б) Первая цифра (" << first << ") больше второй (" << second << ")" << endl;
    } else if (first < second) {
        cout << "б) Вторая цифра (" << second << ") больше первой (" << first << ")" << endl;
    } else {
        cout << "б) Первая и вторая цифры равны" << endl;
    }
    
    if (second > third) {
        cout << "в) Вторая цифра (" << second << ") больше последней (" << third << ")" << endl;
    } else if (second < third) {
        cout << "в) Последняя цифра (" << third << ") больше второй (" << second << ")" << endl;
    } else {
        cout << "в) Вторая и последняя цифры равны" << endl;
    }
    
    return 0;
}

// 4.32:

#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int first = n / 100;
    int second = (n / 10) % 10;
    int third = n % 10;
    
    int square = n * n;
    int sumCubes = first * first * first + second * second * second + third * third * third;
    
    if (square == sumCubes) {
        cout << "Ответ: ДА, квадрат числа равен сумме кубов его цифр" << endl;
    } else {
        cout << "Ответ: НЕТ, квадрат числа НЕ равен сумме кубов его цифр" << endl;
    }
    
    return 0;
}

// 4.33:


#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int first = n / 100;
    int second = (n / 10) % 10;
    int third = n % 10;
    
    int sum = first + second + third;
    int product = first * second * third;
    
    if (sum >= 10 && sum <= 99) {
        cout << "а) Сумма цифр является двузначным числом" << endl;
    } else {
        cout << "а) Сумма цифр НЕ является двузначным числом" << endl;
    }
    
    if (product >= 100 && product <= 999) {
        cout << "б) Произведение цифр является трехзначным числом" << endl;
    } else {
        cout << "б) Произведение цифр НЕ является трехзначным числом" << endl;
    }
    
    int a;
    cout << "Введите число а для сравнения: ";
    cin >> a;
    
    if (product > a) {
        cout << "в) Произведение цифр (" << product << ") больше числа а (" << a << ")" << endl;
    } else if (product < a) {
        cout << "в) Произведение цифр (" << product << ") меньше числа а (" << a << ")" << endl;
    } else {
        cout << "в) Произведение цифр (" << product << ") равно числу а (" << a << ")" << endl;
    }
    
    if (sum % 5 == 0) {
        cout << "г) Сумма цифр кратна 5" << endl;
    } else {
        cout << "г) Сумма цифр НЕ кратна 5" << endl;
    }
    
    int a2;
    cout << "Введите число а для проверки кратности: ";
    cin >> a2;
    
    if (a2 == 0) {
        cout << "д) Деление на 0 невозможно!" << endl;
    } else if (sum % a2 == 0) {
        cout << "д) Сумма цифр кратна числу " << a2 << endl;
    } else {
        cout << "д) Сумма цифр НЕ кратна числу " << a2 << endl;
    }
    
    return 0;
}

// 4.34:


#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int first = n / 100;
    int second = (n / 10) % 10;
    int third = n % 10;
    
    if (first == second && second == third) {
        cout << "а) Все три цифры одинаковые" << endl;
    } else {
        cout << "а) Не все цифры одинаковые" << endl;
    }
    
    if (first == second || first == third || second == third) {
        cout << "б) Среди цифр есть одинаковые" << endl;
    } else {
        cout << "б) Все цифры различны" << endl;
    }
    
    return 0;
}


// 4.35:


#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите четырехзначное число: ";
    cin >> n;
    
    int first = n / 1000;
    int second = (n / 100) % 10;
    int third = (n / 10) % 10;
    int fourth = n % 10;
    
    int sumFirstTwo = first + second;
    int sumLastTwo = third + fourth;
    int totalSum = first + second + third + fourth;
    int product = first * second * third * fourth;
    
    if (sumFirstTwo == sumLastTwo) {
        cout << "а) Сумма первых двух цифр равна сумме последних двух" << endl;
    } else {
        cout << "а) Сумма первых двух цифр НЕ равна сумме последних двух" << endl;
    }
    
    if (totalSum % 3 == 0) {
        cout << "б) Сумма цифр кратна 3" << endl;
    } else {
        cout << "б) Сумма цифр НЕ кратна 3" << endl;
    }
    
    if (product % 4 == 0) {
        cout << "в) Произведение цифр кратно 4" << endl;
    } else {
        cout << "в) Произведение цифр НЕ кратно 4" << endl;
    }
    
    int a;
    cout << "Введите число а для проверки кратности произведения: ";
    cin >> a;
    
    if (a == 0) {
        cout << "г) Деление на 0 невозможно!" << endl;
    } else if (product % a == 0) {
        cout << "г) Произведение цифр кратно числу " << a << endl;
    } else {
        cout << "г) Произведение цифр НЕ кратно числу " << a << endl;
    }
    
    return 0;
}


// 4.36:


#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите натуральное число: ";
    cin >> n;
    
    int lastDigit = n % 10;
    
    cout << "а) Проверка на четную последнюю цифру: ";
    if (lastDigit == 0) cout << "Да (0 - четное)" << endl;
    else if (lastDigit == 2) cout << "Да" << endl;
    else if (lastDigit == 4) cout << "Да" << endl;
    else if (lastDigit == 6) cout << "Да" << endl;
    else if (lastDigit == 8) cout << "Да" << endl;
    else cout << "Нет" << endl;
    
    cout << "б) Проверка на нечетную последнюю цифру: ";
    if (lastDigit == 1) cout << "Да" << endl;
    else if (lastDigit == 3) cout << "Да" << endl;
    else if (lastDigit == 5) cout << "Да" << endl;
    else if (lastDigit == 7) cout << "Да" << endl;
    else if (lastDigit == 9) cout << "Да" << endl;
    else cout << "Нет" << endl;
    
    return 0;
}


// 4.37:


#include <iostream>
using namespace std;

int main() {
    int a, b;
    cout << "Введите число a: ";
    cin >> a;
    cout << "Введите число b: ";
    cin >> b;
    
    if (a == 0) {
        cout << "a не может быть делителем b, так как a = 0" << endl;
    } else if (b % a == 0) {
        cout << "a является делителем b" << endl;
    } else {
        cout << "a НЕ является делителем b" << endl;
    }
    
    if (b == 0) {
        cout << "b не может быть делителем a, так как b = 0" << endl;
    } else if (a % b == 0) {
        cout << "b является делителем a" << endl;
    } else {
        cout << "b НЕ является делителем a" << endl;
    }
    
    return 0;
}

//4.38:


#include <iostream>
using namespace std;

int main() {
    int a, b, c, d;
    cout << "Введите размеры стола (a > b):" << endl;
    cout << "a = ";
    cin >> a;
    cout << "b = ";
    cin >> b;
    
    cout << "Введите размеры прямоугольника (c > d):" << endl;
    cout << "c = ";
    cin >> c;
    cout << "d = ";
    cin >> d;
    
    int count1_long = a / c;
    int count1_short = b / d;
    int total1 = count1_long * count1_short;
    
    int count2_long = a / d;
    int count2_short = b / c;
    int total2 = count2_long * count2_short;
    
    if (total1 > total2) {
        cout << "Больше прямоугольников можно разместить при первом способе" << endl;
    } else if (total2 > total1) {
        cout << "Больше прямоугольников можно разместить при втором способе" << endl;
    } else {
        cout << "Оба способа позволяют разместить одинаковое количество" << endl;
    }
    
    return 0;
}

 4.39:


#include <iostream>
using namespace std;

int main() {
    double t;
    cout << "Введите время t (в минутах от начала часа): ";
    cin >> t;
    
    int cycle = static_cast<int>(t) % 5;
    
    if (cycle < 3) {
        cout << "В момент времени " << t << " минут горит ЗЕЛЕНЫЙ сигнал" << endl;
    } else {
        cout << "В момент времени " << t << " минут горит КРАСНЫЙ сигнал" << endl;
    }
    
    return 0;
}

// 4.40


#include <iostream>
using namespace std;

int main() {
    double num;
    cout << "Введите число: ";
    cin >> num;
    
    if (num > -5 && num < 3) {
        cout << "Число " << num << " принадлежит интервалу (-5, 3)" << endl;
    } else {
        cout << "Число " << num << " НЕ принадлежит интервалу (-5, 3)" << endl;
    }
    
    return 0;
}

// 4.41

#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите натуральное число: ";
    cin >> n;
    
    if ((n >= 10 && n <= 99) || (n >= -99 && n <= -10)) {
        cout << "Число " << n << " является двузначным" << endl;
    } else {
        cout << "Число " << n << " НЕ является двузначным" << endl;
    }
    
    return 0;
}

// 4.47:


#include <iostream>
using namespace std;

int main() {
    double a, b, c;
    cout << "Введите число a: ";
    cin >> a;
    cout << "Введите число b: ";
    cin >> b;
    cout << "Введите число c: ";
    cin >> c;
    
    if (a < b && b < c) {
        cout << "а) Неравенство a < b < c ВЫПОЛНЯЕТСЯ" << endl;
    } else {
        cout << "а) Неравенство a < b < c НЕ выполняется" << endl;
    }
    
    if (b > a && a > c) {
        cout << "б) Неравенство b > a > c ВЫПОЛНЯЕТСЯ" << endl;
    } else {
        cout << "б) Неравенство b > a > c НЕ выполняется" << endl;
    }
    
    return 0;
}
//4.48:
#include <iostream>
using namespace std;

int main() {
    int a, b;
    cout << "Введите первое число: ";
    cin >> a;
    cout << "Введите второе число: ";
    cin >> b;
    
    bool a_divides_b = (a != 0 && b % a == 0);
    bool b_divides_a = (b != 0 && a % b == 0);
    
    if (a_divides_b && b_divides_a) {
        cout << "Оба числа являются делителями друг друга" << endl;
    } else if (a_divides_b) {
        cout << a << " является делителем " << b << endl;
    } else if (b_divides_a) {
        cout << b << " является делителем " << a << endl;
    } else {
        cout << "Ни одно из чисел не является делителем другого" << endl;
    }
    
    return 0;
}

//4.49


#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите двузначное число: ";
    cin >> n;
    
    int first = n / 10;
    int second = n % 10;
    
    if (first == 3 || second == 3) {
        cout << "а) В число входит цифра 3" << endl;
    } else {
        cout << "а) В число НЕ входит цифра 3" << endl;
    }
    
    int a;
    cout << "Введите цифру а (0-9): ";
    cin >> a;
    
    if (first == a || second == a) {
        cout << "б) В число входит цифра " << a << endl;
    } else {
        cout << "б) В число НЕ входит цифра " << a << endl;
    }
    
    return 0;
}


/4.50

#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите двузначное число: ";
    cin >> n;
    
    int first = n / 10;
    int second = n % 10;
    
    if (first == 4 || first == 7 || second == 4 || second == 7) {
        cout << "а) В число входит цифра 4 или 7" << endl;
    } else {
        cout << "а) В число НЕ входят цифры 4 и 7" << endl;
    }
    
    if (first == 3 || first == 6 || first == 9 ||
        second == 3 || second == 6 || second == 9) {
        cout << "б) В число входит цифра 3, 6 или 9" << endl;
    } else {
        cout << "б) В число НЕ входят цифры 3, 6 и 9" << endl;
    }
    
    return 0;
}


// 4.51:


#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int first = n / 100;
    int second = (n / 10) % 10;
    int third = n % 10;
    
    if (first == 6 || second == 6 || third == 6) {
        cout << "а) В число входит цифра 6" << endl;
    } else {
        cout << "а) В число НЕ входит цифра 6" << endl;
    }
    
    int digit;
    cout << "Введите цифру n (0-9): ";
    cin >> digit;
    
    if (first == digit || second == digit || third == digit) {
        cout << "б) В число входит цифра " << digit << endl;
    } else {
        cout << "б) В число НЕ входит цифра " << digit << endl;
    }
    
    return 0;
}


// 4.52:


#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int first = n / 100;
    int second = (n / 10) % 10;
    int third = n % 10;
    
    if (first == 6 || second == 6 || third == 6) {
        cout << "В число входит цифра 6" << endl;
    } else {
        cout << "В число НЕ входит цифра 6" << endl;
    }
    
    return 0;
}

// 4.53:

#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите трехзначное число: ";
    cin >> n;
    
    int first = n / 100;
    int second = (n / 10) % 10;
    int third = n % 10;
    
    if (first == 4 || first == 7 ||
        second == 4 || second == 7 ||
        third == 4 || third == 7) {
        cout << "а) В число входит цифра 4 или 7" << endl;
    } else {
        cout << "а) В число НЕ входят цифры 4 и 7" << endl;
    }
    
    if (first == 3 || first == 6 || first == 9 ||
        second == 3 || second == 6 || second == 9 ||
        third == 3 || third == 6 || third == 9) {
        cout << "б) В число входит цифра 3, 6 или 9" << endl;
    } else {
        cout << "б) В число НЕ входят цифры 3, 6 и 9" << endl;
    }
    
    return 0;
}
```

// 4.54:

#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите четырехзначное число: ";
    cin >> n;
    
    int first = n / 1000;
    int second = (n / 100) % 10;
    int third = (n / 10) % 10;
    int fourth = n % 10;
    
    if (first == 4 || second == 4 || third == 4 || fourth == 4) {
        cout << "а) В число входит цифра 4" << endl;
    } else {
        cout << "а) В число НЕ входит цифра 4" << endl;
    }
    
    int b;
    cout << "Введите цифру b (0-9): ";
    cin >> b;
    
    if (first == b || second == b || third == b || fourth == b) {
        cout << "б) В число входит цифра " << b << endl;
    } else {
        cout << "б) В число НЕ входит цифра " << b << endl;
    }
    
    return 0;
}

// 4.55:

#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите четырехзначное число: ";
    cin >> n;
    
    int first = n / 1000;
    int second = (n / 100) % 10;
    int third = (n / 10) % 10;
    int fourth = n % 10;
    
    if (first == 2 || first == 7 ||
        second == 2 || second == 7 ||
        third == 2 || third == 7 ||
        fourth == 2 || fourth == 7) {
        cout << "а) В число входит цифра 2 или 7" << endl;
    } else {
        cout << "а) В число НЕ входят цифры 2 и 7" << endl;
    }
    
    if (first == 3 || first == 6 || first == 9 ||
        second == 3 || second == 6 || second == 9 ||
        third == 3 || third == 6 || third == 9 ||
        fourth == 3 || fourth == 6 || fourth == 9) {
        cout << "б) В число входит цифра 3, 6 или 9" << endl;
    } else {
        cout << "б) В число НЕ входят цифры 3, 6 и 9" << endl;
    }
    
    return 0;
}

// 4.56:
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите четырехзначное число: ";
    cin >> n;
    
    int first = n / 1000;
    int second = (n / 100) % 10;
    int third = (n / 10) % 10;
    int fourth = n % 10;
    
    if (first == fourth && second == third) {
        cout << "Число " << n << " является симметричным" << endl;
    } else {
        cout << "Число " << n << " НЕ является симметричным" << endl;
    }
    
    return 0;
}
// 4.57:
#include <iostream>
using namespace std;

int main() {
    int a, b, c, d;
    cout << "Введите неотрицательное число a: ";
    cin >> a;
    cout << "Введите положительное число b: ";
    cin >> b;
    cout << "Введите число c: ";
    cin >> c;
    cout << "Введите число d: ";
    cin >> d;
    
    if (a >= 0 && b > 0) {
        int remainder = a % b;
        
        if (remainder == c || remainder == d) {
            cout << "Остаток от деления " << a << " на " << b 
                 << " равен " << remainder << ", что совпадает с " 
                 << c << " или " << d << endl;
        } else {
            cout << "Остаток от деления " << a << " на " << b 
                 << " равен " << remainder << ", что НЕ совпадает с " 
                 << c << " или " << d << endl;
        }
    } else {
        cout << "Ошибка: a должно быть неотрицательным, b - положительным" << endl;
    }
    
    return 0;
}
// 4.58:
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double a, b, c;
    cout << "Введите число a: ";
    cin >> a;
    cout << "Введите число b: ";
    cin >> b;
    cout << "Введите число c: ";
    cin >> c;
    
    const double EPS = 1e-9;
    bool ab_equal = fabs(a - b) < EPS;
    bool ac_equal = fabs(a - c) < EPS;
    bool bc_equal = fabs(b - c) < EPS;
    
    if (ab_equal || ac_equal || bc_equal) {
        cout << "Среди чисел есть хотя бы одна пара равных" << endl;
    } else {
        cout << "Все три числа различны" << endl;
    }
    
    return 0;
}
// 4.59:
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double a, b, c;
    cout << "Введите сторону a: ";
    cin >> a;
    cout << "Введите сторону b: ";
    cin >> b;
    cout << "Введите сторону c: ";
    cin >> c;
    
    const double EPS = 1e-9;
    
    if (a > 0 && b > 0 && c > 0 &&
        a + b > c && a + c > b && b + c > a) {
        
        if (fabs(a - b) < EPS && fabs(b - c) < EPS) {
            cout << "а) Треугольник равносторонний" << endl;
        } else {
            cout << "а) Треугольник НЕ равносторонний" << endl;
        }
        
        if (fabs(a - b) < EPS || fabs(a - c) < EPS || fabs(b - c) < EPS) {
            cout << "б) Треугольник равнобедренный" << endl;
        } else {
            cout << "б) Треугольник НЕ равнобедренный" << endl;
        }
    } else {
        cout << "Ошибка: с такими сторонами треугольник не существует" << endl;
    }
    
    return 0;
}
// 4.60:
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double height1, height2, height3;
    cout << "Введите рост первого человека (в см): ";
    cin >> height1;
    cout << "Введите рост второго человека (в см): ";
    cin >> height2;
    cout << "Введите рост третьего человека (в см): ";
    cin >> height3;
    
    const double EPS = 1e-9;
    
    if (fabs(height1 - height2) < EPS && fabs(height2 - height3) < EPS) {
        cout << "Рост всех трех человек одинаков: " << height1 << " см" << endl;
    } else {
        cout << "Рост людей разный" << endl;
    }
    
    return 0;
}
// 4.61:
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double a, b, c;
    cout << "Введите коэффициент a (a ≠ 0): ";
    cin >> a;
    
    const double EPS = 1e-9;
    
    if (fabs(a) < EPS) {
        cout << "Ошибка: коэффициент a не должен быть равен 0" << endl;
    } else {
        cout << "Введите коэффициент b: ";
        cin >> b;
        cout << "Введите коэффициент c: ";
        cin >> c;
        
        double D = b * b - 4 * a * c;
        
        if (D > EPS) {
            double x1 = (-b + sqrt(D)) / (2 * a);
            double x2 = (-b - sqrt(D)) / (2 * a);
            cout << "Уравнение имеет два различных корня:" << endl;
            cout << "x₁ = " << x1 << endl;
            cout << "x₂ = " << x2 << endl;
        } else if (fabs(D) < EPS) {
            double x = -b / (2 * a);
            cout << "Уравнение имеет один корень (два равных):" << endl;
            cout << "x = " << x << endl;
        } else {
            cout << "Уравнение не имеет действительных корней" << endl;
        }
    }
    
    return 0;
}
// 4.62:
#include <iostream>
using namespace std;

int main() {
    double a, b, c, d;
    cout << "Введите стороны первого прямоугольника (a, b): ";
    cin >> a >> b;
    cout << "Введите стороны второго прямоугольника (c, d): ";
    cin >> c >> d;
    
    bool fits1 = (a <= c && b <= d);
    bool fits2 = (a <= d && b <= c);
    
    if (fits1 || fits2) {
        cout << "Прямоугольник " << a << "×" << b 
             << " можно поместить в прямоугольник " << c << "×" << d << endl;
    } else {
        cout << "Прямоугольник " << a << "×" << b 
             << " НЕльзя поместить в прямоугольник " << c << "×" << d << endl;
    }
    
    return 0;
}
// 4.63:
#include <iostream>
using namespace std;

int main() {
    double a, b, c, d;
    cout << "Введите размеры конверта (a, b) в мм: ";
    cin >> a >> b;
    cout << "Введите размеры открытки (c, d) в мм: ";
    cin >> c >> d;
    
    double innerWidth = a - 2;
    double innerHeight = b - 2;
    
    bool fits1 = (c <= innerWidth && d <= innerHeight);
    bool fits2 = (c <= innerHeight && d <= innerWidth);
    
    if (fits1 || fits2) {
        cout << "Открытка " << c << "×" << d 
             << " мм поместится в конверт " << a << "×" << b << " мм" << endl;
    } else {
        cout << "Открытка " << c << "×" << d 
             << " мм НЕ поместится в конверт " << a << "×" << b << " мм" << endl;
    }
    
    return 0;
}
// 4.64:
#include <iostream>
using namespace std;

int main() {
    double a, b, d;
    cout << "Введите размеры форточки (a, b) в см: ";
    cin >> a >> b;
    cout << "Введите диаметр головы (d) в см: ";
    cin >> d;
    
    double innerWidth = a - 2;
    double innerHeight = b - 2;
    
    if (d <= innerWidth && d <= innerHeight) {
        cout << "Голова диаметром " << d 
             << " см пройдет в форточку " << a << "×" << b << " см" << endl;
    } else {
        cout << "Голова диаметром " << d 
             << " см НЕ пройдет в форточку " << a << "×" << b << " см" << endl;
    }
    
    return 0;
}
// 4.65:
#include <iostream>
using namespace std;

int main() {
    double a, b, c, x, y;
    cout << "Введите размеры кирпича (a, b, c): ";
    cin >> a >> b >> c;
    cout << "Введите размеры отверстия (x, y): ";
    cin >> x >> y;
    
    bool fits_ab = (a <= x && b <= y) || (a <= y && b <= x);
    bool fits_ac = (a <= x && c <= y) || (a <= y && c <= x);
    bool fits_bc = (b <= x && c <= y) || (b <= y && c <= x);
    
    if (fits_ab || fits_ac || fits_bc) {
        cout << "Кирпич " << a << "×" << b << "×" << c 
             << " пройдет в отверстие " << x << "×" << y << endl;
    } else {
        cout << "Кирпич " << a << "×" << b << "×" << c 
             << " НЕ пройдет в отверстие " << x << "×" << y << endl;
    }
    
    return 0;
}
// 4.66:
#include <iostream>
#include <algorithm>
using namespace std;

int main() {
    double a1, a2, a3, b1, b2, b3;
    cout << "Введите размеры чемодана (a1, a2, a3): ";
    cin >> a1 >> a2 >> a3;
    cout << "Введите размеры коробки (b1, b2, b3): ";
    cin >> b1 >> b2 >> b3;
    
    if (a1 > a2) swap(a1, a2);
    if (a2 > a3) swap(a2, a3);
    if (a1 > a2) swap(a1, a2);
    
    if (b1 > b2) swap(b1, b2);
    if (b2 > b3) swap(b2, b3);
    if (b1 > b2) swap(b1, b2);
    
    if (b1 <= a1 && b2 <= a2 && b3 <= a3) {
        cout << "Коробка " << b1 << "×" << b2 << "×" << b3 
             << " поместится в чемодан " << a1 << "×" << a2 << "×" << a3 << endl;
        cout << "Пассажир может сэкономить на оплате." << endl;
    } else {
        cout << "Коробка " << b1 << "×" << b2 << "×" << b3 
             << " НЕ поместится в чемодан " << a1 << "×" << a2 << "×" << a3 << endl;
        cout << "Пассажиру придется оплатить два места." << endl;
    }
    
    return 0;
}
// 4.67:
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Введите шестизначное число: ";
    cin >> n;
    
    if (n < 100000 || n > 999999) {
        cout << "Ошибка: число должно быть шестизначным!" << endl;
    } else {
        int d1 = n / 100000;
        int d2 = (n / 10000) % 10;
        int d3 = (n / 1000) % 10;
        int d4 = (n / 100) % 10;
        int d5 = (n / 10) % 10;
        int d6 = n % 10;
        
        int sumFirst = d1 + d2 + d3;
        int sumLast = d4 + d5 + d6;
        
        if (sumFirst == sumLast) {
            cout << "Число " << n << " является счастливым!" << endl;
        } else {
            cout << "Число " << n << " НЕ является счастливым." << endl;
        }
    }
    
    return 0;
}
// 4.68:
#include <iostream>
using namespace std;

int main() {
    int year;
    cout << "Введите год: ";
    cin >> year;
    
    bool isLeap = false;
    
    if (year % 4 == 0) {
        if (year % 100 == 0) {
            if (year % 400 == 0) {
                isLeap = true;
            }
        } else {
            isLeap = true;
        }
    }
    
    if (isLeap) {
        cout << year << " год является високосным." << endl;
    } else {
        cout << year << " год НЕ является високосным." << endl;
    }
    
    return 0;
}
// 4.69:
#include <iostream>
#include <algorithm>
using namespace std;

int main() {
    int a, b, c, d, e;
    cout << "Введите размеры стола (a, b), a > b: ";
    cin >> a >> b;
    cout << "Введите размеры кости домино (c, d, e), c > d > e: ";
    cin >> c >> d >> e;
    
    int count1_1 = (a / c) * (b / d);
    int count1_2 = (a / d) * (b / c);
    int count1 = max(count1_1, count1_2);
    
    int count2_1 = (a / c) * (b / e);
    int count2_2 = (a / e) * (b / c);
    int count2 = max(count2_1, count2_2);
    
    int count3_1 = (a / d) * (b / e);
    int count3_2 = (a / e) * (b / d);
    int count3 = max(count3_1, count3_2);
    
    int maxCount = max({count1, count2, count3});
    
    cout << "Максимальное количество костей: " << maxCount << endl;
    
    if (maxCount == count1) {
        cout << "Оптимально размещать на грани " << c << "×" << d << endl;
    } else if (maxCount == count2) {
        cout << "Оптимально размещать на грани " << c << "×" << e << endl;
    } else {
        cout << "Оптимально размещать на грани " << d << "×" << e << endl;
    }
    
    return 0;
}