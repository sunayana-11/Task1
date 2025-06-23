In this task, the following data cleaning operations were performed using Python (with pandas and numpy) and Excel tools:

1. Identify and Handle Missing Values

Used .isnull().sum in Python to detect missing values.


2. Remove Duplicate Rows

Used .drop_duplicates() in pandas to eliminate duplicate records.


3. Standardize Text Values

As the table contained all unique values so no standardization was done.


4. Convert Date Formats

Unified all date fields to the format dd-mm-yyyy using pandas to_datetime() and string formatting.


5. Rename Column Headers

Renamed all column headers to lowercase and replaced spaces with underscores for consistency and readability.


6. Check and Fix Data Types

Ensured numerical columns like age are of int type and date columns are in datetime format.


 Libraries Used:

import pandas as pd  
import numpy as np

These steps ensure the dataset is clean, consistent, and ready for analysis or modeling.
