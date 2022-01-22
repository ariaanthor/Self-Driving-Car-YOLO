# Self-Driving-Car-YOLO
I Used a darknet model trained on the COCO dataset to detect objects in images and in a video of color footage from a self-driving car.
Open the colab notebook. This will create a copy of the notebook. Feel free to change and send me any findings and requests.

## What is YOLO?
The “You Only Look Once,” or YOLO, family of models are a series of end-to-end deep learning models designed for fast object detection, developed by Joseph Redmon, et al. and first proposed in the 2015 paper titled “You Only Look Once: Unified, Real-Time Object Detection.” The model has been updated since then. The model that I used was YOLOv3.

YOLO uses a single deep convolutional neural network called DarkNet that splits the input into a grid of cells. Each cell directly predicts a bounding box and object classification. The result is a large number of candidate bounding boxes that are consolidated into a final prediction by a post-processing step.

In summary, to make object detection on one input image, the first step is a forward pass of the DarkNet; the second step is the post-processing on the DarkNet output to get the final bounding boxes prediction.
