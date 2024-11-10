# CCPP Energy Output Prediction

This project focuses on predicting the power output (PE) of a Combined Cycle Power Plant (CCPP) based on various environmental and operational factors. The dataset used includes attributes like ambient temperature, pressure, humidity, and wind speed, and aims to predict the plant's energy output.

## Project Overview

The goal of this project is to build predictive models to estimate the power output (PE) using machine learning algorithms, specifically:

- **Linear Regression**: A basic regression model to predict continuous values.
- **Random Forest Regressor**: A more advanced ensemble method based on decision trees.

### Steps involved in the project:
1. **Data Exploration and Visualization**: Understand the dataset and its relationships.
2. **Model Training**: Train Linear Regression and Random Forest models on the dataset.
3. **Model Evaluation**: Evaluate both models using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score.
4. **Model Comparison**: Compare both models' performance and select the best-performing model.
5. **Visualization**: Visualize predictions vs actual power output.

## Dataset

The dataset is loaded from a CSV file and consists of the following columns:

- **AT**: Ambient Temperature (in Celsius)
- **V**: Exhaust Vacuum (in mmHg)
- **AP**: Ambient Pressure (in atm)
- **RH**: Relative Humidity (in %)
- **PE**: Power Output (in MW) - This is the target variable.

## Dependencies

This project uses the following Python libraries:

- `pandas`: For data manipulation.
- `numpy`: For numerical operations.
- `matplotlib`: For data visualization.
- `seaborn`: For statistical data visualization.
- `sklearn`: For machine learning models and evaluation metrics.

You can install the required dependencies using:

```bash
pip install -r requirements.txt
