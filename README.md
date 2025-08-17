# 🏠 Airbnb Booking Data Visualization & Analysis (Python)

This project explores **Airbnb booking data** using **Python (Pandas, Matplotlib, Seaborn, Scikit-learn)**.  
It demonstrates **data cleaning, visualization, and analysis** on a real-world dataset, with insights into Airbnb pricing and booking behavior.

---

## 📌 Project Overview
- **Course:** DS332 – Data Science Lab  
- **Topic:** Data Visualization & Analysis using Python  
- **Dataset:** [Airbnb Open Data – Kaggle](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)  
- **Language:** Python (Jupyter Notebook)  

---

## 📊 Features
1. **Data Loading & Exploration**
   - Load dataset into Pandas
   - Inspect dataset structure, types, and summary statistics  

2. **Data Cleaning**
   - Handle missing values (median for numeric, mode for categorical)  
   - Remove duplicates  
   - Ensure correct datatypes  

3. **Data Visualization**
   - 📊 **Bar Chart:** Top 10 cities by listings  
   - 📉 **Histogram:** Distribution of prices  
   - ⚪ **Scatter Plot:** Price vs. Number of Reviews  
   - 🔥 **Heatmap:** Correlation matrix of numeric features  

4. **Analysis**
   - 3–4 sentence interpretations for each visualization  
   - Identified price distribution patterns, city-wise demand, and correlations  

5. **(Optional) Logistic Regression Model**
   - Define binary target (`HighPrice` vs `LowPrice`)  
   - Train logistic regression classifier  
   - Evaluate with Accuracy, Precision, Recall, F1, ROC-AUC  

---

## 📂 Project Files
- `notebooks_Airnb_Open-Data.ipynb` → Jupyter Notebook with full code & analysis  
- `airbnb_clean.csv` → Cleaned dataset (generated inside notebook, optional)  
- `README.md` → Project documentation  

---

## ⚙️ How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/Airbnb-Data-Analysis.git
   cd Airbnb-Data-Analysis
   
📈 Sample Visualizations

Bar chart showing top 10 Airbnb cities by number of listings

Histogram showing skewed distribution of Airbnb prices

Scatter plot (Price vs. Reviews) showing demand patterns

Heatmap showing correlations among features

🎓 Conclusion

This project demonstrates how data visualization & machine learning can be applied to real-world travel data.
It provides insights into Airbnb pricing dynamics, city-level demand, and customer review patterns.
