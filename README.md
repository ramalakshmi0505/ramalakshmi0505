<div align="center">

# Ramalakshmi Mani (Rama)
### Senior Cloud & Platform Engineer

*Building cloud platforms that teams deploy on without raising a ticket*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ramalakshmim-1F6F7A?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ramalakshmim)
[![Location](https://img.shields.io/badge/📍_Relocating_to-Netherlands-FF6B35?style=for-the-badge)](https://linkedin.com/in/ramalakshmim)
[![Visa](https://img.shields.io/badge/Kennismigrant-Visa_Eligible-1F6F7A?style=for-the-badge)](https://linkedin.com/in/ramalakshmim)

</div>

---

<div align="center">

| ☁️ 11 Years | 🏢 7 Companies | 🌍 5 Industries |
|:---:|:---:|:---:|
| **30% lower cloud cost** | **70% faster onboarding** | **6 hrs → 30 min provisioning** |

</div>

---

## 👩‍💻 About

I design and automate the foundational layer teams build on: account and environment provisioning, VPC and IAM, security guardrails, cost controls, and the observability that ties it all together - across AWS, Azure, and GCP.

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

### ☸️ Kubernetes & Platform

<table>
<tr>
<td width="50%" valign="top">

### [workspace-operator](https://github.com/ramalakshmi0505/workspace-operator)
Kubernetes controller that provisions a team namespace, ResourceQuota, and admin RBAC from a single custom resource. Full kubebuilder layout with CRD, reconcile loop, owner references, and status subresource.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![controller-runtime](https://img.shields.io/badge/controller--runtime-gray?style=flat-square)

</td>
<td width="50%" valign="top">

### [k8s-cost-optimizer](https://github.com/ramalakshmi0505/k8s-cost-optimizer)
Identifies oversized workloads, unused resources, and right-sizing opportunities across namespaces. Built from real cost-reduction work at DXC (30% saving replicated across 10+ BUs).

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [gitops-drift-detector](https://github.com/ramalakshmi0505/gitops-drift-detector)
Scans ArgoCD apps for config drift and raises alerts before the gap between desired and actual state causes an incident.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

</td>
<td width="50%" valign="top">

### [istio-ambient-demo](https://github.com/ramalakshmi0505/istio-ambient-demo)
Hands-on demo of Istio ambient mesh mode on EKS. Zero-trust mTLS without sidecars. Built after completing the Kubernetes with Istio course.

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

</td>
</tr>
</table>

---

### ☁️ Cloud Infrastructure & IaC

<table>
<tr>
<td width="33%" valign="top">

### [aws-automated-provisioning](https://github.com/ramalakshmi0505/aws-automated-provisioning)
Multi-environment Terraform and CloudFormation reference architecture with full CI/CD. Modelled on real Vodafone provisioning work.

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

</td>
<td width="33%" valign="top">

### [azure-webapp-terraform](https://github.com/ramalakshmi0505/azure-webapp-terraform)
Azure Web Application provisioned entirely with Terraform. Demonstrates multi-cloud IaC patterns across Azure App Service, networking, and IAM.

![HCL](https://img.shields.io/badge/HCL-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

</td>
<td width="33%" valign="top">

### [terraform-plan-on-pr](https://github.com/ramalakshmi0505/terraform-plan-on-pr)
GitHub Actions workflow that runs Terraform plan on every pull request and posts the diff as a comment. Drop-in for any Terraform repo.

![HCL](https://img.shields.io/badge/HCL-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</td>
</tr>
</table>

---

### 🤖 Automation, AI & n8n

<table>
<tr>
<td width="50%" valign="top">

### [job-feed-builder](https://github.com/ramalakshmi0505/job-feed-builder)
n8n workflow that pulls open roles from company career pages and drops the matches into a sheet daily. Built to automate a 60+ company NL job search.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

</td>
<td width="50%" valign="top">

### [ats-resolver](https://github.com/ramalakshmi0505/ats-resolver)
Give it a list of company names, it probes six public ATS APIs and returns the exact endpoint to pull their open roles. Feeds the job-feed-builder.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [rag-infra-bot](https://github.com/ramalakshmi0505/rag-infra-bot)
RAG infrastructure knowledge bot using PostgreSQL and pgvector. Ask it questions about your infrastructure; it retrieves from a vector store of your own docs.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-gray?style=flat-square)

</td>
<td width="50%" valign="top">

### [n8n-aws-cost-alerts](https://github.com/ramalakshmi0505/n8n-aws-cost-alerts)
Automated AWS cost monitoring with n8n on EKS. Detects spend anomalies and routes alerts to the right team. No manual dashboard checking.

![HCL](https://img.shields.io/badge/HCL-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [n8n-recruitment-automation](https://github.com/ramalakshmi0505/n8n-recruitment-automation)
AI-powered CV screening and candidate pipeline automation with working n8n JSON workflow. End-to-end from intake to shortlist.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![AI](https://img.shields.io/badge/AI--powered-1F6F7A?style=flat-square)

</td>
<td width="50%" valign="top">

### [n8n-copilot-instructions](https://github.com/ramalakshmi0505/n8n-copilot-instructions)
GitHub Copilot instructions optimised for n8n workflow development. Speeds up building automation nodes with AI assistance.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Copilot](https://img.shields.io/badge/GitHub_Copilot-2088FF?style=flat-square&logo=github&logoColor=white)

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

![Streak](https://streak-stats.demolab.com?user=ramalakshmi0505&hide_border=true&ring=1F6F7A&fire=1F6F7A&currStreakLabel=1F6F7A&dates=666666&sideLabels=333333&sideNums=1F6F7A&currStreakNum=1F6F7A&width=500)

<<<<<<< HEAD
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ramalakshmi0505&layout=compact&hide_border=true&title_color=1F6F7A&text_color=333333&bg_color=ffffff&langs_count=8&card_width=500)
=======
>>>>>>> 40539f55aa5871eaa0fba0e8ab39f0612af6b569

</div>

---

<<<<<<< HEAD
=======
## 🚧 Currently Building

- **workspace-operator** - Go Kubernetes controller, kubebuilder layout, full reconcile loop
- **CKA prep** - Certified Kubernetes Administrator exam track
- **NL job search automation** - n8n pipeline pulling open roles from 60+ IND-recognised sponsor companies

---

>>>>>>> 40539f55aa5871eaa0fba0e8ab39f0612af6b569
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

*Open to Senior Cloud, Platform & DevOps roles in the Netherlands*

</div>
