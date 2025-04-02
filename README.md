# Group-activity-6

#include <iostream>

using namespace std;

int main() {
    int num;

    cout << "Enter a positive number: ";
    cin >> num;

    int temp = num;
    int sum = 0;

    do {
        sum += temp % 10;
        temp /= 10;
    } while (temp > 0);

    cout << "The sum of the digits is: " << sum << endl;

    cout << num << " is ";
    if (num % 2 != 0) {
        cout << "not ";
    }
    cout << "divisible by 2" << endl;

    cout << num << " is ";
    if (num % 3 != 0) {
        cout << "not ";
    }
    cout << "divisible by 3" << endl;

    cout << num << " is ";
    if (num % 4 != 0) {
        cout << "not ";
    }
    cout << "divisible by 4" << endl;

    cout << num << " is ";
    if (num % 5 != 0) {
        cout << "not ";
    }
    cout << "divisible by 5" << endl;

    cout << num << " is ";
    if (num % 6 != 0) {
        cout << "not ";
    }
    cout << "divisible by 6" << endl;

    cout << num << " is ";
    if (num % 7 != 0) {
        cout << "not ";
    }
    cout << "divisible by 7" << endl;

    cout << num << " is ";
    if (num % 8 != 0) {
        cout << "not ";
    }
    cout << "divisible by 8" << endl;

    cout << num << " is ";
    if (num % 9 != 0) {
        cout << "not ";
    }
    cout << "divisible by 9" << endl;

    return 0;
}
