# Phase 1

- [ ] Add postiion of cluster to all _cluster feature vector_
    - get center of each cluster from k-means clustering
    - add the value to _cluster feature vector_ of each cluster
- [ ] Clustering _clusters feature vectors_ of all images(using K-Means with k)
- [ ] _image feature vector_: make a vector for each image with length k 
    - k[0] = count of clusters of the image which are in cluster 0 in previous clustering(results of clutering all feature vectors of all images)
    - ...
- [ ] Train a model on _images feature vector_ to recognize flowers

# Phase 2

- [ ] Verctorize Image: average 
