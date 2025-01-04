# ai-car-generator
Generate car images from segmentation maps using the carvana dataset.

![Alt Text](images/sample1.png)

This model was trained to generate a synthetic image of a car from a segmentation map using a pix2pixHD conditional generative adversarial network (CGAN).
We uses the single car image segmentation dataset - Carvana Image Masking (PNG). 
# Data preperation
The entire dataset contains 5088 image-mask pairs and the dimensions of each image are 448x320 pixels. Since this model is intended for initial testing, we decided to use a subset of 701 pairs for quicker fine-tuning.
