# Data Cleaning with Python



### Outline

- Project Overview
- Dataset Used
- Libraries Used
- Data Cleaning Steps



## Project Overview
This project demonstrates essential data-cleaning techniques using Python libraries such as `Pandas` and `NumPy`. The dataset is processed through several preprocessing steps, including:

- Handling missing values through imputation or removal
- Removing duplicate entries to ensure data integrity
- Standardizing data formats for consistency across the dataset

These steps prepare the data for more accurate analysis and modeling.

You can view the full process in the Jupyter Notebook [here](). 


## Dataset Used
The dataset used in this project is sourced from Kaggle. You can access it [here](https://www.kaggle.com/datasets/fatihb/coffee-quality-data-cqi).

## Libraries Used
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For handling numerical operations and missing values.


## Data Cleaning Steps
1. **Loading the Data**

    The dataset is loaded using Pandas `read_csv()` method to read the CSV file from Kaggle.

2. **Handling Missing Values**

    The notebook identifies missing values and demonstrates different ways to handle them, such as filling them with a specific value or dropping rows with missing data.

3. **Removing Duplicates**

    Any duplicate rows in the dataset are removed using the `drop_duplicates()` function from Pandas to ensure the data is clean.

4. **Standardizing Data Formats**

    Columns are standardized to appropriate data types, such as converting string dates to Pandas `datetime` objects.

5. **Final Dataset**

    After performing all the cleaning steps, the cleaned dataset is saved and ready for further analysis.


