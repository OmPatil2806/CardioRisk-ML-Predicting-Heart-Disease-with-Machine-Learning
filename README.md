🫀 Heart Disease Risk Prediction using Machine Learning

Introduction:- Heart disease remains one of the leading causes of mortality worldwide, making early risk detection a crucial step in preventive healthcare. With the increasing availability of medical data, machine learning provides powerful tools to uncover patterns and predict cardiovascular outcomes. This project leverages both classical machine learning models and deep learning techniques to analyze patient health records and predict the likelihood of heart disease. By comparing multiple algorithms and incorporating modern preprocessing methods, the project aims to demonstrate the potential of AI-driven solutions in healthcare.

Business Problem:- Healthcare professionals often face challenges in diagnosing heart disease at an early stage due to overlapping symptoms and varying patient conditions. Misdiagnosis or delayed detection can lead to severe health complications and increased mortality rates. This project addresses the need for a reliable, data-driven decision support system that can assist clinicians in predicting the probability of heart disease risk. Such a system can not only improve diagnostic accuracy but also help in prioritizing patients for preventive care and timely intervention.

Objectives:- The primary objective of this project is to develop a predictive model capable of distinguishing between patients with and without heart disease. To achieve this, the project covers the full data science pipeline, including handling missing values, balancing datasets with SMOTE, feature scaling, and engineering additional risk indicators. Multiple machine learning models, such as Logistic Regression, Decision Tree, and K-Nearest Neighbors, are trained and evaluated alongside a deep learning-based logistic regression implemented with TensorFlow and PyTorch. Each model is assessed using accuracy, precision, recall, F1 score, confusion matrices, and ROC curves, ensuring a comprehensive comparison. Ultimately, the project aims to highlight the most effective modeling approach for heart disease prediction and provide a foundation for future deployment in clinical settings.

Project pipeline:

Step 1: Data Collection and Exploration:- The project begins by loading the heart disease dataset. The dataset’s shape, column names, and statistical properties are explored using descriptive statistics and visualization techniques. This helps in understanding the data distribution and identifying any anomalies.

Step 2: Data Cleaning and Missing Value Handling:- To simulate real-world healthcare data challenges, missing values are intentionally injected into columns such as age, cholesterol, thalach, and slope. These missing values are then imputed using appropriate strategies: median for numerical columns and mode for categorical columns. This ensures the dataset is complete and ready for training.

Step 3: Exploratory Data Analysis (EDA):- EDA is carried out to study class balance between patients with heart disease and those without. Count plots and percentage distributions are used to visualize imbalance. Additional feature distributions are also analyzed to observe trends, such as cholesterol levels, resting blood pressure, and exercise-induced angina.

Step 4: Handling Class Imbalance:- Since medical datasets often suffer from imbalanced classes, the Synthetic Minority Oversampling Technique (SMOTE) is applied. SMOTE balances the target variable by generating synthetic samples of the minority class, ensuring that both positive and negative cases of heart disease are fairly represented.

Step 5: Feature Engineering:-New features are engineered to capture medical risk factors more effectively. For example, patients are grouped into age categories, cholesterol levels are binned into risk ranges, and new exercise-related features are derived. These engineered features provide additional insights and improve model learning.

Step 6: Feature Encoding and Scaling:- Categorical variables are transformed into numerical format using one-hot encoding, and numerical values are standardized to ensure uniform scaling. This step ensures that all features contribute equally during model training.

Step 7: Train-Test Split:- The dataset is divided into training and testing sets to evaluate model generalization. Stratified splitting is applied to preserve class balance across both sets.

Step 8: Model Training:- Decision Tree Classifier (interpretable, tree-based model with depth tuning), K-Nearest Neighbors (KNN) with hyperparameter tuning using GridSearchCV, Logistic Regression using PyTorch to demonstrate a deep learning-based implementation.

Step 9: Model Evaluation:- Models are evaluated using accuracy, precision, recall, and F1 score. ROC-AUC curves are plotted to assess model discrimination ability, and confusion matrices are visualized to analyze correct vs. incorrect predictions.

Step 10: Comparative Analysis and Conclusion:- The results of all models are compared side by side to determine the strongest predictor. The analysis highlights trade-offs between accuracy, interpretability, and computational efficiency. Insights are then summarized for practical healthcare use, paving the way for future deployment.

Visualizations:
![image alt](https://github.com/OmPatil2806/CardioRisk-ML-Predicting-Heart-Disease-with-Machine-Learning/blob/main/1.png)
![image alt](https://github.com/OmPatil2806/CardioRisk-ML-Predicting-Heart-Disease-with-Machine-Learning/blob/main/2.png)
![image alt](https://github.com/OmPatil2806/CardioRisk-ML-Predicting-Heart-Disease-with-Machine-Learning/blob/main/3.png)
![image alt](https://github.com/OmPatil2806/CardioRisk-ML-Predicting-Heart-Disease-with-Machine-Learning/blob/main/4.png)
![image alt](https://github.com/OmPatil2806/CardioRisk-ML-Predicting-Heart-Disease-with-Machine-Learning/blob/main/5.png)
![image alt](https://github.com/OmPatil2806/CardioRisk-ML-Predicting-Heart-Disease-with-Machine-Learning/blob/main/6.png)
![image alt](https://github.com/OmPatil2806/CardioRisk-ML-Predicting-Heart-Disease-with-Machine-Learning/blob/main/7.png)
![image alt](https://github.com/OmPatil2806/CardioRisk-ML-Predicting-Heart-Disease-with-Machine-Learning/blob/main/8.png)
![image alt](https://github.com/OmPatil2806/CardioRisk-ML-Predicting-Heart-Disease-with-Machine-Learning/blob/main/9.png)
![image alt](https://github.com/OmPatil2806/CardioRisk-ML-Predicting-Heart-Disease-with-Machine-Learning/blob/main/10.png)
