# Ezeigbo_Lita_aws_EC2_Project
This is the process of creating Security Group, launching EC2 Instance and deploying Apache web server

### Security Group Creation
Before creating my Securiry Group, i set my region to North Virginia.

I selected an EC2 instance, then Security Group. 

I created a Security Group name oluchiestherezeigbo_litaSG.

My Security Group description is to allow SSH and HTTP Traffic. 

I used lita_project_vpc for the VPC.

I added inbound rules to allow SSH traffic and allow it to be accessed from anywhere IPV4. I also allow for HTTP and allow it to access from anywhere IPV4.

I added outbound rules to allow all traffic to go out.

Then i saved my security Group.

### Launch EC2 Instance
I launched and instance and named it estherezeigbo_lita. 

I chose Amazon linux 2 AMI (HVM). kernel 5.10.SSD volume type.

The Instance type used was t2.micro.

I created a keypair named oluchiesrhernorah_lita_kp.

For my Network setting, I selected the lita project vpc

I made my EC2 instance subnet public, so that it can be accessed from anywhere via the internet. 

I also enabled auto-assign public IP

I selected the Security Group i created then Launched my Instance

#### Connect to EC2 Instance 
I conneced to EC2 instance by selecting my instance and clicking connect

### Deploying Apache
I located my key pair in my downloadeds. Then I used the command prompt to connect my EC2 instance by typing 'cd Downlods' press Enter. I copied my instance example from my SSH and pasted it in my command prompt and pressed enter.
I also used the command prompt to install Apache web server




