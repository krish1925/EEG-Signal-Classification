
# EEG Signal Classification Using Convolutional Recurrent Neural Networks (CRNN)

## Project Overview

This project aims to classify Electroencephalography (EEG) data obtained from the Brain-Computer Interaction (BCI) Competition IV. The data encompasses recordings of four distinct motor imaginary tasks: movement of the left hand, right hand, both feet, and tongue. We utilize a Convolutional Recurrent Neural Network (CRNN) architecture, incorporating bidirectional Long Short-Term Memory (LSTM) units, to classify the EEG data into these four tasks.

## Team Members

- Krish Patel 
- Aryan Singh

## Motivation

EEG signal classification is a pivotal task in brain-computer interfaces (BCI), with applications ranging from assistive technologies to medical diagnosis. By leveraging CRNNs, we aim to capture both spatial and temporal dependencies within the EEG signals for improved classification accuracy.

## Architecture

Our approach employs three distinct models:
1. **Vanilla CNN:** Utilizes convolutional layers for spatial feature extraction.
2. **CNN + LSTM:** Combines convolutional layers with LSTM units to capture both spatial and temporal features.

## Results

- **Vanilla CNN:** Achieved a highest accuracy of 65.7% with a training time of approximately 25-35 minutes.
- **CNN + LSTM:** Reached a highest accuracy of 64.1% after training for around 3-4 hours.
- Detailed performance metrics and a comparative analysis are provided in the report.

## Key Findings

- Temporal dependencies play a crucial role in EEG signal classification.
- The optimal performance requires balancing spatial and temporal feature extraction.
- Model performance varies significantly across different subjects, highlighting the need for personalized model adjustments.

## Future Directions

- **Data Preprocessing:** Explore advanced techniques for data cleaning and preprocessing.
- **Hyperparameter Optimization:** Fine-tune model parameters, especially for LSTM units.
- **Alternative Architectures:** Investigate other RNN variants and incorporate attention mechanisms.

## Installation and Usage

Details on how to install dependencies and run the project are provided in the subsequent sections.

## Dependencies

- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Pandas

## How to Run

Download the publically available EEG dataset from: https://www.bbci.de/competition/iv/, and set the path in both of the notebooks to the unzipped folder containing the data.

