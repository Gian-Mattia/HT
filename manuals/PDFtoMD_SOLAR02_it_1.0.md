# SOLAR02

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-13 -->
# 1 INTRODUZIONE

> **ATTENZIONE**
> L’unità remota è stata progettata per eseguire misure di irraggiamento [`W/m²`] e temperatura [`°C`] tramite apposite sonde ad essa collegate. Può inoltre essere utilizzata in abbinamento ad uno strumento

Per brevità, nel seguito del manuale, gli strumenti Master e gli accessori saranno indicati con l’acronimo indicato nella colonna “Sigla” della precedente Tabella.

*   Visualizzazione in tempo reale dei valori di irraggiamento e temperatura delle
*   Collegamento con piranometro tipo _Irr-P_ o cella di riferimento tipo _Irr-S2_
*
*   registrazione.
*
*   L’unità remota _SOLAR-02_ è uno strumento di misura e, come dispositivo, esso può anche intenzionalmente usare una radiofrequenza per il trasferimento dei dati. Per decisioni progettuali è stata adottata la banda di frequenza armonizzata di _2.4GHz_. Il suddetto dispositivo radio è in Classe _1_, in accordo
*   stabilito una potenza massima di trasmissione irradiata del segnale di uso in interno.

> **ATTENZIONE**

| DESCRIZIONE                         | SIGLA   | MODELLO HT                                                                      |
| :---------------------------------- | :------ | :------------------------------------------------------------------------------ |
| Piranometro                         | _Irr-P_   | HT303, HT 303N                                                                  |
| Sensore di Irraggiamento a 2 celle al silicio | _Irr-S2_  | HT304, HT304N                                                                   |
| Sensore di Temperatura              | _Tmp_     | PT300N                                                                          |
| Strumento Master - collegamento USB | _M-USB_   | SOLAR300, SOLAR300N                                                             |
| Strumento Master - collegamento USB | _M-RF_    | SOLAR I-V, SOLAR I-Vw, SOLAR I-Ve,I-V400,I-V400w,I-V500w, PVCHECK, PVCHECKs |

**TABELLA 1: ELENCO STRUMENTI MASTER E ACCESSORI**

Lo strumento è stato progettato in conformità ai requisiti essenziali della armonizzate relative agli strumenti di misura elettronici. Prima e durante

*   esplosivi, combustibili o in ambienti polverosi.
*
*   inutilizzati, circuiti, ecc.
*   strumento come, deformazioni, rotture, fuoriuscite di sostanze, assenza di visualizzazione sul display, ecc.
*   problemi mentre viene tenuto in mano. I livelli di potenza _2.4GHz_ con dispositivo in trasmissione tra le mani rientrano abbondantemente nei limiti di base per potrebbe causare danni allo strumento o ai suoi componenti

## 2 PRECAUZIONI E MISURE DI SICUREZZA

> **ATTENZIONE**
>
> **ATTENZIONE**

*   Questo strumento è stato progettato per l’utilizzo in condizioni ambientali
*   La invitiamo a seguire le normali regole di sicurezza orientate alla protezione utilizzo errato.
*
*   Solo gli accessori forniti a corredo dello strumento garantiscono gli se necessario, con modelli identici.
*   dello strumento.
*   Controllare che le batterie siano inserite correttamente

### 2.1 ISTRUZIONI PRELIMINARI

> **ATTENZIONE**

### 2.2 DURANTE L'UTILIZZO

La preghiamo di leggere attentamente le raccomandazioni e le istruzioni

> **ATTENZIONE**
>
> *   La mancata osservazione delle avvertenze e/o istruzioni può danneggiare lo strumento e/o i suoi componenti o essere fonte di pericolo per l’operatore
> *   Il simbolo «`[simbolo]`» indica la condizione di batterie esaurite. Interrompere le prove e procedere alla sostituzione delle batterie in accordo a quanto
> *   Quando lo strumento è connesso al circuito in esame non toccare mai alcun terminale, anche se inutilizzato

### 2.3 DOPO L'UTILIZZO

Quando le misure sono terminate, spegnere lo strumento mantenendo strumento per un lungo periodo rimuovere le batterie ed attenersi a quanto

## 3 PREPARAZIONE ALL'UTILIZZO

### 3.1 CONTROLLI INIZIALI

Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili comunque, di controllarlo sommariamente per accertare eventuali danni subiti durante il trasporto. Se si dovessero riscontrare anomalie contattare immediatamente lo spedizioniere. Si consiglia inoltre di controllare che contattare il rivenditore. Qualora fosse necessario restituire lo strumento,

