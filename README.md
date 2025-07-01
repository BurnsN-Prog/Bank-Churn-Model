# Bank-Churn-Model

## Bank Customer Churn Prediction

### Project Aim  
Analyze customer banking data and past behavior to predict which customers are likely to churn, using classification models and handling class imbalance.

---

### Tools Used  
- Python  
- pandas, NumPy  
- scikit-learn (Random Forest, metrics, upsampling)  
- matplotlib, seaborn

---

### Results  
- **Class Imbalance Addressed:** Used upsampling to balance positive (churn) class  
- **Model:** Random Forest (n=70, depth=17) 
  - F1 Score (Test): **0.616**  
  - AUC-ROC Score: **0.860**  
- **Model met and exceeded** the project’s target F1-score of 0.59  
- **Upsampling factor of 3** outperformed a factor of 4, which led to overcompensation

Final model demonstrated strong classification and ranking performance, making it reliable for predicting customer churn.

