# AWS EC2 AMI Backup and Restore Project

## Objective

Demonstrate backup and disaster recovery using Amazon Machine Images (AMI).

## Services Used

- Amazon EC2
- Amazon AMI
- SSH

## Architecture

Source EC2 Instance
→ AMI Backup
→ Restored EC2 Instance

## Steps Performed

1. Created EC2 instance
2. Connected using SSH
3. Created example.txt file
4. Added content "Hello"
5. Created AMI
6. Launched new EC2 from AMI
7. Verified file restoration

## Validation

File restored successfully:

example.txt

Content:

Hello

## Learning Outcomes

- EC2 imaging
- Backup strategy
- Disaster Recovery
- Instance restoration
- Golden Image concept
