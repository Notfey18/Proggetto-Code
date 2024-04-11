git# Cos’è Git?
Git è un *sistema di controllo di versione distribuito* (VCS,version control sistem) utilizzato per gestire progetti software e tracciare le modifiche apportate ai file nel corso del tempo. Consente ai team di collaborare, tenere traccia delle modifiche, coordinare il lavoro e gestire il codice sorgente in modo efficiente. Git consente agli sviluppatori di lavorare in modo collaborativ#o su progetti di qualsiasi dimensione, mantenendo un registro delle modifiche e consentendo di tornare a versioni precedenti del codice se necessario.
Dopo aver scaricato e configurato Git impostando il nome dell’utente e la mail si può cominciare a tenere traccia delle modifiche apportate ai file utilizzando il comando *Init*.S
Una *repository*, o repo abbreviato, in termini informatici, è un luogo in cui vengono conservati e gestiti i file di un progetto, insieme alla cronologia delle modifiche apportate a tali file nel tempo. È una sorta di archivio digitale in cui vengono conservati tutti i file, come codice sorgente, documentazione, immagini, ecc., relativi a un progetto software o a un qualsiasi altro tipo di progetto.

Ecco alcuni comandi essenziali per chi comincia ad utilizzare Git:
1.	git init: Inizializza un nuovo repository Git nella directory corrente.
2.	git clone <URL>: Clona un repository Git esistente dalla specificata URL. Questo è il modo più comune per iniziare a lavorare su un progetto esistente.
3.	git add <file>: Aggiunge un file specifico al "staging area", preparandolo per il commit.
4.	git add .: Aggiunge tutte le modifiche nella directory corrente al "staging area".
5.	git commit -m "messaggio": Crea un nuovo commit con le modifiche che sono state precedentemente aggiunte al "staging area", con un messaggio descrittivo.
6.	git status: Mostra lo stato corrente del repository, inclusi i file modificati, i file nell'area di staging e i filenon tracciati.
7.	git log: Visualizza la cronologia dei commit, elencando tutti i commit nel repository con i relativi dettagli.
8.	git branch: Visualizza l'elenco delle branch presenti nel repository e mostra quella attualmente selezionata.
9.	git checkout -b <nome_branch>: Crea una nuova branch e si sposta su di essa.
10.	git checkout <nome_branch>: Si sposta su una branch esistente.
11.	git merge <nome_branch>: Unisce una branch specificata con quella attualmente selezionata.
12.	git pull: Recupera le modifiche dal repository remoto e le integra nel branch locale corrente.
13.	git push: Carica i commit locali su un repository remoto.
14. git remote add origin <URL di github>
15. git push origin master: stai essenzialmente dicendo a Git di caricare i tuoi commit dalla branch locale denominata "master" al repository remoto denominato "origin". Questo comando è utile quando hai fatto delle modifiche nel tuo repository locale e desideri aggiornare il repository remoto con queste modifiche.
