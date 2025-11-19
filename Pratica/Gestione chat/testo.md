Esercizio 3 
Progettare un API REST (parziale) per la gestione di una chat. La chat è organizzata in stanze, 
ognuna  individuata  da  un  ID  e  una  data  di  apertura;  ogni  stanza  include  un  insieme  di 
messaggi,  ognuno  caratterizzato  da  un  ID,  una  data  di  pubblicazione  ed  autore  e  testo, 
entrambi di tipo stringa.  
 
Scrivere un file in formato JSON o YAML. 
 
L’API permette di: 
●  cancellare tutti i messaggi scritti da uno stesso autore in una data stanza 
●  aggiungere un nuovo messaggio ad una stanza 
●  modificare la data di pubblicazione di un messaggio 
 
Specificare: URL di accesso, metodi HTTP, parametri e risposte con esempi. 
 
L’API restituisce un errore, con codice 400, se i parametri in input non sono corretti. 
 
Note: 
●  Non è richiesto includere le sezioni host, schemes, servers, tags 
●  Non è richiesto gestire autenticazione 
 
 
 
 