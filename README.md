# ✈️ Flight Price Analysis – Data Science Project  

This project was developed as part of a **B.Sc. Data Science course** in a **team of 3 students**.  
The aim was to collect, clean, and analyze flight price data from **Kiwi** and **Momondo**,  
to understand which features affect flight prices and to build predictive models.  

---

## 🔍 Project Workflow  

### 1. Data Collection (Web Scraping)  
Scraped flight prices from **Kiwi** and **Momondo** using Python and stored the raw datasets.  

### 2. Data Cleaning & Preprocessing  
- Removed duplicates and handled missing values  
- Normalized numeric features and converted string prices into numeric format  
- Produced cleaned datasets for analysis  

### 3. Exploratory Data Analysis (EDA)  
- Compared Kiwi and Momondo datasets  
- Visualized feature distributions (airline, duration, stops)  
- Identified correlations between features and price  

### 4. Machine Learning Modeling 🤖  
- Applied multiple ML algorithms for price prediction, including:  
  - Linear Regression  
  - Decision Tree Regressor  
  - Gaussian Process Regressor  
  - Neural Network (MLPRegressor)  
  - HistGradientBoosting Regressor  
  - ElasticNet  
- Evaluated models using **MSE**, **MAE**, and **R²**  
- Results are summarized in `Model_Comparison_Corrected_v1.csv`  

### 5. Clustering Analysis 📊  
- Implemented clustering methods to find hidden patterns:  
  - **K-Means**  
  - **Hierarchical Clustering** (Agglomerative)  
- Used PCA for dimensionality reduction and cluster visualization  

---

## 🛠️ Tech Stack  
- Python: pandas, numpy, scikit-learn, matplotlib, seaborn  
- Jupyter Notebooks  
- GitHub for collaboration  

---

## 👩‍💻 Teamwork & Contribution  
This was a **team project of 3 students**.  
- **My contribution**: clustering analysis (K-Means, Hierarchical), model evaluation, and visualization of results.  

---

✨ *Created as part of the Intro to Data Science course, B.Sc. in Data Science*  
