#Using machine learning and streamlite to make a movie recommender system

This is a movie recommendation system built using machine learning techniques. The system suggests movies based on the similarity of movie tags using cosine similarity. It utilizes a CountVectorizer to transform movie tags into feature vectors and then calculates the similarity between movies.

Features
Movie Recommendations: Given a movie title, the system will recommend 5 similar movies based on the tags.
Cosine Similarity: The recommendation is powered by cosine similarity between movie vectors derived from movie tags.
CountVectorizer: Transforms movie tags into numerical features for the model.

Tech Stack

Python: Programming language used.
Scikit-learn: Machine learning library used for feature extraction and calculating similarity.
Pandas: For data manipulation and handling the movie dataset.
NumPy: For handling arrays and numerical operations.
Example Output
Given the movie "The Matrix", the output will display 5 similar movies based on the tags:

1. The Terminator
2. Inception
3. Interstellar
4. The Matrix Reloaded
5. Blade Runner

![Screenshot 2023-08-29 010454 (1)](https://github.com/user-attachments/assets/45de5bbd-b55e-4c46-a412-055904e45cf4)
