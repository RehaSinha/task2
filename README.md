Table Creation:
A table named Restaurant was created with the following columns:
id (INTEGER, Primary Key) ,name (TEXT – restaurant name),food_name (TEXT – dish name),rating (REAL – rating of the dish)
Data Insertion:
Inserted 6 sample records into the table. Some rows had missing (NULL) values for food_name and rating.
Handling NULL Values:
Replaced NULL values in food_name with 'Unknown'.
Replaced NULL values in rating with a default value 3.0.
Update Records:
Updated rating for a specific dish (id = 1) to 4.8.
Increased rating for dishes that contain "Pasta" by 0.2.
Delete Records:
Deleted dishes with a rating less than 3.6.
Deleted a specific record using its id.
Final Data Display:
Used SELECT * FROM Restaurant;


