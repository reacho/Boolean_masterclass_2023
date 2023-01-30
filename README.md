# Boolean_masterclass_2023

Codici mostrati durante la Masterclass di Boolean (febbraio 2023).

keras_train.ipynb contiene un codice che addestra una rete neurale sul dataset MNIST. 
Il codice controlla se esiste un modello già addestrato in locale. 
Se esiste, il modello viene caricato. Altrimenti, se non esiste o se il caricamento va storto, il modello viene addestrato e salvato.
Si apre poi una schermata interattiva che consente di testare la rete neurale: scrivendo una cifra e poi cliccando "Save image" e poi "Get label" si otterrà il label previsto dalla rete.
Il pulsante "Clear" cancella l'immagine e permette di ricominciare.

keras_chatGPT.ipynb è il codice scritto da chatGPT che fa le stesse cose viste sopra (addestra una rete neurale su MNIST).