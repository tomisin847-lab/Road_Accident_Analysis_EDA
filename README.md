# 🚦Road Traffic Accident Analysis - Exploratory Data Analysis (Python)

## 📌 Project Overview

Road traffic accidents remain a major public safety concern, leading to loss of lives, injuries, and economic impact. Understanding the patterns and contributing factors behind these accidents is essential for developing effective prevention strategies.

In this project, I perform an Exploratory Data Analysis (EDA) on road traffic accident data from Addis Ababa City. The goal is to uncover trends related to accident severity, driver demographics, vehicle characteristics, and causes of accidents. By analyzing this data, we aim to generate insights that can support data-driven decisions for improving road safety and reducing accident-related risks.

This project demonstrates an end-to-end data analysis workflow, including data cleaning, visualization, and interpretation of findings using Python, Pandas, Matplotlib, and Seaborn.

---

## 🎯 Project Objectives

By the end of this project, the analysis aims to:

- Identify temporal patterns of road accidents (days of the week, hours of the day)
- Analyze accident severity to understand the distribution of slight, serious, and fatal accidents
- Examine driver demographics (age and gender) to determine high-risk groups
- Investigate leading causes of accidents to inform prevention strategies
- Explore casualty distribution to support emergency planning and resource allocation

  ---
  
## ❓ Business Questions

- Which days and hours have the highest accident occurrences?
- What is the distribution of accident severity (slight, serious, fatal)?
- Which driver demographics (age, gender) are most frequently involved?
- What are the leading causes of accidents?
- How are casualties distributed per accident?

---

## 📂 Dataset

The dataset contains road accident records, including:

- Accident ID
- Date and Time
- Day of the Week
- Driver Gender
- Driver Age Band
- Vehicle Type
- Accident Severity
- Cause of Accident
- Number of Casualties

The raw data contained missing values (up to 30%) and required cleaning before analysis.

---

## 🧹 Data Cleaning Process

The following steps were performed using Python:

- Converted raw data into structured tables.
- Trimmed text columns to remove extra spaces.
- Standardized date and time formats.
- Converted Day of the Week into a chronological categorical variable (Sunday → Saturday).
- Handled missing values appropriately; high-missing columns were flagged and used cautiously.
- Extracted hour from time for temporal analysis.
- Validated numeric values for casualties and accident counts.
  
--- 

## 📊 Analysis Steps

1. Created summary tables to analyze accidents by:
    - Severity
    - Day & Hour
    - Driver demographics
    - Vehicle type
    - Cause of accident

3. Calculated:
   - Total accidents per severity category
   - Accidents per day of the week
   - Accidents per hour of the day
   - Accidents per driver gender and age band
   - Frequency of each cause of accident

4. Segmented accidents into:
   - Slight, Serious, Fatal
   - Male vs Female drivers
   - High-risk vs low-risk hours

5. Built pivot tables and cross-tabulations to analyze:
   - Accident trends by time and day
   - Accident distribution by driver demographics
   - Leading causes of accidents

---

## 📈 Visualizations

The following charts were created using Python:

- Pie Chart: Accident Severity Distribution
- Column Chart: Accidents per Day of the Week
- Heatmap: Day of Week vs Hour of Day
- Column Chart: Driver Gender Distribution
- Count Plot: Driver Age Bands
- Bar Chart: Top 10 Causes of Accidents
- Histogram with KDE: Number of Casualties per Accident

These visualizations highlight patterns, high-risk groups, and temporal trends for informed decision-making.

---

## 🔑 Key Insights

- Weekdays, particularly Friday, have the highest number of accidents, while weekends are safer.
- Peak accident times occur during morning and evening rush hours.
- Male drivers are significantly more involved in accidents than female drivers.
- 18 - 30 age bands are more frequently involved, indicating a need for targeted road safety education.
- A small number of driver behaviors (e.g., no distancing, careless driving, lane changes) account for the majority of accidents.
- Most accidents result in few casualties, but a few high-impact accidents require emergency preparedness.

--- 

## 🛠 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 👩‍💻Author

- Name: Adeyemi Tomisin Precious
- Role: Data Analyst

