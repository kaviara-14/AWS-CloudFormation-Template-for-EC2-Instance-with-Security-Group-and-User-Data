# AWS CloudFormation Template for EC2 Instance with Security Group and User Data

This repository contains an AWS CloudFormation template that provisions an Amazon EC2 instance with an associated Security Group. The template also includes user data that automatically installs and configures a basic Apache HTTP server on the instance upon launch.

## Features
***EC2 Instance:*** Launches an Amazon EC2 instance with a specified instance type (default: t2.micro).
**Security Group:** Creates a Security Group that allows inbound SSH (port 22) and HTTP (port 80) traffic from any IP address.
**User Data:** Installs Apache HTTP server on the instance and deploys a simple "Welcome" webpage.
