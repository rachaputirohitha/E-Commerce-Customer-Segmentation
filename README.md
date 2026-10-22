# E-Commerce Customer Segmentation Using RFM Analysis

## Project Overview
This project analyzes e-commerce transaction data to understand customer purchasing behavior and identify meaningful customer segments using RFM analysis.

## Objectives
- Analyze customer purchasing patterns.
- Calculate Recency, Frequency, and Monetary values.
- Segment customers based on their RFM scores.
- Apply K-Means clustering to identify customer groups.
- Present key insights through an interactive Power BI dashboard.

## Tools and Technologies
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Microsoft Excel
- Microsoft Power BI

## Dataset
The project uses the UCI Online Retail dataset, which contains transaction records from an online retail business.

## Methodology
1. Load and explore the transaction dataset.
2. Clean the data by handling missing values, duplicate records, cancelled invoices, and invalid quantities or prices.
3. Calculate transaction amounts.
4. Aggregate transaction data at the customer level.
5. Calculate RFM metrics:
   - **Recency:** Days since the customer's most recent purchase.
   - **Frequency:** Number of distinct invoices per customer.
   - **Monetary:** Total customer spending.
6. Assign RFM scores and create rule-based customer segments.
7. Apply K-Means clustering using scaled frequency and monetary features.
8. Summarize and visualize customer segments.

## Project Results
- Cleaned transaction records: **392,692**
- Unique customers analyzed: **4,338**
- Customer segmentation using RFM scoring.
- Additional customer grouping using K-Means clustering with four clusters.

## Customer Segments
The rule-based segmentation includes:
- Champions
- Loyal Customers
- New / Promising
- Potential Loyalists
- At-Risk Customers
- Lost / Hibernating
- Regular Customers

## Power BI Dashboard
The Power BI report presents customer and revenue metrics, customer segment distribution, revenue by customer segment, and customer cluster analysis.

## Files Included
- `E-Commerce_Customer_Segmentation.pbix` — Power BI report.
- `RFM_Customer_Segmentation_Results.xlsx` — cleaned data, customer RFM metrics, and segment summary.
- Google Colab notebook, if included — Python analysis and modeling workflow.

## Conclusion
This project demonstrates how RFM analysis and K-Means clustering can help an e-commerce business understand customer behavior, recognize valuable customer groups, and make more informed customer-retention and marketing decisions.

## Dashboard Screenshot
<img width="943" height="533" alt="E-Commerce_Customer_Segmentation pbix" src="https://github.com/user-attachments/assets/ace66cbe-7269-496c-a9d2-ec3075742379" />

## Excell Screenshots
<img width="1600" height="900" alt="Screenshot (594)" src="https://github.com/user-attachments/assets/663de230-ab95-4062-b496-a9d32d0cd5ef" />

<img width="1600" height="900" alt="Screenshot (595)" src="https://github.com/user-attachments/assets/54ea0fcf-17cb-4055-8efa-6e6312d2517d" />


