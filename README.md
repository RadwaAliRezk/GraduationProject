# Zomato Restaurant Data Science Project

## Overview

This notebook presents a comprehensive data science project focusing on Zomato restaurant data. The project follows the data science lifecycle, encompassing project understanding, data mining and preprocessing, data exploration, model data, and result interpretation.

## Data Source

The dataset used in this project is available on Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants).

## Project Phases

### Project Understanding

In this phase, the project's scope and objectives are outlined. The dataset is introduced, and the key tasks to be performed are highlighted.

### Data Mining and Preprocessing

The notebook covers the following tasks in data mining and preprocessing:

- Data Inspection
- Data Cleaning and Preprocessing

### Data Exploration

Exploratory Data Analysis (EDA) is performed by answering the following questions:

1. Which listed_in(type) has the highest target?
2. What are the most popular cities that have restaurants?
3. Does offering online orders (Yes/No) have an impact on a restaurant's success (0/1)?
4. Is there a relationship between cost and rate number?
5. Correlation between location and listed_in(city) columns to be able to drop location if the listed_in(city) column is dependent on it.
6. What are the rest_type that have a high rate?
7. What are the famous rest_types in each location?

### Data Preparation and Modeling

This phase includes the following tasks:

- Label Encoding and One-Hot Encoding
- Model Selection: Decision Tree, Random Forest, Logistic Regression, KNN

### Result Interpretation

Each model is evaluated using applicable methods, and the conclusion is drawn based on the evaluation results. In this case, the conclusion is that Random Forest is the preferred model due to its highest precision and recall. These metrics are emphasized due to imbalanced data.

## Usage

1. Clone the repository.
2. Download the dataset from the provided Kaggle link.
3. Open the notebook in a Jupyter environment or any compatible Python environment.
4. Run the notebook cells to perform data exploration, preparation, and modeling.
5. Analyze the results and interpretations.

## Dependencies

The notebook requires the following Python libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

Other standard libraries.


