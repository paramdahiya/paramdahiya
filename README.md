<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=6C73FF&height=120&section=header&text=&fontSize=0" width="100%"/>

# Paramveer Dahiya

**Full-Stack Engineer · AI Integration · Sydney, NSW 🇦🇺**

*CS Graduate — University of Sydney (Distinction Average, WAM 75.5)*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-param--dahiya-6C73FF?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/param-dahiya)
[![Portfolio](https://img.shields.io/badge/Live_Project-CodeMuse-2DDBA4?style=flat-square&logo=vercel&logoColor=white)](https://frontend-nine-peach-28.vercel.app)
[![Email](https://img.shields.io/badge/Email-paramdahiya06@gmail.com-FF5C6A?style=flat-square&logo=gmail&logoColor=white)](mailto:paramdahiya06@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-paramdahiya-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/paramdahiya)

</div>

---

## About

I build things that ship — from microservices backends to AI-powered web tools. Currently finishing my Bachelor of Advanced Computing at USYD and looking for a **graduate or junior SWE role** where I can contribute to product engineering from day one.

I'm most interested in the intersection of **full-stack engineering and AI** — building systems where LLMs and ML models do real work inside production applications, not just demos.

- 🔭 &nbsp;Currently building **Whisperly** — an anonymous messaging platform with an AI content moderation pipeline (Next.js, TypeScript, OpenAI)
- 🌱 &nbsp;Learning **TypeScript, Next.js, and AWS** in my current 40-day sprint
- 💬 &nbsp;Ask me about microservices architecture, AI API integration, or E2E testing with Playwright
- 📍 &nbsp;Based in Sydney — open to hybrid and remote roles across Australia

---

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**AI & ML**

![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Testing**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)

---

## Featured Projects

### 🔍 [CodeMuse — AI Code Reviewer](https://frontend-nine-peach-28.vercel.app)
> React · Node.js · TypeScript · Google Gemini API · Tailwind CSS · Vercel

A production-deployed AI code reviewer. Paste any code, get back structured feedback covering bugs, performance issues, and best-practice suggestions — powered by the Gemini API.

- Built and shipped a full-stack application — live at the link above
- Integrated **Zod schema validation** for consistent, typed API responses
- Implemented REST input guards to prevent API abuse and non-code submissions
- Migrated entirely to **TypeScript** for end-to-end type safety

```
Stack: React + TypeScript → Express API → Gemini API → Zod → Vercel
```

---

### 🛒 Online Store — Microservices Architecture
> Java · Spring Boot · React · RabbitMQ · PostgreSQL · Docker

A microservices-based e-commerce platform built to enterprise architecture standards — scored **93% for architecture design and code quality**.

- Asynchronous inter-service communication via **RabbitMQ**
- **ACID-compliant transactions** with optimistic locking for concurrent payment processing
- Normalised **PostgreSQL schema** with complex one-to-many and one-to-one relationships
- Fully **containerised with Docker Compose** — `docker compose up` runs the entire system

```
Order Service ──RabbitMQ──▶ Payment Service
     │                            │
  Postgres                    Postgres
     │                            │
Product Service ◀──REST API──▶ React Frontend
```

---

### 🧠 CNN Medical Image Classifier
> Python · Keras · TensorFlow · scikit-learn · pandas

A convolutional neural network for 9-class pathology image classification on the **PathMNIST dataset** (40,000 images).

- Achieved **70.06% test accuracy** — 4–8% improvement over Random Forest and fully connected baselines
- Systematic **hyperparameter optimisation** with Keras Tuner across 10 trials
- Confusion matrix analysis identifying high-precision classes achieving **80%+ precision**

```
Dataset: PathMNIST (40k images, 9 classes)
Model:   CNN (Keras) vs Random Forest vs FCN baseline
Result:  70.06% accuracy (+4–8% over baselines)
```

---

### 🛡 AnonMsg — Anonymous Messaging with AI Moderation *(in progress)*
> Next.js 14 · TypeScript · NextAuth · OpenAI Moderation API · Prisma · PostgreSQL · Upstash Redis

An anonymous messaging platform where every message passes through a real-time **AI content moderation pipeline** before storage.

- Three-tier severity system: `safe` → store · `warn` → flag · `block` → silent drop
- Rate limiting via **Upstash Redis** sliding window — 5 messages/IP/min
- Full **ModerationLog audit trail** with category breakdown and weekly stats
- Silent blocks — senders never learn their message was filtered

---

## Experience

**Software Developer · University of Sydney — External Benchmarks Team** *(Aug – Nov 2024)*

Worked in an Agile team building an internal benchmarking tool for comparing student performance metrics across external datasets.

- Built full-stack tool with **NiceGUI (Python)** and **scikit-learn**
- Designed and ran an E2E test suite with **Playwright** — 73% coverage across Chrome, Firefox, Safari
- Configured **Bitbucket CI/CD pipeline** with automated test execution for a 5-person team

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=paramdahiya&show_icons=true&theme=transparent&hide_border=true&title_color=6C73FF&icon_color=2DDBA4&text_color=8A94A8&bg_color=0D1117" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=paramdahiya&layout=compact&theme=transparent&hide_border=true&title_color=6C73FF&text_color=8A94A8&bg_color=0D1117&langs_count=8" />

</div>

---

## Education

🎓 **Bachelor of Advanced Computing** — University of Sydney *(Expected May 2026)*

- Major: Computer Science · Minor: Software Development
- WAM: **75.5 / 100 (Distinction Average)**
- Coursework: Cloud Computing, Enterprise Software Architecture, Web Application Development, Operating Systems, Algorithm Design, Machine Learning

---

## Certifications
- ⚛️ &nbsp;**React** — Codecademy *(Jan 2026)*
- 🤖 &nbsp;**Microsoft Promptathon** — GitHub Copilot in consulting workflows *(Microsoft & USYD, Mar 2025)*

---

## Currently

```
🔨  Building:   AnonMsg (Next.js + AI moderation)
📚  Studying:   TypeScript, Next.js
📬  Open to:    Graduate / Junior SWE roles in Sydney (hybrid or remote)
```

---

<div align="center">

*Let's build something.*

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-6C73FF?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/param-dahiya)
[![Email](https://img.shields.io/badge/Send_an_Email-FF5C6A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:paramdahiya06@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=6C73FF&height=80&section=footer" width="100%"/>

</div>
