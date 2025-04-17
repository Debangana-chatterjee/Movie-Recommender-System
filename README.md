# 🎬 Movie Recommender System
A simple movie recommender system built using Python, Streamlit, and The Movie Database. This app recommends movies similar to the one selected by the user, displaying their titles and posters.


---
## Features
- Dropdown to select or search for a movie title

- Movie recommendations based on similarity scores

- Displays movie posters using TMDb API

- Clean and interactive UI with Streamlit


---
## 📁 Files
`app.py`: Main Streamlit application.

`movie_list.pkl`: Pickled file containing the movie titles and metadata.

`similarity pkl.7z`: Pickled similarity matrix generated from movie features.

`MovieRecommenderSystem.ipynb`: Jupyter notebook used to generate movie_list.pkl and similarity.pkl.

📥 [Download the Dataset](https://drive.google.com/drive/folders/16NfPpSpirBLmswcPp7Ao47KiVvgUpw9o?usp=drive_link)


---
## 🧠 How it works
- The similarity.pkl file contains cosine similarity scores between movies.

- When a user selects a movie, the app looks up similar movies using these scores.

- The TMDb API is used to fetch posters of the recommended movies.

- The results are displayed in a row with movie titles and images.
