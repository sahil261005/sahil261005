# Hi, I'm Sahil Pawar 👋

## 🚀 About Me
Final-year B.E. Computer Science Engineering student (SPPU, Pune), building applied GenAI systems — RAG pipelines, multi-agent orchestration, and evaluation-driven AI engineering. I care as much about *proving* a system works as building it.

## 💻 Featured Projects

### 🏥 [HealthScribe](https://health-scribe-three.vercel.app)
A full-stack medical records platform extracting and verifying prescriptions via a hybrid OCR pipeline (Sarvam AI + Gemini 2.5 Flash), with a LangChain + ChromaDB RAG chatbot for querying patient history.
- Benchmarked the hybrid OCR-LLM pipeline against a Gemini-only baseline across 4 clinical entity categories — **94% exact-match accuracy** on medicine names vs. **85%** baseline, at a 1.46x latency cost.
- Replaced similarity search with MMR retrieval, cutting duplicate-record redundancy from **62% to 8%**, validated with a Gemini-as-a-Judge evaluation framework.
- Includes allergy-drug conflict alerts, LLM-based drug interaction checks, multi-doctor comparison, and QR-based health profile sharing.

**Stack:** Django, FastAPI, React, LangChain, ChromaDB, Gemini 2.5 Flash, Sarvam AI, Supabase

---

### 🎥 [VeriFrame](https://veri-frame.vercel.app)
A multi-agent video forensics platform detecting AI-generated video and deepfakes — combining a Vision Transformer, OpenCV/MediaPipe temporal analysis, and Groq Llama 4 Scout reasoning, orchestrated with LangGraph. Produces explainable, per-frame verdicts instead of a single opaque score.
- Evaluated on 40 real and face-swapped videos — **87.5% accuracy**, **90.0% deepfake detection rate**, **15.0% false positive rate**.
- Two-stage frame sampling cuts CV workload by 93.3% and LLM API payload by 99.1%, for 3.63s average end-to-end latency.
- Fault-tolerant design: dynamically shifts decision weight to the LLM reasoning agent if the local vision model fails to load.

**Stack:** FastAPI, LangGraph, HuggingFace Transformers, OpenCV, MediaPipe, Groq API, React, Supabase

## 🛠️ Skills

**Languages:** Python, C++, JavaScript, SQL

**Frameworks & Libraries:** Django, DRF, FastAPI, React, LangChain, LangGraph, SQLAlchemy, OpenCV, MediaPipe, Pydantic

**AI/GenAI:** Multi-Agent Orchestration, RAG, Cross-Encoder Reranking, LLM-as-a-Judge Evaluation, HuggingFace Transformers, Structured JSON Outputs, Groq API, Gemini API

**Databases:** PostgreSQL, Supabase, ChromaDB

**Tools:** Git, GitHub, LangSmith, Postman, JWT, REST APIs, pytest

## 📈 LeetCode
Knight status • 500+ Data Structures & Algorithms problems solved
[View Profile →](https://leetcode.com/u/sahil_2610)

## 📫 Connect with Me
- **LinkedIn:** [linkedin.com/in/sahil-pawar](https://www.linkedin.com/in/sahil-pawar-251187357/)
- **Email:** [sahilrpawar3@gmail.com](mailto:sahilrpawar3@gmail.com)

## 📊 GitHub Stats
![](https://github-readme-stats.vercel.app/api?username=sahil261005&theme=merko&hide_border=false&include_all_commits=false&count_private=false)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=sahil261005&theme=merko&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=sahil261005&theme=radical&no-frame=false&no-bg=false&margin-w=4)
