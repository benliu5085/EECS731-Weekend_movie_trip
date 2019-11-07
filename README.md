# EECS731-Weekend_movie_trip

This is the project of EECS 731 Data science.

(1) Content

|-READ.ME
|-proj3.ipynb
|-data
| |-movies.csv
| |-ratings.csv
| |-tags.csv

(2) Ideas
Firsr I combine ratings and tags from the same user and find out that like genre, some tag seems to have specific ratings associated with them. 
Then I apply kmeans, meanshift and birch clustering algorithm to cluster the genre of all movies. 
I was going to measure the clustering result by apply the model on the favorite movies for each user and see if they belong to the same cluster, but then I found that this measure is not reasonable because the user could like different movies. So I focused on the movies with the same tag, and the result looks reasonably good to me.
