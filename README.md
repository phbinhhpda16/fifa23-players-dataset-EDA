# FIFA 23 Players Dataset EDA

This repository contains an exploratory data analysis (EDA) of the FIFA 23 Players dataset. The dataset provides information about football players, including their attributes, ratings, positions, clubs, and more.

## Getting Started

To get started with the analysis, follow the steps below:

1. Install the required libraries: pandas, numpy, squarify, matplotlib, and statsmodels. You can install them using pip:

   ```
   pip install pandas numpy squarify matplotlib statsmodels
   ```

2. Clone the repository or download the dataset file (Fifa_23_Players_Data.csv) from the repository.

3. Load the dataset into a pandas DataFrame:

   ```python
   import pandas as pd
   
   df = pd.read_csv('Fifa_23_Players_Data.csv')
   ```

## Exploratory Data Analysis

The EDA process involves understanding the dataset, exploring the variables, and extracting insights. Below are some key steps and findings from the EDA:

1. Select Relevant Columns: We begin by selecting a subset of columns from the dataset that are relevant to our analysis.

2. Data Cleaning: Handle missing values by filling them with appropriate values or removing them based on the context of the data.

3. Data Transformation: Convert some columns into more suitable formats, such as converting currency values to million or thousand units.

4. Descriptive Statistics: Compute descriptive statistics, such as mean, median, and quartiles, for relevant columns to gain insights into the data.

5. Data Visualization: Utilize various visualizations to explore relationships, distributions, and patterns in the data.

6. Correlation Analysis: Calculate the correlation between different variables to understand their relationships.

7. Key Findings: Identify interesting findings and insights from the analysis, such as top players by overall and potential ratings, distribution of player attributes, correlation between attributes, and more.

## Repository Structure

- `Fifa_23_Players_Data.csv`: The dataset file containing the FIFA 23 Players data.
- `README.md`: The README file providing an overview of the repository and EDA steps.

## Conclusion

The EDA process provides valuable insights into the FIFA 23 Players dataset, including player ratings, attributes, positions, clubs, and more. By exploring the data and visualizing it, we can gain a deeper understanding of the dataset and uncover interesting patterns and relationships.

Feel free to explore the code and modify it according to your requirements or extend the analysis further. Enjoy the FIFA 23 Players Dataset EDA!

**Note:** The code provided assumes the dataset file is in the same directory as the Python script. Please adjust the file path accordingly if needed.
