# Passaggi per la pull request

## Branch protection
Significa proteggere il branch principale (master) di un repository. In questo modo l'unica possibilità per aggiungere componenti in produzione è quella di effettuare delle pull request.

Una volta entrati nel repository in GitHub, possiamo  configurare la protezione del branch in questo modo:
- Prima clicchiamo sulla tab dei Settings
- Nella barra di destra troviamo il link branches e lo clicchiamo.
- Appare il bottone Add Protection Rule, clicchiamo e iniziamo ad impostare le restrizioni.

Le opzioni che è possibile selezionare includono:

- Require status checks: Questa opzione richiede che il codice venga compilato e testato prima di poter essere pushato sul branch.
- Require reviews: Questa opzione richiede che il codice venga esaminato da un altro sviluppatore prima di poter essere pushato sul branch.
- Require a merge request: Questa opzione richiede che il codice venga unito a un altro branch prima di poter essere pushato sul branch.
- Block direct pushes: Questa opzione blocca tutti i push diretti sul branch.

Una volta configurata la protezione del branch, non sarà più possibile pushare sul branch senza soddisfare le condizioni specificate.

Ecco alcuni suggerimenti per utilizzare la protezione del branch in modo efficace:

Proteggi il branch principale: Il branch principale è il branch più importante del repository, quindi è importante proteggerlo.
Richiedi la compilazione e i test: Questa opzione aiuterà a garantire che il codice sia compilabile e che passi tutti i test.
Richiedi le revisioni: Questa opzione aiuterà a garantire che il codice sia esaminato da un altro sviluppatore prima di essere pushato sul branch principale.
Richiedi una pull request: Questa opzione aiuterà a garantire che il codice venga unito a un altro branch prima di essere pushato sul branch principale.
Blocca i push diretti: Questa opzione aiuterà a impedire che il codice venga pushato sul branch principale direttamente.
La protezione del branch è uno strumento potente che può aiutare a proteggere la qualità e la sicurezza del codice.
