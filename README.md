# 🧩 ERD - Kiwilytics Project

This repository contains the **Entity-Relationship Diagram (ERD)** for a retail sales database designed as part of the **Kiwilytics Data Engineering Course**.

---

## 📘 Project Overview

The ERD illustrates how data is structured and related across different entities in a retail business system.  
It serves as the foundation for designing the database schema that supports data storage, querying, and analysis.

---

## 🧱 Entities and Relationships

The database consists of the following main tables:

- **Employees** – Stores information about company employees who handle customer orders.  
- **Customers** – Contains customer data such as names, contact info, and addresses.  
- **Orders** – Represents customer orders and links customers to employees and shippers.  
- **Order_Details** – Contains details of products within each order (quantity, price, discount).  
- **Products** – Holds product information, supplier details, and category references.  
- **Suppliers** – Lists all suppliers and their contact details.  
- **Category** – Defines product categories (e.g., beverages, electronics).  
- **Shippers** – Stores information about shipping companies.

---

## 🖼️ ERD Diagram

Below is the database diagram designed in **drawSQL**:

![ERD Diagram](erd-kiwilytics-project.png)

---

## 💡 Use Case

This database design can be used for:
- Building a **Data Warehouse** for business analytics  
- Tracking **sales performance** and **employee productivity**  
- Performing **ETL processes** and **data integration** tasks  
- Creating dashboards for **business intelligence (BI)** tools  

---

## 🛠️ Tools Used

- **drawSQL** – for designing and visualizing the ERD  
- **GitHub** – for project version control and portfolio presentation  

---

## 📂 Author

**Malak Shehada**  
_Data Engineering Student at Kiwilytics_
