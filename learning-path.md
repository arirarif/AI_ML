# AI/ML Learning Path — YouTube Roadmap (mapped to topics.md)

> Goal: Learn everything in `topics.md` (the Phitron AI/ML batch curriculum) in the right
> order, with the best free YouTube resources, and get job-ready as fast as realistically possible.
> Created: 2026-05-30.

---

## TL;DR — Is `topics.md` enough to learn AI/ML?

**Yes — the *syllabus* is excellent and genuinely job-oriented.** It covers the full modern
stack: math → Python → data tools → classical ML → deep learning → CNN/RNN → Transformers →
NLP → LLMs → Generative AI (LangChain/RAG/agents), plus a research/thesis track. That is more
complete than most paid bootcamps.

**But a topic list is not a course.** A list of topics ≠ knowing them. What turns this list into
a job is:
1. **Following it in order** (math + Python first, don't skip).
2. **Building the projects** (every project listed — do them, push to GitHub).
3. **Spaced practice** (Kaggle, LeetCode-style Python, re-implementing from scratch).

What `topics.md` is **missing** for employability (add these yourself):
- **SQL** (almost every data/ML job asks for it).
- **Git/GitHub** workflow (you need a public portfolio).
- **ML system design & deployment** (Docker, FastAPI, cloud basics) — partly covered in GenAI section.
- **Communication / portfolio / resume** — a GitHub with 4–6 real projects + a couple of blog posts.

So: curriculum = A. Add SQL + Git + a public portfolio and you are job-ready.

---

## How to use this roadmap

- **One section at a time, in order.** Don't jump to deep learning before Python + math basics.
- **Code along.** Pause the video, type it yourself, break it, fix it.
- **Pick ONE main resource per topic** (don't watch 5 versions of the same thing — that's procrastination).
- **English resources are primary** (best quality + matches global job market). **Bangla links are
  included as backup** if a concept doesn't click in English.
- **Rough pace to job-ready: 6–10 months** at ~2–3 focused hours/day. Faster only if you already code.
- **About the durations below:** single-video courses show their exact runtime. Playlist totals are
  **approximate** (sum of all videos) and marked `~` — your real time is 2–4× the runtime once you
  pause, code along, and redo things. Treat durations as "watch time," not "learn time."

---

## PHASE 0 — Foundations: Math + Python (topics.md lines 1–38)

### 0a. Math for ML (lines 1–11)
You do NOT need a math degree. You need *intuition* + enough to read formulas.

| Resource | Why | Duration | Link |
|---|---|---|---|
| **3Blue1Brown — Essence of Linear Algebra** | Best visual intro to vectors, matrices, matrix mult | ~3 hr (16 videos) | https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab |
| **3Blue1Brown — Essence of Calculus** | Derivatives, gradients — intuition first | ~3 hr (12 videos) | https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr |
| **StatQuest — Statistics Fundamentals** | Probability, distributions, normal dist — the clearest on YouTube | ~6 hr (playlist) | https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9 |
| **3Blue1Brown — Gradient descent / Neural nets ch.2** | Gradient descent intuition | ~2 hr (playlist) | https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi |

> Don't spend more than ~3–4 weeks here. Get intuition, then move on — you'll revisit math in context.

### 0b. Python (lines 12–38, both Python sections)

| Resource | Why | Duration | Link |
|---|---|---|---|
| **Harvard CS50P — Intro to Programming with Python** | Best free structured Python course, rigorous | ~16 hr (full course) | https://www.youtube.com/watch?v=nLRL_NcnK-4 |
| **Corey Schafer — Python OOP series** | Classes, inheritance, OOP done right (lines 29–37) | ~1.5 hr (6 videos) | https://www.youtube.com/playlist?list=PL-osiE80TeTsqhIuOqKhwlXsIBIdSeYtc |
| **freeCodeCamp — Python Full Course for Beginners** | Alternative single long video | 4h 26m | https://www.youtube.com/watch?v=rfscVS0vtbw |

Covers: variables, loops, lists/dicts/sets/tuples, comprehensions, strings, OOP, functions,
iterators/generators, lambda/map/filter/reduce, file handling, exceptions.
**Do the "Movie Script Generator" project (line 39) here.**

---

## PHASE 1 — Data Tools: NumPy, Pandas, Matplotlib (lines 40–54)

| Resource | Why | Duration | Link |
|---|---|---|---|
| **Keith Galli — Complete NumPy Tutorial** | Clear ndarray, reshaping, broadcasting | ~1 hr | https://www.youtube.com/watch?v=GB9ByFAIAH4 |
| **Keith Galli — Complete Pandas Tutorial** | Real dataset, loc/iloc, groupby, cleaning | 1h 34m | https://www.youtube.com/watch?v=2uvysYbKdjM |
| **Corey Schafer — Matplotlib series** | Plots: line, scatter, hist, bar, pie | ~2.5 hr (playlist) | https://www.youtube.com/playlist?list=PL-osiE80TeTvipOqomVEeZ1HRrcEvtZB_ |
| **freeCodeCamp — Data Analysis with Python** | Ties NumPy+Pandas+stats together | 4 hr | https://www.youtube.com/watch?v=r-uOLxNrNk8 |

**Project (line 54): Build a simple ML model from scratch** (e.g., linear regression with only NumPy).

---

## PHASE 2 — Classical Machine Learning (lines 59–91)

This is the core. Two complementary tracks — do **StatQuest for the "why"** + **CampusX or Andrew Ng for the "how"**.

| Resource | Why | Duration | Link |
|---|---|---|---|
| **StatQuest — Machine Learning playlist** ⭐ | THE best intuition for every algorithm (regression, logistic, KNN, Naive Bayes, trees, SVM, random forest, k-means) | ~10 hr (playlist) | https://www.youtube.com/playlist?list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1 |
| **Andrew Ng — Machine Learning Specialization (DeepLearning.AI)** ⭐ | Gold-standard structured course; audit free | ~30–60 hr (3-course spec) | https://www.youtube.com/playlist?list=PLkDaE6sCZn6FNC6YRfRQc_FbeQrF8BwGI |
| **CampusX — 100 Days of Machine Learning** ⭐ | Hands-on, sklearn, EDA, feature engineering, deployment — extremely practical | ~80–100 hr (100+ videos) | https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH |

Covers lines 60–90: descriptive stats, linear/multiple/polynomial regression, logistic regression,
KNN, Naive Bayes, decision trees, SVM, random forest, k-means, hierarchical, DBSCAN, EDA,
feature engineering, overfitting, evaluation metrics.

**Projects (line 91): Student Performance Indicator, Credit Card Fraud Detection, Phishing Classifier.**
Krish Naik has end-to-end versions of these on his channel — search his channel for each.

➕ **Add now: SQL + Git** (not in topics.md but needed for jobs)
- SQL: https://www.youtube.com/watch?v=HXV3zeQKqGY (freeCodeCamp full course) — **4 hr**
- Git/GitHub: https://www.youtube.com/watch?v=RGOj5yH7evk (freeCodeCamp) — **~1h 10m**

---

## PHASE 3 — Deep Learning (lines 96–116)

| Resource | Why | Duration | Link |
|---|---|---|---|
| **3Blue1Brown — Neural Networks** ⭐ | Visual intuition for NN + backprop (line 111) | ~2 hr (playlist) | https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi |
| **Daniel Bourke — PyTorch for Deep Learning** ⭐ | The PyTorch course; tensors, autograd, training loops, ANN | ~25 hr (single video) | https://www.youtube.com/watch?v=Z_ikDlimN6A |
| **Andrej Karpathy — Neural Networks: Zero to Hero** ⭐⭐ | Build everything from scratch incl. backprop (micrograd) — the single best DL series | ~15 hr (8 videos) | https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ |
| **Andrew Ng — Deep Learning Specialization** | Structured theory: optimization, regularization, init, batch norm | ~30–40 hr (5-course spec) | https://www.youtube.com/playlist?list=PLkDaE6sCZn6Ec-XTbcX1uRg2_u4xOEky0 |

Covers lines 97–111: DL fundamentals, PyTorch tensors/autograd, perceptron/MLP, forward prop,
backprop, optimizers (Momentum/AdaGrad/RMSProp/Adam), vanishing/exploding gradients,
regularization (L1/L2/dropout), weight init, batch norm.

**Projects (line 110): MNIST digit recognition, Customer Churn, House Price Prediction.**

---

## PHASE 4 — CNN, RNN & Transformers (lines 117–132)

| Resource | Why | Duration | Link |
|---|---|---|---|
| **Daniel Bourke — PyTorch course (CNN + transfer learning sections)** | Practical CNN, data augmentation, pretrained models | (part of the ~25 hr above) | https://www.youtube.com/watch?v=Z_ikDlimN6A |
| **CampusX — 100 Days of Deep Learning (RNN/LSTM/GRU)** | Activation functions, RNN, LSTM, GRU, bidirectional (RNN starts ~Day 55) | ~40 hr (playlist) | https://www.youtube.com/playlist?list=PLKnIA16_RmvYuZauWaPlRTC54KxSNLtNn |
| **ALT: Andrew Ng — Sequence Models (DL Spec, Course 5)** | If CampusX doesn't click: structured RNN/LSTM/GRU/attention | ~15 hr | https://www.youtube.com/playlist?list=PLkDaE6sCZn6F6wUI9tvS_Gw1vaFAx6rd6 |
| **StatQuest — Neural Networks / Transformers / Attention** | Clearest transformer + self-attention explanation | ~3 hr (relevant videos) | https://www.youtube.com/playlist?list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1 |
| **Andrej Karpathy — "Let's build GPT from scratch"** ⭐ | Self-attention, scaled dot-product, encoder/decoder built live | 1h 56m | https://www.youtube.com/watch?v=kCc8FmEb1nY |

Covers lines 118–131: activation functions, CNN foundation/architectures/math, CNN in PyTorch,
data augmentation, pretrained models; RNN types, LSTM, GRU, bidirectional RNN; transformers,
self-attention, scaled dot-product, encoder/decoder, inference.

**Projects (line 132): Hate Speech Detection (BERT/Bangla-BERT), Skin Lesion Classification,
Tweet Sentiment, Text Generation.**

---

## TRACK 01 — Project Track

### 5a. NLP (lines 141–153)
| Resource | Duration | Link |
|---|---|---|
| **CampusX — NLP playlist** ⭐ (one-hot, BoW, n-grams, TF-IDF, Word2Vec CBOW/Skip-gram, tokenization, stemming/lemmatization, POS, NER) | ~20 hr (playlist) | https://www.youtube.com/playlist?list=PLKnIA16_RmvZo7fp5kkIth6nRTeQQsjfX |
| **freeCodeCamp — NLP with Python** | ~5 hr | https://www.youtube.com/watch?v=dIUTsFT2MeQ |

**Projects: spam detection, sentiment analysis, text generation.**

### 5b. Large Language Models (lines 154–167)
| Resource | Duration | Link |
|---|---|---|
| **Andrej Karpathy — "Intro to Large Language Models"** ⭐ | ~1 hr | https://www.youtube.com/watch?v=zjkBMFhNj_g |
| **3Blue1Brown — Transformers / Attention (LLM chapters)** | ~1 hr (relevant chapters) | https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi |
| Re-watch Karpathy "Let's build GPT" + Zero to Hero (covers seq2seq → transformer LM) | (see Phase 4) | (see Phase 4) |

### 5c. Generative AI — LangChain / RAG / Agents (lines 168–184)
| Resource | Why | Duration | Link |
|---|---|---|---|
| **freeCodeCamp — Generative AI Full Course** | Broad GenAI ecosystem | ~25 hr (playlist) | https://www.youtube.com/playlist?list=PLkz_y24mlSJY7hlQ-GyDgUCWz8TyIX_S3 |
| **freeCodeCamp — RAG from Scratch (by LangChain engineer Lance Martin)** ⭐ | The definitive RAG tutorial | ~2h 45m | https://www.youtube.com/watch?v=sVcwVQRHIc8 |
| **Krish Naik — Generative AI / LangChain playlist** ⭐ | End-to-end apps: PDF chat, doc QA, chatbots, Streamlit/Gradio deploy, Ollama | ~30+ hr (playlist) | https://www.youtube.com/@krishnaik06/playlists |

Covers lines 169–184: GenAI ecosystem, LangChain (prompts/chains/runnables/parsers),
embeddings + vector stores + retrievers, RAG pipelines, Gemini API, agents/tools,
local LLMs (Ollama), deployment (Streamlit/Gradio), fine-tuning, LLMOps.

**Do at least 1–2 full end-to-end GenAI projects and deploy them publicly.**

---

## TRACK 02 — Thesis / Research Track (lines 185–225)
Only if you want research/academic path. YouTube is weaker here; better resources:
- **research methodology & paper reading**: "How to Read a Paper" by Andrew Ng / Stanford CS230 lectures
- Use the curriculum's structure (topic formulation → data strategy → experiments → writing) as a checklist.
- Tools: Papers With Code, arXiv, Connected Papers, Zotero.

---

## BANGLA (বাংলা) BACKUP RESOURCES
If English explanation doesn't click, use these in your native language:
- **Complete Machine Learning Bangla Course** (~30 hr playlist) — https://www.youtube.com/playlist?list=PLKdU0fuY4OFfWY36nDJDlI26jXwInSm8f
- **Complete Data Science & AI Bangla Tutorial** (~40 hr playlist) — https://www.youtube.com/playlist?list=PLKdU0fuY4OFcot0zyVbM1-zKf_eCUK4zQ
- **aiQuest Intelligence** (Bangla data science/AI platform, free YouTube + paid live) — https://aiquest.org/
- **Stack Learner** (Bangla programming/Python) — search "Stack Learner" on YouTube

---

## THE FAST-TRACK TO A JOB (do these in parallel from Phase 2 onward)

1. **GitHub portfolio** — every project from topics.md, clean READMEs. 5–6 solid projects > 20 toy ones.
2. **Kaggle** — do competitions/notebooks; it's a public proof of skill.
3. **SQL + Git** — non-negotiable for jobs (links in Phase 2).
4. **One deployed app** — a GenAI/RAG app live on Streamlit Cloud or HuggingFace Spaces.
5. **Resume + LinkedIn** — list projects with metrics ("improved accuracy from X to Y").
6. **Re-implement from scratch** at least once (Karpathy-style) — interviewers love this.
7. **Mock interviews + DSA basics in Python** — for ML/data roles, some coding rounds still appear.

**Realistic timeline:** 6–10 months of consistent daily effort from zero → junior ML/data role.
Already a programmer? 3–5 months.

---

## TOTAL WATCH TIME PER PHASE (pick ONE main resource per topic — don't add these all up)

These are *core-path* estimates assuming you follow the recommended primary resource(s), not every
link. Real calendar time = roughly **2–4× the watch time** (pausing, coding, redoing).

| Phase | Core watch time (approx) |
|---|---|
| Phase 0 — Math + Python | ~25–30 hr (CS50P dominates; math ~8 hr) |
| Phase 1 — Data tools | ~6–8 hr |
| Phase 2 — Classical ML | ~15–20 hr (StatQuest ML + Ng; CampusX as deep-dive reference) |
| + SQL + Git | ~5 hr |
| Phase 3 — Deep Learning | ~25–40 hr (Bourke OR Karpathy as primary) |
| Phase 4 — CNN/RNN/Transformers | ~8–12 hr (+ Karpathy GPT 2 hr) |
| NLP | ~5–8 hr |
| LLMs | ~2–3 hr |
| GenAI (LangChain/RAG/Agents) | ~10–15 hr + project build time |
| **Core total** | **~100–140 hr of video** (≈ 250–450 hr real effort with practice) |

> The big playlists (CampusX 100-Days ML ~80–100 hr, CampusX DL ~40 hr, Krish Naik GenAI ~30+ hr) are
> **reference libraries, not watch-end-to-end**. Dip into the topic you need. Watching them fully is
> NOT required to be job-ready.

---

## SUGGESTED ORDER (one line)
Math intuition → Python (CS50P+OOP) → NumPy/Pandas/Matplotlib → SQL+Git → StatQuest+CampusX ML
→ classical-ML projects → 3B1B+Karpathy+Bourke deep learning → DL projects → CNN/RNN/Transformers
→ NLP → LLMs → LangChain/RAG/Agents GenAI projects (deploy) → polish portfolio → apply.

---

### Sources
- [MachineLearningMastery — 5 Free ML YouTube Channels](https://machinelearningmastery.com/5-free-youtube-channels-dedicated-to-machine-learning-education/)
- [LearnWithPath — 8 Best YouTube Channels for ML 2026](https://learnwithpath.com/blog/best-youtube-channels-for-machine-learning-2026)
- [Analytics Vidhya — Top YouTube Channels to Learn ML](https://www.analyticsvidhya.com/blog/2026/03/youtube-channels-to-learn-machine-learning/)
- [freeCodeCamp — Mastering RAG from Scratch](https://www.freecodecamp.org/news/mastering-rag-from-scratch/)
- [freeCodeCamp — Generative AI Full Course playlist](https://www.youtube.com/playlist?list=PLkz_y24mlSJY7hlQ-GyDgUCWz8TyIX_S3)
- [Complete Machine Learning Bangla Course](https://www.youtube.com/playlist?list=PLKdU0fuY4OFfWY36nDJDlI26jXwInSm8f)
- [aiQuest — Data Science & AI learning platform (Bangla)](https://aiquest.org/best-data-science-and-ai-learning-platform-in-bangladesh/)
- Phitron AI/ML Batch curriculum (topics.md, user-provided): https://phitron.io/course-details/ai-ml-batch2
