
# Emotion and Gender Recognition using Voice

<p align="center">  
<a href="https://"><img src="https://img.shields.io/static/v1?label=librosa&message=Audio+Analysis&color=2ea44f&logo=librosa&logoColor=blue" alt="librosa - Audio Analysis"></a>    
</p>     
      

## Overview

This project aims to create a machine learning model that can identify the emotion and gender of a speaker based on their voice. The model is built using Convolutional Neural Networks (CNNs) and trained on three datasets: CREMA-D, RAVDESS, and TESS. The audio features used to train the model are Mel Frequency Cepstral Coefficients (MFCCs).

## Dataset Description

The three datasets used in this project are as follows:

**CREMA-D**: The Crowdsourced Emotional Multimodal Actors Dataset (CREMA-D) contains audio and video recordings of actors performing emotional scripts. The audio files consist of 12 emotional categories, including neutral, anger, disgust, fear, happy, sad, surprise, and more. There are a total of 7,442 audio files in this dataset.

**RAVDESS**: The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) contains audio and video recordings of actors performing emotional speech and song. The audio files consist of 8 emotional categories, including calm, happy, sad, angry, fearful, surprise, and more. There are a total of 1,440 audio files in this dataset.

**TESS**: The Toronto Emotional Speech Set (TESS) contains audio recordings of actors performing emotional scripts. The audio files consist of 7 emotional categories, including angry, disgusted, fearful, happy, neutral, sad, and surprised. There are a total of 2,940 audio files in this dataset.

## Methodology

The model is built using **Convolutional Neural Networks** **(CNNs)**, which are known for their ability to recognize patterns in data. The audio features used to train the model are **Mel Frequency Cepstral Coefficients (MFCCs)**, which are a commonly used method for extracting audio features.

The audio files are preprocessed to extract MFCCs, which are then used as input to the CNN model. The CNN model is trained using the three datasets mentioned above, and the model is evaluated using cross-validation.

## Results

The model achieved an accuracy of 87% on the validation set, which demonstrates its effectiveness in recognizing emotions and gender from audio.

## Conclusion

In conclusion, this project demonstrates the effectiveness of using CNNs and MFCCs to recognize emotions and gender from audio. The trained model can be used in a variety of applications, such as in virtual assistants or in sentiment analysis of customer reviews.


