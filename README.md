<div align="center">

# Ramalakshmi Mani

**Senior Cloud Platform Engineer**

*Building cloud platforms that teams deploy on — without raising a ticket*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ramalakshmim-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ramalakshmim)
[![Email](https://img.shields.io/badge/Email-ramalakshmi0505%40outlook.com-0078D4?style=flat-square&logo=microsoft-outlook&logoColor=white)](mailto:ramalakshmi0505@outlook.com)
[![GitHub](https://img.shields.io/badge/GitHub-ramalakshmi0505-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ramalakshmi0505)

</div>

---

## About

11 years delivering cloud and platform engineering across automotive, telecommunications, and financial services. Currently at **BMW TechWorks** operating a multi-region Amazon EKS platform across three AWS regions and running enterprise workflow automation through n8n for multiple business units.

I focus on infrastructure that removes friction: self-service platforms where teams provision compliant environments in one pipeline run, GitOps setups where a git push is the only deployment action, and automation that makes the safe path the only path.

| | |
|---|---|
| **Current Role** | Senior Cloud Platform Engineer, BMW TechWorks India |
| **Experience** | 11 years · 7 companies · 5 industries |
| **Certifications** | AWS DevOps Engineer – Professional · Solutions Architect – Associate · Developer – Associate |
| **Languages** | English (C2) · German (A2 → B1 in progress) |

---

## Impact

<div align="center">

| 6 hrs → 30 min | 70% faster | 15 apps | 35% fewer incidents |
|:---:|:---:|:---:|:---:|
| Environment provisioning time | Team onboarding with self-service Terraform | Zero-downtime migrations to AWS | After GitOps adoption with ArgoCD |

</div>

---

## Technical Skills

**Cloud & Platform**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Amazon EKS](https://img.shields.io/badge/Amazon_EKS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**IaC & GitOps**
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**CI/CD & Automation**
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

**Security & Observability**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aquasecurity&logoColor=white)

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![HCL](https://img.shields.io/badge/HCL-7B42BC?style=flat-square&logo=terraform&logoColor=white)

---

## Projects

Projects are grouped by the core skill they demonstrate, ordered by priority.

---

### Cloud Platform & Kubernetes

| Project | What it does | Stack |
|---|---|---|
| [**n8n-gitops-platform**](https://github.com/ramalakshmi0505/n8n-gitops-platform) | Self-hosted n8n on Kubernetes — Terraform provisions the cluster, ArgoCD manages the Helm release. Push to git, the cluster syncs itself. | `Terraform` `ArgoCD` `Helm` `k3d/EKS` |
| [**multi-cluster-platform**](https://github.com/ramalakshmi0505/multi-cluster-platform) | Highly available platform across two EKS clusters with health-checked failover, a Go sample service, golden-path CI/CD, and an adoption CLI. | `Terraform` `EKS` `Go` `GitHub Actions` |
| [**eu-sovereign-idp**](https://github.com/ramalakshmi0505/eu-sovereign-idp) | Sovereign internal developer platform on EKS with EU data residency, GDPR guardrails, and cost controls enforced as policy-as-code. | `Terraform` `EKS` `Go` `OPA` |
| [**eks-upgrade-demo**](https://github.com/ramalakshmi0505/eks-upgrade-demo) | EKS upgrades as a reviewed pull request — Terraform plan via OIDC on PR, deprecated-API check, control-plane-first runbook. | `Terraform` `EKS` `GitHub Actions` `OIDC` |
| [**istio-ambient-demo**](https://github.com/ramalakshmi0505/istio-ambient-demo) | Hands-on Istio ambient mesh demo — zero-trust networking without sidecars. | `Kubernetes` `Istio` `Helm` |

---

### Infrastructure as Code & GitOps

| Project | What it does | Stack |
|---|---|---|
| [**terraform-aws-modules**](https://github.com/ramalakshmi0505/terraform-aws-modules) | Reusable Terraform module library for AWS — security controls and tagging policies baked in so the safe path is the only path. | `Terraform` `AWS` |
| [**aws-self-service-catalog**](https://github.com/ramalakshmi0505/aws-self-service-catalog) | Order cloud infrastructure like Amazon — six Terraform modules, one order form, no tickets. | `Terraform` `AWS Service Catalog` `IAM` |
| [**gitops-drift-detector**](https://github.com/ramalakshmi0505/gitops-drift-detector) | Scans ArgoCD applications for configuration drift and alerts — know when the cluster diverges from git before it becomes an incident. | `Python` `ArgoCD` `Prometheus` |
| [**terraform-plan-on-pr**](https://github.com/ramalakshmi0505/terraform-plan-on-pr) | Terraform plan output as a PR comment on every pull request — reviewers see the infrastructure diff before merge. | `Terraform` `GitHub Actions` `OIDC` |
| [**azure-webapp-terraform**](https://github.com/ramalakshmi0505/azure-webapp-terraform) | Azure web application provisioned end-to-end with Terraform. | `Terraform` `Azure` |
| [**aws-automated-provisioning**](https://github.com/ramalakshmi0505/aws-automated-provisioning) | AWS automated multi-environment provisioning. | `Terraform` `AWS` |

---

### Workflow Automation & n8n

| Project | What it does | Stack |
|---|---|---|
| [**n8n-Platform-Configuration-Guide**](https://github.com/ramalakshmi0505/n8n-Platform-Configuration-Guide) | Production governance guide for self-hosted n8n — security, backup, credential management, and multi-user setup. | `n8n` `Kubernetes` |
| [**n8n-aws-cost-alerts**](https://github.com/ramalakshmi0505/n8n-aws-cost-alerts) | Automated AWS cost monitoring with n8n running on EKS — alerts when daily spend spikes above threshold. | `n8n` `AWS` `EKS` `Terraform` |
| [**n8n-recruitment-automation**](https://github.com/ramalakshmi0505/n8n-recruitment-automation) | AI-powered CV screening and candidate pipeline automation with a working n8n JSON workflow. | `n8n` `AI` `Automation` |
| [**job-feed-builder**](https://github.com/ramalakshmi0505/job-feed-builder) | n8n workflow that pulls open roles from company career pages and drops matches into a sheet, daily. | `n8n` `JavaScript` |
| [**n8n-copilot-instructions**](https://github.com/ramalakshmi0505/n8n-copilot-instructions) | GitHub Copilot instructions for n8n workflow development. | `n8n` `GitHub Copilot` |

---

### AI & RAG

| Project | What it does | Stack |
|---|---|---|
| [**local-rag**](https://github.com/ramalakshmi0505/local-rag) | Local RAG pipeline built from scratch in ~300 lines of Python — no frameworks, no cloud, no API keys. Ollama + ChromaDB. | `Python` `Ollama` `ChromaDB` |
| [**rag-infra-bot**](https://github.com/ramalakshmi0505/rag-infra-bot) | Infrastructure knowledge bot using PostgreSQL + pgvector — ask questions about your own runbooks and docs. | `Python` `PostgreSQL` `pgvector` |

---

### Tooling

| Project | What it does | Stack |
|---|---|---|
| [**k8s-cost-optimizer**](https://github.com/ramalakshmi0505/k8s-cost-optimizer) | Kubernetes cost optimizer — identifies oversized workloads and rightsizing recommendations. | `Python` `Kubernetes` |
| [**ats-resolver**](https://github.com/ramalakshmi0505/ats-resolver) | Detects a company's ATS and its public job feed URL. | `JavaScript` |

---

## GitHub Activity

<div align="center">

![Repos](https://img.shields.io/badge/Public_Repos-21-0969DA?style=flat-square&logo=github&logoColor=white)
![HCL](https://img.shields.io/badge/HCL_(Terraform)-most_used-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Python](https://img.shields.io/badge/Python-second-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-third-00ADD8?style=flat-square&logo=go&logoColor=white)

</div>

> Contribution graph is visible directly on the [GitHub profile](https://github.com/ramalakshmi0505).

---
