# Exploring and Visualizing the Iris Dataset

## Task 1: Objective
This notebook explores the famous Iris dataset, performs basic data analysis, visualizes features, and examines relationships between flower species and features. The goal is to understand the dataset and gain insights that can be useful for classification tasks.

## Dataset
- The Iris dataset is a built-in dataset in Seaborn.
- It contains 150 samples of iris flowers with the following features:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
  - `species` (target variable)

## Steps Performed
1. **Import Libraries**  
   Libraries used for data manipulation and visualization:
   - `pandas` for handling tabular data
   - `matplotlib.pyplot` and `seaborn` for plotting

2. **Load Dataset**  
   Loaded the Iris dataset from Seaborn and displayed the first 5 rows.

3. **Explore Dataset**  
   - Checked dataset shape, column names, and data types.
   - Reviewed summary statistics for numeric columns.

4. **Data Visualization**  
   - Scatter plot of sepal length vs petal length colored by species.
   - Histograms of all numeric features to check distribution.
   - Boxplots of features to detect outliers and understand ranges.

5. **Insights**  
   - Petal length separates species better than sepal length.
   - Numeric features are roughly normally distributed.
   - Boxplots help identify potential outliers and feature ranges.
   - Dataset is clean and ready for classification modeling.

## Libraries Used
- `pandas`
- `matplotlib`
- `seaborn`

## Conclusion
This notebook provides a foundational understanding of the Iris dataset and prepares it for further machine learning tasks such as classification. Visualizations and descriptive statistics give insights into feature distributions and relationships between species.
