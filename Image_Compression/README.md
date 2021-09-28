# Image Compression 
Image compression is a type of data compression applied to digital images without degrading the quality of the image to an unacceptable level.

#### How does image compression work ?
Image compression algorithms take advantage of visual perception and the statistical properties of image data to provide superior results. 
There are two types of image compression:
1. Lossy (Eg: JPEG)
2. lossless. (Eg: PNG)

#### Lossless Compression:
Lossless compression is a method used to reduce the size of a file while maintaining the same quality as before it was compressed. The size of the file does not change in this type of compression. 
Algorithms used for lossless compression are:
1. Run Length encoding
2. Huffman Coding
3. Arithmetic Coding

#### Lossy Compression:
Lossy compression is a method of compression that eliminates the data which is not noticeable. To give the photo an even smaller size, lossy compression discards some parts of a photo which are less important. The compressed file cannot be restored in its exact original form. 
In this type of compression data quality is compromised and the size of data changes. Lossy compression is used mainly for images, audio and, video compression.
Algorithms used for lossy compression are:
1. Discrete Cosine Transform
2. Fractal compression
3. Transform Coding

#### Project implementation and workflow:
Following are the subtasks of the project:
1. Import Libraries
2. Data Preprocessing
3. Visualizing the Color Space using Point Clouds
4. Visualizing the K-means Reduced Color Space
5. K-means Image Compression with Interactive Controls

In this project, I have used K-Means clustering unsupervised learning algorithm using scikit-learn and Python to build an image compression application. It is a type of Transform method of compression. Using K-means clustering, we will perform quantization of colors present in the image which will further help in compressing the image.


#### What is K-Means Clustering ?
K-Means algorithm is a centroid based clustering technique. This technique cluster the dataset into k different clusters. Each cluster in the k-means clustering algorithm is represented by its centroid point.


#### How does the K-Means Clustering technique compress the image?
In a colored image, each pixel is of size 3 bytes (RGB), where each color can have intensity values from 0 to 255. Following combinatorics, the total number of colors which can be represented is 256x256x256 ( equal to 16,777,216). 
Practically, we can visualize only a few colors in an image very less than the above number. So the k-Means Clustering algorithm takes advantage of the visual perception of the human eye and uses few colors to represent the image. 
Colors having different values of intensity that are RGB values seem the same to the human eye. The K-Means algorithm takes this advantage and clubs similar looking colors (which are close together in a cluster).
