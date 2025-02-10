Please check our paper [Wearable Sensor-Based Human Activity Recognition with Transformer Model](https://www.mdpi.com/1424-8220/22/5/1911) for more details.

![Tag](https://img.shields.io/github/v/tag/markub3327/HAR-Transformer)
[![Issues](https://img.shields.io/github/issues/markub3327/HAR-Transformer)](https://github.com/markub3327/HAR-Transformer/issues)
![Commits](https://img.shields.io/github/commit-activity/w/markub3327/HAR-Transformer)
![Size](https://img.shields.io/github/repo-size/markub3327/HAR-Transformer)

## Description

The Transformer for Human Activity Recognition operates in sequence-to-sequence mode and predicts the class for each time series feature. The advantage is that if there are several consecutive classes in one time series, these classes can be easily identified, and the transformer is not limited to the features in the whole time series belonging to one class. 

## Dataset

[KU-HAR](https://www.kaggle.com/datasets/niloy333/kuhar?resource=download)

## Model

<p align="center">
  <img src="model.png" style="background-color: white;">
</p>


**Dependencies:** TensorFlow, NumPy, Pandas, Scikit-learn, WanDB

---

Work originally done by: https://github.com/markub3327/HAR-Transformer
