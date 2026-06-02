# Thyroid Cancer Recurrence Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting **thyroid cancer recurrence** using patient demographic and clinical data. Machine learning models are applied to assist in early identification of high-risk patients, supporting better clinical decision-making.

---

## 🔍 Summary
This project uses machine learning techniques to predict the recurrence of thyroid cancer based on medical and demographic features. The solution aims to support early intervention and improved treatment planning.

---

## 🎯 Problem Statement
Recurrence of thyroid cancer is a major challenge in long-term patient management. The objective of this project is to predict whether a patient is likely to experience cancer recurrence using historical clinical data, enabling timely medical intervention. :contentReference[oaicite:0]{index=0}

---

## 🧰 Tools and Technologies
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  
- **Models Used:**  
  - Logistic Regression  
  - Decision Tree Classifier  
  - Random Forest Classifier  
  - K-Nearest Neighbors (KNN)  
- **Environment:** Jupyter Notebook  

---

## 🧪 Methods
1. **Data Loading and Validation**
   - Loaded the *Differentiated_Thyroid_Cancer_Recurrence* dataset.
   - Verified data quality (no missing values detected).

2. **Exploratory Data Analysis (EDA)**
   - Analyzed age distribution and recurrence patterns.
   - Visualized correlations using heatmaps.
   - Examined target variable imbalance (Recurred vs Not Recurred). :contentReference[oaicite:1]{index=1}

3. **Data Preprocessing**
   - Encoded categorical variables using Label Encoding.
   - Split data into 80% training and 20% testing sets.

4. **Model Training and Evaluation**
   - Trained multiple classification models.
   - Evaluated performance using Accuracy, Confusion Matrix, and Classification Report.

---

## 📊 Key Insights
- The dataset contains **no missing values**, ensuring reliable model training.
- Age and clinical staging variables show strong correlation with recurrence.
- **Random Forest Classifier** performed best with:
  - **98.7% accuracy**
  - High precision and recall for both recurrent and non-recurrent cases
  - Strong performance on the minority (recurred) class :contentReference[oaicite:2]{index=2}

---

## 🚀 Future Scope
- Deploy the model as a **clinical decision support tool**.
- Apply hyperparameter tuning to further improve performance.
- Extend the model to handle larger and more imbalanced datasets.
- Explore deep learning techniques for complex medical data.
- Integrate the solution with hospital management systems for real-time prediction. :contentReference[oaicite:3]{index=3}

---

## 👤 Author
**Shreyash Vishwakarma**

---

## 📬 Contact
📧 **shreyash.sk.sv@gmail.com**

---

## 📄 Disclaimer
This project is developed for academic and learning purposes using anonymized medical data.  
