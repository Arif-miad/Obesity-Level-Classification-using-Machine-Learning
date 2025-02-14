# Obesity Level Classification using Machine Learning

## 📌 Overview
This project aims to predict obesity levels in individuals from **Mexico, Peru, and Colombia** based on their eating habits and physical conditions. The dataset consists of **2111 records** with **17 attributes**, including details like BMI, family history, eating habits, physical activity, and transportation mode.

## 📊 Dataset Features
- **Gender:** Male/Female
- **Age, Height, Weight:** Physical attributes
- **Eating Habits:** Frequency of high-caloric food, vegetable intake, water consumption, snacking behavior
- **Lifestyle Factors:** Smoking, alcohol consumption, exercise frequency, screen time, transportation mode
- **Target Variable:** **Obesity Level** (7 categories: Insufficient Weight, Normal Weight, Overweight I & II, Obesity I, II & III)

---
## 🚀 Project Workflow

### **1️⃣ Exploratory Data Analysis (EDA)**
- **Univariate Analysis:** Distribution of numerical & categorical features
- **Bivariate Analysis:** Relationship between variables using scatterplots, box plots, and bar plots
- **Correlation Analysis:** Heatmaps to identify feature relationships
- **Outlier Detection:** Identifying extreme values in numerical features

### **2️⃣ Data Preprocessing & Feature Engineering**
- Encoding categorical variables using **Label Encoding**
- Feature creation: **Body Mass Index (BMI)**
- Train-test split (80-20 ratio)
- Scaling numerical features using **StandardScaler**

### **3️⃣ Machine Learning Model Training (10 Models)**
We implemented and compared **10 classification models:**
- Logistic Regression
- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Naïve Bayes
- XGBoost
- LightGBM
- CatBoost

### **4️⃣ Model Evaluation & Performance Metrics**
Each model was evaluated using:
- **Accuracy, F1 Score, ROC-AUC Score**
- **Confusion Matrix for Misclassification Analysis**
- **Classification Report for Precision, Recall, F1-Score**
- **Feature Importance Analysis** for tree-based models

### **5️⃣ Model Comparison & Optimization**
- Performance comparison across models
- Hyperparameter tuning using **GridSearchCV & RandomizedSearchCV**

---
## 📌 Results & Insights
- **Best Performing Model:** Identified based on accuracy & ROC-AUC
- **Feature Importance:** Key factors influencing obesity prediction
- **Impact of Lifestyle Factors:** Strong correlation with obesity levels

---
## 📂 Repository Structure
```
📦 Obesity_Level_Classification
├── 📁 data                 # Dataset & Preprocessed Files
├── 📁 notebooks            # Jupyter Notebooks for EDA & Modeling
├── 📁 models               # Trained Machine Learning Models
├── 📜 obesity_classification.py   # Main Code Implementation
├── 📜 README.md            # Project Documentation
```

---
## 📌 Kaggle Notebook & LinkedIn Profile
🔗 **Kaggle Notebook:** [Check it out here](https://www.kaggle.com/code/arifmia/predicting-obesity-levels-using-machine-learning)

🔗 **LinkedIn Profile:** [Connect with me](www.linkedin.com/in/arif-miah-8751bb217)

---
## 💡 Future Improvements
- **Deep Learning Approach:** Experimenting with Neural Networks
- **More Features:** Incorporating dietary habits, sleep patterns, and medical history
- **Deployment:** Creating a web-based prediction tool using Flask or Streamlit

### ⭐ **If you found this helpful, don't forget to star the repository!** ⭐