### 3.2 ALIMENTAZIONE DELL' UNITÀ REMOTA _SOLAR-02_

ALIMENTAZIONE DELLO STRUMENTO

### 3.3 CONSERVAZIONE

Per garantire misure precise, dopo un lungo periodo di conservazione,

# 4 DESCRIZIONE

## 4.1 DESCRIZIONE DEI COMANDI

**TASTO `MODE`**
cella solare di riferimento in uso all’interno della programmazione e di passare dalla visualizzazione
Il tasto `MODE` è usato all’interno della programmazione dell’unità per l’impostazione dei valori dei parametri.

## 4.2 DESCRIZIONE DEI TASTI FUNZIONE

## 4.3 CONDIZIONI ALL' ACCENSIONE

1.  Dopo la videata iniziale con la visualizzazione di tutti i simboli del display, è mostrata dall’unità per alcuni istanti collegata. Da questo momento è possibile utilizzare l’unità

Display elements (likely from an image):
1.  Display LCD
2.  `/ESC`
3.
4.
5.
6.
7.
8.

# 5 UTILIZZO DELL'UNITÀ

## 5.1 INTRODUZIONE

1.  master per la misura in tempo reale dei valori di irraggiamento, temperatura
    *   `PYRA/CELL` Sonda piranometro a termopila tipo _Irr-P_ Doppia cella di riferimento al silicio tipo
    *   ingresso `TEMP` Sonda di temperatura tipo _Tmp_
2.  master per la misura e il salvataggio dei valori di irraggiamento e temperatura delle celle e ambiente. Il tipo di collegamento con gli strumenti master è il
    *   _M-USB_
    *   _M-RF_
    *
    *   dei moduli `G p 800`

> **ATTENZIONE**
> _K_ misurato tramite la sonda di temperatura bensì quello calcolato. In ogni eseguire una corretta impostazione preliminare dei valori di sensibilità delle sonde collegate nell’ingresso `PYRA/CELL` dell’unità. I valori impostati saranno letti e considerati dagli strumenti master in fase di collaudo/registrazione e saranno

## 5.2 PROGRAMMAZIONE DELL’UNITÀ _SOLAR-02_

L’unità _SOLAR-02_ permette l’impostazione dei parametri di max 3 sensori di
*   in `mV/kW*m` oppure in `μV/W*m` e il parametro `Alpha` espresso in `%`/`°C`
*   _Irr-P_ in `mV/kW*m` oppure in `μV/W*m`. Il parametro `Alpha` espresso in `%`/`°C` viene ignorato.

1.  `SET` mentre si accende lo strumento con il tasto `/ESC`
2.  `e`
3.  Premere il tasto `SET` Per confermare il valore.
4.  In caso di sensore tipo _Irr-P_ premere il tasto `ESC` per uscire dalla modalità di programmazione.
5.  `e` per impostare il valore di `Te`
6.  Premere il tasto `SET` per confermare il valore e passare all’impostazione del sensore 2

    _Per impostazione del sensore 2:_
    1.  `e`
    2.  Premere il tasto `SET` Per confermare il valore
    3.  `e` per impostare il valore di `Te`
    4.  Premere il tasto `SET` per confermare il valore

    _In caso di sensore tipo _Irr-S2_:_
    1.  Premere il tasto `ESC` per uscire dalla modalità
    2.  `e`
    3.  Premere il tasto `SET` Per confermare il valore.
    4.  `e` per impostare il valore di `Te`
    5.  Premere il tasto `SET` per confermare il valore ed uscire dalla modalità di programmazione salvando le impostazioni eseguite

1.  Accendere lo strumento premendo il tasto `/ESC`
2.  Premere il tasto `SET`
3.  `e` per selezionare il tipo di sensore desiderato
4.  Confermare la scelta con il tasto `SET` per tornare alla modalità di misura
5.  all’ingresso `PYRA/CELL` dell’unità _SOLAR-02_
6.  all’ingresso `TEMP` dell’unità _SOLAR-02_
7.  *   Irraggiamento nel display principale espresso in `W/m²`
    *   `°C`
    *   `°C`

## 5.4 USO DELLA FUNZIONE INCLINOMETRO

