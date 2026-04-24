# final-term-deep-learning-52300090-52300100-52300128
#1. Introduction

This repository presents the final project for the course Deep Learning. The project consists of two main components:

Task 1: Development of a Vietnamese Visual Question Answering (VQA) system.
Task 2: Proposal and implementation of a deep learning-based solution for a selected problem.

#2. Task 1: Visual Question Answering (VQA)
   
2.1 Problem Description

The objective of this task is to build a Visual Question Answering system in Vietnamese. The system takes an image and a corresponding natural language question as input, and generates a short textual answer.

2.2 Methodology

Two main approaches are implemented:

Approach A: Modular Architecture
Image Encoder: Convolutional Neural Networks (e.g., ResNet, EfficientNet)
Text Encoder: LSTM-based models or pretrained language models (e.g., PhoBERT)
Fusion Mechanism: Feature concatenation or other multimodal fusion techniques
Answer Decoder:
LSTM-based decoder
Transformer-based decoder

A comparative analysis is conducted between LSTM and Transformer decoders while keeping the encoders unchanged.

Approach B: Multimodal Pretrained Models
Fine-tuning state-of-the-art multimodal models such as BLIP or ViLT
Consideration of Vietnamese language handling strategies (direct input or translation-based approaches)
2.3 Evaluation Metrics

The system is evaluated using multiple metrics:

VQA Accuracy
BLEU, ROUGE-L, METEOR
BERTScore

#3. Task 2: Galaxy Classification and AGN Detection

3.1 Problem Description

This task focuses on the classification of galaxy images and the identification of galaxies containing Active Galactic Nuclei (AGN). The objective is to leverage deep learning techniques to extract visual patterns associated with different galaxy morphologies and AGN characteristics.

3.2 Dataset

The experiments are conducted on the Galaxy10 DECals dataset, which contains labeled images of galaxies across multiple categories.

3.3 Methodology

The proposed pipeline includes the following steps:

Image preprocessing (normalization and data augmentation)
Feature extraction using convolutional neural networks
Classification into predefined galaxy categories

Two model configurations are implemented:

Baseline model: A custom Convolutional Neural Network
Improved model: EfficientNet-B0 with transfer learning
3.4 Evaluation

Model performance is assessed using:

Accuracy
F1-score
3.5 Model Interpretation

To improve interpretability, Grad-CAM is applied to visualize the regions of the input images that contribute most to the model's predictions.

3.6 Demonstration

A simple demonstration system is developed, allowing users to upload an image and receive a predicted galaxy class.
