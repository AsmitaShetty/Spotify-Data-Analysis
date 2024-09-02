# Spotify Data Analysis
![Spotify_App_Logo svg](https://github.com/user-attachments/assets/07a05927-8efd-4bd9-be93-668371160338)

## About Dataset

artist: Name of the Artist.
song: Name of the Track.
duration_ms: Duration of the track in milliseconds.
explicit: The lyrics or content of a song or a music video contain one or more of the criteria which could be considered offensive or unsuitable for children.
year: Release Year of the track.
popularity: The higher the value the more popular the song is.
danceability: Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.
energy: Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity.
key: The key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.
loudness: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typically range between -60 and 0 db.
mode: Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.
speechiness: Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.
acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.
instrumentalness: Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.
liveness: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.
valence: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).
tempo: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.
genre: Genre of the track.

#Exploratory Data Analysis (EDA)

The following images represent various visualizations created during the exploratory data analysis of the Spotify dataset:

1. Distribution of Track Durations:

![image](https://github.com/user-attachments/assets/f54c656f-b977-443a-bb20-6f9e59d10c85)

2. Track Popularity Distribution:

![image](https://github.com/user-attachments/assets/7b307789-9292-4f86-87ce-39cc28707210)

3. Danceability vs. Energy:

![image](https://github.com/user-attachments/assets/db5dc402-2c25-4ab8-984c-7c46cebc4d52)

4. Track Popularity Over the Years:

![image](https://github.com/user-attachments/assets/fcd721da-282a-483d-89d2-849d51cebdaa)

5. Distribution of Explicit Content:

![image](https://github.com/user-attachments/assets/55a443d3-ce48-4d4a-8b47-4af883193dfd)

6. Popularity of Explicit vs. Non-Explicit Songs:

![image](https://github.com/user-attachments/assets/2567fb23-a263-4552-87e7-9c1aeca54dbb)

7. Top Genres by Popularity:

![image](https://github.com/user-attachments/assets/0ebf5e67-2815-44d3-be89-3b8643a7f2f5)

8. Top Artists by Number of Songs:

![image](https://github.com/user-attachments/assets/d40cc887-6b81-49f7-82ef-33c2abca6c77)

9. Top Artists by Popularity:

![image](https://github.com/user-attachments/assets/b553d247-9412-4732-9892-0b82de53e11b)

10. Distribution of Track Tempo:

![image](https://github.com/user-attachments/assets/c29898c0-cfb3-40cb-9fde-b38ecb1278a6)

11. Acousticness vs. Energy:

![image](https://github.com/user-attachments/assets/c0d51009-9dd7-4f9f-a20d-e375090798ac)

12. Valence vs. Danceability:

![image](https://github.com/user-attachments/assets/1d319cf4-a0ed-461e-9f58-97c93669a8d3)

13. Instrumentalness vs. Popularity:

![image](https://github.com/user-attachments/assets/af6e7afc-163d-47dd-83a6-76f8f4336956)

14. Loudness vs. Popularity:

![image](https://github.com/user-attachments/assets/b3f50231-c54f-4e3f-97fb-6c7833c6a270)

15. Top 10 Most Popular Songs:

![image](https://github.com/user-attachments/assets/f5011dea-66dc-4e37-896a-c908f27d51b5)

### Conclusion

From this analysis, we can draw several key insights:

Most Popular Genre: The most popular genre in the music market is pop. Pop music's inherent familiarity makes it widely appealing, allowing listeners to quickly connect with new tracks that sound familiar.

Explicit Content: Approximately 28% of the songs in the dataset contain explicit content. Songs with explicit content generally have a higher median popularity compared to non-explicit tracks.

Top Artists:

Top 3 Artists by Number of Songs: Rihanna, Drake, and Eminem have recorded the maximum number of songs in their albums.
Top 3 Popular Artists: Rihanna, Eminem, and Drake are the most popular artists on Spotify, based on the dataset.
Top 3 Popular Songs:

"Sweater Weather" by The Neighbourhood
"Another Love" by Tom Odell
"Without Me" by Eminem
These findings highlight the dominance of certain genres and artists on Spotify, and the influence of explicit content on song popularity. The dataset provides a comprehensive overview of the characteristics that contribute to a song's success on the platform.
