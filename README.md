# -Student-Career-Success-Prediction-Dataset
 # 10. Conclusion 🏆💰🥇🥈🎖️🥉🥇

🎖️🏅🥉🥈🥇🏆💰The dataset had 50,000 student records with no missing values, making it clean and ready for modeling.
About 78% of students were placed and 22% were not, showing a moderate class imbalance.
We carefully removed leakage columns (like Company Tier, Salary, and Employability Score) that are only known after placement, ensuring the model learns from genuinely predictive, pre-outcome features.
Comparing three models, Random Forest performed best overall, reaching around 81% accuracy and ~0.80 ROC-AUC, with Logistic Regression and LightGBM offering slightly better recall on the "Not Placed" class at the cost of overall accuracy.
Interview Score, Resume Score, CGPA, and skill ratings (programming, communication, problem-solving) emerged as the biggest factors influencing placement outcomes.
Honest note: The ~0.80 ROC-AUC shows the model captures a solid pattern, but placement outcomes also depend on external factors (market demand, luck, company-specific criteria) that aren't captured in this dataset — so no model here is claimed to be "perfect."
Possible next steps: try SMOTE for balancing, hyperparameter tuning with GridSearchCV, or testing XGBoost/CatBoost for a possible further boost.
