# AWS Web Application Architecture Project

## Overview
This project shows a multi-tier web application architecture built on AWS.
It includes a web server, a relational database, load balancing, and basic monitoring.

---

## Architecture Components
- Amazon EC2 (Amazon Linux, NGINX, PHP)
- Amazon RDS (MySQL)
- Application Load Balancer
- Amazon CloudWatch (monitoring and alarms)

---

## Architecture Flow
User → Application Load Balancer → EC2 (Web Server) → RDS (MySQL)

---

## Functionality
- Deployed a dynamic web application connected to RDS
- Configured secure communication between EC2 and database
- Implemented load balancing for traffic distribution
- Configured CloudWatch alarm for CPU monitoring

---

## Configuration Steps


### EC2 Setup
- Launched an Amazon Linux EC2 instance
- Installed and configured NGINX and PHP

### RDS Setup
- Created a MySQL RDS instance
- Configured security groups to allow access from EC2
- 
### Database Integration
- Connected EC2 instance to RDS database
- Created database and tables
- Inserted and queried data
  
### Web Application
- Created a simple PHP application to display data from the database

### Load Balancer
- Created an Application Load Balancer
- Configured target group and health checks
- Verified application availability using the Load Balancer DNS  
- Confirmed instance health status in the target group  
  
### Monitoring
- Configured a CloudWatch alarm for CPU utilization

---

## Screenshots

### RDS Instance
![RDS](screenshots/rds-instance.png)

### Database Connection
![Connection](screenshots/rds-connection.png)

### Table Data
![Table](screenshots/rds-table.png)

### Web App Output
![WebApp](screenshots/webapp-rds.png)

### Load Balancer
![ALB](screenshots/alb-created.png)

### Target Group
![Target](screenshots/target-group.png)

### CloudWatch Alarm
![Alarm](screenshots/cloudwatch-alarm.png)

---

## Key Skills Demonstrated
- Basic cloud architecture design
- EC2 and Linux server configuration
- RDS database setup and integration
- Load balancing using Application Load Balancer
- Monitoring using CloudWatch
- Security group configuration and access control
---

## Author
Jelena
