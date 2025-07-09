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


2. **Clone repository**


3. **Create Conda environment, or a python environment**
```bash
conda create --name myenv python=3.11
or
python3.11 -m venv myenv
```

4. **Activate your environment**
```bash
conda activate myenv
or
Windows - .\myenv\Scripts\Activate
MacOs - source myenv/bin/activate
```


5. **Install dependencies:**
While in the activated environment install dependencies
    ```bash
    pip install -r requirements.txt
    ```


6. **Configure your notebook to point to the newly created environment** 

This is by selecting kernel in the notebook at the top right corner while in vscode.

Choose python environments and then the created environment(myenv)

> Allow it to download jupyter/ipykernel when prompted
    

7. **Run the code**

📄 How to Run Jupyter Notebook:

In your vscode from inside the jupyter notebook, tomato_leaf_disease_classifier2.ipynb run each cell by **shift + enter** or at the top run the entire code by clicking **run all**

When running you get a .pkl file which saves the label binarizer (a preprocessing utility often used in machine learning to convert categorical labels into a binary 1 and 0 like dummy variables), it is ignored in the .gitignore file


📂 Dataset

This repository includes a sample dataset in the `sample_data/` directory. If you wish to train on the full dataset, download it from [kaggle](https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf) and place it in `sample_data/` after unzipping.


[Original_file](tomato-leaf-disease-detection.ipynb)- the undocumented file

[Documented_file](tomato-leaf-disease-detection2.ipynb) - the documented file with code comments





ℹ️ Glossary
- Convolutional Neural Network (CNN): A type of deep learning model designed to process and classify images.
- Data Augmentation: Randomly transforming images (rotating, flipping) to improve model generalization.


## EDGE CASES

Before starting NB

> 🔴 The training part of the model in the notebook might require a bigger ram, the dataset is trimmed and will run on 8gb RAM but if not move to [google colab](https://colab.google/), all you need to do is go to new notebook then file, then upload the notebook to google colab, !pip install on code cell any libraries not pre installed by colab like tensorflow, keras and scikit-learn for example 
```
!pip install scikit-learn==1.2.0
```
and upload the data as well