# Phishing URL Detection Using Machine Learning

## Project Overview

This project builds a machine learning pipeline for detecting phishing URLs. The goal is to classify URLs as legitimate or malicious by extracting useful URL-based features and training multiple machine learning and deep learning models.

The project includes feature extraction, dataset preparation, model development, neural network experiments, and result comparison using Jupyter Notebook.

## Problem Statement

Phishing attacks are a common cybersecurity threat where attackers use deceptive URLs to trick users into sharing sensitive information. This project explores how machine learning can help detect suspicious URLs by analyzing patterns in URL structure and related features.

## Datasets

The project uses phishing and legitimate URL datasets stored in the `data/raw/` folder. These datasets are used to extract features, train models, and evaluate classification performance.

## Technologies Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
- Git
- GitHub

## Machine Learning Models Used

- Traditional classification models
- Fully Connected Neural Network (FCNN)
- GRU-based neural network
- Feature-based phishing URL classification pipeline

## Methodology

1. Data loading and preparation
2. URL feature extraction
3. Data cleaning and preprocessing
4. Train/test split
5. Model development and training
6. Neural network experimentation
7. Evaluation and result comparison

## Results and Findings

The project shows how URL-based features can be used to detect phishing links using machine learning. The notebooks include saved model outputs and training results so the project can be reviewed without rerunning every notebook immediately.

The experiments compare traditional machine learning and deep learning approaches, including FCNN and GRU-based models, to evaluate how well they classify URLs as phishing or legitimate.

## Repository Structure

```text
Phishing-URL-Detection-ML/
│
├── README.md
├── RUN_ORDER.md
├── requirements.txt
├── .gitignore
│
├── data/
│   └── raw/
│       ├── malicious_data.csv
│       ├── PhiUSIIL_Phishing_URL_Dataset.csv
│       └── tranco_58PNN-2.csv
│
└── notebooks/
    ├── 01_feature_extraction.ipynb
    ├── 02_model_development.ipynb
    ├── 03_fcnn_model.ipynb
    └── 04_gru_model_results.ipynb
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/sarakhan97/Phishing-URL-Detection-ML.git
```

2. Open the project folder:

```bash
cd Phishing-URL-Detection-ML
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Run notebooks using the order in `RUN_ORDER.md`.

## Project Purpose

This project demonstrates an end-to-end machine learning workflow for cybersecurity analytics, including feature extraction, preprocessing, classification modeling, neural network training, model evaluation, and GitHub project organization.
