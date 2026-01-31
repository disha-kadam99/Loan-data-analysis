# Loan-data-analysis
# Loan Approval Prediction Project

## Project Overview
This project predicts whether a loan will be approved or rejected based on applicant information.  
It uses **Machine Learning** techniques with Python, Pandas, and Scikit-learn to create a predictive model.  

---

## Dataset
- Dataset Name: `loan_prediction.csv`
- Source: Kaggle / College dataset
- Columns include:
  - Gender
  - Married
  - Dependents
  - Education
  - Self_Employed
  - ApplicantIncome
  - CoapplicantIncome
  - LoanAmount
  - Loan_Amount_Term
  - Credit_History
  - Property_Area
  - Loan_Status (Target Column)

---

## Project Steps

1. **Data Loading**  
   Loaded dataset using Pandas and checked first few rows.
   
2. **Exploratory Data Analysis (EDA)**  
   - Count plots for Loan Status, Education, and Credit History  
   - Distribution plots for Applicant Income  
   - Correlation heatmap to analyze feature relationships

3. **Data Cleaning**  
   - Filled missing numerical values with **median**  
   - Filled missing categorical values with **mode**

4. **Encoding Categorical Data**  
   - Used `LabelEncoder` to convert categorical text into numerical values

5. **Feature & Target Split**  
   - Features (`X`) = All columns except `Loan_Status`  
   - Target (`y`) = `Loan_Status`

6. **Train-Test Split**  
   - Split data into 80% training and 20% testing sets

7. **Model Training**  
   - Random Forest Classifier used for prediction  
   - Model trained on training set

8. **Prediction & Evaluation**  
   - Predicted loan approval on test set  
   - Accuracy score calculated to measure performance

---

## Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn

---

## Results
- Graphs show patterns such as:
  - Strong credit history increases chances of loan approval  
  - Education level also affects loan approval  
- Model Accuracy: **[Add your accuracy here, e.g., 85%]**

---

## Conclusion
- The project successfully predicts loan approval status using historical data.  
- It can help banks make faster, data-driven decisions.  
- Random Forest model performed best among tested models.

---

## How to Run
1. Upload `loan_prediction.csv` to your local or Colab environment  
2. Run the notebook sequentially line-by-line  
3. Graphs and accuracy will display after running all cells

---

## Author
**Disha Kadam**  
College / Intern Project
