// The following below is a C++ Program about "Cookie Recipe" made by Christopher Wilson

#include <iostream>
using namespace std;

int main() {
	double sugar = 1.5;
	double butter = 1.0;
	double flour = 2.75;
	int cookies;

	cout << "Enter the amount of cookies desired to be made. ";
	cin >> cookies;

	double sugarNeeded = (sugar / 48) * cookies;
	double butterNeeded = (butter / 48) * cookies;
	double flourNeeded = (flour / 48) * cookies;

	cout << "For " << cookies << " cookies, you will need:" << endl;
	cout << sugarNeeded << " cups of sugar" << endl;
	cout << butterNeeded << " cups of butter" << endl;
	cout << flourNeeded << " cups of butter" << endl;

	return 0;

}
