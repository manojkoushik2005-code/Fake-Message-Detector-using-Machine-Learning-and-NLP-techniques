# Fake Message Detector

## Overview

Fake Message Detector is a machine learning-based application that identifies whether a message is fake/spam or legitimate. The project uses Natural Language Processing (NLP) techniques and text classification algorithms to analyze message content and provide accurate predictions.

## Features

* Detects fake or spam messages
* Text preprocessing and cleaning
* Machine learning-based classification
* Easy-to-use Python implementation
* Dataset-driven training and prediction

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Natural Language Processing (NLP)

## Project Structure

```
FAKE_MESSAGE_DETECTOR/
│
├── dataset.csv
├── fake_message_detector.py
├── requirements.txt
└── README.md
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Supreetharavuri16/FAKE_MESSAGE_DETECTOR.git
```

2. Navigate to the project directory:

```bash
cd FAKE_MESSAGE_DETECTOR
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the Python script:

```bash
python fake_message_detector.py
```

Enter a message when prompted, and the model will predict whether it is fake/spam or legitimate.

## Dataset

The project uses `dataset.csv` as the training dataset. The dataset contains labeled messages used to train and evaluate the machine learning model.

## How It Works

1. Load and preprocess message data.
2. Convert text into numerical features using NLP techniques.
3. Train a machine learning classifier.
4. Predict whether a new message is fake/spam or legitimate.

## Future Improvements

* Improve model accuracy with advanced algorithms.
* Add a web-based user interface.
* Support multiple languages.
* Deploy as a cloud-based application.

## Author

**Supreeth Aravuri**

GitHub: https://github.com/Supreetharavuri16

## License

This project is open-source and available under the MIT License.
