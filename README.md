# 🎧 Spotify Track Analysis Project

## Project Description
This project analyzes Spotify track-level data to understand how different audio features, genres, and content attributes influence track popularity and listening characteristics.  
The project demonstrates a complete **data analytics workflow**, starting from raw data inspection to SQL-based analysis and interactive dashboard creation.

---

## Tools Used & Their Role in the Project

### 1. Microsoft Excel
Excel was used as the **first step of data handling**.

Its role in this project:
- Initial inspection of the dataset
- Checking column names and structure
- Verifying data types (numerical, text, boolean)
- Detecting obvious inconsistencies or missing values
- Ensuring the CSV file is ready for database import

Excel was not used for analysis but for **data understanding and validation**.

---

### 2. SQLite
SQLite was used as the **primary database** for this project.

Its role:
- Storing the Spotify dataset in a structured format
- Handling large datasets efficiently compared to spreadsheets
- Enabling fast querying and aggregation of data
- Supporting SQL-based analysis without requiring a server setup

SQLite allowed the project to remain lightweight, portable, and easy to share.

---

### 3. SQL
SQL was the **core analysis tool** of this project.

Its role:
- Extracting meaningful insights from the dataset
- Performing aggregations such as averages and counts
- Grouping tracks by genre, tempo, mood, and explicit content
- Creating derived fields using `CASE` statements (e.g., tempo categories, mood classification)
- Preparing analysis outputs suitable for visualization

All analysis queries are stored in a dedicated `.sql` file for transparency and reproducibility.

---

### 4. DB Browser for SQLite
DB Browser for SQLite was used as the **database management interface**.

Its role:
- Importing the CSV dataset into SQLite
- Viewing table structure and records
- Running and testing SQL queries
- Exporting and validating query results
- Managing the database without writing setup scripts

This tool made working with SQLite accessible and efficient.

---

### 5. Power BI
Power BI was used for **data visualization and dashboard creation**.

Its role:
- Connecting analysis results to interactive visuals
- Designing charts and KPIs to communicate insights clearly
- Creating an analytical dashboard with filters and comparisons
- Transforming raw SQL outputs into business-friendly visuals

## 📊 Dashboard Screenshots

![Dashboard Overview](Screenshot%20263.png)

![Genre Analysis](Screenshot%20264.png)

The Power BI dashboard acts as the **final presentation layer** of the project.


## Author
**Mayank Bisht**  
Aspiring Data Analyst | SQL | Power BI | Data Analytics Projects









