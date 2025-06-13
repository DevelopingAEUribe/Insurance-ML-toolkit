# Insurance-ML-toolkit
# Sure Tomorrow Insurance ML Toolkit

A multi-part machine learning project designed to solve real-world problems for the Sure Tomorrow Insurance Company. This toolkit demonstrates the use of classification, regression, similarity search, and data obfuscation techniques to support key business functions like marketing, risk evaluation, and privacy protection.

##  Project Overview

Sure Tomorrow Insurance tasked us with evaluating whether machine learning could improve several aspects of their operations. This project implements and assesses four core tasks:

###  Task 1: Customer Similarity Search
Use k-nearest neighbors (kNN) to identify customers most similar to a given individual. This can assist marketing teams in designing more personalized outreach strategies.

###  Task 2: Binary Classification - Benefit Eligibility
Predict whether a customer will receive insurance benefits using kNN and compare it against a baseline random classifier. Performance is evaluated using F1 score and confusion matrices.

###  Task 3: Regression - Benefit Amount Prediction
Train a linear regression model to predict the number of benefits a customer may receive, based on features like age, income, and family size.

###  Task 4: Data Obfuscation (Privacy Protection)
Apply a data masking transformation (random matrix multiplication) to anonymize customer features while preserving the ability to make accurate predictions.

---

##  Project Structure

.
├── sure_tomorrow_ml_toolkit.ipynb # Main Jupyter Notebook
├── data/ # Input dataset (not included here for privacy)
└── README.md # Project description and instructions

yaml
Copy
Edit

---

##  Technologies Used

- Python 3.9+
- NumPy, Pandas
- Scikit-learn
- SciPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

##  Evaluation Metrics

- Classification: F1 Score, Confusion Matrix
- Regression: RMSE, R² Score
- Obfuscation: Model performance parity pre- and post-transformation

---

##  Results Summary

- **Similarity Search:** Accurately identified the 5 closest customers using Euclidean distance on selected features.
- **Classification:** kNN outperformed the dummy model, achieving a significantly higher F1 score on scaled data.
- **Regression:** Linear regression model demonstrated good predictive power for benefit counts.
- **Obfuscation:** Successfully masked sensitive data without reducing regression model accuracy.

---

##  Key Learnings

- Feature scaling significantly impacts kNN performance.
- Even simple baseline models are valuable for benchmarking.
- Linear models can offer both performance and interpretability.
- Data obfuscation can be achieved with minimal impact on model fidelity if done correctly.

---

##  License

This project is for educational purposes and is not licensed for commercial use.

---

##  Author

Adam Edwards-Uribe  

