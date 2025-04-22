This RStudio code enables the user to:

1) Read the data from a survey as txt, remove missing values and standardize it
2) Keep the values from certain columns
3) Create diagrammes based on literature (cf. code) for the decision-making of the most optimal amount of clusters k, as explained in the code itself (Number of Clusters vs. Total Within Sum of Squares & Number of Clusters vs. Gap Statistic)
4) Read the data again with different removal of missing values and no standardization
5) Select chosen columns. The values on these columns will be used to make the k-cluster analysis assignation. The number of clusters k must be written manually in the code here
6) Perform k-cluster analysis based on the steps from Okamura 2016.
7) Create a summary table of the amount of clusters, amount of people in each clusters and the mean and standard deviation of the values from the selected columns
8) Export the summary table
9) Create a cluster assignation to each person in the original survey and export it as a new txt and csv file.
