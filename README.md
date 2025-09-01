# Netflix-Data-Cleaning-with-Pandas-Remove-Null-Values-
A Python project that cleans and preprocesses the Netflix dataset using Pandas. It handles missing values in cast, director, country, date_added, and rating columns, preparing the dataset for further analysis and visualization.

Overview
This project focuses on data cleaning and preprocessing of the Netflix dataset using Python.
The dataset contains details about movies and TV shows available on Netflix, such as:

Title

Director

Cast

Country

Date Added

Rating

Duration

Type (Movie/TV Show)

Cleaning the dataset ensures it becomes ready for further analysis, visualization, or machine learning models.

Technologies Used

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn – Statistical visualization

Key Steps in Data Cleaning

Load the dataset (netflix.csv) using Pandas.

Explore dataset structure using .head(), .info(), .shape(), and .describe().

Check for missing values with .isnull().sum().

Handle missing values by filling them with the mode (most frequent value) for categorical columns such as:

cast

director

country

date_added

rating

Verify that the dataset is clean and contains no null values.

Results

All missing values were handled properly.

The dataset is now cleaned and ready for visualization and further analysis.

Project Structure
Netflix-Data-Cleaning
┣ netflix.csv (Dataset)
┣ netflix_cleaning.py (Python script)
┗ README.md (Project documentation)

Future Improvements

Perform exploratory data analysis (EDA)

Build visualizations (e.g., top directors, movie trends by year)

Apply machine learning models for recommendation or classification

Author
Der Ravi
