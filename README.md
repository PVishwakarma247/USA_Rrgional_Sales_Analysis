# USA Regional Sales Analysis

This project provides an in-depth exploratory data analysis (EDA) of Acme Co.’s 2014–2018 USA sales data. The goal is to uncover key revenue and profit drivers across products, channels, and regions, and to deliver actionable insights for strategic decision-making.


## Workspace Structure

```
EDA_Regional_Sales_Analysis.ipynb      # Main analysis notebook
Regional Sales Dataset.xlsx            # Source Excel data
sample data/
    Regional Sales Dataset.xlsx        # Copy of source data
    Sales_data(EDA Exported).csv       # Cleaned/exported data for BI/dashboard
Background/
    1.jpg, Page 1.png, ...             # Images for reporting/presentation
PPT --- Regional Sales Analysis.pptx   # PowerPoint summary
SALES REPORT.pbix                      # Power BI dashboard
```


## Key Analyses

- Monthly and seasonal sales trends
- Top products by revenue and profit margin
- Channel mix and order value distribution
- Regional and state-level performance
- Customer segmentation and correlation analysis


## Key Insights

- California is the top-performing state, followed by Illinois and Florida.
- Wholesale is the dominant sales channel, but export growth is a major opportunity.
- Top products and customers drive a large share of revenue; margin optimization is possible for mid/low tiers.
- No strong monthly seasonality, but May–June and January are notable for volume changes.
- Profit and revenue are strongly correlated; pricing is the main driver.

<img width="1302" height="727" alt="Screenshot 2025-11-29 110803" src="https://github.com/user-attachments/assets/2f86a02b-dfc8-4d7a-b1da-d5921117f1ac" />

## Installation

```bash
git https://github.com/PVishwakarma247/USA_Rrgional_Sales_Analysis.git
cd USA_Rrgional_Sales_Analysis
```


## Requirements

- Python 3.8+
- pandas
- matplotlib

Install dependencies:

```bash
pip install -r requirements.txt
```


For details, see [EDA_Regional_Sales_Analysis.ipynb](EDA_Regional_Sales_Analysis.ipynb).
