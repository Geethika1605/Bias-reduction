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

**Libraries & Frameworks**

OpenCV – image processing

NumPy, Pandas – data handling

Matplotlib, Seaborn – visualization

Scikit-learn – model evaluation, SMOTE integration

Imbalanced-learn (SMOTE) – class balancing

CTGAN / SDV – synthetic tabular data generation

TensorFlow / Keras – deep learning model

PIL – image handling




🔄 Workflow

1.Dataset Validation – Reads paths, checks readable image files

2.Feature Extraction – Computes 15+ statistical + texture + frequency features

3.Augmentation – Generates synthetic images through transformations

4.SMOTE Balancing – Oversamples underrepresented class

5.CTGAN Generation – Produces high-quality synthetic feature vectors

6.Model Training – Deep learning classifier to detect Real vs Synthetic

7.Testing & Evaluation – Accuracy, confusion matrix, classification report

8.Real-Time Prediction – Classifies a single uploaded medical image
