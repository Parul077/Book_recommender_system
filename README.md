# 📚 Book Recommender System

A Book Recommender System built using Flask, Python, and Machine Learning techniques.
This system recommends books to users based on popularity and similarity scores.

## 🚀 Features

🔥 Top 50 Books – Displays the most popular 50 books with votes and ratings.

🔍 Personalized Recommendation – Enter a book name and get similar recommendations.

🎨 Modern UI – Clean, responsive interface built with Bootstrap.

⚡ Fast & Lightweight – Powered by Flask and precomputed similarity scores.

## 🛠️ Tech Stack

Backend: Flask (Python)

Frontend: HTML, CSS, Bootstrap

Data Handling: Pandas, NumPy, Pickle

ML Logic: Cosine Similarity on Book Vectors

## 📂 Project Structure
├── app.py                # Flask backend
├── templates/
│   ├── index.html        # Home page (Top 50 books)
│   ├── recommend.html    # Recommendation page
├── static/               # (Optional) CSS/JS if needed
├── popular.pkl           # Pickled DataFrame of top books
├── pt.pkl                # Pivot table for recommendations
├── books.pkl             # Books dataset
├── similarity_scores.pkl # Precomputed similarity matrix
└── README.md             # Project documentation

## ⚙️ Installation & Setup

Clone this repository

git clone https://github.com/Parul077/Book_recommender_system.git
cd book-recommender


## 📸 Screenshots
🔹Home Page (Top 50 Books)
<img width="1877" height="832" alt="Screenshot 2025-09-08 134658" src="https://github.com/user-attachments/assets/f768b030-3f9f-4d32-9d40-9132243a1435" />

Displays the most popular books with votes and ratings.

<img width="1892" height="836" alt="Screenshot 2025-09-08 134714" src="https://github.com/user-attachments/assets/581ce792-efab-41be-9595-6c7b9569bf33" />

🔹 Recommendation Page
<img width="1919" height="822" alt="Screenshot 2025-09-08 134728" src="https://github.com/user-attachments/assets/6b9d21e2-29af-4fc5-8d5c-c4264cc91c66" />

Enter a book name and get similar book recommendations.

<img width="1880" height="821" alt="Screenshot 2025-09-08 134753" src="https://github.com/user-attachments/assets/d5ed612f-4541-4ee1-a453-a121e77365cf" />

## 📊 How It Works

The system uses popularity-based filtering to display the top 50 books.

For recommendations, it uses a cosine similarity matrix computed from a pivot table (pt.pkl).

When a user enters a book name, the system finds similar items and displays them with book cover, author, and title.

## 🤝 Contribution

Contributions are welcome! If you’d like to improve the UI/UX, add new features, or optimize the ML logic:

Fork this repo

Create a new branch (feature/new-feature)

Commit your changes

Push and create a Pull Request

## 👨‍💻 Author

Developed by Parul Singh ✨
