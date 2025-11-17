Progettare un API REST (parziale) per la gestione di una collana di racconti e descriverla in
Swagger/OpenAPI.
La collana è organizzata in uscite, una per ogni mese, e in ogni uscita ci sono diversi racconti.
Ogni uscita è caratterizzata da un identificativo numerico che rappresenta anno e mese (di tipo
stringa, sintassi arbitraria) e un prezzo (valore intero). Ogni racconto è identificato da un numero
intero progressivo, che riparte da 1 in ogni uscita, da un titolo (stringa) e da una lunghezza in
pagine (di tipo intero).
Scrivere un file in formato JSON o YAML.
L’API permette di:
1. elencare tutte i racconti in una data uscita e con almeno X pagine
2. aggiornare il numero di pagine di un racconto
3. cancellare tutte le uscite di un determinato anno
Scrivere un file in formato JSON o YAML.
Specificare: URL di accesso, metodi HTTP, parametri e risposte con esempi.
L’API restituisce un errore, con codice 400, se i parametri in input non sono corretti.
Note:
● Non è richiesto includere le sezioni host, schemes, servers, tags
● Non è richiesto gestire autenticazione