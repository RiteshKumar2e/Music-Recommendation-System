# Music Recommendation System

## Overview

This project implements a **Music Recommendation System** combining **Content-Based Filtering**, **Collaborative Filtering**, and **KNN-Based Recommendations**. It leverages machine learning techniques to recommend songs based on lyrics, user preferences, and user-item interactions.

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
