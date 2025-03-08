# Group-activity-2.
#include <iostream>
using namespace std;

int main() {
    int num;
    cout << "Please enter an integer: ";
    cin >> num;

    string evenOdd;
    if (num % 2 == 0) {
        evenOdd = "even";
    } else {
        evenOdd = "odd";
    }

    string sign;
    if (num > 0) {
        sign = "positive";
    } else if (num < 0) {
        sign = "negative";
    } else {
        sign = "zero";
    }

    cout << "The number " << num << " is " << evenOdd << " and " << sign << endl;

    return 0;
}
