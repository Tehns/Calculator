#include <iostream>
using namespace std;
//Дарова
int main()
{
    setlocale(LC_ALL, "Rus");

    double num1, num2;
    char operation;

    cout << "Введите первое число: ";
    cin >> num1;

    cout << "Введите второе число: ";
    cin >> num2;

    cout << "Введите операцию (+, -, *, /): ";
    cin >> operation;

    switch (operation) 
    {
    case '+':
        cout << "Результат: " << num1 + num2 << endl;
        break;
    case '-':
        cout << "Результат: " << num1 - num2 << endl;
        break;
    case '*':
        cout << "Результат: " << num1 * num2 << endl;
        break;
    case '/':
        if (num2 != 0) 
        {
            cout << "Результат: " << num1 / num2 << endl;
        }
        else 
        {
            cout << "Делить на ноль нельзя" << endl;
        }
        break;
    default:
        cout << "Такой операции нету" << endl;
        break;
    }
}
