# Database Used Cars

## Data types:
- strings: [varchar(number), char(number), text, longtext]
- numbers: [tinyint, smallint, mediumint, int, bigint]
- decimals: [float(i,d), double(i,d), decimal(i,d)]
- dates: [datetime, date, time, year, timestamp]

## Attributes:
- NULL / NOT NULL
- DEFAULT(value)
- PRIMARY_KEY
- AUTO_INCREMENT
- UNIQUE

## Entity name: Used Car

## Table name: Used Cars

## Table columns:

- id | BIGINT, PRIMARY_KEY, AUTO_INCREMENT, NOTNULL, UNIQUE, INDEX
- brand | VARCHAR(50), NULLABLE, INDEX
- model | VARCHAR(50), NULLABLE
- setup | VARCHAR(50), NULL
- year_of_registration | YEAR
- mileage | MEDIUMINT, NULLABLE
- price | DECMIAL(9,2), NULLABLE, INDEX
- margin | DECMIAL(9,2), NULLABLE
- color | VARCHAR(20), NULLABLE, INDEX 
- fuel_type | VARCHAR(20), NULLABLE, INDEX
- power | VARCHAR(8), NULL
- transmission | VARCHAR(20), NULLABLE, INDEX
- number_of_previeus_owners | CHAR(2), NULLABLE
- description | TEXT, NULLABLE
- photo | VARCHAR(255), NOTNULL