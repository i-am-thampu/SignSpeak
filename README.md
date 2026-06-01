# SignSpeak – Real-Time Sign Language Detection App

SignSpeak is a mobile application developed using Flutter and TensorFlow Lite for real-time sign language gesture detection using a smartphone camera. The project was built as an exploration into mobile AI integration, accessibility-focused applications, and real-time computer vision on resource-constrained devices.

## Overview

The goal of the project was to create a lightweight mobile application capable of recognizing sign language gestures in real time and providing an accessible communication aid through on-device inference.

The application uses a TensorFlow Lite model integrated into a Flutter application to process camera input and perform gesture recognition directly on the smartphone.

## Features

* Real-time sign language gesture detection
* Cross-platform mobile application using Flutter
* On-device inference using TensorFlow Lite
* Lightweight mobile deployment
* Camera-based gesture recognition
* Offline-capable prediction workflow

## Tech Stack

### Frontend / Mobile

* Flutter
* Dart

### Machine Learning

* TensorFlow Lite

### Other Technologies

* Mobile Camera Integration
* Real-Time Frame Processing

## Motivation

The project was built to explore:

* Mobile AI deployment
* Accessibility-focused technology
* Real-time inference on smartphones
* Flutter application development
* TensorFlow Lite integration

It also served as a practical learning experience in combining mobile development with machine learning workflows.

## Challenges Faced

One of the biggest challenges during development was the learning curve associated with both Flutter and TensorFlow Lite integration. Since the project was developed independently on an older smartphone, performance limitations and optimization became important considerations.

Additional challenges included:

* Real-time frame processing
* Maintaining acceptable inference speed
* Managing hardware limitations
* Improving detection consistency

## Technical Decisions

A major technical decision was choosing on-device inference using TensorFlow Lite instead of relying on a cloud-based prediction system.

### Why TensorFlow Lite?

* Faster response time
* Reduced dependency on internet connectivity
* Better portability for mobile usage
* Lower latency for real-time detection

### Tradeoff

The decision introduced hardware limitations, especially regarding:

* Processing power
* Model complexity
* Real-time performance
* Prediction accuracy

## Future Improvements

Potential future improvements include:

* Improved model training with larger datasets
* Better hardware resources for training and testing
* Increased detection accuracy
* Support for additional sign language gestures
* Enhanced UI/UX
* Performance optimization for low-end devices

## Learning Outcomes

Through this project, I gained experience in:

* Flutter application development
* TensorFlow Lite integration
* Real-time mobile inference
* Debugging and optimization
* Mobile AI workflows
* Independent project development

## Status

Prototype / Experimental Project

## Author

Thampu Varghese Jacob
