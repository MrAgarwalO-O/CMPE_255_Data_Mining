# Exploratory Data Analysis (EDA) with D3.js Visualizations

This project demonstrates the process of exploratory data analysis (EDA) on a dataset `AB_NYC_2019.csv` using Python and includes advanced D3.js visualizations to provide an interactive and insightful view of the data.


## EDA Steps
### Step 1: Import Libraries and Load Data
Import necessary libraries: pandas, numpy, matplotlib.pyplot, and seaborn.<br>
Load the dataset using pandas.read_csv().
### Step 2: Data Cleaning and Preprocessing
Handle missing values by filling them with zeros.
Remove duplicate rows.
Convert data types as required.
### Step 3: Understanding the Dataset
Check the structure of the dataset using data.info().
Describe numerical variables and check unique values in categorical variables.
### Step 4: Univariate Analysis
Plot histograms for numerical variables and bar plots for categorical variables to understand the distribution of data.
### Step 5: Bivariate Analysis
Analyze the correlation between numerical variables and the relationship between numerical and categorical variables.
### Step 6: Multivariate Analysis
Analyze interactions between variables.
## D3.js Visualizations
### Visualization 1: Interactive Bubble Chart
This visualization uses D3.js to create an interactive bubble chart. Each bubble represents a data point with its radius corresponding to a value. The bubbles are draggable, and their positions will adjust dynamically to avoid overlap.

### Visualization 2: Bar Chart with Transitions
This visualization uses D3.js to create a bar chart with transitions. The bars start with zero height and gradually transition to their final height, creating a smooth animation effect.

### Visualization 3: Scatter Plot with Interactivity
This visualization uses D3.js to create an interactive scatter plot. Each data point is represented as a circle, and when you hover over a circle, its coordinates are displayed as a tooltip.
## References
https://towardsdatascience.com/data-visualization-for-eda-exploratory-data-analysis-f001a1bf0087 <br>
https://python.plainenglish.io/unicorn-startups-data-analysis-and-visualization-377224424a6a <br>
https://medium.com/hackernoon/taking-data-visualization-to-another-level-4d1c47bb01a2
