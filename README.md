# Dogs vs Cats – Image Classification in Keras

This project trains a Convolutional Neural Network (CNN) to classify images of **dogs** and **cats** using the classic [Kaggle Dogs vs Cats dataset](https://www.kaggle.com/datasets/biaiscience/dogs-vs-cats).

---

## 1. Project Objectives

- Build a **binary image classifier** (`dog` vs `cat`).
- Use **data augmentation** to improve generalization.
- Monitor **training vs validation performance** and detect overfitting.
- Visualize **sample predictions** to understand model behavior.
- Provide a clean, reusable notebook that can be run on Google Colab or Kaggle.

---

## 2. Dataset

- Source: Kaggle dataset  
  **`biaiscience/dogs-vs-cats`**
- Classes:  
  - `cat`  
  - `dog`
- Images are RGB JPG files with varying resolutions.
- In this notebook:
  - We create a `DataFrame` with:
    - `filename` – image file name (e.g. `dog.1234.jpg`)
    - `category` – label (`"dog"` or `"cat"`)
  - We split the data into:
    - **Training set** (e.g. 80%)
    - **Validation set** (e.g. 20%)

---

## 3. Environment & Requirements

The notebook is designed to run on **Google Colab** (GPU recommended) or on **Kaggle Notebooks**.

Main libraries:

- `python 3`
- `tensorflow` / `keras`
- `numpy`
- `pandas`
- `matplotlib`
- `opencv-python` (for some image visualization)
- `scikit-learn` (for `train_test_split`)

```bash
├── Image_Classification_Colab.ipynb   # main notebook
├── README.md                          # this file
├── data/
│   ├── train/                         # training images (cats & dogs)
│   └── test/                          # test / inference images (optional)
└── models/
   └── dog_cat_cnn.h5                 # saved Keras model (if saved)
---
data/train/
├── cat.0.jpg
├── cat.1.jpg
├── ...
├── dog.0.jpg
├── dog.1.jpg
└── ...
-
