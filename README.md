# 📊 High-Order Thinking Skills (HOTS) Assignment — Data Science

> **Course:** Data Science | **Type:** Higher-Order Thinking Assignment  
> **Team Members:**  
> - Adharsh V S — `RA2311026050021`  


---

## 📌 Project Overview

This repository contains the complete submission for the **Higher-Order Thinking Skills (HOTS) Assignment** in the Data Science course. The project focuses on **HR Employee Attrition Analysis and Prediction** — a real-world HR analytics problem that applies advanced Data Science techniques to uncover insights about employee turnover.

The assignment encompasses the full data science lifecycle:
- **Exploratory Data Analysis (EDA)**
- **Feature Engineering**
- **Predictive Modeling**
- **Insight Generation and Business Recommendations**

---

## 📂 Repository Structure

```
HOTS_assignment-Datascience/
│
├── WA_Fn-UseC_-HR-Employee-Attrition.csv   # IBM HR Analytics Dataset
├── hr_feature_engineering.ipynb            # Jupyter Notebook (EDA + Feature Engineering + Modeling)
├── HOTS_021.pdf                            # Final Assignment Report (PDF)
└── README.md                               # Project Documentation
```

---

## 📋 Dataset

**IBM HR Analytics Employee Attrition & Performance Dataset**

| Attribute | Details |
|-----------|---------|
| **Source** | IBM Watson Analytics / Kaggle |
| **Records** | 1,470 employees |
| **Features** | 35 attributes |
| **Target** | `Attrition` (Yes / No) |

### Key Features:
- **Demographics:** Age, Gender, MaritalStatus, Education, EducationField  
- **Job Details:** Department, JobRole, JobLevel, BusinessTravel, OverTime  
- **Compensation:** MonthlyIncome, HourlyRate, StockOptionLevel  
- **Satisfaction Scores:** JobSatisfaction, EnvironmentSatisfaction, WorkLifeBalance  
- **Performance:** PerformanceRating, TrainingTimesLastYear  
- **Tenure:** YearsAtCompany, YearsInCurrentRole, YearsSinceLastPromotion  

---

## 🔬 Methodology

### 1. Exploratory Data Analysis (EDA)
- Distribution analysis of numerical and categorical features
- Attrition rate visualization by department, role, gender, and age group
- Correlation heatmaps and feature relationship plots
- Identifying class imbalance in the target variable

### 2. Feature Engineering
- Encoding categorical variables (Label Encoding / One-Hot Encoding)
- Creating derived features (e.g., Salary-to-Satisfaction ratio, Tenure bands)
- Handling constant/redundant columns (`EmployeeCount`, `StandardHours`, `Over18`)
- Feature scaling using StandardScaler
- Feature importance analysis

### 3. Predictive Modeling
- Baseline model evaluation
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting (XGBoost / sklearn)
- Model performance comparison (Accuracy, Precision, Recall, F1-Score, ROC-AUC)

### 4. Business Insights & Recommendations
- Top drivers of employee attrition
- Actionable HR strategies based on model findings
- Risk profiling of high-attrition employee segments

---

## 📈 Key Findings

- **Overall Attrition Rate:** ~16% (class imbalance observed)
- **High Risk Groups:** Employees in Sales, with overtime, early career stage, and low job satisfaction
- **Top Attrition Predictors:** `OverTime`, `MonthlyIncome`, `JobSatisfaction`, `YearsAtCompany`, `WorkLifeBalance`

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| **Python 3.x** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib / Seaborn** | Data visualization |
| **Scikit-Learn** | Machine learning models |
| **Jupyter Notebook** | Interactive development |

---

## 🚀 How to Run

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/adharsh2006/HOTS_assignment-Datascience.git
   cd HOTS_assignment-Datascience
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook hr_feature_engineering.ipynb
   ```

3. Run all cells sequentially (`Kernel → Restart & Run All`)

---

## 📄 Report

The complete written report is available as [`HOTS_021.pdf`](./HOTS_021.pdf), which includes:
- Problem statement and objectives
- Literature review
- Methodology
- Results and analysis
- Conclusions and future scope

---

## 👨‍💻 Authors

| Name | Roll Number |
|------|-------------|
| Adharsh V S | RA2311026050021 |


---

## 📜 License

This project is submitted for academic purposes under the Data Science course. All rights reserved by the authors.

---

*SRM Institute of Science and Technology — Department of Data Science*
