# K-Car Classificaiton

## Overview

Classification of Korean Car images using machine learning and deep learning models.
This project is for 2020 Data Creater Camp : Final Round, hosted by NIA(National Information Society Agency). (2020.11.)

- Baseline(ML)
  - Logistic Regression
  - SVM(support vector classifier)
  - Perceptron
- Deep Learning
  - CNN(convolutional neural network)
  - more

## Data

- previous version of [AI-HUB 한국 차량 이미지](https://aihub.or.kr/aidata/13596).
- 24,916 kcar _low size_ images (30\*30\*3 pixel)
- 33 kcar model
- train, test split 8:2<br><br>
  <img alt="avante" src="./data/Hyundai_AvanteMD_2015_10th_H330_V15.JPG" width="100" height="100">&nbsp;
  <img alt="grandeur" src="./data/Hyundai_GarndeurIG_2018_14th_H300_V30.JPG" width="100" height="100">

## Report

| Model               | Accuracy |
| ------------------- | -------- |
| logistic regression | 0.1794   |
| SVM                 | 0.3959   |
| perceptron          | 0.1258   |
