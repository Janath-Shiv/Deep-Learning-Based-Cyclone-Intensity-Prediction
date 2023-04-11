# Deep Learning Based Cyclone Intensity Prediction

Development of a deep CNN for Tropical Cyclone
 intensity estimation using half-hourly INSAT-3D IR Images and development of a
 web application for visualization of the imagery. 

INSAT3D/3DR observations are available at every 
30-minute interval and these observations are very useful in understanding the
 instantaneous structural changes during evolution, intensification, and landfall of 
Tropical Cyclones. 

Datasets of Cyclones captured by INSAT-3D over the 
Indian Oceans are available since 2014. These datasets can be used for training and 
testing of the Model. 
			Traditional methods for Intensity estimation require 
accurate center determination for intensity estimation. Development of this estimation 
will be very useful during the initial stage of cyclone formation when determination 
of accurate center becomes difficult.

CNN:
It is used mainly for image processing, classification, segmentation and 
     also for other auto correlated data. 
A convolution is essentially sliding a filter over the input.

VGG16:
 It is one of the CNN model used for image processing.
 Accuracy is high comparing with mobile net model.
VGG16 has 
13 convolutional layers to extract features 
3 dense layers for classification.

- Cyclone Tauktae
	- From 14/05/2021 to 19/05/2021.
	- Images taken : 257

- Cyclone Amphan
	-From 16/05/2020 to 21/05/2020.
	- Images taken : 200
	
- Non-Cyclonic days:
	-20/05/2021 and 21/05/2021.
	-Images taken : 96

	Total number of images taken : 553 (before augmentation).
  
  Total number of images taken : 6000 (after augmentation).
  
  Using VGG16 model, considering two types of cyclones Tauktae and Amphan with images of 553 and with 300 epochs we got the accuracy of 0.8779 .





