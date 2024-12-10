# customer_churn_predict_101
# **Customer Churn Prediction**

This project involves building a machine learning model to predict customer churn for a subscription-based service. The goal is to predict whether a customer will churn (leave the service) or stay based on their demographic and service usage data.

## **Project Overview**

Customer churn is a critical problem for businesses, especially in the subscription-based service industry. By predicting churn, companies can take proactive measures to retain customers, reducing the cost of acquiring new customers. This project uses machine learning algorithms to predict whether a customer will churn based on factors such as contract type, monthly charges, and service usage.

### **Features:**
- **Gender**: Customer's gender
- **SeniorCitizen**: Whether the customer is a senior citizen
- **Partner**: Whether the customer has a partner
- **Dependents**: Whether the customer has dependents
- **Tenure**: The number of months the customer has been with the service
- **PhoneService**: Whether the customer has phone service
- **MultipleLines**: Whether the customer has multiple phone lines
- **InternetService**: The type of internet service the customer uses
- **OnlineSecurity**: Whether the customer has online security
- **OnlineBackup**: Whether the customer has online backup
- **DeviceProtection**: Whether the customer has device protection
- **TechSupport**: Whether the customer has tech support
- **StreamingTV**: Whether the customer has streaming TV service
- **StreamingMovies**: Whether the customer has streaming movies service
- **Contract**: The type of contract the customer has
- **PaperlessBilling**: Whether the customer uses paperless billing
- **PaymentMethod**: The method the customer uses for payment
- **MonthlyCharges**: The customer's monthly charges
- **TotalCharges**: The total charges the customer has accumulated

### **Objective:**
The main objective is to predict whether a customer will churn based on these features. We train a machine learning model using historical customer data, and the model predicts if a new customer will churn or stay. The model uses algorithms like Logistic Regression, Decision Trees, or Random Forest for the classification task.

## **How the Project Works**

1. **Data Preprocessing**: 
   - Categorical features are encoded using saved encoders to transform them into a format suitable for the machine learning model.
   - Data is split into training and testing sets.

2. **Model Training**:
   - A machine learning model (Random Forest Classifier) is trained on the data to predict whether a customer will churn.
   
3. **Prediction**:
   - After training, the model can be used to predict whether a new customer will churn based on their data.
   - The prediction includes both the churn/no-churn result and the probability of churn.

4. **Evaluation**:
   - The model's performance is evaluated using accuracy, confusion matrix, and classification report, which provide insight into its ability to predict churn accurately.


