# terraform-aws-cost-optimizer
End-to-end AWS EC2 cost optimization using Terraform and Python.
Provisions infrastructure with Terraform and uses Python scripts (via Lambda) to automatically start and stop EC2 instances based on schedules, reducing AWS costs.

# 🚀 terraform-aws-cost-optimizer

Automate AWS EC2 **cost optimization** using **Terraform** and **Python**.  
Terraform provisions the infrastructure (Lambda, IAM, CloudWatch Events, EC2), while Python scripts perform the **start** and **stop** operations on EC2 instances to minimize idle cost.

---

## 🧩 Features

- 🏗️ Infrastructure as Code with **Terraform**
- 🐍 Automation logic in **Python (Boto3)**
- 💰 Auto start/stop EC2 instances for cost saving
- ⏰ **CloudWatch Events** for scheduling
- 🔐 **IAM roles/policies** with least privilege
- 📊 **CloudWatch Logs** for monitoring execution

---

## 🏗️ Architecture Overview
Terraform → Provisions AWS Resources
├── IAM Role & Policy
├── Lambda Function (Python Script)
├── CloudWatch Scheduler (EventBridge)
└── EC2 Instances (Tagged for Automation)

