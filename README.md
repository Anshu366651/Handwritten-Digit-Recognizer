# Handwritten-Digit-Recognizer
## Project Description
This project uses a Convolutional Neural Network (CNN) built with TensorFlow/Keras to recognize handwritten digits (0–9) from the MNIST dataset. The model is trained on thousands of labeled images and can also predict digits from custom input images.



##  Features
- Load and preprocess MNIST dataset
- Build and train CNN model with TensorFlow/Keras
- Evaluate performance on test set (expected >98% accuracy)
- Predict unseen handwritten digit images
- Save and reload trained models


##  Repository Structure
Handwritten-Digit-Recognizer/
│── data/ # Dataset and custom images
│── notebooks/ # Jupyter notebooks
│── src/ # Source code files
│── saved_models/ # Trained models
│── requirements.txt # Dependencies
│── README.md # Documentation


##  Requirements
- Python 3.8+
- TensorFlow 2.x
- NumPy
- Matplotlib
- scikit-learn
- Pillow

Install dependencies:
```bash
pip install -r requirements.txt
