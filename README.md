# Speech Emotion Recognition using RAVDESS Dataset 🎙️😃😢😡

This project is a **Speech Emotion Recognition (SER)** system that uses machine learning and audio signal processing techniques to classify emotions from speech audio. It leverages the **RAVDESS dataset**, and includes preprocessing using `librosa`, followed by training a deep learning model for emotion classification.

## 🔍 Overview

- **Dataset**: [RAVDESS](https://zenodo.org/record/1188976)
- **Audio Preprocessing**: Feature extraction using `librosa` (MFCCs, Chroma, Mel spectrogram, etc.)
- **Model Architecture**: Deep learning model (likely CNN/LSTM-based) built using TensorFlow/Keras
- **Emotions Detected**: Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, Surprised

---

## 📁 Project Structure

```bash
├── app.ipynb         # Preprocessing script: loading audio, feature extraction using librosa
├── model.ipynb       # Model training: defining, compiling, and training the deep learning model
├── README.md         # Project overview and instructions (this file)
