# AWS Organizational Setup

This repository contains the setup and configuration details for an **AWS Organizational Structure**, including account management, security policies, and resource allocation. The final project documentation is available in a **PDF file** included in this repository.

## Overview
- Establishing an AWS **Organization** with multiple accounts.
- Implementing **IAM Roles and Policies** for secure access.
- Setting up **AWS Organizations and SCPs (Service Control Policies)**.
- Configuring **VPC, S3, and EC2** resources.
- Enabling **CloudWatch Monitoring and Logging**.

## Directory Structure
```
/aws-organizational-setup/
│── setup-guide.md
│── architecture-diagram.png
│── final-project-documentation.pdf
│── policies/
│   ├── iam-policies.json
│   ├── scp-rules.json
│── terraform/
│   ├── main.tf
│   ├── variables.tf
│── scripts/
│   ├── setup.sh
```

## Prerequisites
- An **AWS account** with admin access.
- **AWS CLI** installed and configured.
- **Terraform** (if using Infrastructure as Code).

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/aws-organizational-setup.git
   ```
2. Navigate to the project directory:
   ```sh
   cd aws-organizational-setup
   ```
3. Follow the setup guide in **setup-guide.md**.
4. Review the **final-project-documentation.pdf** for detailed insights.

## Final Project PDF
The complete documentation and architecture details are available in **[final-project-documentation.pdf](./final-project-documentation.pdf)**.

## Future Enhancements
- Automate account creation and policy enforcement.
- Integrate AWS **Security Hub** for enhanced monitoring.
- Implement cost optimization strategies.



---
**Maintained by Shiwansh Srivastava**
