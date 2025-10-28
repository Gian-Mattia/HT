# HT9025

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-22 -->
- - -
1. PRECAUZIONI E MISURE DI SICUREZZA
    1.1. Durante l’utilizzo
    1.2. Dopo l’utilizzo
    1.3. Definizione di Categoria di misura
2. DESCRIZIONE GENERALE
    2.1. Strumenti a Valore medio/Valore Efficace
    2.2. Valore Efficace e fattore di cresta
3. PREPARAZIONE ALL’UTILIZZO
    3.1. Controlli iniziali
    3.2. Alimentazione dello strumento
    3.3 Conservazione
4. NOMENCLATURA
    4.1. Descrizione dello strumento
    4.2. Descrizione tasti funzione
    4.3. Descrizione funzioni interne
5. ISTRUZIONI OPERATIVE
    5.1. Misura Tensione AC, AC+DC, VFD
    5.2. Misura Tensione LoZAC, LoZAC+DC
    5.3. Misura Tensione DC
    5.4. Misura Frequenza e Duty Cycle
    5.5. Misura Resistenza e Test Continuità
    5.6. Prova Diodi
    5.7. Misura Capacità
    5.8. Misura Temperatura con sonda K
    5.9. Misura Corrente DC
    5.10. Misura Corrente AC
    5.11. Misura Corrente di Spunto AC (INRUSH)
    5.12. Misura Corrente DC, AC, AC+DC con pinza
    5.13. Funzione Data Logger
    5.14. Uso della termocamera interna (`HT9025T`)
    5.15. Download APP HTMercury
6. MANUTENZIONE
    6.1. Generalità
    6.2. Ricarica batteria interna
    6.3. Pulizia dello strumento
7. SPECIFICHE TECNICHE
    7.1. Caratteristiche tecniche
    7.2. Caratteristiche generali
    7.3. Accessori
        7.3.1. Accessori in dotazione
        7.3.2. Accessori opzionali
8. ASSISTENZA
    8.1. Condizioni di garanzia
    8.2. Assistenza
9. FIGURE INTERNE

---

# 1. PRECAUZIONI E MISURE DI SICUREZZA

Lo strumento è stato progettato in conformità alla direttiva IEC/EN61010-1, relativa agli strumenti di misura elettronici. Per la Sua sicurezza e per evitare di danneggiare lo strumento, La preghiamo di seguire le procedure descritte nel presente manuale e di leggere con particolare attenzione tutte le note precedute dal simbolo **ATTENZIONE**. Prima e durante l’esecuzione delle misure attenersi scrupolosamente alle seguenti indicazioni:

**ATTENZIONE**
* Non effettuare misure in presenza di gas o materiali esplosivi, combustibili o in ambienti umidi o polverosi
* Non effettuare alcuna misura qualora si riscontrino anomalie nello strumento come, deformazioni, rotture, fuoriuscite di sostanze, assenza di visualizzazione sul display, ecc..
* Evitare contatti con il circuito in esame se non si stanno effettuando misure
* Evitare contatti con parti metalliche esposte, con terminali di misura inutilizzati, circuiti, ecc..
* Prestare particolare attenzione quando si effettuano misure di tensioni superiori a 20V in quanto è presente il rischio di shock elettrici
* Mantenere lo strumento stabile durante ogni operazione di misura
* Questo strumento è stato progettato per un utilizzo in un ambiente con livello di inquinamento 2
* Può essere utilizzato per misure di TENSIONE e CORRENTE su installazioni in CAT IV 600V and CAT III 1000V
* Non effettuare misure che superino i limiti di temperatura di lavoro e di conservazione specificati
* Solo gli accessori forniti a corredo dello strumento garantiscono gli standard di sicurezza. Essi devono essere utilizzati solo se in buone condizioni e sostituiti, se necessario, con modelli identici
* Controllare che la batteria sia inserita correttamente
* Controllare che il display LCD dia indicazioni coerenti con la funzione selezionata
* Non puntare lo strumento verso sorgenti ad elevata intensità di radiazione (ex: sole) al fine di evitare il danneggiamento del sensore IR
* Evitare urti o forti vibrazioni sullo strumento al fine di evitarne il danneggiamento
* Nel passaggio dello strumento da una condizione ambientale fredda ad una molto calda lasciarlo acceso per un tempo sufficiente all’evaporazione degli effetti di condensazione

I seguenti simboli sono usati sullo strumento:

* **ATTENZIONE**: attenersi alle istruzioni riportate nel manuale d’uso. Un uso improprio potrebbe causare danni allo strumento o ai suoi componenti
* **Pericolo Alta Tensione**: rischi di shock elettrici
* Lo strumento può operare su conduttori nudi sotto tensione
* Doppio isolamento
* Tensione o Corrente DC
* Tensione o Corrente AC
* Riferimento di Terra
* Questo simbolo presente sullo strumento (`HT9025T`) indica che lo stesso è in grado di emettere un puntatore Laser in Classe 2. Non puntare la radiazione verso gli occhi al fine di prevenire danni fisici alle persone
* Il simbolo indica che l'apparecchiatura ed i suoi accessori devono essere raccolti separatamente e trattati in modo corretto

## 1.1. DURANTE L’UTILIZZO

La preghiamo di leggere attentamente le raccomandazioni e le istruzioni seguenti:
* Prima di azionare il commutatore, rimuovere dal toroide il conduttore o scollegare i puntali di misura dal circuito in esame
* Quando lo strumento è connesso al circuito in esame non toccare mai qualunque terminale inutilizzato
* Evitare la misura di resistenza in presenza di tensioni esterne. Anche se lo strumento è protetto, una tensione eccessiva potrebbe causare malfunzionamenti della pinza
* Prima di effettuare una misura di corrente tramite il toroide, rimuovere dalle rispettive boccole i puntali
* Durante la misura di corrente, ogni altra corrente localizzata in prossimità della pinza può influenzare la precisione della misura
* Durante la misura di corrente posizionare sempre il conduttore il più possibile al centro del toroide in modo da ottenere una lettura più accurata
* Se, durante una misura, il valore o il segno della grandezza in esame rimangono costanti controllare se è attivata la funzione `HOLD`

**ATTENZIONE**
La mancata osservazione delle Avvertenze può danneggiare lo strumento e/o i suoi componenti e costituire fonte di pericolo per l’operatore.

## 1.2. DOPO L’UTILIZZO

* Quando le misure sono terminate, posizionare il commutatore su `OFF`
* Se si prevede di non utilizzare lo strumento per un lungo periodo rimuovere la batteria

## 1.3. DEFINIZIONE DI CATEGORIA DI MISURA

La norma IEC/EN 61010-1: Prescrizioni di sicurezza per apparecchi elettrici di misura, controllo e per utilizzo in laboratorio, Parte 1: Prescrizioni generali, definisce cosa si intenda per categoria di misura. Al § 6.7.4: Circuiti di misura, essa recita: (OMISSIS)

I circuiti sono suddivisi nelle seguenti categorie di misura:
* La **Categoria di misura IV** serve per le misure effettuate su una sorgente di un’installazione a bassa tensione.
    Esempi sono costituiti da contatori elettrici e da misure sui dispositivi primari di protezione dalle sovracorrenti e sulle unità di regolazione dell’ondulazione.
* La **Categoria di misura III** serve per le misure effettuate in installazioni all’interno di edifici.
    Esempi sono costituiti da misure su pannelli di distribuzione, disgiuntori, cablaggi, compresi i cavi, le barre, le scatole di giunzione, gli interruttori, le prese di installazioni fisse e gli apparecchi destinati all’impiego industriale e altre apparecchiature, per esempio i motori fissi con collegamento ad impianto fisso.
* La **Categoria di misura II** serve per le misure effettuate su circuiti collegati direttamente all’installazione a bassa tensione.
    Esempi sono costituiti da misure su apparecchiature per uso domestico e similari.
* La **Categoria di misura I** serve per le misure effettuate su circuiti non collegati direttamente alla RETE DI DISTRIBUZIONE.
    Esempi sono costituiti da misure su non derivati dalla RETE e derivati dalla RETE ma con protezione particolare (interna). In quest’ultimo caso le sollecitazioni da transitori sono variabili, per questo motivo (OMISSIS) si richiede che l’utente conosca la capacità di tenuta ai transitori dell’apparecchiatura

# 2. DESCRIZIONE GENERALE

Lo strumento esegue le seguenti misure:

**Funzione Multimetro**
* Tensione DC fino a 1500V
* Tensione AC, AC+DC T RMS
* Tensione DC, AC, AC+DC TRMS con bassa impedenza (LoZ)
* Tensione e corrente AC TRMS su dispositivi VFD (misure a valle di inverter)
* Corrente DC / AC TRMS con toroide integrato
* Corrente DC, AC, AC+DC TRMS con trasduttore a pinza esterno
* Corrente di spunto AC TRMS (INRUSH)
* Resistenza e Test continuità
* Prova diodi
* Capacità
* Frequenza
* Duty Cycle
* Temperatura con sonda K
* Funzione Data Logger e visualizzazione grafici delle misure
* Salvataggio immagini BMP su memoria interna

**Funzione Termocamera (`HT9025T`)**
* Misura di temperatura all’infrarosso con campo da –20°C a 260°C
* 3 cursori di misura (centrale fisso + punto caldo + punto freddo)
* Emissività dei materiali selezionabile tra 0.01 e 1.00
* Frequenza immagine: 50Hz
* 5 tavolozze colori selezionabili
* Rilevazione automatica punti caldo/freddo dell’immagine
* Salvataggio immagini BMP su memoria interna
* Risoluzione sensore IR: 120 x 120 pxl
* Puntatore laser e illuminatore incorporato

Ciascuna di queste funzioni può essere selezionata tramite un apposito selettore. Sono inoltre presenti tasti funzione (vedere il § 4.3), bargraph analogico e display a colori LCD TFT ad alto contrasto. Lo strumento è inoltre dotato della funzione di Auto Power OFF che provvede a spegnere automaticamente lo strumento dopo un periodo di tempo (programmabile) di inutilizzo.

## 2.1. STRUMENTI A VALORE MEDIO / VALORE EFFICACE

