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

Q10. How do you merge two Pandas DataFrames on a specific column?

Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?

Q12. How do you pivot a Pandas DataFrame?

Q13. How do you change the data type of a column in a Pandas DataFrame?

Q14. How do you sort a Pandas DataFrame by a specific column?

Q15. How do you create a copy of a Pandas DataFrame?

Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?

Q17. How do you calculate the mean of a column in a Pandas DataFrame?

Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?

Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?

Q20. How do you select specific columns in a DataFrame using their labels?

Q21. How do you select specific rows in a DataFrame using their indexes?

Q22. How do you sort a DataFrame by a specific column?

Q23. How do you create a new column in a DataFrame based on the values of another column?

Q24. How do you remove duplicates from a DataFrame?

Q25. What is the difference between .loc and .iloc in Pandas?
