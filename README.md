#MNIST Handwritten Digit Recognizer

#Overview
This project implements a deep learning-based handwritten digit recognizer using the MNIST dataset. The model is trained to classify digits (0-9) from grayscale images of handwritten numbers.

# Features
- Preprocessing of MNIST dataset
- Neural network model built using TensorFlow/Keras (or PyTorch)
- Training and evaluation of the model
- Visualization of training progress
- Testing the model with custom images

# Dataset
The MNIST dataset consists of 70,000 grayscale images of handwritten digits (28x28 pixels), split into:
- Training set: 60,000 images
- Test set: 10,000 images

# Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/mnist-digit-recognizer.git
   cd mnist-digit-recognizer
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```


# Model Architecture
- Input layer (28x28 flattened to 784 neurons)
- Hidden layers with ReLU activation
- Output layer with 10 neurons (softmax activation for classification)

# Results
- Achieves ~98% accuracy on the test dataset.
- Loss and accuracy curves are plotted during training.

# Future Enhancements
- Implement CNN for improved accuracy.
- Deploy the model as a web service.
- Extend to real-time digit recognition using a camera.

# License
This project is licensed under the MIT License.

# Acknowledgments
- [MNIST Dataset](https://keras.io/api/datasets/mnist/)
- TensorFlow/Keras and PyTorch Documentation

