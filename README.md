# Titanic Dataset - Exploratory Data Analysis

This repository contains my work on **Exploratory Data Analysis (EDA)** using the famous **Titanic dataset**. The goal of this project is to explore and visualize survival trends on the Titanic based on various features such as age, gender, passenger class, and more.

## Project Overview

The focus was on:

1. **Data Loading and Cleaning**: 
   - Loaded the Titanic dataset from a CSV file.
   - Handled missing values and outliers.
   - Converted categorical data into numerical format using encoding techniques.

2. **Univariate Analysis**:
   - Analyzed individual features such as `Age`, `Fare`, `Survived`, etc.
   - Visualized distributions using histograms, box plots, and count plots.

3. **Bivariate Analysis**:
   - Examined the relationship between survival status and various features (`Sex`, `Pclass`, `Embarked`, etc.).
   - Created visualizations like pair plots, heatmaps, and bar plots to explore correlations and patterns.

4. **Survival Trend Visualization**:
   - Visualized survival trends based on `Pclass`, `Sex`, and `Age` using Seaborn and Matplotlib.

## Skills Used
- **Data Cleaning**: Handling missing values, encoding categorical variables, and removing outliers.
- **Data Analysis**: Analyzing relationships between features and drawing insights.
- **Visualization**: Using **Matplotlib** and **Seaborn** to create plots and visualizations.

## Libraries Used
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For visualizing data.
- **Seaborn**: For creating more advanced visualizations.

## Dataset

The dataset used is the **Titanic dataset** from Kaggle, which contains information about passengers aboard the ill-fated ship. The features include details such as:

- **Survived**: Whether the passenger survived or not.
- **Pclass**: Passenger class (1st, 2nd, or 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **Fare**: The fare the passenger paid for the ticket.
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## How to Run

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/titanic-eda.git
   ```

2. Navigate to the project directory:
   ```bash
   cd titanic-eda
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebook:
   ```bash
   jupyter notebook Titanic_EDA.ipynb
   ```

## Results

By the end of this project, you'll be able to identify patterns such as:
- The survival rate across different passenger classes.
- The significant impact of gender on survival probability.
- How age and fare correlate with survival trends.

## Next Steps

- Implement advanced machine learning techniques to predict survival on the Titanic.
- Explore feature engineering to improve model performance.

## Contributing

Feel free to fork this repository, create a branch, and submit a pull request with any improvements or suggestions. Contributions are always welcome!

Make sure to replace "yourusername" in the clone URL with your actual GitHub username. Would you like to make any adjustments or add further sections?
