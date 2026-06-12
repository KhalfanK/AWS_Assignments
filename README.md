# AWS Assignments

Welcome to this repository! Having recently completed my foundational module in Amazon Web Services (AWS), this space will be used as my hands-on sandbox where I document AWS infrastructure I create.

# Projects

So far There are two assignments in this repo which I have completed a breakdown for:
- [Assignment 1: VPC, Subnets, IGW, NATGW](./README.md)
- [Assignment 2: EC2 Instances behind Load Balancer](./README.md)

# Thoughts

It has been incredibly rewarding putting pen to paper and turning theoretical cloud concepts into functioning infrastructure. I did have some hiccups, for example, I spent a chunk of time troubleshooting why I couldn't connect to an EC2 instance inside my custom VPC. After combing through the entire network path, it turned out to be a classic rookie mistake, I had forgotten to configure the inbound rules on the Security Group 😅. While humbling, troubleshooting that issue was the best way to learn. It forced me to deeply understand how VPC networking, routing, and security components interact.

# What's Next?

Now that I have a solid grasp of how these services connect via "ClickOps" (the AWS Management Console), my next goal is to move away from manual configuration. Learning to automate building AWS infrastructure using Terraform as Infrastructure as Code (IaC).
