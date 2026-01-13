# Robot Movement Classifier with PCA

**Abstract:**

Here, we study a robot which records the movements of 38 of its joints. It performs 3 movements:
running, jumping, and walking. Our goal is to construct a classifier that takes a sample of movement and
identifies which movement was performed. We do this by using Principal Component Analysis (PCA) to
project our data onto a lower dimension, and classify each sample by assigning it to the class of movement
whose centroid is closest to its position, in low-dimensional space. We will adjust the dimensionality of the
problem and explore how many dimensions are necessary in our low-dimensional approximation.

Note: Data and project setup provided by Dr. Natalie Frank at the University of Washington as a part of the AMATH 482 Course.
