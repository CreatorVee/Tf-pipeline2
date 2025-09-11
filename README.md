 DevOps E2E Project

This project demonstrates an end-to-end DevOps pipeline using Terraform, Ansible, Python, Jenkins, AWS, Kubernetes, and Docker.
The goal is to show how different DevOps tools work together to automate infrastructure, configuration, validation, and deployment.

---

🛠 Tech Stack


[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/) 
[![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)](https://www.ansible.com/) 
[![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/) 
[![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/) 
[![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)](https://www.jenkins.io/) 
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/) 
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)


---








<div style="border-top: 4px solid black; margin: 30px 0;"></div>
 Project Overview

This project ties together infrastructure provisioning, configuration management, validation, and CI/CD automation into a single workflow.

🔑 Key Features

Terraform creates AWS EKS clusters

Ansible automates node configuration (placeholder in this repo)

Python validates variables/configurations

Jenkins runs the pipeline end-to-end

AWS + Kubernetes + Docker for scalable cloud deployments


---

📂 Project Structure
devops-e2e/
├── backend.tf      # Terraform backend configuration  
├── main.tf         # Terraform infrastructure (AWS EKS cluster)  
├── playbook.yml    # Ansible playbook (placeholder for node config)  
├── validate.py     # Python validation script (placeholder for variable checks)  
├── Jenkinsfile     # CI/CD pipeline definition  
└── README.md       # Documentation  

---

⚙️ Setup & Run
1. Clone the Repository
git clone <repo-url>
cd <repo-folder>

---

2. Run Terraform
terraform init
terraform apply --auto-approve

---

3. Run Python Validation
python3 validate.py

---

4️.  Run Ansible Playbook
ansible-playbook playbook.yml

---

5. Jenkins Pipeline

Runs Python validation

Runs Ansible playbook

Applies Terraform provisioning

---


✅ Problems & Solutions
## 🔧 Problems and Solutions

### Terraform
- **Problem (Before):** Setting up infrastructure like EKS clusters manually on AWS was time-consuming, repetitive, and prone to human error.  
- **Solution (Now):** Terraform automates infrastructure creation using Infrastructure as Code (IaC). Resources can be provisioned consistently, version-controlled, and easily replicated across environments.  

### Ansible (Placeholder in this project)
- **Problem (Before):** Configuring each server node manually (installing packages, managing users, applying updates) often led to inconsistencies and wasted time.  
- **Solution (Now):** In real-world use, Ansible automates this configuration process using playbooks. While in this project it served as a placeholder, it represents how configuration management tools ensure that all servers remain consistent and easy to scale.  

### Python (Placeholder in this project)
- **Problem (Before):** No quick way to validate variables or check configurations before deployment, which sometimes caused failed builds or errors.  
- **Solution (Now):** A Python script was used as a placeholder to show how validation can be automated. In real pipelines, Python is often used to create validation scripts, small automation utilities, or health checks that prevent mistakes from moving forward.  

### Jenkins
- **Problem (Before):** Running build, test, and deployment steps manually was slow, error-prone, and not repeatable.  
- **Solution (Now):** Jenkins pipelines automate the entire CI/CD process. Code changes trigger automated builds, tests, and deployments, improving speed, reliability, and consistency.  

### AWS + Kubernetes + Docker
- **Problem (Before):** Running applications only on local machines limited scalability, reliability, and made collaboration difficult.  
- **Solution (Now):** Using Docker for containerization, Kubernetes for orchestration, and AWS for cloud hosting provides scalability, consistency, and high availability. This cloud-native stack demonstrates how applications can be deployed and managed effectively at scale.  


---


 What I Learned:

##  What I Learned

- **Terraform** → Writing infrastructure as code to automate the creation of servers, networks, and cloud resources.  
- **Ansible** → Managing configurations and automating repetitive setup tasks across multiple machines,however in this case i used ansible as a placeholder,furthermore, i was able to understand  the role it plays in the configuration aspect.
- **Python** → Creating validation and helper scripts to test deployments and ensure reliability,in addition i also used pyhton as a placeholder in this project however,it didnt stop me from understanding how python can help avoid bugs  and help the ci/cd proccess run smmoother with the hope of no bugs or fixes.  
- **Jenkins** → Building CI/CD pipelines that automate code builds, tests, and deployments.  
- **AWS, Kubernetes, and Docker** → Understanding how cloud services, containerization, and orchestration work together in modern DevOps workflows.  
- **Git & GitHub** → Version control, branching, and collaborating effectively using pull requests.  
- **Monitoring & Logging Basics** → Gaining awareness of tools that help track system health and troubleshoot issues.  


---
# Evidence 
<img width="1920" height="1032" alt="2025-05-20_21h36_57" src="https://github.com/user-attachments/assets/9f8c955d-d9d2-4446-991a-510d4b5f477c" />


<img width="816" height="698" alt="2025-09-11_10h40_25" src="https://github.com/user-attachments/assets/769f2c85-c4a4-465e-9418-462bdbdbf288" />



---

