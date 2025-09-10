# Pandas-Learnings
1. The most powerful, fast, flexible and easy to use open source data analytics and manipulation tool.
  
2. Two most frequently used datatypes in pandas are "series and dataframe.
 
3. A pandas series is like a column in a table (1-d array holding any datatype).
 
4. When we have to create series from a table earlier we had (squeeze=True) but its not supported everywhere so we instead use indexing subs=subs[:,0].
    
5. Pandas does not use : slicing like NumPy arrays directly with labels. You need .loc (label-based indexing) or .iloc (integer position indexing).

# Pandas2-Learnings

1. Groupby is study of groups.  

2. Only works with categorical columns.  

3. We can apply multiple agg functions on multiple columns.

4. There are 4 types of join : Inner, Left, Right, Outer the working is same as in SQL a join can be said as crossproduct between tables+ some condition.    


<img width="253" height="148" alt="image" src="https://github.com/user-attachments/assets/932d27ad-f201-4bb7-947c-d8052cd761eb" />  




5. table1.merge(table2) by default:- inner join between 2 tables on common column.

6. why 1d? because to fetch value we would require one piece of information, why 2d? to fetch single value we would require 2 pieces of information.

7. wide format table= each datapoint has single row containing values of all attributes, long format table= each datapoint has as many rows dedicated as number of attributes.

8. melt-> converts wide format to long format.

9. pd.to_datetime() converts strings like "2019-09-09" to pandas datetime64 object.  
