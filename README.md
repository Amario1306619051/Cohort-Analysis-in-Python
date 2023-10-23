# Cohort Analysis Using Python

This GitHub repository demonstrates cohort analysis using Python on a retail dataset available for download [here](https://www.kaggle.com/datasets/carrie1/ecommerce-data).

## Overview

Cohort analysis helps understand customer behavior over time. In this analysis, we reformat the timestamp, create cohorts, and build a cohort heatmap to visualize customer retention.

## Steps

1. **Data Loading:** The dataset is loaded using Pandas.

2. **Reformat Timestamp:** The timestamp is reformatted to extract month and year.

3. **Creating Cohorts:** Cohorts are created based on the customer's first transaction month and year.

4. **Building Cohort Header:** A header is built for each cohort.

5. **Pivoting Data:** Data is pivoted to create a cohort heatmap, showing customer retention rates.

6. **Heatmap Visualization:** The cohort heatmap is visualized using Seaborn.

## Result

The resulting heatmap provides insights into customer retention over different cohorts, enabling better decision-making for customer-centric strategies.

Explore the Jupyter Notebook for detailed implementation and analysis.

Feel free to use and adapt the code for your own cohort analysis.
