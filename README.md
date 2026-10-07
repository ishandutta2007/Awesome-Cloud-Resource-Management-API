# Awesome-Cloud-Resource-Management-API 🔌 ☁️

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Cloud Resource Management API Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Resource-Management-API"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Cloud-Resource-Management-API?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Resource-Management-API/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Cloud-Resource-Management-API?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Resource-Management-API/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Cloud-Resource-Management-API?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Cloud Resource Management API & IaC Ecosystem

**A Curated List of Cloud Resource Management APIs, Commercial Control Planes, & Open-Source Infrastructure-as-Code (IaC) Automation Frameworks** ⚡  

*Focused on Unified Resource Provisioning, Declarative Infrastructure, Multi-Cloud Control Planes, Policy-as-Code & Self-Hosted GitOps Automation*

**Last updated: October 2026** 📅

---

### 📌 Overview & Market Insight 🚀

Welcome to the definitive curated directory of **cloud resource management APIs**, **open-source Infrastructure-as-Code (IaC) tools**, and **multi-cloud control plane engines**. Whether you are evaluating hyperscaler-native APIs (such as *AWS Cloud Control API*, *Azure Resource Manager*, and *Google Cloud Resource Manager*), enterprise commercial platforms (*HCP Terraform*, *Pulumi Cloud*, *Spacelift*), or privacy-preserving open-source tools (*Crossplane*, *OpenTofu*, *Terragrunt*, *Terrakube*), this catalog covers leading tools for automated cloud infrastructure provisioning and governance.

**Key Market Context:**
- **AWS Cloud Control API** offers a **standardized REST API** for uniform create, read, update, delete, and list (CRUD+L) operations across AWS resources with **immediate consistency**. ☁️
- **Crossplane** is a **CNCF graduated project** converting Kubernetes clusters into universal cloud control planes with **continuous drift reconciliation**. ☸️
- **OpenTofu** stands as the **Linux Foundation & CNCF backed open-source fork** of Terraform featuring state encryption, enhanced provider caching, and community governance. 🍞

---

## 📑 Table of Contents

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS & Commercial Platforms

> 📈 **Market Size & Structure Analysis:** The global Cloud Management & Infrastructure Automation Market is estimated at **$28.5 Billion in 2026** (projected to reach $55+ Billion by 2030 at a ~18% CAGR). The market structure is **moderately fragmented**: while hyper-scaler providers (Microsoft, Amazon, Alphabet) dominate native baseline control planes, specialized independent vendors (IBM/HashiCorp, Pulumi, Spacelift, env0) capture significant high-margin enterprise market share for multi-cloud orchestration and policy-as-code governance.

*Sorted by Company Revenue / Market Valuation (Descending)* 📊

