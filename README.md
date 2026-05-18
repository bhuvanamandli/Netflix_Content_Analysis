# 🎬 Netflix Content Analysis (Power BI Project)

## 📊 Overview

Netflix Content Analysis is an interactive Power BI project built using a dataset of **16,000+ Netflix movies (up to 2025)**. The goal of this project is to explore and analyze key patterns in Netflix content, including **genres, ratings, popularity, revenue, budget, and global distribution**.

This project helps uncover insights into how Netflix content is distributed across countries, how different genres perform, and what factors influence movie success.

---

## 🛠️ Technologies Used

- Power BI  
- Power Query  
- DAX (Data Analysis Expressions)  
- Data Modeling  

---

## 📂 Dataset Structure

The dataset contains multi-value fields that were normalized for better analysis and performance.

### 🔹 Main Tables

- `netflix_movies_details_upto_2025` – Core movie details  
- `movies_genre` – Mapping of movies and genres  
- `movie_countries` – Mapping of movies and production countries  
- `movie_cast` – Mapping of movies and cast members  

---

## 🔗 Data Modeling

To improve performance and avoid duplication issues, multi-value columns such as **Genres, Countries, and Cast** were split into separate mapping tables.

### Relationships

- Primary Key: `show_id`  
- Relationship Type: **One-to-Many**

---

## 📈 Dashboards

### 1. 🎭 Content & Genre Analysis
- Movies by Genre  
- Average Rating by Genre  
- Release Year Trends  
- Popularity Analysis  

---

### 2. 🎥 Movie Performance Analysis
- Budget vs Revenue Comparison  
- ROI (Return on Investment) Analysis  
- Top Revenue Movies  
- Ratings & Vote Analysis  

---

### 3. 🌍 Global Movie Distribution
- Country-wise movie distribution (Map Visualization)  
- Movie count by country  
- Release year trends by region  

---

## 💡 Key Learnings

- Data cleaning and transformation using Power Query  
- Handling multi-value columns using normalization  
- Building efficient data models in Power BI  
- Writing DAX measures for advanced analytics  
- Creating interactive and insightful dashboards  
- Performing geographic analysis in BI tools  

---

## 📌 Conclusion

This project provides meaningful insights into Netflix’s content strategy, including trends in genres, global reach, and financial performance. It demonstrates how data visualization and modeling can transform raw movie data into actionable business insights.

---  