# Recommendation engine for books

### Objective:
The idea is to create a recommendation engine for most preferred books based on 'saves and searches' by getting into the readers mind. This project will analyze the book ratings, author, average ratings, and the book itself.

![books](book.jpg)

### Exploring the data:
Some of the columns of the data are bookID, title, authors, average_ratings, etc. Cleaned some of the data by removing the NaN value and reordering the columns. Added some new columns to include them for the engine. Sorted out the incorrect values from the data

### Clustering:
Used PCA in hierarchian clustering to make the data output better. this was done by sing StandardScaler() and PCA(). PCA function is to reduce the dimension of the data. The StandardScaler function is used to remove the mean and scale the values to unit vector so that the clustering can be done easily. 

### Conclusion:
By calculating the mean and getting the minimum number of ratings count was able to create the recommendation engine to cluster similar books together for recommendation.
