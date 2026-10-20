# Hi, I'm Anurag Singh

**Final-year B.Tech CS student at SMVDU, building NLP and applied ML systems. Seeking AI/ML or SDE internships.**

I fine-tune transformers, build retrieval pipelines, and ship full-stack products. My research is accepted at an international conference, and I've shipped AI-integrated features to real schools in production.

---

## At a glance

| | |
|---|---|
| **Research** | First-author paper accepted at **NLPIR 2026** (Nara, Japan; Springer LNNS) |
| **Industry** | Software Development Intern at **Eduspheria** (Jun to Aug 2026) |
| **Competitions** | **Smart India Hackathon 2025 Finalist**: 1,360 teams selected from 68,766 |
| **Leadership** | **AI Club Co-Lead**, SMVDU: workshops on Deep Learning and Computer Vision for 100+ students |
| **Focus** | NLP, transformer fine-tuning, RAG, explainable AI, full-stack development |

---

## Research

**RoBERTa-Driven Transformer Framework for Context-Aware Sentiment Classification of Social Media Text**
First author, accepted at NLPIR 2026 (Springer LNNS)

- Fine-tuned RoBERTa for 3-class sentiment classification on 18,170 YouTube comments
- **96% accuracy, 0.95 macro-F1** on a held-out test set
- Handled a heavy class imbalance (62.6% positive vs. 12.9% negative) with weighted cross-entropy and label smoothing
- Stack: PyTorch, Hugging Face Transformers, stratified 70/15/15 split, AdamW with LR scheduling
- Code: [Paper repository](ADD_LINK)

**RAG-RERoBERTa: Explainable Multilingual Biomedical Question Answering** *(in progress)*

- Novel recursive embedding refinement, with Graph Attention Networks for evidence aggregation over biomedical knowledge graphs
- Trained across PubMedQA, MedQA and HealthSearchQA with Optuna hyperparameter search
- SHAP and Integrated Gradients explainability, plus an English-Hindi translation and speech output pipeline
- Code: [explainable-biomedical-qa](https://github.com/anurag-env/explainable-biomedical-qa)

---

## Selected projects

| Project | What it does | Stack |
|---|---|---|
| [**Local Password Manager**](ADD_LINK) | Offline, zero-network password vault with a strict security design. Argon2id key derivation, AES-256-GCM encryption, in-memory-only keys. | Electron, Node.js, SQLite |
| [**NL2SQL**](ADD_LINK) | Natural language to SQL on WikiSQL. Fine-tuned T5 with QLoRA to fit a 4GB consumer GPU. | PyTorch, Transformers, PEFT |
| [**Pragya**](ADD_LINK) | Fully local RAG assistant that explains research papers in technical or plain language. Section-aware chunking, query latency under 400ms on CPU. | Llama3, ChromaDB, MiniLM, Streamlit |
| [**AI Research Paper Writer**](ADD_LINK) | Turns a single topic into a structured DOCX paper with abstract, references, tables and figures through a 10-module LLM pipeline. | Python, LLM APIs, python-docx |
| [**KrishiRakshak**](ADD_LINK) | Smart India Hackathon 2025 finalist: wheat disease risk maps from satellite imagery, drone footage and farmer-uploaded leaf photos. | React, Node.js, PyTorch, MongoDB |

---

## Industry experience

**Software Development Intern, Eduspheria** (Jun to Aug 2026)
*EdTech startup building school-management and tutoring software used by schools across India. Code is private.*

- **Saksham**: built and maintained a 60+ page React 18 app (~97K lines) with role-based access across 6 user roles, real-time WebSocket and push notifications, PWA support, and 30+ Django REST integrations
- Integrated AI features: DALL·E 3 poster generation, AI question-paper generation, and a conversational assistant
- **Sarthi**: designed 5+ original gamified learning exercises for Grades 5 to 12 and integrated 100+ PhET simulations through an iframe/postMessage architecture
- Worked in a 6-person team with feature branches and PR review

---

## Tech I work with

| | |
|---|---|
| **ML / NLP** | PyTorch, TensorFlow, Hugging Face Transformers, scikit-learn, Optuna, SHAP, RAG, embeddings |
| **Languages** | Python, JavaScript, SQL, Java, C/C++ |
| **Web** | React, Django, Django REST Framework, Node.js, FastAPI |
| **Tools** | Git, Linux, Docker, PostgreSQL, SQLite, AWS |

---

## Get in touch

[Portfolio](https://anurag-env.github.io/Portfolio-website/) · [LinkedIn](https://www.linkedin.com/in/anu-env/) · anuragsingh.eu@gmail.com

Open to paid AI/ML and SDE internships.
