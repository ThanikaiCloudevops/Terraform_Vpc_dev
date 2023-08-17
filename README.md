# Terraform VPC-3 Project
![Logo](data:image/png;base64,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) 

This project demonstrates the use of Terraform to create a multi-tier Virtual Private Cloud (VPC) environment in AWS.

**Overview**
<summary>
  
This Terraform project illustrates the creation of a multi-tier VPC in AWS, including public and private subnets,database subnets,security groups,application loadbalancer along with network configurations that ensure security and isolation across different tiers

</summary>





