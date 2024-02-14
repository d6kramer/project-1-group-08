## Group 08 Project:  Spotify 2023 Analysis

### Team Members:

Austin DeVore
David Kogge
Dan Kramer

### Project Description/Outline:

We will be analyzing a comprehensive dataset of streaming information from Spotify on 2023 streams focused on the most popular artists for that year. There are quantitative elements including number of streams per song, number of songs per artist, chart appearances on various platforms, etc., as well as qualitative elements, such as perceived danceability or "mood" of a song. Both types of data can be studied to answer interesting questions about users' listening habits in 2023.

Collaborators will each investigate different aspects of the dataset: David's analysis focuses on qualitative aspects regarding artists and number of streams; Austin's analysis of chart and playlist appearances look into any significant impact of such appearances on song popularity; and Dan's analysis considers the various musical characteristics and what "type" of music proved most popular with listeners in 2023.

Analsis summaries for each segment can be found below.

### Dataset to be used:

https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023


### Analysis of the Musical Characteristics -- Dan

This analysis focuses on three major components of the musical characteristics: Tempo (beats per minute), Modality (Major vs. Minor mode), and presence of a set of characteristics as defined and provided by the Spotify API. 

#### Tempo

While the selection of tempos in the top streamed songs ranges from 65 to 206, the median tempo clocks in at 120bpm. At two beats per second, this is an upbeat, fairly brisk tempo that may inspire energy in the listener, without being overwhelming. When analyzing the mode of the datasets, it was interesting to note a divergence between the full set of songs and the 20 most streamed artists' songs; 90bpm tracks showed up most often in the most streamed artists, but only accounted for 7 out of over 250 tracks. Meanwhile, the mode of the full dataset was equal to the median of 120bpm. While interesting, this only translated to 34 songs out of over 950 studied.

#### Modality

In music, major modes tend to have bright, positive, upbeat qualities, while minor modes are often associated with sadness, mysterious, uncertain, and darker qualities. While the full dataset revealed a simple majority of nearly 58% songs utilized a major mode, it was of note to see that the top 20 most streamed artist's tracks leaned into this result further, with over 62% of tracks having a major modality. This preference for characteristics provided by major modes so far aligns with the analysis of tempo - the associations are strong between upbeat, moderately paced music with a bright, positive modality! While no causation can be declared with certainty, it is interesting to consider whether popular demand for music of this type led to major modality being a feature in the 20 most streamed artists' tracks, or if the artists' tracks influenced the use of major modality throughout the dataset via their popularity. Studying the profile of musical characteristics may help shed light on this question.

### Characteristics

The characteristics provided by the Spotify API included danceability, valence (amount of positive vibes/messaging), energy, acousticness, instrumentalness, liveness, and speechiness. These are represented as a percentage value Spotify has assigned to each track. Upon analyzing the dataset, it becomes immediately clear that in 2023, danceability, valence, and energy were highly demanded musical traits, while acoustic, liveness, and speechiness qualities were considerably less popular. Practially non-existent for the year were tracks with purely instrumental qualities! When analyzing different measures of central tendency, it is interesting to note that the emphasis on certain characteristics seems to change. For instance, the most streamed artists appeared to put less emphasis on danceability, while more songs by those artists leaned into positive vibes and messaging. Meanwhile, the full data set revealed the opposite relationship between those values. The energy characteristic was highly utilized by both groups, regardless of approach to other musical traits.

### Summary

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




—Breakdown 

Data Cleaning - Initial cleaning opportunities by all three members

Questions/Analysis - See questions above for members' focuses. Each member will conduct their own analysis on a portion and create their respective charts and summaries.

Presentation - one person (TBA) to give a brief overview at the start of the presentation. Then each member will present their analysis.
