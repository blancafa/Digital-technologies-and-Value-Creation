# 🎬 Old Movie Re-Runs Data Analysis – Curzon Cinemas

## 🧭 Business Case

As part of a strategy to differentiate from streaming services, **Curzon Cinemas** is exploring the re-release of classic movies in theaters. The goal is to create a nostalgic and immersive cinematic experience that can't be replicated at home.

> **Main Question:**  
> *Which movies should Curzon re-run to gain a competitive edge, and why?*

---

## 📊 Overview

This project explores real-world data from APIs and web scraping to identify high-potential classic movies. Data was collected from TMDB, Reddit, Letterboxd, and Rotten Tomatoes, then merged and analyzed to generate insights on popularity, engagement, and audience sentiment.

---

## 🔗 Data Sources & Collection Methods

| Source           | Method             | Key Data Collected                         |
|------------------|--------------------|---------------------------------------------|
| TMDB             | API                | Title, Release Date, Popularity, Revenue, Genres |
| Reddit           | API                | Post frequency, Comments, Relevance Score   |
| Letterboxd       | Web Scraping       | User Ratings                                |
| Rotten Tomatoes  | Web Scraping       | Audience Ratings                            |

All raw and cleaned data are consolidated into `API_Scraping_DATA.csv`.

---

## 📁 Dataset Structure (`API_Scraping_DATA.csv`)

| Column Name              | Description                                              |
|--------------------------|----------------------------------------------------------|
| Title                    | Movie name                                               |
| Release Date             | Official theatrical release                              |
| Popularity               | TMDB popularity index                                    |
| Genres                   | Associated genres                                        |
| Revenue                  | Box office earnings                                      |
| Reddit Score             | Reddit engagement score (calculated)                     |
| Reddit Comments          | Total number of Reddit comments                          |
| N Reddit Posts Week 1    | Posts in the last week                                   |
| N Reddit Posts Week2-3   | Posts during weeks 2 and 3                               |
| N Reddit Posts Week3+    | Older Reddit posts (>3 weeks)                            |
| Reddit Relevance Score   | Weight of sustained Reddit activity                      |
| Rating Letterboxd        | User rating from Letterboxd                              |
| Rating TMDB              | TMDB average rating                                      |
| Rating Rotten            | Audience rating from Rotten Tomatoes                     |

---

## 🛠 Tech Stack

- Python (Pandas, NumPy, Requests, BeautifulSoup, Selenium)
- APIs: TMDB, Reddit
- Web scraping: Letterboxd, Rotten Tomatoes
- Jupyter Notebook for analysis and visualization

---

## 🎥 Presentation

[🔗 Watch Our 10-Minute Summary Video (YouTube – Private)](https://your-video-link.com)  
_(Link stored in `video_presentation_link.txt` for reference.)_

---

## 👥 Team

- Niiara Aliieva  
- Valentina Donado  
- Blanca Farina  
- Marius Kiefer

---

## 📌 Summary

This project demonstrates how web data can inform content strategy decisions in the film exhibition industry. By analyzing popularity, sentiment, and engagement around classic films, Curzon can strategically program re-releases that resonate with modern audiences.

