# Projects To understand them all

## Docker

### Project 1: Basic Docker Container

Objective: Learn the basics of Docker by creating and running a simple container.

#### Tasks:

- Install Docker.
- Pull a Docker image from Docker Hub.
- Run a container from the pulled image.
- Interact with the container.

#### Learning Outcomes:

Understanding Docker installation and basic commands.
Running and managing Docker containers.

### Project 2: Dockerize a Simple Web Application

Objective: Containerize a simple web application (e.g., Node.js, Python Flask).

#### Tasks:

- Write a Dockerfile to create a Docker image for the application.
- Build the Docker image.
- Run the application in a Docker container.
- Expose the application on a specific port.

#### Learning Outcomes:

- Writing Dockerfiles.
- Building and running custom Docker images.
- Exposing container ports.

### Project 3: Multi-Container Application using Docker Compose

Objective: Use Docker Compose to manage a multi-container application (e.g., web application with a database).

#### Tasks:

- Write a docker-compose.yml file to define multiple services.
- Define dependencies between services.
- Use Docker Compose to build and run the application.

#### Learning Outcomes:

- Using Docker Compose for multi-container applications.
- Managing service dependencies.

### Project 4: Docker Networking and Volumes

Objective: Understand Docker networking and volumes by creating a more complex application.

#### Tasks:

- Set up a custom Docker network for container communication.
- Use Docker volumes for persistent storage.
- Configure containers to use the network and volumes.

#### Learning Outcomes:

- Managing Docker networks and volumes.
- Ensuring data persistence and inter-container communication.

### Project 5: Docker Swarm for Orchestration

Objective: Explore Docker's built-in orchestration tool, Docker Swarm.

#### Tasks:

- Initialize a Docker Swarm.
- Deploy a stack using a docker-stack.yml file.
- Manage services and scale the application within the Swarm.

#### Learning Outcomes:

- Using Docker Swarm for container orchestration.
- Scaling services in a Docker Swarm cluster.

## Kubernetes

### Project 1: Basic Kubernetes Deployment

Objective: Deploy a simple application on a Kubernetes cluster.

#### Tasks:

- Install Minikube to create a local Kubernetes cluster.
- Write a Kubernetes deployment YAML file.
- Deploy the application and expose it using a service.

#### Learning Outcomes:

- Setting up a local Kubernetes cluster.
- Writing and applying Kubernetes deployment manifests.

### Project 2: Kubernetes Services and Ingress

Objective: Learn about Kubernetes services and ingress for traffic management.

#### Tasks:

- Create a service to expose the deployed application.
- Set up an ingress resource to manage external access.
- Configure DNS for the ingress.

#### Learning Outcomes:

- Using Kubernetes services and ingress resources.
- Managing external traffic in Kubernetes.

### Project 3: ConfigMaps and Secrets

Objective: Use ConfigMaps and Secrets to manage configuration and sensitive data.

#### Tasks:

- Create ConfigMaps and Secrets.
- Use them in the application deployment.
- Update configurations without redeploying the application.

#### Learning Outcomes:

- Managing application configurations and secrets in Kubernetes.
- Using ConfigMaps and Secrets in deployments.

### Project 4: Stateful Applications with Persistent Volumes

Objective: Deploy a stateful application with persistent storage.

#### Tasks:

- Set up persistent volume claims (PVCs) and persistent volumes (PVs).
- Deploy a stateful application (e.g., MySQL) using PVCs.
- Ensure data persistence across pod restarts.

#### Learning Outcomes:

- Using persistent storage in Kubernetes.
- Deploying and managing stateful applications.

### Project 5: Helm Chart Deployment

Objective: Package and deploy applications using Helm charts.

#### Tasks:

- Write a Helm chart for a simple application.
- Install the application using the Helm chart.
- Customize the deployment with Helm values.

#### Learning Outcomes:

- Creating and using Helm charts for application deployment.
- Managing Helm releases and upgrades.

## Shell Script

