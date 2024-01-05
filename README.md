# Fake News Detection with CNNs and LSTMs

## Overview

This project focuses on fake news detection using a hybrid approach of Convolutional Neural Networks (CNNs) and Long Short-Term Memory networks (LSTMs). The objective is to create a robust model capable of distinguishing between genuine and fake news based on textual content.

## Implementation Steps

### 1. Data Preprocessing

- **Data Cleaning:**
  - Imputation and removal of missing values.
  - Elimination of stopwords and lemmatization.

### 2. Feature Engineering

- **TF-IDF Transformation:**
  - Application of Term Frequency-Inverse Document Frequency (TF-IDF) to transform text data.
  - Removal of low-value words to reduce dimensionality.
![image](https://github.com/DuyAccel/fakenews-detection-with-hybrid-CNN-LSTM/assets/84909478/6e824253-d6b0-4245-8892-5d58d77d0fbb)

### 3. Word Embedding

- **Embedding Text Data:**
  - Utilization of word embedding techniques for continuous vector representation.

### 4. Convolutional Neural Networks (CNNs)

- **Extracting Features with 1D Convolution:**
  - Application of a one-dimensional convolutional layer to extract relevant features.

### 5. Long Short-Term Memory networks (LSTMs)

- **Sequence Processing with LSTMs:**
  - Integration of LSTM units to handle sequential dependencies and contextual understanding.

### 6. Model Evaluation
- **Training step:**
![image](https://github.com/DuyAccel/fakenews-detection-with-hybrid-CNN-LSTM/assets/84909478/31c82ce5-61c3-4130-b1ea-c68972ba9d79)

- **Performance Evaluation on Test Set:**
  - Model evaluation on a test set yields exceptional results.
  - **Accuracy:** Approximately 97.5%
  - **Precision:** Approximately 96.8%
  - **Recall:** Approximately 98.2%
![image](https://github.com/DuyAccel/fakenews-detection-with-hybrid-CNN-LSTM/assets/84909478/e411bd3e-6c7d-43ce-9af5-8a058b487610)

## Conclusion

The hybrid CNN-LSTM model demonstrates remarkable efficiency in detecting fake news, achieving consistently high scores across accuracy, precision, and recall metrics. The robustness of the model suggests its potential for real-world applications in identifying and combatting the spread of misinformation.

