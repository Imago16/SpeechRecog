# Speech Emotion Recognition for Filipino Languages

## Overview

This project is based on a series of Kaggle notebooks that implement a Speech Emotion Recognition (SER) model using a combination of Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. The primary goal is to evaluate the model’s performance on Filipino language speech data to assess its effectiveness in detecting emotions from speech in the Philippines.

### Kaggle Notebooks

The original models were designed and implemented by Rikin Zala and can be found in the following Kaggle notebooks:

1. [Speech Emotion Recognition Model CNN + LSTM - Part 1](https://www.kaggle.com/code/rikinzala/speech-emotion-recognition-model-cnn-lstm-part-1/)
2. [Speech Emotion Recognition Model CNN + LSTM - Part 2](https://www.kaggle.com/code/rikinzala/speech-emotion-recognition-model-cnn-lstm-part-2/)
3. [Speech Emotion Recognition Model CNN + LSTM - Part 3](https://www.kaggle.com/code/rikinzala/speech-emotion-recognition-model-cnn-lstm-part-3/)

### Project Motivation

The main motivation behind this project is to determine whether the model, originally trained on English and other languages, will work effectively on speech data in Filipino. The project aims to:

- Test the model on Filipino speech data.
- Evaluate its accuracy and performance on detecting emotions in a Filipino linguistic context.
- Fine-tune the model to improve performance on Filipino speech data if necessary.

## Model Description

The model consists of two main components:
1. **CNN Layers:** These layers extract important features from the spectrogram of the speech signal.
2. **LSTM Layers:** The LSTM networks capture the sequential information, which is essential for speech emotion recognition as emotions are typically conveyed over time.

The model architecture processes the audio data in the form of spectrograms to recognize patterns that correlate with emotional states like happiness, sadness, anger, and others.

### Data

The original notebooks were trained on datasets such as **Ravdess** and **TESS**, which contain English-language speech with labeled emotions. For this project, we aim to use Filipino speech data to test the model's adaptability to languages and dialects spoken in the Philippines.

## Setup

### Requirements

To replicate and run this project, you will need the following:

- **Python 3.x** (preferably Python 3.7+)
- **Libraries:**
    - `numpy`
    - `pandas`
    - `librosa`
    - `tensorflow` or `keras`
    - `matplotlib`
    - `scikit-learn`
    - `seaborn`
    - `pydub`
  
To install these libraries, you can use:

```bash
pip install numpy pandas librosa tensorflow matplotlib scikit-learn seaborn pydub

