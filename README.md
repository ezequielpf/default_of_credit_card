# Default of credit card

## 1. Business problem

Original data https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

## 2. Business assumptions


## 3. Solution strategy

### 1. Step 01. Data description

#### Data Dictionary

1. **Response Variable:**
   - **Default Payment (Y):** Binary variable (1 = Yes, 0 = No)

2. **Explanatory Variables:**

   - **Demographic Information:**
      - LIMIT_BAL: Amount of the given credit (NT dollar) - Includes individual and supplementary family credit.
      - SEX: Gender (1 = Male, 2 = Female)
      - EDUCATION: Education (1 = Graduate School, 2 = University, 3 = High School, 4 = Others)
      - MARRIAGE: Marital Status (1 = Married, 2 = Single, 3 = Others)
      - AGE: Age (in years)

   - **History of Past Payment (Repayment Status):**
      - PAY_1: Repayment status in September 2005
      - PAY_2: Repayment status in August 2005
      - ...
      - PAY_6: Repayment status in April 2005
      - Measurement Scale: -1 = Pay duly, 1 = Payment delay for one month, 2 = Payment delay for two months, ..., 8 = Payment delay for eight months, 9 = Payment delay for nine months and above

   - **Amount of Bill Statement (NT dollar):**
      - BILL_AMT1: Bill statement amount in September 2005
      - BILL_AMT2: Bill statement amount in August 2005
      - ...
      - BILL_AMT6: Bill statement amount in April 2005

   - **Amount of Previous Payment (NT dollar):**
      - PAY_AMT1: Amount paid in September 2005
      - PAY_AMT2: Amount paid in August 2005
      - ...
      - PAY_AMT6: Amount paid in April 2005
   


### 2. Step 02. Feature engineering
### 3. Step 03. Data filtering
### 4. Step 04. Exploration Data Analysis (EDA) 
### 5. Step 05. Data preparation
### 6. Step 06. Feature selection
### 7. Step 07. Machine learning modelling
### 8. Step 08. Hyperparameter fine tunning
### 9. Step 09 Convert model performance to business values
## 4. Top 3 data insights
## 5. Machine learning model applied
## 6. Machine learning performance
## 7. Business results
## 8. Conclusions
## 9. Lessons learned
## 10. Next steps
