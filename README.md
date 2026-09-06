# Highly Available & Auto-Scalable Website Hosting on AWS

## Project Overview
This project demonstrates how to host a highly available and auto-scalable website on Amazon Web Services (AWS).

The website is deployed on Amazon EC2 instances and traffic is distributed using an Application Load Balancer. Auto Scaling automatically manages the EC2 instances based on demand.

## Architecture
Internet → Application Load Balancer → Target Group → EC2 Instances → Website
![AWS Architecture Diagram](architecture-diagram.png)

## AWS Services Used
- Amazon VPC
- Amazon EC2
- Application Load Balancer (ALB)
- Target Group
- Auto Scaling Group (ASG)
- Launch Template
- Amazon S3
- IAM
- Security Groups

## Key Features
- Highly available website
- Load balancing using ALB
- Automatic scaling using Auto Scaling Group
- Secure access using IAM roles and Security Groups
- Website source code stored in GitHub

## Technologies Used
- HTML
- CSS
- JavaScript
- AWS
- Apache Web Server

## Project Objective
The main objective of this project is to deploy a reliable, highly available, and scalable website using AWS cloud services.

## Future Scope
- Add HTTPS using SSL/TLS
- Add Amazon CloudFront for faster content delivery
- Add Route 53 for custom domain management
- Implement monitoring using Amazon CloudWatch
- Add CI/CD pipeline for automatic deployment

## Author
Samruddhi Gade