Gli strumenti di misura di grandezze alternate si dividono in due grandi famiglie:
* **Strumenti a VALORE MEDIO**: strumenti che misurano il valore della sola onda alla frequenza fondamentale (50 o 60 HZ)
* **Strumenti a VERO VALORE EFFICACE** anche detti TRMS (True Root Mean Square value): strumenti che misurano il vero valore efficace della grandezza in esame.
* In presenza di un’onda perfettamente sinusoidale le due famiglie di strumenti forniscono risultati identici. In presenza di onde distorte invece le letture differiscono. Gli strumenti a valore medio forniscono il valore efficace della sola onda fondamentale, gli strumenti a vero valore efficace forniscono invece il valore efficace dell’intera onda, armoniche comprese (entro la banda passante dello strumento). Pertanto, misurando la medesima grandezza con strumenti di entrambe le famiglie, i valori ottenuti sono identici solo se l’onda è puramente sinusoidale, qualora invece essa fosse distorta, gli strumenti a vero valore efficace forniscono valori maggiori rispetto alle letture di strumenti a valore medio

## 2.2. VALORE EFFICACE E FATTORE DI CRESTA

Il valore efficace per la corrente è così definito: "In un tempo pari ad un periodo, una corrente alternata con valore efficace della intensità di 1A, circolando su di un resistore, dissipa la stessa energia che sarebbe dissipata, nello stesso tempo, da una corrente continua con intensità di 1A". Da questa definizione discende l’espressione numerica:

`G=  + T t t dt t g T 0 0 ) ( 1 2`

Il valore efficace viene indicato come RMS (`Root Mean Square value`)

Il Fattore di Cresta è definito come il rapporto fra il Valore di Picco di un segnale ed il suo Valore Efficace:

`CF (G)= RMS p G G`

Questo valore varia con la forma d'onda del segnale, per un’onda puramente sinusoidale esso vale `2 =1.41`. In presenza di distorsioni il Fattore di Cresta assume valori tanto maggiori quanto più è elevata la distorsione dell’onda.

# 3. PREPARAZIONE ALL’UTILIZZO

## 3.1. CONTROLLI INIZIALI

Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili affinché lo strumento potesse essere consegnato senza danni. Tuttavia, si consiglia, comunque, di controllare sommariamente lo strumento per accertare eventuali danni subiti durante il trasporto. Se si dovessero riscontrare anomalie contattare immediatamente lo spedizioniere. Si consiglia inoltre di controllare che l’imballaggio contenga tutte le parti indicate al § 7.3.1. In caso di discrepanze contattare il rivenditore. Qualora fosse necessario restituire lo strumento, si prega di seguire le istruzioni riportate al § 8.

## 3.2. ALIMENTAZIONE DELLO STRUMENTO

Lo strumento è alimentato con `1 x 7.4 V` batteria ricaricabile Li-ION inclusa nella confezione. Quando la batteria è scarica il simbolo “ ” è mostrato a display. Per la ricarica della batteria vedere il § 6.2.

## 3.3 CONSERVAZIONE

Per garantire misure precise, dopo un lungo periodo di conservazione, attendere che lo strumento ritorni alle condizioni normali (vedere il § 7.2).

# 4. NOMENCLATURA

## 4.1. DESCRIZIONE DELLO STRUMENTO

Fig. 1 Descrizione parte anteriore dello strumento

1. Toroide apribile
2. Polarità positiva corrente DC
3. Sensore NCV
4. Leva apertura toroide
5. Display LCD
6. Tasto `MODE/VFD`
7. Tasto `HOLD/REL`
8. Tasto `/INRUSH`
9. Tasto `RANGE`
10. Tasto `IR/` (`HT9025T`) / Tasto (`HT9025`)
11. Selettore funzioni
12. Ingresso `COM`
13. Ingresso `V Hz% CAP Ω`

Fig. 2 Descrizione parte posteriore dello strumento

1. Polarità negativa corrente DC
2. Illuminatore a LED bianco
3. Puntatore laser (`HT9025T`)
4. Lente termocamera (`HT9025T`)
5. Selettore protezione lente (`HT9025T`)
6. Vite di fissaggio vano batteria
7. Coperchio vano batteria

Fig. 3 Tacche di allineamento

1. Tacche di allineamento
2. Conduttore

## 4.2. DESCRIZIONE TASTI FUNZIONE

### Tasto `HOLD / REL`

La pressione del tasto `HOLD /REL` attiva il mantenimento del valore della grandezza visualizzata a display. Conseguentemente alla pressione di tale tasto il messaggio “`HOLD`” appare a display. Premere nuovamente il tasto `HOLD / REL` per uscire dalla funzione. Per il salvataggio del valore a display vedere il § 4.3. Il tasto `HOLD/REL` permette anche di uscire dal menu di programmazione tornando alla videata principale di misura dello strumento. Premere il tasto `HOLD/REL` per oltre 1 secondo per attivare/disattivare la misura relativa sulla funzione selezionata (vedere § 4.3) e per riaccendere lo strumento dopo un’autospegnimento.

### Tasto `RANGE`

Premere il tasto `RANGE` per attivare il modo manuale disabilitando la funzione Autorange. Il simbolo “`Manual Range`” compare a display. In modo manuale premere il tasto `RANGE` per cambiare il campo di misura notando lo spostamento del relativo punto decimale e il valore di fondo scala della barra grafica. Il tasto `RANGE` non è attivo nella posizioni `Ω`, `Hz%`, `Type K` e `60A`, `600A`, `1000A`. In modo Autorange lo strumento seleziona il rapporto più appropriato per effettuare la misura. Se una lettura è più alta del valore massimo misurabile, l’indicazione "`OL`" appare a display. Premere il tasto `RANGE` per oltre 1 secondo per uscire dal modo manuale e ripristinare il modo Autorange.

### Tasto `MODE /VFD`

La pressione del tasto `MODE /VFD` consente la selezione di una doppia funzione presente sul selettore. In particolare esso è attivo nella posizione `Ω CAP` per la selezione delle misure di prova diodi, il test continuità, capacità e la misura di resistenza, nella posizione `TypeK` per la selezione della misura di temperatura in `°C`, `°F` o `K`, `Hz%` per la selezione delle misure di frequenza e duty cycle, `V AC+DC` per la selezione delle misure “`mV`” e “`V (AC+DC)`” (vedere § 4.3), `V Hz%` per la selezione delle misure di tensione AC, frequenza tensione AC e duty cycle tensione AC, `LoZAC+DC` per la selezione delle misure di tensione AC con bassa impedenza (vedere § 4.3) “`V`” e “`V (AC+DC)`”, `60A`, `600A`, `1000A` per la selezione delle misure di corrente AC o DC. Nella posizione `Ω CAP` la pressione prolungata (`>2s`) del tasto `MODE /VFD` permette la selezione del tipo di pinza Standard () oppure Flessibile (). Nelle posizioni `VAC+DC`, `60A`, `600A`, `1000A` la pressione prolungata (`>2s`) del tasto `MODE/VFD` permette di abilitare/disabilitare il modo di misura VFD (`Variable Frequency Driver`) (vedere § 4.3) che permette di eseguire una valutazione di corrente e tensione AC a valle di regolatori di frequenza variabile (Inverters).

### Tasto `IR/` (`HT9025T`), Tasto (`HT9025`)

La pressione del tasto `IR/` (`HT9025T`) permette di attivare la visualizzazione della sezione multimetro o della combinazione multimetro + immagine termografica (vedere § 5.14). La pressione prolungata (`>2s`) del tasto `IR/` (`HT9025T`) o semplice del tasto (`HT9025`) permette l’accensione/spegnimento dell’illuminatore interno a LED bianco (vedere Fig. 2 – parte 2).

### Tasto `/INRUSH`

Il tasto `/INRUSH`, formato dall’insieme dei tasti “ ” e ``, ``, ``, ``, permette di entrare nella sezione di programmazione dello strumento al fine di impostare sia i parametri di sistema sia quelli legati alla rilevazione dell’immagine termografica (vedere § 4.3). Nelle posizioni `60A`, `600A`, `1000A` la pressione prolungata (`>2s`) del tasto `/INRUSH` permette di abilitare/disabilitare la misura delle correnti di spunto AC di macchine elettriche con tempo di risposta 100ms (vedere § 5.11).

### Rilevazione presenza tensione AC senza contatto

**ATTENZIONE**
* Usare preliminarmente il sensore NCV su una sorgente AC nota al fine di verificarne il regolare funzionamento
* Lo spessore dell’isolamento del cavo e la distanza dalla sorgente possono influenzare l’operazione

1. Accendere lo strumento in qualunque posizione del selettore
2. Avvicinare lo strumento in prossimità di una sorgente AC e notare l’accensione del LED rosso sulla parte alta (vedere Fig. 1 – parte 3) che ne evidenzia la presenza

## 4.3. DESCRIZIONE FUNZIONI INTERNE

### Descrizione display parte Multimetro

Fig. 4 Descrizione simboli presenti a display

| Simbolo      | Descrizione                                                                 |
| :----------- | :-------------------------------------------------------------------------- |
|              | Indicazione livello di carica batteria                                      |
| 13.17        | Indicazione ora corrente di sistema                                         |
| HOLD         | Indicazione funzione Data HOLD attiva                                       |
| V            | Indicazione funzione attualmente selezionata                                |
| 228.5        | Indicazione valore misurato                                                 |
| Auto Range   | Indicazione funzione Auto Range attiva                                      |
| Manual Range | Indicazione funzione Range Manuale attiva                                   |
|              | Indicazione presenza tensione elevata                                       |
|              | Indicazione barra grafica analogica                                         |
| Max          | Indicazione valore Massimo della grandezza in misura                        |
| Min          | Indicazione valore Minimo della grandezza in misura                         |
| Pmax         | Indicazione valore di Picco Massimo della grandezza in misura               |
| Pmin         | Indicazione valore di Picco Minimo della grandezza in misura                |
| MAX ``      | Attivazione MAX/MIN con tasto freccia ``                                   |
| REL ``      | Attivazione funzione REL con tasto freccia ``                              |
| PICCO ``    | Attivazione Pmax/Pmin con tasto freccia ``                                 |
| SALVA ``    | Attivazione salvataggio immagine con tasto freccia ``                      |
|              | Attivazione misura duty cycle                                               |

