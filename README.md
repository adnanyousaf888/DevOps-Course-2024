# DevOps-Course-2024

This repository houses the work completed for the DevOps Course 2024 assignment, featuring:
- A Guide to Learning and Contributions
- Blog Summaries
- A sample repository sourced online with applied DevOps tools
- Expanded guidance based on existing knowledge
- A sample landing page showcasing my CV


## Blog Summaries
### Blog 01:

This guide explains how to manage multiple GitHub accounts (personal and work) on the same machine with SSH. Key steps include:

- Generate SSH Keys: Create separate SSH keys for each GitHub account using specific commands for personal and work accounts.
- Add SSH Keys to GitHub: Upload each public SSH key to its respective GitHub account via Settings → SSH and GPG keys.
- Configure SSH for Multiple Keys: Set up an SSH config file to define which key to use for each account, ensuring a smooth switch between them.
- Clone Repositories Using Aliases: Use the configured aliases to clone repositories for the respective accounts.
- Test SSH Setup: Verify your SSH configuration by testing the connection for both personal and work accounts.
This setup streamlines account management, improving both security and workflow efficiency.


### Blog 02:
This guide provides a comprehensive, step-by-step tutorial for deploying an Amazon EKS cluster on AWS using Terraform. It covers the entire process from setting up prerequisites and writing Terraform configurations to initializing and applying the deployment.

#Key sections:
It includes configuring the AWS CLI, setting up a Virtual Private Cloud (VPC) for EKS, deploying Kubernetes resources, and connecting to the cluster with kubectl. The guide concludes with instructions for deploying a sample application and cleaning up resources, highlighting how Terraform simplifies the automation and scalability of Kubernetes infrastructure on AWS.
