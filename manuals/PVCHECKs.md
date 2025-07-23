# PVCHECKs

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-23 -->
© Copyright HT ITALIA 2025 Versione IT 3.02 - 14/05/2025
**PVCHECKs** Manuale d'uso

**PVCHECKs** IT - 1

# INDICE

1.  PRECAUZIONI E MISURE DI SICUREZZA
    1.1. Istruzioni preliminari
    1.2. Durante l’utilizzo
    1.3. Dopo l’utilizzo
    1.4. Definizione di categoria di misura (sovratensione)
2.  DESCRIZIONE GENERALE
    2.1. Introduzione
    2.2. Funzionalità dello strumento
3.  PREPARAZIONE ALL’UTILIZZO
    3.1. Controlli iniziali
    3.2. Alimentazione dello strumento
    3.3. Conservazione
4.  NOMENCLATURA
    4.1. Descrizione dello strumento
    4.2. Descrizione della tastiera
    4.3. Descrizione del display
    4.4. Videata iniziale
5.  MENU GENERALE
    5.1. SET – impostazione dello strumento
        5.1.1. Generali
        5.1.2. Unità di misura
        5.1.3. Data e ora
        5.1.4. Unità Remota/Solarimetro
        5.1.5. Irraggiamento
        5.1.6. Pinza DC
    5.2. EFF – Impostazioni test Efficienza impianti FV
        5.2.1. Impostazione strumento
        5.2.2. Parametri impianto
        5.2.3. Selezione della relazione di compensazione degli effetti della Temperatura
    5.3. LOW  – Impostazioni test continuità con 200mA
        5.3.1. Impostazione strumento
    5.4. M  – Impostazioni misura di isolamento
        5.4.1. Impostazione strumento
    5.5. IVCK – Impostazioni test rapido IVCK
        5.5.1. Impostazione strumento
    5.6. DB – Gestione database moduli
        5.6.1. Definizione di un nuovo modulo FV
        5.6.2. Modifica di un modulo FV esistente
        5.6.3. Cancellazione di un modulo FV esistente
6.  ISTRUZIONI OPERATIVE
    6.1. Misura Efficienza impianti FV con uso di unita’ remota SOLAR - 02
    6.2. Misura parametri impianto FV senza uso di SOLAR - 02
    6.3. Test rapido su moduli e stringhe FV (IVCK)
        6.3.1. Introduzione
        6.3.2. Esecuzione test rapido IVCK senza misura di Irraggiamento
        6.3.3. Esecuzione test rapido IVCK con misura di Irraggiamento
        6.3.4. Reset Medie
            6.3.4.1. Situazioni anomale test IVCK
    6.4. Misura di Isolamento su moduli/stringhe/campi FV (M  )
        6.4.1. Introduzione
        6.4.2. Esecuzione misura di isolamento – Modo CAMPO
        6.4.3. Esecuzione misura di isolamento – Modo TIMER
        6.4.4. Esecuzione misura di isolamento – Modo STRINGA
            6.4.4.1. Situazioni anomale
    6.5. Misura di Continuità su moduli/stringhe/campi FV (LOW  )
        6.5.1. Introduzione
        6.5.2. Calibrazione cavi di misura

**PVCHECKs** IT - 2

    6.5.3. Esecuzione misura di continuità
        6.5.3.1. Situazioni anomale
    6.6. Elenco dei messaggi a display
7.  MEMORIZZAZIONE RISULTATI
    7.1. Salvataggio delle misure di Efficienza
    7.2. Salvataggio delle misure di IVCK, M  e LOW 
    7.3. Operazioni con risultati
        7.3.1. Richiamo a display dei risultati di efficienza FV
        7.3.2. Richiamo a display dei risultati di misura IVCK, M  e LOW 
            7.3.2.1. Accesso ai dati salvati in memoria – Visualizzazione numerica
        7.3.3. Cancellazione dei dati in memoria
8.  COLLEGAMENTO DELLO STRUMENTO A PC
9.  MANUTENZIONE
    9.1. Generalità
    9.2. Sostituzione batterie
    9.3. Pulizia dello strumento
    9.4. Fine vita
10. SPECIFICHE TECNICHE
    10.1. Caratteristiche tecniche efficienza installazioni FV
    10.2. Caratteristiche tecniche funzione IVCK
    10.3. Caratteristiche tecniche sicurezza elettrica
    10.4. Normative di riferimento
        10.4.1. Generali
    10.5. Caratteristiche generali
    10.6. Condizioni ambientali di utilizzo
    10.7. Accessori
11. APPENDICE – CENNI TEORICI
    11.1. Test di Efficienza impianti FV
12. ASSISTENZA
    12.1. Condizioni di garanzia
    12.2. Assistenza

**PVCHECKs** IT - 3

# 1. PRECAUZIONI E MISURE DI SICUREZZA

Lo strumento è stato progettato in conformità alla direttiva IEC/EN61010-1 relativa agli strumenti di misura elettronici. Prima e durante l’esecuzione delle misure attenersi alle seguenti indicazioni e leggere con particolare attenzione tutte le note precedute dal simbolo `•`.

*   Non effettuare misure di tensione o corrente in ambienti umidi
*   Non effettuare misure in presenza di gas o materiali esplosivi, combustibili o in ambienti polverosi
*   Evitare contatti con il circuito in esame se non si stanno effettuando misure
*   Evitare contatti con parti metalliche esposte, con terminali di misura inutilizzati, ecc ..
*   Non effettuare alcuna misura qualora si riscontrino anomalie nello strumento come, deformazioni, rotture, assenza di visualizzazione sul display, ecc..
*   Prestare particolare attenzione quando si effettuano misure di tensioni superiori a 25V in ambienti particolari e 50V in ambienti ordinari in quanto si è in presenza di rischio di shock elettrici

Nel presente manuale e sullo strumento sono utilizzati i seguenti simboli:

> **ATTENZIONE**: attenersi alle istruzioni riportate nel manuale; un uso improprio potrebbe causare danni allo strumento o ai suoi componenti

**Pericolo alta tensione**: rischi di shock elettrici
**Doppio isolamento**
**Tensione o corrente DC**
**Riferimento di terra**

## 1.1. ISTRUZIONI PRELIMINARI

*   Questo strumento è stato progettato per l’utilizzo in condizioni ambientali specificate al § 10.6. Non operare in condizioni ambientali differenti
*   Lo strumento può essere utilizzato per misure di **TENSIONE** e **CORRENTE** in CAT III 300V DC con tensione massima 1000V DC tra gli ingressi. Non operare su circuiti che superino i limiti specificati al § 10.1, § 10.2 e § 10.3

> **ATTENZIONE**
> Non utilizzare lo strumento per test IVCK su moduli FV con efficienza >19%. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento

*   La invitiamo a seguire le normali regole di sicurezza orientate alla protezione contro correnti pericolose e proteggere lo strumento contro un utilizzo errato
*   Solo gli accessori forniti a corredo dello strumento garantiscono gli standard di sicurezza. Essi devono essere in buone condizioni e sostituiti, se necessario, con modelli identici
*   Controllare che le batterie siano inserite correttamente
*   Prima di collegare i cavi di misura al circuito in esame, controllare che sia stata selezionata la funzione desiderata

**PVCHECKs** IT - 4

## 1.2. DURANTE L’UTILIZZO

La preghiamo di leggere attentamente le raccomandazioni e le istruzioni seguenti:

> **ATTENZIONE**
> *   La mancata osservazione delle avvertenze e/o istruzioni può danneggiare lo strumento e/o i suoi componenti o essere fonte di pericolo per l’operatore
> *   Il simbolo “ `[Battery full symbol]` ” indica il livello di carica completo delle batterie interne. Quando il livello di carica scende a livelli minimi il simbolo “ `[Battery low symbol]` ” è mostrato a display. In questo caso interrompere le prove e procedere alla sostituzione delle batterie in accordo a quanto descritto nel § 9.2
> *   Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie

## 1.3. DOPO L’UTILIZZO

Quando le misure sono terminate, spegnere lo strumento mantenendo premuto il tasto `ON/OFF` per alcuni secondi. Se si prevede di non utilizzare lo strumento per un lungo periodo rimuovere le batterie ed attenersi a quanto specificato nel § 3.3.

## 1.4. DEFINIZIONE DI CATEGORIA DI MISURA (SOVRATENSIONE)

La norma "IEC/EN 61010-1: Prescrizioni di sicurezza per apparecchi elettrici di misura, controllo e per utilizzo in laboratorio, Parte 1: Prescrizioni generali", definisce cosa si intenda per categoria di misura, comunemente chiamata categoria di sovratensione. Al § 6.7.4: Circuiti di misura, essa recita:

I circuiti sono suddivisi nelle seguenti categorie di misura:

*   La **Categoria di misura IV** serve per le misure effettuate su una sorgente di un’installazione a bassa tensione
    Esempi sono costituiti da contatori elettrici e da misure sui dispositivi primari di protezione dalle sovracorrenti e sulle unità di regolazione dell’ondulazione
*   La **Categoria di misura III** serve per le misure effettuate in installazioni all’interno di edifici
    Esempi sono costituiti da misure su pannelli di distribuzione, disgiuntori, cablaggi, compresi i cavi, le barre, le scatole di giunzione, gli interruttori, le prese di installazioni fisse e gli apparecchi destinati all’impiego industriale e altre apparecchiature, per esempio i motori fissi con collegamento ad impianto fisso
*   La **Categoria di misura II** serve per le misure effettuate su circuiti collegati direttamente all’installazione a bassa tensione
    Esempi sono costituiti da misure su apparecchiature per uso domestico, utensili portatili ed apparecchi similari
*   La **Categoria di misura I** serve per le misure effettuate su circuiti non collegati direttamente alla RETE DI DISTRIBUZIONE
    Esempi sono costituiti da misure su non derivati dalla RETE e derivati dalla RETE ma con protezione particolare (interna). In quest’ultimo caso le sollecitazioni da transitori sono variabili, per questo motivo (OMISSIS) si richiede che l’utente conosca la capacità di tenuta ai transitori dell’apparecchiatura

**PVCHECKs** IT - 5

# 2. DESCRIZIONE GENERALE

## 2.1. INTRODUZIONE

Lo strumento è stato progettato per la realizzazione di test rapidi di pre-collaudo (**IVCK**) su moduli/stringhe fotovoltaici (FV) al fine di verificare i parametri dichiarati dal costruttore oltre a eseguire misure di isolamento/continuità su moduli/stringhe/campi FV e valutazione dell’efficienza di un campo FV.
Le misure **IVCK** e isolamento/continuità possono essere svolte sia in modo sequenziale nell’ordine **IVCK → Isolamento → Continuità** oppure essere svolte manualmente in modo separato.

## 2.2. FUNZIONALITÀ DELLO STRUMENTO

Le seguenti caratteristiche sono disponibili:

**Prova di continuità dei conduttori di protezione (LOW )**
*   Test con corrente di prova > 200mA in accordo alla normativa IEC/EN62446-1
*   Calibrazione manuale dei cavi di misura

**Misura di resistenza di isolamento su moduli/stringhe FV (M )**
*   Tensioni di prova 250V, 500V, 1000VDC in accordo alla normativa IEC/EN62446-1
*   3 modalità di misura: Campo, Timer, Stringa
*   Verifica isolamento masse metalliche non collegate a riferimenti di terra

**Valutazione efficienza installazione FV nel breve/medio periodo (EFF)**
*   Misura tensione DC, corrente DC e potenza DC in uscita da moduli/stringhe FV
*   Misura irraggiamento [W/m²] tramite cella di riferimento connessa a unità remota opzionale SOLAR-02
*   Misura temperatura moduli e ambiente tramite sonda connessa a unità remota opzionale SOLAR-02
*   Applicazione delle relazioni di compensazione dell’Efficienza DC
*   Valutazione immediata efficienza DC in funzione di limiti impostati dall’utente
*   Registrazione parametri di un impianto FV con PI programmabile da 5s a 60min

**Misure rapide di pre-collaudo (IVCK) in accordo alla normativa IEC/EN62446**
*   Misura di tensione a vuoto Voc su moduli/stringhe FV fino a 1000VDC
*   Misura di corrente di cortocircuito Isc su moduli/stringhe FV fino a 15A
*   Misura irraggiamento con uso di cella di riferimento opzionale
*   Valutazione immediata (OK/NO) dei risultati ottenuti
*   Collegamento eventuale dell’unità remota opzionale SOLAR-02
*   Database interno personalizzabile per la gestione fino a 30 moduli FV
*   Visualizzazione risultati in condizioni OPC e STC

Il modello dispone della funzione di retroilluminazione del display, la possibilità di regolazione interna del contrasto e un tasto `HELP` in grado di fornire a display un aiuto all’operatore nella fase di collegamento dello strumento all’impianto. Una funzione di autospegnimento, eventualmente disattivabile, è disponibile dopo circa 5 minuti di non utilizzo dello strumento.

**PVCHECKs** IT - 6

# 3. PREPARAZIONE ALL’UTILIZZO

## 3.1. CONTROLLI INIZIALI

Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili affinché lo strumento potesse essere consegnato senza danni. Tuttavia si consiglia di controllarlo per accertare eventuali danni subiti durante il trasporto. Qualora si dovessero riscontrare anomalie contattare immediatamente il rivenditore.
Si consiglia inoltre di controllare che l’imballaggio contenga tutte le parti indicate al § 10.7. In caso di discrepanze contattare il rivenditore. Qualora fosse necessario restituire lo strumento si prega di seguire le istruzioni riportate al § 12.

## 3.2. ALIMENTAZIONE DELLO STRUMENTO

Lo strumento è alimentato a batteria. Per modello ed autonomia delle batterie vedere § 10.5.
Il simbolo “ `[Battery full symbol]` ” indica il livello di carica completo delle batterie interne. Quando il livello di carica scende a livelli minimi il simbolo “ `[Battery low symbol]` ” è mostrato a display. In questo caso interrompere le prove e procedere alla sostituzione delle batterie in accordo a quanto descritto nel § 9.2.
Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie.
Lo strumento dispone di sofisticati algoritmi per aumentare al massimo l'autonomia delle batterie.
Una breve pressione del tasto `[Backlight symbol]` attiva la retroilluminazione del display. Al fine di salvaguardare l’efficienza delle batterie la retroilluminazione si spegne automaticamente dopo circa 30 secondi.
L'utilizzo sistematico della retroilluminazione diminuisce l'autonomia delle batterie.

## 3.3. CONSERVAZIONE

Per garantire misure precise, dopo un lungo periodo di permanenza in magazzino in condizioni ambientali estreme, attendere che lo strumento ritorni alle condizioni normali (vedere § 10.6).

**PVCHECKs** IT - 7

# 4. NOMENCLATURA

## 4.1. DESCRIZIONE DELLO STRUMENTO

**LEGENDA:**

1.  Ingressi
2.  Display
3.  Connettore per uscita ottica/USB
4.  Tasti freccia/ ENTER
5.  Tasto GO/STOP
6.  Tasto SAVE
7.  Tasto ON/OFF
8.  Tasto HELP / `[Backlight symbol]`
9.  Tasto ESC/MENU

*Fig. 1: Descrizione parte frontale dello strumento*

**LEGENDA:**

1.  Ingresso per sonda misura irraggiamento
2.  Ingresso per sonda misura temperatura ausiliaria / pinza per corrente DC (IVCK, EFF)
3.  Ingressi P, N per misura tensione DC (IVCK, EFF) / Isolamento (M)
4.  Ingressi E, C per test continuità (LOW )

*Fig. 2: Descrizione parte superiore dello strumento*

**LEGENDA:**

1.  Connettore per collegamento cavo di uscita optoisolata ottico/USB

*Fig. 3: Descrizione parte laterale dello strumento*

**PVCHECKs** IT - 8

## 4.2. DESCRIZIONE DELLA TASTIERA

La tastiera è costituita dai seguenti tasti:

*   Tasto `ON/OFF` per accendere e spegnere lo strumento
*   Tasto `ESC/MENU` per uscire dalla videata corrente senza confermare le modifiche e per tornare al menu principale
*   Tasti `   ` per spostare il cursore all’interno delle varie schermate allo scopo di selezionare i parametri di programmazione
*   Tasto `ENTER` per confermare le modifiche, i parametri di programmazione selezionati e per selezionare da menu la funzione alla quale accedere
*   Tasto `GO/STOP` per avviare la misurazione
*   Tasto `SAVE` per salvare la misura
*   Tasto `HELP` (pressione prolungata) per accedere all’help on line visualizzando le possibili connessioni tra strumento ed impianto
*   Tasto `[Backlight symbol]` (semplice pressione) per attivare la retroilluminazione del display

## 4.3. DESCRIZIONE DEL DISPLAY

Il display è un modulo grafico con risoluzione 128 x 128 punti.
Nella prima riga del display viene visualizzata la data/ora di sistema e l'indicatore dello stato batterie.
Nella parte bassa è invece indicata la funzionalità del Tasto `ENTER` e la modalità attiva.
Il simbolo `[Radio signal symbol]` indica la presenza di un collegamento radio attivo con l’unità remota SOLAR-02.
Il simbolo `[Flashing radio signal symbol]` intermittente indica la ricerca in corso di un collegamento radio con l’unità remota SOLAR-02.

```
15/05/12   15:34:26
Selezione
```

## 4.4. VIDEATA INIZIALE

All’accensione dello strumento viene visualizzata per qualche secondo la videata iniziale. In essa sono visualizzati:

*   Il modello dello strumento (`PVCHECKs`)
*   Il costruttore
*   Presenza del modulo di comunicazione radio interna abilitato (RF)
*   Il numero di serie dello strumento (SN:)
*   La versione del firmware presente nella memoria dello strumento (FW:)
*   La data in cui è avvenuta l’ultima calibrazione dello strumento (Data calibrazione:)

```
PVCHECKS
HT
RF SN: 15345678
FW: 1.10
Data calibrazione: 09/04/2025
```

Dopo alcuni istanti lo strumento passa all'ultima funzione selezionata.

**PVCHECKs** IT - 9

# 5. MENU GENERALE

La pressione del tasto `ESC/MENU`, in qualunque condizione si trovi lo strumento, provoca la comparsa della videata del menu generale attraverso la quale è possibile impostare lo strumento, visualizzare le misure memorizzate, e selezionare la misurazione desiderata
Selezionando con il cursore una delle opzioni e confermando con `ENTER` si accede alla funzione desiderata

```
15/05/12   15:34:26
IV CK   Test   moduli/stringhe
LOW    Test   continuità   PE
M    Test   isolamento
EFF   Test   efficienza
SET   Impostazioni
DB   Archivio moduli
MEM   Dati   memoria
PC   Trasf.   dati   PC
ENTER   per   selezionare
MENU
```

## 5.1. SET – IMPOSTAZIONE DELLO STRUMENTO

Posizionare il cursore sulla voce `SET` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata che elenca le varie impostazioni dello strumento.
Le impostazioni vengono mantenute anche dopo lo spegnimento dello strumento

```
15/05/12   15:34:26
Generali
Unità di misura
Data e Ora
Unità remota - solarimetro
Irraggiamento
Pinza DC
ENTER   per   selezionare
SET
```

### 5.1.1. Generali

