# DAX Assignment - Power BI Sales Analysis

## Project Overview

This project demonstrates the implementation of Data Analysis Expressions (DAX) in Power BI using a retail sales dataset. The objective is to perform business analysis, create calculated columns, measures, time intelligence calculations, and analyze sales performance through Matrix visualizations.

---

## Dataset Information

The project uses the following tables:

* Date_Dim
* Product_Dim
* Customer_Dim
* Region_Dim
* Sales_Fact
* Returns_Fact

### Data Model Relationships

* Sales_Fact → Date_Dim
* Sales_Fact → Product_Dim
* Sales_Fact → Customer_Dim
* Sales_Fact → Region_Dim
* Returns_Fact → Sales_Fact

---

## Calculated Columns

### Profit

Calculates profit for each sales transaction.

### ReturnFlag

Identifies whether an order was returned or not.

### Customer Full Name

Combines customer first and last name into a single field.

---

## Measures Created

### Sales & Profit Measures

* Total Sales
* Total Cost
* Total Profit
* Average Sale Per Transaction

### Return Analysis

* Total Orders
* Returned Orders
* Return Rate %

### Filter Context Measures

* Sales All Regions (ALL)
* Sales Above 3000 (FILTER)
* North Region Sales (CALCULATE)

### Time Intelligence Measures

* Sales YTD
* Previous Year Sales
* Running Total
* YoY Sales Growth %

### Iterator Functions

* Profit SUMX
* Average Profit (AVERAGEX)

---

## DAX Functions Demonstrated

### Logical Functions

* IF
* SWITCH

### Text Functions

* UPPER
* LEFT

### Date Functions

* YEAR
* MONTH
* EOMONTH

### Aggregation Functions

* COUNTX
* DISTINCTCOUNT

### Relationship Functions

* RELATED

---

## Matrix Visualization

The project uses Matrix Visuals to analyze:

* Sales Performance by Region
* Product Category Analysis
* Customer Segment Analysis
* Monthly Sales Trends
* Profitability Analysis
* Return Analysis

---

## Key Learning Outcomes

* Understanding DAX Calculated Columns
* Creating Business Measures
* Using Filter Context Functions
* Implementing Time Intelligence
* Working with Relationships using RELATED()
* Building Analytical Matrix Reports in Power BI

---

## Tools Used

* Microsoft Power BI Desktop
* DAX (Data Analysis Expressions)

---

## Author

**Maulik Baldaniya**

Data Analytics| Power BI Developer | SQL & Python
