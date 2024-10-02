# My Bio Repo

Welcome to my **My Bio Project Repository**! This project showcases my skills in DevOps, cloud infrastructure, automation, and system administration. The demo includes a tech bio webpage, outlining my journey and experience in the field, as well as key configurations and workflows related to cloud infrastructure and automation.

## Table of Contents

- [About Me](#about-me)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)

## About Me

I’m **Jeremiah Onwoh**, an IT professional with over 10 years of experience in network administration, cloud-based infrastructures, and automation. I specialize in deploying, optimizing, and managing both off-cloud networks (LAN/WAN) and cloud infrastructures on AWS, Azure, and GCP. This demo project represents a part of my learning journey in DevOps, including various tools and techniques I've mastered.

## Technologies Used

- **HTML5 & CSS3**: For creating the front-end tech bio page.
- **Terraform**: For automating infrastructure provisioning.
- **Docker**: For containerizing applications.
- **Kubernetes**: For managing containerized workloads.
- **Ansible**: For configuration management and deployment automation.
- **Bash Scripting**: For automating processes and server management.
- **AWS, Azure, GCP**: Cloud platforms used to deploy the infrastructure.
- **Git**: Version control for managing code.

## Features

- **Tech Bio Webpage**: A single-page HTML page that details my professional journey and skills.
- **Automated Infrastructure**: Includes a Terraform setup for provisioning cloud resources.
- **Containerization**: Demonstrates Dockerfile creation and container orchestration using Kubernetes.
- **Configuration Management**: Shows Ansible playbooks for automating server configurations.

## Setup and Installation

### Prerequisites

- Docker
- Terraform
- Ansible
- Kubernetes CLI
- A cloud account (AWS, Azure, GCP)

### Installation Steps

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/jerryben/bio-portfolio.git
   cd bio-portfolio
   ```

2. **Set up Docker**:

   - Build the Docker image:
     ```bash
     docker build -t portfolio-site .
     ```
   - Run the container:
     ```bash
     docker run -d -p 80:80 portfolio-site
     ```

3. **Deploy with Terraform**:

   - Navigate to the Terraform directory:
     ```bash
     cd terraform
     ```
   - Initialize and apply the infrastructure:
     ```bash
     terraform init
     terraform apply
     ```

4. **Configure with Ansible**:
   - Navigate to the Ansible playbook directory:
     ```bash
     cd ansible
     ```
   - Run the playbook to configure servers:
     ```bash
     ansible-playbook setup.yml
     ```

### Kubernetes (Optional)

If you're deploying with Kubernetes:

1. **Deploy the Kubernetes cluster**:
   ```bash
   kubectl apply -f k8s/deployment.yml
   ```

## Usage

- Visit the deployed webpage at `http://localhost` if running locally, or at the cloud-provided URL after deployment.
- Explore the source code in the `terraform`, `ansible`, and `docker` directories to understand infrastructure automation and containerization setups.

## Contributions

Contributions are welcome! Please create a fork of this repository and submit a pull request with detailed explanations of your changes.

## License

This project is licensed under the MIT License.

```

This `README.md` provides a clear overview of the project, instructions for setup, and additional information to help others understand and contribute to your DevOps demo. You can modify it further to suit any specific aspects of your project!
```
