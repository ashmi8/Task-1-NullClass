# Task-1-NullClass

# Age and Gender Prediction with Machine Learning

This project utilizes machine learning techniques to predict the age and gender of individuals based on images. It employs a Convolutional Neural Network (CNN) model trained on the UTKFace dataset for age estimation and gender classification.

## Features

- **Age Prediction**: Predicts the approximate age of a person in an image.
- **Gender Classification**: Classifies the gender (Male/Female) of individuals in images.
- **Shirt Color Recognition**: Enhances age and gender predictions based on shirt color (White/Black).

## Requirements

- Python 3.x
- Libraries:
  - TensorFlow
  - Keras
  - OpenCV (cv2)
  - NumPy
  - Tkinter (for GUI)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ashmi8/Task 1 Nullclass.git
   cd age-gender-prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the UTKFace dataset from [Kaggle](https://www.kaggle.com/jangedoo/utkface-aligned-cropped) and place it in the project directory under a folder named `UTKFace`.

## Usage

1. Train the model using `model.ipynb` to build and train the CNN model on the UTKFace dataset.
2. For GUI interface, run `gui.py` to open a graphical interface where you can select images and view predictions.

## Files

- `model.ipynb`: Jupyter Notebook for model training and evaluation.
- `gui.py`: Python script for GUI implementation using Tkinter.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, please feel free to open an issue or create a pull request.


## Acknowledgments

- UTKFace dataset contributors
- OpenCV, TensorFlow, and Keras communities

