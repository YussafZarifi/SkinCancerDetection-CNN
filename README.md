his project builds and trains a Convolutional Neural Network (CNN) to classify dermoscopy images as benign or malignant, supporting early detection of skin cancer using deep learning.
It includes data preprocessing, model training, evaluation, and visualization of performance metrics.

🔍 Overview

Implemented a CNN using PyTorch

Trained on publicly available skin-lesion images (e.g., ISIC dataset)

Includes full training loop: loss tracking, accuracy calculation, and validation

Generates predictions and visualizes results

Runs smoothly in Google Colab or locally

🧠 Skills Demonstrated

Deep learning fundamentals

Building custom CNN architectures

Data preprocessing and augmentation

Training/validation pipeline

Confusion matrix + evaluation

GPU acceleration (Colab)

Clean reproducible ML workflow

🛠️ Tech Stack

Python

PyTorch

torchvision

NumPy

Pandas

Matplotlib

Google Colab

▶️ How to Run
Option A: Google Colab

Open the notebook

Run each cell in order

Make sure torch, torchvision, and all imports are installed

Upload dataset or mount Google Drive

📊 Results

Training & validation accuracy tracked per epoch

Loss curves plotted

Confusion matrix for final classification

Example predictions visualized

📦 Dataset

This project uses publicly available dermoscopy images such as those from the ISIC 2018/2019 challenge datasets.

⭐ Future Improvements

Try deeper architectures (ResNet18, EfficientNet, etc.)

Use data augmentation to reduce overfitting

Deploy model on a simple Flask web app

Add Grad-CAM for heatmap visual explanations

👤 Author

Yussaf Zarifi
Skin Cancer Detection – ML Portfolio Project
