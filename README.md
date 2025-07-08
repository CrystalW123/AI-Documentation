# AI DOCUMENTATION

Credits for the notebook go to [author](https://www.kaggle.com/code/shakib23/tomato-leaf-disease-detection)

The purpose of the repository is to use AI to do documntation improving the code explainability

# Tomato Leaf Disease Image Classifier

This project implements a Convolutional Neural Network (CNN) which is a type of deep learning model particularly effective for image classification, using Keras and TensorFlow(python libraries) to classify tomato leaf images into disease categories. It processes labeled images, applies data augmentation, and trains a deep learning model capable of recognizing different tomato leaf diseases from images.

---

## 🚀 Project Overview

This repository provides:

- A complete image classification pipeline.
- Preprocessing steps to load, resize, and normalize images.
- Data augmentation to improve generalization.
- Training and validation with performance tracking.

The model outputs a probability distribution across all disease classes, enabling precise identification of plant health issues.

---

## 💻 Python Version

**Recommended Python Version:**

Python 3.11+

## 🛠️ Installation

1. **Fork this repository to get a copy on your own account**

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    
3. **Run the code**

📂 Dataset

This repository includes a sample dataset in the `sample_data/` directory. If you wish to train on the full dataset, download it from [kaggle](https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf) and place it in `sample_data/` after unzipping.

📄 How to Run
For Jupyter Notebook:

In your vscode or any other code editor from inside the jupyter notebook tomato_leaf_disease_classifier2.ipynb run each cell by **shift + enter** or at the top run the entire code by clicking **run all**


[Original_file](tomato-leaf-disease-detection.ipynb)- the undocumented file

[Documented_file](tomato-leaf-disease-detection2.ipynb) - the documented file with code comments

> 🔴**The training part of the model in the notebook might require a bigger ram, the dataset is trimmed and hopefully will run on 8gb RAM but if not move to google colab, all you need to do is import the notebook to google colab**

ℹ️ Glossary
- Convolutional Neural Network (CNN): A type of deep learning model designed to process and classify images.
- Data Augmentation: Randomly transforming images (rotating, flipping) to improve model generalization.