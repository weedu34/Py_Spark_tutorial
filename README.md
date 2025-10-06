# PySpark Data Preprocessing Tutorials

This repository contains Jupyter notebooks that introduce basic data preprocessing techniques in PySpark. The tutorials are designed for beginners who want to learn how to handle missing values and prepare data for machine learning workflows.

## Tutorials

- **Tutorial 01**: Introduction to data preprocessing with PySpark  
  - Setting up a Spark session  
  - Basic data preprocessing steps

- **Tutorial 02**: Handling missing values in PySpark  
  - Dropping null values  
  - Filling null values using `Imputer`

## Requirements

- Python 3.8+  
- [Apache Spark](https://spark.apache.org/) with PySpark  
- Jupyter Notebook or JupyterLab  

You can install PySpark with:

```bash
pip install pyspark
```

## Usage

Clone this repository:

```bash
git clone https://github.com/weedu34/Py_Spark_tutorial.git
cd your-repo-name
```

## Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks and run the cells in order:

- `Tutorial_01.ipynb`  
- `Tutorial_02.ipynb`  

These tutorials use two CSV files as input data. The files are read into PySpark DataFrames and then processed to demonstrate different preprocessing techniques such as dropping and imputing missing values.

## Learning Goals

By the end of these tutorials you will be able to:

- Create and configure a Spark session in Python  
- Load CSV files into PySpark DataFrames  
- Perform basic data preprocessing steps  
- Handle missing values using both drop and imputation techniques  