### Descrizione display parte Termocamera (`HT9025T`)

Fig. 5 Descrizione simboli presenti a display

| Simbolo  | Descrizione                                                                                              |
| :------- | :------------------------------------------------------------------------------------------------------- |
| E=0.95   | Valore impostato dell’emissività dell’oggetto (vedere § 4.3)                                            |
| °C       | Indicazione unità di misura temperatura                                                                  |
| S        | Indicazione temperatura associata al cursore fisso centrale                                              |
| H        | Indicazione temperatura del punto più caldo (Hot) dell’immagine                                          |
| C        | Indicazione temperatura del punto più freddo (Cold) dell’immagine                                        |
| 21.9, 41.1 | Indicazione livelli di temperatura dell’immagine IR                                                      |
| Tavolozza | Indicazione tavolozza colori (vedere § 4.3)                                                              |
|          | Indicazione connessione Bluetooth attiva (vedere § 5.15)                                                 |

### Misura Tensione e Corrente AC+DC

Lo strumento è in grado di misurare l’eventuale presenza di componenti alternate sovrapposte ad una generica tensione continua. Ciò può essere di utilità nella misurazione dei segnali impulsivi tipici di carichi non lineari (ex: saldatrici, forni elettrici, ecc..).

1. Selezionare le posizioni `VAC+DC`, `LoZAC+DC` o
2. Premere il tasto `MODE /VFD` selezionando le modalità “`V`” o “`A`” (vedere Fig. 6)
3. Seguire le istruzioni operative mostrate nel § 5.3 e § 5.12

Fig. 6 Descrizione misura tensione e corrente AC+DC

### Salvataggio risultato di misura

1. Premere il tasto `HOLD/REL` per fissare il risultato. Il messaggio “`HOLD`” appare a display e il tasto virtuale `SALVA ` è mostrato a display (vedere Fig. 7 – parte destra)
2. Premere il tasto `` per salvare il dato nella memoria interna dello strumento (il tasto `SALVA ` lampeggia per qualche secondo poi scompare) come immagine BMP oppure nuovamente `HOLD/REL` per uscire dalla funzione
3. Entrare nel Menu generale per rivedere il risultato salvato (vedere § 4.3)

Fig. 7 Salvataggio valore fissato a display

### Misura Relativa

1. Premere a lungo il tasto `HOLD/REL` per entrare nella misura relativa (vedere Fig. 8 – parte destra). Lo strumento azzera il display e salva il valore visualizzato quale valore di riferimento a cui saranno riferite le successive misure. Il simbolo “``” è mostrato a display. Le funzioni “MAX/MIN” e “PICCO” non sono attive in questa modalità
2. Premere il tasto `HOLD/REL` per fissare il risultato. Il messaggio “`HOLD`” appare a display e il tasto virtuale `SALVA ` è mostrato a display
3. Premere il tasto `` per salvare il dato nella memoria dello strumento come immagine BMP oppure nuovamente `HOLD/REL` per tornare alla funzione REL
4. Premere a lungo nuovamente il tasto `HOLD/REL` o ruotare il selettore per uscire dalla funzione

Fig. 8 Misura relativa

### Misura MIN/MAX e PICCO

1. Premere il tasto `MAX ` per entrare nella misura dei valori MAX e MIN della grandezza in esame (vedere Fig. 9 – parte centrale). I simboli “`MAX`” e “`MIN`” sono mostrati a display
2. I valori sono automaticamente aggiornati dallo strumento al superamento di quelli correntemente mostrati (maggiore per MAX, minore per MIN)
3. Premere il tasto `HOLD/REL` per fissare il risultato. Il messaggio “`HOLD`” e il tasto `SALVA ` sono mostrati a display
4. Premere il tasto `` per salvare il dato nella memoria dello strumento come immagine BMP oppure nuovamente `HOLD/REL` per tornare alla funzione MAX/MIN
5. Premere nuovamente il tasto `MAX ` o ruotare il selettore per uscire dalla funzione
6. Premere il tasto `PICCO ` per entrare nella misura dei valori di Picco della grandezza in esame (vedere Fig. 9 – parte destra). I simboli “`Pmax`” e “`Pmin`” sono mostrati a display e i valori sono aggiornati con le stesse modalità della funzione MAX/MIN
7. Premere il tasto `HOLD/REL` per fissare il risultato. Il messaggio “`HOLD`” e il tasto `SALVA ` sono mostrati a display
8. Premere il tasto `` per salvare il dato nella memoria interna dello strumento come immagine BMP oppure nuovamente `HOLD/REL` per tornare alla funzione PICCO
9. Premere nuovamente il tasto `PICCO ` o ruotare il selettore per uscire dalla funzione

Fig. 9 Misura MAX /MIN e PICCO

### Misura di Tensione AC, AC+DC con bassa impedenza (LoZ)

Questa modalità permette di eseguire la misura della tensione AC/DC con una bassa impedenza di ingresso in modo da eliminare le letture errate dovute a tensioni parassite per accoppiamenti di tipo capacitivo.

1. Selezionare la posizione `LoZAC+DC`
2. Premere il tasto `MODE /VFD` selezionando le modalità “`V`” o “`V`” (vedere Fig. 10)
3. Seguire le istruzioni operative mostrate nei § 5.2

Fig. 10 Descrizione misura Tensione LoZ

### Misura Tensione o Corrente su dispositivi VFD

Questa modalità permette di eseguire la misura della tensione AC o della corrente AC a valle di regolatori di frequenza variabile (`VFD = Variable Frequency Drivers = Inverters`)

1. Selezionare le posizioni `VAC+DC` o `60A`, `600A`, `1000A`.
2. Premere il tasto `MODE/VFD` selezionando le modalità “`V`” o “`A`”
3. Premere a lungo il tasto `MODE/VFD` selezionando le modalità “`VFD`” (vedere Fig. 11)
4. Seguire le istruzioni operative mostrate nei § 5.1 o § 5.9
5. Premere a lungo nuovamente il tasto `MODE/VFD` o ruotare il selettore per uscire dalla funzione

Fig. 11 Descrizione misura di Tensione o Corrente AC in modo VFD

### Menu generale dello strumento

1. Premere il tasto `/INRUSH` per accedere al menu generale dello strumento

Fig. 12 Menu generale dello strumento (`HT9025T` e `HT9025`)

2. Usare i tasti freccia `` o `` per la selezione delle voci di menu e i tasti freccia ``, `` per la selezione dei parametri e per entrare/uscire dalle sottosezioni interne

#### Comando Tavolozza (`HT9025T`)

3. Selezionare la voce “Tavolozza” e premere il tasto per la scelta della tavolozza di colori da usare nella funzionalità Termocamera
4. Usare il tasto freccia `` o il tasto per la selezione tra le opzioni: `Ferro`, `Arcobaleno Grigio`, `Grigio Inverso`, `Piuma`
5. Premere il tasto freccia ``, il tasto o il tasto `HOLD/REL` per confermare e uscire dal menu generale

#### Comando Unità Temp (`HT9025T`)

6. Selezionare la voce “Unità Temp” e premere i tasti o `` per abilitare la scelta dell’unità di misura della temperatura a infrarossi (il parametro è evidenziato in grigio)
7. Usare i tasti freccia `` o `` per la selezione delle opzioni: `°C` (`Celsius`), `°F` (`Fahrenheit`) o `K` (`Kelvin`)
8. Premere il tasto freccia ``, il tasto o il tasto `HOLD/REL` per confermare e uscire dal menu generale

#### Comando Misura (`HT9025T`)

9. Selezionare la voce “Misura” e premere il tasto o `` per abilitare l’attivazione/disattivazione dei cursori associati al punto più “caldo” o più “freddo” nell’immagine termografica (vedere Fig. 13)

Fig. 13 Menu Misura

10. Usare il tasto freccia `` per la selezione delle opzioni: `ON` (attivazione), `OFF` (disattivazione)
11. Premere il tasto freccia ``, il tasto o il tasto `HOLD/REL` per confermare e uscire dal menu generale

#### Comando Emissività (`HT9025T`)

12. Selezionare la voce “Emissività” e premere i tasti o `` per impostare il valore del parametro Emissività da usare nella funzionalità Termocamera
13. Usare i tasti freccia `` o `` per la selezione del valore all’interno del campo: `0.01 ÷ 1.00`
14. Premere il tasto freccia ``, il tasto o il tasto `HOLD/REL` per confermare e uscire dal menu generale

#### Comando Registrazione

Questo comando permette di impostare i parametri e attivare la registrazione dei valori delle grandezze misurate dallo strumento in funzionalità Multimetro. Per le istruzioni operative vedere il § 5.13.

#### Comando Lingua

15. Selezionare la voce “Lingua” e premere i tasti o `` per abilitare la scelta della lingua
16. Usare i tasti freccia `` o `` per la selezione della lingua tra le opzioni disponibili

Fig. 14 Menu Lingua

17. Premere il tasto freccia ``, il tasto o il tasto `HOLD/REL` per confermare e uscire dal menu generale

#### Comando Impostazioni

18. Selezionare la voce “Impostazioni” e premere i tasti o `` per la visualizzazione delle impostazioni di sistema. La videata seguente è mostrata a display:

Fig. 15 Menu Impostazioni (`HT9025T` e `HT9025`)

19. Usare i tasti freccia `` o `` e i tasti o `` per la selezione delle seguenti opzioni:
    * `Suono tasti` → attivazione/disattivazione del suono associato alla pressione dei tasti funzione
    * `Bluetooth` → attivazione/disattivazione collegamento Bluetooth (vedere § 5.15)
    * `Laser` → attivazione/disattivazione puntatore laser (`HT9025T`)
    * `Luminosità` → impostazione livello di contrasto del display
    * `Autospegnimento` → disattivazione (`OFF`) e attivazione (`15min`, `30min`, `60min`) dell’autospegnimento dello strumento
20. Premere il tasto freccia ``, il tasto o il tasto `HOLD/REL` per confermare e uscire dal menu generale

