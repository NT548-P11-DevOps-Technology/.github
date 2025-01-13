# NT548-P11-DevOps-Technology Organization

Welcome to the GitHub organization for the **NT548-P11-DevOps-Technology** team. This organization hosts repositories for our project titled **Implementing a DevSecOps Model for a High Availability CI/CD System in a Microservices Environment**. Below, you'll find an overview of each repository and its purpose.

## Microservices Repositories

These repositories contain the source code for the microservices that make up the **Class Management** application:

### 1. [**class-management-FE**](https://github.com/NT548-P11-DevOps-Technology/class-management-FE)
- **Description**: Frontend application for the class management system.
- **Technologies**: React, TypeScript, TailwindCSS.
- **Purpose**: Provides a user interface for students, lecturers, and administrators to interact with the system.

### 2. [**class-management-auth-service**](https://github.com/NT548-P11-DevOps-Technology/class-management-auth-service)
- **Description**: Authentication and authorization service.
- **Technologies**: Node.js, Express, MongoDB.
- **Purpose**: Manages user authentication, authorization, and token issuance.

### 3. [**class-management-student-service**](https://github.com/NT548-P11-DevOps-Technology/class-management-student-service)
- **Description**: Handles operations related to student management.
- **Technologies**: Node.js, NestJS, PostgreSQL.
- **Purpose**: Manages student profiles, enrollment, and related functionality.

### 4. [**class-management-lecturer-service**](https://github.com/NT548-P11-DevOps-Technology/class-management-lecturer-service)
- **Description**: Manages lecturer-specific operations.
- **Technologies**: Node.js, NestJS, PostgreSQL.
- **Purpose**: Handles lecturer profiles, schedules, and course assignments.

### 5. [**class-management-class-service**](https://github.com/NT548-P11-DevOps-Technology/class-management-class-service)
- **Description**: Core service for managing class data.
- **Technologies**: Node.js, NestJS, PostgreSQL.
- **Purpose**: Manages class schedules, student lists, and attendance tracking.

## Infrastructure Repositories

These repositories manage the infrastructure and deployment of the application:

### 6. [**terraform-hub**](https://github.com/NT548-P11-DevOps-Technology/terraform-hub)
- **Description**: Contains Terraform scripts for infrastructure provisioning.
- **Technologies**: Terraform.
- **Purpose**: Automates the provisioning of cloud resources, including VPCs, subnets, EC2 instances, and other AWS services.

### 7. [**ansible-hub**](https://github.com/NT548-P11-DevOps-Technology/ansible-hub)
- **Description**: Houses Ansible playbooks for configuration management.
- **Technologies**: Ansible.
- **Purpose**: Automates the configuration of servers, including software installations and environment setups.

### 8. [**kubernetes-hub**](https://github.com/NT548-P11-DevOps-Technology/kubernetes-hub)
- **Description**: Contains Kubernetes manifests for deploying microservices.
- **Technologies**: Kubernetes, Helm.
- **Purpose**: Manages the deployment and scaling of microservices in the Kubernetes cluster.

## Organization Overview

Our organization aims to implement a streamlined DevSecOps workflow for high availability and efficiency. Below are two diagrams that illustrate the core processes:

<br>

<p align="center">
    <img src="../images/Infrastructure.png" alt="Provisioning & Configure Management"></img>
</p>

<br>

<p align="center">
    <img src="../images/CICD.png" alt="CI/CD pipeline architecture"></img>
</p>

## Contribution Guidelines

1. **Fork and Clone**: Fork the repository you want to contribute to and clone it to your local machine.
2. **Branch Naming**: Use descriptive branch names (e.g., `feature/add-authentication`, `fix/ui-bug`).
3. **Code Style**: Follow the coding standards specified in each repository's documentation.
4. **Pull Requests**: Create a pull request with a clear description of changes. Ensure all checks pass before requesting a review.
5. **Issues**: Report bugs and propose features using the Issues tab in each repository.

## Contact

For any questions or issues, please reach out to the team through the repository's Issues section or contact the organization administrators directly.

---

We hope this documentation helps you navigate our repositories efficiently. Thank you for visiting our organization!

