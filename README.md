# Terraform module of  AWS - EC2 Security Group - Just for learn purpose!!!

All terraform modules from my repositories is only for learn purpose, so it can be broken, incomplete or not working well!

So if you use that code be careful and you will be at your own!!! Good lucky!!!

Terraform doc: https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket

# What is an EC2 Security Group?
A security group acts as a virtual firewall for your EC2 instances to control incoming and outgoing traffic. Inbound rules control the incoming traffic to your instance, and outbound rules control the outgoing traffic from your instance. When you launch an instance, you can specify one or more security groups. If you don't specify a security group, Amazon EC2 uses the default security group. You can add rules to each security group that allow traffic to or from its associated instances. You can modify the rules for a security group at any time. New and modified rules are automatically applied to all instances that are associated with the security group. When Amazon EC2 decides whether to allow traffic to reach an instance, it evaluates all of the rules from all of the security groups that are associated with the instance.

Source of information: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security-groups.html

# And how can I use this in the Datalake?
Any resources that security group is available you should use, like ec2 instances, rds databases and other services...

# Motivation
I wrote a lot of codes using terraform modules and for each individual project I had to replicated the modules.

Therefore as terraform accept to work with remote repositories I decided to use github as my source of terraform modules.

# About the project
This project just store the common git files (license and readme.md) and terraform files (main, var and output).