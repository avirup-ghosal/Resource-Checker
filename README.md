# AWS Resource Checker
This bash script automates the process of listing all the resources in an AWS account. It supports a wide range of AWS services, including EC2, RDS, S3, CloudFront, VPC, IAM, Route53, CloudWatch, CloudFormation, Lambda, SNS, SQS, DynamoDB, and EBS.
## Features
- Lists resources from multiple AWS services
- Supports user-defined AWS regions
- Validates AWS CLI installation and configuration
- Provides error handling for invalid inputs
## Supported AWS services
1. ECS
2. RDS
3. S3
4. CloudFront
5. VPC
6. IAM
7. Route53
8. CloudWatch
9. CloudFormation
10. Lambda
11. SNS
12. SQS
13. DynamoDB
14. EBS
    
## Prerequisites
- AWS CLI installed and configured
- Bash environment (Linux, macOS, or WSL on Windows)
## Installation
Clone the repository and navigate to the script directory:
```bash
 git clone https://github.com/avirup-ghosal/Resource-Checker.git
 cd Resource-Checker
```
## Usage 
The script takes two arguments: the AWS region and the service name.
```bash
./aws_list_resources.sh <aws_region> <aws_service>
./aws_list_resources.sh us-east-1 ec2
```
## Error Handling
- The script checks whether AWS CLI is installed and configured
- Displays a message if service name is invalid

