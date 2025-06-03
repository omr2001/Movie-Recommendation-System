# 🎬 Movie Recommendation System using Weighted Average

A content-based Movie Recommendation System that ranks and recommends movies using the **Weighted Average Formula**, inspired by IMDb's ranking system.

---

## 📘 Project Overview

With thousands of movies released every year, users often struggle to find quality content. This project uses a **Weighted Average Rating** to recommend movies based on a balance of popularity and quality, ensuring both fairness and relevance.

**Formula Used**:

WR = (v / (v + m)) * R + (m / (v + m)) * C

Where:  
- `R` = average rating of the movie  
- `v` = number of votes for the movie  
- `m` = minimum votes required to be listed  
- `C` = mean vote across the dataset  

---

## 🚀 Features

- Ranks movies using IMDb-style weighted average
- Filters out low-vote movies for better quality control
- Displays top-rated movies based on popularity and quality
- Easy to integrate into a larger recommendation pipeline

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`  
- **Dataset**: TMDB 5000 Movies Dataset (or similar)

---

## 📂 Dataset

- `movies_metadata.csv`: Includes fields like `title`, `vote_average`, `vote_count`, `genres`
- Optional: `credits.csv` and `keywords.csv` for advanced filtering
