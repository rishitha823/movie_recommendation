# 🎬 Movie Recommendation System (Content-Based)

This is a Content-Based Movie Recommendation System built using Python, Pandas, NumPy, and Scikit-learn.  
It recommends movies based on similarity of content such as:

- Keywords  
- Cast  
- Genres  
- Director  

The system uses CountVectorizer and Cosine Similarity to find similar movies.

---

## 🚀 Features

- Recommends movies similar to a given movie
- Uses content-based filtering
- Fast and simple implementation
- Based on real movie metadata

---

## 🧠 How It Works

1. Load movie dataset (movie_dataset.csv)
2. Combine important features:
   - keywords
   - cast
   - genres
   - director
3. Convert text to vectors using CountVectorizer
4. Compute similarity using Cosine Similarity
5. When a user enters a movie name, it:
   - Finds similar movies
   - Sorts them by similarity
   - Shows top recommendations

---

## 📁 Project Structure

movie_recommendation/
│
├── movie_recommendation_engine.py
├── movie_dataset.csv
└── README.md

---

## 🛠 Requirements

- Python 3.8+
- pandas
- numpy (<1.25 recommended)
- scikit-learn
- scipy

---

## ⚙️ Installation

1. Download or clone the project

git clone <your-github-repo-url>
cd movie_recommendation

2. (Recommended) Create virtual environment

python3 -m venv mlenv
source mlenv/bin/activate

3. Install dependencies

pip install "numpy<1.25" pandas scikit-learn scipy

---

## ▶️ How to Run

python3 movie_recommendation_engine.py

---

## ✏️ How to Change Movie Name

Open movie_recommendation_engine.py and change:

movie_user_likes = "Avatar"

To:

movie_user_likes = "Iron Man"

(Any movie that exists in the dataset)

---

## 📊 Sample Output

Top 5 similar movies to Avatar are:

Guardians of the Galaxy  
John Carter  
Aliens  
Star Wars  
Interstellar  

---

## 📚 Concepts Used

- Content-Based Filtering
- Natural Language Processing (NLP)
- Cosine Similarity
- Machine Learning Basics

---

## 🔮 Future Improvements

- Take movie name from user input
- Build GUI or Web App
- Use TF-IDF instead of CountVectorizer
- Add collaborative filtering

---

## 👩‍💻 Author

Riha  
AI / Data Science Student

---
