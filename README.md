# Instagram Data Analysis using SQL and Power BI

## 📌 Project Summary
This project involves **end-to-end SQL-based and power BI analysis of Instagram user activity data** to uncover insights related to **user engagement, growth trends, content performance, and platform integrity**. The analysis answers **real-world business and marketing questions** using structured queries and relational database concepts.

The project demonstrates strong proficiency in **SQL, Power BI ,data analysis, analytical thinking, and business problem-solving**, making it suitable for **Data Analyst, Business Analyst, and SQL Analyst roles**.

---

## 🧰 Tech Stack
- **Database:** MySQL  
- **SQL Version:** 9.2.0  
- **IDE:** SQL Workbench  
- **Operating System:** macOS,Windows for Power BI
- Power BI desktop

---

## 📊 Dataset Overview
The dataset simulates a real-world Instagram environment and includes the following relational tables:
- `users` – user profile and registration data  
- `photos` – photo upload information  
- `likes` – user engagement via likes  
- `comments` – textual engagement data  
- `tags` – hashtag metadata  
- `photo_tags` – many-to-many relationship between photos and hashtags  

---

## 🎯 Business Problems Solved

### 1️⃣ Loyal User Identification
- **Objective:** Identify the top 5 earliest registered users.
- **SQL Concepts:** `ORDER BY`, `LIMIT`, date sorting  
- **Business Value:** Enables reward programs for long-term and loyal users.

---

### 2️⃣ Inactive User Detection
- **Objective:** Find users who have never posted a photo.
- **SQL Concepts:** `LEFT JOIN`, `NULL` filtering  
- **Business Value:** Helps product teams target inactive users for re-engagement campaigns.

---

### 3️⃣ Contest Winner Analysis
- **Objective:** Identify the user whose photo received the highest number of likes.
- **SQL Concepts:** Subqueries, `GROUP BY`, `COUNT`, `ORDER BY`  
- **Business Value:** Automates contest winner selection based on engagement metrics.

---

### 4️⃣ Hashtag Performance Analysis
- **Objective:** Identify the top 5 most frequently used hashtags.
- **SQL Concepts:** Joins, aggregation, sorting  
- **Business Value:** Supports marketing teams in selecting high-performing hashtags for campaigns.

---

### 5️⃣ User Registration Trend Analysis
- **Objective:** Determine the day of the week with the highest number of user registrations.
- **SQL Concepts:** Date functions, grouping  
- **Business Value:** Optimizes ad campaign launch timing to maximize user acquisition.

---

### 6️⃣ User Engagement Metrics
- **Objective:** Calculate:
  - Average posts per user  
  - Average photos per user  
- **SQL Concepts:** Variables, aggregate functions  
- **Business Value:** Provides high-level KPIs to assess overall platform engagement.

---

### 7️⃣ Bot & Fake Account Detection
- **Objective:** Identify users who liked 100% of available photos.
- **SQL Concepts:** `HAVING`, aggregation, joins  
- **Business Value:** Flags suspicious activity for platform integrity and moderation.

---

## 🧠 SQL & Analytical Skills Demonstrated
- Writing **complex SQL queries** using joins and subqueries  
- Applying **aggregate and analytical functions**  
- Using **date and time functions** for trend analysis  
- Translating **business requirements into SQL solutions**  
- Identifying **patterns, anomalies, and engagement insights**  
- Structuring queries for **performance and clarity**

---
## 📈 Power BI Dashboard Overview
The Power BI dashboard is divided into **two main pages**:

### 🔹 Page 1: Signup & Growth Analysis
- KPI Cards:
  - Total Users
  - Total Companies
  - Number of Languages
- User Growth by Year (Line Chart)
- Weekly User Registration (Bar Chart)
- Year slicer for interactive analysis

*(Reference: Dashboard overview shown in the PBIX and PDF summary page)* :contentReference[oaicite:0]{index=0}

---

### 🔹 Page 2: Activity & Engagement Analysis
- Event Activity Over Time
- Activity per User (Average)
- Device Distribution (Pie / Treemap)
- Location-wise User Distribution

This page focuses on **behavioral and engagement insights**, helping understand how users interact with the platform.

---


## 📈 Key Outcomes
- Extracted actionable insights on **user behavior, engagement, and growth**
- Identified **high-value users, inactive users, and potential bot accounts**
- Provided **data-driven recommendations** for marketing and product teams
- Power bi dashboard KPI driven

---

## 📄 Project Documentation
Detailed queries, outputs, and insights are documented in:
**`Project 2 instagram data analysis.pdf`**

---

## 👤 Author
**Ankit Gaurav**  
Aspiring Data Analyst | SQL | Python | Data Analytics  

---

## 🚀 How to Use This Repository
1. Import the dataset into MySQL  
2. Execute the SQL queries step-by-step  
3. Review outputs to understand business insights
4. Use bi file to use slicer and look at different aspect of data.

---

## 🔮 Future Enhancements
- Perform cohort and retention analysis
- Optimize queries for large-scale datasets
- Extend analysis with Python for automation

---

⭐ *This project reflects practical SQL  and Power BI usage aligned with real business scenarios.*
