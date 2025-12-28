# A/B Testing – Recommendation System

## Industry
E-commerce

## Business Problem
An international e-commerce platform implemented a new recommendation system and needed to evaluate whether it improved user conversion across the purchase funnel.

## Objective
Assess the impact of the new recommendation system on user behavior and conversion rates through a controlled A/B test.

## Data Description
The dataset includes:
- User events (product page views, add-to-cart, purchases)
- Group assignment (control vs. test)
- Event timestamps
- User identifiers

The test targeted 15% of new EU users over a defined experimental period.

## Tools Used
- Python (Pandas)
- Statistical Testing
- Data Visualization

## Methodology
- Performed data cleaning and validation (duplicates, missing values, overlapping users).
- Conducted exploratory data analysis to assess funnel behavior and event distribution.
- Calculated conversion rates at each funnel stage.
- Applied z-tests to compare proportions between control and test groups.

## Key Findings
- Conversion rates did not achieve the expected minimum 10% uplift across funnel stages.
- Statistical testing showed no significant improvement attributable to the new recommendation system.
- Identified data anomalies that could impact test validity.

## Business Impact
The analysis supports data-driven decision-making by:
- Preventing premature rollout of ineffective product changes
- Highlighting the importance of proper experimental design and data validation
- Providing recommendations for improving future A/B tests

## Challenges & Learnings
- Evaluated data quality issues that could bias experimental results.
- Improved adaptability by adjusting analytical approaches when test assumptions were violated.
- Strengthened understanding of experimentation frameworks and statistical rigor.
