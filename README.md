# ChurnModel-Using-DecisionTrees

##Project: Customer Churn Prediction Using Decision Trees

### **Business Objective**

XYZ is a subscription-based service company that offers one-year subscription plans to customers. The company wants to predict whether customers will renew their subscriptions for the upcoming year or not. Customer churn, in this context, refers to customers who choose not to renew their subscriptions.

### **Data Description**

The dataset contains information about a video streaming service company. It consists of approximately 2000 rows and 16 columns.

### **Aim**

The goal of this project is to build a decision tree model to determine whether a customer will churn or not.

## Approach

1. **Data Preparation:**
   - Import the necessary Python libraries.
   - Read the dataset containing customer information.

2. **Feature Engineering:**
   - Perform data preprocessing, including handling missing values.
   - Remove unnecessary columns that do not contribute to the prediction.

3. **Model Building:**
   - Build a decision tree model to predict customer churn.

4. **Data Splitting:**
   - Split the dataset into training and testing sets for model evaluation.

5. **Model Validation:**
   - Evaluate the decision tree model:
     - Calculate accuracy score to measure overall model performance.
     - Generate a confusion matrix to understand prediction outcomes.
     - Evaluate ROC and AUC for model discrimination capability.
     - Compute recall, precision, and F1-score to assess prediction quality.

6. **Feature Importance Analysis:**
   - Determine feature importance using the trained decision tree model.
   - Create a custom function to identify and rank important features.

7. **Visualization:**
   - Visualize feature importance to gain insights into the factors influencing customer churn.
