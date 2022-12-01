## Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## TABLE NAME: Used Car Dealership

## TABLE COLUMNS: 

- license_plate - VARCHAR(15) | PRIMARY_KEY | NOT_NULL
- storehouse_vehicle - VARCHAR (20) | NOT_NULL
- vehicle_model - VARCHAR (20) | NOT_NULL
- price | DECIMAL (7, 2) | NULL
- first_enrollment | YEAR | NULL
- mile_age | INT | NULL
- fuel | VARCHAR(15) | NULL
- condition_of_the_car | TEXT | NULL
- previous_owners | TINYINT | NULL
- color | VARCHAR (10) | NULL
- vehicle_class | VARCHAR(10) | NULL
- consume | FLOAT (2, 1) | NULL
- car equipment | TEXT | NULL
- country_of_origin | VARCHAR(15) | NULL