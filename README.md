# ESERCIZIO

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!

# TABELLA AUTO IN CONCESSIONARIA

| COLONNA    | TIPO        | ATTRIBUTI           |
| ---------- | ----------- | ------------------- |
| marca      | varchar(50) | NOT NULL            |
| modello    | varchar(50) | NOT NULL            |
| cilindrata | tinyint     | NOT NULL            |
| carburante | varchar(3)  | NOT NULL            |
| anno       | tinyint     | UNSIGNED,NULL       |
| nuovo      | tinyint(1)  | UNSIGNED,DEFAULT(0) |
| usato      | tinyint     | UNSIGNED,DEFAULT(0) |
| foto       | varchar     | NULL                |
