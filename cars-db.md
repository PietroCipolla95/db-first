Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario



Used Cars Table

-id |BIGINT, unique, autoincrement
-manufacturer | VARCHAR(30) not null
-model | VARCHAR(20) not null 
-year | YEAR not null
-type of fuel | VARCHAR(15) not null
-transmission | VARCHAR(9) not null
-emission | VARCHAR(7) not null
-km | SMALLINT not null
-color | VARCHAR(10) not null
-price | MEDIUMINT not null
-image | VARCHAR(255)  not null
-where is seller | VARCHAR(255) not null
-n of precedent owners | TINYINT null

