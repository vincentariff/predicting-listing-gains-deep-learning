# Predicting Listing Gains Deep Learning

## Table of Contents

* [Introduction](https://github.com/vincentariff/predicting-listing-gains-deep-learning#introduction)
* [Dataset](https://github.com/vincentariff/predicting-listing-gains-deep-learning#dataset)
* [Requirements](https://github.com/vincentariff/predicting-listing-gains-deep-learning#requirements)
* [Installation](https://github.com/vincentariff/predicting-listing-gains-deep-learning#installation)
* [License](https://github.com/vincentariff/predicting-listing-gains-deep-learning#license)

## Introduction

* In this project, we have built Deep Learning Classification model using the deep learning framework, Keras, in TensorFlow. We used a real-world IPO dataset and built a classifier algorithm to predict whether an IPO will list at profit or not.

* Our model predicts listing gains in the Indian IPO market with an accuracy of 71%. We trained it using six key features, handling outliers with the IQR boxplot method, scaling values between 0 and 1, and splitting the data 70-30 for training and testing. Built with TensorFlow's Functional API, the model has four hidden layers (starting at 128 nodes, "relu" activation, ending with "sigmoid"), two dropout layers to address overfitting, and uses the Adam optimizer with a learning rate of 0.01, binary cross-entropy loss, and accuracy as the evaluation metric over 150 epochs.

## Dataset

* The dataset we will use is sourced from [moneycontrol](https://www.moneycontrol.com/ipo/listed-ipos/) and contains historical data on past IPOs in India.

## Requirements

* All libraries and dependencies are listed in the `requirements.txt` file.

## Installation

Clone the repository:
 ```
git clone https://github.com/vincentariff/predicting-listing-gains-deep-learning.git
```

Install dependencies:
```
pip install -r requirements.txt
```

## License

* This project is licensed under the MIT License, detailed in the `license.txt` file.
