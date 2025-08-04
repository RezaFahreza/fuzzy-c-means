# Customer Segmentation using Fuzzy C-Means Clustering on Credit Card Data

This project uses the **Fuzzy C-Means (FCM)** clustering algorithm to segment credit card customers based on spending behavior and other attributes.

## 🧠 Clustering Method & Parameters

FCM was applied with the following settings:

- Fuzzification coefficient `m = 2`
- Convergence error threshold = `0.01`
- Maximum iterations = `1000`

A Grid Search was conducted to find the optimal number of clusters `c`, with values tested from 2 to 9. Clustering performance was evaluated using:

- Final Partition Coefficient (FPC)  
- Partition Entropy (PE)  
- Xie-Beni Index

## 📊 Results

- **Optimal number of clusters**: 2  
- **FPC score**: 0.757

These results indicate good clustering compactness and separation, suggesting that FCM is effective for customer segmentation in financial datasets. This approach is useful for tasks like **targeted marketing** and **credit risk analysis**.
