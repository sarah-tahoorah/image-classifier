# Digit Recognition with scikit-learn

A small, self-contained machine learning project that classifies handwritten
digits (0–9) using scikit-learn's built-in `load_digits` dataset and a
Support Vector Machine (SVM) classifier.

## What's in this repo

- `digit_recognition_sklearn.ipynb` — the notebook containing the full project

## Requirements

- Python 3.8+
- `scikit-learn`
- `matplotlib`

## Setup

1. Clone or download this folder.
2. Install the dependencies:
   ```bash
   pip install scikit-learn matplotlib
   ```

## Running the notebook

### In VS Code
1. Open this folder in VS Code (File → Open Folder).
2. Install the **Jupyter** extension if you don't already have it.
3. Open `digit_recognition_sklearn.ipynb`.
4. Click **Select Kernel** (top-right of the notebook) and choose the Python
   interpreter you installed the dependencies into.
5. Click **Run All**.

### In Jupyter Notebook / JupyterLab
```bash
jupyter notebook digit_recognition_sklearn.ipynb
```
or
```bash
jupyter lab
```
then open the file from the browser tab that appears.

## What the notebook does

1. Loads the `load_digits` dataset (1,797 images of handwritten digits, 8x8
   pixels each).
2. Previews a few sample digits.
3. Splits the data into training (80%) and test (20%) sets.
4. Trains a Support Vector Machine (`SVC`) classifier.
5. Evaluates accuracy and prints a classification report.
6. Plots a confusion matrix to show which digits get confused with each other.
7. Visualizes individual predictions vs. true labels (correct predictions in
   green, incorrect ones in red).

