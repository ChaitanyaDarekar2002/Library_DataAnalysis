# 📚 Library Data Analysis Project

## 📌 Project Overview

This project focuses on analyzing a Library Management Dataset using Python, SQL, Power BI, and Tableau.
The objective of this project is to clean the dataset, perform exploratory data analysis (EDA), generate insights, and create interactive dashboards for better decision-making.

The analysis helps identify:

* Most popular genres
* Top-rated books
* Language distribution
* Books availability
* Most issued books
* Author popularity
* Publishing trends

This project demonstrates practical skills in:

* Data Cleaning
* Data Analysis
* SQL Querying
* Data Visualization
* Dashboard Creation
* Business Insights Generation

---

# 🛠 Tools & Technologies Used

| Tool       | Purpose                      |
| ---------- | ---------------------------- |
| Python     | Data Cleaning & Analysis     |
| Pandas     | Data Manipulation            |
| Matplotlib | Data Visualization           |
| SQL Server | Query Analysis               |
| Power BI   | Interactive Dashboard        |
| Tableau    | Data Visualization Dashboard |
| GitHub     | Project Hosting              |

---

# 📂 Dataset Information

The dataset contains information about books available in a library.

### Dataset Features

| Column Name    | Description             |
| -------------- | ----------------------- |
| Book ID        | Unique Book Identifier  |
| Book Title     | Name of the Book        |
| Author         | Book Author             |
| Genre          | Category of Book        |
| Publisher      | Publishing Company      |
| ISBN           | Book ISBN Number        |
| Year Published | Publication Year        |
| Pages          | Total Number of Pages   |
| Language       | Language of Book        |
| Price (₹)      | Book Price              |
| Available      | Availability Status     |
| Total Copies   | Total Copies in Library |
| Copies Issued  | Issued Copies           |
| Location/Shelf | Shelf Location          |
| Rating (1-5)   | User Rating             |

---

# 🧹 Data Cleaning Process

The following data cleaning steps were performed:

* Removed duplicate records
* Checked null values
* Corrected data types
* Created new calculated columns
* Standardized formatting
* Verified numerical columns
* Created price categories

### Python Libraries Used

```python id="t0uc1j"
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

---

# 📊 Exploratory Data Analysis (EDA)

The dataset was analyzed using multiple visualizations and statistical techniques.

## Analysis Performed

### ✅ Top Genres Analysis

Identified the most popular book genres available in the library.

### ✅ Language Distribution

Analyzed language-wise book distribution using pie charts.

### ✅ Rating Analysis

Calculated average ratings for books and genres.

### ✅ Author Analysis

Found authors with the highest number of books.

### ✅ Copies Issued Analysis

Identified most borrowed books.

### ✅ Availability Analysis

Checked available and unavailable books.

### ✅ Price Distribution

Analyzed pricing categories of books.

---

# 📈 Python Visualizations

The following charts were created using Matplotlib:

* Bar Charts
* Pie Charts
* Histogram
* Line Charts
* Distribution Charts

Example:

```python id="a1w8fq"
df['Genre'].value_counts().head(10).plot(kind='bar')

plt.title("Top Genres")
plt.xlabel("Genre")
plt.ylabel("Count")
plt.show()
```

---

# 🗄 SQL Analysis

SQL queries were written to generate business insights.

## SQL Operations Performed

* GROUP BY
* ORDER BY
* Aggregate Functions
* TOP Queries
* Filtering
* Sorting
* Average Calculations

### Example SQL Query

```sql id="9v8ynk"
SELECT TOP 10 Genre,
COUNT(*) AS Total_Books
FROM library
GROUP BY Genre
ORDER BY Total_Books DESC;
```

---

# 📊 Power BI Dashboard

An interactive Power BI dashboard was created to visualize the library dataset.

## Dashboard Features

* KPI Cards
* Genre Analysis
* Language Distribution
* Rating Analysis
* Copies Issued Analysis
* Interactive Filters
* Trend Analysis

## KPI Cards Used

* Total Books
* Average Rating
* Total Genres
* Total Copies Issued

---

# 📉 Tableau Dashboard

A Tableau dashboard was also created for advanced visual storytelling.

## Tableau Visuals

* Genre Analysis
* Author Analysis
* Rating Dashboard
* Publishing Trends
* Interactive Filters

---

# 🔍 Key Insights

### 📌 Most books are available in English language.

### 📌 Fiction and educational genres dominate the library.

### 📌 Some books are heavily issued, indicating high demand.

### 📌 Highly rated books attract more readers.

### 📌 Certain authors contribute significantly to library collections.

### 📌 A small percentage of books remain unavailable due to frequent borrowing.

---

# 🚀 Project Workflow

```text id="kk17ta"
Dataset Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
SQL Query Analysis
        ↓
Dashboard Creation
        ↓
Business Insights
        ↓
Project Documentation
```

---
---

# 💡 Skills Demonstrated

* Data Cleaning
* Data Analysis
* Data Visualization
* SQL Query Writing
* Dashboard Development
* Problem Solving
* Business Intelligence
* Data Storytelling

---

# 📷 Dashboard Preview

<img width="1918" height="1015" alt="Screenshot 2026-05-16 150218" src="https://github.com/user-attachments/assets/bcf430d9-2a7e-4f1a-9a57-2f10324f85ef" />


# 🎯 Conclusion

This project successfully demonstrates end-to-end data analysis using Python, SQL, Power BI, and Tableau.

The project provides valuable insights into library operations, book demand, ratings, and user preferences while showcasing strong analytical and visualization skills.

---

# 👨‍💻 Author

## Chaitanya Darekar
