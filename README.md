![image](https://github.com/user-attachments/assets/7b0e913d-9323-4b9b-bb4e-baf1cd6c87c5)

# 🖼️ CIFAR-10 Image Classification with TensorFlow

This repository contains a convolutional neural network (CNN) model built using TensorFlow and Keras to classify images from the CIFAR-10 dataset.

## 📂 Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images across 10 different classes (e.g., airplane, car, bird, cat, etc.). The dataset is loaded directly from TensorFlow datasets.

## 🔍 Data Analysis
- Examined shape of training and test data
- Displayed sample images with labels
- Verified class distribution

## 🧹 Data Cleaning
- Normalized pixel values to the range [0, 1]
- Converted labels to integers
- No missing or corrupted data

## 🏗️ Model Training
- Built a CNN using:
  - Conv2D and MaxPooling layers
  - Dropout layer to prevent overfitting
  - Dense layers for final classification
- Tuned hyperparameters like:
  - Number of filters
  - Kernel size
  - Learning rate (optional with Keras Tuner)

## 🔮 Prediction
- Performed predictions using `model.predict()`
- Converted probabilities to class indices with `np.argmax()`

## 📊 Evaluation
- Evaluated model using:
  - Accuracy score
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)

## 🛠️ Tools Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn
- Keras Tuner (optional for hyperparameter tuning)

## 📈 Output
- Classification report with all 10 classes
- Visualized predictions
- Model summary and training accuracy graphs

---

Contributions and suggestions are welcome. Feel free to fork and explore!
