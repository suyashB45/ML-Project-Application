# Stock Market Prediction for Tata Motors Using KNN Classification and Regression

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Data](#data)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to predict the stock prices of Tata Motors using K-Nearest Neighbors (KNN) classification and regression. By leveraging historical stock data from Quandl, we aim to develop models that can help in forecasting future stock prices and making informed investment decisions.

## Project Structure

```
Tata-Motors-Stock-Prediction/
│
├── data/
│   ├── tata_motors_stock.csv      # Historical stock data
│   └── processed_data.csv         # Processed data ready for modeling
│
├── notebooks/
│   ├── data_preprocessing.ipynb   # Notebook for data cleaning and preprocessing
│   ├── knn_classification.ipynb   # Notebook for KNN classification model
│   └── knn_regression.ipynb       # Notebook for KNN regression model
│
├── src/
│   ├── data_preprocessing.py      # Script for data cleaning and preprocessing
│   ├── knn_classification.py      # Script for KNN classification model
│   └── knn_regression.py          # Script for KNN regression model
│
├── README.md
└── requirements.txt               # List of dependencies
```

## Dependencies

To run this project, you will need the following Python packages:

- pandas
- numpy
- scikit-learn
- matplotlib
- quandl

You can install these dependencies using pip:

```bash
pip install -r requirements.txt
```

## Data

The historical stock data for Tata Motors is sourced from Quandl. You need to obtain your API key from Quandl and store it in a file named `quandl_api_key.txt` in the root directory of the project.

The data folder contains:

- `tata_motors_stock.csv`: Raw historical stock data.
- `processed_data.csv`: Processed data ready for modeling.

## Usage

### Data Preprocessing

First, preprocess the data by running the data preprocessing script or notebook:

```bash
python src/data_preprocessing.py
```

Or use the Jupyter notebook:

```bash
jupyter notebook notebooks/data_preprocessing.ipynb
```

### KNN Classification

To train and evaluate the KNN classification model, run the following script:

```bash
python src/knn_classification.py
```

Or use the Jupyter notebook:

```bash
jupyter notebook notebooks/knn_classification.ipynb
```

### KNN Regression

To train and evaluate the KNN regression model, run the following script:

```bash
python src/knn_regression.py
```

Or use the Jupyter notebook:

```bash
jupyter notebook notebooks/knn_regression.ipynb
```

## Results

After running the models, you will find the results and performance metrics in the corresponding notebooks and scripts. The results will help you understand the accuracy and predictive power of the models.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


 
