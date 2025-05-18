
# Fraudulent Insurance Claim Detection

This project focuses on identifying fraudulent insurance claims using data science and machine learning techniques. The goal is to reduce financial losses by building a model that can detect likely frauds early and accurately.

## Objective

- Detect fraudulent claims using historical insurance data.
- Improve claim validation by supporting manual reviews with model predictions.
- Reduce company losses by catching frauds before payout.

## Project Workflow

1. **Data Cleaning**: Removed ID fields, handled missing values, and encoded categorical variables.
2. **EDA (Exploratory Data Analysis)**: Identified fraud patterns using visualizations and correlation analysis.
3. **Feature Engineering**: Created meaningful features such as claim ratios.
4. **Model Building**: Trained Logistic Regression and Random Forest classifiers.
5. **Evaluation**: Compared models using Accuracy, Precision, Recall, F1 Score, and ROC Curve.
6. **Insights and Recommendations**: Derived actionable steps for business application.

## Results

| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 82.2%    | 79.3%     | 76.5%  | 77.9%    |
| Random Forest       | 88.4%    | 86.9%     | 84.2%  | 85.5%    |

Random Forest was chosen for production due to its better overall performance.

## Visuals Included

- Class Balance Chart
- Correlation Heatmap
- Feature Distributions
- ROC Curve Comparison

## Files

- `Fraudulent_Claim_Detection_Starter.ipynb`: Full notebook with all steps and results.
- `insurance_claims.csv`: Source dataset.
- `Fraud_Claim_Report_Complete_Blue.docx`: Final report with visuals.
- `Fraud_Claim_Evaluation_Simple_Academic_PPT.pptx`: Academic-style presentation.

## Recommendations

- Deploy Random Forest model to flag high-risk claims.
- Manually review claims with high fraud scores.
- Regularly retrain the model with updated data.

## Assumptions

- Dataset is a representative sample of real claims.
- Rare categories were grouped, and high-cardinality identifiers were excluded.
- Some features were simplified or excluded to improve model performance.

---

This project is a demonstration of applying ML to real-world business problems, focusing on clarity, interpretability, and actionable results.
