# Customer Segmentation Analysis

## Objective
The objective of this project is to segment customers based on their income, age, and purchasing behavior using K-Means clustering, to support targeted marketing strategies.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (StandardScaler, KMeans)

## Dataset Features
- Income, Age, Recency
- Spending across product categories (Wines, Fruits, Meat, Fish, Sweets, Gold)
- Purchase channels (Web, Catalog, Store)
- Marketing campaign acceptance
- MntTotal (total spending)

## Analysis Performed
- Data Cleaning (duplicate removal, missing value check)
- Descriptive Statistics
- Feature Scaling (StandardScaler)
- Elbow Method to determine optimal cluster count
- K-Means Clustering (k=4)
- Cluster Visualization (scatter plots, bar chart, correlation heatmap)

## Key Insights
- Customers were grouped into 4 segments based on Income, Age, and Total Spending.
- Spending is driven primarily by income level, not age — high-income clusters spend similarly regardless of age gap.
- Low and moderate income clusters show consistently lower spending across age groups.

## Conclusion
The segmentation reveals that income is the strongest driver of customer spending behavior, more so than age. This insight can guide targeted marketing: premium offerings for high-income segments, and budget-friendly campaigns for lower-income segments.
