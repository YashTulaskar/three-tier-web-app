# AWS 3-Tier Web Application

This project implements a three-tier architecture using AWS services and EC2-based deployment, as part of the [AWS Workshop](https://catalog.us-east-1.prod.workshops.aws/workshops/85cd2bb2-7f79-4e96-bdee-8078e469752a/en-US/introduction).

## 🛠 Technologies

- **Frontend**: React, Nginx, EC2
- **Backend**: Node.js/Express API, EC2
- **Database**: Amazon RDS (MySQL)
- **Networking**: ALB (internal), Security Groups, Subnets
- **Infrastructure**: EC2 Auto Scaling, IAM

## 📸 Architecture Diagram

![image](https://github.com/user-attachments/assets/ba8561a8-949a-4e2b-9f25-ad47302181b0)


## 🚀 Features

- Scalable, fault-tolerant 3-tier design
- React frontend hosted with Nginx
- Internal ALB routing to app-tier APIs
- RDS-backed data persistence

## 📝 Setup Instructions

1. Launch EC2 instances in proper subnets
2. Deploy frontend to web-tier with Nginx
3. Setup internal ALB and backend app on app-tier
4. Connect to RDS instance securely
5. Verify with health checks and logs

## 📚 Workshop Source

Based on the AWS Workshop:  
https://catalog.us-east-1.prod.workshops.aws/workshops/85cd2bb2-7f79-4e96-bdee-8078e469752a/en-US/introduction

## 📬 Contact

Feel free to reach out if you'd like to collaborate or learn more!

