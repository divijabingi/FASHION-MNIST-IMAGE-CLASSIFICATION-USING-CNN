# Fashion-MNIST Image Classification Using CNN

## Project Overview

This project focuses on classifying fashion and clothing images using a **Convolutional Neural Network (CNN)**. It uses the Fashion-MNIST dataset to identify different categories of clothing items from grayscale images.

The model learns visual patterns and features from images to predict the correct clothing category.

## Dataset

The project uses the **Fashion-MNIST dataset**, which contains 70,000 grayscale images of clothing items.

- Training Images: 60,000
- Testing Images: 10,000
- Image Dimensions: 28 × 28 pixels
- Color Format: Grayscale
- Number of Classes: 10

### Classes

1. T-shirt/Top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle Boot

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook
- Convolutional Neural Networks (CNN)

## Model Architecture

The project uses a CNN architecture to extract important image features and perform multi-class classification.

The model involves:

- Convolutional Layers – Extract image features.
- ReLU Activation – Introduces non-linearity.
- Max Pooling Layers – Reduce spatial dimensions.
- Flatten Layer – Converts feature maps into a one-dimensional vector.
- Dense Layers – Learn classification patterns.
- Softmax Output Layer – Predicts probabilities for 10 classes.

## Project Workflow

1. Load the Fashion-MNIST dataset.
2. Explore and visualize sample images.
3. Preprocess and normalize image data.
4. Build the CNN model.
5. Compile the model using an optimizer and loss function.
6. Train the model using training images.
7. Evaluate the model using test images.
8. Predict clothing categories for unseen images.

## How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/divijabingi/FASHION-MNIST-IMAGE-CLASSIFICATION-USING-CNN.git
   ```

2. Navigate to the project directory:

   ```bash
   cd FASHION-MNIST-IMAGE-CLASSIFICATION-USING-CNN
   ```

3. Install the required libraries:

   ```bash
   pip install tensorflow numpy matplotlib jupyter
   ```

4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the notebook:

   `1-Multi-Class-Image-Classification-Fashion-MNIST.ipynb`

6. Run all cells to train and evaluate the CNN model.

## Results

The trained CNN model predicts one of the 10 fashion categories based on the input image.

Model performance can be evaluated using test accuracy and loss.

## Applications

- Automated clothing image classification
- Fashion recommendation systems
- E-commerce product categorization
- Computer vision applications

## Author

**Divija Bingi**

GitHub: [divijabingi](https://github.com/divijabingi)

