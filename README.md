# Data-Visualization-challenge

# Data Loading and Cleaning:
Importing Libraries: The code begins by importing necessary libraries: pandas, matplotlib.pyplot, seaborn, and LinearRegression from sklearn.linear_model.

Loading Data: It loads two datasets (mouse_metadata and study_results) using pd.read_csv.

Combining Data: The code merges the two datasets on the 'Mouse ID' column, creating a single DataFrame (combined_data).

Data Preview: The first five rows of the combined DataFrame are displayed using print(combined_data.head()).

Checking Number of Mice: The code checks and prints the number of unique mice in the combined dataset.

Handling Duplicates: It identifies and displays duplicate entries based on 'Mouse ID' and 'Timepoint'.

Optional: Duplicate Mouse Data: The code retrieves and displays all data for the duplicate mouse ID, if any.

Creating Clean DataFrame: It creates a clean DataFrame (clean_combined_data) by dropping duplicate mouse entries based on 'Mouse ID' and 'Timepoint'.

Checking Number of Mice in Clean DataFrame: It prints the number of unique mice in the clean DataFrame.

# Exploratory Data Analysis (EDA):
Summary Statistics Table: The code calculates and prints the summary statistics table (mean, median, variance, standard deviation, and standard error) for the tumor volume, grouped by drug regimen.

Bar Plot (Pandas): It generates and displays a bar plot using Pandas to show the total number of mice per drug regimen.

Bar Plot (Pyplot): It generates and displays a bar plot using Pyplot to show the total number of mice per drug regimen.

Pie Plot (Pandas): It generates and displays a pie plot using Pandas to show the distribution of female vs. male mice.

Pie Plot (Pyplot): It generates and displays a pie plot using Pyplot to show the distribution of female vs. male mice.

Outliers Detection and Box Plot: It detects potential outliers for four treatment regimens and generates a box plot to visualize the distribution of tumor volume for each regimen.

# Treatment-Specific Analysis:
Line Plot (Capomulin): It generates and displays a line plot of tumor volume vs. time point for a single mouse treated with Capomulin.

Scatter Plot (Capomulin): It generates and displays a scatter plot of mouse weight vs. average observed tumor volume for the Capomulin regimen.

Correlation and Linear Regression: It calculates the correlation coefficient and fits a linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen. The results are printed.

# Overall Analysis:
The code provides a comprehensive analysis of the dataset, covering data loading, cleaning, exploratory data analysis, and specific analyses related to the Capomulin treatment regimen. Visualizations such as bar plots, pie plots, box plots, line plots, and scatter plots are used to convey insights, and statistical measures are employed to summarize key information in the dataset. The inclusion of the linear regression model adds a quantitative aspect to the relationship between mouse weight and tumor volume.