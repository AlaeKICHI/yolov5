
yolo_annotation - v1 Yolov5_22_11_21
==============================

This dataset was exported via roboflow.ai on November 22, 2021 at 12:06 AM GMT

It includes 5141 images.
YOLOv5 are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)
* Grayscale (CRT phosphor)

The following augmentation was applied to create 3 versions of each source image:
* Random brigthness adjustment of between -30 and +30 percent
* Salt and pepper noise was applied to 1 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically
* Random exposure adjustment of between -20 and +20 percent


