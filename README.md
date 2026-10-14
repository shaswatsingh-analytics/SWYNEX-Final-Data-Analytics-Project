# Netflix Data Analytics Case Study | SWYNEX Task 4

A Python-based data analytics project focused on Netflix movies and TV shows, including data preparation, exploratory data analysis (EDA), visualizations, an interactive dashboard, and business insights.

## 🔗 Project Links

- **[📊 Open Interactive Netflix Dashboard](https://shaswatsingh-analytics.github.io/SWYNEX-Interactive-Dashboard/Netflix_Content_Intelligence_Dashboard.html)**
- **[📓 View Python Analysis Notebook](https://github.com/shaswatsingh-analytics/SWYNEX-Final-Data-Analytics/blob/main/Netflix_Final_Data_Analytics_Project.ipynb)**
- **[📁 View Cleaned Dataset](https://github.com/shaswatsingh-analytics/SWYNEX-Final-Data-Analytics/blob/main/netflix_titles_cleaned.csv)**
- **[💻 View GitHub Repository](https://github.com/shaswatsingh-analytics/SWYNEX-Final-Data-Analytics)**
- **[👤 Visit My GitHub Profile](https://github.com/shaswatsingh-analytics)**
- **LinkedIn Project Post:** Add your published LinkedIn post URL here.

> Note: The notebook and dataset links assume the files are uploaded to the repository using the filenames shown above.

## 📌 Project Overview

This project was completed as part of **Task 4 of my Data Analyst Internship at SWYNEX Technologies**.

The objective is to explore the Netflix Movies and TV Shows dataset, identify patterns in catalogue composition, and communicate the findings through Python analysis, visualizations, and an interactive dashboard.

## 🎯 Problem Statement

How can catalogue data be analyzed to understand the distribution of movies and TV shows, content ratings, genres, country representation, movie durations, and content addition trends?

This project uses exploratory data analysis to investigate these questions and present useful descriptive insights.

## 📂 Dataset Information

- **Dataset:** Netflix Movies and TV Shows
- **Total records:** 8,807
- **Original columns:** 12
- **Format:** CSV
- **Source file:** `netflix_titles_cleaned.csv`

Key columns include `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, and `description`.

The dataset represents historical catalogue information, with content addition dates extending through 2021. It should not be treated as a live snapshot of Netflix's current catalogue.

## 🛠️ Tools and Technologies

- Python
- Pandas
- Matplotlib and Seaborn, where used
- Jupyter Notebook
- HTML, CSS and JavaScript
- GitHub and GitHub Pages

## 🧹 Data Cleaning and Preparation

The data preparation workflow included:

- Checking missing values
- Checking duplicate records and IDs
- Trimming extra whitespace
- Converting `date_added` to a date format
- Preparing data for analysis and visualization
- Preserving genuine missing values where appropriate

## 📊 Exploratory Data Analysis

The project explores six main areas:

1. **Content Type Analysis:** Movies versus TV shows.
2. **Content Ratings:** Distribution of content ratings.
3. **Genre Analysis:** Most frequently listed categories.
4. **Country Analysis:** Countries represented in the catalogue.
5. **Movie Duration:** Average, median, and longest movie duration.
6. **Year-wise Additions:** Trends in the years titles were added.

## 💡 Key Findings

- The dataset contains **8,807 titles**.
- Movies account for **6,131 titles (approximately 69.6%)**.
- TV shows account for **2,676 titles (approximately 30.4%)**.
- International Movies, Dramas, and Comedies are among the most frequently listed categories.
- The United States, India, and the United Kingdom feature prominently in the country analysis.
- The average movie duration is approximately **99.56 minutes**, with a median of **98 minutes**.
- **2019** was the peak year for content additions in the analyzed dataset.

*Country and genre counts may include the same title in multiple categories because some records contain multiple countries or genres.*

## 📈 Interactive Dashboard

**[Launch the Netflix Content Intelligence Dashboard](https://shaswatsingh-analytics.github.io/SWYNEX-Interactive-Dashboard/Netflix_Content_Intelligence_Dashboard.html)**

The dashboard presents selected findings through visualizations and interactive filters, providing a convenient way to explore the dataset.

## 🧠 Business Insights and Recommendations

- Review the balance between movies and TV shows when evaluating catalogue composition.
- Explore genre distribution to understand which categories are widely represented.
- Analyze country representation to identify areas for further content research.
- Compare content addition trends across years while considering the historical coverage of the dataset.
- Combine catalogue analysis with viewing, engagement, and revenue data in future projects to support stronger business decisions.

These recommendations are based on
