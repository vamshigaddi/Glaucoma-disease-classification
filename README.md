# Glaucoma-disease-classification
## Overview
This repository contains the source code and documentation for a deep learning-based project aimed at detecting glaucoma from retinal fundus images. The project utilizes Pretrained model to analyze retinal images and classify them as either indicating the presence of "Referable Glaucoma" (RG) and "No Referable Glaucoma" (NRG) .

# Project Structure:
## Task Definition:

Binary classification of glaucoma images into RG and NRG categories. 
## Dataset:

Utilize the glaucoma dataset sourced from Kaggle.
dataset link: [https://www.kaggle.com/datasets/deathtrooper/eyepacs-airogs-light/data?select=release-crop]
## Model:

Implemented the Xception pre-trained model for image classification.
## Dependencies:
```bash
pip install requirements.txt
```
## Preprocessing:

Normalize and resize images for model input.
## Data Augmentation:

Apply augmentation techniques to enhance dataset diversity.
## Model Training:

Fine-tuned the Xception model on the training dataset.
## Evaluation:

Assess model performance using the test dataset and calculated test accuracy.

## Conclusion:
The Glaucoma Classification Project demonstrates the potential of deep learning in accurately diagnosing glaucoma from retinal images. By leveraging pre-trained models, data augmentation, and rigorous evaluation, the project achieves high test accuracy of 93%, contributing to the advancement of glaucoma diagnosis and treatment


