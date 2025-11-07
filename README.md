This project demonstrates how to use AWS CDK (Cloud Development Kit) to build a serverless logging solution.
It automatically provisions:

A DynamoDB table to store log records (with timestamps).

An AWS Lambda function that writes entries (like log events or user actions) into that table.

Required IAM roles and permissions so the Lambda can interact with DynamoDB.

When executed, the Lambda function captures the current timestamp and writes it along with other log details (e.g., user info, event type) into the DynamoDB table — helping track when each event occurred.

⚙️ Skills Used

AWS Services:
AWS Lambda, DynamoDB, CloudFormation, IAM, AWS CDK

Programming & Tools:
JavaScript (Node.js), AWS SDK, Infrastructure as Code (IaC), Serverless Architecture

Concepts:
Event Logging, Timestamp Tracking, NoSQL Database Operations, Cloud Automation, Resource Deployment
