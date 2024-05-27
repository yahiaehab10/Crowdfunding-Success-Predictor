# Project Overview

This repository contains a collection of Jupyter notebooks and a PDF file related to data processing, machine learning, and exploratory data analysis. The project is structured as follows:

## Contents

1. [Preprocessing Notebook](#1-preprocessing-notebook)
2. [SparkML Models](#2-sparkml-models)
3. [Queries](#3-queries)
   - [Success Rate by Main Category and USD Goal](#31-success-rate-by-main-category-and-usd-goal)
   - [Highest Countries with Total Pledged Amount in Euros](#32-highest-countries-with-total-pledged-amount-in-euros)
   - [Average Backers and Pledged by Main Category](#33-average-backers-and-pledged-by-main-category)
4. [Description Document](#4-description-document)

## 1. Preprocessing Notebook

**File:** `preprocessing_notebook.ipynb`

This notebook contains data preprocessing steps necessary for preparing the dataset for further analysis and machine learning. It includes data cleaning, transformation, and feature engineering processes.

## 2. SparkML Models

**File:** `sparkml_models.ipynb`

This notebook demonstrates the implementation of various machine learning models using Apache Spark's MLlib. It includes steps for model training, evaluation, and comparison of different algorithms.

## 3. Queries

The `Queries` directory contains notebooks that perform specific exploratory data analysis tasks.

### 3.1 Success Rate by Main Category and USD Goal

**File:** `Queries/Success_rate_by_Main_Category_and_USD_Goal.ipynb`

This notebook analyzes the success rate of projects by their main category and the goal amount in USD. It provides insights into which categories and goal ranges are more likely to succeed.

### 3.2 Highest Countries with Total Pledged Amount in Euros

**File:** `Queries/Highest_Countries_with_Total_Pledged_Amount_in_Euros.ipynb`

This notebook identifies the countries with the highest total pledged amounts in Euros. It helps in understanding the geographical distribution of funding.

### 3.3 Average Backers and Pledged by Main Category

**File:** `Queries/Average_Backers_and_Pledged_by_Main_Category.ipynb`

This notebook calculates the average number of backers and the average pledged amount for each main category. It provides insights into the popularity and funding levels of different categories.

## 4. Description Document

**File:** `Description.pdf`

This PDF document provides a detailed description of the project, including objectives, methodologies, and key findings. It serves as a comprehensive guide to understanding the scope and results of the project.

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/yahiaehab10/Crowdfunding-Success-Predictor.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Crowdfunding-Success-Predictor
    ```
3. Open the Jupyter notebooks using JupyterLab or Jupyter Notebook:
    ```bash
    jupyter lab
    # or
    jupyter notebook
    ```

## Requirements

- Jupyter Notebook or JupyterLab
- Apache Spark
- Python libraries: pandas, numpy, matplotlib, seaborn, etc.

## Acknowledgments

- Special thanks to the contributors and the community for their support.
- References and sources of data used in this project.

