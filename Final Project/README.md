# Churn Prediction in Online Retail

This repository contains a Jupyter Notebook for predicting customer churn in an online retail setting using various techniques such as GAN, VAE, SMOTE, and clustering. The notebook explores several features and methodologies to improve the accuracy of churn prediction.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Data Preprocessing](#data-preprocessing)
- [Modeling Techniques](#modeling-techniques)
- [Results](#results)
- [Installation](#installation)
- [License](#license)

## Introduction
This project aims to enhance customer churn prediction in online retail by leveraging advanced data generation and clustering techniques. The notebook includes methods to generate synthetic data, handle imbalanced datasets, and perform clustering to identify patterns in customer behavior.

## Features
The notebook focuses on the following features:
- **Month of Purchase**: Adds a feature representing the month of purchase.
- **Most Common Day**: Adds a feature representing the most common day of purchase.
- **Number of Purchases**: Adds a feature representing the number of purchases made by a customer.
- **Weighted Mean Time Between Purchases**: Adds a feature representing the weighted mean time between purchases.
- **Standard Deviation of Time Between Purchases**: Adds a feature representing the standard deviation of time between purchases.

## Data Preprocessing
Data preprocessing steps include handling missing values, encoding categorical variables, and normalizing numerical features. Additionally, the dataset is augmented using SMOTE to address class imbalance.

## Modeling Techniques
The notebook employs various modeling techniques including:
- **Generative Adversarial Networks (GAN)**
- **Variational Autoencoders (VAE)**
- **Synthetic Minority Over-sampling Technique (SMOTE)**
- **Clustering Algorithms**

## Results
The results section presents the performance metrics of different models and discusses the effectiveness of each technique in improving churn prediction.
## Getting Started

### Prerequisites

- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/dednoremios/ML_2024_Aliyari.git
cd ML_2024_Aliyari
