# Dec





# Basic calculator using cpp




# program starts her 

#include<iostream>
using namespace std;
int main()
{
int i,j;
float r,o,m;
cout<<"Enter two numbers =";
cin>>r>>o;
cout<<"Operation that is available to perform  "<<endl;
cout<<" 1.Addition \n 2.Subtraction \n 3.Multiplication \n 4.Division \n  "<<endl;
cout<<"The operation that you like to perfrorm = ";
cin>>j;
switch(j)
{
case 1 :
        cout<<r+o<<endl;
        m=r+o;
        cout<<m;
        break;
case 2 :
        cout<<r-o<<endl;
        m=r+o;
        cout<<m;
        break;
case 3 :
        cout<<r*o<<endl;
        m=r*o;
        cout<<m;
        break;
case 4 :
        cout<<r/o<<endl;
        m=r/o;
        cout<<m;
        break;

case 5:
      cout<<"Invalid choice ";
}
return 0;
}
