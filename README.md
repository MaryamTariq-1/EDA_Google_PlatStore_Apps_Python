# Golden Projects: Playstore Apps EDA

### Google Playstore Apps - Exploratory Data Analysis (EDA)

This repository contains the Exploratory Data Analysis (EDA) of the "Google Playstore Apps" dataset. The aim of this project is to analyze user ratings, download counts, category successes, and monetization strategies to identify what drives app popularity and user engagement. This project aims to uncover key factors that app developers and marketers can leverage to enhance app visibility, improve user experience, and drive downloads.

## Project Overview

The project involves:
- Loading and cleaning the dataset
- Handling missing values
- Converting data types
- Performing feature engineering
- Visualizing the data
- Implementing clustering and regression models
- Evaluating model performance

## Dataset

The dataset used in this project contains information about apps available on the Google Playstore. The data includes details such as app names, categories, ratings, reviews, size, installs, price, type, content rating, and last updated date.

## File Structure

- `googleplaystore.csv`: The raw dataset file.
- `cleaned_googleplaystore.csv`: The cleaned dataset file.
- `googleplaystore.ipynb`: The Python script for performing EDA, feature engineering, and model training.
- `README.md`: This file.

## Requirements

- Python 3.6 or higher
- pandas
- numpy
- seaborn
- matplotlib
- missingno
- scikit-learn
- textblob
- shap

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/MaryamTariq-1/EDA_Google_PlatStore_Apps_Python.git
    ```

2. Install the required packages:
    ```bash
    pip install pandas numpy seaborn matplotlib missingno scikit-learn textblob shap
    ```

## Usage

1. Run the analysis script:
    ```bash
    jupyter notebook googleplaystore.ipynb
    ```

2. Load the cleaned dataset:
    ```python
    import pandas as pd

    df = pd.read_csv('cleaned_googleplaystore.csv')
    ```

## Exploratory Data Analysis

The EDA includes the following steps:

1. **Data Loading and Cleaning:**
   - Load the dataset and inspect the first few rows.
   - Display summary statistics and check for missing values.
   - Impute missing values in numerical and categorical columns.
   - Verify data types and convert them as necessary.

2. **Feature Engineering:**
   - Extract additional features such as year and month from the 'Last Updated' column.
   - Create new features like 'Revenue_Estimate'.

3. **Visualizations:**
   - Create histograms, box plots, scatter plots, bar plots, and heatmaps to explore the data.
   - Generate pie charts to summarize categorical data distributions.

4. **Clustering:**
   - Standardize the features and apply KMeans clustering.
   - Visualize the clusters of Playstore apps.

5. **Regression Modeling:**
   - Train linear regression, polynomial regression, random forest, and gradient boosting models to predict app ratings.
   - Evaluate the models' performance using metrics like Mean Squared Error and R^2 Score.

6. **Advanced Analysis:**
   - Perform hyperparameter tuning using GridSearchCV.
   - Conduct feature importance analysis and interpret results using SHAP values.
   - Analyze sentiment from review text using TextBlob.

## Results

The analysis provides insights into the factors influencing app popularity and user engagement on the Google Playstore. Visualizations help in understanding data distributions, correlations, and clusters. Regression models are used to predict app ratings, with the evaluation metrics indicating their performance.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any questions or inquiries, please contact:
- Your Name: [marymughal216@gmail.com]
- GitHub: [MaryamTariq-1]
```
