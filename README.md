# TAF-to-CSV
Converte una Tabella attuale dei punti fiduciali (Taf) dell' Agenzia delle Entrate in un file csv aggiungendo le opportune intestazioni

### Installazione

Per installarlo basta che scarichiate lo zip del repo e da QGIS fate installa plugin da zip. Spero a breve sia disponibile nel repository ufficiale di QGIS.

### Finestra processing
Il plugin, una volta caricato, compare negli script di processing nella cartella 'TAF to CSV'.

![uno](images/processing.png)

Una volta avviato inserire il file da convertire ed eventualmente il file di destinazione.

![due](images/finestra.png)

E' possibile deselezionare tra i campi disponibili (19 selezionati di default) quelli non desiderati e la loro eventuale riorganizzazione per trascinamento.

![tre](images/selezione_campi.png)

Una volta selezionati i campi di interesse e avviato il plugin si otterrà un file temporaneo o il file csv definitivo.

### Piccolo trick
Evidenziando il risultato nel log lo potete copiare e incollare direttamente nella finestra di caricamento file '**Data Source Manager - Testo Delimitato**'.

![tre](images/log_selection.png)

### Riferimenti
https://wwwt.agenziaentrate.gov.it/servizi/Monografie/taf/tracciato_taf.pdf

### Ringraziamenti
[QGIS.org](https://www.qgis.org/it/site/) - [Totò Fiandaca](https://pigrecoinfinito.com/) 