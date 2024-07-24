# Market-Segmentation-Unsupervised-Learning

**WHAT IS MARKET SEGMENTATION?**

Market Segmentation In marketing, market segmentation is the process of dividing a broad consumer or business market, normally consisting of existing and potential customers, into sub groups of consumers based on some type of shared characteristics.

**Dimensionality Reduction:**

The use of dimensionality reduction techniques (such as PCA) could have potential benefits in simplifying the data and aiding in visualizing the clustered data. By converting the DataFrame into a 2D DataFrame for visualization, it becomes easier to comprehend and interpret the clusters.

**Hyperparameter Tuning:**

Hyperparameter tuning is mentioned, specifically the process of finding the optimal value of 'k' for K-means clustering using the Elbow Method. This indicates an effort to optimize the clustering algorithm for better performance.

**K-means Clustering:
**
The K-means clustering model shows a Silhouette Score of 0.465 and an Adjusted Rand Index of 0.187. These metrics suggest moderate cluster separation and agreement with the true labels if available.

**Decision Tree Classifier:**

The Decision Tree Classifier demonstrates good performance with high precision, recall, and f1-score for each class, resulting in an overall accuracy of 94%. This indicates that the decision tree is able to effectively classify the data points.

**Hierarchical Clustering:**

The Hierarchical Clustering shows a Cophenetic Correlation Coefficient of 0.330 and a Silhouette Score of 0.173. The Silhouette Score suggests suboptimal cluster cohesion and separation, reflecting the clustering quality.

**Kdesbag Algorithm:**

The Kdesbag Algorithm exhibits an accuracy of 94%, with high precision, recall, and f1-score for each class. This indicates that the Kdesbag Algorithm can effectively classify the data points as well.

Based on these interpretations, the Decision Tree Classifier and Kdesbag Algorithm both demonstrate strong performance in terms of accuracy, precision, recall, and f1-score. K-means clustering also shows promise with a moderate Silhouette Score, but it may necessitate further evaluation and refinement of the cluster assignments. However, it's important to consider the specific requirements of the problem and the nature of the data in determining the most suitable algorithm. Additionally, considering computational cost and interpretability of the model is essential in making a decision.
