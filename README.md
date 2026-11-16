# indian-flight-price-data-analysis
Exploratory Data Analysis of Indian domestic flight prices using Python, NumPy, Pandas, Matplotlib, Seaborn, and Plotly. Analyzes airline fares, routes, travel duration, departure timings, and stop categories through data cleaning, statistical analysis, and interactive visualizations.

# Indian Flight Price Data Analysis

## Project Overview

This project focuses on analyzing Indian domestic flight price data using Python and popular data analysis and visualization libraries.

The objective is to explore flight ticket prices and understand how different factors, such as airline, travel date, departure time, journey duration, route, and number of stops, relate to ticket fares.

The project follows an end-to-end data analysis workflow, including data collection, preprocessing, exploratory data analysis (EDA), data visualization, and feature engineering.

## Objectives

- Analyze flight ticket prices across different airlines.
- Compare average and median fares between airlines.
- Identify routes with relatively higher and lower ticket prices.
- Study the relationship between journey duration and ticket prices.
- Analyze the impact of stops and departure timings on fares.
- Perform data cleaning and preprocessing.
- Create static and interactive visualizations.
- Apply feature engineering, categorical encoding, and numerical scaling.

## Dataset Information

- **Dataset Name:** Indian Flight Price Dataset
- **File Name:** economy.csv
- **Format:** CSV
- **Total Records:** 206,774
- **Total Features:** 11
- **Domain:** Aviation / Travel Analytics

**Dataset Source:** Add the original Kaggle dataset URL here if applicable. The exact source URL was not included in the uploaded CSV.

### Dataset Attributes

| Column | Description |
|---|---|
| date | Date of journey |
| airline | Airline operating the flight |
| ch_code | Airline code |
| num_code | Flight number |
| dep_time | Departure time |
| from | Origin city |
| time_taken | Total journey duration |
| stop | Number and details of stops |
| arr_time | Arrival time |
| to | Destination city |
| price | Flight ticket price |

## Technologies Used

- **Python** – Programming language
- **NumPy** – Numerical computations
- **Pandas** – Data manipulation and cleaning
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Plotly** – Interactive data visualization
- **Scikit-learn** – Categorical encoding and numerical scaling
- **Jupyter Notebook** – Development environment

## Project Workflow

### 1. Dataset Collection
Loaded the Indian Flight Price dataset in CSV format and identified the problem statement and objectives.

### 2. Python and NumPy
Performed array creation, indexing, slicing, arithmetic operations, and statistical calculations on numerical flight data.

### 3. Pandas Operations
Explored dataset records, dimensions, column names, data types, descriptive statistics, missing values, and duplicate records.

### 4. Data Cleaning and Preprocessing
- Removed duplicate records.
- Standardized column names and text values.
- Converted flight dates into datetime format.
- Converted ticket prices into numerical values.
- Converted journey duration into minutes.
- Extracted departure and arrival hours.
- Detected outliers using the IQR method.
- Compared data before and after cleaning.

### 5. Exploratory Data Analysis (EDA)
- Analyzed flight prices and journey durations.
- Compared airline-wise average and median fares.
- Studied route-wise pricing patterns.
- Analyzed stop categories.
- Investigated correlations between numerical variables.

### 6. Data Visualization Using Matplotlib and Seaborn

Created the following visualizations:

- Histogram – Distribution of flight ticket prices.
- Bar Chart – Number of flight records by airline.
- Line Chart – Average flight fare by travel date.
- Scatter Plot – Journey duration versus ticket price.
- Box Plot – Ticket price distribution by airline.
- Correlation Heatmap – Relationships between numerical variables.

### 7. Interactive Visualization Using Plotly

Created interactive visualizations:

- Interactive Histogram of Flight Prices.
- Interactive Scatter Plot of Journey Duration vs Ticket Price.
- Interactive Bar Chart of Average Ticket Price by Airline.

### 8. Feature Engineering

Created meaningful features from existing data:

- Route – Combines origin and destination cities.
- Travel Month – Extracts the month of travel.
- Travel Day – Extracts the calendar day.
- Travel Day of Week – Identifies the weekday.
- Departure Period – Categorizes flights into Morning, Afternoon, Evening, and Night.
- Stop Count – Converts stop categories into numerical values.
- Fare Category – Classifies fares into Budget, Mid-range, and Premium.

Applied Label Encoding and Standard Scaling to prepare data for further analysis.

### 9. Analysis and Conclusion

Summarized the findings, compared airline fares, identified route-level pricing patterns, and discussed recommendations and dataset limitations.

## Key Learning Outcomes

- Python programming for real-world data analysis.
- Numerical operations using NumPy.
- Data manipulation using Pandas.
- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- Statistical analysis and correlation.
- Static and interactive data visualization.
- Feature engineering and data transformation.
- Interpretation of airline and route pricing patterns.

## Dataset Limitations

- The dataset represents a historical snapshot of flight fares.
- Ticket prices may change due to dynamic pricing.
- Booking lead time and seat availability are not provided.
- Fare classes, baggage allowance, and refund conditions are unavailable.
- The exact number of stops is not available for records categorized as 2+ stops.
- The dataset contains flight listings, not confirmed ticket purchases.

## Conclusion

This project demonstrates an end-to-end data analysis workflow using Indian domestic flight data. It provides insights into airline pricing, route comparisons, journey duration, and travel patterns while developing practical skills in Python, statistical analysis, data preprocessing, and visualization.

---

**Author:** Arnika  
**Project Type:** Data Analytics | Exploratory Data Analysis  
**Tools:** Python, NumPy, Pandas, Matplotlib, Seaborn, Plotly, Scikit-learn
