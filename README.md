# 🎓 Clustering & Classification Analysis on QS World University Rankings 2026

## Project Overview
This project is part of a Machine Learning capstone focused on applying **unsupervised** and **supervised learning** techniques to the **QS World University Rankings 2026** dataset.  
The goal is to analyze and classify universities based on performance indicators such as **academic reputation**, **employer reputation**, and **research strength**.

### Objectives
- Identify patterns and clusters among global universities.  
- Group universities into meaningful clusters using **K-Means** and **Hierarchical Clustering**.  
- Predict ranking tiers through **Random Forest Classification**.  
- Determine the most influential features driving university performance.

### Dataset 
The dataset csv file used for this project is available on this repository 
and on Kaggle:  
👉 [Kaggle Dataset Link](https://www.kaggle.com/datasets/akashbommidi/2026-qs-world-university-rankings) 

---

##  Challenges

### Challenge 1: Exploratory Data Analysis (EDA)
- Explored dataset structure, data types, and missing values.  
- Visualized data distributions, outliers, and country-wise university counts.  

### Challenge 2: Unsupervised Learning
- Implemented **K-Means Clustering** and identified the optimal `k` using the **Elbow Method** and **Silhouette Score**.  
- Used **PCA** (Principal Component Analysis) to visualize clusters in 2D space.  
- Applied **Hierarchical Clustering** with **Ward linkage** and visualized results using a **dendrogram**.

### Challenge 3: Supervised Learning – Rank Tier Classification
- Created ranking tiers:
  -  Top 100  
  -  101–300  
  -  301–600  
  -  601+  
- Trained a **RandomForestClassifier** to predict tiers.  
- Optimized the model using **GridSearchCV**.  
- Visualized **feature importance** to understand which factors most influenced ranking outcomes.

---

##  Key Findings
- Universities naturally cluster into **three distinct groups** based on academic and international metrics.  
- **Academic Reputation** and **Employer Reputation** are the strongest predictors of rank.  
- The optimized **Random Forest model** achieved **over 90% accuracy** in predicting university tiers.  

---

##  Technologies Used
- **Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, scipy  
- **Environment:** Google Colab / Jupyter Notebook  

---

##  How to Run the Analysis

### Clone the Repository
```bash
git clone https://github.com/sindhuja469/clustering.git

### To execute the notebook:
```bash
jupyter notebook clustering.ipynb

```bash
