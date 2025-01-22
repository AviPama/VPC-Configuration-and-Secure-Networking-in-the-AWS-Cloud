# VPC-Configuration-and-Secure-Networking-in-the-AWS-Cloud

## Project Overview

This project demonstrates how to create and configure a Virtual Private Cloud (VPC) to understand network segmentation and secure networking in the cloud. The objective is to build a secure, scalable, and logically segmented network by leveraging public and private subnets. Key highlights include deploying resources in the private subnet, configuring a bastion host for secure access, and setting up security rules to isolate the private subnet from public internet traffic.

## Objectives

1. **Create a VPC**:
   - Define the IP address range using CIDR blocks.
   - Create both public and private subnets within the VPC.

2. **Deploy Resources in the Private Subnet**:
   - Launch EC2 instances or other resources in the private subnet.
   - Ensure resources are inaccessible directly from the internet.

3. **Configure a Bastion Host**:
   - Deploy a bastion host in the public subnet.
   - Configure the bastion host for secure remote access (SSH) to resources in the private subnet.

4. **Implement Security Rules**:
   - Apply security group rules to allow only necessary traffic.
   - Isolate the private subnet from direct public internet access while allowing necessary outbound communication.

## Architecture Diagram

![image](https://github.com/user-attachments/assets/579966af-b36d-4518-aced-76217266dfc9)


## Prerequisites

- AWS Account.
- Basic knowledge of VPC, subnets, security groups, and SSH.
- Installed AWS CLI and configured with necessary credentials.
- Terraform for infrastructure as code.
