# Mall Customer Segmentation (KMeans Clustering)

This project performs customer segmentation on the **Mall_Customers** dataset using the KMeans clustering algorithm.  
The aim is to group customers based on their **Annual Income** and **Spending Score** to understand different customer types.

---

## 📌 Features
- **Data Preprocessing**: Selects relevant features for clustering
- **Elbow Method**: Finds the optimal number of clusters
- **KMeans Clustering**: Groups customers into segments
- **Visualization**: Displays cluster distribution with centroids
- **Data Export**: Saves segmented customer data into a CSV file

---

## 📂 Project Structure

├── customer_segmentation.py # Main script
├── Mall_Customers.csv # Dataset
├── clustered_customers.csv # Output with clusters
├── plots/
│ ├── elbow_method.png # Elbow method graph
│ └── customer_segments.png # Segmentation result
└── README.md # Project description


## 🚀 How to Run
1. **Clone the Repository**
   1. **Clone the Repository**
   1. **Clone the Repository**
   ```bash
   git clone https://github.com/yashvi-data-analyst/Mall-Customer-Segmentation.git
   cd mall-customer-segmentation

📊 Sample Visualizations
1. Elbow Method (Choosing Optimal Clusters)
2. Customer Segmentation Result

📜 Output
clustered_customers.csv contains original data + cluster labels:

CustomerID	Annual Income (k$)	Spending Score (1-100)	Cluster
1	15	39	4
2	15	81	2
...	...	...	...

🛠 Tools & Libraries

-Python 3.x
-Pandas
-Matplotlib
-Scikit-learn

✨ Project by Yashvi Verma 


 









