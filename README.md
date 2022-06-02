# Housescape

Progetto di Linguaggi e tecnologie per il web Anno Accademico 2021-22
Autori: Rosapia Laudati, Lorenzo Mastrandrea e Lorenzo Frangella.
 
Il nostro progetto consiste nella realizzazione di un gioco in stile escape room completamente online.
Le tecnologie utilizzate per lo sviluppo di tale progetto sono state:
Lato server: PHP
Database: PostgreSQL
Lato client: HTML(Con qualche componente di bootstrap), CSS, Javascript (Utilizzando Ajax e JQuery come librerie)
Tutta l'applicazione è stata sviluppata in modo da avere un design responsive, questo grazie alla presenza di media query in css e anche grazie alla presenza di librerie Jquery che rendono responsive le mappe di immagini presenti nel gioco.
Il file zip che stiamo allegando contiene soltanto i file .php .html e .js. quindi non abbiamo allegato nessun tipo di file multimediale. Se si volesse scaricare una copia completa del progetto originale, lasciamo il link alla repository su github: https://github.com/LorenzoFrangella/Housescape
Un piccolo indice che indica i nomi dei file e a cosa si riferiscono:
PHP:
- index.php -> pagina principale
- registrazione.php -> pagina di registrazione
- login.php -> pagina di login
- ceck_registrazione.php -> pagina che una volta validata la form di registrazione inserisce l'utente nel database
- ceck_login.php -> pagina che una volta validata la form di login permette di inizializzare le variabili di sessione
- classifica.php -> pagina di classifica
- controllo.php -> script che viene eseguito tramite ajax in modo asincrono in registrazione.php per controllare nickname ed email
- gioco_completato.php -> pagina che viene visualizzata quando il gioco è terminato
- primo_livello.php -> pagina contenente l'interfaccia di gioco, con le iframe delle varie stanze
- introduzione.php -> introduzione che viene visualizzata appena si entra nel gioco
- page1.php -> prima stanza del gioco
- page2.php -> seconda stanza del gioco
- page3.php -> terza stanza del gioco
- tempo_scaduto.php -> pagina che viene visualizzata se non si finisce in tempo il gioco
JAVASCRIPT:
- housescape.js -> file javascript che contiene la maggio parte del codice javascript del gioco
- page1.js -> file javascript della prima stanza del gioco
- page2.js -> file javascript della seconda stanza del gioco
- page3.js -> file javascript della terza stanza del gioco
- valida_login.js -> file javascript che viene utilizzato per validare la form di login
- valida_registrazione.js -> file javascript che viene utilizzato per validare la form di registrazione
CSS:
 
- stile.css -> foglio di stile generale che contiene le definzione per tutti i componenti di base del sito
- primo_livello.css -> foglio di stile della pagina che contiene le stanze
- stile_pg3.css -> foglio che contiene alcune regole di stile per l'ultima stanza del gioco
CARTELLE:
timer -> contiene i file html, javascript e css necessari per la gestione del timer
audio -> contiene i suoni del gioco
css -> contiene i fogli di stile presi da bootstrap
js -> contiene gli script presi da bootstrap
orologio -> contiene i fogli di stile e javascript per l'indovinello dell'orologio
giochi -> contiene la cartella piano che contiene i file html, javascript e css per l'indovinello del pianoforte
 
All' interno del codice inoltre sono presenti dei commenti che permetteranno una migliore comprensione.

