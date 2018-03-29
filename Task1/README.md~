# AWS Cloudformation template

## Stack

This is LAMP Stack
- Amazon Linux 2017.03
- Apache 2
- MySQL 5.6
- PHP 7.0

## Architecture

Highly availabile and scalable secure architecture includes

- VPC on 2 Availability Zones with 2 public subnets and 2 private subnets
- 2 NATGateways (1 Gateway per availability zone)
- Multi-AZ RDS MySQL Cluster GP2 EBS deployed into private subnets
- Cross-Zone internet-facing Application ELB deployed into public subnets
- EC2 AutoScaling Group deployed into private subnets
- Security Group allowing HTTP Traffics from Internet to ELB only
- Security Group allowing HTTP Traffics between ELB and EC2 only
- Security Group allowing traffics between EC2 and RDS MySQL Cluster only
- SNS Notification for scaling events


## Contents 
  1.Created CloudFormation template for highly available and scalable LAMP Stack Deployment

  2.Uploaded lamp.cf.template.json to s3 bucket

  3.While creating LAMP we need to chose above template.

  4.Then we need to pass application parameters and DB parameters.

     Example:
             1.Application user name and password
             2.DB User root password.











