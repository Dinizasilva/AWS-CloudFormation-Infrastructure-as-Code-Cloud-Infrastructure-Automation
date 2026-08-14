## AWS-CloudFormation-Infrastructure-as-Code-Cloud-Infrastructure-Automation

** Designing, provisioning and managing AWS infrastructure using declarative YAML templates** 

<div align="center">

![AWS](https://img.shields.io/badge/AWS-Cloud%20Infrastructure-232F3E?logo=amazonaws&logoColor=white)
![CloudFormation](https://img.shields.io/badge/AWS%20CloudFormation-IaC-FF9900?logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/Amazon%20EC2-Compute-FF9900?logo=amazonec2&logoColor=white)
![S3](https://img.shields.io/badge/Amazon%20S3-Storage-569A31?logo=amazons3&logoColor=white)
![VPC](https://img.shields.io/badge/Amazon%20VPC-Networking-8C4FFF?logo=amazonaws&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-Template-000000?logo=yaml&logoColor=white)
![Infrastructure as Code](https://img.shields.io/badge/Infrastructure%20as%20Code-IaC-623CE4)

![English](https://img.shields.io/badge/Documentation-English-1E88E5)
![Português](https://img.shields.io/badge/Documentação-Português-2E7D32)

</div>

## Cloud Engineering • Infrastructure as Code • Infrastructure Automation • AWS Solutions



<p align="center">
  <img src="./capa-lab-cloudformation.png" alt="Capa do Lab CloudFormation" width="650">

</p>

## Overview

This project demonstrates the design, deployment, and lifecycle management of AWS cloud infrastructure using **AWS CloudFormation** and **Infrastructure as Code (IaC)** principles.

Instead of provisioning resources individually through the AWS Management Console, the infrastructure was defined declaratively using **YAML templates**, enabling a more consistent, repeatable, and automated approach to cloud resource management.

The solution progressively builds an AWS environment by provisioning and integrating networking, security, storage, and compute resources, including an **Amazon VPC, Security Group, Amazon S3 bucket, and Amazon EC2 instance**.

The CloudFormation stack was also updated throughout the implementation to demonstrate how cloud infrastructure can evolve without manually recreating existing resources. Resource dependencies were managed using CloudFormation intrinsic functions such as `!Ref`, while **AWS Systems Manager Parameter Store** was used to dynamically retrieve the Amazon Linux AMI.

The project concludes with the controlled deletion of the CloudFormation stack, demonstrating the complete infrastructure lifecycle:

**CREATE → UPDATE → MANAGE → DELETE**

This hands-on implementation reinforces core **Cloud Engineering and Cloud Solutions** concepts, including infrastructure automation, declarative provisioning, resource orchestration, dependency management, and infrastructure lifecycle management.

