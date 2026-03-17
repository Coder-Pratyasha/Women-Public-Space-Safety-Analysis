# 🚺 Women Safety Analysis using Clustering  

---

## 📌 Overview  

This project analyzes women's safety in public spaces using survey data and unsupervised machine learning techniques. It identifies patterns in safety perception and infrastructure, grouping locations into clusters such as:

- ✔ Safe  
- ✔ Moderately Safe  
- ✔ Unsafe  

---

## 🎯 Objectives  

- Analyze safety conditions across public places  
- Combine infrastructure and perception-based features  
- Apply clustering algorithms to detect patterns  
- Provide insights for urban safety improvements  

---


## 📊 Dataset  

- Collected via **Google Forms**  
- Approximately **550 responses**  
- Mix of:
  - **Objective data** (infrastructure)  
  - **Subjective data** (perception)  

---

## 🔑 Features  

| Feature | Type |
|--------|------|
| Type_of_Public_Place | Nominal |
| Mode_of_Transport | Nominal |
| Crowd_Level | Ordinal |
| Lighting_Condition | Ordinal |
| CCTV_Available | Binary |
| Security_in_Public_Place | Binary |
| Safe_Visiting_Alone | Binary |
| Avoid_Going_Out_At_Night | Binary |
| Experienced_Harassment | Binary |

---

## ⚙️ Methodology  

### 🔹 Data Processing  
- Data Cleaning (handling missing values, standardization)  
- Data Preprocessing (encoding categorical variables)  

### 🔹 Feature Engineering  
- Infrastructure Score  
- Perception Score  
- Safety Score  

### 🔹 Model Pipeline  
- Outlier Removal (IQR Method)  
- Data Aggregation (place-wise averaging)  
- Feature Scaling (StandardScaler)  

### 🔹 Clustering Algorithms  
- K-Means Clustering  
- Hierarchical Clustering  
  - Ward Linkage  
  - Average Linkage  

### 🔹 Ensemble Learning  
- Majority voting across clustering methods  

### 🔹 Evaluation  
- Silhouette Score  

---

## 📈 Visualizations  

- 📍 Scatter Plots (Cluster visualization)  
- 🌳 Dendrograms (Hierarchical clustering)  
- 🔥 Heatmaps (Safety comparison)  
- 📊 Bar Charts (Safety scores)  

---

## 🧠 Results  

- Successfully identified distinct safety clusters  
- Highlighted differences between infrastructure vs perception  
- Revealed areas needing improvement in safety measures  

---

## 💡 Applications  

- Urban Planning  
- Public Safety Policy  
- Smart City Development  
- Awareness & Decision Making  

---

## 🚀 Future Scope  

- Add demographic & location-based features  
- Use advanced ML models  
- Expand dataset size  
