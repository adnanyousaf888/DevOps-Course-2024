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

This guide explains how to manage multiple GitHub accounts, both personal and work, on a single machine using SSH. The process begins with generating separate SSH keys for each account, ensuring that each key is associated with a specific GitHub account. Once the keys are generated, the next step is to upload the public SSH keys to their respective GitHub accounts through the Settings → SSH and GPG keys section. To streamline the process, an SSH config file is then created to specify which key to use for each account, enabling smooth switching between personal and work profiles. When cloning repositories, the configured aliases are used to ensure the correct key is applied. Finally, it’s important to test the SSH setup by verifying the connection to both personal and work accounts. This configuration simplifies managing multiple GitHub accounts, improving both security and workflow efficiency.

- [Creating an EKS Cluster on AWS with Terraform: A Comprehensive Tutorial](https://medium.com/@adnanyousaf1357/creating-an-eks-cluster-on-aws-with-terraform-a-comprehensive-tutorial-08f201e803dd "Creating an EKS Cluster on AWS with Terraform: A Comprehensive Tutorial")

This guide provides a thorough, step-by-step tutorial on deploying an Amazon EKS cluster on AWS using Terraform. It takes you through the entire process, starting with setting up prerequisites and writing Terraform configurations, and continuing with initializing and applying the deployment. Key topics covered include configuring the AWS CLI, setting up a Virtual Private Cloud (VPC) for EKS, deploying Kubernetes resources, and connecting to the cluster using kubectl. The guide wraps up by showing how to deploy a sample application and clean up resources, emphasizing how Terraform simplifies the automation and scalability of Kubernetes infrastructure on AWS.

### 2. My Continuous Learning Path
Moving forward, I want to deepen my DevOps knowledge by exploring new areas:

 - **Infrastructure as Code (IaC):** I’m diving into tools like Terraform and Ansible to automate infrastructure setup and management.
 - **Advanced Monitoring and Observability:** Tools like Prometheus, Grafana, and the ELK stack are next on my list to help monitor and improve system performance.
 - **Security and Compliance:** I’m learning more about DevSecOps to integrate security into every step of the development pipeline.
Through continuous learning and hands-on projects, I aim to keep growing in DevOps and contribute to the field as I develop into a skilled DevOps engineer.

# Skills and Tools
Service Mesh: Istio
Version Control: Git
Policy Management: Kyverno
Cluster Management: Amazon-EKS, Minikube
Containerization: Docker, Knative, Kubernetes




