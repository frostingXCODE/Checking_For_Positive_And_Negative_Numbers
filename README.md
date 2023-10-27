# Checking_For_Positive_And_Negative_Numbers
#include <iostream>
using namespace std;

int x;

void CheckingForPositiveAndNegativeNumbers() {

	cout << "Enter a number: ";
	cin >> x;

	if (x > 0) {
		cout << x << " is possive number! \n";
	}
	else if (x < 0) {
		cout << x << " is negative number! \n";
	}
}

int main() {
	CheckingForPositiveAndNegativeNumbers();
}
