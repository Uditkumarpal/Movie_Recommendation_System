# 🎬 Movie Recommendation System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3-orange?style=for-the-badge&logo=scikit-learn)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28-red?style=for-the-badge&logo=streamlit)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green?style=for-the-badge&logo=pandas)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

**An intelligent Movie Recommendation System that suggests personalized movies using Content-Based Filtering, Collaborative Filtering, and a Hybrid approach — built entirely with Python and Machine Learning.**

[Live Demo](#) · [Report Bug](#) · [Request Feature](#)

</div>


## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)

---

## 🎯 About the Project

In today's digital era, millions of movies are available across streaming platforms making it overwhelming for users to discover content they love. This project solves that problem by building an intelligent **Movie Recommendation System** that analyzes movie features and user behavior to deliver highly personalized suggestions.

The system is built using three powerful recommendation approaches:

- **Content-Based Filtering** — Recommends movies similar to what you already like based on genre, cast, director, and plot keywords
- **Collaborative Filtering** — Recommends movies that users with similar tastes have enjoyed
- **Hybrid Model** — Combines both approaches for the most accurate and diverse recommendations

This project mirrors real-world systems used by platforms like Netflix, Amazon Prime, and Hotstar.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🎭 Content-Based | Recommends based on movie similarity (genre, cast, plot) |
| 👥 Collaborative | Recommends based on similar user preferences |
| 🔀 Hybrid Model | Combines both for best accuracy |
| 🌐 Web Application | Interactive Streamlit app with live recommendations |
| 📊 Data Analysis | Full EDA with visualizations |
| 💾 Model Persistence | Saved models using Pickle for fast loading |
| 🔍 Smart Search | Search any movie from 5,000+ database |
| ⭐ Rating Display | Shows IMDb-style ratings with recommendations |

---

## 🛠️ Tech Stack

| Library | Version | Purpose |
|---|---|---|
| **Python** | 3.9+ | Core programming language |
| **Pandas** | 2.0.0 | Data manipulation and analysis |
| **NumPy** | 1.24.0 | Numerical computations |
| **Scikit-learn** | 1.3.0 | ML algorithms and vectorization |
| **NLTK** | 3.8.1 | Natural language processing / stemming |
| **Scikit-Surprise** | 1.1.3 | Collaborative filtering (SVD) |
| **Streamlit** | 1.28.0 | Interactive web application |
| **Matplotlib** | 3.7.0 | Data visualization |
| **Seaborn** | 0.12.0 | Statistical visualizations |
| **Pickle** | Built-in | Model saving and loading |

---

---


## 📊 Dataset

### TMDB 5000 Movie Dataset
| Property | Details |
|---|---|
| **Source** | Kaggle — TMDB Movie Metadata |
| **Movies** | 5,000+ films |
| **Features** | Title, Genres, Cast, Crew, Keywords, Overview |
| **Link** | kaggle.com/datasets/tmdb/tmdb-movie-metadata |

### MovieLens Dataset
| Property | Details |
|---|---|
| **Source** | GroupLens Research |
| **Ratings** | 100,000+ user ratings |
| **Users** | 600+ unique users |
| **Movies** | 9,000+ unique movies |
| **Link** | grouplens.org/datasets/movielens |

---


### Sample Recommendations

**Input Movie:** The Dark Knight

| # | Recommended Movie | Similarity | Rating |
|---|---|---|---|
| 1 | Batman Begins | 94.2% | 7.9/10 |
| 2 | The Dark Knight Rises | 91.8% | 7.8/10 |
| 3 | Iron Man | 78.4% | 7.9/10 |
| 4 | The Avengers | 72.1% | 7.7/10 |
| 5 | Man of Steel | 69.3% | 7.0/10 |


## 🗓️ Development Timeline

| Day | Task | Status |
|---|---|---|
| Day 1 | Project setup and structure | ✅ Done |
| Day 2 | Dataset download and upload | ✅ Done |
| Day 3 | Exploratory Data Analysis | ✅ Done |
| Day 4 | Data preprocessing pipeline | ✅ Done |
| Day 5 | Content-based model | ✅ Done |
| Day 6 | Model testing and validation | ✅ Done |
| Day 7 | Collaborative filtering | ✅ Done |
| Day 8 | Hybrid model | ✅ Done |
| Day 9 | Streamlit web application | ✅ Done |
| Day 10 | Deployment and documentation | ✅ Done |

---

## 🔮 Future Improvements

- [ ] Add movie poster fetching using TMDB API
- [ ] Implement Neural Collaborative Filtering (Deep Learning)
- [ ] Add user login and personalized history
- [ ] Include Bollywood movie dataset
- [ ] Add mood-based recommendation feature
- [ ] Mobile responsive UI


<div align="center">


*"Data is the new oil — and recommendation systems are the refinery."*

</div>
