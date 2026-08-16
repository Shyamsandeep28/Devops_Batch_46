# 🚀 Terraform Hands-On Labs – Complete Beginner to Advanced Series

### **Author: Dr. Sandeep Kumar Sharma**

Welcome to the **Terraform Labs Repository** — a complete, structured, end-to-end learning path designed for beginners, intermediate learners, and professionals preparing for real-world Terraform + AWS projects.

This repository contains **step-by-step, production-ready, instructor-style labs** created in a natural, easy-to-understand teaching format. If you follow these labs in order, you will confidently master Terraform from zero to advanced.

---

# 🌟 Why This Repository?

Most Terraform tutorials stop at beginner level. Real production infrastructure requires:

* modules
* workspaces
* remote state
* VPC design
* autoscaling setups
* load balancers
* security and IAM
* data sources
* tfvars

This repository bridges that gap.
You will learn Terraform **as if sitting inside a live corporate training session.**

---

# 📚 Lab Structure Overview

The labs are divided into two parts:

## **1️⃣ Beginner to Intermediate Labs (Lab 1 – 16)**

These labs help you build a strong foundation.

| Lab No. | Topic                                                   |
| ------- | ------------------------------------------------------- |
| 1       | Introduction to Terraform & Deploying First Resource    |
| 2       | Terraform Folder Structure & Best Practices             |
| 3       | Create EC2 Instance (No Variables – Clean Basics)       |
| 4       | Understanding Terraform State & Backend (S3 + DynamoDB) |
| 5       | Variables in Terraform (Inline + variables.tf)          |
| 6       | tfvars – Externalizing Variable Values                  |
| 7       | Output Values – Displaying Important Info               |
| 8       | Locals – Internal Reusable Values                       |
| 9       | Creating Your First Terraform Module                    |
| 10      | Security Groups Using Terraform                         |
| 11      | Using Terraform Public Module (EC2 Module)              |
| 12      | VPC Module (Basic)                                      |
| 13      | Terraform Data Sources (AMI, VPC, Subnets)              |
| 14      | Terraform Conditionals (ternary, count)                 |
| 15      | Terraform Loops (count, for_each, dynamic)              |
| 16      | Terraform Workspaces (Multi-Environment Setup)          |

Each lab contains:

* Concept explanation
* Real-life analogy
* Step-by-step instructions
* Validations
* Clean, production-friendly code

---

## **2️⃣ Advanced, Production-Ready Labs (Lab 17+ )**

These labs shift your gears into real enterprise infrastructure.

| Lab No. | Production Scenario                                           |
| ------- | ------------------------------------------------------------- |
| 17      | Multi-AZ Production-Ready VPC (Public + Private + DB Subnets) |
| 18      | ALB + AutoScaling Group + EC2 Deployment (Recommended)        |
| 19      | Secure S3 Bucket (KMS, Versioning, Logging)                   |
| 20      | RDS Production Deployment (Private Subnets + SG)              |
| 21      | Full Architecture Deployment Using Modules                    |

> New advanced labs will be added continuously.

---

# 🧩 Skills You Will Gain

By completing all labs, you will gain:

* Strong Terraform fundamentals
* Multi-file & modular Terraform architecture
* AWS production infrastructure experience
* Terraform backend & state management
* Complex VPC networking hands-on experience
* Reusable module creation
* Workspace-based multi-environment infra
* Secure, scalable, production-grade deployments

Perfect for:

* Terraform Associate Certification
* DevOps, Cloud & SRE engineers
* Production-grade Terraform project work

---

# 🛠️ Tools & Services Used

* Terraform (>= 1.4)
* AWS (EC2, VPC, S3, IAM, SG, RDS, ALB, ASG, IGW, NAT, DynamoDB)
* Visual Studio Code
* Git / GitHub

---

# 📁 Repository Structure

```
terraform-labs/
├── lab01-introduction
├── lab02-folder-structure
├── lab03-ec2-basic
├── lab04-state-backend
├── lab05-variables
├── lab06-tfvars
├── lab07-outputs
├── lab08-locals
├── lab09-modules
├── lab10-security-groups
├── lab11-public-module-ec2
├── lab12-vpc-module
├── lab13-data-sources
├── lab14-conditionals
├── lab15-loops
├── lab16-workspaces
└── lab17-prod-vpc
```

Each folder contains:

* All `.tf` files
* Lab explanation
* Architecture diagram (if applicable)
* Commands to run

---

# 🚀 How to Use This Repository

### **Step 1: Clone the repo**

```bash
git clone https://github.com/Shyamsandeep28/Terraform_AWS_New_Labs_by_Sandeep.git
```

### **Step 2: Go to any lab folder**

```bash
cd terraform-labs/lab06-tfvars
```

### **Step 3: Run Terraform**

```bash
terraform init
terraform plan
terraform apply
```

Follow the instructions written in each lab.

---

# 🧑‍🏫 About the Author

**Dr. Sandeep Kumar Sharma** is a:

* Senior Corporate Trainer
* Solution Architect & DevOps Engineer
* Specialist in Terraform, AWS, Kubernetes, CI/CD, & Databricks
* Trainer for 100+ global corporate clients

Connected with tens of thousands of learners worldwide through high-quality hands-on content.

---

# ⭐ Support This Repository

If this repo helps you:

* ⭐ Star this repository
* 🔁 Share it with others
* 🐛 Raise issues for improvements
* 🤝 Contribute by submitting PRs

Your support motivates the creation of more **advanced Terraform labs**.

---

# 🎯 Final Note

This repository isn’t just a collection of labs — it’s a **complete Terraform learning journey**, crafted with real-world clarity and production standards.

Happy Terraforming! ☁️💻

---
🌐 Connect With Me

If you enjoyed these Terraform labs or found them useful, feel free to follow me for more hands-on content, real-world architecture guides, and corporate-training style explanations.

🔗 LinkedIn

Connect with me for DevOps, Cloud, Terraform, Kubernetes, and Databricks updates:
👉 https://www.linkedin.com/in/sandeep-kaushik-2a345856/

📝 Medium (Technical Blogs)

Read my latest blogs on ADF, Databricks, Terraform, DevOps, and Cloud architecture:
👉 https://medium.com/@shyamsandeep28

**© 2025 – Dr. Sandeep Kumar Sharma. All rights reserved.**
