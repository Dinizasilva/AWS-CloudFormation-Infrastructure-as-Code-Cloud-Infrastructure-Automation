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

This project demonstrates how AWS CloudFormation can be used to provision and manage cloud infrastructure through **Infrastructure as Code (IaC)**.

The infrastructure was defined using **YAML templates**, allowing AWS resources to be created and updated from a single declarative configuration instead of being provisioned individually through the AWS Management Console.

The environment was built progressively, starting with an **Amazon VPC and Security Group**, followed by the addition of an **Amazon S3 bucket** and an **Amazon EC2 instance**.

During the implementation, the CloudFormation template was updated to add new resources while preserving the existing infrastructure. **CloudFormation intrinsic functions such as `!Ref`** were used to reference resources within the template, and **AWS Systems Manager Parameter Store** was used to retrieve the Amazon Linux AMI dynamically.

The project also covered the complete lifecycle of the CloudFormation stack, from initial deployment and updates to the final removal of the infrastructure.

**CREATE → UPDATE → DELETE**

This project provided practical experience with **AWS infrastructure automation, Infrastructure as Code, resource dependencies, cloud networking, compute, storage, and infrastructure lifecycle management**.
