# **Point Classifier - Neural Network Implementation**  

This repository provides a **didactic implementation of point classification** using neural networks. The project focuses on **generating and classifying a circular dataset (concentric rings) using multiple machine learning frameworks**, including **PyTorch, Keras, and Scikit-Learn**.  

## **Table of Contents**  
- [Introduction](#introduction)  
- [Features](#features)  
- [Requirements](#requirements)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results](#results)  
- [License](#license)  

## **Introduction**  

The main goal of this repository is to provide a **step-by-step guide** to implementing a **neural network for point classification**, comparing the most popular frameworks in deep learning:  
- **PyTorch**  
- **Keras (TensorFlow backend)**  
- **Scikit-Learn**  

By using a synthetic dataset of concentric circles, this project helps users **understand the strengths and differences** between these frameworks in a practical way.  

## **Features**  

✅ **Dataset Generation**: Creates a non-linearly separable dataset using `make_circles` from `sklearn.datasets`.  
✅ **Multi-framework Implementation**: Compares PyTorch, Keras, and Scikit-Learn for neural network classification.  
✅ **Visualization**: Plots decision boundaries and training metrics.  
✅ **Didactic Approach**: Designed for learners and practitioners to understand neural network implementation basics.  

## **Requirements**  

- Python 3.x  
- PyTorch  
- TensorFlow / Keras  
- Scikit-Learn  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

## **Installation**  

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/FullFran/Point_classifier.git
   cd Point_classifier
   ```

2. **Install dependencies**:  
   ```bash
   pip install numpy matplotlib scikit-learn torch tensorflow keras jupyter
   ```

3. **Run Jupyter Notebook**:  
   ```bash
   jupyter notebook
   ```
   Then open and run `make_circles.ipynb`.  

## **Usage**  

1. **Generate the dataset**:  
   - Uses `sklearn.datasets.make_circles()` to create a **non-linearly separable dataset**.  

2. **Train neural networks**:  
   - Implements models using **PyTorch, Keras, and Scikit-Learn**.  
   - Compares performance, training times, and convergence behavior.  

3. **Analyze Results**:  
   - Visualizes **decision boundaries** of different models.  
   - Evaluates accuracy and loss curves.  

## **Results**  

📌 **Visualization of dataset**: Scatter plots of training data.  
📌 **Decision boundary comparison**: How different models classify points.  
📌 **Performance metrics**: Training loss and accuracy curves for each framework.  




