# Image Color Segmentation

This is an interesting take on segmentation. The goal of the project is to create a tool which is able to segment images by    color, and further report the top three colors present in the images along with their densities. Additionally, It also          identifies these colors by their name

## Goal
The goal of the project is to create a tool which is able to segment images by color, and further report the top three colors present in the images along with their densities. Additionally, It also identifies these colurs by their name

## Some Applications
This tool can potentially find application across a wide array of use cases - from automating the filling in the decsription/ color details in a product catalogs (or in an e-commerce page) or to perform a visual analysis of brand logos or corporate communication to more outside the box ideas like identifying the forest cover in landscape images.

## Underlying Logic / Algorithm
The pixels of the image are clustered into groups based on their RGB values. The cluster centroids (centers) are the average intensities of prominent colors. This point will be clearer looking at some of the examples below.

The underlying algorithm is a version of KMeans called KMeans++ . KMeans++ converges better than the regular KMeans algorithm.
