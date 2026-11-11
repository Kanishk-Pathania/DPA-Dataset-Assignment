## Data Preparation and Analysis — MNIST Handwritten Digits
**Subject Code:** MTAI-PE1-20
DPA assignment for MNIST dataset from Kaggle. Using Python, NumPy, Pandas, Matplotlib, and Plotly,  perform data preprocessing, Exploratory Data Analysis (EDA), data visualization, and feature engineering.

---

## 📌 Project Description

This project performs end-to-end **Data Preparation and Analysis** on the **MNIST Handwritten Digits** dataset using Python. It covers:

- Loading and exploring the dataset with **NumPy** and **Pandas**
- Converting image pixel data into NumPy arrays and Pandas DataFrames
- Data cleaning and preprocessing (missing values, duplicates, invalid pixels, outliers)
- **Exploratory Data Analysis (EDA)** with at least 5 documented observations
- Static visualizations using **Matplotlib** and **Seaborn** (digit images, pixel histograms, class distribution, correlation heatmap)
- Interactive visualizations using **Plotly**
- **Feature Engineering** (pixel statistics, image-level features, label encoding, scaling)
- Final analysis, conclusions, and limitations

---

## 📂 Dataset

| Field | Details |
|---|---|
| **Dataset Name** | MNIST Handwritten Digits Dataset |
| **Source** | [Kaggle — MNIST in CSV](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv) |
| **Files Used** | `mnist_train.csv`, `mnist_test.csv` |
| **Format** | CSV — each row is one 28×28 grayscale image flattened into **784 pixel columns** (values 0–255), plus a `label` column (0–9) |
| **Description** | The MNIST dataset is a classic benchmark for image classification. It contains 70,000 grayscale images of handwritten digits (0–9). Each image is 28×28 pixels. |
| **License** | CC0: Public Domain (verify on the Kaggle page before redistributing) |

> ⚠️ **Note:** The CSV files are large (~100 MB). Confirm the dataset license on Kaggle before uploading the CSV to this repository. If redistribution is not permitted, keep only the download link above.

---

## 🎯 Problem Statement

Analyze the MNIST handwritten digit dataset to understand the **pixel-level characteristics of each digit class**, identify distinguishing features, and prepare the data for potential downstream machine learning tasks.

### Objectives
1. Load and structure the flattened image data for analysis.
2. Clean and validate the dataset (missing values, duplicates, pixel ranges).
3. Explore pixel intensity distributions and per-class patterns.
4. Visualize digits and statistical summaries using Matplotlib and Plotly.
5. Engineer meaningful new features from raw pixel data.
6. Summarize findings and provide recommendations.

---

## 🗂️ Repository Structure
