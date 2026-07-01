<div align="center">

# 🧬 Genetic Profile-Based Drug Sensitivity Prediction in Acute Myeloid Leukemia Using SVR

### Machine Learning for Precision Oncology and Personalized Drug Response Prediction

<p>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=25&pause=1000&color=6C63FF&center=true&vCenter=true&width=850&lines=Precision+Oncology;Drug+Sensitivity+Prediction;Support+Vector+Regression;Cancer+Genomics;Bioinformatics+%7C+Machine+Learning"/>

</p>

<p>

<img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python"/>
<img src="https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn"/>
<img src="https://img.shields.io/badge/Support_Vector_Regression-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Bioinformatics-green?style=for-the-badge"/>

</p>

</div>

---

# 📖 Overview

This project presents a machine learning framework for predicting **drug sensitivity in Acute Myeloid Leukemia (AML)** using **Support Vector Regression (SVR)**. By learning the relationship between genetic profiles and drug response, the model supports precision oncology through personalized treatment prediction and biomarker discovery.

---

# ✨ Features

- 🧬 Drug sensitivity prediction using genetic profiles
- 🤖 Support Vector Regression (SVR)
- 🎯 Recursive Feature Elimination (RFE)
- ⚙️ Hyperparameter tuning with GridSearchCV
- 📊 Five-fold Cross Validation
- 🔬 Biomarker identification
- 💊 Precision medicine applications

---

# ⚙️ Pipeline

```text
           GDSC2 Dataset
                  │
                  ▼
         Data Preprocessing
                  │
                  ▼
      Feature Selection (RFE)
                  │
                  ▼
     Hyperparameter Tuning
          (GridSearchCV)
                  │
                  ▼
 Support Vector Regression (SVR)
                  │
                  ▼
      Drug Sensitivity Prediction
                  │
                  ▼
        Model Evaluation
      (R² • MSE • Cross Validation)
```

---

# 📊 Dataset

| Dataset | Description |
|---------|-------------|
| Source | Genomics of Drug Sensitivity in Cancer (GDSC2) |
| Cancer Type | Acute Myeloid Leukemia (AML) |
| Samples | 902 |
| Target Variable | IC50 Drug Response |

---

# 🤖 Machine Learning Model

| Component | Method |
|-----------|--------|
| Feature Selection | Recursive Feature Elimination (RFE) |
| Regression Model | Support Vector Regression (SVR) |
| Hyperparameter Optimization | GridSearchCV |
| Validation | 5-Fold Cross Validation |

---

# 📈 Results

| Metric | Score |
|--------|------:|
| Validation R² | **0.9523** |
| Test R² | **0.8928** |
| Validation MSE | **0.0066** |
| Test MSE | **0.0096** |
| Mean Cross Validation Score | **0.9642** |

---

# 🔬 Selected Biomarkers

The feature selection process identified several important predictors of drug response, including:

- SACS Mutation
- THR-103
- Glutathione
- IC50 Feature Statistics
- Feature Significance (p-value)
- Microsatellite Instability (MSI)

These biomarkers contributed significantly to predicting personalized drug sensitivity in AML patients.

---

# 🛠 Tech Stack

<p>

<img src="https://skillicons.dev/icons?i=python"/>

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="45"/>

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="45"/>

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" width="45"/>

</p>

**Libraries**

- Scikit-learn
- NumPy
- Pandas
- Matplotlib

---

# 📂 Repository Structure

```text
AML-Drug-Sensitivity/

├── data/
├── notebooks/
├── preprocessing/
├── feature_selection/
├── models/
├── evaluation/
├── figures/
├── requirements.txt
└── README.md
```

---

# 🚀 Getting Started

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/AML-Drug-Sensitivity.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebooks or Python scripts to reproduce the experiments.

---

# 🎯 Future Work

- [ ] Multiomics integration
- [ ] Deep learning-based drug response prediction
- [ ] Explainable AI using SHAP
- [ ] Clinical validation on independent cohorts
- [ ] Extension to additional cancer types

---

# 📚 Citation

```bibtex
@article{ruhama2024amlsvr,
  title={Genetic Profile-Based Drug Sensitivity Prediction in Acute Myeloid Leukemia Patients Using Support Vector Regression},
  author={Ruhama, Sadia},
  year={2024}
}
```

---

# 👩‍💻 Author

## Sadia Ruhama

**M.Sc. Student**  
Department of Computer Science and Engineering  
BRAC University

### Research Interests

- Computational Biology
- Bioinformatics
- Machine Learning
- Precision Medicine
- Cancer Genomics

📧 **Email:** sadia.ruhama@g.bracu.ac.bd

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

Made with ❤️ by **Sadia Ruhama**

</div>
