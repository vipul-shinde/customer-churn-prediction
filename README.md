<h1 align="center">Customer Churn Prediction and Retention using ML.</h1>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)]()
  ![GitHub repo size](https://img.shields.io/github/repo-size/vipul-shinde/customer-churn-prediction)

</div>

---

<p align="center"> In this project, we are trying to predict the possibility of a customer churning by the end of next quater from a telecom company thus helping the company target and come up with offers for such customers.
    <br>
</p>

## 📝 Table of Contents

- [🧐 About](#about)
- [📊 Dataset Overview](#data-overview)
- [🧠 Model Building](#neural-network-model)
- [🏅 Model Evaluation](#model-evaluation)
- [🌟 Support](#support)

## 🧐 About <a name = "about"></a>

Customer churn, is when someone chooses to stop using your products or services. In effect, it’s when a customer ceases to be a customer.

Customer churn is measured using customer churn rate. That’s the number of people who stopped being customers during a set period of time, such as a year, a month, or a financial quarter.

In this project, we have build a machine learning model that'll help the telecom company predict if there is chance that given customer is going to churn after the current quater. 

## 📊 Dataset Overview <a name="data-overview"></a>

The dataset was downloaded from the <a href="https://community.ibm.com/accelerators/?context=analytics&query=telco%20churn&type=Data&product=Cognos%20Analytics">IBM Accelerator Catalog</a>. 

The Telco customer churn data contains information about a fictional telco company that provided home phone and Internet services to 7043 customers in California in Q3. It indicates which customers have left, stayed, or signed up for their service.

<details>
<summary>Click to check Dataset Attributes:</summary>
<br>

1. ```CustomerID```: A unique ID that identifies each customer.

2. ```Senior Citizen```: Indicates if the customer is 65 or older: Yes, No

3. ```Partner```: Indicates if the customer is married: Yes, No

4. ```Dependents```: Indicates if the customer lives with any dependents: Yes, No. Dependents could be children, parents, grandparents, etc.

5. ```Tenure in Months```: Indicates the total amount of months that the customer has been with the company by the end of the quarter specified above.

6. ```Phone Service```: Indicates if the customer subscribes to home phone service with the company: Yes, No

7. ```Multiple Lines```: Indicates if the customer subscribes to multiple telephone lines with the company: Yes, No

8. ```Internet Service```: Indicates if the customer subscribes to Internet service with the company: No, DSL, Fiber Optic, Cable.

9. ```Online Security```: Indicates if the customer subscribes to an additional online security service provided by the company: Yes, No

10. ```Online Backup```: Indicates if the customer subscribes to an additional online backup service provided by the company: Yes, No

11. ```Device Protection Plan```: Indicates if the customer subscribes to an additional device protection plan for their Internet equipment provided by the company: Yes, No

12. ```Tech Support```: Indicates if the customer subscribes to an additional technical support plan from the company with reduced wait times: Yes, No

13. ```Streaming TV```: Indicates if the customer uses their Internet service to stream television programing from a third party provider: Yes, No. The company does not charge an additional fee for this service.

14. ```Streaming Movies```: Indicates if the customer uses their Internet service to stream movies from a third party provider: Yes, No. The company does not charge an additional fee for this service.

15. ```Contract```: Indicates the customer’s current contract type: Month-to-Month, One Year, Two Year.

16. ```Paperless Billing```: Indicates if the customer has chosen paperless billing: Yes, No

17. ```Payment Method```: Indicates how the customer pays their bill: Bank Withdrawal, Credit Card, Mailed Check

18. ```Monthly Charge```: Indicates the customer’s current total monthly charge for all their services from the company.

19. ```Total Charges```: Indicates the customer’s total charges, calculated to the end of the quarter specified above.

20. ```Churn Label```: Yes = the customer left the company this quarter. No = the customer remained with the company. Directly related to Churn Value.
</details>

### Click to view 👇:

[![forthebadge](figures/badges/solution-exploratory-data-analysis.svg)](https://github.com/vipul-shinde/customer-churn-prediction/blob/main/notebooks/01-eda-and-data-cleaning.ipynb)

```P.S: The notebook is still in works```

## 🧠 Model Building <a name="neural-network-model">

We implemented the following machine learning models for predicting the chances that a given customer will churn. 

1. Logistic Regression
2. Random Forest Classifier
3. K Nearest Neigbors Classifier
4. Extreme Gradient Boosting Classifier

A Grid Search approach was used to fine tune the hyperparameters of RF, KNN and XGB classifiers after setting a baseline with the Logistic Regression model.

### Click to view 👇:

[![forthebadge](figures/badges/solution-exploratory-data-analysis.svg)](https://github.com/vipul-shinde/customer-churn-prediction/blob/main/notebooks/02-model-building-and-evaluation.ipynb)

## 🏅 Model Evaluation <a name="model-evaluation"

## 🌟 Support <a name="support">

Please hit the ⭐button if you like this project. 😄

# Thank you!