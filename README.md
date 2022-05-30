# K-means-classifier

Here, Iris data set is given as input. There are 3 types of flowers in this data set. They are as follow Iris-setosa, Iris-virginica, Iris-versicolor. So, now task is to divide the given data set into groups. You can divide dataset into 2,3,4, 5… groups. There are 4 features based on which you can group dataset. Features are Sepal length, sepal width, petal length, petal width. 
K – means 
It is clustering algorithm, and aim is to partition n observation into k clusters in which each observation belongs to the cluster with nearest mean. Also, we can say that K- means algorithm have k centroids and we try to place point to nearest cluster, measuring distance with each cluster canter point. K- means 
K- Means Algorithm Explanation
First step is to decide value of K. 
Here k = number of groups you want to create for given data set.
Second step Select k centroids from given data set. That k centroids represents k group respectively.
Third step, take points one by one and find distance of each point with k centroids.
Select minimum distance from centroid to given point (each point in dataset).
Assign Given point to the group which has least distance from respective centroid.
For example, there are 2 groups. First group has centroid c1 and second group has centroid has centroid c2. There are 20 points in data set. Now task here to find minimum distance for each 20 points to 2 centroids. For point 1 distance to centroid 1 is least then point 1 is assigned to group1.
After process is completed for all points in dataset, Find centroid for each group. Check if centroids are same as previous one then stop otherwise repeat process from step1. 
