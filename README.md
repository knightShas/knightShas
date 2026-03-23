<div align="center">

<!-- Dynamic banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Shashank%20Kumar&fontSize=50&fontColor=00d4ff&fontAlignY=38&desc=DevOps%20%7C%20Cloud%20%7C%20Platform%20Engineering&descColor=a0c4d8&descAlignY=58&animation=fadeIn" width="100%" />

</div>

---

## 👨‍💻 About Me

> *"Automating infrastructure, shipping reliability."*

I'm a **DevOps & Cloud Engineer** with hands-on experience building and operating production infrastructure on **AWS** and **Kubernetes**. I focus on designing scalable, self-healing platforms — from EKS cluster bootstrapping to GitOps-driven deployments.

- 🚀 Currently working on: **EKS + ALB Ingress Controller** with IRSA & Helm
- 🌩️ Deep-diving into: **Terraform**, **ArgoCD**, **Prometheus/Grafana** observability stacks
- 🧠 Philosophy: Infrastructure as Code first, manual steps never
- 📫 Reach me: [shashankkumar8092@outlook.com](mailto:shashankkumar8092@outlook.com)
- 🔗 LinkedIn: [knight-shashank-kumar](https://www.linkedin.com/in/knight-shashank-kumar/)

---

## 🛠️ Tech Stack

### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-%230F1689.svg?style=for-the-badge&logo=helm&logoColor=white)

### 🐳 Containers & Orchestration
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Amazon EKS](https://img.shields.io/badge/Amazon%20EKS-%23FF9900.svg?style=for-the-badge&logo=amazon-eks&logoColor=white)
![Amazon ECR](https://img.shields.io/badge/Amazon%20ECR-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

### ⚙️ CI/CD & GitOps
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-%23EF7B4D.svg?style=for-the-badge&logo=argo&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)

### 📊 Observability
![Prometheus](https://img.shields.io/badge/Prometheus-%23E6522C.svg?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)

### 🖥️ OS & Scripting
![Linux](https://img.shields.io/badge/Linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-%234EAA25.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)

---

## 🏗️ Featured Projects

### 🔷 [EKS ALB Ingress Setup](https://github.com/knightShas)
> **AWS EKS · ALB Controller · IRSA · Helm · IAM OIDC**

End-to-end setup of an Application Load Balancer on Amazon EKS using the **AWS Load Balancer Controller**.
- Configured IAM OIDC provider and IRSA for fine-grained pod-level IAM permissions
- Deployed controller via Helm with custom `values.yaml` overrides
- Tagged public/private subnets for ALB discovery
- Created Kubernetes Ingress resources with ALB annotations for path-based routing

---

### 🔷 [Spring Boot Online Exam Backend](https://github.com/knightShas/Spring-OnlineExam)
> **Java · Spring Boot · REST API**

Containerisable Spring Boot REST backend — structured for Docker/ECS deployment patterns.

---

### 🔷 [Policy Management API](https://github.com/knightShas/spring-logged-policy)
> **Java · Spring Boot · Postman**

Lightweight API for logged policy management — designed for microservice decomposition.

---

## 📐 Infrastructure Architecture (EKS + ALB)

```
                         ┌─────────────────────────────────────┐
                         │            AWS Cloud                │
   User Traffic          │                                     │
   ──────────►  Route53  │  ┌──────────────────────────────┐   │
                         │  │  Application Load Balancer   │   │
                         │  │  (Provisioned via ALB Ctrl)  │   │
                         │  └───────────────┬──────────────┘   │
                         │                  │                  │
                         │        ┌─────────▼───────────┐      │
                         │        │    EKS Cluster      │      │
                         │        │  ┌───────────────┐  │      │
                         │        │  │  Ingress Obj  │  │      │
                         │        │  └───────┬───────┘  │      │
                         │        │          │          │      │
                         │        │  ┌───────▼───────┐  │      │
                         │        │  │  Service/Pods │  │      │
                         │        │  └───────────────┘  │      │
                         │        │                     │      │
                         │        │ ALB Controller Pod  │      │
                         │        │  (IRSA → IAM Role)  │      │
                         │        └─────────────────────┘      │
                         │                  │                  │
                         │        ┌─────────▼──────────┐       │
                         │        │   IAM / OIDC / STS  │      │
                         │        └─────────────────────┘      │
                         └─────────────────────────────────────┘
```

---

## 📈 GitHub Stats

<div align="center">

![Shashank's GitHub Stats](https://github-readme-stats.vercel.app/api?username=knightShas&theme=chartreuse-dark&show_icons=true&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=knightShas&theme=chartreuse-dark&layout=compact&hide_border=true&hide=python)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=knightShas&theme=chartreuse-dark&hide_border=true)

</div>

---

## 🎯 Currently Leveling Up

```yaml
learning:
  - Terraform (IaC for EKS, VPC, IAM)
  - ArgoCD GitOps workflows
  - Prometheus + Grafana observability stack
  - Kubernetes RBAC & Network Policies
  - AWS Certified DevOps Engineer (Pro) — in prep

goals_2025:
  - Contribute to open-source CNCF projects
  - Build a multi-region EKS setup with Terraform
  - Publish infrastructure patterns as reusable Helm charts
```

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=100&section=footer" width="100%" />

*"The best infrastructure is the one no one has to think about."*

</div>
