# Text-Clustering-Kmeans
## Download the fine foods dataset from:
[Web Fine Foods](http://snap.stanford.edu/data/web-FineFoods.html)
## Performed the following processing the data set:
#### Identified all the unique words that appear in the “review/text” field of the reviews. 
#### Removed all stopwords in “Long Stopword List” from http://www.ranks.nl/
#### Counted the number of times each word appears among all reviews (“review/text” field)
#### Vectorized all reviews (“review/text” field) using these 500 words (see an example of vectorization here: https://bit.ly/3CcY9i4).
#### Clustered the vectorized reviews into 10 clusters using k-means. 
#### From each centroid, selected the top 5 words that represent the centroid (i.e., the words with
the highest feature values)
