
emergency-nonemergency-vehicle - v7 2024-03-26 8:24pm
==============================

This dataset was exported via roboflow.com on September 10, 2024 at 9:01 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 2760 images.
Emergency-nonemergency are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Randomly crop between 0 and 21 percent of the image
* Random brigthness adjustment of between -22 and +22 percent
* Random Gaussian blur of between 0 and 2.5 pixels
* Salt and pepper noise was applied to 0.61 percent of pixels


