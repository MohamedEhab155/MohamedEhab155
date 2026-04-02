<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Mohamed%20Ehab&fontSize=50&fontColor=ffffff&fontAlignY=35&desc=AI%20Engineer%20%7C%20Arabic%20NLP%20Specialist%20%7C%20MLOps&descAlignY=55&descSize=18&descColor=a0aec0" width="100%"/>

<br/>



<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-ehab-4a190022b/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamed.ehab.ai.cv@gmail.com)

</div>

---

##  About Me

```python
class MohamedEhab:
    def __init__(self):
        self.role        = "AI Engineer"
        self.location    = "Cairo, Egypt 🇪🇬"
        self.education   = "B.Sc. Computer Science — AI Dept., Zagazig University (2025)"
        self.languages   = ["Arabic (Native)", "English (Conversational)"]
        self.speciality  = "Arabic NLP · LLMs · Computer Vision · MLOps"

    def current_focus(self):
        return [
            "Fine-tuning Arabic LLMs with GPT-4o knowledge distillation",
            "Production RAG systems with sub-second bilingual retrieval",
            " Self-hosted LLM inference at zero per-request cost",
            " Real-time Computer Vision on edge devices",
        ]

    def what_drives_me(self):
        return "Bridging the gap between AI research and real-world systems"
```

---

##  Featured Projects

<table>
<tr>
<td width="50%" valign="top">

###  RAG System
**Production-grade Bilingual RAG API**

A fully async, provider-agnostic RAG system supporting Arabic & English — built for real production workloads.

**Highlights:**
-  **902ms** average end-to-end response time
-  Dual vector DB: **Qdrant** + **PgVector** (switch via env config, zero code change)
-  Parallelized OCR pipeline for scanned PDFs & mixed Arabic/English docs
-  Full observability: **Prometheus + Grafana** across 8 Docker services
-  Deployed on **Azure** with CI/CD via GitHub Actions

**Stack:**
`FastAPI` `PostgreSQL` `Qdrant` `PgVector` `Azure` `Docker` `Nginx` `Alembic` `asyncpg`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MohamedEhab155/RAG-System)

</td>
<td width="50%" valign="top">

###  ArabicLLM
**Arabic News NLP Fine-Tuning**

Fine-tuned **Qwen2.5-1.5B** on Arabic news tasks using GPT-4o as teacher model — achieving GPT-4o-quality output at zero inference cost.

**Highlights:**
-  Knowledge distillation pipeline with **Pydantic v2** validated outputs
-  **vLLM** production server with LoRA hot-loading on NVIDIA T4
-  **14s** latency at 4096-token context · validated under 20 concurrent users
-  Full experiment tracking on **Weights & Biases** across 3 epochs
-  Live **Streamlit** UI with real-time token streaming

**Stack:**
`Qwen2.5` `LLaMA-Factory` `vLLM` `LoRA` `Streamlit` `W&B` `Locust` `GPT-4o`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MohamedEhab155/ArabicLLM)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Smart Parking System
**Graduation Project — Team Lead** *(Top Project in Faculty)*

Led a team of 5 engineers building a full AI-powered smart parking system from CV model to mobile app.

**Highlights:**
-  Recognized as **one of the best graduation projects** in the college
-  **YOLOv11** license plate detection — 94.2% train / 91.8% val accuracy
-  **~50ms** inference time per image
-  Full mobile/web app with real-time parking availability & session tracking
-  Tesseract OCR pipeline integrated with YOLO detections

**Stack:**
`YOLOv11` `Tesseract` `FastAPI` `Python` `OpenCV`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)]([https://github.com/YOUR_USERNAME/smart-parking](https://github.com/youssefibrahim258/Smart-Parking))

</td>
<td width="50%" valign="top">

### 🏭 AI Engineer @ OZ_Tech & RMG
**Production CV Pipelines**

Developed and deployed real-world object detection & segmentation models for two companies simultaneously.

**Highlights:**
-  **>90% Precision · 87% Recall** with YOLOv12 across production projects
-  Managed full ML lifecycle: data collection → annotation → training → deployment
-  Integrated CV models with **Arduino** hardware for real-time edge inference
-  Cross-functional collaboration across AI, hardware, and ops teams

**Stack:**
`YOLOv12` `YOLOv11` `OpenCV` `PyTorch` `Arduino` `Python`

</td>
</tr>
</table>

---

##  Tech Stack & Skills

### Machine Learning & Deep Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

`Supervised Learning` `Unsupervised Learning` `Transfer Learning` `Fine-Tuning` `Knowledge Distillation` `Hyperparameter Tuning` `Experiment Tracking`

###  LLMs & NLP
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

`vLLM` `LLaMA-Factory` `LoRA` `RAG Pipeline` `Prompt Engineering` `Arabic NLP` `Structured Output Extraction` `Sequence Modeling`

###  Computer Vision
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

`YOLO v11/v12` `ResNet` `ViT` `Object Detection` `Segmentation` `Image Classification` `Real-Time Inference` `Edge Deployment` `Data Annotation`

### Backend & APIs
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

`SQLAlchemy` `asyncpg` `Async Processing` `REST APIs` `Provider-Agnostic Design`

###  Databases & Vector Stores
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

`Qdrant` `PgVector` `Alembic` `HNSW Indexing` `JSONB` `Async SQLAlchemy`

### MLOps, Cloud & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)

###  Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---



[![GitHub Streak](https://streak-stats.demolab.com?user=MohamedEhab155&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## Education & Certifications

| | |
|---|---|
|  | **B.Sc. Computer Science — AI Department**, Zagazig University *(2021 – 2025)* |
|  | **AWS AI Practitioner Certificate**, Manara *(2026)* |
|  | **CS224N: NLP with Deep Learning**, Stanford University *(2025 – 2026)* |
|  | **Mastering Deep Learning**, ScSkilled — Dr. Mostafa Saad *(2024 – 2026)* |
|  | **Machine Learning Diploma**, ScSkilled — Dr. Mostafa Saad *(2023 – 2024)* |

---

##  Experience

** OZ_Tech** — AI Intern *(Part-time · Feb 2025 – Jul 2025 · Cairo)*
> YOLOv12 object detection & segmentation · >90% Precision · Arduino edge integration · End-to-end ML pipelines

** RMG (Saudi Company)** — AI Intern *(Full-time · Feb 2025 – May 2025 · Cairo)*
> Production CV model deployment · Cross-functional AI team collaboration · Full project lifecycle from research to deployment

---

<div align="center">

###  Let's Connect

*Open to full-time AI Engineer roles — Remote or Cairo-based*

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-ehab-4a190022b/)
[![Email](https://img.shields.io/badge/Send_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamed.ehab.ai.cv@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=100&section=footer" width="100%"/>

</div>
