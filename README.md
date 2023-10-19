

# SMS Spam Classifier

This project aims to build a machine learning model to classify SMS messages as either spam or not spam (ham). The model is trained on a dataset of labeled SMS messages to accurately predict whether a given message is spam or not.

## Table of Contents

- [Introduction](#introduction)
- [image](#image)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Live URL](#liveurl)

## Introduction

The SMS Spam Classifier is a machine learning project developed to help users identify and filter out spam messages from their inbox. It utilizes natural language processing techniques and a classification algorithm to predict whether an incoming SMS message is spam or not. The model's accuracy and performance make it a valuable tool for anyone looking to reduce the clutter in their messaging inbox.

## image
![image](https://github.com/AnalyticalShivam/spam_classifier/assets/93965065/18837d58-0714-45e2-9324-0f500d000f01)


## Installation

To run the SMS Spam Classifier project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/AnalyticalShivam/spam-classifier.git`
2. Install the required dependencies: `pip install -r requirements.txt`

## Usage

After installing the necessary dependencies, run the main script to use the SMS Spam Classifier:

```
app.py
```

This script will prompt the user to input an SMS message and will return whether the message is classified as spam or not.

## Dataset

The SMS Spam Classifier project uses the SMS Spam Collection dataset, which contains a set of SMS messages that have been labeled as either spam or ham. The dataset is preprocessed and split into training and testing sets for model training and evaluation.

## Model

The SMS Spam Classifier employs a machine learning model based on natural language processing techniques and a classification algorithm (Naive Bayes). The model is trained on the labeled dataset to learn patterns and features that distinguish spam messages from legitimate ones.

## Results

The performance of the SMS Spam Classifier is evaluated based on metrics such as precision, recall, and F1 score, because the dataset is imbalanced 

## Live URL
https://spamclassifier-b2btn6csl5kpyct5csq65j.streamlit.app/
