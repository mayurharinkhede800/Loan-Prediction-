# Loan-Prediction-

### Problem Statement

Optimize the Loan eligibility process
Predict Loan Eligibility for Dream Housing Finance company
Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers. 

Data Dictionary
 

Train file: CSVcontaining the customers for whom loan eligibility is known as 'Loan_Status'

Variable	Description
Loan_ID	Unique Loan ID
Gender	Male/ Female
Married	Applicant married (Y/N)
Dependents	Number of dependents
Education	Applicant Education (Graduate/ Under Graduate)
Self_Employed	Self employed (Y/N)
ApplicantIncome	Applicant income
CoapplicantIncome	Coapplicant income
LoanAmount	Loan amount in thousands
Loan_Amount_Term	Term of loan in months
Credit_History	credit history meets guidelines
Property_Area	Urban/ Semi Urban/ Rural
Loan_Status	(Target) Loan approved (Y/N)
 
Test file: CSVcontaining the customer information for whom loan eligibility is to be predicted

Variable	Description
Loan_ID	: Unique Loan ID
Gender :	Male/ Female
Married	: Applicant married (Y/N)
Dependents	: Number of dependents
Education	: Applicant Education (Graduate/ Under Graduate)
Self_Employed	: Self employed (Y/N)
ApplicantIncome	: Applicant income
CoapplicantIncome	: Coapplicant income
LoanAmount :	Loan amount in thousands
Loan_Amount_Term :	Term of loan in months
Credit_History	: credit history meets guidelines
Property_Area	: Urban/ Semi Urban/ Rural
 
## Submission file format

Variable	Description
Loan_ID	Unique Loan ID
Loan_Status	(Target) Loan approved (Y/N)
 
## Evaluation Metric

Your model performance will be evaluated on the basis of your prediction of loan status for the test data (test.csv), which contains similar data-points as train except for the loan status to be predicted. Your submission needs to be in the format as shown in sample submission.

We at our end, have the actual loan status for the test dataset, against which your predictions will be evaluated. We will use the Accuracy value to judge your response.


## Public and Private Split

Test file is further divided into Public (25%) and Private (75%)

 

Your initial responses will be checked and scored on the Public data.
The final rankings would be based on your private score which will be published once the competition is over.