1.  Accendere l’unità con il tasto `/ESC`. La seguente videata è mostrata a display
2.  Premere il tasto `FUNC/` per attivare la modalità di inclinometro dell’unità
3.  calamite presenti nella parte posteriore
4.  Attendere qualche secondo
5.  rispetto al piano orizzontale dell’oggetto in prova
    le funzionalità, l’attivazione di un collaudo/registrazione sullo strumento master si veda il manuale d’uso dello strumento master stesso.

## 5.5 ABILITAZIONE/DISABILITAZIONE COMUNICAZIONE RF

Disabilitare la comunicazione RF tenendo premuto il tasto `FUNC/` mentre si accende lo strumento con il tasto `/ESC`. Il messaggio `rF OFF` `rF ON` spegnere lo strumento e ripetere l’operazione. Successivamente lo strumento mantenuta anche in caso di sostituzione delle batterie.

Abilitare la comunicazione RF tenendo premuto il tasto `FUNC/` mentre si accende lo strumento con il tasto `/ESC`. Successivamente lo strumento presenta la normale videata iniziale. sostituzione delle batterie

### 5.5.1 CONTROLLI PRELIMINARI

## 5.6 USO DELLO STRUMENTO

### 5.6.1 CONTROLLI PRELIMINARI

1.  Accendere lo strumento e successivamente premere il tasto `SET`. L’unità
2.  `e` per selezionare il tipo di sensore desiderato
3.  Confermare la scelta con il tasto `SET`
4.  strumento master
5.  Attivando un collaudo/registrazione sullo strumento master, l’unità _SOLAR-02_ si pone in attesa della sincronizzazione mostrando il `HoLd` attendere prima di poter avviare le procedure di collaudo
6.  `Recording` di irraggiamento e temperatura
7.  Posizionare la sonda per misura di irraggiamento tipo _Irr-P_ o _Irr-S2_
8.  terminale di uscita all’ingresso `TEMP` dell’unità _SOLAR-02_
9.  Al raggiungimento di un valore di irraggiamento superiore alla soglia
10. Scollegare le sonde di irraggiamento e temperatura, ricollegare l’unità
11. Al riconoscimento del comando di terminazione del collaudo/ registrazione da parte dello strumento master, l’unità cessa le operazioni, le funzionalità, l’attivazione di un collaudo/registrazione sullo strumento master si veda il manuale d’uso dello strumento master stesso

### 5.6 USO DELLO STRUMENTO (Continuazione)

1.  Accendere lo strumento e avvicinare l’unità _SOLAR-02_ allo strumento
    *
    *   entro circa `30s`
    *   circa `30s`. Per riavviare una nuova ricerca di unità master _M-RF_ è .
2.  Premere il tasto `SET` il sensore 1
3.  `e` per selezionare il tipo di sensore desiderato
4.  Confermare la scelta con il tasto `SET` per tornare alla modalità di misura
5.  sullo strumento master, l’unità _SOLAR-02_ si pone in attesa della `HoLd` del tempo per cui è necessario mantenre l’unità _SOLAR-02_ in prossimità
6.  `Recording…` le sonde di irraggiamento e temperatura
7.
8.  terminale di uscita all’ingresso `TEMP` dell’unità _SOLAR-02_
9.  Al raggiungimento di un valore di irraggiamento superiore alla soglia `READY`
10. Scollegare le sonde di irraggiamento e temperatura e riportare l’unità in prossimità dello strumento master in modo da attivare la connessione
11. *   Se il simbolo "`[simbolo]`" lampeggia a display, attendere per il riconoscimento reciproco delle due unità, al termine del quale il suddetto simbolo resta
    *   Se il simbolo "`[simbolo]`" è assente. Premere il tasto `[tasto non identificato]` per avviare una nuova
12. Al riconoscimento del comando di terminazione del collaudo/registrazione da parte dello strumento master, l’unità cessa le operazioni, presenta a `SEnd`

# 6 MANUTENZIONE

## 6.1 GENERALITÀ

1.  Per evitare possibili danni o pericoli durante l’utilizzo o l’immagazzinamento dell’accessorio rispettare le raccomandazioni elencate in questo manuale
2.
3.  Se si prevede di non utilizzare l’accessorio per lungo tempo rimuovere le batterie per evitare fuoruscite di liquidi che possano danneggiare i circuiti interni

## 6.2 SOSTITUZIONE BATTERIE

1.  Spegnere l’unità remota _SOLAR-02_
2.
3.  Aprire il coperchio del vano batteria nella parte posteriore dell’accessorio
4.  Rimuovere le batterie esaurite sostituendole con altrettante dello stesso
5.  Riposizionare il coperchio del vano batterie.
6.  contenitori per lo smaltimento

Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie.

