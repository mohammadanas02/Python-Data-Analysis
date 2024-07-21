# Diwali Sales Analysis

This project involves analyzing sales data during the Diwali festival using Python. The objective is to derive insights and visualize trends to better understand the sales patterns.

## Dataset

The dataset used in this project is a CSV file named `Diwali Sales Data.csv` which contains the following columns:

- `User_ID`
- `Cust_name`
- `Product_ID`
- `Gender`
- `Age Group`
- `Age`
- `Marital_Status`
- `State`
- `Zone`
- `Occupation`
- `Product_Category`
- `Orders`
- `Amount`
- `Status`
- `unnamed1`

## Project Structure

The project is organized as follows:

1. **Data Import and Preprocessing**: 
    - Importing necessary libraries.
    - Loading the CSV file.
    - Displaying basic information about the dataset.

2. **Data Cleaning**:
    - Handling missing values.
    - Removing unnecessary columns.

3. **Exploratory Data Analysis (EDA)**:
    - Analyzing customer demographics.
    - Visualizing sales data based on gender, age group, and occupation.
    - State and zone-wise sales analysis.

4. **Data Visualization**:
    - Plotting graphs to show sales trends.
    - Heatmaps to show correlations.

## Libraries Used

- `numpy`: For numerical computations.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization.
- `seaborn`: For enhanced data visualization.

## Code Snippets

### Importing Libraries

```python
import numpy as np 
import pandas as pd 
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns
```
## Conclusion
This project demonstrates the process of cleaning, analyzing, and visualizing sales data to extract meaningful insights. The visualizations help in understanding the sales distribution across different demographics and regions during the Diwali festival.

## Acknowledgments
Special thanks to the dataset provider and the open-source community for their valuable contributions.

## Author 
Mohammad Anas Alam
