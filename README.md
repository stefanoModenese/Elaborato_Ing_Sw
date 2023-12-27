<img alt="img_1.png" height="" src="img_1.png" width="50"/>WORK IN PROGRESS<img alt="img_1.png" height="" src="img_1.png" width="50"/>

# MENTCARE #

Laura Canaia VR489361    
Stefano Modenese VR491230

## Informazioni generali ##

****

## Requisiti ##
Informazioni generali sul progetto -> si richiede di sviluppare un componente per il sistema
mentcare con diversi tipi di funzionalità. \
Il componente deve rappresentare 7 scenari

****

## Scenari ##

Gli scenari sono stati modellati partendo dall'idea di implementare un componente per l'accesso utente al
sistema in modo che sia in grado di prenotare visite, richiedere farmaci, etc ...

### 1. Login ###
__Assunzioni iniziali :__ L'utente si è appena collegato al sito e si interfaccia con la pagina di Login.       
Se l'utente si fosse precedentemente connesso, ora deve ri-loggarsi in modo da poter accedere al sistema.       
__Funzionamento standard :__ La schermata si presenta come un semplice form nel quale viene richiesto all'utente
di loggarsi inserendo il proprio nome utente, password e cliccare il pulsante di login per poter effettuare l'accesso.
Se l'utente sa di non essere registrato, è presente anche un pulsante per permettere di registrarsi.     
__Possibili funzionamenti errati :__ se l'utente tenta di loggarsi senza prima essersi registrato, il sistema 
mostra un messaggio di errore all'utente chiedendo di reinserire le credenziali oppure di registrarsi al sistema.  
__Cosa succede in caso l'esecuzione vada a buon fine :__ l'utente accede senza problemi nel sistema e passa ad un'altra pagina


### 2. Registrazione ###
__Assunzioni iniziali :__ L'utente non possiede un account e accede alla schermata di registrazione tramite il 
pulsante presente sulla schermata di login.   
__Funzionamento standard :__ L'utente si registra al sistema tramite la compilazione del form inserendo : nome, cognome,
codice fiscale, password. Dopo aver inserito tutti i parametri l'utente deve cliccare il pulsante "registrati".   
__Possibili funzionamenti errati :__ Ci sono diversi possibili comportamenti inattesi che possono portare il sistema in
errore :    
a) Se i campi non sono stati tutti compilati, l'utente riceve un messaggio di errore dedicato;    
b) Se il codice fiscale non è valido, nella schermata compare un messaggio di errore dedicato;     
c) Se la password non rispetta le indicazioni date, viene restituito un messaggio di errore dedicato.   
__Cosa succede in caso l'esecuzione vada a buon fine :__ l'utente viene registrato correttamente e viene reindirizzato
alla schermata di login dove potrà accedere al sistema inserendo le credenziali appena create.

### 3. Home Page ###
__Assunzioni iniziali :__ L'utente ha effettuato l'accesso al sistema.    
__Fuznionamento standard :__ All'utente si presenta una pagina con il proprio nome, con a fianco ad esso 2 pulsanti : il 
pulsante di logout e quello di prenotazione di una nuova visita.   
Sotto di esso vi è una tabella (con anche 0 righe potenzialmente) con tutte le visite che sono in programma e, per ogni 
visita nella tabella, c'è la possibilità di modificarla o di cancellarla tramite un pulsante a fianco.    
__Possibili funzionamenti errati :__ essendo una pagina "di passaggio" per altri scenari, l'utente non può direttamente
causare dei funzionamenti inaspettati.    
__Cosa succede in caso l'esecuzione vada a buon fine :__ L'utente riesce ad accedere alla sezione collegata al pulsante
o effettua il logout

### 4. Prenotazione visita ###

### 5. Modifica Visita ###

### 6. Cancellazione visita ###

### 7. Logout ###

****

## Testing ##