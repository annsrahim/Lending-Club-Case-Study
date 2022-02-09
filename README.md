# Lending Club Case Study - by Anns Rahim and Sankalp Gupta
> This project is about analysing historial loans data of a leading finance company to determine driving attributes that lead to loan default

## Contributors
> Sankalp Gupta
> 
> Anns Rahim


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?
> 2. Based on the above attributes - recommend to the company
>    a) Loan applications to be Rejected OR
>    b) Loan applications to be accepted (with high risk) OR
>    c) Loan applications to be accepted (with low risk)
> 3. In case of high risk loan applications, determine whether to:
>    a) Reduce loan amount OR
>    b) Increase Interest Rate OR
>    c) Reduce loan tenure OR
>    d) One or more of the above


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Low Risk Loans
> Disbursement Amount = Loan Requested
> Tenure = 36 months
> Low Interest Rate
> Annual Income > 200K
> Home Ownership is Mortgaged or Own
> Public Records and Bankruptcies are ZERO
> Employment Length between 1 to 9 years
> Loan Purpose is Car, Major Purchase, Wedding
> State is IA, IN, ME, DC
> Loan Inquiries in last 6 months are less than 2

- High Risk Loans
> Disbursement Amount Less Than Loan requested
> Tenure = 60 months
> High Interest Rate
> Annual Income < 50K
> Home Ownership is Rented or Other
> Public Records and Bankruptcies >= 1
> Employment Length < 1 yr OR > 10 years
> Loan Purpose is Small Business, Debt Consolidation, Education or Renewable Energy
> State is NV or NE
> Loan Inquiries in last 6 months are 3 or more

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- operating system - microsoft windows - version Windows 11 Home edition
- programming language - python 3 - version 3.9.7 
- jupyter notebook - version 6.4.5
- pandas library - version 1.3.4
- numpy library - version 1.20.3
- matplotlib library - version 3.4.3
- seaborn library - version 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Lending Club Case Study
- References : Lending Club Case Study Project as a part of PG course in AI & ML by IIITB and upGrad
- This project was based on [Statistics Essentials](https://learn.upgrad.com/course/1994/segment/13374/100455/302536/1574889).


## Contact
Created by [@sagupta153] - feel free to contact me!

Created by [@anns_rahim] - feel free to contact me!
