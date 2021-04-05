# Streaming Music Analysis - Project 1
By: Eric Meyer, Kristen Scaletta and Michelle Simek

## Data Sources
We downloaded our data from the following sources:
- Spotify Dataset 1921-2020, 160k+ Tracks (https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks)
- Spotify - Top Songs by Country Charts (https://www.kaggle.com/hkapoor/spotify-top-songs-by-country-may-2020?select=SpotifyTopSongsByCountry+-+May+2020.csv)

## Overall Findings

Hypothesis 1: Artists ranked higher overall are consistently ranked higher in individual continents. (Higher being closer to 1.)
Based on this analysis, it appears there is some merit in this statement and it would be worth further exploration. This analysis shows that when artists are ranked closer to 1 globally, this is not indicative of country rankings. More research into how rankings are calculated globally and by country could be interesting to see if there is a different method.

Hypothesis 2: More popular and better ranked artists tend to have higher energy, danceability, loudness and tempo.
There appears to be some correlations when looking at popularity but not when looking at rank. Perhaps bucketing musicalities into broader song categories (like genre) and seeing which together tend to result in more popular or higher ranked songs could be interesting. Also, looking at the same musicalities for popularity and rank may help.


### Findings by Question

#### Question 1: How does top artists’ rank across continents compare to their global rank?

Process: Looked at individual top artists’ ranks in each continent in which they are ranked compared to how they are ranked globally.

Related Plots and Findings:

![GitHub Logo](/Images/top_artist_The Weeknd.png)

1. Findings: In this case, it appears the Weeknd is ranked higher globally (10) than in any continent. Would be worth looking into global ranking methodology

![GitHub Logo](/Images/top_artist_Lady Gaga.png)

2. Findings: Lady Gaga ranked well in Australia and Africa but ranked above 30 in South America. 


![GitHub Logo](/Images/top_artist_Dua Lipa.png)

3. Findings: Dua Lipa globally ranked in the top 20 but was in the 20 – 30 range across all continents except for Australia.

![GitHub Logo](/Images/top_artist_Powfu.png)

4. Findings: Powfu ranked well in Africa, Asia and Australia but ranked worst in North and South America. 

![GitHub Logo](/Images/top_artist_Tones and I.png)

5. Findings: Tones and I ranked well in Africa with a global ranking around 10 but averaged between 20 and 30 for the remainder continents.  

![GitHub Logo](/Images/top_artist_SAINt JHN.png)

6. Findings: SAINT JHN ranked better across continents compared to the previous 5 artists noted above but shoots to roughly 35 in South America. 

![GitHub Logo](/Images/top_artist_Drake.png)

7. Findings: Drake ranked the worst in South America compared to all top 10 artists but, globally, he is one of the top performers. 

![GitHub Logo](/Images/top_artist_Ariana Grande.png)

8. Findings: Ariana Grande was one of the best ranked in North America.

![GitHub Logo](/Images/top_artist_Doja Cat.png)

9. Doja Cat ranked worst both globally and across most continents compared to other artists.

![GitHub Logo](/Images/top_artist_THE SCOTTS.png)

10. The Scotts ranked very well in Africa and, globally, is one of the best ranked artists. 


#### Question 1: Is there a relationship between “musicalities” and rank? 

Process: Compared average artist rank to various musicalities for artists whose average rank is less than or equal to 10. Musicalities includes energy, danceability, tempo, loudness, etc.

Related Plots and Findings:

![GitHub Logo](/Images/DancevRank.png)

1. It appears there may be a very weak positive correlation between danceability and rank suggesting lower ranked songs (farther away from 1) may have more danceability.

![GitHub Logo](/Images/EnergyvRank.png)

2. Findings: There appears to be a weak negative correlation between energy and popularity, suggesting higher ranked songs (being closer to 1) may have more energy. 


Overall Analysis: We did not see strong correlations between artist rank, danceability and energy. We also did not see any clear clusters between either musicalities in the data sets. 

#### Question 2: Is there a relationship between “musicalities” and popularity across countries? 

Process: Compared popularity to various musicalities for the top 10. Musicalities includes energy, tempo, loudness, etc.


Related Plots and Findings:

![GitHub Logo](/Images/pop_loudness_scatter.png)

1. Findings: It appears there may be a positive correlation between loudness and popularity.

![GitHub Logo](/Images/pop_tempo_scatter.png)

2. Findings: There appears to be a positive correlation between tempo and popularity. Looking further into the cluster would be interesting.

![GitHub Logo](/Images/pop_val_scatter.png)

3. Findings: There appears to be a weak negative correlation between valence and popularity.

Overall Analysis: When looking at music “likability” across countries, both Tempo and song Loudness seems to correlate with a song’s popularity. Tempo is clustered around 120bpm and loudness between -7 and -6. Valence, a ranking if a song is happy (higher valence) or sad (lower valence), doesn’t seem to have a strong correlation across countries by popularity and there doesn’t seem to be any apparent valence clusters. 

#### Question 3: Is there a relationship between “musicalities” and rank? 

Process: For this analysis, song rank was compared to various musicalities for the top 10 (artists or songs). Musicalities includes energy, danceability, tempo, loudness, etc.

Related Plots and Findings:

![GitHub Logo](/Images/DancevRank.png)

1. It appears there may be a very weak positive correlation between danceability and rank suggesting lower ranked songs (farther away from 1) may have more danceability.

![GitHub Logo](/Images/EnergyvRank.png)

2. Findings: There appears to be a weak negative correlation between energy and popularity, suggesting higher ranked songs (being closer to 1) may have more energy. 

Overall Analysis: We did not see strong correlations between artist rank, danceability and energy. We also did not see any clear clusters between either musicalities in the data sets. 
