## consegna
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## esercizio

Table name: car_listing
- id transazione -> Primary Key, SMALL/MEDIUMINT, NOTNULL, AUTO_INCREMENT, UNIQUE
- data dell'inserimento -> DATE, DEFAULT(attuale)
- casa madre -> VARCHAR(50)
- modello auto -> VARCHAR(50)
- categoria veicolo (suv, citycar, van, motocicletta...) -> VARCHAR(50)
- alimentazione (benzina, diesel, elettrico, ibrido) -> VARCHAR(50)
- colore -> VARCHAR(50)
- disponibilità (pronta consegna o differita) -> BOOLEAN
- condizioni (nuovo, auto aziendale km 0, usato in ottime condizioni...) -> TEXT, NOTNULL
- venduto (si, no) -> BOOLEAN (BLOB?)
- data della vendita -> DATETIME
- prezzo di vendita -> DECIMAL(10, 4), NOTNULL
- utile prodotto -> DECIMAL(10, 4)
- venditore addetto -> VARCHAR(100)
- nome acquirente -> VARCHAR(100)
- cognome acquirente -> VARCHAR(100)
- mail acquirente -> VARCHAR(100)
- età acquirente -> TINYINT
- data per il primo tagliando -> DATE
- data scadenza garanzia -> DATE
- note -> TEXT 

