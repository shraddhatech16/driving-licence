# driving-licence
//eligibility criteria for driving licence
#include<iostream>
using namespace std;
int main()
{
   int age;
   cout<<"Enter your age :  ";
   cin>>age;

   if(age>=18)
   {
       cout<<"\n You will get the driving licence";
   }
   else
   {
       cout<<"\n Sorry you will not get the driving licence";
   }
   return 0;
}
