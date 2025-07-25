# 🏗️ SQL Data Warehouse Project (Learning Version)

This repository is a **personal learning adaptation** of the original [SQL Data Warehouse Project](https://github.com/DataWithBaraa/sql-data-warehouse-project) by **DataWithBaraa (Baraa Khatib Salkini)**.

I cloned this project to study and understand **modern data warehouse architecture**, focusing on best practices in:
- ETL pipelines
- Data modeling (star schema)
- SQL transformations
- Layered architecture (Bronze, Silver, Gold)
- Business analytics using SQL

---

## 🎯 Learning Objectives

I use this project to:
- Learn how raw data (from ERP & CRM) is ingested, transformed, and modeled
- Understand the **Medallion Architecture** concept in practice
- Practice building ETL workflows with SQL scripts
- Analyze business questions using warehouse-ready data

This is part of my effort to gain practical, industry-relevant skills in:
- **Data Engineering**
- **Data Warehousing** 
- **Analytical SQL**

---

## 🧠 My Study Approach

I prefer to start by cloning real-world projects and then:

1. **Go through each script and diagram**
2. **Add personal comments and annotations**
3. **Experiment with queries and structure**
4. **Modify or extend the project as needed**

This helps me focus on **understanding the entire flow** rather than spending time setting up from scratch.

---

## 📦 Repository Structure

```
sql-data-warehouse-project/
├── datasets/         # ERP and CRM CSV source data
├── docs/             # Draw.io diagrams & documentation  
├── scripts/
│   ├── bronze/       # Load raw data
│   ├── silver/       # Clean & standardize
│   └── gold/         # Model for analytics (star schema)
├── tests/            # Data quality checks
├── README.md         # Project overview
└── LICENSE
```

---

## 🛠️ Tools Used

- **SQL Server** (Express)
- **SSMS** (SQL Server Management Studio)
- **T-SQL**
- **Draw.io** for architecture design
- **Notion** for documentation templates

---

## 📌 Original Source & Credit

- 💻 **Original Repository**: [github.com/DataWithBaraa/sql-data-warehouse-project](https://github.com/DataWithBaraa/sql-data-warehouse-project)
- 📺 **Course by**: Data With Baraa
- 🧾 **License**: MIT

> **All credits** for the architecture, scripts, and idea go to the original creator.  
> This repo is used purely for **educational and non-commercial learning**.

---

## 🚀 Future Plans

- [ ] Add personal annotations on the SQL scripts
- [ ] Run the scripts and test ETL processes on my local SQL Server
- [ ] Build a dashboard based on the Gold layer outputs using Tableau or Power BI
- [ ] Extend the model to include historical snapshots
- [ ] Document my learning journey and key insights

---

## 📚 Learning Resources

If you're also interested in learning data warehousing, I recommend checking out:
- The original project by DataWithBaraa
- Microsoft's SQL Server documentation
- Kimball Group's data warehousing methodology

---

*Happy learning! 🎓*
