# Pharma-Data-Analytics-Portfolio
A data analytics study applying Python (Pandas, Scipy, Seaborn) to evaluate excipient variability and process robustness in capsule manufacturing.

## Project Overview
This project investigates the impact of lactose excipient variability on pharmaceutical Critical Quality Attributes (CQAs). By applying statistical analysis and predictive modeling, this study evaluates whether supplier-related differences in raw materials pose a risk to process robustness.

## Data Source
The dataset used in this project is **synthetically generated** to mirror real-world pharmaceutical manufacturing parameters. It was designed to simulate typical batch-to-batch variability in lactose excipients and its subsequent impact on capsule quality attributes, ensuring a realistic environment for statistical analysis while maintaining data privacy.

## Key Findings
* **Supplier Variability:** One-way ANOVA confirmed no significant difference (p > 0.05) between suppliers regarding particle size, moisture, and bulk density.

* **Blend Uniformity:** Identified a strong relationship (R² = 0.52) between Blend RSD and Capsule Content Uniformity, supporting its role as a key process parameter.

* **Dissolution Impact:** Found a statistically significant but weak relationship (R² = 0.11) between lactose moisture and dissolution, indicating limited practical impact within the studied range.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas (Data Manipulation), Scipy (Statistical Testing), Seaborn/Matplotlib (Visualization)
* **Environment:** Jupyter Notebook

## Conclusion
The findings support a "Quality by Design" (QbD) approach, suggesting that current supplier variability is well-managed within the existing design space. This analysis demonstrates the value of data-driven decision-making in pharmaceutical manufacturing.
