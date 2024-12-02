" Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario"
   
## Table structure

- id | INT - AUTO_INCREMENT - PRIMARY KEY - NOT NULL,
- brand | VARCHAR(50) - NOT NULL,
- model | VARCHAR(50) - NOT NULL,
- production_year | YEAR - NOT NULL,
- mileage | INT - NOT NULL,
- price | DECIMAL(10, 2) - NOT NULL,
- color | VARCHAR(30) - NULL,
- fuel_type | VARCHAR(20) - NOT NULL,
- number_of_doors | VARCHAR(5) - NOT NULL,
- type | VARCHAR(50) - NOT NULL,
- description | TEXT - NULL,