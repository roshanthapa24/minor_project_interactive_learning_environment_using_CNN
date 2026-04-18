# Multi-Class Image Classification using CNN

A custom Convolutional Neural Network (CNN) model built from scratch for multi-class image classification on the CIFAR-10 dataset. This project was developed as a minor project to explore deep learning techniques for image recognition.

---

## Project Overview

Image classification is a fundamental task in computer vision. This project implements a custom CNN architecture trained on the CIFAR-10 dataset, which contains 60,000 images across 10 different classes. The model is trained, evaluated, and saved for future inference.

---

## Features

- Custom CNN architecture built from scratch
- Trained on CIFAR-10 dataset (10 classes)
- Model checkpointing and saving
- Training logs and visualization
- Overfitting analysis with separate model versions
- Model performance plots

---

## Dataset

**CIFAR-10** — 60,000 color images (32x32 pixels) in 10 classes:

| Class | Label |
|-------|-------|
| Airplane | 0 |
| Automobile | 1 |
| Bird | 2 |
| Cat | 3 |
| Deer | 4 |
| Dog | 5 |
| Frog | 6 |
| Horse | 7 |
| Ship | 8 |
| Truck | 9 |

- 50,000 training images
- 10,000 test images

---

## Project Structure

```
├── multiclassimageclassifier.ipynb   ← main notebook
├── model.h5                          ← trained model
├── overhit-model.h5                  ← overfitted model (for comparison)
├── checkpoint                        ← model checkpoint
├── model_plt.png                     ← training accuracy/loss plot
├── model_plt.gz                      ← compressed plot
├── model_plt.gz.pdf                  ← plot PDF
├── logs/                             ← training logs
└── .ipynb_checkpoints/               ← notebook checkpoints
```

---

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- CIFAR-10 Dataset

---

## Installation

```bash
git clone https://github.com/roshanthapa24/minor_project_interactive_learning_environment_using_CNN.git
cd minor_project_interactive_learning_environment_using_CNN
pip install tensorflow numpy matplotlib
```

---

## Usage

1. Open `multiclassimageclassifier.ipynb` in Jupyter Notebook or Google Colab
2. Run all cells to train the model
3. Model will be saved as `model.h5`

---

## Model Architecture

- Input Layer — 32x32x3 images
- Convolutional Layers with ReLU activation
- MaxPooling Layers
- Flatten Layer
- Dense (Fully Connected) Layers
- Output Layer — 10 classes with Softmax activation

---

## Results

- Training and validation accuracy/loss plotted in `model_plt.png`
- Two model versions saved:
  - `model.h5` — optimized model
  - `overhit-model.h5` — overfitted model for comparison

---

## Author

**Roshan Thapa**
- GitHub: [roshanthapa24](https://github.com/roshanthapa24)
