<h1 align="center">Jiya Jain</h1>

<p align="center">
  <b>CSE undergrad @ MSIT</b> · Machine Learning Engineer · RAG, Agentic AI &amp; Deep Learning
</p>

<p align="center">
  <a href="https://jiya-portfolio-gilt.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:jainjiya2312@gmail.com"><img src="https://img.shields.io/badge/Mail-4F46E5?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/jiyajain23/"><img src="https://img.shields.io/badge/LinkedIn-1E293B?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

### About

```python
from dataclasses import dataclass, field

@dataclass
class Jiya:
    role: str = "ML Engineer in the making"
    focus: list = field(default_factory=lambda: [
        "natural language processing","retrieval-augmented generation",
        "AI safety & red teaming", "applied deep learning", "DSA"
    ])
    building: str = "hybrid-retrieval RAG systems that actually cite the right page"
    learning: str = "agentic workflows, eval harnesses, inference optimization"
    motto: str = "turn the theory into something that ships"
```

- ML Summer Intern at the **Airports Authority of India** — neural nets from scratch, plus retrieval and latency work on an enterprise RAG system.
- AI/ML Intern at **DomaiynLabs** — adversarial red teaming research and a prompt-injection firewall served over FastAPI.
- **LinkedIn CoachIn** mentee — selected among the top 100 from 21,000+ applicants, and won the internal hackathon.
- **9.19 / 10** CGPA, B.Tech CSE @ Maharaja Surajmal Institute of Technology, graduating 2028.

---

### Toolbox

**Languages**

![Python](https://img.shields.io/badge/Python-0F172A?style=for-the-badge&logo=python&logoColor=4F46E5)
![C++](https://img.shields.io/badge/C++-0F172A?style=for-the-badge&logo=cplusplus&logoColor=4F46E5)
![JavaScript](https://img.shields.io/badge/JavaScript-0F172A?style=for-the-badge&logo=javascript&logoColor=4F46E5)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-1E293B?style=for-the-badge&logo=pytorch&logoColor=E2E8F0)
![TensorFlow](https://img.shields.io/badge/TensorFlow-1E293B?style=for-the-badge&logo=tensorflow&logoColor=E2E8F0)
![Keras](https://img.shields.io/badge/Keras-1E293B?style=for-the-badge&logo=keras&logoColor=E2E8F0)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1E293B?style=for-the-badge&logo=scikitlearn&logoColor=E2E8F0)
![LangChain](https://img.shields.io/badge/LangChain-1E293B?style=for-the-badge&logo=langchain&logoColor=E2E8F0)
![Sentence--Transformers](https://img.shields.io/badge/Sentence--Transformers-1E293B?style=for-the-badge&logo=huggingface&logoColor=E2E8F0)
![NLTK](https://img.shields.io/badge/NLTK-1E293B?style=for-the-badge&logoColor=E2E8F0)
![NumPy](https://img.shields.io/badge/NumPy-1E293B?style=for-the-badge&logo=numpy&logoColor=E2E8F0)
![Pandas](https://img.shields.io/badge/Pandas-1E293B?style=for-the-badge&logo=pandas&logoColor=E2E8F0)

**Data &amp; Vector Stores**

![ChromaDB](https://img.shields.io/badge/ChromaDB-334155?style=for-the-badge&logoColor=E2E8F0)
![FAISS](https://img.shields.io/badge/FAISS-334155?style=for-the-badge&logo=meta&logoColor=E2E8F0)
![MongoDB](https://img.shields.io/badge/MongoDB-334155?style=for-the-badge&logo=mongodb&logoColor=E2E8F0)
![SQLite](https://img.shields.io/badge/SQLite-334155?style=for-the-badge&logo=sqlite&logoColor=E2E8F0)
![Prisma](https://img.shields.io/badge/Prisma-334155?style=for-the-badge&logo=prisma&logoColor=E2E8F0)

**Backend &amp; Tools**

![FastAPI](https://img.shields.io/badge/FastAPI-475569?style=for-the-badge&logo=fastapi&logoColor=E2E8F0)
![Node.js](https://img.shields.io/badge/Node.js-475569?style=for-the-badge&logo=nodedotjs&logoColor=E2E8F0)
![Streamlit](https://img.shields.io/badge/Streamlit-475569?style=for-the-badge&logo=streamlit&logoColor=E2E8F0)
![Git](https://img.shields.io/badge/Git-475569?style=for-the-badge&logo=git&logoColor=E2E8F0)
![Jupyter](https://img.shields.io/badge/Jupyter-475569?style=for-the-badge&logo=jupyter&logoColor=E2E8F0)

---

### Selected work

| Project                                                   | What it is                                                          | Stack                                                                                      | Highlight                                                                                                                                                                        |
| --------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[Aviation Safety RAG Assistant](TODO_REPO_URL)**        | Hybrid-retrieval assistant over AAI's ATS manual and ATMC circulars | Python · LangChain · Llama 3.1 · ChromaDB · Cross-Encoder · Streamlit                      | BM25 + vector + cross-encoder reranking across **670+ pages**, with PyMuPDF/RapidOCR ingestion for scanned legacy PDFs and a Pytest regression suite guarding retrieval accuracy |
| **[SpeakEZ](TODO_REPO_URL)**                              | Real-time AI coaching platform simulating workplace conversations   | FastAPI · Node.js · Gemini Live API · PyTorch · sentence-transformers · MediaPipe · Prisma | Low-latency voice loop plus a multi-modal scoring pipeline — embeddings, speech fluency, acoustic confidence and live MediaPipe nudges — feeding personalized insights           |
| **[Marketplace Product Image Classifier](TODO_REPO_URL)** | Large-scale product image categorization                            | Python · TensorFlow · MobileNetV2                                                          | **110,000+ images across 42 classes (10GB)**, transfer learning to 72.4% accuracy with imbalance handling that added 5% validation accuracy                                      |

---

### Experience

**Machine Learning Intern — Airports Authority of India** · Jun 2026 – Aug 2026
Benchmarked a custom CNN against transfer learning for image classification, cutting convergence time **5×**, and improved an enterprise RAG system with BM25 retrieval, reranking, digital-text detection to skip needless OCR, and lazy-loaded model caching.

**AI/ML Intern — DomaiynLabs LLP** · Apr 2026 – Jul 2026
Researched adversarial testing for **Bayora**, an automated red-teaming platform, and shipped a firewall layer: a binary classifier for adversarial prompt detection served through a FastAPI inference backend for real-time LLM protection.

---

### GitHub
![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=jiyajain23&theme=tokyonight&bg_color=1a1b27&color=f2bbd0&line=f2bbd0&point=d48da3&area=true&hide_border=true)


---

<p align="center">
  <sub>If you've scrolled this far, you might as well <a href="mailto:jainjiya2312@gmail.com">say hi</a>.</sub>
</p>

---
