# Spotify Data Analysis with Python

An exploratory data analysis (EDA) and visualization project built in Python to uncover patterns in Spotify song attributes, artist metrics, genre popularity, and historical music trends.

## Project Overview
This project analyzes Spotify track and artist metadata to understand how audio features—such as energy, loudness, danceability, and track duration—relate to song popularity and how listener preferences have evolved over time.

## Key Features & Analysis
- **Data Cleaning & Preprocessing:** Handled missing values, standardized release dates into a time-series index, converted track duration from milliseconds to seconds, and merged track and artist datasets.
- **Exploratory Data Analysis (EDA):** Computed descriptive statistics, identified top and least popular songs, and analyzed feature distributions.
- **Correlation & Regression Analysis:** Generated a Pearson correlation heatmap across numerical audio features and modeled the relationship between track loudness and energy.
- **Time-Series & Genre Trends:** Visualized song release volume per year, tracking the decline in modern song duration and identifying the top 5 most popular genres.
- **Interactive Visualizations:** Built interactive Plotly visualizations to filter and inspect track-level metrics dynamically.

## Tech Stack
- **Language:** Python 3.x
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Google Colab / Jupyter Notebook

## Repository Structure
