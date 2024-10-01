# SOM_Algorithm_22MIS1128_BDA_DA2
# Credit Card Fraud Detection using Self Organizing Maps (SOMs)

## This is Ankit Singh 22MIS1128 with SWE2011- Big Data Analytics DA2

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


## Steps to Execute

1. **Clone the repository**:

    ```bash
    git clone https://github.com/sinkankit/credit-card-fraud-som.git
    cd credit-card-fraud-som
    ```

2. **Upload or ensure the dataset is in place**:

    Make sure the file `Credit_Card_Applications_Datasets.csv` is in the project directory. If not, download the dataset and place it in the directory.

3. **Run the Jupyter Notebook**:

    Open the `SOM_Fraud_Detection.ipynb` file in Jupyter or Google Colab.

    If you are using Colab, upload your dataset or access it via Google Drive or Kaggle as described in the notebook.

4. **Train the SOM**:

    The notebook includes training the Self-Organizing Map on the credit card application data using the following parameters:
    - SOM grid: 10x10 nodes
    - Sigma: 1.0
    - Learning rate: 0.5
    - 100 iterations

5. **Visualize and Identify Frauds**:

    After training, the notebook visualizes the SOM and highlights the customers whose applications might be fraudulent. The potential fraudsters are printed out by customer ID.

## Results
![Alt text]("E:\SOM\som_grid.png")

## Output

The final output of the notebook will print the **Customer IDs** of potential fraudulent credit card applicants, allowing the financial institution to review these cases further.

### Example Output:

```bash
Fraud Customer IDs:
15720644
15746258
15700511
15761158
15666166
15605872
15665087

