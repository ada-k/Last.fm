### Last.fm
Start [here](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjW1uDf0urtAhWCyYUKHW0qB8wQmhMwJ3oECC0QAg&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FLast.fm&usg=AOvVaw3uWCXF5ZOlO5HHonorU1ix)

So its gonna be an analysis platform and a recommendation system. The beginning of an epic journey.

#### Dataset
* This [Benjaminbenben](https://benjaminbenben.com/lastfm-to-csv/) site allows one to download a users data from the lastfm api and save it as a csv file. 
* [Kaggle dataset](https://www.kaggle.com/pcbreviglieri/lastfm-music-artist-scrobbles?select=lastfm_user_scrobbles.csv) - contains info about scrobbles per artist per user. Useful in artist recommendation.
* [Kaggle dataset](https://www.kaggle.com/ravichaubey1506/lastfm), kinda same as the above set.

1. Recommendation part: 
* Personalised recommendation -- Reviews and ...
* Non-personalised recommendation -- Common pairs.
* Text based -- Attributes/Features - Jaccard Similarity.
* Content Based -- Plot/Description/Summary - Cosine Similarity.
* Profile Recommendation -- 
* Collaborative filtering -- user based(similar users). -- item based (similar item feeling)
* KNNs
* Dealing with Sparsity - matrix factorisation -- singular value decomposition.
* Validation

2. Language Processing

