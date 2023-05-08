# c-program
Write a program to find out sum of all digits of given number.
         [Use while loop]

PROGRAM :

#include<stdio.h>
#include<conio.h>
#include<iostream.h>
void main()
{
   	int i,sum=0,num;
   	clrscr();
   	cout<<"Enter the number:";
   	cin>>num;
   	while(num>0)
   	{
       		i=num%10;
       		sum=sum+i;
       		num=num/10;
   	}	
   	cout<<"Sum="<<sum;
   	getch();
}	
