# Diabetic-Retionpathy-Detection

This project detects the severity of diabetic retinopathy from retinal fundus images using a convolutional neural network (CNN) built with TensorFlow/Keras.[file:56] It is intended as an educational machine learning project and a portfolio example.

## Project Overview

Diabetic retinopathy (DR) is a diabetes-related eye disease that can lead to vision loss if not detected early. In this project, we train a multi-class image classifier to predict DR severity from retinal images.

Main goals:

- Explore and visualize the dataset and class distribution.
- Build a TensorFlow/Keras pipeline for training and evaluation.
- Handle class imbalance and assess model performance on all classes.[file:56]

## Dataset

The project uses a public diabetic retinopathy image dataset from Kaggle (retinal fundus images labeled by DR severity).  
**You need to:**

1. Create a Kaggle account (if you don’t have one).
2. Download the dataset locally.
3. Place the dataset under the `data/` directory (see below).

In the notebook, you set a `dataset_path` variable that should point to the root directory where the class folders (e.g. `Healthy`, `Mild`, `Moderate`, etc.) are stored.

> Note: Images are **not** included in this repository due to size and licensing. Please download them separately.

## Project Structure

```text
diabetic-retinopathy-detection/
├─ README.md
├─ requirements.txt
├─ DiabeticRetionpathy.ipynb

## How to Run

1. Clone repo: `git clone https://github.com/YOUR_USERNAME/Diabetic-Retionpathy-Detection.git`
2. Install: `pip install -r requirements.txt`
3. Download Kaggle dataset → put class folders in `data/`
4. Set `dataset_path = "data"` in notebook
5. Run: `jupyter notebook DiabeticRetionpathy.ipynb`

## Results

- Validation accuracy: XX.X%
- Test accuracy: YY.Y%
- Note: Lower performance on Severe/Proliferative due to class imbalance
