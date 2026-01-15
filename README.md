# 🎬 Movie Recommendation System

A web-based machine learning application that recommends movies based on content similarity. Built with Python and Streamlit.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://movie-recommendation-system-gzna3chhbuatsnyfrc6hkg.streamlit.app/)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 🔗 Live Demo
Check out the live application here:  
👉 **[Movie Recommendation System Live App](https://movie-recommendation-system-gzna3chhbuatsnyfrc6hkg.streamlit.app/)**

---

## 📝 About The Project
This project is a Content-Based Recommendation System that suggests movies similar to the movie a user likes. It analyzes movie metadata (such as genres, keywords, cast, and crew) to find similarities between films.

### Key Features
* **Interactive Web Interface:** User-friendly UI built with Streamlit.
* **Smart Recommendations:** instantly generates a list of similar movies.
* **Poster Display:** Fetches and displays movie posters for a visual experience.
* **Large Dataset:** Trained on thousands of movies using the TMDB dataset.

---

## 🛠️ Tech Stack
* **Frontend:** [Streamlit](https://streamlit.io/)
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (Cosine Similarity / CountVectorizer)

---

## 📂 Dataset & Git LFS
This project uses a large dataset (`movies_metadata.csv`).
**Note:** This repository uses **Git LFS (Large File Storage)** to track the CSV and model files.

If you clone this repository, make sure you have Git LFS installed to pull the actual data files:
```bash
git lfs install
git lfs pull
