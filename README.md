# Housing Price Prediction with Linear Regression

This project focuses on predicting house prices using a **Linear Regression** model. It demonstrates a complete machine learning workflow, from data collection and exploration to model training, evaluation, and visualization.

---

## Project Overview

The goal of this project is to build a predictive model that can estimate house prices based on various features of a house. We utilize a dataset containing information about housing properties and apply linear regression, a fundamental **supervised learning algorithm**, to achieve this.

---

## Challenges Addressed

This project addresses key challenges in a typical machine learning pipeline:

1.  **Data Collection**: Obtaining and loading a dataset with numerical features and a target variable for prediction.
2.  **Data Exploration and Cleaning**: Understanding dataset structure, handling missing values (though none were present in this dataset), and ensuring data quality, including the critical step of handling categorical features.
3.  **Feature Selection**: Identifying relevant features that contribute significantly to the predictive model's accuracy.
4.  **Model Training**: Implementing and training a Linear Regression model using `Scikit-Learn`.
5.  **Model Evaluation**: Assessing the model's performance on unseen data using metrics such as Mean Squared Error (MSE) and R-squared (R²).
6.  **Visualization**: Creating insightful visualizations to illustrate the relationship between predicted and actual values, and to analyze model residuals.

---

## Dataset

The dataset used in this project is `Housing.csv`. It contains various features of houses, including:
* `price`: The target variable (house price).
* `area`: Size of the house.
* `bedrooms`: Number of bedrooms.
* `bathrooms`: Number of bathrooms.
* `stories`: Number of stories.
* `mainroad`: Proximity to a main road (Yes/No).
* `guestroom`: Presence of a guest room (Yes/No).
* `basement`: Presence of a basement (Yes/No).
* `hotwaterheating`: Presence of hot water heating (Yes/No).
* `airconditioning`: Presence of air conditioning (Yes/No).
* `parking`: Number of parking spots.
* `prefarea`: Proximity to a preferred residential area (Yes/No).
* `furnishingstatus`: Furnishing status (Furnished, Semi-furnished, Unfurnished).

---

## Project Structure

* `4.Predicting House Prices with Linear Regression.ipynb`: The main Jupyter Notebook containing all the code for data loading, exploration, cleaning, feature engineering, model training, evaluation, and visualization.
* `Housing.csv`: The dataset used for this project.
* `README.md`: This file, providing an overview of the project.

---

## How to Run the Project

To run this project on your local machine, follow these steps:

### Prerequisites

* **Python 3.x**
* **Jupyter Notebook**
* Required Python libraries:
    * `pandas`
    * `numpy`
    * `matplotlib`
    * `seaborn`
    * `scikit-learn`

## Installation

To run this project locally, you'll need Python and several libraries.

1.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

2.  **Install the required libraries:**
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn scipy
    ```

---
## 📈 Model Evaluation Metrics

The model's performance is assessed using the following metrics:

- **Mean Squared Error (MSE)**:  
  Measures the average of the squares of the errors. It indicates the average squared difference between the estimated values and the actual values.  
  _Lower MSE values indicate better model performance._

- **R-squared (R²)**:  
  Represents the proportion of variance in the dependent variable that is predictable from the independent variables.  
  _An R² value closer to 1 indicates a better fit of the model to the data._

---

## 📊 Visualizations

The notebook includes several visualizations to help understand both the dataset and the model's performance:

- **Correlation Heatmap**  
  Displays linear relationships between features. Helps identify multicollinearity and key predictors.

- **Actual vs. Predicted Prices (Scatter Plot)**  
  Provides a visual assessment of how well the model’s predictions match actual values.

- **Residuals Distribution Histogram**  
  Shows whether prediction errors (residuals) are normally distributed around zero — a sign of a well-fitting model.

- **Residuals vs. Predicted Values (Scatter Plot)**  
  Helps detect non-random patterns in the errors, which could indicate issues like heteroscedasticity or model bias.

---

