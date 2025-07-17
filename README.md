
````markdown
# 🎬 Movie Recommender System

A simple content-based recommender system using the TMDB 5000 dataset. It suggests similar movies based on genres, overview, cast, crew, and keywords.

## 📦 Dataset
- Source: [Kaggle](https://www.kaggle.com/datasets/sumitverma19/dataset)
- Files used:
  - `tmdb_5000_movies.csv`
  - `tmdb_5000_credits.csv`

## 🔍 How It Works
- Combines key movie features into a `tags` column
- Transforms text using CountVectorizer
- Computes similarity using cosine distance
- Returns top 5 similar movies

## 📌 Tech Stack

* Python, pandas, scikit-learn
* Jupyter Notebook

## 🚀 To Run

```bash
git clone https://github.com/Sumit191105/Movie-Recommender-System.git
cd Movie-Recommender-System
jupyter notebook
```

Made with 💻 by [Sumit Verma](https://github.com/Sumit191105)