### Project 1: Basic Shell Script

Objective: Write a basic shell script to automate a simple task.

#### Tasks:

- Create a script to automate file backups.
- Use basic shell commands and conditionals.
- Schedule the script using cron.

#### Learning Outcomes:

- Writing and executing basic shell scripts.
- Automating tasks with cron.

### Project 2: User Management Script

Objective: Automate user management tasks.

#### Tasks:

- Write a script to add, remove, and list users.
- Handle user input and validate inputs.
- Manage user permissions.

#### Learning Outcomes:

- Writing scripts for user management.
- Handling input and managing permissions.

### Project 3: System Monitoring Script

Objective: Create a script to monitor system resources.

#### Tasks:

- Write a script to monitor CPU, memory, and disk usage.
- Send alerts if usage exceeds specified thresholds.
- Log monitoring data to a file.

#### Learning Outcomes:

- Monitoring system resources with shell scripts.
- Sending alerts and logging data.

### Project 4: Automated Backup Script

Objective: Automate the backup of files and databases.

#### Tasks:

- Write a script to backup files and MySQL databases.
- Use tar and mysqldump commands.
- Schedule regular backups with cron.

#### Learning Outcomes:

- Automating backups with shell scripts.
- Using advanced shell commands and scheduling with cron.

### Project 5: Complex Automation Script

Objective: Develop a complex automation script for deployment.

#### Tasks:

- Write a script to automate the deployment of a web application.
- Include steps for pulling code, building the application, and restarting services.
- Handle errors and send notifications on completion.

#### Learning Outcomes:

- Writing complex automation scripts.
- Error handling and notifications in shell scripts.

## Prometheus & Grafana

### Project 1: Basic Prometheus Setup

Objective: Set up Prometheus for basic monitoring.

#### Tasks:

- Install Prometheus.
- Configure Prometheus to scrape metrics from a local application.
- Visualize metrics using Prometheus UI.

#### Learning Outcomes:

- Installing and configuring Prometheus.
- Basic metric scraping and visualization.

### Project 2: Grafana Integration

Objective: Integrate Grafana with Prometheus for advanced visualization.

#### Tasks:

- Install Grafana.
- Add Prometheus as a data source in Grafana.
- Create dashboards to visualize application metrics.

#### Learning Outcomes:

- Integrating Grafana with Prometheus.
- Creating and managing Grafana dashboards.

### Project 3: Alerting with Prometheus and Alertmanager

Objective: Set up alerting for critical metrics.

#### Tasks:

- Install and configure Alertmanager.
- Define alert rules in Prometheus.
- Set up notification channels (e.g., email, Slack).

#### Learning Outcomes:

- Setting up alerting with Prometheus and Alertmanager.
- Configuring notifications.

### Project 4: Advanced Metrics and Exporters

Objective: Monitor advanced metrics using exporters.

#### Tasks:

- Install and configure node_exporter for system metrics.
- Install other exporters (e.g., MySQL exporter) for application metrics.
- Integrate exporters with Prometheus and Grafana.

#### Learning Outcomes:

- Using exporters for advanced metrics.
- Monitoring various system and application metrics.

### Project 5: Logging with Loki

Objective: Set up Loki for logging and integrate with Grafana.

#### Tasks:

- Install Loki and Promtail.
- Configure Promtail to collect logs from an application.
- Integrate Loki with Grafana for log visualization.

#### Learning Outcomes:

- Setting up Loki for log collection.
- Visualizing logs in Grafana.

## Terraform

### Project 1: Basic Infrastructure Provisioning

Objective: Use Terraform to provision basic infrastructure (e.g., AWS EC2 instance).

#### Tasks:

- Install Terraform.
- Write Terraform configuration files to create an EC2 instance.
- Apply the configuration and verify the instance.

#### Learning Outcomes:

- Writing and applying basic Terraform configurations.
- Provisioning cloud resources with Terraform.

### Project 2: Terraform Variables and Outputs

