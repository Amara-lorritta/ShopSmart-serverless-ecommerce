## **ShopSmart – Serverless E-Commerce Application**

## **Overview**

ShopSmart is a fully serverless e-commerce application built using AWS cloud-native services. The platform allows users to browse products, add items to a shopping cart, and perform checkout operations.
This project demonstrates serverless backend development, API design, IAM security, DynamoDB data management, and static front-end hosting using AWS S3 and CloudFront.

## **My Role in This Project**

As part of a 5-person engineering team, I contributed to:

Designing and documenting the AWS serverless backend architecture

Creating, configuring, and securing IAM Roles and Policies

Implementing REST API routes using Amazon API Gateway

Connecting Lambda functions with DynamoDB for CRUD operations

Setting up the S3 Bucket for frontend hosting and CloudFront distribution

Testing endpoints with real user flows (products, cart, checkout)

Troubleshooting deployment, permissions, and CORS issues

Supporting front-end integration using JavaScript + API Gateway endpoints

This repository represents my personal full copy of the completed team project.


## **Objectives & Learning Outcomes**

By completing this project, I gained hands-on experience in:

Designing secure serverless architectures

Building scalable REST APIs in AWS

Implementing Lambda functions with Node.js

Creating DynamoDB tables and performing CRUD operations

Configuring IAM permissions using least privilege

Hosting static websites with S3 + CloudFront

Troubleshooting CORS, API Gateway routing, and identity-based policies

Collaborating using GitHub and version-controlled workflows

## **Architecture Diagram / Live Demo**

<img width="480" height="720" alt="aws_serverless_e-commerce_architecture_flow_720" src="https://github.com/user-attachments/assets/189ff554-e41a-4a95-8796-980bd4b89a8d" />

https://github.com/user-attachments/assets/998a45c0-4c3b-4186-9a70-ce7261d5804d

## Frontend

Single-page app (index.html) using HTML, CSS, and JavaScript

Hosted on Amazon S3 static website hosting

Communicates with API Gateway to load products and handle cart operations

## Backend
Amazon API Gateway (REST)

GET /products → loads product catalog from DynamoDB via Lambda

AWS Lambda (Python)

Runtime: Python 3.x

Reads from DynamoDB table ShopSmartProducts

Converts DynamoDB Decimal types to standard JSON numbers

Returns a list of product objects as JSON

Amazon DynamoDB


## **Tools & AWS Services Used**

AWS Services

Amazon API Gateway

AWS Lambda

Amazon DynamoDB

Amazon S3 (Static Website Hosting)

AWS IAM (Roles & Policies)

Amazon CloudWatch

CloudShell

Technologies

HTML, CSS, JavaScript

Serverless Design Architecture

JSON REST API

Git & GitHub

API Endpoints (REST)


| Method | Description                     |
| ------ | ------------------------------- |
| GET    | Retrieve all available products |
| Method | Description           |
| ------ | --------------------- |
| GET    | Get items in the cart |
| POST   | Add item to the cart  |
| Method | Description       |
| ------ | ----------------- |
| POST   | Complete checkout |
| Method | Description                             |
| ------ | --------------------------------------- |
| GET    | Get details of a specific product by ID |


## **Deployment Flow (AWS CloudShell)**

Create S3 bucket

Upload frontend and set bucket policy

Deploy Lambda + API Gateway

Insert products into DynamoDB

Visit the live website

## **What Actually Happened**

We planned the application structure, API routes, front-end pages, and architecture.

We created DynamoDB tables for Products and Cart.

We wrote Lambda functions for product retrieval, cart management, and checkout.

We connected Lambda to API Gateway routes and enabled CORS.

We configured IAM roles to allow Lambda to read/write DynamoDB.

We deployed and tested endpoints using Postman and the API Gateway console.

We hosted the front-end files on S3 and enabled public access.

We added a CloudFront distribution for faster global performance.

We integrated front-end JavaScript with live API Gateway links.

We performed final testing of the entire shopping workflow.

We fixed IAM permission issues, CORS problems, and routing errors.

We completed documentation and prepared for team presentation.


## **Key Takeaways**

Serverless architecture drastically reduces cost and maintenance.

IAM least privilege is essential for securing Lambda and DynamoDB.

CORS issues are common when connecting front-end and API Gateway.

CloudFront greatly improves front-end performance.

Proper API routing and testing prevent integration failures.

Team collaboration strengthens code quality and delivery speed.

## **Authors**

Amarachi Emeziem

GitHub: https://github.com/Amara-lorritta

LinkedIn: https://www.linkedin.com/in/amarachi-emeziem

Hawi Jordan

Github: https://github.com/HawiK285


Olusegun Ajayi-Johnson

Github: https://github.com/segunaj78-lgtm

SohelKhan

GitHub: https://github.com/SohelKhanDeveloper




🔗 LinkedIn: www.linkedin.com/in/hawi-jordan-3b18752a9
