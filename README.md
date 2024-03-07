Tecnologie innovative per la piattaforma unica della Trasparenza
================================================================

Obiettivi
---------

L'obietto principale di questo progetto lo studio, progettazione e realizzazione di una piattaforma
automatizzata per la raccolta, l’analisi e la validazione delle informazioni relative alla
Trasparenza Amministrativa presenti sui siti delle PA e dei soggetti che rientrano nel campo di
applicazione del d.lgs. n. 33/2013, contribuendo alla progettazione della piattaforma unica per la
trasparenza amministrativa finalizzata alla diffusione delle informazioni delle PA e facilitarne
la fruizione.

L'archifettura della piattaforma realizzata è composta da molti componenti integrati tra di loro,
questo repository contiene la documentazione dell'architettura generale, dei singoli componenti e
dei risultati di validazione ottenuti.

Generazione della documentazione
--------------------------------

Tutta la documentazione è presente nella cartella docs ed è scritta in formato restructuredText.
Per poter generare la documentazione è necessario installare le dipendente python tramite il comando

```
pip install -r requirements.txt
```

La generazione della documentazione è possibile tramite il comando 

```
make html
```

La documentazione in formato html sarà generata nella cartella *_build*.