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

# **Simple Storage Service-S3**
- *S3 has a simple web services interface that we can use to store and retrieve any amount of data, at any time, from anywhere on the web.*
- *S3 is secure,durable and highly scalable.S3 provides 99.999999999% durability of objects.*
- *Within the S3 service we create 'Buckets'. Buckets are used to store object based files and can be thought of as folders.
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
- *When we create a security group, it has no inbound rules. Therefore, no inbound traffic originating from another host to your instance is allowed until you add inbound rules to the security group.

## Outbound rule
- *Outbound rules filter traffic passing from the local computer to the network based on the filtering conditions specified in the rule.* 
- *By default a security group includes an outbound rule that allows all outbound traffic.*
  *We can remove the rule and add outbound rules that allow specific outbound traffic only.*


