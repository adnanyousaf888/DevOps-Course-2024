# DevOps-Course-2024

This repository houses the work completed for the DevOps Course 2024 assignment, featuring:
- A Guide to Learning and Contributions
- Blog Summaries
- A sample repository sourced online with applied DevOps tools
- Expanded guidance based on existing knowledge
- A sample landing page showcasing my CV

## A Guide to Learning and Contribution:

I’ve always been curious about how modern software systems are built, deployed, and managed. This curiosity has led me to explore DevOps through hands-on projects, research, and writing. Below is an overview of what I’ve learned and contributed so far.

### 1. Sharing Knowledge: Writing Blogs on DevOps Topics
Alongside gaining practical experience, I’ve written a few blog articles to share what I’ve learned and help others in the DevOps community.

- [Optimize Your Workflow: Configuring Multiple GitHub Accounts on a Single Machine with SSH](https://medium.com/@adnanyousaf1357/optimize-your-workflow-configuring-multiple-github-accounts-on-a-single-machine-with-ssh-b59c81e3c859 "Optimize Your Workflow: Configuring Multiple GitHub Accounts on a Single Machine with SSH")

This guide explains how to manage multiple GitHub accounts, both personal and work, on a single machine using SSH. The process begins with generating separate SSH keys for each account, ensuring that each key is associated with a specific GitHub account. Once the keys are generated, the next step is to upload the public SSH keys to their respective GitHub accounts through the Settings → SSH and GPG keys section. To streamline the process, an SSH config file is then created to specify which key to use for each account, enabling smooth switching between personal and work profiles. When cloning repositories, the configured aliases are used to ensure the correct key is applied. Finally, it’s important to test the SSH setup by verifying the connection to both personal and work accounts. This configuration simplifies managing multiple GitHub accounts, improving both security and workflow efficiency.

- [Creating an EKS Cluster on AWS with Terraform: A Comprehensive Tutorial](https://medium.com/@adnanyousaf1357/creating-an-eks-cluster-on-aws-with-terraform-a-comprehensive-tutorial-08f201e803dd "Creating an EKS Cluster on AWS with Terraform: A Comprehensive Tutorial")

This guide provides a thorough, step-by-step tutorial on deploying an Amazon EKS cluster on AWS using Terraform. It takes you through the entire process, starting with setting up prerequisites and writing Terraform configurations, and continuing with initializing and applying the deployment. Key topics covered include configuring the AWS CLI, setting up a Virtual Private Cloud (VPC) for EKS, deploying Kubernetes resources, and connecting to the cluster using kubectl. The guide wraps up by showing how to deploy a sample application and clean up resources, emphasizing how Terraform simplifies the automation and scalability of Kubernetes infrastructure on AWS.


- Spring Petclinic (Java Web Application) with Github Actions and Docker

This project is a guide to setting up a CI/CD pipeline for the Spring PetClinic application. It starts by cloning the repository and verifying it builds locally. Then, it guides you through creating a workflow file on GitHub Actions to automate building, testing, and deploying the application. The workflow includes stages for building with Maven, running tests, building a Docker image, and optionally pushing it to a container registry. Finally, it mentions the possibility of extending the pipeline to automatically deploy the application to various platforms.


### 2. My Continuous Learning Path
Moving forward, I want to deepen my DevOps knowledge by exploring new areas:

 - **Infrastructure as Code (IaC):** I’m diving into tools like Terraform and Ansible to automate infrastructure setup and management.
 - **Advanced Monitoring and Observability:** Tools like Prometheus, Grafana, and the ELK stack are next on my list to help monitor and improve system performance.
 - **Security and Compliance:** I’m learning more about DevSecOps to integrate security into every step of the development pipeline.
Through continuous learning and hands-on projects, I aim to keep growing in DevOps and contribute to the field as I develop into a skilled DevOps engineer.


### Skills and Tools

- Service Mesh: Istio
- Version Control: Git
- Policy Management: Kyverno
- Cluster Management: Amazon-EKS, Minikube
- Containerization: Docker, Knative, Kubernetes


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

### Links to Blogs
Blog 01: https://medium.com/@adnanyousaf1357/optimize-your-workflow-configuring-multiple-github-accounts-on-a-single-machine-with-ssh-b59c81e3c859

Blog 02: https://medium.com/@adnanyousaf1357/creating-an-eks-cluster-on-aws-with-terraform-a-comprehensive-tutorial-08f201e803dd



## Applying DevOps tooling

## Spring Petclinic (Java Web Application) with Github Actions and Docker

This guide outlines how to establish a CI/CD pipeline for Spring PetClinic application using GitHub Actions. This pipeline will automate building, testing, and (optionally) deploying your application, ensuring a streamlined development workflow.

### Prerequisites

- A GitHub account
- Basic understanding of Git and GitHub (navigating repositories, editing files)
- Familiarity with YAML syntax (GitHub Actions workflows are written in YAML)
- Java Development Kit (JDK) 11 installed locally (optional for local testing)
- Docker installed locally (optional for Dockerizing the application)

### Step 1: Clone the Repository
- Clone the Spring PetClinic repository to your local machine.

### Step 2: Explore the Project Structure
- Verify the project builds and runs successfully by executing:

![image](https://github.com/user-attachments/assets/7f665eaa-3dc6-481d-8c87-fbf43d2bffd0)

- This will ensure that the local setup works before adding CI/CD tooling.

### Step 3: Set Up CI/CD Pipeline with GitHub Actions
- Create a GitHub Actions Workflow File:

In the cloned repository, create a .github/workflows/ci.yml file.

![image](https://github.com/user-attachments/assets/4cf06f35-ff08-407f-8e25-2dbc243e39f0)

This file will define your CI/CD pipeline. You can start with a basic workflow to build and test the project:

### Step 4: Dockerize the Application
- Create a Dockerfile to package the application into a Docker container:

![image](https://github.com/user-attachments/assets/732017d1-3e72-4655-9b12-6f201d214573)


- Add this to your repository, build the Docker image, and test it locally:

![image](https://github.com/user-attachments/assets/81fa9ce6-7835-4b0b-a075-dbca4aa3912c)

### Step 5: Extend CI/CD to Build and Push Docker Image
- In the GitHub Actions workflow, add a step to build and push the Docker image to a container registry (e.g., Docker Hub, GitHub Container Registry).

![image](https://github.com/user-attachments/assets/0459bfa2-f2c7-4df0-96d0-fb2f3cd77dba)

- Store Docker credentials in GitHub Secrets for secure access.


## My Resume

You can view my Resume by using the link below:


