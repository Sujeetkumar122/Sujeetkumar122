<div align="center">

<img src="./assets/banner.svg" alt="Sujeet Kumar - Senior Azure & DevOps Engineer" width="100%" />

<a href="https://readme-typing-svg.demolab.com/">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=20&pause=1200&color=00E5FF&center=true&vCenter=true&width=900&height=60&lines=Senior+Azure+%26+DevOps+Engineer;17%2B+Years+of+IT+Experience+%7C+Enterprise+Infrastructure;Terraform+Modular+IaC+(for_each%2C+maps%2C+dynamic+blocks);Azure+DevOps+(ADO)+Multi-Stage+YAML+Pipelines;Git%2C+GitHub+Actions+%26+Azure+Cloud+Solutions" alt="Sujeet Kumar Headline" />
</a>

### ☁️ Senior Azure & DevOps Engineer | 17+ Years IT Experience

**Microsoft Azure · Terraform (IaC) · Azure DevOps (ADO) · CI/CD Pipelines · Git & GitHub**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sujeetkumar122)
[![GitHub](https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sujeetkumar122?tab=repositories)
[![Azure Cloud](https://img.shields.io/badge/Focus-Azure_%26_DevOps-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](#-featured-repositories)
[![Status](https://img.shields.io/badge/Status-Open_to_Opportunities-16803D?style=for-the-badge)](#-connect-with-me)

</div>

---

## 👋 About Me

I am a **Senior Azure & DevOps Engineer** with **17+ years of IT experience**, with a solid track record in designing, automating, and maintaining enterprise infrastructure on **Microsoft Azure**.

My core hands-on expertise spans **Terraform Infrastructure as Code (IaC)**, **Azure DevOps (ADO) multi-stage YAML pipelines**, **Git / GitHub workflows**, and **Azure cloud architecture**. I focus on building reliable, repeatable infrastructure, automating application deployments, and streamlining team delivery without overcomplicating systems.

### 💼 What I Do:
* ☁️ **Azure Cloud Infrastructure:** Provisioning and managing VNets, Subnets, Network Security Groups (NSGs), Virtual Machines, Storage Accounts, Key Vaults, and Azure Kubernetes Service (AKS).
* 🏗️ **Terraform Automation:** Writing production-ready, reusable Terraform modules using `for_each`, maps, `dynamic` blocks, variables validation, and remote state backends with Azure Blob Storage lease locks.
* 🔄 **CI/CD with Azure DevOps & GitHub:** Designing multi-stage YAML pipelines for continuous integration and deployment, managing self-hosted and Microsoft-hosted build agents, service connections, and approval gates.
* 🔒 **Security & Secrets Management:** Storing and retrieving credentials, certificates, and keys securely using Azure Key Vault, Managed Identities, and RBAC roles.
* 📊 **Monitoring & Operations:** Writing practical KQL queries in Azure Log Analytics to track VM performance, heartbeats, storage usage, and operational alerts.
* 🛠️ **Scripting & Automation:** Writing PowerShell and Bash scripts for routine operational tasks, inventory reports, and cost-saving cleanup of orphaned resources.

---

## 🧭 Real-World DevOps & Azure Architecture Flow

```mermaid
flowchart LR
    subgraph SCM["Source Code & Version Control"]
        A[Git Repository<br/>GitHub / ADO] -->|Feature Branch| B[Pull Request & Code Review]
        B -->|Merge to Main| C[Trigger Pipeline]
    end

    subgraph ADO["Azure DevOps CI/CD Pipeline"]
        C --> D[Lint & Terraform Validate]
        D --> E[Terraform Plan]
        E -->|Approval Gate| F[Terraform Apply]
    end

    subgraph State["Remote State Backend"]
        F <-->|State & Lease Lock| G[Azure Storage Account<br/>Blob Container]
    end

    subgraph Azure["Microsoft Azure Infrastructure"]
        F --> H[Virtual Network & Subnets]
        F --> I[Network Security Groups]
        F --> J[Virtual Machines & Scale Sets]
        F --> K[Azure Kubernetes Service AKS]
        F --> L[Key Vault & Secrets]
    end

    subgraph Monitor["Observability"]
        H & I & J & K --> M[Azure Monitor & Log Analytics]
        M --> N[KQL Dashboards & Alerts]
    end

    classDef blue fill:#0B1F3A,stroke:#0078D4,stroke-width:2px,color:#fff;
    classDef green fill:#052e16,stroke:#10b981,stroke-width:2px,color:#fff;
    classDef amber fill:#331a00,stroke:#f59e0b,stroke-width:2px,color:#fff;
    class A,B,C blue;
    class D,E,F,G amber;
    class H,I,J,K,L,M,N green;
```

---

## 🧰 Technical Skills

<div align="center">

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=azure,terraform,githubactions,git,github,powershell,bash,linux,docker,kubernetes,vscode&perline=6" alt="Tech Stack" />
</a>

</div>

<br/>

| Category | Technologies & Tools |
|---|---|
| ☁️ **Cloud Platform** | Microsoft Azure (VNets, Subnets, NSGs, Route Tables, VMs, Storage Accounts, Key Vault, AKS, Azure Bastion, Private Endpoints) |
| 🏗️ **Infrastructure as Code** | Terraform (`for_each`, maps, `dynamic` blocks, module development, state migration, backend storage locking) |
| 🔄 **CI / CD Tools** | Azure DevOps (ADO Pipelines, Multi-Stage YAML, Releases, Environments, Service Connections), GitHub Actions |
| 🌿 **Version Control** | Git, GitHub, Branching Strategies (GitFlow, Trunk-based), Pull Requests, Branch Protection Rules |
| 📜 **Scripting & Shell** | PowerShell, Azure CLI (`az cli`), Bash, Linux Administration |
| ☸️ **Containers** | Docker, Azure Kubernetes Service (AKS), Container Registry (ACR), Pods, Services, Ingress |
| 📊 **Monitoring** | Azure Monitor, Log Analytics Workspaces, KQL (Kusto Query Language), Metric Alerts |
| 🔐 **Security & Access** | Azure Active Directory / Entra ID, RBAC, Managed Identities, Azure Key Vault |

---

## 🚀 Featured Repositories

### 1. 🏗️ [`azure-enterprise-landing-zones`](https://github.com/Sujeetkumar122/azure-enterprise-landing-zones)
Modular, production-ready Terraform repository demonstrating advanced language constructs (`for_each`, maps, and `dynamic` blocks).
* **Terraform Highlights:** Uses `dynamic "security_rule"` inside NSG modules, `for_each` over subnets and route tables, and remote state backend locking in Azure Blob Storage.
* **Architecture:** Enterprise Hub-and-Spoke network topology with dedicated subnets for Firewall, Gateway, and Workload tiers.
* **CI/CD:** Automated multi-stage Azure DevOps YAML pipeline running `terraform validate`, `plan`, and `apply`.

[**View Repository →**](https://github.com/Sujeetkumar122/azure-enterprise-landing-zones)

---

### 2. 🔄 [`azure-devops-yaml-ci-cd-templates`](https://github.com/Sujeetkumar122/azure-devops-yaml-ci-cd-templates)
Production-grade Azure DevOps YAML pipeline templates designed for real-world development workflows.
* **Template Architecture:** Reusable template structure for Build, Test, Security Scan, and Multi-Environment Deployments (Dev, Stage, Prod).
* **Best Practices:** Parameterized inputs, service connection integrations, artifact publishing, and manual approval gates before production releases.

[**View Repository →**](https://github.com/Sujeetkumar122/azure-devops-yaml-ci-cd-templates)

---

### 3. ☸️ [`azure-kubernetes-aks-terraform`](https://github.com/Sujeetkumar122/azure-kubernetes-aks-terraform)
Clean, standard Terraform module to provision and configure Azure Kubernetes Service (AKS).
* **Components:** System node pool, user node pool, Azure CNI networking, Managed Identity, and integration with Azure Monitor.
* **Practical Design:** Readable variables, outputs, and `.tfvars` examples that can be directly adapted for customer projects.

[**View Repository →**](https://github.com/Sujeetkumar122/azure-kubernetes-aks-terraform)

---

### 4. 💰 [`azure-cost-optimization-automation`](https://github.com/Sujeetkumar122/azure-cost-optimization-automation)
Practical PowerShell and Azure CLI automation scripts to identify and clean up unattached cloud resources.
* **Cost Savings:** Detects unattached Azure Managed Disks, obsolete snapshots, and unused Public IPs.
* **Automation:** Generates CSV inventory reports with estimated cost waste and includes scheduled VM auto-shutdown runbooks.

[**View Repository →**](https://github.com/Sujeetkumar122/azure-cost-optimization-automation)

---

### 5. 📊 [`azure-monitoring-log-analytics-kql`](https://github.com/Sujeetkumar122/azure-monitoring-log-analytics-kql)
Curated collection of practical KQL (Kusto Query Language) queries for day-to-day Azure cloud operations and monitoring.
* **Operational Queries:** VM Heartbeat status, CPU & memory utilization thresholds, failed user logins, storage operations, and NSG flow logs.
* **Alert Rules:** Ready-to-use queries for setting up Azure Monitor metric and log alert rules.

[**View Repository →**](https://github.com/Sujeetkumar122/azure-monitoring-log-analytics-kql)

---

## 💡 How I Approach Daily Work

- **Keep It Simple & Maintainable:** Infrastructure should be easy to read, review, and maintain by any team member.
- **Automate Repetitive Tasks:** If a task has to be performed more than twice, automate it using Terraform, PowerShell, or CI/CD pipelines.
- **Security by Default:** Never commit secrets, passwords, or tokens in Git. Always use Azure Key Vault and Managed Identities.
- **Test Before Applying:** Always review `terraform plan` outputs and test pipeline changes in non-production environments first.
- **Collaborative Engineering:** Clear pull request descriptions, meaningful commit messages, and thorough documentation.

---

## 📈 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Sujeetkumar122&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true" alt="Sujeet Kumar's GitHub Stats" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Sujeetkumar122&theme=radical&hide_border=true" alt="GitHub Streak" width="48%" />

</div>

---

## 🤝 Connect With Me

I am always happy to connect with fellow DevOps engineers, cloud professionals, and tech teams.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sujeetkumar122)
[![GitHub](https://img.shields.io/badge/Follow_on-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sujeetkumar122)
[![Email](https://img.shields.io/badge/Email-Get_in_Touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sujeetkumar.devsecops@gmail.com)

<br/>

<img src="./assets/footer.svg" alt="Sujeet Kumar Footer" width="100%" />

</div>
