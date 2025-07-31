# SOLARIVe

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-16 -->
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
        5.1.3. Data Ora
        5.1.4. Unità Remota/Solarim.
        5.1.5. Irraggiamento
        5.1.6. Pinza DC (**SOLAR I - Vw** e **SOLAR I - Ve**)
    5.2. CLD – Impostazioni collaudo impianti FV (**SOLAR I - Vw**, **SOLAR I - Ve**)
        5.2.1. Impostazioni per Impianti FV con Inverter Mono MPPT - Uscita AC monofase
            5.2.1.1. Impostazione Strumento
            5.2.1.2. Parametri Impianto
        5.2.2. Impostazioni per Imp. FV con inverter Mono/Multi MPPT - Uscita AC mono/trifase
            5.2.2.1. Impostazione Strumento
            5.2.2.2. Parametri Impianto
            5.2.2.3. Stato MPP300
        5.2.3. Selezione della relazione di compensazione degli effetti della Temperatura
    5.3. DB – Gestione database moduli
        5.3.1. Definizione di un nuovo modulo FV
        5.3.2. Modifica di un modulo FV esistente
        5.3.3. Cancellazione di un modulo FV esistente
6.  ISTRUZIONI OPERATIVE
    6.1. Collaudo Impianti FV (**SOLAR I - Vw**, **SOLAR I - Ve**)
        6.1.1. Collaudo Impianti FV con Inverter Mono MPPT - Uscita AC monofase
        6.1.2. Collaudo Impianti FV con inverter Mono/Multi MPPT - Uscita AC mono/trifase
    6.2. Misura della Caratteristica I - V
        6.2.1. Rilievo curva I - V con misura Irr/Temp effettuata direttamente da strumento
        6.2.2. Rilievo curva I - V con misura Irr/Temp effettuata tramite unità **SOLAR - 02**
            6.2.2.1. Rilievo curva I - V tramite unità **SOLAR - 02** in connessione RF
            6.2.2.2. Rilievo curva I - V tramite unità **SOLAR - 02** in registrazione sincrona
        6.2.3. Interpretazione dei risultati di misura
    6.3. TEST RAPIDO moduli e stringhe FV (IVCK)
        6.3.1. Generalità
        6.3.2. Impostazioni preliminari
        6.3.3. Test Rapido IVCK senza misura di Irraggiamento
        6.3.4. Test Rapido IVCK con misura di Irraggiamento
        6.3.5. Reset Media
    6.4. Elenco dei messaggi a display
7.  MEMORIZZAZIONE RISULTATI
    7.1. Salvataggio delle misure di collaudi FV (**SOLAR I - Vw**, **SOLAR I - Ve**)
    7.2. Salvataggio delle misure di caratteristica I - V
    7.3. Operazioni con risultati
        7.3.1. Richiamo a display dei risultati di collaudi FV (**SOLAR I - Vw**, **SOLAR I - Ve**)
        7.3.2. Richiamo a display dei risultati di misura caratteristica I - V
            7.3.2.1. Accesso ai dati salvati in memoria – Visualizzazione numerica
            7.3.2.2. Accesso ai dati salvati in memoria – Visualizzazione grafica curva I - V
            7.3.2.3. Accesso ai dati salvati in memoria – Visualizzazione grafica potenza
        7.3.3. Cancellazione dei dati in memoria
8.  COLLEGAMENTO DELLO STRUMENTO A PC
    8.1. Collegamento tramite cavo ottico/USB C2006
    8.2. Collegamento tramite WiFi
9.  MANUTENZIONE
    9.1. Generalità
    9.2. Sostituzione batterie
    9.3. Pulizia dello strumento
    9.4. Fine vita
10. SPECIFICHE TECNICHE
    10.1. Specifiche tecniche collaudo impianti FV (**SOLAR I - Vw**, **SOLAR I - Ve**)
    10.2. Caratteristiche tecniche funzione I - V e IVCK
    10.3. Norme di sicurezza
        10.3.1. Generalità
    10.4. Caratteristiche generali
    10.5. Condizioni ambientali di utilizzo
    10.6. Accessori
11. APPENDICE – CENNI TEORICI
    11.1. Collaudo degli impianti FV (**SOLAR I - Vw**, **SOLAR I - Ve**)
    11.2. Cenni su MPPT (Maximum Power Point Tracker)
    11.3. Misura della caratteristica I - V
        11.3.1. Aspetti teorici sulla misura della Caratteristica I - V
        11.3.2. Errori tipici sulla misura di curva I - V e possibili soluzioni
12. ASSISTENZA
    12.1. Condizioni di garanzia
    12.2. Assistenza

---

# 1. PRECAUZIONI E MISURE DI SICUREZZA
Nel seguito del manuale con la parola “strumento” si intendono genericamente i modelli **I - V400w**, **I - V500w**, **SOLAR I - Vw** e **SOLAR I - Ve** salvo notazione specifica all’occorrenza indicata. Lo strumento è stato progettato in conformità alla direttiva IEC/EN61010-1 relativa agli strumenti di misura elettronici. Prima e durante l’esecuzione delle misure attenersi alle seguenti indicazioni e leggere con particolare attenzione tutte le note precedute dal simbolo •

*   Non effettuare misure di tensione o corrente in ambienti umidi
*   Non effettuare misure in presenza di gas o materiali esplosivi, combustibili o in ambienti polverosi
*   Evitare contatti con il circuito in esame se non si stanno effettuando misure
*   Evitare contatti con parti metalliche esposte, con terminali di misura inutilizzati, circuiti
*   Non effettuare alcuna misura qualora si riscontrino anomalie nello strumento come, deformazioni, fuoriuscite di sostanze, assenza di visualizzazione sul display, ecc…
*   Utilizzare solo gli accessori originali HT

Nel presente manuale e sullo strumento sono utilizzati i seguenti simboli:

**Attenzione:** attenersi alle istruzioni riportate nel manuale; un uso improprio potrebbe causare danni allo strumento o ai suoi componenti
**Pericolo alta tensione:** rischi di shock elettrici
**Doppio isolamento**
**Tensione o corrente DC**
**Tensione o corrente AC**
**Riferimento di terra**

## 1.1. ISTRUZIONI PRELIMINARI
*   Questo strumento è stato progettato per l’utilizzo in condizioni ambientali specificate al § 10.5. Non operare in condizioni ambientali differenti
*   Lo strumento può essere utilizzato per misure di **TENSIONE** e **CORRENTE** in CAT II 1000V DC o CAT III 300V verso terra, massima Tensione fra gli Ingressi 1000VDC (**I - V400w** e **SOLAR I - Vw**) o 1500VDC (**I - V500w** e **SOLAR I - Ve**). Non operare su circuiti che superino i limiti specificati al § 10.1 e § 10.2

> **ATTENZIONE**
> Non utilizzare lo strumento per misure di Curve I - V e test IVCK su moduli FV con efficienza > 19%. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento

*   La invitiamo a seguire le normali regole di sicurezza orientate alla protezione contro correnti pericolose e proteggere lo strumento contro un utilizzo errato
*   Solo gli accessori forniti a corredo dello strumento garantiscono gli standard di sicurezza. Essi devono essere in buone condizioni e sostituiti, se necessario, con modelli identici
*   Controllare che le batterie siano inserite correttamente
*   Prima di collegare i cavi di misura al circuito in esame, controllare che sia stata selezionata la funzione desiderata

## 1.2. DURANTE L’UTILIZZO
La preghiamo di leggere attentamente le raccomandazioni e le istruzioni seguenti:

> **ATTENZIONE**
> *   La mancata osservazione delle avvertenze e/o istruzioni può danneggiare lo strumento e/o i suoi componenti o essere fonte di pericolo per l’operatore
> *   Il simbolo "full battery symbol" indica il livello di carica completo delle batterie interne. Quando il livello di carica scende a livelli minimi il simbolo "low battery symbol" è mostrato a display. In questo caso interrompere le prove e procedere alla sostituzione delle batterie in accordo a quanto descritto nel § 9.2
> *   Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie

## 1.3. DOPO L’UTILIZZO
Quando le misure sono terminate, spegnere lo strumento mantenendo premuto il tasto **ON/OFF** per alcuni secondi. Se si prevede di non utilizzare lo strumento per un lungo periodo rimuovere le batterie ed attenersi a quanto specificato nel § 3.3.

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

# 2. DESCRIZIONE GENERALE

## 2.1. INTRODUZIONE
Lo strumento è stato progettato per la realizzazione delle operazioni di collaudo su installazioni FV Monofase (Trifase con accessorio opzionale **MPP300**) dal punto di vista dei controlli di efficienza in accordo alle prescrizioni della Guida CEI 82-25 (**SOLAR I - Vw** e **SOLAR I - Ve**) e per test di caratteristiche I - V nei moduli/stringhe fotovoltaici (FV) al fine di verificare i parametri di riferimento dichiarati dal costruttore.

## 2.2. FUNZIONALITÀ DELLO STRUMENTO
**Collaudo di impianti FV Monofase** (CLD – **SOLAR I - Vw** e **SOLAR I - Ve**)
*   Misura tensione e corrente DC (1000V per **SOLAR I - Vw**, 1500V per **SOLAR I - Ve**)
*   Misura tensione e corrente AC TRMS
*   Misura potenze DC/AC
*   Misura irraggiamento [W/m²] tramite cella di riferimento connessa a unità **SOLAR - 02**
*   Misura temperatura moduli e ambiente tramite sonda connessa a **SOLAR - 02**
*   Applicazione delle relazioni di compensazione dell’Efficienza DC
*   Valutazione immediata esito OK/NO di un collaudo
*   Registrazione parametri di un impianto FV con PI programmabile da 5s a 60min

**Collaudo di impianti FV Mono/Trifase** (MPP – **SOLAR I - Vw** / **SOLAR I - Ve** + **MPP300**)
*   Misura 3 tensioni e correnti DC
*   Misura potenze stringhe DC e totale DC
*   Misura 3 tensioni e correnti AC TRMS
*   Misura potenza totale AC
*   Misura irraggiamento [W/m²] tramite cella di riferimento connessa a unità **SOLAR - 02**
*   Misura temperatura moduli e ambiente tramite sonda connessa a **SOLAR - 02**
*   Applicazione delle relazioni di compensazione dell’Efficienza DC
*   Valutazione immediata esito OK/NO di un collaudo
*   Registrazione parametri di un impianto FV con PI programmabile da 5s a 60min

**Misura caratteristica Corrente - Tensione (I - V)**
*   Tensione / corrente / potenza modulo/stringa 1000VDC, 15A DC (**SOLAR I - Vw**, **I - V400w**)
*   I - V/potenza modulo/stringa 1500VDC - 10ADC o 1000VDC - 15ADC (**SOLAR I - Ve**, **I - V500w**)
*   Attivazione misura in modo Manuale e Automatico
*   Misura della temperatura del modulo/stringa
*   Misura irraggiamento [W/m²] tramite cella di riferimento
*   Visualizzazione numerica e grafica della caratteristica I - V con metodo di misura a 4 fili
*   Confronto diretto con i valori nominali riferiti a STC ed esito OK / NO della verifica
*   Database interno personalizzabile per la gestione fino a 30 moduli FV
*   Valutazione del degrado annuo di moduli/stringhe/campi FV
*   Memoria interna per salvataggio dati
*   Interfacce ottica/USB e WiFi per trasferimento dati a PC

**Misure rapide di pre - collaudo** (IVCK)
*   Misure rapide di Tensione a vuoto e corrente di cortocircuito FV fino a 1000V DC, 15A (**SOLAR I - Vw**, **I - V400w**) e fino a 1500V DC, 15A (**SOLAR I - Ve**, **I - V500w**)
*   Attivazione misura in modo Manuale e Automatico
*   Valutazione immediata (OK/NO) dei risultati ottenuti

Il modello dispone della funzione di retroilluminazione del display, la possibilità di regolazione interna del contrasto e un tasto **HELP** in grado di fornire a display un aiuto all’operatore nella fase di collegamento dello strumento all’impianto. Una funzione di autospegnimento è disponibile dopo circa 5 minuti di non utilizzo dello strumento.

# 3. PREPARAZIONE ALL’UTILIZZO

## 3.1. CONTROLLI INIZIALI
Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili affinché lo strumento potesse essere consegnato senza danni. Tuttavia si consiglia di controllarlo per accertare eventuali danni subiti durante il trasporto. Qualora si dovessero riscontrare anomalie contattare immediatamente il rivenditore.
Si consiglia inoltre di controllare che l’imballaggio contenga tutte le parti indicate al § 0. In caso di discrepanze contattare il rivenditore. Qualora fosse necessario restituire lo strumento si prega di seguire le istruzioni riportate al § 12.

## 3.2. ALIMENTAZIONE DELLO STRUMENTO
Lo strumento è alimentato a batteria. Per modello ed autonomia delle batterie vedere § 10.4. Il simbolo "full battery symbol" indica il livello di carica completo delle batterie interne. Quando il livello di carica scende a livelli minimi il simbolo "low battery symbol" è mostrato a display. In questo caso interrompere le prove e procedere alla sostituzione delle batterie in accordo a quanto descritto nel § 9.2.
Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie.
Lo strumento dispone di sofisticati algoritmi per aumentare al massimo l'autonomia delle batterie. Una breve pressione del tasto **backlight symbol** attiva la retroilluminazione del display. Al fine di salvaguardare l’efficienza delle batterie la retroilluminazione si spegne automaticamente dopo circa 30 secondi.
L'utilizzo sistematico della retroilluminazione diminuisce l'autonomia delle batterie.

## 3.3. CONSERVAZIONE
Per garantire misure precise, dopo un lungo periodo di permanenza in magazzino in condizioni ambientali estreme, attendere che lo strumento ritorni alle condizioni normali (vedere § 10.5).

# 4. NOMENCLATURA

## 4.1. DESCRIZIONE DELLO STRUMENTO
**LEGENDA:**
1.  Ingressi
2.  Display
3.  Connettore per uscita ottica/USB
4.  Tasti freccia/ **ENTER**
5.  Tasto **GO/STOP**
6.  Tasto **SAVE**
7.  Tasto **ON/OFF**
8.  Tasto **HELP** / **backlight symbol**
9.  Tasto **ESC/MENU**
Fig. 1: Descrizione parte frontale dello strumento

**LEGENDA:**
1.  Ingresso per sonda misura irraggiamento (I - V) / pinza di corrente DC (CLD – **SOLAR I - Vw**, **SOLAR I - Ve**)
2.  Ingresso per sonda misura temperatura ausiliaria (I - V) / pinza per corrente AC (CLD – **SOLAR I - Vw**, **SOLAR I - Ve**)
3.  Ingressi C1, C2 per misura corrente (I - V) / misura tensione DC (CLD – **SOLAR I - Vw**, **SOLAR I - Ve**)
4.  Ingressi P1, P2 per misura tensione (I - V) / tensione AC (CLD – **SOLAR I - Vw**, **SOLAR I - Ve**)
Fig. 2: Descrizione parte superiore dello strumento

**LEGENDA:**
1.  Connettore per collegamento cavo di uscita optoisolata ottico/USB
Fig. 3: Descrizione parte laterale dello strumento

## 4.2. DESCRIZIONE DELLA TASTIERA
La tastiera è costituita dai seguenti tasti:
*   Tasto **ON/OFF** per accendere e spegnere lo strumento
*   Tasto **ESC/MENU** per uscire dalla videata corrente senza confermare le modifiche e per tornare al menu principale
*   Tasti **   ** per spostare il cursore all’interno delle varie schermate allo scopo di selezionare i parametri di programmazione
*   Tasto **ENTER** per confermare le modifiche, i parametri di programmazione selezionati e per selezionare da menu la funzione alla quale accedere
*   Tasto **GO/STOP** per avviare la misurazione
*   Tasto **SAVE** per salvare la misura
*   Tasto **HELP** (pressione prolungata) per accedere all’help on line visualizzando le possibili connessioni tra strumento ed impianto
*   Tasto **backlight symbol** (semplice pressione) per attivare la retroilluminazione del display

## 4.3. DESCRIZIONE DEL DISPLAY
Il display è un modulo grafico con risoluzione 128 x 128 punti.
Nella prima riga del display viene visualizzata la data/ora di sistema e l'indicatore dello stato batterie.
Nella parte bassa è invece indicata la funzionalità del Tasto **ENTER** e la modalità attiva.
Il simbolo **active radio connection symbol** indica la presenza di un collegamento radio attivo con l’unità remota selezionata (**SOLAR - 02** o **MPP300**).
Il simbolo **flashing radio connection symbol** intermittente indica la ricerca in corso di un collegamento radio con l’unità remota selezionata (**SOLAR - 02** o **MPP300**).

```
15/05/10   15:34:26
Selezione
```

## 4.4. VIDEATA INIZIALE
All’accensione dello strumento viene visualizzata per qualche secondo la videata iniziale. In essa sono visualizzati:
*   Il modello dello strumento
*   Il costruttore
*   Presenza del modulo di comunicazione radio interna abilitato (RF) e del modulo WiFi
*   Il numero di serie dello strumento (SN:)
*   La versione del firmware presente nella memoria dello strumento (FW:)
*   La data in cui è avvenuta l’ultima calibrazione dello strumento (Data calibrazione:)

```
S O L A R
I   -   V   w
H T
R F   -   W i   S N : 1   5   3 4 5 6 7 8
FW:   7 .0 7   H4
Data calibrazione:
0 9 /0 2 /20 1 6
```
Dopo alcuni istanti lo strumento passa all'ultima funzione selezionata.

# 5. MENU GENERALE
La pressione del tasto **ESC/MENU**, in qualunque condizione si trovi lo strumento, provoca la comparsa della videata del menu generale attraverso la quale è possibile impostare lo strumento, visualizzare le misure memorizzate, e selezionare la misurazione desiderata (la voce **CLD** appare solo per **SOLAR I - Vw** e **SOLAR I - Ve**).
Selezionando con il cursore una delle opzioni e confermando con **ENTER** si accede alla funzione desiderata

```
15/05/10   15:34:26
I   -   V   Ca ratt.   I - V
C L D   C o l l a u d o
S E T   I m p o s t a z i o n i
DB   Moduli
MEM   Dati memoria
PC   Colleg. con PC
E N T E R   p e r   s e l   e z .
M E N U
```

## 5.1. SET – IMPOSTAZIONE DELLO STRUMENTO
Posizionare il cursore sulla voce **SET** utilizzando i tasti freccia (****, ****) e confermare con **ENTER**. A display appare la videata che elenca le varie impostazioni dello strumento.
Le impostazioni vengono mantenute anche dopo lo spegnimento dello strumento

```
15/05/10   15:34:26
G e n e r a l i
U n i t à   d i   m i s u r a
D a t a   O r a
U n i t à   r   e m o t a   / S o l a r i m .
I r r a g g i a m e n t o
P i n z a   D C
E N T E R   p e r   s e l e z .
I M P O S T
```

### 5.1.1. Generali
1.  Posizionare il cursore sulla voce **Generali** utilizzando i tasti freccia (****, ****) e confermare con **ENTER**.
2.  A display appare la videata che consente:
    *   L’impostazione della lingua dello strumento
    *   L’attivazione/disattivazione dell’autospegnimento
    *   La regolazione del contrasto del display
    *   L’abilitazione della segnalazione acustica in corrispondenza della pressione di un tasto
    *   L’attivazione/disattivazione dell’interfaccia WiFi in ogni sezione del menu generale per l’utilizzo dello strumento in abbinamento con l’APP HTAnalysis (nella sezione **PC** l’interfaccia WiFi è sempre attiva). Con WiFi attivo il simbolo "WiFi symbol" appare nella parte bassa destra del display. L’attivazione dell’interfaccia WiFi comporta un maggior consumo delle batterie.
3.  Per le impostazioni delle opzioni usare i tasti freccia (****, ****) e scegliere l’opzione desiderata usando i tasti freccia (****, ****)
4.  Premere il tasto **SAVE** per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto **ESC/MENU** per uscire senza salvare e tornare alla videata precedente

```
15/05/10   15:34:26
L i n g u a   :      I t a l i a n o   
A U T O P O W E R O F F   :   N O
C o n t r a s t o   :   4 0
S u o n o   t a s t i :   N O
W i F i :   N O
S A V E   p e r   s a l v a r e
I M P O S T
```

### 5.1.2. Unità di misura
Questa sezione permette l’impostazione delle unità di misura di alcuni parametri presenti nella gestione del database (DB) dei moduli FV (vedere § 5.3) nella misura di curva I - V
1.  Posizionare il cursore sulla voce “Unità di misura” utilizzando i tasti freccia (****, ****) e confermare con **ENTER**
2.  A display appare la videata che consente l’impostazione delle unità di misura dei parametri misurati dallo strumento
3.  Per abbandonare le modifiche effettuate premere il tasto **ESC/MENU**

```
15/05/10   15:34:26
P a r a m e t r i
E N T E R   p e r   s e l e z .
M E N U
```

4.  Posizionare il cursore sulla voce “Parametri” utilizzando i tasti freccia (****, ****) e confermare con **ENTER**
5.  A display appare la videata che consente l’impostazione delle unità di misura dei seguenti parametri tipici dei moduli:
    *   Alpha → selezioni possibili: “%/°C” e “mA/°C”
    *   Beta → selezioni possibili: “%/°C” e “mV/°C”
    *   Gamma → selezioni possibili: “%/°C” e “W/°C”
    *   Tolleranza → selezioni possibili: “%” e “W”
6.  Per l’impostazione delle unità di misura usare i tasti freccia (****, ****)
7.  Premere il tasto **SAVE** per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto **ESC/MENU** per uscire senza salvare e tornare alla videata precedente

```
15/05/10   15:34:26
A   l p h a   :      m A / ° C   
B   e t a   :   m V / ° C
G   a m m a   :   W / ° C
T   o l l e r a n z a   :   %
S A V E   p e r   s a l v a r e
I M P O S T
```

### 5.1.3. Data Ora
1.  Posizionare il cursore sulla voce “Data Ora” utilizzando i tasti freccia (****, ****) e confermare con **ENTER**
2.  A display appare la videata che consente l’impostazione della data/ora di sistema sia nel formato Europeo (EU) sia nel formato USA (US)
3.  Per l’impostazione delle unità di misura usare i tasti freccia (****, ****)
4.  Premere il tasto **SAVE** per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto **ESC/MENU** per uscire senza salvare e tornare alla videata precedente

```
15/05/10   15:34:26
A n n o   :      2 0   1 0   
M e s e   :   0   5
G i o r n o   :   1 5
O r e   :   0 9
M i n u t i   :   5 3
F o r m a t o   :   E U
S A V E   p e r   s a l v a r e
I M P O S T
```

### 5.1.4. Unità Remota /Solarim.
Questa sezione consente di selezionare il tipo di unità remota da utilizzare (se disponibile) ed impostare i valori dei parametri caratteristici (Sensitivity e Alpha) della cella solare di riferimento fornita in dotazione. I valori di questi parametri sono riportati sull’etichetta posteriore della cella stessa in funzione del tipo di modulo in prova.
1.  Posizionare il cursore sulla voce **Unità Remota** utilizzando i tasti freccia (****, ****) e confermare con **ENTER**
2.  A display appare la videata che consente di:
    *   Selezionare il tipo di unità remota da utilizzare per il collaudo di impianti FV (**SOLAR I - Vw** e **SOLAR I - Ve**):
        *   **NO**: Unità remota disabilitata
        *   **SOLAR**: utilizzo di **SOLAR - 02**
        *   **MPP300**: utilizzo di **MPP300** (opzionale)
    *   Abilitare/disabilitare l’utilizzo dell’unità remota **SOLAR - 02** per le misure I - V (opz. per **I - V400w** e **I - V500w**). Nel caso che non sia stato abilitato l’utilizzo dell’U.remota sarà possibile impostare i valori della Sensitivity (Sens.) della cella di riferimento in dotazione espressa in “mV/kW\*m⁻²” e del parametro Alpha
3.  Per l’impostazione dei valori usare i tasti freccia (****, ****)
4.  Premere il tasto **SAVE** per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto **ESC/MENU** per uscire senza salvare e tornare alla videata precedente

```
15/05/10   15:34:26
U n i t à   r .   C L D :   M P P 3 0 0
U n i t à   r .   I   -   V :      N O   
S e n s .   :      3 1 . 0      m V / k W / m 2
A l p h a   :   0 . 0 6 0   % / ° C
S A V E   p e r   s a l v a r e
I M P O S T
```

> **ATTENZIONE**
> Per le misure tipo CLD (collaudo impianti FV – **SOLAR I - Vw** e **SOLAR I - Ve**), la disabilitazione dell’unità remota comporta:
> *   Impossibilità di eseguire misure di Irraggiamento e Temperatura tramite l’unità **SOLAR - 02**
> *   Impossibilità di utilizzare l’unità **MPP300** (se disponibile)
>
> Conseguentemente sarà impossibile ottenere un esito circa il collaudo effettuato

### 5.1.5. Irraggiamento
Questa sezione consente l’impostazione della soglia minima di irraggiamento sia per la misura della curva I - V sia per il collaudo di una installazione FV (**SOLAR I - Vw**, **SOLAR I - Ve**).
1.  Posizionare il cursore sulla voce “Irraggiamento” utilizzando i tasti freccia (****, ****) e confermare con **ENTER**
2.  A display appare la videata con le voci “Irr min IV”, che consente l’impostazione della soglia minima di irraggiamento espressa in W/m², utilizzata come riferimento dallo strumento nell’esecuzione delle misure di curva I - V e “Irr min CLD” (**SOLAR I - Vw**, **SOLAR I - Ve**) che consente l’impostazione della soglia minima di irraggiamento espressa in W/m², utilizzata come riferimento dallo strumento nell’esecuzione delle misure di collaudo di impianti FV. Usare i tasti (****, ****) per passare tra le due voci
3.  Per l’impostazione della soglia minima di irraggiamento usare i tasti freccia (****, ****). Per ottenere risultati di precisione conforme a quanto indicato nel presente manuale si raccomanda di attenersi alle indicazione del § 10.1. Nella misura di curva I - V il valore è impostabile tra 0  800 W/m² e 400  800 W/m² per le operazioni di collaudo (**SOLAR I - Vw**, **SOLAR I - Ve**)
4.  Premere il tasto **SAVE** per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto **ESC/MENU** per uscire senza salvare e tornare alla videata precedente

```
15/05/10   15:34:26
I r r   m i n   I V   :      1   0 0      W / m 2
I r r   m i n   C L D   :      6 0 0      W / m 2
S A V E   p e r   s a l v a r e
I M P O S T
```

