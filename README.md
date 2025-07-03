# Customer-Segmentation-Data-for-Marketing-Analysis

### 📌 Problem
Segment customers into meaningful groups for targeted marketing.

## 🚀 Workflow Overview

1. **Data Preprocessing**   
   - Handled categorical features  
   - Removed null values if any

2. **Feature Scaling**   
   - Applied `StandardScaler` for normalization

3. **Finding Optimal Clusters** 📉  
   - Used **Elbow Method** to choose ideal `k`

4. **KMeans Clustering**   
   - Clustered the dataset into groups

5. **Dimensionality Reduction (PCA)**   
   - Visualized clusters in 2D

6. **Cluster Analysis**   
   - Analyzed feature distributions across clusters using **Boxplots**

## 📊 Results

- Identified **4 distinct customer clusters**
- Output saved to CSV with cluster labels

---

  ## 🖼️ Visualizations

### 📌 PCA Cluster Plot
![PCA Clusters](![image](https://github.com/user-attachments/assets/c7d3dd80-4388-42a2-acaf-12bee6439431))

### 📌 Elbow Method
![Elbow Method](![image](https://github.com/user-attachments/assets/8671e20a-172f-4ce3-b548-25924b62a722))

### 📌 Boxplot Analysis

#### Age Distribution by Cluster
![Age Boxplot](![image](https://github.com/user-attachments/assets/bcc0cb40-dd5c-41e8-ab92-cceac92f9800))

#### Income Distribution by Cluster
![Income Boxplot](![image](https://github.com/user-attachments/assets/17b61a23-9baf-4fb9-a9fb-21967c64fed1))

#### Spending Score by Cluster
![Spending Boxplot](![image](https://github.com/user-attachments/assets/8d6be7ea-0ffb-4477-9a6d-e37f9d10cfff))

---

## 📁 Output

![Output CSV](![image](https://github.com/user-attachments/assets/47ea98b5-70ad-42c8-bbfc-95fa7870f129))

---

## 🛠️ Tools & Libraries
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

