# Customer Segmentation Analysis

## Project Overview
This project applies K-Means clustering to group mall customers based on their annual income and spending score. The goal is to identify distinct customer segments and explore how businesses could use these insights to inform targeted marketing strategies.

## Dataset
The Mall Customer Segmentation dataset contains 200 customers and five columns, including customer ID, gender, age, annual income and spending score.

## Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Methodology
1. Loaded and inspected the dataset.
2. Checked for missing values and duplicate records.
3. Standardised annual income and spending score.
4. Compared cluster counts using the elbow method and silhouette scores.
5. Applied K-Means clustering with five clusters.
6. Summarised and visualised customer segments.
7. Developed business recommendations and documented limitations.

## Key Findings
- Five customer segments were identified.
- The largest segment represents 40.5% of customers and has average income and spending scores.
- The high-income, high-spending segment represents 19.5% of customers.
- The high-income, low-spending segment represents 17.5% of customers and may offer an opportunity for further investigation.

## Limitations
Spending score is not actual spending or profit. The analysis identifies patterns in this dataset but cannot establish why customers behave as they do. Recommendations should be tested before implementation.

## Project Files
- `Customer_Segmentation.ipynb` — analysis notebook.
- `Mall_Customers.csv` — dataset used.
- `screenshots/` — project evidence and visualisations.

## Conclusion
K-Means clustering revealed five customer groups with different income and spending-score patterns. These insights can support more targeted marketing hypotheses and further customer research.