> **ATTENZIONE**
> L’impostazione “0 W/m²” per il parametro “Irr min IV” consente l’esecuzione delle misure I - V senza che vengano controllate le seguenti condizioni:
> *   Connessione della cella di riferimento all’ingresso IRR dello strumento
> *   Valori instabili di irraggiamento
> *   Numero moduli coerente con la tensione a vuoto misurata

### 5.1.6. Pinza DC (**SOLAR I - Vw** e **SOLAR I - Ve**)
Questa opzione consente di impostare l’eventuale fattore correttivo K per la pinza DC al fine di migliorare la misura della corrente. Se presente, il fattore correttivo è indicato sull’etichetta posteriore della pinza stessa indicato come:
K= X.xxx
Nel caso non fosse presente nessuna etichetta impostare k = 1.000
1.  Posizionare il cursore sulla voce **Pinza DC** utilizzando i tasti freccia (****, ****) e confermare con **ENTER**
2.  A display appare la videata “K pinza DC” che consente l’impostazione del fattore correttivo in un intervallo compreso tra 0.950 e 1.050. Per l’impostazione dei valori usare i tasti freccia (****, ****)
3.  Premere il tasto **SAVE** per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto **ESC/MENU** per uscire senza salvare e tornare alla videata precedente

```
15/05/10   15:34:26
k   P i n z a   D C   :      1 . 0 0 0   
S A V E   p e r   s a l v a r e
I M P O S T
```

## 5.2. CLD – IMPOSTAZIONI COLLAUDO IMPIANTI FV (**SOLAR I - VW**, **SOLAR I - VE**)
Nel seguito si indicherà con l’acronimo MPPT (Multiple Power Point Tracker) la caratteristica del convertitore DC/AC (inverter) in grado di massimizzare la potenza DC prelevabile dal campo fotovoltaico. Vedere il § 11.2 per ulteriori dettagli.

### 5.2.1. Impostazioni per Impianti FV con Inverter Mono MPPT - Uscita AC monofase
Controllare preventivamente le impostazioni effettuate in **MENU → SET → Unità Remota** e verificare di avere selezionato “**SOLAR**“ come impostazione per il parametro “Unità r.“

#### 5.2.1.1. Impostazione Strumento
1.  Posizionare il cursore sulla voce **CLD** utilizzando i tasti freccia (****, ****) e confermare con **ENTER**. A display appare la videata che riporta i valori dei parametri elettrici in uscita dal generatore fotovoltaico (lato DC)

```
15/05/10   15:34:26
P R p   -   -   -
P n o m   0 . 0 0 0   k W
T c   -   -   -   ° C
T e   -   -   -   ° C
P d c   0 . 0   k W
V d c   0 . 0 0 0   V
I d c   0 . 0   A
n d c   -   -   -

G   O   p e r   A v v i a r e
Selezione   C L D
```

2.  Premere il tasto **ENTER**. Lo strumento mostra le opzioni: **Par. Impianto** e **Imp. Strumento**
3.  Usare i tasti freccia (****, ****) per selezionare la voce “**Imp. Strumento**” e confermare con **ENTER**. Lo strumento mostra la seguente videata:

```
15/05/10   15:34:26
P R p   -   -   -
I r r   -   -   -   W / m 2
P n o m   0 . 0 0 0   k W
T c   -   -   -   ° C
T e   -   -   -   ° C
P d c   0 . 0   k W
V d c   0 . 0 0 0   V
I d c   0 . 0   A
n d c   -   -   -
Par . Impianto
I m p   .   S t r u m e n t o
Selezione   C L D
```

4.  Usando i tasti freccia (****, ****) è possibile impostare:
    *   Il periodo di integrazione (IP) utilizzabile dallo strumento nell’operazione di collaudo dei parametri di un’installazione FV. I valori **5s, 10s, 30s, 60s, 120s, 300s, 600s, 900s, 1800s, 3600s** sono selezionabili
    *   Il FS della pinza DC utilizzata per la misura di corrente DC con valore selezionabile tra **1A**  **3000A**
    *   Il FS della pinza AC utilizzata per la misura di corrente AC con valore selezionabile tra **1A**  **3000A**
5.  Premere il tasto **SAVE** per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto **ESC/MENU** per uscire senza salvare e tornare alla videata precedente.

```
15/05/10   15:34:26
I P   :      5      s
F S   P i n z a   D C   :   1 0 0 0   A
F S   P i n z a   A C   :   1 0 0 0   A
S A V E   p e r   s a l v a r e
C L D
```

#### 5.2.1.2. Parametri Impianto
1.  Posizionare il cursore sulla voce **CLD** utilizzando i tasti freccia (****, ****) e confermare con **ENTER**. A display appare la videata che riporta i valori dei parametri elettrici in uscita dal generatore fotovoltaico (lato DC)

```
15/05/10   15:34:26
P R p   -   -   -
I r r   -   -   -   W / m 2
P n o m   0 . 0 0 0   k W
T c   -   -   -   ° C
T e   -   -   -   ° C
P d c   0 . 0   k W
V d c   0 . 0 0 0   V
I d c   0 . 0   A
n d c   -   -   -

G O   p e r   A v v i a r e
Selezione   C L D
```

2.  Premere il tasto **ENTER**. Lo strumento mostra le opzioni: **Par. Impianto** e **Imp. Strumento**
3.  Usare i tasti freccia (****, ****) per selezionare la voce “**Par. Impianto**” e confermare con **ENTER**. Lo strumento mostra la seguente videata:

```
15/05/10   15:34:26
P R p   -   -   -
I r r   -   -   -   W / m 2
P n o m   0 . 0 0 0   k W
T c   -   -   -   ° C
T e   -   -   -   ° C
P d c   0 . 0   k W
V d c   0 . 0 0 0   V
I d c   0 . 0   A
n d c   -   -   -
Par . Impianto
I m p   .   S t r u m e n t o
Selezione   C L D
```

4.  Usando i tasti freccia (****, ****) è possibile impostare:
    *   **Pinv** → Potenza nominale della tipologia dell’inverter facente parte della sezione dell’impianto in esame. In accordo con la normativa vigente occorre specificare se l’inverter o gli inverter della parte di impianto in esame sono caratterizzati o meno da una potenza >20kW.
    *   **Pmax** → potenza nominale massima dell’installazione FV espressa in kW
    *   **Gamma** → coefficiente di variazione della potenza con la temperatura, parametro caratteristico dei moduli FV (tipicamente nel range: -0.3  -0.5%/C)
    *   **Noct** → temperatura nominale di lavoro della cella, parametro caratteristico dei moduli FV (tipicamente nel range: 42  48°C)
    *   **Te, Tc** → impostazione valori di default delle temperature dell’ambiente e dei moduli FV. Questi valori sono considerati dallo strumento solo in assenza di sonda ausiliaria collegata all’unità **SOLAR - 02**
    *   **Rel. Corr.** → Impostazione della relazione di compensazione sul calcolo della potenza Pdc e della massimizzazione del rendimento DC (vedere § 5.2.3)

```
15/05/10   15:34:26
P   i n v   :      > 2 0      k W
P m a x :   3 . 5 0 0   k W
G a m m a   :   -   0 . 0 2   % / ° C
N o c t   :   4 5   ° C
T e   :   4 0   ° C
T c   :   4 5   ° C
R e l .   C o r r .   :   T .   A m b
S A V E   p e r   s a l v a r e
C L D
```

### 5.2.2. Impostazioni per Imp. FV con inverter Mono/Multi MPPT - Uscita AC mono/trifase
Vedere il § 11.2 per ulteriori dettagli circa il significato di **MPPT**. Questa modalità richiede l’utilizzo dell’unità remota **MPP300** (opzionale). Controllare preventivamente le impostazioni effettuate in **MENU → SET → Unità Remota** e verificare di avere selezionato “**MPP300**“ come impostazione per il parametro “Unità r.“

#### 5.2.2.1. Impostazione Strumento
1.  Posizionare il cursore sulla voce **CLD** utilizzando i tasti freccia (****, ****) e confermare con **ENTER**. A display appare la videata a fianco che indica i parametri globali dell’impianto.

```
15/05/10   15:34:26
P R p   -   -   -
I r r   -   -   -   W / m 2
P n o m   1 5 0 . 0   k W
T c   -   -   -   ° C
T e   -   -   -   ° C
P d c   -   -   -   k W
P a c   -   -   -   k W
n d c   -   -   -
n a c   -   -   -

G O   p e r   A v v i a r e
Selezione   M P P
```

2.  Premere il tasto **ENTER**. Lo strumento mostra le opzioni: **Stato MPP300**, **Par. Impianto** e **Imp. Strumento**
3.  Usare i tasti freccia (****, ****) per selezionare la voce “**Imp. Strumento**” e confermare con **ENTER**. Lo strumento mostra la seguente videata:

```
15/05/10   15:34:26
P R p   -   -   -
I r r   -   -   -   W / m 2
P n o m   1 5 0 . 0   k W
T c   -   -   -   ° C
T e   -   -   -   ° C
P d c   -   -   -   k W
P a c   -   -   -   k W
n   d c   -   -   -
n a   c   -   -   -
Stato MPP 300
Par . Impianto
I m p   .   S t r u m e n t o
Selezione   M P P
```

4.  Usando i tasti freccia (****, ****) è possibile impostare:
    *   Il periodo di integrazione (IP) utilizzabile dallo strumento nell’operazione di collaudo dei parametri di un’installazione FV. Sono selezionabili i valori **5s, 10s, 30s, 60s, 120s, 300s, 600s, 900s, 1800s, 3600s**
    *   Il FS della pinza DC utilizzata per la misura di corrente DC con valore selezionabile tra **1A**  **3000A**
    *   Il FS della pinza AC utilizzata per la misura di corrente AC con valore selezionabile tra **1A**  **3000A**
    *   Il tipo di pinza AC utilizzata: **STD** (standard) o **FLEX** (pinza a toroide flessibile)
    *   Il numero di ingressi DC da utilizzare per la misura: **1**, **1+2**, **1+2+3**
    *   Il tipo di sistema elettrico AC: **MONO**, **4 FILI**
5.  Premere il tasto **SAVE** per salvare le impostazioni effettuate e il messaggio “Dati memorizzati” sarà mostrato per un istante. Premere il tasto **ESC/MENU** per uscire senza salvare e tornare alla videata precedente

```
15/05/10   15:34:26
I P   :      5      s
F S   P i n z a   D C   :   1 0 0 0   A
F S   P i n z a   A C   :   1 0 0 0   A
T i p o   P i n z a :   S   T D
I n g r e s s i   D c   1 + 2 + 3
S i s t e m i   A c   4   f i l i
S A V E   p e r   s a l v a r e
M P P
```

<!-- Chunk: Pages 17-32 -->
### 5.2.2.2. Parametri Impianto

1.  Posizionare il cursore sulla voce `CLD` utilizzando i tasti freccia (, ) e confermare con `ENTER`. A display appare la videata a fianco che indica i parametri globali dell’impianto.

    ```
    15/05/10   15:34:26
    P R p   -   -   -
    I r r   -   -   -   W / m 2
    P n o m   1 5 0 . 0   k W
    T c   -   -   -   ° C
    T e   -   -   -   ° C
    P d c   -   -   -   k W
    P a c   -   -   -   k W
    n d c   -   -   -
    n a c   -   -   -
      G   o   p e r   A v v i a r e
    Selezione   M P P
    ```

2.  Premere il tasto `ENTER`. Lo strumento mostra le opzioni: `Stato MPP 300`, `Par. Impianto` e `Imp. Strumento`.

3.  Usare i tasti freccia (, ) per selezionare la voce “Par. Impianto” e confermare con `ENTER`. Lo strumento mostra la seguente videata:

    ```
    15/05/10   15:34:26
    P R p   -   -   -
    I r r   -   -   -   W / m 2
    P n o m   0 . 0 0 0   k W
    T c   -   -   -   ° C
    T e   -   -   -   ° C
    P d c   0 . 0   k W
    V d c   0 . 0 0 0   V
    I d c   0 . 0   A
    n d c   -   -   -
    S t a t o   M P P   3 0 0
    Par . Impianto
    I m p   .   S t r u m e n t o
    Selezione   M P P
    ```

4.  Usando i tasti freccia (, ) è possibile impostare:
    *   `Pinv` → Potenza nominale della tipologia dell’inverter facente parte della sezione dell’impianto in esame. In accordo con la normativa vigente occorre specificare se l’inverter o gli inverter della parte di impianto in esame sono caratterizzati o meno da una potenza >20kW.
    *   `Pmax` → potenza nominale massima dell’installazione FV espressa in kW
    *   `Gamma` → coefficiente di variazione della potenza con la temperatura, parametro caratteristico dei moduli FV (tipicamente nel range: -0.3  -0.5%/C)
    *   `Noct` → temperatura nominale di lavoro della cella, parametro caratteristico dei moduli FV (tipicamente nel range: 42  48°C)
    *   `Te, Tc` → impostazione valori di default delle temperature dell’ambiente e dei moduli FV. Questi valori sono considerati dallo strumento solo in assenza di sonda ausiliaria collegata all’unità SOLAR - 02
    *   `Rel. Corr.` → Impostazione della relazione di compensazione sul calcolo della potenza Pdc e della massimizzazione del rendimento DC (vedere § 5.2.3)

    ```
    15/05/10   15:34:26
    P   i n v   :      > 2 0      k W
    P m a x   3 . 5 0 0   k W
    G a m m a   :   0 . 4 5   % / ° C
    N o c t   :   4 5   ° C
    T e   :   4 0   ° C
    T c   :   4 5   ° C
    R e l   C o r r .   :   T .   A m b
    S A V E   p e r   s a l v a r e
    M P P
    ```

### 5.2.2.3. Stato MPP300

Qualora il `SOLAR I - Vw` o il `SOLAR I - Ve` si trovino in prossimità del MPP300 possono essere visualizzati i parametri generali di quest’ultimo.

1.  Posizionare il cursore sulla voce `CLD` utilizzando i tasti freccia (, ) e confermare con `ENTER`. A display appare la videata a fianco che indica i parametri globali dell’impianto.

    ```
    15/05/10   15:34:26
    P R p   -   -   -
    I r r   -   -   -   W / m 2
    P n o m   1 5 0 . 0   k W
    T c   -   -   -   ° C
    T e   -   -   -   ° C
    P d c   -   -   -   k W
    P a c   -   -   -   k W
    n d c   -   -   -
    n a c   -   -   -
      G   o   p e r   A v v i a r e
    Selezione   M P P
    ```

2.  Premere il tasto `ENTER`. Lo strumento mostra le opzioni: `Stato MPP 300`, `Par. Impianto` e `Imp. Strumento`.

3.  Usare i tasti freccia (, ) per selezionare la voce “Stato MPP 300” e confermare con `ENTER`. Lo strumento mostra la videata a lato con indicati i principali parametri generali dello strumento.

    ```
    15/05/10   15:34:26
    A l i m e n t a z i o n e   B a t t
    B a t t e r i a   I n   u s o
    C a r i c a   9 9 %
    C o n n e s s i o n e   S o l a r   S I
    V e r s i o n e   1 . 0 1
    S N   1 1 0 1 0 0 3 0
    Stato MPP 300
    Par . Impianto
    I m p   .   S t r u m e n t o
    Selezione   M   E N U
    ```

### 5.2.3. Selezione della relazione di compensazione degli effetti della Temperatura

Questa opzione consente di selezionare la relazione da utilizzare per effettuare delle correzioni alle misure effettuate in funzione della Temperatura dei moduli. Sono disponibili le seguenti modalità di correzione dei termini PRp e nDC:

*   `T.mod.`: Calcolo del termine Rfv2 in funzione della Temp. moduli in accordo a Guida CEI - 82 - 25
*   `T.amb`: Calcolo del termine Rfv2 in funzione della Temp. ambiente in accordo a Guida CEI - 82 - 25
*   `n dc`: Correzione PRp tramite Temperatura moduli

**ATTENZIONE**
*   Nell’ambito di verifiche di sistemi FV in accordo a quanto prescritto dalla guida CEI 82 - 25, è consigliabile adottare la relazione “T.amb.”, in quanto la temperatura dei moduli FV, calcolata utilizzando la relazione del NOCT, risulta tipicamente superiore a quella che si può misurare sul retro dei moduli stessi
*   La relazione “nDC” non è contemplata dalla guida CEI 82 - 25 pertanto la sua selezione comporta la mancata indicazione dell’esito finale di un collaudo FV da parte dello strumento

| Tipo    | Correzz. Temperatura utilizzata (Tcel)                                                                         | Calcolo del PRp                                                                                                                              | Rif.         |
| :------ | :-------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------- | :----------- |
| T.mod.  | `s Tm oduli_Mi Tcel =           = C) 40 Tcel (se 100 40) - (Tcel - 1 C) 40 Tcel (se 1 fv2  R`         | `da cui             =  n S TC p ca  P G G Rfv P PRp  2`                                                                            | CEI 82 - 25  |
| T.amb.  | `(   )             − + =   800 Irr 20 Tamb Tcel   NOCT d c   s Tm oduli_Mi Tcel   =`                   | `(   )  n ca cel p S TC  P P T G G PRp              −  +  =   25 100 1    -   -   -`                                           | CEI 82 - 25  |
| n dc    | Correzione PRp tramite Temperatura moduli                                                                       | - - -                                                                                                                                        | - - -        |

dove:

| Simbolo | Descrizione                                                                                                                     | U.di misura |
| :------ | :------------------------------------------------------------------------------------------------------------------------------ | :---------- |
| p G     | Irraggiamento misurato sul piano dei moduli                                                                                     | `[ W/m^2 ]` |
| S TC G  | Irraggiamento in condizione Standard = 1000                                                                                     | `[ W/m^2 ]` |
| n P     | Potenza nominale = somma delle Pmax dei moduli FV facenti parte della sezione dell’impianto in esame                            | `[ kW ]`    |
| ca P    | Potenza in ca complessiva misurata all’uscita del/degli inverter facenti parti della sezione dell’impianto in esame            | `[ kW ]`    |
| 2 Rfv   | Coefficiente correttivo funzione della Temperatura delle Celle FV (Tcel) misurata o calcolata in accordo al tipo di relazione di correzione selezionata |             |
|        | Valore assoluto del coef. Termico della Pmax dei moduli FV facenti parte della sezione impianto in esame.                       | `[ %/°C ]`  |
| NOCT    | (Nominal Operating Cell Temperature) = Temperatura a cui si portano le celle in condizioni di rif (800W/m^2, 20°C, AM=1.5, Vel. Aria =1m/s). | `[%]`       |

Per ulteriori dettagli vedere il § 11.1.

### 5.3. DB – GESTIONE DATABASE MODULI

Lo strumento permette la gestione fino ad un massimo di 30 tipologie di moduli FV oltre ad un modulo di DEFAULT (non modificabile né cancellabile) che può essere usato come riferimento qualora non si abbiano informazioni sul tipo di modulo a disposizione. I parametri, riferiti a 1 modulo, che possono essere impostati nella definizione sono riportati nella Tabella 1 seguente, insieme ai campi di misura, risoluzione e condizioni di validità:

| Simbolo | Descrizione                                          | Range                            | Risol.         | Condizioni            |
| :------ | :--------------------------------------------------- | :------------------------------- | :------------- | :-------------------- |
| Nms     | Numero moduli per stringa                            | 1  50                         | 1              |                       |
| Pmax    | Potenza massima nominale del modulo                  | 50  4800 W                      | 1W             | `0.01 <= Imax * Vmax / P <= 1` |
| Voc     | Tensione a vuoto                                     | 15.00  99.99V, 100.0  320.0V   | 0.01V, 0.1V    | `Voc >= Vmpp`         |
| Vmpp    | Tensione nel punto di massima potenza                | 15.00  99.99V, 100.0  320.0V   | 0.01V, 0.1V    | `Voc >= Vmpp`         |
| Isc     | Corrente di cortocircuito                            | 0.5  15.00 A                    | 0.01A          | `Isc >= Impp`         |
| Impp    | Corrente nel punto di massima potenza                | 0.5  15.00 A                    | 0.01A          | `Isc >= Impp`         |
| Toll -  | Tolleranza negativa per la Pmax fornita dal costruttore del modulo | 0%  25.0%                       | 0.1%           | `100*Toll-/Pnom < 25` |
|         |                                                      | 0  99W                          | 1              |                       |
| Toll +  | Tolleranza positiva per la Pmax fornita dal costruttore del modulo | 0  25%                          | 0.1%           | `100*Toll+/Pnom < 25` |
|         |                                                      | 0  99W                          | 1              |                       |
| Alpha   | Coefficiente di temperatura Isc                      | -0.100  0.100%/°C               | 0.001%/°C      | `100*Alpha/Isc <= 0.1`|
|         |                                                      | -15.00  15.00 mA/°C             | 0.01mA/°C      |                       |
| Beta    | Coefficiente di temperatura Voc                      | -0.99  -0.01%/°C                | 0.01%/°C       | `100*Beta/Voc <= 0.999`|
|         |                                                      | -0.999  -0.001V/°C              | 0.001V/°C      |                       |
| Gamma   | Coefficiente di temperatura Pmax                     | -0.99  -0.01%/°C                | 0.01%/°C       |                       |
| NOCT    | Temperatura nominale di lavoro della cella           | 0  100°C                        | 1°C            |                       |
| Tech.   | Effetti dovuti alla tecnologia del modulo            | STD (standard), CAP (eff.capacitivi), HIT (tecn. Ibrida) |                |                       |
| Degr.   | Degrado percentuale prestazioni/anno                 | 0.0  25.0%/yr                   | 0.1 %/yr       |                       |

Tabella 1: Parametri associati ad un modulo FV

**ATTENZIONE**
*   La voce “Tech” è riferita alla scelta della tecnologia del modulo in prova. Selezionare l’opzione “STD” in caso di test su moduli FV di tipo “STANDARD”, l’opzione “CAP” in caso di moduli FV con effetti capacitivi considerevoli oppure “HIT” (moduli con tecnologia Ibrida HIT/HIP)
*   La scelta errata del tipo di tecnologia può comportare un esito negativo del test finale
*   Il parametro “Degr.” rappresenta il degrado di prestazioni in potenza di un modulo/stringa/campo FV in termini di percentuale annua (limite massimo impostabile = 25%)

### 5.3.1. Definizione di un nuovo modulo FV

1.  Posizionare il cursore sulla voce `DB` utilizzando i tasti freccia (, ) e confermare con `ENTER`. A display appare la videata che riporta:
    *   Il tipo di modulo selezionato
    *   I valori dei parametri associati al modulo (vedere Tabella 1)

    ```
    15/05/10   15:34:26
    T i p o   :      D E F A U L T   
    
    P m a x   =   1 8 5   W
    V o c   =   4 4 . 5   V
    V m p p   =   3 7 . 5   V
    I s c   =   5 . 4 0   A
    I m p p   =   4 . 9 5   A
    T o l l   -   =   0   %
    
    Selezione   D B
    ```

2.  Usare i tasti freccia (, ) per selezionare il tipo di modulo “DEFAULT” e confermare con `ENTER`.

3.  Premere il tasto `ENTER`, selezionare il comando “Nuovo” (che consente di definire un nuovo modulo) e confermare ancora con `ENTER`. Usare i tasti freccia (, ) per scorrere l’elenco dei parametri

    ```
    15/05/10   15:34:26
    T i p o   :      D E F A U L T   
    
    P m a x   =   1 8 5   W
    V o c   =   4 4 . 5   V
    V m p p   =   3 7 . 5   V
    I s c   =   5 . 4 0   A
    I m p p   =   4 . 9 5   A
    T o l l   -   =   0   %
    
    N u o v o
    Selezione   D B
    ```

4.  Lo strumento presenta una tastiera virtuale interna in cui è possibile definire il nome del modulo (ex: SUNPOWER 210) usando i tasti freccia (, , , ). La pressione del tasto `ENTER` consente l’inserimento di ogni carattere del nome digitato.

5.  Premere il tasto `SAVE` per salvare il nome del nuovo modulo così definito o il tasto `ESC/MENU` per uscire senza salvare.

    ```
    15/05/10   15:34:26
    T i p o   :
    
    P m a x   =   1 8 5   W
    V o c   =   4 4 . 5   V
    T A S T I E R A
    S U N P O W E R   2 1 0
    A   B   C   D   E   F   G   H   I   J   K   L   M   N   O   P
    Q   R   S   T   U   V   W   X   Y   Z   -   +   0   1   2   3
    4   5   6   7   8   9   S P A C E   D E L
    SAVE / ESC
    ```

6.  Inserire il valore di ogni parametro (vedere Tabella 1) in funzione del datasheet eventuale del costruttore Posizionare il cursore sul parametro da definire utilizzando i tasti freccia (, ) e impostare il valore utilizzando i tasti freccia (, ). Tenere premuto i tasti (, ) per eseguire una rapida impostazione dei valori.

7.  Premere il tasto `SAVE` per salvare le impostazioni o `ESC/MENU` per uscire senza salvare.

    ```
    15/05/10   15:34:26
    T i p o   :   S U N P O W E R   2 1 0
    
    P m a x   =      0      W
    V o c   =   0 . 0   V
    V m p p   =   0 . 0   V
    I s c   =   0 . 0 0   A
    I m p p   =   0 . 0 0   A
    T o l l   -   =   0   %
    
    D B
    ```

**ATTENZIONE**
*   Premere il tasto `HELP` per alcuni secondi nel caso di valore non noto al fine di inserire il valore di default
*   Alla pressione del tasto `SAVE` lo strumento controlla le condizioni riportate nella Tabella 1 e, nel caso in cui una o più di esse non sia verificata, fornisce a display uno dei messaggi di errore riportati nel § 6.4 e non salva la configurazione impostata finché le cause di errore non sono risolte

### 5.3.2. Modifica di un modulo FV esistente

1.  Selezionare il modulo FV da modificare all’interno del database utilizzando i tasti freccia (, ).

2.  Premere il tasto `ENTER` e selezionare il comando “Modifica” usando il tasto freccia ().

3.  Confermare la selezione con `ENTER`.

    ```
    15/05/10   15:34:26
    T i p o   :      S U N P O W E R 2 1 0   
    
    P m a x   =   2 1 0   W
    V o c   =   4 7 . 7 0   V
    V m p p   =   4 0 . 0 0   V
    I s c   =   5 . 7 5   A
    N u o v o
    M o d i f i c a
    C a n c e l l a
    C a n c e l l a   T u t t o
    S e l e z i o n e   I M P O S T
    ```

4.  Lo strumento presenta una tastiera virtuale interna in cui è possibile ridefinire il nome del modulo o lasciarlo inalterato usando tasti freccia (, , , ). La pressione del tasto `ENTER` consente l’inserimento di ogni carattere del nome digitato.

