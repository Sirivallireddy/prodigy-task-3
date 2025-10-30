Task 3 - Cat vs Dog Image Classification using SVM Overview

This project focuses on building an image classification model using a Support Vector Machine (SVM) to distinguish between images of cats and dogs. The dataset used is from Kaggle and contains separate folders for training and testing images. ..Objective To implement an SVM model capable of classifying cat and dog images based on extracted visual features after preprocessing.

Steps Performed Data Loading: Loaded the Kaggle dataset containing training and testing images for both cats and dogs. *Image Preprocessing: Resized images to a fixed dimension (e.g., 64x64). Converted images to grayscale for simplicity. Flattened images into one-dimensional feature vectors suitable for SVM input.

*Feature Extraction and Labeling: Assigned labels to the images — 0 for cats and 1 for dogs.

*Model Training: Trained a Support Vector Machine (SVM) classifier using the processed training data.

*Model Evaluation: Tested the model on the test dataset. Calculated accuracy and displayed the confusion matrix.

*Visualization: Displayed a few test images along with the model’s predicted labels to verify correct classification.

**Results Successfully classified cat and dog images using an SVM model. Displayed sample predictions to visually validate performance. Evaluated the model using accuracy and confusion matrix metrics.
