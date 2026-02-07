# AWS-VPC---Cloud-Networking-

Hands-on AWS Cloud Networking Project,VPC Design & Security Implementation

Over the past few days, I built and secured a complete Virtual Private Cloud (VPC) on Amazon Web Services (AWS) from the ground up, simulating how real organizations design their cloud networks with layered security.

Here’s what I achieved :

Network Architecture:
- Created a custom VPC with Public and Private Subnets.
- Configured Route Tables and an Internet Gateway (IGW) for Internet access.
- Implemented NAT Gateway to enable secure outbound access from private servers.
- Designed two-tier architecture (Public EC2 as Bastion / Private EC2 as Backend)

Security Controls:
- Applied Security Groups (SGs) for instance-level firewalls.
- Built Network ACLs (NACLs) for subnet-level access control.
- Enabled VPC Flow Logs and CloudWatch integration for traffic monitoring
- Integrated CloudTrail for auditing API activity.
- Implemented encryption using AWS KMS for secure log storage.

This project helped me connect the dots between networking, security, and monitoring and gave me a real appreciation for the layered defense that underpins modern cloud infrastructures.
