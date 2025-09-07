# 🏥 Emergency Room Visits Analysis

📌 **Objective**
Analyze hospital emergency room (ER) visits data to understand patient inflow patterns, common complaints, and optimize hospital resource allocation. This project focuses on data exploration, feature engineering, and visualization to extract meaningful healthcare insights.

---

💡 **Project Resources**
* **GitHub Repository:** [Emergency\_Room\_Visits](https://github.com/Ankithavenkannagari/Emergency_Room_Visits)

 ---
 
📂 **Dataset**
**Source:** [Real World Fake Data – Hospital ER](https://data.world/markbradbourne/rwfd-real-world-fake-data/workspace/file?filename=Hospital+ER.csv)
**Size:** \~15,000 records
**Features:**

* **Categorical:** Department, Gender, Complaint\_Type, Triage\_Level
* **Numerical:** Age, Wait\_Time\_Minutes, Treatment\_Time\_Minutes
* **Target/Insights:** ER visit patterns, patient wait time, and treatment duration

---

🔍 **Methodology**

1. **Exploratory Data Analysis (EDA)** 🩺

   * Plotted histograms, bar charts, and boxplots to understand distributions of patient age, wait times, and treatment times.
   * Identified peak hours and most common complaints.
   * Analyzed correlations between triage level, wait time, and treatment duration.

2. **Feature Engineering** 🧬

   * Created `Age_Group` (Child, Adult, Senior) based on patient age.
   * Calculated `Total_ER_Time = Wait_Time_Minutes + Treatment_Time_Minutes`.
   * Encoded categorical variables (Department, Gender, Complaint\_Type) using one-hot encoding.

3. **Data Preprocessing** 🧹

   * Handled missing values in wait time and treatment time.
   * Removed extreme outliers for wait times exceeding 12 hours.
   * Standardized numerical features for modeling and visualization.

4. **Analysis & Insights** 📊

   * Average wait time per department and triage level.
   * Peak visit hours and days of the week.
   * Most common ER complaints and demographic patterns.
   * Visualized trends using heatmaps, bar charts, and line plots.

---

📊 **Key Findings**

| Metric                             | Value / Insight   |
| ---------------------------------- | ----------------- |
| Avg Wait Time ⏱                    | 42 minutes        |
| Avg Treatment Time 🩹              | 85 minutes        |
| Most Common Complaint 🚑           | Headache & Fever  |
| Peak Hours 🕐                      | 6 PM – 10 PM      |
| Department with Highest Traffic 🏥 | General Emergency |

✅ **Key Learnings**

* Identified bottlenecks in patient inflow 🧾.
* ER resource allocation can be optimized using historical patterns 📈.
* Feature engineering improved analytical insights on patient demographics and complaint types 💊.

---

🛠 **Tools & Technologies**

* **Python:** Pandas, NumPy, Scikit-learn
* **Visualization:** Matplotlib, Seaborn, Plotly
* **Notebook:** Jupyter Notebook
* **Version Control:** [GitHub Project Link](https://github.com/Ankithavenkannagari/Emergency_Room_Visits)

---

📈 **Future Improvements**

* Predictive modeling for wait times and patient inflow 🧠.
* Dashboard creation for hospital staff using Power BI or Tableau 📊.
* Include seasonal and demographic analysis for healthcare policy planning 🌡️.
