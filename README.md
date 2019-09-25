# UF2 Installazione di wordpress
Guida a come installare correttamente passo dopo passo WordPress in locale


#### Indice
[Scaricare il necessario](#download)  
[Preparare le cartelle](#folder)  
[Preparare il database](#database)  
[Avviare WordPress](#wordpress)  

<a name="download"></a>
## Scaricare il necessario
Per poter installare e far funzionare WordPress sulla nostra macchina avremo bisogno di **installare un software che simuli un `web server` nel nostro computer**.
Ne esistono di vari, i più famosi sono **XAMPP** (windows) e **MAMP** (mac).
Entrambi sono molto validi e sta a voi scegliere in base alle vostre esigenze.
[Questo è il link per scaricare XAMPP](https://www.apachefriends.org/it/download.html) mentre [questo è per scaricare MAMP](https://www.mamp.info/en/downloads/).
Scaricate e installate pure.

Oltre questo sarà necessario **scaricare l’ultima versione di WordPress**.

Per farlo vi basterà andare su [https://it.wordpress.org] scorrere fino in fondo e premere **Scarica WordPress**.
Dalla pagina che si apre, di nuovo **scarica WordPress x.x.x**.

<a name="folder"></a>
## Preparare le cartelle
Dopo aver scaricato WordPress e installato XAMPP / MAMP dovrete preparare le cartelle.

Quindi estraete il contenuto dell’archivio `.zip` scaricato dal sito *wordpress.org*, date un nome alla cartella appena estratta a vostro piacimento (di default dovrebbe essere wordpress) e copiatela all’interno della cartella HTDOCS appena creata da XAMPP o MAMP.

WINDOWS: La cartella HTDOCS sarà in `C > XAMPP / MAMP > HTDOCS`.
MAC: La cartella HTDOCS sarà in `Applicazioni > MAMP > HTDOCS`. Se volete potete utilizzare Spotlight per trovarla prima. In quel caso vi basterà avviarlo premendo `CMD + SPAZIO` oppure `premere sull'icona della lente di ingrandimento in alto a destra` e cercare `htdocs`.

<a name="database"></a>
## Preparare il database
Grazie a XAMPP o MAMP abbiamo la possibilità di crearne quanti vogliamo. Ci basterà avviare il programma scelto, **se XAMPP ricordatevi di premere START sulle voci APACHE e MYSQL**.

#### Adesso dovremo inserire svariate credenziali, se credete di non ricordarle appuntatevele su un foglio. 

Dopo aver fatto ciò cliccate su PHPmyadmin. Dalla colonna di sinistra potrete creare un nuovo DB. Assegnateli pure il nome che volete (il mio consiglio è quello di darli il nome del cliente con la digitura `_db` alla fine (esempio: `cna_db`). 

Sarà necessario anche creare l'utente con i massimi privilegi nel DB. 
Per farlo dovrete selezionare il DB appena creato nella colonna di sinistra e, nella pagina che si aprirà, nella riga in alto selezionare `Privilegi`, se non dovesse apparire provate a cliccare prima su `Più` dovrebbe spuntare un menu a tendina in cui apparirà la voce `privilegi`.
Date lo stesso nome che avete dato al Database con la differenza che, invece di `_db` dovrete utilizzare `_user` (esempio: `cba_user`). Come `Host` inserite `localhost`.
Scorrendo più in basso assegnate tutti i privilegi all'utente e date la conferma **premendo il bottone in basso a destra**.

<a name="wordpress"></a>
## Avviare WordPress
Ci siamo! Se tutto è stato fatto correttamente vi basterà digitare nella barra degli indirizzi del vostro browser preferito (speriamo sia chrome o firefox) `localhost/nome_wordpress`

Quindi ad esempio se nel punto numero 2 avete chiamato la vostra cartella `cna` vi basterà digitare `localhost/cna`.
Qui WordPress vi chiederà svariati dati, dopo aver premuto su “iniziamo”. Inserite i dati che avete utilizzato nel punto numero 3 e continuate. 

Se tutto è andato correttamente WordPress dovrebbe chiedervi di inserire il title del sito, il nome utente e la password. Questi saranno i dati che utilizzerete da ora in poi per accedere al pannello di controllo di questa installazione di WordPress. Vi consiglio di appuntare anche questi. 
