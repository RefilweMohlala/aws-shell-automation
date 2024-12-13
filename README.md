# aws-shell-automation
This project automates the retrieval of AWS resources ( EC2 instances, S3 buckets, Lmbda functions, and Iam) using shell scripting. It schedules tasks via cron jobs, providing a lightweight and effecient solution for monitoring AWS environments.

## Features
-Automated scheduling with cron jobs.
-Retrieves and displays:
 -EC2 instance ID's, states, and tags.
 -S3 bucket names and sizes.
 -Lambda function names and runtime environments.
-Error handling for authentication and resource unavalability.
-Easily extensible to include additional AWS services.

## Prerequisites
-AWS CLI installed and configured.
-Shell scripting environment ( linux Ubuntu).
-Access to an AWS account with proper IAM roles and permissions.

## Installation
1. Clone this repository
   '''bash
   git clone https://github.com/RefilweMohlala/aws-shell-automation.git
   cd aws-shell-automation
