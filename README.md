# Breast Cancer Tumor Detection Model

## Background

Breast Cancer is the most common type of cancer; in 2020, more than 2.6 million women were diagnosed worldwide, and 685 million women died. According to stats in the same year, every 14 seconds, somewhere in the world, a woman is diagnosed with breast cancer.
I aim to create an AI prediction model by using data from previous diagnoses in
Wisconsin.

## Data

This dataset was computed from a digitized image of a fine needle aspirate of a breast mass viewed by a robotic microscope, resulting in 30 features that characterize the cell nuclei image. These features can help researchers answer many questions like predicting the breast cancer, diagnosing if it is a benign or malignant tumor, and more.
These are some example features:   

## Pre-processing
For pre-processing, I deleted the 'ID' and the 'Unnamed: 32' columns as I didn’t need the ID column for my model and the 'Unnamed: 32' as it was all null values I could not use. I also detected and eliminated the outliers.

I had two diagnosis values called malignant and benign; I rearranged them by changing their values to 1 and 0.

## Model / Algorithm
I used logistic regression, SVM, and random forest algorithms to train my data. I picked the model that trained with logistic regression, which had the highest accuracy.


## Evaluation
My logistic regression model was %98 accurate at classifying if the patient has a malignant(cancerous) or benign tumor(not cancerous).

## Acknowledgements
My mentor and the AI4All Community greatly supported this research; much thanks for contributing to this project’s progress.
