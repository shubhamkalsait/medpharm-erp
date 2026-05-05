# Medpharm B2B erp application

Tech stack:
1 Frontend. (React)
3 Backend   (Spring Boot, JAva)
Database (MongoDB)

Prerequisite:

AWS Services: S3, EKS, EC2, AS, LB, VPC, CloudFront, Route53, ECR, IAM
DevOps: Docker Host, kubectl, aws-cli, eks-cluster, s3 bucket, domain name
Environment: java-17, maven, Nodejs, npm

Branching Strategy:
    Feature
DEV 
TEST
UAT
PROD
    HotFix


Infra:
s3 + EKS + MongoDB (Atlas)

Credentials:
- DB_USER: cloudblitz
- DB_PASS: redhat
- DB_HOST: cluster0.1msw0d5.mongodb.net/?appName=Cluster0
- DB_NAME:  users_db, products_db, orders_db

Connections String: mongodb+srv://cloudblitz:redhat@cluster0.1msw0d5.mongodb.net/?appName=Cluster0

----



