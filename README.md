<h1 align="center">Hi, I'm Elikem Adablah 👋</h1>

<p align="center">
  <b>Cloud &amp; DevOps Engineer · AWS-native infrastructure</b><br/>
  Serverless (Lambda · API Gateway · DynamoDB) + infrastructure as code (Terraform · Docker · GitHub Actions)<br/>
  AWS Certified Solutions Architect – Associate · University of Texas at Tyler · Dallas–Fort Worth, TX
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/elikem-adablah-92978235b">LinkedIn</a> ·
  <a href="mailto:elikadablah@gmail.com">Email</a> ·
  <a href="https://cv.eliadablah.com">Live CV</a>
</p>

---

I'm a cloud engineer who builds AWS systems end-to-end — from the Terraform that creates them to the pipeline that deploys them and the alarms that watch them. I'm an AWS Certified Solutions Architect – Associate, and I care about least-privilege security, low cost, and infrastructure I can rebuild with one command.

My day job is IT support at **Applied Systems**, and most of what I build lives at the intersection of serverless AWS, infrastructure as code, and CI/CD.

## 🔭 What I'm building

- **[Budget App Tracker](https://github.com/eliadablah/budget-app-tracker)** — I built and own a personal-finance app running live on AWS. React + Vite + TypeScript dashboard on S3 and CloudFront, a TypeScript API packaged as a Docker image on Lambda behind API Gateway, DynamoDB for data, Cognito for login, and Plaid for bank transactions. It tracks bills, partial payments, and monthly budgets by spending category, with warnings at 80% and 100%.
- **The platform behind it** — everything is Terraform, with separate **live and staging environments** deployed from their own Git branches through GitHub Actions. Deploys are keyless (OIDC), each deploy role trusts only its own branch, and a workspace guard stops staging settings from ever being applied to the live app. A second Lambda on EventBridge Scheduler sends DKIM-signed reminder emails through SES, and CloudWatch alarms and a dashboard watch it all. Lambdas run outside a VPC on purpose, which avoids a NAT Gateway (about $33/month).

## 🛠️ Tech I work with

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HCL](https://img.shields.io/badge/HCL-844FBA?style=flat-square&logo=terraform&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Cloud (AWS)** Lambda · API Gateway · S3 · CloudFront · DynamoDB · RDS · EC2 · ECS · ECR · Route 53 · IAM · Cognito · SES · SNS · CloudWatch · EventBridge · Glue · Athena

**Infrastructure &amp; DevOps**
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

**Web**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**IT &amp; Support** Freshdesk · Jira Service Desk · ServiceNow APIs · Network administration · Troubleshooting

## 📌 Featured projects

| Project | What it is | Stack |
| --- | --- | --- |
| [Budget App Tracker](https://github.com/eliadablah/budget-app-tracker) | Personal-finance app with bank sync, bills, budgets, and email reminders, running in live and staging environments | TypeScript · React · Lambda · DynamoDB · Terraform |
| [Serverless CV site](https://github.com/eliadablah/CV-) | My live CV at [cv.eliadablah.com](https://cv.eliadablah.com), redesigned from an always-on setup (about $145/month) to under $1/month | Python · Docker · Lambda · CloudFront · Terraform |
| [UTC Student Services Portal](https://github.com/eliadablah/utcapp) | Three-tier, multi-AZ AWS environment where only the load balancer is public | Terraform · ALB · EC2 Auto Scaling · RDS MySQL |
| [ECS CI/CD pipeline](https://github.com/eliadablah/ecs-cicd-pipeline) | Container build-and-deploy pipeline for Amazon ECS | Docker · GitHub Actions · ECS |

## 💼 Experience

- **IT Support Technician III @ Applied Systems** (Aug 2025–present)
- **Generalist AI Expert @ Mercor** (Aug 2026–Oct 2026) — evaluated and rated AI model outputs across IT support, cloud infrastructure, and DevOps, wrote reference responses used to train large language models, and tested AI-generated code, CLI commands, and configurations for correctness and security.
- **Cloud Engineer @ Novrupt** (Dec 2025–May 2026) — built REST APIs with OAuth and RBAC, ETL pipelines with AWS Glue and PySpark, CI/CD with GitHub Actions and Jenkins, and cost tooling that cut cloud spend by over 20%.
- **Information Technology Intern @ Southside Bank** (May 2024–Aug 2024) — rotated through cybersecurity operations, identity and access management, infrastructure, and network teams.

## 📜 Certifications

- **AWS Certified Solutions Architect – Associate** — Amazon Web Services (Apr 2026)
- **Foundations of Cybersecurity** — Google (Nov 2024)

## 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/elikem-adablah-92978235b) · [elikadablah@gmail.com](mailto:elikadablah@gmail.com)

*I build on AWS for real use — but the fundamentals (least privilege, infrastructure as code, tested pipelines) come first.*
