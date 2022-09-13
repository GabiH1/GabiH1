#include <iostream>
#include <conio.h>
using namespace std;
int suma(int a,int b);
int diferenta(int a,int b);
int maxim(int a,int b);
int produs(int a,int b);
int impartire (int a,int b);
int main()
{
    int x,y,s,d,m,p,i;
    cout<<"x="; cin>>x;
    cout<<"y="; cin>>y;
    s=suma(x,y);
    cout<<"suma="<<s<<endl;;
    d=diferenta(x,y);
    cout<<"diferenta="<<d<<endl;
    m=maxim(x,y);
    cout<<"maximul="<<m<<endl;
    p=produs(x,y);
    cout<<"produs="<<p<<endl;
    i=impartire(x,y);
    cout<<"cutul="<<i;
    getch();
}
int suma(int a,int b)
{
    int c;
    c=a+b;
    return c;
}
int diferenta(int a,int b)
{
    int c;
    c=a-b;
    return c;
}
int maxim(int a,int b)
{
    if (a<b)
        return b;
    else
        return a;
}
int produs(int a,int b)
{
    int c;
    c=a*b;
    return c;
}
int impartire (int a,int b)
{
    int c;
    c=a/b;
    return c;
}
