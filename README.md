# Customer Segmentation - RFM Analysis

**Author:** Antoni Šitum  
**Service:** CHI-SQUARE - Data Science for Business

## Overview
Customer segmentation using RFM analysis (Recency, Frequency, Monetary) and K-means clustering to identify distinct customer groups for targeted marketing strategies.

## Dataset
- Superstore dataset (9,994 transactions)
- 793 unique customers
- Period: 2014-2017

## Methodology
- **RFM Metrics:** Recency (days since last purchase), Frequency (number of orders), Monetary (total sales)
- **Clustering:** K-means (k=3, optimal by silhouette score)
- **Alternative method:** DBSCAN for comparison

## Results

| Segment | Type | Customers | Revenue Share |
|---------|------|-----------|---------------|
| Segment 0 | Standard | 453 (57.1%) | 36.7% |
| Segment 1 | Loyal | 230 (29.0%) | 55.6% |
| Segment 2 | Occasional | 110 (13.9%) | 7.7% |

## Key Insights
- **Loyal customers (29% of base) generate 55.6% of total revenue**
- Standard customers represent majority (57%) but lower spending
- Occasional customers (14%) need reactivation campaigns

## Technologies
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- K-means, DBSCAN
- RFM analysis

## Contact
Antoni Šitum – chisquare.analiza@gmail.com  
CHI-SQUARE – Data science for businesses
