# pizzeria-Sannicandro-De-ruvo-Spagnoletta
# Relazione progetto SanderSpà Pizza

## 1. Scopo della relazione

Lo scopo di questo progetto è realizzare un sito web per una pizzeria chiamata **SanderSpà Pizza**. Il sito permette agli utenti di consultare il menu del ristorante, visualizzare le pizze, i dolci e le bevande disponibili e compilare un modulo per prenotare un tavolo.

L'obiettivo è creare un sito semplice, ordinato e facile da utilizzare, che permetta ai clienti di trovare rapidamente le informazioni principali della pizzeria e di inserire i dati necessari per una prenotazione.

## 2. Descrizione del progetto

Il sito web è stato realizzato utilizzando i linguaggi **HTML, CSS e JavaScript**.

- **HTML:** utilizzato per creare la struttura delle pagine, inserire testi, titoli, pulsanti, collegamenti, moduli e tabelle.
- **CSS:** utilizzato per personalizzare l'aspetto grafico del sito, scegliendo colori, caratteri, bordi, spaziature e allineamenti.
- **JavaScript:** utilizzato nella pagina `Visualizza.html` per recuperare i dati della prenotazione dall'indirizzo della pagina e mostrarli all'interno di una tabella.

Il progetto è composto da diverse pagine collegate tra loro.

### Pagina principale – `menu.html`

La pagina principale presenta il nome della pizzeria, lo slogan "La vera pizza italiana" e tre pulsanti che permettono di accedere alle sezioni dedicate alle pizze, ai dolci e alle bevande.

Nella parte inferiore sono presenti l'indirizzo, il numero di telefono e il pulsante per accedere alla pagina di prenotazione.

### Pagina delle pizze – `pizze.html`

Questa pagina contiene il menu delle pizze classiche, con il nome, il prezzo e una breve descrizione degli ingredienti. Tra le pizze presenti ci sono la Margherita, la Marinara, la Diavola, la Prosciutto e funghi, la Quattro formaggi e la Capricciosa.

È presente anche un collegamento per tornare alla pagina principale.

### Pagina dei dolci – `dolci.html`

La pagina dei dolci presenta diverse proposte, tra cui Tiramisù, Panna cotta, Cheesecake, Profiteroles, Gelato e Pizza alla Nutella. Per ogni dolce sono indicati il prezzo e una breve descrizione.

### Pagina delle bevande – `bevande.html`

Questa pagina è divisa in due categorie: bevande analcoliche e bevande calde. Sono presenti prodotti come acqua, Coca-Cola, Fanta, Sprite, tè freddo, succhi di frutta, caffè e cappuccino, con i relativi prezzi.

### Pagina di prenotazione – `prenotazione.html`

Questa pagina contiene un modulo HTML che permette al cliente di inserire il proprio nome, cognome, data della prenotazione, numero di persone, orario e numero di telefono.

I campi principali sono obbligatori e l'orario selezionabile è compreso tra le 19:30 e le 23:00. Il modulo utilizza il metodo `GET` per inviare i dati alla pagina `Visualizza.html`.

Sono inoltre presenti il pulsante per inviare la prenotazione e quello per azzerare i campi del modulo.

### Pagina di visualizzazione – `Visualizza.html`

Questa pagina riceve i dati inseriti nel modulo e li mostra in una tabella. Per recuperare le informazioni viene utilizzato JavaScript, attraverso l'oggetto `URLSearchParams`, che permette di leggere i parametri presenti nell'indirizzo della pagina.

In questo modo è possibile visualizzare in maniera ordinata il riepilogo dei dati inseriti dall'utente.

### Aspetto grafico

Per mantenere uno stile uniforme, tutte le pagine utilizzano una grafica simile, con uno sfondo color crema, testo marrone scuro e bordi rosso scuro. Il carattere utilizzato è Georgia, mentre il contenuto è organizzato in riquadri centrati nella pagina.

Queste scelte rendono il sito ordinato e permettono di riconoscere facilmente le diverse sezioni.

## 3. Conclusione

Realizzando questo progetto ho imparato a creare e collegare più pagine web utilizzando HTML, a personalizzarle con CSS e a utilizzare JavaScript per gestire e visualizzare i dati inseriti in un modulo.

Ho inoltre approfondito l'utilizzo dei collegamenti tra pagine, dei campi di input, dei pulsanti, delle tabelle e dei parametri trasmessi tramite il metodo `GET`.

Il progetto mi ha permesso di mettere in pratica le conoscenze acquisite durante le lezioni e di comprendere meglio come si realizza un sito web composto da più pagine. In conclusione, il risultato è un sito semplice e funzionale che permette di consultare il menu della pizzeria e di inserire i dati per una prenotazione.

