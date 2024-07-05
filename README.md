# Credit Risk Modeling

This repository contains notebooks for credit risk modeling, focusing on data preprocessing and model building. The dataset includes various features relevant to assessing credit risk.

## Files

- **Data_Preprocessing.ipynb**: This notebook contains the steps for cleaning and preprocessing the dataset. It includes handling missing values, encoding categorical variables, and feature scaling.
- **Model_Building.ipynb**: This notebook covers the steps for building and evaluating machine learning models for credit risk prediction.

## Dataset Features

1. **pct_tl_open_L6M**: Percentage of trade lines (accounts) opened in the last 6 months.
2. **pct_tl_closed_L6M**: Percentage of trade lines closed in the last 6 months.
3. **Tot_TL_closed_L12M**: Total number of trade lines closed in the last 12 months.
4. **pct_tl_closed_L12M**: Percentage of trade lines closed in the last 12 months.
5. **Tot_Missed_Pmnt**: Total number of missed payments.
6. **CC_TL**: Number of credit card trade lines.
7. **Home_TL**: Number of home loan trade lines.
8. **PL_TL**: Number of personal loan trade lines.
9. **Secured_TL**: Number of secured loan trade lines.
10. **Unsecured_TL**: Number of unsecured loan trade lines.
11. **Other_TL**: Number of other types of trade lines.
12. **Age_Oldest_TL**: Age of the oldest trade line.
13. **Age_Newest_TL**: Age of the newest trade line.
14. **time_since_recent_payment**: Time since the most recent payment was made.
15. **max_recent_level_of_deliq**: Maximum level of delinquency in recent times.
16. **num_deliq_6_12mts**: Number of delinquencies in the last 6 to 12 months.
17. **num_times_60p_dpd**: Number of times payments were 60+ days past due.
18. **num_std_12mts**: Number of standard delinquencies in the last 12 months.
19. **num_sub**: Number of subprime delinquencies.
20. **num_sub_6mts**: Number of subprime delinquencies in the last 6 months.
21. **num_sub_12mts**: Number of subprime delinquencies in the last 12 months.
22. **num_dbt**: Number of debt-related issues.
23. **num_dbt_12mts**: Number of debt-related issues in the last 12 months.
24. **num_lss**: Number of loan loss issues.
25. **recent_level_of_deliq**: Recent level of delinquency.
26. **CC_enq_L12m**: Number of credit card inquiries in the last 12 months.
27. **PL_enq_L12m**: Number of personal loan inquiries in the last 12 months.
28. **time_since_recent_enq**: Time since the most recent inquiry.
29. **enq_L3m**: Number of inquiries in the last 3 months.
30. **NETMONTHLYINCOME**: Net monthly income of the individual.
31. **Time_With_Curr_Empr**: Time with the current employer.
32. **CC_Flag**: Flag indicating if the individual has a credit card.
33. **PL_Flag**: Flag indicating if the individual has a personal loan.
34. **pct_PL_enq_L6m_of_ever**: Percentage of personal loan inquiries in the last 6 months out of all inquiries ever.
35. **pct_CC_enq_L6m_of_ever**: Percentage of credit card inquiries in the last 6 months out of all inquiries ever.
36. **HL_Flag**: Flag indicating if the individual has a home loan.
37. **GL_Flag**: Flag indicating if the individual has a general loan.
38. **EDUCATION**: Education level of the individual.
39. **Approved_Flag**: Flag indicating if the loan was approved.
40. **MARITALSTATUS_Married**: Flag indicating if the individual is married.
41. **MARITALSTATUS_Single**: Flag indicating if the individual is single.
42. **GENDER_F**: Flag indicating if the individual is female.
43. **GENDER_M**: Flag indicating if the individual is male.
44. **last_prod_enq2_AL**: Last product inquiry for auto loans.
45. **last_prod_enq2_CC**: Last product inquiry for credit cards.
46. **last_prod_enq2_ConsumerLoan**: Last product inquiry for consumer loans.
47. **last_prod_enq2_HL**: Last product inquiry for home loans.
48. **last_prod_enq2_PL**: Last product inquiry for personal loans.
49. **last_prod_enq2_others**: Last product inquiry for other loans.
50. **first_prod_enq2_AL**: First product inquiry for auto loans.
51. **first_prod_enq2_CC**: First product inquiry for credit cards.
52. **first_prod_enq2_ConsumerLoan**: First product inquiry for consumer loans.
53. **first_prod_enq2_HL**: First product inquiry for home loans.
54. **first_prod_enq2_PL**: First product inquiry for personal loans.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python libraries (specified in the notebooks)

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss changes.
