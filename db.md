Db_NAME : concessionario 


Table name : auto usate

- id | INDEX | INT or BIGINT | NOTNULL | UNIQUE | AI
- marca  | VARCHAR(50) | NOTNULL |  UNIQUE 
- modello | VARCHAR(50) | NOTNULL  
- anno | YEAR | NOTNULL
- chilometraggio | SMALL/MEDIUMINT | NOTNULL 
- prezzo | FLAT(8,2) | NOTNULL  
- carburante | VARCHAR(50) | NOTNULL
- colore  VARCHAR(30) | NULL
- immagine VARCHAR(255) | NULL | DEFAULT('https:images/lorem10/.png')
- condizione VARCHAR(150) | NULL 
- note | TEXT | NULL


