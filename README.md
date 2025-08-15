# Customer-segmentation-using-Kmeans-clustering
This project demonstrates not only technical skills in data preprocessing, clustering, and visualization but also business insight by translating numerical outputs into actionable marketing recommendations. It serves as a strong example of how data science can support data-driven decision-making in customer relationship management.

📊 Workflow
1. Data Exploration & EDA

Loaded dataset and checked for structure & missing values.

Explored distributions of Annual Income and Spending Score.

Visualized patterns using histograms, scatter plots, and pair plots.

2. Feature Selection & Scaling

Selected Annual Income (k$) and Spending Score (1-100) for clustering.

Applied StandardScaler to normalize feature values.

3. Finding Optimal Clusters

Elbow Method — identified point of diminishing returns.

Silhouette Score — validated cluster separation quality.

KneeLocator — automated optimal cluster detection.

4. Model Training

Trained K-Means with optimal cluster count.

Assigned each customer a cluster label.

5. Visualization & Profiling

Created color-coded scatter plots with centroids marked.

Calculated average income & spending score for each cluster.

Named clusters for easy interpretation (VIPs, Balanced Spenders, Value Seekers, etc.).

6. Output

Saved results in clustered_customers.csv.

Ready for integration into marketing dashboards or CRM systems.

💡 Business Applications

VIP Customers: Offer premium deals and loyalty programs.

Trendy Low-Income Spenders: Introduce affordable, stylish products.

Wealthy Low Spenders: Upsell premium products via targeted campaigns.

Budget-Conscious Customers: Use discounts & offers to boost sales.

🛠 Tech Stack

Programming: Python

Libraries: Pandas, NumPy, scikit-learn, matplotlib, seaborn, kneed
