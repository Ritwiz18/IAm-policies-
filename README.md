# IAm-policies-
🔐 IAM Policies, Secure Storage & Data Encryption on AWS
This project demonstrates how to implement secure and controlled access to AWS resources using IAM policies, along with secure storage in S3 and data encryption using AWS-managed and customer-managed keys.

🚀 Project Overview
This project focuses on three core aspects of cloud security:
IAM (Identity and Access Management)
Creating custom IAM policies
Assigning least-privilege permissions to users and roles
Restricting access to specific actions and resources
Secure S3 Storage
Bucket policies for controlled access
Enforcing HTTPS-only access
Disabling public access
Enabling versioning and logging
Data Encryption
Using SSE-S3, SSE-KMS, and Client-Side Encryption
Creating and managing KMS keys
Encrypting and decrypting data with proper key policies

🛠️ Tools & Technologies
AWS IAM
AWS S3
AWS KMS (Key Management Service)
AWS CLI / AWS Console
JSON Policy Documents


📁 Project Structure
.
├── iam/
│   ├── custom-policy.json
│   └── role-assignment.md
├── s3/
│   ├── bucket-policy.json
│   ├── enable-versioning.sh
│   └── s3-encryption-config.md
├── kms/
│   ├── create-cmk.md
│   ├── encrypt-decrypt-example.py
│   └── key-policy.json
└── README.md
