Ogni gioco è caratterizzato da un ID (di tipo intero per semplicità), un nome (string) e una
categoria, che può assumere valori Shooter, Adventure, Puzzle, o Sport, e un numero di giocatori
minimo e massimo, entrambi valori interi.
Scrivere un file in formato JSON o YAML.
L'API permette di:
· ottenere l'elenco di tutti i giochi di una data categoria
· modificare il numero minimo e massimo di giocatori in un gioco
· aggiungere un insieme di giochi e le relative informazioni; è possibile quindi aggiungere anche
più di un gioco con un'unica richiesta.
Specificare: URL di accesso, metodi HTTP, parametri e risposte con esempi. L'API restituisce un
errore, con codice 400, se i parametri in input non sono corretti.
Note:
· Non è richiesto includere le sezioni servers, tags
· Non è richiesto gestire autenticazione