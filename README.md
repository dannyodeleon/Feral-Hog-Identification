# Feral-Hog-Identification
Transfer learning with an object detection model


## Overview 

Feral hogs are out of control 
Object detection is a computer vision technique used to locate and identify one or more objects in an image or video.  Various types of object detection algorithms exist today.  The top-preforming algorithms employ CNNs and Deep Neural Network architecture.  Put a picture here of the models.  

These models can 2 broken up in 2 broad categories:
Two-step Detectors(region proposal based framework)
One-step Detectors(regression based framework)


I choose utilize YOLOV4, a one-step detector, for this project. Though it is not accurate as some of the top preforming two-step detectors, YOLO is much faster and can be run on a single GPU making it more well-suited for real time applications.  

Use cases/Applications 

3 things: 
1. At a high level, outline the basic architectures or maybe just preformance metrics of today's current top-preforming object detectors.
2. Assemble a Yolo V4 object detection model pre-trained on the [Coco Dataset](https://cocodataset.org/#home) with Keras/TF and a GPU in Co-Labs or AWS. 
3. Utilize transfer learning to train this model on a different dataset.  A few I have in mind: 
  - [Deep Fashion 2 Dataset](https://github.com/switchablenorms/DeepFashion2) An incredible dataset for useful for various computer vision tasks. 
  - [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/)
  - [Embrapa Wine Grape Instance Segmentation Dataset](https://github.com/thsant/wgisd) 
  
  Evaluate the model(mAP, speed, CM)
  
 Some stretch goals include: 
  - Real time video objection 
  - Demonstrate an example of an application.
        Social distance detector, unwanted animal notification, there/not there, etc...



The goal of this project is to demonstrate the ability to deploy cutting-edge, scaleable object detection models/algorithms, including tuning/training for a specific application, to quickly create solutions for my team and customers.

## YOLOV4

short history, architecture, features

I chose utilize YOLOV4, a one-step detector, for this project. Though it is not accurate as some of the top preforming two-step detectors, YOLO is much faster and can be run on a single GPU making it more well-suited for real time applications.  

## Transfer Learning  



## Summary and Next Steps


## Acknowlegements/References