1.  Posizionare il cursore sulla voce `Generali` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`.
2.  A display appare la videata che consente:
    ➢ L’impostazione della lingua dello strumento
    ➢ L’attivazione/disattivazione dell’autospegnimento
    ➢ La regolazione del contrasto del display
    ➢ L’abilitazione della segnalazione acustica in corrispondenza della pressione di un tasto.
3.  Per le impostazioni delle opzioni usare i tasti freccia (``, ``) e scegliere l’opzione desiderata usando i tasti freccia (``, ``).
4.  Premere il tasto `SAVE` per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto `ESC/MENU` per uscire senza salvare e tornare alla videata precedente.

```
15/05/12   15:34:26
Lingua   :  Italiano 
Autospegnimento : NO
Contrasto : : 40
Suono tasti : NO
SAVE   per   salvare
SET
```

**PVCHECKs** IT - 10

### 5.1.2. Unità di misura

Questa sezione permette l’impostazione delle unità di misura di alcuni parametri presenti nella gestione del database (DB) dei moduli FV (vedere § 5.6) nella misura di IVCK.

1.  Posizionare il cursore sulla voce “`Unità di misura`” utilizzando i tasti freccia (``, ``) e confermare con `ENTER`.
2.  A display appare la videata che consente l’impostazione delle unità di misura dei seguenti parametri:
    *   Alpha → selezioni possibili: “%/°C” e “mA/°C”
    *   Beta → selezioni possibili: “%/°C” e “mV/°C”
    *   Gamma → espresso in “%/°C”
    *   Tolleranza Voc e Isc → espresso in “%”
3.  Per l’impostazione delle unità di misura usare i tasti freccia (``, ``).
4.  Premere il tasto `SAVE` per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante.
5.  Premere il tasto `ESC/MENU` per uscire senza salvare e tornare alla videata precedente.

```
15/05/12   15:34:26
Alpha   :  mA/°C 
Beta      : %/°C
Gamma   : %/°C
Tolleranza: %
SAVE   per   salvare
SET
```

### 5.1.3. Data e ora

1.  Posizionare il cursore sulla voce “`Data Ora`” utilizzando i tasti freccia (``, ``) e confermare con `ENTER`.
2.  A display appare la videata che consente l’impostazione della data/ora di sistema sia nel formato Europeo (EU) sia nel formato USA (US).
3.  Per l’impostazione delle unità di misura usare i tasti freccia (``, ``).
4.  Premere il tasto `SAVE` per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto `ESC/MENU` per uscire senza salvare e tornare alla videata precedente.

```
15/05/12   15:34:26
Anno   :  2012 
Mese   : 05
Giorno : 15
Ore    : 09
Minuti : 53
Formato: EU
SAVE   per   salvare
IMPOST
```

**PVCHECKs** IT - 11

### 5.1.4. Unità Remota /Solarimetro

Questa sezione consente di selezionare il tipo di unità remota da utilizzare (se disponibile) ed impostare i valori dei parametri caratteristici (Sensitivity e Alpha) della cella solare di riferimento (accessorio opzionale HT304k). I valori di questi parametri sono riportati sull’etichetta posteriore della cella stessa in funzione del tipo di modulo in prova.

1.  Posizionare il cursore sulla voce `Unità Remota` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`.
2.  A display appare la videata che consente di selezionare l’uso dell’unità remota per test EFF o IVCK. Le opzioni possibili sono:
    ➢ `SI` (uso del SOLAR-02)
    ➢ `NO` (non utilizzo del SOLAR-02). In caso di non utilizzo dell’unità remota SOLAR-02 per test IVCK occorre impostare sullo strumento i valori della Sensitivity (Sens.) e del parametro Alpha della cella di riferimento (accessorio opzionale HT304k).
3.  Per l’impostazione dei valori usare i tasti freccia (``, ``).
4.  Premere il tasto `SAVE` per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto `ESC/MENU` per uscire senza salvare e tornare alla videata precedente.

```
15/05/12   15:34:26
U. Remota EFF :  SI 
U. Remota IV CK: NO
Sens. :  31.0  mV/kW/m2
Alpha : 0.060 %/°C
SAVE   per   salvare
IMPOST
```

**PVCHECKs** IT - 12

### 5.1.5. Irraggiamento

Questa sezione consente l’impostazione della soglia minima di irraggiamento sia per la misura IVCK sia per il test di efficienza di un’installazione FV.

1.  Posizionare il cursore sulla voce “`Irraggiamento`” utilizzando i tasti freccia (``, ``) e confermare con `ENTER`.
2.  A display appare la videata con le voci “`Irr min IV CK`” , che consente l’impostazione della soglia minima di irraggiamento espressa in W/m², utilizzata come riferimento dallo strumento nell’esecuzione della misura IVCK e “`Irr min EFF`” che consente l’impostazione della soglia minima di irraggiamento espressa in W/m², utilizzata come riferimento dallo strumento nell’esecuzione delle misure di efficienza di un’installazione FV. Usare i tasti (``, ``) per passare tra le due voci.
3.  Per l’impostazione della soglia minima di irraggiamento usare i tasti freccia (``, ``). Per ottenere risultati di precisione conforme a quanto indicato nel presente manuale si raccomanda di attenersi alle indicazione del § 10. Il valore è impostabile tra 0  800 W/m².
4.  Premere il tasto `SAVE` per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto `ESC/MENU` per uscire senza salvare e tornare alla videata precedente.

```
15/05/12   15:34:26
Irr. Min IV CK :  300  W/m2
Irr Min EFF :  600  W/m2
SAVE   per   salvare
IMPOST
```

> **ATTENZIONE**
> L’impostazione “0 W/m²” per il parametro “Irr min IV CK” consente l’esecuzione della misura IVCK senza che vengano controllate le seguenti condizioni:
> ➢ Connessione della cella di riferimento all’ingresso IRR dello strumento
> ➢ Valori instabili di irraggiamento
> ➢ Numero moduli coerente con la tensione a vuoto misurata

### 5.1.6. Pinza DC

Questa opzione consente di impostare l’eventuale fattore correttivo K per la pinza DC al fine di migliorare la misura della corrente. Se presente, il fattore correttivo è indicato sull’etichetta posteriore della pinza stessa indicato come:
K= X.xxx
Nel caso non fosse presente nessuna etichetta impostare k = 1.000

1.  Posizionare il cursore sulla voce `Pinza DC` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`.
2.  A display appare la videata “K pinza DC” che consente l’impostazione del fattore correttivo in un intervallo compreso tra 0.950 e 1.050. Per l’impostazione dei valori usare i tasti freccia (``, ``).
3.  Premere il tasto `SAVE` per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto `ESC/MENU` per uscire senza salvare e tornare alla videata precedente.

```
15/05/12   15:34:26
k Pinza DC :  1.000 
SAVE   per   salvare
IMPOST
```

**PVCHECKs** IT - 13

## 5.2. EFF – IMPOSTAZIONI TEST EFFICIENZA IMPIANTI FV

Lo scopo di questa misura è la valutazione dell’efficienza DC di un’installazione fotovoltaica con possibilità di ottenere un esito positivo o negativo del collaudo/registrazione in funzione di un limite sul parametro nDC liberamente impostato dall’utente. Per questo test è necessario l’uso dell’unità remota opzionale SOLAR-02 (vedere § 6.1).

### 5.2.1. Impostazione strumento

1.  Posizionare il cursore sulla voce `EFF` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata che riporta i valori dei parametri elettrici in uscita dal generatore fotovoltaico.

```
15/05/12   15:34:26
Irr     --- W/m2
Pnom    3.500 kW
Tc      --- °C
Te      --- °C
Pdc     0.0 kW
Vdc     0.000 V
Idc     0.0 A
ndc     ---
GO   per   Avviare
Selezione EFF
```

2.  Premere il tasto `ENTER`. Lo strumento mostra le opzioni: `Parametri Impianto` e `Impostazioni Strumento`.
3.  Usare i tasti freccia (``, ``) per selezionare la voce “`Impostazioni Strumento`” e confermare con `ENTER`. Lo strumento mostra la seguente videata:

```
15/05/12   15:34:26
Irr     --- W/m2
Pnom    3.500 kW
Tc      --- °C
Te      --- °C
Pdc     0.0 kW
Vdc     0.000 V
Idc     0.0 A
ndc     ---
Parametri Impianto
Impostazioni Strumento
Selezione EFF
```

4.  Usando i tasti freccia (``, ``) è possibile impostare:
    ➢ Il periodo di integrazione (**PI**) utilizzabile dallo strumento nell’operazione di collaudo dei parametri di un’installazione FV. I valori `5s, 10s, 30s, 60s, 120s, 300s, 600s, 900s, 1800s, 3600s` sono selezionabili.
    ➢ Il FS della pinza DC utilizzata per la misura di corrente DC con valore selezionabile tra `1A  3000A`.
5.  Premere il tasto `SAVE` per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto `ESC/MENU` per uscire senza salvare e tornare alla videata precedente.

```
15/05/12   15:34:26
PI :  5  s
FS Pinza DC : 1000 A
SAVE   per   salvare
EFF
```

**PVCHECKs** IT - 14

### 5.2.2. Parametri impianto

1.  Posizionare il cursore sulla voce `EFF` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata che riporta i valori dei parametri elettrici in uscita dal generatore fotovoltaico.

```
15/05/12   15:34:26
Irr     --- W/m2
Pnom    3.500 kW
Tc      --- °C
Te      --- °C
Pdc     0.0 kW
Vdc     0.000 V
Idc     0.0 A
ndc     ---
GO   per   Avviare
Selezione EFF
```

2.  Premere il tasto `ENTER`. Lo strumento mostra le opzioni: `Parametri Impianto` e `Impostazione Strumento`.
3.  Usare i tasti freccia (``, ``) per selezionare la voce “`Parametri Impianto`” e confermare con `ENTER`. Lo strumento mostra la seguente videata:

```
15/05/12   15:34:26
Irr     --- W/m2
Pnom    3.500 kW
Tc      --- °C
Te      --- °C
Pdc     0.0 kW
Vdc     0.000 V
Idc     0.0 A
ndc     ---
Parametri Impianto
Impostazioni Strumento
Selezione EFF
```

4.  Usando i tasti freccia (``, ``) è possibile impostare:
    ➢ `Pmax` → potenza nominale massima totale dell’installazione FV espressa in kW
    ➢ `Gamma` → coefficiente di variazione della potenza con la temperatura, parametro caratteristico dei moduli FV (campo: `-1.00  -0.01 %/C`)
    ➢ `NOCT` → temperatura nominale di lavoro della cella, parametro caratteristico dei moduli FV (campo: `0°C  100°C`)
    ➢ `Te`, `Tc` → impostazione valori di default delle temperature dell’ambiente (Te) e dei moduli FV (Tc). Questi valori sono considerati dallo strumento solo in assenza di sonda ausiliaria collegata all’unità SOLAR-02 (campo: `Te = 0°C  80°C`; `Tc = 0°C  100°C`)
    ➢ `nDC Lim` → limite minimo di efficienza DC (valore di default: `0.85`; campo: `0.01  1.15`)
    ➢ `Tipo Corr.` → Impostazione della relazione di compensazione sul calcolo della potenza Pdc e della massimizzazione dell’efficienza DC (vedere § 5.2.3)

```
15/05/12   15:34:26
Pmax : :  3.500  kW
Gamma : -0.45 %/°C
NOCT : 45 °C
Te : 40 °C
Tc : 45 °C
nDC Lim : : 0.85
Tipo. Corr. : T. Env.
SAVE   per   salvare
EFF
```

**PVCHECKs** IT - 15

### 5.2.3. Selezione della relazione di compensazione degli effetti della Temperatura

Questa opzione consente di selezionare la relazione da utilizzare per effettuare delle correzioni alle misure effettuate in funzione della temperatura dei moduli nell’ambito del calcolo dell’efficienza nDC. Sono disponibili le seguenti modalità:

*   **T. Mod.**: Calcolo del termine Rfv2 in funzione della Temp. moduli in accordo a Guida CEI-82-25
*   **T. Env**: Calcolo del termine Rfv2 in funzione della Temp. ambiente in accordo a Guida CEI-82-25
*   **nDC**: Correzione nDC tramite Temperatura moduli

> **ATTENZIONE**
> *   Nell’ambito di verifiche di sistemi FV in accordo a quanto prescritto dalla guida CEI 82-25, è consigliabile adottare la relazione “T. Env.”, in quanto la temperatura dei moduli FV, calcolata utilizzando la relazione del NOCT, risulta tipicamente superiore a quella che si può misurare sul retro dei moduli stessi
> *   La relazione “nDC” non è contemplata dalla guida CEI 82-25 pertanto la sua selezione comporta la mancata indicazione dell’esito finale di un collaudo FV da parte dello strumento

| Tipo Corr. | Temperatura utilizzata (Tcel) | Calcolo di nDC                                                                | Rif.         |
| :--------- | :----------------------------- | :---------------------------------------------------------------------------- | :----------- |
| T. Mod.    | Tm oduli_Mi Tcel =             |                                                                               | CEI 82-25    |
|            |                                | ![Formula 1](https://latex.codecogs.com/png.image?%5Clarge%20R_{fv2}%20=%20%5Cbegin%7Bcases%7D%201%20-%20%5Cgamma%20%5Ccdot%20%28T_{cel}%20-%2040%29%20%26%20%5Ctext%7Bse%7D%20T_{cel}%20%5Cleq%2040%5E%5Ccir%20C%20%5C%5C%201%20-%20%5Cgamma%20%5Ccdot%20%5Cfrac%7BT_{cel}%20-%2040%7D%7B100%7D%20%26%20%5Ctext%7Bse%7D%20T_{cel}%20%3E%2040%5E%5Ccir%20C%20%5Cend%7Bcases%7D%5C%5C%20n_{DC}%20=%20%5Cfrac%7BP_{dc}%7D%7BP_{nSTC}%7D%20%5Ccdot%20%5Cfrac%7BG_{STC}%7D%7BG_p%7D%20%5Ccdot%20R_{fv2}) |              |
| T. Env.    | Tm oduli_Mi Tcel =             | ![Formula 2](https://latex.codecogs.com/png.image?%5Clarge%20T_{cel}%20=%20T_{amb}%20%2B%20%28NOCT%20-%2020%29%20%5Ccdot%20%5Cfrac%7BIrr%7D%7B800%7D%5C%5C%20n_{DC}%20=%20%5Cfrac%7BP_{dc}%7D%7BP_{nSTC}%7D%20%5Ccdot%20%5Cfrac%7BG_{STC}%7D%7BG_p%7D%20%5Ccdot%20R_{fv2}) | CEI 82-25    |
| nDC        | Tm oduli_Mi Tcel =             | ![Formula 3](https://latex.codecogs.com/png.image?%5Clarge%20n_{DC}%20=%20n_{STC}%20%5Ccdot%20P_{p}%20%5Cleft%5B1%20%2B%20%5Cgamma%20%5Ccdot%20%28T_{cel}%20-%2025%29%20%5Cright%5D%20%5Ccdot%20%5Cfrac%7BG_p%7D%7BG_{STC}%7D) | -            |

dove:

| Simbolo  | Descrizione                                                                                         | Unità di misura |
| :------- | :-------------------------------------------------------------------------------------------------- | :-------------- |
| Gp       | Irraggiamento misurato sul piano dei moduli                                                         | [W/m²]          |
| GSTC     | Irraggiamento in condizione Standard = 1000                                                         | [W/m²]          |
| Pn       | Potenza nominale = somma delle Pmax dei moduli FV facenti parte della sezione dell’impianto in esame | [kW]            |
| Pdc      | Potenza DC misurata in uscita dal generatore FV                                                     | [kW]            |
| Rfv2     | Coefficiente correttivo funzione della Temperatura delle Celle FV (Tcel) misurata o calcolata in accordo al tipo di relazione di correzione selezionata |                 |
|         | Valore assoluto del coefficiente termico della Pmax dei moduli FV facenti parte della sezione impianto in esame. | [%/°C]          |
| NOCT     | (Normal Operating Cell Temperature) = Temperatura a cui si portano le celle in condizioni di riferimento (800W/m², 20°C, AM=1.5, vel. Aria =1m/s). | [%/°C]          |

Per ulteriori dettagli vedere il § 11.1.

**PVCHECKs** IT - 16

## 5.3. LOW  – IMPOSTAZIONI TEST CONTINUITÀ CON 200MA

Lo scopo di questa misura è l’esecuzione del test di continuità dei conduttori di protezione ed equipotenziali (ex: dal dispersore fino alle masse e masse estranee collegate) e dei conduttori di messa a terra degli SPD sulle installazioni FV. Il test deve essere condotto usando una corrente di prova > 200mA in accordo alle prescrizioni della Guida CEI 82-25 e delle normative IEC/EN62446-1 e IEC60364.

### 5.3.1. Impostazione strumento

1.  Posizionare il cursore sulla voce `LOW ` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata seguente:

```
15/05/12   15:34:26
R PE max   1 
Rcal      --- 
Rpe       --- 
Itest     --- mA
Selezione LOW 
```

2.  Premere il tasto `ENTER`. Lo strumento mostra le opzioni: `Impostazioni` e `Calibrazione cavi`.
3.  Usare i tasti freccia (``, ``) per selezionare la voce “`Impostazioni`” e confermare con `ENTER`. Lo strumento mostra la seguente videata:

```
15/05/12   15:34:26
R PE max   1 
Rcal      --- 
Rpe       --- 
Itest     --- mA
Calibrazione cavi
Impostazioni
Selezione LOW 
```

4.  Usando i tasti freccia (``, ``) è possibile impostare il valore limite massimo della resistenza Rpe che lo strumento usa come riferimento durante la misura (campo: `1   5 `).
5.  Premere il tasto `SAVE` per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto `ESC/MENU` per uscire senza salvare e tornare alla videata precedente.

```
15/05/12   15:34:26
R PE max :  01  
SAVE   per   salvare
Selezione LOW 
```

> **ATTENZIONE**
> Le impostazioni salvate sulla RPE max hanno effetto anche sulle impostazioni della prova di Continuità contenuta nella misura IVCK (MENU → IVCK).

**PVCHECKs** IT - 17

## 5.4. M  – IMPOSTAZIONI MISURA DI ISOLAMENTO

### 5.4.1. Impostazione strumento

1.  Posizionare il cursore sulla voce `M ` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata seguente:

```
15/05/12   15:34:26
Test Iso   1000 V
R i min    1.0 M 
Modo   Campo
Vtest     --- V   --- V
Ri(+)     --- M 
Ri(-)     --- M 
Rp        --- M 
Selezione M  
```

2.  Premere il tasto `ENTER`. Lo strumento mostra l’opzione: `Impostazioni`.
3.  Confermare con `ENTER`. Lo strumento mostra la seguente videata:

```
15/05/12   15:34:26
Test Iso   1000 V
R i min    1.0 M 
Modo   Campo
Vtest     --- V   --- V
Ri(+)     --- M 
Ri(-)     --- M 
Rp        --- M 
Impostazioni
Selezione M  
```

4.  Per le impostazioni delle opzioni usare i tasti freccia (``, ``) e scegliere l’opzione desiderata usando i tasti freccia (``, ``). I parametri impostabili sono i seguenti:
    ➢ `Test Iso` → tensione di prova: `250, 500, 1000VDC`
    ➢ `Modo` → modi di funzionamento: `Campo`, `Timer`, `Stringa`
    ➢ `Ri Lim` → valore limite minimo della resistenza di isolamento
    ➢ `Tempo di prova` → valore massimo del tempo di prova (solo per modo TIMER) (campo: `10s  300s` in passi da 1s)
5.  Premere il tasto `SAVE` per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto `ESC/MENU` per uscire senza salvare e tornare alla videata precedente.

```
15/05/12   15:34:26
Test Iso :  1000  V
R i min : 1.0 M 
Modo : TIMER
Tempo di prova : 10s
SAVE   per   salvare
M 
```

> **ATTENZIONE**
> Le impostazioni salvate sulla tensione di prova hanno effetto anche sulle impostazioni della misura di isolamento contenuta nella misura IVCK (MENU → IVCK).

**PVCHECKs** IT - 18

## 5.5. IVCK – IMPOSTAZIONI TEST RAPIDO IVCK

Lo scopo di questa misura è la verifica della funzionalità dei collegamenti e delle stringhe di un campo fotovoltaico in accordo a quanto previsto dalla IEC/EN62446 misurando la tensione a vuoto e la corrente di corto-circuito alle condizioni operative e riferite a STC (tramite la misura opzionale di Irraggiamento) e fornendo un esito immediato inerente la misura appena effettuata sia in termini assoluti che per comparazione con le stringhe precedentemente testate. Il test consente anche l’esecuzione (se selezionate) in sequenza della prova di continuità e della misura di isolamento.

### 5.5.1. Impostazione strumento

1.  Posizionare il cursore sulla voce `IVCK` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata seguente:

```
15/05/12   15:34:26
Modulo   SUNPWR318
Vdc      0.0 V
Irr      0 W/m2
Tc       Auto °C
Voc, Isc:
R i (1000V)   --- M 
Rpe (No Cal)  --- 
Selezione IVCK
```

2.  Premere il tasto `ENTER`. Lo strumento mostra le opzioni: `Impostazioni`, `Reset Medi` (vedere § 6.3.4) e `Calibrazione cavi` (vedere § 6.5.2).
3.  Usare i tasti freccia (``, ``) per selezionare la voce “`Impostazioni`” e confermare con `ENTER`. Lo strumento mostra la seguente videata:

```
15/05/12   15:34:26
Modulo   SUNPWR318
Vdc      0.0 V
Irr      0 W/m2
Tc       Auto °C
Voc, Isc:
R i (1000V)   --- M 
Rpe (Cal)     --- 
Calibrazione cavi
Reset Medie
Impostazioni
Selezione IVCK
```

4.  Per le impostazioni delle opzioni usare i tasti freccia (``, ``) e scegliere l’opzione con i tasti freccia (``, ``). I parametri impostabili sono i seguenti:
    ➢ `Modulo` → tipo di modulo in prova
    ➢ `N. Mod. x Str.` → numero di moduli della stringa. Valori ammessi `1  50`
    ➢ `Temp` → metodo di misura della temperatura. Opzioni selezionabili:
        “`Auto`” → misura automatica (**raccomandata**) eseguita in funzione del valore misurato della Voc dei moduli

```
15/05/12   15:34:26
Modulo :  SUNPWR 210 
N. Mod x Str : 01
Temp : Manuale
25 °C
Toll. Voc : 05% (+4%)
Toll. Isc : 05% (+4%)
Test Iso : 1000 V
R i min : 1.0 M 
Test R PE : 2 
SAVE   per   salvare
IVCK
```

**PVCHECKs** IT - 19

    “`Manuale`” → inserimento da parte dell’operatore del valore noto della temperatura del modulo nella riga sottostante
    “`Aux`” → misura della temperatura con sonda ausiliaria PT300N
    ➢ `Toll. Voc (%)` → valore percentuale della tolleranza limite desiderata (impostata dall’operatore in funzione delle proprie esigenze) per la misura di Voc eseguita dallo strumento. Valori ammessi: `0%  25%`. Il valore tra parentesi (`4%`) indica l’errore di lettura dello strumento nella misura di Voc
    ➢ `Toll. Isc (%)` → valore percentuale della tolleranza limite desiderata (impostata dall’operatore in funzione delle proprie esigenze) per la misura di Isc eseguita dallo strumento. Valori ammessi: `0%  25%`. Il valore tra parentesi (`4%`) indica l’errore di lettura dello strumento nella misura di Isc
    ➢ `Test Iso` → abilitazione/disabilitazione della misura di isolamento e impostazione della tensione di prova. Opzioni possibili: `OFF`, `250V`, `500V`, `1000V`. Con funzione abilitata appare la riga “Ri min” che consente l’impostazione della soglia limite minima nel range `0.1  100M `
    ➢ `Test R PE` → abilitazione/disabilitazione del test di continuità e impostazione valore di soglia limite sulla misura. Opzioni possibili `OFF, 1   5 ` in passi da 1 
5.  Premere il tasto `SAVE` per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto `ESC/MENU` per uscire senza salvare e tornare alla videata precedente.

> **ATTENZIONE**
> Le impostazioni salvate sulla tensione di prova della misura di isolamento svolta all’interno della funzione IVCK hanno effetto anche sulle impostazioni della singola misura (MENU → M).

**PVCHECKs** IT - 20

## 5.6. DB – GESTIONE DATABASE MODULI

Lo strumento permette la gestione fino ad un massimo di 30 tipologie di moduli FV oltre ad un modulo di DEFAULT (non modificabile né cancellabile) che può essere usato come riferimento qualora non si abbiamo informazioni sul tipo di modulo a disposizione.
I parametri, riferiti a 1 modulo, che possono essere impostati nella definizione sono riportati nella Tabella 1 seguente, insieme ai campi di misura, risoluzione e condizioni di validità:

**Tabella 1: Parametri associati ad un modulo FV**

| Simbolo  | Descrizione                                                     | Range                          | Risol.        | Condizioni                                  |
| :------- | :-------------------------------------------------------------- | :----------------------------- | :------------ | :------------------------------------------ |
| Nms      | Numero moduli per stringa                                       | 1  50                         | 1             |                                             |
| Pmax     | Potenza massima nominale del modulo                             | 50  4800 W                    | 1W            | 0.01 <= (V_mpp * I_mpp) / P_max             |
| Voc      | Tensione a vuoto                                                | 15.00  99.99V<br>100.0  320.0V | 0.01V<br>0.1V | Voc >= Vmpp                                 |
| Vmpp     | Tensione nel punto di massima potenza                           | 15.00  99.99V<br>100.0  320.0V | 0.01V<br>0.1V | Voc >= Vmpp                                 |
| Isc      | Corrente di cortocircuito                                       | 0.5  15.00 A                  | 0.01A         | Isc >= Impp                                 |
| Impp     | Corrente nel punto di massima potenza                           | 0.5  15.00 A                  | 0.01A         | Isc >= Impp                                 |
| Toll-    | Tolleranza negativa per la Pmax fornita dal costruttore del modulo | 0%  25.0%                     | 0.1%          | 100*Tol- /Pnom< 25<br>0  99W               |
| Toll+    | Tolleranza positiva per la Pmax fornita dal costruttore del modulo | 0  25%                        | 0.1%          | 100*Tol+ /Pnom< 25<br>0  99W               |
| Alpha    | Coefficiente di temperatura Isc                                 | -0.100  0.100%/°C<br>-15.00  15.00mA/°C | 0.001%/°C<br>0.01mA/°C | 100*Alfa / Isc <= 0.1                       |
| Beta     | Coefficiente di temperatura Voc                                 | -0.99  -0.01%/°C<br>-0.999  -0.001V/°C | 0.01%/°C<br>0.001V/°C | 100*Beta/Voc <= 0.999                       |
| Gamma    | Coefficiente di temperatura Pmax                                | -0.99  -0.01%/°C              | 0.01%/°C      |                                             |
| NOCT     | Temperatura nominale di lavoro della cella                      | 0  100°C                      | 1°C           |                                             |
| Tech.    | Effetti dovuti alla tecnologia del modulo                      | STD (standard), CAP (eff.capacitivi) |               |                                             |
| Rs       | Resistenza serie interna                                        | 0.00  10.00                  | 0.01         |                                             |

> **ATTENZIONE**
> *   La voce “`Tech`” è riferita alla scelta della tecnologia del modulo in prova. Selezionare l’opzione “`STD`” in caso di test su moduli FV di tipo “STANDARD”, l’opzione “`CAP`” in caso di moduli FV con effetti capacitivi considerevoli
> *   La scelta errata del tipo di tecnologia può comportare un esito negativo del test finale

**PVCHECKs** IT - 21

### 5.6.1. Definizione di un nuovo modulo FV

1.  Posizionare il cursore sulla voce `DB` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata che riporta:
    *   Il tipo di modulo selezionato
    *   I valori dei parametri associati al modulo (vedere Tabella 1)
2.  Usare i tasti freccia (``, ``) per selezionare il tipo di modulo “`DEFAULT`” e confermare con `ENTER`.

```
15/05/12   15:34:26
Modello :  DEFAULT 
Pmax    = 185 W
Voc     = 44.5 V
Vmpp    = 37.5 V
Isc     = 5.40 A
Impp    = 4.95 A
Toll -  = 0 %

