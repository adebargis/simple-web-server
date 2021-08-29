# Simple Web Server
This repository contains a CloudFormation template that sets up your AWS account with:
* VPC
* 2 public subnets
* Internet Gateway (IGW)
* Route Table & associations
* 2 Security Groups (ELB & Web Server)
* Elastic Load Balancer (ELB)
* Auto Scaling Group (ASG)
* Launch Configuration
* 2 Auto Scaling Policies:
    * Scale out (with CW Alarm)
    * Scale in (with CW Alarm)

The only component that needs to be created manually is the EC2 SSH key (*Parameter Key: KeyPairName*)