# ESERCIZIO

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!

# TABELLA AUTO IN CONCESSIONARIA

| COLONNA         | TIPO        | ATTRIBUTI            |
| --------------- | ----------- | -------------------- |
| chassis         | brigint     | PRIMARY KEY!         |
| brand           | varchar(50) | NOT NULL             |
| model           | varchar(50) | NOT NULL             |
| displacement    | smallint    | UNSIGNED, NULL       |
| fuel            | varchar(25) | NOT NULL             |
| production year | year        | NOT NULL             |
| price           | mediumint   | NOT NULL             |
| number of owner | tinyint     | UNSIGNED, DEFAULT(1) |
| note            | text        | NULL                 |
| plate           | char(7)     | NOT NULL             |
| khilometer      | mediumint   | NOT NULL             |
| condition       | tinyint     | DEFAULT(1)           |
