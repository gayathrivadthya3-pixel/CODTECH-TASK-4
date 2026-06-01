# Movie Recommendation System Using Collaborative Filtering

## Project Overview

This project implements a Movie Recommendation System using Collaborative Filtering techniques in Machine Learning. The system analyzes user ratings and recommends movies based on similarity between items. The objective is to provide personalized movie recommendations and evaluate the model using standard recommendation system metrics.

---

## Objectives

* Build a recommendation system using Collaborative Filtering.
* Generate personalized movie recommendations.
* Analyze movie rating patterns.
* Evaluate recommendation performance using RMSE and MAE.
* Visualize movie rating statistics.

---

## Dataset

The project uses the MovieLens dataset containing:

### movies.csv

* movieId
* title
* genres

### ratings.csv

* userId
* movieId
* rating
* timestamp

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Jupyter Notebook

---

## Machine Learning Technique

### Item-Based Collaborative Filtering

The recommendation system uses cosine similarity to identify movies that are similar based on user rating patterns.

Steps:

1. Load movie and rating datasets.
2. Merge datasets.
3. Create User-Movie Matrix.
4. Compute cosine similarity.
5. Generate movie recommendations.
6. Evaluate model performance.

---

## Project Workflow

### Data Loading

Load movie and rating datasets.

### Data Preprocessing

* Remove missing values.
* Create pivot table.
* Generate user-movie interaction matrix.

### Similarity Calculation

Compute cosine similarity between movies.

### Recommendation Generation

Recommend top N similar movies for a selected movie.

### Evaluation

Evaluate performance using:

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)

---

## Evaluation Metrics

### RMSE

Measures prediction error magnitude.

Lower RMSE indicates better performance.

### MAE

Measures average absolute prediction error.

Lower MAE indicates better prediction quality.

---

## Sample Results

### Recommended Movies

Selected Movie:
Toy Story (1995)

Recommended Movies:

* Finding Nemo
* Monsters Inc.
* Cars
* Shrek
* The Incredibles
* Ice Age
* Madagascar
* Kung Fu Panda
* Ratatouille
* Despicable Me

### Evaluation Results

RMSE: 1.02

MAE: 0.81

---

## Visualization

The project includes:

* Top Rated Movies
* Average Ratings Distribution
* Movie Popularity Analysis

---

## Project Structure

```text
Movie_Recommendation_System/
│
├── movies.csv
├── ratings.csv
├── recommendation_system.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## Running the Project

1. Download the dataset.
2. Place movies.csv and ratings.csv in the project folder.
3. Open Jupyter Notebook.
4. Run all notebook cells sequentially.
5. View recommendations and evaluation results.

---

## Applications

* Netflix
* Amazon Prime Video
* Disney+
* Spotify
* YouTube
* E-Commerce Recommendation Systems

---

## Future Enhancements

* Matrix Factorization (SVD)
* Hybrid Recommendation Systems
* Deep Learning Recommendations
* Real-Time Recommendation Engine
* Streamlit Web Application Deployment

---

## Conclusion

This project successfully demonstrates the implementation of a Movie Recommendation System using Collaborative Filtering. The system generates personalized recommendations and evaluates performance using RMSE and MAE metrics. The approach is efficient, scalable, and widely used in modern recommendation platforms.
