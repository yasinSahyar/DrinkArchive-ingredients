# DrinkArchive-ingredients
 Table: drinkingredients
 1	ingredient_id Primary	int(11)			No	None		AUTO_INCREMENT	Change Change	Drop Drop	
	2	drink_id Index	int(11)			Yes	NULL			Change Change	Drop Drop	
	3	amount	decimal(10,2)			Yes	NULL			Change Change	Drop Drop	
 
Table: drinkki
 1	drink_id Primary	int(11)			No	None		AUTO_INCREMENT	Change Change	Drop Drop	
	2	name	varchar(255)	utf8mb4_general_ci		No	None			Change Change	Drop Drop	
	3	category	varchar(255)	utf8mb4_general_ci		Yes	NULL			Change Change	Drop Drop	
	4	description	text	utf8mb4_general_ci		Yes	NULL			Change Change	Drop Drop	
	5	hyvaksytty	int(11)			Yes	0		
 
 Table: drinks
 	1	drink_id Primary	int(11)			No	None		AUTO_INCREMENT	Change Change	Drop Drop	
	2	name	varchar(255)	utf8mb4_general_ci		Yes	NULL			Change Change	Drop Drop	
	3	category	varchar(255)	utf8mb4_general_ci		Yes	NULL			Change Change	Drop Drop	
	4	description	text	utf8mb4_general_ci		Yes	NULL			Change Change	Drop Drop	
	5	rating	decimal(3,2)			Yes	NULL			Change Change	Drop Drop	
	6	serving_size	int(11)			Yes	NULL			Change Change	Drop Drop	
	7	image_url	varchar(255)	utf8mb4_general_ci		Yes	NULL			Change Change	Drop Drop	
	8	hyvaksytty	tinyint(4)			Yes	NULL			Change Change	Drop Drop	


Table: ingredients
 	1	ingredient_id Primary	int(11)			No	None		AUTO_INCREMENT	Change Change	Drop Drop	
	2	name	varchar(255)	utf8mb4_general_ci		Yes	NULL			Change Change	Drop Drop	
	3	category	varchar(255)	utf8mb4_general_ci		Yes	NULL			Change Change	Drop Drop	
	4	description	text	utf8mb4_general_ci		Yes	NULL			Change Change	Drop Drop	


