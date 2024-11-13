# ML-Playground

This repository contains my machine learning exercises and experiments as part of my course on Machine Learning. The focus is on using **PyTorch** and **Scikit-Learn**, based on the book:

**Machine Learning with PyTorch and Scikit-Learn**  
by *Sebastian Raschka*

## Table of Contents
1. [Overview](#overview)
2. [Technologies](#technologies)
3. [Setup](#setup)
4. [Projects](#projects)
5. [License](#license)

## Overview
This repository is a collection of Jupyter Notebooks that document my journey in learning machine learning. It includes practical implementations of various algorithms, experiments, and case studies following the chapters of the book.

The primary focus is on:
- Data preprocessing
- Training machine learning models
- Model evaluation and optimization
- Implementing deep learning using PyTorch

**Instructor**: Dr. Seyed Mojtaba Sabbagh-Jafari

## Technologies
- **Python 3.x**
- **Jupyter Notebook**
- **Scikit-Learn**
- **NumPy & Pandas**
- **Matplotlib**

## Setup

To run the code in this repository, follow these steps to set up a virtual environment and install the required libraries:

1. Clone this repository:
    ```bash
    git clone https://github.com/Reza-Nonva/ML-playground.git
    cd ML-Playground
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:

   - On **Windows**:
     ```bash
     venv\Scripts\activate
     ```

   - On **macOS/Linux**:
     ```bash
     source venv/bin/activate
     ```

4. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

You are now ready to run the Jupyter Notebooks!

-----------
## Projects

1. **Breast Cancer Classification**
   - **Description**: In this notebook, I experimented with four popular models—Perceptron, AdalineGD, Logistic Regression,
   and SVM(using linear and RBF kernels)—to classify breast cancer data. I walked through each step carefully,
   testing and comparing the performance of the models.
   - **Notebook**: [Breast_Cancer_Classification.ipynb](notebooks/Breast_Cancer_Classification.ipynb)



2. **Dimensionality Reduction Techniques**
   - **Description**: In this notebook, I explored three widely-used dimensionality reduction techniques:
   Principal Component Analysis (PCA), Linear Discriminant Analysis (LDA), and 
   t-Distributed Stochastic Neighbor Embedding (t-SNE). I implemented each method step-by-step, comparing how they
   transform the dataset to lower dimensions and discussing their applications. 
   The goal was to observe how each technique preserves data structure and improves data visualization,
   particularly when working with high-dimensional data.
   - **Notebook**: [Dimensionality_Reduction.ipynb](notebooks/Dimensionality_Reduction.ipynb)

This list will grow as I progress through the book.

## License
This repository is licensed under the MIT License. See the [LICENSE](https://github.com/Reza-Nonva/ML-playground/blob/main/LICENSE) file for more details.