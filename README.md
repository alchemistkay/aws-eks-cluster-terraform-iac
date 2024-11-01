# Infrastructure as Code (IaC): AWS EKS Cluster with Terraform

This project demonstrates the use of **Infrastructure as Code (IaC)** principles with **Terraform** to provision, manage, and scale multiple **Kubernetes (EKS) environments on AWS**. This repository is a DevOps portfolio project showcasing how to automate and standardize the infrastructure setup and management for production, development, staging, and testing environments using Terraform and CI/CD with Jenkins.

---

## Overview

In this project, I:
- Created a **Terraform project** to provision a **Kubernetes (EKS) cluster on AWS**.
- Set up **multiple identical environments** (production, development, test, and staging) using the same Terraform configurations.
- Automated the provisioning of **MySQL with persistent storage** in Kubernetes using Helm.
- Configured **remote state management** using an **S3 bucket** for state sharing across team members.
- Built a **CI/CD pipeline with Jenkins** to automate the deployment and management of infrastructure changes.

---

## Project Goals

This project highlights my understanding of:
- **Infrastructure as Code (IaC)** for provisioning and managing resources.
- **Scalability** and **environment consistency** by using automation tools.
- Leveraging **AWS EKS** to provide scalable Kubernetes environments.
- **CI/CD pipelines** to streamline infrastructure deployment.

---

## Features

### 1. **Terraform Project for EKS Cluster Setup**
- The Terraform configuration provisions an **EKS cluster** with 3 managed nodes and a Fargate profile, allowing AWS to manage part of the infrastructure.
- Configured for deploying a **Java Gradle application**.

### 2. **MySQL Deployment with Persistent Storage**
- Used **Helm** to deploy a **MySQL database** in Kubernetes with 3 replicas.
- Configured **AWS EBS CSI Driver** and persistent storage volumes for data durability and reliability.

### 3. **Remote State Management**
- Configured **Terraform remote state storage** with an **AWS S3 bucket** to allow team collaboration and maintain consistent infrastructure state.
- Remote state storage allows for centralized state management, making it easier for the team to collaborate and maintain infrastructure integrity.

### 4. **Jenkins CI/CD Pipeline for Terraform Project**
- Implemented a **CI/CD pipeline in Jenkins** to:
  - Trigger infrastructure changes automatically.
  - Run Terraform plan and apply stages for automated deployment and management.
  - Separate infrastructure changes from application changes, ensuring efficient workflows for both application and platform teams.

---

## Technology Stack

- **Terraform**: Tool for Infrastructure as Code, provisioning and managing AWS resources declaratively.
- **AWS EKS**: Managed Kubernetes service for running containerized applications.
- **AWS S3**: Object storage service used for remote state storage.
- **AWS EBS**: Elastic Block Store used for persistent storage with Kubernetes.
- **Helm**: Kubernetes package manager for managing application deployment.
- **Jenkins**: CI/CD automation server for continuous integration and deployment.
- **Docker**: Containerization platform for building and deploying applications.

---

## Conclusion

This project demonstrates my ability to:
- Use Infrastructure as Code (IaC) with Terraform to automate cloud resource provisioning.
- Configure Kubernetes clusters on AWS EKS for multiple environments
- Implement remote state management for team collaboration.
- Set up a CI/CD pipeline with Jenkins to automate infrastructure deployment.

By following these practices, I ensure consistent, reliable, and scalable infrastructure management, making it easier for teams to maintain and deploy resources effectively.


