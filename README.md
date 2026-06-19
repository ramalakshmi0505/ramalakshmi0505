<div align="center">
  
![header](https://capsule-render.vercel.app/api?type=rect&color=1F6F7A&height=200&text=Ramalakshmi%20Mani%20(Rama)&fontColor=ffffff&fontSize=42&desc=Senior%20Cloud%20Platform%20Engineer&descSize=20&descAlignY=78)

*Building cloud platforms that teams deploy on without raising a ticket*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ramalakshmim-1F6F7A?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ramalakshmim)
[![GitHub](https://img.shields.io/badge/GitHub-ramalakshmi0505-1F6F7A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ramalakshmi0505)
[![AWS](https://img.shields.io/badge/AWS-Certified_DevOps_Engineer-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://linkedin.com/in/ramalakshmim)

</div>


---

<div align="center">

| ☁️ 11 Years | 🏢 7 Companies | 🌍 5 Industries |
|:---:|:---:|:---:|
| **30% lower cloud cost** | **70% faster onboarding** | **6 hrs → 30 min provisioning** |

</div>

---

## 👩‍💻 About

I design and automate the foundational layer teams build on: account and environment provisioning, VPC and IAM, security guardrails, cost controls, and the observability that ties it all together across AWS, Azure, and GCP.

Currently running a **multi-region EKS platform across 3 AWS regions** at BMW TechWorks. I build in public: every tool here started as something I needed at work and couldn't find anywhere else.

---

## 🛠️ Stack

**Cloud & Containers**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

**IaC & GitOps**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

**Observability & Security**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black)
![Dynatrace](https://img.shields.io/badge/Dynatrace-1496FF?style=for-the-badge&logo=dynatrace&logoColor=white)

**Automation & AI**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

---

## 📦 Projects

*Newest first*

### [n8n-Platform-Configuration-Guide](https://github.com/ramalakshmi0505/n8n-Platform-Configuration-Guide)
A checklist for taking n8n from a teammate's personal workflow to a governed production platform. Step-by-step config for source control, SSO, external secrets, RBAC, log streaming, and queue-mode scaling, with n8n docs references for each.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

---

### [terraform-aws-modules](https://github.com/ramalakshmi0505/terraform-aws-modules)
Reusable, production-ready Terraform modules for AWS. Every project ends up rewriting the same VPC, EKS, RDS and S3 configs, this puts them in one place, versioned and validated. CI runs terraform validate + TFLint on every PR.

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### [eu-sovereign-idp](https://github.com/ramalakshmi0505/eu-sovereign-idp)
Self-service developer platform on EKS where the golden path enforces EU data residency, GDPR classification, and cost guardrails at admission. A Go operator provisions residency-stamped namespaces, Kyverno denies non-EU regions and storage, ArgoCD flags drift, Karpenter keeps nodes EU-only and right-sized.

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Kyverno](https://img.shields.io/badge/Kyverno-1F6F7A?style=flat-square)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

---

### [local-rag](https://github.com/ramalakshmi0505/local-rag)
Retrieval-augmented generation built from scratch and running fully local. Point it at your docs; it chunks them, embeds with Ollama, stores vectors in ChromaDB, and answers questions using only what it retrieved, with sources cited. About 300 lines of Python, no framework. Built after the LinkedIn Learning Local AI course.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-gray?style=flat-square)

---

### [aws-self-service-catalog](https://github.com/ramalakshmi0505/aws-self-service-catalog)
Self-service catalog of approved, pre-guardrailed AWS environments that teams can provision on demand without raising a ticket.

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

### [ats-resolver](https://github.com/ramalakshmi0505/ats-resolver)
Give it a list of company names, it probes six public ATS APIs and returns the exact endpoint to pull their open roles. Feeds the job-feed-builder.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

---

### [job-feed-builder](https://github.com/ramalakshmi0505/job-feed-builder)
n8n workflow that pulls open roles from company career pages and drops the matches into a sheet daily. Built to automate a 60+ company NL job search.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

---

### [terraform-plan-on-pr](https://github.com/ramalakshmi0505/terraform-plan-on-pr)
GitHub Actions workflow that runs Terraform plan on every pull request and posts the diff as a comment. Drop-in for any Terraform repo.

![HCL](https://img.shields.io/badge/HCL-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### [aws-automated-provisioning](https://github.com/ramalakshmi0505/aws-automated-provisioning)
Multi-environment Terraform and CloudFormation reference architecture with full CI/CD. Modelled on real Vodafone provisioning work.

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

### [istio-ambient-demo](https://github.com/ramalakshmi0505/istio-ambient-demo)
Hands-on demo of Istio ambient mesh mode on EKS. Zero-trust mTLS without sidecars. Built after completing the Kubernetes with Istio course.

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

### [rag-infra-bot](https://github.com/ramalakshmi0505/rag-infra-bot)
RAG infrastructure knowledge bot using PostgreSQL and pgvector. Ask it questions about your infrastructure; it retrieves from a vector store of your own docs.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-gray?style=flat-square)

---

### [azure-webapp-terraform](https://github.com/ramalakshmi0505/azure-webapp-terraform)
Azure Web Application provisioned entirely with Terraform. Demonstrates multi-cloud IaC patterns across Azure App Service, networking, and IAM.

![HCL](https://img.shields.io/badge/HCL-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

---

### [gitops-drift-detector](https://github.com/ramalakshmi0505/gitops-drift-detector)
Scans ArgoCD apps for config drift and raises alerts before the gap between desired and actual state causes an incident.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

---

### [k8s-cost-optimizer](https://github.com/ramalakshmi0505/k8s-cost-optimizer)
Identifies oversized workloads, unused resources, and right-sizing opportunities across namespaces. Built from real cost-reduction work at DXC (30% saving replicated across 10+ BUs).

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

---

### [n8n-recruitment-automation](https://github.com/ramalakshmi0505/n8n-recruitment-automation)
AI-powered CV screening and candidate pipeline automation with working n8n JSON workflow. End-to-end from intake to shortlist.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![AI](https://img.shields.io/badge/AI--powered-1F6F7A?style=flat-square)

---

### [n8n-copilot-instructions](https://github.com/ramalakshmi0505/n8n-copilot-instructions)
GitHub Copilot instructions optimised for n8n workflow development. Speeds up building automation nodes with AI assistance.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Copilot](https://img.shields.io/badge/GitHub_Copilot-2088FF?style=flat-square&logo=github&logoColor=white)

---

### [n8n-aws-cost-alerts](https://github.com/ramalakshmi0505/n8n-aws-cost-alerts)
Automated AWS cost monitoring with n8n on EKS. Detects spend anomalies and routes alerts to the right team. No manual dashboard checking.

![HCL](https://img.shields.io/badge/HCL-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

---

## 📈 Contributions

<div align="center">

## 📈 Contributions

<div align="center">

![Total Contributions](https://img.shields.io/badge/Total_Contributions-109-1F6F7A?style=for-the-badge&logo=github&logoColor=white)
![Public Repositories](https://img.shields.io/badge/Public_Repositories-17-1F6F7A?style=for-the-badge&logo=github&logoColor=white)

</div>

</div>

## 🎓 Certifications

| Certification | Issuer | Level |
|---|---|---|
| AWS DevOps Engineer | Amazon Web Services | Professional |
| AWS Solutions Architect | Amazon Web Services | Associate |
| AWS Developer | Amazon Web Services | Associate |

---

## 📬 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Let's_connect_on_LinkedIn-1F6F7A?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ramalakshmim)
[![Email](https://img.shields.io/badge/ramalakshmi0505@outlook.com-1F6F7A?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:ramalakshmi0505@outlook.com)



</div>
