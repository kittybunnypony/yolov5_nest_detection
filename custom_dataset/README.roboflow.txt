
nest - v2 Nest detection_new
==============================

This dataset was exported via roboflow.ai on April 16, 2022 at 2:33 AM GMT

It includes 234 images.
Nest are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise
* Random rotation of between -30 and +30 degrees
* Salt and pepper noise was applied to 5 percent of pixels


