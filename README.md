# Feral-Hog-Identification
Transfer learning with an object detection model


## Overview 

![pigs]

Feral pigs(a.k.a feral hogs, wild hogs, feral swine, razorbacks) are out of control.  In recent decades, feral pig numbers have grown to unmanagable level, particularly in Texas.  They are widely considered to be the most destructive invasive species in the United States.  Feral hogs cause tremndous damage to crops, livestock, waterways, native plants, wildlife, and local eco-systems.  Their annual damage is estimated to be around 1.5 billion dollars annually.  2.6 million feral pigs reside in Texas, accounting for half of the total US population.  That population is exploding at an estimated 20% growth rate.  Mitigation and control efforts at the Federal, State, and local levels has proved the issue to extrememely challenging. Farmers spend millions in efforts to protect their business and property from feral pigs.  It's not unheard of to lose 10s of thousands of dollars in a single night due to the feral pigs destruction.  As AI and embedded device technologies mature and become more affordable, there is an opportunity to provide relief to those affected by feral pigs.      

# Object Detection  

Object detection is a computer vision technique used to locate and identify one or more objects in an image or video.  Object detection combines object localization and classification.  Whereas classification and localization works for only one object in a frame.  Object detection works for mulitple objects as well as multiple instances of an object in a given image.  Various types of object detection algorithms exist today.  The top-preforming algorithms employ CNNs and Deep Neural Network architecture.       

These models can 2 broken up in 2 broad categories:

 1)Two-stage Detectors(region proposal based framework)
    More accurate than one-stage detectors.
   
 2)One-step Detectors(regression based framework)
    More suitable for real-time applications as they are much faster and less computationally expensive than two-stage detectors. 
    
![Yolo diagram]()
I chose to utilize YOLOv4, a one-step detector, for this project. Though it is not accurate as some of the top preforming two-stage detectors, YOLO is much faster and can be run on a single GPU making it more well-suited for real time applications.  



  
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
