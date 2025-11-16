Progettare un'API REST per la gestione di una libreria digitale.
Requisiti
Ogni libro è caratterizzato da:

Un ID (di tipo intero per semplicità)
Un titolo (string)
Un genere, che può assumere valori: Romanzo, Giallo, Fantascienza, Saggistica, o Biografia
Un numero di pagine (intero)
Una valutazione media (numero decimale da 0.0 a 5.0)

Funzionalità dell'API
Scrivere un file in formato JSON o YAML che permetta di:

Ottenere l'elenco di tutti i libri di un dato genere con valutazione superiore a un valore minimo specificato
Modificare il numero di pagine e la valutazione di un libro esistente
Aggiungere un insieme di libri e le relative informazioni; deve essere possibile aggiungere anche più di un libro con un'unica richiesta

Specifiche Tecniche
Per ogni endpoint specificare:

URL di accesso
Metodi HTTP
Parametri (path, query, body)
Risposte con codici di stato ed esempi

L'API deve restituire un errore con codice 400 se i parametri in input non sono corretti.
Note Importanti

Non è richiesto includere le sezioni servers, tags
Non è richiesto gestire autenticazione
Utilizzare la specifica OpenAPI/Swagger 2.0
Includere definizioni complete dei modelli dati