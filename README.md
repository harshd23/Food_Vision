# FOOD VISION:
---
## Introduction:
Food Vision is a simple project which uses Machine Learning algorithms to train the computer to classify 101 classes of food items. The dataset is available from the [TensorFlow](https://www.tensorflow.org/datasets/catalog/food101) datasets library. Also, the dataset can be found on [Kaggle](https://www.kaggle.com/datasets/kmader/food41).The goal is to be able to automatically classify an unknown image using the dataset. The model created in this project was using transfer learning algorithm. The model used for Food Vision project was **Efficient Net B0.**

## Features of Food Vision:
* Mixed Precision
* Feature Extraction
* Fine Tuning
* Batching & Prefetching Datasets
* ModelCheckpoint callback
* EarlyStopping callback
* ReduceLROnPlateau callback
* TensorBoard callback

## Model Training curves using TensorBoard:
![Different Models](https://i.imgur.com/N8AE7xQ.png)
![Epoch Accuracy](https://i.imgur.com/k7G8YiI.png)
![Epoch Loss](https://i.imgur.com/RcncckD.png)

## Resources:
* [DeepFood Paper](https://arxiv.org/abs/1606.05675)
## Conclusion: 
The model is able to perform great achieving the accuracy of about **79.79%.**