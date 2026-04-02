# Handwritten Digit Classification using ANN and CNN

##  Project Overview

This project focuses on **handwritten digit classification** using the MNIST dataset. Two models — an **Artificial Neural Network (ANN)** and a **Convolutional Neural Network (CNN)** — are implemented to classify digits (0–9).

The models are trained and evaluated, and their performance is compared primarily based on **accuracy**.

---

##  Objectives

* Implement an ANN for digit classification
* Implement a CNN for digit classification
* Evaluate both models on test data
* Compare their performance using accuracy

---

##  Dataset

* **Name:** MNIST Dataset
* **Total Samples:** 70,000 images

  * Training: 60,000
  * Testing: 10,000
* **Image Size:** 28 × 28 pixels (grayscale)

---

##  Tools & Libraries

* Python
* NumPy
* Matplotlib
* TensorFlow / Keras

---

##  Workflow

1. Load MNIST dataset
2. Normalize pixel values (0–255 → 0–1)
3. Build and train ANN model
4. Build and train CNN model
5. Evaluate both models on test data
6. Compare accuracy

---

##  Models

###  Artificial Neural Network (ANN)

* Input: Flattened image (784 features)
* Hidden layers: Dense layers with ReLU activation
* Output: 10 neurons (Softmax)

---

###  Convolutional Neural Network (CNN)

* Convolution layers for feature extraction
* MaxPooling layers for downsampling
* Fully connected dense layers
* Output: 10 neurons (Softmax)

---

##  Results

| Model | Test Accuracy |
| ----- | ------------- |
| ANN   | ~97–98%       |
| CNN   | ~99%          |

---

##  Observations

* ANN performs well but does not capture spatial features
* CNN performs better as it preserves image structure
* CNN achieves higher accuracy on image data

---

##  Conclusion

Both ANN and CNN can classify handwritten digits effectively. However, CNN provides better performance due to its ability to extract spatial features from images.

---

