# A/B Testing on Grocery Campaign Data

This project uses a grocery retail dataset to apply A/B testing methodologies and evaluate the impact of a marketing campaign offering free delivery memberships. The marketing team conducted an experiment where customers were randomly assigned to receive either Mailer 1 or Mailer 2 promoting a $100/year delivery club membership. A control group received no mailer. 

The objective was to determine whether Mailer 1 or Mailer 2 was more effective in driving customer sign-ups, and to quantify the impact through statistical hypothesis testing.

## Purpose of Analysis

- Compare sign-up rates between customers who received Mailer 1 and Mailer 2.
- Evaluate if the difference in outcomes between the two mailers is statistically significant.
- Practice different types of t-tests using both real-world and synthetic data to reinforce hypothesis testing techniques.
- Visualize customer behavior before and after interventions to interpret shifts in behavior.

## Grocery Database Overview

The provided `grocery_database.xlsx` consists of the following tables:

- `customer_details`: Contains customer demographic information such as distance from store, gender, and credit score.
- `transactions`: Contains customer purchase records including transaction date, product area, number of items, and sales cost.
- `product_areas`: Provides mapping between product area IDs and their names along with associated profit margins.
- `delivery_club_campaign`: Records customer mailer assignments (Mailer 1, Mailer 2, Control Group) and signup status.
- `loyalty_scores`: Provides loyalty scores representing the percentage of a customer's grocery spend allocated to the supermarket.

## Key Testing Scenarios

- **Independent Samples T-Test (Real Campaign Data)**
  - Objective: Compare signup rates between Mailer 1 and Mailer 2 recipients.
  - Script: `1_Independent_Samples_T_test.py`

- **One-Sample T-Test (Synthetic Data)**
  - Objective: Test if the sample mean significantly differs from a known population mean.
  - Script: `2_One_Sample_T_test.py`

- **Independent Samples T-Test (Synthetic Data)**
  - Objective: Practice comparing two unrelated synthetic groups.
  - Script: `3_Independent_Samples_T_test.py`

- **Paired Samples T-Test (Synthetic Data)**
  - Objective: Measure changes in customer behavior before and after a campaign intervention.
  - Script: `4_Paired_Samples_T_test.py`

## Summary of Findings

- A/B testing using Mailer 1 and Mailer 2 allowed a data-driven evaluation of which marketing approach was more successful in promoting sign-ups.
- Statistical testing clarified whether observed differences were meaningful or could have occurred by random chance.
- Visualization of distributions helped in understanding the behavioral patterns between groups.
- The exercises reinforced the practical use of one-sample, independent-samples, and paired-samples t-tests in real-world business scenarios.


