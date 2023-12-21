# AWS EC2 File Cloud Setup with S3 Storage 🚀

This guide provides step-by-step instructions for deploying File Cloud on an AWS EC2 instance while utilizing AWS S3 for scalable, secure storage. Additionally, it includes IAM setup to manage access permissions. 

## Introduction ℹ️

This repository offers a comprehensive walkthrough for setting up File Cloud on an AWS EC2 instance, coupled with S3 storage to ensure reliable and secure data management. The integration of File Cloud with S3 elevates the solution's capabilities by leveraging AWS's robust storage infrastructure.

## Prerequisites 🛠️

Ensure you have:
- An active AWS account 🌐
- Basic familiarity with AWS services (EC2, S3, IAM) 🧭
- Access to the AWS Management Console 💻

## Setup Steps 📋

1. **EC2 Instance Creation**
    - Launch an EC2 instance via the AWS Management Console, selecting the appropriate AMI and instance type.
    - Retain the SSH key pair securely for accessing the instance.

2. **Accessing the EC2 Instance**
    - Utilize SSH to connect to the EC2 instance using the previously downloaded key pair.

3. **File Cloud Installation**
    - Follow the File Cloud installation instructions designed for EC2 instances.
    - Adapt the configuration to employ S3 storage instead of local storage.

4. **IAM Configuration**
    - Generate an IAM user with granular permissions to access the S3 bucket.
    - Obtain Access and Secret Access Keys for the IAM user.

5. **S3 Bucket Creation**
    - Create an S3 bucket dedicated to storing File Cloud data.
    - Configure precise access permissions for the IAM user to interact with the bucket.

6. **File Cloud - S3 Integration**
    - Update the File Cloud configuration settings to integrate seamlessly with the designated S3 bucket.
    - Enable AWS-managed encryption for enhanced data security.

## Additional Information ℹ️

- Safeguard sensitive information such as access keys and credentials. 🔒
- Prioritize AWS best practices for security and access control. 🛡️

## Contributors 👨‍💻

- Pratik Ghawate 
