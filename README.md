# PlantPixClassifier

PlantPixClassifier, is a image classification project focused to identifying plant species using advanced deep learning models. This repository compares the performance of three  models: ResNet, EfficientNet, and Vision Transformer, to find out which one does better job at classifying the plant images.


## Dataset

The dataset used in this project is the (House Plant Species)[https://www.kaggle.com/datasets/kacpergregorowicz/house-plant-species ] which images of house plants of 47 different species.


![Plant Images]('images/plant_sample.png')

![Plant Species]('images/class_bar.png')

## Models

The models used in this project are: ResNet, EfficientNet, and Vision Transformer. The models are trained using transfer learning with the pretrained weights from the ImageNet dataset.

## Metrics:

Training and validation loss, top-1 and top-5 accuracy, F1-Score, AUC.

## Results

EfficientNet outperformed ResNet and Vision Transformer in accuracy, F1-Score, and AUC, with the highest top-1 validation accuracy of 93.22% and the lowest validation loss of 0.2398.

### Training and Validation Loss

![Loss]('images/val_top1.png')
![Accuracy]('images/train_top1.png')

### F1-Score

![F1-Score]('images/f1_score.png')

## Prediction on Test Images

![Prediction]('images/predict_test.png')
