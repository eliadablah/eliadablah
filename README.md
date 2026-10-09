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

- **[Budget App Tracker](https://github.com/eliadablah/budget-app-tracker)** — I built and own a personal-finance app that I run live on AWS. I wrote a React + Vite + TypeScript dashboard that I serve from S3 and CloudFront, and a TypeScript API that I package as a Docker image and run on Lambda behind API Gateway. I use DynamoDB for data, Cognito for login, and Plaid for my bank transactions. I use it to track my bills, partial payments, and monthly budgets by spending category, and it warns me at 80% and 100%.
- **The platform behind it** — I wrote all of it in Terraform, and I run separate **live and staging environments** that I deploy from their own Git branches through GitHub Actions. I made the deploys keyless (OIDC), I let each deploy role trust only its own branch, and I added a workspace guard so I can never apply staging settings to the live app. I added a second Lambda on EventBridge Scheduler that sends me DKIM-signed reminder emails through SES, and I watch it all with CloudWatch alarms and a dashboard. I run my Lambdas outside a VPC on purpose, which saves me a NAT Gateway (about $33/month).

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

## 📌 My featured projects

| Project | What I built | Stack I used |
| --- | --- | --- |
| [Budget App Tracker](https://github.com/eliadablah/budget-app-tracker) | My personal-finance app, where I sync my bank, track my bills and budgets, and get email reminders. I run it in live and staging environments | TypeScript · React · Lambda · DynamoDB · Terraform |
| [Serverless CV site](https://github.com/eliadablah/CV-) | My live CV at [cv.eliadablah.com](https://cv.eliadablah.com). I redesigned it from an always-on setup (about $145/month) to one I run for under $1/month | Python · Docker · Lambda · CloudFront · Terraform |
| [UTC Student Services Portal](https://github.com/eliadablah/utcapp) | A three-tier, multi-AZ AWS environment I wrote in Terraform, where I keep everything private except the load balancer | Terraform · ALB · EC2 Auto Scaling · RDS MySQL |
| [ECS CI/CD pipeline](https://github.com/eliadablah/ecs-cicd-pipeline) | A pipeline I built to build and deploy my containers to Amazon ECS | Docker · GitHub Actions · ECS |

## 💼 My experience

- **IT Support Technician III @ Applied Systems** (Aug 2025–present) — I work remotely in IT support, where I troubleshoot issues and work with Freshdesk and network services every day.
- **Generalist AI Expert @ Mercor** (Aug 2026–Oct 2026) — I evaluated and rated AI model outputs across IT support, cloud infrastructure, and DevOps. I wrote reference responses used to train large language models, and I tested AI-generated code, CLI commands, and configurations for correctness and security.
- **Cloud Engineer @ Novrupt** (Dec 2025–May 2026) — I built REST APIs with OAuth and RBAC, ETL pipelines with AWS Glue and PySpark, and CI/CD with GitHub Actions and Jenkins. I also wrote cost tooling that cut cloud spend by over 20%.
- **Information Technology Intern @ Southside Bank** (May 2024–Aug 2024) — I rotated through the cybersecurity operations, identity and access management, infrastructure, and network teams.

## 📜 My certifications

- I earned my **AWS Certified Solutions Architect – Associate** from Amazon Web Services in April 2026.
- I completed **Foundations of Cybersecurity** from Google in November 2024.

## 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/elikem-adablah-92978235b) · [elikadablah@gmail.com](mailto:elikadablah@gmail.com)

*I build on AWS for real use — but for me the fundamentals (least privilege, infrastructure as code, tested pipelines) come first.*
