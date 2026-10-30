# Support Vector Machine (SVM) Classification

A small, beginner-friendly machine learning demonstration of **Support Vector Machine (SVM)** classification using Python and scikit-learn.

## Project overview

This notebook trains a Support Vector Classifier with a **linear kernel** to separate two classes using two numeric features.

- Class `0` is displayed as **Class A**.
- Class `1` is displayed as **Class B**.
- The training data is defined directly in the notebook; no external dataset is required.

## What the notebook does

1. Creates a two-feature dataset with 16 labeled observations.
2. Trains an `sklearn.svm.SVC` model using `kernel="linear"` and `C=1.0`.
3. Calculates the model's decision function over a grid of feature values.
4. Plots the two classes, the decision boundary, and the margin lines.
5. Highlights the model's support vectors.
6. Uses the trained model to classify three new points: `[4, 5]`, `[5, 6]`, and `[9, 8]`.
7. Annotates the predicted class for each new point in the plot.

## Project structure

```text
SVM/
├── SVM.ipynb
├── README.md
└── requirements.txt
```

## Requirements

- Python 3
- NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook or JupyterLab

## Installation

Open a terminal in the project folder and install the dependencies:

```bash
pip install -r requirements.txt
```

## Run the notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `SVM.ipynb` and run the cells in order. The notebook trains the model and displays a plot of the decision boundary, margins, support vectors, and predictions for the three new points.

## Important note

This is an educational example using only 16 manually specified observations and two features. It demonstrates how a linear SVM works; it is not a validated real-world classifier. For practical use, train and evaluate the model with a representative dataset, use a suitable train/test split or cross-validation, and tune preprocessing and model parameters as needed.

## License

Add a license file if you want to specify how others may use, modify, or distribute this project.
