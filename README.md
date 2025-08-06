# ML-Based Resume Ranking & Personalized Interview System

This project introduces an AI-powered solution to automate two crucial HR processes: ranking resumes based on their relevance to job descriptions and generating personalized interview questions from candidate profiles. It leverages NLP, ML, and explainability tools to streamline recruitment and reduce human bias.

---

## Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Modeling Approach](#-modeling-approach)
- [References](#-References)

---

## Features

- Automated resume parsing and relevance ranking
- Personalized interview question generation using GPT/T5
- Model explainability using SHAP
- Supports multiple ML models (Random Forest, XGBoost, etc.)
- Interactive web interface (built with Streamlit)
- Secure handling of resume and job data

---

## Tech Stack

- **Language**: Python 3.x
- **Libraries**: scikit-learn, pandas, NumPy, nltk, spaCy, SHAP, Sentence-BERT, HuggingFace Transformers
- **ML Models**: Random Forest, Logistic Regression, XGBoost, LightGBM
- **Interface**: Streamlit
- **Deployment**: Local / Cloud (AWS/GCP compatible)

---

## Installation

```bash
# Clone the repo
git clone # Clone the repo
git clone https://github.com/lovely05-sjsu/ML-Based-Resume-Ranking-Personalized-Interview-System.git
cd ML-Based-Resume-Ranking-Personalized-Interview-System

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
cd ML-Based-Resume-Ranking-Personalized-Interview-System

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

---

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Upload a job description and a set of resumes (PDF or CSV format).
3. View ranked candidates and personalized interview questions.

---

## Modeling Approach

- **Resume Ranking**: Semantic similarity using Sentence-BERT & classification via Random Forest/XGBoost.
- **Interview Generation**: GPT/T5 models used to generate contextually relevant questions.
- **Explainability**: SHAP plots to explain why a resume was selected or rejected.

---

## References

Key technologies used:
- [Sentence-BERT](https://arxiv.org/abs/1908.10084)
- [SHAP](https://shap.readthedocs.io)
- [Transformers](https://huggingface.co/docs/transformers)
- [scikit-learn](https://scikit-learn.org/)
- [Streamlit](https://streamlit.io/)
