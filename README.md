# AWS Cloud Computing Practical Project

## Project Title
**Cloud Infrastructure Design, Storage Implementation, and Web Application Deployment Using AWS**

## Overview
This project demonstrates the design and implementation of cloud infrastructure using Amazon Web Services (AWS). It covers cloud storage, virtual networking, web application hosting, security configuration, and troubleshooting connectivity issues.

A simple Hello World web application is hosted on an Amazon EC2 instance, while Amazon S3 is used to store application files and static resources. AWS networking services are configured to provide secure and reliable access to the application.

## Objectives
- Understand the fundamentals of AWS cloud infrastructure.
- Create and configure cloud storage using Amazon S3.
- Design a Virtual Private Cloud (VPC) with public and private subnets.
- Deploy a web application using Amazon EC2.
- Configure security groups, route tables, and Internet Gateway.
- Identify and troubleshoot network connectivity problems.
- Verify application accessibility from different networks.

## Technologies and Services Used
- **Amazon EC2:** Hosts the Hello World web application.
- **Amazon S3:** Stores files and static resources.
- **Amazon VPC:** Provides an isolated virtual network.
- **Internet Gateway:** Enables Internet connectivity for public resources.
- **Security Groups:** Control inbound and outbound instance traffic.
- **Network ACLs:** Control traffic at the subnet level.
- **Route Tables:** Define network traffic paths.
- **Application Load Balancer:** Distributes incoming application requests when required.
- **VPC Reachability Analyzer:** Helps diagnose network connectivity issues.

## Project Modules

### Round 1 – Cloud Infrastructure Design
Study the AWS cloud environment and design the infrastructure required to host a web application.

### Round 2(i) – AWS Storage Implementation
Create an Amazon S3 bucket, configure its basic security settings, enable versioning if required, and upload sample files.

### Round 2(ii) – End-to-End AWS Solution
Configure a VPC, subnets, Internet Gateway, route tables, and security groups. Deploy the Hello World application on EC2 and test Internet connectivity.

### Round 3 – Data Integration and Deployment
Investigate the issue where the website is accessible from the office network but unavailable from a mobile network. Check EC2 status, security groups, Network ACLs, route tables, web server status, public IP configuration, and network restrictions. Correct the identified issue and retest connectivity.

### Round 4 – Viva Voce
Review AWS services, cloud architecture, storage, networking, security, deployment, and troubleshooting concepts.

## General Implementation Steps
1. Sign in to the AWS Management Console.
2. Create the required cloud storage and networking resources.
3. Launch and configure an EC2 instance.
4. Install a web server and deploy the Hello World page.
5. Configure the required network and security rules.
6. Upload sample files to Amazon S3.
7. Test the website from different networks.
8. Troubleshoot connectivity issues and verify the final configuration.

## Expected Output
- An Amazon S3 bucket containing uploaded files.
- A configured AWS virtual network.
- An EC2 instance hosting the Hello World website.
- Appropriate network and security configurations.
- Successful website access from authorized external networks after troubleshooting.

## Security Considerations
- Keep S3 Block Public Access enabled unless public access is explicitly required.
- Allow only necessary ports in security groups.
- Restrict SSH access to trusted IP addresses.
- Avoid storing AWS credentials in source code.
- Remove unused resources after testing to avoid unnecessary charges.

## Conclusion
This project provides practical experience in designing AWS cloud infrastructure, implementing storage, deploying a web application, and troubleshooting network connectivity. It demonstrates how AWS services work together to provide a secure, accessible, and maintainable cloud-based application.
