# 🌍 Global Socioeconomic Analysis using Machine Learning & Genetic Algorithms

This project develops a machine learning framework to identify countries with high socioeconomic vulnerability using clustering, classification, and regression models.

It combines exploratory data analysis, dimensionality reduction, unsupervised learning, supervised learning, and hyperparameter optimization to generate data-driven insights for global development.

---

## 🎯 Project Objective

The goal of this project is to analyze country-level socioeconomic indicators and identify countries with disadvantaged profiles that may require greater support or intervention.

The workflow integrates:
- **Clustering** to group similar countries
- **Classification** to predict country group membership
- **Regression** to model socioeconomic outcomes
- **Genetic Algorithms** to optimize model hyperparameters

---

## 📊 Dataset

- Source: Kaggle country-level socioeconomic dataset  
- Observations: 167 countries  
- Features include:
  - Child mortality
  - Exports / Imports
  - Health spending
  - Income
  - Inflation
  - Life expectancy
  - Total fertility
  - GDP per capita  

---

## 🧠 Methods Used

### Exploratory Data Analysis
- Descriptive statistics  
- Histograms  
- Density plots  
- Boxplots  
- Correlation heatmap  

### Dimensionality Reduction
- Principal Component Analysis (PCA)

### Unsupervised Learning
- K-Means  
- K-Medoids  
- Hierarchical Clustering  
- t-SNE  
- UMAP  

### Supervised Learning

#### Classification
- K-Nearest Neighbors  
- Decision Tree  
- Random Forest  
- AdaBoost  
- Gradient Boosting  

#### Regression
- Linear Regression  
- Decision Tree  
- Random Forest  
- Lasso  
- Ridge  
- K-Nearest Neighbors  
- Gradient Boosting  

### Hyperparameter Optimization
- Genetic Algorithms using `sklearn-genetic-opt`

---

## 📈 Key Results

- Identified clusters of countries with similar socioeconomic conditions  
- Built classification models with strong predictive performance  
- Built regression models explaining key socioeconomic indicators  
- Generated benchmark comparisons across multiple models  
- Produced insights useful for policy and development analysis  

---

## 🗂️ Repository Structure
```text
global-socioeconomic-ml-analysis/
├── data/
│   ├── raw/
│   └── processed/
├── documents/
├── notebooks/
│   └── socioeconomic_analysis.ipynb
├── outputs/
│   ├── figures/
│   └── results/
├── README.md
├── requirements.txt
└── .gitignore
```
---

## 📦 Outputs

The notebook automatically generates and saves:

- Processed datasets → `data/processed/`  
- Visualizations → `outputs/figures/`  
- Benchmark results → `outputs/results/`  
- Statistical test outputs  

---

## ⚙️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/NathanGhenassia/global-socioeconomic-ml-analysis.git
cd global-socioeconomic-ml-analysis
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the notebook
Open:
notebooks/socioeconomic_analysis.ipynb
Then run all cells.

---

## 🛠️ Tech Stack
```markdown
Python
Pandas
NumPy
Scikit-learn
SciPy
Matplotlib
Seaborn
Plotly
Kneed
sklearn-genetic-opt
Jupyter Notebook

---

## 👤 Author

Nathan Ghenassia
Data Scientist | Machine Learning Engineer

LinkedIn: https://www.linkedin.com/in/nathan-ghenassia-data/
GitHub: https://github.com/NathanGhenassia
