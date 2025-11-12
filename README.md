# 📊 Play Store Data Analysis

This project analyzes the Google Play Store dataset to uncover insights about app ratings, installs, categories, pricing, and more.  
It uses Python for data preprocessing, cleaning, and visualization to understand trends that impact app success on the Play Store.

---

## 🧠 Project Overview

The Play Store is a massive app marketplace. This project performs data analysis to answer key questions like:
- What factors influence app ratings?
- Which app categories dominate the store?
- How do app size, price, and installs correlate?
- What trends can developers use to improve visibility?

---

## 🛠️ Tools and Libraries Used

- **Python**
- **Pandas** – for data cleaning and manipulation  
- **NumPy** – for numerical computation  
- **Matplotlib & Seaborn** – for data visualization  
- **Plotly (optional)** – for interactive plots  
- **Jupyter Notebook** – for analysis and presentation  

---

## 📂 Dataset

The dataset used is the **Google Play Store Apps dataset**, typically containing:
- `App`, `Category`, `Rating`, `Reviews`, `Size`, `Installs`, `Type`, `Price`, `Content Rating`, `Genres`, `Last Updated`, etc.

Make sure your dataset file is named `PlayStore.csv` (or similar) and is placed in the same directory as the notebook.

---

## 📈 Key Steps in the Notebook

1. **Import and Explore Data**  
   Load dataset and check for missing values, duplicates, and data types.

2. **Data Cleaning**  
   - Remove or impute missing values  
   - Format data types (e.g., numeric conversions)  
   - Clean inconsistent entries (e.g., installs, prices, sizes)

3. **Exploratory Data Analysis (EDA)**  
   - Distribution of app ratings  
   - Most popular categories  
   - Relationship between reviews and installs  
   - Pricing trends  
   - Correlation heatmaps

4. **Visualization and Insights**  
   Interactive and static charts to display relationships and trends across various features.

---

## 💡 Insights Gained

- Most apps on Play Store are **free** and belong to **Family, Game, and Tools** categories.  
- Higher ratings correlate with **lower app size** and **more installs**.  
- **Paid apps** generally have **fewer installs** but sometimes **higher average ratings**.  

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ThakurPradeepRawat/Google-Play-Store-Exploratory-Data-Analysis
   
