# Pneumonia Chest X-ray Classification

📌 Project Description

This project develops a deep learning model to classify **chest X-ray images** as either **Normal** or **Pneumonia** using a **Convolutional Neural Network (CNN)**. The model is trained on a dataset of labeled X-ray images and evaluated using accuracy and other performance metrics.

📂 Dataset

-> Source: Publicly available Pneumonia X-ray dataset.
- >Structure:
    - `train/` (Training Images)
    - `validation/` (Validation Images)
    - `test/` (Testing Images)
-> Classes:
    - Normal: X-rays of healthy patients.
    - **Pneumonia:** X-rays indicating pneumonia infection.

🏗️ Model Architecture

The CNN model consists of:

  - 3 Convolutional Layers with ReLU activation
  - MaxPooling Layers for feature reduction
  - Flatten Layer to transform features into a 1D vector
  - Dense Layers with Dropout to reduce overfitting
  - Sigmoid Activation for binary classification




📊 Results & Performance

  - Training Accuracy:~99.48%
  - Validation Accuracy:~87.50%
  - Confusion Matrix & Classification Report included in the notebook.




