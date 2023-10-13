Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


# car database

## table name

- cars

## table columns

- id | PRIMARY_KEY, UNIQUE, BIGINT, NOT NULL, AUTO_INCREMENT
- year| NOT NULL, DATE
- power-supply | NULL, CHAR(15)
- accident | DEFAULT(0)
- note | TEXT, NULL
- km | NOT NULL, DOUBLE (11, 3) //99 999 999, 999
- condition-external | TEXT, NULL 
- condition-internal | TEXT, NULL
- pictures| VARCHAR(255), NULL
- price | DOUBLE (10, 3), DEFAULT(0) // 9 999 999, 999
- typology | CHAR (15), NULL
- transmission gearbox | CHAR (15), NULL
- seats | TINYINT, DEFAULT(4)
- color | CHAR (25), NULL
- brand | CHAR (25), NOT NULL
- model | CHAR (50), NOT NULL
- optionals | TEXT, NULL
- wheel | DEFAULT(4), TINYINT
- driving wheels | CHAR (15), NULL








