# FIFA 23 Players Dataset EDA

This repository contains code for analyzing the FIFA 23 Players dataset. The dataset includes various attributes of players such as their overall rating, potential, value, positions played, nationality, age, height, weight, club information, and more.

## Prerequisites

To run the code and reproduce the analysis, you need to have the following dependencies installed:

- pandas
- numpy
- squarify
- matplotlib
- statsmodels

You can install these dependencies using pip:

```
pip install pandas numpy squarify matplotlib statsmodels
```

## Getting Started

1. Clone the repository to your local machine or download the code files.

2. Download the FIFA 23 Players dataset (Fifa_23_Players_Data.csv) and place it in the same directory as the code files.

3. Make sure you have the necessary dependencies installed as mentioned in the "Prerequisites" section.

4. Open the code file (e.g., `fifa23_analysis.py`) in a Python IDE or editor.

5. Run the code file to perform the analysis on the FIFA 23 Players dataset.

## Code Description

The code file `fifa23_analysis.py` contains the following major sections:

1. Importing the required libraries: pandas, numpy, squarify, matplotlib, and statsmodels.

2. Loading the FIFA 23 Players dataset using pandas.

3. Data preprocessing steps, including selecting relevant columns, handling missing values, and converting data types.

4. Exploratory data analysis, including visualizations of overall ratings, potentials, player positions, clubs, preferred foot, age distribution, nationality distribution, and correlation analysis between overall rating and wage.

5. Summary statistics and linear regression analysis to examine the relationship between overall rating and other player attributes such as age, height, weight, preferred foot, and skill moves.

## Results

The analysis provides insights into various aspects of the FIFA 23 Players dataset, including:

- Distribution of overall ratings and potentials
- Best players by position based on overall rating and potential
- Club-wise overall and potential rating averages
- Distribution of overall ratings and potentials by preferred foot
- Distribution of player ages
- Nationality distribution of players
- Top players by wage
- Correlation analysis between overall rating and wage
- Distribution of BMI (Body Mass Index) index

The linear regression analysis results provide coefficients and statistical significance for the relationship between overall rating and player attributes such as age, height, weight, preferred foot, and skill moves.

## License

The code in this repository is released under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgments

- The FIFA 23 Players dataset used in this analysis is not provided in this repository and should be obtained separately.
- The code is provided as a demonstration of data analysis techniques and can be modified and extended as per your requirements.
