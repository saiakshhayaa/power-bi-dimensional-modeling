📊 Power BI Dimensional Modeling & Data Integration

📌 Project Overview

This project focuses on building a multi-fact data model in Power BI using data from multiple sources. It demonstrates data transformation, integration, dimensional modeling, relationship management, and DAX measures to support business reporting and analysis.

🎯 Project Objectives

- Transform and prepare data using Power Query.
- Build fact and dimension tables.
- Apply dimensional modeling concepts.
- Establish relationships between tables.
- Create DAX measures for business reporting.
- Integrate data from multiple business processes.
- Explore row-level security to manage data access.

🛠️ Tools & Technologies

- 📊 Power BI – Data modeling, relationships, and reporting
- 🔄 Power Query – Data cleaning, transformation, and integration
- 🧮 DAX – Measures and calculations
- 📁 Microsoft Excel – Source data

🏗️ Data Modeling Approach

The project uses a multi-fact data model in which multiple fact tables share relevant dimension tables.

📂 Dimension Tables

- "dim_customer"
- "dim_product"
- "dim_geography"
- "dim_date"
- "dim_campaign"
- "dim_order_flags"

📈 Fact Tables

- "fact_sales"
- "fact_inventory"
- "fact_campaign_log"
- "fact_promotion"
- "fact_order_process"
- "fact_sales_targets"

⚙️ Key Implementations

- Combined and transformed data from multiple source tables using Power Query.
- Created fact and dimension tables to organize business data.
- Added keys to support relationships between tables.
- Unpivoted inventory data to structure it for analysis across products and periods.
- Split campaign product lists into individual records to represent campaign-product associations.
- Integrated order, shipment, invoice, and payment information for process analysis.
- Established relationships between multiple fact tables and shared dimensions.
- Created DAX measures to support reporting and analysis.
- Explored row-level security (RLS) to control data access based on user permissions.

📊 Report Overview

The Power BI report includes KPI cards and a summary table for analyzing orders, sales, units, revenue targets, and time-based performance.

📁 Repository Structure

d_data_modeling_project/
│
├── dimensional_modeling_project.pbix
├── dataset.xlsx
├── README.md
│
└── images/
    ├── data-model.png
    └── report-page.png

💡 Key Learning Outcomes

- Understand dimensional modeling, including fact tables, dimension tables, factless fact tables, and bridge tables.
- Work with multiple fact tables connected through shared dimensions and understand data granularity, keys, and relationship cardinality.
- Implement role-playing dimensions, such as bill-to and ship-to geography, to represent different business roles.
- Use Power Query for data integration and transformation.
- Create DAX measures for reporting and analysis.
- Apply row-level security (RLS) to control data access based on user permissions.

📝 Conclusion

This project provided practical experience in designing a multi-fact data model in Power BI, integrating data from multiple business processes, and preparing structured data for business intelligence reporting.