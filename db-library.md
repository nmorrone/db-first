# DB FIRST

tabella: Auto Usate


- id PK AUTO_INCREMENT UNIQUE NOTNULL
- marca VARCHAR(30) NOTNULL
- modello VARCHAR(80) NOTNULL
- alimentazione VARCHAR(20) NULL
- colore VARCHAR(30) NULL
- anno YEAR NOTNULL
- kilometraggio DECIMAL (8, 2) DEFAULT(0) NOTNULL
- cambio VARCHAR(20) NULL
- cilindrata DECIMAL (4,1) NOTNULL
- potenza(kw) DECIMAL (5,1) NOTNULL
- consumo (l/100km) DECIMAL (4,1) NULL
- classe ambientale VARCHAR (20) NULL
//esempio Euro5, Euro6..
- peso(kg) DECIMAL (6,1) NULL
- numero telaio CHAR(17) NOTNULL UNIQUE
- prezzo DECIMAL (8, 2) NOTNULL DEFAULT (0)
- lista optional TEXT NULL