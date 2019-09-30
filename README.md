# Satellite Imagery Python
Capstone project for DSI9 General Assembly.

Sample scripts and notebooks on processing satellite imagery over Jordan, Palestine and the dead sea.

## Executive summary:

The project goal is to develop an unsupervised model to cluster the pixels inside satellite imagery and distinguish land use from nature. A successful model can produce Land cover maps which can be used for producing more advanced and accurate maps. The work was carried out in three main phases: 
1. Obtsining imagery and and cropping multi Area of interest
2. Enhancing and manipulating images proprties to inhance contrast and hue
3. Developing the model and testing it

Land cover maps represent spatial information on different types (classes) of physical coverage of the Earth's surface, e.g. forests, grasslands, croplands, lakes, wetlands. Developing such a model is hugly dependant on the resolution of the satellite image and the Area-of-Interest. Once the images are obtained, some image manipulation, enhancement  and editing is required to make it easier to the model to distinguish each pixel within an image. The higher the resolution the better is the model at predicting since edges between objects become more clear.

After developing and tuning the model on a small image, it will produce clusters of similar pixels depending on their properties. Then, depending on the intended use of the study, we can improve the model by manually idintify correctly clustered features (water, land, buildings, rocks, roads, etc..). 

After running various models on different areas, it was clear that the model could result in different results depending on the training image, AOI, resolution, and number of clusters assumed in the image. 

Conclusions: Shadows in images induced some bias. arial images taken by drones and airplanes has better resolution and usually  adjusted for topographic relief lens distortion, and camera tilt.

## Image preparation 

The document contains all the required steps to crop a small portion of  the full spatial image to be able to work with limited resources.

two different satellite imagery types were used with different resolutions.


## Capstone Project - Building k-means clustering model

The Capstone document contains all the steps starting from the cropped images to model development.
