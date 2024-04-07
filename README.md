# Drowsiness Detection Project

This project focuses on detecting drowsiness using deep learning techniques. It employs Convolutional Neural Networks (CNNs) and Artificial Neural Networks (ANNs) to classify images into different categories such as open eyes, closed eyes, yawning, no yawning, strong posture, and weak posture. The models can be utilized to alert individuals when they are becoming drowsy, thus aiding in preventing accidents, especially in scenarios like driving.

## Overview

The project consists of the following components:

1. Data Loading and Preprocessing: Images are loaded from directories and preprocessed to be used for training the models.
2. CNN Model Training: A CNN model is trained using TensorFlow/Keras to classify images into different drowsiness states.
3. ANN Model Training: An ANN model is trained using TensorFlow/Keras as an alternative approach for classification.
4. Evaluation: The trained models are evaluated using various metrics such as accuracy, loss, and confusion matrix.
5. Drowsiness Check: Functions are provided to check drowsiness based on an input image for both CNN and ANN models.
6. Prediction Visualization: Utilities are included to predict drowsiness for multiple images and display the results.

## Dependencies

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- scikit-learn
- seaborn
- PIL (Python Imaging Library)

## Usage

1. Clone the repository:

```bash
git clone https://github.com/VijayJoshi17/Drowsiness-Detection
```

2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Run the main script to train the models and evaluate their performance:

```bash
python drowsiness_final.py
```

4. Utilize the provided functions to check drowsiness on individual images or a folder of images.

## Results

### CNN Model

#### Confusion Matrix

![CNN Confusion Matrix](https://github.com/VijayJoshi17/Drowsiness-Detection/assets/96180147/9f696698-9496-45e8-92d7-02570ce89441)

#### Receiver Operating Characteristic (ROC) Curve

![CNN ROC Curve](https://github.com/VijayJoshi17/Drowsiness-Detection/assets/96180147/7449afd6-82a8-42bc-8541-1333ed668de8)

#### Learning Curve

![CNN Learning Curve](https://github.com/VijayJoshi17/Drowsiness-Detection/assets/96180147/956ccc78-6a64-415b-8d22-85daf6472a75)

#### Model loss

![CNN Model Loss](https://github.com/VijayJoshi17/Drowsiness-Detection/assets/96180147/f1bd5462-e1c4-458d-b4ac-a706062ee6d3)

#### Model Accuracy

![CNN Model Accuracy](https://github.com/VijayJoshi17/Drowsiness-Detection/assets/96180147/1a9f7b55-9bde-4fbb-9618-240e85f17537)

### ANN Model

#### Model Loss

![ANN Model Loss](https://github.com/VijayJoshi17/Drowsiness-Detection/assets/96180147/41139a0e-929d-44c2-8e57-da88c7e0a1f5)

#### Model Accuracy

![ANN Model Accuracy](https://github.com/VijayJoshi17/Drowsiness-Detection/assets/96180147/c8cafdd1-3178-4337-b177-22c42958e28f)

#### Example Predicted Image

![Predicted Image](https://github.com/VijayJoshi17/Drowsiness-Detection/assets/96180147/1361c21e-d065-4509-88bc-fe985db91c5f)


## Example Usage

To check drowsiness for a folder of images:

```python
from drowsiness_detection import predict_and_display_for_folder

folder_path = "path_to_folder"
predict_and_display_for_folder(model, folder_path, image_height, image_width)
```

## Contributors

- Vijay Joshi
- Harshaal Bajaj
- Hetul Shah

