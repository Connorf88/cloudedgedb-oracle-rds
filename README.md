
CloudEdgeDB Oracle RDS

CloudEdgeDB Oracle RDS is a hands-on project designed to demonstrate the provisioning and configuration of an Oracle RDS database in AWS using Infrastructure as Code (IaC). This project showcases core cloud computing skills, including VPC networking, secure authentication, and integration with cloud-based relational databases.

🚀 Project Overview

This project provisions:
- An Oracle RDS instance on AWS
- A dedicated Virtual Private Cloud (VPC) with subnets and routing
- Secure IAM roles and security groups
- Database initialization using SQL scripts (optional)

It highlights best practices for cloud-native architecture, emphasizing resilience, modularity, and security.

📂 Folder Structure

`bash
cloudedgedb-oracle-rds/
├── terraform/             # IaC configuration files
├── sql-scripts/           # Optional: DB setup & test queries
├── diagrams/              # Architecture diagrams & visuals
├── README.md              # Project documentation
└── outputs/               # Saved Terraform outputs (optional)
`

🧰 Tech Stack

- AWS RDS – Oracle Standard Edition
- Terraform for infrastructure provisioning
- SQL for schema creation (optional)
- IAM, VPC, Security Groups

🏗️ Setup Instructions

1. Clone the repository
   `bash
   git clone https://github.com/Connorf88/cloudedgedb-oracle-rds.git
   cd cloudedgedb-oracle-rds
   `

2. Initialize Terraform
   `bash
   cd terraform
   terraform init
   `

3. Configure variables  
   Update terraform.tfvars with your AWS region, credentials, DB instance size, etc.

4. Deploy infrastructure
   `bash
   terraform apply
   `

5. (Optional): Connect to your DB using SQL tools like DBeaver or SQLcl.

🔐 Security & Credentials

Secrets and sensitive values (like DB passwords or AWS credentials) are excluded from version control. Refer to the .gitignore file and use environment variables or a secrets manager for secure access.

📊 Architecture Diagram

Add a diagram here to visually represent your VPC, subnets, RDS, and IAM setup.

✍️ Author

Connor F.  
Cloud Computing Student @ Purdue Global  
🔗 LinkedIn · 🌐 GitHub