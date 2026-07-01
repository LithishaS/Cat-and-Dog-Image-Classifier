# 🐱🐶 Cat and Dog Image Classifier

A Deep Learning project that classifies images as **Cat** or **Dog** using a Convolutional Neural Network (CNN).

## 📌 Project Overview

This project uses the Microsoft Kaggle Cats and Dogs dataset. The images are preprocessed, augmented, and trained using a CNN model built with Keras.

## ✨ Features

- Image classification
- Cat and dog dataset preprocessing
- Image cleaning and invalid file removal
- Data augmentation
- CNN model training
- Accuracy and loss visualization
- Custom image prediction

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- TensorFlow / Keras
- Jupyter Notebook

## 📂 Project Structure

```text
cat-dog-image-classifier/
│
├── Cat_and_Dog_Image_Classifier_.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## 📊 Dataset

Dataset used:

- Kaggle Cats and Dogs Dataset
- Contains cat and dog images used for binary classification.

## ⚙️ Workflow

1. Download and unzip the dataset
2. Load image paths and labels
3. Remove invalid/corrupted image files
4. Visualize cat and dog images
5. Split data into training and validation sets
6. Apply image augmentation
7. Build CNN model
8. Train the model
9. Plot accuracy and loss graphs
10. Predict custom cat/dog images

## 🧠 Model Used

Convolutional Neural Network (CNN)

Layers used:
- Conv2D
- MaxPool2D
- Flatten
- Dense

## 📷 Output

The model predicts:

```text
It's a Cat
```

or

```text
It's a Dog
```

## 🚀 How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook
```

Run:

```text
Cat_and_Dog_Image_Classifier_.ipynb
```


## 👩‍💻 Author

**Lithisha S**
