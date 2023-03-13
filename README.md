# SQL
SQL Portfolio
CREATE TABLE plants (id INTEGER PRIMARY KEY, name TEXT, price INTEGER, care_difficulty INTEGER, light_requirements INTEGER, units_left INTEGER );

INSERT INTO plants VALUES (1, 'Pothos', 12.99, 2,'bright indirect', 50);
INSERT INTO plants VALUES (2, 'Pilea', 17.99, 4, 'bright indirect', 35);
INSERT INTO plants VALUES (3, 'Fiddle leaf fig', 23.99, 7, 'bright direct', 42);
INSERT INTO plants VALUES (4, 'Prayer', 19.99, 8, 'moderate indirect', 36);
INSERT INTO plants VALUES (5, 'Jade', 11.99, 5, 'bright indirect', 30);
INSERT INTO plants VALUES (6, 'Cactus', 10.99, 2, 'bright direct', 20);
INSERT INTO plants VALUES (7, 'Monstera', 43.99, 4, 'bright direct', 5);
INSERT INTO plants VALUES (8, 'Sago Palm', 16.99, 5, 'bright direct', 9);
INSERT INTO plants VALUES (9, 'Aloe Vera', 15.99, 3, 'bright direct', 11);
INSERT INTO plants VALUES (10, 'Pearl of strings', 18.99, 8, 'direct/indirect',6);
INSERT INTO plants VALUES (11, 'Dracaena', 23.99, 4, 'bright indirect', 4);
INSERT INTO plants VALUES (12, 'Snake Plant', 17.99, 2, 'low to bright indirect',7);
INSERT INTO plants VALUES (13, 'Peace Lily', 18.99, 4, 'low to bright indirect', 3);
INSERT INTO plants VALUES (14, 'Boston Fern', 12.99, 3, 'medium to bright indirect',15);
INSERT INTO plants VALUES (15, 'Spider Plant', 9.99, 1, 'bright to moderate indirect', 10);

SELECT * FROM plants
ORDER BY price
