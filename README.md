# Titanic Data Analysis

This project aims to perform data analysis on the Titanic dataset and build predictive models to determine the survival status of passengers. The analysis includes Exploratory Data Analysis (EDA), feature analysis, transformation of categorical features into numerical ones, and training of various classifiers using Python libraries such as pandas, seaborn, and scikit-learn.

## Requirements

- Python 3.x
- pandas
- seaborn
- scikit-learn

## Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/titanic-data-analysis.git
```

2. Install the required dependencies:

```
pip install pandas seaborn scikit-learn
```

## Usage

1. Navigate to the project directory:

```
cd titanic-data-analysis
```

2. Run the script to perform EDA and feature analysis:

```
python eda_and_feature_analysis.py
```

This script will explore the dataset, visualize the distributions of features, and analyze the relationship between features and survival status.

3. Transform remaining categorical features into numerical ones and standardize numerical data:

```
python transform_data.py
```

This script will convert categorical features into numerical ones using techniques like one-hot encoding and standardize numerical data to ensure that all features have the same scale.

4. Train models using Logistic Regression, SVM, Decision Tree, and Random Forest classifiers:

```
python train_models.py
```

This script will train the classifiers and evaluate their performance using accuracy, precision, recall, and F1 metrics.

5. Choose hyperparameters using k-fold cross-validation, Grid Search, and Random Search:

```
python hyperparameter_tuning.py
```

This script will perform hyperparameter tuning using k-fold cross-validation, Grid Search, and Random Search to find the best hyperparameters for each classifier.

6. Train the models on better hyperparameters and measure the metrics:

```
python train_with_best_hyperparameters.py
```

This script will train the classifiers using the best hyperparameters obtained from the hyperparameter tuning step and measure their performance metrics.

## Results

The results include the accuracy, precision, recall, and F1 scores of the trained models. Additionally, visualizations may be provided to illustrate the performance of the models.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
