#include<bits/stdc++.h>
using namespace std;
// ************euclid's algorithm using recursion*************
int gcd(int a, int b)
{
    if(b==0)
    return a;
    else 
    return gcd(b, a%b);
}
int main(){
    int a, b, hcf;
    cout<<"enter the numbers"<<endl;
    cin>>a>>b;
    cout<<gcd(a, b);
    return 0;
}