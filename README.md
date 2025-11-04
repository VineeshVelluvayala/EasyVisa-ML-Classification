
# 🧠 EasyVisa-ML-Classification  
**End-to-End Machine Learning Classification Project using CRISP-DM**

This project demonstrates a **complete Business Analytics and Machine Learning workflow** using the **CRISP-DM framework** — from data understanding to model evaluation — on a real-world visa application dataset.  
It was developed as part of the **Business Analytics coursework** to strengthen practical ML skills using Python.

---

## 🚀 Project Overview
The goal of this project is to **predict visa approval outcomes** based on various applicant and job attributes such as education, experience, and employer details.  
By applying **supervised learning algorithms**, we aim to build an interpretable model that helps identify key factors influencing visa approvals.

---

## 🧩 CRISP-DM Framework

### 1️⃣ Business Understanding
The business objective is to:
- Analyze historical visa applications.
- Identify key patterns leading to approval or denial.
- Build a predictive model to improve transparency and decision-making.

### 2️⃣ Data Understanding
Dataset: `EasyVisa.csv`  
Key attributes include:
- Applicant education, occupation, employer
- Work experience and salary range
- Country and job classification codes
- Target variable: `case_status` (Certified / Denied)

Initial steps performed:
- Data inspection and descriptive statistics.
- Visualization of categorical and numerical distributions.
- Checking for class imbalance and missing values.

### 3️⃣ Data Preparation
- Cleaned inconsistent text and categorical labels.
- Encoded categorical variables using LabelEncoder/OneHotEncoder.
- Normalized numerical fields.
- Split dataset into **Train (70%)** and **Test (30%)** sets.

### 4️⃣ Modeling
Trained and compared multiple classification algorithms:
- ✅ Decision Tree Classifier  
- ✅ Random Forest Classifier  
- ✅ Gradient Boosting  
- ✅ XGBoost  

Best Model: **Random Forest**  
- Achieved highest F1-score and accuracy  
- Balanced performance across all classes  

### 5️⃣ Evaluation
Evaluated models using:
- Accuracy, Precision, Recall, F1-Score  
- Confusion Matrix & ROC-AUC curve  

Model Metrics Example:
| Model | Accuracy | F1-Score | AUC |
|--------|-----------|----------|------|
| Decision Tree | 83% | 0.81 | 0.85 |
| Random Forest | **89%** | **0.87** | **0.90** |
| Gradient Boost | 86% | 0.84 | 0.88 |

### 6️⃣ Deployment & Insights
The trained model can be deployed in HR systems to:
- Pre-screen visa applicants
- Highlight risk factors for denial
- Provide data-driven insights to policy analysts

---

## 📊 Tools & Technologies
| Category | Tools Used |
|-----------|-------------|
| Programming | Python (Jupyter / Google Colab) |
| Libraries | pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost |
| Framework | CRISP-DM |
| Visualization | Matplotlib, Seaborn |
| Version Control | GitHub |

---

## 📁 Repository Structure
