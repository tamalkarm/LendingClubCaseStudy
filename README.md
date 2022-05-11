# Lending Club Case Study Analysis
> The project mainly deals with the analysis of the loan data using different EDA methodlogies and understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.
The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
-  Project Description : 
    * The project mainly deals with finding out the driver variable which can lead to identify the applicant with risky loan. To identify these variable, loan data sheet needed to be analyzed and based on the EDA inferences risky variable to be found out
- Project Background : 
    *Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
- What is the business probem that your project is trying to solve?
    * Identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study
- What is the dataset that is being used?
    * Loan data for all loans issued through the time period 2007 t0 2011

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Possiblity of Loan charge off will be more 
    * If an applicant belongs to Grade B, C or D and loan amount 5.5k to 10k, then chances of full-payment is very low.
    * Loan amount from 5.5K to 10K and interest rate is 14 to 20 %, these stats are strong indicators of defaulters.
    * One of the simplest analysis says that if the loan is taken for the duration of 36 months, overall count of defaulters are more as compared to those applicants taking loan for 60 months.
    * Another very important point that needs to be dig into is Employment durations is either 0 to 1 year or 10 years and above and the loan amount is between 30K to 40K, the loan may go into debt. Account of Business.
    * Any applicant with 7 or more active bank accounts along with annual income ranging 30K to 40K and loan amount between 5.5K to 10K, risk is high.
    * A very important contributor in deciding if the loan should be given or not is, if the application is falls in the category of “Not-Verified”.
    * Avoid giving loan to those applicants who has requested for loan amount around 5.5 K to 10K and also requested for EMI length of 100 to 300.
    * Applications should be triple checked (to be careful), if income range is 30K to 40K and Loan amount is 5500 to 10,000 and interest rage is 14 % to 20%, request might be risky.
    * The risk is high if the purpose of the loan is to pay another debt. 
    * Applications coming in for loan section, specially in the month of Dec. or November and loan amount between 5.5 K to 10K, this might be an indicator that requester is asking loan for fun/luxury – as Nov. and Dec. are holiday season.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Matplotlib - v3.4.3
- Numpy   - v1.20.3
- Seaborn - v0.11.2
- Pandas  - v1.3.4
- Python  - v3.9.7
- Excel
- Jupyter Notebook - v6.4.5
- IPython - v7.29.0
- Vscode - v1.67.0
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
### Contributer.
    * Amit Ahuja
    * Tamal Karmakar

#### This project is created as part of IIITB and UPgrads Lending Club case study analysis


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->