Objective: Use variables and outputs in Terraform.

#### Tasks:

- Define input variables for configuration.
- Use output values to display information about the provisioned resources.
- Pass variables using a tfvars file.

#### Learning Outcomes:

- Using variables and outputs in Terraform.
- Managing configuration inputs and outputs.

### Project 3: Terraform Modules

Objective: Create reusable Terraform modules.

#### Tasks:

- Write a Terraform module for a specific resource (e.g., S3 bucket).
- Use the module in multiple configurations.
- Share and version the module.

#### Learning Outcomes:

- Writing and using Terraform modules.
- Reusing and sharing configuration code.

### Project 4: Remote State Management

Objective: Manage Terraform state remotely.

#### Tasks:

- Configure a remote backend (e.g., AWS S3) for storing the Terraform state.
- Migrate existing state to the remote backend.
- Use state locking to prevent conflicts.

#### Learning Outcomes:

- Managing Terraform state remotely.
- Implementing state locking.

### Project 5: Complex Infrastructure with Dependencies

Objective: Provision complex infrastructure with multiple resources and dependencies.

#### Tasks:

- Write Terraform configurations for a multi-tier application (e.g., VPC, EC2, RDS).
- Manage resource dependencies and order of creation.
- Use data sources to reference existing resources.

#### Learning Outcomes:

- Provisioning complex infrastructure with Terraform.
- Managing dependencies and data sources.

## Ansible

### Project 1: Basic Ansible Playbook

Objective: Write a basic Ansible playbook to automate system configuration.

#### Tasks:

- Install Ansible.
- Write a playbook to install and configure a web server.
- Run the playbook on a remote server.

#### Learning Outcomes:

- Writing and executing basic Ansible playbooks.
- Automating system configurations.

### Project 2: Ansible Roles

Objective: Use Ansible roles to organize playbooks.

#### Tasks:

- Create an Ansible role for a specific task (e.g., web server setup).
- Use the role in a playbook.
- Share and reuse roles.

#### Learning Outcomes:

- Creating and using Ansible roles.
- Organizing and reusing playbook code.

### Project 3: Ansible Vault for Secrets Management

Objective: Manage sensitive data with Ansible Vault.

#### Tasks:

- Encrypt sensitive variables using Ansible Vault.
- Use encrypted variables in playbooks.
- Decrypt and update vault files as needed.

#### Learning Outcomes:

- Managing sensitive data with Ansible Vault.
- Using encrypted variables in playbooks.

### Project 4: Ansible Dynamic Inventory

Objective: Use dynamic inventory in Ansible.

#### Tasks:

- Configure dynamic inventory for a cloud provider (e.g., AWS).
- Use the dynamic inventory in playbooks.
- Query and manage dynamic hosts.

#### Learning Outcomes:

- Using dynamic inventory with Ansible.
- Managing cloud infrastructure dynamically.

### Project 5: Complex Multi-Tier Application Deployment

Objective: Deploy a multi-tier application using Ansible.

#### Tasks:

- Write playbooks to set up the entire application stack (e.g., web server, database).
- Use roles, variables, and templates to manage configurations.
- Deploy and verify the application.

#### Learning Outcomes:

- Deploying complex applications with Ansible.
- Using advanced playbook features.

## AWS

### Project 1: Basic EC2 Instance Setup

Objective: Launch and configure an EC2 instance.

#### Tasks:

- Create and configure an EC2 instance using the AWS Management Console.
- SSH into the instance and install a web server.
- Configure security groups for access.

#### Learning Outcomes:

- Launching and configuring EC2 instances.
- Managing security groups.

### Project 2: S3 Bucket Management

Objective: Manage S3 buckets and objects.

#### Tasks:

- Create an S3 bucket.
- Upload and manage objects in the bucket.
- Configure bucket policies and permissions.

#### Learning Outcomes:

- Managing S3 buckets and objects.
- Configuring bucket policies and permissions.