Selezione DB
```

3.  Premere il tasto `ENTER`, selezionare il comando “`Nuovo`” (che consente di definire un nuovo modulo) e confermare ancora con `ENTER`. Usare i tasti freccia (``, ``) per scorrere l’elenco dei parametri.

```
15/05/12   15:34:26
Modello :  DEFAULT 
Pmax    = 185 W
Voc     = 44.5 V
Vmpp    = 37.5 V
Isc     = 5.40 A
Impp    = 4.95 A
Toll -  = 0 %
Nuovo 
Selezione DB
```

4.  Lo strumento presenta una tastiera virtuale interna in cui è possibile definire il nome del modulo (ex: SUNPOWER 210) usando i tasti freccia (``, ``, ``, ``). La pressione del tasto `ENTER` consente l’inserimento di ogni carattere del nome digitato.
5.  Premere il tasto `SAVE` per salvare il nome del nuovo modulo così definito o il tasto `ESC/MENU` per uscire senza salvare.

```
15/05/12   15:34:26
Modello :
Pmax    = 185 W
Voc     = 44.5 V
TASTIERA
SUNPOWER 210
A B C D E F G H I J K L M N O P
Q R S T U V W X Y Z - + 0 1 2 3
4 5 6 7 8 9 SPACE DEL
SAVE / ESC
```

6.  Inserire il valore di ogni parametro (vedere Tabella 1) in funzione del datasheet eventuale del costruttore. Posizionare il cursore sul parametro da definire utilizzando i tasti freccia (``, ``) e impostare il valore utilizzando i tasti freccia (``, ``). Tenere premuto i tasti (``, ``) per eseguire una rapida impostazione dei valori.
7.  Premere il tasto `SAVE` per salvare le impostazioni o `ESC/MENU` per uscire senza salvare.

```
15/05/12   15:34:26
Modello : SUNPWR 210
Pmax    =  0  W
Voc     = 0.0 V
Vmpp    = 0.0 V
Isc     = 0.00 A
Impp    = 0.00 A
Toll -  = 0 %
DB
```

> **ATTENZIONE**
> *   Premere il tasto `HELP` per alcuni secondi nel caso di valore non noto al fine di inserire il valore di default
> *   Alla pressione del tasto `SAVE` lo strumento controlla le condizioni riportate nella Tabella 1 e, nel caso in cui una o più di esse non sia verificata, fornisce a display uno dei messaggi di errore riportati nel § 6.6 e non salva la configurazione impostata finché le cause di errore non sono risolte

<!-- Chunk: Pages 24-46 -->
## 5.6.2. Modifica di un modulo FV esistente

1.  Selezionare il modulo FV da modificare all’interno del database utilizzando i tasti freccia (``, ``).
2.  Premere il tasto `ENTER` e selezionare il comando “`Modifica`” usando il tasto freccia (``).
3.  Confermare la selezione con `ENTER`.

```
15/05/12   15:34:26
M o d e l l o   :      S U N P W R 2 1 0   
P m a x   =   2 1 0   W
V o c   =   4 7 . 7 0   V
V m p p   =   4 0 . 0 0   V
I s c   =   5 . 7 5   A
N u o v o
M o d i f i c a
C a n c e l l a
C a n c e l l a   T u t t o   
D B
```

4.  Lo strumento presenta una tastiera virtuale interna in cui è possibile ridefinire il nome del modulo o lasciarlo inalterato usando tasti freccia (``, ``, ``, ``). La pressione del tasto `ENTER` consente l’inserimento di ogni carattere del nome digitato.
5.  Premere il tasto `SAVE` per salvare il nome del nuovo modulo così definito o per accedere alla nuova programmazione dei parametri.

```
15/05/12   15:34:26
M o d e l l o :      S U N P W R 2 1 0   
P m a x   =   1 8 5   W
V o c   =   4 4 . 5   V
T A S T I E R A
S U N P O W E R   2 1 0
A   B   C   D   E   F   G   H   I   J   K   L   M   N   O   P
Q   R   S   T   U   V   W   X   Y   Z   -   +   0   1   2   3
4   5   6   7   8   9   S P A C E   D E L
SAVE / ESC
```

6.  Modificare il valore dei parametri desiderati utilizzando i tasti freccia (``, ``) e impostare il valore utilizzando i tasti freccia (``, ``). Tenere premuto i tasti (``, ``) per eseguire una rapida impostazione dei valori. Premere il tasto `HELP` per alcuni secondi nel caso di valore non noto al fine di inserire il valore di default.
7.  Premere il tasto `SAVE` per salvare le impostazioni eseguite o `ESC/MENU` per uscire senza salvare. Lo strumento fornisce in tal caso il messaggio “`Dati non memorizzati`”.

```
15/05/12   15:34:26
M o d e l l o   :   S U N P W R   2 1 0

P m a x   =      2 1 0      W
V o c   =   4 7 . 7 0   V
V m p p   =   4 0 . 0 0   V
I s c   =   5 . 7 5   A
I m p p   =   5 . 2 5   A
T o l l   -   =   5   %