#### Comando Data/Ora

21. Selezionare la voce “Data/Ora” e premere il tasto o `` per l’impostazione della data/ora di sistema. La videata seguente è mostrata a display

Fig. 16 Menu Data/Ora

22. Usare i tasti `` o `` e i tasti o `` per la selezione/impostazione della data/ora nei formati:
    * `Europeo` → opzione `24h (ON)`
    * `Americano` (visualizzazione AM/PM) → opzione `24h (OFF)`
23. Premere il tasto freccia ``, il tasto o il tasto `HOLD/REL` per confermare e uscire dal menu generale

#### Comando Memoria (richiamo e cancellazione immagini)

24. Selezionare la voce “Memoria” e premere il tasto o `` per accedere all’area di memoria interna in cui è possibile richiamare e cancellare le immagini salvate. La seguente videata è mostrata a display:

Fig. 17 Menu Memoria

25. Usare i tasti `` o `` e i tasti o `` per la selezione dell’opzione “Richiama foto”. Le seguenti videate (corrispondenti all’ultima immagine salvata) sono mostrate a display:

Fig. 18 Richiamo immagini a display

26. Usare i tasti freccia `` o `` per richiamare a display l’immagine desiderata tra quelle salvate nella memoria interna. L’immagine salvata è sempre nel formato “`AAMMGGHHMMSS.bmp`” da cui si può risalire al momento esatto di salvataggio
27. Premere il tasto `MODE/VFD` per uscire dalla funzione e tornare alla videata di misura
28. Premere il tasto `HOLD/REL` sull’immagine richiamata. La videata di Fig. 19 – parte sinistra è mostrata a display

Fig. 19 Cancellazione e condivisione immagini richiamate

29. Premere il tasto `MODE/VFD` per cancellare la foto richiamata o il tasto `HOLD/REL` per tornare alla videata precedente
30. Con immagine fissa a display usare il tasto freccia `` per selezionare l’opzione “Condividi” (disponibile solo per screenshots di immagini IR su `HT9025T`) (vedere Fig. 19 – parte destra) in modo da condividere l’immagine su dispositivo mobile tramite APP HTMercury e collegamento Bluetooth (vedere § 5.15)
31. Usare i tasti `` o `` e i tasti o `` per la selezione dell’opzione “Cancella foto” (vedere Fig. 17). La seguente videata è mostrata a display:

Fig. 20 Cancellazione di tutte le immagini salvate

32. Usare i tasti freccia `` o `` per confermare (Si) o negare (No) l’operazione di cancellazione di tutte le immagini salvate
33. Premere il tasto per confermare l’operazione

#### Comando Informazioni

34. Selezionare la voce “Informazioni” e premere i tasti o `` per la visualizzazione delle informazioni sullo strumento (versione Hardware e Firmware)

<!-- Chunk: Pages 23-44 -->
35. Premere il tasto freccia ``, il tasto `<ok>` o il tasto `HOLD/REL` per confermare e uscire dal menu generale.

#### Comando Imp:Default

36. Selezionare la voce “Imp.Default” e premere i tasti `<ok>` o `` per ripristinare le condizioni di default (fabbrica) dello strumento.
    ![Videata ripristino condizioni di default](Fig._22_Videata_ripristino_condizioni_di_default.png)
37. Usare i tasti freccia `` o `` per confermare (Si) o negare (No) l’operazione di reset.
38. Premere il tasto `<ok>` per confermare o il tasto `HOLD/REL` per uscire dal menu generale.
39. L’operazione **non** cancella i dati salvati nella memoria interna.

---

# 5. ISTRUZIONI OPERATIVE

## 5.1. MISURA TENSIONE AC, AC+DC, VFD

> ATTENZIONE
> La massima tensione AC in ingresso è 1000Vrms. Non misurare tensioni che eccedano i limiti espressi in questo manuale. Il superamento di tali limiti potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.

1. Selezionare la posizione `VAC+DC`. Verificare la presenza di una sorgente AC usando il sensore NCV (vedere § 4.2).
2. Premere il tasto `MODE/VFD` per selezionare la misura “V ”.
3. Inserire il cavo rosso nel terminale di ingresso `VHz% CAP ` e il cavo nero nel terminale di ingresso `COM`.
4. Posizionare il puntale rosso ed il puntale nero rispettivamente nei punti del circuito in esame (vedere Fig. 23). Il valore della tensione è mostrato a display.
5. Se sul display è visualizzato il messaggio "OL" selezionare una portata più elevata.
6. Premere il tasto `MODE/VFD` per selezionare le misure “Hz” o “%” al fine di visualizzare i valori della frequenza e del duty cycle della tensione in ingresso. La barra grafica non è attiva in queste funzioni.
7. Per l’uso delle funzioni `HOLD` e `RANGE` vedere il § 4.2.
8. Per le misure AC+DC, VFD e le funzioni interne vedere il § 4.3.
9. Per il salvataggio del risultato di misura vedere § 4.3.

## 5.2. MISURA TENSIONE LOZAC, LOZAC+DC

> ATTENZIONE
> La massima tensione AC in ingresso è 1000Vrms. Non misurare tensioni che eccedano i limiti espressi in questo manuale. Il superamento di tali limiti potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.

1. Selezionare la posizione `LoZ AC+DC` (vedere § 4.3).
2. Premere il tasto `MODE/VFD` per selezionare la misura “V “ o “V (AC+DC)”.
3. Inserire il cavo rosso nel terminale di ingresso `VHz% CAP ` e il cavo nero nel terminale di ingresso `COM`.
4. Posizionare il puntale rosso ed il puntale nero rispettivamente nei punti del circuito in esame (vedere Fig. 24). Il valore della tensione è mostrato a display.
5. Se sul display è visualizzato il messaggio "OL" selezionare una portata più elevata.
6. Per l’uso delle funzioni `HOLD` e `RANGE` vedere il § 4.2.
7. Per le misure AC+DC e l’uso delle funzioni interne vedere il § 4.3.
8. Per il salvataggio del risultato di misura vedere § 4.3.

---

## 5.3. MISURA TENSIONE DC

> ATTENZIONE
> * La massima tensione DC in ingresso è 1500V. Non misurare tensioni che eccedono i limiti indicati in questo manuale. Il superamento dei limiti di tensione potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.
> * La marcatura CAT III 1000V su puntali di misura garantisce comunque la misura in sicurezza di tensione fino a 1500V.

1. Selezionare la posizione `VAC+DC`.
2. Premere il tasto `MODE/VFD` per selezionare la misura “mV ”.
3. Inserire il cavo rosso nel terminale di ingresso `VHz% CAP ` e il cavo nero nel terminale di ingresso `COM`.
4. Posizionare il puntale rosso ed il puntale nero rispettivamente nei punti a potenziale positivo e negativo del circuito in esame (vedere Fig. 25). Il valore della tensione è mostrato a display.
5. Se sul display è visualizzato il messaggio "OL" selezionare una portata più elevata.
6. La visualizzazione del simbolo " -" sul display dello strumento indica che la tensione ha verso opposto rispetto alla connessione di Fig. 25.
7. Per l’uso delle funzioni `HOLD` e `RANGE` vedere il § 4.2.
8. Per l’uso delle funzioni interne vedere il § 4.3.
9. Per il salvataggio del risultato di misura vedere § 4.3.

## 5.4. MISURA FREQUENZA E DUTY CYCLE

> ATTENZIONE
> La massima tensione AC in ingresso è 1000V. Non misurare tensioni che eccedono i limiti indicati in questo manuale. Il superamento dei limiti di tensione potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.

1. Selezionare la posizione `Hz%`.
2. Premere il tasto `MODE/VFD` per selezionare le misure “Hz” o “%” al fine di visualizzare i valori della frequenza e del duty cycle (simbolo “ ” presente a display) del segnale in ingresso.
3. Inserire il cavo rosso nel terminale di ingresso `VHz% CAP ` e il cavo nero nel terminale di ingresso `COM`.
4. Posizionare il puntale rosso ed il puntale nero rispettivamente nei punti del circuito in esame (vedere Fig. 26). Il valore della frequenza (Hz) o duty cycle (%) è mostrato a display. La barra grafica non è attiva in queste funzioni.
5. Per l’uso delle funzioni `HOLD` e `RANGE` vedere il § 4.2.
6. Per l’uso delle funzioni interne vedere il § 4.3.
7. Per il salvataggio del risultato di misura vedere § 4.3.

---

## 5.5. MISURA RESISTENZA E TEST CONTINUITÀ

> ATTENZIONE
> Prima di effettuare una qualunque misura di resistenza accertarsi che il circuito in esame non sia alimentato e che eventuali condensatori presenti siano scarichi.

1. Selezionare la posizione ` CAP`.
2. Inserire il cavo rosso nel terminale di ingresso `VHz% CAP ` e il cavo nero nel terminale di ingresso `COM`.
3. Posizionare i puntali nei punti desiderati del circuito in esame (vedere Fig. 27). Il valore della resistenza è visualizzato a display.
4. Se sul display è visualizzato il messaggio "OL" selezionare una portata più elevata.
5. Premere il tasto `MODE/VFD` per selezionare la misura “ ” relativa al test continuità e posizionare i puntali nei punti desiderati del circuito in esame (vedere Fig. 27 – parte sinistra).
6. Il valore della resistenza (solo indicativo) è visualizzato sul display espresso in `` e lo strumento emette un segnale acustico qualora il valore della resistenza risulti `< 50 `.
7. Per l’uso delle funzioni `HOLD` e `RANGE` vedere il § 4.2.
8. Per l’uso delle funzioni interne vedere il § 4.3.
9. Per il salvataggio del risultato di misura vedere § 4.3.

## 5.6. PROVA DIODI

> ATTENZIONE
> Prima di effettuare una qualunque misura di resistenza accertarsi che il circuito in esame non sia alimentato e che eventuali condensatori presenti siano scarichi.

