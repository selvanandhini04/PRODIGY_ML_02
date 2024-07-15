# Customer Segmentation using K-Means Clustering

This project demonstrates the use of a K-means clustering algorithm to segment customers of a retail store based on their purchase history. The notebook includes data preprocessing, model training, and visualization of clusters.

## Contents

- `Task_2_K_Means_Clustering.ipynb`: Jupyter notebook containing the code for the project.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required packages using the following command:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Data

The dataset used for this project contains customer information including:
- Customer ID
- Age
- Gender
- Income
- Spending Score

## Notebook Overview

### 1. Import Libraries
The necessary libraries for data manipulation, visualization, and model building are imported.

### 2. Load Data
The customer dataset is loaded using pandas.

### 3. Data Exploration
Exploratory Data Analysis (EDA) is performed to understand the distribution and relationship of features.

### 4. Data Preprocessing
Data cleaning and preprocessing steps are applied, including handling missing values and encoding categorical variables.

### 5. K-Means Clustering
A K-means clustering algorithm is applied to segment customers into different groups based on their features.

### 6. Visualization
The clusters are visualized using scatter plots to understand the grouping of customers.

## How to Use

1. Clone the repository:
```bash
git clone https://github.com/your_username/customer-segmentation.git
```

2. Navigate to the project directory:
```bash
cd customer-segmentation
```

3. Open the Jupyter notebook:
```bash
jupyter notebook Task_2_K_Means_Clustering.ipynb
```

4. Run the notebook cells to execute the code.

## Results

The notebook outputs the clusters of customers and visualizes them in scatter plots. This helps in understanding the different segments of customers based on their purchase history.
