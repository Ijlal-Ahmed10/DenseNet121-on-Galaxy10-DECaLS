# 🌌 Galaxy Morphology Classification using DenseNet121 on Galaxy10 DECaLS

This repository contains the complete implementation of my research project on Galaxy Morphology Classification, currently in the process of being published. The project leverages DenseNet121, a state-of-the-art deep convolutional neural network, to classify galaxy images into their respective morphological categories.

All experiments, preprocessing, model development, training, evaluation, and visualizations were conducted using Kaggle Notebooks. This repository includes the full workflow, experimental findings, metrics, and plots.

```diff
📁 Repository Structure
├── notebook.ipynb          # Main Kaggle notebook with full pipeline and plots
└── README.md               # Project overview (this file)
```


Folder names may differ depending on your uploads—customize as needed.

# 🚀 Project Overview

Galaxy morphology classification plays a crucial role in astrophysics by helping researchers study galaxy formation, evolution, and large-scale structures in the universe. This project trains and evaluates a DenseNet121-based classifier on a galaxy image dataset, performing more than 16 experiments with varying hyperparameters.

# 🧠 Key Features
## ✔ Dataset Preprocessing & Augmentation
- Loaded dataset from Kaggle input directory.
- Applied extensive preprocessing steps:
    - Resizing
    - Normalization
    - Train/validation splitting
    - Data augmentation (rotation, zoom, horizontal flip, brightness adjustments, etc.)

## ✔ Model Architecture

- Base model: DenseNet121 (ImageNet weights)
- Custom classifier head
- Configurable hyperparameters:
    - Optimizer
    - Learning rate
    - Batch size
    - Epochs
    - Trainable layers
    - Dropout values

## ✔ Training & Evaluation

- Trained model across 16+ experiments
- Logged metrics:
    - Accuracy
    - Loss
    - Precision
    - Recall
    - F1-score
- Plotted:
    - Accuracy curves
    - Loss curves
    - Learning curves
    - Confusion matrices

## ✔ Experiment Tracking

- Saved:
    - All metrics to CSV files
    - All plots and visualizations
    - Best-performing model
- Organized experiment-level results for reproducibility.

## 📊 Results Summary

- Each experiment generated:
    - Training & validation accuracy/loss
    - Performance metrics 
    - Visualizations

- The repository includes:
    - Accuracy curves
    - Loss curves
    - Experiment comparison plots
    - Detailed metrics for all experiments

You can explore these results to analyze the influence of hyperparameters on model performance.

## 🧪 Experiments Conducted

A total of 16+ experiments were performed with variations including:
- Different learning rates
- Different optimizers
- Different batch sizes
- Training the full model vs. freezing backbone
- Varying dropout rates
- Adjusting augmentation intensity

Each experiment was logged and saved for reproducibility.

## 📈 Visualizations

This project includes:
- Training/validation accuracy & loss plots
- Confusion matrices
- Learning curves
- Experiment comparison charts

All visualizations can be found in the figures/ directory.

## 📝 How to Use

1. Clone the repository:
```bash
git clone https://github.com/<username>/<repo-name>.git
```

2. Open the notebook in Jupyter or Kaggle.

3. Update dataset paths as needed.

4. Run all cells to reproduce preprocessing, training, and evaluation.

## 🧾 Research Paper

The accompanying research paper is currently under review for publication.
Once published, the citation details will be added here.
