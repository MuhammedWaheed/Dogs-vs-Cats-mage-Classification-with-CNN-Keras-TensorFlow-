# 🐶🐱 Dogs vs Cats – Image Classification in Keras

-This project trains a Convolutional Neural Network (CNN) to classify images of **dogs** and **cats** 


## 📌 1. Project Objectives

- Build a **binary image classifier** (`dog` vs `cat`)
- Use **data augmentation** to improve generalization
- Monitor **training vs validation performance** and detect overfitting
- Visualize predictions on sample images
- Provide a clean, reusable notebook for Colab or Kaggle

---
## 📂 Dataset

-[Kaggle Dogs vs Cats dataset](https://www.kaggle.com/datasets/biaiscience/dogs-vs-cats).  

-It demonstrates a complete deep-learning workflow including data preparation, augmentation, model training, evaluation, and prediction.

| Attribute             | Description                                               |
| --------------------- | --------------------------------------------------------- |
| **Dataset Name**      | **Dogs vs Cats Image Classification**                            |
| **Total Images**      | **37,500** (approx.)                                      |
| **Training Images**   | **20000**                                                |
| **Validation Images**    | **5000**                                                 |
| **Validation Images** | **12500**                                                  |
| **Number of Classes** | **2** (Dog ,Cat) |
| **Data Format**       | **JPEG Images**                                           |


---
---
## 🧮 Technologies Used
| Category | Tools / Libraries |
|-----------|-------------------|
| Language | Python 🐍 |
| Deep Learning | TensorFlow, Keras |
| Data Processing | NumPy, OpenCV |
| Visualization | Matplotlib, Seaborn |
| Dataset | Dogs vs Cats Classification (Kaggle) |

---
## ⚙️ Environment & Requirements

The notebook runs on **Google Colab** (GPU recommended) or **Kaggle Notebooks**.

### Main libraries:
- `python 3`
- `tensorflow` / `keras`
- `numpy`
- `pandas`
- `matplotlib`
- `opencv-python`
- `scikit-learn`
---
## 📂 Project Structure
```bash
├── Image_Classification_Colab.ipynb   # main notebook
├── README.md                          # this file
├── data/
│   ├── train/train                         # training images (cats & dogs)
│   └── test/test                         # for testing model 
           
---

