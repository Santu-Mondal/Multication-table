#include<iostream>
#include<conio.h>
using namespace std;
int main()
{
    int num;
    cout << "Enrer any integer : ";
    cin>> num;
    for(int i =1;i<=10 ;i++)
    {
        cout<< num << "X" <<i <<" = "<<(num*i)<<endl;

    }
getch();
}
