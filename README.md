🎬 Movie Recommendation System

This project is a basic **Movie Recommendation System** built using Python.  
It recommends movies based on **content similarity** using **TF-IDF Vectorization** and **Cosine Similarity**.
The system suggests the **Top 5 similar movies** based on a given movie title.

🚀 Features
- Content-based filtering system
- TF-IDF based text processing
- Cosine similarity for measuring movie similarity
- Displays Top 5 recommended movies
- Built using TMDb dataset

🧠 How It Works
1. Movie data is loaded from dataset (TMDb/IMDb)
2. Important features like overview are extracted
3. Text is converted into numerical vectors using TF-IDF
4. Cosine similarity is calculated between all movies
5. Based on similarity score, top 5 movies are recommended

 🛠️ Tech Stack
- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

 📂 Project Structure
 Movie-Recommendation-System/ │
 ├── movie_recommender.ipynb 
 ├── tmdb_5000_movies.csv 
 ├── requirements.txt 
 └── README.md
💡 Future Improvements
-Add movie posters using TMDb API
-Build web app using Flask or Streamlit
-Add search bar UI
-Deploy project online (Render / Streamlit Cloud)
👨‍💻 Author
Developed as part of the CodeAlpha Internship to demonstrate the implementation of a Content-Based Movie Recommendation System using Machine Learning techniques
