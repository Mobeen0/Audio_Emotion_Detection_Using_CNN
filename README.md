# Audio Emotion Detection CNN Model

This project implements a Convolutional Neural Network (CNN) for detecting emotions in audio samples using the RAVDESS and SURREY datasets.

## Table of Contents
- [Overview](#overview)
- [Datasets](#datasets)
- [Requirements](#requirements)
- [License](#license)

## Overview

This CNN model is designed to classify emotions from audio inputs into 8 categories. It leverages the power of deep learning to extract features from audio spectrograms and predict the corresponding emotion.

## Datasets

The model is trained on two popular emotional speech datasets:

1. **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)**: 
   - 24 professional actors (12 female, 12 male)
   - 8 emotions: calm, happy, sad, angry, fearful, surprise, disgust and neutral

2. **SURREY Audio-Visual Expressed Emotion (SAVEE) Database**:
   - 4 male actors
   - 7 emotions: anger, disgust, fear, happiness, sadness, surprise, and neutral

## Requirements

- Python
- TensorFlow
- keras
- Librosa
- Pandas
- Numpy
- Matplotlib
- sk-learn
- joblib

## Usage

1. Clone the repository: git clone https://github.com/Mobeen0/Audio_Emotion_Detection_Using_CNN
