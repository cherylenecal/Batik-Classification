# Batik Classification

## Introduction
This project focuses on classifying batik images into different categories. Batik is an important part of Indonesian culture, with many kinds, each showcasing unique patterns, colors, and techniques from various regions. Using a dataset of batik images, we used deep learning and image processing techniques to recognize and categorize them based on their visual features. This project aims to aid in understanding and preserving the diversity of batik in Indonesia.
Dataset is sourced from https://www.kaggle.com/datasets/dionisiusdh/indonesian-batik-motifs.

## Methodology
For starters, we chose 3 groups of batik for the model to classify into. 
Data exploration : brightness, noise, image formatting, duplicate data
Data preprocessing : removed duplicate data
Model : CNN with architecture from scratch and CNN with pre-trained (transfer learning) models (EfficientNetB2 and MobileNetV2)

## Conclusion
These models didn't really make a good performance on the dataset, but MobileNetV2 with dropout and batch normalization had a  better performance compared to the other 2 in classifying the batik images, with an accuracy of 0.65
