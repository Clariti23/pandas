# Tutorial Summary

1. `import pandas as pd`
   This is a convention to import the library.

2. `df = pd.read_csv('survey_results_public.csv')`
   Set up the data frame by reading in the data from the file path where the data we want is located.

3. `df` will print out the data frame.

4. `df.shape` will tell us the number of rows and columns in the dataframe.

5. `df.info()` has some more details about the dataframe, such as the data types of each column.

6. `pd.set_option('display.max_columns', 85)` makes it so that running `df` looks a bit nicer--can scroll horizontally.

7. A DataFrame is kind of like a dictionary of lists: columns with many rows. A series is like all the rows for one column. A dataframe is basically a container of series objects.

8. `iloc` stands for integer location.