5.  Premere il tasto `SAVE` per salvare il nome del nuovo modulo così definito o per accedere alla nuova programmazione dei parametri.

    ```
    15/05/10   15:34:26
    T i p o :      S U N P O W E R 2 1 0   
    
    P m a x   =   1 8 5   W
    V o c   =   4 4 . 5   V
    T A S T I E R A
    S U N P O W E R   2 1 0
    A   B   C   D   E   F   G   H   I   J   K   L   M   N   O   P
    Q   R   S   T   U   V   W   X   Y   Z   -   +   0   1   2   3
    4   5   6   7   8   9   S P A C E   D E L
    SAVE / ESC
    ```

6.  Modificare il valore dei parametri desiderati utilizzando i tasti freccia (, ) e impostare il valore utilizzando i tasti freccia (, ). Tenere premuto i tasti (, ) per eseguire una rapida impostazione dei valori. Premere il tasto `HELP` per alcuni secondi nel caso di valore non noto al fine di inserire il valore di default.

7.  Premere il tasto `SAVE` per salvare le impostazioni eseguite o `ESC/MENU` per uscire senza salvare. Lo strumento fornisce in tal caso il messaggio “Dati non memorizzati”.

    ```
    15/05/10   15:34:26
    T i p o   :   S U N P O W E R   2 1 0
    
    P m a x   =      2 1 0      W
    V o c   =   4 7 . 7 0   V
    V m p p   =   4 0 . 0 0   V
    I s c   =   5 . 7 5   A
    I m p p   =   5 . 2 5   A
    T o l l   -   =   5   %
    
    I M P O S T
    ```

### 5.3.3. Cancellazione di un modulo FV esistente

1.  Selezionare il modulo FV presente all’interno del database utilizzando i tasti freccia (, ).

2.  Premere il tasto `ENTER` e selezionare il comando “Cancella” usando il tasto freccia () per cancellare il modulo selezionato.

3.  Premere il tasto `ENTER` e selezionare il comando “Cancella Tutto” usando il tasto freccia () per cancellare ogni modulo presente all’interno del database.

4.  Confermare la selezione con `ENTER` oppure premere `ESC/MENU` per uscire dalla funzione.

    ```
    15/05/10   15:34:26
    T i p o   :      S U N P O W E R 2 1 0   
    
    P m a x   =   2 1 0   W
    V o c   =   4 7 . 7 0   V
    V m p p   =   4 0 . 0 0   V
    I s c   =   5 . 7 5   A
    N u o v o
    M o d i f i c a
    C a n c e l l a
    C a n c e l l a   T u t t o
    S e l e z i o n e   I M P O S T
    ```

**ATTENZIONE**
*   Non è possibile modificare né cancellare il modulo FV di DEFAULT presente come impostazione di fabbrica

## 6. ISTRUZIONI OPERATIVE

### 6.1. COLLAUDO IMPIANTI FV (SOLAR I - VW, SOLAR I - VE)

Per semplicità, nel seguito di questo § si adotterà il termine “stringa” anche se spesso il termine “campo fotovoltaico” sarebbe il più opportuno. Dal punto vista dello strumento la gestione di una sola stringa o di più stringhe in parallelo fra loro (campo fotovoltaico) è identica. Si indicherà inoltre con l’acronimo MPPT (Multiple Power Point Tracker) la caratteristica del convertitore DC/AC (inverter) in grado di massimizzare la potenza DC prelevabile dal campo fotovoltaico (vedere il § 11.2 per ulteriori dettagli) e con l’acronimo PRp il Performance ratio (valutato sulla base delle potenza attive – vedere § 5.2.3).

**ATTENZIONE**
*   Ai fini della valutazione del solo PRp, la misura delle grandezze DC (tensione e corrente) NON è strettamente necessaria
*   È viceversa necessaria se si desidera valutare anche le prestazione della sezione fotovoltaica (ndc) e della sezione di conversione DC/AC (nac)

Descrizione dei Simboli visualizzati

| Simbolo   | Descrizione                                                                    | U. mis    |
| :-------- | :----------------------------------------------------------------------------- | :-------- |
| PRp       | Performace Ratio valutato sulle potenze attive                                 |           |
| Irr       | Irraggiamento                                                                  | `W/m^2`   |
| Pnom      | Potenza nominale complessiva della sezione dell’impianto in esame              | `kW`      |
| Tc        | Temperatura moduli                                                             | `°C`      |
| Te        | Temperatura ambiente                                                           | `°C`      |
| Pdc, Pdcx | Potenza totale DC misurata, Potenza DC misurata del campo FV x (x=1,2,3)       | `kW`      |
| Pac, Pacx | Potenza totale AC misurata, Potenza AC misurata della Fase x (x=1,2,3,)        | `kW`      |
| ndc       | Efficienza della sezione fotovoltaica                                          |           |
| nac       | Efficienza della sezione di conversione DC/AC (inverter)                       |           |
| Vdc, Vdcx | Tensione DC misurata, Tensione DC misurata del campo FV x (x=1,2,3)            | `V`       |
| Idc, Idcx | Corrente DC misurata, Corrente DC misurata del campo FVx (x=1,2,3)             | `A`       |
| Vac, Vacx | Tensione AC misurata, Tensione AC misurata della Fase x (x=1,2,3,)             | `V`       |
| Iac, Iacx | Corrente AC misurata, corrente AC misurata della Fase x (x=1,2,3,)             | `A`       |

### 6.1.1. Collaudo Impianti FV con Inverter Mono MPPT - Uscita AC monofase

Lo strumento `SOLAR I - Vw` o `SOLAR I - Ve` (Master) consente di eseguire collaudi su installazioni FV Monofase in abbinamento con l’unità remota `SOLAR - 02` a cui sono collegate le sonde di irraggiamento e temperatura. Tale unità remota è in grado di comunicare con quella Master (per la gestione delle operazioni di sincronizzazione e scaricamento dei dati) attraverso un collegamento a radiofrequenza (RF) attivo fino ad una distanza massima di circa 1m tra di esse.

**ATTENZIONE**
*   La massima tensione tra gli ingressi C1, C2 è 1000VDC (per lo strumento `SOLAR I - Vw`) o 1500VDC (per lo strumento `SOLAR I - Ve`) e tra gli ingressi P1, P2 è 265VAC rms. Non misurare tensioni che eccedano i limiti espressi in questo manuale. Il superamento di tali limiti potrebbe causare shock elettrici all’utilizzatore e danni allo strumento
*   Per garantire la sicurezza dell’operatore, durante la fase dei collegamenti, mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter).

Fig. 4: Collegamento dello strumento per collaudo su impianto FV Monofase

1.  Controllare ed eventualmente impostare sul `SOLAR - 02` la sensibilità della cella di riferimento coerentemente con il tipo di moduli FV che si andrà ad esaminare (vedere manuale d’uso del `SOLAR - 02`).

2.  Si raccomanda di eseguire una valutazione preliminare del valore dell’Irraggiamento sul piano dei moduli FV in esame tramite l’unità `SOLAR - 02` (in funzionamento indipendente) e la cella di riferimento. Si ricorda che in accordo alla Guida CEI 82 - 25 l’irraggiamento minimo per eseguire una verifica di efficienza su un impianto fotovoltaico è pari a 600W/m^2.

3.  Accendere il `SOLAR I - Vw` o `SOLAR I - Ve`, controllare ed eventualmente modificare le impostazioni dello strumento relativamente al tipo di unità remota, alla soglia minima di irraggiamento, al fondo scala delle pinze AC e DC, al periodo di integrazione e i parametri del sistema in esame (vedere § 5.1.4, § 5.1.5, 5.1.6, 5.2.1).

4.  Per garantire la sicurezza dell’operatore mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter).

5.  Nel caso di inverter dotati di più di un inseguitore di potenza (MPPT) lasciare collegata solo la stringa corrispondente al primo MPPT come mostrato in Fig. 4. Sarà poi necessario ripetere le operazioni di seguito indicate lasciando collegata solo la stringa connessa al secondo MPPT, al terzo, ecc.

6.  Avvicinare fra loro (max 1 m circa) il `SOLAR I - Vw` o `SOLAR I - Ve` e il `SOLAR - 02`. Tutti gli strumenti devono essere accesi (vedere il manuale d’uso di `SOLAR - 02` per ulteriori dettagli).

7.  Su `SOLAR I - Vw` o `SOLAR I - Ve` premere il tasto `MENU`, selezionare la funzione `CLD` e premere `ENTER` ed attendere che le due unità inizino a comunicare fra loro. Questa condizione è evidenziata dalla presenza simultanea dei seguenti indicatori:
    *   Simbolo fisso (non intermittente) sul display del `SOLAR I - Vw`, `SOLAR I - Ve`
    *   Simbolo fisso (non intermittente) sul display del `SOLAR - 02`

8.  Collegare gli ingressi `C2` e `C1` rispettivamente ai poli positivo e negativo di uscita della stringa. Collegare gli ingressi `P1`, `P2` ai conduttori di Fase e Neutro rispettando i colori indicati in Fig. 4.

9.  Collegare il connettore di uscita della pinza DC all’ingresso `IDC`.

    **ATTENZIONE**
    PRIMA DI COLLEGARE LE PINZE DC SUI CONDUTTORI
    Accendere la pinza, controllare il LED indicante lo stato delle batterie interne della pinza (se presenti), selezionare la portata corretta, premere il tasto `ZERO` sulla pinza DC e verificare sul display del `SOLAR I - Vw`, `SOLAR I - Ve` l’effettivo azzeramento del valore Idc corrispondente (valori fino a 0.02A sono comunque accettabili).

10. Collegare la pinza di corrente DC sul conduttore positivo in uscita dalla stringa rispettando il verso della freccia presente sulla pinza stessa come indicato in Fig. 4. Posizionare la pinza il più lontano possibile dall’inverter ed evitare che il toroide sia in prossimità del conduttore negativo.

11. Collegare la pinza AC sul conduttore di Fase L1 rispettando il verso della freccia presente sulla pinza stessa come indicato in Fig. 4. Posizionare la pinza il più lontano possibile dall’inverter ed evitare che il toroide sia in prossimità del conduttore Neutro. Collegare l’uscita della pinza all’ingresso `IAC` dello strumento.

12. Mettere nuovamente in servizio il sistema elettrico in esame.

13. A display appare la prima videata che riporta i valori dei parametri elettrici sul lato DC dell’inverter.

    ```
    15/05/10   15:34:26
    P R p   -   -   -
    I r r   -   -   -   W / m 2
    P n o m   3   .   5 0 0   k W
    T c   4 5   ° C
    T e   3 0   ° C
    P d c   3   .   1 2 5   k W
    V d c   3 8 9   V
    I d c   8   . 0   1   A
    n d c   -   -   -
      G o   p e r   A v v i a r e
    Sele zione   C L D
    ```

14. Premere il tasto () per accedere alla seconda videata che riporta i valori dei parametri elettrici sul lato AC dell’inverter. Prima di attivare il collaudo:
    *   Verificare la presenza del simbolo “` `” fisso che indica il corretto collegamento RF con l’unità remota `SOLAR - 02`
    *   Verificare che la potenza attiva Pac sia positiva In caso di valori negativi della potenza attiva aprire la pinza, ruotarla di 180° e ricollegarla al conduttore
    *   Verificare che il valore del rendimento AC ` ac` = Pac / Pdc sia un valore coerente (ex: una situazione di ` ac > 1` non è fisicamente possibile)

    ```
    15/05/10   15:34:26
    
    P d c   3 . 1 2 5   k W
    V d c   3 8 9   V
    I d c   8 . 0 1   A
    n d c   -   -   -   ° C
    P   a   c   3 .   0 1 2   k W
    V   a   c   2 3 1   V
    I   a   c   1 3   .   0 3   A
    n   a   c   0 . 9 6
    G o   p e r   A v v i a r e
    Sele zione   C L D
    ```

15. Mantenendo l’unita `SOLAR - 02` sempre in prossimità dell’unità principale, premere il tasto `GO/STOP` su `SOLAR I - Vw`, `SOLAR I - Ve` per attivare il collaudo. Il messaggio “reg. in attesa” appare a display dell’unità principale ed il messaggio “HOLD” a display del `SOLAR - 02` oltre all’indicazione del tempo in secondi in attesa dell’istante “00”.

    ```
    15/05/10   15:34:26
    
    P d c   3 . 1 2 5   k W
    V d c   3 8 9   V
    I d c   8 . 0 1   A
    n d c   -   -   -   ° C
    P a c   3 . 0 1 2   k W
    V a c   2 3 1   V
    I a c   1 3 . 0 3   A
    n a c   0 . 9 6
    r e g .   i n   a t t e s a
    Selezione   C L D
    ```

16. Al raggiungimento dell’istante ”00” successivo alla pressione del tasto `GO/STOP` il collaudo ha inizio e le due unità sono tra loro sincronizzate. In tali condizioni il messaggio “reg. in corso” appare a display dell’unità principale ed il messaggio “Recording…” appare a display del `SOLAR - 02`.

    ```
    15/05/10   15:35:00
    
    P d c   3 . 1 2 5   k W
    V d c   3 8 9   V
    I d c   8 . 0 1   A
    n d c   -   -   -   ° C
    P a c   3 . 0 1 2   k W
    V a c   2 3 1   V
    I a c   1 3 . 0 3   A
    n a c   0 . 9 6
    r e g .   i n   c o r s o
    Selezione   C L D
    ```

17. In qualunque momento sarà possibile analizzare lo stato attuale della registrazione tramite pressione del tasto `MENU`. Verranno visualizzati:
    *   Data ed ora di inizio registrazione
    *   Il valore impostato del periodo di integrazione
    *   Il numero di Periodi trascorsi dall’inizio registrazione
    *   La capacità di memoria residua di registrazione.

    Premere il tasto `ESC` per uscire dalla videata.

    ```
    15/05/10   15:35:00
    S t a r t
    1 4 / 0 2 / 0 0   1 7 : 1 8 : 0 0
    P e r i o d o :   5 s
    N u m e r o   I P   6 1
    A u t o n o m i a   0 d   1 h
    Reg. in corso
    r e g .   i n   c o r s o
    Selezione   C L D
    ```

18. A questo punto è possibile portare l’unità `SOLAR - 02` in prossimità delle stringhe FV per effettuare le misure di irraggiamento e temperatura tramite le rispettive sonde. Quando la distanza tra l’unità `SOLAR - 02` e `SOLAR I - Vw` è tale da non consentire il collegamento RF, sul display del `SOLAR - 02`, il simbolo “` `” lampeggia per circa 30s poi scompare, mentre il `SOLAR I - Vw`, `SOLAR I - Ve` resta in ricerca per 1 minuto circa.

19. Posizionare la cella di riferimento sul piano dei moduli FV. Fare riferimento al relativo manuale d’uso per un corretto montaggio.

20. Posizionare il sensore di temperatura a contatto con il retro del modulo fissandolo con nastro e evitando di toccarlo al fine di falsare la misura.

21. Attendere qualche secondo per consentire alle sonde di raggiungere una misura stabile e poi collegare la sonda di Irraggiamento all’ingresso `PYRA/CELL` e la sonda di temperatura all’ingresso `TEMP` dell’unità `SOLAR - 02`.

22. Attendere il messaggio “READY” a display del `SOLAR - 02` ad indicare che l’unità ha rilevato dei dati con Irraggiamento solare > soglia minima impostata (vedere § 5.1.5).

23. Con messaggio “READY” a display attendere per circa 1 minuto in modo da raccogliere un certo numero di campioni.

24. Scollegare le sonde di Irraggiamento e temperatura dall’unità `SOLAR - 02` e avvicinarla al `SOLAR I - Vw`, `SOLAR I - Ve` (max 1m).

25. L’unità principale `SOLAR I - Vw` deve essere in modalità `CLD`. Se è assente il simbolo “` `” lampeggiante, premere il tasto  per riattivare la ricerca del collegamento RF.

26. Premere il tasto  sul `SOLAR - 02` per riattivare il collegamento RF. Conseguentemente sull’unità principale verrà visualizzato il messaggio “connessione radio attiva”.

27. Per arrestare il collaudo premere il tasto `GO/STOP` sullo strumento e confermare con `ENTER` alla richiesta di arresto della registrazione.

28. Il messaggio “SEND” è mostrato a display dell’unità `SOLAR - 02` ad indicare il trasferimento dei dati all’unità principale.

29. Dopo la fase automatica di trasferimento dati, lo strumento visualizzerà:
    *   `ESITO SI`: se esiste almeno 1 valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
    *   `ESITO NO`: se NON esiste nessun valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
    *   `Impossibile effettuare l’analisi`: se l’irraggiamento non ha mai raggiunto un valore stabile superiore alla soglia minima impostata oppure se non esiste nessun valore valido durante tutto l’arco della registrazione (PRp > 1.15)
    *   Non visualizzerà nessun esito (SI o NO) se lo strumento è stato impostato con correzione di temperatura tipo “nDC” (vedere § 5.2.3)

    ```
    15/05/10   15:35:00
    
    P d c   3 . 1 2 5   k W
    V d c   3 8 9   V
    I d c   8 . 0 1   A
    n d c   0 . 8 8   ° C
    P a c   3 . 0 1 2   k W
    V a c   2 3 1   V
    I a c   1 3 . 0 3   A
    n a c   0 . 9 6
    E S I T O   S I
    Selezione   C L D
    ```

30. Premere `SAVE` per salvare i risultati ottenuti (vedere § 7.1) o `ESC` per uscire dalla videata e tornare alla videata iniziale.

### 6.1.2. Collaudo Impianti FV con inverter Mono/Multi MPPT - Uscita AC mono/trifase

Lo strumento `SOLAR I - Vw`, `SOLAR I - Ve` abbinato alle unità remote `SOLAR - 02` e `MPP300` (opzionale) consente di eseguire collaudi su installazioni FV caratterizzate da 1 o più stringhe (aventi lo stesso orientamento ed inclinazione) ed uscita Monofase o Trifase. L’unità remota `MPP300` è in grado di comunicare con il `SOLAR I - Vw`, `SOLAR I - Ve` (per la gestione delle operazioni di sincronizzazione e scaricamento dei dati) e con l’unità remota `SOLAR - 02` (dedicata alla registrazione dei valori di Irraggiamento e temperatura) attraverso un collegamento wireless a radiofrequenza (RF) attivo fino ad una distanza massima di circa 1m tra di esse.

Fig. 5: Collegamento dell’MPP300 per collaudo di un impianto FV Monofase
Fig. 6: Collegamento dell’MPP300 per collaudo di un impianto FV Trifase

**ATTENZIONE**
*   Quando il `SOLAR I - Vw`, `SOLAR I - Ve` è impostato in modo da utilizzare `MPP300` come unità remota TUTTI i collegamenti relativi a grandezze elettriche (Tensioni e correnti) vanno eseguiti sull’unità `MPP300`. Il `SOLAR I - Vw`, `SOLAR I - Ve` non deve avere nessuna tensione o corrente collegata a propri ingressi.
*   La massima tensione per gli ingressi di `MPP300` è 1000V DC tra gli ingressi VDC1,VDC2, VDC3 e 600V AC fra gli ingressi VAC1, VAC2, VAC3. Non misurare tensioni che eccedano i limiti espressi in questo manuale. Il superamento di tali limiti potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.
*   Per garantire la sicurezza dell’operatore, durante la fase dei collegamenti mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter).

1.  Controllare ed eventualmente impostare sul `SOLAR - 02` la sensibilità della cella di riferimento coerentemente con il tipo di moduli FV che si andrà ad esaminare (vedere manuale d’uso del `SOLAR - 02`).

2.  Si raccomanda di eseguire una valutazione preliminare del valore dell’Irraggiamento sul piano dei moduli FV in esame tramite l’unità `SOLAR - 02` (in funzionamento indipendente) e la cella di riferimento. Si ricorda che in accordo alla Guida CEI 82 - 25 l’irraggiamento minimo per eseguire una verifica di efficienza su un impianto fotovoltaico è pari a 600W/m^2.

3.  Accendere il `SOLAR I - Vw`, `SOLAR I - Ve` e controllare ed eventualmente modificare le impostazioni relativamente al tipo di unità remota, alla soglia minima di irraggiamento, al fondo scala delle pinze AC e DC, al periodo di integrazione e i parametri del sistema in esame (vedere § 5.1.4, § 5.1.5, § 5.1.6, § 5.2.2).

4.  Per garantire la sicurezza dell’operatore mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter).

5.  Avvicinare fra loro (max 1 m circa) il `SOLAR I - Vw`, `SOLAR I - Ve` il `SOLAR - 02` e l’unità `MPP300`. Tutti gli strumenti devono essere accesi (vedere i manuali d’uso di `SOLAR - 2` e `MPP300` per ulteriori dettagli).

6.  Su `SOLAR I - Vw` premere il tasto `MENU`, selezionare la funzione `CLD` e premere `ENTER` ed attendere che le tre unità inizino a comunicare fra loro. Questa condizione è evidenziata dalla presenza simultanea dei seguenti indicatori:
    *   Simbolo fisso (non intermittente) sul display del `SOLAR I - Vw`, `SOLAR I - Ve`
    *   Simbolo fisso (non intermittente) sul display del `SOLAR - 02`
    *   Lampeggio verde dei LED MASTER e REMOTE sull’unità `MPP300`

7.  Collegare gli ingressi `VDC 1(+)` e `VDC1(-)` dell’unità `MPP300` ai terminali di uscita della stringa rispettando le polarità ed i colori indicati in Fig. 5 o Fig. 6.

8.  Ripetere l’operazione indicata al punto sopra per altri eventuali inseguitori di potenza DC da monitorare utilizzando gli ingressi `VDC2` e `VDC3` in accordo al numero di ingressi DC impostato (vedi § 5.2.1.1).

9.  Collegare il connettore di uscita della pinza DC all’ingresso `IDC1` dell’unità `MPP300`.

    **ATTENZIONE**
    PRIMA DI COLLEGARE LE PINZE DC SUI CONDUTTORI
    Accendere la pinza, controllare il LED indicante lo stato delle batterie interne della pinza (se presenti), selezionare la portata corretta, premere il tasto `ZERO` sulla pinza DC e verificare sul display del `SOLAR I - Vw`, `SOLAR I - Ve` l’effettivo azzeramento del valore Idc corrispondente (valori fino a 0.02A sono comunque accettabili).

10. Inserire la pinza di corrente DC sul conduttore positivo in uscita dalla stringa rispettando il verso della freccia presente sulla pinza stessa come indicato in Fig. 5 o Fig. 6. Posizionare il toroide della pinza il più lontano possibile dall’inverter e dal conduttore negativo in uscita dalla stringa stessa.

11. Ripetere le operazioni indicate ai due punti sopra per altri eventuali inseguitori di potenza DC da monitorare utilizzando gli ingressi `IDC2` e `IDC3` in accordo al numero di ingressi DC impostato (vedi § 5.2.1.1).

12. Collegare gli ingressi `VAC1` ed `N` dell’unità `MPP300` rispettivamente ai conduttori di Fase e Neutro rispettando le polarità ed i colori indicati in Fig. 5 o Fig. 6. Nel caso di impianti trifase in cui il conduttore di Neutro non sia disponibile, collegare l’ingresso `N` a Terra.

13. Nel caso di inverter con uscita Trifase (vedi impostazioni § 5.2.1.1), ripetere l’operazione indicata al punto sopra per le restanti fasi utilizzando gli ingressi `VAC2` e `VAC3` dell’`MPP300`.

14. Collegare la pinza AC sul conduttore di Fase L1 rispettando il verso della freccia presente sulla pinza stessa come indicato in Fig. 5. o e Fig. 6. Posizionare il toroide della pinza il più lontano possibile dall’inverter e dal conduttore Neutro. Collegare l’uscita della pinza all’ingresso `IAC 1` dell’`MPP300`.

15. Nel caso di inverter con uscita Trifase (vedi impostazioni § 5.2.1.1), ripetere l’operazione indicata al punto sopra per le restanti fasi utilizzando gli ingressi `IAC2` e `IAC3` dell’`MPP300`.

16. Rimettere nuovamente in servizio il sistema elettrico in esame.

17. A display del `SOLAR I - Vw`, `SOLAR I - Ve` saranno visualizzati i valori dei parametri elettrici complessivi del sistema in esame. In particolare in questa videata:
    *   `Pdc` = Potenza DC complessiva (somma delle potenze di stringa)
    *   `Pac` = Potenza AC (se monofase) o somma delle potenze AC (se trifase)

    Si consiglia di controllare che i valori dei parametri elettrici (Pnom, Pdc, Pac) e che il valore del rendimento ac (` ac`) siano coerenti con il sistema in esame (Esempio: ` ac > 1` non è fisicamente accettabile).

    ```
    15/05/10   15:34:26
    P R p   -   -   -
    I r r   -   -   -   W / m 2
    P n o m   3 . 5 0 0   k W
    T c   -   -   -   ° C
    T e   -   -   -   ° C
    P d c   3 . 1 2 5   k W
    P a c   2 . 9 6 0   k W
    n d c   -   -   -
    n a c   0 . 9 5
      G O   p e r   A v v i a r e
    Selezione   M P P
    ```

18. Su `SOLAR I - Vw`, `SOLAR I - Ve` premere il tasto () per accedere alla seconda videata che riporta i valori dei parametri DC in uscita alle stringhe in accordo al numero di ingressi DC impostato (vedi § 5.2.1.1). In particolare in questa videata:
    *   `Vdcx`=Tensione DC della stringa x
    *   `Idcx`=Corrente DC della stringa x.
    *   `Pdx` = Potenza DC della stringa x

    Si consiglia di controllare che i valori dei parametri elettrici (Vdc, Idc, Pdc) e siano coerenti con il sistema in esame.

    ```
    15/05/10   15:34:26
    
    V d c 1   4 6 0 . 1   k W
    V d c 2   4 6 1 . 4   V
    V d c 3   4 6 2 . 5   A
    I d c 1   2 . 2 5   A
    I d c 2   2 . 3 1   A
    I d c 3   2 . 2 1   A
    P d c 1   1 . 0 3   5   k W
    P d c 2   1 . 0   6 6   k W
    P d c 3   1   .   0 2 4   k W   
    G O   p e r   A v v i a r e
    Selezione   M P P
    ```

