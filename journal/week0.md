# Week 0 — Billing and Architecture

## Install AWS CLI
The AWS CLI can be installed in 3 platforms Linux, Mac-OS and Windows , Since i have windows i will be installing the AWS-CLI Windows 
Reference: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
I have downloaded the AWS-CLI from https://awscli.amazonaws.com/AWSCLIV2.msi 

Step 1 : Click the link https://awscli.amazonaws.com/AWSCLIV2.msi where the AWS CLI MSI file will be downloaded

!.[install].Aws-Masterminds/_docs/assets/Screenshot 2023-02-18 082625

Step 2 : After successfully installing the AWS CLI i verified by typing the following cmd "aws" and i received the below output.

Step 3 : To verify if i'm able to connect to the AWS account , i required to configure the AWS key below are the steps i followed. 

  1. Go to aws management console 
  2. Login with the root account 
  3. Search IAM in the services "search" in Top left corner 
  4. click users on the left tab 
  5. create a user or click use the existing user 
  6. You wil find tabs like "Permissions", "Groups", "Tags", "SecurityCredentials", "Access Advisor" , Clck Security Credentials 
  7. Generate the access key as follows , Once the access key is generated in AWS cli type "aws configure" 
  8. Provide the AWS access key , Security token , Region and output format. 
  9. Region can be where you are located i choose region to be me-south-1 as i'm located in Bahrain 
  10. output format can be of 4 types Refernece : https://docs.aws.amazon.com/cli/latest/userguide/cli-usage-output-format.html
       1. json 
       2. yaml
       3. yam-stream
       4. text 
       5. table 
As Json is default for AWS-CLi i choose the json format.
