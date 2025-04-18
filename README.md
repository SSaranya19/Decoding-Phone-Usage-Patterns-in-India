# 📱 Decoding Phone Usage Patterns in India

## 🔍 Overview

This project focuses on analyzing mobile device usage patterns across Indian users using machine learning and clustering techniques. By leveraging user and device data, we aim to uncover behavioral trends, classify primary device usage categories, and segment users into distinct behavioral groups. The final deliverable is an interactive **Streamlit application** providing real-time insights, visualizations, and predictive capabilities.

---

## 🎯 Problem Statement

The core objective is to design a robust analytical system that:

- Processes and cleans raw device usage data
- Builds supervised models to classify user’s primary device usage
- Applies unsupervised learning techniques to identify user behavior clusters
- Presents insights via an interactive dashboard built with Streamlit

---

## 💼 Business Use Cases

| Use Case              | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Behavioral Insights    | Analyze how users interact with mobile devices across usage metrics         |
| Device Optimization    | Support manufacturers in improving device design and power consumption     |
| Personalized Services  | Enable telecom and app companies to tailor services and notifications      |
| Energy Efficiency      | Educate users on battery usage patterns and suggest energy-saving practices|

---

## 🧭 Project Approach

### 1. 📦 Data Preparation
- Source: Dataset includes user IDs, device models, OS details, screen/app usage, and battery stats
- Merging multiple data files into a unified structure

### 2. 🧹 Data Cleaning
- Handling missing values using imputation strategies
- Standardizing device model/OS name formats
- Outlier removal using IQR and Z-score techniques

### 3. 🛠️ Feature Engineering
- Created new features such as:
  - Total Phone Usage Time
  - Entertainment Index: average of streaming, gaming, and social media
  - Spend Ratio: E-commerce Spend vs. Recharge Cost
  - Bin Age into age groups
- Encoded categorical features using one-hot and ordinal encoding
- Applied scaling (Standard) to normalize numerical features
- Dimensionality reduction using PCA for clustering visualization

### 4. 📊 Exploratory Data Analysis (EDA)
- Screen time, app usage, and battery drain trend analysis
- Feature correlations visualized using heatmaps and pairplots
- Primary usage class distribution and analysis

### 5. 🧠 Machine Learning & Clustering

#### 📌 Classification Models
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting
- XGBoost
- KNN

**Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

#### 🧩 Clustering Techniques
- K-Means Clustering
- Hierarchical Clustering
- DBSCAN
- Gaussian Mixture Models
- Spectral Clustering

**Evaluation**: Silhouette Score, Cluster Visualization (PCA)


![image](https://github.com/user-attachments/assets/ace1642e-e88c-49c3-aaab-d982647bba6e)



### 6. 🖥️ Application Development (Streamlit)
- Interactive EDA visualizations

  ![s1](https://github.com/user-attachments/assets/649277e9-52bf-46d4-92f4-c6102fc921ab)

  

- Input interface for real-time Primary Use prediction

  ![s2](https://github.com/user-attachments/assets/a84c65fb-9baa-4a6a-9572-aa51e0acc811)
- Clustering result visualization and user segmentation
  ![c1](https://github.com/user-attachments/assets/2f61aa3d-4044-4b80-ac6f-0c825c493da3)
  ![c2](https://github.com/user-attachments/assets/6cf568fb-92e5-49c8-b526-de8c78cb1c50)

### 7. ☁️ Deployment
- Deployed using Streamlit for web accessibility
---

## 🧰 Tech Stack

| Category        | Tools/Libraries |
|----------------|------------------|
| Programming     | Python       |
| Data Handling   | pandas, numpy    |
| Visualization   | seaborn, matplotlib, plotly |
| Machine Learning| scikit-learn, xgboost |
| Clustering      | scipy, sklearn   |
| Deployment      | Streamlit |

---

## 🧪 How to Run the Project Locally

1. **Clone the repository**
```bash
git clone https://github.com/SSaranya19/Decoding-Phone-Usage-Patterns-in-India.git
cd Decoding-Phone-Usage-Patterns-in-India
