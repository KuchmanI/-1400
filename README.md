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
