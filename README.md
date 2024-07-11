Esercizio di oggi: *Carosello Array di Oggetti*
nome repo: *js-array-objects-carousel*
*Consegna:*
Dato il seguente array di oggetti
(vedi script.js)
Creare un carosello. Se non avete fantasia potete copiare l'immagine allegata (è comprensiva di bonus).
Numero di push minimi: 10
Raccomandazione: seguite le milestone una per una. Ricordarsi/rivedere il live coding della mattina
può essere d'aiuto
*Milestone 0:*
Come visto a lezione, focalizziamoci prima sulla creazione del markup statico: costruiamo il container e inseriamo l'immagine grande in modo da poter stilare lo slider.
*Milestone 1:*
Ora rimuoviamo i contenuti statici e usiamo l’array di oggetti letterali per popolare dinamicamente il carosello.
****
Al click dell'utente sulle frecce verso sinistra o destra, l'immagine attiva diventerà visibile e dovremo aggiungervi titolo e testo.
**Milestone 2:
Aggiungere il *ciclo infinito* del carosello.** Ovvero se la miniatura attiva è la prima e l'utente clicca la freccia verso destra, la miniatura che deve attivarsi sarà l'ultima e viceversa per l'ultima miniatura se l'utente clicca la freccia verso sinistra.
*BONUS 1:*
Aggiungere le thumbnails (sottoforma di miniatura) ed al click attivare l’immagine corrispondente.
*BONUS 2:*
Aggiungere funzionalità di autoplay: dopo un certo periodo di tempo (3 secondi) l’immagine attiva dovrà cambiare alla successiva.
*BONUS 3:*
Aggiungere bottoni di start/stop e di inversione del meccanismo di autoplay

Pseudocodice

1 creo i tag html contenitori delle immagini e del testo
2 inserisco l'immagine grande da visualizzare
3 definisco lo stile con css
4 rimuovo i contenuti statici dall'html 
5 inserisco gli oggetti contenuti nell'array
6 rendo non visibili (o in miniatura) gli oggetti diversi da quello in primo piano
7 aggiungo l'evento click ai relativi tag di scorrimento degli oggetti
8 imposto lo scorrimento degli oggetti in entrambe le direzioni