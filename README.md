# dbms4


### The AND operator is used to filter records based on more than one condition, 
 * like if you want to return all customers from Spain that starts with the letter 'G':

   ```sql
   SELECT *
   FROM Customers
   WHERE Country='Spain' AND Customer LIKE 'G%' ;```

   
