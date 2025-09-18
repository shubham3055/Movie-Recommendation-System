🎬 Movie Recommendation System – Item-based Collaborative Filtering

📌 Project Overview

This project implements a Movie Recommendation System using Item-based Collaborative Filtering on the MovieLens dataset
.

The system analyzes user ratings, computes cosine similarity between movies, and generates personalized top-N movie recommendations for users.

🚀 Features

Downloads and processes the MovieLens dataset automatically.

Builds an item-user matrix from ratings.

Computes item-to-item similarity using cosine similarity.

Generates top recommended movies for a given user.

Fully implemented in Python using pandas, numpy, and scikit-learn.

🛠️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, scikit-learn, Requests

Dataset: MovieLens (ml-latest-small)

📂 Project Structure
movie-recommendation-system/
│
├── main.py              # Main script to run the recommendation system
├── requirements.txt     # Required Python libraries
├── README.md            # Project documentation
└── data/                # MovieLens dataset (downloaded automatically)

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/shubham3055/Movie-Recommendation-System.git
cd movie-recommendation-system

2️⃣ Create Virtual Environment (Optional but Recommended)
python -m venv venv


Activate it:

Windows: venv\Scripts\activate

Linux/Mac: source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Project
python main.py

📊 Example Output

When you run the project, you’ll see recommendations for User 1:

Top Recommendations for User 1:
                   title     score
     The Shawshank Redemption  15.23
                The Dark Knight 13.87
                 Pulp Fiction   12.45
                  Fight Club    12.12
                   Inception    11.95

📖 Learning Outcomes

Understanding Collaborative Filtering concepts.

Building a recommendation engine from scratch.

Using cosine similarity for measuring item similarity.

Handling real-world datasets with Pandas.

🔮 Future Improvements

Add User-based Collaborative Filtering.

Implement a Hybrid Recommendation System.

Build a simple web interface using Flask/Streamlit.

👩‍💻 Author

Developed by Shubham Jamble
