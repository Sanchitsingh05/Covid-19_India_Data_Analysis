# 🦠 COVID-19 India Statewise Data Analysis

## 📝 Description
This project performs a detailed **Exploratory Data Analysis (EDA)** and **visualization** of the latest COVID-19 statewise data in India. The goal is to understand the spread, severity, and trends of the pandemic across Indian states and Union Territories using real-world data. This analysis covers statistical summaries, geospatial mapping, correlation studies, and comprehensive visual reports for effective insight generation.

## 📂 Dataset
* **Source**: [Kaggle – Latest COVID-19 India Statewise Data](https://www.kaggle.com/datasets)
* **Format**: CSV
* **Attributes**:

  * `State/UTs`: Name of state or union territory
  * `Total Cases`: Total confirmed COVID-19 cases
  * `Active`: Current active cases
  * `Discharged`: Recovered/discharged cases
  * `Deaths`: Number of deaths
  * `Active Ratio (%)`: Active cases as a % of total cases
  * `Discharge Ratio (%)`: Discharged cases as a % of total cases
  * `Death Ratio (%)`: Deaths as a % of total cases


## 🎯 Project Objectives
* Clean and preprocess COVID-19 data for Indian states
* Visualize key metrics using graphs, maps, and scatter plots
* Analyze trends in active, discharged, and death ratios
* Compare states based on severity, recovery, and mortality
* Generate insights using correlation and statistical reports

## ⚙️ Tools & Libraries Used
* **Python**
* **Pandas, NumPy** – Data handling
* **Matplotlib, Seaborn** – Static plots
* **Plotly Express** – Interactive and geospatial plots
* **GeoJSON** – India map visualization

## 📈 Key Analyses & Visualizations
### ✅ Data Processing

* Removed duplicates and standardized long state names
* Verified missing values and ensured numeric conversion
* Calculated correlation matrix among all numerical features

### 📊 Visualizations

* **Bar Plots**: Top states by total cases and deaths
* **Pie Charts**: Statewise distribution of total, death, and recovery percentages
* **Scatter Plots**: Comparison of active vs death ratios, total vs active cases
* **Heatmaps**: Correlation between all numeric metrics
* **Choropleth Maps**: Geo-based mapping of cases and deaths using Indian state boundaries
* **Pair Plots**: Relationships among multiple COVID metrics
* **Histograms and Density Maps**: Distribution of COVID impact by state

## 🧮 Statistical Reporting
* **Highest Cases**: Maharashtra
* **Lowest Cases**: Lakshadweep or Daman & Diu
* **Highest Active Ratio**: Mizoram
* **Highest Death Ratio**: Punjab (\~2.72%)
* **Highest Discharge Ratio**: Multiple states above 98%

Reports were created to show **top 5 states by death ratio**, **active cases**, and more using both tabular and visual summaries.

## 📌 Highlights
* Maharashtra leads in total cases but **Punjab has the highest death ratio**.
* States like **Mizoram** show high active case rates, indicating persistent spread.
* Over **50% of total cases** come from just **4–5 states**, emphasizing the uneven impact of the pandemic.
* Correlation studies reveal strong relationships between total cases and discharges.

## 💡 Future Improvements

* Add time-series data to observe pandemic trends over time
* Incorporate vaccination and testing statistics for deeper analysis
* Deploy this as a dashboard using Streamlit or Dash
* Perform predictive modeling on case growth or fatality forecasting

## 👨‍💻 Owner

This project is created and maintained by **Sanchit Singh**, with the goal of understanding real-time health data through effective visual storytelling and analytics.

## 🚀 Final Note
This end-to-end analysis combines data cleaning, statistics, geospatial visualization, and reporting to give a complete picture of India's COVID-19 landscape. It demonstrates the power of Python and EDA in extracting actionable insights from health data for informed public decision-making.
