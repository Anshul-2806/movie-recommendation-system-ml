# movie-recommendation-system-ml
Movie Recommendation System using Machine Learning, this project good for Interview. Recommendation System Similarity Logic NLP Data Processing Visualization can show all

# 🎬 Movie Recommendation System using Machine Learning

A Machine Learning based Movie Recommendation System that suggests similar movies based on movie metadata such as genres, keywords, cast, crew, and overview.

This project uses **Natural Language Processing (NLP)** techniques and **Cosine Similarity** to recommend movies.

---

# 🚀 Project Overview

The main goal of this project is to build a recommendation system that helps users discover movies similar to their interests.

The system analyzes movie information and recommends similar movies using machine learning techniques.

---

# 🧠 Machine Learning Concepts Used

- Natural Language Processing (NLP)
- CountVectorizer
- Cosine Similarity
- Recommendation System

---

# 📂 Dataset

Dataset Source:

[TMDB Movie Metadata Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

Files used:

```bash
tmdb_5000_movies.csv
tmdb_5000_credits.csv



🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-Learn
Matplotlib
Jupyter Notebook / Google Colab
⚙️ How the Project Works
Step 1: Data Collection

Movie datasets are loaded using Pandas.

Step 2: Data Preprocessing

Important columns are selected:

Genres
Keywords
Cast
Crew
Overview

Missing values are removed.

Step 3: Feature Engineering

All important text columns are combined into a single column called:

tags
Step 4: Text Vectorization

Using:

CountVectorizer

Movie text data is converted into numerical vectors.

Step 5: Similarity Calculation

Using:

Cosine Similarity

The system calculates similarity scores between movies.

Step 6: Recommendation

When a movie name is entered, the system recommends similar movies.

📊 Data Visualization

The project includes graphs such as:

✅ Top Frequent Words Graph
✅ Dataset Distribution Pie Chart

▶️ Example Output
Recommended Movies:

John Carter
Guardians of the Galaxy
Star Trek Into Darkness
Aliens
Titan A.E.
📈 Project Workflow
Dataset Collection
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Text Vectorization
        ↓
Similarity Calculation
        ↓
Movie Recommendation
