This analysis will create a new column and add boolean values based on the data found in the active column from the csv file.
I used np.where() function to look through the active column for any customer with an active value of 0.
I created a new column name "status" using pandas and give each customer a status of false if the active==0 or true if active==1.
