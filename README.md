Acoustic Defect Detection System using FFT and Machine Learning
This project implements an AI-based acoustic wave monitoring system for detecting defects in railway tracks using ultrasonic signals. The system simulates both defect-free and defective signals, extracts key features from the signals (e.g., amplitude, frequency), and uses a machine learning model to classify the signals as defective or defect-free.

Table of Contents
Overview
Project Features
Prerequisites
Installation
Usage
System Architecture
Signal Simulation
Feature Extraction
Model Training and Prediction
Visualizations
Future Improvements
License
Overview
This project demonstrates the development of an acoustic monitoring system that detects defects in railway tracks using FFT and machine learning techniques. The system consists of a mobile device that transmits ultrasonic signals, collects echoes, and analyzes the signals to identify defects.

Key components:

Simulate induced and echo signals with and with
Project Features
Simulates ultrasonic signals with and without defects.
Extracts relevant signal features like amplitude, RMS, dominant frequency, skewness, etc.
Implements FFT to convert signals from the time domain to the frequency domain.
Trains a machine learning model on the extracted features to classify signals.
Visualizes FFT and time-domain signals to help understand the differences between defective and defect-free signals.
