# Hi, I'm Mohamed Ehab 👋

AI Engineer based in Cairo, Egypt. I build things that actually run in production — not just notebooks.

My work sits at the intersection of model training, backend engineering, and deployment infrastructure. I care about the full picture: how data gets collected, how models get trained, how they get served, and whether the system holds up under real load.

Native Arabic speaker — which shapes a lot of what I build. Bilingual NLP, Arabic OCR pipelines, Arabic-specific fine-tuning.

<br>

📧 [mohamed.ehab.ai.cv@gmail.com](mailto:mohamed.ehab.ai.cv@gmail.com) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/mohamed-ehab-4a190022b/) &nbsp;·&nbsp; Cairo, Egypt 🇪🇬

---

## 🚀 Projects

### RAG System — Bilingual Production API
*FastAPI · PostgreSQL · Qdrant · PgVector · Docker · Azure · GitHub Actions · Prometheus · Grafana · Nginx · Alembic*

A bilingual Arabic/English RAG API I built from scratch — the kind that handles real traffic, not just curl requests in a demo.

- LLM backend (OpenAI GPT / Cohere Command-R+) is swappable via environment config, no code changes needed. Same idea for the vector store — Qdrant or PgVector (HNSW), switched at runtime through a factory
- OCR runs in parallel across pages using `ThreadPoolExecutor`, with Mistral OCR and Gemini Vision covering scanned PDFs, embedded images, and mixed Arabic/English content
- Deployed on Azure with separate CI/CD pipelines for `develop` and `main`, 8 Docker Compose services behind Nginx, full Prometheus + Grafana observability

Average end-to-end response time: **~902ms**. Still optimizing.

[View on GitHub →](https://github.com/MohamedEhab155/RAG-System)

---

### ArabicLLM — Fine-tuning Qwen2.5 on Arabic News
*PyTorch · Hugging Face · LLaMA-Factory · vLLM · Streamlit · W&B · Pydantic · Locust*

I wanted to see how far a small model could go on Arabic NLP tasks if you train it right — NER, summarization, keyword extraction, categorization. The short answer: pretty far.

- Used GPT-4o as a teacher model to generate labeled training data from raw Arabic news, with outputs validated against Pydantic v2 schemas
- Fine-tuned Qwen2.5-1.5B with LoRA (rank 64) via LLaMA-Factory — 3 epochs, lr 2e-4, tracked on W&B
- Deployed with vLLM on an NVIDIA T4 — LoRA adapters hot-load without restart
- Live Streamlit UI with SSE token streaming over an OpenAI-compatible endpoint
- Load-tested with Locust at 20 concurrent users — ~14s latency at 4096-token context, acceptable for the hardware

The point was **zero per-request cost at inference**. No GPT-4o calls in production.

*Repo coming soon*

---

### Smart Parking System — Graduation Project *(🏅 Best Project Award)*
*YOLOv11 · PyTorch · OpenCV · Tesseract OCR · FastAPI · MySQL*

Led a team of 4–5 engineers on my graduation project — task splitting, faculty coordination, and making sure we actually shipped. Ended up winning best project in the college.

- Trained YOLOv11 on a custom 2,640-image annotated dataset — **94.2% training accuracy**, 91.8% validation, ~50ms inference per image
- Full pipeline: YOLO detection → Tesseract OCR → structured vehicle lookup
- FastAPI backend with real-time parking availability, vehicle sessions, and lookup

[View on GitHub →](https://github.com/youssefibrahim258/Smart-Parking)

---

## 🛠️ Skills

**Languages** — Python, SQL

**ML / DL** — PyTorch · TensorFlow · Hugging Face Transformers · scikit-learn · LLaMA-Factory · vLLM · LangChain

**Computer Vision** — YOLO (v11, v12) · OpenCV · ResNet · ViT · detection, segmentation, classification, real-time inference, embedded hardware integration

**NLP / LLMs** — Fine-tuning · RAG · Knowledge distillation · Prompt engineering · Structured output extraction · Bilingual Arabic/English pipelines

**Backend** — FastAPI · SQLAlchemy (async) · Pydantic · Streamlit

**MLOps** — Docker · GitHub Actions · Prometheus · Grafana · Weights & Biases · Alembic · Nginx

**Cloud / Databases** — Microsoft Azure · AWS · PostgreSQL · Qdrant · PgVector · asyncpg

**Tools** — Git · Kaggle · Colab · Jupyter · VS Code · Locust

---

## 💼 Experience

**AI Engineer Intern — OZ_Tech** · Cairo *(Feb – Jul 2025)*
Real Computer Vision work using YOLOv12 — detection and segmentation across multiple projects, full pipeline from annotation through deployment. Also integrated models with Arduino-based embedded hardware, which pushed me into territory beyond pure ML.

**AI Engineer Intern — RMG** · Remote, Saudi Arabia *(Feb – May 2025)*
Worked remotely with a cross-functional AI team. Trained and deployed CV models from early research through production handoff across multiple concurrent projects.

---

## 🎓 Education & Certifications

**B.Sc. Computer Science — AI Department** &nbsp;·&nbsp; Zagazig University &nbsp;·&nbsp; *July 2025*

| Course | Provider | Note |
|---|---|---|
| Mastering DSA | ScSkilled — Dr. Mostafa Saad | Advanced problem-solving & data structures |
| Mastering ML & Deep Learning | ScSkilled — Dr. Mostafa Saad | End-to-end ML/DL workflows |
| NLP and LLMs | Stanford Online | Transformers, fine-tuning, RAG |
| ML Professional Training | Creativa Ismailiya | Industry workflows · **Grade: 98%** |

---

## 📊 GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=MohamedEhab155&show_icons=true&theme=default&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MohamedEhab155&layout=compact&theme=default&hide_border=true" height="150"/>
</p>

![](https://komarev.com/ghpvc/?username=MohamedEhab155&style=flat-square&color=grey)

---

**Arabic** — native &nbsp;·&nbsp; **English** — professional
