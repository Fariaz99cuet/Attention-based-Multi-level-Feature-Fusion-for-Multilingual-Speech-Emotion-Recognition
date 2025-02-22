Attention-based Multi-level Feature Fusion for Multilingual Speech Emotion Recognition

Overview

Speech Emotion Recognition (SER) is an essential component of human-computer interaction, enabling machines to detect emotions from speech. Traditional models often struggle to generalize effectively across multiple languages and datasets. This repository provides the official implementation of our hybrid model that integrates Convolutional Neural Networks (CNN) with a multi-head attention Transformer to enhance SER accuracy.

Model Architecture

Our model extracts both low- and high-level speech features, including:

Zero-Crossing Rate (ZCR)

Mel-Frequency Cepstral Coefficients (MFCC)

Root Mean Square Energy

By capturing both local and global relationships in speech, our approach effectively identifies complex emotions.

Datasets Used

The proposed model was trained and evaluated on five benchmark datasets:

TESS

RAVDESS

SUBESCO

SAVEE

CREMA-D

Performance

The model achieved an average accuracy of 96% across these datasets, outperforming existing SER models, especially in recognizing challenging emotions like "Angry" and "Disgust."

Dataset

Accuracy

TESS

96.5%

RAVDESS

95.8%

SUBESCO

96.2%

SAVEE

96.1%

CREMA-D

95.9%
