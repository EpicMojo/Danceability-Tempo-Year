# Danceability-Tempo-Year
The purpose of this project is to find the 'danceability' of songs in relation to their tempos and release year.
There are two graphs: one presents the danceability of songs to the range of tempos and one presents the danceability of songs per year.

The dataset was collected from Rodolfo Figueroa on Kaggle. The dataset contains audio features of over 1.2 million songs obtained through the Spotify API. Here's the link to the API documentation: https://developer.spotify.com/documentation/web-api/reference/#/operations/get-audio-features

'tempo' = value given to each song's tempo

'year' = value given to each song's year of release

'danceability' = value used to determine how easily a song is to dance to: 0.0 (hardest to dance to) - 1.0 (easiest to dance to)

There are 10 songs withing the dataset that are labeled year '0'. Otherwise, there are no known errors within the dataset or with the process of collecting the raw data. There is a possible bias, considering that the dataset was only made by one party (Spotify).

This dataset was downloaded from a user on Kaggle (Rodolfo Figueroa), was processed by separating and comparing three attributes/columns ('danceability', 'tempo', and 'year'), and those attributes were compared on two separate histograms ('danceability[y-axis]-tempo[x-axis]' & 'danceability[y-axis]-year[x-axis]') using regerssion analysis. The first histogram presents how easy it is to dance to each tempo and the second presents overall danceability of each year's songs.
