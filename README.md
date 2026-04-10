# 🧠 Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project focuses on **Customer Segmentation** using the **K-Means Clustering algorithm**, an unsupervised machine learning technique. The goal is to group customers based on their purchasing behavior and income patterns to help businesses make better marketing decisions.

---

## 🎯 Objectives

* Segment customers into different groups based on similarities
* Identify high-value and low-value customers
* Evaluate clustering performance using various metrics

---

## 📊 Dataset

The project uses the **Mall Customers Dataset**, which contains the following features:

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 🔍 Methodology

### 1. Data Preprocessing

* Selected relevant features:

  * Annual Income
  * Spending Score
* Applied **Standard Scaling** to normalize data

### 2. Finding Optimal Clusters

* Used the **Elbow Method** to determine the best value of K

### 3. Model Building

* Applied **K-Means Clustering**
* Assigned cluster labels to each customer

### 4. Evaluation Metrics

The performance of clustering is evaluated using:

* **Inertia (WCSS)** → Measures compactness of clusters
* **Silhouette Score** → Measures cluster separation (-1 to 1)
* **Davies-Bouldin Index** → Lower value indicates better clustering

---

## 📈 Results

* Optimal number of clusters (K): *5 (based on Elbow Method)*
* Customers were successfully segmented into distinct groups
* Clustering showed good separation and compactness

---

## 📊 Visualization

* Elbow Curve to determine K
* Scatter plot showing customer segments

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
   ```

2. Navigate to the project folder:

   ```bash
   cd customer-segmentation
   ```

3. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

4. Run the script:

   ```bash
   python main.py
   ```

---

## 📌 Project Structure

```
customer-segmentation/
│
├── Mall_Customers.csv
├── main.py
├── README.md
```

---

## 💡 Applications

* Targeted marketing
* Customer retention strategies
* Personalized recommendations
* Business decision-making

---

---
