# 📊 Unemployment Rate Analysis in India

This project analyzes unemployment trends across various Indian states, comparing *urban* and *rural* areas. The analysis includes data cleaning, visualization, and insights on unemployment rates over time.

---

## 📁 Dataset

- *Source:* [Kaggle - Unemployment in India](https://www.kaggle.com/datasets/ramjasmaurya/unemployment-in-india)  
- *File Used:* Unemployment_in_india.csv

*Columns:*
- Region / states: Name of the state or region  
- Date: Reporting date (monthly)  
- Frequency: Data collection frequency (Monthly)  
- Estimated Unemployment Rate (%)  
- Estimated Employed  
- Estimated Labour Participation Rate (%)  
- Area: Urban or Rural classification  

---

## 🧹 Data Preprocessing

- Removed *196 missing values*.  
- Checked and confirmed *0 duplicate rows*.  
- Renamed Region to states.  
- Trimmed whitespace in column names.  
- Converted Date to datetime format using pd.to_datetime.  

---

## 📊 Exploratory Data Analysis (EDA)

1. *Average Unemployment by State*  
   - Bar chart showing the average unemployment rate across states.

2. *Urban vs Rural Trends*  
   - Line chart comparing unemployment rates in urban and rural areas.

3. *India-wide Trend*  
   - Line chart showing overall unemployment rate progression from mid-2019 to mid-2020.

---

## 📈 Visualizations

- *Matplotlib* and *Seaborn* used for plotting:
  - Bar chart for average unemployment by state.
  - Time-series line plot for urban vs rural trends.
  - National unemployment trend plot.

---

## 📌 Insights

- States like *Tripura* and *Haryana* have the highest average unemployment rates.  
- Urban unemployment spiked in early 2020, likely due to COVID-19 lockdowns.  
- Rural areas had smaller fluctuations but still faced a rise in unemployment.  

---

## 🛠 Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

