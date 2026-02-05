# 🎵 Spotify-Style Music Recommender System

This project builds a Spotify-style music recommendation system using song-level audio features, similarity-based learning, exploratory data analysis, and neural embeddings.

## 🔍 Overview
- Dataset: Spotify Audio Features (April 2019)
- Methods:
  - K-Nearest Neighbors (KNN) for similarity-based recommendations
  - Feature normalization and Euclidean distance metrics
  - Mood classification using valence and energy
  - Neural network autoencoder for song embeddings
- Tools: Python, pandas, scikit-learn, seaborn, TensorFlow/Keras

## 📂 Repository Structure

## 📊 Key Visualizations

### Feature Distributions
![Feature Distributions](figures/feature_distributions.png)

### Feature Correlations
![Correlation Heatmap](figures/correlation_heatmap.png)

### Mood Classification
![Mood Scatter](figures/mood_scatter.png)

### Genre Distribution
![Genre Distribution](figures/genre_distribution.png)

### Model Training Loss
![Training Loss](figures/training_loss.png)

## 🎧 Recommendation Example
```python
recommend_songs("Shape of You", mood="Happy")
