# Task 8 - K-Means Clustering

## 🎯 Objective
Segment mall customers into distinct groups using K-Means clustering based on their annual income and spending score.

## 📁 Dataset
- Name: `Mall_Customers.csv`
- Source: [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 🧪 Steps Performed
1. Loaded and explored the dataset
2. Selected relevant features for clustering
3. Applied the Elbow Method to find the optimal number of clusters
4. Implemented K-Means clustering with optimal `k`
5. Visualized the resulting customer clusters
6. Evaluated model performance using Silhouette Score

## ✅ Sample Output

📥 Dataset loaded successfully:
CustomerID Gender Age Annual Income (k$) Spending Score (1-100)
0 1 Male 19 15 39
1 2 Male 21 15 81
2 3 Female 20 16 6
3 4 Female 23 16 77
4 5 Female 31 17 40


📈 Elbow Method Output:
- Optimal number of clusters: **5**

📊 Silhouette Score: `0.55`

🧬 Cluster Labels assigned:

🎨 Cluster visualization shown with distinct colors.

## 📌 Feature Importances
(Not applicable to K-Means — all features used equally)

## 💡 What I Learned
- How to implement **K-Means clustering** for unsupervised learning
- How to determine the optimal number of clusters using the **Elbow Method**
- How to evaluate cluster cohesion using the **Silhouette Score**
- How to visualize high-dimensional customer segmentation data

## 📊 Plots Generated
- Elbow Method plot for `k` selection
- Scatter plot showing the 5 customer clusters

## 📤 Submission Files
- `task8.py` – Python code for clustering
- `Mall_Customers.csv` – Dataset file
  
