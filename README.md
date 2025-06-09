# AWS IAM Custom Policies

This repository contains a collection of custom IAM policies designed to follow the **Principle of Least Privilege**. Each policy grants only the necessary permissions for specific tasks, improving security and manageability in AWS environments.

## 🔐 Purpose

- Promote secure IAM practices
- Provide reusable, production-ready IAM policies
- Help developers and DevOps teams assign minimal permissions for specific use cases

## 🚀 Usage

1. Browse the policy JSON files in this repository.
2. Copy and paste the policy into the AWS Console, AWS CLI, or your infrastructure as code (IaC) tool like Terraform.
3. Review and modify the resource ARNs and conditions to fit your environment.

## 📌 Best Practices

- Always tailor policies to specific users, roles, or resources.
- Avoid using `"Action": "*"` or `"Resource": "*"` unless absolutely required.
- Review policies periodically to remove unused or over-privileged access.

## 📄 License

This project is open-source and licensed under the MIT License.
