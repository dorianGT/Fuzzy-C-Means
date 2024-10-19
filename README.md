# Fuzzy-C-Means

## Description

The goal of this project was to implement the Fuzzy C-Means (FCM) algorithm for image segmentation. FCM is a clustering method that allows each data point to belong to multiple clusters with varying degrees of membership, making it ideal for handling uncertain or overlapping data points. The objective was to apply FCM to segment images into fuzzy regions, visualizing the results through heatmaps.

Initially, the project focused on grayscale images with two clusters (K=2), later expanding to RGB images. The Python implementation relied on libraries like numpy, matplotlib, and cv2 for efficient computation and visualization.

## The core steps involved

- Initializing a membership matrix for clustering,
- Iteratively updating cluster centroids and membership values based on pixel distances,
- Displaying the segmented regions using heatmaps.

Further, the algorithm was adapted to RGB images by using Euclidean distances across color channels. While the segmentation produced satisfactory results for simpler images, some adjustments, like fine-tuning the fuzziness parameter and the number of clusters, were necessary to handle more complex images.
