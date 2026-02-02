# 🎬 Movie Recommendation System

This project is a content-based Movie Recommendation System built using Python and Machine Learning. It recommends movies similar to a user-selected movie by analyzing textual features such as genres, keywords, cast, director, and overview. The system uses Natural Language Processing (NLP) techniques along with TF-IDF Vectorization and Cosine Similarity to compute similarity scores between movies and display the top 10 recommended movies.

The workflow includes loading and preprocessing a movie dataset, combining important features into a single text representation, converting text into numerical vectors, calculating similarity scores, sorting the results, and finally displaying recommendations while excluding the selected movie itself.

Technologies & Libraries Used: Python, Pandas, NumPy, Scikit-learn, TF-IDF Vectorizer, Cosine Similarity, NLP basics.

How to Run: Clone the repository, install required libraries (`pandas`, `numpy`, `scikit-learn`), open the `Movie-Recommendation-System.ipynb` notebook in Jupyter, run all cells, and enter a movie name when prompted.

Project Files: `Movie-Recommendation-System.ipynb`, `movie_dataset.csv`.

Output: Displays the top 10 movies most similar to the selected movie (e.g., *Avengers: End Game* → *Inception*, *28 Weeks Later*, *Timecop*, etc.).

This project helped me understand how real-world recommendation systems work, strengthen my skills in data preprocessing, similarity measures, and applying machine learning concepts to practical problems. Future improvements include adding collaborative filtering, building a web interface, and enhancing recommendation accuracy.

⭐ If you find this project useful, feel free to star the repository!
