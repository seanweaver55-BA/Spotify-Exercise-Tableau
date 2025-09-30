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

<img src="IMAGE-LINK" alt="Music Genre Analysis Dashboard" width="800"/>

---

## Insights Highlighted
- A calculated “Mood Group” field (combining energy, danceability, and valence) identifies genres such as Reggaeton, Reggae, and Ska as having the highest mood scores, while Soundtrack, Opera, and Classical rank lowest.  
- Liveness and loudness show limited correlation, with most tracks clustering between –12 dB and –6 dB loudness.  
- Valence analysis reveals clear differences in emotional tone across genres, with Reggae and Ska scoring highest and Classical and Opera lowest.  
- Track duration converted into minutes shows that genre identity drives popularity more than track length, with Pop and Dance consistently outperforming other categories.  

---

## Tools and Skills Demonstrated
- Tableau Public: Dashboard design and interactivity  
- Data Preparation: Calculated fields for mood grouping and duration standardisation  
- Comparative Analysis: Multi-dimensional genre-based comparisons  
- Feature Interpretation: Understanding Spotify’s audio metrics and applying them to genre-level insights  

---

## Explore the Dashboard
- [View on Tableau Public](#)  
- [Download Workbook](#)  

---

## Feedback
Feedback and suggestions are welcome — feel free to reach out or comment directly on the Tableau Public page.
