# Diamonds Data Exploration

## Dataset

The data consists of information regarding more than 170,000 tracks on Spotify. The dataset contains the numerical and categorical
attributes of different tracks. These attributes are: Valence, acousticness, energy, danceability, liveness, loudness, popularity, instrumentalness, speechiness, duration, tempo, key, mode, and explicitness.
The dataset can be found on Kaggle [here](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks).


## Summary of Findings

After the preliminary of data wrangling I started my univariate analysis, showing some useful results such as that the mean tempo of all tracks is about 117 bpm, and that so many tracks have a popularity of 0.

Following that, I started my bivariate analysis stage, in which I plotted the correlation plot on a heatmap, showing some solid correlations. I then plotted categorical variables against numerical ones, one of the results I got was that acoustic tracks in D#/Eb are more than any other key.

I then proceeded to split my dataset into 10 different ones, each holding a span of 10 years. I did that to find trends in the attributes of music. As expected, acousticness decreased sharply in the 1960s and the decades following it, this is due to the introduction of electric instruments. Another interesting result was that the key of C#/Db gained huge popularity in the last few decades, exceeding any other key.

I then plotted scatterplots holding 3 variables, the popularity on the hue variable. Showing that popularity decreases with increasing acousticness was one of the results I found.


## Key Insights for Presentation

For the presentation, I focus on just the important distributions such as the duration, tempo, and other numerical attributes;
along with the distribution of the use of each key. Another source of insights was the scatterplots and barplots
plotted between different attributes (both categorical and numerical). I found trends in the progression of
acousticness, energy, and the use of keys. I then studied the relationship between three different numerical attributes:
energy, acousticness, and popularity.

