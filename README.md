# Mall Customer Segmentation (KMeans Clustering)
This project performs customer segmentation on the Mall_Customers dataset using the KMeans clustering algorithm.
The aim is to group customers based on their Annual Income and Spending Score to understand different customer types.

📂 Dataset
The dataset Mall_Customers.csv contains the following columns:

CustomerID — Unique ID assigned to each customer

Gender — Gender of the customer

Age — Age of the customer

Annual Income (k$) — Annual income in thousands of dollars

Spending Score (1-100) — Score assigned based on customer behavior and spending nature

🛠 Requirements
To run this project, install the following Python libraries:
-pip install pandas matplotlib scikit-learn

🚀 How to Run
Clone the repository:

git clone https://github.com/yashvi-data-analyst/Mall-Customer-Segmentation.git
cd Mall-Customer-Segmentation
Place the dataset Mall_Customers.csv in the project directory (already included).

Run the Python script:
-python customer_segmentation.py

📊 Project Workflow
Import Libraries & Dataset

Select Features — Using Annual Income & Spending Score

Find Optimal Number of Clusters — Using the Elbow Method

Apply KMeans Clustering — Group customers into segments

Save Plots — Save both elbow method plot and customer segmentation plot as PNG files

🖼 Output
Elbow Method Plot
Helps determine the optimal number of clusters.
Saved as: elbow_method.png



Customer Segments Plot
Shows customer groups in different colors based on their annual income and spending score.
Saved as: customer_segments.png



📌 Files in Repository
Mall_Customers.csv          # Dataset
customer_segmentation.py    # Main Python script
elbow_method.png            # Elbow method plot
customer_segments.png       # KMeans segmentation plot
README.md                   # Project documentation
💡 Insights
Customers with high income & high spending score are the most valuable.

Low income & low spending score group may need promotions to increase engagement.

Middle segments can be targeted for upselling strategies.


## 🎥 Demo

You can watch the step-by-step execution of this project in the following screen recording:

[![Watch the demo](https://drive.google.com/file/d/1ogJmlzBOE5Bur_sM9AW1Y-M79cWcYEQt/view?usp=drivesdk)


✍ Author
Yashvi Verma
Data Analyst | Machine Learning Enthusiast