| SaaS / Commercial Platform | Company / Owner | Valuation / Revenue / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Azure Resource Manager](https://azure.microsoft.com/en-us/products/azure-resource-manager/)** 🔷 | Microsoft | ~$3.90 Trillion | **Free control plane** (pay for underlying Azure compute/storage) | **Free forever** (includes 12 months free popular services + $200 credit) | **Azure-native deployment & management** — Declarative templates (ARM/Bicep), Resource groups, and enterprise RBAC/policy enforcement. |
| **[AWS Cloud Control API](https://aws.amazon.com/cloudcontrolapi/)** ☁️ | Amazon | ~$2.0 Trillion | **Free API** (pay only for provisioned AWS resources) | **Free forever** (AWS Free Tier includes 750 hrs EC2, 5GB S3 monthly) | **AWS-native unified API** — Standardized CRUD+L REST operations across AWS services with uniform JSON schemas and CloudFormation registry support. |
| **[Google Cloud Resource Manager](https://cloud.google.com/resource-manager)** 🌐 | Google (Alphabet) | ~$2.0 Trillion | **Free API** (pay for underlying GCP resources) | **Free forever** (GCP Free Tier includes $300 trial credit + 20+ free products) | **GCP-native resource hierarchy** — Organizations, folders, and projects with IAM controls, tagging, and organization policies. |
| **[HCP Terraform](https://www.hashicorp.com/products/terraform)** 🏗️ | HashiCorp (IBM) | ~$5.0 Billion (Acquisition) | **$0.00014 / resource / hour** (Plus tier) | **Free tier: Up to 500 managed resources** | **Managed Terraform platform** — Remote state management, VCS integration, private module registry, and Sentinel policy-as-code. |
| **[Pulumi Cloud](https://www.pulumi.com/)** 🚀 | Pulumi | ~$750 Million Valuation | **$30 / user / month** (Team tier) | **Free tier: 1 user & up to 150 managed resources/month** | **Modern Infrastructure as Code** — Write IaC in TypeScript, Python, Go, C#, or Java with state management, secrets, and policy enforcement. |
| **[env0](https://www.env0.com/)** ⚡ | env0 | ~$250 Million Valuation | **$49 / active environment / month** (Pro tier) | **Free tier: Up to 3 active environments & 250 deployments/month** | **Multi-IaC FinOps platform** — Infrastructure management for Terraform, OpenTofu, Terragrunt, Pulumi, and CloudFormation with built-in cost controls. |
| **[Spacelift](https://spacelift.io/)** 🎛️ | Spacelift | ~$200 Million Valuation | **$299 / month** (Includes 2 concurrent runs) | **14-Day Free Trial** (Unlimited features during trial period) | **Multi-IaC orchestration platform** — Declarative workflow manager for Terraform, OpenTofu, Pulumi, and CloudFormation with OPA policy hooks. |
| **[Scalr](https://scalr.io/)** ⚙️ | Scalr | ~$100 Million Valuation | **$0.00008 / resource / hour** (Beyond free tier) | **Free tier: Up to 50 runs / month & 500 managed resources** | **Terraform & OpenTofu automation platform** — Drop-in replacement for Terraform Cloud with OPA policies, drift detection, and OIDC auth. |
| **[Terrateam](https://terrateam.io/)** 🐙 | Terrateam | ~$15 Million Valuation | **$19 / user / month** (Commercial tier) | **Free tier: Free for open-source repositories & 1 user** | **GitHub-native GitOps for Terraform** — Automates Terraform, OpenTofu, CDKTF, and Terragrunt execution directly via GitHub pull requests. |
| **[StackGuardian](https://www.stackguardian.io/)** 🛡️ | StackGuardian | ~$10 Million Valuation | **$50 / workspace / month** | **Free tier: Up to 2 workspaces & 50 runs/month** | **Policy-as-Code GitOps platform** — Infrastructure orchestration with OPA/Rego policy enforcement and self-hosted workflow runners. |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub Stars_Count (Descending)* 🌟

- **[Terraform](https://github.com/hashicorp/terraform)** [![Stars](https://img.shields.io/github/stars/hashicorp/terraform?style=social&color=white)](https://github.com/hashicorp/terraform/stargazers) 🏗️  
  **Declarative Infrastructure as Code CLI tool**, BUSL-1.1 licensed. Enables building, changing, and versioning cloud infrastructure safely and efficiently across hundreds of public and private cloud providers.

- **[Pulumi CLI](https://github.com/pulumi/pulumi)** [![Stars](https://img.shields.io/github/stars/pulumi/pulumi?style=social&color=white)](https://github.com/pulumi/pulumi/stargazers) 🚀  
  **Developer-first Infrastructure as Code SDK**, Apache-2.0 licensed. Provision infrastructure using general-purpose programming languages like TypeScript, Python, Go, C#, and Java.

- **[Crossplane](https://github.com/crossplane/crossplane)** [![Stars](https://img.shields.io/github/stars/crossplane/crossplane?style=social&color=white)](https://github.com/crossplane/crossplane/stargazers) ☸️  
  **Kubernetes-based universal control plane for cloud infrastructure**, Apache-2.0 licensed. **CNCF graduated project** — turns cloud resources into Kubernetes Custom Resources (CRDs) with continuous reconciliation and self-service API compositions.

- **[Checkov](https://github.com/bridgecrewio/checkov)** [![Stars](https://img.shields.io/github/stars/bridgecrewio/checkov?style=social&color=white)](https://github.com/bridgecrewio/checkov/stargazers) 🔍  
  **Static analysis security scanner for IaC**, Apache-2.0 licensed. Scans Terraform, CloudFormation, Kubernetes, Dockerfile, and ARM templates for security and compliance misconfigurations.

- **[Terragrunt](https://github.com/gruntwork-io/terragrunt)** [![Stars](https://img.shields.io/github/stars/gruntwork-io/terragrunt?style=social&color=white)](https://github.com/gruntwork-io/terragrunt/stargazers) 📦  
  **Thin wrapper for Terraform and OpenTofu**, MIT licensed. Keeps code DRY, manages remote state automatically, handles module dependency graphs, and executes stack-wide deployments.

- **[LocalStack](https://github.com/localstack/localstack)** [![Stars](https://img.shields.io/github/stars/localstack/localstack?style=social&color=white)](https://github.com/localstack/localstack/stargazers) 🧪  
  **Fully functional local AWS cloud stack**, Apache-2.0 licensed. Develop and test cloud and serverless apps offline without connecting to actual AWS services.

- **[OpenTofu](https://github.com/opentofu/opentofu)** [![Stars](https://img.shields.io/github/stars/opentofu/opentofu?style=social&color=white)](https://github.com/opentofu/opentofu/stargazers) 🍞  
  **Community-driven open-source Terraform fork**, MPL-2.0 licensed. **Linux Foundation & CNCF Sandbox project** featuring state encryption, client-side provider caching, and open governance.

- **[Atlantis](https://github.com/runatlantis/atlantis)** [![Stars](https://img.shields.io/github/stars/runatlantis/atlantis?style=social&color=white)](https://github.com/runatlantis/atlantis/stargazers) 🏛️  
  **Terraform Pull Request Automation Framework**, Apache-2.0 licensed. Executes `terraform plan` and `apply` directly inside PR comments with lock management.

- **[Terratest](https://github.com/gruntwork-io/terratest)** [![Stars](https://img.shields.io/github/stars/gruntwork-io/terratest?style=social&color=white)](https://github.com/gruntwork-io/terratest/stargazers) 🧪  
  **Go framework for automated infrastructure testing**, Apache-2.0 licensed. Write unit and integration tests in Go for Terraform, Helm, Docker, and Kubernetes configurations.

- **[tfsec](https://github.com/aquasecurity/tfsec)** [![Stars](https://img.shields.io/github/stars/aquasecurity/tfsec?style=social&color=white)](https://github.com/aquasecurity/tfsec/stargazers) ⚡  
  **Ultra-fast static security scanner for Terraform**, MIT licensed. Scans Terraform code for security risks in CI/CD pipelines with SARIF output support.

- **[Terramate](https://github.com/terramate-io/terramate)** [![Stars](https://img.shields.io/github/stars/terramate-io/terramate?style=social&color=white)](https://github.com/terramate-io/terramate/stargazers) 🗂️  
  **Code generator & orchestrator for Terraform/OpenTofu**, MPL-2.0 licensed. Simplifies multi-stack environment management, change detection, and code generation.

- **[Infracost](https://github.com/infracost/infracost)** [![Stars](https://img.shields.io/github/stars/infracost/infracost?style=social&color=white)](https://github.com/infracost/infracost/stargazers) 💰  
  **Cloud cost estimates for Terraform in pull requests**, Apache-2.0 licensed. Shows cloud cost diffs before launching infrastructure.

- **[Terrakube](https://github.com/terrakube-io/terrakube)** [![Stars](https://img.shields.io/github/stars/terrakube-io/terrakube?style=social&color=white)](https://github.com/terrakube-io/terrakube/stargazers) 🏢  
  **Self-hosted Terraform Cloud alternative**, Apache-2.0 licensed. Remote execution backend with state management, private registry, RBAC, and custom workflows.

- **[Digger](https://github.com/diggerhq/digger)** [![Stars](https://img.shields.io/github/stars/diggerhq/digger?style=social&color=white)](https://github.com/diggerhq/digger/stargazers) 🦴  
  **Open-source IaC orchestrator for existing CI engines**, MIT licensed. Runs Terraform/OpenTofu inside GitHub Actions or GitLab CI without external SaaS dependency.

- **[Terratag](https://github.com/env0/terratag)** [![Stars](https://img.shields.io/github/stars/env0/terratag?style=social&color=white)](https://github.com/env0/terratag/stargazers) 🏷️  
  **Automated resource tagging CLI for IaC**, MPL-2.0 licensed. Automatically injects tags and labels into Terraform/Terragrunt resources across AWS, Azure, and GCP.

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new resource management APIs or open-source IaC software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Cloud-Resource-Management-API&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Cloud-Resource-Management-API&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this cloud resource management API repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow platform engineers, DevOps practitioners, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

Thank you for supporting open-source software! ❤️

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Terraform's license changed to BUSL-1.1 in 2023**, driving the **OpenTofu fork under Linux Foundation/CNCF governance** with MPL-2.0 license. Review licensing implications for your organization before standardizing on either tool.
- **Crossplane requires a healthy Kubernetes cluster as critical infrastructure** — if the cluster fails, infrastructure reconciliation stops.
- **AWS Cloud Control API, Azure Resource Manager, and Google Cloud Resource Manager are free control planes** — you pay only for underlying resources provisioned.
- **Open-source IaC tools are not turnkey** — always validate with a proof-of-concept before migrating production infrastructure workflows. 🔌

---

<p align="center">
  <b>Made with ❤️ for platform engineers, DevOps practitioners, and open-source infrastructure advocates.</b>
</p>
