# Miscellaneous-Functions
Basic data analysis functions written by me.

1. Column Check:
- This is a very basic function that checks if a dataset contains a predefined list of columns. Requires a list of necessary columns to be defined first before the function can work properly. This version of the function is case sensitive and therefore requires the predefined list of variables and the variables in the column to be an exact match casewise. 

- An update for the function that ignores cases and removes underbars to ensure better accuracy will also be implemented.


2. Proc Freq:
- This is an updated version of the old proc freq function that now returns the sum of the frequency of unique values as well as the sum of the frequency percentages.


3. Null Table:
- This is a function that combines the outputs of isna().sum() and notna().sum() into a single table whilst also returning the sum totals for Null Values and Non-Null Values. This function only requires pandas and is designed to serve as a replacement for missingno as circumstances at my previous workplace did not allow to me download modules at will. 
