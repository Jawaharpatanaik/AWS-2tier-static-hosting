# AWS 2-Tier Static Hosting

This project demonstrates a **2-Tier Static Web Hosting Architecture on AWS**, designed for scalability, security, and high availability.  

It uses services like **VPC, EC2, ALB, Auto Scaling, RDS, Route 53, CloudFront, ACM, and WAF** to deliver a secure static web application.

---

## 📌 Architecture Overview
- **Amazon Route 53** routes user requests.  
- **Application Load Balancer (ALB)** distributes traffic across **EC2 instances**.  
- **Auto Scaling Group** ensures high availability and fault tolerance.  
- **Amazon RDS** in private subnets provides the database layer.  
- **CloudFront + ACM (SSL/TLS)** secures communication with HTTPS.  
- **AWS WAF** enhances security against common attacks.  

---

## 🛠️ Steps Implemented
1. **Created VPC and Subnets** (2 public, 2 private).  
2. Configured **Internet Gateway** and **NAT Gateway**.  
3. Launched **EC2 Instances** and created **Target Group**.  
4. Set up **Application Load Balancer (ALB)**.  
5. Created **AMI** and **Launch Template**.  
6. Configured **Auto Scaling Group**.  
7. Created **DB Subnet Group** and launched **RDS (Primary + Read Replica)**.  
8. Requested **SSL Certificate (ACM)**.  
9. Configured **Route 53** hosted zone and records.  
10. Deployed **CloudFront Distribution** with WAF.  
11. Verified **HTTPS secure access**.  


---


## ✅ Features
- Highly available  
- Scalable infrastructure  
- Secure with HTTPS & WAF  
- Cost-efficient 2-tier design  


---


## 👤 Author
**Chakramahanti Jawahar**  
  

