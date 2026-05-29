# Concessionaria `Zio Scassone Revamped`

task: Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario. 

## Schema Tabella `cars`

| Nome Colonna | Tipo | Attributi | Index
|---|---|---|---|
| id | UNSIGNED INT | NOT NULL AUTO INCREMENT | PRIMARY KEY |
| marca | VARCHAR(20) | NOT NULL | INDEX |
| modello | VARCHAR(70) | NOT NULL | INDEX |
| anno_immatricolazione | YEAR | NOT NULL | INDEX |
| colore | VARCHAR(40) | NOT NULL | |
| stato_usura | VARCHAR(20) | NOT NULL | INDEX |
| tipo_carrozzeria | VARCHAR(30) | NOT NULL | INDEX |
| n_posti | UNSIGNED TINYINT | NOT NULL | | 
| n_porte | UNSIGNED TINYINT | NOT NULL | |
| capienza_baule_litri | SMALLINT | NULL DEFAULT NULL |
| ruota_scorta | UNSIGNED TINYINT | NOT NULL |
| tipo_carburante | VARCHAR(15) | NOT NULL | INDEX |
| elettrica | UNSIGNED TINYINT | NOT NULL | |
| elettrica_tipologia | VARCHAR(15) | NULL DEFAULT NULL | |
| classe_ambientale_euro | UNSIGNED TINYINT | NOT NULL | INDEX | 
| fascia_emissioni | VARCHAR(50) | NOT NULL | |
| targetbuyer | VARCHAR(40) | NOT NULL DEFAULT | |
| prezzo_vendita_consigliato | SMALLINT | NOT NULL | INDEX |
| prezzo_di_costo | SMALLINT | NOT NULL | |
| note | VARCHAR(255) | NULL | |
