# 🚢 Titanic: Machine Learning from Disaster  

## 📌 Project Overview  
This project focuses on **predicting passenger survival on the Titanic** using machine learning techniques.  

- 🔍 **Comprehensive Data Exploration** – analyzing missing values, statistical summaries, and visual patterns  
- 🛠 **Feature Engineering** – creating meaningful features and handling categorical/numerical data  
- 🤖 **Predictive Modeling** – training a logistic regression model with cross-validation for reliability  
- 🎯 **Goal** – identify key survival factors (e.g., gender, class, age) and build an accurate classification model  


# Titanic Survival Prediction Project

## 📊 Dataset
[![Titanic Survivorship Dataset](https://img.youtube.com/vi/HippD992DCE/0.jpg)](https://youtu.be/HippD992DCE)

🎥 [Titanic Survivorship Dataset](https://youtu.be/HippD992DCE) 🎥

The Titanic dataset from Kaggle contains information about 891 passengers, with the following features:

- **PassengerId**: Unique identifier for each passenger  
- **Survived**: Survival status (0 = No, 1 = Yes) - target variable  
- **Pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- **Name**: Passenger name  
- **Sex**: Gender of passenger  
- **Age**: Age in years  
- **SibSp**: Number of siblings/spouses aboard  
- **Parch**: Number of parents/children aboard  
- **Ticket**: Ticket number  
- **Fare**: Passenger fare  
- **Cabin**: Cabin number  
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  

---

## 🛠 Key Techniques Implemented

**Data Exploration & Visualization**
  
[![Titanic: Data Exploration & Visualization](https://img.youtube.com/vi/HZY-79KZX9c/0.jpg)](https://youtu.be/HZY-79KZX9c)

🎥 [Titanic: Data Exploration & Visualization](https://youtu.be/HZY-79KZX9c) 🎥  

  - Missing value analysis  
  - Statistical summary of features  
  - Correlation analysis between numerical features  
  - Distribution analysis of categorical variables  
  - Survival rates by passenger class and gender  
  - Visualization of survival patterns across different passenger groups  

---

**Feature Engineering & Data Preprocessing**
  
[![Titanic: Feature Engineering & Data Preprocessing](https://img.youtube.com/vi/QYsjfEf7KSk/0.jpg)](https://youtu.be/QYsjfEf7KSk)

🎥 [Titanic: Feature Engineering & Data Preprocessing](https://youtu.be/QYsjfEf7KSk) 🎥 

  - Creation of binary features (`is_female`, `is_child`)  
  - Missing value imputation (Age, Embarked, Fare)  
  - Categorical encoding using one-hot encoding  
  - Feature scaling with `StandardScaler`  

---

**Advanced Analysis with SQL Queries**
  
[![Titanic: SQL](https://img.youtube.com/vi/ueXbL8Zlmms/0.jpg)](https://youtu.be/ueXbL8Zlmms)

🎥 [Titanic: SQL](https://youtu.be/ueXbL8Zlmms) 🎥  

  - Survival statistics by demographic groups  
  - Age analysis of survivors  
  - Class and gender-based survival rate calculations  

---

**Model Training & Evaluation**
  
[![Titanic: Model Training & Evaluation](https://img.youtube.com/vi/1qdgQ7hrez8/0.jpg)](https://youtu.be/1qdgQ7hrez8)

🎥 [Titanic: Model Training & Evaluation](https://youtu.be/1qdgQ7hrez8) 🎥 

  - Train-test split with stratification  
  - Logistic Regression classifier  
  - Cross-validation using K-Fold (5-fold)  
  - Classification reports and confusion matrix  
  - Feature importance analysis  

---

**Visualization of Results**
  - Survival rates by sex and child status  
  - Overall survival distribution  
  - Confusion matrix heatmap  
  - Feature importance chart  

---

## 📈 Results
The Logistic Regression model achieves good accuracy in predicting passenger survival. Key findings include:

- Gender was the most significant predictor of survival, with females having a much higher survival rate  
- Passenger class strongly influenced survival chances  
- Children had better survival rates than adults  
- Feature engineering steps significantly contributed to model performance  
- Cross-validation demonstrates the model's stability and reliability  

---

## 📦 Requirements
- Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- pandasql (for SQL queries)  

---

## 🚀 How to Use
1. Clone this repository  
2. Ensure you have all required packages installed  
3. Open the Jupyter notebook `Titanic_Dataset.ipynb`  
4. Run the cells sequentially to see the analysis and results  

---

## 📂 File Structure
- `Titanic_Dataset.ipynb` - The main Jupyter notebook containing all analysis and code  
- `train.csv` - Training dataset with survival information  
- `test.csv` - Test dataset for making predictions  
- `gender_submission.csv` - Sample submission file  
- `titanic_predictions.csv` - Generated predictions file  
- `README.md` - This file with project information  

---

## 💡 Key Insights
- Feature engineering (especially binary features like `is_female` and `is_child`) significantly improves model performance  
- Demographic factors (gender, passenger class) were more important predictors than numeric variables like fare  
- The standard logistic regression model performs well for this classification task  
- The confusion matrix reveals strong performance in predicting both survival and non-survival cases  
- The model outperforms the baseline gender-based prediction approach  
