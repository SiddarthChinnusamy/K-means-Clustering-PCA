# Objective
  The objective of this exercise is to build a model that clusters the 22 provinces in Argentina into groups
  so that one province from each of the group can be chosen for the pilot implementation of an educational program.
  The reason being to ensure that the provinces chosen for pilot implementation are representative of the entire country, 
  so that the results observed from the pilot implementation can be trusted to be reliable once the program is scaled up to the entire     nation.
  This is a guided project in Datacamp

# Data Understanding
  The dataset has information on the following 10 aspects of the 22 provinces in Argentina
  1. gdp
  2. Illiteracy Index
  3. Poverty Index
  4. Deficient-infrastructre Index
  5. School_dropout index
  6. Healthcare index
  7. Birth mortality rate
  8. population
  9. Movie theatres per capita
  10. doctors per capita

# Flow
  1. Apply Principal Component Analysis to reduce the dimensionality of the dataset and extract maximum variation of the data in minimum      number of dimensions (Principal Components)
  2. Cluster the 22 provinces by applying k-means algorithm on the dataset transformed to co-ordinates in the Principal components
  3. Choose one province from each of the clusters for pilot implementation of the program

Additional Exploratory analysis
  1. After clustering, the datapoints of various clusters can be compared with individual fields like Poverty Index to check how the          clusters vary with respect to a particular metric

# Results
  1. % of variance explained by the 2 principal components = 63.5% (PCA1 = 45.3%, PCA2=18.2%);
  2. Number of clusters = 4;
  3. Number of provinces in each cluster ;
  4. Cluster 1 = 1;
  5. Cluster 2 = 7;
  6. Cluster 3 = 6;
  7. Cluster 4 = 8;







