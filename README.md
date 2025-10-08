3.	Write a program to illustrate default constructor, parameterized constructor and copy constructor, destructors for a class. 
DEFAULT CONSTRUCTOR:
#include <bits/stdc++.h>
using namespace std;

class Employee {
  public:
    int age;
  
    // Default constructor.
    Employee() {
      /* Data member is defined with the help of the 
      default constructor.*/
      age = 50;
    }
};

int main() {
  // Object of class Employee declared.
  Employee e1;
  // Prints value assigned by default constructor.
  cout << e1.age;
  return 0;
}

OUTPUT
50
--------------------------------
Process exited after 0.06815 seconds with return value 0
Press any key to continue . . .
