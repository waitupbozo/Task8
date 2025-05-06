# Customer Segmentation using K-Means Clustering 🛍️

This project demonstrates customer segmentation using the K-Means clustering algorithm in Python. We analyze a dataset of mall customers to identify distinct customer groups based on their annual income and spending score.

## 📝 Project Overview

The goal of this project is to group customers into different segments based on their purchasing behavior. This information can be valuable for targeted marketing campaigns, personalized recommendations, and improving customer satisfaction.

## 🚀 Steps Involved

1. **Import Libraries and Load Data:** 📚
   - Import necessary libraries like pandas, numpy, matplotlib, seaborn, and scikit-learn.
   - Load the 'Mall_Customers.csv' dataset into a pandas DataFrame.

2. **Data Preprocessing and Analysis:** 📊
   - Inspect the dataset using `head()` and `info()` to understand its structure and data types.
   - Check for and handle any missing values or duplicates.
   - Perform exploratory data visualization using scatter plots to understand the relationship between annual income and spending score.

3. **Elbow Method for Optimal K:** 📐
   - Use the Elbow method to determine the optimal number of clusters (K) for K-Means.
   - Visualize the WCSS (Within-Cluster Sum of Squares) values for different K values using a line plot.
   - Identify the elbow point on the plot, which indicates the optimal K value.

4. **Outlier Detection with Isolation Forest:** 🕵️‍♀️
   - Utilize the Isolation Forest algorithm to identify potential outliers in the data.
   - Create a cleaned dataset by removing the identified outliers.

5. **K-Means Clustering:** 🎯
   - Apply the K-Means algorithm with the optimal K value (5 in this case) to the cleaned dataset.
   - Assign each customer to a cluster based on their features.

6. **Cluster Visualization:** 📈
   - Create a scatter plot to visualize the customer segments.
   - Use different colors to represent different clusters.
   - Plot the cluster centroids to highlight the cluster centers.

7. **Model Evaluation:** ✅
   - Evaluate the clustering model using the Silhouette Score metric.
   - The Silhouette Score obtained for this model is **0.57**, indicating a reasonably good clustering structure.
   - Interpret the Silhouette Score to assess the quality of the clusters.
   - Usually, a Silhouette Score > 0.5 suggests a good structure, and a score > 0.7 indicates an excellent structure.

## 💡 Insights and Conclusion

- The project successfully identifies distinct customer segments based on annual income and spending score.
- Businesses can use these segments for targeted marketing and personalized recommendations.
- The Silhouette Score of 0.57 suggests a reasonably good clustering solution.
- Further analysis can be conducted to understand the characteristics of each segment and tailor strategies accordingly.

## 🧰 Tools and Technologies

- **Python:** Programming language
- **Pandas:** Data manipulation and analysis library
- **NumPy:** Numerical computing library
- **Matplotlib:** Data visualization library
- **Seaborn:** Statistical data visualization library
- **Scikit-learn:** Machine learning library

## 🤝 Contributions

Contributions to this project are welcome! Feel free to open issues or pull requests.
