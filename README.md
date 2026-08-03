# 🎬 Netflix Content Analysis

Netflix ke 8,800+ titles ke dataset ka analysis, jisme content type, country-wise
distribution, genres, ratings aur yearly growth ke trends dekhe gaye hain.

## 📊 Dataset
- **Source:** [Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) (Kaggle)
- **Rows:** 8,807 titles
- **Columns:** type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

## 🛠️ Tools Used
- Python
- Pandas (data cleaning & analysis)
- Matplotlib & Seaborn (data visualization)

## 🔍 What I Did
1. Loaded and explored the raw dataset
2. Handled missing values in `director`, `cast`, and `country` columns
3. Converted `date_added` to proper datetime format
4. Analyzed content type distribution, top countries, top genres, yearly growth, and rating distribution
5. Visualized findings using bar charts, pie charts, and line charts

## 📈 Key Insights
- **Movies vs TV Shows:** 6,129 Movies vs 2,664 TV Shows — Netflix's library skews heavily toward movies
- **Top Content-Producing Country:** United States (3,683 titles)
- **Most Popular Genre:** International Movies (2,752 titles)
- **Peak Year for Content Addition:** 2019, with 2,016 titles added

## 📷 Visualizations

### Movies vs TV Shows
![Movie vs TV Show](chart_movie_vs_tvshow.png)

### Top 10 Countries by Content
![Top Countries](chart_top_countries.png)

### Content Added Per Year
![Yearly Growth](chart_yearly_growth.png)

### Top 10 Genres
![Top Genres](chart_top_genres.png)

### Content Ratings Distribution
![Ratings](chart_ratings.png)

## 🚀 How to Run
```bash
pip install pandas matplotlib seaborn
python analysis.py
```

## ✍️ Author
Patel Mohammadsaad
