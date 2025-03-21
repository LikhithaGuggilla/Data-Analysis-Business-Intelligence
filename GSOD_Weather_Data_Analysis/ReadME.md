# **Advanced Weather Analysis Using PySpark**

## **Overview**  
This project leverages PySpark to analyze the Global Summary of the Day (GSOD) dataset, containing **12 million rows and 32 columns**. The goal is to conduct advanced weather data analysis using **PySpark SQL, Pandas UDFs, and window functions**, demonstrating the ability to efficiently process large datasets.

---

## **Data Source:**
- Global Summary of the Day (GSOD) dataset (~12M rows, 32 columns)

## **Tech Stack:**
- Apache PySpark (Big Data Processing)
- Pandas UDFs (Efficient Data Transformation)
- SQL Queries in Spark (Data Aggregation & Filtering)
- Matplotlib & Seaborn (Visualization)

---

## **Skills & Learnings in PySpark**  
This project demonstrates proficiency in PySpark, particularly in big data processing, SQL integration, and time-series analysis.

* **Data Processing & Cleaning**
    - Handling large-scale datasets (12M+ rows) efficiently in PySpark.
    - Using SQL-style queries to extract relevant insights.

* **Filtering & Aggregation**
    - Selecting records where temperature >90°F & wind speed >20 knots.
    - Finding top 10 stations with extreme weather.

* **Time-Series Analysis (Window Functions)**
    - Computing a 3-day rolling window temperature.
    - Finding the hottest and windiest months/years at a given station.

* **Pandas UDFs for Data Transformation**
    - Writing Pandas UDFs to:
    - Convert temperature from Fahrenheit to Celsius.
    - Convert wind speed from knots to meters per second.

* **Threshold-Based Consecutive Value Analysis**
    - Creating a new column to track maximum consecutive days where temperature exceeded 90°F.

* **Data Visualization & Insights**
    - Generating plots to showcase temperature trends and extreme weather events.

---

## **Results & Insights**  

* **Extreme Weather Conditions:**
    - Found top stations experiencing extreme temperatures and high winds.

* **Hottest & Windiest Periods:**
    - Identified the hottest month/year in the world.

    **It is hot and windy at Khanaqin and July 2018 is the hottest.**

* **Rolling Temperature Trends:**
    - Finding the hottest and windiest months/years at a given station.

    The plot shows a clear seasonal temperature pattern with peaks in summer (mostly May) and dips in winter, indicating a cyclical trend. The fluctuations suggest consistent yearly temperature variations.

* **Consecutive Days Analysis:**
    - Created a column to track maximum consecutive days ≥90°F in the hottest month identified (May).

    The plot shows the cumulative count of days where temperature exceeded a threshold (e.g., ≥90°F) in May 2018 for a specific station. A steady increase in the latter part of the month indicates a prolonged period of extreme heat.


