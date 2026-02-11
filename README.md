#include <iostream>
using namespace std;

int main()
{
    double celsius;
    double fahrenheit;

    // 1. Get input from user
    cout << "Enter temperature in Celsius: ";
    cin >> celsius;

    // 2. Convert to Fahrenheit
    fahrenheit = (celsius * 1.8) + 32;

    // 3. Show the result
    cout << celsius << "°C = " << fahrenheit << "°F" << endl;

    // 4. Bonus - temperature messages
    if (celsius < 0) {
        cout << "Freezing!" << endl;
    }
    else if (celsius > 30) {
        cout << "Hot!" << endl;
    }
    // You can also add an else if (celsius >= 0 && celsius <= 30) → "Nice weather" if you want

    return 0;
}
