# Steps for Writing and Compiling C++ on Linux.

### **Step1:** Run the below command to install gcc compiler.
```
$ sudo yum -y install gcc-c++
```
### **Step2:** To check gcc version and if it is installed properly.
```
$ gcc –version or gcc –v
```
### **Step3:** Now go to that folder where you will create C/C++ programs. I am creating my programs in c++ directory.
```
$ mkdir c++
$ cd c++/
```
### **Step4:** Now create a cpp file inside  c++ directory using below command.Here for example I am creating a file 1st.cpp
```
$ vi 1st.cpp
```
### **Step4:** Add the code of your choice inside the file .For Example swapping of two numbers.
```
#include <iostream>
using namespace std;

int main()
{
    int a = 5, b = 10, temp;

    cout << "Before swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    temp = a;
    a = b;
    b = temp;

    cout << "\nAfter swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    return 0;
}
```
### **Step5:** Use the below command to compile the code.
```
g++ 1st.cpp -o 1st
```
### **Step6:** Run the code using below.
```
./1st
```
 ### **Output:**
![swap](https://user-images.githubusercontent.com/63540937/80867258-88cc0100-8cbd-11ea-8951-919c54290e38.jpg)



### **Below are few more examples:**
1.[Addition of two numbers](https://github.com/aishwarya96-cmd/cloud/blob/aishwarya/first.md)

2.[Calling of display1 function from display2 function](https://github.com/aishwarya96-cmd/cloud/blob/aishwarya/second.md)

3.[Display output using Virtual function](https://github.com/aishwarya96-cmd/cloud/blob/aishwarya/third.md)

4.[Concatenation of two strings](https://github.com/aishwarya96-cmd/cloud/blob/aishwarya/fourth.md)



