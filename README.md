# 9abilMirmanovAmir
For my project for Jaqsylyq ABI
SELECT * FROM items;

Table: items

Description: This query selects all rows and all columns from the items table. It retrieves all information about every item (e.g., item names, categories, prices, and statuses).

SELECT DISTINCT Category FROM items;

Table: items

Description: This query selects unique values from the Category column. It will return a list of all distinct categories of items.

SELECT ItemName, Price FROM items WHERE Price < 5.00;

Table: items

Description: This query selects the item names and their prices from the items table where the price is less than 5.00. Since all items have a price higher than 5.00, the result will likely be empty.

SELECT * FROM items WHERE Status = 'доставлен';

Table: items

Description: This query selects all rows and all columns from the items table where the status is 'доставлен' (delivered). It will return all items that have been delivered.

SELECT * FROM items WHERE Status = 'готовится';

Table: items

Description: This query selects all rows and all columns from the items table where the status is 'готовится' (being prepared). It will return all items that are in the process of being prepared.
