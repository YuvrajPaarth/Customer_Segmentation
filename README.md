🎯 CUSTOMER SEGMENTATION USING K-MEANS CLUSTERING

An in-depth implementation of K-Means Clustering to analyze and segment customers based on their spending patterns and demographic data. This project helps identify distinct customer groups, enabling businesses to implement targeted marketing strategies effectively.

📑 TABLE OF CONTENTS
	1.	Overview
	2.	📂 Dataset Details
	3.	🛠️ Tools & Libraries
	4.	🚀 Installation & Setup
	5.	🔍 Step-by-Step Analysis
	6.	📊 Results & Key Insights
	7.	✨ Visualization
	8.	💻 How to Use
	9.	📚 References

📌 OVERVIEW

Customer segmentation involves categorizing customers into distinct groups based on shared characteristics. This project uses K-Means Clustering to analyze customer data from a mall and identify behavioral patterns that can drive business decisions.

💡 Objective
	•	Group customers based on Annual Income and Spending Score.
	•	Understand different customer profiles for personalized marketing.

📂 DATASET DETAILS

The dataset includes the following features:
	•	CustomerID: Unique identifier for each customer.
	•	Gender: Customer’s gender.
	•	Age: Customer’s age.
	•	Annual Income (k$): Annual income of the customer in thousands of dollars.
	•	Spending Score (1-100): Score assigned based on spending behavior and loyalty.

🔗 Source: Kaggle: Mall Customers Dataset

🛠️ TOOLS & LIBRARIES

The following libraries were used:
	•	Python: Core programming language.
	•	Pandas: Data manipulation and preprocessing.
	•	NumPy: Mathematical computations.
	•	Matplotlib & Seaborn: Data visualization.
	•	Scikit-learn: K-Means clustering and machine learning tools.

🚀 INSTALLATION & SETUP

1️⃣ Prerequisites

Ensure you have Python 3.6+ installed.

2️⃣ Install Required Libraries

Run the following command to install dependencies:

pip install numpy pandas matplotlib seaborn scikit-learn kagglehub

3️⃣ Download Dataset

Use the kagglehub library to fetch the dataset:

import kagglehub
path = kagglehub.dataset_download("vjchoudhary7/customer-segmentation-tutorial-in-python")

🔍 STEP-BY-STEP ANALYSIS

1️⃣ Data Loading & Cleaning
	•	Load the dataset and handle missing values (if any).
	•	Inspect data structure using descriptive statistics.

2️⃣ Feature Selection
	•	Extract Annual Income and Spending Score for clustering.

3️⃣ Determine Optimal Clusters
	•	Use WCSS (Within-Cluster Sum of Squares) and the Elbow Method to identify the optimal number of clusters (k=5).

4️⃣ Apply K-Means Clustering
	•	Train the K-Means model with 5 clusters.
	•	Assign cluster labels to each customer.

5️⃣ Visualization
	•	Visualize clusters and centroids using scatter plots.

📊 RESULTS & KEY INSIGHTS
	•	Optimal Clusters: 5 groups of customers were identified using the Elbow Method.
	•	Cluster Profiles:
	•	High income, low spending.
	•	Moderate income, high spending.
	•	Low income, low spending, etc.
	•	Business Use Case: Enables targeted marketing campaigns for each group.

✨ VISUALIZATION

🎨 Cluster Scatter Plot

Clusters are visualized with different colors, and the centroids are highlighted:

<img src="https://via.placeholder.com/800x400.png?text=Cluster+Visualization" alt="Cluster Visualization" style="width:80%; border:1px solid #ccc; display:block; margin:auto;">


💻 HOW TO USE
	1.	Run the script in a Python IDE or notebook.
	2.	Modify the dataset or clustering features if needed.
	3.	Visualize results and interpret customer groups.

Using with a Different Dataset
	•	Replace the data loading and preprocessing steps.
	•	Ensure selected features are numerical.

📚 REFERENCES
	1.	Kaggle: Mall Customers Dataset
	2.	Scikit-learn Documentation
	3.	Matplotlib Documentation
	4.	Seaborn Documentation

👨‍💻 Author: Yuvraj
📧 Contact: yuvraj.works1@gmail.com
📜 License: MIT

⭐️ If you found this helpful, feel free to share and star this repository!
