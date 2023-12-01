Create a private repo on Github
Create branch named EC2 in private repo 
Provide access to the private repo
Write a terraform file to create EC2 instance with hard coded values
Clone the private repo using Git bash
Run terraform code on Visual Studio to provision the resource and destroy the same
Update the terraform code to make use of variables and push the changes to Github using git bash
Add collaborator on Github, add a new branch called S3, add S3.tf file, use pull request and approver role to commit changes
Pull new branch and files to local and create EC2 instance & S3 bucket
    Use output command for instance ID and bucket name
Create local modules to provision VPC and attach to the instance created earlier
    Use output command for VPC ID
Write a code to create public subnet and private subnet and attach to the VPC created earlier
Write a code to create remote modules to provision IGW, NAT, Routing tables and attach to the resources created earlier
Write a code to create terraform statefile in S3 bucket and attach DynamoDB, perform excecution simultaneously on 2 terminals to verify file lock status
