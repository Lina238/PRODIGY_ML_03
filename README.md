# Cat vs Dog Image Classifier

## Overview
This project implements a machine learning model to classify images of cats and dogs using Support Vector Machine (SVM) and Histogram of Oriented Gradients (HOG) features.
## How it works
1. The script loads images from the specified directories.
2. Each image is converted to grayscale and resized to 64x64 pixels.
3. HOG features are extracted from each image.
4. The dataset is split into training and testing sets.
5. An SVM model is trained on the feature set.
6. The model's performance is evaluated using accuracy score and classification report.
