<h1> Spotify Project </h1>

The goal of this topic is to exploit data extracted from the Spotify streaming platform. The available data comes from Kaggle, and you can directly download it via the following links:


[artists](https://www.kaggle.com/datasets/rolanddutauziet/dataset-projet-spotify?select=artists.csv)
- The artists.csv file contains information about the artists.

| Variable Label | Definition |
|----------------|------------|
| id             | Artist ID  |
| followers      | Number of artist's followers |
| genres         | Genres associated with the artist |
| name           | Name of the artist |
| popularity     | Popularity of the artist (between 0 and 100) |


[top200global](https://www.kaggle.com/datasets/rolanddutauziet/dataset-projet-spotify?select=spotify_top200_global.csv)
- The spotify_top200_global.csv file contains the titles that are part of the global top 200 of the year 2020.

| Variable Label | Definition |
|----------------|------------|
| Artist         | Name of the artist |
| Country        | Country (here it will be global as the file is on the global ranking) |
| Date           | Date |
| Rank           | Rank in the classification |
| Streams        | Number of streams |
| Title          | Name of the song |


[tracks](https://www.kaggle.com/datasets/rolanddutauziet/dataset-projet-spotify?select=tracks.csv)
- The `tracks.csv` file contains information about songs on Spotify (songs dating from 1921 to 2020):

| Variable Label    | Definition |
|-------------------|------------|
| id                | Song ID |
| name              | Name of the song |
| popularity        | Popularity of the song (between 0 and 100) |
| duration_ms       | Duration of the song in milliseconds |
| explicit          | Whether the song contains explicit content (1 for yes, 0 for no) |
| artists           | Artists featured on the song |
| id_artists        | IDs of the artists featured on the song |
| release_date      | Release date of the song |
| danceability      | A measure that describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity (between 0 and 100) |
| energy            | A measure that represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy (between 0 and 100) |
| key               | The estimated overall key of the track |
| loudness          | The overall loudness of a track in decibels (dB) |
| mode              | Modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0 |
| speechiness       | Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g., talk show, audio book, poetry), the higher the attribute value |
| instrumentalness  | Predicts whether a track contains no vocals. “Ooh” and “aah” sounds are treated as instrumental in this context |
| liveness          | Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live |
| valence           | A measure describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g., happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g., sad, depressed, angry) |
| tempo             | The overall estimated tempo of a track in beats per minute (BPM) |
| time_signature    | An estimated overall time signature of a track. This denotes the number of beats in each bar of the song |
