# BreastCancer-PCA
Principal component analysis (PCA) is a technique used for identification of a smaller number of uncorrelated variables known as principal components from a larger set of data. The technique is widely used to emphasize variation and capture strong patterns in a data set. 

Imported Breast Cancer dataset from SciKit-Learn and visualized with Seaborn library to analyze the
data.
 Scaled the data to make each feature has a single unit variance.
 PCA is used to find the first two principal components, and visualize the data in this new, twodimensional
space, with a single scatterplot.
 PCA is used to emphasize variation and capture strong patterns in a data set.
 Instantiated a PCA object, found the principal components using the fit method, then applied the
rotation and dimensionality reduction by calling transform() function.
 Transformed the data to its first 2 principal components.
 In the components NumPy matrix array, each row represented a principal component, and each
column related back to the original features. The matrix is visualized this relationship with a heatmap.
