# 🏡 Airbnb Data Analysis Project

## 📌 Overview
This project analyzes Airbnb listings data to uncover insights into **pricing, availability, and customer behavior**.  
The goal was to clean, process, and visualize the dataset in order to identify patterns and trends that affect hosts and guests.  

---

## 📊 Dataset
- **Source**: [Inside Airbnb](http://insideairbnb.com/) 
- **Columns analyzed**:
  - `latitude`, `longitude`
  - `price`
  - `minimum_nights`
  - `number_of_reviews`
  - `availability_365`
  - `beds`

---

## 🔧 Tools & Libraries
- Python 🐍
- Pandas 📑
- NumPy 🔢
- Matplotlib 📈
- Seaborn 🎨
- Jupyter Notebook 📓

---

## 🔍 Key Steps
1. **Data Cleaning**
   - Removed duplicates, handled missing values
   - Stripped extra spaces from column names
2. **Exploratory Data Analysis (EDA)**
   - Distribution of price, reviews, and availability
   - Binning of `minimum_nights` into ranges
   - Correlation analysis of numerical variables
3. **Visualization**
   - Histograms
   - Correlation heatmap
   - Trend charts

---

## 📈 Insights
- Most listings fall within **1–125 nights** range for `minimum_nights`.
- Strong correlations found between **beds** and **price**.
- Availability patterns highlight differences between long-term vs. short-term hosts.

🌟 Future Work

Build a predictive model for price estimation

Interactive dashboard with Plotly / Dash / Streamlit

Geo-mapping of listings

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.



👤 Pratham Baraskar
🔗 [LinkedIn](https://www.linkedin.com/in/prathambaraskar/) | GitHub
