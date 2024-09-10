# Viikko 2 - Yhteen taulukkoon kohdistuvat kyselyt ja where-osan liitosehto

### Tehtävä 1 - Yhteen taulukkoon kohdistuvat kyselyt harjoitus

### 1.

SELECT * FROM goal;  
![kuvakaappaus](k1.png)

### 2.

SELECT name, type FROM airport WHERE iso_country = "FI";  
![kuvakaappaus](k2.png)

### 3.

SELECT name FROM airport WHERE iso_country = "FI" ORDER BY name ASC;  
![kuvakaappaus](k3.png)

### 4.

SELECT name, type FROM airport WHERE iso_country = "FI" ORDER BY type ASC, name ASC;  
![kuvakaappaus](k4.png)

### 5.

SELECT name FROM country WHERE name LIKE "f%";  
![kuvakaappaus](k5.png)

### 6.

SELECT name FROM country WHERE name like "%f%"; 
![kuvakaappaus](k6.png)

### 7.

SELECT ident AS location FROM airport WHERE ident = "EGCC"; 
![kuvakaappaus](k7.png)

## 8.

SELECT co2_consumed FROM game WHERE co2_consumed = 8000;  
![](image-1.png)

### 9.

SELECT co2_budget from game LIMIT 1;  
![](image-2.png)