## 6.3 PULIZIA

mai panni umidi, solventi, acqua, ecc.

## 6.4 FINE VITA

> **ATTENZIONE**
> l'apparecchiatura e le batterie devono essere raccolte separatamente e trattata in modo corretto.

# 7 SPECIFICHE TECNICHE

## 7.1 CARATTERISTICHE TECNICHE

*   Rapporto di taratura ISO

| Range [`W/m²`] | (100 * 0.1/K) | Incertezza |
| :------------- | :------------ | :--------- |
| 0 ÷ 1400       | 1 + INT       | ± [1.0%lettura + INT(1000 * 0.1/K) dgt] |

| Sensibilità Sonda | Range      | Risoluzione | Incertezza           |
| :---------------- | :--------- | :---------- | :------------------- |
| `mV/kW*m`         |            | `m`         |                      |
| K<10              | 15.00÷0.00 | 0.01        | ± (1.0%lettura+0.1mV) |
|                   | 65.00÷0.00 | 0.02        |                      |

**INGRESSO `TEMP` TRAMITE SONDA “_TMP_”**

## 7.2 CARATTERISTICHE GENERALI

*   Display: `4 LCD` (2000 punti), segno e punto decimale
*   Alimentazione Batterie: `4x1.5V` alcaline tipo `AAA IEC LR03`
*   Durata batterie: circa `480` ore
*   Auto Power OFF: dopo `5` minuti di non utilizzo (non in reg.)

**Caratteristiche modulo radio**
*   Campo di frequenza: `2.400 ÷ 2.4835GHz`
*   Categoria `R&TTE`: Classe `1`
*   Potenza max di trasmissione: `30 ÷ W`

**Connettori di ingresso**
*   Porta USB: `USB 2.0`
*   Ingressi `PYRA/CELL` e `TEMP`: tipo `Hypertac`

**Memoria interna**
*   Autonomia: circa `1.5` ore (`@ PI` strumento master `= 5s`)

**Caratteristiche meccaniche**
*   Dimensioni (`L` x `La` x `H`) `120x 65 x 35mm`
*   Peso (batterie incluse) `215g`

## 7.3 CONDIZIONI AMBIENTALI DI UTILIZZO

*   Temperatura di riferimento: `23°C ± 5°C`
*   Temperatura di utilizzo: `0°C ± 40°C`
*   Umidità relativa di utilizzo: `<80%RH`
*   Temperatura di conservazione: `-10°C ÷ 60°C`
*   Umidità di conservazione: `<80%RH`

## 7.4 ACCESSORI IN DOTAZIONE

HT dichiara (vedere Declaration of Conformity) che lo strumento è conforme ai requisiti

| Range      | Risoluzione | Incertezza            |
| :--------- | :---------- | :-------------------- |
| -20.0 ÷ 99.9 | 0.1         | ± (1.0%lettura + 1°C) |

| Range | Risoluzione | Incertezza            |
| :---- | :---------- | :-------------------- |
| 0 ÷ 90 | 1           | ± (1.0%lettura + 1°) |

# 8 ASSISTENZA

## 8.1 CONDIZIONI DI GARANZIA

Questo strumento è garantito contro ogni difetto di materiale e fabbricazione, in conformità con le condizioni generali di vendita. Durante il periodo di garanzia, le parti difettose possono essere sostituite, ma il costruttore si riserva il diritto di riparare ovvero sostituire il prodotto. Qualora lo strumento debba essere restituito al servizio post - vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballo originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente.Il costruttore declina ogni responsabilità per danni causati a persone o oggetti.

*   Riparazioni che si rendono necessarie a causa di un errato utilizzo dello strumento o del suo utilizzo con apparecchiature non compatibili.
*   Riparazioni che si rendono necessarie a causa di un imballaggio non adeguato.
*   Riparazioni che si rendono necessarie a causa di interventi eseguiti da personale non autorizzato.
*   costruttore.
*   d’uso.

I nostri prodotti sono brevettati e i marchi depositati. Il costruttore si dovuto a miglioramenti tecnologici.

## 8.2 ASSISTENZA

Se lo strumento non funziona correttamente, prima di contattare il Servizio di Assistenza, controllare lo stato della batteria e degli accessori e sostituirli se necessario. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post - vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballaggio originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente.