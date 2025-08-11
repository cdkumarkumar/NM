FreshBasket – Scalable E-Commerce Platform Deployment with Flask on AWS EC2 and RDS
📌 Overview
FreshBasket is a cloud-native e-commerce platform designed for selling fresh vegetables and fruits. The project demonstrates the deployment of a scalable, fault-tolerant backend using Flask hosted on AWS EC2 with database management via Amazon RDS.

The platform ensures:

Scalability to handle seasonal traffic surges

High availability to maintain user trust

Cost-effectiveness for small and medium businesses

Real-time operations for inventory and order management

🚀 Features
Product Catalog Management – Add, update, and display products dynamically.

Order Processing System – Place, track, and manage customer orders.

User Authentication – Secure registration and login.

AWS Cloud Infrastructure – EC2 for hosting, RDS for database, S3 for storage, CloudWatch for monitoring.

Auto-Scaling & Load Balancing – Ensures uptime during peak loads.

RESTful API – For seamless integration with frontend or mobile apps.

🛠️ Tech Stack
Backend: Python (Flask)
Database: MySQL on AWS RDS
Hosting: AWS EC2
Storage: AWS S3
Monitoring: AWS CloudWatch
Security: AWS IAM, HTTPS, role-based access control
Deployment: Docker, AWS CodePipeline & CodeDeploy

📂 System Architecture
Presentation Layer: Basic HTML/CSS/JS UI for demonstration.

Application Layer: Flask backend with business logic and APIs.

Data Layer: AWS RDS (MySQL) for structured data storage.

📜 API Endpoints (Examples)
GET /products → Fetch all products

POST /orders → Place a new order

GET /order-status → Track order status

🔍 Testing & Optimization
Unit Testing: PyTest, unittest

Integration Testing: Postman, MySQL Workbench

Load Testing: Apache JMeter, AWS CloudWatch

Security Testing: OWASP ZAP, Burp Suite

End-to-End Testing: Selenium

📈 Future Enhancements
Mobile application for better accessibility

AI-driven recommendations & inventory predictions

Advanced search and customer review system

Multi-currency & payment gateway integration

Blockchain for supply chain transparency

📚 References
AWS Account Setup

AWS EC2 Setup

RDS Database Setup

MySQL Tutorial

AWS Cost Management

👨‍💻 Contributors
Keerthivasan G

Akhilan LH

Kumar D

Kumar R

Manish ESJ
