# Camouflage_Project
Dataset

I have used the COD10K dataset to predict the camouflaged objects in the image
The project is still in progress

# Preprcessing 
for the x label i have taken the camouflaged images and normalized them by converting the array values of the image between 0 and 1
for the y label i have used the object detecion image, passed is through a contour filter so that the y label becomes a green colored outline pf the image
all of the images are normalized and are in rgb ie 3 channels

# Model
the si-net model architecture is used for this problem. The model takes the image in 3 channels and outputs and image in 3 channels

# Overall Progress

i have basically taken 4 categories of images and trained the model seperately. The categories are aquatic, amphibian, terresstrial and Flying
i have the model seperately for the categories and for prediction the individual weights are loaded to predict their respective categories. The model is able 
to predict different shapes for different categories but it is not able to locate the camouflaged object in the image.

The project is still in progress
