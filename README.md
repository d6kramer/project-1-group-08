## Group 08 Project Title:    Spotify 2023 Analysis

### Team Members:

Austin DeVore
David Kogge
Dan Kramer

### Project Description/Outline:

We will be analyzing a comprehensive dataset of streaming information from Spotify on 2023 streams focused on the most popular artists for that year. There are quantitative elements including number of streams per song, number of songs per artist, etc., as well as qualitative elements, such as perceived danceability or "mood" of a song. Both types of data can be studied to answer interesting questions about users' listening habits in 2023.

Collaborators will split research and analysis of the dataset into the following categories, with findings summarized below:

David: Song and artist popularity quantitative analysis

Austin: Chart and playlist appearance on various platforms' relationship to song and artist popularity, streaming figures

Dan: Analysis of musical characteristics to determine most popular traits of songs steamed in 2023

### Analysis of the effects on number of playlists a song appears and the ranking of a song in the charts - Austin

This analysis focuses on the effects on number of playlists a song appears and the ranking of a song in the charts.  Each platform has a count of the number of times a song appears in a playlist.  The platform also provides a ranking of the song within their respective charts. 

#### Effects on number of playlists

Overall there seemed to be weak positive coorelation when looking at how many times a song appears in a playlist and how many times a song is streamed.  We looked at the top 100 streamed songs of the data set where we recieved a correlation coefficent of 0.3345158403 and r-value of 0.11190084743056486.  Again we recieved a weak positive correlation when looking at the top 100 songs that appeared on all streaming platforms and the number of times they have been streamed.  The correlation coefficent is 0.1446829038 and the r-value is 0.02093314265788846.  Finally, we looked at the top 100 songs on playlists and the bottom 100.  From the scatterplot, we could see that songs in the bottom 100 did not get over 1 billion streams, but songs in the top 100 were well over 1 billion, even over 6 billion streams. 

#### Charts

We then looked at if the ranking of a song would effect the popularity of the song.  For this we looked at each platform indiviually.  Each platform seemed to have its own pattern.  For Deezer and Shazam, their scatterplots really showed the songs that are ranked higher on their charts ended up with more streams.  Spotify did as well, but I do not know it was as strong of a correlation as deezer and shazam.  The Apple platform was interesting as their most streamed songs were more in 100 to 200 ranking in the charts.  

#### Summary

In conclusion, when asked the question "Do songs in playlists get more listens than songs not on playlists?" based on our findings from the scatterplots, I would say that if a song is on more playlists then a song will generally get more streamed even though it is a weak correlation. As for if charts have an impact on popularity, I would say that the ranking of a song on a platform does not necessarily dictate the songs popularity.  

### Analysis of the Musical Characteristics - Dan

This analysis focuses on three major components of the musical characteristics: Tempo (beats per minute), Modality (Major vs. Minor mode), and presence of a set of characteristics as defined and provided by the Spotify API. 

#### Tempo

While the selection of tempos in the top streamed songs ranges from 65 to 206, the median tempo clocks in at 120bpm. At two beats per second, this is an upbeat, fairly brisk tempo that may inspire energy in the listener, without being overwhelming. When analyzing the mode of the datasets, it was interesting to note a divergence between the full set of songs and the 20 most streamed artists' songs; 90bpm tracks showed up most often in the most streamed artists, but only accounted for 7 out of over 250 tracks. Meanwhile, the mode of the full dataset was equal to the median of 120bpm. While interesting, this only translated to 34 songs out of over 950 studied.

#### Modality

In music, major modes tend to have bright, positive, upbeat qualities, while minor modes are often associated with sadness, mysterious, uncertain, and darker qualities. While the full dataset revealed a simple majority of nearly 58% songs utilized a major mode, it was of note to see that the top 20 most streamed artist's tracks leaned into this result further, with over 62% of tracks having a major modality. This preference for characteristics provided by major modes so far aligns with the analysis of tempo - the associations are strong between upbeat, moderately paced music with a bright, positive modality! While no causation can be declared with certainty, it is interesting to consider whether popular demand for music of this type led to major modality being a feature in the 20 most streamed artists' tracks, or if the artists' tracks influenced the use of major modality throughout the dataset via their popularity. Studying the profile of musical characteristics may help shed light on this question.

#### Characteristics

The characteristics provided by the Spotify API included danceability, valence (amount of positive vibes/messaging), energy, acousticness, instrumentalness, liveness, and speechiness. These are represented as a percentage value Spotify has assigned to each track. Upon analyzing the dataset, it becomes immediately clear that in 2023, danceability, valence, and energy were highly demanded musical traits, while acoustic, liveness, and speechiness qualities were considerably less popular. Practially non-existent for the year were tracks with purely instrumental qualities! When analyzing different measures of central tendency, it is interesting to note that the emphasis on certain characteristics seems to change. For instance, the most streamed artists appeared to put less emphasis on danceability, while more songs by those artists leaned into positive vibes and messaging. Meanwhile, the full data set revealed the opposite relationship between those values. The energy characteristic was highly utilized by both groups, regardless of approach to other musical traits.

#### Summary

When considering the analysis of all of the musical characteristics in aggregate, it appears that Spotify users were most heavily drawn to high energy, upbeat, positive music that showcased positive vibes and was quite danceable. They also picked songs that were brisk without being aggressively fast, suggesting the music could compliment moderately physical activities, such as dancing or working out. It is also possible that listeners more often than not were seeking a "pick-me-up" or positive energy association with their music choices, rather than being conmtemplative or dark. Without qualitative surveys of listeners, or further information regarding how musical characteristic percentages are assigned, it is difficult to make more specific conclusions, or to test our initial findings. 




–Research Questions to Answer:

Who were the most popular artists in 2023 by number of streams?

What was the distribution of listening based on year? - David

Do songs in playlists get more listens than songs not on playlists?

Do charts have an impact on popularity? Austin 

 What factors were most popular for 2023? Is there a relation between factors?
i.e., which types of songs were listened to more? Fast/Major vs Slow/minor, high danceability, low “speechiness,” etc. What is the average BPM of the most *
listened to songs? How did this compare to other qualities? Dan

*Questions are intended to be “sharpened” into more specific ideas as these are the exploratory starting points.*


–Datasets to be used:

https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023

—Breakdown 

Data Cleaning - Initial cleaning opportunities by all three members

Questions/Analysis - See questions above for members' focuses. Each member will conduct their own analysis on a portion and create their respective charts and summaries.

Presentation - one person (TBA) to give a brief overview at the start of the presentation. Then each member will present their analysis.
