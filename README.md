
# Spotify Streaming Data Analysis 2023

This project analyzes the most streamed Spotify songs of 2023 to understand trends in streaming, artist popularity, and song characteristics across platforms like Spotify, Apple Music, Deezer, and Shazam.

**[Data](#data)** | **[Pre-Processing](#pre-processing)** | **[Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)** | **[Modeling](#modeling)** | **[Technologies and Tools](#technologies-and-tools)**

---

## Abstract

This project focuses on analyzing the top-streamed songs on Spotify in 2023. The analysis includes exploring data patterns and visualizing trends such as streams, artist presence in playlists, and chart rankings.

---

## Data

#### Sourcing

* This dataset contains a comprehensive list of the most popular songs of 2023 as listed on Spotify. The dataset offers song attributes, popularity, and presence on various music platforms, including **track name, artist(s) name, release date, Spotify playlists and charts, streaming statistics, Apple Music presence, Deezer presence, Shazam charts, and audio attributes.**
* Sourced from Kaggle and contains information about the most streamed Spotify songs in 2023:  [https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023]()

#### Pre-Processing

* Imported CSV file as ISO-8859 to prevent formatting issues; converted multiple date columns into single DateTime object.
* Some some heterogeneous data existing within some of the columns and were imported as objects, requiring converstion:  streams, in_deezer_playlists, in_shazam_charts (to numeric); track_name, artist(s)_name, mode (to string))

#### Feature Transformation

* Nothing found for data scaling or encoding.

---

## Exploratory Data Analysis (EDA)

* Visualized the top 50 most streamed tracks and artists, using bar plots to represent their presence in Spotify playlists and charts.
* Nothing found for correlation analysis.
* Nothing found for descriptive statistics.

---

## Modeling

#### Model Selection and Training

* No modeling was applied in this project, as it focused on descriptive analysis and visualization.

#### Evaluation and Scoring

* Nothing found for evaluation metrics or cross-validation.

#### Interpretation and Insights

* Created bar plots showing the most popular tracks by Spotify streams and playlist inclusion, highlighting key insights into artist and track performance.

---

## Technologies and Tools

* **Data Scaling** : Nothing found.
* **Visualizations** : Generated bar plots using **matplotlib** and **seaborn** to explore data distribution and relationships.
* **Tools and Libraries** : Python, pandas, and Jupyter Notebook were used for data cleaning, analysis, and visualization.

---

## Follow-On Studies

* Apply machine learning models to predict song popularity based on features like tempo, valence, and danceability.
* Explore other platforms like YouTube or Tidal to understand cross-platform trends.

---

Let m
