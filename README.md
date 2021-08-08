# Credit Card Approval Prediction

The dataset chosen for this study has been picked up from Kaggle as below:
https://www.kaggle.com/rikdifos/credit-card-approval-prediction
<br/> This is the dataset for predicting the credit card approval status which is in line with the research being carried out for prediction of loan approval status for the applicants. <br/> <br/> This dataset consists of two csv files such as:
<br/> application_record.csv
<br/> credit_record.csv
<br/> <br/>
Below is the list of features available in application_record.csv data file along with their description: application_record.csv Feature name Explanation Remarks
<br/> ID - Client number
<br/> CODE_GENDER - Gender
<br/> FLAG_OWN_CAR - Is there a car
<br/> FLAG_OWN_REALTY - Is there a property
<br/> CNT_CHILDREN - Number of children
<br/> AMT_INCOME_TOTAL - Annual income
<br/> NAME_INCOME_TYPE - Income category
<br/> NAME_EDUCATION_TYPE - Education level
<br/> NAME_FAMILY_STATUS - Marital status
<br/> NAME_HOUSING_TYPE - Way of living
<br/> DAYS_BIRTH - Birthday. Count backwards from current day (0), -1 means yesterday
<br/> DAYS_EMPLOYED - Start date of employment. Count backwards from current day (0). If positive, it means the person currently unemployed.
<br/> FLAG_MOBIL - Is there a mobile phone
<br/> FLAG_WORK_PHONE - Is there a work phone
<br/> FLAG_PHONE - Is there a phone
<br/> FLAG_EMAIL - Is there an email
<br/> OCCUPATION_TYPE - Occupation
<br/> CNT_FAM_MEMBERS - Family size
<br/> 
<br/> Below is the list of features available in credit_record.csv data file along with their description:
<br/> ID - Client number 
<br/> MONTHS_BALANCE - Record month. The month of the extracted data is the starting point, backwards, 0 is the current month, -1 is the previous month, and so on 
<br/> STATUS - Status 0: 1-29 days past due 1: 30-59 days past due 2: 60-89 days overdue 3: 90-119 days overdue 4: 120-149 days overdue 5: Overdue or bad debts, write-offs for more than 150 days C: paid off that month X: No loan for the month
<br/> <br/> 
application_record.csv file has total 438,557 rows and 18 features. It has below numeric fields:
<br/> ID
<br/> CNT_CHILDREN
<br/> AMT_INCOME_TOTAL
<br/> DAYS_BIRTH
<br/> DAYS_EMPLOYED
<br/> FLAG_MOBIL (boolean – 0 or 1)
<br/> FLAG_WORK_PHONE (boolean – 0 or 1)
<br/> FLAG_PHONE (boolean – 0 or 1)
<br/> FLAG_EMAIL (boolean – 0 or 1)
<br/> CNT_FAM_MEMBERS
<br/> <br/> 
It has below categorical features:
<br/> CODE_GENDER
<br/> FLAG_OWN_CAR
<br/> FLAG_OWN_REALTY
<br/> NAME_INCOME_TYPE
<br/> NAME_EDUCATION_TYPE
<br/> NAME_FAMILY_STATUS
<br/> NAME_HOUSING_TYPE
<br/> OCCUPATION_TYPE
<br/> <br/> 
credit_record.csv file has total 1,048,575 rows and 3 features. It has below numeric features:
<br/> ID
<br/> MONTH_BALANCE
