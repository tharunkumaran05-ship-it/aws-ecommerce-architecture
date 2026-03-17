# Highly Available E-Commerce Architecture on AWS

## Project Description
This project demonstrates a highly available and fault-tolerant e-commerce architecture built using AWS services.

## Services Used
- VPC
- Subnets (Public & Private)
- Internet Gateway
- NAT Gateway
- EC2
- Application Load Balancer
- Target Group
- Auto Scaling (optional)
- RDS (MySQL)
- Security Groups

## Architecture
![Architecture](architecture.png)

## Screenshots

### VPC
![VPC](01-vpc.png)

### Subnets
![Subnets](02-subnets.png)

### Security Groups
![SG](03-security-groups.png)

### EC2
![EC2](04-ec2.png)

### Load Balancer
![ALB](05-alb.png)

### Target Group
![TG](06-target-group.png)

### RDS
![RDS](07-rds.png)

### App Running
![App](08-app-working.png)

### RDS SG
![RDS SG](09-rds-sg.png)

## Result
Application is accessible through Load Balancer and database is secured in private subnet.