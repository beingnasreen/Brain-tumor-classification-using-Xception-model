# Brain Tumor Classification with CNN

## Introduction
This project uses convolutional neural networks (CNNs) to classify brain tumors from MRI images, built on TensorFlow and Keras, leveraging the Xception model.

## Dataset
The dataset includes four classes: glioma, meningioma, no tumor, and pituitary tumor, split into training and testing sets.

## Setup
**Prerequisites**: Python 3.x, TensorFlow, Keras, OpenCV, scikit-learn, NumPy, Seaborn, Matplotlib, tqdm.

**Installation**:
1. Clone the repo: `git clone https://github.com/your-username/brain-tumor-classification.git`
2. Install dependencies: `pip install -r requirements.txt`

## Usage
- **Training**: `python train.py`
- **Prediction**: `python predict.py <path_to_image>`

## Features
- Based on Xception model architecture.
- Includes scripts for training and prediction.
- Utilizes callbacks like ReduceLROnPlateau, ModelCheckpoint, and TensorBoard.

## Results
Training/validation accuracy and loss, along with a confusion matrix, are provided in the `results` section.

## Contributions
Contributions are welcome. Please fork the project, make your changes, and submit a pull request.
