# Beyond the Syllabus — Missing Essentials + Advanced "Pro" Track

> Companion to `learning-path.md` and `topics.md`.
> Purpose: everything the Phitron curriculum does NOT cover that you need to (a) actually get hired
> and (b) grow into a senior/competitive AI engineer. Ordered so you can **mix it into** the main
> roadmap, not learn it all at the end.
> Created: 2026-05-30.

---

## How to read this
Three layers, learned in **parallel** with `learning-path.md`, not after:

- 🟢 **LAYER 1 — Job-Ready Gaps**: the missing basics that block you from any job. Learn alongside Phase 1–2.
- 🟡 **LAYER 2 — Professional Engineering**: what separates a "bootcamp grad" from a hireable engineer. Phase 3–4.
- 🔴 **LAYER 3 — Advanced / Competitive Edge**: what puts you ahead of the crowd and into senior territory. After / during GenAI.

Rule: **start applying for jobs once Layer 1 is done — don't wait for Layer 3.**

---

## 🟢 LAYER 1 — JOB-READY GAPS (mix into Phase 1–2)

These are non-negotiable. Most rejected juniors fail here, not on ML theory.

### 1. SQL (the #1 missing skill)
- SELECT, WHERE, JOIN (inner/left/right), GROUP BY, HAVING, subqueries, window functions, CTEs.
- Practice: [SQLBolt](https://sqlbolt.com/), [DataLemur](https://datalemur.com/) (real interview SQL), LeetCode SQL.
- Video: [freeCodeCamp SQL Full Course](https://www.youtube.com/watch?v=HXV3zeQKqGY)

### 2. Git & GitHub (your portfolio lives here)
- branch, commit, push, pull, merge, pull requests, `.gitignore`, README writing.
- Video: [freeCodeCamp Git & GitHub](https://www.youtube.com/watch?v=RGOj5yH7evk)
- **Action:** every project goes public with a clean README (problem, data, approach, results, demo link).

### 3. Command line + environments
- bash/PowerShell basics, `venv` / `conda`, `pip`, `requirements.txt`, virtual environments.
- Why: nobody hires someone who can only run code in one notebook.

### 4. Jupyter → real code
- Move from notebooks to `.py` scripts, functions, modules. Notebooks for exploration, scripts for shipping.

### 5. Data Structures & Algorithms (light, Python)
- Arrays, hashmaps, two pointers, sorting, Big-O, recursion basics.
- Why: many ML/data roles still have a coding screen. ~50 easy/medium LeetCode is enough for juniors.

### 6. Statistics for interviews (deepen StatQuest)
- p-values, hypothesis testing, confidence intervals, A/B testing, Bayes' theorem, distributions.
- Data Science interviews lean heavily on this.

### 7. Excel / Google Sheets + a BI tool
- Pivot tables; one of **Power BI / Tableau / Looker Studio**. Opens Data Analyst roles fast (fastest first job).

---

## 🟡 LAYER 2 — PROFESSIONAL ENGINEERING (mix into Phase 3–4)

This is the "I can ship, not just train" layer. This is where you become *hireable*, not just *knowledgeable*.

### 1. ML model lifecycle & deployment
- **FastAPI** — wrap a model in a REST API.  [FastAPI docs](https://fastapi.tiangolo.com/)
- **Streamlit / Gradio** — quick demo UIs.
- **Docker** — containerize so it runs anywhere.  [Docker for beginners](https://www.youtube.com/watch?v=fqMOX6J1hoI)
- **Deploy targets:** HuggingFace Spaces (free), Render, Railway, then a cloud (AWS/GCP/Azure).

### 2. MLOps fundamentals (huge differentiator)
- **Experiment tracking:** MLflow or Weights & Biases (W&B).
- **Data/model versioning:** DVC.
- **Pipelines:** train → validate → register → serve.
- **CI/CD basics:** GitHub Actions running tests on push.
- **Monitoring:** data drift, model drift, why models degrade in production.

### 3. Cloud basics (pick ONE: AWS recommended)
- S3 (storage), EC2 (compute), SageMaker (ML), IAM (permissions), Lambda (serverless).
- A single cloud cert (AWS Cloud Practitioner / ML Specialty) is a strong resume signal.

### 4. Software engineering hygiene
- Clean code, type hints, logging, unit tests (`pytest`), config files, error handling.
- Project structure: `src/`, `tests/`, `data/`, `models/`, `notebooks/`, `README`, `requirements.txt`.

### 5. Data engineering touch
- ETL concepts, APIs, web scraping (BeautifulSoup/Scrapy), working with JSON/Parquet, basic Spark awareness.
- Where the real-world data actually comes from.

### 6. Advanced model topics
- **Hyperparameter tuning:** Optuna, GridSearch, cross-validation strategies.
- **Imbalanced data:** SMOTE, class weights, proper metrics (precision/recall/F1/ROC-AUC, not just accuracy).
- **Boosting:** XGBoost, LightGBM, CatBoost — these WIN most tabular Kaggle competitions and real jobs.
- **Model interpretability:** SHAP, LIME, feature importance.

---

## 🔴 LAYER 3 — ADVANCED / COMPETITIVE EDGE (during/after GenAI)

This is what puts you in the "forward phase" — ahead of the typical bootcamp graduate.

### 1. Modern LLM engineering (the hottest hireable skill right now)
- **Prompt engineering** (systematic, not guessing): few-shot, chain-of-thought, structured output.
- **RAG — advanced:** chunking strategies, hybrid search, re-ranking, evaluation (RAGAS), vector DBs (Pinecone, Weaviate, Qdrant, ChromaDB, FAISS).
- **Agents:** tool use, function calling, ReAct, multi-agent systems. LangGraph, CrewAI, AutoGen.
- **Fine-tuning:** LoRA / QLoRA, PEFT, when to fine-tune vs RAG vs prompt.
- **Local/open models:** Llama, Mistral, Qwen via Ollama / vLLM.
- **Evals & guardrails:** measuring LLM output quality, hallucination control.
- **LLMOps:** cost/latency optimization, caching, observability (LangSmithLangfuse).

### 2. Deep learning depth
- **Attention/Transformers from scratch** (re-implement — Karpathy style). Interviewers love this.
- **Computer Vision:** object detection (YOLO), segmentation, Vision Transformers (ViT).
- **Diffusion models** (Stable Diffusion) — image generation.
- **Multimodal models** (CLIP, vision-language models like LLaVA).
- **Model optimization:** quantization, pruning, distillation, ONNX, mixed precision.
- **Distributed training:** multi-GPU, gradient accumulation, DDP basics.

### 3. Research literacy (your thesis track + more)
- Read papers weekly: [arXiv](https://arxiv.org/), [Papers With Code](https://paperswithcode.com/), [Connected Papers](https://www.connectedpapers.com/).
- Reproduce a paper end-to-end — elite portfolio piece.
- Follow: Andrej Karpathy, Yannic Kilcher (YouTube), Hugging Face blog, key AI newsletters.

### 4. Specialization (pick a lane to stand out)
Generalists get filtered; specialists get hired. Choose one as your "brand":
- **GenAI/LLM Application Engineer** ← fastest-growing, most demand in 2026
- **MLOps / ML Platform Engineer** ← high pay, low supply
- **Computer Vision Engineer**
- **NLP Engineer**
- **Data Scientist (analytics + ML)**

### 5. Competition & visibility (be "in the forward phase")
- **Kaggle:** climb from Novice → Expert. Competitions, datasets, notebooks all count.
- **Open source:** contribute to a library (even docs/bug fixes) — real-world collaboration proof.
- **Build in public:** LinkedIn posts, a blog (Medium/Hashnode/dev.to), or a YouTube/X thread per project.
- **Hackathons:** AI hackathons = portfolio + network + sometimes job offers.

---

## 🧭 THE MIXED MASTER TIMELINE (everything interleaved)

| Months | Main roadmap | Add from this file | Outcome |
|---|---|---|---|
| **1–2** | Math intuition + Python | Git, command line, environments | Code on GitHub |
| **3–4** | NumPy/Pandas + Classical ML | **SQL**, stats-for-interviews, a BI tool, light DSA | **Start applying: Data Analyst** |
| **5–6** | Deep Learning (PyTorch) | FastAPI + Docker + Streamlit, XGBoost, deploy 1 app | First deployed project |
| **7–8** | CNN/RNN/Transformers + NLP | MLOps (MLflow/DVC), cloud basics, pytest | **Apply: Junior ML / GenAI dev** |
| **9–10** | LLMs + GenAI (LangChain/RAG) | Advanced RAG, agents, LoRA fine-tuning, vector DBs | GenAI app live + Kaggle rank |
| **11–12+** | Specialize + thesis/research | Pick a lane, reproduce a paper, contribute OSS, build in public | Mid-level trajectory |

**Golden rule:** projects > certificates > courses. Ship one real thing every 3–4 weeks.

---

## ✅ "AM I AHEAD OF THE COMPETITION?" CHECKLIST
You're in the forward phase when you can tick most of these:
- [ ] 5–6 real projects on GitHub, each with a README + live demo
- [ ] At least one **deployed** end-to-end app (data → model → API → UI → cloud)
- [ ] SQL fluent (can solve medium interview questions)
- [ ] Comfortable with Docker + one cloud
- [ ] One MLOps tool used in a project (MLflow/W&B/DVC)
- [ ] Built a RAG app AND fine-tuned a model at least once
- [ ] Re-implemented a transformer / paper from scratch
- [ ] Kaggle Expert OR an OSS contribution OR active build-in-public presence
- [ ] A chosen specialization you can talk about for 10 minutes
- [ ] Resume with quantified results + tailored to each role

---

## Quick links hub
- Kaggle: https://www.kaggle.com/
- Hugging Face: https://huggingface.co/
- Papers With Code: https://paperswithcode.com/
- DataLemur (SQL interviews): https://datalemur.com/
- FastAPI: https://fastapi.tiangolo.com/
- LangChain docs: https://python.langchain.com/
- Weights & Biases: https://wandb.ai/
- MLflow: https://mlflow.org/
