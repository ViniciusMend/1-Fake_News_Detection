# Fake News Detector
<img src="images/fake-news.png"
     alt="Fake News Image"
     style="width: 50%; height: 50%" />

Fake news encapsulates pieces of news that may be hoaxes and is generally spread through social media and other online media. Such news items may contain false and/or exaggerated claims, and may end up being viralized by algorithms, and users may end up in a filter bubble.

## :bulb: Motivation
This project aims to use Natural Language Processing (NLP) using TfidfVectorizer and Passive Aggressive Classifier to detect fake news directly, based on the text content of news articles.

## :pencil2: Objectives
1. To design and develop a machine learning based fake news detection system
2. To validate the effectiveness of a machine learning based fake news detection system

## :speech_balloon: Dataset Overview

- news.csv: A full training dataset with the following attributes:
    - title: the title of the article
    - text: the text of the article
    - label: a label that marks the article is fake or real
        - 1: Fake news
        - 0: Real News 

Dataset Source: 
1. [news.csv](https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view)

## :dart: Model Training Results
The Passive-Aggressive model trained in this project was able to get the accuracy score as below:

Accuracy: **93.72%**