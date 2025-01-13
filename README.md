# Music Recommendation System

## Overview

This project implements a **Music Recommendation System** combining **Content-Based Filtering**, **Collaborative Filtering**, and **KNN-Based Recommendations**. It leverages machine learning techniques to recommend songs based on lyrics, user preferences, and user-item interactions.



## Project Description

The Music Recommendation System leverages a combination of advanced machine learning techniques to provide users with personalized song recommendations. This system integrates Content-Based Filtering, Collaborative Filtering, and KNN-Based Recommendations, offering a holistic approach to suggesting songs based on song attributes, user interactions, and similarity to other users.
The project uses lyrics-based content filtering and user interaction data to deliver customized recommendations, ensuring that the system adapts to both individual preferences and popular trends.

## Features

### Content-Based Recommender
- Recommends songs similar to a given song based on lyrics.
- Utilizes **TF-IDF vectorization** and **cosine similarity** for comparison.

### Collaborative Filtering Recommender
- Recommends songs based on user listening patterns.
- Uses the **SVD algorithm** from the **Surprise** library.

### KNN-Based Recommender
- Recommends songs by finding similar users using **k-nearest neighbors**.
- Creates a **user-item interaction matrix**.

### Visualization Functions
- Plots **pie charts**, **bar charts**, **histograms**, and **heatmaps** to analyze song popularity and user interactions.

## Datasets

The system uses two datasets:

1. **Content-Based Dataset**:  
   - `songdata.csv`: Contains song lyrics, titles, and artist information.
   
2. **Collaborative Filtering Dataset**:  
   - `Bollywood-Songs-Dataset(2017-23).csv`: Contains synthetic user interactions, song IDs, and listen counts.
# Prerequisites
The system requires the following Python libraries:

# Installing Python 3.x (Recommended version: 3.7 or higher)

### pandas - Data manipulation and analysis
### numpy - Numerical computations
### matplotlib - Plotting and visualization
### seaborn - Statistical data visualization
### scikit-learn - Machine learning algorithms
### scipy - Scientific computing
### surprise - A library for building and analyzing recommender systems
# Install the required libraries
```bash 
pip install numpy 
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install scipy 
pip install surprise
