# serverless-rest-api-aws-project
Serverless CRUD API on AWS (API Gateway, Lambda, DynamoDB, S3, CloudFront)
## 📌 Overview
This project demonstrates a serverless architecture using AWS services to build a REST API for managing tasks (CRUD operations).

## 🏗️ Architecture
- Amazon S3 (Static Website Hosting)
- Amazon CloudFront (CDN)
- Amazon API Gateway (REST API)
- AWS Lambda (Backend Logic)
- Amazon DynamoDB (Database)
- AWS IAM (Security)
- Amazon CloudWatch (Monitoring)

## 🔄 Workflow
1. User accesses the app via CloudFront
2. Static content served from S3
3. API requests go to API Gateway
4. Lambda processes requests
5. Data stored/retrieved from DynamoDB

## ⚙️ Features
- Fully Serverless
- Scalable Architecture
- CRUD Operations
- Secure access with IAM
- Monitoring with CloudWatch

## 🚀 Future Improvements
- Add Authentication (AWS Cognito)
- CI/CD Pipeline
- Custom Domain with HTTPS

## 👨‍💻 Author
Mostafa Adel