D B
```

## 5.6.3. Cancellazione di un modulo FV esistente

1.  Selezionare il modulo FV presente all’interno del database utilizzando i tasti freccia (``, ``).
2.  Premere il tasto `ENTER` e selezionare il comando “`Cancella`” usando il tasto freccia (``) per cancellare il modulo selezionato.
3.  Premere il tasto `ENTER` e selezionare il comando “`Cancella Tutto`” usando il tasto freccia (``) per cancellare ogni modulo presente all’interno del database.
4.  Confermare la selezione con `ENTER` oppure premere `ESC/MENU` per uscire dalla funzione.

```
15/05/12   15:34:26
M o d e l l o   :      S U N P W R 2 1 0   
P m a x   =   2 1 0   W
V o c   =   4 7 . 7 0   V
V m p p   =   4 0 . 0 0   V
I s c   =   5 . 7 5   A
N u o v o
M o d i f i c a
C a n c e l l a
C a n c e l l a   T u t t o   
D B
```

**ATTENZIONE**
*   Non è possibile modificare né cancellare il modulo FV di `DEFAULT` presente come impostazione di fabbrica.

## 6. ISTRUZIONI OPERATIVE

### 6.1. MISURA EFFICIENZA IMPIANTI FV CON USO DI UNITA’ REMOTA SOLAR-02

Per semplicità, nel seguito di questo § si adotterà il termine “stringa” anche se spesso il termine “campo fotovoltaico” sarebbe più opportuno. Dal punto vista dello strumento la gestione di una sola stringa o di più stringhe in parallelo fra loro (campo FV) è identica. Lo strumento `PVCHECKs` (Master) consente di eseguire misure di efficienza su installazioni FV in abbinamento con l’unità remota opzionale `SOLAR-02` a cui sono collegate le sonde di irraggiamento e temperatura. Tale unità remota è in grado di comunicare con quella Master (per la gestione delle operazioni di sincronizzazione e scaricamento dei dati) attraverso un collegamento a radiofrequenza (`RF`) attivo fino ad una distanza massima di circa 1m tra di esse.

**ATTENZIONE**
*   La massima tensione tra gli ingressi `P` e `N` è `1000VDC`. Non misurare tensioni che eccedano i limiti espressi in questo manuale. Il superamento di tali limiti potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.
*   Per garantire la sicurezza dell’operatore, durante la fase dei collegamenti, mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter).

**Fig. 4**: Collegamento dello strumento per misura di efficienza su impianto FV

1.  Controllare ed eventualmente impostare sul `SOLAR-02` la sensibilità della cella di riferimento coerentemente con il tipo di moduli FV che si andrà ad esaminare (vedere manuale d’uso del `SOLAR-02`).
2.  Si raccomanda di eseguire una valutazione preliminare del valore dell’Irraggiamento sul piano dei moduli FV in esame tramite l’unità `SOLAR-02` (in funzionamento indipendente) e la cella di riferimento.
3.  Accendere il `PVCHECKs`, controllare ed eventualmente modificare le impostazioni dello strumento relativamente al tipo di unità remota, alla soglia minima di irraggiamento, al fondo scala della pinza DC, al periodo di integrazione e i parametri del sistema in esame (vedere `§ 5.1.4`, `§ 5.1.5`, `§ 5.1.6`, `§ 5.2.1` e `§ 5.2.2`).

4.  Per garantire la sicurezza dell’operatore mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter).
5.  Avvicinare fra loro (max 1 m circa) il `PVCHECKs` e il `SOLAR-02`. Tutti gli strumenti devono essere accesi (vedere il manuale d’uso di `SOLAR-02` per ulteriori dettagli).
6.  Su `PVCHECKs` premere il tasto `MENU`, selezionare la funzione `EFF` e premere `ENTER` ed attendere che le due unità inizino a comunicare fra loro. Questa condizione è evidenziata dalla presenza simultanea dei seguenti indicatori:
    *   Simbolo fisso (non intermittente) sul display del `PVCHECKs`.
    *   Simbolo fisso (non intermittente) sul display del `SOLAR-02`.
7.  Collegare gli ingressi `P` e `N` rispettivamente ai poli positivo e negativo di uscita della stringa rispettando i colori indicati in Fig. 4.
8.  Collegare il connettore di uscita della pinza DC all’ingresso `IDC`.

**ATTENZIONE**
PRIMA DI COLLEGARE LA PINZA DC SUI CONDUTTORI
Accendere la pinza, controllare il LED indicante lo stato delle batterie interne della pinza (se presenti), selezionare la portata corretta, premere il tasto `ZERO` sulla pinza DC e verificare sul display del `PVCHECKs` l’effettivo azzeramento del valore Idc corrispondente (valori fino a `0.02A` sono comunque accettabili).

9.  Collegare la pinza di corrente DC sul conduttore positivo in uscita dalla stringa rispettando il verso della freccia presente sulla pinza stessa come indicato in Fig. 4. Posizionare la pinza in modo che il toroide non sia in prossimità del conduttore negativo.
10. A display appare la prima videata che riporta i valori dei parametri elettrici in uscita dal modulo/stringa.
11. Prima di attivare la misura verificare la presenza del simbolo “` `” fisso che indica il corretto collegamento RF con l’unità remota `SOLAR-02`.

```
15/05/12   15:34:26
I r r   -   -   -   W / m 2
P n o m   3   .   5   0 0   k W
T c   4 5   ° C
T   e   3 0   ° C
P d c   3   .   1 2 5   k W
V d c   3 8 9   V
I d c   8   . 0   1   A
n d c   -   -   -
G o   p e r   A v v i a r e
Sele zione   E F F
```

12. Mantenendo l’unita `SOLAR-02` sempre in prossimità dell’unità principale, premere il tasto `GO/STOP` su `PVCHECKs` per attivare il collaudo. Il messaggio “`Registrazione in attesa`” appare a display dell’unità principale ed il messaggio “`HOLD`” a display del `SOLAR-02` oltre all’indicazione del tempo in secondi in attesa dell’istante “00”.

```
15/05/12   15:34:26
I r r   -   -   -   W / m 2
P n o m   3 . 5 0 0   k W
T c   4 5   ° C
T   e   3 0   ° C
P d c   3 . 1 2 5   k W
V d c   3 8 9   V
I d c   8 . 0 1   A
n d c   -   -   -
R   e g i s t r a z i o n e   i n   a t t e s a
Selezione   E F F
```

13. Al raggiungimento dell’istante ”00” successivo alla pressione del tasto `GO/STOP` il collaudo ha inizio e le due unità sono tra loro sincronizzate. In tali condizioni il messaggio “`Registrazione in corso`” appare a display dell’unità principale ed il messaggio “`Recording…`” appare a display del `SOLAR-02`.

```
15/05/12   15:35:00
I r r   -   -   -   W / m 2
P n o m   3 . 5 0 0   k W
T c   4 5   ° C
T e   3 0   ° C
P d c   3 . 1 2 5   k W
V d c   3 8 9   V
I d c   8 . 0 1   A
n d c   -   -   -
R   e g   i s t r a z i o n e   i n   c o r s o
Selezione   E F F
```

14. In qualunque momento sarà possibile analizzare lo stato attuale della registrazione tramite pressione del tasto `MENU`. Verranno visualizzati:
    *   Data ed ora di inizio registrazione
    *   Il valore impostato del periodo di integrazione
    *   Il numero di Periodi trascorsi dall’inizio registrazione
    *   La capacità di memoria residua di registrazione.
    Premere il tasto `ESC` per uscire dalla videata.

```
15/05/12   15:35:00
S t a r t :   1   5   / 0   5   /   1 2   1   5   :   3 0   : 0 0
P e r i o d o :   5 s
N u m e r o   I P   6 1
A u t o n o m i a   0 d   1 h
R e g i s t r a z i o n e   i n   c o r s o …
Selezione   E F F
```

15. A questo punto è possibile portare l’unità `SOLAR-02` in prossimità delle stringhe FV per effettuare le misure di irraggiamento e temperatura tramite le rispettive sonde. Quando la distanza tra l’unità `SOLAR-02` e `PVCHECKs` è tale da non consentire il collegamento RF, sul display del `SOLAR-02`, il simbolo “` `” lampeggia per circa 30s poi scompare, mentre il `PVCHECKs` resta in ricerca per 1 minuto circa.
16. Posizionare la cella di riferimento sul piano dei moduli FV. Fare riferimento al relativo manuale d’uso per un corretto montaggio.
17. Posizionare il sensore di temperatura a contatto con il retro del modulo fissandolo con nastro e evitando di toccarlo al fine di falsare la misura.
18. Attendere qualche secondo per consentire alle sonde di raggiungere una misura stabile e poi collegare la sonda di Irraggiamento all’ingresso `PYRA/CELL` e la sonda di temperatura all’ingresso `TEMP` dell’unità `SOLAR-02`.
19. Attendere il messaggio “`READY`” a display del `SOLAR-02` ad indicare che l’unità ha rilevato dei dati con Irraggiamento solare > soglia minima impostata (vedere `§ 5.1.5`).
20. Con messaggio “`READY`” a display attendere per circa 1 minuto in modo da raccogliere un certo numero di campioni.
21. Scollegare le sonde di Irraggiamento e temperatura dall’unità `SOLAR-02` e avvicinarla al `PVCHECKs` (max 1m).
22. L’unità principale `PVCHECKs` deve essere in modalità `EFF`. Se è assente il simbolo “` `” lampeggiante, premere il tasto `` per riattivare la ricerca del collegamento RF.
23. Premere il tasto `` sul `SOLAR-02` per riattivare il collegamento RF. Conseguentemente sull’unità principale verrà visualizzato il messaggio “`connessione radio attiva`”.
24. Per arrestare il collaudo premere il tasto `GO/STOP` sullo strumento e confermare con `ENTER` alla richiesta di arresto della registrazione.
25. Il messaggio “`SEND`” è mostrato a display dell’unità `SOLAR-02` ad indicare il trasferimento dei dati all’unità principale.

27. Premere `SAVE` per salvare i risultati ottenuti (vedere `§ 7.1`) o `ESC` per uscire dalla videata e tornare alla videata iniziale.
26. Dopo la fase automatica di trasferimento dati, lo strumento visualizzerà:
    *   `Esito SI`: se esiste almeno 1 valore fra quelli rilevati che soddisfa le relazioni indicate nel `§ 5.2.3`.
    *   `Esito NO`: se NON esiste nessun valore fra quelli rilevati che soddisfa le relazioni indicate nel `§ 5.2.3`.
    *   `Impossibile effettuare l’analisi`: se l’irraggiamento non ha mai raggiunto un valore stabile superiore alla soglia minima impostata oppure se non esiste nessun valore valido durante tutto l’arco della registrazione (`nDC > 1.15`).
    *   Non visualizzerà nessun esito (SI o NO) se lo strumento è stato impostato con correzione di temperatura tipo “`nDC`” (vedere `§ 5.2.3`).

```
15/05/12   15:35:00
I r r   7 1 2   W / m 2
P n o m   3 . 5 0 0   k W
T c   4 5   ° C
T e   3 0   ° C
P d c   3 . 1 2 5   k W
V d c   3 8 9   V
I d c   8 . 0 1   A
n d c   0 . 8 8
E   s i t o :   S I
Selezione   E F F
```

### 6.2. MISURA PARAMETRI IMPIANTO FV SENZA USO DI SOLAR-02

Il test di “efficienza impianti FV” senza uso di unità remota opzionale `SOLAR-02` comporta la valutazione dei soli parametri di tipo elettrico in uscita da una stringa o da un campo fotovoltaico (grandezze Vdc, Idc e Pdc) di cui è possibile eseguire una registrazione periodica con periodo di integrazione programmabile (vedere `§ 5.2.1`). In questa modalità non vengono valutati i valori di Irraggiamento, Te, Tc, il valore dell’efficienza `nDC` e non viene fornito nessun esito da parte dello strumento.

**ATTENZIONE**
*   La massima tensione tra gli ingressi `P` e `N` è `1000VDC`. Non misurare tensioni che eccedano i limiti espressi in questo manuale. Il superamento di tali limiti potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.
*   Per garantire la sicurezza dell’operatore, durante la fase dei collegamenti, mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter).

**Fig. 5**: Collegamento dello strumento per misura parametri impianto FV senza `SOLAR-02`

1.  Selezionare l’opzione “`NO`” relativamente al tipo di unità remota nel test `EFF` (vedere `§ 5.1.4`), impostare il fondo scala della pinza DC (vedere `§ 5.2.1`), l’eventuale fattore di correzione della pinza DC (vedere `§ 5.1.6`), il periodo di integrazione e la potenza nominale dell’impianto (vedere `§ 5.2.1` e `§ 5.2.2`).
2.  Per garantire la sicurezza dell’operatore mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter).
3.  Collegare gli ingressi `P` e `N` rispettivamente ai poli positivo e negativo di uscita della stringa rispettando i colori indicati in Fig. 5.
4.  Collegare il connettore di uscita della pinza DC all’ingresso `IDC`.

**ATTENZIONE**
PRIMA DI COLLEGARE LA PINZA DC SUI CONDUTTORI
Accendere la pinza, controllare il LED indicante lo stato delle batterie interne della pinza (se presenti), selezionare la portata corretta, premere il tasto `ZERO` sulla pinza DC e verificare sul display del `PVCHECKs` l’effettivo azzeramento del valore Idc corrispondente (valori fino a `0.02A` sono comunque accettabili).

5.  Collegare la pinza di corrente DC sul conduttore positivo in uscita dalla stringa rispettando il verso della freccia presente sulla pinza stessa come indicato in Fig. 5. Posizionare la pinza in modo che il toroide non sia in prossimità del conduttore negativo.
6.  A display appare la prima videata che riporta i valori dei parametri elettrici in uscita dal modulo/stringa.

```
15/05/12   15:34:26
I r r   -   -   -   W / m 2
P n o m   3 . 5 0 0   k W
T c   -   -   -   ° C
T e   -   -   -   ° C
P d c   3 . 1 2 5   k W
V d c   3 8 9   V
I d c   8 . 0 1   A
n d c   -   -   -
G o   p e r   A v v i a r e
Selezione   E F F
```

7.  Premere il tasto `GO/STOP` su `PVCHECKs` per attivare il test. Il messaggio “`Registrazione in attesa`” appare a display dello strumento in attesa dell’istante “00”.

```
15/05/12   15:34:26
I r r   -   -   -   W / m 2
P n o m   3 . 5 0 0   k W
T c   4 5   ° C
T e   3 0   ° C
P d c   3 . 1 2 5   k W
V d c   3 8 9   V
I d c   8 . 0 1   A
n d c   -   -   -
R   e g   i s t r a z i o n e   i n   a t t e s a
Selezione   E F F
```

8.  Al raggiungimento dell’istante ”00” successivo alla pressione del tasto `GO/STOP` il test ha inizio. In tali condizioni il messaggio “`Registrazione in corso`” appare a display dello strumento.

```
15/05/12   15:35:00
I r r   -   -   -   W / m 2
P n o m   3 . 5 0 0   k W
T c   4 5   ° C
T e   3 0   ° C
P d c   3 . 1 2 5   k W
V d c   3 8 9   V
I d c   8 . 0 1   A
n d c   -   -   -
R   e g   i s t r a z i o n e   i n   c o r s o
Selezione   E F F
```

9.  In qualunque momento sarà possibile analizzare lo stato attuale della registrazione tramite pressione del tasto `MENU`. Verranno visualizzati:
    *   Data ed ora di inizio registrazione
    *   Il valore impostato del periodo di integrazione
    *   Il numero di Periodi trascorsi dall’inizio registrazione
    *   La capacità di memoria residua di registrazione.
    Premere il tasto `ESC` per uscire dalla videata.

```
15/05/12   15:35:00
S t a r t   1 5 / 0 5 / 1 2   1 5 : 3 0 : 0 0
P e r i o d o :   5 s
N u m e r o   I P   6 1
A u t o n o m i a   0 d   1 h
R e g i s t r a z i o n e   i n   c o r s o
E F F
```

10. Per arrestare il test premere il tasto `GO/STOP` sullo strumento e confermare con `ENTER` alla richiesta di arresto della registrazione.
11. Premere `SAVE` per salvare i risultati ottenuti (vedere `§ 7.1`) o `ESC` per uscire dalla videata e tornare alla videata iniziale.

### 6.3. TEST RAPIDO SU MODULI E STRINGHE FV (IVCK)

#### 6.3.1. Introduzione

Questa funzione esegue una serie di test rapidi su un modulo/stringa FV misurando in sequenza:
*   La tensione a vuoto `Voc` e la corrente di corto circuito `Isc` in accordo alle prescrizioni della norma `IEC/EN62446` con possibilità di misura (utilizzando le rispettive sonde) anche dei valori di irraggiamento e temperatura dei moduli.
*   Misura della resistenza di isolamento (se abilitata – vedere `§ 5.5.1`) eseguito esclusivamente nel modo `STRINGA` (vedere `§ 6.4.4`) ossia eseguendo automaticamente un cortocircuito interno tra i terminali di ingresso `P` e `N` e realizzando la misura tra questo punto di cortocircuito e il terminale di ingresso `E`.
*   Test continuità dei conduttori di protezione (se abilitato – vedere `§ 5.5.1`) con `200mA` tra i terminali di ingresso `E` e `C` dello strumento.

La misura di irraggiamento può essere fatta tramite una delle seguenti modalità:
*   Cella di riferimento collegata direttamente a `PVCHECKs`.
*   Cella di riferimento collegata a `SOLAR-02` in collegamento `RF` con `PVCHECKs`.

Le misure di irraggiamento sono effettuate sempre in tempo reale, non è quindi possibile avviare una registrazione “remota” dei valori di irraggiamento tramite `SOLAR-02`.
Se la soglia di Irraggiamento minimo (vedere `§ 5.1.5`) è:
*   `= 0` → lo strumento non controlla la presenza della cella di riferimento, le variazioni di irraggiamento, il numero dei moduli e non visualizza messaggi di errore se non è possibile calcolare i valori trasposti a `STC` di `Voc` e `Isc`. Questa modalità è indicata per eseguire una sessione di test in maniera estremamente rapida su un numero elevato di stringhe.
*   `> 0` (consigliato `>700 W/m²`) → lo strumento esegue tutti i controlli previsti per la prova `I-V`, gestisce tutte le condizioni ed i messaggi di errore della prova `I-V` (num. Mod. errato, Temp. Fuori range, presenza cella, Irr. Min, ecc..) e calcola i valori a `STC` di `Voc` e `Isc`. Questa modalità è raccomandata qualora si intenda eseguire delle prove più approfondite sui moduli/stringhe in esame.

La pagina dei risultati conterrà in generale:
*   La descrizione del modulo in uso.
*   I valori di Irraggiamento e temperatura (se disponibili).
*   I valori medi di `Voc` e `Isc` calcolati come media dei corrispondenti valori a `OPC` sulle ultime 10 prove memorizzate e salvate. Se il numero delle prove è < 10 la media viene calcolata sul numero delle prove disponibili. La prima prova visualizzerà trattini nel campo “valori medi” visto che non ci sono prove precedenti su cui calcolare la media.
*   I valori di `Voc` e `Isc` misurati a `OPC` e gli eventuali esiti parziali (presenti solo se i valori `STC` non sono disponibili) ottenuti per confronto con i valori medi.
*   I valori di `Voc` e `Isc` calcolati a `STC` (se disponibili) e gli eventuali esiti parziali ottenuti per confronto dei valori calcolati a `STC` con quelli nominali (inseriti nel `DB` moduli).
*   L’esito complessivo della prova (`OK/NO`). L’esito complessivo verrà calcolato sulla base degli esiti parziali ottenuti:
    *   Sulla base degli esiti parziali a `STC` (se questi sono disponibili).
    *   Sulla base degli esiti parziali a `OPC` (se i valori `STC` non sono disponibili).
Lo strumento non visualizzerà nessun esito complessivo se non è disponibile nessun esito parziale.

#### 6.3.2. Esecuzione test rapido IVCK senza misura di Irraggiamento

**ATTENZIONE**
Non utilizzare lo strumento per test `IVCK` su moduli FV con efficienza `>19%`. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento.

**ATTENZIONE**
*   La massima tensione tra gli ingressi `P`, `N`, `E` e `C` è `1000VDC`. Non misurare tensioni che eccedano i limiti espressi in questo manuale.
*   Non eseguire mai prove su moduli o stringhe FV connessi al convertitore DC/AC.
*   La corrente massima tollerabile dallo strumento è `15 A`. Prima di eseguire le misure di `IVCK` verificare sempre che lo strumento sia connesso ad UNA SOLA STRINGA e non a più stringhe connesse in parallelo al fine di evitare il possibile danneggiamento dello strumento.

1.  Accendere lo strumento premendo il tasto `ON/OFF`.
2.  Controllare che l’unità remota `SOLAR-02` non sia selezionata (vedere `§ 5.1.4` – impostazione `NO`).
3.  Controllare che il valore di Irraggiamento minimo impostato nella sezione “`Irraggiamento`” (vedere `§ 5.1.5`) sia pari a `0`.
4.  Posizionare il cursore sulla voce `IVCK` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a fianco. Il significato dei parametri è il seguente:
    *   `Modulo` → tipo di modulo in prova
    *   `Vdc` → valore della tensione in uscita dal modulo/stringa misurato in tempo reale
    *   `Irr` → valore dell’irraggiamento misurato in tempo reale
    *   `Tc` → valore della temperatura del modulo (vedere `§ 5.5.1`)
    *   `Voc, Isc` → sezione con visualizzazione esito `OK/NO` della misura di `Voc` e `Isc`
    *   `Ri()` → il valore tra parentesi può essere `NO`/tensione di prova selezionata (vedere `§ 5.5.1`). Il valore di `Ri` indica la resistenza di isolamento
    *   `Rpe()` → il valore tra parentesi può essere `NO`, `Cal` o `NoCal` (vedere `§ 5.5.1`). Il valore di `Rpe` indica il risultato della prova di continuità.

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   0 . 0   V
I r r   -   -   -   W / m 2
T c   -   -   -
V o c , I s c :
R i ( 1 0 0 0 V )   -   -   -   M   
R p e   ( C a l )   -   -   -   
Selezione   I V C K
```

5.  Premere il tasto `ENTER`, selezionare la voce “`Impostazioni`” e confermare ancora con `ENTER`. Eseguire le impostazioni sullo strumento come riportato nel `§ 5.5.1`.
6.  Se necessario premere il tasto `ENTER`, selezionare la voce “`Reset Medie`” e confermare ancora con `ENTER`. Eseguire l’eventuale operazione come riportato nel `§ 6.3.4`.
7.  Se necessario premere il tasto `ENTER`, selezionare la voce “`Calibrazione cavi`” e confermare ancora con `ENTER`. Eseguire l’eventuale operazione come riportato nel `§ 6.5.2`.
8.  Collegare lo strumento al modulo/stringa in prova ed eventualmente al nodo principale di terra dell’impianto e alle masse metalliche messe a terra come mostrato in Fig. 6. In particolare collegare il polo Negativo in uscita dal modulo/stringa al terminale `N` e il polo Positivo in uscita dal modulo/stringa al terminale `P`.

**Fig. 6**: Collegamento per test IVCK senza misura di irraggiamento
**LEGENDA**:
*   `E`: Cavo verde
*   `C`: Cavo blu
*   `P`: Cavo rosso
*   `N`: Cavo nero
1.  Modulo/Stringa FV
2.  Riferimento principale di terra dell’impianto
3.  Struttura metallica messa a terra dell’impianto

**ATTENZIONE**
Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere `§ 6.6`) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test.

9.  Premere il tasto `GO/STOP` per attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura in corso…`” e la misura della tensione a vuoto tra i terminali `P` e `N` e della corrente di cortocircuito (per valori di `Isc` ` 15A`).

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   5 4 8 . 0   V
I r r   0   W / m 2
T c   A u t o   ° C
V o c , I s c :
R i ( 1 0 0 0 V )   -   -   -   M   
R p e   ( C a l )   -   -   -   
Misura in corso…
Selezione   I V C K
```

10. Al termine delle misure di `Voc` e `Isc` il messaggio “`OK`” è fornito in caso di esito positivo del test (valori misurati entro le tolleranze impostate sullo strumento).
11. Con misura di isolamento selezionata lo strumento continua il test mantenendo in cortocircuito i terminali `P` e `N` ed eseguendo la prova tra questo punto e il terminale `E` per un tempo necessario ad ottenere un risultato stabile.
12. Il valore della resistenza di isolamento è mostrato nel campo “`Ri`” e il messaggio “`OK`” in caso di esito positivo del test (valore misurato superiore al limite minimo impostato sullo strumento).

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   5 4 8 . 0   V
I r r   0   W / m 2
T c   A u t o   ° C
V o c , I s c :   O K
R i ( 1 0 0 0 V )   1 1 6   M      O K
R p e   ( C a l )   -   -   -   
Misura in corso…
Selezione   I V C K
```

13. Con misura di continuità selezionata lo strumento continua il test aprendo il cortocircuito ed eseguendo il test tra i terminali `E` e `C`.
14. Il valore della resistenza nella prova di continuità è mostrato nel campo “`Rpe`” e il messaggio “`OK`” in caso di esito positivo del test (valore misurato inferiore al limite massimo impostato sullo strumento).
15. Il messaggio “`Esito OK`” è infine mostrato dallo strumento in caso di esito positivo di tutti i test eseguiti.

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   5 4 8 . 0   V
I r r   0   W / m 2
T c   A u t o   ° C
V o c , I s c :   O K
R i ( 1 0 0 0 V )   1 1 6   M      O K
R p e   ( C a l )   2 . 0 0      O K
Esito :   OK
   I V C K
```

16. Premere il tasto freccia `` per visualizzare la pagina successiva in cui sono presenti i valori dei parametri `Voc` e `Isc`. In essa a sono visualizzati:
    *   Il modulo in uso
    *   I valori medi di `Voc` e `Isc` alle condizioni `OPC`
    *   I valori di `Voc` e `Isc` misurati a `OPC` ed i relativi esiti parziali ottenuti per confronto con i valori medi.
    In generale:
    `Esito Voc OK se +  −  = Voc@OPC VocMed@OPC VocMed@OPC 4% Voc Tol 100`
    `Esito Isc OK se +  −  = Isc@OPC IscMed@OPC IscMed@OPC 4% Isc Tol 100`
    *   Il valore complessivo degli esiti:
        *   `OK`: se tutti gli esiti `OPC` sono `OK`,
        *   `NO`: se uno degli esiti `OPC` è `NO`.

