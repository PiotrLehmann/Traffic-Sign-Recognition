# Traffic-Sign-Recognition

## Short Description
This project implements a machine learning system for traffic sign detection and recognition. **It is designed for the detection and classification of traffic signs visible in images taken while driving**. The system serves as a simplified version of the traffic sign recognition technology used in modern vehicles.

## More Specificly
This code contains full implementation of Hybrid model consisting of:
- Dataset augmentation and balancing
- Detection of traffic sign using yolo v8, which at the moment of creating project was the newest model of yolo. However this model was used ONLY for detection, not for prediction
- Cropping square images of detected sign/signs and adjusting its size for next model
- Classification of detected signs using Convolutional Neural Network of my design

So the whole Hybrid Model is working like:
(detection with yolo v8) -> (cropping) -> (classification with CNN)

## Example of Hybrid Model prediction:

