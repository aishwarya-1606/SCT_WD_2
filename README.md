📌 Project Overview

This project performs Customer Segmentation using the K-Means Clustering Algorithm.

A synthetic mall customer dataset (200 customers) is generated inside the code.
Customers are grouped into clusters based on:

Annual Income

Spending Score

This helps businesses understand different customer types for targeted marketing.

🎯 Objective

To segment customers into different groups based on purchasing behavior using unsupervised machine learning.

🛠 Technologies Used

Python

NumPy

Pandas

Matplotlib

Scikit-learn

📂 Dataset Information

The dataset is generated inside the program (no external file required).

Features:
Column Name	Description
CustomerID	Unique customer ID
Gender	Male / Female
Age	Age of customer
Annual Income (k$)	Annual income in thousand dollars
Spending Score (1-100)	Customer spending score

For clustering, only:

Annual Income

Spending Score
are used.

⚙️ Project Workflow
1️⃣ Data Generation

200 random customers are generated using NumPy.

Stored in a Pandas DataFrame.

2️⃣ Feature Selection

Selected features:

Annual Income

Spending Score

3️⃣ Data Standardization

Data is scaled using StandardScaler.

Ensures equal importance to both features.

4️⃣ Elbow Method

WCSS (Within Cluster Sum of Squares) calculated.

Elbow graph plotted to determine optimal number of clusters.

5️⃣ K-Means Clustering

K = 5 clusters selected.

Model trained using scaled data.

Cluster labels assigned to customers.

6️⃣ Visualization

Elbow curve plotted.

Customer clusters visualized in 2D scatter plot.

7️⃣ Output

First 10 clustered customers displayed.

Cluster centers printed.
