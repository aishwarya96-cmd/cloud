

# **Cloud computing**

 Cloud computing means computing resources as rent.It is the on-demand availability of computer system resources.
There are 3 types of clouds :
1. Public cloud-
*This can be used by anybody like company,school,indiviual.*
2. Private cloud-
*This is owned by the particular organisation and only that members of that organisation can access it.*
3. Hybrid- 
*This is combination of public and private.It means public parts and private parts access is given according to the need.*

## Advantages of cloud-
1. It charges on the basis of amount of time we use it so it is cost saving.
2. It provides free internet with great speed.
3. It provides free electricity.
4. High storage capacity.

# **Elastic Compute Cloud-EC2**
- *EC2 is the most used AWS service. It lets users create virtual machines of their own choice of configurations.*
- *It lets users launch and manage server instances, at any time and for as long as one needs.*
- *EC2 enables on-demand, scalable computing capacity in the AWS cloud.*
- *It enables you to build and run applications faster. You can use EC2 in AWS to launch as many virtual servers as you need.*
- *Key and Value pairs are used to identify the particular instance while it is running.*

## **Benefits of EC2**
### 1.Auto-scaling:
- *Auto-scaling is basically providing resources according to the demand. They either scale up or scale down corresponding to the increase or decrease in demand.*
### 2.Pay-as-you-go:
- *You will be charged by the hour, and you have to pay only for what you have used.*
- *e.g A company, XYZ might be using 100 servers normally, and on Mondays it scales down to 50 servers. So, it only has to pay for 50 servers those days, not the usual fee for the usage of 100 servers.*


# **Simple Storage Service-S3**
- *S3 has a simple web services interface that we can use to store and retrieve any amount of data, at any time, from anywhere on the web.*
- *S3 is secure,durable and highly scalable.S3 provides 99.999999999% durability of objects.*
- *Within the S3 service we create 'Buckets'. Buckets are used to store object based files and can be thought of as folders.*
- *Bucket names are common throughout web,hence it must be very unique.*
- *S3 stores data as objects within buckets. An object consists of a file and optionally any metadata that describes that file.*
- *To store an object in  S3, the we can upload the file that they wants to store in the bucket.*
- *The total volume of data and number of objects you can store are unlimited.* 
- *Using S3 we can also launch static web pages by configuring the bucket for the same. Once configured you can make basic HTML pages using the static URL.*

# **Security Group**
- *A security groups acts as a virtual firewall that controls the traffic for one or more instances.*
- *When we launch an instance we can specify one or more security groups; otherwise we can use the default security group.*
- *After that we can set up ports and protocols, which remain open for users and computers over the internet.*
- *Security Groups controls both inbound and outbound traffic.*
- *For each security group, we add rules that control the inbound traffic to instances, and a separate set of rules that control the outbound traffic.* 

## Inbound rule
- *Inbound rules filter traffic passing from the network to the local computer based on the filtering conditions specified in the rule.*
- *When we create a security group, it has no inbound rules. Therefore, no inbound traffic originating from another host to your instance is allowed until you add inbound rules to the security group.*

## Outbound rule
- *Outbound rules filter traffic passing from the local computer to the network based on the filtering conditions specified in the rule.* 
- *By default a security group includes an outbound rule that allows all outbound traffic.*
  *We can remove the rule and add outbound rules that allow specific outbound traffic only.*
  
 # **Relational Database Service-RDS**
- *RDS is a service which provides database connectivity through the Internet.*
- *RDS is used to set up, manage and scale a relational database instance in the cloud.* 
- *A database administrator can create, configure, manage and delete an  RDS instance, which is a cloud database environment, along with the compute and storage resources it uses.*
- *RDS adds support for major and minor versions of database engines over time, and an admin can specify an engine version when he or she creates a database instance.*
- *RDS is Cost-effective,you just pay for what you use, and nothing more. No upfront payment is needed, just the monthly usage payment.*
- *It just takes a few minutes to scale your infrastructure up or down.*
- *There are six database engines which RDS provides, and they are:*
1. *Amazon Aurora*
2.*PostgreSQL*
3.*MySQL*
4.*MariaDB*
5.*Oracle Database*
6.*Microsoft SQL Server*
- *Once the database is created and the status is changed to Available you need to connect it with your local MySQL shell and can perform operations.*

# **Writing and Compiling C++ on Linux**

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



