# Stroke-prediction-using-CNN-VIT-ensemble-model

## 🧠 Stroke Prediction using Ensemble CNN Models
## 📌 Overview

This project builds and evaluates Convolutional Neural Network (CNN) based deep learning models for stroke prediction.
The notebook explores:

Data preprocessing and augmentation

Multiple CNN architectures

Model ensembling for improved accuracy

Model interpretability using Grad-CAM and Occlusion Maps

The goal is not only to achieve high predictive performance but also to provide explainability in clinical decision support systems.

## 📂 Repository Structure
├── stroke_prediction_ensamble_model.ipynb   # Main notebook with code

├── README.md                                # Project documentation

## 📊 Dataset

Source:  Kaggle Stroke Prediction Dataset 

Binary classification task: Stroke (1) vs No Stroke (0)

## 🏗️ Model Architectures

Base CNN models with 3 convolutional blocks (Conv2D → MaxPooling → Dropout).

Ensemble model combining predictions from multiple CNN variants.

Dense layers for final binary classification.

## 🔍 Interpretability

The notebook includes:

LIME: Highlights the regions of an image most influential for the model’s decision.

Occlusion Maps: Analyzes the sensitivity of predictions when parts of the input are masked.

These methods improve trust and transparency for healthcare AI applications.

## ▶️ Usage

Run the Jupyter notebook:

jupyter notebook stroke_prediction_ensamble_model.ipynb

## The notebook walks through:

Loading and preprocessing the dataset

Training multiple CNN models

Creating the ensemble

Visualizing Grad-CAM and Occlusion Maps

## 📈 Results

The ensemble CNN outperformed individual models.

Interpretability methods highlighted relevant brain regions for stroke classification.

Accuracy:  0.9863

Precision: 0.9844

Recall:    0.9692

F1 Score:  0.9767

AUC:       0.9990

## 📌 Requirements

Python 3.9+

TensorFlow / Keras

NumPy, Pandas, Matplotlib, Seaborn

scikit-learn

## Install with:

pip install tensorflow numpy pandas matplotlib seaborn scikit-learn

