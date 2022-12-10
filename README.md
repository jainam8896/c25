# c25#include<iostream.h>

#include<conio.h>

#include<stdio.h>

#include<stdlib.h>

void main()

{

	clrscr();

	cout.setf(ios::hex, ios::basefield);

	cout.setf(ios::showbase);

	cout<<150<<endl;

	cout.unsetf(ios::showbase);

	cout<<150<<endl;

	double n=4.5678;

	cout<<setprecision(3);

	cout<<n;

	getch();

}
