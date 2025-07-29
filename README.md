# Sales Correlation Dashboard
## Purpose
This dashboard is designed to analyze the statistical relationship (correlation) between two sets of sales data: internal sales to partners (Sell-In Units) and the final sales from those partners to end-customers (POS Sell-Out). It helps identify how well these two metrics align across different products, markets, and time periods.

## How to Use
1. Upload Files: Use the "Upload Data Files" section to select your Actuals (Sell-In) and POS Sell-Out CSV files.

2. Process Data: Click the "Load and Process Data" button. The application will merge the files based on common columns and prepare them for analysis.

3. Filter Data: Use the various dropdown filters to slice the data by Market Center, Product Family, Customer, etc. The charts and correlation score will update automatically.

4. Analyze Results: Observe the "Trend over Time" and "Units vs. POS Sell-Out" charts. The "Pearson Correlation Coefficient" provides a numerical value for the strength of the relationship for the selected data slice.

5. Reset View: Click the "Clear All Filters" button at any time to return to the high-level, overall view of the entire dataset.

## Understanding the Metrics

**Pearson Correlation Coefficient (r):** This value ranges from -1 to +1.

- A value close to +1 indicates a strong positive correlation (as one value goes up, the other goes up).

- A value close to -1 indicates a strong negative correlation (as one value goes up, the other goes down).

- A value near 0 indicates little to no linear relationship.
