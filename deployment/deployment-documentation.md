# AWS Task 2 Deployment Documentation

## AWS Region

**Region Code:** `eu-north-1`

**Region Name:** Stockholm

---

## Project

Cloud Infrastructure Provisioning with AWS

## Objective

This project provisions and documents a basic AWS cloud infrastructure environment using IAM, VPC, EC2, S3 and CloudWatch.

## 1. IAM Configuration

IAM users and related access configuration were created for the lab environment.

The configuration includes:

- IAM users
- IAM groups
- IAM policies
- MFA/security configuration
- IAM user access management

Evidence is available in:

`screenshots/iam/`

## 2. VPC Configuration

A custom VPC was configured for the project.

The networking configuration includes:

- VPC
- Subnet configuration
- Internet Gateway
- Route Table
- Security Groups

Evidence is available in:

`screenshots/vpc/`

and:

`screenshots/security-groups/`

## 3. EC2 Deployment

An Ubuntu EC2 instance was launched and configured.

Evidence is available in:

`screenshots/ec2/`

## 4. Nginx Web Server

Nginx was installed on the Ubuntu EC2 instance and verified.

Evidence:

`screenshots/ec2/nginx-web-server.jpeg`

## 5. Security Groups

Security Group rules were configured for the EC2 instance according to the required access.

Evidence:

`screenshots/security-groups/`

## 6. Amazon S3

Amazon S3 was configured for cloud object storage.

Evidence is available in:

`screenshots/s3/`

## 7. CloudWatch Monitoring

CloudWatch monitoring was configured for the AWS infrastructure.

Evidence is available in:

`screenshots/cloudwatch/`

## 8. AWS Architecture

The AWS architecture diagram is stored at:

`architecture/aws-architecture.jpeg`

## 9. Cost Estimation

AWS Pricing Calculator evidence is stored in:

`cost/`

## 10. Security Considerations

Sensitive AWS credentials, private SSH keys, passwords, MFA secrets and other secret values must not be stored in this repository.

## 11. Cleanup

Unused AWS resources should be stopped or terminated after completing the lab to avoid unnecessary charges.
