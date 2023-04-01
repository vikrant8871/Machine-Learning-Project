# Machine-Learning-Project
## Supervised Learning Capstone Project

### Tree Methods Focus - ON Telecome and Internet Providing Company

Task we will Perform in this Data set~

1. Exploratory Data Analysis
2. Cohort Analysis
3. Imbalance class Analysis (SMOTE METHOD USED)
4. Predictive Classification Models

Telecom Service churn rates prediction project involved developing prediction model using Machine learning algorithms. Such as logistic regression, decision tree and Random forest. Telecom service churn rate prediction refers to the process of using statistical and machine learning techniques to predict the likelihood of customers leaving a telecom service provider for a competitor or another alternative.
Churn rate is an important metric for telecom service providers as it directly impacts their revenue and profitability. By predicting which customers are most likely to churn, providers can take proactive measures to retain them, such as offering personalized incentives or improving their service offerings.
To predict churn rate, historical customer data is collected and analyzed to identify patterns and trends that may indicate which customers are more likely to leave. This data typically includes information such as customer demographics, usage patterns, billing information, and customer service interactions.

![tt](https://user-images.githubusercontent.com/123053722/229271618-65f865e7-bd57-488c-be6c-39f278172d15.JPG)

# Dataset

 The dataset used for this project contains the following colums:
 
customerID: A unique identifier for each customer.

gender: The gender of the customer.

SeniorCitizen: A binary variable indicating whether the customer is a senior citizen (typically defined as 65 or older).

Partner: A binary variable indicating whether the customer has a partner (e.g., spouse or significant other).

Dependents: A binary variable indicating whether the customer has any dependents (e.g., children or other family members).

tenure: The number of months the customer has been with the telecom service provider.

PhoneService: A binary variable indicating whether the customer has a phone service subscription.

MultipleLines: A categorical variable indicating whether the customer has multiple phone lines.

InternetService: A categorical variable indicating the type of internet service the customer has (e.g., DSL, fiber optic, or no internet service).

OnlineSecurity: A categorical variable indicating whether the customer has online security services.

OnlineBackup: A categorical variable indicating whether the customer has online backup services.

DeviceProtection: A categorical variable indicating whether the customer has device protection services.

TechSupport: A categorical variable indicating whether the customer has tech support services.

StreamingTV: A categorical variable indicating whether the customer has streaming TV services.

StreamingMovies: A categorical variable indicating whether the customer has streaming movie services.

Contract: A categorical variable indicating the type of contract the customer has (e.g., month-to-month, one year, or two year).

PaperlessBilling: A binary variable indicating whether the customer has opted for paperless billing.

PaymentMethod: A categorical variable indicating the customer's preferred payment method.

MonthlyCharges: The customer's monthly charges for telecom services.

TotalCharges: The total charges for telecom services incurred by the customer over their tenure.

Churn: A binary variable indicating whether the customer has churned (i.e., left the telecom service provider).

# 1. Exploratory Data Analysis

In the EDA process, data cleaning involves removing duplicate entries, missing values, and outliers that may skew the analysis. Descriptive statistics such as mean, median, mode, standard deviation, and histograms are used for univariate analysis to examine the distribution and frequency of each variable. Bivariate analysis involves visualization techniques such as scatter plots, box plots, and heat maps to examine the relationship between predictor variables and the response variable. Multivariate analysis involves visualization techniques such as scatter matrices and correlation matrices to examine the relationship between multiple predictor variables and the response variable.

![jj](https://user-images.githubusercontent.com/123053722/229272867-70e791c8-e7d8-4a8d-9d48-7f0e8160efa2.JPG)

Feature engineering involves identifying new features that can be derived from existing variables or external data sources that may improve the predictive power of the model. Variable selection involves identifying the most important predictor variables for the model using techniques such as correlation analysis and feature importance.
Finally, the insights gained from the EDA process are used to build and evaluate the predictive model using appropriate machine learning algorithms. Overall, the EDA process provides valuable insights into the telecom service churn rate data and helps to identify trends and relationships that may be useful for predicting customer churn and improving the overall performance of the model.

# 2. Cohort Analysis

Cohort analysis can provide valuable insights into customer behavior over time, allowing companies to identify trends and patterns that may be useful in predicting churn and improving customer retention. By understanding the behavior of different customer cohorts, companies can tailor their marketing and retention strategies to improve customer satisfaction and reduce churn.


![kk](https://user-images.githubusercontent.com/123053722/229273276-84d51f96-e395-4a04-9543-29fb0ed15b45.JPG)

# 3. Imbalance class Analysis (SMOTE METHOD USED)

Imbalanced class analysis is an important step in modeling churn rate in the telecom industry. This is because the occurrence of churn is often rare, leading to an imbalanced class distribution between churn and non-churn customers in the dataset. Imbalance class analysis involves identifying the imbalance and applying methods to handle it.
One method to handle imbalance is the SMOTE (Synthetic Minority Over-sampling Technique) method. SMOTE works by generating synthetic minority class samples by creating new data points based on the existing minority class data. The algorithm identifies the minority class data points that are closest to each other and generates new data points along the line segments that connect them.


![ll](https://user-images.githubusercontent.com/123053722/229273565-37a52f86-7fe1-4353-9aa2-7c18fda096e0.JPG)


The SMOTE method helps to balance the class distribution, which in turn improves the accuracy of the predictive model. It also reduces the risk of overfitting that can occur when the model is trained on a highly imbalanced dataset.

# 4. Predictive Classification Models

In the context of telecom service churn rate prediction, various machine learning classification models can be applied to predict customer churn. These models aim to identify the factors that contribute to customer churn and to build a predictive model that can accurately identify customers who are likely to churn.
One commonly used model is logistic regression. This is a simple yet powerful algorithm that models the probability of a customer churning based on the input variables. Logistic regression is a linear algorithm that can handle both categorical and continuous variables, making it a suitable choice for predicting churn.
Another popular classification algorithm is Random Forest, which is an ensemble-based algorithm that combines multiple decision trees to create a robust predictive model. Random Forest is known for its ability to handle high-dimensional datasets with a large number of input variables, making it a suitable choice for predicting churn.

## Results

![rr](https://user-images.githubusercontent.com/123053722/229273991-6eeea7a3-57f0-415f-b1a9-89d982012c04.JPG)

The choice of the machine learning classification model depends on various factors such as the size and complexity of the dataset, the number of input variables, and the desired level of accuracy. By comparing the performance of different models using evaluation metrics such as accuracy, precision, recall, and F1-score, the best model can be selected for predicting telecom service churn rate.



