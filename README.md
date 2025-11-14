# Apnea Classification Using Deep Learning (TensorFlow & ESP32-S3 Deployment)
Deep-learning models for detecting sleep apnea events from audio and PSG-derived features.

## Introduction
This project implements a complete pipeline for **sleep apnea classification** using audio-based features such as log-Mel spectrograms or MFCCs.  
It is designed to be modular, easy to extend, and optimized for both CNN and RNN training workflows.

The goals of this project are:

- Convert raw audio into time–frequency representations.  
- Build patient-based datasets with correct train/val/test splitting.  
- Train deep learning models (CNN, LSTM, CNN-LSTM, etc.) for multi-class apnea classification.  
- Save processed data to speed up future training and experimentation.
- Deploying the Model on ESP32-S3 (TensorFlow Lite Micro)
## Dataset
- Raw data: https://www.kaggle.com/datasets/bryandarquea/psg-audio-apnea-audios
- Preprocessed Data Blocks: https://drive.google.com/drive/folders/1gB85M_46lLmz2ijb7appVILrFo5nXK88?usp=drive_link
