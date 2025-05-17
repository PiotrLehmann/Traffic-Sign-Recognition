# Traffic-Sign-Recognition
#### Whole Presentation of this project can be found and viewed in this repository, in [➡️ Presentation.pdf](Presentation.pdf)

## Example of Hybrid Model prediction:

<img src="https://github.com/PiotrLehmann/Traffic-Sign-Recognition/blob/72abdb9a744a916123db88c80fbb09b883917a6b/Example.png" width="1000">

## Short Description
This project implements a machine learning system for traffic sign detection and recognition. **It is designed for the detection and classification of traffic signs visible in images taken while driving**. The system serves as a simplified version of the traffic sign recognition technology used in modern vehicles.

Code contains full implementation of Hybrid model consisting of:
- Dataset augmentation and balancing
- Detection of traffic sign using yolo v8, which at the moment of creating project was the newest model of yolo. However this model was used ONLY for detection, not for prediction
- Cropping square images of detected sign/signs and adjusting its size for next model
- Classification of detected signs using Convolutional Neural Network of my design

So the whole Hybrid Model is working like:
(detection with yolo v8) -> (cropping) -> (classification with CNN)

## This repository contains two Jupyter notebooks:
- [➡️ Testing_all_created_models.ipynb](Testing_all_created_models.ipynb) The first notebook is dedicated to experiments on training the model, testing various dataset configurations
- [➡️ Full-hybrid-model-wrapper.ipynb](full-hybrid-model-wrapper.ipynb) The second notebook contains the final version with the best-performing detection model and classification model, combined into a hybrid wrapper
NOTE: I recommend using those files on kaggle with your own Datsets, or even better would be using my kaggle

## Kaggle projects You can use
- [https://www.kaggle.com/code/piotrlehmannml/all-possible-models-testing-in-traffic-sign-det](https://www.kaggle.com/code/piotrlehmannml/all-possible-models-testing-in-traffic-sign-det)
- [https://www.kaggle.com/code/piotrlehmannml/full-hybrid-model-wrapper](https://www.kaggle.com/code/piotrlehmannml/full-hybrid-model-wrapper)

## Datasets download links:
- [Final test dataset (Edited dashcam footage of a friend)](https://www.kaggle.com/datasets/piotrlehmannml/final-test)
- [Polish Traffic Signs Dataset (Cropped)](https://www.kaggle.com/datasets/kasia12345/polish-traffic-signs-dataset)
- [Polish Traffic Sings Dataset (Whole Photos)](https://www.kaggle.com/datasets/chriskjm/polish-traffic-signs-dataset)
- [Signs in Yolo format (For detection)](https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-dataset-in-yolo-format)




