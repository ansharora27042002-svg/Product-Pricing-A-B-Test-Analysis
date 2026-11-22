# Product Pricing A/B Testing & Revenue Analysis

## Project Overview

This project analyzes the impact of different delivery-fee strategies on customer order value and revenue using A/B testing.

The primary objective is to evaluate the performance of the Control and Test groups, understand customer purchasing patterns, identify statistically significant differences, and provide data-driven recommendations for pricing decisions.

## Business Objective

To identify a delivery-fee strategy that can improve order performance while maintaining or increasing revenue.

**Revenue Formula:**

`Revenue = (Order Value × 20%) + Delivery Fee`

## Tools & Technologies

- **Python:** Data analysis and statistical testing
- **Pandas & NumPy:** Data cleaning and manipulation
- **Matplotlib:** Data visualization
- **SciPy:** Statistical hypothesis testing
- **Statsmodels:** ANOVA and statistical modeling
- **Jupyter Notebook:** Analysis and documentation

## Key Analysis Performed

1. **Exploratory Data Analysis (EDA)**
   - Analyzed order value across different hours.
   - Identified hourly revenue and purchasing patterns.
   - Examined missing values and duplicate records.

2. **Control vs. Test Analysis**
   - Compared average order value (AOV).
   - Evaluated average revenue per order.
   - Compared delivery-fee distributions.
   - Analyzed total revenue and order volume.

3. **Statistical Hypothesis Testing**
   - Welch's Independent T-Test.
   - One-way ANOVA.
   - Two-way ANOVA.
   - Levene's Test for variance comparison.
   - Pearson Correlation Analysis.

4. **Customer Behavior Analysis**
   - Examined morning and evening purchasing patterns.
   - Evaluated the relationship between delivery fees and order value.
   - Compared hourly performance across experimental groups.

## Key Findings

- Test group average order value was **31.90**, compared with **29.32** in Control — approximately 8.8% higher.
- Average revenue per order was **8.33** in Test versus **8.15** in Control — approximately 2.1% higher.
- The difference in average revenue per order was statistically significant (Welch's t-test, p = 0.00821).
- Test group order values showed greater variation than Control.
- A significant interaction was observed between pricing variant and time of day.
- Zero-delivery-fee transactions in the Test group had higher average order values, although customer and order mix may explain part of this relationship.

## Business Recommendations

- Conduct a follow-up randomized experiment with clearly defined delivery-fee treatment groups.
- Measure conversion and orders per eligible customer rather than relying only on transaction-level revenue.
- Track contribution margin alongside revenue and average order value.
- Evaluate performance across different time periods and customer segments.
- Monitor cancellations, refunds, delivery costs, and repeat purchases before implementing a pricing change.

## Project Deliverables

- `Ansh_Product_Pricing_AB.ipynb` – Python analysis and statistical testing.
- `Ansh_Product_Pricing_AB_doc.docx` – Detailed project documentation.
- `Ansh_Product_Pricing_AB_Test_PPT.pptx` – Project presentation.

## Important Note

The observed differences between the Control and Test groups should not automatically be interpreted as causal effects. The experimental assignment method and eligible-user exposure denominators are not documented. A properly randomized follow-up experiment is recommended before making final pricing decisions.

## Conclusion

This project demonstrates how data analytics and statistical testing can support business decisions around pricing, customer purchasing behavior, and revenue optimization.

**Skills Demonstrated:** Python | EDA | A/B Testing | Hypothesis Testing | Statistical Analysis | Data Visualization | Business Insights
