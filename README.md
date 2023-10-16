# Customer Credit Scoring & Segmentation Analysis

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)

## Overview

The Customer Credit Scoring & Segmentation Analysis project aims to provide insights into a customer dataset with a focus on credit scoring. By employing advanced machine learning techniques, the project segments customers into distinct clusters, offering businesses actionable strategies tailored for each group.

## Getting Started

### Prerequisites

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

### Installation

1. Clone the repository:
```
git clone https://github.com/[your-username]/customer-credit-scoring.git
```

2. Navigate to the cloned directory and install the required libraries:
```
pip install -r requirements.txt
```

## Data Description

The dataset, `customer_data.csv`, comprises several features describing customers' behaviors and attributes, including a specific label for credit scoring. Some key columns include:

- `id`: Unique identifier for each customer.
- `fea_1`, `fea_2`, ...: Anonymized features related to customer behaviors and attributes.
- `label`: Credit score label assigned to the customer.

## Methodology

The project follows a structured approach:

1. **Data Preprocessing**: This includes handling missing values, encoding categorical variables, and scaling the data to ensure uniformity.
2. **Clustering**: KMeans clustering is used to group customers into distinct segments based on their features.
3. **Dimensionality Reduction**: PCA (Principal Component Analysis) is employed to visualize the multi-dimensional data in a 2D space.
4. **Analysis & Interpretation**: Each cluster is deeply analyzed to derive characteristics, and actionable insights are provided for businesses.
![Unknown](https://github.com/iamirrf/creditscoring/assets/112046597/58cec000-d2ee-4b97-aa2b-d1f9f4920827)


## Results

The customer base is segmented into three distinct clusters:

- **Cluster 0**: Customers requiring attention and potential retention strategies.
- **Cluster 1**: Loyal customers that can benefit from loyalty programs or exclusive offers.
- **Cluster 2**: New/exploratory customers that can be targeted with introductory promotions or onboarding programs.
![Unknown-2](https://github.com/iamirrf/creditscoring/assets/112046597/da4ad496-e29e-4905-8b4c-5564c152583d)

For a more detailed analysis and interpretation, refer to the project's main report.

## Usage

1. Ensure you have the dataset (`customer_data.csv`) in the root directory.
2. Run the main script:
```
python credit_scoring_analysis.py
```
3. The script will output a visual representation of the clusters and save a new CSV file (`customer_data_with_clusters.csv`) containing the original data along with the cluster assignments for each customer.

## Acknowledgments

I would like to thank the kaggle.com platform for curating the dataset and the indirect contributors to this project.
