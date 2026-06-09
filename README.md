# AI-Based RF Signal Classification Using Deep Learning

## Overview

This project implements an RF modulation classification system using Deep Learning and the RadioML 2016.10A dataset.

The system processes raw In-Phase (I) and Quadrature (Q) samples and classifies RF signals into multiple modulation categories using a Convolutional Neural Network (CNN).

---

## Features

* RadioML 2016.10A dataset support
* I/Q waveform visualization
* Constellation diagram generation
* CNN-based modulation classification
* Accuracy and Loss curve generation
* Model export using TensorFlow/Keras

---

## Dataset

Dataset: RadioML 2016.10A

Contains:

* 220,000 RF signal samples
* 11 modulation classes
* SNR range from -20 dB to +18 dB

Download separately and place:

RML2016.10a_dict.pkl

inside the project root directory.

---

## Project Structure

RF_AI_Project

├── dataset_loader.py

├── visualize.py

├── cnn_model.py

├── train.py

├── accuracy_curve.png

├── loss_curve.png

├── rf_classifier.keras

└── README.md



## Results

### CNN Performance

* Training Accuracy: ~47%
* Validation Accuracy: ~51%

### Generated Outputs

* I/Q Waveform Plot
* 8PSK Constellation Diagram
* Accuracy Curve
* Loss Curve
* Trained CNN Model



## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-Learn



## Future Improvements

* CNN-LSTM Architecture
* Confusion Matrix Analysis
* SNR-wise Accuracy Evaluation
* Real-Time SDR Signal Classification


B.Tech Electronics and Communication Engineering
