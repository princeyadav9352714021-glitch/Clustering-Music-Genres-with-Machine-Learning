# Clustering Music Genres with Machine Learning

## Project Overview

This project uses Machine Learning techniques to group songs with similar musical characteristics into clusters. Instead of predicting predefined genres, the model identifies hidden patterns within the music dataset and creates meaningful song groups based on audio features.

The project demonstrates the use of unsupervised learning, specifically K-Means Clustering, for music analysis and recommendation applications.

---

## Objectives

* Analyze music-related features from a dataset.
* Perform data preprocessing and feature scaling.
* Apply K-Means Clustering to identify similar songs.
* Evaluate cluster quality using Silhouette Score.
* Visualize clusters for better understanding.
* Save the trained model for future use.

---

## Dataset Features

The dataset contains various audio characteristics, including:

* BPM (Beats Per Minute)
* Energy
* Danceability
* Loudness (dB)
* Liveness
* Valence
* Acousticness
* Speechiness
* Duration
* Popularity

These features help describe the mood, tempo, and style of songs.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Plotly
* Scikit-learn
* Joblib

---

## Project Workflow

### 1. Data Collection

The music dataset is loaded into a Pandas DataFrame.

### 2. Data Preprocessing

* Remove unnecessary columns.
* Handle missing values if present.
* Select numerical features.
* Scale data using MinMaxScaler.

### 3. Feature Scaling

MinMaxScaler is used to normalize all features into a similar range.

### 4. Model Training

K-Means Clustering is applied to divide songs into multiple clusters.

### 5. Evaluation

Silhouette Score is calculated to measure clustering performance.

### 6. Visualization

2D and 3D visualizations help understand cluster separation and song grouping.

### 7. Model Saving

The trained K-Means model and scaler are saved using Joblib for future predictions.

---

## Machine Learning Algorithm

### K-Means Clustering

K-Means is an unsupervised learning algorithm that groups data points into K clusters based on similarity.

Advantages:

* Fast and efficient
* Easy to implement
* Works well with numerical datasets

---

## Results

The model successfully grouped songs into clusters based on their musical properties.

Potential applications include:

* Music Recommendation Systems
* Playlist Generation
* Genre Discovery
* User Preference Analysis
* Music Market Research

---

## Files in Project

* dataset.csv
* clustering_music_genres.ipynb
* kmeans_model.pkl
* scaler.pkl
* README.md
* Case_Study.docx

---

## Future Improvements

* Use PCA for dimensionality reduction.
* Experiment with DBSCAN and Hierarchical Clustering.
* Build an interactive web application using Streamlit.
* Integrate real-time music recommendation features.

---

## Conclusion

This project demonstrates how unsupervised Machine Learning can discover hidden patterns in music data. By using K-Means Clustering and feature scaling techniques, songs can be grouped into meaningful clusters that support recommendation systems and music analytics applications.
