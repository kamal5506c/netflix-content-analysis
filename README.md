# 🎬 Netflix Content Analysis

## 📌 Project Overview
This project analyzes Netflix's content library (Movies & TV Shows) to understand genre trends, content ratings, growth patterns, and platform composition using data cleaning, EDA, and interactive dashboard visualization.

## 🛠️ Tools & Technologies
- **Python** (Pandas) – Data cleaning and preprocessing
- **SQL** (SQLite via Python) – Data querying and analysis
- **Google Colab** – Development environment
- **Power BI** – Interactive dashboard and visualization

## 📊 Dataset
- **Source:** [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Fields:** Title, type, director, cast, country, date_added, release_year, rating, duration, listed_in (genres), description

## 🧹 Data Cleaning Steps
1. Removed duplicate rows
2. Handled missing values in director, cast, country, rating, and date_added columns
3. Converted date_added column to proper datetime format
4. Converted release_year to numeric format
5. Verified data consistency across all columns

## 📈 Dashboard Features
- Total shows, total directors, genre count, and rating count (KPI cards)
- Genre distribution by total shows
- Content rating distribution (TV-MA, TV-14, etc.)
- Movies vs TV Shows composition (donut chart)
- Total shows by release year (trend over time)

## 🔍 Key Insights
- Netflix's content library spans nearly 100 years (1925–2021), with a total of 8,803 titles.
- "Dramas, International Movies" is the most popular genre combination, followed by Documentaries and Stand-Up Comedy specials.
- TV-MA is the most common content rating, indicating the library skews toward mature audiences.
- Movies significantly outnumber TV Shows in Netflix's catalog.
- Content additions grew exponentially between 2015–2020, peaking around 2018–2019, reflecting Netflix's aggressive content expansion during the streaming wars.
- The catalog features high content diversity, with 515 unique genres and 4,527 unique directors.

## 📁 Repository Contents
- `Netflix_Data_Cleaning_and_EDA.ipynb` – Python & SQL code for data cleaning and analysis
- `Netflix_Dashboard.pbix` – Power BI dashboard file
- `README.md` – Project documentation

## 🚀 How to Use
1. Open the `.ipynb` file in Google Colab to view the data cleaning and SQL analysis process
2. Open the `.pbix` file in Power BI Desktop to explore the interactive dashboard
