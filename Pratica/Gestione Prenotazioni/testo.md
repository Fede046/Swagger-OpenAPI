Esercizio: API REST per la gestione di un sistema di prenotazioni
Progettare un'API REST (parziale) per la gestione di un sistema di prenotazioni di eventi.
Il sistema è organizzato in eventi, ognuno individuato da un ID (intero), un titolo (string), una data di svolgimento e una capienza massima (intero); ogni evento include un insieme di prenotazioni, ognuna caratterizzata da un ID (intero), una data di creazione, un nome del partecipante (string) e un numero di posti richiesti (intero).
Requisiti
Scrivere un file in formato JSON o YAML.
Funzionalità dell'API
L'API permette di:

Ottenere l'elenco di tutte le prenotazioni effettuate da un partecipante (dato il nome) per un determinato evento
Aggiungere una nuova prenotazione ad un evento esistente
Modificare il numero di posti richiesti in una prenotazione esistente

Specifiche tecniche
Per ogni endpoint specificare:

URL di accesso
Metodi HTTP
Parametri (path, query, body)
Risposte con codici di stato ed esempi

L'API restituisce un errore con codice 400 se i parametri in input non sono corretti.
Note

Non è richiesto includere le sezioni host, schemes, servers, tags
Non è richiesto gestire autenticazione
Utilizzare la specifica OpenAPI/Swagger 2.0 o 3.0
Includere definizioni complete dei modelli dati dove appropriato


Suggerimento: Prestare attenzione alla corretta definizione dei path parameters, query parameters e request body per ogni operazione richiesta.