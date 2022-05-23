# KMEANS-clustering--MNIST
#Write a program k-means to implement k-means clustering. The function accepts two inputs: 
#a list of N data vectors to be clustered, and the number of clusters, K. The program outputs three
#quantities: a list ofN, group assignment indices ( Ci, c2 , ... , cN) indicating the association of each data vector to a specific group,
#a list ofK group representative vectors (µ1, ... , µK) and the value 
#of Jclu5t after each iteration of the algorithm until convergence or termination. 
#Let K = 20. Implement k-means on the MNIST dataset, starting with a random assignment of the vectors to clusters, and repeating the experiment P = 30 times. 
#Save the output of the algorithm for each of the 30 runs.
#(a)	Plot the value of Jclust as a function of the number of iterations. Comment.
#(b)	Visualize the K group representatives as images. 
#Interpret the group representatives (if which digits, they represent, or if they represent something else) and compare them for these two runs.
#(c)	Find the 10 nearest data points to each of the K group representatives.
#Manually list what digits they represent (by eye estimation). 
#Plot a few of the correctly classified as well as misclassified data points as images, alongside the group representatives (also represented as images).
#3.	Repeat part 2 for K = 10 and P = 20
#4.  Repeat part 2 for K = 5 and P = 10
