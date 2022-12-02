# isprimeusingbool
//To find whether a number is prime numbers
#include <iostream>
using namespace std;
 bool isprime(int n){
    for(int i=2;i<n;i++){
        if(n%i==0){
            return 0;
        }
        else{
            return 1;
        }
    }
}

int main() {
    // Write C++ code here
    int n;
    
    cout<<"enter a number";
    cin>>n;
    
    cout<<"is prime or not: "<<(isprime(n))<<endl; //1=isprime,0=not 
    
    return 0;
}
