#include<iostream>
using namespace std;
int main()
{
  int num,factorial=1;
  cout<<"Enter the number to find its factorial:";
  cin>>num;
  for(int a=1;a<=num;a++)
  {
  factorial=factorial*a;
  }
  cout<<"The factorial of"<<num<<"="<<factorial<<endl;
  return 0;
  }
