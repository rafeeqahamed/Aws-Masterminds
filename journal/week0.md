# Week 0 — Billing and Architecture

## Resetting the Password for user created. 

![Resetting Password](https://github.com/rafeeqahamed/Aws-Masterminds/blob/main/journal/asset/change%20user%20password.png)


## Install AWS CLI
The AWS CLI can be installed in 3 platforms Linux, Mac-OS and Windows , Since i have windows i will be installing the AWS-CLI Windows 
Reference: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

I have downloaded the AWS-CLI from https://awscli.amazonaws.com/AWSCLIV2.msi 

![Installation of AWS_CLI](https://github.com/rafeeqahamed/Aws-Masterminds/blob/main/journal/asset/Screenshot%202023-02-18%20082625.png)

![Installtion Completed](https://github.com/rafeeqahamed/Aws-Masterminds/blob/main/journal/asset/Screenshot%202023-02-18%20082815.png)

Step 1 : Click the link https://awscli.amazonaws.com/AWSCLIV2.msi where the AWS CLI MSI file will be downloaded
 
Step 2 : After successfully installing the AWS CLI i verified by typing the following cmd "aws" and i received the below output.

Step 3 : To verify if i'm able to connect to the AWS account , i required to configure the AWS key below are the steps i followed. 

  1. Go to aws management console 
  2. Login with the root account 
  3. Search IAM in the services "search" in Top left corner 
  4. click users on the left tab 
  5. create a user or click use the existing user 
  6. You wil find tabs like "Permissions", "Groups", "Tags", "SecurityCredentials", "Access Advisor" , Clck Security Credentials 
  7. 
  ![Access_Key](https://github.com/rafeeqahamed/Aws-Masterminds/blob/main/journal/asset/Screenshot%202023-02-18%20084004.png)
  
  8. Generate the access key as follows , Once the access key is generated in AWS cli type "aws configure" 
  9. Provide the AWS access key , Security token , Region and output format. 
  10. Region can be where you are located i choose region to be me-south-1 as i'm located in Bahrain 
  11. output format can be of 4 types Refernece : https://docs.aws.amazon.com/cli/latest/userguide/cli-usage-output-format.html
       1. json 
       2. yaml
       3. yam-stream
       4. text 
       5. table 
As Json is default for AWS-CLi i choose the json format.

aws --cli-auto-prompt is very useful to find which cmd you would like to execute 

## Architecture Diagram in Lucid Chard 

Below is the link for the archiectural diagram. 
https://lucid.app/lucidchart/82cbeaa2-836c-41c0-81f2-fd68722c77f7/edit?viewport_loc=-48%2C-335%2C2219%2C1079%2C0_0&invitationId=inv_ec9f7d4d-328d-45f4-a01a-cb700a59c898
