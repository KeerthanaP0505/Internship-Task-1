# 🔍 Crime Data Analysis with PySpark

This project analyzes crime data from 2020 to the present using **PySpark** for distributed processing and **Matplotlib/Seaborn** for insightful visualizations. It highlights crime trends, high-risk areas, victim demographics, and patterns over time and day.

---

## 📁 Dataset

- **Source**: [Crime_Data_from_2020_to_Present.csv](https://data.lacity.org/)
- **Attributes Used**:
  - `DATE OCC`: Date of crime occurrence
  - `TIME OCC`: Time of occurrence (24-hour format)
  - `AREA NAME`: Area where the crime occurred
  - `Crm Cd Desc`: Crime description
  - `Vict Age`, `Vict Sex`, `Vict Descent`: Victim demographic info

---

## ⚙️ Technologies Used

- **PySpark** (Apache Spark via Python)
- **Google Colab** / Jupyter Notebook
- **Pandas**
- **Matplotlib & Seaborn** (for visualization)

---

## 📊 Key Analyses

1. **Crime Trend Over Time**  
   ➤ Monthly crime trends using a time-series line graph

2. **Top 10 Most Dangerous Areas**  
   ➤ Bar chart of areas with the highest crime counts

3. **Crime Distribution by Time of Day**  
   ➤ Pie chart categorizing crime into time-based groups:
   - Midnight - Morning
   - Morning - Noon
   - Afternoon - Evening
   - Evening - Midnight

4. **Average Victim Age by Crime Type**  
   ➤ Horizontal bar chart showing which crimes affect which age groups the most

5. **Victim Age Group Distribution**  
   ➤ Distribution of crimes across age categories:
   - Under 18
   - 18–30
   - 31–50
   - Above 50

---

## 📌 How to Run

1. Clone this repo or upload files to your Google Colab.
2. Install PySpark (if running locally):
   ```bash
   pip install pyspark