1. Selezionare la posizione ` CAP`.
2. Premere il tasto `MODE/VFD` per selezionare la misura “ ”.
3. Inserire il cavo rosso nel terminale di ingresso `VHz% CAP ` e il cavo nero nel terminale di ingresso `COM`.
4. Posizionare i puntali ai capi del diodo in esame (vedere Fig. 28) rispettando le polarità indicate. Il valore della tensione di soglia in polarizzazione diretta è mostrato a display.
5. Se il valore della tensione di soglia è 0mV la giunzione P-N del diodo è in corto circuito.
6. Se lo strumento visualizza il messaggio "OL" i terminali del diodo sono invertiti rispetto a quanto indicato in Fig. 28 oppure la giunzione P-N del diodo è danneggiata.
7. Per l’uso delle funzioni `HOLD` e `RANGE` vedere il § 4.2.
8. Per l’uso delle funzioni interne vedere il § 4.3.
9. Per il salvataggio del risultato di misura vedere § 4.3.

---

## 5.7. MISURA CAPACITÀ

> ATTENZIONE
> Prima di eseguire misure di capacità su circuiti o condensatori, rimuovere l’alimentazione al circuito sotto esame e lasciare scaricare tutte le capacità presenti in esso. Nel collegamento tra il multimetro e la capacità sotto esame rispettare la corretta polarità (quando richiesto).

1. Selezionare la posizione ` CAP`.
2. Premere il tasto `MODE/VFD` fino a visualizzare il simbolo “nF” a display.
3. Inserire il cavo rosso nel terminale di ingresso `VHz% CAP ` e il cavo nero nel terminale di ingresso `COM`.
4. Premere a lungo il tasto `HOLD/REL` prima di eseguire la misura (vedere § 4.2).
5. Posizionare i puntali ai capi della capacità in esame rispettando eventualmente le polarità positive (cavo rosso) e negative (cavo nero) (vedere Fig. 29). Il valore è mostrato a display. In funzione della capacità, lo strumento potrebbe impiegare diversi secondi prima di visualizzare il valore finale corretto. La barra grafica non è attiva in questa funzione.
6. Il messaggio "OL" indica che il valore di capacità eccede il valore massimo misurabile.
7. Per l’uso delle funzioni `HOLD` e `RANGE` vedere il § 4.2.
8. Per l’uso delle funzioni interne vedere il § 4.3.
9. Per il salvataggio del risultato di misura vedere § 4.3.

## 5.8. MISURA TEMPERATURA CON SONDA K

> ATTENZIONE
> Prima di effettuare qualunque misura di temperatura accertarsi che il circuito in esame non sia alimentato e che eventuali condensatori presenti siano scarichi.

1. Selezionare la posizione `TypeK`.
2. Premere il tasto `MODE/VFD` fino a visualizzare il simbolo “°C” o “°F” a display.
3. Inserire l’adattatore in dotazione nei terminali di ingresso `VHz% CAP ` (polarità +) e `COM` (polarità -).
4. Collegare la sonda a filo tipo K in dotazione o la termocoppia tipo K opzionale allo strumento tramite l’adattatore rispettando le polarità positiva e negativa presenti su di esso (vedere Fig. 30). Il valore della temperatura è mostrato a display. La barra grafica non è attiva in questa funzione.
5. Il messaggio "OL." indica che il valore di temperatura eccede il valore massimo misurabile.
6. Per l’uso delle funzioni `HOLD` e `RANGE` vedere il § 4.2.
7. Per l’uso delle funzioni interne vedere il § 4.3.
8. Per il salvataggio del risultato di misura vedere § 4.3.

---

## 5.9. MISURA CORRENTE DC

> ATTENZIONE
> Assicurarsi che tutti i terminali di ingresso dello strumento siano disconnessi.

1. Selezionare la posizione `60A`, `600A` o `1000A`.
2. Premere il tasto `MODE/VFD` per selezionare la misura “A ”.
3. Premere a lungo il `HOLD/REL` per azzerare la corrente di magnetizzazione residua (vedere § 4.3).
4. Inserire il cavo all’interno del toroide al centro dello stesso (vedere Fig. 31) al fine di ottenere misure accurate nella direzione dal polo positivo “+” (vedere Fig. 1 – parte 2) al polo negativo “-“ (vedere Fig. 2 – parte 1). Utilizzare le tacche presenti come riferimento (vedere Fig. 3).
5. Il valore della corrente DC è visualizzato a display.
6. Se sul display è visualizzato il messaggio "OL" si è raggiunto il valore massimo misurabile.
7. La visualizzazione del simbolo " -" sul display dello strumento indica che la corrente ha verso opposto rispetto alla connessione di Fig. 31.
8. Per l’uso della funzione `HOLD` vedere il § 4.2.
9. Per l’uso delle funzioni interne vedere il § 4.3.
10. Per il salvataggio del risultato di misura vedere § 4.3.

## 5.10. MISURA CORRENTE AC

> ATTENZIONE
> Assicurarsi che tutti i terminali di ingresso dello strumento siano disconnessi.

1. Selezionare la posizione `60A`, `600A` o `1000A`.
2. Premere il tasto `MODE/VFD` per selezionare la misura “A ”.
3. Inserire il cavo all’interno del toroide al centro dello stesso (vedere Fig. 32) al fine di ottenere misure accurate. Utilizzare le tacche presenti come riferimento (vedere Fig. 3).
4. Il valore della corrente AC è visualizzato a display.
5. Se sul display è visualizzato il messaggio "OL" si è raggiunto il valore massimo misurabile.
6. Per l’uso della funzione `HOLD` vedere il § 4.2.
7. Per l’uso delle funzioni interne vedere il § 4.3.
8. Per il salvataggio del risultato di misura vedere § 4.3.

---

## 5.11. MISURA CORRENTE DI SPUNTO AC (INRUSH)

> ATTENZIONE
> Assicurarsi che tutti i terminali di ingresso dello strumento siano disconnessi.

1. Selezionare la posizione `60A`, `600A` o `1000A`.
2. Premere il tasto `MODE/VFD` per selezionare la misura “A ”.
3. Premere a lungo il tasto `<INRUSH>` per attivare la funzione “INRUSH”. I simboli “ ” e “ - - - - “ sono mostrati a display (vedere – parte sinistra).
4. Inserire il cavo all’interno del toroide al centro dello stesso (vedere Fig. 33 – parte destra) al fine di ottenere misure accurate. Utilizzare le tacche presenti come riferimento (vedere Fig. 3).
5. Il valore della corrente di spunto AC è visualizzato a display.
6. Se sul display è visualizzato il messaggio "OL" si è raggiunto il valore massimo misurabile.
7. Per l’uso della funzione `HOLD` vedere il § 4.2.
8. Per l’uso delle funzioni interne vedere il § 4.3.
9. Per il salvataggio del risultato di misura vedere § 4.3.

---

## 5.12. MISURA CORRENTE DC, AC, AC+DC CON PINZA

> ATTENZIONE
> * La massima corrente misurabile in questa funzione è 3000A AC o 1000A DC. Non misurare correnti che eccedono i limiti indicati in questo manuale.
> * Lo strumento esegue la misura sia con il trasduttore a pinza flessibile F3000U (solo AC) sia con altri trasduttori a pinza standard della famiglia HT. Con trasduttori aventi il connettore di uscita HT è necessario l’adattatore opzionale NOCANBA per eseguire il collegamento.

1. Selezionare la posizione `A`.
2. Premere a lungo (>2s) il tasto `MODE/VFD` per selezionare il tipo di pinza tra le opzioni “ ” (pinza standard) oppure “ ” (pinza flessibile F3000U).
3. Premere il tasto `MODE/VFD` per selezionare il tipo di misura “DC”, “AC” o “AC+DC” (solo per pinze standard).
4. Premere il tasto `RANGE` per selezionare sullo strumento la stessa portata impostata sulla pinza tra le opzioni: 1000 mA, 10A, 30A, 40A, 100A, 300A, 400A, 1000A, 3000A. Tale valore è presente nella parte alta centrale del display.
5. Inserire il cavo rosso nel terminale di ingresso `VHz% CAP ` e il cavo nero nel terminale di ingresso `COM`. Per modelli di trasduttori standard (vedere § 7.3.2) con connettore HT usare l’adattatore opzionale NOCANBA. Per informazioni sull’uso dei trasduttori a pinza fare riferimento al relativo manuale d’uso.
6. Inserire il cavo all’interno del toroide (vedere Fig. 34). Il valore della corrente è visualizzato a display.
7. Se sul display è visualizzato il messaggio "OL" si è raggiunto il valore massimo misurabile.
8. Per l’uso della funzione `HOLD` vedere il § 4.2.
9. Per la misura AC+DC vedere il § 4.3. Per l’uso delle funzioni interne vedere il § 4.3.
10. Per il salvataggio del risultato di misura vedere § 4.3.

---

## 5.13. FUNZIONE DATA LOGGER

1. Accendere lo strumento ruotando il selettore nella posizione desiderata.

#### Impostazione intervallo di campionamento

2. Premere il tasto “<menu>”, selezionare la voce “Registrazione” e premere il tasto ``. La videata di Fig. 35 – parte sinistra è mostrata a display.
    ![Data logger – Impostazione intervallo di campionamento](Fig._35_Data_logger_–_Impostazione_intervallo_di_campionamento.png)
3. Selezionare la voce “Intervallo Camp.” (vedere – parte centrale) e premere il tasto `` per la definizione dell’intervallo di campionamento della registrazione. La videata di – parte destra è mostrata a display.
4. Usare i tasti freccia `` o `` per selezionare le voci “Min” o “Sec” e premere il tasto `<ok>` per entrare nella modalità di impostazione. Il valore presente assume colore nero.
5. Usare i tasti freccia `` o `` per l’impostazione dei valori compresi negli intervalli: 0 ÷ 59sec e 0 ÷ 15min.
6. Premere il tasto `<ok>` per confermare. I valori impostati assumono colore bianco.
7. Premere il tasto `` per tornare alla videata precedente.

#### Impostazione durata registrazione

8. Selezionare la voce “Durata” (vedere Fig.36 – parte sinistra) e premere il tasto ``. La videata di Fig.36 – parte destra è mostrata a display.
    ![Data logger – Impostazione durata registrazione](Fig._36_Data_logger_–_Impostazione_durata_registrazione.png)

---

