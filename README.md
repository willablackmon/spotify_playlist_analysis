# Spotify 2023

# Project Description:

# Questions to Investigate:

Rough list of questions that the data might answer. Make sure the questions pertain to specific columns in the dataData Source.

```
'release_date', 'track_name', 'artist(s)name', 'artist_count',
       'in_spotify_playlists', 'in_spotify_charts', 'streams',
       'in_apple_playlists', 'in_apple_charts', 'in_deezer_playlists',
       'in_deezer_charts', 'in_shazam_charts', 'bpm', 'key', 'mode',
       'danceability%', 'valence_%', 'energy_%', 'acousticness_%',
       'instrumentalness_%', 'liveness_%', 'speechiness_%']
```

This information is useful for analyzing trends in music popularity, genre characteristics, and streaming performance across different platforms.
This dataset offers a variety of insights into modern music trends, streaming performance, and musical characteristics. Here are some interesting facts that can be derived from this dataset:

**1. Popularity Trends:**
Identify which artists and tracks are most popular by looking at the number of streams and their presence in playlists and charts.
The dataset allows tracking the rise of certain tracks over time by comparing their streams, playlist inclusions, and chart positions.

```
'artist(s)name' 
	'in_spotify_playlists', 'in_spotify_charts', 'streams',
	'in_apple_playlists', 	'in_apple_charts', 
	'in_deezer_playlists',	'in_deezer_charts', 
	'in_shazam_charts
```


**2.  Collaboration and Artist Influence:**
The artist count column highlights tracks with multiple artists, which could indicate collaborations that boost a song's popularity.
Comparing single-artist tracks with collaborations can reveal if collaborations tend to be more successful.

```
'artist_count'
	'in_spotify_playlists', 'in_spotify_charts', 'streams',
	'in_apple_playlists', 	'in_apple_charts',
	'in_deezer_playlists',	'in_deezer_charts',
	'in_shazam_charts
```


**3.  Seasonal Releases:**
By analyzing the released month and release day columns, we can see if there are any trends in the release dates, such as more releases during summer or holiday seasons.

```
['release_date'].month, ['release_date'].day
```

Possible months/days to investigate:  Spring Break (mid-March), Summer (June-August), Holiday Season (Nov-Dec)

**4.  Musical Features:**
The dataset includes audio features like `danceability_%, valence_%, energy_%, acousticness_%, instrumentalness_%, liveness_%, and speechiness_%.` 

These features can be analyzed to understand the characteristics of popular songs. 

For instance, you can find out if high-energy songs or more acoustic tracks are currently trending.

Investigate: Which characteristics/audio features are present in the most popular songs? 

**5.  Platform Popularity:**
The` in_spotify_playlists`, `in_spotify_charts`, and `in_apple_playlists columns` allow comparison of platform-specific popularity. 

This can show whether some tracks perform better on Spotify or Apple Music.

**6.  Release Date Insights:**
The `release_date` column provides exact dates, which can be used to study the impact of release timing on a track's success.

Does there seem to be a time of year that leads to success of a track?  

**7.  Genre and Mood Analysis:**
By examining the key and `mode (Major/Minor) columns`, along with `valence_%`, you can infer the general mood of popular music?

For example, you might find that most popular songs are in a major key and have a high valence, indicating a positive mood.

**8.  Artist Dominance:**
The number of times an artist ` artist(s)name` appears in the dataset can show which artists are currently dominating the music scene. 

This can be cross-referenced with their chart and playlist presence.
By exploring these aspects, you can uncover valuable insights into what makes a song popular, how musical tastes evolve over time, and the impact of various factors on a track's success.

---

# Data:

#### Most Streamed Spotify Songs 2023

[https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023]()

#### Description:

> This dataset contains a comprehensive list of the most famous songs of 2023 as listed on Spotify. The dataset offers a wealth of features beyond what is typically available in similar datasets. It provides insights into each song's attributes, popularity, and presence on various music platforms. The dataset includes information such as  **track name, artist(s) name, release date, Spotify playlists and charts, streaming statistics, Apple Music presence, Deezer presence, Shazam charts, and various audio features** .

#### Key Features:

> * **track_name** : *Name of the song*
> * **artist(s)_name** : *Name of the artist(s) of the song*
> * **artist_count** : *Number of artists contributing to the song*
> * **released_year** : *Year when the song was released*
> * **released_month** : *Month when the song was released*
> * **released_day** : *Day of the month when the song was released*
> * **in_spotify_playlists** : *Number of Spotify playlists the song is included in*
> * **in_spotify_charts** : *Presence and rank of the song on Spotify charts*
> * **streams** : *Total number of streams on Spotify*
> * **in_apple_playlists** : *Number of Apple Music playlists the song is included in*
> * **in_apple_charts** : *Presence and rank of the song on Apple Music charts*
> * **in_deezer_playlists** : *Number of Deezer playlists the song is included in*
> * **in_deezer_charts** : *Presence and rank of the song on Deezer charts*
> * **in_shazam_charts** : *Presence and rank of the song on Shazam charts*
> * **bpm** : *Beats per minute, a measure of song tempo*
> * **key** : *Key of the song*
> * **mode** : *Mode of the song (major or minor)*
> * **danceability_%** : *Percentage indicating how suitable the song is for dancing*
> * **valence_%** : *Positivity of the song's musical content*
> * **energy_%** : *Perceived energy level of the song*
> * **acousticness_%** : *Amount of acoustic sound in the song*
> * **instrumentalness_%** : *Amount of instrumental content in the song*
> * **liveness_%** : *Presence of live performance elements*
> * **speechiness_%** : *Amount of spoken words in the song*

---

# Schedule:

* **Day 1 (Tue 6/25):**
  * Dataset selected
  * Data imported and generally discussed.
  * A rough list of questions that the data might answer.
  * Make sure the questions pertain to specific columns in the data!
  * If time allows, start assigning questions to specific people.
* **Day 2 (Thursday 6/27):**
  * All team members have data imported.
  * Data is cleaned.
  * Share code for this with teammates. Its often better if everyone uses the same cleaned data!
  * Consider creating and sharing a `cleaned_data.csv` that can be imported in a fresh `ipynb` file to start analysis.
  * Each team member has at least one visualization created.
* **Day 3 (Monday 7/1 ):**
  * All team members have at least 3 visualizations made.
  * Team discusses all visualizations for value and interesting findings.
  * Visuals for presentation are selected (1 to 2 per individual).
  * Any modifications needed for visuals are documented.
  * e.g. change the color, make it easier to read, make it bigger, change x ticks, etc.
* **Day 4 (Next Tuesday 7/2):**
  * Draft a full presentation
  * Polish visuals if needed
  * Polish presentation
* **Day 5 (Monday 7/8):**
  * Extra time. Save in case of emergency.
* **Day 6 (Tuesday 7/9):**
  * Give presentation
