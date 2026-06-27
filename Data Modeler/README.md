<div align="center">

# ⭐ Data Modeler
### Power BI Data Modeling & Relationship Building Project

<p>

<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">

<img src="https://img.shields.io/badge/Data_Modeling-blue?style=for-the-badge">

<img src="https://img.shields.io/badge/Star_Schema-success?style=for-the-badge">

<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">

</p>

<p>

<a href="https://github.com/mkbaldaniya/PowerBI_Exams">
<img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github">
</a>

<a href="https://www.linkedin.com/in/maulik-baldaniya-795174262/">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin">
</a>

<a href="mailto:maulikbaldaniya001@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail">
</a>

</p>

---

### 📌 Professional Power BI Data Modeling Project

*Building a normalized relational data model using Power BI Model View.*

</div>

---

# 📖 Project Overview

**Data Modeler** is a Power BI project focused exclusively on **Data Modeling**.

The objective is to create a clean, scalable and optimized relational model by designing proper relationships, hierarchies and schema structures.

No dashboards, DAX or charts were created.

---

# 🎯 Objectives

✔ Import multiple datasets

✔ Build relationships

✔ Design Star Schema

✔ Implement Snowflake Schema

✔ Configure Cardinality

✔ Handle Cross Filter Direction

✔ Create Hierarchies

✔ Test Relationships

---

# 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| Microsoft Power BI | Data Modeling |
| Model View | Relationship Design |
| Power Query | Data Preparation |
| Excel | Data Source |

---

# 📂 Dataset

The project contains six normalized datasets.

| Table | Description |
|--------|------------|
| Sales_Fact | Transaction Table |
| Customer_Dim | Customer Information |
| Product_Dim | Product Details |
| Region_Dim | Region Details |
| Date_Dim | Calendar Table |
| Returns_Fact | Returned Orders |

---

# ⭐ Schema Design

```text
                 Date_Dim
                     │
                     │
                     ▼
Customer_Dim ──► Sales_Fact ◄── Product_Dim
                     │
                     │
                     ▼
                Region_Dim
                     │
                     ▼
               Returns_Fact
```

---

# 🔗 Relationships

Created relationships between

- Sales → Customer
- Sales → Product
- Sales → Region
- Sales → Date
- Returns → Sales
- Returns → Date (Inactive)

---

# ⚙ Model Features

## Relationship Types

- One-to-Many
- Many-to-One
- Active Relationships
- Inactive Relationships

---

## Cross Filter

- Single Direction
- Bidirectional (where required)

---

## Hierarchies

Created

### Date

```
Year
   └── Quarter
          └── Month
                 └── Date
```

### Region

```
Country
     └── State
            └── City
```

### Product

```
Category
      └── Subcategory
              └── Product
```

---

# 📌 Tasks Completed

## Data Preparation

- Import Excel Files
- Remove Blank Rows
- Correct Data Types

---

## Relationship Building

- Primary Keys
- Foreign Keys
- Model View
- Relationship Validation

---

## Schema Design

- Star Schema
- Snowflake Schema
- Relationship Optimization

---

## Advanced Modeling

- Cross Filter Direction
- Cardinality
- Inactive Relationship
- Relationship Testing

---

## Verification

Matrix Table created for

- Product Category Analysis
- Region Analysis
- Fiscal Year Analysis

---

# 📁 Repository Structure

```text
Data Modeler/
│
├── Data Modeler.pbix
├── Customer_Dim.xlsx
├── Product_Dim.xlsx
├── Region_Dim.xlsx
├── Date_Dim.xlsx
├── Sales_Fact.xlsx
├── Returns_Fact.xlsx
├── Images/
└── README.md
```

---

# 💡 Skills Demonstrated

- Data Modeling
- Star Schema
- Snowflake Schema
- Relationship Management
- Primary Keys
- Foreign Keys
- Cardinality
- Hierarchies
- Model View
- Power Query

---

# 🚀 Learning Outcomes

This project demonstrates

- Enterprise Data Modeling
- Dimensional Modeling
- Relationship Design
- Power BI Best Practices
- Normalized Database Concepts

---

# 📈 Future Improvements

- DAX Measures
- Dashboard Development
- Performance Optimization
- Incremental Refresh
- Row Level Security

---

# 👨‍💻 Author

## Maulik Baldaniya

📧 **Email**

maulikbaldaniya001@gmail.com

💼 **LinkedIn**

https://www.linkedin.com/in/maulik-baldaniya-795174262/

💻 **GitHub**

https://github.com/mkbaldaniya

---

<div align="center">

### ⭐ If you found this repository helpful, please give it a Star.

Made with ❤️ using Microsoft Power BI

</div>
