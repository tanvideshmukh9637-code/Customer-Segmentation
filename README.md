
# Customer Segmentation Using K-Means Clustering

## 📌 Project Overview

This project focuses on segmenting mall customers based on their Annual Income and Spending Score using the K-Means Clustering algorithm.

The objective is to identify different customer groups based on their purchasing behavior, helping businesses understand customer patterns and make data-driven marketing decisions.

## 🎯 Objectives

* Analyze customer demographics and spending behavior.
* Perform Exploratory Data Analysis (EDA).
* Identify customer segments using K-Means Clustering.
* Determine the optimal number of clusters using the Elbow Method.
* Visualize customer segments.
* Predict the cluster of a new customer.

## 🛠️ Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

## 📂 Dataset

**Dataset:** Mall Customers Dataset (`Mall_Customers.csv`)

The dataset contains customer information, including:

* CustomerID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1-100)

## ⚙️ Project Workflow

### 1. Data Loading

Imported the dataset using Pandas.

### 2. Data Understanding

* Checked dataset dimensions.
* Examined data types and statistical summaries.
* Checked missing values and duplicate records.
* Removed duplicate records.

### 3. Exploratory Data Analysis (EDA)

Created histograms to understand:

* Age Distribution
* Annual Income Distribution
* Spending Score Distribution

### 4. Feature Selection

Selected two features for clustering:

* Annual Income (k$)
* Spending Score (1-100)

### 5. Feature Scaling

Applied StandardScaler to standardize the selected features before clustering.

### 6. Optimal Cluster Selection

Used the Elbow Method with WCSS (Within-Cluster Sum of Squares) to determine a suitable number of clusters.

### 7. Model Building

Implemented the K-Means Clustering algorithm with 5 clusters using Scikit-learn.

### 8. Cluster Visualization

Visualized customer segments using a scatter plot.

### 9. Cluster Analysis

Prepared a cluster-wise summary using:

* Average Age
* Average Annual Income
* Average Spending Score

### 10. New Customer Prediction

Applied the trained K-Means model to assign a cluster to a new customer based on their income and spending score.

## 📊 Results

* Segmented customers into 5 clusters.
* Visualized customer groups based on income and spending behavior.
* Demonstrated how clustering can help identify different customer profiles.
* Implemented cluster prediction for a new customer.

## 💡 Business Applications

* Customer profiling
* Targeted marketing campaigns
* Personalized offers
* Customer behavior analysis
* Business decision-making

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/Customer-Segmentation.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Customer-Segmentation
   ```

3. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib scikit-learn jupyter
   ```

4. Keep `Mall_Customers.csv` in the project directory.

5. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Run the notebook cells sequentially.

## 👩‍💻 Author

**Komal Kamble**

Computer Engineering Graduate | Aspiring Data Analyst / Machine Learning Enthusiast
