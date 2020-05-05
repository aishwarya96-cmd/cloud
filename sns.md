
# **Simple Notification Service-SNS**

***Simple Notification Service is used to send an notification in form of message,email etc as soon as some event occurs.
eg if you want to get notification whenever you upload files in your s3 bucket or when ec2 instance has been created or ec2
server is down SNS is used.
SNS creates subscription i.e Sns works in publisher and subscriber model.
i.e one who send message is publisher and the one receives it is subscriber and channel between then is topic.
for e.g if we are sending notification through mail using s3 service then s3 is publisher and email is the subscriber.***

## **Below are the steps on how to use SNS service.**

Step 1: Click on services and type sns in search box.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns1.png)


Step 2:It will ask topic name.You can create multiple topics for various services where your messages will be stored 
like for e.g when ec2 is created you can send your message on topic1 and when s3 is used you can send message on topic2.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns2.png)


Step 3:Enter the display name of your choice.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns3.png)


Step 4:Scroll down and from access policy select everyone. 
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns4.png)


Step 5:Scroll down and select IAM roles and click on create new role.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns5.png)


Step 6:A new window will appear just click on allow and come back to the below page your IAM role will be displayed. 
Now click on create .
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns6.png)


Step 7:Now your topic is ready.Click on create subscription.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns7.png)


Step 8:Now click on the dropdown and select the mode of notification where you want to receive the message.
I have selected email and entered my email id.Click on create subscription.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns8.png)


Step 9:Now you will get a mail on the above entered email id for confirmation. click on confirm subscription.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns9.png)


Step 10:You will see the below message once you confirmed.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns10.png)


Step 11:Now go in SNS service again and you can see the status is now confirmed.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns11.png)


Step 12:Now open s3 service in another tab and click on your bucket. Go in the properties and select events.
Click on add notification
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns12.png)


Step 13: Tick on the checkbox as shown below and select sns in send to and the topic where you want to send your message.
Click on save
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns13.png)


Step 14: Now to test our sns service upload some file in s3 bucket.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns14.png)


Step 15: Immediately you will receive a mail will all the details.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/sns15.png)




