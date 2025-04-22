# 📚 Book Recommender System

A simple web app built with Flask that recommends top books based on popularity and similarity. Includes book cover, author, votes, and ratings.

---

## 🚀 Live Demo

https://my-book-recommendation.onrender.com/
---

## 🛠️ Tech Stack

- Python
- Flask
- HTML / Bootstrap 5
- Pandas
- Scikit-learn (for cosine similarity)
- Gunicorn (for production)

---

## 📦 Features

- Displays **Top 50 Popular Books** with:
  - Cover image
  - Author
  - Number of Votes
  - Average Rating

- **Book Recommender Section**:
  - Recommends **7 similar books** based on cosine similarity of book features
  - Input any book title to get smart recommendations

- Fully responsive and clean UI
- Deployed on **Render (Free Tier)**

---

## 🧰 Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/Abhaybs/my-book-recommendation.git
cd my-book-recommendation
