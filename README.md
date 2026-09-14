# What Motivates Donors to Give to Charities?
## A Case Study of StoveTeam International

This applied econometric research project examines factors associated with charitable giving to StoveTeam International. The project was completed as part of my graduate training in economics at the University of Nebraska at Omaha.

## Research Question

What donor characteristics and fundraising strategies are associated with charitable giving to StoveTeam International?

## Data

The analysis combines:

- StoveTeam International donor and fundraising records from the May 2023, November 2023, and May 2024 appeal periods.
- U.S. Census / American Community Survey (ACS) demographic and socioeconomic data used to construct geographic proxies for selected donor characteristics.

The donor-level organizational data are **not included in this repository** to protect confidential and non-public information.

## Methodology

The analysis was conducted in **R** and includes:

- Data cleaning, transformation, and merging
- Construction of demographic and fundraising variables
- Descriptive statistics
- Pairwise correlation analysis
- Ordinary Least Squares (OLS) regression
- HC1 heteroskedasticity-robust standard errors
- Pooled-sample analysis
- Robustness checks using an alternative donation-period measure

## Key Findings

The analysis found that follow-up email communication was consistently positively associated with donation amounts across the main specifications. The results also suggest that fundraising strategies may play an important role in charitable giving behavior.

These findings should be interpreted as **associations rather than causal effects**. Several donor characteristics were unavailable at the individual level and were therefore represented using geographic demographic proxies from Census/ACS data, creating important measurement limitations.

## Tools

- R
- tidyverse
- dplyr
- stargazer
- sandwich
- lmtest

## Repository Contents

- **Research paper:** Full paper presenting the motivation, literature, methodology, empirical analysis, results, and conclusions.
- **R analysis:** Code used for data preparation, descriptive analysis, econometric estimation, robust standard errors, and robustness checks.
- **Data:** Donor-level data are not publicly shared because of confidentiality considerations.

## Author

**Seun Jide Akinbowale**  
M.S. Economics & MBA Candidate  
University of Nebraska at Omaha
