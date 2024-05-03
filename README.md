# Modern Approaches in Natural Language Processing: Word Embedding and Sentiment Analysis on VLSP dataset

This repository contains the research and implementation for the sentiment analysis study conducted as part of the course "Modern Approaches in Natural Language Processing" at Ho Chi Minh City University of Technology (HCMUT), Faculty of Computer Science and Engineering.

## Description
After utilizing Continuous Bag of Words (CBOW) for word embedding, I conducted sentiment analysis experiments employing CNN, LSTM, and a hybrid CNN-LSTM model. Subsequently, I refined these methods to enhance sentiment discernment.
## Overview

The study focuses on various deep learning models for sentiment analysis in the Vietnamese language, utilizing the VLSP 2016 dataset. Models explored include:
- Continuous Bag of Words (CBOW) for word embedding
- Long Short-Term Memory (LSTM)
- Convolutional Neural Network (CNN)
- Convolutional Recurrent Neural Network (CRNN)
- Gated Recurrent Unit (GRU)

## Dataset

The VLSP 2016 dataset used in this study is divided into training and testing subsets, containing sentiment classifications across different emotional states.

## Preprocessing

Data preprocessing steps include:
- URL removal
- Emoticon text conversion
- Stopword removal
- Text normalization (lowercasing, special character removal)
- Whitespace reduction

## Models

This section includes a brief overview of each model's architecture and its role in sentiment analysis. Detailed model descriptions are provided in the respective source code files within this repository.

## Results

Performance of the models is evaluated based on Accuracy, Precision, Recall, and F1-Score. The CRNN model showed the most promising results in terms of overall accuracy and balance between precision and recall.

## Installation

Instructions on how to set up the project environment and run the models are provided below:

```bash
# Clone the repository
git clone [URL to Repository]
cd [Repository Name]

# Install dependencies
pip install -r requirements.txt

# Run the models
python run_models.py
