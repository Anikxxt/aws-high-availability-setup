
# High Availability Setup for Company ABC's Product on AWS

## 📖 Project Overview
This project focuses on migrating Company ABC's PHP-based website and MySQL database to AWS, ensuring high availability using Auto Scaling, Load Balancing, and other AWS services.

## 🧩 Problem Statement
- **Scenario**: Company ABC wants to migrate their product to AWS for improved scalability and high availability.
- **Components**: 
  1. PHP-based website
  2. MySQL database
- **Objective**: Ensure high availability with Auto Scaling enabled for the website.

## 🛠️ Solution Architecture
(png/Untitled Diagram.png)  

### Key AWS Services Used
- **EC2**: Hosts the PHP-based website.
- **RDS**: Manages the MySQL database.
- **ELB (Elastic Load Balancer)**: Distributes traffic across EC2 instances.
- **Auto Scaling**: Adjusts the number of EC2 instances based on traffic demands.
- **CloudWatch**: Monitors resources and triggers scaling.

## 🌟 Features
- High Availability using Auto Scaling and Load Balancer.
- Secure MySQL database using RDS with a multi-AZ deployment.
- Fault-tolerant architecture with CloudWatch for proactive monitoring.
- Separation of application and database tiers.

## 🧑‍💻 Tech Stack
- PHP
- MySQL
- AWS (EC2, RDS, Auto Scaling, ELB, CloudWatch)

## 📂 Documentation
- Detailed step-by-step guide with screenshots:  
  - [AWS Migration Step-by-Step Guide (PDF)](doc/Project.pdf)  
  
## 🏆 Outcomes
- **Reduced Downtime**: Auto Scaling ensures optimal performance under varying traffic loads.
- **Scalable Architecture**: Easily handles growth in traffic and data.
- **AWS Best Practices**: Secure, scalable, and cost-effective solution.

## 📜 Lessons Learned
- Optimizing Auto Scaling policies for dynamic workloads.
- Integrating PHP applications with AWS services seamlessly.

## 🤝 Contributions
Feel free to fork this repo, raise issues, or contribute to its development.

## 📬 Contact
- LinkedIn: https://www.linkedin.com/in/aniket-bhola-9b19601ba
