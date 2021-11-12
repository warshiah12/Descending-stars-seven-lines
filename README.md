# Descending-stars-seven-lines
# FOR LOOP
#include<iostream>
using namespace std;
int main()
{
	for (int i = 1; i <= 7; i++) //using nested for loop
	{
		for (int j = i; j <= 7; j++)  //inner for loop
		{
			cout << "*";  
		}
		cout << endl;
	}
	return 0;
}
