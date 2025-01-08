# MNIST Handwritten Digit Classification
This project builds a neural network to classify handwritten digits (0-9) using the MNIST dataset. The dataset contains 60,000 training images and 10,000 test images, each of size 28x28 pixels. The goal is to train a model that achieves high accuracy in recognizing handwritten numbers.

### Features
1. Data preprocessing and visualization.
2. A simple neural network built using TensorFlow and Keras.
3. Training and evaluation with accuracy and loss metrics.
4. Model predictions visualized for individual test samples.

### Requirements
To run this project, you need:
1. Python (>=3.7)
2. TensorFlow
3. Matplotlib
4. Jupyter Notebook (optional, for running interactively)

### Install the required libraries with:
pip install tensorflow matplotlib

### How to Run
Clone the repository:
git clone https://github.com/FemiJames070/MNIST-Handwritten-Digits-Classification.git
cd MNIST-Handwritten-Digits-Classification

### Open the Jupyter Notebook:
1. jupyter notebook mnist_classification.ipynb
2. Run all cells sequentially to:
3. Load and preprocess the data.
4. Build and train the neural network model.
5. Evaluate the model's performance.
6. Visualize predictions.
7. (Optional) Export the notebook to a Python script if needed.

### Results
The model achieves approximately 97% accuracy on the test set after 5 training epochs.
Example output:
1. Accuracy: 0.9744
2. Loss: 0.0897

### Sample Prediction
For the 100th test image:
1. Predicted label: 6
2. True label: 6

Visualization:

### File Structure
MNIST-Handwritten-Digits-Classification/
1. mnist_classification.ipynb  # Main Jupyter Notebook for the project
2. README.md                   # Project documentation
3. requirements.txt            # Dependencies

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### Acknowledgments
1. The MNIST dataset is publicly available and widely used for image classification tasks.
2. TensorFlow and Keras for their intuitive APIs.
2. Matplotlib for visualization support.
