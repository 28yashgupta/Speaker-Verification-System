# Speaker-Verification-System
# 🚀 Overview

This project implements a real-time speaker verification system that classifies incoming audio as either the target speaker or a non-target speaker. The system takes a reference audio recording of a target speaker, extracts relevant audio features, and uses a machine learning model to verify if the incoming audio matches the target speaker.

# 🎯Features

- ✅ Real-time audio classification
- 🎼 Feature extraction using MFCCs
- 🤖 Machine learning-based speaker verification
- 📊 Evaluation using accuracy, F1-score, and other relevant metrics

# 🗂 Dataset

- The dataset consists of audio recordings of the various speakers. 
- Dataset Link: https://www.kaggle.com/datasets/vjcalling/speaker-recognition-audio-dataset

# 🛠️ Approach

1️⃣ Data Preprocessing & Feature Extraction
- 🎙️ Collected audio recordings of the target speaker and non-target speakers.
- 🔄 Preprocessed audio by normalizing and resampling.
- 🔍 Extracted Mel-Frequency Cepstral Coefficients (MFCCs) as key features for classification.

2️⃣ Model Development & Training
- 🏗️ Used a Convolutional Neural Network (CNN) for speaker verification.
- 🎯 Trained on extracted MFCC features using a labeled dataset.
- 🔧 Fine-tuned hyperparameters and optimized the model for better performance.

3️⃣ Real-Time Classification

- 🎤 Captured real-time audio using a microphone.
- 📈 Extracted MFCC features and passed them through the trained model.
- 🏷️ Classified the audio as either the target speaker or a non-target speaker.

4️⃣ Evaluation
- 📊 Evaluated the model using accuracy, precision, recall, and F1-score.
- 🧪 Tested the system with unseen speakers to assess generalization.

# 📊 Results

- ✅ Achieved 90%+ accuracy on a validation set.

# 🔮 Future Improvements

- 🚀 Implement transformer-based models for better speaker verification.
- 📱 Optimize real-time inference for mobile deployment.
