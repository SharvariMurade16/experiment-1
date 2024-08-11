# Experiment-1
## Aim-
Downloading and installing vs code,(Hello world and calculator program).
## Software used-
Vs code and Online compiler.
## Theory-
We study about vs code, how to download and install it and use it for programming.These programs introduce fundamental concepts in C++ programming.
Hello World-Hello World programs are traditionally used to demonstrate how the coding process works as well as to ensure that a language or system is working properly.
Calculator-Calculator is a program that help us to enable various arithematic opertations like addition,subtraction,divison and multiplication.
## Code-
1)-
//sharvari murade
//23070123088
//entc b1

#include <iostream>
using namespace std;

int main(){
    cout<<"Hello World";
    return 0;
}
### Output-
![4F0FC88C-B862-4A6E-BF14-00D14F6D2F47](https://github.com/user-attachments/assets/db34ee26-a006-4b0a-977a-28b65e20860e)
2)-
//sharvari murade
//23070123088
//entc b1

#include <iostream>
using namespace std;

int main() {
  int a,b;
  cout<<"Welcome to calculator"<<endl;
  cout << "Enter first number: ";
  cin >> a;
  cout << "Enter second number: ";
  cin >> b;
    cout<<"The sum of your digits is = "<<(a+b)<<endl;
    cout<<"The difference of your digits is = "<<(a-b)<<endl;
    cout<<"The product of your digits is = "<<(a*b)<<endl;
    if(b!=0){
        cout<<"The division of your digits is = "<<(a/b)<<endl;
    } else { 
        cout<<"divide by 0 error";
    }
  return 0;
}





