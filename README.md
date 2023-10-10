# Exploring Unsupervised Learning Methods from Scratch
# Problem 1
This task involves exploring methods of dimensionality reduction. We will be looking into PCA (principal component analysis) for this task. Principal Component Analysis (PCA) is the general name for a technique which uses sophisticated underlying mathematical principles to transform a number of possibly correlated variables into a smaller number of variables called principal components.

Use only NumPy, Pandas, Matplotlib, and Plotly libraries for the tasks. The use of any other libraries shall be accepted only upon the approval of the TAs.

## PCA
This task requires you to implement Principal Component Analysis and perform dimensionality reduction on a given dataset(s). The list of subtasks is given below.
- Perform dimensionality reduction on the IIIT-CFW dataset, varying the number of principal components. We have given the script to pre-process the data and to get the necessary information from the image Script.
- Plot the relationship between the cumulative explained variance and the number of principal components. The x-axis of the plot typically represents the number of principal components, and the y-axis represents the cumulative explained variance.
- Perform dimensionality reduction on features that you have used for assignment 1 (pictionary dataset) and show the metrics you have shown for assignment 1. Compare the results and write down the observations in the MARKDOWN.
- Observe the impact of dimensionality reduction on the dataset. Use a classifier on the dataset pre and post-dimensionality reduction (if the number of features of the dataset is n, perform dimensionality reduction varying the principal components from 1 to n) and note the accuracies of the classifier. You are free to use external libraries for the classifier.

## Pictionary Dataset
This task is to perform PCA on the Pictionary Dataset (Dataset). The attachment also contains the description for the Dataset. Perform PCA for both drawer and guesser.
- Plot the above features with respect to the obtained PCA axes.
- What does each of the new axes that are obtained from PCA represent?

# Problem 2
The EM algorithm is used for obtaining maximum likelihood estimates of parameters when some of the data is missing. More generally, however, the EM algorithm can also be applied when there is latent, i.e. unobserved, data which was never intended to be observed in the first place. In that case, we simply assume that the latent data is missing and proceed to apply the EM algorithm. The EM algorithm has many applications throughout statistics. It is often used, for example, in machine learning and data mining applications, and in Bayesian statistics where it is often used to obtain the mode of the posterior marginal distributions of parameters.

Membership value ric of a sample xi is the probability that the sample belongs to cluster c, in a given GMM (Gaussian Mixture Model).

# Problem 3
Hierarchical clustering is a popular method for grouping objects. It creates groups so that objects within a group are similar to each other and different from objects in other groups. Clusters are visually represented in a hierarchical tree called a dendrogram.

Use only NumPy, Pandas, Matplotlib, and Plotly libraries for the tasks. The use of any other libraries shall be accepted only upon the approval of the TAs.

## Hierarchical Clustering
This task requires you to implement Hierarchical clustering and perform clustering on a given dataset(s). The list of subtasks is given below. You are expected to implement the required, using classes and methods. We expect to see routines like hc.linkages(X, linkage type) (takes the data and provides linkage matrix), hc.dendogram(Z) (takes the linkage matrix and plots a dendogram).

- Perform hierarchical clustering on the dataset and obtain the linkage matrix. Vary the linkages and features used and state your observations. Plot the dendogram using the linkage matrix.
- Perform hierarchical clustering on the gene expression dataset and obtain the linkage matrix. Vary the linkages and features used and state your observations. (In the dataset, you are given 58 genes, their respective expression levels for 12 proteins and their IDs, resulting in a 58 × 13 matrix). Plot the dendogram, using the linkages obtained.

# Problem 4
For this section, you are free to use external libraries to solve the question(s). Submit separate notebooks for each of the following sub-questions in this section.

## Problem 4.1
You have been provided a dataset of 99 different shapes KIMIA-99. The task is to find the align the remaining shapes based on the orientation of the given template shape. Along with the code, write the flowchart of the algorithm that you will be using to implement the following task in the Jupyter Notebook itself as a MARKDOWN.

## Problem 4.2
The task is to determine the optimal horizontal and vertical euclidean distance thresholds between bounding boxes containing words on a document page. The objective of this task is to establish connections between boxes within a paragraph while ensuring that boxes across paragraphs and columns remain unconnected.

You have also been given the following scripts:
- To visualize the enclosing boxes.
- Script to visualize the connecting boxes is there in the above attachment. The input for this script is a dataframe object with the following attributes: ID, Top-Left, Bottom-Right, Top edge center, Bottom edge center, Right edge center, Left edge center, Top box, Bottom box, Right box, Left Box.

## Problem 4.3
For this problem, you shall be provided with a dataset of 2-dimensional points, of various colors. The data you will be given is in the form of an array, where each element, X, represents a point in the 2D color space. The data has been generated from 7 distinct Gaussian color components. The list of subtasks is given below.
- Find the likely color components which generate the dataset.
- Create a function which would take in an input of (number of components (an integer, n), means (a numpy array of shape (n, 2)), covariances (a numpy array of shape n, 2, 2)), and generates a sample dataset with the n likely components described by the above components. State your observations.


