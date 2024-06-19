# Data-Projects
Analyzing factors impacting number of streams on Spotify using Python



The project included running all the major tests starting from data cleaning and analysis including: Descriptive analysis of data, checking for heterskedaticity and outliers; finding the right factors that impact maximum number of spotofy streams using BorutaShap and Mallow CP, and then conducting k-cross validation to validate that data is trained and then tested to check if model is giving right predictions or not.

<img width="878" alt="Screenshot 2024-06-18 at 11 49 55 PM" src="https://github.com/akshikh/Spotify-Streaming-Regression-Analysis/assets/173235208/c6da7628-2dd8-40a0-b42d-b6f5b9f3aa68">


After running OLS regression and validating its results, we can conclude that top 4 predictors found were 'in_spotify_playlists', 'in_apple_playlists', 'in_deezer_charts', 'in_deezer_playlists' that affected the number of times a song is streamed
