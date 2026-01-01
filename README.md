#Project Overview

Cyber threats such as malware, phishing, and denial-of-service (DoS) attacks pose significant risks to modern digital infrastructures. Traditional rule-based intrusion detection systems often struggle to adapt to evolving attack patterns. This project proposes a deep learning–based cyber threat detection framework that leverages the BETH dataset, a realistic system and network log dataset, to identify malicious activities.

The project designs, trains, and evaluates a Multilayer Perceptron (MLP) model for binary classification of cyber events into malicious or benign categories. The proposed model is compared against classical machine learning baselines to demonstrate its effectiveness.

Objectives

Design a deep learning model for cyber threat detection

Analyze system and network logs using supervised learning

Compare deep learning performance with traditional ML models

Evaluate performance using cybersecurity-critical metrics.

Dataset Description

Dataset Name: BETH Dataset

Type: Preprocessed system and network logs

Target Label: sus_label

1 → Malicious event

0 → Benign event

The dataset simulates real-world cybersecurity scenarios and is suitable for evaluating intrusion detection and threat analysis models.

Models Implemented
1. Deep Learning Model

Architecture: Multilayer Perceptron (MLP)

Key Components:

Fully connected layers

ReLU activation

Dropout regularization

Sigmoid output layer

2. Baseline Models

Logistic Regression

Random Forest Classifier

Experimental Setup

Train–Validation–Test Split

Optimizer: Adam

Loss Function: Binary Cross-Entropy

Early Stopping: Based on validation loss

Evaluation Metrics

Accuracy

Attack Recall

False Negative Rate (FNR)

ROC-AUC

These metrics are chosen to reflect real-world cybersecurity priorities, where missing an attack can have severe consequences.

Experimental Setup

Train–Validation–Test Split

Optimizer: Adam

Loss Function: Binary Cross-Entropy

Early Stopping: Based on validation loss

Evaluation Metrics

Accuracy

Attack Recall

False Negative Rate (FNR)

ROC-AUC

These metrics are chosen to reflect real-world cybersecurity priorities, where missing an attack can have severe consequences.


Deployment Considerations

The proposed model can be integrated into:

SIEM systems

Log analysis pipelines

Real-time intrusion detection frameworks

It is best used as a second-line defense, complementing rule-based detection systems.
