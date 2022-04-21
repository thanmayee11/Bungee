In Question 1:
First checking the average price of each product.
Then checking the results by comparing the missing values in the price column with the values in the new column.


In Question 2:
For the products that have a unit of kg, the sales amount values will be the same as sales quantity values.
For the products that are sold in pieces, we need to extract the kg information from the description and multiply it by the sales amount.
We can use the where function to update the values conditionally. The weight information can be extracted by using the split function under the st accessor.



In Question 3:
Select only the Goal column.
Viewing only the columns Team, Yellow Cards and Red Cards and assign them to a dataframe called discipline
Sorting the teams by Red Cards, then to Yellow Cards
