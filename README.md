
# 🎓 Chance of Admission Prediction
### Predictive Analytics for Graduate School Admissions

<p align="center">
<img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-Regression-F7931E?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Analysis-Predictive%20Modeling-8E44AD?style=for-the-badge">
<img src="https://img.shields.io/badge/Library-Pandas-150458?style=for-the-badge&logo=pandas">
<img src="https://img.shields.io/badge/Visualization-Seaborn-444444?style=for-the-badge">
</p>

---

## 🌟 Overview

Navigating graduate school admissions can be a daunting process for students. This project implements a **Supervised Machine Learning** pipeline to estimate the probability of admission based on a candidate's academic and professional profile. By analyzing historical admission data, the model identifies key success factors and provides a data-driven "Chance of Admission" score.



### Core Objectives:
- **Probability Estimation:** Quantify the likelihood of admission on a scale of 0 to 1.
- **Academic Impact Analysis:** Determine the weight of GRE, TOEFL, and CGPA on successful applications.
- **Model Benchmarking:** Compare various regression algorithms to find the most accurate predictor.

---

## 🎯 Key Features

* ✅ **Multi-Algorithm Comparison:** Evaluates Linear Regression, Decision Trees, Random Forest, and XGBoost.
* ✅ **Feature Engineering:** Robust preprocessing including feature scaling and correlation analysis to handle varying score ranges.
* ✅ **Comprehensive Evaluation:** Uses R² Score, RMSE (Root Mean Squared Error), and MAE (Mean Absolute Error) for high-fidelity performance tracking.
* ✅ **Interactive Documentation:** Step-by-step implementation via Jupyter Notebook for transparency and reproducibility.

---

## 🧠 Tech Stack

| Category | Tools |
| :--- | :--- |
| **Language** | Python 3.8+ |
| **ML Framework** | Scikit-learn, XGBoost |
| **Data Handling** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Environment** | Jupyter Notebook |

---

## 📁 Project Structure

```bash
Chance_of_Admission_for_Higher_Studies/
├── Chance_of_Admission_for_Higher_Studies.ipynb   # Main ML implementation & training
├── Chance of Admission for Higher Studies_intro.txt  # Project context & objectives
├── Chance of Admission for Higher Studies_report.txt # Detailed analysis & results
├── requirements.txt                                # Project dependencies
└── README.md                                       # Documentation

```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone [https://github.com/G-Narendra/Chance_of_Admission_for_Higher_Studies.git](https://github.com/G-Narendra/Chance_of_Admission_for_Higher_Studies.git)
cd Chance_of_Admission_for_Higher_Studies

```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt

```

### 3️⃣ Run the Analysis

```bash
jupyter notebook Chance_of_Admission_for_Higher_Studies.ipynb

```

---

## 📊 Data Insights & Methodology

The model analyzes several critical features to predict the target variable:

* **GRE & TOEFL Scores:** Standardized test performance.
* **University Rating:** The prestige tier of the target institution.
* **SOP & LOR Strength:** Qualitative profile components (Letter of Recommendation/Statement of Purpose).
* **CGPA:** Undergraduate academic consistency.
* **Research Experience:** Binary indicator of research involvement.

---

## 🚀 Future Roadmap

* [ ] **Web Integration:** Develop a Flask/Streamlit interface for real-time user predictions.
* [ ] **Profile Optimizer:** Add a feature that suggests which score (GRE/TOEFL) needs improvement to hit a specific probability target.
* [ ] **Neural Network Expansion:** Implement Multi-Layer Perceptrons (MLP) for non-linear pattern recognition.

---

## 👨‍💻 Author

**Narendra (G‑Narendra)** AI | ML | Python | Full Stack | GenAI Enthusiast

📧 [Email Me](mailto:narendragandikota2540@gmail.com) | 💼 [LinkedIn](https://linkedin.com/in/g-narendra/) | 👨‍💻 [GitHub](https://github.com/G-Narendra)

---

<p align="center">⭐ If you find this project useful, feel free to give it a star! 🚀</p>

