# house-price-prediction
## Overview

This project aims to predict house prices using a linear regression model. The model is built and evaluated using the dataset from the [Kaggle House Prices - Advanced Regression Techniques competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data). The dataset includes various features of houses, such as square footage, number of bedrooms, and number of bathrooms. The goal is to develop a model that accurately predicts house prices based on these features.

## Dataset
The dataset consists of two primary files:
- `train.csv`: Training data with features and target values.
- `test.csv`: Test data with features only (no target values).

### Data Description

The `train.csv` and `test.csv` files contain the following features:
#### Features

- **Id**: Identifier for each home.
- **MSSubClass**: The building class.
- **MSZoning**: The general zoning classification.
- **LotFrontage**: Linear feet of street connected to property.
- **LotArea**: Lot size in square feet.
- **Street**: Type of road access.
- **Alley**: Type of alley access.
- **YearBuilt**: Original construction date.
- **YearRemodAdd**: Remodel date.
- **RoofStyle**: Type of roof.
- **OverallQual**: Overall material and finish quality (1 to 10 scale).
- **OverallCond**: Overall condition rating (1 to 10 scale).
- **MasVnrType**: Masonry veneer type.
- **MasVnrArea**: Masonry veneer area in square feet.
- **ExterCond**: Condition of exterior material.
- **ExterQual**: Quality of exterior material.
- **Foundation**: Type of foundation.
- **BsmtQual**: Height of basement.
- **BsmtCond**: General condition of basement.
- **BsmtExposure**: Walkout or garden level basement walls.
- **BsmtFinType1**: Type of basement finished area.
- **BsmtFinSF1**: Type 1 finished square feet.
- **BsmtFinType2**: Type of basement finished area (if applicable).
- **BsmtFinSF2**: Type 2 finished square feet.
- **BsmtUnfSF**: Unfinished square feet of basement area.
- **TotalBsmtSF**: Total square feet of basement area.
- **Heating**: Type of heating.
- **HeatingQC**: Heating quality and condition.
- **CentralAir**: Central air conditioning.
- **Electrical**: Electrical system.
- **1stFlrSF**: First floor square feet.
- **2ndFlrSF**: Second floor square feet.
- **GrLivArea**: Above grade (ground) living area square footage.
- **FullBath**: Full bathrooms above grade.
- **HalfBath**: Half bathrooms above grade.
- **BedroomAbvGr**: Bedrooms above grade.
- **KitchenAbvGr**: Kitchens above grade.
- **KitchenQual**: Kitchen quality.
- **TotRmsAbvGrd**: Total rooms above grade.
- **Functional**: Home functionality rating.
- **Fireplaces**: Number of fireplaces.
- **FireplaceQu**: Fireplace quality.
- **GarageType**: Garage location.
- **GarageFinish**: Interior finish of the garage.
- **GarageCars**: Size of garage in car capacity.
- **GarageArea**: Size of garage in square feet.
- **GarageQual**: Garage quality.
- **GarageCond**: Garage condition.
- **PavedDrive**: Paved driveway.
- **PoolQC**: Pool quality.
- **Fence**: Fence quality.
- **MiscFeature**: Miscellaneous feature not covered in other categories.
- **MiscVal**: Value of miscellaneous feature.
- **SaleType**: Type of sale.
- **SaleCondition**: Condition of sale.

#### Target Variable

- **SalePrice**: The target variable, price of the house.

## Project Structure

- `data/`: Contains the dataset files (`train.csv`, `test.csv`).
- `notebooks/`: Jupyter notebooks for exploratory data analysis (EDA) and model implementation.
- `scripts/`: Python scripts for data preprocessing, model training, and evaluation.
- `models/`: Saved models and model-related files.
- `requirements.txt`: List of dependencies required to run the project.
- `README.md`: Documentation for the project (this file).
- `LICENSE`: License information for the project.

## Installation

To set up and run the project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/dimpaldm/house-price-prediction.git
    cd house-price-prediction
    ```

2. **Set up a virtual environment** (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Download the dataset** from Kaggle and place it in the `data/` directory. Ensure you have the following files:
    - `train.csv`
    - `test.csv`

## Usage

### Jupyter Notebooks

Explore the data and model implementation by opening the Jupyter notebooks:

**Download the dataset** from Kaggle and place it in the `data/` directory.

## Running the Model

To train and evaluate the linear regression model, follow these steps:

1. **Run the training script**:
    ```bash
    python scripts/train_model.py
    ```

2. **View the results**:
   After the script runs, evaluation metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE), will be displayed in the terminal.

## Model Evaluation

The performance of the model is assessed using the following metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

These metrics are printed out after running the training script.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Special thanks to [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) for providing the dataset used in this project.

