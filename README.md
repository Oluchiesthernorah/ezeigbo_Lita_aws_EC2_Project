# Ezeigbo_Lita_aws_EC2_Project
This is the process of creating Security Group, launching EC2 Instance and deploying Apache web server

### Security Group Creation
Before creating my Securiry Group, i set my region to North Virginia.
I selected an EC2 instance, then Security Group. I created a Security Group name oluchiestherezeigbo_litaSG.
My Security Group description is to allow SSH and HTTP Traffic. I used lita_project_vpc for the VPC.
I added inbound rules to allow SSH traffic and allow it to be accessed from anywhere IPV4. I also allow for HTTP and allow it to access from anywhere IPV4.
I added outbound rules to allow all traffic to go out.
Then i saved my security Group.

### Launch EC2 Instance
I launched and instance and named it estherezeigbo_lita. I chose Amazon linux 2 AMI (HVM). kernel 5.10.SSD volume type.


### HTTPD Creation

