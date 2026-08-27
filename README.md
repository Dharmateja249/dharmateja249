![Header](https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,100:22d3ee&height=260&section=header&text=Dharmateja&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Software%20Engineer%20%7C%20Fullstack%20and%20GenAI&descAlignY=58&descSize=18)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Dharmateja249&color=6366f1&style=flat" alt="Profile Views" />
</p>

Software Engineer focused on fullstack and backend development — currently deep in GenAI, learning to build products that actually use it well instead of bolting a chatbot onto everything.

I like taking a project from "idea on a whiteboard" to something with a working auth flow, a real database, and a link you can click. CS undergrad at BVRIT (CGPA 8.66), and an IEEE-published researcher on the side.

---

## 🔭 Right Now

Building **LibrisAI** and **Revora** (details below). Also applying for backend/fullstack software engineering internships, and open to **remote roles** and **freelance work** — if you need something built, my inbox is open.

---

## 🛠️ Tech Stack

**Languages**
<p>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" />
</p>

**Frontend**
<p>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</p>

**Backend**
<p>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
<img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
</p>

**Databases**
<p>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
</p>

**GenAI / ML**
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
</p>

**Tools**
<p>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</p>

---

## 🚀 Currently Building

### 📚 LibrisAI
An AI-powered intelligent reading platform that turns books into interactive, personalized learning experiences — not just a PDF viewer with a chatbot bolted on.

- 📄 **PDF Book Import** — upload PDFs, auto-extract and structure the content
- 🧠 **Structured Insights** — books broken into segments with summaries and key takeaways
- 🔐 **Secure User Libraries** — Clerk auth with user-scoped access and ownership validation
- 🗄️ **Persistent Storage** — MongoDB + Mongoose for books, segments, users, voice sessions
- 🎙️ **Voice Interviews** — interactive voice conversations around book content
- 🗑️ **Book Management** — secure create/retrieve/delete with cascading cleanup

**Stack:** `Next.js` `React` `TypeScript` `Tailwind CSS` `MongoDB` `Mongoose` `Clerk` `PDF.js` `Vercel Blob`
🔗 [View Repository](https://github.com/Dharmateja249/LibrisAI)

### 🔄 Revora — Adaptive Payment Recovery Agent
An AI-powered system that recovers failed transactions by retrieving relevant historical recovery outcomes at decision time, instead of leaning on a static ML model trained on stale data.

- 🔎 RAG-based retrieval layer to find similar customers, past failures, and what actually worked
- 🤖 Context-aware decision engine recommending `RETRY`, `PAYMENT_LINK`, `REMINDER`, or `ESCALATE`
- 🔄 Closed-loop feedback — the system checks whether a recovery actually succeeded before trusting it as a good strategy
- 📊 Full audit trail across customers, payments, recovery opportunities, and attempts
- 🗄️ Historical-data ingestion with validation, dedup, idempotency, and DB migrations
- ♻️ Built to adapt from new outcomes continuously, without full retraining

**Goal:** evolve into a production-oriented recovery platform combining retrieval, LLM reasoning, real-time payment context, and outcome-driven adaptation.

**Tech focus:** `Python` `FastAPI` `SQLAlchemy` `SQLite/PostgreSQL` `Alembic` `RAG` `LLMs` `Embeddings` `Vector Databases` `AI Agents` `Evaluation & Observability`
🔗 [View Repository](https://github.com/Dharmateja249/Revora)

---

## 🏆 Shipped Projects

### CollabX — Hackathon Team-Up Platform
A fullstack platform that helps hackathon participants find teammates by matching on skills and interests, instead of relying on random Discord pings and last-minute scrambling. Handles real-time interactions and auth end-to-end.

**Built with:** React.js · Node.js · Express.js · MongoDB · Socket.io · JWT

### Student Mental Health Prediction System
A machine learning system that predicts student mental health risk factors from survey/behavioral data, with SHAP used to explain *why* the model made a given prediction — not just spit out a number.

**Built with:** Python · Scikit-learn (Random Forest) · SHAP · Streamlit

### Retinal Abnormality Detection for Diabetic Retinopathy — *IEEE Published*
A CNN-based system for early detection of diabetic retinopathy from retinal scans, co-authored and presented at an IEEE conference in 2025.

**Built with:** CNNs · Python

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats-xi-ten-32.vercel.app/api?username=Dharmateja249&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="49%" />
  <img src="https://github-readme-stats-xi-ten-32.vercel.app/api/top-langs/?username=Dharmateja249&layout=compact&theme=tokyonight&hide_border=true" width="49%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dharmateja249&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Dharmateja249&theme=tokyonight&no-frame=true&row=1&column=6" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Dharmateja249/Dharmateja249/output/github-contribution-grid-snake.svg" />
</p>

---

## 📫 Let's Connect

<p align="center">
  <a href="https://linkedin.com/in/Golla-DharmaTeja"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:23211a0599@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

If you're hiring, freelancing out work, or want to talk about GenAI projects that aren't vaporware — reach out.