19. Su `SOLAR I - Vw`, `SOLAR I - Ve` premere il tasto () per accedere alla terza videata che riporta i valori dei parametri elettrici sul lato AC dell’inverter coerentemente con le impostazioni effettuate al § 5.2.2 (monofase, trifase 4 fili). In particolare in questa videata:
    *   `Vacx y` =Tensione AC fra fase e Neutro (se monofase) o fra le fasi x e y (se trifase)
    *   `Iacx`=Corrente AC della fase x
    *   `Pacx` = Potenza AC della fase x

    Si consiglia di controllare che i valori dei parametri elettrici (Vac, Iac, Pac) e siano coerenti con il sistema.

    ```
    15/05/10   15:34:26
    
    V a   c 1   2   4 0 1 . 4   V
    V a c   2   3   4 0 1 . 1   V
    V a c   3   1   4 0 0 . 1   V
    I a c   1   4 . 2 6   A
    I a c   2   4 . 2 6   A
    I a c   3   4 . 2 7   A
    P a c 1   9 8 7   W
    P a c 2   9 8 6   W
    P a c 3   9 8 5   W
    
    G O   p e r   A v v i a r e
    Selezione   M P P
    ```

    Esempio di videata per sistemi FV con uscita trifase

20. Mantenendo sempre i tre strumenti in prossimità fra loro (max 1m circa), premere il tasto `GO/STOP` sul `SOLAR I - Vw`, `SOLAR I - Ve` per attivare il collaudo. Conseguentemente:
    *   Sul display di `SOLAR I - Vw`, `SOLAR I - Ve` appare il messaggio “reg. in attesa”
    *   Sul display di `SOLAR - 02` appare il messaggio “HOLD” e l’indicazione del tempo in secondi rimanenti prima dell’avvio registrazione
    *   Su `MPP300` si accende in verde (non lampeggiante) il LED `STATUS`

    ```
    15/05/10   15:34:26
    P R p   -   -   -   W / m 2
    I r r   -   -   -   W / m 2
    P n o m   3 . 5 0 0   k W
    T c   -   -   -   ° C
    T e   -   -   -   ° C
    P d c   3 . 1 2 5   k W
    P a c   2 . 9 6 0   k W
    n d c   -   -   -
    n a c   0 . 9 5
      r e g .   i n   a t t e s a
    Selezione   M P P
    ```

21. Al raggiungimento dell’istante ”00” successivo alla pressione del tasto `GO/STOP` il collaudo ha inizio e le tre unità sono tra loro sincronizzate. In tali condizioni:
    *   Sul display di `SOLAR I - Vw`, `SOLAR I - Ve` appare il messaggio “reg. in corso”
    *   Sul display di `SOLAR - 02` appare il messaggio “Recording…”
    *   Su `MPP300` si lampeggia in verde il LED `STATUS`

    ```
    15/05/10   15:35:00
    P R p   -   -   -
    I r r   -   -   -   W / m 2
    P n o m   3 . 5 0 0   k W
    T c   -   -   -   ° C
    T e   -   -   -   ° C
    P d c   3 . 1 2 5   k W
    P a c   2 . 9 6 0   k W
    n d c   -   -   -
    n a c   0 . 9 5
    r e g .   i n   c o r s o
    Selezione   M P P
    ```

22. In qualunque momento sarà possibile analizzare lo stato attuale della registrazione tramite pressione del tasto `MENU`. Verranno visualizzati:
    *   Data ed ora di inizio registrazione
    *   Il valore impostato del periodo di integrazione
    *   Il numero di Periodi trascorsi dall’inizio registrazione
    *   La capacità di memoria residua di registrazione.

    Premere il tasto `ESC` per uscire dalla videata.

    ```
    15/05/10   15:35:00
    S t a r t
    1 4 / 0 2 / 0 0   1 7 : 1 8 : 0 0
    P e r i o d o :   5 s
    N u m e r o   I P   6 1
    A u t o n o m i a   0 d   1 h
    Reg.   in corso
    r e g .   i n   c o r s o
    Selezione   M P P
    ```

23. A questo punto è possibile portare l’unità `SOLAR - 02` in prossimità delle stringhe FV per effettuare le misure di irraggiamento e temperatura tramite le rispettive sonde. Quando la distanza tra l’unità `SOLAR - 02` e `MPP 300` è tale da non consentire il collegamento RF, sul display del `SOLAR - 02`, il simbolo “` `” lampeggia per circa 30s poi scompare. L’unità `MPP300` resta invece sempre in ricerca del collegamento RF con l’unità `SOLAR - 02`.

24. Posizionare la cella di riferimento sul piano dei moduli FV. Fare riferimento al relativo manuale d’uso per un corretto montaggio.

25. Posizionare il sensore di temperatura a contatto con il retro del modulo fissandolo con nastro e evitando di toccarlo con le dita (azione che potrebbe falsare la misura).

26. Attendere qualche secondo per consentire alle sonde di raggiungere una misura stabile e poi collegare la sonda di Irraggiamento all’ingresso `PYRA/CELL` e la sonda di temperatura all’ingresso `TEMP` dell’unità `SOLAR - 02`.

27. Attendere il messaggio “READY” a display del `SOLAR - 02` ad indicare che l’unità ha rilevato dei dati con Irraggiamento solare > soglia minima impostata (vedere § 5.1.5).

28. Con messaggio “READY” a display attendere per circa 1 minuto in modo da raccogliere un certo numero di campioni.

29. Scollegare le sonde di Irraggiamento e temperatura dall’unità `SOLAR - 02`, e avvicinarla all’unità `MPP300`. Avvicinare inoltre l’unità principale `SOLAR I - Vw`, `SOLAR I - Ve` all’`MPP300`. Le tre unità deve essere vicine fra loro (max 1m).

30. L’unità principale `SOLAR I - Vw`, `SOLAR I - Ve` deve essere in modalità `CLD`, se è assente il simbolo “` `” lampeggiante, premere il tasto  per riattivare la ricerca del collegamento RF.

31. Premere il tasto  sul `SOLAR - 02` per riattivare il collegamento RF. Conseguentemente sull’unità principale verrà visualizzato il messaggio “connessione radio attiva”.

<!-- Chunk: Pages 33-48 -->
32. Per arrestare il collaudo premere il tasto **GO/STOP** sullo strumento **SOLAR I - Vw**, **SOLAR I - Ve** e confermare con **ENTER** alla richiesta di arresto della registrazione
33. Sul display del **SOLAR I - Vw**, **SOLAR I - Ve** sarà visualizzato il messaggio **“SCARICO DATI”** ad indicare il trasferimento dei dati verso l’unità principale nelle sue varie fasi.
34. Dopo la fase automatica di trasferimento dati, lo strumento visualizzerà:
    *   **ESITO SI**: se esiste almeno 1 valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
    *   **ESITO NO**: se NON esiste nessun valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
    *   **Impossibile effettuare l’analisi**: se l’irraggiamento non ha mai raggiunto un valore stabile superiore alla soglia minima impostata oppure se non esiste nessun valore valido durante tutto l’arco della registrazione (PRp > 1.15)
    *   Non visualizzerà nessun esito (SI o NO) se lo strumento è stato impostato con correzione di temperatura tipo “**nDC**” (v. § 5.2.3)
35. Premere **SAVE** per salvare i risultati ottenuti (vedere § 7.1) o **ESC** per uscire dalla videata dei risultati e tornare alla videata iniziale

```
15/05/10   15:35:00
  P R p   0 . 8 1   5
I r r   9 7 1   W / m 2
P n o m   3 . 5 0 0   k W
T c   4 5 . 1   ° C
T e   3 0 . 5   ° C
P d c   3 . 1 2 5   k W
P a c   2 . 9 6 0   k W
n d c   0 . 8 6   0
n a c   0 . 9 5   1
E S I T O   S I
Selezione   M P P
```

## 6.2. MISURA DELLA CARATTERISTICA I - V

Lo strumento consente il rilievo della caratteristica *I - V* in modo di attivazione Manuale o Automatico operando in una delle due seguenti modalità:
*   Rilievo curva *I - V* con misura di *Irr*/*Temp* effettuata direttamente da strumento
*   Rilievo curva *I - V* con misura di *Irr*/*Temp* effettuata tramite unità remota **SOLAR - 02**

Per informazioni teoriche sulla misura vedere il § 11.3

### 6.2.1. Rilievo curva I - V con misura Irr/Temp effettuata direttamente da strumento

**ATTENZIONE**
Non utilizzare lo strumento per misure di Curve *I - V* e test **IVCK** su moduli FV con efficienza >19%. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento

**ATTENZIONE**
*   La massima tensione tra gli ingressi P1, P2, C1 e C2 è **1000VDC** (per gli strumenti **I - V400w** e **SOLAR I - Vw**) o **1500VDC** (per gli strumenti **I - V500w** e **SOLAR I - Ve**). Non misurare tensioni eccedenti i limiti espressi nel § 10.2
*   La corrente massima tollerabile dallo strumento è **15A**. Non effettuare prove su stringhe di moduli FV in parallelo
*   Non eseguire mai prove su moduli o stringhe FV connessi al convertitore DC/AC

1.  Accendere lo strumento premendo il tasto **ON/OFF**
2.  Controllare che l’unità remota **SOLAR - 02** non sia selezionata (opzione **NO**) sullo strumento (vedere § 5.1.4)
3.  Controllare che i valori impostati nella sezione “Unità Remota” (vedere § 5.1.4) siano coerenti con le caratteristiche della cella di riferimento utilizzata in funzione del tipo di modulo/stringa in esame
4.  Controllare che il valore impostato nella sezione “Irraggiamento” (vedere § 5.1.5) sia coerente con le misure che si intende effettuare. Si consiglia si eseguire le misure con soglia **≥ 700 W/m²** in accordo alla normativa IEC/EN60891
5.  Tornare al MENU principale e selezionare la voce “**I - V**”
6.  Premere il tasto **ENTER**, selezionare con i tasti freccia (, ) la voce “**Misurazione** ”
7.  Usare il tasto freccia  per accedere al sottomenu interno, selezionare la voce “**Caratt. IV**” e confermare con **ENTER** per attivare la videata iniziale del rilievo della caratteristica IV

```
15/05/10   15:34:26
V d c   =   0 . 0   V
I r r   =   0   W / m 2
T c   =   -   -   -   ° C
Modulo: SUNPOWER 210
C a r a t t .   I V
I m p   I V   C h e c k
M i s
Selezione   I   -   V
```

8.  La seguente videata è mostrata a display in cui:
    *   **Vdc** = tensione DC in uscita dal modulo, misurata tra gli ingressi C1 e C2 dello strumento
    *   **Irr** = irraggiamento misurato dalla cella di riferimento
    *   **Tc** = temperatura della cella del modulo. Questo campo presenta le seguenti indicazioni in funzione del modo di temperatura selezionato:
        *   **AUTO** → modo misura Temp. Automatico
        *   **Numero** → modo misura Temp. MAN o AUX
        *   “ **- - -** “ → mod. AUX con sonda non collegata
    *   **Modulo** = tipo di modulo attualmente selezionato
    *   **Temp** = modo di misura della temperatura del modulo
    *   **Start** = modalità di attivazione della misura

```
15/05/10   15:34:26
V d c   =   0 . 0   V
I r r   =   -   -   -   W / m 2
T c   = A u t   o
Modulo: DEFAULT
Temp: Auto
Start:   Manuale
Selezione   I   -   V
```

9.  Premere il tasto **ENTER**, selezionare la voce “**Impostazioni**” e confermare ancora con **ENTER** per accedere alla videata seguente in cui è possibile eseguire le impostazioni sulla scelta del tipo di modulo e sul numero di moduli di cui è costituita la stringa oggetto del test

```
15/05/10   15:34:26
V d c   =   0 . 0   V
I r r   =   -   -   -   W / m 2
T c   =   -   -   -   ° C
I m p o s t a z i o n i
M i s u r a z i o n e   
Selezione   I   -   V
```

10. Usare i tasti freccia (, ) per selezionare il tipo di modulo tra quelli presenti nel database interno dello strumento (vedere § 5.3.1)
11. Usare i tasti freccia (, ), selezionare la voce “**Mod. x Str**” e usare i tasti freccia (, ) per inserire il numero di moduli della stringa in prova. Il numero massimo di moduli impostabile è **50**
12. Usare i tasti freccia (, ), selezionare la voce “**Anni Servizio**” e usare i tasti freccia (, ) per selezionare il numero di anni di servizio dell’impianto/stringa/modulo FV dalla sua installazione (vedere § 6.2.3). Il valore massimo impostabile è **25.0** (0.5 = 6 mesi)

```
15/05/10   15:34:26
Tipo   :    SUNPOWER 210 
M o d .   x   S t r   :   1 5
A n n i   s e r v  T e m p  :   4 . 5
:   A u t o
S t a r t   :   M a n u a l e
P m a x   =   2 1 0
V o c   =   4 7 . 7 0
V m p p   =   4 0 . 0 0
I s c   =   5 . 7 5
I m p p   =   5 . 2 5
I M P O S T
```

13. Usare i tasti freccia (, ), selezionare la voce “**Temp**” e usare i tasti freccia (, ) per scegliere il tipo di misura della temperatura del modulo tra le modalità:
    *   **Auto** → misura automatica eseguita in funzione del valore misurato della tensione a vuoto dei moduli. (Modalità di funzionamento raccomandata)
    *   **Manuale** → inserimento da parte dell’operatore del valore noto della temperatura del modulo nel campo “**Valore**” corrispondente
    *   **Aux** → misura della temperatura con sonda ausiliaria
14. Usare i tasti freccia (, ), selezionare la voce “**Start**” e usare i tasti freccia (, ) per selezionare il modo di attivazione della misura scegliendo tra le seguenti opzioni:
    *   **Auto** → test attivato automaticamente dallo strumento in presenza di tensione stabile in ingresso per circa 1s e con valore compreso nel campo di misura (vedere § 10.2)
    *   **Manuale** → test attivato dall’utente alla pressione del tasto **GO/STOP**
15. Premere **SAVE** per salvare le selezioni eseguite oppure **ESC/MENU** per uscire senza salvare

16. Montare lo stelo sul disco dell’accessorio M304 (inclinometro) in dotazione e tenerlo appoggiato sul piano del modulo. Verificare che l’ombra dello stelo proiettata sul disco cada entro il “cerchio concentrico limite” interno al disco stesso (vedere Fig. 7b). In caso contrario l’angolo tra i raggi solari e la superficie del modulo è troppo elevato e pertanto le misure eseguite dallo strumento NON sono da ritenere attendibili. Ripetere le operazioni in altri momenti della giornata
17. Fissare la staffa al modulo usando le viti in dotazione e montare la cella di riferimento su di essa possibilmente con terminali di uscita rivolti verso il basso. Ruotare la cella fino ad appoggiarla sull’aletta presente sulla staffa in modo da renderla esattamente parallela al piano del modulo e fissarla quindi tramite le apposite viti
18. Collegare l’uscita della cella, corrispondente al tipo di modulo in prova, all’ingresso **IRR.** dello strumento usando il cavo in dotazione alla cella stessa
19. Collegare, se utilizzato, il sensore di temperatura all’ingresso **AUX** dello strumento ed al retro del modulo sotto una cella usando nastro adesivo
20. Collegare lo strumento al modulo/stringa in prova come mostrato nella seguente Fig. 7a. In particolare collegare il polo Negativo in uscita dal modulo/stringa ai terminali P1, C1 e il polo Positivo in uscita dal modulo/stringa ai terminali P2, C2. In modalità di attivazione misura “**Auto**” è raccomandato l’uso dell’accessorio opzionale **KITKELVIN**

Fig. 7a: Collegamento strumento al modulo/stringa FV
Fig. 7b: Posizionamento inclinometro M304

**ATTENZIONE**
Il metodo usato dallo strumento nella misurazione della tensione VDC e della corrente IDC in uscita dal modulo/stringa FV è quello a “4 terminali” pertanto è possibile prolungare i cavi di misura collegati agli ingressi P1, C1, P2, C2 senza necessità di eseguire alcuna compensazione della resistenza dei cavi di prova. Per le prolunghe usare sempre cavi con sezione **≥ 4mm²**

21. Dopo il collegamento all’impianto, lo strumento mostra in tempo reale i valori di:
    *   **Vdc** = tensione DC in uscita dal modulo/stringa
    *   **Irr** = irraggiamento misurato dal sensore
    *   **Tc** = temperatura del modulo

```
15/05/10   15:34:26
V d c   =   3 6 7   V
I r r   =   1 0 4 5   W / m 2
T c   =   4 5   ° C
Modulo: SUNPOWER 210
Selezione   I   -   V
```

**ATTENZIONE**
Alla pressione del tasto **GO/STOP** lo strumento può fornire diversi messaggi di errore (vedere § 6.3) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test

22. Premere il tasto **GO/STOP** (in modo di attivazione Manuale) per attivare il test. In caso di assenza di condizioni di errore, lo strumento fornisce il messaggio “**Misura in corso…**” per alcuni secondi in funzione della potenza in esame

```
15/05/10   15:34:26
V d c   =   3 6 7   V
I r r   =   1 0 4 5   W / m 2
Tc   =   45   °C
Modulo: SUNPOWER 210
Misura in corso…
Selezione   I   -   V
```

