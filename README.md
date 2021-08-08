# Credit Card Approval Prediction

The dataset chosen for this study has been picked up from Kaggle as below:
https://www.kaggle.com/rikdifos/credit-card-approval-prediction
This is the dataset for predicting the credit card approval status which is in line with the research being carried out for prediction of loan approval status for the applicants. This dataset consists of two csv files such as:
application_record.csv
credit_record.csv

Below is the list of features available in application_record.csv data file along with their description: application_record.csv Feature name Explanation Remarks
ID - Client number
CODE_GENDER - Gender
FLAG_OWN_CAR - Is there a car
FLAG_OWN_REALTY - Is there a property
CNT_CHILDREN - Number of children
AMT_INCOME_TOTAL - Annual income
NAME_INCOME_TYPE - Income category
NAME_EDUCATION_TYPE - Education level
NAME_FAMILY_STATUS - Marital status
NAME_HOUSING_TYPE - Way of living
DAYS_BIRTH - Birthday. Count backwards from current day (0), -1 means yesterday
DAYS_EMPLOYED - Start date of employment. Count backwards from current day (0). If positive, it means the person currently unemployed.
FLAG_MOBIL - Is there a mobile phone
FLAG_WORK_PHONE - Is there a work phone
FLAG_PHONE - Is there a phone
FLAG_EMAIL - Is there an email
OCCUPATION_TYPE - Occupation
CNT_FAM_MEMBERS - Family size

Below is the list of features available in credit_record.csv data file along with their description:
ID - Client number 
MONTHS_BALANCE - Record month. The month of the extracted data is the starting point, backwards, 0 is the current month, -1 is the previous month, and so on 
STATUS - Status 0: 1-29 days past due 1: 30-59 days past due 2: 60-89 days overdue 3: 90-119 days overdue 4: 120-149 days overdue 5: Overdue or bad debts, write-offs for more than 150 days C: paid off that month X: No loan for the month

application_record.csv file has total 438,557 rows and 18 features. It has below numeric fields:
ID
CNT_CHILDREN
AMT_INCOME_TOTAL
DAYS_BIRTH
DAYS_EMPLOYED
FLAG_MOBIL (boolean – 0 or 1)
FLAG_WORK_PHONE (boolean – 0 or 1)
FLAG_PHONE (boolean – 0 or 1)
FLAG_EMAIL (boolean – 0 or 1)
CNT_FAM_MEMBERS

It has below categorical features:
CODE_GENDER
FLAG_OWN_CAR
FLAG_OWN_REALTY
NAME_INCOME_TYPE
NAME_EDUCATION_TYPE
NAME_FAMILY_STATUS
NAME_HOUSING_TYPE
OCCUPATION_TYPE

credit_record.csv file has total 1,048,575 rows and 3 features. It has below numeric features:
ID
MONTH_BALANCE
