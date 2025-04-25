
# Salary Prediction Using Linear Regression

This project demonstrates a **Simple Linear Regression model** built to predict the salary of an employee based on their **years of experience**. The model was implemented using **Python** and popular libraries like **Scikit-learn** and **Matplotlib**.

## Project Overview

The goal of this project is to predict the salary of employees given the years of experience they have. Using a **linear regression model**, the relationship between experience and salary is explored and used to create predictions.

## Key Concepts Covered:
- **Linear Regression**: Building a regression model to predict continuous outcomes.
- **Train-Test Split**: Dividing the dataset into training and testing sets to ensure model evaluation.
- **Model Evaluation**: Using metrics like **Mean Squared Error (MSE)** to evaluate the model's performance.
- **Data Visualization**: Plotting the predicted vs. actual values using **Matplotlib**.

## Dataset

This project uses a **salary dataset** that contains two columns:
- **YearsExperience**: The years of experience an employee has.
- **Salary**: The corresponding salary of the employee.

The dataset is simple and contains historical data of employees with varying experience levels and their respective salaries.

## Requirements

Before running this project, make sure you have the following Python libraries installed:

- `pandas`
- `matplotlib`
- `scikit-learn`

You can install them using pip:

```bash
pip install pandas matplotlib scikit-learn
```

## Usage

1. **Clone this repository:**

```bash
git clone https://github.com/yourusername/salary-prediction-linear-regression.git
cd salary-prediction-linear-regression
```

2. **Run the Python script:**

```bash
python salary_prediction.py
```

This will:
- Load the dataset
- Split the data into training and testing sets
- Train the linear regression model
- Evaluate the model using MSE
- Visualize the predicted vs. actual salary values

## Key Learnings:
- Implementing linear regression from scratch using **Scikit-learn**
- Understanding how to evaluate model performance with **MSE**
- Building confidence in machine learning model development and visualization

## Future Work
- Explore advanced regression models like **Polynomial Regression**.
- Apply the model to larger, real-world datasets.
- Improve model accuracy by experimenting with feature engineering.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
