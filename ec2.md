
## **Elastic Compute Cloud-EC2**
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

### Below are the steps for creating EC2 instance.

Step 1: Click on the services and select EC2 instance.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec21.png)

Step 2: After the step1 the below page will be displayed click on launch instance.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step2.jpg)

Step 3: You can choose any of the operating system of your choice.Here I am using Linux instance
Click on the select or you can also search the instance in the search box.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step3.jpg)

Step 4:Select t2.miro as it is free tier others may charge you more and then click on next:configure instance details.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step4.jpg)

Step 5: Don’t change anything just leave it as default and click on Next:Add storage

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step5.jpg)

Step 6: The default storage size is 8 GB you can increase it till 30 GB as per your choice.Now click on Next:Add tags.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step6.jpg)
Step 7:Click on add tag as show in the below image.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step7.jpg)

Step 8:Select the key value pair of your choice as it will help you to identify your instance.

later click on Next:configure security group.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step8.jpg)

Step 9: Security group controls the traffic for your instance.Select the security group name of your choice .Bydefault TCP port no 22 is selected for linux .You can add your rules if you want.
Now click on Review and launch.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step9.jpg)

Step 10:You can check your details and edit if you want to change or add anything.Later click on Launch.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step10.jpg)

Step11: click on dropdown and select create a new key pair and enter the key pair name.
Click on download key pair.This will download your private key.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step11.jpg)

Step 12: Save the key as it will be needed further.Later click on launch instance.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step12.jpg)

Step 13: Click on view instance.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step13.jpg)

Step14: Now your instance is ready as you can see the status is running.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/ec2-step14.jpg)
