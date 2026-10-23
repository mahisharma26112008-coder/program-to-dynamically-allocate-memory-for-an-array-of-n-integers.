# program-to-dynamically-allocate-memory-for-an-array-of-n-integers.

#include<iostream>
  using namespace std;
 int main(){
     int n;
     cout<<"enter size";
     cin>>n;

     int *p=new int[n];

     cout<<"enter "<<n<<"elements"<<"\n";
     for(int i=0;i<5;i++){
         cin>>p[i];
     }

     cout<<"elements are of array : "<<"\n";
     for(int i=0;i<5;i++){
         cout<<p[i]<<" ";
     }

     delete p;

     return 0;

 }
