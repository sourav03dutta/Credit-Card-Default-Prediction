
# Credit Card Default Prediction

THIS PROJECT IS VERIFIED BY [ALMABETTER](https://www.almabetter.com/)

![Logo](https://www.horstinsurance.com/wp-content/uploads/2016/12/credit-card-debt-relief.png)

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of Risk Management, the result of perdictive accuracy of the estimated probability of default will be more valuable then the binary result of Classification - credible or not credible clients.

We will import NumPy, pandas, matplotlib, seaborn, sklearn models and other librarires in Google Colab then mount the drive. After that we will read csv file from working directory path and assigned it into the data frame. The dataset description is given below :-

1. ID: ID of each client

2. LIMIT_BAL: Amount of given credit in NT dollar (includes individual and family/supplementary credit

3. SEX: Gender (1=male, 2=female)

4. EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)

5. MARRIAGE: Marital status (1=married, 2=single, 3=others)

6. AGE: Age in years

7. PAY_0: Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months, 8=payment delay for eight months, 9=payment delay for nine months and above)

8. PAY_2: Repayment status in August, 2005 (scale same as above)

9. PAY_3: Repayment status in July, 2005 (scale same as above)

10. PAY_4: Repayment status in June, 2005 (scale same as above)

11. PAY_5: Repayment status in May, 2005 (scale same as above)

12. PAY_6: Repayment status in April, 2005 (scale same as above)

13. BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)

14. BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)

15. BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)

16. BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)

17. BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)

18. BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)

19. PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)

20. PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)

21. PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)

22. PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)

23. PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)

24. PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)

25. default payment next month: Default payment (1=yes, 0=no)

In this dataset, there are 30000 rows and 25 columns. The dataset contains no duplicate values and null values or missing values. After Data Wrangling, Exploratory Data Analysis is done to get data visualization and deeper insights of the datasets. Correlation heatmap is plotted to check multicollinearity of the datasets. Hypothesis Testing is done on the analysis provided in EDA. In feature engineering, feature selection is done. Then train test split, Implementation of Classification model with cross validation and hyperparameter tuning.

## Conclusion :-

1. Percentage of Defaulters are smaller than the Non
Defaulters in the given dataset.

2. Number of Male credit card holder is less than Female.

3. More number of credit cards holder are Married.

4. More number of credit card holders are university students followed by Graduates and then High school students.

5. 30% male have default payment while 26% female have default payment, the difference is not significant.

6. The data indicates customers with lower education levels default more. Customers with high school and university educational level had higher default percentages than customers with graduate did.

7. There is no difference of default risk in terms of marital status, although the 'other'marital status group had high default percentage.

8. Customers aged between 30-50 had the lowest delayed payment rate, while younger groups (20-30) and older groups (50-70) all had higher delayed payment rates. However, the delayed rate dropped slightly again in customers older than 70 years. 

9. There was a huge jump from May,2005 (PAY_5) to July, 2005 (PAY_3) when delayed payment increased significantly, then it peaked at August, 2005 (PAY_2), things started to get better in September, 2005 (PAY_1).

10. XGBoost Classifier Tuned has the highest Accuracy and F1 Score. XGBoost Classifier has the highest Precision. Random Forest Classifier Tuned has the highest Recall. In this classification problem there is a high cost for the bank when a default credit card is predicted as non-default, since no actions can be taken. Thus, recall is one important metric to pay attention to. But if you check the final evaluation metrics above then you will find out that the Random Forest Classifier Tuned is the most balaced one. Hence I choose RANDOM FOREST CLASSIFIER TUNED from the above created models as my final prediction model.






## 🛠 Skills

**Programming Language** :- Python

**Libraries used** :- NumPy, Pandas, Seaborn, Matplotlib, Scipy, Sklearn, Imblearn, Missingno


## Author

- [@sourav03dutta](https://github.com/sourav03dutta)

