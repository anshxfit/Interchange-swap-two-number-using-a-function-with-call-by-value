# Interchange-swap-two-number-using-a-function-with-call-by-value
#include<iostream.h>
#include<conio.h>
void swap(int a, int b){
int temp;
temp=a;
a=b;
b=temp;
cout<<"\n inside swap function(after swapping):\n"r;
cout<<"a=<<"<<a<<"\n";
cout<<"b=<<"<<b<<"\n
}
void main()
{
clrscr();
int num1, num2;
cout<<"enter first mumber:";
cin>>num1;
cout<<"enter second number:";
cin>>num2;
cout<<"\n before calling swap Function:\n";
cout<<"num1="<<num1<<"\n";
cout<<"num2="<<num2<<"\n";
swap(num1, num2);
cout<<"\n after cailing swap Function:\n";
cout<<"num1="<<num1<<"\n";
cout<<"num2="<<num2<<"\n";
getch();
}
