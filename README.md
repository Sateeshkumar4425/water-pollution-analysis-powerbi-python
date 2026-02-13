# water-pollution-analysis-powerbi-python-Excel
End-to-end data analysis and visualization of Indian water pollution data using Excel, Python (EDA), and Power BI.

# 🌊 Water Pollution Analysis – India
### End-to-End Data Analysis & Visualization using Excel, Python, and Power BI

---

## 📌 Project Overview

This project analyzes water pollution data collected from the Central Pollution Control Board (CPCB), India.

The dataset was originally available in PDF format and was transformed into structured data for analysis and visualization.

This project demonstrates a complete end-to-end data workflow:

- Data Extraction from Government Source  
- Data Structuring in Excel  
- Data Cleaning using Python  
- Exploratory Data Analysis (EDA)  
- Interactive Dashboard Development using Power BI  

---

## 📂 Data Source

- Source: Central Pollution Control Board (CPCB)  
- Website: https://cpcb.nic.in/nwmp-data/  
- Original Format: PDF  
- Converted To: Structured Excel format  

---

## 🔄 Project Workflow

### 1️⃣ Data Extraction
- Downloaded raw pollution data from the CPCB website  
- Converted PDF data into Excel format  
- Structured the data into tabular format  

### 2️⃣ Data Cleaning (Python)

**Libraries Used:**
- pandas  
- numpy  
- matplotlib  
- seaborn  

**Cleaning Steps Performed:**
- Removed irrelevant columns  
- Handled missing values  
- Standardized column names  
- Converted data types  
- Created derived features (`water_type`, `aquatic_score`, `pH_category`)  

### 3️⃣ Exploratory Data Analysis (EDA)

- State-wise pollution comparison  
- BOD vs DO relationship analysis  
- Year-wise pollution trends  
- Water quality classification distribution  
- Correlation analysis  

### 4️⃣ Power BI Dashboard

- State-wise pollution map  
- Top polluted states  
- Year-wise trend analysis  
- Water quality distribution visuals  
- Interactive filters  

---

## 📊 Key Insights

- Certain states show consistently high BOD levels.  
- High BOD is associated with lower Dissolved Oxygen levels.  
- Pollution trends vary significantly across years.  
- Water quality classification highlights regions requiring intervention.  

---

## 🛠 Tools & Technologies Used

- Microsoft Excel  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook  
- Power BI  
- GitHub  

---

## 📁 Repository Structure

water-pollution-analysis-powerbi-python-excel/
│
├── data/
│ ├── raw/
│ ├── processed/
│
├── excel/
├── notebooks/
├── powerbi/
├── images/
├── requirements.txt
└── README.md


---

## 📊 Excel Data Structuring

### Raw Converted Data
![Raw Excel](Excel/unstructured/unstuctured.png)

### Structured and Cleaned Data
![Structured Excel](Excel/Structuresd/Stuctured.png)

---

## 📊 Exploratory Data Analysis Visualizations

### Drinkable Water Comparison (Top vs Bottom States)
![Drinking Water Comparison](notebooks/images/top5vsBottom5_statesDrinking_water_comparsion.png)

### Top 10 States by Aquatic Suitability Score
![Aquatic Suitability](notebooks/images/Top10_State-wise_AquaticLife_Suitability.png)

### Distribution of Water Quality Types
![Water Quality Distribution](notebooks/images/Types_of_Water_Based_on_Quality.png)

---

## 📊 Power BI Dashboard

### Dashboard Preview
![Dashboard Overview](powerbi/images/Water_pollution_Detection1.png)

---

## 🚀 Project Highlights

- End-to-end pipeline from raw government PDF to interactive dashboard  
- Real-world environmental dataset  
- Demonstrates data cleaning, transformation, and visualization skills  
- Business-ready Power BI dashboard  

---

## 📌 Future Improvements

- Predictive modeling for pollution forecasting  
- Automated PDF data extraction pipeline  
- Deployment as a web-based dashboard  

---

## ⚠️ Disclaimer

I hereby declare that this project is my original work. The dataset was sourced from the CPCB official website and processed, analyzed, and visualized independently using Excel, Python, and Power BI for educational and portfolio purposes.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Sateesh Kumar Patlegar**

💼 Open to Data Science, Analytics, and Quant roles  

📧 Email: patlegarsateeshkumar@gmail.com  

🔗 LinkedIn: https://www.linkedin.com/in/patlegar-sateesh-kumar-868870258/



