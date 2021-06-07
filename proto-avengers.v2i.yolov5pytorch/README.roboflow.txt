
proto-avengers - v2 2021-06-07 4:32pm
==============================

This dataset was exported via roboflow.ai on June 7, 2021 at 2:02 PM GMT

It includes 477 images.
Labels are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random rotation of between -25 and +25 degrees
* Random shear of between -45° to +45° horizontally and -45° to +45° vertically
* Random brigthness adjustment of between -27 and +27 percent