### Project 3: AWS Lambda Function

Objective: Create and deploy a serverless function using AWS Lambda.

#### Tasks:

- Write a simple Lambda function (e.g., in Python).
- Deploy the function using the AWS Management Console.
- Trigger the function using an AWS service (e.g., S3 event).

#### Learning Outcomes:

- Writing and deploying AWS Lambda functions.
- Integrating Lambda with other AWS services.

### Project 4: VPC and Networking

Objective: Set up a Virtual Private Cloud (VPC) with subnets, route tables, and gateways.

#### Tasks:

- Create a VPC with public and private subnets.
- Configure route tables and internet gateways.
- Launch instances in the VPC and test connectivity.

#### Learning Outcomes:

- Setting up and configuring VPCs.
- Managing networking components in AWS.

### Project 5: AWS CloudFormation for IaC

Objective: Use AWS CloudFormation to provision infrastructure as code.

#### Tasks:

- Write a CloudFormation template to create a stack (e.g., VPC, EC2 instances).
- Deploy and manage the stack using CloudFormation.
- Update the stack and handle changes.

#### Learning Outcomes:

- Writing and managing CloudFormation templates.
- Using infrastructure as code in AWS.

These projects should provide a comprehensive review of each tool and technology, starting from the basics and progressing to more advanced concepts and real-world applications.

## Jenkins

### Project 1: Simple CI Pipeline

Objective: Set up a basic Jenkins pipeline to build and test a simple Java application.

#### Tasks:

- Install Jenkins.
- Create a new freestyle project.
- Configure the project to pull code from a GitHub repository.
- Set up the project to build the application using Maven.
- Add a post-build action to archive the build artifacts.

#### Learning Outcomes:

- Understanding Jenkins UI and basic configuration.
- Integrating Jenkins with a version control system (GitHub).
- Automating build processes.

### Project 2: Automated Testing Pipeline

Objective: Extend the basic CI pipeline to include automated testing.

#### Tasks:

- Use the previous project's setup.
- Add steps to run unit tests using JUnit after building the application.
- Generate and publish test reports in Jenkins.

#### Learning Outcomes:

- Enhancing CI pipelines with automated testing.
- Publishing and analyzing test reports.

### Project 3: Docker Integration

Objective: Integrate Docker into your Jenkins pipeline.

#### Tasks:

- Install Docker on the Jenkins server.
- Create a Jenkins pipeline that builds a Docker image from a Dockerfile.
- Push the Docker image to Docker Hub.
- Run a container from the Docker image as part of the pipeline.

#### Learning Outcomes:

- Using Docker within Jenkins.
- Building and pushing Docker images.
- Running Docker containers in a CI/CD pipeline.

### Project 4: Complete CI/CD Pipeline with Kubernetes

Objective: Create a complete CI/CD pipeline to deploy an application to a Kubernetes cluster.

#### Tasks:

- Set up a multi-branch pipeline project in Jenkins.
- Configure Jenkins to build, test, and package the application.
- Use Helm to deploy the application to a Kubernetes cluster.
- Implement a rollback mechanism in case of deployment failures.

#### Learning Outcomes:

- Building multi-branch pipelines.
- Deploying applications to Kubernetes using Jenkins.
- Implementing deployment strategies and rollbacks.

### Project 5: Infrastructure as Code (IaC) with Terraform and Jenkins

Objective: Automate the provisioning of infrastructure using Terraform in a Jenkins pipeline.

#### Tasks:

- Write Terraform scripts to provision cloud infrastructure (e.g., AWS, Digital Ocean).
- Create a Jenkins pipeline to run Terraform commands.
- Integrate Jenkins with a version control system to manage Terraform scripts.
- Implement state management and remote backend for Terraform state files.

#### Learning Outcomes:

- Automating infrastructure provisioning with Terraform and Jenkins.
- Managing Terraform state in a CI/CD pipeline.
- Integrating infrastructure as code (IaC) practices in Jenkins.
