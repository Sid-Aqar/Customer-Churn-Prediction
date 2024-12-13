 # Customer-Churn-Prediction

 ## Problem Statement
 Predicting customer churn is critical for businesses to reduce attrition rates and improve customer retention.

 ## Dataset
 -**Source**: [Kaggle Customer Churn](https://www.kaggle.com/competitions)
 -**Description**: Contains customer demographics, services subscribed to, and churn labels.

 ## Project Workflow
 1. **Exploratory Data Analysis (EDA)**:
    - Visualized trends in customer demographics and services.
    - Identified correlations between features and churn.
 2. **Modeling**:
    - Compared Logistic Regression and Random Forest models.
    - Fine-turned Random Forest using GridSearchCV for optimal performance.
 3. **Evaluation**:
    - **Best Model**: Random Forest
    - **Metrics**:
    - Accuracy: 81%
    - Precision: 69%
    - Recall: 51%
    - F1 Score: 59%
    - ROC-AUC Score: 86%

 ## Key Insights
 - Top contributing features:
   `<Feature 1>`, `<Feature 2>`, etc.
   - Random Forest outperformed Logistic Regression in ROC-AUC and F1 Score.

 ## Visualization
 - **Confusion Matrix**: Shows model performance in predicting churn.
 - **ROC Curve**: Hightlights the model's ability to distinguish between classes.
 - **Feature Importance**: Provides insights into key predictors of churn.

   ## Conclusion
   The Random Forest model is effective in predicting customer churn, with strong performance metrics and actionable insights.

   ## How to Run
   1. Clone this respository
   2. Install dependencies: `pip install -r requirements.txt`.
   3. Run the notebook: `churn_prediction.ipynb`.

      -----
