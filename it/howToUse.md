[`Guarda il video di introduzione su YouTube`](https://youtu.be/uN3GkA_Afuw)

## Concetti

I concetti principali di Daily Money sono molto semplici, ce ne sono solo tre:

> 1. Uno o più `Libri Contabili`
> 2. Vari `Conti` all'interno dei Libri Contabili
> 3. Trasferire importi tra conti diversi e registrare queste `Transazioni`

## ![Libri Contabili](icon:///notebook-multiple) Libri Contabili

È richiesto almeno un Libro Contabile, con conti che hanno la stessa unità di valuta. Puoi anche creare più Libri Contabili con la stessa unità di valuta in base alle tue esigenze.

## ![Conti](icon:///bookmark-multiple) Conti

Ci sono cinque tipi di conti diversi, che puoi aggiungere, modificare o eliminare nella schermata di gestione dei conti.

> - `Entrate`: Stipendio, ecc.
> - `Spese`: Cibo, intrattenimento, ecc.
> - `Attività`: Contanti, banca, ecc.
> - `Passività`: Carte di credito, prestiti, ecc.
> - `Altro`: ...

* I nomi dei conti possono utilizzare punti (.) per separare (ad esempio, Cibo.Ristorante, Cibo.Riunioni), fornendo una migliore visualizzazione gerarchica durante la selezione dei conti o la visualizzazione del bilancio.
* Puoi ordinare i conti per dare priorità a quelli utilizzati più frequentemente.

## ![Transazioni](icon:///receipt) Transazioni

Quando c'è una transazione tra i conti, come una spesa, un prelievo, un deposito o il pagamento con carta di credito (ad esempio, hai speso 320 yuan per un pasto), usa `Nuova Transazione` per creare una nuova transazione.
> - Seleziona `Data e Ora`: Data e ora della transazione.
> - Seleziona `Conto di Uscita`: Contanti
> - Seleziona `Conto di Ingresso`: Ristorante
> - Inserisci `Importo`: 320
> - Inserisci `Nota`: Riunione con amici
> - Clicca su `Crea`

## Esempi

### Trasferimento dello Stipendio in Banca

> Conto di Uscita `Entrate`: Stipendio
> Conto di Ingresso `Attività`: Banca

### Prelievo di Contanti dalla Banca

> Conto di Uscita `Attività`: Banca
> Conto di Ingresso `Attività`: Contanti

### Acquisto di un Telefono con Carta di Credito

> Conto di Uscita `Passività`: Carta di Credito
> Conto di Ingresso `Spese`: Elettronica

### Pagamento della Fattura della Carta di Credito con la Banca

> Conto di Uscita `Attività`: Banca
> Conto di Ingresso `Passività`: Carta di Credito

## ![Bilancio](icon:///scale-balance)![Grafico del Bilancio](icon:///chart-pie) Bilancio e Grafico

Attraverso una contabilità diligente, l'applicazione ti aiuterà a registrare tutti i dettagli delle transazioni e generare un bilancio in base alle condizioni di query. Questo foglio presenta chiaramente il saldo delle attività e delle passività in diversi periodi di tempo, consentendoti di comprendere meglio la tua situazione finanziaria. Inoltre, l'applicazione può generare vari grafici per rappresentare visivamente le tue entrate e le tue spese, rendendo più facile comprendere il tuo flusso finanziario.

## Valori Iniziali dei Conti

Quando usi per la prima volta l'applicazione, potresti già avere alcuni conti attuali con valori effettivi, come depositi bancari, contanti in mano o debiti di carta di credito. Per garantire che il bilancio fornisca risultati di calcolo più accurati, puoi utilizzare la funzione di inizializzazione dei conti per stabilire i valori iniziali corretti di questi conti. In questo modo, puoi far sì che il bilancio rifletta la vera situazione finanziaria.

## Suddivisione Uno-a-Molti

A volte, una singola spesa può coinvolgere diverse categorie di spese. Ad esempio, quando fai shopping in un supermercato, potresti acquistare cibo, beni di prima necessità e prodotti elettronici in una volta sola. Per affrontare questa situazione, l'applicazione fornisce una modifica avanzata della creazione delle transazioni, consentendo di allocare una singola spesa a più categorie di spese diverse. In altre parole, puoi allocare l'importo di una singola spesa con carta di credito a più categorie come cibo, beni di prima necessità e prodotti elettronici. Si prega di notare: nelle transazioni all'interno dello stesso libro contabile, poiché le unità di valuta sono uguali, l'importo totale trasferito fuori deve essere uguale all'importo totale trasferito dentro, altrimenti il programma respingerà la creazione della tua transazione.

## Trasferimento tra Libri Contabili

Il programma ti consente di trasferire tra conti in diversi libri contabili. Sia nella schermata di modifica o creazione della transazione di base che avanzata, puoi selezionare i conti da altri libri contabili quando selezioni i conti. Poiché i valori di valuta tra diversi libri contabili possono differire e il tasso di cambio non è fisso al momento, ad esempio trasferendo da Nuovi Dollari di Taiwan a Dollari USA, il programma non ti limiterà a creare una transazione in cui l'importo totale trasferito fuori deve essere uguale all'importo totale trasferito dentro. Si prega di creare transazioni basate sugli importi effettivi durante la creazione e fare attenzione.

## Visualizzazione Rapida del Bilancio e dei Grafici

Quando visualizzi il bilancio o i grafici, puoi aggiungere specifici elementi di conto alla visualizzazione rapida sulla schermata principale [*1]. Basta scorrere a destra sull'elemento nel bilancio e fare clic su `Aggiungi alla Visualizzazione Rapida`, o fare clic su "Aggiungi all'icona Visualizzazione Rapida" nell'angolo in alto a destra della scheda del grafico di bilancio. Successivamente, sulla schermata principale, vedrai il saldo delle attività e delle passività per quell'elemento, o puoi visualizzarlo sulla pagina del grafico della schermata principale. Inoltre, puoi ordinare o rimuovere questi elementi in `Preferenze > Impostazioni della Schermata Principale`.

[*1] Le visualizzazioni rapide eccessive sulla schermata principale possono influenzare il tempo di caricamento della stessa.
