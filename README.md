# Lending Club Case study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Analysis overview](#analysis-overview)
* [Conclusions](#conclusions)


## General Information
The lending club provides loans to urban consumers. However, few members fail to pay back the loan (Defaulters) who are identified as a risk to the lending club. The case study revolves around identifying the patterns of defaulters.

Once we have identified the patterns, the club can take decisions to not provide loans or lower the amount of lending loans to defaulters.

'loan.csv' is the dataset used, which gives information about each member and their demograhics, characteristics, loan details, etc.

## Technologies Used
- pandas 1.3.4
- numpy 1.20.3
- plotly 5.5.0
- matplotlib 3.4.3

## Analysis overview
- Data cleaning and standardization
- Univariate analysis on unordered categorical variables
- Univariate analysis on ordered categorical variables
- Bivariate analysis

## Conclusions
- Members with low income (<50k) are not likely to pay back the funded amount
- Defaulters are usually higher when the intrest rates are greater than 15%
- Higher grade loans (>C grade) are more likely to be defaulted
- Higher number of defaulters are seen in 10+ years of experience who use the loans for small business
- The defaulters exhibit a monthly purpose patttern. Eg - Loans taken in Aug-Sept for Education, Loans taken in December for Wedding, are likely to be charged off

## Contact
Created by Varsha R, Shreyas P
