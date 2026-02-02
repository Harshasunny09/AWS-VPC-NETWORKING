# AWS VPC Networking Project

This project demonstrates hands-on AWS networking by building a custom Virtual Private Cloud (VPC) from scratch. The goal was to understand how AWS networking works internally instead of relying on default console settings.

## Project Overview
In this project, I created and configured a custom VPC using AWS CloudShell and the AWS CLI. The setup focuses on core networking components such as CIDR planning, subnets, internet gateways, and route tables to enable public internet access.

## What I Built
- Created a custom VPC with a /16 IPv4 CIDR block
- Designed and created subnets within the VPC
- Attached an Internet Gateway to the VPC
- Configured route tables to allow outbound internet traffic
- Enabled public IP auto-assignment for resources in the subnet
- Verified connectivity using AWS Resource Map and CLI outputs

## AWS Services Used
- Amazon VPC
- Subnets
- Internet Gateway
- Route Tables
- AWS CloudShell
- AWS CLI

## Key Learnings
- A subnet is not public unless its route table allows internet traffic
- Attaching an Internet Gateway alone does not provide connectivity
- Proper CIDR planning is critical for scalable network design
- Using the CLI gives deeper visibility into how AWS networking works

## Purpose
This project was completed as part of hands-on learning to strengthen AWS networking fundamentals while preparing for the AWS Solutions Architect Associate certification.

## Author
Harshavardhan Sagiri
