# Deploy AWS Dev Environment using CloudFormation Template

## Introduction

In this project I deployed EC2 instance as a web server in AWS. I also deployed VPC, Subnets, Elastic IP address, Internet Gateway, Custom Route table and Security group. All the resources have been created using CloudFormation. Please find the architecure of this project below.

![](https://github.com/AbiVavilala/CloudFormation-deployment-AWS/blob/main/pics/architecturenew.png)

## Upload the template to AWS

I will upload Cloudinfra.yml to AWS Cloud Formation

![](https://github.com/AbiVavilala/CloudFormation-deployment-AWS/blob/main/pics/uploadtemplate.png)


I will give parameter values AMIID and Environment name

![](https://github.com/AbiVavilala/CloudFormation-deployment-AWS/blob/main/pics/parameters.png)

you can leave configure option as default and click next. Then click on Submit your template
![](https://github.com/AbiVavilala/CloudFormation-deployment-AWS/blob/main/pics/submit.png)

Under Events you can see creation in progress

![](https://github.com/AbiVavilala/CloudFormation-deployment-AWS/blob/main/pics/creationinprogress.png)

Under resource you can see resource created

![](https://github.com/AbiVavilala/CloudFormation-deployment-AWS/blob/main/pics/resourcescreated.png)

## Let's see the resource created in the portal

We can see VPC resources created in console

![](https://github.com/AbiVavilala/CloudFormation-deployment-AWS/blob/main/pics/VPCresourcescreated.png)

We can see EC2 instance created in Console

![](https://github.com/AbiVavilala/CloudFormation-deployment-AWS/blob/main/pics/webservercreated.png)

## Access the webserver

Let's access the server 

![](https://github.com/AbiVavilala/CloudFormation-deployment-AWS/blob/main/pics/accessserver.png)









