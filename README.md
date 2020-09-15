#include<iostream>
#include<cmath>
using namespace std;
void main()
{
	int a, c;
	double b, d;
	cin >> a;
	cout << "What root ?" << endl;
	cout << "1.sqrt" << endl;
	cout << "2.cbrt" << endl;
	cin >> c;
	switch (c)
	{ 
	case 1:
		 b = sqrt(a);
		 cout << a << "n^2 = m^2 => m^2 = " << a * a << "=> n^2 = " << a;
		 break;
	case 2:  
		 b = cbrt(a);  
		 break;
	
	default:
		cout << "SOSI NETU";
		break;
	}
}
