# Amazon EKS Blueprints for Terraform - Use Existing VPC and Security Groups

This is a fork of the existing [Amazon EKS Blueprints for Terraform](https://github.com/aws-ia/terraform-aws-eks-blueprints) project, and has been modified to demonstrate how to use Terraform to create an EKS cluster when you are required to use an existing VPC and Security Groups.

## Prerequisites

- Provision a VPC. I used this [cloudformation](https://s3.us-west-2.amazonaws.com/amazon-eks/cloudformation/2020-10-29/amazon-eks-vpc-private-subnets.yaml) template which provisions a VPC with public and private subnets. Link came from [here](https://docs.aws.amazon.com/eks/latest/userguide/creating-a-vpc.html).
- Become familiar with the need for [subnet tagging](https://docs.aws.amazon.com/eks/latest/userguide/network_reqs.html#vpc-subnet-tagging).

## How to deploy

Reference the `README.md` file in the `examples/existing-vpc-and-sgs` directory.