23. Al termine della prova, lo strumento fornisce i valori delle grandezze (come mostrato nella videata di fianco oltre all’esito del test (vedere § 6.2.3) in base ai calcoli eseguiti automaticamente relativamente a:
    *   Traslazione della curva *I - V* alle condizioni STC
    *   Verifica delle tolleranze % della potenza massima dichiarata dal costruttore

```
15/05/10   15:34:26
V o c   =   1 5 . 2   V
V m p p   =   1 4 . 7   V
I m p p   =   4 . 7   A
I s c   =   5 . 2   A
P m a x   =   2 0 0   W
F F   =   7 7 . 1   %
D P m a x   =   2 . 1   %
RISULTATI @ STC   –   ESITO: OK
Selezione   I   -   V
```

**ATTENZIONE**
*   Lo strumento riferisce tutti i valori delle grandezze ad un solo modulo alle condizioni STC
*   La tensione totale di stringa ottenuta a OPC è divisa per il numero dei moduli della stessa. Considerando questo valore “medio”, unitamente alla corrente misurata, lo strumento calcola la curva *I - V* @ OPC che viene poi traslata alle condizioni STC

24. Premere **ENTER** per la visualizzazione dei risultati di misura sia in forma numerica che grafica riferiti ad STC o ad OPC (vedere § 6.2.3)
25. Usare il tasto freccia  per la selezione della tabella o del grafico corrispondente
26. Premere il tasto **SAVE** per salvare il risultato del test nella memoria dello strumento (vedere § 7.2) o il tasto **ESC/MENU** per uscire dalla videata senza salvare e tornare al menu principale
27. Il modo di attivazione “**Auto**” richiede di scollegare e ricollegare i terminali di prova per avviare automaticamente una nuova misura

```
15/05/10   15:34:26
V o c   =   1 5 . 2   V
V m p p   =   1 4 . 7   V
I m p p   =   4 . 7   A
I s c   =   5 . 2   A
P m a x   =   2 0 0   W
F F   =   7 7 . 1   %
D P m a x   =   2 . 1   %
T a b e l l a   
G r a f i c o      –   ESITO: OK
Selezione   I   -   V
```

### 6.2.2. Rilievo curva I - V con misura Irr/Temp effettuata tramite unità SOLAR - 02

Il rilievo della curva *I - V* con misura di Irragg./Temp. effettuata tramite unità remota **SOLAR - 02** può essere eseguita in una delle due seguenti modalità:
*   Unità remota **SOLAR - 02** in connessione RF
*   Unità remota **SOLAR - 02** in registrazione sincrona (no connessione RF)

#### 6.2.2.1. Rilievo curva I - V tramite unità SOLAR - 02 in connessione RF

Questa modalità è possibile SOLO se la distanza fra lo strumento e l’unità remota **SOLAR - 02** è tale da consentire un collegamento stabile a RF. La distanza limite fra strumento e unità remota è influenzata da ostacoli, umidità dell’aria, ecc.. quindi è solo stimabile nell’ordine di qualche metro.

**ATTENZIONE**
Non utilizzare lo strumento per misure di Curve *I - V* e test **IVCK** su moduli FV con efficienza >19%. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento

**ATTENZIONE**
*   La massima tensione tra gli ingressi P1, P2, C1 e C2 è **1000VDC** (per gli strumenti **I - V400w** e **SOLAR I - Vw**) o **1500VDC** (per gli strumenti **I - V500w** e **SOLAR I - Ve**). Non misurare tensioni che eccedano i limiti del § 10.2
*   La corrente massima tollerabile dallo strumento è **15A**. Non effettuare prove su stringhe di moduli FV in parallelo
*   Non eseguire mai prove su moduli o stringhe FV connessi al convertitore DC/AC

1.  Accendere lo strumento premendo il tasto **ON/OFF**
2.  Controllare che l’unità remota **SOLAR - 02** sia selezionata (opzione **SI**) sullo strumento (vedere § 5.1.1)
3.  Controllare che i valori impostati nella sezione “Unità Remota” (vedere § 5.1.4) siano coerenti con le caratteristiche della cella di riferimento utilizzata in funzione del tipo di modulo/stringa in esame
4.  Controllare che il valore impostato nella sezione “Irraggiamento” (vedere § 5.1.5) sia coerenti con le misure che si intende effettuare. Si consiglia si eseguire le misure con soglia **≥ 700 W/m²** in accordo alla normativa IEC/EN60891
5.  Tornare al MENU principale e selezionare la voce “**I - V**”
6.  Premere il tasto **ENTER**, selezionare con i tasti freccia (, ) la voce “**Misurazione** ”
7.  Usare il tasto freccia  per accedere al sottomenu interno, selezionare la voce “**Caratt. IV**” e confermare con **ENTER** per attivare la videata iniziale del rilievo della caratteristica IV

```
15/05/10   15:34:26
V d c   =   0 . 0   V
I r r   =   0   W / m 2
T c   =   -   -   -   ° C
Modulo: SUNPOWER 210
C a r a t t .   I V
I m p   I V   C h e c k
M i s
Selezione   I   -   V
```

8.  Accendere l’unità remota **SOLAR - 02** ed attendere che sul display dello strumento appaia il messaggio “**Connessione radio attiva**”

9.  Sul display dello strumento appare la seguente videata:
    *   **Vdc** = tensione DC in uscita dal modulo/stringa
    *   **Irr** = irraggiamento misurato dalla cella di riferimento
    *   **Modulo** = tipo di modulo attualmente selezionato
    *   **Temp** = modo di misura della temperatura del modulo
    *   **Tc** = temperatura del modulo FV. Questo campo presenta una delle seguenti indicazioni in funzione della modalità di misura della temperatura selezionata:
        *   **AUTO**: mod. misura Temp. Automatica
        *   **Numero**: mod. misura Temp. MAN o AUX
        *   “ **- - -** “: mod. AUX con la sonda non collegata
    *   **Start** = modalità di attivazione della misura
    *   il simbolo fisso (non intermittente) che indica la presenza di un collegamento stabile con **SOLAR - 02**

```
15/05/10   15:34:26
V d c   =   0 . 0   V
I r r   =   -   -   -   W / m 2
T c   = A u t o   ° C
Modulo: DEFAULT
Temp: Auto
Start: Manuale
Selezione   I   –   V
```

10. Premere il tasto **ENTER**, selezionare la voce “**Impostazioni**” e confermare ancora con **ENTER** per accedere alla videata seguente in cui è possibile eseguire le impostazioni sulla scelta del tipo di modulo e sul numero di moduli di cui è costituita la stringa oggetto del test

```
15/05/10   15:34:26
V d c   =   0 . 0   V
I r r   =   -   -   -   W / m 2
T c   =   -   -   -   ° C
A t t i v a   R e g .
I m p o s t a z i o n i
M i s u r a z i o n e   
Selezione   I   -   V
```

11. Usare i tasti freccia (, ) per selezionare il tipo di modulo tra quelli presenti nel database (vedere § 5.3.1)
12. Usare i tasti freccia (, ), selezionare la voce “**Mod. x Str**” e usare i tasti freccia (, ) per inserire il numero di moduli della stringa. Il numero massimo impostabile è **50**
13. Usare i tasti freccia (, ), selezionare la voce “**Anni Servizio**” e usare i tasti freccia (, ) per selezionare il numero di anni di servizio dell’impianto/stringa/modulo FV dalla sua installazione (vedere § 6.2.3). Il valore massimo impostabile è **25.0** (0.5 = 6 mesi)

```
15/05/10   15:34:26
Tipo   :    SUNPOWER 210 
M o d .   x   S t r   :   1 5
A n n i   s e r v  T e m p  : 4 . 5
:   A u t o
S t a r t :   : M a n u a l e
P m a x   =   2 1 0
V o c   =   4 7 . 7 0
V m p p   =   4 0 . 0 0
I s c   =   5 . 7 5
I m p p   =   5 . 2 5
I M P O S T
```

14. Usare i tasti freccia (, ), selezionare la voce “**Temp**” e usare i tasti freccia (, ) per scegliere il tipo di misura della temperatura del modulo tra le modalità:
    *   “**Auto**” → misura automatica eseguita in funzione del valore misurato della tensione a vuoto di moduli. (Modalità di funzionamento raccomandata)
    *   **Manuale** → inserimento da parte dell’operatore del valore noto della temperatura del modulo nel campo “**Valore**” corrispondente
    *   **Aux** → misura della temperatura con sonda ausiliaria
15. Usare i tasti freccia (, ), selezionare la voce “**Start**” e usare i tasti freccia (, ) per selezionare il modo di attivazione della misura scegliendo tra le seguenti opzioni:
    *   **Auto** → test attivato automaticamente dallo strumento in presenza di tensione stabile in ingresso per circa 1 s e con valore compreso nel campo di misura (vedere § 10.2)
    *   **Manuale** → test attivato dall’utente alla pressione del tasto **GO/STOP**
16. Premere **SAVE** per salvare le selezioni eseguite oppure **ESC/MENU** per uscire senza salvare

17. Montare lo stelo sul disco dell’accessorio M304 (inclinometro) in dotazione e tenerlo appoggiato sul piano del modulo. Verificare che l’ombra dello stelo proiettata sul disco cada entro il “cerchio concentrico limite” interno al disco stesso (vedere Fig. 8). In caso contrario l’angolo tra i raggi solari e la superficie del modulo è troppo elevato e pertanto le misure eseguite dallo strumento NON sono da ritenere attendibili. Ripetere le operazioni in altri momenti della giornata.
18. Fissare la staffa al modulo usando le viti in dotazione e montare la cella di riferimento su di essa possibilmente con terminali di uscita rivolti verso il basso. Ruotare la cella fino ad appoggiarla sull’aletta presente sulla staffa in modo da renderla esattamente parallela al piano del modulo e fissarla quindi tramite le apposite viti
19. Collegare l’uscita della cella, corrispondente al tipo di modulo in prova, all’ingresso **PYRA/CELL** del **SOLAR - 02** usando il cavo in dotazione alla cella stessa.
20. Collegare, se utilizzato, il sensore di temperatura all’ingresso **TEMP** del **SOLAR - 02** ed al retro del modulo sotto una cella usando nastro adesivo
21. Collegare lo strumento al modulo/stringa in prova come mostrato nella seguente Fig. 9. In particolare collegare il polo Negativo in uscita dal modulo/stringa ai terminali P1, C1 e il polo Positivo in uscita dal modulo/stringa ai terminali P2, C2. In modalità di attivazione misura “**Auto**” è raccomandato l’uso dell’accessorio opzionale **KITKELVIN**

Fig. 8: Posizionamento inclinometro M304
Fig. 9: Collegamento dello strumento al modulo/stringa FV

22. Dopo il collegamento all’impianto, lo strumento mostra in tempo reale i valori di:
    *   **Vdc** = tensione DC in uscita dal modulo/stringa
    *   **Irr** = irraggiamento mis. dalla cella di rif. in dotazione
    *   **Modulo** = tipo di modulo attualmente selezionato
    *   **Temp** = modo di misura della temperatura del modulo
    *   **Tc** = temperatura del modulo FV. Questo campo presenta una delle seguenti indicazioni in funzione della modalità di misura della temperatura selezionata:
        *   **AUTO**: mod. misura Temp. Automatica
        *   **Numero**: mod. misura Temp. MAN o AUX
        *   “ **- - -** “: mod. AUX con sonda non collegata
    *   **Start** = modalità di attivazione della misura
    *   Il simbolo fisso indica la presenza di un collegamento stabile con **SOLAR - 02**

```
15/05/10   15:34:26
V d c   =   3 6 7   V
I r r   =   1 0 4 5   W / m 2
T c   =   4 5   ° C
Modulo: SUNPOWER 210
Temp: Auto
Start: Manuale
Selezione   I   –   V
```

**ATTENZIONE**
Alla pressione del tasto **GO/STOP** lo strumento può fornire diversi messaggi di errore (vedere § 6.3) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test

23. Premere il tasto **GO/STOP** (in modo di attivazione Manuale) per attivare il test. In caso di assenza di condizioni di errore, lo strumento fornisce il messaggio “**Misura in corso…**” per alcuni secondi in funzione della potenza in esame

```
15/05/10   15:34:26
V d c   =   3 6 7   V
I r r   =   1 0 4 5   W / m 2
Tc   =   45   °C
Modulo: SUNPOWER 210
Misura in corso…
Selezione   I   -   V
```

24. Al termine della prova, lo strumento fornisce i valori delle grandezze (riferiti tutti ad un solo modulo alle condizioni STC) come mostrato nella videata di fianco oltre all’esito del test (vedere § 6.2.3) in base ai calcoli eseguiti automaticamente relativamente a:
    *   Traslazione della curva *I - V* alle condizioni STC
    *   Verifica delle tolleranze % della potenza massima dichiarata dal costruttore

```
15/05/10   15:34:26
V o c   =   1 5 . 2   V
V m p p   =   1 4 . 7   V
I m p p   =   4 . 7   A
I s c   =   5 . 2   A
P m a x   =   2 0 0   W
F F   =   7 7 . 1   %
D P m a x   =   2 . 1   %
RISULTATI @ STC   –   ESITO: OK
Selezione   I   -   V
```

25. Premere **ENTER** per la visualizzazione dei risultati di misura sia in forma numerica che grafica riferiti ad STC o ad OPC (vedere § 6.2.3 per il significato delle grandezze)
26. Usare il tasto freccia  per la selezione della tabella o del grafico corrispondente
27. Premere il tasto **SAVE** per salvare il risultato del test nella memoria dello strumento (vedere il § 7.2) o il tasto **ESC/MENU** per uscire dalla videata senza salvare e tornare alla videata principale di misura
28. Il modo di attivazione “**Auto**” richiede di scollegare e ricollegare i terminali di prova per avviare automaticamente una nuova misura

```
15/05/10   15:34:26
V o c   =   1 5 . 2   V
V m p p   =   1 4 . 7   V
I m p p   =   4 . 7   A
I s c   =   5 . 2   A
P m a x   =   2 0 0   W
F F   =   7 7 . 1   %
D P m a x   =   2 . 1   %
T a b e l l a   
G r a f i c o      –   ESITO: OK
Selezione   I   -   V
```

### 6.2.2.2. Rilievo curva I - V tramite unità SOLAR - 02 in registrazione sincrona

Questa modalità, che prevede la registrazione autonoma delle grandezze Irraggiamento e temperatura da parte dell’unità remota, consente il rilievo della caratteristica *I - V* anche con distanze considerevoli fra lo strumento e l’unità **SOLAR - 02** senza la necessità di alcun collegamento fra le due unità. Per contro, non avendo lo strumento la disponibilità immediata delle suddette grandezze, si dovrà attendere il trasferimento dati da unità remota a unità principale per poter disporre di tutti i risultati disponibili

**ATTENZIONE**
Non utilizzare lo strumento per misure di Curve *I - V* e test **IVCK** su moduli FV con efficienza >19%. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento

**ATTENZIONE**
*   La massima tensione tra gli ingressi P1, P2, C1 e C2 è **1000VDC** per gli strumenti (**I - V400w** e **SOLAR I - Vw**) o **1500VDC** per gli strumenti (**I - V500w** e **SOLAR I - Ve**). Non misurare tensioni che eccedano i limiti manuale
*   La corrente massima tollerabile dallo strumento è **15A**. Non effettuare prove su stringhe di moduli FV in parallelo
*   Non eseguire mai prove su moduli o stringhe FV connessi al convertitore DC/AC

1.  Accendere lo strumento premendo il tasto **ON/OFF**
2.  Premere il tasto **MENU** e controllare che l’unità remota sia selezionata (vedere § 5.1.4)
3.  Controllare che il valore di soglia di irraggiamento impostata sia coerente con le misure che si intende effettuare (vedere § 5.1.5). Si consiglia si eseguire le misure con soglia **≥ 700 W/m²** in accordo alla normativa IEC/EN60891
4.  Tornare al MENU principale e selezionare la voce “**Caratt. I - V**”
5.  Premere il tasto **ENTER**, selezionare con i tasti freccia (, ) la voce “**Misurazione** ”
6.  Usare il tasto freccia  per accedere al sottomenu interno, selezionare la voce “**Caratt. IV**” e confermare con **ENTER** per attivare la videata iniziale del rilievo della caratteristica IV

```
15/05/10   15:34:26
V d c   =   0 . 0   V
I r r   =   0   W / m 2
T c   =   -   -   -   ° C
Modulo: SUNPOWER 210
C a r a t t .   I V
I m p   I V   C h e c k
M i s
Selezione   I   -   V
```

7.  Accendere l’unità remota **SOLAR - 02** ed attendere che sul display dello strumento appaia il messaggio “**Connessione radio attiva**”
8.  Controllare lo stato delle batterie del **SOLAR - 02** (il simbolo “ ” NON deve essere visualizzato)
9.  Controllare che i valori impostati su **SOLAR - 02** di sensibilità e coefficiente di temperatura siano coerenti con il tipo di cella di riferimento utilizzata in funzione del tipo di modulo/stringa in esame (vedere manuale d’uso SOLAR - 02).

10. Sul display dello strumento appare la seguente videata:
    *   **Vdc** = tensione DC in uscita dal modulo/stringa
    *   **Irr** = irraggiamento misurato dalla cella di riferimento
    *   **Modulo** = tipo di modulo attualmente selezionato
    *   **Temp** = modo di misura della temperatura del modulo
    *   **Tc** = temperatura del modulo FV. Questo campo presenta una delle seguenti indicazioni in funzione della modalità di misura della temperatura selezionata:
        *   **AUTO**: mod. misura Temp. Automatica
        *   **Numero**: mod. misura Temp. MAN o AUX
        *   “ **- - -** “: mod. AUX con la sonda non collegata
    *   **Start** = modalità di attivazione della misura
    *   Il simbolo fisso indica un collegamento stabile con **SOLAR - 02**

```
15/05/10   15:34:26
V d c   =   0 . 0   V
I r r   =   -   -   -   W / m 2
T c   = A u t o   ° C
Modulo:   DEFAULT
Temp: Auto
Start: Manuale
Selezione   I   –   V
```

11. Premere il tasto **ENTER**, selezionare la voce “**Impostazioni**” e confermare ancora con **ENTER** per accedere alla videata seguente in cui è possibile eseguire le impostazioni sulla scelta del tipo di modulo e sul numero di moduli di cui è costituita la stringa

```
15/05/10   15:34:26
V d c   =   0 . 0   V
I r r   =   -   -   -   W / m 2
T c   =   -   -   -   ° C
A t t i v a   R e g .
I m p o s t a z i o n i
M i s u r a z i o n e   
Selezione   I   -   V
```

12. Usare i tasti freccia (, ) per selezionare il tipo di modulo tra quelli presenti nel database interno dello strumento (vedere § 5.3.1)
13. Usare i tasti freccia (, ), selezionare la voce “**Mod. x Str**” e usare i tasti freccia (, ) per inserire il numero di moduli. Il numero massimo impostabile è **50**
14. Usare i tasti freccia (, ), selezionare la voce “**Anni Servizio**” e usare i tasti freccia (, ) per selezionare il numero di anni di servizio dell’impianto/stringa/modulo FV dalla sua installazione (vedere § 6.2.3). Il valore massimo impostabile è **25.0** (0.5 = 6 mesi)

```
15/05/10   15:34:26
Tipo   :    SUNPOWER 210 
M o d .   x   S t r   :   1 5
A n n i   s e r v  T e m p  : 4 . 5
:   A u t o
S t a r t :   :   M a n u a l e
P m a x   =   2 1 0
V o c   =   4 7 . 7 0
V m p p   =   4 0 . 0 0
I s c   =   5 . 7 5
I m p p   =   5 . 2 5
I M P O S T
```

15. Usare i tasti freccia (, ), selezionare la voce “**Temp**” e usare i tasti freccia (, ) per scegliere il tipo di misura della temperatura del modulo tra le modalità:
    *   “**Auto**” → misura automatica eseguita in funzione del valore misurato della tensione a vuoto di moduli. (Modalità di funzionamento raccomandata)
    *   **Manuale** → inserimento temperatura nota del modulo nel campo “**Valore**”
    *   **Aux** → misura della temperatura con sonda ausiliaria
16. Usare i tasti freccia (, ), selezionare la voce “**Start**” e usare i tasti freccia (, ) per selezionare il modo di attivazione della misura scegliendo tra le seguenti opzioni:
    *   **Auto** → test attivato automaticamente dallo strumento in presenza di tensione stabile in ingresso per circa 1 s e con valore compreso nel campo di misura (vedere § 10.2)
    *   **Manuale** → test attivato dall’utente alla pressione del tasto **GO/STOP**
17. Premere **SAVE** per salvare le selezioni eseguite oppure **ESC/MENU** per uscire senza salvare

18. Montare lo stelo sul disco dell’accessorio M304 (inclinometro) in dotazione e tenerlo appoggiato sul piano del modulo. Verificare che l’ombra dello stelo proiettata sul disco cada entro il “cerchio concentrico limite” interno al disco stesso (vedere Fig. 10). In caso contrario l’angolo tra i raggi solari e la superficie del modulo è troppo elevato e pertanto le misure eseguite dallo strumento NON sono da ritenere attendibili. Ripetere le operazioni in altri momenti della giornata.
19. Fissare la staffa al modulo usando le viti in dotazione e montare la cella di riferimento su di essa possibilmente con terminali di uscita rivolti verso il basso. Ruotare la cella fino ad appoggiarla sull’aletta presente sulla staffa in modo da renderla esattamente parallela al piano del modulo e fissarla quindi tramite le apposite viti
20. Collegare l’uscita della cella di riferimento, corrispondente al tipo di modulo in prova, all’ingresso **PYRA/CELL** del **SOLAR - 02** usando il cavo in dotazione alla cella stessa.
21. Collegare, se utilizzato, il sensore di temperatura all’ingresso **TEMP** del **SOLAR - 02** ed al retro del modulo sotto una cella usando nastro adesivo
22. Collegare lo strumento al modulo/stringa in prova come mostrato nella seguente Fig. 11. In particolare collegare il polo Negativo in uscita dal modulo/stringa ai terminali P1, C1 e il polo Positivo in uscita dal modulo/stringa ai terminali P2, C2. In modalità di attivazione misura “**Auto**” è raccomandato l’uso dell’accessorio opzionale **KITKELVIN**

Fig. 10: Posizionamento inclinometro M304
Fig. 11: Collegamento dello strumento al modulo/stringa FV

23. Dopo il collegamento all’impianto, lo strumento mostra in tempo reale i valori di:
    *   **Vdc** = tensione DC in uscita dal modulo/stringa
    *   **Irr** = irraggiamento misurato dalla cella di riferimento in dotazione
    *   **Modulo** = tipo di modulo attualmente selezionato
    *   **Temp** = modo di misura della temperatura del modulo
    *   **Tc** = temperatura del modulo FV. Questo campo presenta una delle seguenti indicazioni in funzione della modalità di misura della temperatura selezionata:
        *   **AUTO**: mod. misura Temp. Automatica
        *   **Numero**: mod. misura Temp. MAN o AUX
        *   “ **- - -** “: mod. AUX con sonda non collegata
    *   **Start** = modalità di attivazione della misura
    *   il simbolo fisso (non intermittente) che indica la presenza di un collegamento stabile con l’unità remota **SOLAR - 02**

```
15/05/10   15:34:26
V d c   =   3 6 7   V
I r r   =   1 0 4 5   W / m 2
T c   =   4 5   ° C
Modulo: SUNPOWER 210
Temp: Auto
Start: Manuale
Selezione   I   –   V
```

24. Premere il tasto **ENTER**, selezionare la voce “**Attiva Reg.**” e confermare ancora con **ENTER**. Sul display dello strumento apparirà il messaggio “**Unità remota in registrazione...**”. A questo punto è possibile iniziare ad eseguire i rilievi di caratteristica *I - V* fermo restando che i risultati completi saranno disponibili SOLO DOPO avere arrestare la registrazione su **SOLAR - 02** e ricevuti da essa i dati

```
15/05/10   15:34:26
V d c   =   0 . 0   V
I r r   =   -   -   -   W / m 2
T c   =   -   -   -   ° C
A t t i v a   R e g .
I m p o s t a z i o n i
M i s u r a z i o n e   
Selezione   I   –   V
```

**ATTENZIONE**
Alla pressione del tasto **GO/STOP** lo strumento può fornire diversi messaggi di errore (vedere § 6.4) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test

25. Premere il tasto **GO/STOP** (in modo di attivazione Manuale) per attivare il test. In caso di assenza di condizioni di errore, lo strumento fornisce il messaggio “**Misura in corso…**” per alcuni secondi in funzione della potenza in esame

```
15/05/10   15:34:26
V d c   =   3 6 7   V
I r r   =   - - - -   W / m 2
Tc   =   Auto   °C
Modulo: SUNPOWER 210
Misura in corso…
Selezione   I   -   V
```

26. Al termine della prova, coerentemente con quanto descritto nei punti precedenti, lo strumento visualizza il messaggio “**Dati STC disponibili solo dopo Stop registrazione**”, e poi fornisce i valori delle grandezze alle condizioni OPC.

```
15/05/10   15:34:26
V o c   =   1 5 . 2   V
V m p p   =   1 4 . 7   V
I m p p   =   4 . 7   A
I s c   =   5 . 2   A
P m a x   =   2 0 0   W
F F   =   7 7 . 1   %
I r r   =   -   -   -   W / m   2
T c   =   A u t o
MISURE @ OPC
Selezione   I   -   V
```

27. Premere **ENTER** per la visualizzazione dei risultati di misura sia in forma numerica che grafica (vedere § 6.2.3 per il significato delle grandezze)
28. Usare il tasto freccia  per la selezione della tabella o del grafico corrispondente
29. Premere il tasto **SAVE** per salvare il risultato del test nella memoria dello strumento (vedere § 7.2) o il tasto **ESC/MENU** per uscire dalla videata senza salvare e tornare alla videata principale di misura
30. Il modo di attivazione “**Auto**” richiede di scollegare e ricollegare i terminali di prova per avviare automaticamente una nuova misura

```
15/05/10   15:34:26
V o c   =   1 5 . 2   V
V m p p   =   1 4 . 7   V
I m p p   =   4 . 7   A
I s c   =   5 . 2   A
P m a x   =   2 0 0   W
F F   =   7 7 . 1   %
I r r   =   - - -   W / m   2
T a b e l l a   
Grafico   
Selezione   I   -   V
```

31. Al termine delle rilievi *I - V*, premere il tasto **ENTER**, selezionare la voce “**Arresta Registrazione**” e confermare con **ENTER**. Sul display dello strumento apparirà il messaggio “**Attendere...**” e poi “**Risultati a STC disponibili in Memoria**”
32. A questo punto, per le misure che dispongono di valori di irraggiamento sopra soglia e stabili, saranno disponibili in memoria anche i risultati a STC.

```
15/05/10   15:34:26
V d c   =   0 . 0   V
I r r   =   -   -   -   W / m 2
T c   = A u t o ° C
A r r e s t a   R e g .
I m p o s t a z i o n i
M i s u r a z i o n e   
Selezione   I   -   V
```

33. Sullo strumento appare a display il messaggio “**Scarico dati**” e allo stesso tempo il messaggio “**Send**” appare a display dell’unità **SOLAR - 02** ad indicare il trasferimento dei valori di irraggiamento e (eventualmente) temperatura delle celle sull’unità principale
34. Al termine del trasferimento lo strumento assocerà automaticamente i valori medi di irraggiamento (rilevato con PI = 5s) ad ogni misura di caratteristica *I - V* eseguita e, corrispondentemente, calcolerà i risultati traslati alle condizioni STC e l’esito SI/NO di ogni misura. I risultati completi sono richiamabili a display secondo quanto descritto al § 7.3.2).
35. Per l’interpretazione dei risultati di misura vedere il § 6.2.3

### 6.2.3. Interpretazione dei risultati di misura

I parametri misurati dallo strumento hanno il seguente significato:

| Parametro | Descrizione                                                              |
| :-------- | :----------------------------------------------------------------------- |
| Pmax      | Potenza massima del modulo misurata dallo strumento                      |
| DPmax     | Scostamento % fra la Potenza max misurata (@ STC) e la potenza nominale |
| FF        | Fill Factor %                                                            |
| Voc       | Tensione a vuoto                                                         |
| Vmpp      | Tensione nel punto di massima potenza                                    |
| Isc       | Corrente di cortocircuito                                                |
| Impp      | Corrente nel punto di massima potenza                                    |

Tabella 2: Elenco parametri misurati dallo strumento

In cui:
`DPmax = (Pmax - Pnom) / Pnom x 100 %`
→ parametro di controllo che definisce l’esito del test

`Pnom = potenza nominale del modulo`

`P P Nom Nom Age No m :        −  = 100 % 1 DegrAnnuo AnniServ`
*(This line contains visually malformed characters from the original text, making the formula for "P P Nom Nom Age No m" unclear. Please refer to the original document for accurate interpretation.)*

`FF = 100 x [ (Vmpp x Impp ) / (Voc x Isc)] = Fill Factor` → rappresenta una sorta di “rendimento” del modulo/stringa mettendo a confronto la potenza massima misurata e la potenza a vuoto

Lo strumento fornisce i seguenti esiti di misura:

| Tipo Esito | Condizione                                                         | Note                                                          |
| :--------- | :----------------------------------------------------------------- | :------------------------------------------------------------ |
| OK         | `- Tol (-) + εStrum ≤ εMis ≤ Tol (+) - εStrum` (1)                 | Esito del test positivo anche considerando l’errore strumentale nella misura |
| OK*        | La precedente relazione (1) non è verificata ma comunque vale: `- Tol (-) ≤ εMis ≤ Tol (+)` (2) | Esito del test positivo a meno dell’errore strumentale nella misura |
| NO OK*     | Non sono verificate le (1) e (2) ma comunque vale: `- Tol (-) - εStrum ≤ εMis ≤ Tol (+) + εStrum` (3) | Esito del test negativo a meno dell’errore strumentale nella misura |
| NO OK      | Nessuna delle relazioni (1), (2) e (3) è verificata (4)            | Esito del test negativo anche considerando l’errore strumentale nella misura |

dove:
*   **Tol (-)** = **Tol (-)** (%)\**Pnom* → Tolleranza Negativa, in valore assoluto, dichiarata dal costruttore
*   **Tol (+)** = **Tol (+)** (%)\**Pnom* → Tolleranza Positiva, in valore assoluto, dichiarata dal costruttore
*   ***εMis*** = *Pmax* – *Pnom* → *D Pmax* che definisce lo scostamento tra i valori misurati e quelli dichiarati
*   ***εStrum*** → Errore assoluto della catena di misura (strumento + trasduttori nel punto di misura) considerando l’errore % e i dgt dichiarati

## 6.3. TEST RAPIDO MODULI E STRINGHE FV (IVCK)

### 6.3.1. Generalità

Questa funzione esegue un Test rapido di un pannello/stringa misurando solamente la **Tensione a vuoto** e la **corrente di corto circuito** in accordo a quanto previsto dalla norma IEC/EN62446. Potranno poi essere misurati (utilizzando le rispettive sonde) anche i valori di Irraggiamento e Temperatura moduli.

**ATTENZIONE**
Non utilizzare lo strumento per misure di Curve *I - V* e test **IVCK** su moduli FV con efficienza >19%. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento

La misura di *Irraggiamento* potrà essere fatta solamente tramite una delle seguenti modalità:
*   Sensore *Irragg.* collegato direttamente a **I - V400w**, **I - V500w**, **SOLAR I - Vw** o **SOLAR I - Ve**
*   Sensore *Irragg.* collegato a **SOLAR - 02** in collegamento RF con **I - V400w**, **I - V500w**, **SOLAR I - Vw** o **SOLAR I - Ve**

Le misure di *Irraggiamento* sono effettuate sempre in tempo reale, non è quindi possibile avviare una registrazione “remota” dei valori di irraggiamento tramite **SOLAR - 02**

Se la soglia di Irraggiamento minimo IV (vedere § 5.1.5) *I - V* è posta:
*   **= 0** → lo strumento non controlla la presenza della Cella, le variazioni di *Irragg*, il numero dei moduli e non visualizza messaggi di errore se non è possibile calcolare i valori trasposti a STC di Voc e Isc. Questa modalità è indicata per eseguire una sessione di Test in maniera estremamente rapida su un numero elevato di stringhe.
*   **> 0** (consigliato > 700) → lo strumento esegue tutti i controlli previsti per la prova *I - V*, gestisce tutte le condizioni ed i messaggi di errore della prova *I - V* (num. Mod. errato, Temp. Fuori range, presenza cella, Irr. Min, ecc..) e calcola i valori a STC di Voc e Isc. Questa modalità è raccomandata qualora si intenda eseguire delle prove più approfondite sui moduli/stringhe in esame.

