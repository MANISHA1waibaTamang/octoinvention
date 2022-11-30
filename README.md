enter values of length and breadth of a rectangle from user and check if it is square or not.
```cpp
#include<iostream>
using namespace std;
int main()
{
    int l,b;
    cout<<"enter a length:";
    cin>>l;
    cout<<"enter a breadth:";
    cin>>b;
    if(l==b)
    {
        cout<<"it is square";
    }
    else
    {
        cout<<"it is rectangle";
    }
}
```
