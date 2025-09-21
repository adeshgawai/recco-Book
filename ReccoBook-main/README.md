# ReccoBook

📚 Book Recommendation System

A Flask-based Book Recommendation Web Application that suggests similar books to users based on their input. It uses pre-computed similarity scores, collaborative filtering matrices, and a curated dataset of books with ratings.

The app also provides a simple and clean web interface with multiple pages (Home, Recommendations, Team, Contact, etc.).

✨ Features

🔍 Search and Recommend: Enter a book title to get recommendations of similar books.

⭐ Popular Books Section: Displays popular books with ratings and votes.

👥 Team, Contact, Success/Failure pages: Pre-built UI pages included.

⚡ Flask Backend: Handles requests and serves recommendations.

📦 Pickle Models: Uses pre-saved .pkl files for fast loading of recommendation data.

📂 Project Structure
```
bash
book_recommender/
│
├── app.py                     # Main Flask application
├── books_dict.pkl             # Serialized dataset of books
├── popular.pkl                # Precomputed popular books
├── pt.pkl                     # Pivot table (user-book matrix)
├── similarity_scores.pkl      # Precomputed similarity scores
│
├── templates/                 # HTML templates
│   ├── index.html             # Homepage
│   ├── recommend.html         # Recommendation page
│   ├── team.html              # Team page
│   ├── contact.html           # Contact page
│   ├── success.html           # Success page
│   └── failure.html           # Failure page
│
├── static/                    # CSS/JS/images
│   └── style.css
│
├── requirements.txt           # Dependencies
└── README.md                  # Project documentation
```

![Picture1](https://github.com/codingking123/ReccoBook/assets/75785111/3c8b574f-4541-47f5-bc9d-a457caf6f789)

![Picture2](https://github.com/codingking123/ReccoBook/assets/75785111/d43c0b13-a6cd-4f2e-ba18-d7e27f59bdd4)
