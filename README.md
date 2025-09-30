# Music Genre Analysis Dashboard – Tableau Project

This Tableau Public project explores patterns in musical features across genres using Spotify track data. The work highlights the ability to create insightful visualisations and perform feature-based comparisons, uncovering how mood, loudness, liveness, and duration relate to popularity across genres.

---

## Dataset Overview
The dataset contains detailed audio attributes for tracks available on Spotify, including:

| Column Name       | Description |
|-------------------|-------------|
| genre             | The genre the track belongs to |
| artist_name       | Artist(s) who performed the track |
| track_name        | Name of the track |
| popularity        | Popularity score (0–100), based on play frequency |
| duration_ms       | Track length in milliseconds |
| energy            | Intensity and activity level (0.0–1.0) |
| danceability      | Suitability for dancing (0.0–1.0) |
| valence           | Positivity or emotional tone (0.0–1.0) |
| loudness          | Overall track loudness (dB) |
| liveness          | Probability of live audience presence |
| acousticness      | Likelihood the track is acoustic |
| speechiness       | Amount of spoken content |
| tempo             | Tempo in beats per minute (BPM) |

---

## Dashboard Preview
Music Feature Insights by Genre  

---

## Insights Visualised

### 1. Mood Grouping of Genres
A calculated field combines Energy, Danceability, and Valence into a single “Mood Group” score, representing the overall levity of a track.  
- Genres such as Reggaeton, Reggae, and Ska scored the highest.  
- Soundtrack, Opera, and Classical scored lowest by a large margin.  

<img src="IMAGE-LINK-1" alt="Mood Grouping of Genres" width="800"/>

---

### 2. Liveness vs Loudness
Scatter plot comparing track Liveness and Loudness.  
- Most tracks cluster between –12 dB and –6 dB loudness, and liveness between 0.15 and 0.25.  
- Suggests loudness does not strongly correlate with liveness.  

<img src="IMAGE-LINK-2" alt="Liveness vs Loudness" width="800"/>

---

### 3. Average Valence by Genre
Comparison of valence scores across genres, highlighting emotional tone.  
- Genres like Reggae, Children’s Music, and Ska exhibit higher positivity.  
- Opera, Classical, and Soundtrack sit at the lower end of the spectrum.  

<img src="IMAGE-LINK-3" alt="Average Valence by Genre" width="800"/>

---

### 4. Track Duration vs Popularity
Duration was standardised into minutes (`duration_ms / 60`) for easier interpretation.  
- Pop and Dance genres show higher popularity regardless of track length.  
- Electronic and Jazz sustain popularity with longer average durations.  

<img src="IMAGE-LINK-4" alt="Track Duration vs Popularity" width="800"/>

---

## Tools and Skills Demonstrated
- Tableau Public: Dashboard design and interactivity  
- Dat
