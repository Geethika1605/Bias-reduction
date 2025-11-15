📌 Synthetic Data for Real-Time Bias Reduction



📖 Project Overview


A deep learning-based system designed to detect and classify medical images as real or AI-generated/synthetic, with built-in bias reduction techniques to ensure  accurate model performance across diverse medical imaging datasets.



🎯 Purpose


Detect AI-generated medical images that may introduce bias in diagnostic models

Reduce dataset bias using advanced data augmentation and synthetic data generation

Provide transparency in identifying synthetic medical imagery



🛠️ Tech Stack
Programming Languages

Python

Libraries & Frameworks

Pandas – Data preprocessing

NumPy – Numerical operations

Scikit-learn – SMOTE, model training

Imbalanced-learn (imblearn) – SMOTE implementation

CTGAN / SDV – GAN-based synthetic data generation

Matplotlib / Seaborn – Data visualization

Jupyter Notebook – Experimentation and analysis





📊 Workflow

Data Loading & Preprocessing

Handle missing values, encoding, normalization, etc.

Identify Class Imbalance

Visualize majority vs minority classes

Apply SMOTE

Generate synthetic samples for minority classes using interpolation

Apply CTGAN

Generate realistic synthetic tabular data using GANs

Combine & Rebuild Balanced Dataset

Train Model on Balanced Data

Compare performance with imbalanced dataset

Evaluate Improvements

Accuracy

Precision/Recall

Confusion matrix visuals
