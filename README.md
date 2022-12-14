Question:To print the elements in the array and the size of an array
code:
#include <iostream>
using namespace std;

int main()
{
  
    int b;
    int m[4]={0,1,2,3};
    
    for(b=0;b<4;b++)
    cout<<m[b]<<" element in the is array  "<<m[b]<<endl;
    cout<<endl;
    cout<<m[2]<<" index m[2]";
    b=sizeof(m);
    cout<<endl<<b<<" size of array";
    int c=2,d=5,e=6;
    int f=sizeof(c)+sizeof(d)+sizeof(e);
    cout<<endl<<f<<" size of integer";
  
    return 0;
}
