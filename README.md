# songLyricsAnalysis_NLP
This project consists of web scrapping some websites to collect the data for song lyrics in 3 countries: Morocco, Algeria, and Tunisia.
And also applying the preprocessing on the data to remove the non-important things such as the special characters, the stop words ... In the preprocessing, I also apply id Lemmatization, Stemming, and The tokenization.
Then, I apply different methods like TF-IDF, word2vec, and Transformers.
The scrapped data 'songs.csv' contains 992 lines and 4 columns (Artist, Song, Lyrics, Dialect). 
The Dialect = 0 for Moroccan songs, Dialect = 1 for Tunisian songs, and Dialect = 2 for Algerian songs.