9. Usare i tasti freccia `` o `` per selezionare le voci “Ora”, “Min” o “Sec” e premere il tasto `<ok>` per entrare nella modalità di impostazione. Il valore presente assume colore nero.
10. Usare i tasti freccia `` o `` per l’impostazione dei valori compresi negli intervalli: 0 ÷ 10ore, 0 ÷ 59min e 0 ÷ 59sec.
11. Premere il tasto `<ok>` per confermare. I valori impostati assumono colore bianco.
12. Premere il tasto `` per tornare alla videata precedente.

#### Avvio e terminazione registrazione

13. Selezionare la voce “Avvia Registrazione” (vedere Fig.37 – parte sinistra) e premere il tasto `<ok>`. La videata di Fig.37 – parte centrale in cui sono presenti la data/ora di avvio, il tempo residuo e il numero dei campioni acquisiti in tempo reale è mostrata a display. Il messaggio “Registrazione” è presente nella parte alta del display ad indicare il processo in corso.
    ![Data logger – Avvio e terminazione registrazione](Fig._37_Data_logger_–_Avvio_e_terminazione_registrazione.png)
14. Premere il tasto `` (STOP) per terminare la registrazione in qualunque momento oppure attendere lo svolgimento completo dell’operazione.
15. A processo completato la videata di Fig.37 – parte destra è mostrato a display. Premere il tasto `` (SALVA) per salvare la registrazione nella memoria interna dello strumento oppure il tasto `` (CHIUDI).

#### Richiamo, visualizzazione e cancellazione dati registrazione

16. Selezionare la voce “Richiama” (vedere Fig.38 – parte sinistra) e premere il tasto `<ok>`. La videata di Fig.38 – parte destra è mostrata a display.
    ![Data logger – Richiamo a display dati registrazione](Fig._38_Data_logger_–_Richiamo_a_display_dati_registrazione.png)

---

17. Premere il tasto `MODE/VFD` (TREND) per visualizzare a display il grafico della registrazione e il relativo andamento nel tempo (Trend). La videata di Fig.39 – parte sinistra è mostrata a display:
    ![Data logger – Visualizzazione grafico registrazione](Fig._39_Data_logger_–_Visualizzazione_grafico_registrazione.png)
18. Usare i tasti `` o `` per spostare il cursore sul grafico osservando il valore del dato campionato e del relativo istante di campionamento nella parte bassa del display.
19. Premere il tasto `` (ZOOM) per attivare (se disponibile) lo Zoom dei valori sul grafico (vedere Fig.39 – parte destra) allo scopo di aumentare la risoluzione. L’indicazione “Zoom xY” in cui Y = max dimensione di zoom è presente nella parte alta del display. È possibile uno zoom X1 per almeno 10 punti di misura, X2 per almeno 20 punti di misura, X3 per almeno 40 punti di misura e così via per un massimo di 6 operazioni di zoom.
20. Premere il tasto `MODE/VFD` (TREND) per tornare alla videata precedente o il tasto `HOLD/REL` per tornare alla videata normale di misura.
21. Premere il tasto `` (CANC.) per cancellare la registrazione richiamata. La seguente videata e il messaggio “Cancella Registrazioni?” è mostrata a display.
    ![Data logger – Cancellazione registrazione](Fig._40_Data_logger_–_Cancellazione_registrazione.png)
22. Premere nuovamente il tasto `` (CANC.) per confermare l’operazione o il tasto `HOLD/REL` per tornare alla videata normale di misura.

#### Contenuto della memoria e cancellazione di tutte le registrazioni

23. Selezionare la voce “Memoria” (vedere Fig.41 – parte sinistra) e premere il tasto ``. La videata di Fig.41 – parte destra è mostrata a display.

---

    ![Funzione data logger – Contenuto memoria](Fig._41_Funzione_data_logger_–_Contenuto_memoria.png)
24. Il parametro “Num. Registrazioni” indica quante registrazioni sono state salvate nella memoria interna. È possibile salvare fino ad un massimo di 16 registrazioni. Il parametro “Memoria residua” indica il valore percentuale di memoria ancora disponibile per il salvataggio delle registrazioni.
25. Premere il tasto `` per tornare alla videata precedente.
26. Selezionare la voce “Cancella tutte Regist.” (vedere Fig.42 – parte sinistra) e premere il tasto `<ok>`. La videata di Fig.42 – parte destra è mostrata a display.
    ![Data logger – Cancellazione di tutte le registrazioni](Fig._42_Data_logger_–_Cancellazione_di_tutte_le_registrazioni.png)
27. Usare i tasti `` o `` e il tasto `<ok>` per confermare la cancellazione (Si) oppure uscire e tornare alla videata precedente (No).

---

## 5.14. USO DELLA TERMOCAMERA INTERNA (HT9025T)

1. Accendere lo strumento in qualsiasi posizione del selettore.
2. Premere il tasto `IR/` per attivare la termocamera interna.
3. Agire sul selettore di protezione (vedere Fig. 2 – parte 3) scoprendo la lente.
4. Premere il tasto `<menu>` entrando nel menu generale al fine di impostare i valori di emissività dell’oggetto in prova, attivare eventualmente i punti di misura H (punto caldo) e C (punto freddo) e il puntatore laser come descritto nel § 4.3.
5. Inquadrare l’oggetto in prova la cui immagine termografica sarà mostrata a display (vedere § 4.3) con focalizzazione automatica.
6. Nell’immagine termografica i punti di misura H e C sono rispettivamente indicati con puntatori a croce di colore rosso e azzurro.

> ATTENZIONE
> Lo strumento esegue una sequenza di autocalibrazione automatica dopo circa ogni 10s (non disabilitabile) che continua durante il normale funzionamento della termocamera al fine di eliminare gli errori di offset. L’effetto udibile di commutazioni delle parti interne non costituisce un problema dello strumento.

7. Per misure accurate di temperatura assicurarsi che la superficie dell’oggetto in prova sia sempre maggiore della superficie effettivamente misurabile dallo strumento espressa dal suo campo visivo (FOV = Field Of View). Lo strumento HT9025T ha un campo visivo pari a 15.6° x 15.6° e un vettore di rilevazione di 120 x 120 (14400) pxl come mostrato in Fig.43.
    ![Rappresentazione del FOV dello strumento HT9025T](Fig._43_Rappresentazione_del_FOV_dello_strumento_HT9025T.png)
8. Di seguito è riportato la rappresentazione del rapporto D(distanza dall’oggetto)/S (superficie dell’oggetto) per lo strumento con lente da 7.5mm installata. In cui si può notare come il parametro IFOV (Campo visivo istantaneo = risoluzione geometrica dello strumento = dimensione del singolo pxl del sensore IR) sia pari ad 2.26mm alla distanza di 1m dello strumento dall’oggetto in misura. Questo significa che lo strumento è in grado di eseguire corrette misure di temperatura alla distanza di 1m su oggetti aventi dimensioni non inferiori a 2.26mm.

---

    ![Rappresentazione rapporto D/S dello strumento HT9025T](Fig._44_Rappresentazione_rapporto_D_S_dello_strumento_HT9025T.png)
9. Premere il tasto `HOLD/REL` per fissare il risultato. Il messaggio “HOLD” e il tasto `SALVA ` sono mostrati a display (vedere Fig.45).
    ![Salvataggio immagine IR](Fig._45_Salvataggio_immagine_IR.png)
10. Premere il tasto `` per salvare il dato nella memoria interna dello strumento come immagine BMP oppure nuovamente `HOLD/REL` per uscire dalla funzione.
11. Entrare nel Menu generale per rivedere il risultato salvato (vedere Fig. 46 – parte sinistra).
    ![Richiamo e cancellazione immagine IR](Fig._46_Richiamo_e_cancellazione_immagine_IR.png)
12. Premere il tasto `HOLD/REL` per selezionare l’opzione “Cancella” e confermare con il tasto `MODE/VFD`.
13. Usare i tasti freccia `` o `` per selezionare l’opzione “Cond.” in modo da condividere l’immagine su dispositivo mobile tramite APP HTMercury e collegamento Bluetooth (vedere § 5.15).

---

## 5.15. DOWNLOAD APP HTMERCURY

1. Premere il tasto `<menu>/INRUSH`, selezionare il menu “Impostazioni” e attivare il collegamento Bluetooth sullo strumento (vedere § 4.3) come mostrato nella Fig.47.
    ![Attivazione collegamento Bluetooth](Fig._47_Attivazione_collegamento_Bluetooth.png)
2. Scaricare la APP HTMercury dagli stores di Android e iOS e installarla sul dispositivo mobile utilizzando i seguenti QR codes:

> ATTENZIONE
> Per ogni informazione sull’utilizzo dell’APP HTMercury fare riferimento alla guida in linea presente all’interno dell’applicazione.

**Download versione Android**
**Download versione iOS**

---

# 6. MANUTENZIONE

## 6.1. GENERALITÀ

1. Durante l’utilizzo e la conservazione rispettare le raccomandazioni elencate in questo manuale per evitare possibili danni o pericoli durante l’utilizzo.
2. Non utilizzare lo strumento in ambienti caratterizzati da elevato tasso di umidità o temperatura elevata. Non esporre direttamente alla luce del sole.
3. Spegnere sempre lo strumento dopo l’utilizzo. Se si prevede di non utilizzarlo per un lungo periodo rimuovere la batteria per evitare fuoruscite di liquidi da parte di quest’ultima che possano danneggiare i circuiti interni dello strumento.

## 6.2. RICARICA BATTERIA INTERNA

Quando sul display appare il simbolo “<battery_low_symbol>” occorre ricaricare la batteria interna.

> ATTENZIONE
> Solo tecnici esperti possono effettuare questa operazione. Prima di effettuare questa operazione assicurarsi di aver rimosso tutti i cavi dai terminali di ingresso o il cavo in esame dall’interno del toroide.

