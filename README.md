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
![VPC](screenshots/01-vpc.png)

### Subnets
![Subnets](screenshots/02-subnets.png)

### Security Groups
![SG](screenshots/03-security-groups.png)

### EC2
![EC2](screenshots/04-ec2.png)

### Load Balancer
![ALB](screenshots/05-alb.png)

### Target Group
![TG](screenshots/06-target-group.png)

### RDS
![RDS](screenshots/07-rds.png)

### App Running
![App](screenshots/08-app-working.png)

### RDS SG
![RDS SG](screenshots/09-rds-sg.png)

## Result
Application is accessible through Load Balancer and database is secured in private subnet.