```
15/05/12   15:34:26
M o d u l o :   S U N P W R 2 1 0
I r r   - - -   W / m 2
T c   ( A U T O )   - -   ° C
V o c M e d @ O P C   6 4 7   V
I s c M e d @ O P C   5 . 4 3   A
V o c @ O P C   6 4 7   V   O K
I s c @ O P C   5 . 3 5   A   O K
V o c @ S T C   - - -   V
I s c @ S T C   - - -   A
Esito: OK
   I V C K (   ) (   )
```

17. Premere il tasto freccia `` per tornare alla videata precedente.
18. Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il `§ 7.2`) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura.

**ATTENZIONE**
Nella pagina dei risultati compaiono i valori medi di `Voc` e `Isc`. Tale valori contengono i valori medi di `Voc` e `Isc` alle condizioni `OPC` calcolati come media sulle ultime 10 prove precedentemente memorizzate. Se l’utente ha eseguito e memorizzato un numero di prove `<10` oppure ha resettato i valori medi (vedere `§ 6.3.4`) la media visualizzata nel corso della prova `N+1` saranno quelli calcolata su gli N valori disponibili.

#### 6.3.3. Esecuzione test rapido IVCK con misura di Irraggiamento

**ATTENZIONE**
Non utilizzare lo strumento per test `IVCK` su moduli FV con efficienza `>19%`. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento.

**ATTENZIONE**
*   La massima tensione tra gli ingressi `P`, `N`, `E` e `C` è `1000VDC`. Non misurare tensioni che eccedano i limiti espressi in questo manuale.
*   Non eseguire mai prove su moduli o stringhe FV connessi al convertitore DC/AC.
*   La corrente massima tollerabile dallo strumento è `15A`. Prima di eseguire le misure di `IVCK` verificare sempre che lo strumento sia connesso ad UNA SOLA STRINGA e non a più stringhe connesse in parallelo al fine di evitare il possibile danneggiamento dello strumento.

1.  Accendere lo strumento premendo il tasto `ON/OFF`.
2.  La misura di irraggiamento è eseguita tramite uno dei due modi seguenti:
    *   Misura tramite cella di riferimento collegata direttamente a `PVCHECKs`.
    *   Misura tramite cella di riferimento collegata a `SOLAR-02` in collegamento `RF` con `PVCHECKs`.
3.  Controllare che l’impostazione dell’unità remota `SOLAR-02` sia coerente con il tipo di misura che si intende realizzare (vedere `§ 5.1.4`).
4.  Controllare il valore di irraggiamento minimo impostato (vedere `§ 5.1.5`).
5.  Posizionare il cursore sulla voce `IVCK` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a fianco. Il significato dei parametri è il seguente:
    *   `Modulo` → tipo di modulo in prova
    *   `Vdc` → valore della tensione in uscita dal modulo/stringa misurato in tempo reale
    *   `Irr` → valore dell’irraggiamento misurato in tempo reale
    *   `Tc` → valore della temperatura del modulo (vedere `§ 5.5.1`)

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   0 . 0   V
I r r   0   W / m 2
T c   A u t o   ° C
V o c , I s c :
R i ( 1 0 0 0 V )   -   -   -   M   
R p e   ( C a l )   -   -   -   
Selezione   I V C K
```

    *   `Voc, Isc` → sezione con visualizzazione esito `OK/NO` della misura di `Voc` e `Isc`.
    *   `Ri ()` → il valore tra parentesi può essere `NO`/tensione di prova selezionata (vedere `§ 5.5.1`). Il valore di `Ri` indica la resistenza di isolamento.
    *   `Rpe ()` → il valore tra parentesi può essere `NO`, `Cal` o `NoCal` (vedere `§ 5.5.1`). Il valore di `Rpe` indica il risultato della prova di continuità.
6.  Premere il tasto `ENTER`, selezionare la voce “`Impostazioni`” e confermare ancora con `ENTER`. Eseguire le impostazioni sullo strumento come riportato nel `§ 5.5.1`.
7.  Se necessario premere il tasto `ENTER`, selezionare la voce “`Reset Medie`” e confermare ancora con `ENTER`. Eseguire operazione come riportato nel `§ 6.3.4`.
8.  Se necessario premere il tasto `ENTER`, selezionare la voce “`Calibrazione cavi`” e confermare ancora con `ENTER`. Eseguire l’operazione come riportato nel `§ 6.5.2`.
9.  Montare lo stelo sul disco dell’accessorio opzionale `M304` e tenerlo appoggiato sul piano del modulo. Verificare che l’ombra dello stelo proiettata sul disco cada entro il “cerchio concentrico limite” interno al disco stesso (vedere Fig. 7). In caso contrario l’angolo tra i raggi solari e la superficie del modulo è troppo elevato e pertanto le misure eseguite dallo strumento NON sono da ritenere attendibili. Ripetere le operazioni in altri momenti della giornata.

10. Fissare la staffa al modulo usando le viti in dotazione alla cella di riferimento opzionale `HT304k` e montarla su di essa possibilmente con terminali di uscita rivolti verso il basso. Ruotare la cella fino ad appoggiarla sull’aletta presente sulla staffa in modo da renderla esattamente parallela al piano del modulo e fissarla quindi tramite le apposite viti.

**Fig. 7**: Posizionamento dell’inclinometro opzionale M304

11. Collegare l’uscita della cella, corrispondente al tipo di modulo in prova, all’ingresso `IRR`. dello strumento usando il cavo in dotazione alla cella stessa oppure all’ingresso `PYRA/CELL` dell’unità remota `SOLAR-02` se utilizzata (vedere Fig. 8 e Fig. 9).
12. Collegare, se utilizzato, il sensore di temperatura all’ingresso `TEMP` dello strumento ed al retro del modulo sotto una cella usando nastro adesivo oppure all’ingresso `TEMP` dell’unità remota `SOLAR-02` se utilizzata (vedere Fig. 8 e Fig. 9).
13. Collegare lo strumento al modulo/stringa in prova ed eventualmente al nodo principale di terra dell’impianto e alle masse metalliche messe a terra come mostrato nelle Fig. 8 e Fig. 9. In particolare, collegare il polo Negativo in uscita dal modulo/stringa al terminale `N` e il polo Positivo in uscita dal modulo/stringa al terminale `P`.

**ATTENZIONE**
In caso di utilizzo dell’unità remota `SOLAR-02` per misura di irraggiamento assicurarsi che la comunicazione radio `RF` con l’unità master `PVCHECKs` sia sempre attiva (simbolo “` `” accesso fisso a display).

**Fig. 8**: Collegamento per test IVCK con misura diretta irraggiamento
**LEGENDA**:
*   `E`: Cavo verde
*   `C`: Cavo blu
*   `P`: Cavo rosso
*   `N`: Cavo nero
1.  Modulo/Stringa FV
2.  Riferimento principale di terra dell’impianto
3.  Struttura metallica messa a terra dell’impianto
4.  Cella di riferimento per misura irraggiamento
5.  Sensore temperatura (se richiesto)

**Fig. 9**: Collegamento per test IVCK con misura irraggiamento tramite `SOLAR-02`
**LEGENDA**:
*   `E`: Cavo verde
*   `C`: Cavo blu
*   `P`: Cavo rosso
*   `N`: Cavo nero
1.  Modulo/Stringa FV
2.  Riferimento principale di terra dell’impianto
3.  Struttura metallica messa a terra dell’impianto
4.  Cella di riferimento per misura irraggiamento
5.  Sensore temperatura (se richiesto)
6.  Unità remota `SOLAR-02`

14. Nella videata iniziale della modalità `IVCK` vengono visualizzati in tempo reale i valori di:
    *   `Modulo` → tipo di modulo in prova
    *   `Vdc` → valore della tensione in uscita dal modulo/stringa
    *   `Irr` → irraggiamento (proveniente da misura diretta o `SOLAR-02` in collegamento a `RF`)
    *   `Tc` → temperatura del modulo (in modo `MAN` o `AUX`) e il relativo modo di misura oppure “`- - -`“ in modo `AUTO`
    *   L’eventuale simbolo “` `” del collegamento `RF` con l’unità `SOLAR-02`

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   5 4 8 . 0   V
I r r   8 5 6   W / m 2
T c   A u t o   ° C
V o c , I s c :
R i ( 1 0 0 0 V )   -   -   -   M   
R p e   ( C a l )   -   -   -   
Selezione   I V C K
```

**ATTENZIONE**
Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere `§ 6.6`) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test.

15. Premere il tasto `GO/STOP` per attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura in corso…`” e la misura della tensione a vuoto tra i terminali `P` e `N` e della corrente di cortocircuito (per valori di `Isc` ` 15A`).

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   5 4 8 . 0   V
I r r   8 5 6   W / m 2
T c   A u t o   ° C
V o c , I s c :
R i ( 1 0 0 0 V )   -   -   -   M   
R p e   ( C a l )   -   -   -   
Misura in corso…
Selezione   I V C K
```

16. Al termine delle misure di `Voc` e `Isc` il messaggio “`OK`” è fornito in caso di esito positivo del test (valori misurati entro le tolleranze impostate sullo strumento).
17. Con misura di isolamento selezionata lo strumento continua il test mantenendo in cortocircuito i terminali `P` e `N` ed eseguendo la prova tra questo punto e il terminale `E` per un tempo necessario ad ottenere un risultato stabile.
18. Il valore della resistenza di isolamento è mostrato nel campo “`Ri`” e il messaggio “`OK`” in caso di esito positivo del test (valore misurato superiore al limite minimo impostato sullo strumento).

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   5 4 8 .   0   V
I r r   8 5 6   W / m 2
T c   A u t o   ° C
V o c , I s c :   O K
R i ( 1 0 0 0 V )   1 1 6   M      O K
R p e   ( C a l )   -   -   -   
Misura in corso…
Selezione   I V C K
```

19. Con misura di continuità selezionata lo strumento continua il test aprendo il cortocircuito ed eseguendo il test tra i terminali `E` e `C`.
20. Il valore della resistenza nella prova di continuità è mostrato nel campo “`Rpe`” e il messaggio “`OK`” in caso di esito positivo del test (valore misurato inferiore al limite massimo impostato sullo strumento).
21. Il messaggio “`Esito OK`” è infine mostrato dallo strumento in caso di esito positivo di tutti i test eseguiti.

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   5 4 8 . 0   V
I r r   8 5 6   W / m 2
T c   A u t o   ° C
V o c , I s c :   O K
R i ( 1 0 0 0 V )   1 1 6   M      O K
R p e   ( C a l )   2 . 0 0      O K
Esito OK
   I V C K
```

22. Premere il tasto freccia `` per visualizzare la pagina successiva in cui sono presenti i valori dei parametri `Voc` e `Isc`. In essa a sono visualizzati:
    *   Il modulo in uso
    *   Il valore dell’Irraggiamento
    *   Il valore della temperatura del modulo
    *   I valori medi di `Voc` e `Isc` alle condizioni `OPC`
    *   I valori di `Voc` e `Isc` misurati a `OPC`
    *   I valori di `Voc` e `Isc` calcolati a `STC` ed i relativi esiti parziali ottenuti per confronto con i valori nominali.
    In generale:
    `Esito Voc OK se +  −  = Voc@STC VocNom VocNom 4% Voc Tol 100`
    `Esito Isc OK se +  −  = Isc@STC IscNom IscNom 4% Isc Tol 100`
    I valori di `Voc` e `Isc` nominali sono i valori presenti nel `DB` moduli interno allo strumento (vedere `§ 5.6`).
    *   Il valore complessivo degli esiti:
        *   `OK`: se tutti gli esiti `STC` sono `OK`,
        *   `NO`: se uno degli esiti `STC` è `NO`.

```
15/05/12   15:34:26
M o d u l o :   S U N P W R 2 1 0
I r r   - - -   W / m 2
T c   ( A U T O )   5 7   ° C
V o c M e d @ O P C   6 4 7   V
I s c M e d @ O P C   5 . 4 3   A
V o c @ O P C   6 4 7   V
I s c @ O P C   5 . 3 5   A
V o c @ S T C   7 8 7   V   O K
I s c @ S T C   5 . 7 2   A   O K
Esito OK
   I V C K (   ) (   )
```

23. Premere il tasto freccia `` per tornare alla videata precedente.
24. Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il `§ 7.2`) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura.

**ATTENZIONE**
Nella pagina dei risultati compaiono i valori medi di `Voc` e `Isc`. Tale valori contengono i valori medi di `Voc` e `Isc` alle condizioni `OPC` calcolati come media sulle ultime 10 prove precedentemente memorizzate. Se l’utente ha eseguito e memorizzato un numero di prove `<10` oppure ha resettato i valori medi (vedere `§ 6.3.4`) la media visualizzata nel corso della prova `N+1` saranno quelli calcolata su gli N valori disponibili.

#### 6.3.4. Reset Medie

Se non sono misurati i valori di Irraggiamento, lo strumento fornisce un esito confrontando i valori misurati con i valori medi calcolati sulla base delle misure precedentemente salvate. Pertanto in questo caso i valori medi calcolati dallo strumento assumono particolare importanza.

Nel caso si inizi una nuova campagna di misura con variazioni significative di Irraggiamento o temperatura è consigliabile azzerare i valori medi di riferimento per poi farlo ricalcolare sulle base di nuove misure.

Per resettare i valori medi attenersi ai seguenti passi:
1.  All’interno della modalità `IVCK`, premere il tasto `ENTER`, selezionare la voce “`Reset Medie`” e confermare ancora con `ENTER` per azzerare i valori medi fino a quel momento calcolati.

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   0 . 0   V
I r r   0   W / m 2
T c   A u t o   ° C
V o c , I s c :
R i ( 1 0 0 0 V )   -   -   -   M   
R p e   ( C a l )   -   -   -   
Calibrazione cavi
Reset Medie
Impostazioni
Selezione   I V C K
```

I valori medi vengono automaticamente resettati anche modificando e poi salvando uno dei seguenti parametri:
*   Tipo di modulo FV
*   Numero di moduli x stringa

I valori medi non vengono invece resettati se l’operatore cambia modalità di funzionamento per poi tornare a questa modalità.

##### 6.3.4.1. Situazioni anomale test IVCK

1.  Qualora lo strumento rilevi ai terminali `P-N`, `P-E` e `N-E` una tensione superiore a `1000V` non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`Vin > 1000`”.

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   0 . 0   V
I r r   0   W / m 2
T c   A u t o   ° C
V o c , I s c :
R i ( 1 0 0 0 V )   -   -   -   M   
R p e   ( C a l )   -   -   -   
Vin   >   1000
Selezione   I V C K
```

2.  Qualora lo strumento rilevi ai terminali `P` e `N` una tensione inferiore a `15V` non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`Tensione bassa`”.

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   0 . 0   V
I r r   0   W / m 2
T c   A u t o   ° C
V o c , I s c :
R i ( 1 0 0 0 V )   -   -   -   M   
R p e   ( C a l )   -   -   -   
Tensione   bassa
Selezione   I V C K
```

3.  Qualora lo strumento rilevi ai terminali `E` e `C` una tensione superiore a `> 5 V` non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`Tensione > Lim`”.

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   0 . 0   V
I r r   0   W / m 2
T c   A u t o   ° C
V o c , I s c :
R i ( 1 0 0 0 V )   -   -   -   M   
R p e   ( C a l )   -   -   -   
Tensione >   Lim
Selezione   I V C K
```

4.  Qualora lo strumento rilevi una corrente `Isc` superiore a `15 A` non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`Corrente Isc troppo alta`”.

```
15/05/12   15:34:26
M o d u l o   S U N P W R 3 1 8
V d c   0 . 0   V
I r r   0   W / m 2
T c   A u t o   ° C
V o c , I s c :
R i ( 1 0 0 0 V )   -   -   -   M   
R p e   ( C a l )   -   -   -   
Corrente Isc troppo alta
Selezione   I V C K
```

### 6.4. MISURA DI ISOLAMENTO SU MODULI/STRINGHE/CAMPI FV (MΩ)

#### 6.4.1. Introduzione

Lo scopo di questa misura è l’esecuzione delle misure di resistenza di isolamento dei conduttori attivi di un modulo, di una stringa, di un intero campo FV e di eventuali masse metalliche non connessi a terra in accordo alle prescrizioni della Guida `CEI 82-25` e della normativa `IEC/EN62446-1`. In generale lo strumento esegue la misura di isolamento nei seguenti modi:
*   `Modo CAMPO` → utilizzata per la misura di resistenza di isolamento di un Campo FV (generatore fotovoltaico) formato da una o più stringhe connesse in parallelo. Lo strumento esegue la misura sui poli Positivo e Negativo del campo FV.
*   `Modo TIMER` → lo strumento esegue la misura in modo continuo (con durata max `300s`) sul solo terminale “`P`” visualizzando il valore minimo ottenuto della resistenza al termine del periodo di tempo selezionato. Può essere utilizzato per la misura di resistenza di isolamento di più masse e stranee non collegate a riferimenti di terra.
*   `Modo STRINGA` → utilizzata per la misura di isolamento esclusivamente su singoli moduli o singole stringhe FV, eseguendo automaticamente un cortocircuito interno tra i poli Positivo e Negativo senza la necessità di utilizzare un interruttore esterno per porre in corto-circuito i terminali positivo e negativo e realizzando la misura tra questo punto di cortocircuito e il riferimento di terra dell’installazione.

#### 6.4.2. Esecuzione misura di isolamento – Modo CAMPO

1.  Posizionare il cursore sulla voce `MΩ` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a fianco:
2.  Premere il tasto `ENTER`, attivare la voce “`Impostazioni`” ed eventualmente modificare i parametri desiderati (vedere `§ 5.4.1`). I seguenti parametri sono mostrati a display:
    *   `Test Iso` → tensione di prova selezionata (`250`, `500`, o `1000VDC`)
    *   `Ri min` → soglia limite minima per la misura di isolamento (si ricorda che la `IEC/EN62446-1` fissa un valore minimo di isolamento pari a `1MΩ` con tensioni di prova di `500V` o `1000V`)
    *   `Modo` → modo di misura: `CAMPO`
    *   `Vtest` → tensioni di prova reali applicate rispettivamente tra il polo Positivo e il polo Negativo del campo rispetto al riferimento di terra
    *   `Ri (+) `→ misura di resistenza di isolamento tra il polo Positivo del campo FV e il riferimento di terra
    *   `Ri (-) `→ misura di resistenza di isolamento tra il polo Negativo del campo FV e il riferimento di terra

```
15/05/12   15:34:26
T e s t   I s o   1 0 0 0   V
R i   m i n   1 . 0   M   
M o d o   C a m p o
V t e s t   -   -   -   V   -   -   -   V
R i   ( + )   -   -   -   
R i   (   -   )   -   -   -   
R p   -   -   -   
Selezione   M      
```

```
15/05/12   15:34:26

V P N   -   -   -   V
V E P   -   -   -   V
V E N   -   -   -   V
Selezione   M   
```

    *   `Rp` → valore finale della misura ottenuto dal parallelo dei valori di `Ri (+) `e `Ri (-) `che è confrontato dallo strumento con il valore `Ri min` impostato.
    *   `Tasto ` → accesso alla seconda pagina con i valori misurati delle tensioni `VPN`, `VEP` e `VEN`.
3.  Collegare lo strumento al campo FV in prova e al nodo principale di terra dell’impianto come mostrato in Fig. 10. In particolare collegare il polo Negativo in uscita dal campo FV al terminale `N` e il polo Positivo in uscita dal campo FV al terminale `P`.