1. Posizionare il selettore in posizione `OFF` e rimuovere i cavi dai terminali di ingresso.
2. Ruotare la vite di fissaggio del coperchio vano batterie dalla posizione “<closed_lock_symbol>” alla posizione “<open_lock_symbol>” e rimuovere lo stesso (vedere Fig. 2 – parte 6).
3. Rimuovere la batteria ricaricabile e inserirla nella base di ricarica in dotazione.
4. Inserire l’alimentatore caricabatteria nella base di ricarica.
5. Collegare l’alimentatore alla rete elettrica e alla base di ricarica. Osservare l’accensione del LED verde “Power” e del LED rosso “Charge”.
6. Eseguire il processo di ricarica fino allo spegnimento del LED rosso “Charge”.
7. Scollegare l’alimentatore dalla rete ed estrarre la batteria dalla base di ricarica.
8. Reinserire la batteria nello strumento.
9. Riposizionare il vano batterie e ruotare la vite di fissaggio del vano batterie dalla posizione “<open_lock_symbol>” alla posizione “<closed_lock_symbol>”.

## 6.3. PULIZIA DELLO STRUMENTO

Per la pulizia dello strumento utilizzare un panno morbido e asciutto. Non usare mai panni umidi, solventi, acqua, ecc.

---

# 7. SPECIFICHE TECNICHE

## 7.1. CARATTERISTICHE TECNICHE

Incertezza calcolata come ± [%lettura + (num. cifre x risoluzione)] a 18°C  28°C, < 75% RH

#### Tensione DC

| Campo      | Risoluzione | Incertezza                | Impedenza ingresso |
| :--------- | :---------- | :------------------------ | :----------------- |
| 600.0mV    | 0.1mV       | ± (0.8%lettura + 8 cifre) | > 10 M            |
| 6.000V     | 0.001V      | ± (0.5%lettura + 5 cifre) |                    |
| 60.00V     | 0.01V       |                           |                    |
| 600.0V     | 0.1V        | ± (0.8%lettura + 5 cifre) |                    |
| 1500V      | 1V          |                           |                    |

Protezione contro sovraccarichi: 1500V DC

#### Tensione AC TRMS

| Campo      | Risoluzione | Incertezza (*)                                   | Impedenza ingresso |
| :--------- | :---------- | :----------------------------------------------- | :----------------- |
| 6.000V     | 0.001V      | ± (1.2%lett. + 5 cifre) (50 Hz  60Hz) <br> ± (2.5%lettura + 5 cifre) (61 Hz  1kHz) | > 9 M             |
| 60.00V     | 0.01V       |                                                  |                    |
| 600.0V     | 0.1V        |                                                  |                    |
| 1000V      | 1V          |                                                  |                    |

(*) Incertezza specificata dal 10% al 100% del campo di misura e forma d’onda sinusoidale
Protezione da sovraccarichi: 1000V DC/AC rms; Campo frequenza: 50Hz ÷ 1kHz;
Incertezza funzione PEAK: ±(10%lettura), Tempo di risposta funzione PEAK: 1ms
Per forma d’onda non sinusoidale l’incertezza è: ± (10.0%lettura + 20 cifre)
Sensore NCV integrato per rilevazione tensione AC: LED acceso per tensione fase-terra compresa tra 100V e 1000V, 50/60Hz

#### Tensione AC+DC TRMS

| Campo      | Risoluzione | Incertezza (*)             | Impedenza ingresso |
| :--------- | :---------- | :------------------------- | :----------------- |
| 6.000V     | 0.001V      | ± (2.5%lettura + 20 cifre) | > 10 M            |
| 60.00V     | 0.01V       |                            |                    |
| 600.0V     | 0.1V        |                            |                    |
| 1000V      | 1V          |                            |                    |

(*) Incertezza specificata dal 10% al 100% del campo di misura e forma d’onda sinusoidale
Protezione da sovraccarichi: 1000V DC/AC rms; Campo frequenza: 50Hz ÷ 1kHz

#### Tensione AC TRMS con bassa impedenza (LoZ)

| Campo      | Risoluzione | Incertezza (*)             | Impedenza ingresso |
| :--------- | :---------- | :------------------------- | :----------------- |
| 6.000V     | 0.001V      | ± (3.0%lettura + 20 cifre) | 300k              |
| 60.00V     | 0.01V       |                            |                    |
| 600.0V     | 0.1V        |                            |                    |
| 1000V      | 1V          |                            |                    |

(*) Incertezza specificata dal 10% al 100% del campo di misura e forma d’onda sinusoidale
Per forma d’onda non sinusoidale l’incertezza è: ± (10.0%lettura + 20 cifre)
Protezione da sovraccarichi: 1000V DC/AC rms; Campo frequenza: 50Hz ÷ 1kHz

#### Tensione AC+DC TRMS con bassa impedenza (LoZ)

| Campo      | Risoluzione | Incertezza (*)             | Impedenza ingresso |
| :--------- | :---------- | :------------------------- | :----------------- |
| 6.000V     | 0.001V      | ± (3.5%lettura + 40 cifre) | < 300k            |
| 60.00V     | 0.01V       |                            |                    |
| 600.0V     | 0.1V        |                            |                    |
| 1000V      | 1V          |                            |                    |

(*) Incertezza specificata dal 10% al 100% del campo di misura e forma d’onda sinusoidale
Protezione da sovraccarichi: 1000V DC/AC rms; Campo frequenza: 50Hz ÷ 1kHz

#### Corrente DC

| Campo     | Risoluzione | Incertezza (*)            |
| :-------- | :---------- | :------------------------ |
| 60.00A    | 0.01A       | ± (2.0%lettura + 8 cifre) |
| 600.0A    | 0.1A        |                           |
| 1000A     | 1A          |                           |

Protezione da sovraccarichi: 1000A DC/AC rms

---

#### Corrente AC TRMS / Corrente di spunto (INRUSH)

| Campo     | Risoluzione | Incertezza (*)            |
| :-------- | :---------- | :------------------------ |
| 60.00A    | 0.01A       | ± (2.5%lettura + 5 cifre) |
| 600.0A    | 0.1A        |                           |
| 1000A     | 1A          |                           |

(*) Incertezza specificata dal 10% al 100% del campo di misura; forma d’onda sinusoidale
Tempo di risposta funzione INRUSH: 100ms; Campo frequenza: 50Hz ÷ 60Hz
Protezione da sovraccarichi: 1000A DC/AC rms

#### Corrente DC con trasduttori a pinza standard

| Campo    | Rapporto di uscita | Risoluzione | Incertezza (*)            |
| :------- | :----------------- | :---------- | :------------------------ |
| 1000mA   | 1000mV/1000mA      | 1mA         | ± (0.8%lettura + 5 cifre) |
| 10A      | 100mV/1A           | 0.01A       |                           |
| 40A (**) | 10mV/1A            | 0.01A       | ± (1.8%lettura + 5 cifre) |
| 100A     | 10mV/1A            | 0.1A        | ± (0.8%lettura + 5 cifre) |
| 400A (**) | 1mV/1A             | 0.1A        | ± (1.8%lettura + 5 cifre) |
| 1000A    | 1mV/1A             | 1A          | ± (0.8%lettura + 5 cifre) |

(*) Incertezza riferita al solo strumento senza trasduttore (**) Con trasduttore a pinza HT4006
Per forma d’onda non sinusoidale l’incertezza è: ± (10.0%lettura + 10 cifre)
Protezione da sovraccarichi: 1000A DC/AC rms

#### Corrente AC TRMS, AC+DC TRMS con trasduttori a pinza standard

| Campo    | Rapporto di uscita | Risoluzione | Incertezza (50-60Hz) (*)  |
| :------- | :----------------- | :---------- | :------------------------ |
| 1000mA   | 1V/1mA             | 1mA         | ± (0.8%lettura + 5 cifre) |
| 10A      | 100mV/1A           | 0.01A       |                           |
| 40A (**) | 10mV/1A            | 0.01A       | ± (1.8%lettura + 5 cifre) |
| 100A     | 10mV/1A            | 0.1A        | ± (0.8%lettura + 5 cifre) |
| 400A (**) | 1mV/1A             | 0.1A        | ± (1.8%lettura + 5 cifre) |
| 1000A    | 1mV/1A             | 1A          | ± (0.8%lettura + 5 cifre) |

(*) Incertezza riferita al solo strumento senza trasduttore (**) Con trasduttore a pinza HT4006
Incertezza per campo frequenza 61Hz ÷1kHz: ± (2.4%lettura + 5 cifre)
Campo frequenza: 50Hz ÷ 1kHz: Protezione da sovraccarichi: 1000A DC/AC rms

#### Corrente AC TRMS con trasduttore a pinza flessibile (F3000U)

| Campo    | Rapporto di uscita | Risoluzione | Incertezza (*)            |
| :------- | :----------------- | :---------- | :------------------------ |
| 30A      | 100mV/1A           | 0.01A       | ± (3.0%lettura + 5 cifre) |
| 300A     | 10mV/1A            | 0.1A        |                           |
| 3000A    | 1mV/1A             | 1A          |                           |

(*) Incertezza riferita al solo strumento senza trasduttore
Incertezza specificata dal 5% al 100% del campo di misura; Campo frequenza: 50Hz ÷ 400Hz
Incertezza funzione PEAK: ±(10%lettura + 20 cifre), Tempo di risposta funzione PEAK: 1ms
Protezione da sovraccarichi: 1000A DC/AC rms

#### Resistenza e Test Continuità

| Campo       | Risoluzione | Incertezza                | Buzzer |
| :---------- | :---------- | :------------------------ | :----- |
| 600.0      | 0.1        | ± (1.0%lettura + 10 cifre) | ≤ 50  |
| 6.000k     | 0.001k     | ± (0.8%lettura + 5 cifre) |        |
| 60.00k     | 0.01k      |                           |        |
| 600.0k     | 0.1k       |                           |        |
| 6.000M     | 0.001M     |                           |        |
| 60.00M     | 0.01M      | ± (2.5%lettura + 10 cifre) |        |

Protezione da sovraccarichi: 1000V DC/AC rms

#### Prova Diodi

| Funzione | Corrente di prova | Tensione a vuoto |
| :------- | :---------------- | :--------------- |
|          | < 1.5mA           | 3.3VDC           |

#### Frequenza (circuiti elettrici)

