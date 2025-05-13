# 🧠 NLP Topic Modeling on Consumer Complaints

This project is part of the IU course **DLBDSEDA02 – Project: Data Analysis**.  
The objective is to analyze unstructured consumer complaints using Natural Language Processing (NLP) techniques to extract the most prevalent topics and support data-driven decision-making.

---

## 📁 Dataset

- **Source:** [Kaggle – Consumer Complaint Dataset]([https://www.kaggle.com/datasets/heemalichaudhari/consumer-complaints/data])
- **Content:** Customer complaint narratives submitted to the U.S. Consumer Financial Protection Bureau.
- **Used Column:** `Consumer complaint narrative`

---

## 🧪 Implementation Environment

- Implemented entirely in **Google Colab** (Python 3)
- All necessary libraries are installed using `pip` within the notebook
- Code is designed for reproducibility and ease of use

---

## 🔧 Main Steps

1. **Text Preprocessing**
   - Lowercasing, punctuation/number removal
   - Stopword removal and anonymized token cleanup (e.g., "xxxx")
   
2. **Text Vectorization**
   - `TF-IDF` vectorization using scikit-learn

3. **Topic Modeling**
   - **Latent Dirichlet Allocation (LDA)**
   - **Non-negative Matrix Factorization (NMF)**

4. **Visualization**
   - Word distributions per topic via bar plots
   - Optional word clouds for enhanced clarity

---

## 📊 Sample Extracted Topics

Topics included:
- Credit reporting issues
- Debt collection practices
- Banking and account access problems
- Mortgage and loan servicing difficulties

---

## 📎 Files Included

- `Consumer_Complaints.csv` – Raw dataset (external download)
- `NLP_Complaints_Analysis.ipynb` – Main notebook with full pipeline
- `README.md` – Project overview

---

## 🔗 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload the dataset or mount from Google Drive
3. Run all cells sequentially
4. Adjust parameters (e.g., number of topics or features) as needed

---

## 🧠 Learnings

This project demonstrates how to transform raw textual data into valuable insights using core NLP workflows, including preprocessing, vectorization, and topic modeling. It also showcases the importance of cleaning noisy data and adjusting model parameters for interpretable results.

---

