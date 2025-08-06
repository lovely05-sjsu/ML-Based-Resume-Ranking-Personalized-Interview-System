# ML-Based Resume Ranking & Personalized Interview System

This project introduces an AI-powered solution to automate two crucial HR processes: ranking resumes based on their relevance to job descriptions and generating personalized interview questions from candidate profiles. It leverages NLP, ML, and explainability tools to streamline recruitment and reduce human bias.

---

## Table of Contents

- [Features](#-features)
- [Demo](#-demo)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Modeling Approach](#-modeling-approach)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)
- [Authors](#-authors)

---

## Features

- Automated resume parsing and relevance ranking
- Personalized interview question generation using GPT/T5
- Model explainability using SHAP
- Supports multiple ML models (Random Forest, XGBoost, etc.)
- Interactive web interface (built with Streamlit)
- Secure handling of resume and job data

---

## Demo

> A live demo is not deployed, but screenshots are available below.

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
git clone https://github.com/lovely05-sjsu/ML-project.git
cd ML-project

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

## Screenshots

| Main Dashboard | Resume Upload | Result |
|----------------|----------------|--------|
| ![Main](assets/screenshot_main.png) | ![Upload](assets/screenshot_upload.png) | ![Output](assets/screenshot_output.png) |

> *(Add screenshots to `assets/` folder and update the links accordingly)*

---

## Contributing

We welcome contributions! Please fork the repository and submit a pull request.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Authors

- [Devarsh Patel](mailto:devarshnatvarlal.patel@sjsu.edu)
- [Smit Ardeshana](mailto:smitarvindkumar.ardeshana@sjsu.edu)
- [Dharmitkumar Patel](mailto:dharmitkumarsureshbhai.patel@sjsu.edu)
- [Shatayu Thakur](mailto:shatayu.thakur@sjsu.edu)
- [Lovely Priya](mailto:lovely@sjsu.edu)
- [Mansi Tanna](mailto:mansisanjaybhai.tanna@sjsu.edu)
- [Sai Swetha Madapati](mailto:saiswetha.madapati@sjsu.edu)

---

## References

Key technologies used:
- [Sentence-BERT](https://arxiv.org/abs/1908.10084)
- [SHAP](https://shap.readthedocs.io)
- [Transformers](https://huggingface.co/docs/transformers)
- [scikit-learn](https://scikit-learn.org/)
- [Streamlit](https://streamlit.io/)
