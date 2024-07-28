SUPSI 2022-23  
Corso d’interaction design, CV427.01  
Docenti: A. Gysin, G. Profeta  

Elaborato 2: Antologia a due mani  

# I guanti: accessorio dalle origini antiche
Autore: Chiara Andreoli  
[Sito Web Guanti](https://andreolichiara.github.io/pagina_guanti/)


## Introduzione e tema
Il compito assegnato era quello di realizzare una ricerca testuale e iconografica per raccontare l’aspetto, la funzionalità e la storia dell'oggetto da noi scelto, legato all'utilizzo della mano. Il tema che ho deciso di trattare riguarda i guanti, per tanto ho inizialmente fatto una ricerca sulla storia e le origini dell'oggetto, incrementando le informazioni attraverso immagini e catalogazioni.


## Riferimenti progettuali
Per quanto riguarda la sezione dedicata all'archivio, mi sono ispirata al  layout della pagina web "Mousse Magazine", dato l'utilizzo di una griglia per racchiudere le varie riviste.


https://www.moussemagazine.it/


## Design dell’interfraccia e modalià di interazione
Il sito che ho realizzato è principalmente statico. Nella parte iniziale della pagina è presente la barra di navigazione, con i titoli delle due pagine che ho realizzato sulla sinistra, mentre sulla destra troviamo l'indice. 
<br>

<video src="video/(0061-1)_bianco_nero.mp4" width="600">

<br>
Nella Home page è possibile trovare la parte testuale del sito. Ho deciso di dividere il contenuto in diverse sezioni, così da facilitare la lettura.
Ho iniziato parlando delle origini del guanto, per poi trattare "Il significato negativo dei guanti", "I guanti nella moda" e "L'evoluzione dei guanti nel lavoro".
<br>
<br>

<img src="doc/home.png" width="600">


Nella seconda pagina si trova l'archivio, suddiviso in tre macro categorie, contenente immagini, titolo, e descrizione di ogni specifico guanto attraverso un elenco. Troviamo un link "scopri di più" con il quale è possibile approfondire la storia del singolo oggetto e altre informazioni. <br>
<br>

<img src="doc/archivio.png" width="600">

<br>

Nella parte inferiore della pagina è presente il footer riportante i siti da cui sono state ricavate le foto e le informazioni, e di seguito tutti i dati del corso.


## Tecnologia usata
Il sito è stato realizzato tramite il codice HTML e CSS.
Nell'HTML ho inserito tutti gli elementi, utilizzando i classici tag come "h1" per i titoli, "p" per i paragrafi e via dicendo, mentre con il CSS ho potuto modificarli in base alle mie esigenze.
Per la suddivisione in colonne ho utilizzato il tag CSS "display: grid", così da mantenere spazio ai lati del titolo e del testo. <br> <br>
<p>
    
    .grid{
	display: grid;
	grid-template-columns: 10% 15% 15% 10% 25% 8%;
	grid-template-rows: 30px auto auto 90px;
    }
    
    .titolo-capitolo {
	grid-column: 2/2;
	grid-row: 2;
    }
    
    .paragrafo {
    grid-column: 4/6;
	grid-row: 2;
    }


</p>


## Target e contesto d’uso
Questo sito è destinato sia a coloro interessati al tema trattato ma anche a chi vorrebbe sapere quante tipologie di guanti esistono e le caratteristiche principali di quest'ultimi. I contesti di utilizzo possono variare, infatti il sito si può utilizzare sia per interesse personale ma anche come enciclopedia per ricerche o informazioni.

