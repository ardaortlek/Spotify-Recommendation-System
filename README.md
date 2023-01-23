# Spotify-Recommendation-System
In this project, we aimed to code a recommendation system for Spotify playlists. The
goal is to recommend 10 songs based on the technical properties of each track in the playlist
using unsupervised learning algorithms. Since the playlists contain a set of songs within a
similar fashion, the song which will be recommended will also have compatible features.
Content-based approach was utilized. For this purpose, the tracks’ features in the playlists are
taken from Spotify Web API. Then, the average of these features forms a single vector close
to the desired track. On the other hand, the unsupervised learning methods such as k-Means
and DBSCAN perform clustering. The trained models give recommendations based on those
clusters and the vectorized playlist. In this way, a matching track from a track pool will be
selected in line with the feature vector. In order to evaluate the model, we calculate the
Silhouette Score, Mean Square Error (MSE) and R2 Score. For this project we tried three
different inputs by changing data reduction methods and two different clustering algorithms.
The evaluation scores of those inputs and algorithms will be discussed in the following parts.
