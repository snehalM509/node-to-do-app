# node-todo-cicd
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




About

Task definitions
<img width="940" height="223" alt="image" src="https://github.com/user-attachments/assets/e6134fdb-a936-4c0c-a74d-514cbeefe7b5" />
Cluster
<img width="940" height="229" alt="image" src="https://github.com/user-attachments/assets/7970565c-1db5-4821-bc62-a7f177998214" />
Images
<img width="940" height="288" alt="image" src="https://github.com/user-attachments/assets/49f3577c-bd8b-4319-b49e-021f684933ec" />
Permissions added to IAM user
<img width="940" height="339" alt="image" src="https://github.com/user-attachments/assets/8e721ffd-4ced-40d3-91ee-a34ed6bca83f" />
Created ECSTaskExecutionRole
<img width="940" height="443" alt="image" src="https://github.com/user-attachments/assets/d952c251-8b0e-4def-bbc9-747c78386e0b" />
Cluster
<img width="940" height="448" alt="image" src="https://github.com/user-attachments/assets/464dc86e-e9bd-4f77-884e-94e8e6db28c4" />
EC2
<img width="940" height="251" alt="image" src="https://github.com/user-attachments/assets/fa333f6e-22f3-4b56-a3a7-c07451f8cdf5" />
Docker Images
<img width="940" height="173" alt="image" src="https://github.com/user-attachments/assets/a0a58661-2e2d-4d73-be62-4cc072b6d24f" />
See Custer Info
<img width="940" height="530" alt="image" src="https://github.com/user-attachments/assets/f4def26a-d2b6-4200-b482-5ba0b710df74" />
Output
<img width="940" height="342" alt="image" src="https://github.com/user-attachments/assets/da2baae9-035d-490b-a3f9-054e4573ce6b" />