La pagina dei risultati conterrà in generale:
*   La descrizione del modulo in uso
*   I valori di Irraggiamento e temperatura (se disponibili)
*   I valori medi di Voc e Isc calcolati come media dei corrispondenti valori a OPC sulle ultime 10 prove memorizzate e salvate. Se il numero delle prove è < 10 la media viene calcolata sul numero delle prove disponibili. La prima prova visualizzerà trattini nel campo “valori medi” visto che non ci sono prove precedenti su cui calcolare la media.
*   I valori di Voc e Isc misurati a OPC e gli eventuali esiti parziali (presenti solo se i valori STC non sono disponibili) ottenuti per confronto con i valori medi.
*   I valori di Voc e Isc calcolati a STC (se disponibili) e gli eventuali esiti parziali ottenuti per confronto dei valori calcolati a STC con quelli nominali (inseriti nel DB moduli).
*   L’esito complessivo della prova (OK(NO). L’esito complessivo verrà calcolato sulla base degli esiti parziali ottenuti:
    *   Sulla base degli esiti parziali a STC (se questi sono disponibili)
    *   Sulla base degli esiti parziali a OPC (se i valori STC non sono disponibili)

Lo strumento non visualizzerà nessun esito complessivo se non è disponibile nessun esito parziale.
Nel caso di esito negativo è consigliabile eseguire una rilievo della caratteristica *I - V* (vedere § 6.2) al fine di approfondire l’analisi sul modulo/stringa esaminato.

<!-- Chunk: Pages 49-64 -->
## 6.3.2. Impostazioni preliminari

1.  Accendere lo strumento premendo il tasto `ON/OFF`.
2.  Premere il tasto `ESC/MENU` per visualizzare il menu principale.
3.  Selezionare la voce “`I - V`” e premere `ENTER` per accedere alla sezione di misura delle prestazioni dei moduli FV.
4.  Nel caso la modalità corrente non sia già IVCK, premere il tasto `ENTER`, selezionare con i tasti freccia (``, ``) la voce “`Misurazione `”. Usare il tasto freccia `` per accedere al sottomenu interno, selezionare la voce “`IV Check`” e confermare con `ENTER` per attivare la videata iniziale del Test rapido `IVCK`.
    ```
    15/05/10   15:34:26
    M o d u l o :   S U N P W R 2 1 0
    I r r   9 8 0   W / m 2
    T c   ( A U T O )   4 9   ° C
    V o c M e d @ O P C   6 4 7   V
    I s c M e d @ O P C   5 . 4 3   A
    V o c @ O P C   6 4 6   V
    I s c @ O P C   - - -   A
    R e s e t   M e d i a   V
    I m p o s t a z i o n e   A
    M i s u r a z i o n e   
    Selezione   I V C K
    ```
5.  Premere il tasto `ENTER`, selezionare la voce “`Impostazioni`” e confermare ancora con `ENTER` per accedere alla videata seguente in cui è possibile eseguire le impostazioni inerenti il tipo di modulo e il numero di moduli di cui è costituita la stringa oggetto del test.
    ```
    15/05/10   15:34:26
    Tipo   :    SUNPOWER 210 
    M o d .   x   S t r   :   1 5
    T e m p   :   M a n u a l e
    V a l o r e   :   5 1 ° C
    T o l   V o c   :   3 %   ( + 4 % )
    T o l   I s c   :   3 %   ( + 4 % )
    S t a r t   :   M a n u a l e
    V o c   =   6 4 . 7   %
    I s c   =   6 . 2 0   %
    I M P O S T
    ```
6.  Usare i tasti freccia (``, ``) per selezionare il tipo di modulo tra quelli presenti nel database interno dello strumento (vedere § 5.3.1).
7.  Usare i tasti freccia (``, ``), selezionare la voce “`Mod. x Str`” e usare i tasti freccia (``, ``) per inserire il numero di moduli della stringa in prova. Il numero massimo di moduli impostabile è `50`.
8.  Usare i tasti freccia (``, ``), selezionare la voce “`Temp`” e usare i tasti freccia (``, ``) per scegliere il tipo di misura della temperatura del modulo tra le modalità:
    *   “`Auto`” → misura automatica eseguita in funzione del valore misurato della tensione a vuoto dei moduli (metodo raccomandato)
    *   `Manuale` → inserimento da parte dell’operatore del valore noto della temperatura del modulo nel campo “`Valore`” corrispondente
    *   `Aux` → misura della temperatura con sonda ausiliaria
9.  Usare i tasti freccia (``, ``), selezionare la voce “`Tol Voc`” e “`Tol Isc`” e usare i tasti freccia (``, ``) per impostare i valori delle Tolleranze per la Tensione a Vuoto (Voc) e corrente di cortocircuito (Isc) fornite dal costruttore del modulo (valori ammessi: +0% .. +25%). Notare che a lato dei suddetti valori è anche indicata fra parentesi l’incertezza dello strumento che verrà sommata al valore immesso per fornire l’esito (OK/NO).
10. Usare i tasti freccia (``, ``), selezionare la voce “`Start`” e usare i tasti freccia (``, ``) per selezionare il modo di attivazione della misura scegliendo tra le seguenti opzioni:
    *   `Auto` → test attivato automaticamente dallo strumento in presenza di tensione stabile in ingresso per `circa 1s` e con valore compreso nel campo di misura (vedere § 10.2)
    *   `Manuale` → test attivato dall’utente alla pressione del tasto `GO/STOP`
11. Premere `SAVE` per salvare le selezioni eseguite oppure `ESC/MENU` per uscire senza salvare.

## 6.3.3. Test Rapido IVCK senza misura di Irraggiamento

> **ATTENZIONE**
> Non utilizzare lo strumento per misure di Curve I - V e test IVCK su moduli FV con efficienza >19%. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento.

> **ATTENZIONE**
> *   La massima tensione tra gli ingressi P1, P2, C1 e C2 è `1000VDC` (per gli strumenti I - V400w e SOLAR I - Vw) o `1500VDC` (per gli strumenti I - V500w e SOLAR I - Ve). Non misurare tensioni eccedenti i limiti espressi nel § 10.2.
> *   La corrente massima tollerabile dallo strumento è `15A`. Non effettuare prove su stringhe di moduli FV in parallelo.
> *   Non eseguire mai prove su moduli o stringhe FV connessi al convertitore DC/AC.

1.  Accendere lo strumento premendo il tasto `ON/OFF`.
2.  Controllare che l’unità remota `SOLAR - 02` non sia selezionata (vedere § 5.1.4 – impostazione NO).
3.  Controllare che il valore di Irraggiamento minimo impostato nella sezione “`Irraggiamento`” (vedere § 5.1.5) sia `pari a 0`.
4.  Tornare al MENU principale e selezionare la voce “`I - V`”.
5.  Selezionare la voce “`I - V`” e premere `ENTER` per accedere alla sezione di misura delle prestazioni dei moduli FV. In generale all’atto della selezione della voce `I - V` nel menu generale lo strumento presenta automaticamente l’ultima modalità utilizzata (I - V o IVCK).
6.  Nel caso la modalità corrente non sia già IVCK, premere il tasto `ENTER`, selezionare con i tasti freccia (``, ``) la voce “`Misurazione `”. Usare il tasto freccia `` per accedere al sottomenu interno, selezionare la voce “`IV Check`” e confermare con `ENTER` per attivare la videata iniziale del Test rapido `IVCK`.
    ```
    15/05/10   15:34:26
    V d c   =   0 . 0   V
    I r r   =   0   W / m 2
    T c   =   -   -   -   ° C
    Modulo: SUNPOWER 210
    C a r a t t .   I V
    I m p   I V   C h e c k
    M i s
    Selezione   I   -   V
    ```
7.  Controllare le impostazioni preliminari secondo quanto descritto al § 6.3.2.
8.  Collegare lo strumento al modulo/stringa in prova come mostrato nella seguente figura. In particolare collegare il polo Negativo in uscita dal modulo/stringa ai terminali P1, C1 e il polo Positivo in uscita dal modulo/stringa ai terminali P2, C2. In modalità di attivazione misura “`Auto`” è raccomandato l’uso dell’accessorio opzionale KITKELVIN.

    **LEGENDA**:
    *   P1: Cavo Nero
    *   P2: Cavo Blu
    *   C1: Cavo Verde
    *   C2: Cavo Rosso
    *   1: Modulo o stringa FV

    Fig. 13: Coll. strumento al modulo/stringa FV per prove IVCK senza misura mis. Irragg.

9.  Nella videata iniziale della modalità IVCK vengono visualizzati i valori di:
    *   Modulo in uso
    *   I valori medi di Voc e Isc alle condizioni OPC.
    *   Il valore della Voc misurata alle condizioni OPC

    ```
    15/05/10   15:34:26
    M o d u l o :   S U N P W R 2 1 0
    I r r .   - - -   W / m 2
    T c   ( A U T O )   -   - -   ° C
    V o c M e d @   6 4 7   V
    I s c M e d @ O P   C   5 . 4 3   A
    V o c @ O P C   6 4 6   V
    I s c @ O P C   - - -   A
    V o c @ S T C   - - -   V
    I s c @ S T C   - - -   A
    Selezione   I V C K
    ```

    > **ATTENZIONE**
    > Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere § 6.3) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test.

10. Premere il tasto `GO/STOP` (in modo di attivazione `Manuale`) per attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza la videata dei risultati del tipo indicato a lato. In essa sono visualizzati:
    *   Il modulo in uso
    *   I valori medi di Voc e Isc alle condizioni OPC
    *   I valori di Voc e Isc misurati a OPC ed i relativi esiti parziali ottenuti per confronto con i valori medi.
    ```
    15/05/10   15:34:26
    M o d u l o :   S U N P W R 2 1 0
    I r r   - - -   W / m 2
    T c   ( A U T O )   - -   ° C
    V o c M e d @ O C   6 4 7   V
    I s c M e d @ O P C   5 . 4 3   A
    V o c @ O P C   6 4 7   V   O K
    I s c @ O P C   5 . 3 5   A   O K
    V o c @ S T C   - - -   V
    I s c @ S T C   - - -   A
    ESITO: OK
    Selezione   I V C K (   ) (   )
    ```
    In generale:
    *   `Esito Voc OK = se (Voc @ OPC >= VocMed @ OPC - (VocMed @ OPC * (Tol Voc + Incertezza Strumento) / 100))`
    *   `Esito Isc OK = se (Isc @ OPC <= IscMed @ OPC + (IscMed @ OPC * (Tol Isc + Incertezza Strumento) / 100))`
    *   Il valore complessivo degli esiti:
        *   OK: se tutti gli esiti OPC sono OK,
        *   NO se uno degli esiti OPC è NO
11. Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il § 7.2) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura.
12. Il modo di attivazione “`Auto`” richiede di scollegare e ricollegare i terminali di prova per avviare automaticamente una nuova misura.

**NOTA sui VALORI MEDI visualizzati**
Nella pagina dei risultati compaiono i valori medi di Voc e Isc. Tali valori contengono i valori medi di Voc e Isc alle condizioni OPC calcolati come media sulle ultime 10 prove precedentemente memorizzate. Se l’utente ha eseguito e memorizzato un numero di prove <10 oppure ha resettato i valori medi (vedi § 6.3.5) la media visualizzata nel corso della prova N+1 saranno quelli calcolata su gli N valori disponibili.

## 6.3.4. Test Rapido IVCK con misura di Irraggiamento

> **ATTENZIONE**
> Non utilizzare lo strumento per misure di Curve I - V e test IVCK su moduli FV con efficienza >19%. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento.

> **ATTENZIONE**
> *   La massima tensione tra gli ingressi P1, P2, C1 e C2 è `1000VDC` per gli strumenti (I - V400w e SOLAR I - Vw) o `1500VDC` per gli strumenti (I - V500w e SOLAR I - Ve). Non misurare tensioni eccedenti i limiti espressi nel § 10.2.
> *   La corrente massima tollerabile dallo strumento è `15A`. Non effettuare prove su stringhe di moduli FV in parallelo.
> *   Non eseguire mai prove su moduli o stringhe FV connessi al convertitore DC/AC.

1.  Accendere lo strumento premendo il tasto `ON/OFF`.
2.  La misura di Irraggiamento potrà essere fatta tramite le due seguenti modalità:
    *   Misura tramite Cella di riferimento collegata direttamente a `I - V400w, I - V500w, SOLAR I - Vw` o `SOLAR I - Ve`
    *   Misura tramite Cella di riferimento collegata a `SOLAR - 02` in coll. RF con `I - V400w, I - V500w, SOLAR I - Vw` o `SOLAR I - Ve`

    Controllare che l’impostazione inerente l’unità remota `SOLAR - 02` sia coerente con il tipo di misura che si intende realizzare (vedere § 5.1.4).
3.  Controllare il valore di Irraggiamento minimo impostato nella sezione “`Irraggiamento`” (vedere § 5.1.5).
4.  Tornare al MENU principale e selezionare la voce “`I - V`”.
5.  Selezionare la voce “`I - V`” e premere `ENTER` per accedere alla sezione di misura delle prestazioni dei moduli FV. In generale all’atto della selezione della voce `I - V` nel menu generale lo strumento presenta automaticamente l’ultima modalità utilizzata (IV o IVCK).
6.  Nel caso la modalità corrente non sia già IVCK, premere il tasto `ENTER`, selezionare con i tasti freccia (``, ``) la voce “`Misurazione `”. Usare il tasto freccia `` per accedere al sottomenu interno, selezionare la voce “`IV Check`” e confermare con `ENTER` per attivare la videata iniziale del Test rapido `IVCK`.
    ```
    15/05/10   15:34:26
    V d c   =   0 . 0   V
    I r r   =   0   W / m 2
    T c   =   -   -   -   ° C
    Modulo: SUNPOWER 210
    C a r a t t .   I V
    I m p   I V   C h e c k
    M i s
    Selezione   I   -   V
    ```
7.  Controllare le impostazioni preliminari secondo quanto descritto al § 6.3.2.
8.  Collegare lo strumento al modulo/stringa in prova come mostrato nella seguente figura. In particolare, collegare il polo Negativo in uscita dal modulo/stringa ai terminali P1, C1 e il polo Positivo in uscita dal modulo/stringa ai terminali P2, C2. In modalità di attivazione misura “`Auto`” è raccomandato l’uso dell’accessorio opzionale KITKELVIN.

    **Legenda:**
    *   P1: Cavo Nero
    *   P2: Cavo Blu
    *   C1: Cavo Verde
    *   C2: Cavo Rosso
    *   1: Modulo o stringa FV
    *   2: Cella di riferimento
    *   3: Sens. Temp (se richiesto)
    *   4 U.remota SOLAR - 02

    Fig. 14: Connessioni dello strumento per prove IVCK con mis. Diretta di Irragg /Temp
    Fig. 15: Connessioni dello strumento per prove IVCK con mis. di Irragg /Temp tramite SOLAR - 02

9.  Collegare le sonde di Irraggiamento e la sonda di Temperatura (se necessaria) in accordo alle figure precedenti ed alle impostazioni effettuate (vedi § 6.3.2).
10. Nella videata iniziale della modalità IVCK vengono visualizzati i valori di:
    *   Modulo in uso
    *   Irraggiamento (proveniente da misura diretta o SOLAR_02 in coll. RF)
    *   Il valore della Temperatura (se mod. MAN o AUX) e la relativa mod. di misura. Se mod. AUTO → ”`- - -`“
    *   I valori medi di Voc e Isc alle condizioni OPC

    Sono inoltre visualizzati i valori acquisiti in tempo reale di:
    *   Tensione a vuoto
    *   L’eventuale simbolo del coll. RF con l’unità `SOLAR - 02`

    ```
    15/05/10 15:34:26
    M o d u l o :   S U N P W R 2 1 0
    I r r .   9 8 0   W / m 2
    T c   ( A U T O )   - -   ° C
    V o c M e d @ O P C   6 4 7   V
    I s c M e d @ O P C   5 . 4 3   A
    V o c @ O P C   6 4 6   V
    I s c @ O P C   - - -   A
    V o c @ S T C   - - -   V
    I s c @ S T C   - - -   A
    Selezione   I V C K
    ```

    > **ATTENZIONE**
    > Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere § 6.3) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test.

11. Premere il tasto `GO/STOP` (in modo di attivazione `Manuale`) per attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza la videata dei risultati con indicati:
    *   Il modulo in uso
    *   Il valore dell’Irraggiamento
    *   Il valore della Temperatura Celle
    *   I valori medi di Voc e Isc alle condizioni OPC
    *   I valori di Voc e Isc misurati a OPC
    *   I valori di Voc e Isc calcolati a STC ed i relativi esiti parziali ottenuti per confronto con i valori nominali

    ```
    15/05/10   15:34:26
    M o d u l o :   S U N P W R 2 1 0
    I r r   9 3 2   W / m 2
    T c   ( A U T O )   5 7   ° C
    V o c M e d @ O P C   6 4 7   V
    I s c M e d @ O P C   5 . 4 3   A
    V o c @ O P C   6 4 7   V
    I s c @ O P C   5 . 3 5   A
    V o c @ S T C   7 8 7   V   O K
    I s c @ S T C   5 . 7 2   A   O K
    ESITO: OK
    Selezione   I V C K (   ) (   )
    ```

    In generale:
    *   `Esito Voc OK = se (Voc @ STC >= VocNom @ STC - (VocNom @ STC * (Tol Voc + Incertezza Strumento) / 100))`
    *   `Esito Isc OK = se (Isc @ STC <= IscNom @ STC + (IscNom @ STC * (Tol Isc + Incertezza Strumento) / 100))`
    I valori di Voc e Isc nominali sono i valori presenti nel DB moduli interno allo strumento (vedi § 5.3).

    *   Il valore complessivo degli esiti:
        *   OK: se tutti gli esiti STC sono OK,
        *   NO se uno degli esiti STC è NO
12. Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il § 7.2) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura.
13. Il modo di attivazione “`Auto`” richiede di scollegare e ricollegare i terminali di prova per avviare automaticamente una nuova misura.

## 6.3.5. Reset Media

Se non sono misurati i valori di Irraggiamento, lo strumento fornisce un esito confrontando i valori misurati con i valori medi calcolati sulla base delle misure precedentemente salvate. Pertanto in questo caso i valori medi calcolati dallo strumento assumono particolare importanza.
Nel caso si inizi una nuova campagna di misura con variazioni significative di Irraggiamento o temperatura è consigliabile azzerare i valori medi di riferimento per poi farlo ricalcolare sulle base di nuove misure.
Per resettare i valori medi attenersi ai seguenti passi:

1.  All’interno della modalità IVCK, premere il tasto `ENTER`, selezionare la voce “`Reset Media`” e confermare ancora con `ENTER` per azzerare i valori medi fino a quel momento calcolati.
    ```
    15/05/10   15:34:26
    M o d u l o :   S U N P W R 2 1 0
    I r r   9 8 0   W / m 2
    T c   ( A U T O )   4 9   ° C
    V o c M e d @ O P C   - - -   V
    I s c M e d @ O P C   - - -   A
    V o c @ O P C   6 4 6   V
    I s c @ O P C   - - -   A
    R e s e t   M e d i a   V
    I m p o s t a z i o n i   A
    M i s u r a z i o n e   
    Selezione   I V C K
    ```
    I valori medi vengono automaticamente resettati anche modificando e poi salvando uno dei seguenti parametri:
    *   Tipo di modulo FV
    *   Numero di moduli x stringa

I valori medi non vengono invece resettati se l’operatore cambia modalità di funzionamento (esempio passa al rilievo completo della curva I - V per approfondire l’analisi di una stringa) per poi tornare a questa modalità.

## 6.4. ELENCO DEI MESSAGGI A DISPLAY

| MESSAGGIO                       | DESCRIZIONE                                                                                                                                                                                                                                    |
| :------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tensione di ingresso assente    | Controllare la tensione tra i terminali di ingresso C1 e C2                                                                                                                                                                                    |
| Vin > 1000                      | Tensione DC in uscita dal modulo/stringa > 1000V (I - V400w, SOLAR I - Vw)                                                                                                                                                                      |
| Irraggiamento troppo basso      | Valore di irraggiamento inferiore al limite minimo impostato                                                                                                                                                                                   |
| Errore NTC                      | Efficienza NTC interna compromessa. Contattare assistenza                                                                                                                                                                                      |
| Attendere raffreddamento…       | Strumento surriscaldato. Attendere prima di riprendere i test                                                                                                                                                                                  |
| Memoria piena                   | Raggiunto il limite di salvataggio. Scaricare i dati a PC                                                                                                                                                                                      |
| Tempo impulso troppo lungo      | Condizioni anomale. Ripetere il test con più moduli in serie                                                                                                                                                                                   |
| Corrente troppo bassa           | Valore di corrente misurata inferiore al minimo rilevabile                                                                                                                                                                                     |
| Errata inserzione Vdc           | Controllare la tensione tra i terminali di ingresso C1 e C2                                                                                                                                                                                    |
| Tensione negativa               | Controllare le polarità dei terminali di ingresso dello strumento                                                                                                                                                                              |
| Database pieno                  | Il numero dei moduli inseriti nel DB interno è > 30                                                                                                                                                                                            |
| Dati @ STC non disponibili      | Lo strumento non ha calcolato i dati alle condizioni STC                                                                                                                                                                                       |
| Irraggiamento troppo alto       | Valore di irraggiamento maggiore al massimo misurabile                                                                                                                                                                                         |
| Dati non disponibili            | Errore generico. Ripetere il test                                                                                                                                                                                                              |
| Corrente Isc troppo alta        | Corrente in uscita maggiore del massimo misurabile                                                                                                                                                                                             |
| Data errata                     | Inserire una data/ora di sistema coerente                                                                                                                                                                                                      |
| Errore 1/2/3/4 /5 : contattare assistenza | Contattare assistenza                                                                                                                                                                                                                  |
| Errore EEPROM : cont. assistenza | Contattare assistenza                                                                                                                                                                                                                          |
| Errore FLASH : cont. assistenza | Contattare assistenza                                                                                                                                                                                                                          |
| Errore RTC : cont. assistenza   | Contattare assistenza                                                                                                                                                                                                                          |
| Batteria scarica                | Livello batterie basso. Inserire nuove batterie nello strumento                                                                                                                                                                               |
| Errore: Vmpp >= Voc             | Controllare le impostazioni del modulo all’interno del DB                                                                                                                                                                                      |
| Errore: Impp >= Isc             | Controllare le impostazioni del modulo all’interno del DB                                                                                                                                                                                      |
| Errore: Vmpp * Impp >= Pmax     | Controllare le impostazioni del modulo all’interno del DB                                                                                                                                                                                      |
| Errore: alpha , beta, Gamma, Toll troppo alto | Controllare le impostazioni del modulo all’interno del DB                                                                                                                                                                      |
| Modulo già presente             | Nome del modulo inserito già presente nel DB                                                                                                                                                                                                   |
| Delta - Irragg. Elevato. Ripetere | Condizioni non stabili di irraggiamento. Ripetere il test                                                                                                                                                                                      |
| Tensione non stabile            | Condizioni anomale. Ripetere il test con più moduli in serie                                                                                                                                                                                   |
| Corrente non stabile            | La differenza fra 2 valori istantanei consecutivi di corrente è> 0.13A                                                                                                                                                                         |
| Firmware non corretto           | Problemi con FW interno. Contattare assistenza                                                                                                                                                                                                 |
| Temp. Cella rif. oltre i limiti | Temperatura misurata dalla cella di riferimento troppo alta                                                                                                                                                                                    |
| Temp. Modulo oltre i limiti     | Temperatura sul modulo oltre il massimo misurabile                                                                                                                                                                                             |
| Tensione Voc fuori range . Continuare? (ENTER/ESC) | Voc misurata non coerente con il valore del numero moduli impostato (controllare anche i parametri Voc e Beta nel data sheet del modulo). Premere GO per continuare il test                                                         |
| Vshort > Lim                    | La tensione corrispondente alla misura Isc è > 30V. Strumento proababilmente danneggiato. Contattare assistenza                                                                                                                               |
| Temp.cella non rilevata. (ENTER/ESC) | Misura non eseguita sulla cella del modulo                                                                                                                                                                                             |
| Unità remota non rilevata       | Lo strumento non rileva nessuna unità SOLAR - 02                                                                                                                                                                                               |
| Memoria esaurita                | Memoria dello strumento piena alla pressione del tasto GO                                                                                                                                                                                      |
| Tensione AC e DC scambiate      | Terminali C1, C2 e P1, P2 scambiati in fase di collaudo FV                                                                                                                                                                                     |
| Errore memorizzazione           | Problemi nell’accesso all’area di memoria                                                                                                                                                                                                      |
| Errore RADIO: contattare assistenza | Contattare assistenza                                                                                                                                                                                                                  |
| Errore Trasmissione RADIO       | Contattare assistenza                                                                                                                                                                                                                          |
| Errore scarico dati             | Contattare assistenza                                                                                                                                                                                                                          |
| Registrazione scaricata         | Registrazione correttamente scaricata sullo strumento                                                                                                                                                                                          |
| Connessione radio attiva        | Stabilita connessione RF con unità remota SOLAR - 02                                                                                                                                                                                           |
| Attendere analisi dati          | Scarico dati da SOLAR - 02 e attesa esito collaudo FV                                                                                                                                                                                          |
| Impossibile effettuare l'analisi | Problemi sui dati scaricati dal SOLAR - 02. Verificare impostazioni                                                                                                                                                                          |
| I < Lim                         | Corrente in uscita inferiore al minimo misurabile                                                                                                                                                                                              |
| Attenzione: corto circuito interno | Contattare assistenza                                                                                                                                                                                                                  |
| Unità remota non rilevata Enter/Esc | Unità SOLAR - 02 non connessa RF allo strumento                                                                                                                                                                                          |
| Unità remota in reg.            | Unità SOLAR - 02 in registrazione parametri Irr/Temp                                                                                                                                                                                           |
| Dati STC disp. solo dopo stop Reg. | Terminare la registrazione per ottenere dati a STC                                                                                                                                                                                         |
| Dati STC disp. in memoria       | Dati condizione STC memorizzati                                                                                                                                                                                                                |
| Verificare colleg. P1           | Controllare il corretto inserimento del cavo di prova nell’ingresso P1                                                                                                                                                                         |
| Errore scarico dati SOLAR - 02  | SOLAR I - Vw impostato per l’uso di MPP300. Errore download da SOLAR - 02                                                                                                                                                                      |
| SOLAR - 02 non rilevato. Ferma Reg? | SOLAR I - Vw impostato per l’uso di MPP300. SOLAR - 02 non rilevato all’arresto Reg.                                                                                                                                                     |
| MPP300 non rilevato             | SOLAR I - Vw impostato per l’uso in abbinamento a MPP300. MPP300 non rilevato                                                                                                                                                                  |
| SOLAR - 02 non rilevato         | SOLAR I - Vw impostato per l’uso in abbinamento a MPP300. SOLAR - 02 non rilevato                                                                                                                                                              |
| MPP300:potenza Ac negativa      | MPP300 ha rilevato delle potenze AC negative                                                                                                                                                                                                   |
| MPP300:Tensione Ac e Dc scambiate | MPP300 ha rilevato Tensione AC e DC scambiate fra loro                                                                                                                                                                                       |
| No alim MPP Continuare? Enter/Esc | MPP300 non ha rilevato la presenza dell’alim. esterno.                                                                                                                                                                                       |
| C1 C2 non connessi              | Controllare i collegamenti dello strumento al pannello / stringa in esame.                                                                                                                                                                     |
| C1 C2 non connessi o fusibile int. | Controllare i collegamenti dello strumento e riprovare ad eseguire nuovamente la prova. Se il problema persiste contattare l’assistenza tecnica                                                                                              |
| Fusibile Interrotto             | Controllare i collegamenti dello strumento e riprovare ad eseguire nuovamente la prova. Se il problema persiste contattare l’assistenza tecnica                                                                                              |
| Versione Lingua non corretta    | Aggiornare il file delle lingue dello strumento.                                                                                                                                                                                               |
| C1/C2: tensione neg.            | Controllare la polarità dei collegamenti effettuati.                                                                                                                                                                                           |

# 7. MEMORIZZAZIONE RISULTATI

Lo strumento consente la memorizzazione di `99` risultati di prove di collaudo (solo `SOLAR I - Vw`, `SOLAR I - Ve`) e `249` test di misura di caratteristiche I - V. È inoltre possibile eseguire, nelle operazioni di collaudo, il salvataggio di valori istantanei presenti a display. I dati possono essere richiamati a display e cancellati in ogni momento ed è possibile associare (per la misura della caratteristica I - V) degli identificatori numerici di riferimento mnemonici relativi all’impianto, alla stringa e al modulo FV (max 255).

## 7.1. SALVATAGGIO DELLE MISURE DI COLLAUDI FV (SOLAR I - VW, SOLAR I - VE)

1.  Premere il tasto `SAVE` con esito del collaudo presente a display o per il salvataggio dei valori istantantanei a display. Lo strumento presenta la videata mostrata a lato in cui è presente la tastiera virtuale.
    ```
    15/05/10   15:34:26
    P R p   0 . 8 5
    I r r   8 2 7   W / m 2
    P n o m   3 . 5 0 0   k W
    T c   4 5   ° C
    T e   3 0   ° C
    T A S T I E R A
    I M P I A N T O   R O S S I
    A   B   C   D   E   F   G   H   I   J   K   L   M   N   O   P
    Q   R   S   T   U   V   W   X   Y   Z   -   +   0   1   2   3
    4   5   6   7   8   9   S P A C E   D E L
    SAVE per salvare
    ```
2.  Usare i tasti freccia (``, ``) e (``, ``) per inserire una breve descrizione (max 12 caratteri) relativa al collaudo eseguito.
3.  Premere ancora il tasto `SAVE` per confermare il salvataggio dei dati o `ESC/MENU` per uscire senza salvare.

## 7.2. SALVATAGGIO DELLE MISURE DI CARATTERISTICA I - V

1.  Premere il tasto `SAVE` con risultato di misura presente a display. Lo strumento presenta la videata mostrata a lato in cui sono mostrate le seguenti voci:
    *   La prima locazione di memoria disponibile (“Misura”)
    *   Il marcatore numerico “Impianto”
    *   Il marcatore numerico “Stringa”
    *   Il marcatore numerico “Modulo”
    *   Il campo “Commento” in cui l’operatore può inserire una breve descrizione (max 12 caratteri) per l’impianto

    ```
    15/05/10   15:34:26
    M i s u r a   :   0 0 7
    I m p i a n t o   :      0 1 0   
    S t r i n g a   :   0 0 9
    M o d u l o   :   0 0 4
    C o m m e n t o   :
    T A S T I E R A
    I M P I A N T O   R O S S I
    A   B   C   D   E   F   G   H   I   J   K   L   M   N   O   P
    Q   R   S   T   U   V   W   X   Y   Z   -   +   0   1   2   3
    4   5   6   7   8   9   S P A C E   D E L
    SAVE per salvare
    C o m m e n t o   M E M
    ```
