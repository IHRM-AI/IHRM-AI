# Ishan Mishra  
### Machine Learning Engineer | Designing AI Systems for the Real World

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/ihrm-ishan/)
![Profile Views](https://komarev.com/ghpvc/?username=ihrm-ishan&color=blue)

---

## 🧠 How I Think About AI

Most ML engineers focus on **models**.  
I focus on **decisions, systems, and constraints**.

> A good model in a bad system fails in production.

I design AI systems where **models are one component**, not the entire solution.

---

## 🔍 What I Build

- End-to-end **ML & LLM systems**
- **RAG pipelines** with evaluation and guardrails
- Cloud-deployed AI services (GCP)
- Decision-support tools, not just predictions
- Responsible AI with governance and privacy awareness

---

## 🏗️ Architecture Sketches (System-Level View)
User
│
▼
Web / API Gateway
│
▼
Request Router
│
├──► Embedding Model
│ │
│ ▼
│ Vector Database
│ │
│ ▼
│ Context Retrieval
│
└──► Prompt Composer
│
▼
LLM (LoRA / Fine-tuned)
│
▼
Response Validator
│
▼
User


**Design priorities:**  
Low latency • Cost control • Explainability • Replaceable components

---

### 2️⃣ ML System Lifecycle I Optimize For

Problem → Data → Features → Model → API → Deployment → Monitoring → Feedback


Most failures occur **after training** — that’s where I invest most effort.

---

## 📌 Pinned Project (Primary System)

### 🔹 AI-Powered Decision Support System (LLM + RAG)

**What it is**  
A cloud-hosted AI assistant that retrieves domain-specific knowledge and generates grounded, explainable responses.

**Why it matters**  
Moves beyond chatbot demos into **usable enterprise AI systems**.

### System Highlights
- Retrieval-Augmented Generation (reduced hallucinations)
- LoRA-based fine-tuning for domain adaptation
- Modular architecture (model-agnostic design)
- GCP-based deployment with scalable inference

### Measured Impact
- ⏱️ **Latency:** ↓ ~35% (prompt optimization + caching)
- 💰 **Inference Cost:** ↓ ~30% (LoRA + batching)
- 🎯 **Response Accuracy:** ↑ ~20% (retrieval grounding)
- ❌ **Hallucinations:** Significantly reduced via context constraints

> This is the system pinned on my GitHub — it reflects how I engineer AI.

---

## ⚙️ Technical Stack (Used in Practice)

**Languages**  
Python, SQL

**Machine Learning & AI**  
Classical ML, Deep Learning, Transformers  
Large Language Models, RAG, Prompt Engineering  
Hugging Face, PEFT, LoRA

**Data & Analytics**  
EDA, feature engineering  
Tableau, Power BI

**Cloud & Tools**  
Google Cloud (Firebase, AppSheet, Flutter, Looker)  
IBM Cloud  
Git, GitHub

---

## ❌ A Failure I Learned From

### “The model worked. Production didn’t.”

I once built a high-accuracy ML model that failed in production because:
- Data distribution shifted
- Inference latency wasn’t considered
- No monitoring or feedback loop existed

**What this taught me**
- Design monitoring **before** training
- Validate latency and cost early
- Treat deployment as part of ML, not an afterthought

That failure shaped my engineering mindset more than any success.

---

## 🏆 Selected Credentials

- **Tata Insights & Quants** — GenAI Powered Data Analytics  
- **Deloitte Australia** — Data Analytics  
- **Infosys Springboard** — Generative AI Landscape  
- **IBM** — Data Science & Machine Learning Foundations  
- **Google Cloud Skills Boost** — Firebase, AppSheet, Flutter, Looker  

---

## 🧭 Engineering Principles

- Simple systems beat complex models
- Data quality > algorithm complexity
- If it can’t be deployed, it’s not done
- Ethics and governance are engineering problems

---

## 🌐 Let’s Connect

If you’re building:
- Production ML or GenAI systems
- Cloud-native AI products
- Decision-support platforms

📩 LinkedIn: https://www.linkedin.com/in/ihrm-ishan/

---

<p align="center">
<b>Engineering AI that works beyond notebooks.</b>
</p>


### 1️⃣ LLM + RAG Production Architecture

