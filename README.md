# Stroke-prediction-using-CNN-VIT-ensemble-model

🧠 Stroke Prediction using Ensemble CNN Models
📌 Overview

This project builds and evaluates Convolutional Neural Network (CNN) based deep learning models for stroke prediction.
The notebook explores:

Data preprocessing and augmentation

Multiple CNN architectures

Model ensembling for improved accuracy

Model interpretability using Grad-CAM and Occlusion Maps

The goal is not only to achieve high predictive performance but also to provide explainability in clinical decision support systems.

📂 Repository Structure
├── stroke_prediction_ensamble_model.ipynb   # Main notebook with code
├── README.md                                # Project documentation
├── requirements.txt                         # Dependencies
└── models/                                  # (Optional) Saved models

📊 Dataset

Source: [Add dataset link here – e.g., Kaggle Stroke Prediction Dataset or your custom dataset]

Input shape: (224, 224, 3) images

Binary classification task: Stroke (1) vs No Stroke (0)

🏗️ Model Architectures

Base CNN models with 3 convolutional blocks (Conv2D → MaxPooling → Dropout).

Ensemble model combining predictions from multiple CNN variants.

Dense layers for final binary classification.

🔍 Interpretability

The notebook includes:

Grad-CAM: Highlights the regions of an image most influential for the model’s decision.

Occlusion Maps: Analyzes the sensitivity of predictions when parts of the input are masked.

These methods improve trust and transparency for healthcare AI applications.

⚙️ Installation

Clone the repository:

git clone https://github.com/yourusername/stroke-prediction-ensemble.git
cd stroke-prediction-ensemble


Install dependencies:

pip install -r requirements.txt

▶️ Usage

Run the Jupyter notebook:

jupyter notebook stroke_prediction_ensamble_model.ipynb


The notebook walks through:

Loading and preprocessing the dataset

Training multiple CNN models

Creating the ensemble

Visualizing Grad-CAM and Occlusion Maps

📈 Results

The ensemble CNN outperformed individual models.

Interpretability methods highlighted relevant brain regions for stroke classification.

(You can add accuracy/F1-score table here once finalized.)

📌 Requirements

Python 3.9+

TensorFlow / Keras

NumPy, Pandas, Matplotlib, Seaborn

scikit-learn

Install with:

pip install tensorflow numpy pandas matplotlib seaborn scikit-learn

