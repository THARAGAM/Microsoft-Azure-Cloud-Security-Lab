# Microsoft Azure Cloud Security Lab

## Overview

This project demonstrates the configuration and security of a Microsoft Azure cloud environment through a hands-on virtual lab.

The project focuses on fundamental cloud infrastructure, networking, identity and access management, and security controls within Microsoft Azure.

The objective was to gain practical experience designing and securing cloud resources while applying core cybersecurity and cloud security principles.

---

## Objectives

- Configure Microsoft Azure cloud resources
- Create and configure an Azure Virtual Network
- Configure subnets for network segmentation
- Configure network security controls
- Apply access control principles
- Understand Azure resource management
- Configure secure communication between cloud resources
- Explore cloud identity and access management
- Apply the principle of least privilege
- Document and test the cloud environment

---

## Azure Environment

| Component | Technology |
|---|---|
| Cloud Platform | Microsoft Azure |
| Networking | Azure Virtual Network |
| Network Segmentation | Azure Subnets |
| Security | Network Security Groups |
| Identity & Access | Azure IAM / RBAC |
| Compute | Azure Virtual Machine |
| Management | Azure Portal |
| Monitoring | Azure monitoring tools |
| Region | Azure selected region |

---

## Azure Configuration

The following tasks were completed as part of the Azure cloud security lab.

### 1. Resource Group

Created an Azure Resource Group to logically organise and manage cloud resources.

### 2. Virtual Network

Created and configured an Azure Virtual Network to provide a private networking environment for cloud resources.

### 3. Subnet Configuration

Created subnets within the Virtual Network to provide network segmentation and organised resource placement.

### 4. Network Security

Configured Network Security Groups (NSGs) to control inbound and outbound network traffic using security rules.

### 5. Virtual Machine

Deployed and configured a virtual machine within the Azure environment.

### 6. Access Control

Applied Azure Role-Based Access Control (RBAC) concepts to manage permissions and access to cloud resources.

### 7. Network Connectivity

Configured and tested network connectivity between Azure resources.

### 8. Security Testing

Reviewed security configurations and tested network access to verify that security rules were functioning as expected.

---

## Security Concepts Demonstrated

This project demonstrates practical knowledge of:

- Cloud Security
- Microsoft Azure
- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Principle of Least Privilege
- Network Security
- Network Segmentation
- Virtual Networks
- Subnets
- Network Security Groups (NSGs)
- Virtual Machines
- Cloud Infrastructure
- Access Control
- Secure Network Configuration

---

## Skills Demonstrated

- Microsoft Azure
- Azure Portal
- Azure Virtual Networks
- Azure Subnets
- Network Security Groups
- Azure Virtual Machines
- Azure IAM
- Azure RBAC
- Cloud Security
- Network Configuration
- Troubleshooting
- Cybersecurity
- Cloud Infrastructure Administration

---

## Project Architecture

The Azure environment was designed using a segmented virtual network architecture.

```text
                    Microsoft Azure
                          |
                    Resource Group
                          |
                    Virtual Network
                          |
              +-----------+-----------+
              |                       |
           Subnet 1                Subnet 2
              |                       |
       Virtual Machine          Other Resources
              |
       Network Security Group
              |
       Inbound / Outbound
          Security Rules
          
          
##Disclaimer

This project was completed in a controlled Azure lab environment for educational and portfolio purposes. No unauthorised systems or production environments were accessed.
