---

# Movie Recommender System

This repository contains a machine learning-based Movie Recommender System that suggests movies similar to those users have enjoyed in the past. It addresses "choice paralysis" by providing personalized movie recommendations using content-based filtering. The system analyzes movie metadata, including overviews, genres, and themes, and computes similarities between movies to offer recommendations.

## Features
- **Content-Based Filtering**: Recommends movies based on the metadata (e.g., overview, genre) of user-specified movies.
- **TF-IDF & Cosine Similarity**: Utilizes TF-IDF for vectorization and cosine similarity for ranking movie similarities.
- **API Integration**: Fetches and displays movie posters using The Movie Database (TMDB) API to enhance the user experience.

## Technologies
- **Python**: Core programming language.
- **Libraries**: 
  - `pandas` & `numpy` for data handling.
  - `scikit-learn` for TF-IDF vectorization and similarity computation.
  - `requests` for API calls to TMDB.
- **API**: The Movie Database (TMDB) API to fetch movie posters.

## How It Works
1. User inputs a movie title.
2. System retrieves relevant metadata and computes content similarity using TF-IDF and cosine similarity.
3. Outputs a list of top 10 recommended movies with their posters.

## Example
For input "Iron Man 2", recommendations include:
- Krrish
- Ant-Man
- Iron Man 3
- The Truman Show, and more.

---

