[`Guarda il video introduttivo su YouTube`](https://youtu.be/uN3GkA_Afuw)
[`Documento online`](https://colaorange.gitbook.io/daily-money-one-doc/eng)

## Concetti

I concetti principali di Daily Money sono molto semplici, sono solo tre:

> 1. Uno o più `Libri`
> 2. Vari `Conti` all'interno dei libri
> 3. Trasferire importi tra conti diversi e registrare questi `Movimenti`

## ![Books](icon:///notebook-multiple) Libri

È richiesto almeno un Libro, con conti che usano la stessa unità di valuta. Puoi anche creare più Libri con la stessa unità di valuta in base alle tue esigenze.

## ![Accounts](icon:///bookmark-multiple) Conti

Esistono cinque diversi tipi di conto, che puoi aggiungere, modificare o eliminare nella schermata di gestione conti.

> - `Entrata`: stipendio, ecc.
> - `Spesa`: cibo, intrattenimento, ecc.
> - `Attivo`: contanti, banca, ecc.
> - `Passività`: carte di credito, prestiti, ecc.
> - `Altro`: ...

* I nomi dei conti possono usare punti (.) per separare i livelli (es. Cibo.Ristorante, Cibo.Riunione), offrendo una visualizzazione gerarchica migliore quando selezioni conti o visualizzi stati patrimoniali.
* Puoi ordinare i conti per dare priorità a quelli usati più spesso.

## ![Transactions](icon:///receipt) Movimenti 

Quando c'è un movimento tra conti, per esempio una spesa, uno spostamento di denaro tra conti o un pagamento con carta di credito (es. hai speso 320 yuan per un pasto), usa `Nuovo movimento` per creare un nuovo movimento.
> - Seleziona `Data e ora`: data e ora del movimento.
> - Seleziona `Origine`: contanti
> - Seleziona `Destinazione`: ristorante
> - Inserisci `Importo`: 320
> - Inserisci `Nota`: incontro con amici
> - Tocca `Crea`

## Esempi

### Trasferimento dello stipendio in banca

> Conto `Entrata` di origine: stipendio
> Conto `Attivo` di destinazione: banca

### Prelevare contanti dalla banca

> Conto `Attivo` di origine: banca
> Conto `Attivo` di destinazione: contanti

### Acquistare un telefono con carta di credito

> Conto `Passività` di origine: carta di credito
> Conto `Spesa` di destinazione: elettronica

### Pagare la carta di credito con la banca

> Conto `Attivo` di origine: banca 
> Conto `Passività` di destinazione: carta di credito

## ![Balance Sheet](icon:///scale-balance)![Balance Chart](icon:///chart-pie) Stato patrimoniale e grafico

Con una contabilità diligente, l'applicazione ti aiuterà a registrare tutti i dettagli dei movimenti e a generare uno stato patrimoniale in base alle condizioni di ricerca. Questo prospetto presenta chiaramente il saldo di attivi e passività in periodi diversi, permettendoti di comprendere meglio la tua situazione finanziaria. Inoltre, l'applicazione può generare vari grafici per rappresentare visivamente entrate e spese, rendendo più semplice capire il flusso finanziario.

## Saldi iniziali dei conti

Quando usi l'applicazione per la prima volta, potresti avere già alcuni conti correnti con valori reali, come depositi bancari, contanti disponibili o debiti su carta di credito. Per assicurare che lo stato patrimoniale fornisca risultati di calcolo più accurati, puoi usare la funzione di inizializzazione dei conti per stabilire i saldi iniziali corretti di questi conti. In questo modo, lo stato patrimoniale può riflettere la reale situazione finanziaria.

## Suddivisione uno-a-molti (avanzata)

A volte una singola spesa può coinvolgere più categorie di spesa. Per esempio, facendo acquisti al supermercato, puoi acquistare insieme alimenti, beni di uso quotidiano e prodotti elettronici. Per gestire questa situazione, l'applicazione offre la creazione e modifica avanzata dei movimenti, permettendo di assegnare una singola spesa a più categorie diverse. In altre parole, puoi assegnare l'importo di una singola spesa con carta di credito a più categorie come cibo, beni quotidiani e prodotti elettronici. Nota: nei movimenti all'interno dello stesso libro, poiche le unità di valuta sono uguali, l'importo totale in uscita deve essere uguale all'importo totale in entrata, altrimenti il programma rifiuterà la creazione del movimento.

## Trasferimento tra libri

Il programma consente trasferimenti tra conti in libri diversi. Nelle schermate di modifica o creazione movimento, sia base sia avanzata, puoi selezionare conti da altri libri quando scegli i conti. Poiché i valori valutari tra libri diversi possono differire e il tasso di cambio non è fisso al momento, per esempio trasferendo da nuovi dollari taiwanesi a dollari statunitensi, il programma non ti limita a creare un movimento in cui l'importo totale in uscita deve essere uguale all'importo totale in entrata. Crea i movimenti in base agli importi reali e fai attenzione.

## Vista rapida di stato patrimoniale e grafici

Quando navighi nello stato patrimoniale o nei grafici, puoi aggiungere specifici elementi conto alla Vista rapida nella schermata Home [*1]. Basta scorrere a destra sull'elemento nello stato patrimoniale e toccare `Aggiungi a Vista rapida`, oppure toccare l'icona "Aggiungi a Vista rapida" nell'angolo in alto a destra della scheda del grafico saldo. Poi, nella schermata Home, vedrai il saldo di attivi e passività per quell'elemento, oppure potrai visualizzarlo nella pagina grafici della schermata Home. Inoltre, puoi ordinare o rimuovere questi elementi in `Preferenze > Schermata Home`.

[*1] Un numero eccessivo di elementi Vista rapida nella schermata Home può influire sul tempo di caricamento della schermata Home.

## Modelli e pianificazioni ricorrenti

Puoi impostare modelli di movimento per le azioni contabili comuni, così da aggiungere rapidamente un movimento. Puoi anche impostare modelli di pianificazione ricorrente per azioni contabili che si ripetono regolarmente. Il programma ti avvisera alla scadenza, permettendoti di aggiungere rapidamente il movimento e pianificarlo automaticamente per la prossima scadenza. Basta scorrere a sinistra sull'elemento nell'elenco movimenti, toccare `Nuovo modello`, inserire l'orario di pianificazione e crearlo. Inoltre, puoi ordinare, modificare o rimuovere questi elementi nella pagina `Modelli`.

## Impostazioni budget

Quando navighi nello stato patrimoniale, basta scorrere a destra su un elemento conto, quindi toccare `Crea budget` e selezionare la modalità. Una volta creato, puoi visualizzare l'avanzamento del budget nello stato patrimoniale o nella Vista rapida della schermata Home. Inoltre, puoi ordinare, modificare o rimuovere questi elementi nella pagina `Budget`.
