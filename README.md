# Esercizio di oggi: Database First

## Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!

# Bonus:

nomi colonne in inglese

| Column           | Type        | Attributes           |
| ---------------- | ----------- | -------------------- |
| Chassis          | BIGINT      | Primary Key          |
| Brand            | VARCHAR(50) | NOTNULL              |
| Model            | VARCHAR(50) | NOTNULL              |
| Displacement     | SMALLINT    | UNSIGNED, NULL       |
| Production Year  | YEAR        | NOTNULL              |
| Price            | MEDIUMINT   | UNSIGNED, NOTNULL    |
| Number of owners | TINYINT     | UNSIGNED, DEFAULT(1) |
| Note             | TEXT        | NULL                 |
| Plate            | CHAR(7)     | NOTNULL              |
| Km               | MEDIUMINT   | UNSIGNED, NOTNULL    |
| Fuel             | VARCHAR(25) | NOTNULL              |
