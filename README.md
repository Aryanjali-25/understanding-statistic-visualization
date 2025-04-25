# understanding-statistic-visualization
#This project analyzes Amazon sales data for 2025 using Python. The analysis includes basic statistics, visualizations, and pattern identification to gain insights from the sales data.

##The code performs five main types of analysis:

1. Summary Statistics
   - Calculates mean, median, standard deviation
   - Provides basic statistical overview of the data

2. Data Visualization
   - Creates histograms to show data distribution
   - Generates boxplots to identify outliers
   - Visual representation of each numeric feature

3. Correlation Analysis
   - Creates correlation matrix heatmap
   - Generates pairplot to show relationships between features
   - Helps identify related variables

4. Pattern Detection
   - Calculates skewness of data
   - Identifies outliers
   - Shows data distribution patterns

5. Basic Feature-Level Inferences
   - Made basic inferences about each feature based on the histograms and boxplots:
     - Identified the type of distribution (e.g., skewness and transformation needs).
     - Identified outliers and recommended potential treatments.
     - Checked for potential data transformations (such as log transformations for skewed data).

## Final Insights

--Skewness
  - Some features exhibit positive or negative skewness, indicating that transformations (such as logarithmic transformations) may be necessary for normalization or to meet the assumptions of machine learning models.
  
--Outliers
  - Several features have outliers, as seen in the boxplots. These outliers may need to be handled by either removing or transforming the extreme values, especially when using machine learning models that are sensitive to outliers.

--Correlation
  - Certain features are highly correlated with each other (e.g., product price and sales amount), which could lead to multicollinearity in regression models. This may require feature engineering (e.g., removing or combining correlated features).

--Data Distribution
  - Features such as sales amount are highly right-skewed, meaning that most transactions are low value, with a small number of high-value transactions contributing significantly to the total sales.
