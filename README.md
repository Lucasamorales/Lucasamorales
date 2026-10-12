# Lucas Morales

**Lead Full Stack AI Engineer · Córdoba, Argentina**

I build AI systems end to end: agents, RAG assistants, and the full-stack applications and infrastructure around them. At Studio 34 I started the Development Area from scratch and lead it as its sole developer.

I also enjoy teaching. I taught algebra classes at university, and I run technical talks on AI implementation, security, and prompting techniques.

---

## Current Work at Studio 34

**Lead Full Stack AI Engineer (Apr 2025 – Present)**

Leading the Development Area for a marketing agency: application architecture, project roadmaps, and technical strategy. Most of this work lives in private repositories.

- **Internal AI Assistant (Matty):** A modular assistant for Google Chat built on Anthropic's Claude. It works in Asana through the Model Context Protocol (MCP) and requires human approval before any change. Deployed on Cloud Run with Firestore.
- **Invoice Portal:** An internal web application, in production, where contractors generate and submit their monthly invoices. Built with FastAPI and PostgreSQL on Cloud Run behind Identity-Aware Proxy, with encrypted bank details and Terraform-managed infrastructure.
- **RAG Scoping Assistant:** A client-facing assistant built with FastAPI and Gemini that determines whether a request is within scope. Verdicts are resolved by deterministic code rather than the LLM, and retrieval quality is measured with evaluation harnesses.
- **Operations Dashboard:** A Next.js and TypeScript dashboard, fed by a scheduled collector on Cloud Run, that monitors the status, errors, and costs of the agency's Google Cloud projects and repositories.
- **Automations:** Review replies with human approval, lead triage, email-marketing reporting, and Google Workspace bots for kudos, out-of-office queries, and leave booking.
- **Search Intelligence:** Geo-audits and generative search evaluations that show clients how they are found and ranked across AI search.

---

## Open Projects

- **[TEMI](https://github.com/Lucasamorales/TEMI):** A real-time voice translation app, built as an MVP. Two people speak their own languages and hear each other translated. Go backend streaming speech-to-text, LLM translation, and text-to-speech over WebSockets, with a Flutter mobile app and Terraform-managed infrastructure on GCP.
- **[volley-stats](https://github.com/Lucasamorales/volley-stats):** Per-player volleyball statistics from amateur tripod video. Models track the ball, players, and poses and propose every touch, and a person confirms the uncertain ones. An early prototype.

---

## Tech Stack

| Area | Tools |
|---|---|
| Languages | Python, TypeScript, JavaScript, Go, Dart |
| AI | Claude, Gemini, OpenAI, RAG, agents, MCP, evaluation harnesses, transformer fine-tuning, computer vision |
| Backend and frontend | FastAPI, Node.js, Next.js, React, Vue, HTMX, Flutter |
| Cloud and infrastructure | Google Cloud (Cloud Run, Firestore, IAP, KMS), Azure, Terraform, Docker, GitHub Actions |

---

## Previous Experience

- **AI Engineer @ Pi Data Strategy & Consulting (Jun 2024 – Apr 2025)**
  - Built enterprise proof-of-concept (POC) solutions using LLMs and Retrieval-Augmented Generation (RAG) on Microsoft Azure.
  - Integrated Azure RAG with Azure Purview to deploy document-governed, contextual virtual assistants.
  - Designed a secondary LLM filtering framework achieving 85% response correctness in recommendations.
  - Developed database normalization pipelines combining OpenAI Search and Perplexity AI for location verification.

- **Data Science Consultant @ Virtual Dev (Dec 2023 – Jun 2024)**
  - Fine-tuned transformer models for Intent Classification and Named Entity Recognition (NER).
  - Orchestrated a production pipeline to integrate the models into automated systems.

- **Full Stack Developer @ AdminSeg (Sep 2023 – Dec 2023)**
  - Developed full-stack software for insurance companies.

- **AI & Data Science Consultant @ Freelance (2021 – 2023)**
  - Built a two-factor authentication system using keystroke dynamics, a loan default prediction model, inventory automations, and WhatsApp customer service bots.

- **Full Stack Developer @ Quote (2020 – 2021)**
  - Maintained an e-commerce platform, including inventory control and database migrations.

---

## GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Lucasamorales&theme=dark" alt="GitHub Streak" width="48%" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Lucasamorales&theme=github-dark" alt="Activity Graph" width="48%" />
</p>

---

## Reach Me

<p align="left">
  <a href="mailto:lucasamorales00@gmail.com"><img src="https://img.shields.io/badge/Email-lucasamorales00%40gmail.com-c14438?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/lucas-morales-37b1b9221/"><img src="https://img.shields.io/badge/LinkedIn-Lucas%20Morales-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>
