# 📊 Power BI Dimensional Modeling & Data Integration

## 📌 Project Overview

A **Power BI data modeling project** focused on integrating data from multiple business processes and building a multi-fact data model.

The project covers **data transformation, dimensional modeling, fact and dimension tables, relationship management, DAX measures, and row-level security (RLS)** to organize business data for reporting and analysis.

## 🎯 Project Objectives

- Integrate and transform data from multiple source tables.
- Design fact and dimension tables for business analysis.
- Build relationships between multiple fact tables using shared dimensions.
- Explore dimensional modeling concepts, including factless fact tables and bridge tables.
- Create DAX measures for reporting and analysis.
- Understand role-playing dimensions and row-level security.

## 📂 Dataset Overview

The dataset consists of multiple related tables covering different business processes, including customer management, products, orders, inventory, campaigns, invoicing, payments, shipments, sales targets, and geographical information.

These source tables were transformed and integrated using Power Query to build a structured, multi-fact data model for business intelligence and reporting.

## ⚙️ Data Preparation & Transformation

- 🔗 **Data Integration:** Merged and appended related source tables to consolidate information across business processes.
- 🧹 **Data Cleaning:** Removed unnecessary columns, redundant fields, and irrelevant data.
- 🔑 **Key Creation:** Created index-based keys where required to support table relationships.
- 🔄 **Data Restructuring:** Unpivoted inventory data and split campaign product lists into individual records.
- 📐 **Dimensional Modeling:** Organized transformed data into fact and dimension tables with appropriate relationships.
- 🌍 **Relationship Management:** Connected multiple fact tables through shared dimensions and handled different geographical roles.
- 🔐 **Security:** Explored row-level security (RLS) to understand data access based on user permissions.

## 🏗️ Data Model Overview

The model brings together data related to sales, customers, products, inventory, campaigns, promotions, orders, and sales targets.

### 📐 Dimension Tables

| Dimension Table | Purpose |
|---|---|
| `dim_customer` | Stores customer-related information. |
| `dim_product` | Stores product and product category information. |
| `dim_geography` | Represents geographical information for different business roles. |
| `dim_date` | Supports time-based analysis. |
| `dim_campaign` | Stores campaign details, channels, dates, and budgets. |
| `dim_order_flags` | Organizes order attributes such as channel, status, and priority. |

### 📈 Fact Tables

| Fact Table | Purpose |
|---|---|
| `fact_sales` | Stores order-line-level sales information, including quantities, prices, and line totals. |
| `fact_inventory` | Stores inventory values by product and period. |
| `fact_campaign_log` | Stores campaign performance metrics such as impressions, clicks, and spend. |
| `fact_promotion` | Represents campaign-to-product associations. |
| `fact_order_process` | Brings together order lifecycle information, including shipment, invoice, and payment dates. |
| `fact_sales_targets` | Stores target revenue information by date or period. |

## 🔬 Data Modeling Concepts

- ⭐ **Multi-Fact Data Modeling:** Organizing multiple fact tables within one data model.
- 🔗 **Shared Dimensions:** Connecting related fact tables through common dimensions.
- 📐 **Data Granularity:** Understanding what each row represents in a fact table.
- 🔑 **Keys and Relationships:** Working with keys, relationship cardinality, and connections between tables.
- 🧩 **Factless Fact Tables:** Representing business relationships or occurrences without numerical measures.
- 🔀 **Bridge Tables:** Representing associations between entities, such as campaigns and products.
- 🌍 **Role-Playing Dimensions:** Using geography for different purposes, such as bill-to and ship-to locations.
- 🔐 **Row-Level Security (RLS):** Understanding how data access can be restricted according to user permissions.

## 🧮 DAX & Reporting

- Created DAX measures for key metrics such as total orders and total sales.
- Built basic KPI cards, tables, and visuals to validate the data model and summarize business data.

## 🛠️ Tools & Technologies

**Power BI** • **Power Query** • **DAX** • **Microsoft Excel**

## ⭐ Key Learning Outcomes

- Understand dimensional modeling, including fact tables, dimension tables, factless fact tables, and bridge tables.
- Work with multiple fact tables connected through shared dimensions.
- Understand data granularity, keys, relationship cardinality, and role-playing dimensions.
- Use Power Query for data integration, cleaning, and transformation.
- Create DAX measures for reporting and analysis.
- Explore row-level security (RLS) and its role in data access control.

## 📁 Project Structure

    d_data_modeling_project/
    │
    ├── dimensional_modeling_project.pbix
    ├── dataset.xlsx
    ├── README.md
    │
    └── images/
        ├── data-model.png
        └── report-page.png

## 📝 Conclusion

This project demonstrates how **Power Query and dimensional modeling** can be used to integrate data from multiple business processes and build a multi-fact data model in Power BI. It strengthened my understanding of **shared dimensions, data granularity, factless fact tables, bridge tables, relationship management, and DAX measures** for business intelligence reporting.
