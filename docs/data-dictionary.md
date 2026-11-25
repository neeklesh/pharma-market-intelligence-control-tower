# Data Dictionary

## Purpose
This document defines the datasets, fields, data types, descriptions and business rules used in the Pharma Market Intelligence & Commercial Strategy Control Tower.

## Dataset 1: Country Market Data

| Column Name | Data Type | Description |
|---|---|---|
| country | String | Country name |
| country_code | String | ISO country code |
| year | Integer | Reporting year |
| population | Numeric | Population estimate |
| diabetes_prevalence | Numeric | Diabetes prevalence indicator |
| gdp_per_capita | Numeric | GDP per capita |
| healthcare_expenditure | Numeric | Healthcare expenditure indicator |

## Dataset 2: Clinical Trials

| Column Name | Data Type | Description |
|---|---|---|
| trial_id | String | Unique clinical trial identifier |
| company | String | Sponsor or organisation |
| drug_name | String | Investigational drug name |
| indication | String | Disease or indication |
| phase | String | Clinical development phase |
| country | String | Relevant country |
| status | String | Trial status |
| start_date | Date | Trial start date |
| completion_date | Date | Estimated or actual completion date |

## Dataset 3: Company Intelligence

| Column Name | Data Type | Description |
|---|---|---|
| company_id | Integer | Unique company identifier |
| company_name | String | Pharmaceutical company |
| country | String | Country |
| product_name | String | Product name |
| indication | String | Therapeutic indication |
| development_status | String | Development or commercial status |

## Dataset 4: Synthetic Commercial Data

| Column Name | Data Type | Description |
|---|---|---|
| hcp_id | String | Synthetic HCP identifier |
| territory_id | String | Territory identifier |
| segment | String | HCP segment |
| sales_value | Numeric | Simulated sales value |
| target_value | Numeric | Simulated sales target |
| calls_planned | Integer | Planned calls |
| calls_completed | Integer | Completed calls |

## Data Governance
- Document source and extraction date.
- Identify missing values.
- Identify duplicates.
- Document transformations.
- Identify synthetic datasets clearly.
- Document limitations.
