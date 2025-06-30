
## 🎬 Movie Recommender System

This is a web-based **Movie Recommendation System** built with **Streamlit** and powered by **The Movie Database (TMDb) API**. Simply select a movie, and the app will recommend 5 similar movies with their posters.

<br>

### 🚀 Features

* 🎞️ Content-based movie recommendations
* 🧠 Similarity matching using precomputed cosine similarity
* 🖼️ Poster images fetched in real-time using the TMDb API
* ⚡ Lightweight and fast UI with Streamlit

<br>

### 📦 Tech Stack

* **Frontend**: [Streamlit](https://streamlit.io/)
* **Backend**: Python, Pickle (for serialized models)
* **API**: [TMDb API](https://www.themoviedb.org/documentation/api)

<br>

### 📁 Project Structure

```
movie-recommender-system/
├── app.py                 # Main Streamlit app
├── movie_list.pkl         # Movie metadata (title, id, etc.)
├── similarity.pkl         # Precomputed similarity matrix
└── README.md              # Project documentation
```

<br>
---


### 🙌 Acknowledgements

* [TMDb API](https://www.themoviedb.org/documentation/api) for movie data and posters
* [Streamlit](https://streamlit.io/) for simple and elegant UI

---
