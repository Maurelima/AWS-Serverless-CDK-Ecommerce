# AWS Serverless Application with Node.js and CDK

## 🚧 In development 🚧

This project is a **Serverless application** built with **Node.js** and **AWS Cloud Development Kit (CDK)**, for study purpose.

The repository demonstrates a fully functional serverless architecture deployed on AWS using a variety of services. 

---

## Table of Contents

- [AWS Serverless Application with Node.js and CDK](#aws-serverless-application-with-nodejs-and-cdk)
  - [🚧 In development 🚧](#-in-development-)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Features](#features)
  - [AWS Services Used](#aws-services-used)
  - [Tools and Technologies](#tools-and-technologies)
  - [Setup and Deployment](#setup-and-deployment)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Folder Structure](#folder-structure)

---

## Project Overview

The goal of this project is to create and deploy a serverless application utilizing AWS services and the CDK.

This application includes:
- REST APIs with **AWS API Gateway**.
- **AWS Lambda** functions for backend logic.
- **DynamoDB** for a NoSQL database.
- **AWS S3** for static content and file storage.
- **AWS CloudWatch** for monitoring and logging.
- **AWS Cognito** for authentication and user management.

---

## Features

- **Serverless Architecture**: Minimize infrastructure overhead by leveraging managed AWS services.
- **Scalable**: Automatically scales to meet demand using Lambda and API Gateway.
- **High Availability**: Ensures reliability with AWS-managed services.
- **Infrastructure as Code (IaC)**: All infrastructure is defined and deployed using AWS CDK.
- **Authentication**: Secures APIs with AWS Cognito for user management.

---

## AWS Services Used

This project leverages the following AWS services:

1. **AWS Lambda**  
   Executes backend logic in a serverless environment.

2. **AWS API Gateway**  
   Provides RESTful API endpoints to interact with the application.

3. **AWS DynamoDB**  
   A NoSQL database to store data with low latency and high scalability.

4. **AWS S3**  
   - Hosts static files (e.g., frontend assets or uploaded files).
   - Integrates with Lambda for file processing.

5. **AWS CloudFormation**  
   Manages infrastructure as code using CDK.

6. **AWS CloudWatch**  
   Monitors application logs, performance, and metrics.

7. **AWS Cognito**  
   Handles user authentication and authorization with minimal configuration.

8. **AWS IAM**  
   Manages permissions and access controls for resources and services.

9. **AWS CDK**  
   Infrastructure as Code (IaC) to define and deploy AWS resources using TypeScript.

10. **AWS X-Ray**  
    Provides distributed tracing for better debugging and performance monitoring.

---

## Tools and Technologies

- **Node.js**: JavaScript runtime used for Lambda functions.
- **AWS CDK**: Framework for defining cloud infrastructure as code.
- **TypeScript**: Strongly typed superset of JavaScript used for CDK definitions.
- **DynamoDB**: NoSQL database for low-latency operations.
- **API Gateway**: Manages RESTful APIs with built-in scalability and security.
- **Cognito**: Simplified user authentication with OAuth and JWT support.

---

## Setup and Deployment

### Prerequisites

**AWS CLI**: Ensure the AWS CLI is installed and configured with proper credentials.
```bash
aws configure
```

**AWS CDK**: Install the AWS CDK globally on your machine:
```bash
npm install -g aws-cdk
```

**Git**: Clone this repository:
```bash
git clone git@github.com:Maurelima/AWS-Serverless-CDK-Ecommerce.git
```

### Installation

Install project dependencies:
```bash
npm install
```

Bootstrap CDK:
```bash
cdk bootstrap
```

Deploy the application:
```bash
cdk deploy
```

## Folder Structure