# Telco Customer Churn

![Telco](/images/telco.png)

# Business Problem

It is expected to develop a machine learning model that can predict customers who will leave the company.

# Dataset Info

21 Feature, 7043 Sample

| Feature | Definition |
| --- | --- |
| customerID | Customer ID |
| gender | Whether the customer is a male or a female |
| SeniorCitizen | Whether the customer is a senior citizen or not (1, 0) |
| Partner | Whether the customer has a partner or not (Yes, No) |
| Dependents | Whether the customer has dependents or not (Yes, No) |
| tenure | Number of months the customer has stayed with the company |
| PhoneService | Whether the customer has a phone service or not (Yes, No) |
| MultipleLines | Whether the customer has multiple lines or not (Yes, No, No phone service) |
| InternetService | Customer’s internet service provider (DSL, Fiber optic, No) |
| OnlineSecurity | Whether the customer has online security or not (Yes, No, No internet service)|
| OnlineBackup | Whether the customer has online backup or not (Yes, No, No internet service) |
| DeviceProtection | Whether the customer has device protection or not (Yes, No, No internet service) |
| TechSupport | Whether the customer has tech support or not (Yes, No, No internet service) |
| StreamingTV | Whether the customer has streaming TV or not (Yes, No, No internet service) |
| StreamingMovies | Whether the customer has streaming movies or not (Yes, No, No internet service) |
| Contract | The contract term of the customer (Month-to-month, One year, Two year) |
| PaperlessBilling | Whether the customer has paperless billing or not (Yes, No)|
| PaymentMethod | The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)) |
| MonthlyCharges | The amount charged to the customer monthly |
| TotalCharges | The total amount charged to the customer |
| Churn | Whether the customer churned or not (Yes or No) |

# Requirements

```python
catboost==1.0.6
lightgbm==3.1.1
matplotlib==3.5.2
numpy==1.21.5
pandas==1.4.3
scikit_learn==1.1.2
seaborn==0.11.2
xgboost==1.5.0
```

# **Files**

*[telco.ipynb](https://github.com/oguzerdo/telco-churn-prediction-ml/blob/main/telco.ipynb) -* Telco Customer Churn Prediction Notebook

# Author

[Oğuz Erdoğan](http://www.oguzerdogan.com)