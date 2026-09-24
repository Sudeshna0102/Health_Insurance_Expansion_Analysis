# Health Insurance Scenario in India

## Objective and Background

This project presents an end-to-end analysis of the current health insurance scenario in India, with a focus on market expansion and customer acquisition opportunities for health insurance companies.

The data is sourced from the **80th Round of the NSO Survey (2025)**, which focuses on the current healthcare scenario in India. Therefore, the analysis reflects recent healthcare and insurance conditions relevant to business decision-making.

## Objective

The study revolves around two key questions:

1. Identify the potential for expansion in the Indian health insurance market.
2. Identify the segments that marketing and financial teams should focus on.

## Executive Summary
The survey analysis identifies the **East and North** regions, the age group of **18-40**, the **urban areas** and most of the** middle class** as potential segments that can be targeted for a successful business expansion. Moreover, the potential for expansion is high in India as there is a substantial gap in insurance demand and number of insured reflected by a high **OOPE of 19,000 INR** per hospital visits. The sustainable loss ratio of 69% and 4.5 utilization rate indicates the further potential. The country has **52% uninsured** and only 1.88% privately insured despite having a substantial number of middle classes with purchasing power. The recommendations include targeted awareness campaigns and interactive PR efforts, adoptions of AI for customized policies and better communication as well as merging for being able to avail a better range of products with competitive price catering to the middle class.


## Key Metrics

The study uses four key metrics to assess the initial potential of the Indian market.

### 1. Average OOPE

Average **Out-of-Pocket Expenditure (OOPE)** currently stands at approximately **₹19,000 per hospitalization visit**. This highlights the gap between healthcare expenditure and health insurance coverage in India.

### 2. Medical Loss Ratio

The **Medical Loss Ratio (MLR)** for private insurance companies stands at approximately **69%**. This key performance indicator suggests scope for improved fund allocation and further market expansion.

### 3. Cost per Claim

The **average cost per claim is approximately ₹19,000**, nearly equal to the average OOPE. This further highlights the potential for addressing the existing insurance coverage gap.

### 4. Utilization Rate

The **utilization rate is approximately 4.5**, indicating nearly five healthcare utilization instances per insured person. This is an important metric for tracking costs incurred by insurers.


## Insights and Overview

### 1. Regional Demand

* The **East region** contributes the highest share of overall demand at approximately **31%**, despite having a relatively low insurance rate. This segment could play a crucial role in market expansion.

* The **South region** shows a similar pattern, contributing approximately **23% of overall demand** while maintaining a relatively low insurance rate. This segment also shows significant expansion potential.

* The **North region**, despite showing the lowest demand, also has the lowest insurance rate and can therefore be considered for targeted campaigns.

<img width="200" height="183" alt="3" src="https://github.com/user-attachments/assets/25e88f0c-70b1-4cb0-b470-1fe558cf8445" />

<img width="255" height="283" alt="3" src="https://github.com/user-attachments/assets/af76117b-937c-4254-af55-9c6f414a68de" />




### 2. Healthcare Overview

* A majority of people still rely on **income and savings** as their primary source of healthcare expenditure. This further highlights the existing insurance coverage gap.

* Approximately **53% of patients use private healthcare**, yet only **1.88% are covered by private insurers**, while approximately **52% remain uninsured**. This indicates a substantial coverage gap.

* **Healthy individuals have a lower insurance rate** than high- and medium-risk individuals, highlighting the potential need for targeted awareness programs to support sustainable growth.

* The **insurance rate is lower among the middle class** despite their purchasing power, indicating another potential segment for expansion.

<img width="220" height="150" alt="image" src="https://github.com/user-attachments/assets/2b24884b-eeb0-403b-bca3-867fc16dd020" />
<img width="227" height="171" alt="image" src="https://github.com/user-attachments/assets/a8577274-d933-4f58-b454-fecfe732588f" />
<img width="244" height="170" alt="image" src="https://github.com/user-attachments/assets/915b68c1-22c1-4f69-81b5-1f7a738fc0b6" />


### 3. Risk and Likelihood

* The insurance rate is lower among **healthy individuals (41%)** than among **high-risk (61%)** and **medium-risk (58%)** individuals. This may indicate increased liability for insurers.

* The logistic regression model supports this pattern. Compared with healthy individuals, **high- and medium-risk individuals have lower odds of being uninsured**—approximately **30% lower for high-risk individuals** and **35% lower for medium-risk individuals**. This could place additional pressure on the Medical Loss Ratio, as higher-risk individuals may have greater healthcare utilization and claim costs.

