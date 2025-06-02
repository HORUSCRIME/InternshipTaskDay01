# InternshipTaskDay01
Netflix Titles Data Analysis Project
This repository contains the cleaned dataset and relevant documentation for a project focusing on Netflix movies and TV shows. The primary goal of this phase was to perform comprehensive data cleaning and preprocessing, ensuring the dataset is ready for analysis.

Data Source
The original dataset was sourced from a CSV file, specifically netflix_titles.csv and its subsequent iterations (e.g., netflix_titles3.xlsx - netflix_titles (6).csv) during the cleaning process.

Data Cleaning and Preprocessing Steps Completed
Based on your confirmation that all remaining tasks have been completed, the following data cleaning and preprocessing steps have been successfully implemented:

Duplicate Rows Removed: All duplicate rows have been identified and removed, ensuring each entry in the dataset is unique.
Missing Values Handled: Missing values (NaN) in columns such as director, cast, country, date_added, no_of_seasons, durations_in_min, and ratings have been addressed using appropriate strategies (e.g., imputation with 'Unknown', removal, or other methods as determined by the cleaning process).

Duration Information Separated and Converted
The original mixed 'duration' information has been successfully split into two distinct, numerical columns:
    no_of_seasons: Stores the number of seasons for TV shows, converted to a numerical type (e.g., float64 or int64).
    durations_in_min: Stores the duration in minutes for movies, converted to a numerical type (e.g., float64 or int64).

Erroneous duration values found in the original rating column were correctly migrated to durations_in_min.

'Rating' Column Cleaned and Standardized:

The inconsistent values (e.g., duration strings) from the original rating column have been removed or corrected.

The ratings column now serves as the clean and standardized content rating column, containing only valid rating categories with no missing values. The original rating column has been appropriately handled (e.g., removed or fully cleaned).

date_added Data Type and Format: The date_added column has been consistently formatted and successfully converted to a datetime data type, ensuring it is ready for time-series analysis.

Column Headers Standardized: All column headers have been uniformly renamed to a clean and consistent style (e.g., all lowercase, using underscores for multi-word 
names like show_id, date_added, durations_in_min).

Text Value Standardization: Text values in categorical columns like country and listed_in have been reviewed and standardized for consistency, addressing variations (e.g., "United States" vs. "USA").

show_id Data Type: The show_id column is correctly an integer (int64).

Future Work
With the data cleaning and preprocessing phase successfully completed, the project will now proceed to:
  Exploratory Data Analysis (EDA)
  Data Visualization
  Developing insights and potentially building predictive models based on the cleaned data.
