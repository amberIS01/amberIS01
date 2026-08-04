<div align="center">

<img src="github-header.png" alt="Sahil Singh — Cloud Infrastructure · Backend · AI Pipelines" width="100%"/>

</div>

Software engineer at **Innosolve Labs** — the India engineering arm of a US healthcare AI
startup. I own our AWS infrastructure: production, staging, pre-stage, and everything
that pages me at 2 AM.

### What that's looked like this year

💸 **Cut our monthly AWS bill by 65%.** Not with a fancy tool — by actually reading the
console. Right-sized instances, deleted orphaned EBS volumes that had been billing us
since before I joined, killed snapshots nobody could explain.

📟 **Built the monitoring stack from zero.** 12 custom interceptors watching API health,
AI cost per request, and Celery task failures. Alerts over email, SMS, and WhatsApp,
deduplicated through Redis so nobody gets paged twice for the same fire.

🔐 **Locked down the perimeter** after a bot spent a night brute-forcing our SSH.
Audited every security group, restricted ingress to known CIDRs, rolled out GuardDuty,
rotated every IAM key — then moved deployments to SSM so there's no SSH door left to
knock on.

🤖 **Wired Claude and OpenAI into clinical document pipelines** — classification, note
generation, ICD-10 extraction — with per-provider daily cost caps, because an LLM with
no budget limit is an incident waiting for a timestamp.

### Day-to-day stack

<div align="center">

![Python](https://img.shields.io/badge/Python-1e2e42?style=flat-square&logo=python&logoColor=38bdf8&labelColor=0b1827)
![Django](https://img.shields.io/badge/Django-1e2e42?style=flat-square&logo=django&logoColor=38bdf8&labelColor=0b1827)
![Celery](https://img.shields.io/badge/Celery-1e2e42?style=flat-square&logo=celery&logoColor=38bdf8&labelColor=0b1827)
![Terraform](https://img.shields.io/badge/Terraform-1e2e42?style=flat-square&logo=terraform&logoColor=38bdf8&labelColor=0b1827)
![Docker](https://img.shields.io/badge/Docker-1e2e42?style=flat-square&logo=docker&logoColor=38bdf8&labelColor=0b1827)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1e2e42?style=flat-square&logo=githubactions&logoColor=38bdf8&labelColor=0b1827)
![AWS](https://img.shields.io/badge/AWS-1e2e42?style=flat-square&logo=amazonwebservices&logoColor=38bdf8&labelColor=0b1827)
![Redis](https://img.shields.io/badge/Redis-1e2e42?style=flat-square&logo=redis&logoColor=38bdf8&labelColor=0b1827)
![LangChain](https://img.shields.io/badge/LangChain-1e2e42?style=flat-square&logo=langchain&logoColor=38bdf8&labelColor=0b1827)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1e2e42?style=flat-square&logo=postgresql&logoColor=38bdf8&labelColor=0b1827)

</div>

### Worth a look

| Repo | What it is |
|---|---|
| [`aws-multi-region-infra`](https://github.com/amberIS01/aws-multi-region-infra) | Terraform modules for active/active VPCs across two AWS regions — per-AZ NAT, bastions, tiered security groups |
| [`voice-ai-agent`](https://github.com/amberIS01/voice-ai-agent) | Real-time voice agent chasing sub-2s end-to-end latency, with per-segment latency metrics |
| [`ocr-pii-pipeline`](https://github.com/amberIS01/ocr-pii-pipeline) | OCR + PHI detection for handwritten medical documents — deskew, extract, redact |
| [`ecommerce-ai-agent`](https://github.com/amberIS01/ecommerce-ai-agent) | LangGraph conversational shopping assistant backed by a RAG pipeline |

### Numbers

<div align="center">

<img src="https://github-readme-stats-fast.vercel.app/api?username=amberIS01&show_icons=true&count_private=true&include_all_commits=true&bg_color=0b1827&title_color=38bdf8&icon_color=38bdf8&text_color=96a0af&border_color=1e2e42" alt="GitHub stats" height="165"/>
<img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=amberIS01&layout=compact&bg_color=0b1827&title_color=38bdf8&text_color=96a0af&border_color=1e2e42" alt="Top languages" height="165"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=amberIS01&background=0b1827&ring=38bdf8&fire=38bdf8&currStreakLabel=38bdf8&sideLabels=96a0af&currStreakNum=f3f6fa&sideNums=f3f6fa&dates=606e82&border=1e2e42" alt="Streak" height="165"/>

</div>

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/singhsahil73s) · [Portfolio](https://mywebsiteme.netlify.app/) · [LeetCode](https://leetcode.com/amber_01) · sahilsingh8300@gmail.com
