# Customer Churn Prediction 2020 Competition (96% Accuracy)
This competition was about predicting whether a customer will change telecommunications provider, something known as "churning". My Machine Learning model was 96.3% accurate in predicting the customer churn. I have followed the complete lifecycle of data science project - Data Collection(from kaggle), Exploratory Data Analysis, Feature Engineering, Model Building, Hyperparameter Tuning and Model Evaluation.

Notebooks - 
<a href='https://bit.ly/2LSJVy1' target='blank'>Churn Prediction using Machine Learning</a>

The training dataset contains 4250 samples. Each sample contains 19 features and 1 boolean variable "churn" which indicates the class of the sample. The 19 input features and 1 target variable are:

1) "state", string. 2-letter code of the US state of customer residence <br>
2) "account_length", numerical. Number of months the customer has been with the current telco provider <br>
3) "area_code", string="area_code_AAA" where AAA = 3 digit area code.<br>
4) "international_plan", (yes/no). The customer has international plan.<br>
5) "voice_mail_plan", (yes/no). The customer has voice mail plan.<br>
6) "number_vmail_messages", numerical. Number of voice-mail messages.<br>
7) "total_day_minutes", numerical. Total minutes of day calls.<br>
8) "total_day_calls", numerical. Total minutes of day calls.<br>
9) "total_day_charge", numerical. Total charge of day calls.<br>
10) "total_eve_minutes", numerical. Total minutes of evening calls.<br>
11) "total_eve_calls", numerical. Total number of evening calls.<br>
12) "total_eve_charge", numerical. Total charge of evening calls.<br>
13) "total_night_minutes", numerical. Total minutes of night calls.<br>
14) "total_night_calls", numerical. Total number of night calls.<br>
15) "total_night_charge", numerical. Total charge of night calls.<br>
16) "total_intl_minutes", numerical. Total minutes of international calls.<br>
17) "total_intl_calls", numerical. Total number of international calls.<br>
18) "total_intl_charge", numerical. Total charge of international calls<br>
19) "number_customer_service_calls", numerical. Number of calls to customer service<br>
20) "churn", (yes/no). Customer churn - target variable.
