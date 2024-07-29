
[`Guarda il video introduttivo su YouTube`](https://youtu.be/uN3GkA_Afuw)

## Concetti

I concetti principali di Daily Money sono molto semplici, ce ne sono solo tre:

> 1. Uno o molti `Libri Contabili`
> 2. Vari `Conti` all'interno dei Libri Contabili
> 3. Trasferire importi tra conti diversi e registrare queste `Transazioni`

## ![Libri Contabili](icon:///notebook-multiple) Libri Contabili

È necessario almeno un Libro Contabile, con conti che abbiano la stessa unità di valuta. Puoi anche creare più Libri Contabili con la stessa unità di valuta secondo le tue necessità.

## ![Conti](icon:///bookmark-multiple) Conti

Ci sono cinque diversi tipi di conti, che puoi aggiungere, modificare o eliminare nella schermata di gestione dei conti.

> - `Entrate`: Stipendio, ecc.
> - `Spese`: Cibo, intrattenimento, ecc.
> - `Attività`: Contanti, banca, ecc.
> - `Passività`: Carte di credito, prestiti, ecc.
> - `Altro`: ...

* I nomi dei conti possono utilizzare i punti (.) per separare (es. Cibo.Pranzo, Cibo.Cena), fornendo una migliore visualizzazione gerarchica quando si selezionano i conti o si visualizzano i bilanci.
* Puoi ordinare i conti per dare priorità ai conti utilizzati più frequentemente.

## ![Transazioni](icon:///receipt) Transazioni 

Quando c'è una transazione tra conti, come spese, prelievi, depositi o utilizzo di carte di credito (es. hai speso 320 yuan per un pasto), usa `Nuova Transazione` per creare una nuova transazione.
> - Seleziona `Data e Ora`: Data e ora della transazione.
> - Seleziona `Conto di Uscita`: Contanti
> - Seleziona `Conto di Entrata`: Pranzo
> - Inserisci `Importo`: 320
> - Inserisci `Nota`: Cena con amici
> - Clicca `Crea`

## Esempi

### Trasferimento Stipendio in Banca

> Conto di Uscita `Entrate`: Stipendio
> Conto di Entrata `Attività`: Banca

### Prelievo di Contanti dalla Banca

> Conto di Uscita `Attività`: Banca
> Conto di Entrata `Attività`: Contanti

### Acquisto di un Telefono con Carta di Credito

> Conto di Uscita `Passività`: Carta di Credito
> Conto di Entrata `Spese`: Elettronica

### Pagamento della Fattura della Carta di Credito con Banca

> Conto di Uscita `Attività`: Banca 
> Conto di Entrata `Passività`: Carta di Credito

## ![Bilancio](icon:///scale-balance)![Grafico Bilancio](icon:///chart-pie) Bilancio & Grafico

Attraverso una scrupolosa contabilità, l'applicazione ti aiuterà a registrare tutti i dettagli delle transazioni e genererà un bilancio secondo le condizioni di query. Questo bilancio presenta chiaramente il saldo di attività e passività in diversi periodi di tempo, permettendoti di comprendere meglio la tua situazione finanziaria. Inoltre, l'applicazione può generare vari grafici per rappresentare visivamente le tue entrate e spese, rendendo più facile comprendere il flusso delle tue finanze.

## Valori Iniziali dei Conti

Quando utilizzi per la prima volta l'applicazione, potresti già avere alcuni conti correnti con valori effettivi, come depositi bancari, contanti a disposizione o debiti con carta di credito. Per garantire che il bilancio fornisca risultati di calcolo più accurati, puoi utilizzare la funzione di inizializzazione dei conti per stabilire i corretti valori iniziali di questi conti. In questo modo, il bilancio rifletterà la reale situazione finanziaria.

## Divisione Uno-a-Molti

A volte, una singola spesa può coinvolgere più categorie di spesa. Ad esempio, quando fai acquisti in un supermercato, potresti acquistare cibo, articoli di uso quotidiano e prodotti elettronici contemporaneamente. Per affrontare questa situazione, l'applicazione fornisce un'avanzata creazione di transazioni, permettendo a una singola spesa di essere assegnata a più categorie di spesa diverse. In altre parole, puoi allocare l'importo di una singola spesa con carta di credito a più categorie come cibo, articoli di uso quotidiano e prodotti elettronici. Si prega di notare: Nelle transazioni all'interno dello stesso libro contabile, poiché le unità di valuta sono uguali, l'importo totale trasferito in uscita deve essere uguale all'importo totale trasferito in entrata, altrimenti il programma rifiuterà la creazione della transazione.

## Trasferimento tra Libri Contabili

Il programma consente di trasferire tra conti in diversi libri contabili. Sia nella schermata di creazione o modifica avanzata delle transazioni, puoi selezionare conti da altri libri contabili quando selezioni i conti. Poiché i valori di valuta tra diversi libri contabili possono differire, e il tasso di cambio non è fisso al momento, come il trasferimento da Nuovi Dollari Taiwanesi a Dollari Statunitensi, il programma non ti limiterà a creare una transazione in cui l'importo totale trasferito in uscita deve essere uguale all'importo totale trasferito in entrata. Si prega di creare transazioni basate sugli importi effettivi e fare attenzione.

## Visualizzazione Rapida del Bilancio e Grafici

Quando navighi nel bilancio o nei grafici, puoi aggiungere elementi di conto specifici alla visualizzazione rapida nella schermata iniziale [*1]. Basta scorrere verso destra sull'elemento nel bilancio e cliccare su `Aggiungi alla Visualizzazione Rapida`, oppure cliccare sull'icona "Aggiungi alla Visualizzazione Rapida" nell'angolo in alto a destra della scheda del grafico del bilancio. Successivamente, nella schermata iniziale, vedrai il saldo delle attività e passività per quell'elemento, oppure puoi visualizzarlo nella pagina dei grafici della schermata iniziale. Inoltre, puoi ordinare o rimuovere questi elementi in `Preferenze > Impostazioni Schermata Iniziale`.

[*1] Un'eccessiva visualizzazione rapida sulla schermata iniziale può influire sul tempo di caricamento della schermata iniziale.

## Modelli di Transazione e Programmazione Ricorrente

È possibile impostare modelli di transazione per le azioni contabili comuni, consentendo di aggiungere rapidamente le transazioni. È inoltre possibile impostare modelli di pianificazione ricorrente per azioni contabili ricorrenti. Il programma ti avviserà quando sarà il momento, consentendoti di aggiungere rapidamente la transazione e programmarla automaticamente per la prossima scadenza. Basta scorrere verso sinistra sull'elemento nell'elenco delle transazioni, quindi toccare `Crea Modello` e inserire l'orario di pianificazione, quindi crearlo. Inoltre, puoi ordinare, modificare o rimuovere questi elementi nella pagina `Gestione Modelli di Transazione`.
