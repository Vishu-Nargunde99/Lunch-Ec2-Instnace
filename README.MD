# How To Launch EC2 in AWS 
## Introduction
Welcome to our beginner-friendly guide on setting up and accessing EC2 instances in AWS! If you’re new to Amazon Web Services (AWS) or taking your first steps in cloud computing, this post is perfect for you.

In this hands-on guide, we’ll show you how to create your own virtual computer and connect to it step by step.

This is first github upload

Think of EC2 instances as computers in the cloud that can run your applications. By the end of this tutorial, you’ll know how to launch your own EC2 instance and access it from anywhere.

![ec2 image](https://miro.medium.com/v2/resize:fit:720/format:webp/0*9iUjIqntZZHAXfBN.png)

## Prerequisites
### AWS Acoount

Here is big advanatage of AWS you have pay only what you use
There are a free-tier services are avaialble in AWS. It is recommended to utilize the free-tier services; otherwise, you will be required to pay for the services based on your usage

Here are the step-by-step guide of Launch EC2 instance and Connection with Git

## Step 1 :
#### First of all, you need to log in to the AWS Management Console using your email ID and password. Click on the Sign In tab to open the login page.

![project screenshot](/Images/Console%20login%20dashboad.PNG)


## Step 2 :
#### First, on the login page, enter your registered email ID and click Next. This will take you to the password screen where you can enter your credentials to sign in.

![project screenshot](/Images/Login%20page.PNG)


## step 3 :
#### After entering your password, click on the Sign In button to continue.

![project screenshot](/Images/password.PNG)


## Step 4 :
#### Welcome to the AWS dashboard! Here, you can search for all AWS services and also launch an EC2 server


![project screenshot](/Images/aws%20dashboad.PNG)

## Step 5 :
#### On the dashboard, you will see a search bar. In the search bar, type "EC2" and then select the EC2 service from the results.

![project screenshot](/Images/ec2%20search.PNG)

## Step 6 :
#### This is the EC2 dashboard. On the right side of the dashboard, you’ll see a “Launch Instance” button. Click on it to start creating your instance. And you have to select version according to your requirments. 

![project screenshot](/Images/EC2%20Dashboard.PNG)

## Step 7 :
#### Now open the instance launching dashboard. First, give a name to the server/instance, then choose the Amazon Machine Image (AMI) according to your requirements, such as Amazon Linux, Ubuntu, etc. 

![project screenshot](/Images/instance%20db1.PNG)

## Step 8 :
#### Now, you need to choose an instance type based on your requirements. AWS offers a variety of instance types optimized for different use cases such as compute, memory, or storage. If you're just getting started, you’ll be glad to know that some instance types are eligible under the Free Tier, which means you can try them out without any charges. Feel free to select one of these Free Tieingr options if they suit your needs. 

![project screenshot](/Images/instance%20db2.PNG)

#### Next, select a key pair from the dropdown list. This key pair is used to securely connect to your EC2 instance later via SSH. If you don’t have one, you can create a new key pair right from this screen.

## Step 9 :
#### After that, you don’t need to make any changes in the network settings, since you're creating your first instance. The default settings will work just fine.

![project screenshot](/Images/instance%20db3.PNG)

## Step 10 :
#### After that, you can adjust the storage settings based on your server's requirements. Once you're ready, look to the right side of the screen and click the “Launch Instance” button — and just like that, your first EC2 instance is launching!

### 🎉 After Launching
### Once your instance is launched, click on "Instances" in the left-hand menu. There, you’ll see your newly created instance — and yes, it should be in the running state!

![project screenshot](/Images/instance%20db%204.PNG)


## Step 11 :
#### 🎉 Congratulations!
#### Your first EC2 instance has been successfully launched!

![project screenshot](/Images/after%20instance.PNG)


















