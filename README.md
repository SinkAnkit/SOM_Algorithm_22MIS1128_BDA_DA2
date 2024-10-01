# SOM_Algorithm_22MIS1128_BDA_DA2
# Credit Card Fraud Detection using Self Organizing Maps (SOMs)

##This is Ankit Singh 22MIS1128 with SWE2011- Big Data Analytics DA2

## Overview

This project uses Self-Organizing Maps (SOMs), an unsupervised machine learning technique, to identify potential fraudulent credit card applications. SOMs are particularly useful for clustering and visualizing high-dimensional data in a lower-dimensional space. This project aims to spot anomalies or potential fraud by training a SOM on a dataset of credit card applications.

## Features

- Utilizes Self-Organizing Maps for unsupervised learning.
- Identifies potential fraudulent applications from a credit card dataset.
- Visualizes the results using a 2D grid of nodes, showing distances between winning nodes.
- Easy to interpret with clear output highlighting potential fraudsters.
  
## Dataset

The dataset contains credit card applications with 691 entries and multiple features, including customer IDs. The last column indicates whether the application was approved or not.

- **Credit_Card_Applications_Datasets.csv**: A file that contains the dataset with features and labels.

## Usage

### Prerequisites

- Python 3.x
- The following Python libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `MiniSom`
  - `tqdm`
  - `scikit-learn`

You can install the necessary libraries using:

```bash
pip install pandas numpy matplotlib MiniSom tqdm scikit-learn
