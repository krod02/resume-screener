# 📄 AI-Powered Resume Screener (NLP & BERT)

## 🚀 Overview
This project is an AI-powered resume screening system that:
- **Extracts skills, job titles, and relevant details** from PDF resumes.
- **Ranks resumes** based on how well they match a given job description.
- **Provides explainability** using SHAP to show why a resume is a good match.

## 🎯 Features
✔ **Resume Ranking** – Scores resumes based on job descriptions.  
✔ **Job-Title Matching** – Extracts and matches job titles from resumes.  
✔ **Skill Extraction** – Identifies key skills using NLP.  
✔ **Explainability with SHAP** – Shows why a resume was ranked a certain way.  
✔ **PDF Resume Support** (for now).  
✔ **User-Friendly UI** (Streamlit).  

## 🛠 Tech Stack
- **Python** (for NLP processing & modeling)
- **Hugging Face Transformers** (BERT/DistilBERT for job matching)
- **spaCy** (for skill extraction & named entity recognition)
- **SHAP** (Explainability)
- **PyPDF2/pdfminer** (for PDF parsing)
- **FastAPI** (Backend API)
- **Streamlit** (Frontend UI)
- **Docker** (Containerization)
- **AWS/GCP (Optional)** (For future deployment)

## 📂 Project Structure
resume-screener/ ├── data/ 
# Datasets (resumes, job descriptions) ├── notebooks/ 
# Jupyter Notebooks for EDA & model training ├── src/ 
# Core NLP scripts (preprocessing, BERT models) ├── api/ 
# FastAPI backend (resume upload & processing) ├── frontend/ 
# Streamlit UI (resume upload, ranking) ├── docker/ 
# Docker setup for deployment ├── models/ 
# Trained ML models ├── docs/ 
# Documentation & process logs ├── README.md 
# Project description ├── requirements.txt 
# Dependencies ├── .gitignore 
# Ignore unnecessary files

## 📊 Data Sources
- Resume Dataset: 📌 **(To be added)**
- Job Description Dataset: 📌 **(To be added)**

## 📈 Progress Log
A complete log of the project's development can be found in **PROJECT_LOG.md**.

## 📦 Installation & Setup
1️⃣ Clone the repository:
```bash
git clone https://github.com/yourusername/resume-screener.git
```
2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

3️⃣ Run the application:
```bash
streamlit run frontend/app.py
```
🤝 Contributions & Feedback
This is a personal project for learning NLP and AI deployment. Feedback and contributions are welcome!