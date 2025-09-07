# 🏥 Emergency Room Visits – Data Analytics Project

📌 **Objective**
Analyze hospital emergency room (ER) visit data to uncover patient inflow patterns, common complaints, and optimize resource allocation for improved healthcare delivery.

🔗 **Project Links**
* 📂 [GitHub Repository](https://github.com/Ankithavenkannagari/Emergency_Room_Visits)  
* 📂 Dataset: [Hospital ER CSV](https://data.world/markbradbourne/rwfd-real-world-fake-data/workspace/file?filename=Hospital+ER.csv)

👩‍💻 **Role**
As the Data Analyst, I was responsible for:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering for patient insights
* Visualization and reporting of ER patterns
* Deriving actionable healthcare insights

🛠 **Tools & Technologies**

* Python (Pandas, NumPy)
* Visualization: Power BI
* GitHub for version control

🔍 **Process**

**Data Cleaning & Preprocessing**

* Handled missing values for wait time and treatment time.
* Standardized patient and complaint categories.
* Removed extreme outliers for wait times exceeding 12 hours.

**Exploratory Data Analysis (EDA)** 🩺

* Investigated patient demographics, wait times, and treatment durations.
* Identified peak hours, days, and most common complaints.
* Analyzed correlations between triage level, wait time, and treatment time.

**Feature Engineering** 🧬

* Created `Age_Group` (Child, Adult, Senior) based on patient age.
* Calculated `Total_ER_Time = Wait_Time_Minutes + Treatment_Time_Minutes`.
* Encoded categorical features using one-hot encoding.

**Visualization & Insights** 📊

* Designed interactive charts to track patient inflow and departmental workload.
* Highlighted peak visit hours and common complaints.
* Segmented patients by age and complaint type.

📊 **Key Insights**

* Average Wait Time ⏱: 42 minutes
* Average Treatment Time 🩹: 85 minutes
* Peak Hours 🕐: 6 PM – 10 PM
* Department with Highest Traffic 🏥: General Emergency

💼 **Business Impact**

* Optimized ER staffing and resource allocation based on historical patterns.
* Improved patient experience by reducing wait times.
* Provided actionable insights for hospital management planning.

✅ **Challenges & Learnings**

* Tackled missing and inconsistent data through robust preprocessing.
* Learned importance of feature engineering to capture patient characteristics.
* Developed ability to connect technical analysis to healthcare decision-making.

📈 **Future Improvements**

* Predictive modeling for ER wait times and patient inflow.
* Develop real-time dashboards for hospital staff using Power BI or Tableau.
* Integrate seasonal and demographic analysis for healthcare planning.
* Explore machine learning approaches to predict patient load and resource needs.

🏆 **Summary**
This project demonstrates how to leverage Python and data analytics to transform raw ER visit data into actionable healthcare insights. Through EDA, feature engineering, and visualizations, it provided meaningful analysis for optimizing hospital operations and patient care.
