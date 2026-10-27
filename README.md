<div align="center">
  <img src="assets/vexor-logo.svg" alt="VEXOR" width="340" />
  <br />
  <h1>Hi, I'm Sajid Khan 👋</h1>
  <h3>DevSecOps Engineer · Cloud Automation · Full-Stack Deployment</h3>
  <p><b>Building, securing, and deploying real-world applications.</b></p>
  <p>I turn infrastructure into code, automate delivery pipelines, and help applications move from development to production.</p>
  <p>
    <a href="https://github.com/sajidkhan-DevOps"><img src="https://img.shields.io/badge/GitHub-sajidkhan--DevOps-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
    <a href="mailto:sajidkhan299720@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <img src="https://img.shields.io/badge/Focus-DevSecOps-00C7B7?style=for-the-badge" alt="DevSecOps" />
  </p>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=800&color=E34F26&center=true&vCenter=true&width=700&lines=Azure+%7C+Terraform+%7C+Docker+%7C+Kubernetes;CI%2FCD+Automation+%7C+Cloud+Infrastructure;From+Code+to+Production+%F0%9F%9A%80" alt="Animated typing: Azure, Terraform, Docker, Kubernetes, CI/CD" />
</div>

---

## 👨‍💻 About Me

I'm a DevSecOps Engineer based in Lucknow, India, focused on Microsoft Azure, Infrastructure as Code, containers, and CI/CD automation. I enjoy making deployments repeatable, improving server reliability, and connecting application development with secure cloud operations.

My hands-on work spans Terraform-managed infrastructure, Docker-based deployments, Kubernetes, Linux server administration, release operations, database migrations, and troubleshooting production applications.

- ☁️ **Cloud:** Microsoft Azure, Azure CLI, AKS, ACR, VNets, NSGs, Storage
- 🏗️ **Infrastructure as Code:** Terraform, reusable modules, remote state
- 🔁 **CI/CD:** GitHub Actions, Azure DevOps YAML pipelines
- 📦 **Containers:** Docker, Docker Compose, Kubernetes
- 🔐 **Security & Operations:** SSH hardening, RBAC, secrets handling, Nginx, SSL/TLS
- 📍 **Location:** Lucknow, Uttar Pradesh, India

## 🏢 VEXOR — Digital Solutions & Cloud Engineering

<div align="center">
  <img src="assets/vexor-logo.svg" alt="VEXOR agency logo" width="280" />
  <p><b>Modern technology. Thoughtful engineering. Reliable delivery.</b></p>
</div>

VEXOR is my agency brand for helping businesses build digital products and get them deployed reliably. The focus is on practical solutions that connect product development, cloud infrastructure, and ongoing delivery.

| Service | What it covers | Example technologies |
|---|---|---|
| **Web & Full-Stack Development** | Responsive business websites, web applications, dashboards, and API integration | React, Next.js, FastAPI |
| **Cloud Infrastructure** | Cloud resource setup, repeatable environments, and infrastructure automation | Microsoft Azure, Terraform, Azure CLI |
| **DevOps & CI/CD** | Automated build, validation, image publishing, and deployment workflows | GitHub Actions, Azure DevOps, YAML |
| **Containerization** | Packaging applications and running container-based workloads | Docker, Docker Compose, Kubernetes, AKS, ACR |
| **Server Setup & Deployment** | Linux server configuration, reverse proxy, HTTPS, and release support | Ubuntu, Nginx, SSH, SSL/TLS |

> Have a project or deployment challenge? [Contact me by email](mailto:sajidkhan299720@gmail.com). Add VEXOR's official website and social links here once they are public.

---

## 🚀 Featured Project: HungryKart — Food Delivery Platform

**My role: End-to-end deployment, cloud infrastructure, and server-side operations**

HungryKart is a food delivery platform with a FastAPI backend, a Next.js admin panel, and three Flutter apps for customers, restaurant partners, and delivery agents. My work includes deployment and release operations across application and infrastructure layers.

### Architecture at a glance

```mermaid
flowchart TB
    subgraph Apps[Client Applications]
      C[Customer App - Flutter]
      R[Restaurant App - Flutter]
      D[Delivery Agent App - Flutter]
      A[Admin Panel - Next.js]
    end
    subgraph Delivery[Delivery and Application Layer]
      N[Nginx Reverse Proxy and TLS]
      API[FastAPI Backend]
    end
    subgraph Data[Data Layer]
      PG[(PostgreSQL)]
      REDIS[(Redis)]
    end
    subgraph Pipeline[CI/CD]
      GH[GitHub Actions]
      BUILD[Build and Containerize]
      ACR[Azure Container Registry]
      AKS[Azure Kubernetes Service]
      GH --> BUILD --> ACR --> AKS
    end
    C --> N
    R --> N
    D --> N
    A --> N
    N --> API
    API --> PG
    API --> REDIS
```

