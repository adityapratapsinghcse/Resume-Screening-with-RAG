# AI Resume Shortlister

An AI-powered resume shortlisting system that intelligently analyzes, retrieves, and ranks resumes based on job description relevance using Retrieval-Augmented Generation (RAG), semantic embeddings, and NLP techniques.

---

# Overview

Recruiters often spend hours manually filtering resumes. This project automates the process by using AI-based semantic retrieval and ranking techniques to identify the most relevant candidates efficiently.

The system processes resumes, generates embeddings, compares them with job requirements, and retrieves the best-matching profiles.

---

# Features

- AI-powered resume ranking
- Semantic similarity matching
- Retrieval-Augmented Generation (RAG)
- Resume relevance scoring
- Embedding-based search
- Candidate filtering pipeline
- Modular and scalable architecture
- Fast retrieval mechanism

---

# Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core Programming |
| NLP | Text Processing |
| RAG | Intelligent Retrieval |
| Embeddings | Semantic Search |
| Vector Search | Similarity Matching |
| Streamlit / Python UI | Frontend Interface |

---

# Project Architecture

```text
User Query / Job Description
            ↓
Resume Processing
            ↓
Text Embedding Generation
            ↓
Vector Similarity Search
            ↓
Resume Ranking
            ↓
Top Candidate Retrieval
```

---

# Project Structure

```bash
ai-resume-shortlister/
│
├── app.py
├── embeddings.py
├── rag_pipeline.py
├── retriever.py
├── resume_compression.py
├── sample_resumes/
├── screenshots/
├── requirements.txt
├── .gitignore
└── README.md
```

---

# How It Works

## 1. Resume Collection

The system loads and processes candidate resumes from the dataset.

---

## 2. Text Processing

Resume text is cleaned and prepared for embedding generation.

---

## 3. Embedding Generation

Semantic embeddings are generated using NLP embedding models.

---

## 4. Similarity Search

The system compares resume embeddings with job description embeddings.

---

## 5. Candidate Ranking

Candidates are ranked according to semantic relevance and similarity score.

---

# Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-resume-shortlister.git
```

---

## Navigate into Project

```bash
cd ai-resume-shortlister
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Project

## Run Application

```bash
python app.py
```

OR

```bash
streamlit run app.py
```

Depending on your project structure.

Because developers collectively decided one universal standard would be too peaceful.

---

# Example Workflow

1. Upload resumes
2. Enter job description
3. Generate semantic embeddings
4. Retrieve top matching resumes
5. Display ranked candidates

---

# Screenshots

## Home Page

![Home](screenshots/home.png)

---

## Resume Upload

![Upload](screenshots/upload.png)

---

## Candidate Ranking Output

![Results](screenshots/results.png)

---

# Future Improvements

- PDF resume parsing
- Recruiter dashboard
- Advanced ranking metrics
- Web deployment
- Authentication system
- Multi-job comparison
- Database integration
- Real-time analytics

---

# Applications

- HR automation
- Recruitment systems
- Candidate screening
- AI hiring tools
- Resume intelligence systems

---

# Learning Outcomes

This project demonstrates understanding of:

- Retrieval-Augmented Generation (RAG)
- NLP pipelines
- Semantic search
- Embedding models
- Vector retrieval systems
- AI-based ranking systems
- Backend application development

---

# Disclaimer

This project is developed for educational and research purposes.

---

# Author

## Aditya Pratap Singh

B.Tech CSE Student | AI & ML Enthusiast | Developer

---

# License

This project is licensed under the MIT License.
