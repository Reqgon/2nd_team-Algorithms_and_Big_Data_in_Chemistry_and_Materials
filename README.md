# 2nd team - "Algorithms and Big Data in Chemistry and Materials" course 
### Team members: Valentina Bocharova and Alexander Makarov (group A4130)
## Hometask №1 : Data collecting and cleansing
The first step of the project is cleaning and collecting more data (at least 1000 descriptors). The dataframe we chose is '2.csv', then it was renamed to **'data_2.csv'**. The initial number of rows - 5000. All code is in notebook **'Homework_1.ipynb'**.
It was decided first to inspect the dataframe we got.
There are 11 columns in the table. Let's have a look at missing values distribution:
|Name of the column|Type|Missing value rate|
|:-----|:-----:|-----:|
|DOI|object|0.0000|
|Date|object|0.0842|
Journal |object|0.0842|
Title |object|0.0842|
Name |object|0.0010|
measurement_error|float64|0.0000|
measurement_wavelength |object|0.8858|
measurement_method |object|0.0000|
normalised_name |object|0.4116|
raw_value |object|0.0000|
specifier |object|0.0000|

Our mission is to handle missing values, check and clean existing values.
