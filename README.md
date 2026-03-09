# 🎓 AWS Cloud Solution Architecture - Capstone Project (NTI)

This project is the culmination of my training at the **National Telecommunication Institute (NTI)**, an initiative powered by the **Ministry of Communications and Information Technology (MCIT)**. It represents a full-stack infrastructure deployment on AWS Academy Labs.

## 🎯 Project Objective
Design and implement a highly available and scalable multi-tier architecture while strictly managing a cloud budget ($60 limit).

## 🛠️ Key Implementations
* **Database Layer:** Provisioned a managed database (MariaDB/MySQL) based on specific architectural requirements, accounting for ~50% of the project budget.
* **Compute & Scaling:** * Created a **Launch Template** for standardized EC2 instance deployment.
    * Implemented an **Auto Scaling Group (ASG)** to ensure the application handles varying traffic loads automatically.
* **Traffic Management:** Configured an **Application Load Balancer (ALB)** and associated **Target Groups** to distribute incoming traffic across the fleet of instances.
* **Cost Management:** Monitored AWS Academy credits to ensure the infrastructure remained within the $60 budget constraint.

## 📑 Documentation
* `Capston Project .pdf`: Detailed documentation of the DB setup, Target Group configurations, and Auto Scaling policies.

---
*Completed as part of the NTI Cloud Solution Architecture Track (MCIT Initiative).*
