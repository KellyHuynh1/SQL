# SQL
**/Grocery list: 
Bananas (4)
Peanut butter (1)
Apples (4)
Bread (1)
Bottled water (2)
/**

CREATE TABLE grocery_list (ID INTEGER PRIMARY KEY, name TEXT, quantity INTEGER, ) ;
INSERT INTO grocery_list VALUES (1, "Bananas", 4); 
INSERT INTO grocery_list VALUES (2, "Peanut butter", 1);
INSERT INTO grocery_list VALUES (3, "Apples", 4);
INSERT INTO grocery_list VALUES (4, "Bread", 1);
INSERT INTO grocery_list VALUES (5, "Bottles water", 2);

SELECT * FROM grocery_list WHERE quantity >1 ORDER BY quantity;


