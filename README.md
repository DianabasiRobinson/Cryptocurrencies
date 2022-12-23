# Cryptocurrencies
## Project Overview
This analysis provide a report that includes which cryptocurrencies are on the trading market and grouping them to create a classification system for cryptocurrency investment portfolio for bank's customers through unsupervised learning, clustering algorithm and data visualizations.

## Results
First the cryptocurrencies data was cleaned:

- only cryptocurrencies that are being traded, have a working algorithm and mine coins are kept

- Dropped null values 

- only relevant columns that are needed for the analysis are used

![Clean](https://user-images.githubusercontent.com/109990578/209356498-4ce17a2c-1f87-4346-ab3b-f42beb1060c1.png)

- Then the data was standardized using StandardScaler() and reducing PCA dimension to three components

![PCA](https://user-images.githubusercontent.com/109990578/209356786-6a1073c9-a152-4eaf-bff2-7887741c87af.png)

- Also, Elbow Curve for the optimal cluster amount (4) was found

![Ecurve](https://user-images.githubusercontent.com/109990578/209356907-db8fe8cf-8e18-42a9-9054-67b22d258e4b.png)

- A new dataframe is created using K-means predictions for four clusters and three principal components

![Kmeans](https://user-images.githubusercontent.com/109990578/209357049-0a44fefb-786f-4e7d-bd05-8f091f3c7d70.png)

- A 3D-Scatter plot with the PCA data and the clusters is created

![3Dscatter](https://user-images.githubusercontent.com/109990578/209357154-ced1f394-382f-4fea-b30c-4cecc1dacad4.png)

- A scatter plot showing total amount of coins mined and total coin supply is created

![hvplot](https://user-images.githubusercontent.com/109990578/209357411-b0f445fc-874b-41a1-8010-2f35338d4437.png)

## Summary
With this analysis, bank team can offer a new cryptocurrency investment portfolio for its customers.

