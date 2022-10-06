# Loan-Approval-Prediction

##About Company
Dream Housing Finance company deals in all home loans. They have a presence across all urban, semi-urban, and rural areas. Customer-first applies for a home loan after that company validates the customer eligibility for a loan.

##Problem Statement:-
The company wants to automate the loan eligibility process (real-time) based on customer detail provided while filling the online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others.
To automate this process, they have given a problem to identify the customer segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.


##Features of training dataset:-
1.LoanID= Unique Loan ID 2.Gender= Male/ Female 3.Married= Applicant married (Y/N) 4.Dependents= Number of dependents 5.Education= Applicant Education (Graduate/ Under Graduate) 6.SelfEmployed= Self-employed (Y/N)
7.ApplicantIncome= Applicant income
8.CoapplicantIncome= Coapplicant income
9.LoanAmount= Loan amount in thousands
10.LoanAmountTerm= Term of the loan in months
11.CreditHistory= Credit history meets guidelines 12.PropertyArea= Urban/ Semi-Urban/ Rural
13.LoanStatus= (Target) Loan approved (Y/N) ##Features of a Testing dataset:- 1.LoanID= Unique Loan ID
2.Gender= Male/ Female
3.Married= Applicant married (Y/N)
4.Dependents= Number of dependents
5.Education= Applicant Education (Graduate/ Under Graduate)
6.SelfEmployed= Self-employed (Y/N) 7.ApplicantIncome= Applicant income 8.CoapplicantIncome= Coapplicant income 9.LoanAmount= Loan amount in thousands 10.LoanAmountTerm= Term of the loan in months 11.CreditHistory= Credit history meets guidelines
12.PropertyArea= Urban/ Semi-Urban/ Rural ##Features of Samplesubmission dataset:-
1.LoanID= Unique Loan ID 2.LoanStatus= (Target) Loan approved (Y/N)


##Evaluation Metric:-
What makes a good solution? How do you evaluate which submission is better than another?
Your model performance will be evaluated on the basis of your prediction of loan status for the test data (test.csv), which contains similar data-points as train except for the loan status to be predicted. Your submission needs to be in the format as shown in the sample submission.
We at our end, have the actual loan status for the test dataset, against which your predictions will be evaluated. We will use the Accuracy value to judge your response.


The Source code is avilable in Loan_approval_prediction.ipynb

Train dataset named as train.csv
Test dataset named as test.csv
