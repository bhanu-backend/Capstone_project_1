# 🌍 AQI Data Analysis & Visualization Pipeline

## 📌 Overview
This project builds a complete data analysis pipeline for Air Quality Index (AQI) data — starting from raw CSV files to an interactive Power BI dashboard using MySQL as a central database.

---

## 🔄 Workflow Architecture
CSV Data → Jupyter Notebook → Data Cleaning → MySQL Database → Power BI Dashboard

---

## 🛠️ Technologies Used
- **Python (Pandas, NumPy)** – Data cleaning & processing  
- **Jupyter Notebook** – Data analysis  
- **MySQL** – Central data storage  
- **Power BI** – Data visualization & reporting  

---

## ⚙️ Project Workflow

### 1. Data Ingestion
- Imported raw AQI datasets from CSV files into Jupyter Notebook  

### 2. Data Cleaning & Processing
- Handled missing values and inconsistencies  
- Standardized column formats  
- Prepared analysis-ready datasets  

### 3. Data Storage
- Stored cleaned data into:
  - **MySQL database** (for structured querying & reporting)  
  - **CSV files** (for backup and reuse)  

### 4. Data Visualization
- Connected Power BI to MySQL database  
- Created interactive dashboards with filters and KPIs  

---

## 📊 Key Insights
- AQI levels increase significantly during winter  
- PM2.5 and PM10 are the dominant pollutants  
- Noticeable variation in air quality across states  

---

## 📁 Project Structure

AQI-Project/

├── aqi.pbix
|── AQI.ipynb
├── AQI_Cleaned_Data.csv
├── day_wise_aqi_data.csv
├── Pollutant_Over_Years_Cleaned_Data.csv
├── State_By_Season_Cleaned_Data.csv
├── README.md
└── .gitignore


---

## 📷 Dashboard
The Power BI dashboard provides:
- AQI trends over time  
- State-wise comparison  
- Pollutant distribution  

---

## 🚀 Future Enhancements
- AQI prediction using Machine Learning  
- Real-time data integration (API)  
- Deployment of dashboard  

---

## 📌 Conclusion
This project demonstrates an end-to-end data analytics workflow including database management, data cleaning, analysis, and visualization using real-world environmental data.

---

⭐ This project highlights skills in SQL, Python, and Power BI for real-world data analysis.