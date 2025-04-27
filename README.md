# Tehran House Price Analysis

This Jupyter Notebook (`houseprice.ipynb`) analyzes house price data for Tehran. It includes data loading, cleaning, feature engineering, and exploratory data analysis.

## Libraries Used

* **pandas:** For data manipulation and analysis.
* **numpy:** For numerical operations.
* **matplotlib.pyplot:** For creating visualizations.
* **seaborn:** For enhanced data visualization.

## Data Description

The data is contained in the `housePrice.csv` file and includes the following columns:

* **Area:** Area of the house.
* **Room:** Number of rooms.
* **Parking:** Availability of parking (True/False).
* **Warehouse:** Availability of warehouse (True/False).
* **Elevator:** Availability of elevator (True/False).
* **Address:** Address of the house.
* **Price:** Price of the house.
* **Price(USD):** Price of the house in USD.

## Data Processing

The notebook performs the following data processing steps:

1.  **Data Loading:** Loads the data from `housePrice.csv` into a pandas DataFrame.
2.  **Data Inspection:**
    * Displays the first and last 5 rows of the DataFrame.
    * Displays 5 random samples of the data.
    * Analyzes and changes column types, specifically converting the 'Area' column to integer type after cleaning it.
3.  **Feature Engineering:**
    * Adds a new column `Price(1milion_T)` by converting the price to millions of Toman.
    * Adds a new column `Price(per square meter)` to calculate the price per square meter.

## Exploratory Data Analysis and Visualization

The notebook includes exploratory data analysis and visualizations to understand the dataset:

* **Distributions:** Histograms and box plots are used to visualize the distributions of `Area`, `Price(1milion_T)`, and `Price(per square meter)`.
* **Outlier Analysis:** Outliers are identified and analyzed in the numerical features.
* **Categorical Data Analysis:**
    * Count plots are used to show the distribution of houses across different `Address`.
    * Pie charts visualize the availability of `Parking`, `Warehouse`, and `Elevator`, as well as the distribution of the number of `Room`.
* **Bivariate Analysis:** Scatter plots and heatmaps are used to explore relationships between different variables.
* **Correlation Analysis:** Correlation between numerical features is calculated and visualized.

## How to Use

1.  **Prerequisites:**
    * Python 3.x
    * pandas
    * numpy
    * matplotlib
    * seaborn
2.  **Installation:**
    * Install the required libraries using pip:
        ```bash
        pip install pandas numpy matplotlib seaborn
        ```
3.  **Execution:**
    * Place the `housePrice.csv` file in the same directory as the notebook.
    * Run the Jupyter Notebook (`houseprice.ipynb`) to execute the analysis.


# Price-House-Analysis-1