2.  Usare i tasti freccia (``, ``) per la selezione delle varie voci e usare i tasti freccia (``, ``) per l’impostazione dei valori numerici e per l’uso della tastiera virtuale. La modifica del campo “`Commento`” è possibile solo variando il numero dell’identificatore “`Impianto`” inserendone uno non ancora utilizzato. La pressione del tasto `ENTER` consente l’inserimento di ogni carattere del nome digitato.
3.  Premere nuovamente il tasto `SAVE` per completare il salvataggio dei dati o `ESC/MENU` per uscire senza salvare.

## 7.3. OPERAZIONI CON RISULTATI

### 7.3.1. Richiamo a display dei risultati di collaudi FV (SOLAR I - Vw, SOLAR I - Ve)

1.  Premere il tasto `ESC/MENU` per tornare al menu principale, selezionare la voce “`MEM`” e premere `ENTER` per entrare nella sezione di visualizzazione dei dati memorizzati. La videata di fianco è mostrata dallo strumento in cui è presente l’elenco delle prove salvate.
    ```
    15/05/10   15:34:26
    MEM   TIPO
    001   IST   08/04/2010
    002   REG 13/05/2010
    003   *REG 14/05/2010
    C o l l a u d o
    R i c   C a r a t t . I   -   V
    A p r i
    C a n c e l l a   
    Selezione   MEM   -   EF F
    ```
2.  Usando i tasti freccia (``, ``) e il tasto freccia `` selezionare la voce “`Richiama`” e successivamente “`Collaudo`” e confermare con `ENTER` per la visualizzazione dei soli risultati delle prove di collaudo.
3.  Usando il tasto freccia `` è possibile la visualizzazione delle seguenti etichette:
    *   `TIPO` → indica la tipologia di dato salvato: “`REG`” per un collaudo avente un preciso esito finale SI/NO, “`* REG`” quando lo strumento non dispone dei valori di irraggiamento e temperatura registrati dal `SOLAR - 02` e “`IST`” per il salvataggio delle condizioni istantanee a display.
    *   `DATA` → indica la data e l’ora in cui il dato è stato salvato nello strumento.
    *   `DESCRIZIONE` → indica la descrizione fornita dall’utente in fase di salvataggio del dato.
4.  Selezionare il tipo di dato “`IST`”, la voce “`Apri`” e confermare con `ENTER`. Lo strumento mostra la videata seguente:
    ```
    15/05/10   15:35:00
    
    P d c   3 . 1 2 5   k W
    V d c   3 8 9   V
    I d c   8 . 0 1   A
    n d c   0 . 8 8   ° C
    P a c   3 . 0 1 2   k W
    V a c   2 3 1   V
    I a c   1 3 . 0 3   A
    n a c   0 . 9 6
    R i s u l t a t i   a n a l i s i I
    Selezione   E F F
    ```
5.  Premere i tasti freccia (``, ``) per scorrere le due videate di valori disponibili.
6.  Premere il tasto `ESC/MENU` per tornare alla videata precedente.
7.  Selezionare il tipo di dato “`REG`”, la voce “`Apri`” e confermare con `ENTER`. Lo strumento mostra la videata seguente:
    ```
    15/05/10   15:35:00
    
    P d c   3 . 1 2 5   k W
    V d c   3 8 9   V
    I d c   8 . 0 1   A
    n d c   0 . 8 8   ° C
    P a c   3 . 0 1 2   k W
    V a c   2 3 1   V
    I a c   1 3 . 0 3   A
    n a c   0 . 9 6
    E s i t o   S I
    Selezione   E F F
    ```
8.  Premere i tasti freccia (``, ``) per scorrere le due videate di valori disponibili.
9.  Premere il tasto `ESC/MENU` per tornare alla videata precedente.
10. Selezionare il tipo di dato “`REG`”, la voce “`Apri`” e confermare con `ENTER`. Lo strumento mostra la videata dei valori finali del collaudo realizzato e l’indicazione dell’esito finale (SI/NO) del collaudo.
11. Selezionando il tipo di dato “`*REG`”, la voce “`Apri`” e la conferma con `ENTER` lo strumento mostra il messaggio “`Impossibile effettuare l’analisi`” per effetto della mancanza dei valori trasferiti dall’unità `SOLAR - 02`. I valori parziali di questa misura sono visibili solo trasferendo i dati a PC (vedere § 8).

### 7.3.2. Richiamo a display dei risultati di misura caratteristica I - V

1.  Premere il tasto `ESC/MENU` per tornare al menu principale, selezionare la voce “`MEM`” e premere `ENTER` per entrare nella sezione di visualizzazione dei dati memorizzati. La videata di fianco è mostrata dallo strumento in cui è presente l’elenco delle prove salvate.
    ```
    15/05/10   15:34:26
    MEM   DATA
    001   08/04/2010 10:38
    002   13/04/2010 12:15
    C o l l a u d o
    R i c   C a r a t t . I   -   V
    A p r i
    C a n c e l l a   
    Selezione   MEM I   -   V
    ```
2.  Usando i tasti freccia (``, ``) e il tasto freccia `` selezionare la voce “`Richiama`” e successivamente “`Caratt. I - V`” e confermare con `ENTER` per la visualizzazione dei soli risultati delle misure di caratteristica I - V.
3.  Il campo “`DATA`” indica la data/ora in cui è stato salvato il risultato della misura.
4.  Usare il tasto freccia `` per passare all’etichetta di Descrizione.
    ```
    15/06/09   15:34:26
    MEM   DESCRIZIONE
    001   IMPIANTO ROSSI
    002 *   IMPIANTO BIANCHI
    Selezione   MEM I   -   V
    ```
5.  Lo strumento visualizzerà il commento inserito dall’operatore durante la procedura di salvataggio del dato (vedere § 7.2) relativamente all’impianto.
6.  La presenza del simbolo “`*`” a fianco del numero della misura indica che lo strumento ha effettuate dei rilievi I - V con registrazione dei valori di Irraggiamento e Temperatura tramite unità remota ma tali valori non sono stati trasferiti o non sono disponibili. Per queste misure non saranno disponibili i valori traslati a STC.
7.  Usare il tasto freccia `` per passare all’etichetta di visualizzazione dei Parametri (Impianto, Stringa, Modulo).
    ```
    15/06/09   15:34:26
    MEM   IMP   STR   MOD
    001   0 0 1   0 0 1   0 0 1
    002   0 0 1   0 0 1   0 0 2
    Selezione   MEM I   -   V
    ```
8.  Lo strumento visualizzerà i marcatori selezionati dall’operatore durante la procedura di salvataggio del dato, associati al tipo di impianto, alla stringa considerata e al modulo in esame (vedere § 7.2).
9.  Premere `ESC/MENU` per uscire dalla videata e tornare al menu principale.

#### 7.3.2.1. Accesso ai dati salvati in memoria – Visualizzazione numerica

1.  Selezionare una riga corrispondente ad una risultato memorizzato e premere il tasto `ENTER`.
2.  Selezionare la voce “`Apri`” e premere ancora `ENTER` per entrare nella sezione di visualizzazione dei risultati di misura espressi come:
    *   Videate numeriche dei parametri misurati alle condizioni standard (STC) e alle condizioni operative di prova (OPC)
    *   Videate grafiche relative alle curve I - V salvate alle condizioni standard (STC) e alle condizioni operative di prova (OPC)
    ```
    15/05/10   15:34:26
    MEM   IMP   STR   MOD
    001   001   001   001
    002   001   001   002
    A p r i
    C a n c e l l a   
    Selezione   MEM I   -   V
    ```
3.  La prima videata fornisce i valori dei parametri misurati dallo strumento e riferiti ad 1 solo modulo, traslati alle condizioni standard di riferimento (STC) in accordo a quanto descritto nel § 6.2.3.
    ```
    15/05/10   15:34:26
    V o c   4 8 . 0   V
    V m p p   3 9 . 8   V
    I m p p   5 . 2 4   A
    I s c   5 . 6 0   A
    P m a x   2 0 8   W
    F F   0 . 7 8   %
    D P m a x   S T C
    O P C   m e d i a
    T a b e l l   O P C
    G r a f   I   -   V   
    G r a f   P o t      -   O K
    Selezione   MEM   I   –   V
    ```
4.  Premere il tasto `` selezionare con i tasti freccia (``, ``) l’opzione “`OPC media`” e premere `ENTER`.
    ```
    15/05/10   15:34:26
    V o c   4 6 . 9   V
    V m p p   3 9 . 0   V
    I m p p   4 . 8 5   A
    I s c   5 . 2 2   A
    P m a x   1 8 9   W
    F F   0 . 7 7   %
    I r r   9 2 7   W / m 2
    T c   2 5 . 1   ° C
    M i s u r e   @   O P C   –   M e d
    Selezione   MEM I   –   V
    ```
5.  Lo strumento fornisce i valori misurati alle condizioni reali operative (OPC) su di una stringa, mediati sul singolo modulo (coincidenti con quelli totali nel caso in cui la stringa sia formata da un solo modulo).
6.  Premere il tasto `` nella prima videata, selezionare con i tasti freccia (``, ``) l’opzione “`OPC`” e premere `ENTER`.
    ```
    15/05/10   15:34:26
    V o c   4 6 . 9   V
    V m p p   3 9 . 0   V
    I m p p   4 . 8 5   A
    I s c   5 . 2 2   A
    P m a x   1 8 9   W
    F F   0 . 7 7   %
    I r r   9 2 7   W / m 2
    T c   2 5 . 1   ° C
    M i s u r e   @   O P C
    Selezione   MEM I   –   V
    ```
7.  Lo strumento fornisce i valori misurati dallo strumento alle condizioni reali operative (OPC) totali relative alla stringa in prova.
8.  Premere il tasto `ESC/MENU` per tornare alla videata precedente.

#### 7.3.2.2. Accesso ai dati salvati in memoria – Visualizzazione grafica curva I - V

1.  Con videata dei valori misurati dallo strumento traslati alle condizioni standard di riferimento (STC) selezionare la voce “`Graf IV`” con il tasto freccia `` e premere `ENTER` o il tasto freccia ``.
2.  Selezionare la voce “`STC`” e premere `ENTER`.
3.  Lo strumento mostra la videata seguente.
    ```
    15/05/10   15:34:26
    V o c   4 8 . 0   V
    V m p p   3 9 . 8   V
    I m p p   5 . 2 4   A
    I s c   5 . 6 0   A
    P m a x   2 0 8   W
    F F   0 . 7 8   %
    D P m a x   S T C
    O P C   m e d i a
    T a b e l l a   O P C
    G r a f   I   -   V   
    G r a f   P o t      -   O K
    Selezione   MEM I   –   V
    ```
4.  Il grafico rappresenta la caratteristica I - V relativa all’oggetto in prova traslata alle condizioni standard di riferimento (STC) e riferita ad un 1 solo modulo.
    ```
    15/05/10   15:34:26
    G r a f i c o   I V   @   S T C   –   O K
    Selezione   MEM I   –   V
    ```
5.  Premere il tasto `ESC/MENU` per uscire dalla videata e tornare alla sezione di memoria.
6.  Con videata dei valori misurati dallo strumento selezionare la voce “`Graf I - V`” con il tasto freccia `` e premere `ENTER` o il tasto freccia ``.
7.  Selezionare l’opzione “`OPC media`” e premere `ENTER`. Lo strumento mostra la caratteristica I - V misurata su di una stringa, mediata sul singolo modulo alle condizioni reali operative (OPC).
    ```
    15/05/10   15:34:26
    G r a f .   I   -   V   @   O P C   -   M e d
    Selezione   MEM I   –   V
    ```
8.  Premere il tasto `ESC/MENU` per uscire dalla videata e tornare alla sezione di memoria.
9.  Con videata dei valori numerici misurati dallo strumento selezionare la voce “`Graf I - V`” con il tasto freccia `` e premere `ENTER` o il tasto freccia ``.
10. Selezionare l’opzione “`OPC`” e premere `ENTER`. Lo strumento mostra la caratteristica I - V misurata dallo strumento alle condizioni reali operative (OPC) totale relativa alla stringa in prova.
    ```
    15/05/10   15:34:26
    G r a f .   I   -   V   @   O P C
    Selezione   MEM I   –   V
    ```
11. Premere il tasto `ESC/MENU` per uscire dalla videata e tornare alla sezione di memoria.

#### 7.3.2.3. Accesso ai dati salvati in memoria – Visualizzazione grafica potenza

1.  Con videata dei valori misurati dallo strumento selezionare la voce “`Graf Pot`” con il tasto freccia `` e premere `ENTER` o il tasto freccia ``.
2.  Selezionare la voce “`STC`” e premere `ENTER`.
3.  Lo strumento mostra la videata seguente.
    ```
    15/05/10   15:34:26
    V o c   4 8 . 0   V
    V m p p   3 9 . 8   V
    I m p p   5 . 2 4   A
    I s c   5 . 6 0   A
    P m a x   2 0 8   W
    F F   0 . 7 8   %
    D P m a x   0 . 5   %
    T a b   S T C
    G r a f   O P C   m e d i a
    G r a f   O P R
    Selezione   MEM I   –   V
    ```
4.  Il grafico rappresenta l’andamento della potenza in uscita dal modulo /stringa traslato alle condizioni standard di riferimento (STC).
    ```
    15/05/10   15:34:26
    G r a f .   P o t   @   S T C   –   O K
    Selezione   MEM I   –   V
    ```
5.  Premere il tasto `ESC/MENU` per uscire dalla videata e tornare alla sezione di memoria.
6.  Con videata dei valori misurati dallo strumento selezionare la voce “`Graf Pot`” con il tasto freccia `` e premere `ENTER` o il tasto freccia ``.
7.  Selezionare l’opzione “`OPC media`” e premere `ENTER`. Lo strumento mostra l’andamento della potenza in uscita dal singolo modulo di una stringa misurata dallo strumento alle condizioni reali operative (OPC).
    ```
    15/05/10   15:34:26
    G r a f .   P o t   @   O P C   -   M e d
    Selezione   MEM I   –   V
    ```
8.  Premere il tasto `ESC/MENU` per uscire dalla videata e tornare alla sezione di memoria.
9.  Con videata dei valori misurati dallo strumento selezionare la voce “`Graf Pot`” con il tasto freccia `` e premere `ENTER` o il tasto freccia ``.
10. Selezionare l’opzione “`OPC`” e premere `ENTER`. Lo strumento mostra l’andamento della potenza in uscita dalla stringa misurata dallo strumento alle condizioni reali operative (OPC).
    ```
    15/05/10   15:34:26
    G r a f .   P o t   @   O P C
    Selezione   MEM I   –   V
    ```
11. Premere il tasto `ESC/MENU` per uscire dalla videata e tornare alla sezione di memoria.

### 7.3.3. Cancellazione dei dati in memoria

1.  All’interno della lista dei risultati salvati premere il tasto `ENTER` per la visualizzazione dei sottomenu.
2.  Selezionare il campo “`Cancella`”, premere il tasto ``. Lo strumento consente di selezionare le voci:
    *   `Canc Ultima` → cancella l’ultima prova salvata
    *   `Canc Tutto` → cancella l’intero contenuto della memoria
    ```
    15/05/10   15:34:26
    MEM   TIPO
    001   IST   08/04/2010
    002   REG 13/04/2010
    R i c h i a m a   
    A p r i   C a n c   U l t i m a
    C a n c   C a n c   T u t t o
    Selezione   MEM EFF
    ```
3.  Selezionare con i tasti freccia (``, ``) l’opzione desiderata e premere il tasto `ENTER` per confermare la scelta.
4.  Premere `ESC/MENU` per uscire dalla videata e tornare al menu principale.

# 8. COLLEGAMENTO DELLO STRUMENTO A PC

## 8.1. COLLEGAMENTO TRAMITE CAVO OTTICO/USB C2006

> **ATTENZIONE**
> *   La connessione tra PC e strumento avviene tramite il cavo ottico/USB `C2006`. Per effettuare il trasferimento dati verso un PC è necessario avere preventivamente installato nel PC stesso sia il Sw di gestione `Topview` che i driver del cavo `C2006` sul PC di destinazione.
> *   Prima di effettuare il collegamento è necessario selezionare a PC la porta utilizzata e il baud rate corretto (57 600 bps). Per impostare questi parametri avviare il software `TopView` in dotazione e consultare l’help in linea del programma.
> *   La porta selezionata non deve essere impegnata da altri dispositivi o applicazioni come mouse, modem, ecc. Chiudere eventualmente processi in esecuzione a partire dalla funzione Task Manager di Windows.
> *   La porta ottica emette radiazione LED invisibile. Non osservare direttamente con strumenti ottici. Apparecchio LED di classe 1M secondo IEC/ EN60825 - 1.

Per trasferire i dati a PC attenersi alla seguente procedura:

1.  Accendere lo strumento premendo il tasto `ON/OFF`.
2.  Collegare lo strumento a PC utilizzando il cavo ottico/USB `C2006` in dotazione.
3.  Premere il tasto `ESC/MENU` per aprire il menu principale.
4.  Selezionare con i tasti freccia (``, ``) la voce “`PC`” per entrare in modalità trasferimento dati e confermare con `ENTER`.
    ```
    15/05/10   15:34:26
    I   -   V   Ca ratt.   I - V
    CLD   Collaudo
    SET   Impostazioni
    DB   Moduli
    MEM   Dati memoria
    PC   Colleg. con PC
    E N T E R   p e r   s e l e z .
    M E N U
    ```
5.  Lo strumento fornisce la videata seguente:
    ```
    15/05/10   15:34:26
    PC   –   RS232
    WiFI ON
    M E N U
    ```
6.  Usare i comandi del software TopView per attivare il trasferimento dati (consultare l’help in linea del programma).

## 8.2. COLLEGAMENTO TRAMITE WIFI

> **ATTENZIONE**
> *   La connessione tra PC e strumento avviene tramite interfaccia WiFi normalmente attiva sullo strumento. La funzione WiFi non è disponibile se nella videata iniziale compare l'indicazione “`WiFi - OFF`”.
> *   Per effettuare il trasferimento dati è necessario avere un PC dotato di interfaccia WiFi ed avere preventivamente installato il Sw di gestione `Topview`.
> *   Prima di effettuare il collegamento è necessario attivare la comunicazione WiFi sullo strumento (vedere punto 4) e sul PC selezionare e connettere la “rete senza fili” (WiFi) resa disponibile dallo strumento.
> *   Prima di effettuare il collegamento è necessario selezionare a PC la porta “`WiFi`” nella sezione “`Collegamento PC – Strumento`” del software `TopView` in dotazione e consultare l’help in linea del programma.

Per trasferire i dati a PC attenersi alla seguente procedura:

1.  Accendere lo strumento premendo il tasto `ON/OFF`.
2.  Premere il tasto `ESC/MENU` per aprire il menu principale.
3.  Selezionare con i tasti freccia (``, ``) la voce “`PC`” per entrare in modalità trasferimento dati e confermare con `ENTER`.
    ```
    15/05/10   15:34:26
    I   -   V   Caratt. I - V
    CLD   Collaudo
    SET   Impostazioni
    DB   Moduli
    MEM   Dati memoria
    PC   Colleg. con PC
    E N T E R   p e r   s e l e z .
    M E N U
    ```
4.  Lo strumento fornisce la videata seguente:
    ```
    15/05/10   15:34:26
    PC   –   RS232
    WiFI ON
    M E N U
    ```
5.  Abilitare la connessione WiFi sul PC di destinazione (ex: tramite uso di una chiavetta WiFi installata e collegata ad una porta USB). Selezionare e connettere la rete WiFi resa disponibile dallo strumento all’interno delle impostazioni “`Connessioni di rete`” → “`Reti senza fili`”.
6.  Usare i comandi del software TopView per attivare il trasferimento dati (consultare l’help in linea del programma).

<!-- Chunk: Pages 65-79 -->
## 9. MANUTENZIONE

### 9.1. GENERALITÀ

Lo strumento da Lei acquistato è uno strumento di precisione. Durante l’utilizzo e l’immagazzinamento rispettare le raccomandazioni elencate in questo manuale per evitare possibili danni o pericoli durante l’utilizzo.

Non utilizzare lo strumento in ambienti caratterizzati da elevato tasso di umidità o temperatura elevata. Non esporre direttamente alla luce del sole.

Spegnere sempre lo strumento dopo l’utilizzo. Se si prevede di non utilizzarlo per un lungo periodo di tempo, rimuovere le batterie per evitare da parte di queste ultime fuoruscite di liquidi che possono danneggiare i circuiti interni dello strumento.

### 9.2. SOSTITUZIONE BATTERIE

Quando sul display LCD appare il simbolo di batteria scarica “ ” oppure quando durante una prova si ha il messaggio “batteria scarica” a display, sostituire le batterie interne.

> **ATTENZIONE**
> Solo tecnici qualificati possono effettuare questa operazione. Prima di effettuare questa operazione assicurarsi di aver rimosso tutti i cavi dai terminali di ingresso.

1.  Spegnere lo strumento premendo a lungo il pulsante di accensione.
2.  Rimuovere i cavi dai terminali di ingresso.
3.  Svitare la vite di fissaggio del coperchio dal vano batterie e rimuovere lo stesso.
4.  Rimuovere dal vano batterie tutte le batterie e sostituirle solo con batterie tutte nuove e tutte del tipo corretto (§ 10.4 ) rispettando le polarità indicate.
5.  Riposizionare il coperchio vano batterie e fissarlo con l'apposita vite.
6.  Non disperdere nell’ambiente le batterie utilizzate. Usare gli appositi contenitori per lo smaltimento.

### 9.3. PULIZIA DELLO STRUMENTO

Per la pulizia dello strumento utilizzare un panno morbido e asciutto. Non usare mai panni umidi, solventi, acqua, ecc.

### 9.4. FINE VITA

> **ATTENZIONE**: il simbolo riportato indica che l'apparecchiatura, i suoi accessori e le batterie interne devono essere raccolti separatamente e trattati in modo corretto.

## 10. SPECIFICHE TECNICHE

### 10.1. SPECIFICHE TECNICHE COLLAUDO IMPIANTI FV (SOLAR I-VW, SOLAR I-VE)

L’incertezza è indicata come [`% lettura + (num. cifre) * risoluzione`] a 23°C ± 5°C, <80%HR.

#### Tensione DC (SOLAR I-Vw)

| Campo [V]        | Risoluzione [V] | Incertezza               |
| :--------------- | :-------------- | :----------------------- |
| 15.0 ÷ 999.9     | 0.1             | ± (0.5 % lettura + 2cifre) |

#### Tensione DC (SOLAR I-Ve)

| Campo [V]        | Risoluzione [V] | Incertezza               |
| :--------------- | :-------------- | :----------------------- |
| 15.0 ÷ 99.9      | 0.1             | ± (0.5 % lettura + 2cifre) |
| 100.0 ÷ 1499.0   | 0.3             |                          |

#### Tensione AC TRMS

| Campo [V]        | Risoluzione [V] | Incertezza               |
| :--------------- | :-------------- | :----------------------- |
| 50.0 ÷ 265.0     | 0.1             | ± (0.5 % lettura + 2cifre) |

Max fattore di cresta: 1,5

#### Corrente DC (tramite trasduttore a pinza esterno)

| Campo [mV]       | Risoluzione [mV] | Incertezza             |
| :--------------- | :--------------- | :--------------------- |
| -1100 ÷ -5       | 0.1              | ± (0.5 % lettura + 0.6 mV) |
| 5 ÷ 1100         |                  |                        |

Il valore della corrente è visualizzato SEMPRE con segno positivo: Il valore di corrente tradotto in tensione inferiore a 5mV è azzerato.

#### Corrente AC TRMS (tramite trasduttore a pinza esterno)

| Campo [mV]       | Risoluzione [mV] | Frequenza [Hz] | Incertezza             |
| :--------------- | :--------------- | :------------- | :--------------------- |
| 1 ÷ 1200         | 0.1              | 47.5 ÷ 63.0    | ± (0.5 % lettura + 0.6 mV) |

Max fattore di cresta: 2.0; Il valore di corrente tradotto in tensione inferiore a 5mV è azzerato.

#### FS pinze DC e AC

| FS pinze DC e AC [A] | Risoluzione [A] | Valore minimo letto [A] DC | Valore minimo letto [A] AC |
| :------------------- | :-------------- | :------------------------- | :------------------------- |
| 1< FS ≤ 10           | 0.001           | 0.05                       | 0.01                       |
| 10< FS ≤ 100         | 0.01            | 0.5                        | 0.1                        |
| 100< FS ≤ 1000       | 0.1             | 5A                         | 1                          |

#### Potenza DC (Vmis > 150V) (SOLAR I-Vw)

| FS pinza [A] | Campo [W]           | Risoluzione [W] | Incertezza                      |
| :----------- | :------------------ | :-------------- | :------------------------------ |
| 1< FS ≤ 10   | 0.000k ÷ 9.999k     | 0.001k          | ± (0.7 % lettura + 3 cifre )<br>(Imis < 10%FS) |
|              | 10.00k ÷ 99.99k     | 0.01k           |                                 |
| 10< FS ≤ 100 | 0.000k ÷ 9.999k     | 0.001k          | ± (0.7 % lettura )<br>(Imis ≥ 10%FS) |
|              | 10.00k ÷ 99.99k     | 0.01k           |                                 |
| 100< FS ≤ 1000 | 0.00k ÷ 99.99k    | 0.01k           |                                 |
|              | 100.0k ÷ 999.9k     | 0.1k            |                                 |

`Vmis` = tensione a cui è misurata la potenza; `Imis` = corrente misurata.

#### Potenza DC (Vmis > 150V) (SOLAR I-Ve)

| FS pinza [A] | Campo [W]           | Risoluzione [W] | Incertezza                      |
| :----------- | :------------------ | :-------------- | :------------------------------ |
| 1< FS ≤ 10   | 0.000k ÷ 9.999k     | 0.001k          | ± (0.7 % lettura + 3 cifre )<br>(Imis < 10%FS) |
|              | 10.00k ÷ 99.99k     | 0.01k           |                                 |
| 10< FS ≤ 100 | 0.000k ÷ 9.999k     | 0.001k          | ± (0.7 % lettura )<br>(Imis ≥ 10%FS) |
|              | 10.00k ÷ 99.99k     | 0.01k           |                                 |
|              | 100.0k ÷ 999.9k     | 0.1k            |                                 |
| 100< FS ≤ 1000 | 0.00k ÷ 99.99k    | 0.01k           |                                 |
|              | 100.0k ÷ 999.9k     | 0.1k            |                                 |
|              | 1000k ÷ 9999k       | 1k              |                                 |

