# Handwritten Digit Recognition with MNIST

A beginner machine-learning project that trains a neural network to classify handwritten digits from the MNIST dataset (digits 0–9).

## What the notebook does

1. Loads the MNIST training and test sets through TensorFlow/Keras.
2. Normalizes pixel values to the 0–1 range.
3. Builds a neural network with a flattening layer, a dense ReLU layer, dropout, and a 10-class softmax output.
4. Trains for five epochs and evaluates on the test set.
5. Displays sample images with their true and predicted labels.

## Technology

- Python
- TensorFlow / Keras
- Matplotlib

## Run locally

1. Install Python and Jupyter Notebook.
2. Install dependencies:

   ```bash
   pip install tensorflow matplotlib jupyter
   ```

3. Open `handwriting.ipynb` in Jupyter Notebook.
4. Run the cells in order. The first run may download the MNIST dataset.

## Evaluation

The notebook prints the test accuracy from the actual run. Use the value produced by your own run; no unverified accuracy figure is claimed here.

## Status

A learning project demonstrating a basic supervised image-classification workflow. Possible next improvements include saving the trained model, adding a confusion matrix, and testing images outside the built-in MNIST dataset.
