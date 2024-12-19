# Ezeigbo_Lita_aws_EC2_Project
This is the process of creating Security Group, launching EC2 Instance and deploying Apache web server


### Security Group Creation
Before creating my Securiry Group, i set my region to North Virginia.

I selected an EC2 instance, then selected Security Group. 

#### Security Group Name
I created a Security Group named oluchiestherezeigbo_litaSG.

#### Security Group Description
My Security Group description is to allow SSH and HTTP Traffic. 

#### Security Group VPC
I used lita_project_vpc for the VPC.

#### Security Group Inbound Rules
I added inbound rules to allow SSH traffic and allow it to be accessed from anywhere IPV4. 

I also allow for HTTP and allow it to be accessed from anywhere IPV4.

#### Security Group Outbound Rules
I added outbound rules to allow all traffic to go out.

#### Then i saved my security Group.

![Security Group](https://github.com/user-attachments/assets/1ea58d73-088d-4e3b-935c-c3972f1ed51f)

#### Security Group Created Successfully

![Ezeigbo_Instance](https://github.com/user-attachments/assets/352b1765-68b0-45c9-aea7-e1d261ef0c09)


### EC2 Instance Launching
I launched an instance and named it estherezeigbo_lita. 

#### Amazon Type
I chose Amazon linux 2 AMI (HVM). kernel 5.10.SSD volume type.

#### Instance Type Used
The Instance type used was t2.micro.

#### Key Pair Creation
I created a keypair named oluchiesrhernorah_lita_kp.

#### Instance Network Setting
For my Network setting, I selected the lita project vpc

#### EC2 Instance Subnet
I made my EC2 instance subnet public, so that it can be accessed from anywhere via the internet. 

#### EC2 Instance IP
I also enabled auto-assign public IP

#### EC2 Instance Security Group 
I selected the Security Group i created, named oluchiestherezeigbo_litaSG.

#### Then I Launched my Instance

![Instance](https://github.com/user-attachments/assets/60a1e5d2-87de-469e-8e17-c0392dccba74)


### Deploying Apache

#### Connecting to EC2
I connected to EC2 instance by selecting my instance and clicking connect

#### Key Pair
I located my key pair in my downloadeds. 

#### Command Prompt
Then I used the command prompt to connect my EC2 instance by typing 'cd Downlods' press Enter. 

To connect my Instance, I copied my instance example from my SSH and pasted it in my command prompt and pressed enter.

#### Apache
I also used the command prompt to install Apache web server

![Apache](https://github.com/user-attachments/assets/dc8b19ed-7c3c-472b-a792-890cd3c55634)


#### Apache was also tested
![Apachue Deployed](https://github.com/user-attachments/assets/afc1bea4-9578-48d5-acd2-5c8bc6c4f140)

#### My Public IPV4 Address
54.164.196.63
