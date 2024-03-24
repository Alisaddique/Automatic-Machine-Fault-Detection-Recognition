
# Automatic Machine Fault Detection and Recognition

## Table of Contents
1. [Introduction](#introduction)
2. [Project Description](#project-description)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Data](#data)
6. [Features](#features)
7. [Model Architecture](#model-architecture)
8. [Training](#training)
9. [Evaluation](#evaluation)
10. [Results](#results)
11. [Contributing](#contributing)
12. [License](#license)

## Introduction <a name="introduction"></a>
Welcome to the Automatic Machine Fault Detection and Recognition project! This project aims to develop a system capable of automatically detecting and recognizing faults in machines using audio signals and convolutional neural networks (CNNs). By leveraging computer vision techniques and machine learning models, the system can identify various types of anomalies in machine operations, such as Arcing, Corona, Looseness, and Tracking.

## Project Description <a name="project-description"></a>
The project consists of several key components, including:
- **Feature Extraction:** Extracting features from audio signals, such as Mel-frequency cepstral coefficients (MFCC), chroma features, and mel spectrograms.
- **Model Development:** Training CNN models on the extracted features to learn patterns associated with different types of faults.
- **Model Evaluation:** Evaluating the trained models using performance metrics such as accuracy, F1-score, ROC curves, and confusion matrices.
- **Real-time Testing:** Testing the system in real-time to classify faults in new audio samples captured from machines during operation.

## Installation <a name="installation"></a>

To use the project, follow these steps:

1. **Clone the Repository:** Clone the GitHub repository to your local machine.
   ```
   git clone https://github.com/your_username/automatic-machine-fault-detection.git
   ```

2. **Install Dependencies:** Install the required dependencies by running the following command in your terminal.
   ```
   pip install -r requirements.txt
   ```

## Usage <a name="usage"></a>
To use the project:
1. Prepare your audio samples and organize them in the `samples` directory.
2. Follow the instructions in the project code to load, preprocess, and train the model.
3. Evaluate the model's performance using provided metrics and visualization tools.
4. Test the model with new audio samples using the provided functions.

## Data <a name="data"></a>
The dataset used in this project consists of audio samples recorded from machines exhibiting various types of faults. Each audio sample is labeled with the corresponding fault type.

## Features <a name="features"></a>
The features extracted from audio signals include Mel-frequency cepstral coefficients (MFCC), chroma features, and mel spectrograms. These features are used to characterize the underlying patterns in the audio data.

## Model Architecture <a name="model-architecture"></a>
The CNN model architecture comprises convolutional layers, max-pooling layers, dense layers, and dropout layers. The model is designed to learn patterns from the extracted audio features and classify faults accurately.

## Training <a name="training"></a>
To train the model, audio samples are loaded, features are extracted, and the dataset is split into training and testing sets. The model is trained using the training data, and its performance is evaluated on the testing data.

## Evaluation <a name="evaluation"></a>
The trained model is evaluated using various performance metrics, including accuracy, F1-score, ROC curves, confusion matrices, and classification reports. These metrics provide insights into the model's ability to detect and recognize faults in machine audio signals.

## Results <a name="results"></a>
The project achieves promising results in fault detection and recognition, with high accuracy and F1-score values. The ROC curves and confusion matrices demonstrate the model's effectiveness in classifying different fault types.

## Contributing <a name="contributing"></a>
Contributions to the project are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request. Please ensure that your contributions align with the project's goals and coding standards.

---


3. **Prepare Data:** Prepare your audio data by placing them in the `samples` directory within the repository. Ensure that the audio files are properly labeled.

4. **Run the Code:** Run the Jupyter Notebook or Python script provided in the repository to perform feature extraction, model training, evaluation, and testing.

5. **Test a Voice Sample:** Use the provided function `test_voice_sample` to test a voice sample and predict its class label based on the trained model.

## Directory Structure
```
├── samples/                  # Directory containing audio samples
├── automatic_fault_detection.ipynb   # Jupyter Notebook containing project code
├── README.md                 # Project README file
└── requirements.txt          # File containing project dependencies
```

## Contributors
- [Ali Saddique](https://github.com/Alisaddique)


## License
--------------------
