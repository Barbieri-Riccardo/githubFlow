RISPOSTE ALLE DOMANDE:
1) Cos’è e a cosa serve il GitHub flow?
GitHub Flow è un modello di sviluppore che permette di ottenere vantaggi enormi dall’utillo di Git, e come questo aiuti lo sviluppo agile di software  lavora in ambiente di continuo sviluppo di "release" perchè ogni volta che c’è un push questo va direttamente nel master e quindi può essere messo in deploy.

2) Per quale ragione si vuole che tutto ciò che sta nel main (o master) branch sia deployable?
Il motivo è perchè nel main sarà inserito il codice finale e il codice finale deve essere stato verificato, testato e controllato in modo completo perchè sara quello che verrà pubblicato e dovrà rimanere stabile e sicuro per gli utenti che lo utilizzeranno.

3) Per quale ragione ogni sviluppatore deve lavorare su un proprio branch? A cosa serve dare nomi significativi ai branch?
gli sviluppatori utilizzano branch secondari per non compromettere il main branch , in questo modo le modifiche che apportano possono venir controllate prima di applicarle (merge)  al main branch. Dare un nome esplicativo ad un branch aiuta a far comprendere agli altri sviluppatori lo scopo del branch .

4) In che modo un git fetch può dare una panoramica su cosa stanno facendo tutti all’interno del gruppo di lavoro?
Il comando git fetch permette a chi lo esegue di vedere tutte le modifiche (commit) e tutti i branch che gli altri hanno creato così da avere una panoramica di chi ha apportato determinate modifiche e chi sta lavorando di più e su quale parte del codice






6)Per quale ragione è meglio fare un merge del codice dopo una review?
è meglio fare una review prima di fare un merge perchè così un programmatore che non è chi ha scritto quel codice effettua un controllo del codice trovando un modo per migliorarlo o per risolvere gli errori che ci sono all'interno evitando così di creare problemi all'interno del main risolvendoli prima
