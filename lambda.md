# **Lambda**

- ***Lambda is a serverless computing platform provided by aws.***
- ***Lambda function can store multiple codes without any costing.***
- ***It will charge you only at the time of execution of code.***
- ***Whenever you run your code it will automatically calculaute CPU,RAM and multiply the amount of time for which the code is run and charge CPU,RAM only for that time period.***
- ***It provides scalibilty i.e automaticallly calculates the cost required in case you update your code by increasing or decreasing cpu,ram or time.***
- ***It provides parallelization i.e at each execution time if their are multiple requests coming to lambda it automatically manages each request.***

## **Below are the steps for creating lambda function.**

Step 1: Click on services and select lambda or type in the search box.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda1.png)

Step 2:Click on create function.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda2.png)

Step 3: You can either select author from scratch or use a blueprint.Blueprint means they have already provided the code.
lets select use a blueprint.Type the code name which you need to run.Example lets use hello-world.
As you can see hello-world code is available in two languages you can choose any of your choice.I am using python. 

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda3.png)

Step 4: Enter the function name of your choice.Now if lambda function needs to communicate with aws other services it requires IAM role
so for that click on use an existing role and they have bydefault provided you with IAM role. click on the drop down and select the default role.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda4.png)

Step 5: Scroll down you will see the code.you can make changes if you want.Once done click on create function.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda5.png)

Step 6: Lambda function has been created.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda6.png)

Step 7:Alternatively if you choose author from scratch you need to proivde the code and then run.Click on author from scratch
then enter the function name.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda14.png)

Step 8: later click on dropdown and select the language of your choice.Then click on create function.
![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda15.png)

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda16.png)

Step 9:lets continue with our blueprint hello world code. Go back and click on the funcion name 

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda7.png)

Step 10:Scroll down you will see the code you can make changes in the code if you want.If you made any changes click on save and then on test.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda8.png)

Step 11:Enter the event name and you can change the key values e.g i have entered vita in place of value1 and so on.. and click on create.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda9.png)

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda10.png)

Step 12:As you can seen in the below image your event name has been added.Click on your event name.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda11.png)

Step 13:Now its time to run the code.click on test.As seen below execution result :succeeded message will be displayed.Click on the details to see the output.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda12.png)

Step 14:As you see the changes made in the program as vita,dac,dbda are displayed at the output.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/lambda13.png)

# **Lambda driven Automation service (Trigger lambda function using s3 service)**

Step1: Click on services and select S3.

Step2: Create a bucket and click on bucket name.

Step 3:You will see the below window.Click on properties.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/s3lambda1.png)

Step 4:Scroll down and Select Events. Further Click on Add notification.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/s3lambda2.png)

Step 5: Enter the name and tick on the option as shown below.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/s3lambda3.png)

Step 6: Click on dropdown of send to and select lambda function and also select lambda function name .By this whenever you upload anything on s3 bucket selected lambda function will get trigger automatically.Later click on save.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/s3lamda4.png)

Step 7:Below is the output of lambda function which was already created. 

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/s3lamda5.png)

Step 8:Now make some changes in the code and save it.Dont click on test as we need to see wheither the logs are created automatically by s3 or not.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/s3lamda6.png)

Step 9:Now again go in s3 bucket and upload any text file .

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/s3lamda7.png)

Step 10:Now go in the cloudwatch service of aws and click on log groups to check your logs.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/s3lamda8.png)

select your lambda function.Here we have created function with name demo.

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/s3lamda9.png)

Step 11:As you can see the changes made are automatically displayed in the log as we have triggered lambda from s3 .

![image](https://github.com/aishwarya96-cmd/cloud/blob/images/images/s3lamda10.png)




















