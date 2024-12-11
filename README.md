# Drug-safety-and-pharmacovigilance

## Project Overview
This project focuses on predicting the type of drug suitable for a patient based on their medical data. The goal is to use machine learning techniques to accurately predict drug types, ensuring safety and effectiveness for patients. The project provides insights into drug safety and pharmacovigilance by analyzing various features of the dataset and building a predictive model.

## Tools and Technologies Used
- **Programming Language**: Python
- **Technologies**: Data Analysis, Machine Learning
- **Tools**:
  - Python libraries: Pandas, NumPy, Seaborn, Matplotlib, scikit-learn
  - Excel for preliminary data exploration

## Dataset
The dataset includes the following features:
- **Target Feature**: Drug type
- **Feature Sets**:
  - Age
  - Sex
  - Blood Pressure Levels (BP)
  - Cholesterol Levels
  - Na-to-Potassium Ratio (Na_to_K)

## Approach
### Step 1: Data Collection and Loading
- Import the dataset using Python.
- Perform data integration and cleaning.

### Step 2: Exploratory Data Analysis (EDA)
- Analyze the distribution of features and the target variable.
- Visualize data trends and relationships using Matplotlib and Seaborn.

### Step 3: Data Preprocessing
- Handle categorical variables by encoding them.
- Standardize numerical features for consistency.
- Split the data into training and testing sets.

### Step 4: Model Development
- Build a predictive model using machine learning algorithms (e.g., Random Forest).
- Evaluate the model's performance using metrics like accuracy, confusion matrix, and classification report.

### Step 5: Model Deployment
- Save the trained model for future use.

## Results
- Achieved a high accuracy score using the Random Forest Classifier.
- Visualized feature importance, highlighting the key factors influencing drug prediction.
