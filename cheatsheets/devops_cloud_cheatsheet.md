### **DevOps & Cloud Cheatsheet**

This document provides a quick reference for common commands, tools, and concepts in the world of DevOps and Cloud Computing.

---

### 1. Version Control (Git)
Git is essential for tracking code changes and collaboration.

#### **Basic Commands**
```

# Initialize a new Git repository

git init

# Clone a remote repository

git clone [repository\_url]

# Add a file to the staging area

git add [file\_name]

# Commit staged changes with a message

git commit -m "Your commit message"

# Push changes to a remote repository

git push origin [branch\_name]

# Pull the latest changes from a remote repository

git pull origin [branch\_name]

```

---

### 2. Containerization (Docker)
Docker packages applications and their dependencies into a standardized unit called a container.

#### **Basic Commands**
```

# Build a Docker image from a Dockerfile

docker build -t [image\_name] .

# List all Docker images

docker images

# Run a container from an image

docker run -d -p 8080:80 [image\_name]

# List all running containers

docker ps

# Stop a running container

docker stop [container\_id]

# Remove a container

docker rm [container\_id]

# Push an image to a registry (like Docker Hub)

docker push [registry]/[image\_name]

```

---

### 3. Orchestration (Kubernetes)
Kubernetes (K8s) is an open-source system for automating the deployment, scaling, and management of containerized applications.

#### **Basic Commands (kubectl)**
```

# Get information about a resource (pods, services, deployments)

kubectl get pods

# View the detailed status of a resource

kubectl describe pod [pod\_name]

# Apply a configuration from a file (e.g., a YAML file)

kubectl apply -f [file\_name]

# Delete a resource

kubectl delete deployment [deployment\_name]

# View container logs

kubectl logs [pod\_name]

```

---

### 4. Infrastructure as Code (IaC)
IaC manages and provisions infrastructure through code rather than manual processes. This ensures consistency and repeatability.

#### **Key Concepts**
* **Terraform:** A popular open-source IaC tool that allows you to manage resources across multiple cloud providers (AWS, Azure, GCP).
* **AWS CloudFormation:** AWS's native IaC service for managing AWS resources.
* **Azure Resource Manager (ARM) / Bicep:** Azure's native IaC services.
* **Ansible:** An automation tool that can be used for configuration management and provisioning.

---

### 5. Continuous Integration / Continuous Deployment (CI/CD)
CI/CD is a methodology to deliver apps to customers by introducing automation into the stages of app development.

#### **Key Concepts**
* **CI (Continuous Integration):** Developers merge code changes into a central repository. Automated tests and builds are then run.
* **CD (Continuous Delivery/Deployment):** The process of automatically releasing validated code to a repository, ready for deployment (Delivery) or automatically deploying it to production (Deployment).

#### **Common Tools**
* **Jenkins:** A popular, open-source automation server.
* **GitLab CI/CD:** Built-in CI/CD for GitLab repositories.
* **GitHub Actions:** A built-in CI/CD service for GitHub repositories.
* **Azure Pipelines:** Part of Azure DevOps, used for CI/CD.

---

### 6. Cloud Computing Services (AWS, Azure, GCP)
The following are general categories of services you'll encounter on major cloud platforms.

#### **Common Services**
* **Compute:** Provides virtual servers to run applications (e.g., **AWS EC2**, **Azure VMs**, **GCP Compute Engine**).
* **Storage:** Provides different types of storage for data (e.g., **AWS S3** for objects, **Azure Blob Storage**, **GCP Cloud Storage**).
* **Database:** Offers managed database services (e.g., **AWS RDS**, **Azure SQL Database**, **GCP Cloud SQL**).
* **Networking:** Manages virtual networks and connectivity (e.g., **AWS VPC**, **Azure VNet**, **GCP VPC**).
```
