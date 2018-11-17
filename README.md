# DS_Take_Home_Data_Challenge

## Preview

### 02 Spanish Translation AB Test
- two sample ratio test: hypothesis statement, z statistics, upper $1-\alpha$ quantile of Normal distribution
- subsetting pandas dataframe: df.loc[df['column_name'] == condition]
- inner join pandas dataframes: df1.join[df2.set_index('foreign key'), on = 'foreign key']
- COUNT DISTINCT in python: df['user_id'].unique()
- subset with rows and columns selection: df.loc[df.col1 == value1, ['col2','col3']]
- reset_index: for data frames with row names, such as df created by using groupby, use reset_index to make the row names as a independent column

### 04 Fraud Detection
- df.sort_values(by = colname): equal to 'ORDER BY colname'
- array.clip_lower(value) : find all the elements in the array that is smaller than **value**, and change them into **value**
- array[array > 0] : cut array based on condition inside the double square brackets.
- np.argmin(array) : find the index of the minimum element in an array