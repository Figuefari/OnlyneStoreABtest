## Proyect description

Analysis of various hypotheses and A/B tests to increase revenue for a online store.

## Tasks

1. Using the hypotheses file, which contains 9 of them, the ICE and RICE frameworks should be applied to establish which ones may be prioritized to increase store revenue.
2. A/B test analysis based on two .csv files.
   - Graphical representations
   - Conversion rates
3. Decision based on the test results.

## Data description

Data used in the first part of the project (hypotheses_us.csv):

- Hypotheses: brief descriptions of the hypotheses
- Reach: user reach, on a scale from one to ten
- Impact: impact on users, on a scale from one to ten
- Confidence: confidence in the hypothesis, on a scale from one to ten
- Effort: resources needed to test a hypothesis, on a scale from one to ten. The higher the Effort value, the more resources the test requires.

Data used in the second part of the project (orders_us.csv and visits_us.csv):

First dataset:
- transactionId: order identifier
- visitorId: identifier of the user who placed the order
- date: order date
- revenue: order revenue
- group: A/B test group to which the user belongs

Second dataset:
- date: the date
- group: A/B test group
- visits: the number of visits on the specified date for the specified A/B test group

## Table of contents

FIRST PART: HYPOTHESIS PRIORITIZATION

1. Initialization:
    - Data Loading
    - Data Description
    - Preliminary Conclusions
    
2. Data Preprocessing:
    - Column Renaming
 
3. Data Analysis:
    - ICE Framework
    - RICE Framework
    - Hypothesis Prioritization Conclusions
    - Final Result
    
SECOND PART: A/B TEST ANALYSIS

4. Initialization
    - Data Loading
    - Data Description
    - Preprocessing Preliminary Conclusions
    
5. Preprocessing
    - Duplicate Checking
    - Snake Case
    - Data Type Conversion
    - Test Users and Groups
    - Preprocessing Conclusions
    
6. Data Analysis
    - Question Formulation
    - Analysis Order
    - Cumulative Data
    - Relative Differences
    - Conversion Rates
    - Data Dispersion
    - Statistical Significance
    - Criteria Used for Anomalous Data
    - Significance in Filtered Data
    - Decision Based on Results
 
 7. Final Conclusions

## Used libraries

- pandas
- datetime 
- matplotlib
- scipy
- numpy
