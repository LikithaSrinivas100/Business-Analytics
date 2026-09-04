# Assignment 01: Advanced Cross-Platform ETL Ingestion

##  Project Overview
This laboratory experiment establishes a unified analytical schema by integrating fragmented enterprise data layers across physical boundaries:
* **Fact Data (Local Files):** Transaction ledgers and client profile coordinates.
* **Dimension Data (MySQL Server):** Live relational tables mapping product items and store branches.

##  Core Implementation Steps
1. **Driver Integration:** Deployed the official MySQL Connector/NET driver platform to clear client connector exceptions.
2. **Power Query ETL:** Standardized keys (`ProductID`, `StoreID`) into matching integer arrays.
3. **Data Modeling:** Constructed a **Star Schema** layout using unidirectional 1-to-Many (`1:*`) filtering links.

##  Contents
* `*.pbix`: Complete Power BI project containing connections to local files and `localhost:3306`.
* `*.pdf`: Formal structured submission document.
