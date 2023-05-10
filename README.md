# Lending Club Case Study EDA

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- The aim of this project is to identify patterns which indicate if a person is likely to default.
- Based on this identification we can take actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- The data given, contains information about past loan applicants and whether they ‘defaulted’ or not. 

## Technologies Used
- Python - 3.8.2
- Pandas - 1.1.0
- Seaborn - 0.12.2
- Matplotlib - 3.2.1

## Conclusions
### Segmented univariate analysis result
- Loan amount was greater for people who charged off.
- People with less annual income have more chance of charge off. Half of people who defaulted have annual income b/w 37000 and 75000
- Loans with higher interst rate leads to charge off. Half of fully paid loans are in 8.5 to 14 interest rate.
- Lower debt to interest ratio have higher chances of full payback. Half of the fully paid loan have dti ratio between 8 and 18 percent
- Higher credit utilization rate results in more chances of default. Half of the people who defaulted have this rate between 34 and 79.

### Bivariate analysis
- High percentage of defaults happen for Small business, renewable energy and educational loans.
- Higher percentage of defaults happen in 60 months term.
- Defaults are inversly proportional to the loan grade. Higher the grade, lesser the defaults. Pattern is similar for sub-grades with few exceptions.
- Home ownership marked as Rent have slightly higher chance to default
- People with verified income source have slightly higher chance to default.
- Applicants from states Nevada, Florida, Missouri have higher chances of defaults
- If home ownership is mortgage and loan amount is high, there is a higher chance of default.
- As loan amount for small business increase, we have higher chances of default.


## Acknowledgements
- Concepts taught during EDA sessions came in handy for this real-world case study

## Contact
Created by [@himachallad] - feel free to contact me!


## License
This project is open source.