* Compared with the **rural sector**, individuals in the **urban sector have approximately 38% higher odds of being uninsured**. This pattern may present an opportunity for targeted market expansion.




* Compared with men, **women have approximately 3.6% higher odds of being uninsured**.

<img width="250" height="170" alt="image" src="https://github.com/user-attachments/assets/c9e5dce6-d77d-4a44-a1da-bf189f0b556a" />
<img width="250" height="170" alt="image" src="https://github.com/user-attachments/assets/46d13d67-49b9-498d-92ae-6944020ad244" />

## Recommendations

| Action                                                        | Specifications                                                                                                                                                                                                                                     | Priority | Concerned Team |
| ------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------: | -------------- |
| **1. Targeted Marketing Campaign**                            | 1. Run awareness campaigns in the East and North regions. The campaigns should be innovative and educational, using innovative ads, catchy infographics for billboards, etc.                                                                       |    P0    | Marketing      |
|                                                               | 2. Conduct interactive campaigns in urban areas, such as PR events and social events, to engage with potential customers.                                                                                                                          |    P0    | Marketing      |
| **2. AI Integration for Seamless Purchase and Communication** | 1. Adopt AI within business apps for quick and easy communication. Keep multiple communication channels open for both tech-savvy and non-tech-savvy customers.                                                                                     |    P1    | Technical      |
|                                                               | 2. Adopt advanced analytics and predictive models to suggest customized policies to the younger age group of 18–40, as younger people are less likely to have health insurance and their needs may not be categorized into generic policy options. |    P1    | Data           |
| **3. Merging with Potential Partners**                        | 1. Identify potential partners to merge with to provide a wider range of products to the middle class in comptitive price, 3.Merging with potential partners	1.Identify potential partners to merge with to be able to avail a larger range of products in competitive price to the middle class, loss ratio should be checked during this action|	P2	| Executive

 ## Project Workflow

The project follows an end-to-end analytics workflow, from raw survey data preparation to statistical analysis, visualization, and business recommendations.


### Tools & Technologies

| Stage                     | Tool                    | Purpose                                                                               |
| ------------------------- | ----------------------- | ------------------------------------------------------------------------------------- |
| **Data Source**           | NSO 80th Round Survey(CSV)  | Healthcare and health insurance data                                                  |
| **ETL & Data Modelling**  | SQL Server              | Data cleaning, transformation, integration, and creation of analytics-ready tables    |
| **Statistical Analysis**  | Python                  | Logistic regression to analyze factors associated with being uninsured                |
| **Business Intelligence** | Power BI                | KPI calculation, interactive dashboards, segmentation, and visualization              |
| **Business Analysis**     | SQL + Python + Power BI | Identification of insurance gaps, target segments, and market expansion opportunities |
| **Final Output**          | GitHub                  | Documentation of methodology, findings, and business recommendations                  |
                                                                                                                                           
Logistic Regression
The project includes logistic regression to identify the odds of each factors happening that contribute to a person being uninsured. Uninsured is the dependent variable and age, gender, risk, sector, region are the independent variables. 
Uninsured ~ Intercept + age_band + gender + risk_tier + sector + region 
The intercept terms represent the odds of being uninsured when all other factors are held at zero. The intercept has also absorbed the baseline for each factor. The baseline for age_band is ‘18-40’, for gender is ‘male’, for risk_tier is ‘no reported ailment’ in other words the healthy persons, for sector is ‘rural’ and for region is ‘central’. 
Results:
### Logistic Regression Results

| Variable | Odds Ratio | Percentage Change |
|---|---:|---:|
| Intercept | 1.729 | 72.89% |
| Low Risk | 0.717 | -28.27% |
| Medium Risk | 0.674 | -32.61% |
| High Risk | 0.722 | -27.83% |
| Childbirth Related | 0.938 | -6.15% |
| Female | 1.040 | 4.01% |
| Transgender | 0.969 | -3.15% |
| N/A (Gender) | 1.000 | 0.00% |
| Age 40–60 | 0.754 | -24.59% |
| Age 0–18 | 1.000 | 0.00% |
| Age Above 60 | 1.000 | 0.00% |
| Urban | 1.362 | 36.23% |
| East | 0.396 | -60.39% |
| North | 0.742 | -25.79% |
| South | 0.414 | -58.56% |
| West | 0.482 | -51.78% |
*The percent represents the increase or decreases in the odds of being uninsured compared to the baseline. A positive percentage signifies increasing odds and a negative percent signifies decreasing odds of being uninsured.

## Assumptions and Caveats:
The KPI and visualizations are not adjusted for survey weights, the regression results are adjusted for survey weights
