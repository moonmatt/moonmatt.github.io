---
published: true
---
Ho ricominciato a lavorare a metmusic, e devo dire che sta procedendo molto bene.  
Sono riuscito ad implementare il corretto funzionamento del media player da mobile, ovvero i controlli che appaiono quando apri il menù a tendina oppure nella schermata di blocco.  

Ho migrato tutto il sistema da richieste post a socket, in modo da rendere tutto più leggero e veloce nelle comunicazioni, anche perchè le richieste, se effettuate in numero troppo grande, ad un certo punto smettevano di funzionare.  

Il frontend è messo abbastanza decentemente, sia da desktop che da mobile, anche se devo ancora sistemare alcuni punti.  

Inizialmente, a causa del metodo con cui prendevo i titoli delle canzoni, spesso erano troppo lunghi, grazie ad una libreria di npm che ho trovato sono riuscito a trasformare il titolo in una versione accorciata, che in coppia con l'artista della canzone dona un risultato pulito e semplice, ora faccio un esempio:  
Baby Gang - Blitz 2 (feat. Sofiane) [Official Video]  
diventa  
Blitz 2 (feat. Sofiane)

Adesso miglioro l'esperienza da mobile, visto che il suo utilizzo principale sarebbe quello.  
In seguito pulisco il codice e provo a pubblicarlo per tutti in versione open source, è un progetto personale, però nel dubbio sempre meglio condividere, così se qualcuno ne dovesse avere bisogno può usufruirne.  

PS: Per il frontent ho preso spunto da Apple Music e per caricare le canzoni da YouTube basta incollare nel popup il link della canzone o della playlist.  
Eh si, visto che caricare canzone per canzone risulta abbastanza noioso, ho implementato le playlist, bello mettere 30 canzoni alla volta eh? haha.  

Ora è presente anche il pulsante per cancellare le canzoni che non vogliamo più e i messaggi in basso a destra per comunicare messaggi dal server.

Quasi mi stavo dimenticando, è possibile anche cercare le canzoni, per nome, per artista, o qualsiasi cosa!

{% include streamablePlayer.html id=6jjv9p %}
