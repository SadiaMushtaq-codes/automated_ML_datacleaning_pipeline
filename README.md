# automated_ML_datacLeaning_pipeline
# 🧹 Automated ML Data Cleaning Pipeline

An end-to-end automated pipeline for preprocessing and cleaning raw datasets before machine learning model training. Built during the **FutureXcel Machine Learning Internship (2026)**.

---

## 📌 Overview

Raw data is rarely model-ready. This project automates the most time-consuming and error-prone part of any ML workflow — data cleaning — so that datasets can be reliably prepared for training with minimal manual intervention.

The pipeline handles a large real-world dataset (train: ~5.88 MB) and outputs clean, ML-ready CSV files.

---

## ⚙️ Features

- ✅ Automated detection and handling of **missing values**
- ✅ **Outlier detection** and treatment
- ✅ **Categorical encoding** for non-numeric features
- ✅ **Feature scaling** / normalization
- ✅ Automated **train/test split** with cleaned outputs saved as CSV
- ✅ Reproducible pipeline — run once, get consistent results

---

## 🗂️ Repository Structure
automated_ML_datacleaning_pipeline/

│

├── datapipeline.ipynb        # Main notebook — full pipeline implementation

├── cleaned_train.csv         # Cleaned training dataset (output)

├── cleaned_test.csv          # Cleaned test dataset (output)

└── README.md

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| Pandas | Data loading, manipulation, cleaning |
| NumPy | Numerical operations |
| Scikit-Learn | Preprocessing (encoders, scalers, imputers) |
| Jupyter Notebook | Development environment |

---

## 🚀 How to Run

### 1. Clone the repository
git clone https://github.com/SadiaMushtaq-codes/automated_ML_datacleaning_pipeline.git

cd automated_ML_datacleaning_pipeline
### 2. Install dependencies
pip install -r requirements.txt


## 📊 Output

| File | Description |
|------|-------------|
| `cleaned_train.csv` | Preprocessed training data (~5.88 MB) |
| `cleaned_test.csv` | Preprocessed test data |


## 💡 Key Learnings

- Designing modular, reusable preprocessing functions
- Handling real-world data imperfections at scale
- Building reproducible ML pipelines following industry best practices


## 👩‍💻 Author

**Sadia Mushtaq**
BS Artificial Intelligence — Government College University, Hyderabad
📧 sadia.mushtaq.ai@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/sadia-khan-aa4009292/) | [GitHub](https://github.com/SadiaMushtaq-codes)


*Developed as part of the FutureXcel Machine Learning Internship, January–February 2026.*
