# Unlocked with Z Audio Classification

## Introduction

Welcome to the "Unlocked with Z Audio Classification" project! This repository contains code and resources for participating in the HP Company's "Unlocked with Z" competition. The focus of this project is audio classification, specifically targeting CAPUCHIN birds calls.

## Competition Results

In the initial phases of the competition, the model achieved impressive results with a recall score of 1 and precision score of 1 after just 15 epochs. This indicates a high level of accuracy in identifying CAPUCHIN birds calls.
## Dataset 
https://www.kaggle.com/datasets/kenjee/z-by-hp-unlocked-challenge-3-signal-processing
## Project Overview

### 1. Data Preprocessing

The first step involved converting the audio files into waveforms. This was done to extract meaningful features from the audio data for classification purposes.

### 2. Visualization

To gain insights into the audio data, the waveforms were visualized by plotting images of the MP3 files. This step provided a better understanding of the characteristics of CAPUCHIN birds calls.

### 3. Model Architecture

The core of the project is a deep CNN (Convolutional Neural Network) model. The model was designed to effectively learn and classify features from the audio data, enabling accurate predictions.

### 4. Prediction Function

To extend the usability of the trained model, a prediction function was implemented. This function allows users to predict the classification of other MP3 files, providing a practical tool for CAPUCHIN birds call classification.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Run the provided Jupyter notebooks or integrate the model into your own scripts for classification.

## File Structure

The repository is organized as follows:

- `data/`: Contains the raw audio data.
- `notebooks/`: Jupyter notebooks for data preprocessing, visualization, and model training.
- `src/`: Source code, including the deep CNN model and the prediction function.
- `results/`: Store model checkpoints and evaluation metrics.

## Future Improvements

While the current model has shown excellent performance, there is always room for improvement. Future enhancements may include fine-tuning hyperparameters, experimenting with different architectures, and exploring additional data augmentation techniques.

## Contributions

Contributions to this project are welcome! If you have ideas for improvements or new features, feel free to submit a pull request.

## Acknowledgments

Special thanks to HP Company for organizing the "Unlocked with Z" competition and providing an opportunity to explore and contribute to the field of audio classification.

Happy coding! 🚀
