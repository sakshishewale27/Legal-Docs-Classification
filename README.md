# 🧾 Legal Document Classification
This project focuses on classifying **legal contract clauses** into predefined categories using **Natural Language Processing (NLP)** and **Machine Learning** techniques.  
It helps automate the process of understanding and organizing legal documents for faster review and analysis.

---

## 🧠 Project Overview
The Jupyter Notebook includes:
- Text preprocessing (cleaning, tokenization, stopword removal)
- Feature extraction using **TF-IDF** and keyword/length-based features
- Model training with **Decision Tree** and **Random Forest**
- Model evaluation using accuracy score and performance comparison

---

## 📂 Dataset
The dataset used for this project is **CUAD (Contract Understanding Atticus Dataset)** available publicly on Hugging Face:

🔗 [CUAD_v1_Contract_Understanding_clause_classification](https://huggingface.co/datasets/dvgodoy/CUAD_v1_Contract_Understanding_clause_classification)

This dataset contains real contract clauses labeled into different legal categories.

---

## 🧰 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- NLTK  
- Jupyter Notebook  

---

## 📈 Results

### ⚙️ Data Summary
- **Total Samples:** 7,192  
- **Risk Distribution:**  
  - Low: 3,835  
  - Medium: 1,565  
  - High: 1,792  

### 🧮 Model Performance
| Model | Accuracy |
|:------|:----------:|
| Decision Tree | 71.16% |
| Random Forest | **74.08%** |

✅ Random Forest outperformed the baseline Decision Tree model with a **2.92% improvement** in accuracy.