`Vmis` = tensione a cui è misurata la potenza; `Imis` = corrente misurata.

#### Potenza AC (Vmis > 200V, PF=1) (SOLAR I-Vw)

| FS pinza [A] | Campo [W]           | Risoluzione [W] | Incertezza                      |
| :----------- | :------------------ | :-------------- | :------------------------------ |
| 1< FS ≤ 10   | 0.000k ÷ 9.999k     | 0.001k          | ± (0.7 % lettura + 3 cifre )<br>(Imis < 10%FS) |
|              | 10.00k ÷ 99.99k     | 0.01k           |                                 |
| 10< FS ≤ 100 | 0.000k ÷ 9.999k     | 0.001k          | ± (0.7 % lettura )<br>(Imis ≥ 10%FS) |
|              | 10.00k ÷ 99.99k     | 0.01k           |                                 |
| 100< FS ≤ 1000 | 0.00k ÷ 99.99k    | 0.01k           |                                 |
|              | 100.0k ÷ 999.9k     | 0.1k            |                                 |

`Vmis` = tensione a cui è misurata la potenza; `Imis` = corrente misurata.

#### Potenza AC (Vmis > 200V, PF=1) (SOLAR I-Ve)

| FS pinza [A] | Campo [W]           | Risoluzione [W] | Incertezza                      |
| :----------- | :------------------ | :-------------- | :------------------------------ |
| 1< FS ≤ 10   | 0.000k ÷ 9.999k     | 0.001k          | ± (0.7 % lettura + 3 cifre )<br>(Imis < 10%FS) |
|              | 10.00k ÷ 99.99k     | 0.01k           |                                 |
| 10< FS ≤ 100 | 0.000k ÷ 9.999k     | 0.001k          | ± (0.7 % lettura )<br>(Imis ≥ 10%FS) |
|              | 10.00k ÷ 99.99k     | 0.01k           |                                 |
|              | 100.0k ÷ 999.9k     | 0.1k            |                                 |
| 100< FS ≤ 1000 | 0.00k ÷ 99.99k    | 0.01k           |                                 |
|              | 100.0k ÷ 999.9k     | 0.1k            |                                 |
|              | 1000k ÷ 9999k       | 1k              |                                 |

`Vmis` = tensione a cui è misurata la potenza; `Imis` = corrente misurata.

#### Frequenza

| Campo [Hz]       | Risoluzione [Hz] | Incertezza             |
| :--------------- | :--------------- | :--------------------- |
| 47.5 ÷ 63.0      | 0.1              | ± (0.2 % lettura + 1cifra) |

#### Irraggiamento (con cella di riferimento)

| Campo [mV]       | Risoluzione [mV] | Incertezza               |
| :--------------- | :--------------- | :----------------------- |
| 1.0 ÷ 65.0       | 0.1              | ± (1.0 % lettura + 5cifre) |

#### Temperatura (con sonda di tipo PT1000)

| Campo [°C]       | Risoluzione [°C] | Incertezza             |
| :--------------- | :--------------- | :--------------------- |
| -20.0 ÷ 100.0    | 0.1              | ± (1.0 % lettura + 1°C) |

### 10.2. CARATTERISTICHE TECNICHE FUNZIONE I-V E IVCK

#### I-V, IVCK: Tensione DC @ OPC (SOLAR I-Vw, I-V400w)

| Campo [V] (*)    | Risoluzione [V] | Incertezza (*)           |
| :--------------- | :-------------- | :----------------------- |
| 5.0 ÷ 999.9      | 0.1             | ± (1.0 % lettura + 2cifre) |

(*) Le misure della caratteristica I-V partono per `VDC > 15V` con incertezza definita per `VDC > 20V`.

#### I-V, IVCK: Tensione DC@ OPC (SOLAR I-Ve, I-V500w)

| Campo [V] (*)    | Risoluzione [V] | Incertezza (*)           |
| :--------------- | :-------------- | :----------------------- |
| 15.0 ÷ 99.9      | 0.1             | ± (0.5 % lettura + 2cifre) |
| 100.0 ÷ 1499.9   | 0.3             |                          |

(*) Le misure della caratteristica I-V partono per `VDC > 15V` con incertezza definita per `VDC > 20V`.

#### I-V, IVCK: Corrente DC @ OPC

| Campo [A] (*)    | Risoluzione [A] | Incertezza               |
| :--------------- | :-------------- | :----------------------- |
| 0.10 ÷ 15.00     | 0.01            | ± (1.0 % lettura + 2cifre) |

(*) Massima corrente test I-V = 15A per `Voc ≤ 1000V`, Massima corrente = 10A per `Voc > 1000V` (I-V500w e SOLAR I-Ve).

#### I-V: Potenza DC @ OPC (Vmpp > 30V, Impp > 2A)

| Campo [W] (*)    | Risoluzione [W] | Incertezza               |
| :--------------- | :-------------- | :----------------------- |
| 50 ÷ 99999       | 1               | ± (1.0 % lettura + 6cifre) |

`Vmpp` = tensione nel punto di massima potenza; `Impp` = corrente nel punto di massima potenza.
(*) Il valore di Potenza max misurabile deve tenere conto anche del FF max di circa 0.7 → `Pmax = 1000V x 15A x 0.7 = 10500 W` → `Pmax = 1500V x 10A x 0.7 = 10500W`.

#### I-V, IVCK: Tensione DC @ STC

| Campo [V]        | Risoluzione [V] | Incertezza (* ,**)        |
| :--------------- | :-------------- | :----------------------- |
| 5.0 ÷ 999.9      | 0.1             | ± (4.0 % lettura + 2cifre) |

#### I-V: Corrente DC @ STC

| Campo [A]        | Risoluzione [A] | Incertezza (**)          |
| :--------------- | :-------------- | :----------------------- |
| 0.10 ÷ 99.00     | 0.01            | ± (4.0 % lettura + 2cifre) |

#### I-V: Potenza DC @ STC (Vmpp > 30 V, Impp > 2 A)

| Campo [W]        | Risoluzione [W] | Incertezza complessiva (**) |
| :--------------- | :-------------- | :-------------------------- |
| 50 ÷ 99999       | 1               | ± (5.0 % lettura + 1 cifra )  |

`Vmpp` = tensione nel punto di massima potenza, `Impp` = corrente nel punto di massima potenza.
(*) Le misure della caratteristica I-V partono per `VDC > 15V` con incertezza definita per `VDC > 20V`.
(**) Nelle condizioni:
*   Irragg. stabile ≥ 700W/m², spettro AM 1.5, Incidenza raggi solari rispetto alla per ≤ ± 25°, Temp. Celle [15..65°C]
*   L’incertezza dichiarata include già l’incertezza del trasduttore di Irraggiamento e relativo circuito di misura.

#### Irraggiamento (con cella di riferimento)

| Campo [mV]       | Risoluzione [mV] | Incertezza               |
| :--------------- | :--------------- | :----------------------- |
| 1.0 ÷ 100.0      | 0.1              | ± (1.0 % lettura + 5cifre) |

#### Temperatura (con sonda di tipo PT1000)

| Campo [°C]       | Risoluzione [°C] | Incertezza             |
| :--------------- | :--------------- | :--------------------- |
| -20.0 ÷ 100.0    | 0.1              | ± (1.0 % lettura + 1°C ) |

> **ATTENZIONE**
> Non utilizzare lo strumento per misure di Curve I-V e test IVCK su moduli FV con efficienza >19%. Verificare preliminarmente le caratteristiche tecniche dei moduli FV prima di eseguire i test al fine di evitare possibili danneggiamenti dello strumento.

### 10.3. NORME DI SICUREZZA

#### 10.3.1. Generali

*   Sicurezza strumento: IEC/EN61010-1
*   EMC: IEC/EN61326-1
*   Documentazione tecnica: IEC/EN61187
*   Sicurezza accessori di misura: IEC/EN61010-031
*   Misure: Guida CEI 82-25 (SOLAR I-Vw, SOLAR I-Ve)
    *   IEC/EN 60891 (misura caratteristica I-V)
    *   IEC/EN 60904-5 (misura della Temperatura)
*   Isolamento: doppio isolamento
*   Grado di inquinamento: 2
*   Categoria di misura: CAT II 1000V DC, CAT III 300 V AC verso terra
*   Max 1000V tra gli ingressi P1, P2, C1, C2 (SOLAR I-Vw, I-V400w)
*   Max 1500V tra gli ingressi P1, P2, C1, C2 (SOLAR I-Ve, I-V500w)

### 10.4. CARATTERISTICHE GENERALI

#### Display e memoria

*   Tipo display: LCD custom, 128x128 pxl, retroilluminato
*   Capacità di memoria: 256kbytes
*   Dati memorizzabili: 99 collaudi (SOLAR I-Vw/I-Ve); 249 curve I-V, 999 IVCK
*   Interfaccia PC: ottica/USB e WiFi

#### Caratteristiche modulo radio

*   Campo di frequenza: 2.412 ÷ 2.462GHz
*   Modulazione: 802.11b Compatibilità: DSSS (CCK-11, CCK-5.5, DQPSK-2, DBPSK-1), 802.11g: OFDM
*   Categoria R&TTE: Classe 1
*   Potenza max di trasmissione: 30 μW
*   Distanza max collegamento RF: 1m

#### Collaudo impianti FV (SOLAR I-Vw, SOLAR I-Ve)

*   Periodo di integrazione: 5,10,30,60,120,300,600,900,1800,3600s
*   Memoria SOLAR-02 - MPP300: circa 1.5 ore (@ PI = 5s), circa 8 gg (@ PI = 600s)

#### Alimentazione

*   Tipo batterie: 6x1.5V alcaline tipo AA LR06
*   Consumo: 1W
*   Indicazione batteria scarica: simbolo “ ” mostrato a display
*   Durata batterie: circa 120 ore (collaudo FV), 249 misure caratteristica I-V, 999 misure IV Check
*   Autospegnimento: dopo 5 minuti di non utilizzo

#### Caratteristiche meccaniche

*   Dimensioni (L x La x H): 235 x 165 x 75mm
*   Peso (batterie incluse): 1.2kg
*   Protezione meccanica: IP40

### 10.5. CONDIZIONI AMBIENTALI DI UTILIZZO

*   Temperatura di riferimento: 23°C ± 5°C
*   Temperatura di utilizzo: 0°C ÷ 40°C
*   Umidità relativa ammessa: <80%RH
*   Temperatura di conservazione: -10°C ÷ 60°C
*   Umidità di immagazzinamento: <80%RH
*   Max altitudine di utilizzo: 2000m (*)

> **ATTENZIONE**
> (*) Prescrizioni per uso dello strumento ad altitudini comprese tra 2000 e 5000m.
> Lo strumento, relativamente agli ingressi P1, P2, C1, C2 è da considerarsi declassato a categoria di sovratensione CAT I 1000V DC e CAT II 300V verso Terra max 1000V tra gli ingressi (per modelli SOLAR I-Vw e I-V400w) e max 1500V tra gli ingressi (per modelli SOLAR I-Ve e I-V500w). Le marcature e i simboli riportati sullo strumento sono da considerarsi valide solo con uso dello strumento ad altitudine <2000m.
>
> Questo strumento è conforme ai requisiti della Direttiva Europea sulla bassa tensione 2014/35/EU (LVD), della direttiva EMC 2014/30/EU e della direttiva RED 2014/53/EU.
>
> Questo strumento è conforme ai requisiti della direttiva europea 2011/65/EU (RoHS) e della direttiva europea 2012/19/EU (WEEE).

### 10.6. ACCESSORI

Utilizzare solo gli accessori si serie o opzionali presenti nella packing list allegata.

## 11. APPENDICE – CENNI TEORICI

### 11.1. COLLAUDO DEGLI IMPIANTI FV (SOLAR I-VW, SOLAR I-VE)

In accordo con quanto previsto dalla normativa vigente, l’esito del collaudo su una installazione FV monofase sarà funzione del tipo di correzione adottato per compensare gli effetti della temperatura e della relazione matematica utilizzata per calcolare il `PRp` (v. § 5.2.3).

| Corr. | Valore di Tcel                                                                 | Relazione matematica per calcolo PRp                                      | Norma    | Esito    |
| :---- | :----------------------------------------------------------------------------- | :------------------------------------------------------------------------ | :------- | :------- |
| Tmod  | `Tcel = Valore della Temp. moduli misurata`                                    | `PRp = (Pca / (P_n * (G_p / G_STC) * Rfv^2))`                            | CEI 82-25 | OK/NO    |
| Tamb  | `Tcel = Val. della Temp. moduli calcolata: Tamb + 20 * (G_p / 800)`          | `PRp = (Pca / (P_n * (G_p / G_STC) * Rfv^2))`                            |          |          |
| nDC   | `Tcel = Valore della Temperatura moduli misurata`                              | `PRp = Pca / (P_n * (G_p / G_STC) * (1 + gamma/100 * (Tcel - 25)))` | -        | -        |

dove:

| Simbolo      | Descrizione                                                                                                                                                                                                                                       | U.di misura   |
| :----------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------------ |
| `G_p`        | Irraggiamento misurato sul piano dei moduli                                                                                                                                                                                                       | [`W/m²`]      |
| `G_STC`      | Irraggiamento in condizione Standard = 1000                                                                                                                                                                                                       | [`W/m²`]      |
| `P_n`        | Potenza nominale = somma delle `Pmax` dei moduli FV facenti parte della sezione dell’impianto in esame                                                                                                                                              | [`kW`]        |
| `P_inv`      | Potenza nominale della tipologia dell’inverter facente parte della sezione dell’impianto in esame                                                                                                                                                 | [`kW`]        |
| `Pca`        | Potenza in ca complessiva misurata all’uscita del/degli inverter facenti parti della sezione dell’impianto in esame                                                                                                                               | [`kW`]        |
| `γ`          | Coefficiente correttivo funzione della Temperatura delle Celle FV (Tcel) misurata o calcolata in accordo al tipo di relazione di correzione selezionata. `γ = (1 - (Tcel - 40)/100)` se `Tcel <= 40°C`, `γ = 1` se `Tcel > 40°C`               | `% / °C`      |
| `NOCT`       | (Nominal Operating Cell Temperature) = Temperatura a cui si portano le celle in condizioni di rif (800W/m², 20°C, AM=1.5, Vel. Aria =1m/s).                                                                                                      | [`°C`]        |

Le precedenti relazioni sono valide nelle condizioni `Irraggiamento > Irraggiamento min` (vedi manuale d’uso strumento MASTER) e di “irraggiamento stabile” cioè per ogni campione rilevato, con `IP ≤ 1min`, la differenza tra i valori massimi e minimi di irraggiamento misurati deve essere < 20W/m².

In generale l’esito potrà essere:

*   Impossibile effettuare l’analisi se l’irraggiamento non ha mai raggiunto un valore stabile superiore alla soglia minima impostata oppure se non esiste nessun valore valido durante tutto l’arco della registrazione (`PRp > 1.15`).
*   ESITO SI (correz. “Tmod” o “Tamb”): se esiste almeno 1 valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente.
*   ESITO NO (correz. “Tmod” o “Tamb”): se NON esiste nessun valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente.
*   Non visualizzerà nessun esito (SI o NO) se lo strumento è stato impostato con correzione di temperatura tipo “nDC”.

#### Esito visualizzato SI (correz. “Tmod” o “Tamb”)

Lo strumento fornisce un esito complessivo positivo in accordo alla Guida CEI 82-25, se, nell’insieme dei campioni rilevati durante il collaudo, ne esiste almeno uno valido per cui sono soddisfatte le seguenti relazioni:

`PRp = Pca / (P_n * (G_p / G_STC) * Rfv^2)`
Se `P_inv <= 20kW` allora `PRp > 0.78`
Se `P_inv > 20kW` allora `PRp > 0.80`

(per il significato delle definizioni e dei simboli si veda il paragrafo precedente)

Se esistono più campioni che soddisfano tutte le condizioni precedenti, lo strumento visualizza automaticamente quello corrispondente al massimo valore di `PRp`.

#### Esito visualizzato NO (correz. “Tmod” o “Tamb”)

Lo strumento fornisce un esito complessivo negativo in accordo alla Guida CEI 82-25, se, nell’insieme dei campioni rilevati durante il collaudo, NON ne esiste nemmeno uno valido per cui sono soddisfatte le seguenti relazioni:

`PRp = Pca / (P_n * (G_p / G_STC) * Rfv^2)`
Se `P_inv <= 20kW` allora `PRp > 0.78`
Se `P_inv > 20kW` allora `PRp > 0.80`

(per il significato delle definizioni e dei simboli si veda il paragrafo precedente)

In questo caso lo strumento visualizza comunque i valori corrispondenti al massimo valore di `PRp` raggiunto.

#### Nessun esito (correzione “nDC”)

Lo strumento fornisce come risultato i valori corrispondenti al punto di massimo `PRp` calcolato come:

`PRp = Pca / (P_n * (G_p / G_STC) * (1 + gamma/100 * (Tcel - 25)))`

(per il significato delle definizioni e dei simboli si veda il paragrafo precedente)

### 11.2. CENNI SU MPPT (MAXIMUM POWER POINT TRACKER)

L’irraggiamento solare su una superficie quale può essere quella di un impianto fotovoltaico ha caratteristiche fortemente variabili, essendo dipendente dalla posizione del sole rispetto a detta superficie e dalle caratteristiche dell’atmosfera (tipicamente dalla presenza di nuvole). Un modulo fotovoltaico presenta, per vari valori dell’irraggiamento solare, e per vari valori della temperatura, una famiglia di curve caratteristiche del tipo indicato nella seguente figura. In particolare in essa sono rappresentate tre curve I-V (in grassetto) corrispondenti a tre valori (1000, 800, 600W/m²) di irraggiamento solare. Su ogni curva caratteristica esiste uno ed un solo punto tale per cui è massimizzato il trasferimento di potenza verso un ipotetico carico alimentato dal modulo fotovoltaico. Il punto di massima potenza corrisponde alla coppia tensione-corrente tale per cui è massimo il prodotto `V*I`, dove `V` è il valore della tensione ai morsetti del modulo e `I` è la corrente che circola nel circuito ottenuto chiudendo il modulo su un ipotetico carico. Sempre con riferimento alla figura precedente, il prodotto `V*I` è rappresentato per i tre valori dell’irraggiamento solare di cui sopra, tramite le tre curve a tratto più sottile. Come si vede, in accordo con quanto detto prima, tali curve esibiscono un solo massimo. Ad es. per 1000W/m², il punto di massima potenza corrisponde ad un valore di tensione pari a circa 36V e corrente di circa 5,5A. Chiaramente, se si riesce a massimizzare la potenza erogata dall'impianto, si riesce a sfruttarlo al meglio, sia che questo sia connesso alla rete, sia stand-alone.

L’MPPT è un dispositivo integrato negli inverter che, tipicamente, ad ogni istante legge i valori di tensione e corrente, ne calcola il prodotto (cioè la potenza in Watt) e, provocando piccole variazioni nei parametri di conversione (duty cycle), è in grado di stabilire per confronto se il modulo fotovoltaico sta lavorando in condizioni di massima potenza oppure no. A seconda del “responso” agisce ancora sul circuito per portare l’impianto in tale condizione ottimale. Il motivo per cui gli MPPT sono utilizzati è semplice: un impianto fotovoltaico senza MPPT può funzionare comunque, ma a parità di irraggiamento solare fornisce meno energia.

Sul mercato esistono inverter con 1, 2 o anche 3 MPPT integrati al loro interno. Tipicamente gli inverter con più di un MPPT sono impiegati negli impianti in cui:

*   I vari campi fotovoltaici che lo compongono hanno “forzatamente” inclinazioni o orientamenti diversi. In questo modo ogni singolo MPPT gestisce il proprio campo fotovoltaico massimizzandone il rendimento per le caratteristiche di irraggiamento e temperature corrispondenti (senza essere influenzato dagli altri campi fotovoltaici).
*   Sia ricercata una maggior continuità di servizio. Con più MPPT può essere messo fuori servizio un solo campo fotovoltaico mentre gli altri continuano a produrre energia verso i restanti MPPT.

### 11.3. MISURA DELLA CARATTERISTICA I-V

Lo strumento è progettato per eseguire test e misure su moduli FV formati da un opportuno numero di celle FV al fine di rilevare la loro caratteristica I-V (Corrente-Tensione) che li identificano costruttivamente, sulla base della normativa di riferimento IEC/EN60891.
I test sono eseguibili sia su singoli moduli sia su una stringa FV (insieme di moduli FV), il cui insieme costituisce ciò che viene comunemente detto “generatore fotovoltaico”, parte integrante di una installazione FV Monofase o Trifase.

#### 11.3.1. Aspetti teorici sulla misura della Caratteristica I-V

A livello teorico il test sulla caratteristica I-V avviene nel modo seguente:

*   Lo strumento esegue la misura della caratteristica I-V sul modulo ad esso collegato, oltre alla misura di irraggiamento e di temperatura del modulo.
*   Il risultato della misura viene automaticamente “traslato” alle condizioni Standard STC (Standard Test Condition) di irraggiamento pari a `1000W/m²` e temperatura modulo pari a `25°C`. Per ottenere risultati di precisione conforme a quanto indicato nel presente manuale si raccomanda di attenersi alle specifiche riportate nel § 10.1.
*   Viene eseguito il controllo fra la potenza nominale massima, con il margine di tolleranza percentuale dichiarato dal costruttore del modulo e inserito nel tipo di modulo in precedenza selezionato sullo strumento (vedere § 5.3.1), ed il valore misurato.
*   Se il controllo rientra nel margine di tolleranza dichiarato, l’esito della prova sarà “OK” oppure “NOT OK” in caso contrario con conseguenza che il modulo FV non soddisfa le prescrizioni dichiarate dal costruttore (vedere § 6.2.3).

#### 11.3.2. Errori tipici sulla misura di curva I-V e possibili soluzioni

| Evento                             | Descrizione                                                                                                                              | Soluzione                                                                                                                                                                                                                                                                       |
| :--------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Misura corretta                    | • La curva misurata estrapolata alle condizioni STC (blu) è congruente con la curva ideale del costruttore (nera)                         | • Nessun errore, salvare il dato ed eseguite test su un’altra stringa                                                                                                                                                                                                               |
| Isc troppo bassa                   | • Sensore di irraggiamento orientato in modo diverso rispetto alla stringa in prova<br>• Riflessioni sul sensore di irraggiamento<br>• Errata selezione del modulo nella configurazione del sistema FV<br>• Contaminazione ambientale sul modulo (sporcizia, neve, detriti)<br>• Ostruzioni a media distanza (ombreggiamenti)<br>• Invecchiamento | • Orientare correttamente il sensore di irraggiamento<br>• Impostare correttamente lo strumento<br>• Pulire i moduli<br>• Rimuovere le ostruzioni<br>• Controllare i moduli da ombreggiamenti, umidità, ecc<br>• Sostituire i moduli danneggiati                               |
| Isc troppo alta                    | • Sensore di irraggiamento orientato in modo diverso rispetto alla stringa in prova<br>• Riflessioni sul sensore di irraggiamento<br>• Sporcizia sul sensore di irraggiamento<br>• Errata selezione del modulo nella configurazione del sistema FV<br>• Sensore di irraggiamento danneggiato | • Orientare correttamente il sensore di irraggiamento<br>• Pulire il sensore di irraggiamento<br>• Rimuovere le ostruzioni<br>• Controllare i moduli da ombreggiamenti, umidità, ecc.<br>• Controllare le impostazioni sullo strumento<br>• Sostituire il sensore di irraggiamento danneggiato |
| Tensione a vuoto troppo bassa      | • Misura di temperatura bassa<br>• Selezione errata del numero di moduli nella configurazione del sistema FV<br>• Diodi di bypass cortocircuitati | • Collegare correttamente la termocoppia nella sede tipica del modulo<br>• Selezionare il modo AUTO<br>• Impostare correttamente lo strumento<br>• Sostituire i moduli danneggiati                                                                                        |
| Rapporto Impp/Isc basso            | • Sporcizia sui moduli<br>• Problemi di ombreggiatura<br>• Corrispondenza incorretta delle correnti<br>• Degrado della resistenza shunt della cella | • Pulire i moduli<br>• Eliminare l’ombreggiatura sui moduli<br>• Controllare la corrispondenza delle correnti<br>• Sostituire i moduli danneggiati                                                                                                              |
| Rapporto Vmpp/Voc basso            | • Caduta di tensione sui cavi delle stringhe di moduli FV                                                                                | • Controllare cavi, connettori, contatti e connessioni delle stringhe<br>• Controllare lunghezza e sezione dei cavi di collegamento<br>• Verificare la presenza di errate connessioni o ossidazioni sui moduli<br>• Sostituire i moduli danneggiati                                 |
| Gradini nella curva I-V            | • Piccola o parziale ombreggiatura di un modulo della stringa in misura<br>• Riflessioni<br>• Contaminazione ambientale casual sui moduli (sporcizia, neve, detriti, ecc..)<br>• Rottura di celle o vetro<br>• Parti bruciate       | • Rimuovere le ostruzioni<br>• Ripetere il test dopo aver rimosso le ombreggiature<br>• Rimuovere le riflessioni<br>• Pulire i moduli<br>• Controllare la corrispondenza delle correnti<br>• Sostituire i moduli danneggiati                                           |
| Curva I-V non lineare              | • Irraggiamento instabile durante la misura<br>• Ombreggiatura dei moduli a “macchia di leopardo”<br>• Irraggiamento basso durante la misura | • Ripetere il test in condizione di cielo sereno<br>• Ripetere la misura con irraggiamento minimo di 700W/m² (IEC/EN60891)                                                                                                                                                 |

## 12. ASSISTENZA

### 12.1. CONDIZIONI DI GARANZIA

Questo strumento è garantito contro ogni difetto di materiale e fabbricazione, in conformità con le condizioni generali di vendita. Durante il periodo di garanzia, le parti difettose possono essere sostituite, ma il costruttore si riserva il diritto di riparare ovvero sostituire il prodotto.

Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballo originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente. Il costruttore declina ogni responsabilità per danni causati a persone o oggetti.

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

Se lo strumento non funziona correttamente, prima di contattare il servizio di assistenza, controllare lo stato della batteria e dei cavi e sostituirli se necessario. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballaggio originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente.

**HT ITALIA SRL**
Via della Boaria, 40
48018 – Faenza (RA) – Italy
T +39 0546 621002 | F +39 0546 621144
M ht@ht-instruments.com | www.ht-instruments.it

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
