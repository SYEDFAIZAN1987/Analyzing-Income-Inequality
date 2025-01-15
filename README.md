# 📊 Analyzing Income Inequality Using K-Nearest Neighbors (KNN)

![Income Inequality](https://github.com/SYEDFAIZAN1987/Analyzing-Income-Inequality/blob/main/pic%201%20inequality.png)

## 📘 About the Project

This project explores income classification among U.S. citizens using census data, leveraging the **K-Nearest Neighbors (KNN)** algorithm. The analysis focuses on understanding how various demographic and occupational attributes—such as education, occupation, gender, and race—contribute to income disparities. The ultimate goal is to identify significant predictors of income inequality and provide insights for policy recommendations aimed at addressing economic disparities.

---

## 🔑 Key Features

1. **Data Preprocessing**:
   - Addressed missing values with mode imputation for categorical features.
   - Standardized numerical variables for improved performance with KNN.
   - Encoded categorical variables for compatibility with the model.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized the relationships between demographic features and income levels.
   - Analyzed distributions and correlations for key variables like age, education, and work hours.

3. **K-Nearest Neighbors Classifier**:
   - Initial model with default parameters achieved 81% accuracy.
   - Hyperparameter tuning identified **k=24** as the optimal value for balancing bias and variance.

4. **Evaluation Metrics**:
   - Confusion matrix, precision, recall, F1-score, and ROC curves for detailed model evaluation.
   - Improved AUC from 0.79 (initial model) to 0.84 (optimized model).

5. **Business Impact**:
   - Identified critical factors like **education**, **marital status**, and **capital gain** influencing income levels.
   - Provided actionable recommendations for targeting income inequality in policy planning.

---

## 📊 Key Insights

- **Significant Predictors**:
  - **Education Level**: Higher education correlates strongly with higher income.
  - **Marital Status**: Married individuals, particularly in traditional unions, have higher income probabilities.
  - **Capital Gain**: High capital gains are concentrated among higher-income groups.

- **Model Performance**:
  - **Initial Model**: Accuracy of 81%, AUC of 0.79.
  - **Optimized Model (k=24)**: Accuracy improved to 82%, AUC increased to 0.84.

- **Recommendations**:
  - Enhance access to higher education as it significantly impacts income levels.
  - Encourage policies supporting capital investment opportunities for middle-income earners.

---

## 📜 Full Report

For a detailed analysis, including methodology, visualizations, and results, refer to the complete project report:  
[📄 Analyzing Income Inequality Report](https://github.com/SYEDFAIZAN1987/Analyzing-Income-Inequality/blob/main/Analyzing%20Income%20Inequality.pdf)

---

## 📂 Project Structure

```
.
├── Data/
│   ├── adult.csv
├── Scripts/
│   ├── Analyzing_Income_Inequality.py
├── Reports/
│   ├── Analyzing_Income_Inequality.pdf
├── README.md
```
## 🤝 Connect with Me

Feel free to reach out for feedback, questions, or collaboration opportunities:  
**LinkedIn**: [Dr. Syed Faizan](https://www.linkedin.com/in/drsyedfaizanmd/)

---

**Author**: Syed Faizan  
**Master’s Student in Data Analytics and Machine Learning**
