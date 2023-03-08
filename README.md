# Pandasassignment
Q1. How do you load a CSV file into a Pandas DataFrame?
Ans: Just add _csv before the link of the data for example: 
df1 = pd.read_csv('link of the data')
df1 

Q2. How do you check the data type of a column in a Pandas DataFrame?
Ans: df2.dtype is the syntax that can help to check the data type.

Q3. How do you select rows from a Pandas DataFrame based on a condition?
Ans: df1.loc(), loc[] help to access and to select the rows.

Q4. How do you rename columns in a Pandas DataFrame?
Ans: df = df.rename(columns={'oldName1': 'newName1'}) help to rename a column.

Q5. How do you drop columns in a Pandas DataFrame?
Ans: df.drop will help to drop columns in pandas.
For example: df = df.drop(['column 1', 'column 2'...], axis =1)
Q6. How do you find the unique values in a column of a Pandas DataFrame?
Ans: unique syntax help to find unique values of column.
For example: df1 ['Column name'].unique()

Q7. How do you find the number of missing values in each column of a Pandas DataFrame?
Ans:  To get the count of missing values in each column of a dataframe, you can use the pandas isnull () and sum () functions together.
For example: df1.isnull().sum()
Q8. How do you fill missing values in a Pandas DataFrame with a specific value?
Ans: df.ffill() help to fill the missing values in pandas.

Q9. How do you concatenate two Pandas DataFrames?
Ans: To concatenate an arbitrary number of pandas objects ( DataFrame or Series ), use concat. If unnamed Series are passed they will be numbered consecutively. Passing ignore_index=True will drop all name references. A fairly common use of the keys argument is to override the column names when creating a new DataFrame based on existing Series .

Q10. How do you merge two Pandas DataFrames on a specific column?
Ans: We can merge two Pandas DataFrames on certain columns using the merge function by simply specifying the certain columns for merge. Syntax: DataFrame.merge (right, how=’inner’, on=None, left_on=None, right_on=None, left_index=False, right_index=False, sort=False, copy=True, indicator=False, validate=None)

Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?
Ans: The groupby method is the most commonly used function to group data in a Pandas DataFrame. It allows you to group data based on one or multiple columns and apply various aggregation functions, such as sum, mean, count, etc., to the groups.

Q12. How do you pivot a Pandas DataFrame?
Ans: DataFrame - pivot () function The pivot () function is used to reshaped a given DataFrame organized by given index / column values. This function does not support data aggregation, multiple values will result in a MultiIndex in the columns.

Q13. How do you change the data type of a column in a Pandas DataFrame?
Ans: DataFrame.astype () casts this DataFrame to a specified datatype. Following is the syntax of astype () method. we are interested only in the first argument dtype. dtype is data type, or dict of column name -> data type.

Q14. How do you sort a Pandas DataFrame by a specific column?
Ans: To sort the rows of a DataFrame by a column, use sort_values() function with the by=column_name argument. The sort_values() function does not modify the actual DataFrame, but returns the sorted DataFrame


Q15. How do you create a copy of a Pandas DataFrame?
Ans: You can use the pandas dataframe copy()function to create a copy of a dataframe. It creates a deep copy by default. The following is the syntax – The copy() function takes a single parameter deep as an argument. This parameter has two possible values, True and False. 1.

Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?
Ans: Selecting rows in pandas DataFrame based on conditions Selecting rows based on particular column value using '>', '=', '=', '<=', '!=' operator. Selecting those rows whose column value is present in the list using isin() method of the dataframe. Selecting rows based on multiple column conditions using '&' operator.

Q17. How do you calculate the mean of a column in a Pandas DataFrame?
Ans: Often you may be interested in calculating the mean of one or more columns in a pandas DataFrame. Fortunately you can do this easily in pandas using the mean () function. This tutorial shows several examples of how to use this function.



Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?
Ans: You can use the DataFrame.std () function to calculate the standard deviation of values in a pandas DataFrame. You can use the following methods to calculate the standard deviation in practice: Method 1: Calculate Standard Deviation of One Column df['column_name'].std() Method 2: Calculate Standard Deviation of Multiple Columns


Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?
Ans: You can use the following syntax to calculate the correlation between two columns in a pandas DataFrame: df ['column1'].corr(df ['column2'])

Q20. How do you select specific columns in a DataFrame using their labels?
Ans:  Select specific columns using the columns names list You can select specific columns from a DataFrame using the column name. For example, if you have a DataFrame with columns " A " and " B ", you can select column "A" by using the column name.

Q21. How do you select specific rows in a DataFrame using their indexes?
Ans: If you’d like to select rows based on integer indexing, you can use the .iloc function. If you’d like to select rows based on label indexing, you can use the .loc function. This tutorial provides an example of how to use each of these functions in practice.

Q22. How do you sort a DataFrame by a specific column?
Ans:  To sort the rows of a DataFrame by a column, use pandas. DataFrame. sort_values () method with the argument by = column_name. The sort_values () method does not modify the original DataFrame, but returns the sorted DataFrame. You can sort the dataframe in ascending or descending order of the column values.

Q23. How do you create a new column in a DataFrame based on the values of another column?
ANS: Using apply() method If you need to apply a method over an existing column in order to compute some values that will eventually be added as a new column in the existing DataFrame, then pandas.DataFrame.apply()method should do the trick. For example, you can define your own method and then pass it to the apply()method.


Q24. How do you remove duplicates from a DataFrame?
Ans: Pandas drop_duplicates() method helps in removing duplicates from the data frame

Q25. What is the difference between .loc and .iloc in Pandas?
Ans: loc gets rows (and/or columns) with particular labels. iloc gets rows (and/or columns) at integer locations. To demonstrate, consider a series s of characters with a non-monotonic integer index:
