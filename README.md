# 🧠 Customer Segmentation using K-Means Clustering

This project demonstrates how to apply **K-Means Clustering** on customer data to identify distinct customer segments based on their annual income and spending score.

---

## 📌 Objective

To use **unsupervised machine learning** (K-Means Clustering) for segmenting mall customers into distinct groups that exhibit similar purchasing behavior.

---

## 📂 Dataset

- **Source:** [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **File:** `Mall_Customers.csv`
- **Attributes:**
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🔧 Tools & Libraries

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib
- kaggle (for dataset download)

---

## 🧪 Steps Performed

1. **Data Loading & Cleaning**
   - Renamed columns
   - Removed duplicates
   - Checked for null values

2. **Exploratory Data Analysis (EDA)**
   - Pairplot visualization
   - Elbow Method to find optimal clusters

3. **Model Building**
   - KMeans clustering using `income` and `spending score`
   - Optimal clusters: `5`

4. **Visualization**
   - Scatter plot of clusters
   - Gender distribution per cluster

5. **Model Saving**
   - Saved clustering results as CSV
   - Exported trained model using `joblib`

---

## 📈 Key Visualizations

- **Elbow Method Plot**
- **Clustered Scatter Plot (Spending Score vs Income)**
- **Gender Distribution across Clusters**

---

## 📊 Output

- `clustered_customers.csv`: Data with cluster labels.
- `kmeans_model.pkl`: Trained KMeans model.
- `cluster_summary`: Mean age, income, and score per cluster.

---

## 📁 Folder Structure

project/
│
├── Mall_Customers.csv
├── customer_segmentation.ipynb
├── clustered_customers.csv
├── kmeans_model.pkl
└── README.md

