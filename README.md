# 🎬 Movie Recommender System
A simple movie recommender system built using Python, Streamlit, and The Movie Database. This app recommends movies similar to the one selected by the user, displaying their titles and posters.


---
##  Features
- Dropdown to select or search for a movie title

- Movie recommendations based on similarity scores

- Displays movie posters using TMDb API

- Clean and interactive UI with Streamlit


---
## 📁 Files
`app.py`: Streamlit application.

`movie_list.pkl`: Pickled file containing the movie titles and metadata.

`similarity pkl.7z`: Pickled similarity matrix generated from movie features.

`MovieRecommenderSystem.ipynb`: Google colab notebook used to generate movie_list.pkl and similarity.pkl.

📥 [Download the raw Dataset](https://drive.google.com/drive/folders/16NfPpSpirBLmswcPp7Ao47KiVvgUpw9o?usp=drive_link)


---
## 🧠 How it works
**Data Cleaning & Preprocessing**
Done in MovieRecommenderSystem.ipynb using:

- Genre, cast, crew, keywords, overview, etc.

- Combined into a single text feature

- Transformed using CountVectorizer and cosine similarity

**Recommendation Logic**
In app.py:

- Loads movie_list.pkl and similarity.pkl

- On user selection, retrieves top 5 similar movies

- Uses TMDb API to fetch posters

**User Interface**
Built with Streamlit:

- Dropdown to select movies

- Button to get recommendations

- Grid layout showing titles + posters

