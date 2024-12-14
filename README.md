# aws-shell-automation
This project automates the retrieval of AWS resources ( EC2 instances, S3 buckets, Lambda functions, and Iam) using shell scripting. It schedules tasks via cron jobs, providing a lightweight and effecient solution for monitoring AWS environments.

## Features
-Automated scheduling with cron jobs.
-Retrieves and displays:
 -EC2 instance ID's, states, and tags.
 -S3 bucket names and sizes.
 -Lambda function names and runtime environments.
-Error handling for authentication and resource unavalability.
-Easily extensible to include additional AWS services.

## Screenshots
- ssh into the machine 
![ssh](https://github.com/user-attachments/assets/e309842b-5f9d-499e-8cfa-90e31d558cbc)
- script metadata
  ![script metadata](https://github.com/user-attachments/assets/c9c12687-f5f7-44f6-8ee3-b7db2f0a8472)
- Added argument
  ![added arguments](https://github.com/user-attachments/assets/e5e09684-2f7f-43d7-9ccb-0dd3f2bf67bb)
- cat command to view the script content
  ![cat command to view the shell content](https://github.com/user-attachments/assets/a2ef5228-f901-4ab9-9504-48a7ae735f19)
- command to grant full permission to the file
  ![command to grant full permission to the file](https://github.com/user-attachments/assets/7198cb64-7707-4963-9dfc-cba94e961d83)
- command to view an dexecute the script
  ![command to view ans execute the script](https://github.com/user-attachments/assets/42fd945c-7621-4f72-a220-91acbdafdf35)
- generated output
  ![generated output](https://github.com/user-attachments/assets/32046ccb-0261-4449-9d29-805434d1014d)
- redirecting output to a file
  ![redirecting the outputs to a file](https://github.com/user-attachments/assets/5987535a-bbe6-4f9d-8a01-8752a52285ff)
- viewing the ouput file
  ![contents of the output file](https://github.com/user-attachments/assets/1ffb5553-d74f-46ab-8c4a-734f2e3a9084)
- cronjob script
  ![writting a cronjob script](https://github.com/user-attachments/assets/e18b9cfa-215c-4168-8b17-95bcab829df3)
-verifying cronjob installation
  ![cronjob verification](https://github.com/user-attachments/assets/b2332e72-ccda-4fc6-9412-19e8bef12986)


## Prerequisites
-AWS CLI installed and configured.
-Shell scripting environment ( linux Ubuntu).
-Access to an AWS account with proper IAM roles and permissions.

## Installation
1. Clone this repository
   '''bash
  - git clone https://github.com/RefilweMohlala/aws-shell-automation.git
  - cd aws-shell-automation
