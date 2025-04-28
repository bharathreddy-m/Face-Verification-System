# 📦 Project Requirements

This document explains the important libraries used in the Face Verification System and why they are necessary.

---

## 🛠️ Install All Required Libraries
```bash
pip install -r requirements.txt
```

---

## 📋 Detailed Requirements

### 1. TensorFlow
- **Purpose:**
  - The main deep learning framework.
  - Builds, trains, and deploys the Siamese Networks.
  - Provides layers, optimizers, loss functions (like contrastive loss), and model-saving utilities.
- **Why Needed:** Without TensorFlow, the entire model (Siamese structure) cannot be defined or trained.

### 2. Keras
- **Purpose:**
  - A high-level API built on top of TensorFlow.
  - Simplifies building models using Sequential and Functional APIs.
  - Helps in custom model creation, callbacks, and training loops.
- **Why Needed:** Used to define the CNN feature extractors, distance layers, and build the final Siamese architecture easily.

### 3. NumPy
- **Purpose:**
  - Perform numerical operations on matrices and tensors.
  - Handle image data and embedding arrays efficiently.
- **Why Needed:** Used during data preprocessing, distance calculations, and evaluation metrics.

### 4. OpenCV (opencv-python)
- **Purpose:**
  - Load, resize, and preprocess input images.
  - Perform face region extraction, image augmentation if needed.
- **Why Needed:** Critical for reading the images, preparing them for model input, and visualization.

### 5. Scikit-learn
- **Purpose:**
  - Splits data into training and testing sets.
  - Provides functions to compute evaluation metrics like accuracy, precision, and recall.
- **Why Needed:** Necessary for calculating performance metrics after model evaluation.

### 6. Matplotlib
- **Purpose:**
  - Visualize training and validation loss/accuracy curves.
  - Plot sample verification results.
- **Why Needed:** Helpful for debugging, understanding model behavior, and presenting results.

### 7. Pandas (Optional but Helpful)
- **Purpose:**
  - Store model evaluation results in structured DataFrames.
  - Save and load metadata related to images or embeddings easily.
- **Why Needed:** Useful for clean project management and future extensions (like batch processing evaluation).

---

## ✅ Quick Summary

| Library           | Main Use                                |
| ----------------- | -------------------------------------- |
| TensorFlow        | Deep Learning Model Building          |
| Keras             | Simplified Neural Network Design      |
| NumPy             | Numerical Computations                |
| OpenCV (opencv-python) | Image Preprocessing and Augmentation |
| Scikit-learn      | Dataset Splitting and Metrics         |
| Matplotlib        | Plotting Graphs and Visualizations    |
| Pandas (Optional) | Structured Data Handling              |

---

# 🚀 Final Note

These libraries ensure that the **Face Verification System** is built efficiently, is scalable, and can be extended to real-world deployment.  
Make sure all libraries are installed before running the training or evaluation scripts.

---
