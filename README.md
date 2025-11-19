Here is the README for your `PRODIGY_ML_01` repository.

-----

# PRODIGY\_ML\_01: House Price Prediction

A machine learning project that implements a linear regression model to predict residential house prices based on property features. This model helps in understanding the relationship between various housing characteristics (like square footage, number of bedrooms/bathrooms) and their market value.

## 📌 Project Overview

Predicting housing prices is a fundamental problem in real estate analytics. In this project, we use the "House Price India" dataset to build a predictive model using Linear Regression.

**Key Goals:**

  * Preprocess and clean the housing data.
  * Analyze the correlation between different features and house prices.
  * Train a Linear Regression model to predict prices for new data.
  * Evaluate the model's performance using standard metrics.

## 📂 Dataset

The project uses the **House Price India.csv** file included in the repository.

  * **Features:**
      * The dataset contains various attributes of houses such as the number of bedrooms, bathrooms, living area, lot area, condition of the house, and the year it was built, among others.
      * **Target Variable:** Price

## 🛠️ Technologies Used

  * **Python**: Primary programming language.
  * **Pandas**: For data manipulation and analysis.
  * **NumPy**: For numerical computations.
  * **Matplotlib & Seaborn**: For data visualization (correlation heatmaps, scatter plots, etc.).
  * **Scikit-learn**: For model building, training, and evaluation.

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Harsh-4210/PRODIGY_ML_01.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd PRODIGY_ML_01
    ```
3.  **Install dependencies:**
    Ensure you have Python installed. You can install the required libraries using pip:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```
4.  **Launch the Notebook:**
    Open the Jupyter Notebook to view the code and analysis.
    ```bash
    jupyter notebook "Task_01_HousePricePrediction.ipynb"
    ```

## 📊 Methodology

1.  **Data Loading & Exploration:**
      * Loading `House Price India.csv` into a Pandas DataFrame.
      * Checking for missing values and understanding data distribution.
2.  **Data Preprocessing:**
      * Handling null values (if any).
      * Selecting relevant features for the regression model.
      * Splitting the data into training and testing sets.
3.  **Model Training:**
      * Initializing the Linear Regression model from Scikit-learn.
      * Fitting the model on the training data.
4.  **Evaluation:**
      * Predicting prices on the test set.
      * Calculating metrics like **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R-squared score** to assess accuracy.

## 📈 Results

  * The model provides a continuous output representing the estimated price of a house based on its inputs.
  * Visualizations such as "Actual vs Predicted Prices" plots are used to demonstrate the model's effectiveness.

## 🤝 Contributing

Contributions are welcome\! If you'd like to improve the feature engineering or try more advanced models (like Random Forest or Gradient Boosting), feel free to fork the repo and submit a pull request.

## 📜 License

This project is open-source and available for educational purposes.
