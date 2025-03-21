# **PPP Loan Data Analysis Using PySpark**  

## **Overview**  
This project analyzes Paycheck Protection Program (PPP) loan data from the SBA, integrating it with census data to uncover insights on loan distribution, banking patterns, and socioeconomic trends. The dataset contains 3M+ records and 900+ columns, requiring efficient big data processing with PySpark.  

## **Key Objectives**  
- Merge Census and PPP Data based on ZIP codes.  
- Identify Top 10 states & banks with the highest loan distributions.  
- Analyze per capita loan funding by ZIP codes.  
- Determine top industries (NAICS codes) receiving loans.  
- Examine socioeconomic factors influencing loan amounts.  
- Identify ZIP codes with the highest per capita loans to women-owned businesses.  
---

## **Dataset & Tools**  
### **Data Sources**  
- PPP Loan Data (~2.76 Millions of records)  
- Census Data (Socioeconomic indicators)  [https://github.com/Ro-Data/Ro-Census-Summaries-By-Zipcode]

### **Tech Stack**  
- PySpark (Big Data Processing)  
- Pandas (Data Handling)  
- Matplotlib & Seaborn (Visualization)  
---

## **Skills & Learnings in PySpark**  
This project enhanced proficiency in handling large-scale datasets and optimized data processing workflows. Key learnings:  

* **Data Handling & Cleaning**  
    * Setting headers in CSV/text files, merging data row-wise (PPP data) and column-wise (Census data).  
    * Handling null values and extracting substrings using `substr`.  

* **Data Type Optimization**  
    * Efficient type conversions for large datasets (~900 columns) using loop-based transformations.  

* **Aggregation & Querying**  
    * Using groupBy, aggregate, sort, orderBy, limit, and double aggregation for insightful analysis.  

* **Filtering & Data Extraction**  
    * Applying efficient conditional filtering and query optimization.  

* **Data Visualization in PySpark**  
    * Visualizing key insights within PySpark.  

* **Code Optimization & Readability**  
    * Writing well-structured, optimized, and commented PySpark code.  

---



