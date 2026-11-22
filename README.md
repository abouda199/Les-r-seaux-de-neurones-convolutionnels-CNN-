
# CIFAR-10 Image Classification with CNNs

## Project Overview

This project explores image classification using Convolutional
Neural Networks (CNNs) on the CIFAR-10 dataset.

Three CNN architectures were developed, trained, and evaluated
to improve classification performance and reduce overfitting.

The optimized model achieves **86.24% test accuracy**.

## Dataset

- Dataset: CIFAR-10
- Total images: 60,000
- Image dimensions: 32 × 32 × 3
- Number of classes: 10
- Training samples: 40,000
- Validation samples: 10,000
- Test samples: 10,000

## Model Architectures

### CNN Baseline

- Three convolutional layers
- ReLU activation
- MaxPooling
- Fully connected layers
- Softmax classification

### CNN V1

- Data augmentation
- Dropout regularization
- Improved generalization

### CNN V2 — Optimized Architecture

- Six convolutional layers
- Batch Normalization
- Progressive Dropout
- Data augmentation
- Adaptive learning rate
- Model checkpointing

## Experimental Results

| Metric | Baseline | CNN V1 | CNN V2 |
|---|---:|---:|---:|
| Training Accuracy | 90.30% | 60.35% | 89.51% |
| Validation Accuracy | 65.38% | 69.25% | **86.84%** |
| Test Accuracy | 65.63% | 69.00% | **86.24%** |
| Macro Precision | 67.15% | 69.16% | **86.29%** |
| Macro Recall | 65.63% | 69.00% | **86.24%** |
| Macro F1-score | 65.59% | 68.04% | **86.13%** |
| Test Loss | 1.4047 | 0.8869 | **0.4287** |
| Parameters | 319,178 | 319,178 | 552,874 |
| Training Time | 64.63 s | 183.90 s | 415.29 s |

## Key Achievements

- Test accuracy of 86.24%.
- Improvement of 20.61 percentage points over the baseline.
- Reduction of test loss by approximately 69.48%.
- Reduced training-validation accuracy gap.
- Detailed confusion matrix and classification error analysis.

## Technologies

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GPU Computing

## Project Workflow

1. Dataset loading and exploration
2. Data preprocessing and normalization
3. Baseline CNN implementation
4. Data augmentation and regularization
5. CNN architecture optimization
6. Model training and validation
7. Independent test evaluation
8. Confusion matrix analysis
9. Misclassified image analysis

## Getting Started

Clone the repository:

```bash
git clone https://github.com/abouda199/Les-r-seaux-de-neurones-convolutionnels-CNN-.git
```

Open `CIFAR10_CNN.ipynb` using Google Colab or Jupyter Notebook.

GPU acceleration is recommended for model training.

## Author

**Abdelbari BRAHIM**

Computer Engineering Student — Intelligent Systems Engineering

National Engineering School of Sousse (ENISO), Tunisia

GitHub: https://github.com/abouda199
