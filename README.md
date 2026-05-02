# Credit Card Fraud Detection

Machine learning project using **K-Nearest Neighbors (KNN)** and **MLP Neural Network** to detect fraudulent credit card transactions.

## Dataset

Download `creditcard.csv` from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and place it in the root of this folder before running the notebook. The file is excluded from this repo due to its size (~150MB).

## Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR-USERNAME/credit-fraud-detection.git
   cd credit-fraud-detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place `creditcard.csv` in the root folder, then launch the notebook:
   ```bash
   jupyter notebook mlproject_improved.ipynb
   ```

## Models
- K-Nearest Neighbors (KNN) — instance-based baseline
- Multi-Layer Perceptron (MLP) — neural network classifier

## Results
Both models are evaluated using classification reports, confusion matrices, ROC curves, precision-recall curves, and 5-fold cross-validation.
