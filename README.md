This is my Thesis, written in Greek, in hopes of me finding the time to translate it to English.
This Repository was initially created to upload some code segments from various environments that were used in this thesis.

Abstract
This thesis presents the development of a prototype wildfire‐risk mapping system based exclusively on imagery—both satellite and UAV‐acquired. 
First, a preliminary set of satellite images was assembled from the Google Earth collection, which was used to design and initially train convolutional neural networks. Next, a dedicated UAV dataset was created via drone flights, with meticulous annotation of the core classes (ground, shrubs, trees, roads, buildings, and high‐voltage lines). Semantic segmentation was implemented using a U-Net architecture, while specialized mask post‐processing techniques (thresholding, median filtering) ensured label quality. 
Experimental results demonstrated high accuracy, satisfactory mean IoU, and robust performance in the most critical categories. Furthermore, we describe the procedure for assigning risk weights to each detected biomass type in order to produce the final “risk maps.” The thesis concludes with a discussion of the challenges of real-time integration, as well as recommendations for expanding the dataset, incorporating 3D data, and deploying the system in full-scale field applications.
