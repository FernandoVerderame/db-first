Ciao ragazzi,
Esercizio di oggi: DB First
nome repo: db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.
Non sono sicuro del fatto che possiate caricare direttamente un Excel, chiedo conferma a 
@Michele Spiller
 e 
@Marius Minia
Buon lavoro e a domani!



Colonne|Tipo|Attributi
---|---|---
id| BIGINT | PRIMATY_KEY, AUTO_INCREMENT
marca| VARCHAR | NOTNULL
targa| CHAR(7) | NOTNULL, UNIQUE
modello| VARCHAR(20) | NOTNULL
prezzo| MEDIUMINT | NOTNULL
km_percorsi| MEDIUMINT | NOTNULL
porte| TINYINT | NOTNULL
posti| TYNYINT | NOTNULL
potenza(CV)| SMALLINT | NOTNULL
tipologia_cambio | CHAR(1) | NOTNULL
carburante| CHAR(1) | NOTNULL
anno_immatricolazione| YEAR | NOTNULL