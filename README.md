# node-to-do-app
A Node.js application that is fully automated with serverless ECS Fargate, with the image repository ECR and CloudWatch logging  integrated with proper IAM roles and Configuration. 

Architecture 

<img width="864" height="347" alt="image" src="https://github.com/user-attachments/assets/83cf383d-8d41-4dc1-aa74-9d91a28a6288" />

Key Components

Key Components:
EC2: Virtual server where the app runs.
VPC: Isolated network with public/private subnets across 2 AZs
ECS Fargate: Serverless container orchestration
ECR: Public Docker image registry
CloudWatch: Centralized logging and monitoring


