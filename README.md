# Week2Challenge

## Loan Qualifier Application 

This application takes user submitted financial data and compares it to a list of banks to find banks that are suitable for providing a loan.

---

## Technologies

This application uses the (fire) and (questionary) tools to prompt the user to input financial data and to use the command line interface.  It also uses a util file with financial formulas to turn the data into financial ratios to compare to the list of bank data. You will also need to import the csv function to obtain the bank data. 

---

## Installation Guide

To install (fire) and (questionary) use the following commands 
'pip install fire'
'pip intall questionary' 

---

## Usage

The application takes user information and compares it bank data. To use the application you will need to import the bank data from a csv file. To do this you should use the command 'from pathlib import Path' . You will need to set a path to the csv file. The application will ask the user to enter their financial information. This includes monthly debt and income, the loan value, and the home value.  The formulas in the utils folder will help turn the user entered data into financial ratios so that they can be compared to the csv of bank information. The function '''def find_qualifying_loans(bank_data, credit_score, debt, income, loan, home_value):''' will compare the user entered data to the minimum qualifying ratios set by the banks. It will then save the banks that meet the lending criteria for the user. That can be seen in the following image. (![image1](Screen_Shot_12.2.22)). Running the function will return the banks that meet the users criteria and filter out the banks that do not. 

---

## Contributors

Tyler Goering ([tylergoering](www.linkedin.com/in/tyler-goering-cfa))

---

## License

Python Software Foundation License 
