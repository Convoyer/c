#include <iostream>
#include <windows.h>
#include <cmath>
using namespace std;
int n;
char choose;
int choose1, x, m; 
int a;
int main() {
	do 
	{
		cout<<"Enter number X"<<endl;
		cin>>x;
		cout<<"Enter number in degree n"<<endl;
		cin>>a;
			m=1;
			int n=a;
		while(n--) m*=x;
		if (a>=0) cout<<"Number X in degree n "<<m<<endl;
		if (a<0) cout<<"Number X in degree n "<<"1/"<<m<<endl;
	cout<<"Czy chcesz kontynuowac? [T/N]"<<endl;
	cin>>choose;
	
}
	while (choose=='T'||'t');
	
	
	return 0;
}
