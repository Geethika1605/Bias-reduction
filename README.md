📌 Synthetic Data for Real-Time Bias Reduction



📖 Project Overview


A deep learning-based system designed to detect and classify medical images as real or AI-generated/synthetic, with built-in bias reduction techniques to ensure  accurate model performance across diverse medical imaging datasets.



🎯 Purpose


Detect AI-generated medical images that may introduce bias in diagnostic models

Reduce dataset bias using advanced data augmentation and synthetic data generation

Provide transparency in identifying synthetic medical imagery




🛠️ Tech Stack
**Languages**

Python

**Libraries & Frameworks
**
OpenCV – image processing

NumPy, Pandas – data handling

Matplotlib, Seaborn – visualization

Scikit-learn – model evaluation, SMOTE integration

Imbalanced-learn (SMOTE) – class balancing

CTGAN / SDV – synthetic tabular data generation

TensorFlow / Keras – deep learning model

PIL – image handling




🧵 Pipeline Workflow

1.Dataset Validation

Checks number of images

Identifies readable/unreadable files

2.Feature Extraction

Color, texture, gradient, FFT, edge features

3.Synthetic Data Generation

Through augmentation

Via SMOTE

Via CTGAN

4.Bias Reduction & Dataset Balancing

5.Model Training

Deep neural network with dropout layers

Validation split to avoid overfitting

6.Evaluation & Visualization

Confusion matrix

Classification report

Accuracy & precision graphs

7.Real-Time Prediction

Accepts single image as input

Returns prediction: REAL or SYNTHETIC

Confidence score included
