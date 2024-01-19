# Credit-Card-Approval
This is an OdinSchool data science capstone project. The project is about creating a prediction model for credit card approval for customers.

A bank's credit card department is one of the top adopters of data science. A top focus for the bank has always been acquiring new credit card customers. Giving out credit cards without doing proper research or evaluating applicants' creditworthiness is quite risky. The credit card department has been using a data-driven system for credit assessment called Credit Scoring for many years, and the model is known as an application scorecard. A credit card application's cutoff value is determined using the application scorecard, which also aids in estimating the applicant's level of risk. This decision is made based on strategic priority at a given time.

Customers must fill out a form, either physically or online, to apply for a credit card. The application data is used to evaluate the applicant's creditworthiness. The decision is made using the application data in addition to the Credit Bureau Score, such as the FICO Score in the US or the CIBIL Score in India, and other internal information on the applicants. Additionally, banks are rapidly taking a lot of outside data into account to enhance the calibre of credit judgments.

## Objectives
The objective of this project is to build a machine-learning model that accurately predicts credit card approval outcomes. The model can provide insights into the most important factors that impact credit card approval, allowing banks to make informed decisions quickly and accurately. This can result in a faster and more efficient credit card approval process, reducing the time and cost associated with manual credit assessment methods.

Overall, the proposed project has the potential to upgrade the credit card approval process, reduce manual effort and errors, and enhance the customer experience. This project demonstrates the potential of machine learning in automating and improving critical banking processes and can have significant benefits for banks and financial institutions in the global market.

## Dataset
1. Credit_card.csv  
   - Ind_ID: Client ID
   - Gender: Gender information
   - Car_owner: Having a car or not
   - Propert_owner: Having property or not
   - Children: Count of children
   - Annual_income: Annual income
   - Type_Income: Income type
   - Education: Education level
   - Marital_status: Marital_status
   - Housing_type: Living sty
   - Birthday_count: Use backward count from the current day (0), -1 means yesterday.
   - Employed_days: Start date of employment. Use backward count from the current day (0). A positive value means the individual is currently unemployed.
   - Mobile_phone: Any mobile phone
   - Work_phone: Any work phone
   - Phone: Any phone number
   - EMAIL_ID: Any email ID
   - Type_Occupation: Occupation
   - Family_Members: Family size

2. Credit_card_label.csv
   - ID: The joining key between application data and credit status data, same is Ind_ID
   - Label: 0 is the application approved and 1 is the application rejected.


## Steps implemented to complete the project
1. **Data Preprocessing**

-   In this step, two Excel files will be combined into a single file using pandas data frames. Later cleaning and preprocessing steps will be done to ensure its quality and suitability for data analysis.

-   EDA will be implemented. Missing values and outliers will be removed if any and then we will do encoding on the categorical features. The cleaned dataset is what will be used for further analysis.

2. **Feature Selection**

-   After pre-processing the data, when EDA is performed, Univariate Analysis i.e., histogram and pie chart for some columns and Bivariate Analysis i.e., box plot, Scatter plot, and correlation between data using heatmap and listed down the observations accordingly.

3. **Hypothesis Testing**
   
-   Hypothesis Testing methods such as correlation test, Chi-Squared test etc to select the most important features.
   
4. **Machine Learning Algorithms**

   Here ML Algorithms will be applied. Looking at the problem statement with the categorial features involved, classification algorithms can be used. Logistic regression, Support Vector Machines(SVMs), Random Forest, Decision Tree, K-Nearest Neighbors(KNN). 
