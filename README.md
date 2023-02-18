# Store-Inventory
This was the first project that I did in SQL. It is a very simple project, but it is a great first stab. 
CREATE TABLE Store_Inventory (id INTEGER PRIMARY KEY, Item TEXT, Quantity INTEGER);
Insert into Store_Inventory VALUES (1,"Tomatoes",22);
Insert into Store_Inventory VALUES (2, "Carrots", 4);
Insert into Store_Inventory VALUES (3, "Mushrooms", 15);
Insert into Store_Inventory VALUES (4, "Steak", 6);
Insert into Store_inventory VALUES (5, "Pork Chop", 14);
Insert into Store_Inventory VALUES (6, "Salt Shakers", 10);
Insert into Store_Inventory VALUES (7, "Pepper Mills", 10);
Insert into Store_Inventory VALUES (8, "Plastic Forks", 30);
Insert into Store_Inventory VALUES (9, "Hot Chocolate Powder", 25);
Insert into Store_Inventory VALUES (10, "Plastic Spoons", 30);
Insert into Store_Inventory VALUES (11, "Plastic Knifes", 30);
Insert into Store_Inventory VALUES (12, "Ketchup Packets", 60);
Insert into Store_Inventory VALUES (13, "Mustard Packets", 60);
Insert into Store_Inventory VALUES (14, "Brocolli Heads", 5);
Insert into Store_Inventory VALUES (15, "Cheese Blocks", 20);

Select * from Store_Inventory
Order by Quantity;
