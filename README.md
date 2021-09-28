# Tensorflow-Object-Detection

This model will help to detect sign languages using Tensorflow Object Detection model.

Here we have two files
1. Image Collection: This is where we collect the images and label it using the PyQt5 library. After labelling we try to split it into training and test data sets.
2. Training and Detection: 
    2.1: Download TF Models Pretrained Models from Tensorflow Model Zoo and Install TFOD.
    2.2: Installing CUDA and CuDNN.
    2.3: Downloading the tf2 zoo model from website i.e SSD MobileNet V2 FPNLite 320x320.
    2.4: Training and evaluation of the model.
    2.5: Testing using existing image or real time image capture using webcam.

Tensorboard - GUI for interactive monitoring tool

This is the LOSS GRAPH as obtained from the training model:

![Capture](https://user-images.githubusercontent.com/17869716/134928176-6ac653bc-73b0-4be2-8502-10c50900230b.PNG)
![Capture1](https://user-images.githubusercontent.com/17869716/134928179-d5414ad9-0bf8-4f00-8b5c-67cdc5308b31.PNG)

These are the EVALUATION RESULTS as obtained from the training model:

![individualImage (1)](https://user-images.githubusercontent.com/17869716/134931103-c26601af-d088-4ded-b0be-9dfcfe3e9781.png)
![individualImage (2)](https://user-images.githubusercontent.com/17869716/134931123-3a7067ac-9bb3-4c99-be7d-a32a01c8921e.png)
![individualImage (3)](https://user-images.githubusercontent.com/17869716/134931128-2527cefc-f109-46f8-80de-a3747fe5f6ad.png)
![individualImage](https://user-images.githubusercontent.com/17869716/134931132-45e7007b-ec72-465d-ae90-3dffc1fea75f.png)

This is the TEST RESULT obtained from existing image:

![test-result](https://user-images.githubusercontent.com/17869716/134928242-e89510cc-f47b-4494-97f0-e2e47f3f8ffa.PNG)

Use of performance tuning to help in better real time object detection using webcam.

Here are the steps for performance tuning:

1. Add more images for training
2. Increase the step size
3. Change the architecture


Libraries Used:
1. opencv-python
2. PyQt5
3. tensorflow
4. matplotlib
5. pyyaml
6. tensorboard                   
7. object-detection


URLs used:
1. https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md
2. https://developer.nvidia.com

Credits: https://www.youtube.com/channel/UCHXa4OpASJEwrHrLeIzw7Yg
