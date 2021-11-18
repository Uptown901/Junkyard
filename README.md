# Junkyard
# Step-01: Introduction
- What are Terraform Input Variables ?
- How many ways we can define Terraform Input Variables ?
- Learm about `Input Variables - Basics`

## Step-02: Input Variables Basics 
- Create / Review the terraform manifests
1. c1-versions.tf
2. c2-variables.tf
3. c3-resource-group.tf
4. c4-virtual-network.tf
- We are going to define `c2-variables.tf` and define the below listed variables
```t
# Input Variables
# 1. Business Unit Name
variable "business_unit" {
  description = "Business Unit Name"
  type = string
  default = "hr"
}
# 2. Environment Name
variable "environment" {
  description = "Environment Name"
  type = string
  default = "dev"
}
hhh
