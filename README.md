# Paul Ademola Edukpe — DevSecOps & Cloud Security Engineer

Building and automating secure cloud infrastructure on AWS.

---

## What I do

I design security-first cloud infrastructure — automated threat detection, least-privilege IAM at scale, and shift-left security tooling integrated directly into CI/CD pipelines.

My focus: making security automatic, not manual.

---

## Featured project — PERP

**Proactive Enterprise Resilience Platform** · [View Repository →](https://github.com/ailojay/Perp)

A multi-account AWS security platform simulating a production enterprise security posture. Built and operated as sole architect.

| What | Result |
|---|---|
| GuardDuty → EventBridge → Lambda automated response pipeline | Compromised credential isolation in <60 seconds — 85% MTTC reduction |
| Security Hub aggregating findings across 3 accounts | 500+ daily findings with automated prioritisation |
| AWS Config conformance packs with auto-remediation | Public S3, unencrypted EBS, non-compliant SGs caught and fixed automatically |
| 15+ Terraform modules (VPC, IAM, ECS, Auto Scaling, logging) | Remote state via S3/DynamoDB, full modular multi-env architecture |
| ECS Fargate with blue/green deployments + auto-scaling | GitHub Actions OIDC auth, Terraform plan/apply automation, ECR image scanning |
| Environment lifecycle cost governance | $2,000+/month in savings through automated teardown |

---

## Other projects

**PolicyBot — Terraform IaC Security Scanner** · [View Repository →](https://github.com/ailojay/Policybot)  
Slack-integrated scanner processing 200+ Terraform files/week via GitHub Actions. Blocked 30+ high-risk changes, detected 150+ CIS benchmark violations. Reduced security debt by 70%.

**Cloud Cost Security Platform**  
AWS Budgets → Cost Explorer → EventBridge → Lambda anomaly detection. Flags potential cryptomining and resource hijacking within 15 minutes.

**Serverless Portfolio Platform**  
API Gateway → Lambda (Python) → DynamoDB. Debugged 5xx errors via CloudWatch, recovered infrastructure via Terraform state import.

---

## Core stack

```
Cloud & Security    AWS Organizations · GuardDuty · Security Hub · IAM (SCPs, Permission Boundaries)
                    VPC · ECS Fargate · Lambda · API Gateway · CloudWatch · Config · CloudTrail
                    KMS · Secrets Manager

IaC & Scanning      Terraform (modular, multi-env) · Checkov · tfsec · KICS · CloudFormation

CI/CD               GitHub Actions (OIDC) · Docker · ECR · EventBridge · Step Functions

Languages           Python (FastAPI, boto3) · Bash

In progress         Kubernetes (local Minikube cluster) · AWS SAA → Security Specialty
```

---

## Currently

- Building Kubernetes orchestration depth (Minikube → Argo CD → Prometheus/Grafana)
- Studying for AWS Solutions Architect Associate
- Open to remote Junior Cloud Security / DevSecOps roles — EMEA and global

---

📩 ademolaedukpe@gmail.com · [LinkedIn](https://linkedin.com/in/ademola-edukpe)
