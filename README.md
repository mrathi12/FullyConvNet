# FullyConvNet

This is the research report I wrote for my research placement at the Computer Vision Lab in the School of Computer Science at the University of Nottingham during July-August 2016.  

The project was a segmentation task - segmenting the feet of babies from the surrounding clutter in images taken of newborn babies. The results attained from this could then be used to generalise to images of other parts of the newborn babies.
This research project's results (described as "state of the art" by my supervisor) were then used by my supervisor and the rest of the team as part of the Gestate Gates Foundation research project.

As part of this project, I used Matlab to pre-process the image dataset - standardising the images and creating ground truth masks for each of the images - and then trained the Fully Convolutional Network using Caffe. Finally, I used Matlab to post-process the output segmented images, and to visualise and evaluate the performance on the test set.
