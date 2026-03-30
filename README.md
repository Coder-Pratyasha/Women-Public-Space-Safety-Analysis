# 🚺 Women Safety Analysis using Clustering

## 📌 Overview

This project analyzes women's safety in public spaces using survey data and unsupervised machine learning techniques. The primary objective is to identify patterns in safety perception and infrastructure, and group public places into meaningful clusters such as:

- ✔ Safe  
- ✔ Moderately Safe  
- ✔ Unsafe  

The project follows a structured pipeline including data preprocessing, feature engineering, clustering, visualization, and interpretation, along with ethical considerations.

---

## 📂 Repository Structure

```
usl-project/
 ┣ notebooks/
 ┃ ┣ 01_data_preprocessing.ipynb
 ┃ ┣ 02_feature_engineering.ipynb
 ┃ ┣ 03_unsupervised_clustering.ipynb
 ┃ ┣ 04_data_visualization.ipynb
 ┃ ┗ 05_interpretation.ipynb
 ┣ data/
 ┃ ┣ Women_public_place_safety.csv
 ┃ ┣ processed_data.csv
 ┃ ┣ feature_data.csv
 ┃ ┗ clustered_data.csv
 ┣ presentation/
 ┃ ┗ project_presentation.pptx
 ┣ requirements.txt
 ┗ README.md
```

---

## ⚙️ Execution Instructions

Run the notebooks in the following sequence:

1. `01_data_preprocessing.ipynb`  
2. `02_feature_engineering.ipynb`  
3. `03_unsupervised_clustering.ipynb`  
4. `04_data_visualization.ipynb`  
5. `05_interpretation.ipynb`  

Each notebook generates output files that are used as inputs for the next step.

---

## 📊 Dataset

- Collected via **Google Forms**
- Contains approximately **550 responses**
- Includes:
  - **Objective data** (infrastructure-related features)
  - **Subjective data** (perception of safety)

---

## 🔑 Features

| Feature                  | Type    |
|--------------------------|--------|
| Type_of_Public_Place     | Nominal |
| Mode_of_Transport        | Nominal |
| Crowd_Level              | Ordinal |
| Lighting_Condition       | Ordinal |
| CCTV_Available           | Binary  |
| Security_in_Public_Place | Binary  |
| Safe_Visiting_Alone      | Binary  |
| Avoid_Going_Out_At_Night | Binary  |
| Experienced_Harassment   | Binary  |

---

## ⚙️ Methodology

### 🔹 Data Processing
- Handling missing values  
- Standardizing inconsistent entries  
- Encoding categorical variables  

### 🔹 Feature Engineering
- Infrastructure Score  
- Perception Score  
- Safety Score  

### 🔹 Model Pipeline
- Aggregation of data (place-wise averaging)  
- Feature scaling using `StandardScaler`  

### 🔹 Clustering Algorithms
- K-Means Clustering  
- Hierarchical Clustering  
  - Ward Linkage  
  - Average Linkage  

### 🔹 Ensemble Approach
- Majority voting across clustering methods  

### 🔹 Evaluation
- Silhouette Score for cluster validation  

---

## 📈 Visualizations

- 📍 Scatter plots for cluster visualization  
- 🌳 Dendrograms for hierarchical clustering  
- 📊 Bar charts for comparing safety scores  

---

## 🧠 Results & Insights

- Clear clustering of public places based on safety levels  
- Both infrastructure and perception significantly influence safety  
- Identifies mismatches between available facilities and perceived safety  
- Highlights areas that require improvement  

---

## ⚖️ Ethical Considerations

- Survey responses may include subjective bias  
- Privacy and anonymity of participants are maintained  
- Results should not be used to label or stigmatize locations without context  
- Intended to support safer urban planning and awareness  

---

## 🛠️ Requirements

- Python 3.x  
- Jupyter Notebook  

### 📦 Libraries

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

Install dependencies:

```
pip install -r requirements.txt
```

---

## 📽️ Presentation

The project includes a PowerPoint presentation covering:

- Problem statement  
- Dataset overview  
- Methodology  
- Results and insights  
- Ethical considerations  
- Demonstration  

---

## 🚀 Future Scope

- Incorporate demographic and geographic features  
- Increase dataset size for better generalization  
- Apply advanced ML/AI models  
- Develop real-time safety prediction systems  

---

## 👨‍💻 Team Members

- **Pratyasha Palit**
- **Mitali Swaroop**
- **Garima Sablok**
- **Vaishnavi Singh**
