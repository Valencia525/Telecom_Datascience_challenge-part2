# 📊 Customer Churn Prediction in Telecommunications  

## 🎯 Project Objective  
The purpose of this project is to predict customer churn in a telecommunications company.  

The analysis focuses on:  
- Identifying behavioral patterns of customers who cancel their service.  
- Evaluating the most influential variables in churn prediction.  
- Training and comparing machine learning models to determine the most effective one.  

## 🛠️ Tools and Libraries Used  
This project was developed using the following tools and libraries:  

- **Language:** Python 3  
- **Main Libraries:**  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  
  - Imbalanced-learn  

- **Recommended Environments:** Google Colab or Jupyter Notebook  
- **Development Assistance:** ChatGPT (OpenAI), used to support structuring, explanation, and optimization of the project.  

## 📂 Project Structure  
1. **Data Exploration & Preparation**  
   - Data Cleaning and Extraction  
   - Removal of Irrelevant Columns  
   - Encoding  
   - Churn Rate Verification  
   - Data Balancing  
   - Normalization / Standardization  

2. **Correlation & Feature Selection**  
   - Correlation Analysis  
   - Directed Feature Analysis  

3. **Predictive Modeling**  
   - Data Splitting  
   - Model Creation  
   - Model Evaluation  

4. **Interpretation & Conclusions**  
   - Feature Importance Analysis  
   - Final Insights and Conclusion  

## 📈 Key Results  
- Both models showed **competitive performance**, with a reasonable balance between **precision** and **recall**.  
- The most important features for predicting churn were:  
  - **Contract type**  
  - **Additional services** (e.g., fiber optic, streaming)  
  - **Total charges**  
- The use of **SMOTE** improved recall compared to models trained on imbalanced data.  

## 🤝 Acknowledgments  
This project was developed with the support of **ChatGPT (OpenAI)**, which contributed by:  
- Explaining technical concepts.  
- Assisting in code development.  
- Reviewing metrics and results.  

## 🚀 Next Steps  
- Test additional metrics such as **ROC-AUC** and **PR-AUC**.  
- Evaluate distance-based models like **KNN** (with standardization applied).  
- Implement hyperparameter tuning with **GridSearchCV** or **RandomizedSearchCV**.  
