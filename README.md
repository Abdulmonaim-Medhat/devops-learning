# DevOps Learning

A 12-month, hands-on learning portfolio focused on **DevOps and AWS**, with the goal of developing the practical skills required for international DevOps / Cloud Engineer roles.

This repository documents the labs, experiments, troubleshooting exercises, architecture decisions, and lessons learned throughout the roadmap.

## Learning approach

- 5–7 hours per week.
- Practical, scenario-based learning supported by concise theory.
- Build on existing Linux, networking, virtualization, containers, CI/CD, and infrastructure experience.
- Record evidence, root causes, fixes, and prevention steps—not just command lists.
- Keep AWS spending within a target budget of approximately **$10–20/month**; prefer local labs whenever possible.

## Roadmap

| Month | Focus | Status |
|---|---|---|
| 01 | Linux, Networking & Infrastructure Fundamentals | In progress |
| 02 | Virtualization, Docker & Docker Compose | Planned |
| 03 | AWS Fundamentals | Planned |
| 04 | AWS Security & Operations | Planned |
| 05 | Terraform & Infrastructure as Code | Planned |
| 06 | Ansible & Configuration Management | Planned |
| 07 | Kubernetes Fundamentals | Planned |
| 08 | CI/CD, GitHub Actions, GitLab CI/CD & GitOps | Planned |
| 09 | Monitoring, Observability & Incident Response | Planned |
| 10 | Amazon EKS & Advanced AWS | Planned |
| 11 | Cloud-Native Capstone Project | Planned |
| 12 | Interview Preparation & Consolidation | Planned |

## Repository structure

```text
devops-learning/
├── README.md
├── .gitignore
├── Month-01-Linux-Networking/
│   ├── README.md
│   └── Labs/
│       └── Lab-01-Linux-Fundamentals/
│           ├── README.md
│           ├── scripts/
│           ├── scenarios/
│           └── evidence/
├── Month-02-Docker-Virtualization/
├── Month-03-AWS-Fundamentals/
├── Month-04-AWS-Security/
├── Month-05-Terraform/
├── Month-06-Ansible/
├── Month-07-Kubernetes/
├── Month-08-CI-CD-GitOps/
├── Month-09-Monitoring-Observability/
├── Month-10-Amazon-EKS/
├── Month-11-Capstone/
└── Month-12-Interview-Preparation/
```

## Lab documentation standard

Each practical lab should capture:

1. Objective and scenario.
2. Environment and architecture.
3. Deployment / reproduction steps.
4. Symptoms and diagnostic commands.
5. Evidence collected.
6. Root cause.
7. Resolution and verification.
8. Prevention and lessons learned.

## Environment

Primary workstation:
- Windows laptop
- AMD Ryzen 7 7435HS
- 32 GB RAM
- VMware Workstation
- Vagrant

Existing lab environment includes Fedora and Ubuntu Linux virtual machines. Lab resource allocations will be kept lightweight so environments can be created and destroyed quickly.

## Progress

See [Month 01](Month-01-Linux-Networking/README.md) for the current learning plan and [Lab 01](Month-01-Linux-Networking/Labs/Lab-01-Linux-Fundamentals/README.md) for the first hands-on exercise.

---

*This is a working engineering journal. Content will be updated as labs are completed and understanding is validated through practical troubleshooting.*
