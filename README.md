# 📊 Netflix Content Analysis

This project explores and analyzes the Netflix titles dataset using Python. It provides insights into trends in content types, countries of origin, release patterns, ratings, and durations.

## 🔍 Objective
To perform exploratory data analysis (EDA) on Netflix’s library of content and uncover patterns using visualizations and data cleaning techniques.

## 📁 Dataset
- Source: [`netflix_titles.csv`](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- 8,800+ entries including movies and TV shows
- Columns: title, type, country, cast, director, rating, duration, release year, date added, etc.

## 🛠️ Tools & Libraries
- Python 3.13
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook
- Git & GitHub

## 📈 Key Insights
- **Movies dominate** Netflix’s catalog compared to TV shows.
- The **United States** contributes the highest number of titles, followed by India.
- A large share of content was **added between 2017–2021**, peaking in 2019.
- The most common **ratings** are TV-MA and TV-14.
- Many movies cluster around **90-minute durations**, a standard length for global cinema.

## 🧹 Data Cleaning Performed
- Removed null values in critical columns (`title`, `type`)
- Converted `date_added` to datetime and extracted year
- Filtered out incorrectly labeled ratings (e.g., durations like "66 min" in the `rating` column)

## 📊 Visualizations
- Count of Movies vs TV Shows
- Titles added per year
- Top 10 contributing countries
- Ratings distribution
- Common movie durations

## 📦 Repository Contents
- `netflix_analysis.ipynb` – Jupyter Notebook with full EDA workflow
- `netflix_titles.csv` – Dataset

## ✅ Status
Project completed and open for suggestions or improvements.

---

## 🌐 Author
**Daniyal Rahmoon**  
[GitHub Profile](https://github.com/DaniyalRah)