**Fig. 10**: Collegamento strumento per misura di isolamento in modo CAMPO
**LEGENDA**:
*   `E`: Cavo verde
*   `P`: Cavo rosso
*   `N`: Cavo nero
1.  Campo FV non collegato a terra
2.  Riferimento principale di terra dell’impianto

**ATTENZIONE**
Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere `§ 6.6`) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test.

4.  Premere il tasto `GO/STOP` per attivare il test. In caso di assenza di condizioni di errore lo strumento visualizza il messaggio “`Misura in corso…`” come mostrato nella videata a lato:

```
15/05/12   15:34:26
T e s t   I s o   1 0 0 0   V
R i   m i n   1 . 0   M   
M o d o   C a m p o
V t e s t   1 0 4 3   V   1 0 5 7   V
R i   ( + )   -   -   -   
R i   (   -   )   -   -   -   
R p   -   -   -   
Misura in corso…
Selezione   M      
```

5.  Al termine della misura lo strumento fornisce i valori `Ri (+)`, `Ri (-) `e `Rp` rispettivamente resistenze di isolamento dei poli Positivo e Negativo e parallelo delle due resistenze del campo FV in prova. Se il valore di `Rp` è superiore al limite minimo impostato lo strumento visualizza il messaggio “`Esito OK`” altrimenti visualizza il messaggio “`Esito NO`”.
6.  Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il `§ 7.2`) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura.

```
15/05/12   15:34:26
T e s t   I s o   1 0 0 0   V
R i   m i n   1 . 0   M   
M o d o   C a m p o
V t e s t   1 0 4 3   V   1 0 5 7   V
R i   ( + )   > 1 0 0   M   
R i   (   -   )   > 1 0 0   M   
R p   6   9   M   
Esito :   OK
Selezione   M      
```

#### 6.4.3. Esecuzione misura di isolamento – Modo TIMER

1.  Posizionare il cursore sulla voce `MΩ` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a fianco.
2.  Premere il tasto `ENTER`, attivare la voce “`Impostazioni`” ed eventualmente modificare i parametri desiderati (vedere `§ 5.4.1`). I seguenti parametri sono mostrati a display:
    *   `Test Iso` → tensione di prova selezionata (`250`, `500`, `1000VDC`)
    *   `Ri min` → soglia limite minima per la misura di isolamento (si ricorda che la `IEC/EN62446-1` fissa un valore minimo di isolamento pari a `1MΩ` con tensioni di prova di `500V` o `1000V`)
    *   `Modo` → modo di misura: `TIMER`
    *   `Vtest` → tensione di prova reale applicata
    *   `Ri (+)` → resistenza di isolamento minima tra il polo Positivo e il riferimento di terra rilevata per l’intera durata della misura
    *   `Tempo prova` → durata della prova impostabile nel campo `10 ÷ 300s`
    *   `Tasto ` → accesso alla seconda pagina con i valori misurati delle tensioni `VPN`, `VEP` e `VEN`

```
15/05/12   15:34:26
T e s t   I s o   1 0 0 0   V
R i   m i n   1 . 0   M   
M o d o   T i m e r
V t e s t   -   -   -   V
R i ( + )   -   -   -   M   
T e m p o   p r o v a :   2 0   0   s
Selezione   M      
```

3.  Collegare lo strumento a masse metalliche estranee non collegate a terra e al nodo principale di terra dell’impianto (vedere Fig. 11).

**Fig. 11**: Collegamento strumento per misura di isolamento in modo TIMER
**LEGENDA**:
*   `E`: Cavo verde
*   `P`: Cavo rosso
*   `N`: Cavo nero
1.  Modulo/stringa FV non collegata a terra
2.  Riferimento principale di terra dell’impianto
3.  Massa metallica non collegata a terra

**ATTENZIONE**
Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere `§ 6.6`) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test.

4.  Premere il tasto `GO/STOP` per attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura in corso…`” come mostrato nella videata a lato.

```
15/05/12   15:34:26
T e s t   I s o   1 0 0 0   V
R   i   m i n   1 . 0   M   
M o d o   T   i m e r
V t e s t   1 0 2 0   V
R i   ( + )   -   -   -   M   
T e m p o   p r o v a :   2 0   0   s
Misura in corso…
Selezione   M      
```

5.  Al termine della misura lo strumento fornisce il valore `Ri(+)min`, ossia il valore minimo della resistenza di isolamento delle masse estranee continuamente misurato per l’intera durata della misura. Se il risultato è superiore al limite minimo impostato lo strumento visualizza il messaggio “`Esito OK`” altrimenti visualizza il messaggio “`Esito NO`” come mostrato nella videata a lato.
6.  Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il `§ 7.2`) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura.

```
15/05/12   15:34:26
T e s t   I s o   1 0 0 0   V
R   i   m i n   1 . 0   M   
M o d o   T i m e r
V t e s t   1 0 2 0   V
R   i ( + ) m i n   >   2   0 0   M   
T e m p o   p r o v a :   2 0   0   s
Esito:   OK
M      
```

#### 6.4.4. Esecuzione misura di isolamento – Modo STRINGA

**ATTENZIONE**
*   Prima di eseguire le misure di Isolamento in modalità “`STRINGA`”, verificare sempre che lo strumento sia connesso ad UNA SOLA STRINGA e non a più stringhe connesse in parallelo al fine di evitare il possibile danneggiamento dello strumento.
*   Scollegare SEMPRE la stringa in esame dall’inverter prima di eseguire il test.

1.  Posizionare il cursore sulla voce `MΩ` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a fianco.
2.  Premere il tasto `ENTER`, attivare la voce “`Impostazioni`” ed eventualmente modificare i parametri desiderati (vedere `§ 5.4.1`). I seguenti parametri sono mostrati a display:
    *   `Test Iso` → tensione di prova selezionata (`250`, `500`, `1000VDC`)
    *   `Ri min` → soglia limite minima per la misura di isolamento (si ricorda che la `IEC/EN62446-1` fissa un valore minimo di isolamento pari a `1MΩ` con tensioni di prova di `500V` o `1000V`)

```
15/05/12   15:34:26
T e s t   I s o   1 0 0 0   V
R   i   m i n   1 . 0   M   
M o d o   S   t r i n g a
V t e s t   -   -   -   V
R   p   -   -   -   M   
Selezione   M      
```

    *   `Modo` → modo di misura: `STRINGA`
    *   `Vtest` → tensione di prova reale applicata
    *   `Rp` → valore finale della misura ottenuto dal parallelo dei valori di resistenza di isolamento tra i poli Positivo e Negativo e il riferimento di terra rilevata per l’intera durata della misura, confrontato dallo strumento con il valore `Ri min` impostato.
    *   `Tasto ` → accesso alla seconda pagina con i valori misurati delle tensioni `VPN`, `VEP` e `VEN`.
3.  Collegare lo strumento al modulo/stringa FV in prova e al nodo principale di terra dell’impianto come mostrato in Fig. 12. In particolare collegare il polo Negativo in uscita dal campo FV al terminale `N` e il polo Positivo in uscita dal campo FV al terminale `P`.

**Fig. 12**: Collegamento strumento per misura di isolamento in modo STRINGA
**LEGENDA**:
*   `E`: Cavo verde
*   `P`: Cavo rosso
*   `N`: Cavo nero
1.  Modulo/stringa FV non collegata a terra
2.  Riferimento principale di terra dell’impianto

**ATTENZIONE**
Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere `§ 6.6`) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test.

4.  Premere il tasto `GO/STOP` per attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura in corso…`” come mostrato nella videata a lato.

```
15/05/12   15:34:26
T e s t   I s o   1 0 0 0   V
R   i   m i n   1 . 0   M   
M o d o   S t r i n g a
V t e s t   1 0 2 0   V
R   p   -   -   -   M   
Misura in corso…
Selezione   M      
```

5.  Al termine della misura lo strumento fornisce il valore `Rp` della misura ottenuto dal parallelo dei valori di resistenza di isolamento tra i poli Positivo e Negativo e il riferimento di terra confrontato dallo strumento con il valore `Ri min` impostato. Se il risultato è superiore al limite minimo impostato lo strumento visualizza il messaggio “`Esito OK`” altrimenti visualizza il messaggio “`Esito NO`” come mostrato nella videata a lato.
6.  Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il `§ 7.2`) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura.

```
15/05/12   15:34:26
T e s t   I s o   1 0 0 0   V
R   i   m i n   1 . 0   M   
M o d o   S t r i n g a
V t e s t   1 0 2 0   V
R   p   >   1 0 0   M   
Esito:   OK
M      
```

<!-- Chunk: Pages 47-68 -->
### 6.4.4.1. Situazioni anomale

1.  In ogni modalità di funzionamento qualora lo strumento rilevi ai terminali P - N, P - E e N - E una tensione superiore a `1000V` non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`Vin > 1000`”
    ```
    15/05/12   15:34:26
    T e s t   I s o   1 0 0 0   V
    R   i   m i n   1 . 0   M   
    M o d o   S t r i n g a
    V t e s t   -   -   -   V
    R   p   -   -   -   M   
    Vin > 1000
    Selezione   M      
    ```
2.  In modalità di funzionamento STRINGA qualora lo strumento rilevi una corrente Isc superiore a `15A` non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`Corrente Isc troppo alta`”
    ```
    15/05/12   15:34:26
    T e s t   I s o   1 0 0 0   V
    R   i   m i n   1 . 0   M   
    M o d o   S t r i n g a
    V t e s t   -   -   -   V
    R   p   -   -   -   M   
    Corrente Isc troppo alta
    Selezione   M      
    ```
3.  In modalità di funzionamento STRINGA qualora lo strumento rilevi tra i terminali P e N una corrente `< 0.2A` non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`Corrente < Lim`”
    ```
    15/05/12   15:34:26
    T e s t   I s o   1 0 0 0   V
    R   i   m i n   1 . 0   M   
    M o d o   S t r i n g a
    V t e s t   -   -   -   V
    R   p   -   -   -   M   
    Corrente   <   L im
    Selezione   M      
    ```
4.  In modalità di funzionamento STRINGA qualora lo strumento rilevi tra i terminali P e N una tensione `< 15V` non esegue la prova e visualizza il messaggio “`Tensione bassa`”
    ```
    15/05/12   15:34:26
    T e s t   I s o   1 0 0 0   V
    R   i   m i n   1 . 0   M   
    M o d o   S t r i n g a
    V t e s t   -   -   -   V
    R   p   -   -   -   M   
    Tensione bassa
    Selezione   M      
    ```

## 6.5. MISURA DI CONTINUITÀ SU MODULI/STRINGHE/CAMPI FV (LOW )

### 6.5.1. Introduzione

Lo scopo di questa misura è l’esecuzione del test di continuità dei conduttori di protezione ed equipotenziali (ex: dal dispersore fino alle masse e masse estranee collegate) e dei conduttori di messa a terra degli SPD sulle installazioni FV. Il test deve essere condotto usando una corrente di prova > 200mA in accordo alle prescrizioni della Guida CEI 82-25 e della normativa IEC/EN62446-1.

### 6.5.2. Calibrazione cavi di misura

1.  Posizionare il cursore sulla voce `LOW ` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a lato
2.  Connettere i cavi di misura tra di loro come mostrato in Fig. 13
    ```
    15/05/12   15:34:26
    R p e   m a x   1   
    R c a l   -   -   -   
    R p e   -   -   -   
    I t e s t   -   -   -   m A
    Selezione   L O W   
    ```
    **Fig. 13**: Compensazione della resistenza dei cavi di misura
2.  Premere il tasto `ENTER`. Lo strumento mostra le opzioni: `Impostazioni` e `Calibrazione cavi`
3.  Usare i tasti freccia (``, ``) per selezionare la voce “`Calibrazione cavi`” e confermare con `ENTER`
    ```
    15/05/12   15:34:26
    R P E   m a x   1   
    R c a l   -   -   -   
    R p e   -   -   -   
    I t e s t   -   -   -   m A
    Calibrazione cavi
    I m p o s t a z i o n i
    Selezione   L O W   
    ```
4.  Premere il tasto `GO/STOP` per attivare la calibrazione. Il messaggio “`Misura in corso…`” è mostrato a display.
5.  Al termine della procedura di compensazione, nel caso in cui il valore della resistenza misurata risulti inferiore a `5 `, lo strumento emette un doppio segnale acustico a segnalare l’esito positivo della prova e visualizza la seguente videata:
    ```
    15/05/12   15:34:26
    R P E   m a x   1   
    R c a l   -   -   -   
    R p e   -   -   -   
    I t e s t   -   -   -   m A
    M i s u r a   i n   c o r s o …
    Selezione   L O W   
    ```

6.  Il valore della resistenza compensata dei cavi che sarà sottratto a tutte le successive misure di continuità è presente in corrispondenza della voce “`Rcal`” e il messaggio “`Calibrazione OK`” è mostrato a display
7.  Per cancellare il valore della resistenza compensata effettuare una nuova procedura di compensazione con una resistenza superiore a `5 ` come, ad esempio, a puntali aperti. Il valore in `Rcal` viene azzerato a display
    ```
    15/05/12   15:34:26
    R P E   m a x   1   
    R c a l   0 . 0 2   
    R p e   -   -   -   
    I t e s t   -   -   -   m A
    C a l i b r a z i o n e   O K
    Selezione   L O W   
    ```

### 6.5.3. Esecuzione misura di continuità

1.  Posizionare il cursore sulla voce `LOW ` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a lato
2.  Premere il tasto `ENTER`, attivare la voce “`Impostazioni`” ed eventualmente modificare i parametri desiderati (vedere § 5.3.1). I seguenti parametri sono mostrati a display:
    *   `RPE max` → soglia massima per la misura di continuità selezionabile nel campo `1   5 ` in passi da `1 ` (si ricorda che la IEC/EN62446-1 non fissa un valore limite di resistenza e valori tipici sono di circa `1 ` o `2 `)
    *   `Rcal` → valore della resistenza dei cavi di misura dopo aver eseguito la calibrazione degli stessi
    *   `Rpe` → risultato della misura di continuità
    *   `Itest` → corrente reale di prova
    ```
    15/05/12   15:34:26
    R   P E   m a x   1   
    R c a l   -   -   -   
    R p e   -   -   -   
    I t e s t   -   -   -   m A
    Selezione   L O W   
    ```
3.  Premere il tasto `ENTER`, attivare la voce “`Calibrazione cavi`” (vedere § 6.5.2) per eseguire la calibrazione iniziale dei cavi di misura
4.  Collegare lo strumento al modulo/stringa FV in prova e al nodo principale di terra dell’impianto come mostrato in Fig. 14

    **LEGENDA**:
    *   **E**: Cavo verde
    *   **C**: Cavo blu
    *   **1**: Modulo/stringa FV
    *   **2**: Riferimento principale di terra dell’impianto
    *   **3**: Struttura metallica messa a terra dell’impianto

    **Fig. 14**: Collegamento strumento per misura di continuità su strutture dell’impianto FV

> **ATTENZIONE**
> Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere § 6.6) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test

