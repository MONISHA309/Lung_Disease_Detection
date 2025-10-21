#  UTILIZING NEURAL NETWORKS TO ANALYZE RESPIRATORY SOUNDS FOR THE DETECTION OF LUNG DISEASES

This repository contains a deep learning model for classifying respiratory sounds into different disease categories. The model uses a combination of convolutional neural networks (CNNs) and recurrent neural networks (RNNs) to extract features from audio recordings of respiratory sounds.

## Dataset

The dataset used for this project is the Respiratory Sound Database, which contains audio recordings of respiratory sounds from patients with various respiratory diseases.

## Model Architecture

The model consists of three main components:

  1. MFCC Model: This model extracts Mel-Frequency Cepstral Coefficients (MFCCs) from the audio recordings and uses a CNN to classify the sounds.
  2. CSTFT Model: This model extracts Constant-Q Transform (CQT) features from the audio recordings and uses a CNN to classify the sounds.
  3. MSPEC Model: This model extracts Mel-Spectrogram features from the audio recordings and uses a CNN to classify the sounds.
The outputs of these three models are concatenated and fed into a fully connected neural network to produce the final classification.

## Training

The model was trained on a dataset of 6898 audio recordings, with 5173 recordings used for training and 1725 recordings used for testing. The model was trained for 53 epochs with a batch size of 32.

## Results

The model achieved an accuracy of 90.49% on the test set.

