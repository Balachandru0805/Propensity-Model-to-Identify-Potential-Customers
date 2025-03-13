
# Propensity Model to Identify Potential Customers

Propensity modeling is a method that aims to forecast the chance that individuals, leads, and customers will engage in specific actions. This method uses statistical analysis which takes into account all the independent and confounding factors that impact customer behavior. Suppose you are working for a company as a Data Scientist. Your company is commissioned by an insurance company to develop a tool to optimize their marketing efforts. This project is aimed at building a propensity model to identify potential customers.


## Data Source Information

- custAge - The age of the customer.
- prefession - Type of job.
- marital - Marital status.
- schooling - Education level.
- default - Has a previous defaulted account.
- housing - Has a housing loan.
- loan - Has a personl loan.
- contact - Preferred contact type.
- month - Last contact month
- day_of_week - Last contact day of the week.
- campaign - Number of times the customer was contacted.
- pdays - Number of days that passed after the client was last contacted.
- previous - Number of contacts performed before this campaign and for this client.
- poutcome - Outcome of the previous marketing campaign.
- emp.var.rate - Employment variation rate - quarterly indicater.
- cons.price.id - Consumer price index - monthly indicator.
- cons.conf.idx - Consumer confidence index - monthly indicator.
- euribor3m - Euribor 3 month rate - daily indicator.
- nr.employed - Number of employees - quarterly indicator.
- pmonths - Number of months that passed by after the client was last contacted from a previous campaign.
- pastEmail - Number of previous emails sent to this client.
- **responded (target variable)** - Did the customer respond to the campaign and purchase a policy.


## Python Modules Requirements

- pandas==2.2.3
- numpy==2.1.2
- matplotlib==3.10.0
- seaborn==0.13.2
- scipy==1.14.1
- sklearn-compat==0.1.3
- pickleshare==0.7.5

## Machine Learning Model Operations Performed
    1. Import Libraries
    2. Data Preparation
    - 2.1 - Understanding the Data
    - 2.2 - Exploratory Data Analysis
    - 2.3 - Data Cleaning
    - 2.4 - Encoding
    - 2.5 - Balancing the data
    - 2.6 - Feature Scaling
    3. Model Selection, Training & Validation
    - 3.1 - Naive Bayes Model
    - 3.2 - Random Forest Model
    - 3.3 - Support Vector Machine Classifier Model
    4. Hyper Parameter Tuning
    - 4.1 - SVM Model Hyper Parameter Tuning
    - 4.2 - Random Forest Model Hyper Parameter Tuning
    5. Model Deployment
    - 5.1 - Reading and undestanding the test data
    - 5.2 - Preprocessing the test data
    - 5.3 - Predicting the test data result
    6. Conclusion

## Machine Learning Models Applied

- Naive Bayes Classifier - 77% Accuracy
- Support Vector Machine - 87% Accuracy
- Random Forest Classifier - 88% Accuracy

## Conclusion
Completed the Exploratory data analysis, data preprocessing, balancing the data and applied various Machine Learning models of Naive Bayes (77% accuracy), Support Vector Machine (87% accuracy) and Random Forest Classifier (89% accuracy). Used the best Random Forest model to get the result of test dataset.


## 🛠 Skills
Python, EDA, Machine Learning...

