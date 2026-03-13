# Melodica Business Intelligence Pipeline 🎵
**End-to-End Data Engineering & BI Solution**

---

## 📌Project Overview
This project was developed for Melodica Media Corporation, an **imaginary** online music store based in California. The objective was to transform raw transactional data (OLTP) into actionable business insights by building a robust Data Pipeline.

The solution covers the entire BI lifecycle: from source data exploration and ETL processing to Data Warehouse design and interactive dashboarding.

## 🛠️ Tech Stack
* **Database Engine:** SQL Server (T-SQL)
* **Data Modeling:** Dimensional Modeling (Star Schema)
* **Analytics & Visualization:** Power BI Desktop
* **Version Control:** Git & GitHub
* **Documentation:** MS Office Suite

## 🏗️ Project Structure
1. **OLTP Database:** The source data based on the Chinook database.
2. **Staging Area:** A temporary landing zone for data cleaning and transformation.
3. **Data Warehouse:** A Star Schema design for optimized analytical queries.
4. **Power BI Dashboard:** Interactive visualization of sales, customer behavior, and employee performance.

## 📊 Key Insights & Dashboards
The Power BI solution provides 360-degree visibility through four main lenses:
* **Sales Performance:** Revenue trends by year/month and growth metrics.
* **Product Analysis:** Identification of top-selling Genres and Artists.
* **Customer Geography:** Regional sales distribution across countries and cities.
* **Employee Impact:** Performance tracking of Support Representatives based on sales attribution.

## 🚀 How to Run
1. Execute `01_Chinook_SqlServer.sql` to create the source DB.
2. Run `ChinookStaging.sql` to prepare the data.
3. Run `ChinookDW.sql` to build the Warehouse.
4. Open `PF.pbix` in Power BI Desktop to view the report.
