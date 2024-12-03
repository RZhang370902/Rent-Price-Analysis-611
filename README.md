# Rent Price Analysis

This project aims to analyze and predict rental prices using various machine learning models. The dataset used is sourced from [Kaggle](https://www.kaggle.com/datasets/sergiygavrylov/25000-canadian-rental-housing-market-june-2024?resource=download).

## Project Overview

The goal of this project is to predict the price of rental properties based on features such as location, type, and size. We compare the performance of different regression models including Linear Regression, Random Forest, K-NN, and Gradient Boosted Regression Trees.

## Dataset

- **Source**: [Kaggle](https://www.kaggle.com/datasets/sergiygavrylov/25000-canadian-rental-housing-market-june-2024?resource=download)
- **Description**: The dataset contains information about rental properties in Canada, including features like city, province, address, latitude, longitude, lease term, type, price, beds, baths, square feet, and more.

## Setup

To run this project, you need to have Python installed along with the following packages:

- numpy
- pandas
- scikit-learn
- seaborn
- matplotlib

You can install the required packages using:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/RZhang370902/Rent-Price-Analysis-611.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Rent-Price-Analysis-611
   ```

3. Open the Jupyter notebook:

   ```bash
   jupyter notebook notebooks/611_Project_Wu_Zhang.ipynb
   ```

4. Run the cells in the notebook to load the data, train models, and evaluate their performance.

## Results

The models were evaluated based on their R2 scores. Here are the results:

| Model                              | R2 Score |
|------------------------------------|----------|
| Linear Regression (Non-negative)   | 0.6013   |
| Random Forest Regression           | 0.8801   |
| K-NN Regression                    | 0.8776   |
| Gradient Boosted Regression Tree   | 0.7580   |

**Conclusion**: Random Forest Regression and K-NN Regression both performed well, with Random Forest slightly outperforming K-NN. However, K-NN trains faster, making it a recommended choice for this problem.

## Acknowledgments

- Instructor: Dr. L. Dawson
- Contributors: Cory Wu, Rick Zhang

