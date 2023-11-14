# Assignment 3
Submit your answers to the questions below in a Jupyter Notebook where the output is displayed. Submissions are only accepted via Github Classroom. If you would like to know how to submit assignments via Github Classroom, please see: https://www.youtube.com/watch?v=ObaFRGp_Eko


## Task 1: Finding good hotel deals in Europe
Use the data sets `hotels-europe_price.csv` and `hotels-europe_features.csv` and complete the following tasks:

1. Combine the two data frames;
2. Filter the data to only include observations with the following characteristics: we are interested in observations during the week days of August in `hotels` in Vienna and London in 2017. Make sure to check that no outliers (e.g. with respect to price) are present. In other words, clean your data accordingly;
3. Plot the distribution of prices separately for Vienna and London. What can you say about the two distributions and how do they compare?

## Task 2: OOP Practice
1. Create a class `Accomodation` with the following attributes: `accomodation_type`, `name` (e.g. name of hotel), `price`, `stars`, `distance_to_center`. Note that if you find that there are multiple observations for a single accomodation/hotel, the price should reflect the average price at that accomodation.
2. Write a function `from_df_to_class` that takes as an argument the merged data from Task 1.1. and creates an instance of `Accomodation` for every observation.

