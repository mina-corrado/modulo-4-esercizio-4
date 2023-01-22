# Esercizi

## Negozio di libri EPICO 📚

Sei incaricato di creare la funzione di carrello per un marketplace online.

Usa tutti i nuovi tools e features che hai imparato per creare un’applicazione con i seguenti requisiti:

– Una homepage che mostri tutti i libri con delle card di bootstrap
– Le card dovrebbero avere un pulsante per aggiungere al carrello e uno per “saltare” un prodotto
– Una sezione per il carrello
– Un input di testo per cercare i libri

Per raggiungere questo risultato, segui queste istruzioni:

– Usa questo API per ottenere la lista di libri: `https://striveschool-api.herokuapp.com/books`
– Renderizza tutti i libri usando i template literars and .forEach o .map
– Aggiungi il pulsante “aggiungi al carrello” a tutte le card
– Quando il pulsante viene cliccato…
1. Aggiungi il libro alla lista del carrello
2. cambia lo stile della card per mostrare che è già stata aggiunta (un bordo colorato o un badge vanno bene)
– Aggiungi un bottone “salta” a tutte le card
– Quando cliccato, questo bottone dovrebbe far sparire la card corrispondente.
– Aggiungi un input di testo che funzioni come una barra di ricerca. Quando l’utente scrive più di 3 caratteri, filtra il risultato dell’API per renderizzare solo i libri con un titolo che corrisponda, anche parzialmente, al contenuto dell’input. SUGGERIMENTO: usa .filter()
– Dai la possibilità all’utente di cancellare libri dal loro carrello
– Conta gli elementi nel carrello usando “.reduce()” e mostra il risultato nella sezione carrello

### EXTRA:

1. Add a **empty cart** button, to delete the whole list
2. Aggiungi un pulsante per svuotare il carrello
3. Crea una pagine prodotto: quando l’utente clicca sul libro, deve essere portato ad un’altra pagine. Passa l’ASIN del libro come query nell’URL
4. Nella pagina prodotto, mostra i dettagli del libro con l’ASIN corrispondente usando questo endpoint: `https://striveschool-api.herokuapp.com/books/IL TUO ASIN QUI`