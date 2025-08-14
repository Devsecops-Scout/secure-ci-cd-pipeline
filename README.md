# ------------------------------------------------------------------------
# Description: Secure CI/CD Pipeline with Automated Security Gates
# Author: Devsecops-Scout
# Last Updated: 2025-07-19
# ------------------------------------------------------------------------

# Secure CI/CD Pipeline with Automated Security Gates

> A full-stack CI/CD pipeline with built-in security controls and compliance checks, tailored for regulated environments such as federal and enterprise systems.

---

## 🚀 Overview

This project demonstrates a secure, automated CI/CD pipeline with integrated scanning tools, policy gates, secrets management, and infrastructure as code—aligned with DevSecOps best practices.

---

## 🛠️ Tech Stack

- **CI/CD:** GitLab CI/CD
- **Containers:** Docker
- **Security Scanners:** Trivy, Gitleaks, CodeQL
- **IaC:** Terraform
- **Secrets Management:** HashiCorp Vault
- **Cloud:** AWS (Simulated/Free Tier)

---

## 🔐 Security Features

- Static and dynamic code scanning (SAST/DAST)
- Dependency scanning and CVE reporting
- Secrets detection in source code
- Container image hardening and scanning
- Role-based access control (RBAC)
- IaC compliance validation with Open Policy Agent (OPA)

---

## 📊 Architecture

![Pipeline Architecture](./diagrams/secure-pipeline-arch.drawio)
![Pipeline Architecture](./screenshots/pipeline-flow.png)

---

## 🧩 Compliance Mapping

| Control Framework  | Implemented? | Notes                   |
|--------------------|--------------|-------------------------|
| NIST 800-53 Rev.5  | ✅           | AC, AU, SC, SI families |
| FedRAMP Moderate   | ✅           | Evidence captured       |
| DoD STIG           | Partial      | Based on IronBank images |

See full [Compliance Mapping](./docs/compliance-mapping.md)

---

## 📂 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/Devsecops-Scout/secure-ci-cd-pipeline.git
