# 🛍️ Customer Segmentation using KMeans & DBSCAN  

## 📌 Project Overview  
This project applies **Machine Learning clustering algorithms** to segment customers based on their **Annual Income** and **Spending Score**.  
The aim is to help businesses understand their customer base, enabling **personalized marketing**, **targeted campaigns**, and better **resource allocation**.  

We implement two approaches:  
- ✅ **KMeans Clustering** → Finds optimal customer groups using the **Elbow Method**  
- ✅ **DBSCAN Clustering (Bonus)** → Identifies arbitrary-shaped clusters and noise/outliers  

---

## 📂 Datasets  
- **Mall Customers Dataset (Kaggle)**  
  - Features used:  
    - `Annual Income (k$)`  
    - `Spending Score (1-100)`  

---

## ⚙️ Tech Stack  
- **Python 3**  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  

---

## 🚀 Workflow  

### 1️⃣ Data Preprocessing  
- Handle missing values (if any)  
- Select relevant features  
- Apply **Standard Scaling**  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Scatter plots of income vs. spending  
- Visual distribution of customer profiles  

### 3️⃣ KMeans Clustering  
- Use **Elbow Method** to determine optimal clusters  
- Apply **KMeans** with chosen K  
- Visualize customer segments  

### 4️⃣ DBSCAN Clustering (Bonus)  
- Apply **Density-Based Spatial Clustering**  
- Detect **outliers & noise** in customer data  
- Compare with KMeans results  

### 5️⃣ Cluster Analysis  
- Calculate **average income** and **spending score** per cluster  
- Interpret **customer personas** (e.g., High Income – High Spending, Low Income – Low Spending)  

---

## 📊 Results & Visualizations  

### 🔹 Elbow Method  
Helps determine optimal number of clusters for KMeans.  

![Elbow Method](figures/elbow.png)  

### 🔹 KMeans Clustering  
Customer groups based on income & spending.  

![KMeans](figures/kmeans_clusters.png)  

### 🔹 DBSCAN Clustering  
Density-based clusters with outliers detected.  

![DBSCAN](figures/dbscan_clusters.png)  

---

## 🎯 Insights  
- **KMeans** is effective for well-separated clusters.  
- **DBSCAN** detects anomalies (e.g., very high-income or low-spending customers).  
- Businesses can:  
  - Target **high spenders** with loyalty programs.  
  - Design offers for **medium-income customers** to increase spending.  
  - Identify **outlier customers** with unique spending behavior.  

---

## 📌 Future Work  
- Extend clustering to **3D (Income, Spending, Age)**  
- Apply **Hierarchical Clustering** for comparison  
- Deploy as an **interactive dashboard** with Streamlit  

---

## 👨‍💻 Author  
**Mirza Mukarram**  
- 📎 [LinkedIn](https://www.linkedin.com/in/mukarram0)  
- 💻 [GitHub](https://github.com/MirzaMukarram0)  

---
✨ *Uncovering customer personas with Machine Learning for smarter business strategies!* ✨
