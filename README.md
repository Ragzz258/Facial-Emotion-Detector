# Facial Emotion Detector

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Repository Structure](#repository-structure)

## Introduction

Facial Emotion Detector is a deep learning project that can detect human emotions from facial expressions in real-time using a computer's webcam. This README file provides an overview of the project, instructions for installation and usage, and details on how the model was trained.

## Installation

1. Clone this repository to your local machine.
```
git clone https://github.com/your-username/Facial-Emotion-Detector.git
```
## Usage

### Training the Model

1. The `images` folder contains the required dataset

2. Get trained model from `Train_CNN.ipynb` notebook.

### Detecting Emotions in Real-time

To detect emotions in real-time using your computer's webcam:

1. Ensure you have a trained model (model.h5) in the project directory.

2. Run the main script.

    ```bash
    python main.py
    ```

The webcam feed will open, and the emotions detected from the facial expressions will be displayed in real-time.

## Repository Structure

The repository structure is as follows:

- `images/`: This directory should contain the Face Expression Recognition Dataset.

- `train_CNN.ipynb`: Jupyter notebook for training the emotion detection model.

- `main.py`: Python script for real-time emotion detection using the trained model.
