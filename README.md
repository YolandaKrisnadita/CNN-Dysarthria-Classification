# CNN-Dysarthria-Classification
SIF Foundation AI Project
# This Notebook created for the SIF(Singapore International Foundation) project AI learning program.

## About The Project:
> Dysarthria is a speech disorder caused by motor abnormalities. It is caused by damage or abnormalities in the motor system that controls the parts of the body involved in the speech process, such as the jaw, voice box and tongue. Dysarthria can occur at any age, from children to adults.

## About The Data: 
- The data was downloaded from [Public Domain Dataset Kaggle ](https://www.kaggle.com/datasets/poojag718/dysarthria-and-nondysarthria-speech-dataset?select=data_with_path.csv)
- It's contain's Audio Dataset which only record adult Female and Male who have identification as have dysarthria symptoms and Not have dysarthria symptoms.

## The Problem:
<img width="564" alt="Screenshot 2024-05-01 at 12 33 10" src="https://github.com/YolandaKrisnadita/CNN-Dysarthria-Classification/assets/92908655/9e2edc39-6a80-4335-84e3-002b34a8fafc">

## Conclution
In this project, two models, Random Forest and Assemble CNN, were used to build training models on audio datasets. It was found that Random Forest achieved an accuracy score of 99%, while CNN achieved an accuracy score of 96%. This significant difference in performance can be explained by several factors:

## Audio Dataset Characteristics:

- Audio datasets often have a high level of complexity, with a high variety of sounds and noise. This can make it difficult for CNNs to capture relevant patterns and produce accurate predictions.
- CNNs are designed to capture spatial patterns in data. However, audio datasets may not have a clear spatial structure, so CNNs may not be able to utilize their power to the fullest.
- CNN performance generally improves as the dataset size increases. In this project, the audio dataset used may not be large enough to allow the CNN to achieve optimal performance.

- Random Forest is more reliable in handling complex and unstructured data, such as audio datasets. Its ability to build multiple decision trees allows the model to better capture variation and noise in the data.
- Random Forest models are relatively easy to interpret, allowing us to understand the factors that influence the model's predictions. This can help in identifying potential problems in the dataset or model.

This significant performance difference between Random Forest and CNN on audio datasets is likely due to the characteristics of audio datasets and the strength of the Random Forest model in handling complex data. Random Forest may be more suitable for complex and unstructured audio datasets, while CNN may be more suitable for audio datasets with clear spatial structure and large dataset size.

## Suggestion:

- CNN Model Adjustment: Trying different CNN architectures or adding data augmentation techniques to increase the dataset size.
- Further Investigation: Conduct further analysis on the audio dataset to better understand its characteristics and identify potential issues that may affect CNN performance.
- Ensemble Learning: Considered the use of ensemble learning, where predictions from both models are combined to produce a more accurate final prediction.

By making further adjustments and investigations, it is hoped that the performance of CNN on audio datasets can be improved and approach the performance of Random Forest.
