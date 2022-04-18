BEGIN;
CREATE DATABASE IF NOT EXISTS 3450project;
USE 3450project;

CREATE TABLE store (
	STR_ID 		NUMERIC(10,0) PRIMARY KEY
);

CREATE TABLE products (
    ITM_NUM 	NUMERIC(10,0) PRIMARY KEY,
    ITM_DATE	DATE,
    ITM_NAME	VARCHAR(45),
    ITM_COST	NUMERIC(10,0),
    ITM_AMT	NUMERIC(65,0)
);

CREATE TABLE product_removed (
ITM_NUM NUMERIC(10,0),
FOREIGN KEYS(ITM_NUM) REFERENCES PRODUCT(ITM_NUM)
ITM_NAME VARCHAR(45),
ITM_REASON VARCHAR(45)
);

INSERT INTO store VALUES(1);
INSERT INTO products VALUES(1, 'PS5', 2, 799, 3/8/22, 8); 
INSERT INTO products VALUES(2, 'Xbox Series X', 5, 635, 1/24/22, 15);
INSERT INTO products VALUES(3, 'Nintendo Switch', 8, 350, 2/4/22, 12);
INSERT INTO products VALUES(4, 'Super Smash Bros', 21, 45, 2/2/22, 28); 
INSERT INTO products VALUES(5, 'Call of Duty: Black Ops', 47, 45, 2/24/22, 77); 
INSERT INTO products VALUES(6, 'Elden Ring', 75, 60, 2/24/22, 143); 
INSERT INTO products VALUES(7, 'Minecraft', 45, 20, 1/11/22, 67); 
INSERT INTO products VALUES(8, 'GTA V', 20, 45, 2/24/22, 33);
INSERT INTO products VALUES(9, 'God of War', 12, 45, 2/24/22, 33); 
INSERT INTO products VALUES(10, 'Halo 5', 2, 40, 2/24/22, 7); 
INSERT INTO products VALUES(11, 'Sid Meiers Civilization IV', 14, 25, 2/24/22, 46); 
INSERT INTO products VALUES(12, 'Turtle Beach Headset', 5, 100, 2/28/22, 11); 
INSERT INTO products VALUES(13, 'Oculus Quest 2', 5, 400, 3/22/22, 13); 
INSERT INTO products VALUES(14, 'Xbox Series X Controller', 12, 799, 3/8/22, 21); 



