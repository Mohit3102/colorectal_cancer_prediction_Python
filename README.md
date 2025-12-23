# 🧬 Colorectal Cancer Risk & Survival Prediction (Python)

## 📌 Project Overview
This project focuses on predicting the **survival status of colorectal cancer patients** using demographic, medical, and lifestyle-related features. The project applies **Exploratory Data Analysis (EDA)**, **data preprocessing**, and **machine learning (Logistic Regression)** to analyze healthcare data and build a predictive model.

This end-to-end project demonstrates practical **data analyst skills** using Python in a real-world healthcare context.

## 🎯 Objective
To develop a classification model that predicts whether a colorectal cancer patient **survived or not**, based on available patient attributes.

## 📂 Dataset Overview
- The dataset contains patient-level records related to:
  - Demographics
  - Medical history
  - Lifestyle factors
  - Treatment outcomes
- **Target Variable**:
  - `Survival_Status`
    - `0` → Did not survive
    - `1` → Survived
    - 
## 🛠️ Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Project Workflow

### 1️⃣ Data Exploration
- Loaded dataset using Pandas
- Examined dataset shape, column names, and data types
- Generated summary statistics for numerical features
- Identified missing values across columns
- 
### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed missing value counts and percentages
- Visualized survival status distribution
- Explored relationships between numerical variables
- Created a correlation heatmap to identify important feature relationships

### 3️⃣ Data Preprocessing
- Removed unnecessary columns (e.g., `Patient_ID`)
- Encoded categorical variables using one-hot encoding
- Defined features (`X`) and target variable (`y`)
- Prepared clean, model-ready data
  
### 4️⃣ Train-Test Split
- Split data into training and testing sets (80/20)
- Applied stratified sampling to maintain class balance
- Ensured reproducibility using a fixed random state
   
### 5️⃣ Model Training
- Trained a **Logistic Regression** classification model
- Adjusted model parameters for proper convergence
- Generated predictions on test data

### 6️⃣ Model Evaluation
- Evaluated model performance using:
  - Accuracy score
  - Classification report (precision, recall, F1-score)
  - Confusion matrix
- Ensured reliable evaluation by handling zero-division cases

## 📈 Key Results
- Successfully built a survival prediction model
- Identified important numerical and categorical predictors
- Demonstrated an end-to-end healthcare data analytics pipeline

## 💡 Business / Healthcare Impact
- Supports early identification of high-risk patients
- Assists in data-driven clinical decision-making
- Demonstrates how analytics can enhance healthcare outcomes

## 🧠 Skills Demonstrated
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Logistic Regression
- Model Evaluation
- Healthcare Data Analytics
  
## 🚀 Future Enhancements
- Missing value imputation
- Feature scaling
- Advanced models (Random Forest, XGBoost)
- Feature importance analysis
- Hyperparameter tuning

## 👨‍💻 Author
**Mohit Padhiyar**  
Aspiring Data Analyst  
Python | SQL | Power BI | Excel
