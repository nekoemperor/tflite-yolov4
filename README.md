# TFLite YOLOv4

DISCLAIMER: This repository is very similar to the repository: [tensorflow-yolov4-tflite](https://github.com/theAIGuysCode/tensorflow-yolov4-tflite). I created this repository to add a new feature to be implemented with my custom YOLOv4-tiny model, and they may worsen the overal speed of the application and make it not optimized in respect to time complexity.

The classes of the custom model are: Human Hand, Human Head and Box.
The model name is yolov4-tiny3l-416-opt.tflite on checkpoints folder.

The detector will show us how many objects of each class are being detected and also the "Warning" text if human hand and or human head is detected on the video or live webcam.
