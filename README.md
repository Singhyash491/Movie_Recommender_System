# 🎬 Content-Based Movie Recommender System

## 📖 Overview
This project is a **content-based movie recommender system** designed to suggest movies based on a user-selected favorite. The system is trained on a dataset of 5,000 movies and utilizes **cosine similarity** to compute recommendations. It includes an **end-to-end machine learning pipeline** and is deployed as a **GUI web application** using Streamlit.

---

## 🛠️ Problem Statement
Movie recommendation is a key feature for many entertainment platforms, enabling users to discover content they are likely to enjoy. The challenge is to build a system that:
- Suggests movies similar to a user's favorite selection.
- Provides an intuitive and interactive web-based interface.

---

## ✨ Solution
1. **Content-Based Filtering**:
   - Analyzes movie metadata (such as genres, keywords, cast, and crew) to find similar movies.
   - Computes similarity using **cosine similarity** on a vectorized representation of movie features.

2. **Web Application**:
   - Built using **Streamlit**, allowing users to:
     - Select a movie from a dropdown.
     - Receive a list of 5 recommended movies along with their posters.

---

## 📝 Features
- **Movie Metadata Analysis**:
  - Processes textual metadata from the dataset (e.g., genres, cast, keywords).
- **Interactive GUI**:
  - Streamlit-powered interface for selecting movies and viewing recommendations.
- **Poster Retrieval**:
  - Fetches movie posters using **The Movie Database (TMDb) API**.

---

## 📊 Libraries and Tools Used
- **Data Processing**:
  - `numpy`, `pandas`
- **Machine Learning**:
  - `scikit-learn` for vectorization and similarity computation
  - `nltk` for text preprocessing
- **Web Development**:
  - `streamlit` for GUI
  - `requests` for API integration

---

## 🚀 How It Works
1. **Input**: 
   - The user selects a movie from a dropdown list.
2. **Processing**:
   - The system calculates cosine similarity between the selected movie and all other movies in the dataset.
3. **Output**:
   - The top 5 most similar movies are displayed along with their posters.
