# Sound Classification using a Custom Architecture

This project focuses on classifying 10 different urban sounds using a custom architecture. The classification task is performed on the UrbanSound 8k dataset, which consists of 8,732 labeled sound excerpts of urban sounds from 10 classes. The goal is to accurately classify the sound excerpts into the following classes: air conditioner, car horn, children playing, dog bark, drilling, engine idling, gun shot, jackhammer, siren, and street music.

## Problem Statement
The problem at hand is sound classification, which falls under the category of supervised machine learning algorithms. The objective is to develop a model that can accurately classify the input sound excerpts into their respective classes.

## Model Architecture
The model used for sound classification is a custom architecture based on a four-layer deep convolutional neural network (CNN). This architecture is specifically designed to handle signal-based datasets, such as audio waveforms. The CNN layers are responsible for extracting meaningful features from the input audio data, and the subsequent layers perform the classification based on these extracted features.

## Results and Discussion
The model was trained on the UrbanSound 8k dataset, and the following results were achieved:

## Training Accuracy: 72%
Validation Accuracy: 68% after 10 epochs
The achieved accuracy demonstrates the model's ability to classify urban sounds, but there is room for improvement. It is worth noting that achieving high accuracy in sound classification tasks can be challenging due to the complexity and variability of audio data.

## Challenges Faced
One of the challenges encountered during the project was dealing with stereo soundtracks in the UrbanSound 8k dataset. To address this issue, the team used the Librosa library, which provides audio analysis and manipulation capabilities. Librosa was employed to convert the stereo soundtracks into mono, ensuring compatibility with the model's architecture and consistent processing of the audio data.

## Repository
For the complete implementation of the sound classification project, including the source code, documentation, and additional resources, please refer to the project's GitHub repository. You can find the repository by searching relevant keywords such as the project title or the team's name. The repository contains the necessary information to reproduce the results and further explore the project.

Please note that the repository may also include additional details on data preprocessing, model training, evaluation metrics, and any other relevant information related to the project.

## Conclusion
Sound classification is a challenging task that requires specialized architectures and techniques to extract meaningful features from audio waveforms. Although the custom architecture used in this project achieved a reasonable accuracy on the UrbanSound 8k dataset, further improvements can be made to enhance the classification performance.

The team successfully addressed the challenge of stereo soundtracks by utilizing the Librosa library to convert them into mono. This allowed for consistent processing and classification of the audio data.

By referring to the project's GitHub repository, you can delve into the implementation details and explore the code to gain a better understanding of the sound classification process.
