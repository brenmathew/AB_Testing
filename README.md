A/B Testing on Grocery Campaign Data
This project uses a grocery retail dataset to apply A/B testing methodologies and understand the impact of a marketing campaign offering free delivery memberships.

The marketing team conducted an experiment where customers were randomly assigned to receive either Mailer 1 or Mailer 2 promoting a $100/year delivery club membership.

Mailer 1 and Mailer 2 had different designs or messaging strategies.

A Control Group received no mailer.

The key objective was to determine which mailer, if any, was more effective at driving customer sign-ups.

Purpose of Analysis
Compare sign-up rates between customers who received Mailer 1 and those who received Mailer 2.

Evaluate if the difference in performance between the two mailers is statistically significant.

Perform additional one-sample and paired-sample t-tests using synthetic data to practice different hypothesis testing approaches.

Visualize distributions clearly to aid interpretation of results.

About the Grocery Database
The provided grocery_database.xlsx contains five interconnected tables:


Table	Description
customer_details	Demographic and credit score data for each customer.
transactions	Purchase behavior including items bought and sales cost by product area.
product_areas	Lookup table for product category names and profit margins.
delivery_club_campaign	Mailer assignments and sign-up flags for the delivery club campaign.
loyalty_scores	External loyalty database scores showing customer commitment to the supermarket.
Key Testing Scenarios

Scenario	Hypothesis Tested	Python Script
Independent Samples T-Test (Mailer 1 vs Mailer 2)	Is there a significant difference in sign-up rates between Mailer 1 and Mailer 2?	101_Independent_Samples_T_test.py
One-Sample T-Test	Is the sample mean significantly different from the known population mean? (Synthetic data)	102_One_Sample_T_test.py
Independent Samples T-Test (Synthetic Data)	Compare two unrelated groups generated synthetically to practice independent sample testing.	103_Independent_Samples_T_test.py
Paired Samples T-Test (Before vs After)	For the same customers, is there a significant change in behavior after an event? (Synthetic data)	104_Paired_Samples_T_test.py
 Summary of Findings
The A/B testing approach allowed us to quantify the effectiveness of different marketing materials (Mailer 1 vs Mailer 2).

Based on the t-tests, we could accept or reject the hypothesis that both mailers performed equally.

Data-driven insights helped determine which strategy was more effective at increasing membership sign-ups.

Visualization using histograms with professional coloring and legends enhanced the interpretability of results.

Practicing multiple types of t-tests (one-sample, independent, paired) built a broader understanding of which statistical method fits which business question.
