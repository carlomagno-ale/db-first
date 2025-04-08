# Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Table name: 'auto-usate'

- **id** (BIGINT) - primary key - auto_increment 
- **targa**  CHAR(7) - NONULL *(se il concessionario è italiano con 7 caratteri obbligatori) altrimenti VARCHAR(7) se si vuole mantenere la possibilità di immagazzinare sotto i 7 caratteri*
- **marca** VARCHAR(30) - NONULL
- **modello** VARCHAR(30) - NONULL
- **carrozzeria** VARCHAR(20) - NULL
- **tipo di cambio** TINYINT (manuale/automaico true/false) - NULL
- **trazione** VARCHAR(20) - NULL
- **alimentazione** VARCHAR(20) - NULL
- **anno** YEAR - NONULL
- **prezzo** INT - NULL
- **KM percorsi** INT - NONULL
- **cilindrata CM³** MEDIUMINT - NULL
- **potenza CV** SMALLINT - NULL
- **colore** VARCHAR(30) - NULL
- **porte** TINYINT - NULL
- **foto** VARCHAR(255) - NULL
- **disponibilità** TINYINT - NULL
- **note**  TEXT - NULL