![Stephanie Afunogu, Full-Stack Developer and Cloud & DevOps Engineer](./assets/banner-3.png)

[![Typing: I build full-stack web apps, then ship them to the cloud](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=24&pause=1200&color=2DD4BF&vCenter=true&width=650&lines=I+build+full-stack+web+apps.;Then+I+ship+and+run+them+in+the+cloud.;FastAPI+%C2%B7+Next.js+%C2%B7+PostgreSQL;AWS+%C2%B7+Terraform+%C2%B7+Docker+%C2%B7+Kubernetes)](https://github.com/stephcloud)

![Profile views](https://komarev.com/ghpvc/?username=stephcloud&label=Profile%20views&color=2dd4bf&style=flat)

## About me

I'm a **Full-Stack Developer and Cloud/DevOps Engineer** based in Enugu, Nigeria.
I build web apps end to end (FastAPI, Next.js, PostgreSQL), then provision, deploy and run them on the cloud (AWS, Terraform, Ansible, Docker, Kubernetes).

Open to **DevOps / Cloud Engineer** and **Software Developer** roles.

[afunogustephanie@gmail.com](mailto:afunogustephanie@gmail.com) · [LinkedIn](https://www.linkedin.com/in/afunogu/)

## Featured work

### SalonBook: salon booking with deposits that stop no-shows
[Live site](https://salonbook-web-theta.vercel.app) · [API docs](https://salonbook-api-etyz.onrender.com/docs) · [API repo](https://github.com/stephcloud/salonbook-api) · [Web repo](https://github.com/stephcloud/salonbook-web)

Clients pick a stylist, see real free time slots and pay a deposit to confirm.
- A PostgreSQL exclusion constraint makes double-booking impossible, even under concurrent requests, and a concurrency test proves it.
- Paystack deposits (test mode) confirmed by a signed webhook. Replayed webhooks change state only once, and cancellations follow a refund policy.
- **Stack:** FastAPI, SQLModel, Alembic, PostgreSQL, Redis, Docker on Render · Next.js, TypeScript, Tailwind, shadcn/ui, TanStack Query on Vercel

### EpicBook on AWS: Terraform + Ansible, deployed by pipeline
[Infra repo](https://github.com/stephcloud/epicbook-aws-infra) · [Deploy repo](https://github.com/stephcloud/epicbook-aws-deploy)

Infrastructure and deployment live in separate repos, each with its own Azure DevOps pipeline. Terraform provisions the VPC, subnets, routing, security groups, an EC2 instance and RDS MySQL; the pipeline runs `plan`, saves it as an artifact, then applies it. The deploy pipeline runs Ansible roles that set up the server, an Nginx reverse proxy and the app.

### Petclinic Platform: microservices on EKS with GitOps
[Repo](https://github.com/stephcloud/petclinic-platform)

Platform repo for deploying the Spring Petclinic microservices to AWS EKS: Terraform for VPC, EKS, RDS and ECR, Helm charts, ArgoCD for GitOps, GitHub Actions CI and Prometheus + Grafana monitoring.

## Tech stack

[![Python, FastAPI, PostgreSQL, Redis, TypeScript, Next.js, React, Tailwind, AWS, Terraform, Ansible, Docker, Kubernetes, GitHub Actions, Linux, Bash, Nginx, Prometheus, Grafana](https://skillicons.dev/icons?i=python,fastapi,postgres,redis,ts,nextjs,react,tailwind,aws,terraform,ansible,docker,kubernetes,githubactions,linux,bash,nginx,prometheus,grafana&perline=10)](https://skillicons.dev)

- **Backend:** Python, FastAPI, SQLModel, Alembic, PostgreSQL, Redis
- **Frontend:** TypeScript, Next.js, React, Tailwind CSS, shadcn/ui
- **Cloud & IaC:** AWS (VPC, EC2, RDS, EKS, ECR), Terraform, Ansible
- **Containers & delivery:** Docker, Kubernetes, Helm, ArgoCD, GitHub Actions
- **Ops:** Linux, Bash, Nginx, Prometheus, Grafana

## Training

- DevOps Micro Internship with Agentic AI, The Cloud Advisory (2026)
- Ultimate Agentic AI DevOps with Claude Code, Udemy (2025)
- DevOps & Cloud Security, Digital Witch Community (2025)
