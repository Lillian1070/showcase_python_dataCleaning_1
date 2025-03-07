# Data Cleaning with Python


### Outline

- Project Overview
- Dataset Used
- Key Findings & Adjustments
- Libraries Used


## Project Overview
This project demonstrates essential data-cleaning techniques using Python libraries such as `Pandas` and `NumPy`. The dataset is processed through several preprocessing steps, including:

- Removing duplicate entries to ensure data integrity
- Handling outlier and missing values through imputation or removal
- Standardizing data formats for consistency across the dataset
- Transforming features to ensure the data is clean, suitable, and well-prepared for analysis or modeling (optional)

These steps prepare the data for more accurate analysis and modeling.

You can view the full process in the Jupyter Notebook in this repo [here](https://github.com/Lillian1070/showcase_python_dataCleaning_1/blob/main/kaggle_coffeeBean_dataCleaning.ipynb). 


## Dataset Used
The dataset used in this project is sourced from Kaggle. You can access it [here](https://www.kaggle.com/datasets/fatihb/coffee-quality-data-cqi).


## Key Findings & Adjustments
During the data-cleaning process, several important observations and adjustments were made:

- **Outliers**: Extreme values were detected in certain numerical columns. These outliers were either flagged for further investigation or imputed using the median to prevent skewing the analysis
- **Missing Values**: Some key attributes had missing values, which were either removed or imputed using the mode to maintain the integrity of categorical data
- **Inconsistent Formatting**: Data entries contained formatting inconsistencies, which were standardized (e.g., date format and string capitalization) to ensure consistency
- **Categorical Transformations**: Some categorical variables were modified (e.g., mapping textual labels to numerical values) to enhance interpretability and usability

These improvements ensure the dataset is clean and ready for further exploration and analysis.


## Libraries Used
- **Pandas**: For data manipulation, cleaning, and handling dataframes
- **NumPy**: For handling numerical operations and missing values
- **Matplotlib**: For data visualization, including plotting graphs like histograms, scatter plots, etc.
- **Seaborn**: For statistical data visualization and enhanced graphical representations
- **SciPy**: For scientific and technical computing, including statistical tests and optimizations (e.g., Shapiro-Wilk test)
- **Counter**: For counting occurrences of elements in lists or collections
- **re**: For working with regular expressions to manipulate strings and text







_I’d love to hear your thoughts! If you have any suggestions or questions, feel free to connect with me._


