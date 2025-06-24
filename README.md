# ☁️ CloudEdgeDB: Oracle XE to AWS RDS Migration

A secure and cost-efficient migration pipeline for Oracle XE schemas into AWS RDS using native AWS services like EC2, S3, IAM Roles, and Data Pump—designed entirely within the AWS Free Tier.

## 📐 Architecture Overview

- Custom VPC with public/private subnets
- Oracle XE hosted on EC2 in public subnet
- Schema export using Oracle Data Pump
- Upload to S3 and import to Oracle RDS instance in private subnet
- IAM Role–based access from RDS to S3
- Route tables, security groups, and Internet Gateway configured for secure access

