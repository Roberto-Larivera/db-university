# db-university
## DB University

## Giorno 1

### Descrizione

Modellizzare la struttura di un database per memorizzare tutti i dati riguardanti una università:
- sono presenti diversi Dipartimenti (es.: Lettere e Filosofia, Matematica, Ingegneria ecc.);
- ogni Dipartimento offre più Corsi di Laurea (es.: Civiltà e Letterature Classiche, Informatica, Ingegneria Elettronica ecc..)
- ogni Corso di Laurea prevede diversi Corsi (es.: Letteratura Latina, Sistemi Operativi 1, Analisi Matematica 2 ecc.);
- ogni Corso può essere tenuto da diversi Insegnanti;
- ogni Corso prevede più appelli d'Esame;
- ogni Studente è iscritto ad un solo Corso di Laurea;
- ogni Studente può iscriversi a più appelli di Esame;
- per ogni appello d'Esame a cui lo Studente ha partecipato, è necessario memorizzare il voto ottenuto, anche se non sufficiente.

Pensiamo a quali entità (tabelle) creare per il nostro database e cerchiamo poi di stabilirne le relazioni. Infine, andiamo a definire le colonne e i tipi di dato di ogni tabella.
Utilizzare https://www.diagrams.net/ per la creazione dello schema.
Esportare quindi il diagramma in jpg e caricarlo nella repo.


<a href="https://github.com/Roberto-Larivera/db-university/blob/main/DBUniversity.drawio.svg"> Esercizio_Giorno_1 Struttura </a>


## Giorno 2

### Descrizione

Dopo aver creato un nuovo database nel vostro phpMyAdmin e aver importato lo schema allegato, eseguite le query del file allegato.
Cosa consegnare?
Dopo aver testato le vostre query con phpMyAdmin, riportatele in un file txt e caricatelo nella vostra repo.

<a href="https://github.com/Roberto-Larivera/db-university/blob/main/query_select.txt"> Esercizio_Giorno_2 Select </a>



## Giorno 3

### Descrizione

Utilizzando lo stesso database di ieri, eseguite le query in allegato.
Caricate un secondo file nella stessa repo di ieri (db-university) con le query di oggi.

<a href="https://github.com/Roberto-Larivera/db-university/blob/main/query_group-by.txt"> Esercizio_Giorno_3 Group By</a>

<a href="https://github.com/Roberto-Larivera/db-university/blob/main/query_join.txt"> Esercizio_Giorno_3 Join</a>
