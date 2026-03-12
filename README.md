# 📊 Tirumala Temple Darshan Data Analysis

## 📌 Project Overview

This project analyzes Tirumala Tirupati Devasthanams (TTD) darshan data to identify patterns in daily temple visitors and understand how external factors such as festivals, holidays, weather conditions, and seasonal trends influence pilgrim inflow.

Using Microsoft Excel, the dataset was cleaned, transformed, and analyzed through pivot tables and dashboards to generate meaningful insights that support data-driven decision making for crowd management and operational planning.

---

# 🏛 Business Context

Tirumala Temple is one of the most visited pilgrimage sites in the world. Visitor volumes fluctuate significantly due to factors such as:

* Religious festivals
* Public holidays
* Seasonal travel patterns
* Weather conditions
* Weekends and special temple events

Understanding these patterns helps temple administration plan resources effectively and manage peak crowds.

---

# 🛠 Tools & Technologies

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Data Cleaning
* Data Transformation
* Interactive Dashboard Design

---

# 📂 Dataset Description

The dataset contains **daily darshan records and contextual variables** that influence temple attendance. Each row represents a single day's observation with visitor counts and external influencing factors.

### Dataset Columns

| Column Name           | Description                                                                        |
| --------------------- | ---------------------------------------------------------------------------------- |
| date                  | Date of the recorded observation                                                   |
| darshans              | Total number of pilgrims who completed darshan on that day                         |
| weekend               | Indicator showing whether the day falls on a weekend                               |
| weekday               | Indicator showing whether the day is a regular working day                         |
| summer                | Indicator representing the summer season period                                    |
| temp_max              | Maximum temperature recorded for the day                                           |
| temp_min              | Minimum temperature recorded for the day                                           |
| humidity              | Average humidity level recorded for the day                                        |
| rainfall              | Rainfall level recorded for the day                                                |
| rolling_avg_8         | 8-day rolling average of darshan counts used for smoothing short-term fluctuations |
| google_trend_score    | Online search popularity score related to Tirumala temple                          |
| is_public_holiday     | Binary indicator showing whether the day is a public holiday                       |
| is_festival           | Binary indicator indicating whether a religious festival occurred                  |
| is_brahmostavam       | Indicator representing the Brahmotsavam festival period                            |
| rolling_avg_7         | 7-day rolling average of darshan counts                                            |
| day                   | Day of the week derived from the date                                              |
| month                 | Month extracted from the date                                                      |
| year                  | Year of the observation                                                            |
| week_end_darshans     | Darshan counts specifically during weekend periods                                 |
| brahmostavam_darshans | Visitor counts during Brahmotsavam festival days                                   |
| festival_crowd        | Estimated visitor count during festival days                                       |
| public_holiday_crowd  | Visitor count during public holidays                                               |
| holiday_type          | Classification of the day (Holiday / Working Day)                                  |
| festival_type         | Indicates whether the day belongs to a festival period                             |

These features allow the dataset to be analyzed across **temporal trends, seasonal factors, weather influence, and religious events**.

---

# 🧹 Data Preparation

Before performing the analysis, several preprocessing steps were applied:

* Standardized date formats across the dataset
* Derived **day, month, and year** attributes from the date column
* Verified darshan counts and removed inconsistencies
* Categorized days into **holiday vs non-holiday**
* Tagged religious festival periods
* Calculated **rolling averages (7-day and 8-day)** to smooth short-term fluctuations
* Validated weather and trend indicators

These steps ensured the dataset was ready for accurate aggregation and visualization.

---

# 📊 Exploratory Data Analysis

## 1️⃣ Daily Visitor Trend

Daily darshan counts were analyzed to understand fluctuations in temple attendance.

Key questions explored:

* Which days experience the highest pilgrim inflow?
* How do visitor counts vary across weekdays and weekends?

---

## 2️⃣ Monthly & Seasonal Analysis

Darshan counts were aggregated by month to identify seasonal trends and high pilgrimage periods.

Purpose:

* Identify peak pilgrimage seasons
* Detect recurring monthly patterns

---

## 3️⃣ Holiday Impact Analysis

Visitor numbers were compared across:

* Public holidays
* Working days
* Festival days

This analysis reveals how external events influence temple attendance.

---

## 4️⃣ Festival Influence

Festival days such as Brahmotsavam were analyzed separately to evaluate their impact on visitor volume and crowd peaks.

---

## 5️⃣ Weather Influence Analysis

Environmental variables such as temperature, rainfall, and humidity were examined to explore possible correlations with temple visitor numbers.

---

# 📈 Dashboard Features

An interactive Excel dashboard was built to visualize key insights.

Key components include:

* Total Darshan KPI
* Daily and Monthly Visitor Trends
* Holiday vs Non-Holiday Visitor Comparison
* Festival Crowd Analysis
* Pivot-based interactive filtering
* Drill-down analysis using pivot tables

These visualizations help quickly interpret complex visitor patterns.

# 🔎 Key Insights

* Temple visitor numbers increase significantly during **festival periods**.
* **Public holidays** attract higher pilgrim inflow compared to normal working days.
* **Weekend patterns** show a noticeable rise in darshan counts.
* Certain months consistently record **higher pilgrimage activity**.
* Festival days combined with holidays produce the **largest crowd volumes**.
* Online interest (Google trend score) shows correlation with increased visitor traffic.

# 🎯 Project Outcome

This project demonstrates how spreadsheet analytics can transform raw operational data into actionable insights.

The analysis helps understand pilgrim behavior, identify peak crowd periods, and support planning for improved crowd management and operational efficiency at major pilgrimage centers.
