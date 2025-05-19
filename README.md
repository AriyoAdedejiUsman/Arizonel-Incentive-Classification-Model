# 🚀 Arizonel Incentive Classification Model

[![Python](https://img.shields.io/badge/python-3.8%2B-blue)]()
[![License: MIT](https://img.shields.io/badge/license-MIT-green)]()

An impactful machine learning project developed during my internship as a **Data Analysis Intern** at **Dreamline AI**. This model classifies users based on their eligibility for regional incentive programs—empowering smarter, data-driven decisions in targeted outreach.

---

## 🧠 Project Highlights

✅ Developed a full pipeline from raw user data to actionable predictions
✅ Worked with **real-world multi-region data** (demographics, transactions, behavior)
✅ Achieved **100% accuracy** with a well-tuned Random Forest model
✅ Engineered and validated a model that streamlines incentive distribution

---

## 🔧 Machine Learning Workflow

**1. Data Handling**
→ Leveraged **Pandas** and **NumPy** to clean and process regional user datasets

**2. Feature Engineering**
→ Encoded categorical features using **LabelEncoder** and **OneHotEncoder** within a **ColumnTransformer**

**3. Model Training**
→ Built a robust classification pipeline using **RandomForestClassifier** wrapped in a **Scikit-learn Pipeline**

**4. Evaluation**
→ Evaluated model performance using **classification\_report** and **accuracy\_score**:

### ✅ Final Output:

```
Model Accuracy: 1.0

Classification Report:
                           precision    recall  f1-score   support

    Corporate Tax Credit       1.00      1.00      1.00       303
 Corporate Tax Exemption       1.00      1.00      1.00       173
           Grant Program       1.00      1.00      1.00       453
Green Building Incentive       1.00      1.00      1.00         4
            Loan Program       1.00      1.00      1.00       764
          PACE Financing       1.00      1.00      1.00         8
     Personal Tax Credit       1.00      1.00      1.00       468
  Personal Tax Exemption       1.00      1.00      1.00       172
    Public Benefits Fund       1.00      1.00      1.00         2
          Rebate Program       1.00      1.00      1.00       147

                accuracy                           1.00      2494
               macro avg       1.00      1.00      1.00      2494
            weighted avg       1.00      1.00      1.00      2494
```

---

## 🧰 Libraries Used

* `pandas`
* `numpy`
* `seaborn`
* `scikit-learn`

  * `train_test_split`
  * `LabelEncoder`, `OneHotEncoder`
  * `ColumnTransformer`, `Pipeline`
  * `RandomForestClassifier`
  * `classification_report`, `accuracy_score`

---

## 🎯 Why It Matters

This model brings clarity and efficiency to incentive management across diverse user bases—transforming scattered behavioral data into strategic insight. It’s a practical, scalable solution for organizations working with regional segmentation and user targeting.

---

## 📫 Let's Connect

**Adedeji Ariyo Usman**
Data Analysis Intern, Dreamline AI
📧 [adedejiariyo29@gmail.com](mailto:adedejiariyo29@gmail.com)



