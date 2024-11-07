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

#### Key sections:

It includes configuring the AWS CLI, setting up a Virtual Private Cloud (VPC) for EKS, deploying Kubernetes resources, and connecting to the cluster with kubectl. The guide concludes with instructions for deploying a sample application and cleaning up resources, highlighting how Terraform simplifies the automation and scalability of Kubernetes infrastructure on AWS.

# Links to Blogs
Blog 01: https://medium.com/@adnanyousaf1357/optimize-your-workflow-configuring-multiple-github-accounts-on-a-single-machine-with-ssh-b59c81e3c859

Blog 02: https://medium.com/@adnanyousaf1357/creating-an-eks-cluster-on-aws-with-terraform-a-comprehensive-tutorial-08f201e803dd

## Guide to Learning and Contribution:

I’ve always been curious about how modern software systems are built, deployed, and managed. This curiosity has led me to explore DevOps through hands-on projects, research, and writing. Below is an overview of what I’ve learned and contributed so far.

### 1. Sharing Knowledge: Writing Blogs on DevOps Topics
Alongside gaining practical experience, I’ve written a few blog articles to share what I’ve learned and help others in the DevOps community.

- [Optimize Your Workflow: Configuring Multiple GitHub Accounts on a Single Machine with SSH](https://medium.com/@adnanyousaf1357/optimize-your-workflow-configuring-multiple-github-accounts-on-a-single-machine-with-ssh-b59c81e3c859 "Optimize Your Workflow: Configuring Multiple GitHub Accounts on a Single Machine with SSH")
This blog covers the basics of Continuous Integration (CI) and Continuous Delivery (CD), and how Jenkins can automate these processes. I explain how CI/CD speeds up software delivery, reduces issues, and improves quality by automating builds, tests, and deployments.

- **Knative**:
Simplifying Serverless Architectures on Kubernetes: Here, I introduced Knative, a Kubernetes platform that helps build serverless, event-driven applications. The blog highlights how Knative makes serverless computing simpler, more scalable, and cost-effective, all while using Kubernetes.

### 2. My Continuous Learning Path
Moving forward, I want to deepen my DevOps knowledge by exploring new areas:

 - **Infrastructure as Code (IaC):** I’m diving into tools like Terraform and Ansible to automate infrastructure setup and management.
 - **Advanced Monitoring and Observability:** Tools like Prometheus, Grafana, and the ELK stack are next on my list to help monitor and improve system performance.
 - **Security and Compliance:** I’m learning more about DevSecOps to integrate security into every step of the development pipeline.
Through continuous learning and hands-on projects, I aim to keep growing in DevOps and contribute to the field as I develop into a skilled DevOps engineer.
