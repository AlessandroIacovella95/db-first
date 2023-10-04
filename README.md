# Esercizio di oggi: Database First

## Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!

# Bonus:

nomi colonne in inglese

| Column           | Type        | Attributes           |
| ---------------- | ----------- | -------------------- |
| chassis          | BIGINT      | Primary Key          |
| brand            | VARCHAR(50) | NOTNULL              |
| model            | VARCHAR(50) | NOTNULL              |
| displacement     | SMALLINT    | UNSIGNED, NULL       |
| production_year  | YEAR        | NOTNULL              |
| price            | MEDIUMINT   | UNSIGNED, NOTNULL    |
| number_of_owners | TINYINT     | UNSIGNED, DEFAULT(1) |
| note             | TEXT        | NULL                 |
| plate            | CHAR(7)     | NOTNULL              |
| km               | MEDIUMINT   | UNSIGNED, NOTNULL    |
| fuel             | VARCHAR(25) | NOTNULL              |
| condition        | TINYINT     | DEFAULT(1)           |
