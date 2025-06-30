# Task5_titanic_eda
Exploratory Data Analysis on Titanic3 Dataset
# 🚢 Titanic EDA – Exploratory Data Analysis on titanic3.csv

This project contains a complete exploratory data analysis (EDA) on the Titanic dataset using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**.



## 📁 Dataset Used

- **File**: `titanic3.csv`
- Contains extended passenger information from the Titanic dataset (includes `home.dest`, `body`, `boat`, etc.)



## 🧹 Data Cleaning Summary

- Dropped columns: `cabin`, `boat`, `body` ,`home.dest` (excessive missing values)
- Filled missing values:
  - `age` → median
  - `embarked` → mode
- Final dataset has **more less missing values**



## 📊 Visualizations and Key Insights

- ✅ Survival Count: Only 38% survived
- ✅ Survival by Gender: Women had highest survival
- ✅ Survival by Class: 1st-class passengers had better chances
- ✅ Age Distribution: Most were between 20–40 years
- ✅ Fare Analysis: Higher fares associated with higher survival
- ✅ Age vs Fare Scatterplot: Younger, high-fare passengers survived more
- ✅ Heatmap: Strong correlation between fare & class
- ✅ Violin & Swarm Plots: Deeper age-gender-class-survival analysis



## 📂 Files Included

| File Name                   | Description                                |
|-----------------------------|--------------------------------------------|
| `Task5_JU.html`             | Main notebook with code and visualizations |
| `Task5_Final summary.pdf`   | PDF version of the notebook                |
| `titanic3.csv`              | Dataset used in the analysis               |
| `README.md`                 | This summary file                          |



## 🛠️ Tools & Libraries Used

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook



## ✅ Conclusion

This EDA clearly shows that **gender, passenger class, and fare** were the most significant factors affecting survival on the Titanic. The analysis supports historical records and demonstrates how data tells compelling stories.
