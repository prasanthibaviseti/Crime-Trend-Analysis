# Crime Trend Analysis
# 📊 Chicago Crime Data Analysis (2023–2025)

This project performs Exploratory Data Analysis (EDA) on recent crime data from Chicago, focusing on trends, hotspots, arrest patterns, and statistical relationships between different variables. The goal is to uncover insights that could support crime prevention strategies, law enforcement resource allocation, and public safety awareness.

## 📁 Dataset Source
- The dataset was sourced from the *City of Chicago's public crime records* and includes incidents from *2023 to 2025*.
- Key attributes: Primary Type, Location Description, Arrest, Date, District, Community Area, etc.

## 🧪 Project Features

### 🔹 Data Preprocessing
- Loaded and cleaned data using pandas.
- Filtered records from January 2023 onward.
- Converted date columns and handled missing/null values.

### 🔹 Univariate Analysis
- Distribution of crime types, locations, and arrests.
- Visualized with histograms and count plots.

### 🔹 Bivariate & Comparative Analysis
- Compared crime type trends across 2023, 2024, and 2025.
- Analyzed arrest rates by crime type.

### 🔹 Time Series & Trend Analysis
- Created a *heatmap* showing crimes by *day of the week and hour* to spot peak crime periods.

### 🔹 Geographical Hotspots
- Identified top 10 *districts* and *community areas* with the most reported crimes.

### 🔹 Statistical Testing
- Performed *Chi-Square Test* to check relationships between Primary Type and Arrest.

## 🛠 Tools & Technologies
- Python (Jupyter Notebook)
- pandas, NumPy
- seaborn, matplotlib
- scipy (for statistical testing)

## 📌 Key Insights
- Theft and battery were the most reported crimes across all years.
- Certain crimes like narcotics and weapons violations had higher arrest rates.
- Most crimes occurred during late afternoon and evening hours.
- Districts with higher population density reported more incidents.

## 📈 Future Scope
- Integrate crime prediction using machine learning.
- Build real-time dashboards or alert systems.
- Include demographic and weather data for deeper context.

