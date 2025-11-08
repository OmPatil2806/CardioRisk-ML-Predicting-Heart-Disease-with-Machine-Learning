# 🫀 Heart Disease Risk Prediction using Machine Learning

## 📖 Project Overview

**CardioRisk ML** is an end-to-end **machine learning pipeline** designed to predict an individual's risk of developing **heart disease**.  
By leveraging **clinical and demographic data**, the model helps healthcare providers identify **high-risk patients early**, enabling proactive interventions, optimized resource allocation, and improved patient outcomes.  

This project demonstrates a complete **data science workflow** — from **data exploration and preprocessing**, through **feature engineering and model training**, to **evaluation and interpretation**.

---

## 🎯 Business & Clinical Problem

Heart disease remains a **leading cause of death worldwide**.  
A key challenge for healthcare organizations is **early risk detection** among massive patient datasets with limited diagnostic resources.  
Failure to do so leads to increased costs and preventable fatalities.

This project addresses that need by providing a **data-driven predictive model** to identify at-risk patients — allowing for:

1. 🩺 **Prioritization** of preventative therapy  
2. 🧠 **Efficient resource allocation**  
3. 💉 **Reduction in unnecessary testing**  
4. ❤️ **Improved outcomes through early intervention**

---

## 📊 Dataset

**Source:** [Heart Disease Dataset (Kaggle)](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

**Description:**  
Contains **1,025 patient records** with **14 clinical and demographic features** used to predict heart disease presence (`1`) or absence (`0`).

**Example Features:**
- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Serum Cholesterol  
- Maximum Heart Rate  
- Exercise-Induced Angina  
- ST Depression (Oldpeak)  
- Target (Heart Disease Indicator)

---

## 🛠️ Project Pipeline & Technical Implementation

1. **Data Exploration & Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Scaling continuous features

2. **Class Imbalance Handling**
   - SMOTE (Synthetic Minority Oversampling)
   - Stratified sampling for balanced training

3. **Data Visualization**
   - Correlation heatmaps
   - Feature distribution plots
   - Comparison of healthy vs. diseased groups

4. **Machine Learning Models**
   - Logistic Regression
   - Random Forest Classifier
   - Support Vector Machine (SVM)
   - Gradient Boosting Classifier

---

## 📈 Key Results & Insights

- 🧮 Best-performing model achieved **Accuracy = X%** and **AUC-ROC = Y**.  
- 💡 Top predictive features include:
  - **Chest Pain Type (cp)**
  - **Max Heart Rate (thalach)**
  - **Oldpeak**
  - **ST Slope**
  - **Age**
- ⚙️ The model shows strong potential as a **screening tool** for clinicians to support early detection.


---

## 🔮 Future Work

1. 🌐 Deploy the best model using **Flask** or **Streamlit** for real-time risk assessment  
2. 💾 Integrate with **EHR (Electronic Health Record)** systems  
3. 🧠 Explore **Deep Neural Networks** for advanced risk prediction  
4. 🌍 Include more diverse datasets for global model generalization  

---

## 👤 Author

**Om Patil**  
📧 *Data Science & Machine Learning Enthusiast*  
🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/om-patil-039863369/)  
👨‍💻 [GitHub Profile](https://github.com/OmPatil2806)
