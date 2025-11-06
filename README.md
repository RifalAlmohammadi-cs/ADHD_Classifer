# ADHD_Classifer
🧠 Drawings-Based ADHD Screening System Using Deep Learning

A deep learning–based system designed to assist in screening ADHD (Attention Deficit Hyperactivity Disorder) by analyzing drawings created by children.
This project leverages ResNet-18 architecture implemented in PyTorch to classify or assess behavioral patterns in drawings that may correlate with ADHD tendencies.

🚀 Features

Uses ResNet-18, a pre-trained CNN model fine-tuned on custom drawing datasets.

Classifies between ADHD and Non-ADHD categories (binary classification).

Built using PyTorch for flexibility and GPU acceleration.

Includes full data preprocessing and augmentation pipeline.

Provides detailed metrics (Accuracy, F1-score, Confusion Matrix).

🧠 Model Details

Base architecture: ResNet-18 (pretrained on ImageNet)

Optimizer: Adam

Loss: CrossEntropyLoss

Learning Rate: 0.001 (with ReduceLROnPlateau)

Batch Size: 32

Number of Epoch: 20

