
filtered_images_Atos - v1 2021-12-04 5:41pm
==============================

This dataset was exported via roboflow.ai on December 4, 2021 at 4:43 PM GMT

It includes 683 images.
Yolov5 are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Salt and pepper noise was applied to 1 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 20 percent of the bounding box
* Random brigthness adjustment of between -25 and +25 percent
* Random Gaussian blur of between 0 and 10 pixels
* Salt and pepper noise was applied to 1 percent of pixels