5.  Premere il tasto `GO/STOP` per attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura in corso…`” come mostrato nella videata a lato
    ```
    15/05/12   15:34:26
    R   P E   m a x   1   
    R c a l   -   -   -   
    R p e   -   -   -   
    I t e s t   -   -   -   m A
    Misura in corso…
    Selezione   L O W   
    ```
6.  Al termine della misura lo strumento fornisce il valore della resistenza dell’oggetto in prova. Se il risultato è inferiore al limite massimo impostato lo strumento visualizza il messaggio “`Esito OK`” altrimenti visualizza il messaggio “`Esito NO`” come mostrato nella videata a lato
7.  Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il § 7.2) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura
    ```
    15/05/12   15:34:26
    R   p e   m a x   1   
    R c a l   -   -   -   
    R p e   0 . 2 3   
    I t e s t   2 1 0   m A
    Esito:   OK
    L O W   
    ```

#### 6.5.3.1. Situazioni anomale

1.  Qualora lo strumento rilevi ai propri terminali E e C una tensione superiore a `5V` non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`Tensione > Lim`”
    ```
    15/05/12   15:34:26
    R   P E   m a x   1   
    R c a l   -   -   -   
    R p e   -   -   -   
    I t e s t   -   -   -   m A
    T e n s i o n e   >   L   i m
    Selezione   L O W   
    ```
2.  Qualora venga rilevato che la resistenza calibrata sia più elevata della resistenza misurata lo strumento emette un segnale acustico prolungato e visualizza il messaggio: “`Calibrazione non OK`”
    ```
    15/05/12   15:34:26
    R   P E   m a x   1   
    R c a l   -   -   -   
    R p e   -   -   -   
    I t e s t   -   -   -   m A
    C a l i b r a z i o n e   n o n   O K
    Selezione   L O W   
    ```
3.  Qualora lo strumento rilevi ai propri terminali una resistenza superiore a `5 ` emette un segnale acustico prolungato, azzera il valore compensato e visualizza il messaggio “`Calibrazione resettata`”
    ```
    15/05/12   15:34:26
    R   P E   m a x   1   
    R c a l   0 . 0 0   
    R p e   -   -   -   
    I t e s t   -   -   -   m A
    C a l i b r a z i o n e   r e s e t t a t a
    Selezione   L O W   
    ```

## 6.6. ELENCO DEI MESSAGGI A DISPLAY

| MESSAGGIO                       | DESCRIZIONE                                                                     |
| :------------------------------ | :------------------------------------------------------------------------------ |
| Funzione non disponibile        | La funzione/caratteristica selezionata non è disponibile                        |
| Dati non memorizzati            | Lo strumento non è stato in grado di salvare i dati                             |
| Data errata                     | Inserire una data di sistema coerente                                           |
| Errore trasmissione RADIO       | Lo strumento non comunica via RF con unità esterne                              |
| SOLAR-02:Firmware non corretto  | FW SOLAR-02 non coerente. Aggiornare il firmware                                |
| Firmware non corretto           | FW strumento non adeguato. Aggiornare il firmware                               |
| Errore 4: contattare assistenza | Errore interno dello strumento                                                  |
| Data base pieno                 | Il numero dei moduli inseriti nel DB interno è > 30                             |
| Modulo già presente             | Nome del modulo inserito già presente nel DB                                    |
| Memoria piena                   | Memoria dello strumento piena alla pressione del tasto GO                       |
| Errore: Vmpp >= Voc             | Controllare le impostazioni del modulo all’interno del DB                       |
| Errore: Impp >= Isc             | Controllare le impostazioni del modulo all’interno del DB                       |
| Errore: Vmpp * Impp >= Pmax     | Controllare le impostazioni del modulo all’interno del DB                       |
| Errore: Alpha troppo alto       | Controllare le impostazioni del modulo all’interno del DB                       |
| Errore: Beta troppo alto        | Controllare le impostazioni del modulo all’interno del DB                       |
| Errore: Gamma troppo alto       | Controllare le impostazioni del modulo all’interno del DB                       |
| Errore: Toll troppo alta        | Controllare le impostazioni del modulo all’interno del DB                       |
| Attendere analisi dati          | Scarico dati da SOLAR-02 e attesa esito test efficienza FV                      |
| Errore scarico dati             | Contattare assistenza                                                           |
| Errore memorizzazione           | Problemi nell’accesso all’area di memoria                                       |
| Unità remota non rilevata       | Lo strumento non rileva nessuna unità SOLAR-02                                  |
| Impossibile effettuare l’analisi | Problemi sui dati scaricati dal SOLAR-02. Verificare impostazioni               |
| Dati non disponibili            | Errore generico. Ripetere il test                                               |
| Tensione negativa               | Controllare le polarità dei terminali di ingresso dello strumento               |
| Tensione bassa                  | Controllare la tensione tra i terminali di ingresso P e N                       |
| Vin > 1000                      | Tensione tra i terminali di ingresso > 1000V                                    |
| N. moduli errato. Continuare?   | Impostazione numero moduli non coerente con Voc misurata                        |
| Temp. Cella rif. oltre i limiti | Temperatura misurata dalla cella di riferimento troppo alta                     |
| Temp.cella non rilevata.(ENTER/ESC) | Misura non eseguita sulla cella del modulo                                      |
| Batteria scarica                | Livello batterie basso. Inserire nuove batterie nello strumento                 |
| Attendere raffreddamento        | Strumento surriscaldato. Attendere prima di riprendere i test                   |
| Irraggiamento troppo basso      | Valore di irraggiamento inferiore al limite minimo impostato                    |
| Errore NTC                      | Efficienza NTC interna compromessa. Contattare assistenza                       |
| Corrente Isc troppo alta        | Corrente Isc misurata > 15A                                                     |
| Corrente < Lim                  | Corrente misurata tra P e N inferiore al minimo rilevabile                      |
| Errore EEPROM: contattare assistenza | Errore interno dello strumento                                                  |
| Errore FRAM: contattare assistenza | Errore interno dello strumento                                                  |
| Errore RTC: contattare assistenza | Errore interno dello strumento                                                  |
| Errore RADIO: contattare assistenza | Errore interno dello strumento                                                  |
| Errore FLASH: contattare assistenza | Errore interno dello strumento                                                  |
| Errore IO EXP: contattare assistenza | Errore interno dello strumento                                                  |
| Tensione > limite               | Tensione tra i terminali E e C > 10V                                            |
| Label già assegnata             | Cambiare riferimento numerico marcatore associato a misura                      |
| Corrente Isc < Lim              | Corrente Isc inferiore al minimo rilevabile. Contattare assistenza              |
| Attenzione: corto circuito interno | Contattare assistenza                                                           |
| Attenzione: fusibile interrotto | Contattare assistenza                                                           |
| Calibrazione resettata. Premi ENTER | Valore resistenza cavi in ingresso > 2                                         |
| Calibrazione non OK             | Valore resistenza calibrata > resistenza misurata                               |
| Errore: misura offset Isc       | Errore interno dello strumento                                                  |
| Rcal > R misurata               | Valore resistenza calibrata > resistenza misurata                               |
| Attenzione tensione AC alle boccole P-N | Presenza di tensione AC in ingresso                                             |
| Attendere scarico condensatore  | Attesa scarica oggetto in prova dopo isolamento                                 |

## 7. MEMORIZZAZIONE RISULTATI

Lo strumento consente la memorizzazione di `max 999` risultati di misura. I dati possono essere richiamati a display e cancellati in ogni momento ed è possibile associare degli identificatori numerici di riferimento mnemonici relativi all’impianto, alla stringa e al modulo FV (`max 250`).

### 7.1. SALVATAGGIO DELLE MISURE DI EFFICIENZA

1.  Premere il tasto `SAVE` con esito della misura presente a display. Lo strumento presenta la videata mostrata a lato in cui è presente la tastiera virtuale
2.  Usare i tasti freccia (``, ``) e (``, ``) per inserire una breve descrizione (`max 13` caratteri) relativa al test eseguito
3.  Premere ancora il tasto `SAVE` per confermare il salvataggio dei dati o `ESC/MENU` per uscire senza salvare
    ```
    15/05/12   15:34:26
    I r r   7 1 2   W / m 2
    P n o m   3 . 5 0 0   k W
    T c   4 5   ° C
    T e   3 0   ° C
    P d c   3 . 1 2 5   k W
    T A S T I E R A
    I M P I A N T O   R O S S I
    A   B   C   D   E   F   G   H   I   J   K   L   M   N   O   P
    Q   R   S   T   U   V   W   X   Y   Z   -   +   0   1   2   3
    4   5   6   7   8   9   S P A C E   D E L
    SAVE /ESC
    ```

### 7.2. SALVATAGGIO DELLE MISURE DI IVCK, M  E LOW 

1.  Premere il tasto `SAVE` con risultato di misura presente a display. Lo strumento presenta la videata mostrata a lato in cui sono mostrate le seguenti voci:
    *   La prima locazione di memoria disponibile (“`MISURA`”)
    *   Il marcatore di 1° livello (ex: Area)
    *   Il marcatore di 2° livello (ex: Campo)
    *   Il marcatore di 3° livello (ex: Inverter)
    *   Il campo “`Commenti`” in cui l’operatore può inserire una breve descrizione (`max 13` caratteri) per l’impianto
    ```
    15/05/12   15:34:26
    M I S U R A   :   0 0   4
    A r e a   :      0   0 1   
    C a m p o   :   0 0   1
    I n v e r t e r   :   0 0   1
    C o m m e n t   i   :
    M o d i f i c a   S A L V A
    ```
2.  Ad ogni marcatore possono essere assegnate diverse etichette (5 etichette predefinite e 5 personalizzabili). Selezionare il marcatore di livello desiderato con i tasti freccia (``, ``) e premere il tasto `ENTER` per la selezione di una delle etichette disponibili
3.  Selezionare una delle disponibili etichette usando i tasti freccia (``, ``) e confermare con il tasto `ENTER`
    ```
    Inverter
    Area   0 0 4
    Edificio      0 0 2   
    Campo   0 0 1
    Impianto   0 0 1
    C o m m e n t o   :
    M o d i f i c a   S A L V A
    ```
4.  Ai nomi di default delle 5 etichette predefinite possono essere, preliminarmente alle misure tramite software TopView, aggiunti altri 5 nomi personalizzati dall’utente. In tal caso i nuovi valori possono essere selezionati in alternativa a quelli di default come mostrato nella videata a fianco
    ```
    Solar Power
    Azienda PVPlant   0 0 4
    Studio Bianchi      0 0 2   
    HT ITALIA   0 0 1
    Studio Rossi   0 0 1
    Inverter
    Area
    Edificio
    Campo
    Impianto
    M o d i f i c a   S A L V A
    ```

> **ATTENZIONE**
> *   I nomi personalizzati delle etichette dei marcatori possono essere definiti con l’uso del software TopView e caricati sullo strumento tramite collegamento a PC (sezione “`Collegamento PC - Strumento → Gestione marcatori`”)
> *   E’ possibile aggiungere fino a 5 nomi personalizzati per ogni marcatore oltre ai 5 presenti come default
> *   I nomi dei marcatori di default non sono eliminabili. La cancellazione dei nomi personalizzati può avvenire solo da software TopView

5.  Usare i tasti freccia (``, ``) e (``, ``) per l’uso della tastiera virtuale nel campo “`Commento`” in cui l’utente può inserire una breve descrizione (`max 13` caratteri). La pressione del tasto `ENTER` consente l’inserimento di ogni carattere del nome digitato
    ```
    15/05/12   15:34:26
    M I S U R A   :   0 0   4
    H T   I T A L I A   :      0 0   2   
    S t r i n g a   U T   :   0 0   1
    M o d u l o   A 1   :   0 0   1
    C o m m e n t o   :
    T A S T I E R A
    T E S T   I M P .   H T
    A   B   C   D   E   F   G   H   I   J   K   L   M   N   O   P
    Q   R   S   T   U   V   W   X   Y   Z   -   +   0   1   2   3
    4   5   6   7   8   9   S P A C E   D E L
    SAVE /ESC
    ```
6.  Premere nuovamente il tasto `SAVE` per completare il salvataggio dei dati o `ESC/MENU` per uscire senza salvare

### 7.3. OPERAZIONI CON RISULTATI

#### 7.3.1. Richiamo a display dei risultati di efficienza FV

1.  Premere il tasto `ESC/MENU` per tornare al menu principale, selezionare la voce “`MEM`” e premere `ENTER` per entrare nella sezione di visualizzazione dei dati memorizzati. La videata di fianco è mostrata dallo strumento in cui è presente l’elenco delle prove salvate
2.  Usando i tasti freccia (``, ``) e il tasto freccia `` selezionare la voce “`Richiama`” e successivamente “`Efficienza`” e confermare con `ENTER` per la visualizzazione dei soli risultati delle prove di collaudo
3.  Usando il tasto freccia `` è possibile la visualizzazione delle seguenti etichette:
    *   `TIPO` → indica la tipologia di dato salvato: “`REG`” per un collaudo avente un preciso esito finale SI/NO, “`*REG`” quando lo strumento non dispone dei valori di irraggiamento e temperatura registrati dal SOLAR-02 e “`IST`” per il salvataggio delle condizioni istantanee a display
    *   `DATA` → indica la data e l’ora in cui il dato è stato salvato nello strumento
    *   `DESCRIZIONE` → indica la descrizione fornita dall’utente in fase di salvataggio del dato
4.  Selezionare il tipo di dato “`IST`”, la voce “`Apri`” e confermare con `ENTER`. Lo strumento mostra la videata seguente
    ```
    15/05/12   15:34:26
    MEM   TIPO
    001   IST   08/04/2012
    002   REG 13/05/2012
    003   *REG 14/05/201 2
    E f f i c i e n z a
    R i c   I V   C   K ,   S i c u r e z z a
    A p r i
    C a n c e l l a   
    Selezione   MEM   -   EF F
    ```
5.  Premere il tasto `ESC/MENU` per tornare alla videata precedente
    ```
    15/05/12   15:35:00
    I r r   7 1 2   W / m 2
    P n o m   3 . 5 0 0   k W
    T c   4 5   ° C
    T e   3 0   ° C
    P d c   3 . 1 2 5   k W
    V d c   3 8 9   V
    I d c   8 . 0 1   A
    n d c   0 . 8 8
    R i s u l t a t i   a n a l i s i I
    Selezione   E F F
    ```
6.  Selezionare il tipo di dato “`REG`”, la voce “`Apri`” e confermare con `ENTER`. Lo strumento mostra la videata dei valori finali del collaudo realizzato e l’indicazione dell’esito finale (SI/NO) del collaudo
7.  Selezionando il tipo di dato “`*REG`”, la voce “`Apri`” e la conferma con `ENTER` lo strumento mostra il messaggio “`Impossibile effettuare l’analisi`” per effetto della mancanza dei valori trasferiti dall’unità SOLAR-02. I valori parziali di questa misura sono visibili solo trasferendo i dati a PC (vedere § 8) tramite software TopView
    ```
    15/05/12   15:35:00
    I r r   7 1 2   W / m 2
    P n o m   3 . 5 0 0   k W
    T c   4 5   ° C
    T e   3 0   ° C
    P d c   3 . 1 2 5   k W
    V d c   3 8 9   V
    I d c   8 . 0 1   A
    n d c   0 . 8 8
    E s i t o   S I
    Selezione   E F F
    ```

#### 7.3.2. Richiamo a display dei risultati di misura IVCK, M  e LOW 

1.  Premere il tasto `ESC/MENU` per tornare al menu principale, selezionare la voce “`MEM`” e premere `ENTER` per entrare nella sezione di visualizzazione dei dati memorizzati. La videata di fianco è mostrata dallo strumento in cui è presente l’elenco delle prove salvate
2.  Usando i tasti freccia (``, ``) e il tasto freccia `` selezionare la voce “`Richiama`” e successivamente “`IVCK, Sicurezza`” e confermare con `ENTER` per la visualizzazione dei soli risultati delle misure di caratteristica I-V
3.  Il campo “`DATA`” indica la data/ora in cui è stato salvato il risultato della misura, il campo “`TIPO`” indica il tipo di test eseguito (LOW , M , IVCK)
    ```
    15/05/12   15:34:26
    MEM   DAT A   TIPO
    001   08/04/201 2   10:38   LOW 
    002   13/04/201 2   12:15   M 
    003   15/05/12   12:20   IVCK
    E f f i c i e n z a
    R i c   I V C K ,   S i c u r e z z a
    A p r i
    C a n c e l l a   
    Selezione   MEM -   I V CK
    ```
4.  Usare il tasto freccia `` per passare all’etichetta “`Commenti`”
5.  Lo strumento visualizzerà il commento inserito dall’operatore durante la procedura di salvataggio del dato (vedere § 7.2) relativamente all’impianto
6.  La presenza del simbolo “`*`” a fianco del numero della misura indica che lo strumento ha effettuate dei test con registrazione dei valori di Irraggiamento e Temperatura tramite unità remota ma tali valori non sono stati trasferiti o non sono disponibili. Per queste misure non saranno disponibili i valori traslati a STC
    ```
    15/06/12   15:34:26
    MEM   Commenti
    001   IMPIANTO ROSSI
    002 *   IMPIANTO BIANCHI
    Selezione   MEM -   IV CK
    ```
7.  Premere `ESC/MENU` per uscire dalla videata e tornare al menu principale

#### 7.3.2.1. Accesso ai dati salvati in memoria – Visualizzazione numerica

1.  Selezionare una riga corrispondente ad una risultato memorizzato e premere il tasto `ENTER`
2.  Selezionare la voce “`Apri`” e premere ancora `ENTER` per entrare nella sezione di visualizzazione dei risultati di misura espressi come:
    *   Videate numeriche dei parametri misurati alle condizioni standard (STC) e alle condizioni operative di prova (OPC) per il test IVCK
    *   Videate numeriche dei parametri misurati nelle misure di isolamento (M ) e continuità (LOW )
    ```
    15/05/12   15:34:26
    MEM   Commenti
    001   IMPIANTO ROSSI
    002   IMPIANTO BIANCHI
    A p r i
    R i c h i a m a   
    C a n c e l l a   
    Selezione   MEM IV CK
    ```
3.  Per il test IVCK sono presenti i valori dei seguenti parametri
    *   Il modulo in uso
    *   Il valore dell’Irraggiamento
    *   Il valore della temperatura del modulo
    *   I valori medi di Voc e Isc alle condizioni OPC
    *   I valori di Voc e Isc misurati a OPC
    *   I valori di Voc e Isc calcolati a STC ed i relativi esiti parziali ottenuti per confronto con i valori nominali.
    ```
    15/05/12   15:34:26
    M o d u l o :   S U N P W R 2 1 0   
    I r r   9 0 3   W / m 2
    T c   ( A U T O )   5 7   ° C
    V o c M e d @ O P C   -   -   -   V
    I s c M e d @ O P C   -   -   -   A
    V o c @ O P C   6 4 7   V
    I s c @ O P C   5 . 3 5   A
    V o c @ S T C   7 8 7   V   O K
    I s c @ S T C   5 . 7 2   A   O K
    Esito OK
    Selezione   I V C K
    ```
4.  Per il test M  in modo CAMPO sono presenti i valori dei seguenti parametri:
    *   Tensione nominale di prova impostata
    *   Limite minimo impostato sulla misura di isolamento
    *   Il tipo di modo selezionato
    *   I valori reali delle tensioni di prova applicate
    *   Il valore di isolamento del polo Positivo Ri (+)
    *   Il valore di isolamento del polo Negativo Ri (-)
    *   Il valore finale Rp del parallelo tra i valori Ri(+) e Ri(-)
    ```
    15/05/12   15:34:26
    V t e s t   :   1 0 0 0   V
    R   i   m i n   :   1 . 0   M   
    M o d o   :   C a m p o
    V t e s t   1 0 6 5   1 0   6 4   V
    R i ( + )   >   1   0 0   M   
    R i (   -   )   >   1   0 0   M   
    R p   7 2   M   
    Esito: OK
    Selezione   M      
    ```
5.  Per il test M  in modo TIMER sono presenti i valori dei seguenti parametri:
    *   Tensione nominale di prova impostata
    *   Limite minimo impostato sulla misura di isolamento
    *   Il tipo di modo selezionato
    *   Il valore reale della tensione di prova applicata
    *   Il valore Ri(+) minimo della resistenza di isolamento del modulo/stringa FV (o di altri oggetti) in prova continuamente misurato per l’intera durata della misura
    *   Il tempo di misura impostato
    ```
    15/05/12   15:34:26
    V t e s t   :   1 0 0 0   V
    R i   m i n   :   1 . 0   M   
    M o d o   :   T i m e r
    V t e s t   1 0 2 0   V
    R i ( + ) m i n   > 2 0 0   M   
    Tempo di prova:   10s
    Esito: OK
    Selezione   M      
    ```

6.  Per il test M  in modo STRINGA sono presenti i valori dei seguenti parametri:
    *   Tensione nominale di prova impostata
    *   Limite minimo impostato sulla misura di isolamento
    *   Il tipo di modo selezionato
    *   Il valore reale della tensione di prova applicata
    *   Il valore Rp della misura ottenuto dal parallelo dei valori di resistenza di isolamento tra i poli Positivo e Negativo e il riferimento di terra confrontato dallo strumento con il valore Ri min impostato
    ```
    15/05/12   15:34:26
    V t e s t   :   1 0 0 0   V
    R l i m   :   1 . 0   M   
    M o d o   :   S t r i n g a
    V t e s t   1 0 2 0   V
    R p   > 1 0 0   M   
    Esito: OK
    Selezione   M      
    ```
7.  Per il test LOW  sono presenti i valori dei seguenti parametri:
    *   Soglia limite impostata per la misura di continuità
    *   Valore della resistenza di calibrazione dei cavi di prova
    *   Il valore della resistenza dell’oggetto in prova
    *   Il valore reale della corrente di prova applicata
    ```
    15/05/12   15:34:26
    R P E   m a x   :   1 . 0   
    R c a l   :   -   -   -   
    R p e   =   0 . 9 9   
    I t e s t   =   2 1 2 .   m A
    Esito: OK
    Selezione   L O W   
    ```

#### 7.3.3. Cancellazione dei dati in memoria

1.  All’interno della lista dei risultati salvati premere il tasto `ENTER` per la visualizzazione dei sottomenu
2.  Selezionare il campo “`Cancella`”, premere il tasto ``. Lo strumento consente di selezionare le voci:
    *   `Canc Ultima` → cancella l’ultima prova salvata
    *   `Canc Tutto` → cancella l’intero contenuto della memoria
3.  Selezionare con i tasti freccia (``, ``) l’opzione desiderata e premere il tasto `ENTER` per confermare la scelta
4.  Premere `ESC/MENU` per uscire dalla videata e tornare al menu principale
    ```
    15/05/12   15:34:26
    MEM   TIPO
    001   IST   08/04/2012
    002   REG 13/04/201 2
    A p r i
    R i c h i   C a n c   U l t i m a
    C a n c   C a n c   T u t t o
    Selezione   MEM EFF
    ```

## 8. COLLEGAMENTO DELLO STRUMENTO A PC

> **ATTENZIONE**
> *   La connessione tra PC e strumento avviene tramite il cavo `C2006`
> *   Per effettuare il trasferimento dati verso un PC è necessario avere preventivamente installato il software di gestione `Topview` scaricabile dal link: `https://www.ht-instruments.com/download`
> *   Prima di effettuare il collegamento è necessario selezionare a PC la porta `COM` utilizzata. Per impostare questi parametri avviare il software `TopView` e consultare l’help in linea del programma all’occorrenza
> *   La porta selezionata non deve essere impegnata da altri dispositivi o applicazioni come mouse, modem, ecc. Chiudere eventualmente processi in esecuzione a partire dalla funzione Task Manager di Windows
> *   La porta ottica emette radiazione LED invisibile. Non osservare direttamente con strumenti ottici. Apparecchio LED di classe `1M` secondo `IEC/EN60825-1`

Per trasferire i dati a PC attenersi alla seguente procedura:
1.  Accendere lo strumento premendo il tasto `ON/OFF`
2.  Collegare lo strumento a PC utilizzando il cavo ottico/USB `C2006` in dotazione
3.  Premere il tasto `ESC/MENU` per aprire il menu principale
4.  Selezionare con i tasti freccia (``, ``) la voce “`PC`” per entrare in modalità trasferimento dati e confermare con `ENTER`
    ```
    15/05/12   15:34:26
    IVCK   Test   m od uli / s tringhe
    L O W      T e s t   c o n t i n u i t à   P E
    M      T e s t   i s o l a m e n t o
    E F F   T e s t   e   f f i c i e n z a
    S E T   I m p o s t a z i o n i
    DB   Archivio   Moduli
    M E M   D a t i   m e m o r i a
    PC   Trasf .   dati   PC
    E N T E R   p e r   s e l e z .
    M E N U
    ```