| Campo            | Risoluzione       | Incertezza      |
| :--------------- | :---------------- | :-------------- |
| 40.00Hz  10kHz | 0.01Hz  0.001kHz | ± (0.5%lettura) |

Protezione da sovraccarichi: 1000V DC/AC rms; Sensibilità: ± 2 Vrms

---

#### Frequenza (circuiti elettronici)

| Campo       | Risoluzione | Incertezza                  |
| :---------- | :---------- | :-------------------------- |
| 60.00Hz     | 0.01Hz      | ± (0.2%lettura + 5 cifre)   |
| 600.0Hz     | 0.1Hz       |                             |
| 6.000kHz    | 0.001kHz    |                             |
| 60.00kHz    | 0.01kHz     |                             |
| 600.0kHz    | 0.1kHz      |                             |
| 6.000MHz    | 0.001MHz    |                             |
| 10.00MHz    | 0.01MHz     |                             |

Protezione da sovraccarichi: 1000ADC/ACrms; Sensibilità: > 2Vrms (@ 20%  80% duty cycle) e f<100kHz; > 5Vrms (@ 20%  80% duty cycle) e f>100kHz

#### Duty Cycle (ciclo di lavoro)

| Campo          | Risoluzione | Incertezza                |
| :------------- | :---------- | :------------------------ |
| 10.0%  90.0% | 0.1%        | ± (1.2%lettura + 8 cifre) |

Campo frequenza impulso: 40Hz  10kHz, Ampiezza impulso: ±5V (100µs  100ms)

#### Capacità

| Campo        | Risoluzione | Incertezza                |
| :----------- | :---------- | :------------------------ |
| 60.00nF      | 0.01nF      | ± (3.0%lettura + 20 cifre) |
| 600.0nF      | 0.1nF       | ± (3.0%lettura + 8 cifre) |
| 6.000µF      | 0.001µF     |                           |
| 60.00µF      | 0.01µF      |                           |
| 600.0µF      | 0.1µF       |                           |
| 6000µF       | 1µF         | ± (3.5%lettura + 20 cifre) |
| 60.00mF      | 0.01mF      | ± (5.0%lettura + 40 cifre) |
| 100.0mF      | 0.1mF       |                           |

Protezione da sovraccarichi: 1000ADC/ACrms

#### Temperatura con sonda K (Autorange)

| Campo                | Risoluzione | Incertezza (*)          |
| :------------------- | :---------- | :---------------------- |
| -40.0°C ÷ 600.0°C    | 0.1°C       | ± (1.5%lettura + 3°C)   |
| 601°C ÷ 1000°C       | 1°C         |                         |
| -40.0°F ÷ 600.0°F    | 0.1°F       | ± (1.5%lettura+ 5.4°F)  |
| 601°F ÷ 1800°F       | 1°F         |                         |
| 245.0K ÷ 600.0K      | 0.1K        | ± (1.5%lettura+ 3K)     |
| 601K ÷ 1273K         | 1K          |                         |

(*) Incertezza strumento senza sonda specificata con temperatura ambiente stabile a ±1°C
Protezione da sovraccarichi: 1000ADC/ACrms

#### Temperatura a infrarossi (HT9025T)

*   **Tipo sensore IR**: UFPA (120 x 120 pxl, 17µm)
*   **Risposta spettrale**: 8  14µm
*   **Campo visivo (FOV) / Lente**: 15.6° x 15.6° / 7.5mm
*   **IFOV**: 2.26mrad
*   **Sensibilità termica / NETD**: <0.1°C (@30°C /86°F) / 100mK
*   **Focalizzazione**: Automatica
*   **Distanza focale minima**: 0.5m
*   **Frequenza immagine**: 50Hz
*   **Letture temperatura**: °C,°F, K
*   **Tavolozze colori disponibili**: 5
*   **Puntatore laser**: classe 2 in accordo a IEC 60825-1
*   **Illuminatore integrato**: LED luce bianca
*   **Correzione emissività**: 0.01 ÷ 1.00 in passi da 0.01
*   **Cursoridi misura**: 3 (Fisso, Max Temp., Min Temp.)
*   **Campo misura**: -20°C ÷ 260°C (-4°F ÷ 500°F)
*   **Incertezza**: ± 3%lettura oppure ± 3°C (± 5.4°F) (temperatura ambiente 10°C ÷ 35°C, temperatura oggetto >0°C)

---

## 7.2. CARATTERISTICHE GENERALI

#### Normative di riferimento

*   **Sicurezza**: IEC/EN61010-1
*   **EMC**: IEC/EN61326-1
*   **Isolamento**: doppio isolamento
*   **Grado di inquinamento**: 2
*   **Categoria di misura**: CAT IV 600V, CAT III 1000V, CAT II 1500V DC

#### Display

*   **Tipo display**: colori TFT, 6000 punti con bargraph
*   **Velocità aggiornamento**: 3 misure al secondo
*   **Tipo di conversione**: TRMS

#### Alimentazione

*   **Tipo batteria**: 7.4V batteria Li-ION, 1200mAh
*   **Alimentatore caricabatteria**: 100/240VAC, 50/60Hz, 12VDC, 2A
*   **Indicazione batteria scarica**: simbolo “<battery_low_symbol>” a display
*   **Tempo di ricarica**: circa 2 ore
*   **Autonomia batteria**: circa 8 ore (Bluetooth non attivo), circa 7 ore (Bluetooth attivo)
*   **Autospegnimento**: dopo 15  60 min di non utilizzo

#### Caratteristiche meccaniche

*   **Dimensioni (L x La x H)**: 280 x 100 x 50 mm
*   **Peso (batteria inclusa)**: 505g
*   **Max diametro cavo pinzabile**: 40mm
*   **Protezione meccanica**: IP40

#### Memoria interna, funzione logger e collegamento dispositivi mobili

*   **Snapshots salvabili**: max 128 (formato BMP)
*   **Intervallo di campionamento (IC)**: 1s÷15min selezionabile
*   **Registrazioni salvabili**: max 16 (o 34 ore) @IC=1s
*   **Durata singola registrazione**: max 10ore
*   **Collegamento Bluetooth**: tipo BLE 4.0
*   **Dispositivi mobili compatibili**: Android 4.4 o superiore, iPhone 4 o superiore

#### Condizioni ambientali di utilizzo

*   **Temperatura di riferimento**: 18°C  28°C
*   **Temperatura di utilizzo**: 5°C ÷ 40°C
*   **Umidità relativa ammessa**: <80%RH
*   **Temperatura di conservazione**: -20°C ÷ 60°C
*   **Umidità di conservazione**: <80%RH
*   **Max altitudine di utilizzo**: 2000m

Questo strumento è conforme ai requisiti della Direttiva Europea sulla bassa tensione 2014/35/EU (LVD), della direttiva EMC 2014/30/EU e della direttiva RED 2014/53/EU.
Questo strumento è conforme ai requisiti della direttiva europea 2011/65/EU (RoHS) e della direttiva europea 2012/19/EU (WEEE).

---

## 7.3. ACCESSORI

### 7.3.1. Accessori in dotazione

*   Coppia di puntali con punta 2/4mm (Cod. 4324-2)
*   Sonda a filo tipo K (Cod. TK101)
*   Adattatore per collegamento sonda K (Cod. T10)
*   Batteria ricaricabile Li-ION (HT9025) (Cod. BAT64)
*   Batteria ricaricabile Li-ION, 2 pezzi (HT9025T) (Cod. BAT64)
*   Alimentatore multiplug + base di ricarica (Cod. A0EC95)
*   Borsa per trasporto (Cod. B0EC95)
*   Rapporto di taratura ISO
*   Manuale d’uso

### 7.3.2. Accessori opzionali

*   Sonda tipo K per temperatura di aria e gas (Cod. TK107)
*   Sonda tipo K per temperatura di sostanze semisolide (Cod. TK108)
*   Sonda tipo K per temperatura di liquidi (Cod. TK109)
*   Sonda tipo K per temperatura di superfici (Cod. TK110)
*   Sonda tipo K temperatura di superfici con punta a 90° (Cod. TK111)
*   Trasduttore a pinza standard DC/AC 40-400A (Cod. HT4006)
*   Trasduttore a pinza flessibile AC 30/300/3000A (Cod. F3000U)
*   Trasduttore a pinza standard AC 1-100-1000A (con. HT) (Cod. HT96U)
*   Trasduttore pinza standard AC 10-100-1000A (con. HT) (Cod. HT97U)
*   Trasduttore a pinza standard DC 1000A (con. HT) (Cod. HT98U)
*   Adattatore per pinze standard con connettore HT (Cod. NOCANBA)

---

# 8. ASSISTENZA

## 8.1. CONDIZIONI DI GARANZIA

Questo strumento è garantito contro ogni difetto di materiale e fabbricazione, in conformità con le condizioni generali di vendita. Durante il periodo di garanzia, le parti difettose possono essere sostituite, ma il costruttore si riserva il diritto di riparare ovvero sostituire il prodotto. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballo originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente. Il costruttore declina ogni responsabilità per danni causati a persone o oggetti.

La garanzia non è applicata nei seguenti casi:

*   Riparazione e/o sostituzione accessori e batterie (non coperti da garanzia).
*   Riparazioni che si rendono necessarie a causa di un errato utilizzo dello strumento o del suo utilizzo con apparecchiature non compatibili.
*   Riparazioni che si rendono necessarie a causa di un imballaggio non adeguato.
*   Riparazioni che si rendono necessarie a causa di interventi eseguiti da personale non autorizzato.
*   Modifiche apportate allo strumento senza esplicita autorizzazione del costruttore.
*   Utilizzo non contemplato nelle specifiche dello strumento o nel manuale d’uso.

Il contenuto del presente manuale non può essere riprodotto in alcuna forma senza l’autorizzazione del costruttore.
I nostri prodotti sono brevettati e i marchi depositati. Il costruttore si riserva il diritto di apportare modifiche alle specifiche ed ai prezzi se ciò è dovuto a miglioramenti tecnologici.

## 8.2. ASSISTENZA

Se lo strumento non funziona correttamente, prima di contattare il Servizio di Assistenza, controllare lo stato delle batterie e dei cavi e sostituirli se necessario. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballaggio originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente.