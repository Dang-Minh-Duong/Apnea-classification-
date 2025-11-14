# 🫁 Apnea Classification Using Deep Learning
Deep-learning models for detecting sleep apnea events from audio and PSG-derived features.

## 📌 Introduction
This project implements a complete pipeline for **sleep apnea classification** using audio-based features such as log-Mel spectrograms or MFCCs.  
It is designed to be modular, easy to extend, and optimized for both CNN and RNN training workflows.

The goals of this project are:

- Convert raw audio into time–frequency representations.  
- Build patient-based datasets with correct train/val/test splitting.  
- Train deep learning models (CNN, LSTM, CNN-LSTM, etc.) for multi-class apnea classification.  
- Save processed data to speed up future training and experimentation.
