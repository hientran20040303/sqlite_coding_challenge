# SQLite Business Intelligence & Sales Analytics

## 📌 Project Overview
This project focuses on extracting actionable business insights from a relational database using advanced SQL techniques. The analysis covers three key business areas: **Sales Performance**, **Human Resources Benchmarking**, and **Customer Loyalty Mapping**. 

The goal was to transform raw transactional data into structured reports that answer specific business questions regarding revenue, employee compensation, and geographic market penetration.

## 📊 Key Business Questions Addressed
*   **Customer Value:** Identifying the top 5 customers by lifetime spend to target for VIP programs.
*   **Revenue Analysis:** Calculating total revenue by product category to determine high-performing inventory.
*   **HR Analytics:** Benchmarking employee salaries against department averages to identify compensation outliers.
*   **Geographic Insights:** Ranking cities by "Gold" loyalty status distribution to identify key market hubs.

## 🛠️ Technologies & Tools Used
*   **Database Engine:** SQLite 3
*   **Language:** SQL (Structured Query Language)
*   **Tools:** VS Code + SQLTools Extension
*   **Core Concepts:** Multi-table Joins, Subqueries, Aggregations (GROUP BY), and Filtering (HAVING and WHERE).

## 📂 Project Structure
*   `bais_sqlite_lab.db`: The relational database containing sales, product, and employee data.
*   `challenge.sql`: The complete script containing all analytical queries.
*   `INSIGHTS.md`: A summary of the data-driven findings and business recommendations.

## 🏃 How to Run the Analysis
1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/hientran20040303/sqlite_analytics.git
    ```
2.  **Open the Database:** 
    Use a SQLite browser (like [DB Browser for SQLite](https://sqlitebrowser.org/)) or the SQLite extension in VS Code to open `bais_sqlite_lab.db`.
3.  **Execute Queries:** 
    Run the queries located in `challenge.sql` to generate the result sets.
