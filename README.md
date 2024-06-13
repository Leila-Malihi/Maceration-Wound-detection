# Maceration-Wound-detection
# MobileNetV2 Transfer Learning for Binary Image Classification

This repository contains code for training and evaluating a MobileNetV2 model using transfer learning for binary image classification. The model is trained on a dataset of cropped images of wounds categorized as either maceration or another type.

## Project Structure

- **Scripts**: Python scripts used for training (`train_mobilenetv2.py`) and evaluating (`evaluate_mobilenetv2.py`) the model.
- **Data**: Dataset directory (`maceration-cropped double-checked-splitted/`) containing subdirectories for training, validation, and test data splits.
- **Saved Models**: Directory (`saved_models/`) where the best model checkpoint (`Mobilenetv2-best_model.h5`) is saved during training.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib
- Scikit-learn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mobilenetv2-binary-classification.git
   cd mobilenetv2-binary-classification

