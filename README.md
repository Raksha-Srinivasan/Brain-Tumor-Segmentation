# Brain-Tumor-Segmentation

This Project aims in extracting the accurate location of tumor cells using differnt techniques such as K-Means Clustering and WaterShed Algorithm.

# Kmeans Clustering
The main objective of this algorithm is to reduce the sum of distances between the data point and their corresponding clusters.The algorithm takes the dataset as input, and divides it into k-number of clusters,and repeats the process until it does not find the best clusters.The value of k should be prearranged in this algorithm.

**Architecture:**
1.Give Brain MRI-Image as Input Image.
2.Pre-process the image.
3.Apply K-Means Clustering.
4.Extract the important feature and locate the tumor cell.


# WaterShed Algorithm
 The main aim of this algorithm is to segment the image,when two region of interest are close to each other taht is when their edges meet each other.
 
 **Architecture**
1.Give Brain MRI-Image as Input Image.
2.Convert the Original Input Image to Grayscale Image.
3.Filter the image and remove the noises present in the image.
4.Enhance the image and apply Thresholding Technique.
5.Apply WaterShed algorithm
6.Use morphological techniques to locate the final tumor cells.
