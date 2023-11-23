# ECEN-758-Data-Mining-and-Analysis-Project

# Fashion MNIST Classification Experiment

## Introduction

This repository contains the code and documentation for my experiment with the Fashion MNIST dataset, focusing on the comparison of traditional machine learning models, Artificial Neural Networks (ANN), and Convolutional Neural Networks (CNN) for fashion item classification. The Fashion MNIST dataset is a collection of grayscale images of 10 different fashion categories, widely used as a benchmark for image classification tasks.

## Experiment Overview

In this experiment, We systematically evaluated a diverse set of models, including K-Nearest Neighbors (KNN), Random Forest, Decision Trees, Gradient Boosting, SVM Classifier, Logistic Regression, ANN, and CNN. The goal was to understand the strengths and weaknesses of each model class in the context of fashion image classification. The evaluation encompassed accuracy metrics, hyperparameter tuning, and detailed analysis using quantitative metrics such as precision, recall, and F1-score.

## Directory Structure

- `data/`: Placeholder for the Fashion MNIST dataset (not included in this repository). Data will eb downloaded and placed here after running the Jupyter notebook file.
- `FashionMNIST.py`: Single jupyter notebook file where performed data loading, cleaning, visualization, transformation, building ML models, DL models, selecting the best model for further assessment.
- `best-model-fold-0.pth`: weights file to load fold 0 of best model (see section H4 in ipynb file)
- `best-model-fold-1.pth`: weights file to load fold 1 of best model (see section H4 in ipynb file)
- `best-model-fold-2.pth`: weights file to load fold 2 of best model (see section H4 in ipynb file)



## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/N122RAHUL/ECEN-758-Data-Mining-and-Analysis-Project.git
   cd ECEN-758-Data-Mining-and-Analysis-Project

2. Run the Jupyter Notebook file from beginning to end.