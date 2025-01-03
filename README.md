# Supply Chain Data Analytics Architecture

This project uses a modern data pipeline designed for supply chain data analytics using Azure cloud services and visualization tools. The architecture is modular, scalable, and supports data ingestion, transformation, storage, analytics, and dashboarding.

---

## 1. Data Source  
**Description:**  
This stage represents the origin of the data. It could include databases, ERP systems, IoT devices, or other enterprise systems generating supply chain data.  
**Data Types:**  
- Transactional data  
- Inventory levels  
- Supplier performance  
- Logistics data  
- Demand forecasts  

---

## 2. Data Ingestion  
**Component:** Azure Data Factory  
**Description:**  
Azure Data Factory (ADF) is used to orchestrate and automate the movement of data from various sources to the raw data store.  

---

## 3. Raw Data Storage  
**Component:** Azure Data Lake Gen 2  
**Description:**  
The ingested raw data is stored in Azure Data Lake Gen 2, a highly scalable and secure data storage solution optimized for big data analytics.  

---

## 4. Data Transformation  
**Component:** Azure Databricks  
**Description:**  
Azure Databricks is used for processing and transforming raw data into a structured format suitable for analytics.  

---

## 5. Transformed Data Storage  
**Component:** Azure Data Lake Gen 2  
**Description:**  
The transformed data is saved back into Azure Data Lake Gen 2, now in a structured and analysis-ready format.  

---

## 6. Analytics  
**Component:** Azure Synapse Analytics  
**Description:**  
Azure Synapse Analytics is used to query and analyze the structured data stored in Azure Data Lake.  

---

## 7. Dashboard and Visualization  
**Components:**  
- Power BI  

**Description:**  
These tools are used to create interactive dashboards and visualizations for business users.  

---

## 8. Results
-1
![Sales Dashboard](./assets/sdb1.png)
![Supplier Dashboard](./assets/sdb2.png)


## Summary  
This architecture efficiently manages the end-to-end data pipeline for supply chain analytics:  

1. Collects data from various sources.  
2. Orchestrates and stores raw data in Azure Data Lake.  
3. Processes and enriches data using Azure Databricks.  
4. Facilitates structured analytics with Azure Synapse.  
5. Presents insights via visualization tools for actionable decision-making.  

**Key Benefits:**  
- Scalability  
- Real-time insights  
- Actionable intelligence tailored to supply chain optimization  
