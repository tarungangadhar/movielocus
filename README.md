# 🎬 Movie Recommendation System

An interactive movie recommendation system built with **Streamlit**.  
It suggests similar movies based on content features using a **cosine similarity approach** on preprocessed movie embeddings.

---

##  Features
- Search any movie title and get top-N similar recommendations.
- Simple **Streamlit web app** interface.
- Deployed via **Heroku/Streamlit Cloud**.
- Uses **pre-computed embeddings** stored in `movie_list.pkl`.

---

##  Tech Stack
- **Python 3.9+**
- **Streamlit** (UI framework)
- **Scikit-learn** (vectorization, similarity computation)
- **Pandas / Numpy**
- **Pickle** (for preprocessed movie list)


---

##  Usage
### 1. Clone the repo
bash-
git clone https://github.com/vtarungangadhar/movielocus.git
cd movie-recommender

2. Install dependencies
pip install -r requirements.txt

3. Run Locally
streamlit run app.py

## Deployment
This project includes a Procfile and setup.sh for easy deployment to Heroku or Streamlit Cloud.

# Example
https://github.com/tarungangadhar/movielocus/blob/main/Example.png
