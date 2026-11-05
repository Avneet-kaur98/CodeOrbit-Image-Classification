# CodeOrbit Internship Project 3: Image Classification using a Pretrained Model

## Overview
Classifies Rock, Paper, and Scissors hand gesture images using transfer learning with pretrained MobileNetV2.

## Tech stack
- Python
- TensorFlow / Keras
- TensorFlow Datasets
- MobileNetV2 (ImageNet pretrained weights)
- Google Colab

## Run
1. Open `CodeOrbit_Image_Classification.ipynb` in Google Colab.
2. Run cells from top to bottom.
3. Optional: select Runtime → Change runtime type → GPU.

## Method
Images are resized to 160×160, preprocessed using MobileNetV2's preprocessing function, and passed through a frozen ImageNet pretrained MobileNetV2 feature extractor. A small dense classification head is trained for the three classes.

## Dataset
Rock Paper Scissors dataset from TensorFlow Datasets. It is automatically downloaded by the notebook.
