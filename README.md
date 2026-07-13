# Insurance Claims Risk Analysis & Actuarial Pricing Framework
![R](https://img.shields.io/badge/R-Programming-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Excel](https://img.shields.io/badge/Excel-Analysis-green)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange)


## Project Objective
To analyze insurance claims data using actuarial and data analytics techniques to identify key risk drivers, evaluate claim severity and fraud patterns, develop a rule-based risk segmentation framework, and propose data-driven pricing recommendations.


## Tools & Technologies

- **R** – Data cleaning, exploratory analysis and risk segmentation
- **Excel** – Data validation and preprocessing
- **Power BI** – Interactive dashboard development (in progress)
- **Git & GitHub** – Version control and project documentation


## Methodology

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Claim Severity Analysis
5. Fraud Analysis
6. Risk Segmentation
7. Risk-Based Pricing Framework
8. Dashboard Development


## Dataset

Source: Insurance Fraud Detection Dataset (Kaggle)

Dataset Size:

* 1,000 insurance claim records
* 39 variables

Key Variables:

* Age
* Policy Annual Premium
* Policy Deductible
* Incident Severity
* Total Claim Amount
* Injury Claim
* Property Claim
* Vehicle Claim
* Fraud Reported

The dataset contains policyholder, vehicle, incident, and claims information that will be used to evaluate claim severity, fraud patterns, and insurance risk drivers.



## Current Status

Project Progress: 85% Complete

- [x] Repository Setup
- [x] Dataset Collection
- [x] Data Understanding
- [x] Exploratory Data Analysis
- [x] Claim Frequency Analysis
- [x] Claim Severity Analysis
- [x] Risk-Based Pricing Framework
- [ ] Power BI Dashboard
- [ ] Final Report


## Repository Structure

```text
insurance-claims-risk-analysis/
│
├── data/
├── scripts/
├── dashboard/
├── reports/
├── images/
└── README.md
```


## Project Goal
The objective is to identify key risk drivers affecting insurance claims and develop actuarially justified pricing recommendations using historical claims data.


## Expected Outcomes

- Identify high-risk policyholder segments.
- Analyze claim frequency and severity patterns.
- Develop a risk-based pricing framework.
- Create interactive dashboards for portfolio monitoring.
- Generate underwriting and pricing recommendations.


## Key Findings

- Analyzed 1,000 insurance claims across 39 variables using R.
- Collision-related incidents accounted for over 80% of all claims.
- Fraudulent claims exhibited higher average claim amounts than non-fraudulent claims.
- Vehicle claims represented the largest component of total claim costs.
- Older policyholders (55+) recorded the highest average claim amounts.
- Multi-vehicle incidents produced higher claim severity than single-vehicle incidents.
- Developed an initial rule-based risk segmentation model classifying policyholders into Low, Medium, and High Risk categories.
- Developed a 5-level rule-based risk segmentation model using incident severity, fraud status, and number of vehicles involved.
- Successfully differentiated Very Low Risk policyholders from higher-risk groups based on average claim experience.
- Designed a risk-based pricing framework that recommends premium adjustments using actuarial risk factors and historical claim
  experience.
- Demonstrated how premium differentiation can better align pricing with expected claim costs.


## Future Enhancements

- Generalized Linear Models (GLMs)
- Automated pricing recommendations
- Interactive Power BI dashboard


## Sample Visualizations

### Claim Frequency by Age Group

![Claim Frequency by Age Group](images/Claim_frequency_by_age_group.JPG)



### Claim Amount by Incident Severity

![Claim Amount by Incident Severity](images/Claim_amount_by_incident_severity.JPG)



### Claim Amount by Fraud Status

![Claim Amount by Fraud Status](images/Claim_severity_by_Fraud_Status.JPG)



### Claim Amount by Risk Level

![Claim Amount by Risk Level](images/Claim_amount_by_risk_level.JPG)