5.  Lo strumento fornisce la videata seguente:
    ```
    15/05/12   15:34:26
    COLLEGAMENTO A PC
    M E N U
    ```
6.  Usare i comandi del software TopView per attivare il trasferimento dati (consultare l’help in linea del programma)

## 9. MANUTENZIONE

### 9.1. GENERALITÀ

Lo strumento da Lei acquistato è uno strumento di precisione. Durante l’utilizzo e l’immagazzinamento rispettare le raccomandazioni elencate in questo manuale per evitare possibili danni o pericoli durante l’utilizzo.
Non utilizzare lo strumento in ambienti caratterizzati da elevato tasso di umidità o temperatura elevata. Non esporre direttamente alla luce del sole.
Spegnere sempre lo strumento dopo l’utilizzo. Se si prevede di non utilizzarlo per un lungo periodo di tempo, rimuovere le batterie per evitare da parte di queste ultime fuoruscite di liquidi che possono danneggiare i circuiti interni dello strumento.

### 9.2. SOSTITUZIONE BATTERIE

Quando sul display LCD appare il simbolo di batteria scarica “` `” oppure quando durante una prova si ha il messaggio “`batteria scarica`” a display, sostituire le batterie interne

> **ATTENZIONE**
> Solo tecnici qualificati possono effettuare questa operazione. Prima di effettuare questa operazione assicurarsi di aver rimosso tutti i cavi dai terminali di ingresso.

1.  Spegnere lo strumento premendo a lungo il pulsante di accensione
2.  Rimuovere i cavi dai terminali di ingresso
3.  Svitare la vite di fissaggio del coperchio dal vano batterie e rimuovere lo stesso
4.  Rimuovere dal vano batterie tutte le batterie e sostituirle solo con batterie tutte nuove e tutte del tipo corretto (vedere § 10.5) rispettando le polarità indicate
5.  Riposizionare il coperchio vano batterie e fissarlo con l'apposita vite
6.  Non disperdere nell’ambiente le batterie utilizzate. Usare gli appositi contenitori per lo smaltimento

### 9.3. PULIZIA DELLO STRUMENTO

Per la pulizia dello strumento utilizzare un panno morbido e asciutto. Non usare mai panni umidi, solventi, acqua, ecc.

### 9.4. FINE VITA

> **ATTENZIONE**: il simbolo riportato indica che l'apparecchiatura, i suoi accessori e le batterie interne devono essere raccolti separatamente e trattati in modo corretto.

## 10. SPECIFICHE TECNICHE

### 10.1. CARATTERISTICHE TECNICHE EFFICIENZA INSTALLAZIONI FV

L’incertezza è indicata come [`% lettura + (num. cifre) * risoluzione`] a 23°C ± 5°C, <80%HR

**Tensione DC**

| Campo [V] | Risoluzione [V] | Incertezza                  |
| :-------- | :-------------- | :-------------------------- |
| 5.0  199.9 | 0.1             |  (1.0 % lettura + 2cifre) |
| 200.0  999.9 | 0.5             |                             |

**Corrente DC (tramite trasduttore a pinza esterno)**

| Campo [mV]      | Risoluzione [mV] | Incertezza                  |
| :-------------- | :--------------- | :-------------------------- |
| -1100  -5      | 0.1              |  (0.5 % lettura + 0.6 mV) |
| 5  1100        |                  |                             |

Il valore della corrente è visualizzato SEMPRE con segno positivo: Il valore di corrente tradotto in tensione inferiore a 5mV è azzerato

| FS pinze DC [A] | Risoluzione [A] | Valore minimo letto [A] |
| :-------------- | :-------------- | :---------------------- |
| 1< FS  10      | 0.001           | 0.05                    |
| 10< FS  100    | 0.01            | 0.5                     |
| 100< FS  1000  | 0.1             | 5                       |

**Potenza DC (Vmis > 150V)**

| FS pinza [A] | Campo [W]          | Risoluzione [W] | Incertezza                             |
| :----------- | :----------------- | :-------------- | :------------------------------------- |
| 1< FS  10   | 0.000k  9.999k    | 0.001k          |  (1.5 % lettura + 3 cifre) (Imis < 10%FS)<br> (1.5 % lettura) (Imis  10%FS) |
| 10< FS  100 | 0.00k  99.99k     | 0.01k           |                                        |
| 100< FS  1000 | 0.0k  999.9k      | 0.1k            |                                        |

`Vmis = tensione a cui è misura la potenza ; Imis = corrente misurata`

**Irraggiamento (con cella di riferimento HT304k)**

| Campo [mV] | Risoluzione [mV] | Incertezza                  |
| :--------- | :--------------- | :-------------------------- |
| 1  40.0   | 0.02             |  (1.0 % lettura + 0.1mV) |

**Temperatura (con sonda di tipo PT 300N)**

| Campo [°C]      | Risoluzione [°C] | Incertezza                |
| :-------------- | :--------------- | :------------------------ |
| -20.0  100.0   | 0.1              |  (1.0 % lettura + 1°C) |

### 10.2. CARATTERISTICHE TECNICHE FUNZIONE IVCK

**Tensione DC @ OPC**

| Campo [V] | Risoluzione [V] | Incertezza                  |
| :-------- | :-------------- | :-------------------------- |
| 5.0  199.9 | 0.1             |  (1.0 % lettura + 2cifre) |
| 200.0  999.9 | 0.5             |                             |

`Tensione VPN minima per avviare la prova :15V`

**Corrente DC @ OPC**

| Campo [A] | Risoluzione [A] | Incertezza                  |
| :-------- | :-------------- | :-------------------------- |
| 0.10  15.00 | 0.01            |  (1.0 % lettura + 2cifre) |

**Tensione DC @ STC**

| Campo [V] | Risoluzione [V] | Incertezza                  |
| :-------- | :-------------- | :-------------------------- |
| 5.0  199.9 | 0.1             |  (4.0 % lettura + 2cifre) |
| 200  999   | 1               |                             |

**Corrente DC @ STC**

| Campo [A] | Risoluzione [A] | Incertezza                  |
| :-------- | :-------------- | :-------------------------- |
| 0.10  15.00 | 0.01            |  (4.0 % lettura + 2cifre) |

**Irraggiamento (con cella di riferimento HT304k)**

| Campo [mV] | Risoluzione [mV] | Incertezza                  |
| :--------- | :--------------- | :-------------------------- |
| 1  40.0   | 0.02             |  (1.0 % lettura + 0.1mV) |

**Temperatura (con sonda di tipo PT 300N)**

| Campo [°C]      | Risoluzione [°C] | Incertezza                |
| :-------------- | :--------------- | :------------------------ |
| -20.0  100.0   | 0.1              |  (1.0 % lettura + 1°C) |

> **ATTENZIONE**
> Non utilizzare lo strumento per test IVCK su moduli FV con efficienza >19%. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento.

### 10.3. CARATTERISTICHE TECNICHE SICUREZZA ELETTRICA

**Continuità conduttori di protezione (LOW )**

| Campo [] | Risoluzione [] | Incertezza                  |
| :-------- | :-------------- | :-------------------------- |
| 0.00  1.99 | 0.01            |  (2.0 % lettura + 2cifre) |
| 2.0  19.9 | 0.1             |                             |
| 20  199  | 1               |                             |

`Corrente di prova >200mA DC fino a 5  (cavi inclusi), risoluzione 1mA, incertezza  (5.0%lettura + 5cifre)`
`Tensione a vuoto 4 < V0 < 10 V`

**Resistenza di isolamento (M ) – Modo TIMER**

| Tensione di prova [V] | Campo [M ] | Risoluzione [M ] | Incertezza                  |
| :-------------------- | :---------- | :---------------- | :-------------------------- |
| 250, 500, 1000        | 0.01  1.99 | 0.01              |  (5.0 % lettura + 5cifre) |
|                       | 2.0  19.9  | 0.1               |                             |
|                       | 20  199    | 1                 |                             |

`Tensione a vuoto <1.25 x tensione di prova nominale`
`Corrente di cortocircuito < 15mA (picco) per ogni tensione di prova`
`Tensione generata risoluzione 1V, incertezza  (5.0%lettura + 5cifre) @ Rmis> 0.5% FS`
`Corrente di misura nominale > 1mA su 1k  @ Vnom`

**Resistenza di isolamento (M ) – Modi CAMPO (*), STRINGA (**)**

| Tensione di prova [V] | Campo [M ] | Risoluzione [M ] | Incertezza (***)          |
| :-------------------- | :---------- | :---------------- | :------------------------ |
| 250, 500, 1000        | 0.1  1.9   | 0.1               |  (20.0 % lettura + 5cifre) |
|                       | 2  99      | 1                 |                           |

`(*) Per modo CAMPO se VPN >1V la tensione minima VEP e VEN per il calcolo di Ri(+) e Ri(-) è 1V`
`(**) Per modo STRINGA tensione VPN minima per avviare la prova :15V`
`Tensione a vuoto <1.25 x tensione di prova nominale`
`Corrente di cortocircuito < 15mA (picco) per ogni tensione di prova`
`Tensione generata risoluzione 1V, incertezza  (5.0%lettura + 5cifre) @ Rmis> 0.5% FS`
`Corrente di misura nominale > 1mA su 1k  @ Vnom`
`(**) Per modo CAMPO: Aggiungere 5 cifre all’incertezza se : [Max (R+,R-) / Min (R+,R-) ≥ 100]`

### 10.4. NORMATIVE DI RIFERIMENTO

#### 10.4.1. Generali

*   **Sicurezza strumento**: IEC/EN61010-1
*   **EMC**: IEC/EN61326-1
*   **Sicurezza accessori di misura**: IEC/EN61010-031
*   **Misure**: Guida CEI 82-25 (Efficienza FV), IEC/EN 62446 (IVCK, LOW , M )
*   **Isolamento**: doppio isolamento
*   **Grado di inquinamento**: 2
*   **Categoria di misura**: CAT III 300V verso terra, Max 1000V DC tra gli ingressi P, N, E, C

### 10.5. CARATTERISTICHE GENERALI

*   **Display e memoria**
    *   Tipo display: LCD custom, 128x128 pxl, retroilluminato
    *   Dati memorizzabili: max 999
    *   Interfaccia PC: ottica/USB
*   **Caratteristiche modulo radio**
    *   Campo di frequenza: 2.400  2.4835GHz
    *   Categoria R&TTE: Classe 1
    *   Potenza max di trasmissione: 30 µW
    *   Distanza max collegamento RF: 1m
*   **Efficienza impianti FV**
    *   Periodo di integrazione: 5,10,30,60,120,300,600,900,1800,3600s
    *   Memoria SOLAR-02: circa 1.5 ore (@ PI = 5s), circa 8 gg (@ PI = 600s)
*   **Alimentazione**
    *   Tipo batterie: 6x1.5V alcaline tipo AA LR06 MN1500
    *   Indicazione batteria scarica: simbolo “` `” mostrato a display
    *   Durata batterie: circa 120 ore (efficienza FV)
    *   Autospegnimento: dopo 5 minuti di non utilizzo
*   **Caratteristiche meccaniche**
    *   Dimensioni (L x La x H): 235 x 165 x 75mm
    *   Peso (batterie incluse): 1.2kg
    *   Protezione meccanica: IP40

### 10.6. CONDIZIONI AMBIENTALI DI UTILIZZO

*   Temperatura di riferimento: 23°C ± 5°C
*   Temperatura di utilizzo: 0°C ÷ 40°C
*   Umidità relativa ammessa: <80%RH
*   Temperatura di conservazione: -10°C ÷ 60°C
*   Umidità di immagazzinamento: <80%RH
*   Max altitudine di utilizzo: 2000m

Questo strumento è conforme ai requisiti della Direttiva Europea sulla bassa tensione 2014/35/EU (LVD) e della direttiva EMC 2014/30/EU.
Questo strumento è conforme ai requisiti della direttiva europea 2011/65/EU (RoHS) e della direttiva europea 2012/19/EU (WEEE).

### 10.7. ACCESSORI

Vedere packing list allegata.

## 11. APPENDICE – CENNI TEORICI

### 11.1. TEST DI EFFICIENZA IMPIANTI FV

In accordo con quanto previsto dalla normativa vigente la misura di efficienza DC su una installazione FV è funzione del tipo di correzione adottato per compensare gli effetti della temperatura del modulo e della relazione matematica utilizzata per calcolare il parametro `nDC` (vedere § 5.2.3).

**Correzione "Tmod"**
*   **Valore di Tcel**: `Tcel = Valore della Temp. moduli misurata`
*   **Relazione matematica per calcolo nDC**:
    ```
    fv2
    gamma
    R
     1 - (Tcel - 40) * --- se Tcel <= 40 °C
                     100
    
     1 - (Tcel - 40) * --- se Tcel > 40 °C
                     100
    ```
    da cui
    ```
    nDC = (Pdc / Pnom) * (Gstc / Gp) * Rfv2
    ```
*   **Norma**: Guida CEI 82-25
*   **Esito**: OK/NO

**Correzione "Tenv"**
*   **Valore di Tcel**: `Tcel = Val. della Temp. moduli calcolata : Tcel = Tamb + (Gp / 800) * NOCT - 20)`
*   **Relazione matematica per calcolo nDC**:
    ```
    nDC = (Pdc / Pnom) * (Gstc / Gp) * [1 + gamma/100 * (Tcel - 25)]
    ```

**Correzione "nDC"**
*   **Valore della Temperatura moduli misurata**:
    ```
    nDC = (Pdc / Pnom) * (Gstc / Gp) * [1 + gamma/100 * (Tcel - 25)]
    ```

dove:

| Simbolo  | Descrizione                                                                                              | Unità di misura |
| :------- | :------------------------------------------------------------------------------------------------------- | :-------------- |
| Gp       | Irraggiamento misurato sul piano dei moduli                                                              | [W/m2]          |
| Gstc     | Irraggiamento in condizione Standard = 1000                                                              | [W/m2]          |
| Pn       | Potenza nominale = somma delle Pmax dei moduli FV facenti parte della sezione dell’impianto in esame   | [kW]            |
| Pdc      | Potenza DC misurata in uscita dal generatore FV                                                          | [kW]            |
| Rfv2     | Coefficiente correttivo funzione della Temperatura delle Celle FV (Tcel) misurata o calcolata in accordo al tipo di relazione di correzione selezionata |                 |
|         | Valore assoluto del coefficiente termico della Pmax dei moduli FV facenti parte della sezione impianto in esame. | [%/°C]          |
| NOCT     | (Normal Operating Cell Temperature) = Temperatura a cui si portano le celle in condizioni di riferimento (800W/m2, 20°C, AM=1.5, vel. Aria =1m/s). | [%/°C]          |

Le precedenti relazioni sono valide nelle condizioni `Irraggiamento > Irraggiamento min` (vedi manuale d’uso strumento MASTER) e di “irraggiamento stabile” cioè per ogni campione rilevato, con `IP <= 1min`, la differenza tra i valori massimi e minimi di irraggiamento misurati deve essere `< 20W/m2`.

In generale l’esito potrà essere:
*   `Impossibile effettuare l’analisi` se l’irraggiamento non ha mai raggiunto un valore stabile superiore alla soglia minima impostata oppure se non esiste nessun valore valido durante tutto l’arco della registrazione (`nDC > 1.15`)
*   `ESITO SI` (correz. “Tmod” o “Tamb”): se esiste almeno 1 valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
*   `ESITO NO` (correz. “Tmod” o “Tamb”): se NON esiste nessun valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
*   Non visualizzerà nessun esito (SI o NO) se lo strumento è stato impostato con correzione di temperatura tipo “`nDC`”.

**Esito visualizzato OK (correz. “Tmod” o “Tenv”)**

Lo strumento fornisce un esito complessivo positivo in accordo alla Guida CEI 82-25, se, nell’insieme dei campioni rilevati durante il collaudo, ne esiste almeno uno valido per cui il valore calcolato dell’efficienza `nDC` (in base alle precedenti relazioni) è superiore al valore della soglia di riferimento impostata dall’utente in fase di programmazione (vedere § 5.2.2). Se esistono più campioni che soddisfano tutte le condizioni precedenti, lo strumento visualizza automaticamente quello corrispondente al massimo valore di `nDC`.

**Esito visualizzato NO (correz. “Tmod” o “Tenv”)**

Lo strumento fornisce un esito complessivo positivo in accordo alla Guida CEI 82-25, se, nell’insieme dei campioni rilevati durante il collaudo, ne esiste almeno uno valido per cui il valore calcolato dell’efficienza `nDC` (in base alle precedenti relazioni) è inferiore al valore della soglia di riferimento impostata dall’utente in fase di programmazione (vedere § 5.2.2). Se esistono più campioni che NON soddisfano tutte le condizioni precedenti, lo strumento visualizza automaticamente quello corrispondente al massimo valore di `nDC`.

**Nessun esito (correzione “nDC”)**

Lo strumento fornisce come risultato i valori corrispondenti al punto di massimo `nDC` calcolato come:
`nDC = (Pdc / Pnom) * (Gstc / Gp) * [1 + gamma/100 * (Tcel - 25)]`
(per il significato delle definizioni e dei simboli si veda il § precedente)

## 12. ASSISTENZA

### 12.1. CONDIZIONI DI GARANZIA

Questo strumento è garantito contro ogni difetto di materiale e fabbricazione, in conformità con le condizioni generali di vendita. Durante il periodo di garanzia, le parti difettose possono essere sostituite, ma il costruttore si riserva il diritto di riparare ovvero sostituire il prodotto. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballo originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente. Il costruttore declina ogni responsabilità per danni causati a persone o oggetti.

La garanzia non è applicata nei seguenti casi:
*   Riparazione e/o sostituzione accessori e batteria (non coperti da garanzia).
*   Riparazioni che si rendono necessarie a causa di un errato utilizzo dello strumento o del suo utilizzo con apparecchiature non compatibili.
*   Riparazioni che si rendono necessarie a causa di un imballaggio non adeguato.
*   Riparazioni che si rendono necessarie a causa di interventi eseguiti da personale non autorizzato.
*   Modifiche apportate allo strumento senza esplicita autorizzazione del costruttore.
*   Utilizzo non contemplato nelle specifiche dello strumento o nel manuale d’uso.

Il contenuto del presente manuale non può essere riprodotto in alcuna forma senza l’autorizzazione del costruttore.
I nostri prodotti sono brevettati e i marchi depositati. Il costruttore si riserva il diritto di apportare modifiche alle specifiche ed ai prezzi se ciò è dovuto a miglioramenti tecnologici.

### 12.2. ASSISTENZA

Se lo strumento non funziona correttamente, prima di contattare il servizio di assistenza, controllare lo stato delle batterie e dei cavi e sostituirli se necessario. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballaggio originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente.

**HT ITALIA SRL**
Via della Boaria, 40
48018 – Faenza (RA) – Italy
T +39 0546 621002 | F +39 0546 621144
M ht@ht-instruments.com | www.ht-instruments.it

**WHERE WE ARE**

**HT INSTRUMENTS SL**
C/ Legalitat, 89
08024 Barcelona – Spain
T +34 93 408 17 77 | F +34 93 408 36 30
M info@htinstruments.es | www.ht-instruments.com/es-es/

**HT INSTRUMENTS GmbH**
Am Waldfriedhof 1b
D-41352 Korschenbroich – Germany
T +49 (0) 2161 564 581 | F +49 (0) 2161 564 583
M info@ht-instruments.de | www.ht-instruments.de