### Work and responsibilities

- Containerized application components using Docker and Docker Compose on Ubuntu.
- Managed application releases, rebuilds, Alembic database migrations, and health checks.
- Worked with Terraform-provisioned Azure resources, including AKS and Azure Container Registry.
- Set up GitHub Actions workflows to build and publish container images and support deployments.
- Configured Nginx reverse proxy and SSL/TLS, SSH key-based access, a restricted service user, and limited sudo access.
- Worked on admin capabilities including menu management, pricing and GST settings, and delivery-agent incentives.
- Prepared signed Android release builds for Google Play publishing.

**Stack:** FastAPI · Next.js · Flutter · Docker · Docker Compose · Azure · AKS · ACR · Terraform · GitHub Actions · Nginx · PostgreSQL · Redis · Alembic

## 🧩 Other Projects

### ☁️ Azure Multi-Environment Web App Deployment

- Created separate development and production environments using Terraform modules and variables.
- Worked with Azure infrastructure, Docker, ACR, AKS, Nginx, and GitHub Actions.
- Focused on repeatable provisioning and automated application delivery.

### 🏛️ Azure Landing Zone

- Built a foundational Azure environment using Terraform and Azure CLI.
- Worked with resource groups, hub-and-spoke virtual networks, NSGs, role assignments, and Azure Policy.

### 🛡️ Terraform Security Scanning Practice

- Hands-on practice with Trivy, Checkov, and TFLint for infrastructure code and configuration checks.
- Working toward integrating scanning and validation into CI/CD workflows.

> Replace the project titles above with links to the corresponding public repositories when those repository URLs are confirmed.

## 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=azure,terraform,docker,kubernetes,githubactions,git,github,linux,bash,powershell,nginx,python,react,nextjs,postgres,redis" alt="Technology stack icons" />
</p>

| Area | Tools and technologies |
|---|---|
| **Cloud** | Microsoft Azure, VMs, VNets, NSGs, Storage, AKS, ACR, Load Balancer, Application Gateway, Azure CLI |
| **Infrastructure as Code** | Terraform, modules, variables, remote state, workspaces |
| **CI/CD** | GitHub Actions, Azure DevOps, YAML pipelines, Git workflows, pull requests |
| **Containers** | Docker, Docker Compose, Kubernetes, Azure Kubernetes Service |
| **Systems & Networking** | Ubuntu Linux, Bash, PowerShell, Nginx, SSH, SSL/TLS |
| **Security tools** | Trivy, Checkov, TFLint, RBAC, secrets management, least privilege |
| **Application & data** | FastAPI, Next.js, Flutter, PostgreSQL, Redis, Alembic |

## 💼 Experience

**DevOps Engineer Intern — DevOps Insiders**  
*February 2026 – Present*

- Work with Azure resources using Azure Portal, Azure CLI, and Terraform.
- Set up Azure DevOps repositories, boards, and multi-stage YAML pipelines.
- Containerize applications with Docker and work with Azure Container Registry and AKS deployments.
- Build reusable Terraform modules and use Azure Storage for remote state.
- Follow Git branching and pull-request workflows.

## 🎓 Education

**Bachelor of Computer Applications (BCA)**  
Integral University, Lucknow, Uttar Pradesh, India

## 📊 GitHub Activity

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=sajidkhan-DevOps&show_icons=true&hide_border=true&theme=transparent" alt="GitHub stats for sajidkhan-DevOps" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sajidkhan-DevOps&layout=compact&hide_border=true&theme=transparent" alt="Most used languages" />
</div>

## 🤝 Let's Connect

I'm interested in DevSecOps and cloud engineering opportunities, collaboration on real-world projects, and helping businesses improve how they build and deploy software.

- **GitHub:** [@sajidkhan-DevOps](https://github.com/sajidkhan-DevOps)
- **Email:** [sajidkhan299720@gmail.com](mailto:sajidkhan299720@gmail.com)
- **Agency:** VEXOR — add official website and social links when available

<div align="center">
  <sub>Designed with care by Sajid Khan · Cloud, automation, and delivery with VEXOR</sub>
</div>
