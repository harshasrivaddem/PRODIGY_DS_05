This task aims to gain insights into US traffic accidents by conducting exploratory data analysis and visualizing various aspects of the dataset. 
By utilizing pandas for data manipulation and seaborn/matplotlib for visualization,
it aims to uncover patterns, trends, and correlations within the accident data related to location, time, weather, severity, and other relevant factors.
Data Loading and Manipulation:

The task begins by importing pandas to load and manipulate the dataset.
The dataset used is the US accident data obtained from Kaggle.
Exploratory Data Analysis (EDA):

The EDA process involves:
Displaying the first 5 rows of the dataset (head()).
Checking for null values and handling them, possibly by dropping them (dropna()).
Using shape to determine the dimensions (number of rows and columns) of the dataset.
Using info() to get an overview of the dataset including data types and non-null counts.
Data Visualization:

Visualization tasks performed include:
Countplot (sns.countplot()) of city to visualize accident counts per city.
Countplot of weather timestamp to analyze accident occurrences over time.
Countplot of state to visualize accident distribution across different states.
Countplot of severity to understand the distribution of accident severity levels.
Countplot of timezone and wind direction to explore related factors.
Countplot of astronomical twilight to analyze accident trends during different lighting conditions.
Boxplot (sns.boxplot()) for state and wind speed to identify outliers and distributions.
Countplot of weather condition to visualize the frequency of different weather conditions during accidents.
