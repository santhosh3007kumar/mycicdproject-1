<img width="1920" height="1080" alt="Screenshot 2026-02-03 163912" src="https://github.com/user-attachments/assets/1e2e81f4-7e7e-4fac-87da-a39a48e708fa" />
<img width="1920" height="1080" alt="Screenshot 2026-02-03 160245" src="https://github.com/user-attachments/assets/8e065c76-31eb-4b4e-9777-a8a108ea1846" />
<img width="1920" height="1080" alt="Screenshot 2026-02-03 160542" src="https://github.com/user-attachments/assets/a88af62b-92a4-412b-8525-2a7ec69d69b9" />
<img width="1920" height="1080" alt="Screenshot 2026-02-03 160524" src="https://github.com/user-attachments/assets/b1e28290-0310-4ed7-aabb-66461161bd71" />
<img width="1920" height="1080" alt="Screenshot 2026-02-03 160457" src="https://github.com/user-attachments/assets/1b981a8c-2645-4ae1-a5c6-5c71cfc9819d" />
<img width="1920" height="1080" alt="Screenshot 2026-02-03 161115" src="https://github.com/user-attachments/assets/8219f48e-cbeb-4059-9f51-ae80b2df51db" />

🚀 **CI/CD Pipeline using Jenkins, Docker & Kubernetes (K3s)**
📌 **Project Overview**

This project demonstrates an end-to-end CI/CD pipeline that automates application build, containerization, image publishing, and deployment to a Kubernetes (K3s) cluster using Jenkins.

1.Whenever code is pushed to GitHub, Jenkins automatically:

2.Pulls the latest source code

3.Builds a Docker image

4.Pushes the image to Docker Hub

5.Updates Kubernetes manifests

6.Deploys the application to a K8s cluster

This ensures fast, consistent, and reliable deployments with minimal manual intervention.

🧰 **Tools & Technologies Used**

GitHub – Source code management
Jenkins – CI/CD automation
Docker – Application containerization
Docker Hub – Image registry
Kubernetes (K8s) – Container orchestration
Linux (Ubuntu) – Jenkins server OS
YAML – Kubernetes manifests
**
**🔄 CI/CD Pipeline Workflow****

 1.Developer pushes code to GitHub repository

2.Jenkins pipeline is triggered automatically

3.Jenkins pulls the latest code from GitHub

4.Docker image is built using Dockerfile

5.Docker image is pushed to Docker Hub with a unique build tag

6.Kubernetes deployment YAML is updated with the new image

7.Application is deployed to K8s Kubernetes cluster

8.Service exposes the application to users

****🏗️ Architecture Diagram (Textual)**

**GitHub
   |
   v
Jenkins Pipeline
   |
   v
Docker Build → Docker Hub
   |
   v
Kubernetes (K3s Cluster)
   |
   v
Application Service**
**
**🎯 Real-Time Use Case**

1.This project simulates a real-world DevOps workflow used in organizations to:
2.Automate application deployment
3.Reduce manual errors
4.Improve deployment speed
5.Maintain consistency across environments
