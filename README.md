# AWS Policy as Code with Ansible

This project implements **Policy as Code (PaC)** on AWS using **Ansible** to automate compliance and security policies. The playbook enforces versioning on all S3 buckets in the AWS account to ensure data protection and compliance with best practices.

Policy as Code (PaC) in DevSecOps refers to the practice of defining and managing security policies through code. This approach enables automated, consistent, and scalable enforcement of security controls and compliance requirements across the software development lifecycle.

---

## Project Overview

The Ansible playbook automates the following tasks:
- Lists all S3 buckets in the AWS account.
- Enables versioning for any S3 bucket where versioning is not already enabled.

By using Ansible, this project simplifies managing AWS policies, ensuring consistency and automation across cloud resources.

## Tools

- **Ansible**
- **AWS**
- **S3**

