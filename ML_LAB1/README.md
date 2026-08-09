# ML Lab 1 – Titanic Dataset

## Overview

This practical focuses on exploring and preprocessing the Titanic dataset using Python. The notebook demonstrates basic data analysis, data cleaning, outlier treatment, and preparation of the dataset for further machine learning tasks.

## Files Included

* **ML_Lab1.ipynb** – Jupyter Notebook containing the implementation.
* **Titanic-Dataset.csv** – Dataset containing passenger details and survival information.

## Work Performed

### 1. Dataset Exploration

The dataset is loaded using Pandas and examined using:

* `head()` and `tail()`
* `shape` and `info()`
* `describe()`

### 2. Handling Missing Data

Missing entries are identified using `isnull().sum()`. The missing values in `Age` are replaced with the median, while missing `Embarked` values are filled using the mode. The `Cabin` column is removed because of its large number of missing entries.

### 3. Data Validation

Duplicate records are checked to ensure that the dataset does not contain repeated observations.

### 4. Outlier Treatment

Boxplots are used to inspect numerical data for unusual observations. The IQR method is applied to identify and remove outliers from the `Age` feature.

## Tools Used

* Python 3.x
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

## How to Run

1. Install Python and the required libraries.
2. Open `ML_Lab1.ipynb` in Jupyter Notebook.
3. Keep `Titanic-Dataset.csv` in the same folder.
4. Run the notebook cells sequentially.
