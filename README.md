# Credit Risk Analytics using Python

## Applying EDA in a real business scenario.

### The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it as their advantage by becoming a defaulter. Use EDA to analyse the patterns present in the data of finance company which specialises in lending various types of loans to urban customers. This will ensure that the applicants capable of repaying the loan are not rejected.

### When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
-  If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
-  If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
  
### The data given below contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios:
-  The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample
-  All other cases: All other cases when the payment is paid on time.
  
### When a client applies for a loan, there are four types of decisions that could be taken by the client/company:

-  Approved: The company has approved loan application
-  Cancelled: The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client he received worse pricing which he did not want.
-  Refused: The company had rejected the loan (because the client does not meet their requirements etc.).
-  Unused Offer: Loan has been cancelled by the client but on different stages of the process.

### Perform EDA to understand how consumer attributes and loan attributes influence the tendency of default.

### Data Understanding:
- **application_data.csv** contains all the information of the client at the time of application. The data is about wheather a client has payment difficulties.
- **previous_application.csv** contains information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.
- **columns_descrption.csv** is data dictionary which describes the meaning of the variables.

### Results Expected by Learners
- Present the overall approach of the analysis in a presentation. Mention the problem statement and the analysis approach briefly.
- Identify the missing data and use appropriate method to deal with it. (Remove columns/or replace it with an appropriate value)
- Identify if there are outliers in the dataset. Also, mention why do you think it is an outlier. Again, remember that for this exercise, it is not necessary to remove any data points.
- Identify if there is data imbalance in the data. Find the ratio of data imbalance.
- Explain the results of univariate, segmented univariate, bivariate analysis, etc. in business terms.
- Find the top 10 correlation for the Client with payment difficulties and all other cases (Target variable). Note that you have to find the top correlation by segmenting the data frame w.r.t to the target variable and then find the top correlation for each of the segmented data and find if any insight is there.  Say, there are 5+1(target) variables in a dataset: Var1, Var2, Var3, Var4, Var5, Target. And if you have to find top 3 correlation, it can be: Var1 & Var2, Var2 & Var3, Var1 & Var3. Target variable will not feature in this correlation as it is a categorical variable and not a continuous variable which is increasing or decreasing.  
- Include visualisations and summarise the most important results in the presentation. You are free to choose the graphs which explain the numerical/categorical variables. Insights should explain why the variable is important for differentiating the clients with payment difficulties with all other cases.
