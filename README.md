# fibonacci series
 a program which show fibonacci series of a number which is enter by user.
 #include<iostream>
using namespace std;
int main()
{
int a=0,b=1,next=0,i=2,n;
cout<<"Enter a number to find Fibonacci series"<<endl;
cin>>n;
cout<<a<<"\t"<<b<<"\t";
while(i<n)
{
next=a+b;
cout<<next<<"\t";
a=b;
b=next;
i++;
}
return 0;
}
