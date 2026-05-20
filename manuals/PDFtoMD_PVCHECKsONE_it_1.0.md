# PVCHECKsONE

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-32 -->
### INDICE

1.  **PRECAUZIONI E MISURE DI SICUREZZA** (p. 3)
    1.1. Istruzioni preliminari (p. 3)
    1.2. Durante l’utilizzo (p. 4)
    1.3. Dopo l’utilizzo (p. 4)
    1.4. Definizione di categoria di misura (p. 4)
2.  **DESCRIZIONE GENERALE** (p. 5)
    2.1. Introduzione (p. 5)
    2.2. Funzionalità dello strumento (p. 5)
3.  **PREPARAZIONE ALL’UTILIZZO** (p. 6)
    3.1. Controlli iniziali (p. 6)
    3.2. Alimentazione dello strumento (p. 6)
    3.3. Conservazione (p. 6)
4.  **NOMENCLATURA** (p. 7)
    4.1. Descrizione dello strumento (p. 7)
    4.2. Descrizione della tastiera (p. 8)
    4.3. Videata iniziale (p. 8)
5.  **MENU GENERALE** (p. 9)
    5.1. `SET` – impostazione dello strumento (p. 9)
    5.1.1. Lingua (p. 9)
    5.1.2. Data/Ora (p. 10)
    5.1.3. Impostazioni generali (p. 10)
    5.1.4. Irraggiamento & Temperatura (p. 10)
    5.1.5. Informazioni (p. 11)
    5.1.6. Nome operatore (p. 11)
6.  **ISTRUZIONI OPERATIVE** (p. 12)
    6.1. `DMM` – Funzione multimetro (p. 12)
    6.2. `UREM` – Unità remota (p. 13)
    6.3. `RPE` – Misura di Continuità su moduli/stringhe/campi FV (p. 16)
    6.3.1. Calibrazione cavi di misura (p. 16)
    6.3.2. Esecuzione misura di continuità in modo Standard (STD) (p. 18)
    6.3.3. Esecuzione misura di continuità in modo Timer (TMR) (p. 20)
    6.3.4. Situazioni anomale (p. 22)
    6.4. `M ` – Misura di isolamento su moduli/stringhe/campi FV (p. 23)
    6.4.1. Esecuzione misura di Isolamento – Modo `DUAL` (p. 24)
    6.4.2. Esecuzione misura di isolamento – Modo `TMR` (p. 25)
    6.4.3. Situazioni anomale (p. 28)
    6.5. `GFL` – Ricerca guasti su isolamento stringhe FV (p. 30)
    6.6. `OPT` – Misura di isolamento con ottimizzatori di potenza (p. 34)
    6.6.1. Misura di Isolamento con ottimizzatori aventi funzione RSD (p. 35)
    6.6.2. Misura di Isolamento con ottimizzatori senza funzione RSD (p. 37)
    6.6.3. Situazioni anomale (p. 39)
    6.7. `DB` – Gestione database moduli (p. 41)
    6.7.1. Definizione di un nuovo modulo FV (p. 41)
    6.7.2. Modifica di un modulo FV esistente (p. 43)
    6.7.3. Cancellazione di un modulo FV esistente (p. 43)
    6.8. `IVCK` - Test su moduli e stringhe FV (p. 44)
    6.8.1. Introduzione (p. 44)
    6.8.2. Test `IVCK` senza unità remota e senza misura di irraggiamento (p. 46)
    6.8.3. Test `IVCK` senza unità remota e misura di irraggiamento in modo diretto (p. 50)
    6.8.4. Test `IVCK` con unità remota in connessione diretta (p. 54)
    6.8.5. Test `IVCK` con unità remota in registrazione (p. 59)
    6.8.6. Test `IVCK` con uso funzione `Avvia&Salva` (p. 65)
    6.8.7. Interpretazione risultati di misura (p. 68)
    6.8.8. Situazioni anomale (p. 71)
    6.9. Elenco dei messaggi di errore a display (p. 74)
7.  **MEMORIZZAZIONE RISULTATI** (p. 75)
    7.1. Salvataggio delle misure (p. 75)
    7.2. Richiamo a display e cancellazione dati salvati (p. 76)
8.  **COLLEGAMENTO DELLO STRUMENTO A PC** (p. 78)
9.  **MANUTENZIONE** (p. 79)
    9.1. Generalità (p. 79)
    9.2. Sostituzione batterie (p. 79)
    9.3. Pulizia dello strumento (p. 79)
    9.4. Fine vita (p. 79)
10. **SPECIFICHE TECNICHE** (p. 80)
    10.1. Caratteristiche tecniche (p. 80)
    10.2. Caratteristiche generali (p. 82)
    10.3. Condizioni ambientali di utilizzo (p. 83)
    10.4. Accessori (p. 83)
11. **APPENDICE – CENNI TEORICI** (p. 84)
    11.1. Misura Indice di Polarizzazione (PI) (p. 84)
    11.2. Rapporto di Assorbimento Dielettrico (DAR) (p. 84)
    11.3. Funzione `GFL` – Aspetti teorici e riferimenti normativi (p. 85)
    11.4. Funzioni `DUAL` e `TMR` – Approfondimenti tecnici (p. 87)
    11.4.1. Aspetti normativi e teorici della misura di isolamento (p. 87)
    11.5. Caratteristiche generali MLPE (Ottimizzatori e dispositivi RSD) (p. 90)
    11.5.1. Caratteristiche dei dispositivi RSD (p. 90)
    11.5.2. Caratteristiche generali degli ottimizzatori di potenza (p. 90)
    11.5.3. Test `IVCK` o curve I - V su dispositivi MLPE (p. 91)
    11.5.4. Misura di isolamento su dispositivi MLPE (funzione `OPT`) (p. 91)
    11.5.5. Tipologie misure di isolamento con ottimizzatori di potenza (p. 92)
12. **ASSISTENZA** (p. 93)
    12.1. Condizioni di garanzia (p. 93)
    12.2. Assistenza (p. 93)

---

## 1. PRECAUZIONI E MISURE DI SICUREZZA

Lo strumento è stato progettato in conformità alla direttiva IEC/EN61010-1 relativa agli strumenti di misura elettronici. Prima e durante l’esecuzione delle misure attenersi alle seguenti indicazioni e leggere con particolare attenzione tutte le note precedute dal simbolo.

*   Non effettuare misure di tensione o corrente in ambienti umidi
*   Non effettuare misure in presenza di gas o materiali esplosivi, combustibili o in ambienti polverosi
*   Evitare contatti con il circuito in esame se non si stanno effettuando misure
*   Evitare contatti con parti metalliche esposte, con terminali di misura inutilizzati, ecc.
*   Non effettuare alcuna misura qualora si riscontrino anomalie nello strumento come deformazioni, rotture, assenza di visualizzazione sul display, ecc.
*   Prestare particolare attenzione quando si effettuano misure di tensioni superiori a 25V in ambienti particolari e 50V in ambienti ordinari in quanto si è in presenza di rischio di shock elettrici

Nel presente manuale e sullo strumento sono utilizzati i seguenti simboli:

*   **Attenzione:** attenersi alle istruzioni riportate nel manuale; un uso improprio potrebbe causare danni allo strumento o ai suoi componenti
*   Pericolo alta tensione: rischi di shock elettrici
*   Doppio isolamento
*   Tensione o corrente DC
*   Tensione AC
*   Riferimento di terra

### 1.1. ISTRUZIONI PRELIMINARI

*   Lo strumento è stato progettato per essere usato nelle condizioni ambientali specificate al § 10.3. La presenza di condizioni ambientali sensibilmente differenti può compromettere la sicurezza dello strumento e dell’operatore. In ogni caso, prima dell’utilizzo, attendere che le condizioni all’interno dello strumento siano comparabili alle condizioni dell’ambiente in cui esso si trova ad operare
*   Lo strumento può essere utilizzato per misure di **TENSIONE** e **CORRENTE** in CAT III 1000V con tensione massima 1000VDC e 1000V AC tra gli ingressi. Non operare su circuiti che superino i limiti specificati al § 10.1
*   La invitiamo a seguire le normali **regole di sicurezza** orientate alla protezione contro correnti pericolose e proteggere lo strumento contro un utilizzo errato
*   Solo gli accessori forniti a corredo dello strumento garantiscono gli standard di sicurezza. Essi devono essere in buone condizioni e sostituiti, se necessario, con modelli identici
*   Controllare che le batterie siano inserite correttamente
*   Prima di collegare i cavi di misura al circuito in esame, controllare che sia stata selezionata la funzione desiderata

### 1.2. DURANTE L’UTILIZZO

La preghiamo di leggere attentamente le raccomandazioni e le istruzioni seguenti:

> **ATTENZIONE**
>
> *   La mancata osservazione delle avvertenze e/o istruzioni può danneggiare lo strumento e/o i suoi componenti o essere fonte di pericolo per l’operatore
> *   Il simbolo “  “ indica il livello di carica completo delle batterie interne. Quando il livello di carica scende a livelli minimi il simbolo “  “ è mostrato a display. In questo caso interrompere le prove e procedere alla sostituzione delle batterie in accordo a quanto descritto nel § 9.2
> *   In qualunque funzione, anche senza l’attivazione della prova, se lo strumento rileva una tensione >1000V emette un segnale acustico di avviso
> *   Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie

### 1.3. DOPO L’UTILIZZO

Quando le misure sono terminate, spegnere lo strumento mantenendo premuto il tasto `ON/OFF` per alcuni secondi. Se si prevede di non utilizzare lo strumento per un lungo periodo rimuovere le batterie ed attenersi a quanto specificato nel § 3.3.

### 1.4. DEFINIZIONE DI CATEGORIA DI MISURA

La norma "IEC/EN 61010-1: Prescrizioni di sicurezza per apparecchi elettrici di misura, controllo e per utilizzo in laboratorio, Parte 1: Prescrizioni generali", definisce cosa si intenda per categoria di misura, comunemente chiamata categoria di sovratensione. Al § 6.7.4: Circuiti di misura, essa recita:

I circuiti sono suddivisi nelle seguenti categorie di misura:

*   La **Categoria di misura IV** serve per le misure effettuate su una sorgente di un’installazione a bassa tensione
    Esempi sono costituiti da contatori elettrici e da misure sui dispositivi primari di protezione dalle sovracorrenti e sulle unità di regolazione dell’ondulazione
*   La **Categoria di misura III** serve per le misure effettuate in installazioni all’interno di edifici
    Esempi sono costituiti da misure su pannelli di distribuzione, disgiuntori, cablaggi, compresi i cavi, le barre, le scatole di giunzione, gli interruttori, le prese di installazioni fisse e gli apparecchi destinati all’impiego industriale e altre apparecchiature, per esempio i motori fissi con collegamento ad impianto fisso
*   La **Categoria di misura II** serve per le misure effettuate su circuiti collegati direttamente all’installazione a bassa tensione
    Esempi sono costituiti da misure su apparecchiature per uso domestico, utensili portatili ed apparecchi similari
*   La **Categoria di misura I** serve per le misure effettuate su circuiti non collegati direttamente alla RETE DI DISTRIBUZIONE
    Esempi sono costituiti da misure su non derivati dalla RETE e derivati dalla RETE ma con protezione particolare (interna). In quest’ultimo caso le sollecitazioni da transitori sono variabili, per questo motivo (OMISSIS) si richiede che l’utente conosca la **capacità di tenuta ai transitori** dell’apparecchiatura

## 2. DESCRIZIONE GENERALE

### 2.1. INTRODUZIONE

Lo strumento è stato progettato per la realizzazione di **test rapidi di pre-collaudo (IVCK)** su moduli/stringhe fotovoltaici (FV) in accordo alla normativa IEC/EN62446-1.

### 2.2. FUNZIONALITÀ DELLO STRUMENTO

Le seguenti caratteristiche sono disponibili:

**Prova di continuità dei conduttori di protezione (`RPE`)**

*   Test con corrente di prova > 200mA in accordo alle normative IEC/EN62446-1, IEC/EN61557-4
*   Calibrazione manuale dei cavi di misura

**Misura di resistenza di isolamento su moduli/stringhe FV (`M `)**

*   Tensioni di prova 250V, 500V, 1000V DC in accordo alle IEC/EN62446-1, IEC/EN61557-2
*   2 modalità di misura disponibili
    *   **DUAL** → misura in sequenza dell’isolamento fra polo positivo della stringa (+) e PE e tra polo negativo della stringa e PE
    *   **TMR** → misura singola temporizzata fra polo negativo della stringa e PE

**Funzione `GFL` (Ground Fault Locator)** per ricerca posizione di basso isolamento tra i moduli di una stringa FV (vedere § 6.5)

**Funzione `OPT` (Optimizer)** per misura resistenza di isolamento su moduli/stringhe FV in presenza di Ottimizzatori (vedere § 6.6)

**Misure di Tensione a vuoto e Corrente di corto circuito su moduli/stringhe FV Monofacciali o Bifacciali in accordo alle normative IEC/EN62446-1 e IEC/EN60891 (`IVCK`)**

*   Misura di tensione a vuoto Voc su moduli/stringhe FV Monofacciali e Bifacciali fino a 1000VDC con o senza irraggiamento
*   Misura di corrente di cortocircuito Isc su moduli/stringhe FV Monofacciali e Bifacciali fino a 30A con o senza irraggiamento
*   Moduli Monofacciali → Misura irraggiamento frontale tramite collegamento diretto della cella di riferimento HT305
*   Moduli Bifacciali → Misura irraggiamento frontale e posteriore tramite collegamento con unità remota `SOLAR03` e celle di riferimento HT305
*   Misura temperatura dei moduli in accordo alla norma IEC/EN60904-5 (modo Auto) oppure tramite sonda PT305 (connessa all’ingresso `TEMP` dello strumento o all’unità remota `SOLAR03`)
*   Visualizzazione risultati in condizioni OPC e STC
*   Valutazione immediata (OK/NO) dei risultati ottenuti
*   Esecuzione test `IVCK` in sequenza con funzione `Avvia&Salva`

Lo strumento dispone inoltre di un Database interno in grado di memorizzare fino a 64 moduli FV (da caricare a cura dell’utente), della funzione di retroilluminazione del display, la possibilità di regolazione interna del contrasto e un tasto `HELP` in grado di fornire a display un aiuto all’operatore nella fase di collegamento dello strumento all’impianto. Una funzione di autospegnimento, eventualmente disattivabile, è disponibile dopo circa 5 minuti di non utilizzo dello strumento.

## 3. PREPARAZIONE ALL’UTILIZZO

### 3.1. CONTROLLI INIZIALI

Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili affinché lo strumento potesse essere consegnato senza danni. Tuttavia, si consiglia di controllarlo per accertare eventuali danni subiti durante il trasporto. Qualora si dovessero riscontrare anomalie contattare immediatamente il rivenditore. Si consiglia inoltre di controllare che l’imballaggio contenga tutte le parti indicate al § 10.4. In caso di discrepanze contattare il rivenditore. Qualora fosse necessario restituire lo strumento si prega di seguire le istruzioni riportate al § 12.

### 3.2. ALIMENTAZIONE DELLO STRUMENTO

Lo strumento è alimentato tramite 6x1.5V batterie alcaline tipo AA LR06 o 6x1.2V batterie ricaricabili NiMH tipo AA. Il simbolo “  ” indica il livello di carica delle batterie. Per la sostituzione delle batterie vedere il § 9.2.
Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie.
Lo strumento dispone di sofisticati algoritmi per aumentare al massimo l'autonomia delle batterie. Una pressione prolungata del tasto `HELP/` attiva la retroilluminazione del display. L'utilizzo sistematico della retroilluminazione diminuisce l'autonomia delle batterie.

### 3.3. CONSERVAZIONE

Lo strumento è stato progettato per essere usato nelle condizioni ambientali specificate al § 10.3. La presenza di condizioni ambientali sensibilmente differenti può compromettere la sicurezza dello strumento e dell’operatore e/o non garantire misure precise. Dopo un lungo periodo di conservazione e/o in condizioni ambientali estreme, prima dell’utilizzo, attendere che le condizioni all’interno dello strumento siano comparabili alle condizioni dell’ambiente in cui esso si trova ad operare.

## 4. NOMENCLATURA

### 4.1. DESCRIZIONE DELLO STRUMENTO

LEGENDA:
1.  Ingressi
2.  Display LCD
3.  Tasti ``, ``, ``, ``, `SAVE/ENTER`
4.  Vano connettore cavo ottico/USB
5.  Tasti `GO/STOP`
6.  Tasto `HELP/`
7.  Tasto `ESC/MENU`
8.  Tasto `ON/OFF`

Fig. 1: Descrizione parte frontale dello strumento

LEGENDA:
1.  Ingressi `P`, `N` per misura tensione DC (`IVCK`) / Isolamento (`M `)
2.  Ingressi `E`, `C` per test continuità (`RPE`)
3.  Ingresso `TEMP` per misura temperatura modulo con sonda PT305
4.  Ingresso `IRR` per misura irraggiamento con cella HT305

Fig. 2: Descrizione parte superiore dello strumento

LEGENDA:
1.  Connettore per collegamento cavo di uscita optoisolata ottico/USB

Fig. 3: Descrizione parte laterale dello strumento

### 4.2. DESCRIZIONE DELLA TASTIERA

La tastiera è costituita dai seguenti tasti:

*   Tasto `ON/OFF` per accendere e spegnere lo strumento
*   Tasto `ESC` per uscire dal menu selezionato senza confermare le modifiche
*   Tasto `MENU` per tornare al menu generale dello strumento in ogni momento
*   Tasti `` `` `` `` per spostare il cursore all’interno delle varie schermate allo scopo di selezionare i parametri di programmazione
*   Tasto `SAVE/ENTER` per il salvataggio dei parametri interni e i risultati delle misure (`SAVE`) e per selezionare le funzioni desiderate dal menu (`ENTER`)
*   Tasto `GO` per avviare la misurazione
*   Tasto `STOP` per terminare la misurazione
*   Tasto `HELP` per accedere all’help on line visualizzando, per ciascuna funzione selezionata, le possibili connessioni tra strumento ed impianto
*   Tasto ` ` (pressione continua) per la regolazione della retroilluminazione

### 4.3. VIDEATA INIZIALE

All’accensione dello strumento viene visualizzata per qualche secondo la videata iniziale. In essa sono visualizzati:

*   Il modello dello strumento (`PVCHECKs-ONE`)
*   Il costruttore
*   Il numero di serie dello strumento (SN:)
*   La versione dell’hardware (HW) e del firmware (FW) delle due schede presenti nella memoria dello strumento
*   La data in cui è avvenuta l’ultima calibrazione dello strumento (Data calibrazione:)

```
P V C H E C K s   -   O N E
H T   I T A L I A
S N :   2   6   0   6   0 0 0 2
F W CPU : 1. 0 0   FWMIS: 1.00
H W CPU :   0 0   HWMIS: 00
Data   C alibra zione :
14 / 03 /20 2 6
```

Dopo alcuni istanti lo strumento passa all'ultima funzione selezionata.

## 5. MENU GENERALE

La pressione del tasto `ESC`, in qualunque condizione si trovi lo strumento, consente di tornare al menu generale da cui è possibile impostare i parametri interni e selezionare la misura desiderata. Selezionando con il cursore una delle opzioni e confermando con `ENTER` si accede alla funzione desiderata.

```
MENU   15/03   –   18:04
D M M   :   M u l t i m e t r o
U R E M   :   U n i t à   R e m o t   a
I V C K   :   S e q u e n z a   T e s t   F V
O P T   :   O t t i m i z z a t o r e
M      :   I s o l a m e n t o
G F L   :   A n a l . g u a s t i   I S O
R P E   :   C o n t i n u i t à

```

```
MENU   15/03   –   18:04
D B   :   D a t a B a s e   M o d .   F V
S E T   :   I m p o s t a z i o n i
M E M   :   D a t i   s a l v a t i
P C   :   T r a s f e r .   d a t i

```

### 5.1. `SET` – IMPOSTAZIONE DELLO STRUMENTO

Spostare il cursore su `SET` usando i tasti freccia (``, ``) e confermare con `ENTER`. Lo strumento mostra la videata che permette l’accesso alle impostazioni interne. Le impostazioni vengono mantenute anche dopo lo spegnimento dello strumento.

```
S E T   15/10   –   18:04
L i n g u a
D a t a   /   O r a
I m p o s t . g   e n e r a l i
I r r a g .   &   T e m p e r a t u r a
I n f o   r m a z i o n i
N o m e   o   p e r a t o r e
```

#### 5.1.1. Lingua

Spostare il cursore su `Lingua` usando i tasti freccia (``, ``) e confermare con `ENTER`. Lo strumento mostra la videata che permette l’impostazione della lingua di sistema. Selezionare l’opzione desiderata usando i tasti freccia (``, ``). Premere il tasto `ENTER` per confermare o il tasto `ESC` per tornare alla videata precedente.

```
S E T   15/10   –   18:04
E n g l i s h
I t a l i a n o
E s p a ñ o l
D e u t s c h
F r a n ç a i s
P o r t u g u   e s e
```

#### 5.1.2. Data / Ora

Spostare il cursore su `Data / Ora` usando i tasti freccia (``, ``) e confermare con `ENTER`. Successivamente la videata a lato è mostrata a display in modo da impostare la data/ora di sistema. Selezionare il campo “Formato” per impostare il sistema Europeo (formato “DD/MM/YY, hh:mm” `EU`) oppure Americano (formato “MM/DD/YY hh:mm” `USA`). Selezionare l’opzione desiderata usando i tasti freccia (``, ``) e (``, ``). Premere il tasto `ENTER` per confermare o il tasto `ESC` per tornare alla videata precedente.

```
S E T   15/10   –   18:04
For ma t o   :      EU   
A nn o   :      19   
Mes e   :      10   
Giorn o   :      14   
Ora   :      17   
M in ut o   :      38   
```

#### 5.1.3. Impostazioni generali

Spostare il cursore su `Impost. general i` usando i tasti freccia (``, ``) e confermare con `ENTER`. Lo strumento mostra la videata in cui è possibile abilitare/disabilitare l’auto power off, il suono associato alla pressione dei tasti, il contrasto del display e abilitare/disabilitare il collegamento WiFi (vedere § 8). Selezionare l’opzione desiderata usando i tasti freccia (``, ``). Premere il tasto `ENTER` per confermare o il tasto `ESC` per tornare alla videata precedente.

```
S E T   15/10   –   18:04
A ut o Po w erOf f   :      OFF   
S uo n o   t as t i   :      OFF   
Co ntr as to   :      5 0   
W iF i   :      OFF   
```

#### 5.1.4. Irraggiamento & Temperatura

Questa sezione consente l’impostazione del tipo di misura e della soglia minima di irraggiamento per la misura `IVCK` (vedere § 6.8).

1.  Posizionare il cursore sulla voce “`Irrag. & Temperatura`” utilizzando i tasti freccia (``, ``) e confermare con `ENTER`.
2.  La voce “`Irr. & Temp.`” permette la selezione delle seguenti opzioni:
    *   `OFF` → il test `IVCK` è eseguito senza considerare alcun valore di irraggiamento né con collegamento diretto allo strumento della cella HT305, né con collegamento della cella HT305 all’unità remota `SOLAR03`
    *   `Diretta` → il test `IVCK` è eseguito con misura di irraggiamento collegando la cella HT305 direttamente all’ingresso “`IRR`” (vedere Fig. 2 – parte 4) dello strumento. In tal caso il numero di serie della cella HT305 collegata e riconosciuta è mostrato. Se la cella non è collegata o riconosciuta il simbolo “---“ è mostrato a display. E’ inoltre abilitato l’ingresso `TEMP` per la misura della temperatura del modulo (impostabile anche nelle altre modalità previste: AUTO, MAN)
    *   `U . Rem .` → il test `IVCK` è eseguito con misura di irraggiamento con cella/celle HT305 collegata/e all’unità remota `SOLAR03`

> **ATTENZIONE**
> La misura “`Diretta`” è valida **SOLO** per moduli Monofacciali

```
S E T   15/10   –   18:04
Irr. & Temp.   :    Diretta   
Irrag.Min [W/m2]   :    700   
HT305 SN   : 25020000
D a t i   s   a l v a t i
```

3.  Posizionare il cursore sulla voce “`Irrag.Min [W/m2]`”, utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata con la voce che consente l’impostazione della soglia minima di irraggiamento espressa in W/m^2^, utilizzata come riferimento nella misura `IVCK`. Per l’impostazione della soglia minima di irraggiamento usare i tasti freccia (``, ``). Il valore è impostabile nel campo `100  1000 W/m2` in passi di `10 W/m2`.

> **ATTENZIONE**
> La voce “`Unità Remota`” nel menu generale è presente **solo** con opzione “`U . Rem .`” selezionata

4.  Premere il tasto `SAVE` per salvare le impostazioni effettuate e il messaggio “Dati Salvati” sarà mostrato per un istante. Premere il tasto `ESC/MENU` per uscire senza salvare e tornare alla videata precedente.

#### 5.1.5. Informazioni

Spostare il cursore su `Info` usando i tasti freccia (``, ``) e confermare con `ENTER`. Lo strumento mostra la videata iniziale come indicato nella videata a lato. Premere il tasto `ESC` per tornare al menu principale.

```
15/10   –   18:04
P V C H E C K s   -   O N E
HT ITALIA
SN: 2 6 0 6 0002
F W CPU : 1. 0 0   FWMIS: 1.00
H W CPU : 0 0   HWMIS: 00
Data calibrazione:
14/ 0 3 /202 6
```

#### 5.1.6. Nome operatore

Questa opzione consente di includere il nome dell’operatore che esegue le misure con lo strumento (max 12 caratteri). Tale nome sarà incluso nei report creati con uso del software di gestione.

1.  Usare i tasti freccia `` o `` per spostare il cursore sul carattere selezionare e premere il tasto `SAVE/ENTER` per l’inserimento.
2.  Muovere il cursore nella posizione “`CANC`” e premere il tasto `SAVE/ENTER` per cancellare il carattere selezionato.
3.  Muovere il cursore nella posizione “`OK`” e premere il tasto `SAVE/ENTER` per confermare il nome scritto e tornare alla videata precedente.

```
SAVE   15/10   –   18:04
T a s t i e r a
O P E R A T O R E _
0   1   2   3   4   5   6   7   8   9   0   (   )   %
Q   W   E   R   T   Y   U   I   O   P   < = >   #
A   S   D   F   G   H   J   K   L   +   -   *   /   &
Z   X   C   V   B   N   M   .   ,   ;   :   !   ?   _
Ä Ö Ü ß μ Ñ Ç Á Í Ó Ú Ü ¿ ¡
Á È É Ù Ç Ä Ë Ï Ö Ü Æ Ø Å
CANC   OK
```

## 6. ISTRUZIONI OPERATIVE

### 6.1. `DMM` – FUNZIONE MULTIMETRO

In questa funzione lo strumento mostra i valori delle tensioni RMS (efficaci) e DC tra il polo positivo (+) e il polo (-), tra il polo positivo (+) e il riferimento di terra (PE) e tra il polo negativo (-) e il riferimento di terra (PE) allo scopo di verificare la presenza di componenti AC sulle tensioni di ingresso.

1.  Posizionare il cursore sulla voce `DMM` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a lato.

```
D M M   15/10   –   18:04
V P N r m s   0   V
V P E r m s   0   V
V N E r m s   0   V
V P N d c   0   V
V P E d c   0   V
V N E d c   0   V
```

2.  Collegare lo strumento alla stringa FV in prova come mostrato nella Fig. 4.
    Fig. 4: Collegamento strumento nella funzione DMM
3.  I valori delle tensioni sono mostrati a display come mostrato nella videata a lato.

```
D M M   15/10   –   18:04
V P N r m s   9   8 0   V
V P E r m s   4 9   0   V
V N E r m s   7 4 8   V
V P N d c   9 8   0   V
V P E d c   4 9   0   V
V N E d c   -   4 9 0   V
```

> **ATTENZIONE**
> I risultati della funzione `DMM` non sono salvabili nella memoria dello strumento

### 6.2. `UREM` – UNITÀ REMOTA

L’unità remota `SOLAR03` consente di eseguire la misura dei valori di Irraggiamento e Temperatura del modulo, grandezze indispensabile per la valutazione delle misure `IVCK` (Voc, Isc) con valori riferiti @STC. In generale lo strumento e il `SOLAR03` possono operare in **connessione diretta** oppure in **registrazione**.

> **ATTENZIONE**
>
> *   La distanza massima di connessione diretta fra `SOLAR03` e strumento può variare in funzione degli ostacoli interposti fra le due unità e può essere fino a 100m in spazio libero.
> *   La distanza massima per la connessione diretta è **indicativa** in quanto fortemente influenzata da molte variabili esterne non controllabili. Il modo di misura **raccomandato** è sempre quello della “**registrazione**” (vedere § 6.8.5) che non necessita di collegamento Bluetooth attivo durante le misure e, indipendentemente dagli ostacoli presenti e dall’estensione del campo da misurare, garantisce una **misura affidabile** in ogni situazione.

Questa sezione gestisce tutte le operazioni eseguibili dall’unità remota `SOLAR03` utilizzabile durante le misure di tipo `IVCK`. In particolare, è possibile:

*   Eseguire la **ricerca**, tramite collegamento **Bluetooth**, di una unità remota `SOLAR03` che può essere gestita dallo strumento, inserendola nella propria lista interna (max 5 unità remote).

> **ATTENZIONE**
> La distanza massima indicativa di comunicazione tramite Bluetooth (fino a 100m) è riferita ad un campo aperto, ambiente secco, a 1m da terra, in assenza di ostacoli e possibili disturbi elettromagnetici derivanti da altre fonti in prossimità degli strumenti.

*   **Selezionare o cancellare** una unità remota `SOLAR03` tra quelle presenti in lista.
*   **Associare** una unità remota `SOLAR03` allo strumento in modo da poterla riconoscere automaticamente ad ogni collegamento.
*   **Visualizzare le informazioni** dell’unità remota selezionata.
*   **Attivare** e **terminare** la registrazione dei parametri ambientali (irraggiamento/temperatura) su una unità remota attiva e connessa (vedere § 6.8.5).

In particolare, per ogni unità remota `SOLAR03` gestita, lo strumento fornisce:

*   Numero di serie
*   Voce “`Att`” → unità remota attiva (simbolo “√”) o non attiva (nessun simbolo)
*   Voce “`Stato`” → unità remota attiva connessa (simbolo “ ”) o attiva non connessa (simbolo “ ”)
*   Voce “`Rec`” → unità attiva e connessa in fase di registrazione (simbolo “ ”)

Per associare allo strumento una **nuova** unità remota `SOLAR03` procedere come segue:

1.  Posizionare il cursore sulla voce `U REM` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`.
2.  Usare i tasti freccia `` o `` selezionando la posizione “`Cerca`” per iniziare la ricerca di una unità remota `SOLAR03`. Il messaggio “`Attendere…`” è mostrato a display.

```
U R E M   15/10   –   18:04
SOLAR03   At i   Stato   Re g
A t t e n d e r e …
Cerca   Ass .   Info   Avvio
```

3.  Lo strumento **attiva il collegamento Bluetooth** e presenta la videata a fianco per alcuni secondi cercando una unità remota `SOLAR03`.

```
U R E M   15/10   –   18:04
SOLAR03   Att   Stato   Re g
S O L A R 0 3   S N :   -   -   -
T r o v a   U n i t à   R e m o t a
```

4.  Attivare sull’unità remota `SOLAR03` il comando “`Accoppiamento`“ (vedere manuale d’uso dell’unità remota `SOLAR03`) in modo che possa essere riconosciuta dallo strumento. A operazione avvenuta, il numero di serie dell’unità remota e il messaggio “`Rilevata unità remota . Associare? (ENTER/ESC)`“ sono mostrato a display come indicato nella videata a lato.

```
U R E M   15/10   –   18:04
SOLAR03   Att   Stato   Re g
S O L A R 0 3   S N :   2 3 0 5 1 2 0 3
R i l e v a t a   U n i t à   R e m o t a
A s s o c i a r e ?   ( E N T E R / E S C )
```

5.  Confermare con `ENTER` sullo strumento e sull’unità remota `SOLAR03` per associarla ad esso. Da questo momento entrambi i dispositivi sono associati e non sarà necessario ripetere nuovamente le operazioni. Per connettere strumento e unità remota sarà sufficiente accenderle, avvicinarle ed attendere il reciproco riconoscimento.

```
U R E M   15/10   –   18:04
SOLAR03   Att   Stato   Re g
23051203   √
U . R e m .   c o l l e g a t a
Cerca   Disass.   Info   Avvio
```

6.  Per avviare una registrazione sull’unità remota attiva e connessa usare i tasti freccia `` o `` selezionando la posizione “`Avvio`”. Il simbolo “ ” sarà conseguentemente visualizzato.

```
U R E M   15/10   –   18:04
SOLAR03   Att   Stato   Re g
23051203   √
U . R e m .   c o l l e g a t a
Cerca   Disass.   Info   Avvio
```

Nel caso in cui lo strumento fosse stato precedentemente associato a due o più unità remote, per passare da una unità all’altra:

7.  Usare i tasti freccia `` o `` selezionando la posizione “`Disass.`” e confermare con `ENTER` per disassociare l’unità remota corrente. Per eseguire questa operazione non è necessario che l’unità correntemente associata sia anche connessa allo strumento.
8.  Utilizzando i tasti freccia (``, ``) selezionare la nuova unità remota. La nuova unità deve essere accesa e posta a distanza di connessione rispetto allo strumento.
9.  Usare i tasti freccia `` o `` selezionando la posizione “`Ass.`” e confermare con `ENTER` per collegare l’unità remota allo strumento.
10. L’unità precedentemente disassociata può essere definitivamente cancellata dalla lista tramite “`Canc`”.

```
U R E M   15/10   –   18:04
SOLAR03   Att   Stato   Re g
23051203   √
23061215
U . R e m .   c o l l e g a t a
Cerca   Disass.   Info   Avvio
```

11. Usare i tasti freccia `` o `` selezionando la posizione “`Info`” per la visualizzazione delle seguenti informazioni sull’unità remota `SOLAR03` evidenziata:
    *   Modello
    *   Numero di serie
    *   Versione interna di FW e HW
    *   Stato possibile registrazione in corso
    *   Memoria residua disponibile per registrazioni
    *   Stato batteria interna

```
U R E M   15/10   –   18:04
U n i t à   R   e m o t a
S O L A R 0 3
HT ITALIA
S N :   2 3 0 5 1 2 0 3
H W :   1 . 0 2
F W :   1 . 0   2
S t a t o :   N   o   r   e   g i s t r a z .   .
M e m   l i b e r a :   0 g ,   2 h
B a t t e r i a :   5 3 %
```

### 6.3. `RPE` – MISURA DI CONTINUITÀ SU MODULI/STRINGHE/CAMPI FV

Lo scopo di questa misura è l’esecuzione del test di continuità dei conduttori di protezione ed equipotenziali (ex: dal dispersore fino alle masse e masse estranee collegate) e dei conduttori di messa a terra degli SPD sulle installazioni FV. Il test deve essere condotto usando una corrente di prova > 200mA in accordo alle prescrizioni delle normative IEC/EN62446-1 e IEC/EN61557-4.

> **ATTENZIONE**
> Si raccomanda una verifica preliminare di corretto funzionamento dello strumento prima di eseguire una misura mettendo terminali di ingresso `E` e `C` in cortocircuito verificando un valore di continuità pressoché nullo e un valore fuori scala con terminali `E` e `C` aperti.

#### 6.3.1. Calibrazione cavi di misura

1.  Posizionare il cursore sulla voce `RPE` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata seguente:

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
STD   2.00    -   -   -   
MODO   Lim.   >  <
```

2.  Connettere i cavi di misura tra di loro come mostrato in Fig. 5.
    Fig. 5: Compensazione della resistenza dei cavi di misura
3.  Usare i tasti freccia `` o `` selezionando la posizione “`>  <`”. A display appare la videata a lato.

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
STD   2.00    -   -   -   
MODO   Lim.   >  <
```

4.  Premere il tasto `GO/STOP` per attivare la calibrazione. I messaggi “`Misura…`” seguito da “`Verifica`” e da “`Azzeramento`” sono mostrati in sequenza a display.

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
Misura…
STD   2.00    -   -   -   
MODO   Lim.   >  <
```

5.  Al termine della procedura di compensazione, nel caso in cui il valore della resistenza misurata risulti `≤5 `, lo strumento emette un **doppio segnale acustico** a segnalare l’esito **positivo** della prova e visualizza il valore della resistenza compensata dei cavi, che sarà sottratto a tutte le successive misure di continuità, nella parte bassa destra del display.

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
STD   2.00    0.06   
MODO   Lim.   >  <
```

#### 6.3.2. Esecuzione misura di continuità in modo Standard (STD)

1.  Posizionare il cursore sulla voce `RPE` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata seguente. Il simbolo “`STD`” è presente a display.

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
STD   2.00    -   -   -   
MODO   Lim.   >  <
```

2.  Usare i tasti freccia `` o `` selezionando la posizione “`Lim.`”. A display appare la videata a lato.
3.  Utilizzando i tasti freccia (``, ``) impostare la soglia limite di riferimento per la misura di continuità selezionabile nel campo `0.01   9.99 ` in passi da `0.01 ` (si ricorda che la normativa IEC/EN62446-1 non fissa un valore limite di resistenza e valori tipici sono di circa `1 ` o `2 `).

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
STD   2.00    -   -   -   
MODO   Lim.   >  <
```

4.  Eseguire la calibrazione iniziale dei cavi di misura (vedere § 6.3.1).
5.  Collegare lo strumento al modulo/stringa FV in prova e al nodo principale di terra dell’impianto come mostrato in Fig. 6.
    Fig. 6: Collegamento strumento per misura di continuità su strutture dell’impianto FV

> **ATTENZIONE**
> Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere § 6.3.4) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test.

6.  Premere il tasto `GO/STOP` per attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura…`” come mostrato nella videata a lato.

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
Misura…
STD   2.00    0.06   
MODO   Lim.   >  <
```

7.  Al termine della misura lo strumento fornisce il valore della resistenza dell’oggetto in prova. Se il risultato è inferiore al limite massimo impostato lo strumento visualizza il messaggio “`OK`” (valore minore o uguale della soglia limite impostata) altrimenti visualizza il messaggio “`NO OK`” (valore maggiore della soglia limite impostata) come mostrato nella videata a lato.
8.  Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il § 7.1) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura.

```
R P E   15/10   –   18:04
R   0 . 2 3   
I t e s t   2 1 0   m A
OK
STD   2.00    0.06   
MODO   Lim.   >  <
```

#### 6.3.3. Esecuzione misura di continuità in modo Timer (TMR)

1.  Posizionare il cursore sulla voce `RPE` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata seguente.
2.  Usare i tasti freccia (``, ``) per selezionare il modo Timer. Il simbolo “`TMR`” è presente a display.

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
T   -   -   -   s
TMR   2.00    12s   -   -   -   
MODO   Lim.   Tempo   >  <
```

3.  Usare i tasti freccia `` o `` selezionando la posizione “`Lim.`”. A display appare la videata a lato.
4.  Utilizzando i tasti freccia (``, ``) impostare la soglia limite di riferimento per la misura di continuità selezionabile nel campo `0.01   9.99 ` in passi da `0.01 ` (si ricorda che la normativa IEC/EN62446-1 non fissa un valore limite di resistenza e valori tipici sono di circa `1 ` o `2 `).

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
T   -   -   -   s
TMR   2.00    12s   -   -   -   
MODO   Lim.   Tempo   >  <
```

5.  Usare i tasti freccia `` o `` selezionando la posizione “`Tempo.`”. A display appare la videata a lato.
6.  Utilizzando i tasti freccia (``, ``) impostare la durata della misura (Timer) di continuità selezionabile nel campo `3s ÷ 99s` in passi da `3s`.

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
T   -   -   -   s
TMR   2.00    12s   -   -   -   
MODO   Lim.   Tempo   >  <
```

7.  Eseguire la calibrazione iniziale dei cavi di misura (vedere § 6.3.1).
8.  Collegare lo strumento al modulo/stringa FV in prova e al nodo principale di terra dell’impianto come mostrato in Fig. 6.

> **ATTENZIONE**
> Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere § 6.3.4) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test.

9.  Premere il tasto `GO/STOP` per attivare il test. In caso di assenza di condizioni di errore, lo strumento inizia una serie di misure continue per l’intera durata del Timer impostato fornendo un breve suono ogni `3s` alternando i messaggi “`Misura…`” e “`Attendere prego…`” come mostrato nella videata a lato. In questo modo è possibile per l’operatore spostarsi da un punto all’altro del luogo in cui si sta eseguendo la misura. Durante il messaggio “`Attendere prego`” è possibile spostarsi da un punto ad un altro.

```
R P E   15/10   –   18:04
R   0 . 2 3   
I t e s t   2 0 9   m A
T   1 1   S
Attendere prego…
TMR   2.00    12s   0.06   
MODO   Lim.   Tempo   >  <
```

10. Al termine della misura lo strumento fornisce il massimo valore tra tutti quelli delle misure parziali eseguite. Se il risultato è inferiore al limite massimo impostato lo strumento visualizza il messaggio “`OK`” (valore minore o uguale della soglia limite impostata) altrimenti visualizza il messaggio “`NO OK`” (valore maggiore della soglia limite impostata) come mostrato nella videata a lato.
11. Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il § 7.1) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura.

```
R P E   15/10   –   18:04
R   0 . 5 4   
I t e s t   2 0 9   m A
T   0   S
OK
TMR   2.00    12s   0.06   
MODO   Lim.   Tempo   >  <
```

#### 6.3.4. Situazioni anomale

1.  Per azzerare il valore della resistenza compensata effettuare una nuova procedura di compensazione con una resistenza superiore a `5 ` come, ad esempio, a puntali aperti. Il messaggio “`Zero reset`” appare a display.

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
Zer o   r   es et
STD   2.00    -   -   -   
MODO   Lim.   >  <
```

2.  Qualora lo strumento rilevi ai propri terminali `E` e `C` una tensione superiore a `3V` non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`V.Ingresso > 3V`”.

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
V. I n gr ess o   > 3 V
STD   2.00    -   -   -   
MODO   Lim.   >  <
```

3.  Qualora venga rilevato che la resistenza calibrata sia più elevata della resistenza misurata lo strumento emette un segnale acustico prolungato e visualizza il messaggio: “`Azzeramento NO OK`”.

```
R P E   15/10   –   18:04
R   0 . 0 3   
I t e s t   2 1 2   m A
Azz era m e nt o NO O K
STD   2.00    0.220   
MODO   Lim.   >  <
```

4.  Qualora lo strumento rilevi ai propri terminali una resistenza superiore a `5 ` emette un segnale acustico prolungato, azzera il valore compensato e visualizza il messaggio “`Zero reset`”.

```
R P E   15/10   –   18:04
R   > 4 . 9 9   
I t e s t   4 9   m A
Zer o   r   es et
STD   2.00    -   -   -   
MODO   Lim.   >  <
```

5.  Qualora venga rilevato che la resistenza calibrata sia più elevata della resistenza misurata (ad esempio per uso di cavi diversi da quelli in dotazione), lo strumento emette un segnale acustico prolungato e visualizza una videata come quella a fianco. Eseguire un reset e operare una nuova compensazione dei cavi.

```
R P E   15/10   –   18:04
R   -   -   -   
I t e s t   -   -   -   m A
Rca l > Rm   i s
STD   2.00    -   -   -   
MODO   Lim.   >  <
```

### 6.4. `M ` – MISURA DI ISOLAMENTO SU MODULI/STRINGHE/CAMPI FV

Lo scopo di questa misura è l’esecuzione delle misure di resistenza di isolamento dei conduttori attivi di moduli, stringe e campi FV in accordo alle prescrizioni delle normative IEC/EN62446-1 e IEC/EN61557-2 senza la necessità di usare un interruttore esterno per cortocircuitare i terminali positivo e negativo (vedere § 11.4).

> **ATTENZIONE**
>
> *   **NON** usare questa funzione per eseguire misure di isolamento su stringhe o moduli fotovoltaici che integrano dispositivi MLPE (microinverter, ottimizzatori di potenza o dispositivi di spegnimento rapido – RSD). L’esecuzione di prove di isolamento su tali configurazioni può comportare il danneggiamento sia dei dispositivi MLPE sia dello strumento. Fare riferimento al modo “`OPT`” (vedere § 6.6) per la gestione di tali situazioni.
> *   Non toccare le masse dei moduli durante la misura in quanto potrebbero trovarsi a potenziale pericoloso anche ad impianto sezionato per effetto della tensione generata dallo strumento.
> *   La misura potrebbe dare risultati non corretti se il riferimento di terra non è collegato correttamente all’ingresso `E`.
> *   Si raccomanda una verifica preliminare di corretto funzionamento dello strumento prima di eseguire una misura, impostando la funzione `TMR` mettendo i terminali `N` ed `E` in cortocircuito verificando un valore di isolamento pressoché nullo e un valore fuori scala con terminali `N` ed `E` aperti.

> **ATTENZIONE**
>
> *   La misura di isolamento è eseguibile su un singolo modulo, su una stringa o su un impianto costituito da più stringhe connesse in parallelo.
> *   Sezionare la stringa/impianto dall’inverter e da eventuali scaricatori.
> *   Se il modulo/stringa/l’impianto ha un polo connesso a Terra, tale connessione va temporaneamente sezionata.
> *   La normativa IEC/EN62446-1 fissa `1M ` come valore limite minimo di resistenza di isolamento per impianti con tensione nominale superiore a `120V`.
> *   È consigliabile eseguire la misura di isolamento direttamente sul modulo/stringa/campo a monte di eventuali diodi di blocco.

Lo strumento esegue la misura di isolamento nei seguenti modi:

*   Modo **DUAL** → lo strumento esegue la misura di isolamento in sequenza tra il polo positivo (+) e il riferimento PE e tra il polo negativo (-) e il riferimento PE di moduli, stringhe o campi FV e calcola la resistenza complessiva del parallelo **Rp**.
*   Modo **TMR** → lo strumento esegue la misura in modo continuo (con durata max `999s`) tra il terminale “`N`” e il riferimento PE visualizzando il valore minimo ottenuto della resistenza parallelo tra il polo (+) e il polo (-) di stringhe/moduli oppure una generica resistenza di isolamento di cavi non in tensione al termine del periodo di tempo selezionato. Lo strumento esegue in questo modo anche il calcolo dei parametri `DAR` (Rapporto di Assorbimento Dielettrico) e `PI` (Indice di Polarizzazione) se la durata della prova è adeguata al calcolo dei suddetti parametri.

#### 6.4.1. Esecuzione misura di Isolamento – Modo `DUAL`

1.  Posizionare il cursore sulla voce `M ` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a lato. Utilizzando ancora i tasti freccia (``, ``) selezionare il modo di misura “`DUAL`” in corrispondenza della posizione “`MODE`”.

```
M      15/10   –   18:04
( + )   (   -   )
V t e s t   -   -   -   -   -   -   V
R i s o   -   -   -   -   -   -   M   
R p   -   -   -   M   
V P N   V P E   V N E
0 V   0 V   0 V
DUAL   1 0 00V   1.00M 
MODO   Vtest.   Lim.
```

2.  Usare i tasti freccia `` o `` selezionando la posizione “`Vtest`” per impostare la tensione di prova.
3.  Usare i tasti freccia (``, ``) per selezionare una delle seguenti tensioni di prova (`Vnom`): `250`, `500`, `1000` V DC. Si ricorda che in accordo alla IEC/EN62446-1 la tensione di prova `Vtest` deve essere `≥` tensione nominale dell’impianto.

```
M      15/10   –   18:04
( + )   (   -   )
V t e s t   -   -   -   -   -   -   V
R i s o   -   -   -   -   -   -   M   
R p   -   -   -   M   
V P N   V P E   V N E
0 V   0 V   0 V
DUAL   1 0 00V   1.00M 
MODO   Vtest.   Lim.
```

4.  Usare i tasti freccia `` o `` selezionando la posizione “`Lim.`”. A display appare la videata a lato.
5.  Utilizzando i tasti freccia (``, ``) impostare la soglia limite minima di riferimento per la misura di isolamento selezionabile tra i valori `0.05, 0.10, 0.23, 0.25, 0.50, 1.00, 50M `. Si ricorda che la normativa IEC/EN62446-1 fissa un valore limite minimo di resistenza di isolamento pari a `1M ` per impianti con tensione nominale superiore a `120V`.

```
M      15/10   –   18:04
( + )   (   -   )
V t e s t   -   -   -   -   -   -   V
R i s o   -   -   -   -   -   -   M   
R p   -   -   -   M   
V P N   V P E   V N E
0 V   0 V   0 V
DUAL   1 0 00V   1.00M 
MODO   Vtest.   Lim.
```

6.  Collegare lo strumento alla stringa FV in prova come mostrato in Fig. 7. La prova può essere eseguita anche su più stringhe in parallelo fra loro. Si ricorda che occorre sezionare anche eventuali scaricatori connessi ai cavi della stringa/stringhe e che è consigliabile eseguire la misura a monte di eventuali diodi di blocco.
    Fig. 7: Collegamento strumento per misura di isolamento in modo DUAL

> **ATTENZIONE**
> Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere § 6.4.3) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test.

7.  Premere e tenere premuto il tasto `GO/STOP` per almeno `3 s` al fine di attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura…`” come mostrato nella videata a lato. Nel campo “`Vtest`” è mostrata la reale tensione di prova generata dallo strumento. La durata della prova può variare in funzione della presenza o meno di capacità parassite presenti.

```
M      15/10   –   18:04
( + )   (   -   )
V t e s t   -   -   -   -   -   -   V
R i s o   -   -   -   -   -   -   M   
R p   -   -   -   M   
V P N   V P E   V N E
9   8 0 V   4 9   0 V   -   4 9 0   V
Misura…
DUAL   1 0 00V   1.00M 
MODO   Vtest.   Lim.
```

8.  Lo strumento esegue in sequenza le seguenti misure:
    *   Isolamento tra polo positivo (+) della stringa e riferimento di terra
    *   Isolamento tra polo negativo della stringa (-) e riferimento di terra
    *   Calcolo del valore di resistenza `Rp` dato dal parallelo delle misure (+) e (-)
    Se “`Rp≥Lim`” lo strumento fornisce il messaggio “`OK`” ad indicare l’esito **positivo** della misura.
    Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il § 7.1) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura.

```
M      15/10   –   18:04
( + )   (   -   )
V t e s t   1   0   1 0   1   0   1 5   V
R i s o   > 1 0 0   > 1 0 0   M   
R p   > 1 0 0   M   
V P N   V P E   V N E
9 8 0 V   4 9 0 V   -   4 9 0 V
OK
DUAL   1 0 00V   1.00M 
MODO   Vtest.   Lim.
```

#### 6.4.2. Esecuzione misura di isolamento – Modo `TMR`

1.  Posizionare il cursore sulla voce `M ` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a lato. Utilizzando ancora i tasti freccia (``, ``) selezionare il modo di misura “`TMR`” in corrispondenza della posizione “`MODE`”.

```
M      15/10   –   18:04
V t e s t (   -   )   -   -   -   V
R i (   -   )   -   -   -   M   
T e m p o   -   -   -   s
D A R   -   -   -   P I   -   -   -
V P N   V P E   V N E
- - -   V   - - -   V   0 V
TMR   1 0 00V   1.00M    3s
MODO   Vtest.   Lim.   Tempo
```

2.  Usare i tasti freccia `` o `` selezionando la posizione “`Vtest`” per impostare la tensione di prova.
3.  Usare i tasti freccia (``, ``) per selezionare una delle seguenti tensioni di prova (`Vnom`): `250`, `500`, `1000DC`. Si ricorda che in accordo alla IEC/EN62446-1 la tensione di prova `Vtest` deve essere `≥` tensione nominale dell’impianto.

```
M      15/10   –   18:04
V t e s t (   -   )   -   -   -   V
R i (   -   )   -   -   -   M   
T e m p o   -   -   -   s
D A R   -   -   -   P I   -   -   -
V P N   V P E   V N E
- - -   V   - - -   V   0 V
TMR   1 0 00V   1.00M    3s
MODO   Vtest.   Lim.   Tempo
```

4.  Usare i tasti freccia `` o `` selezionando la posizione “`Lim.`”. A display appare la videata a lato.
5.  Utilizzando i tasti freccia (``, ``) impostare la soglia limite minima di riferimento per la misura di isolamento selezionabile tra i valori `0.05, 0.10, 0.23, 0.25, 0.50, 1.00, 50, 100, 200 M `. Si ricorda che la normativa IEC/EN62446-1 fissa un valore limite minimo di resistenza di isolamento pari a `1M ` per impianti con tensione nominale superiore a `120V`.

```
M      15/10   –   18:04
V t e s t (   -   )   -   -   -   V
R i (   -   )   -   -   -   M   
T e m p o   -   -   -   s
D A R   -   -   -   P I   -   -   -
V P N   V P E   V N E
- - -   V   - - -   V   0 V
TMR   1 0 00V   1.00M    3s
MODO   Vtest.   Lim.   Tempo
```

6.  Usare i tasti freccia `` o `` selezionando la posizione “`Tempo.`”. A display appare la videata a lato.
7.  Utilizzando i tasti freccia (``, ``) impostare il tempo di misura nel campo: `3s ÷ 999s`.

```
M      15/10   –   18:04
V t e s t (   -   )   -   -   -   V
R i (   -   )   -   -   -   M   
T e m p o   -   -   -   s
D A R   -   -   -   P I   -   -   -
V P N   V P E   V N E
- - -   V   - - -   V   0 V
TMR   1 0 00V   1.00M    3s
MODO   Vtest.   Lim.   Tempo
```

8.  Collegare lo strumento alla stringa FV in prova come mostrato in Fig. 8. La prova può essere eseguita anche su più stringhe in parallelo fra loro. Si ricorda che occorre sezionare anche eventuali scaricatori connessi ai cavi della stringa/stringhe e che è consigliabile eseguire la misura a monte di eventuali diodi di blocco.
    Fig. 8: Collegamento strumento per misura di isolamento in modo TMR

> **ATTENZIONE**
> Alla pressione del tasto `GO/STOP` lo strumento può fornire diversi messaggi di errore (vedere § 6.4.3) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test.

9.  Premere e tenere premuto il tasto `GO/STOP` per almeno `3 s` al fine di attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura…`” come mostrato nella videata a lato. Nel campo “`Vtest (-)`” è mostrata la reale tensione di prova generata dallo strumento.

```
M      15/10   –   18:04
V t e s t (   -   )   -   -   -   V
R i (   -   )   -   -   -   M   
T e m p o   -   -   -   s
D A R   -   -   -   P I   -   -   -
V P N   V P E   V N E
- - -   V   - - -   V   -   632 V
Misura…
TMR   1 0 00V   1.00M    700s
MODO   Vtest.   Lim.   Tempo
```

10. Se “`Ri(-)≥Lim`” lo strumento fornisce il messaggio “`OK`” ad indicare l’esito **positivo** della misura.
    Se il tempo di misura è `≥60s` lo strumento mostra a display il valore del parametro `DAR` (**Rapporto di Assorbimento Dielettrico**) (vedere § 11.2).
    Se il tempo di misura è `≥600s` lo strumento mostra a display sia il valore del parametro `DAR` (**Rapporto di Assorbimento Dielettrico**) sia il valore del parametro `PI` (**Indice di Polarizzazione**) (vedere § 11.1).
    Premere il tasto `SAVE` per salvare il risultato del test nella memoria dello strumento (vedere il § 7.1) o il tasto `ESC/MENU` per uscire dalla videata senza salvare e tornare alla videata principale di misura.

```
M      15/10   –   18:04
V t e s t (   -   )   1   0   4 0   V
R i (   -   )   > 1 0 0   M   
T e m p o   6 0 0   s
D A R   1 . 4 1   P I   1 . 0 2
V P N   V P E   V N E
- - -   V   - - -   V   -   632V
OK
TMR   1 0 00V   1.00M    700s
MODO   Vtest.   Lim.   Tempo
```

#### 6.4.3. Situazioni anomale

1.  Qualora lo strumento rilevi una delle seguenti condizioni: “`|VPN| > 1000V`”, “`|VPE| > 1000V`” oppure “`|VNE| > 1000V`” interrompe la misura, emette un suono prolungato e il messaggio “`V . Ingr. > 1000VDC`” è mostrato a display. Controllare la tensione in uscita dalla stringa FV.

```
M      15/10   –   18:04
( + )   (   -   )
V t e s t   -   -   -   -   -   -   V
R i s o   -   -   -   -   -   -   M   
R p   -   -   -   M   
V P N   V P E   V N E
> 1   0   0 0 V   5   0   0 V   -   5   0   0   V
V . I n gr.   >   1 0 00VDC
DUAL   1 0 00V   1.00M 
MODO   Vtest.   Lim.
```

2.  In modo `DUAL` qualora lo strumento alla pressione del tasto `GO/STOP` rilevi una tensione `VPN <0V` interrompe la misura, emette un suono prolungato e il messaggio “`Inverti P - N`” è mostrato a display. Controllare la polarità e i collegamenti dello strumento alla stringa FV.

```
M      15/10   –   18:04
( + )   (   -   )
V t e s t   -   -   -   -   -   -   V
R i s o   -   -   -   -   -   -   M   
R p   -   -   -   M   
V P N   V P E   V N E
-   9   8 0 V   -   5   0   0 V   4 8   0   V
Inverti P - N
DUAL   1 0 00V   1.00M 
MODO   Vtest.   Lim.
```

3.  In modo `DUAL` qualora lo strumento alla pressione del tasto `GO/STOP` rilevi una tensione `VPN < 15 V` interrompe la misura, emette un suono prolungato e il messaggio “`V . Ingresso < 15VDC`” è mostrato a display. Controllare la tensione in uscita dalla stringa FV che deve essere `≥ 15 V`.

```
M      15/10   –   18:04
( + )   (   -   )
V t e s t   -   -   -   -   -   -   V
R i s o   -   -   -   -   -   -   M   
R p   -   -   -   M   
V P N   V P E   V N E
1   0 V   5 V   -   5   V
V . I n gresso   <   15VDC
DUAL   1 0 00V   1.00M 
MODO   Vtest.   Lim.
```

4.  In modo `DUAL` qualora lo strumento alla pressione del tasto `GO/STOP` rilevi che una delle seguenti condizioni sulle tensioni misurate:
    `RMS(VPN) - |(VPN) DC| <10`
    `RMS(VPE) - |(VPE) DC| <10`
    `RMS(VNE) - |(VNE) DC| <10`
    non è soddisfatta (presenza di componenti AC sulle tensioni di ingresso) interrompe la misura, emette un suono prolungato e il messaggio “`V . Ingresso > 10VAC`” è mostrato a display. Controllare che la stringa sia scollegata dall’inverter e che i rispettivi cavi siano separati da altri di eventuali sorgenti di tensione AC ausiliarie.

```
M      15/10   –   18:04
( + )   (   -   )
V t e s t   -   -   -   -   -   -   V
R i s o   -   -   -   -   -   -   M   
R p   -   -   -   M   
V P N   V P E   V N E
9   8 0 V   5   0   0 V   -   4 8   0   V
V . I n gresso   >   10VAC
DUAL   1 0 00V   1.00M 
MODO   Vtest.   Lim.
```

5.  Qualora lo strumento rilevi che la tensione tra polo positivo e polo negativo sia maggiore della tensione di prova impostata il messaggio “`VPN>Vtest`” è mostrato a display e lo strumento blocca la prova in quanto non conforme alla normativa IEC/EN62446-1. Controllare la tensione nominale dell’impianto, eventualmente modificare il parametro e `Vtest` e ripetere il test.

```
M      15/10   –   18:04
( + )   (   -   )
V t e s t   9   2 0   9   1 0   V
R i s o   -   -   -   -   -   -   M   
R p   -   -   -   M   
V P N   V P E   V N E
9 8 0 V   5 0 0 V   -   4 8 0 V
VPN>Vtest
DUAL   1 0 00V   1.00M 
MODO   Vtest.   Lim.
```

6.  Qualora lo strumento rilevi che `Rp<Lim`, il messaggio “`NO OK`” è mostrato a display.

```
M      15/10   –   18:04
( + )   (   -   )
V t e s t   1   0   4 0   1   0   2 0   V
R i s o   0 . 1   > 1 0 0   M   
R p   0 . 1   M   
V P N   V P E   V N E
9   8 0   V   5   0   0 V   -   4 8   0   V
NO OK
DUAL   1 0 00V   1.00M 
MODO   Vtest.   Lim.
```

7.  In modo `TMR` qualora lo strumento rilevi una tensione positiva tra i terminali `N` e `E`, il messaggio “`Inverti E - N`” è mostrato a display e il test non è eseguito. Invertire i collegamenti sugli ingressi dello strumento ricordando che sul terminale `N` deve sempre essere presente un potenziale negativo.

```
M      15/10   –   18:04
V t e s t (   -   )   -   -   -   V
R i (   -   )   -   -   -   M   
T e m p o   -   -   -   s
D A R   -   -   -   P I   -   -   -
V P N   V P E   V N E
- - -   V   - - -   V   632V
Inverti E - N
TMR   1 0 00V   1.00M    700s
MODO   Vtest.   Lim.   Tempo
```

8.  In modo `TMR` se la tensione `VNE` misurata è maggiore della tensione di prova, lo strumento mostra il messaggio “`VEN > Vtest`” all’attivazione della prova. Selezionare una tensione di prova maggiore della tensione misurata al fine di eseguire correttamente il test.

```
M      15/10   –   18:04
V t e s t (   -   )   -   -   -   V
R i (   -   )   -   -   -   M   
T e m p o   -   -   -   s
D A R   -   -   -   P I   -   -   -
V P N   V P E   V N E
- - -   V   - - -   V   -   632V
VEN > Vtest
TMR   500V   1.00M    3s
MODO   Vtest.   Lim.   Tempo
```

### 6.5. `GFL` – RICERCA GUASTI SU ISOLAMENTO STRINGHE FV

Nella funzione `GFL` (Ground Fault Locator) lo strumento è in grado di fornire una indicazione sulla posizione di un eventuale singolo guasto di basso isolamento presente in una stringa dell'impianto dovuto ad esempio ad infiltrazioni d'acqua o umidità all'interno delle scatole di giunzione dei moduli FV. Lo strumento misura le tensioni in ingresso e sulla base dello sbilanciamento fra `V(+)` e `V(-)` rispetto a terra individua la presunta posizione del guasto sulla stringa. Per maggiori dettagli vedere § 11.3.

> **ATTENZIONE**
>
> *   **NON** usare questa funzione su stringhe o moduli fotovoltaici che integrano dispositivi MLPE (microinverter, ottimizzatori di potenza o dispositivi di spegnimento rapido – RSD). L’esecuzione del test `GFL` su tali configurazioni può comportare il **danneggiamento** sia dei dispositivi MLPE sia dello strumento (vedere § 11.5).
> *   Non toccare le masse dei moduli durante la misura in quanto potrebbero trovarsi a potenziale pericoloso anche ad impianto sezionato per effetto della tensione generata dallo strumento.
> *   La misura potrebbe dare risultati non corretti se il riferimento di terra non è collegato correttamente all’ingresso `E`.
> *   Si raccomanda una verifica preliminare di corretto funzionamento dello strumento prima di eseguire una misura, impostando la funzione `TMR` mettendo i terminali `N` ed `E` in cortocircuito verificando un valore di isolamento pressoché nullo e un valore fuori scala con terminali `N` ed `E` aperti.

> **ATTENZIONE**
> La funzione `GFL` consente di ottenere risultati corretti **SOLO** nelle seguenti condizioni:
>
> *   Test eseguito a monte di eventuali diodi di blocco su una **singola stringa** disconnessa dall’inverter, da eventuali scaricatori e da connessioni funzionali a terra.
> *   **Singolo guasto** di basso isolamento avvenuto in un qualunque punto della stringa.
> *   Resistenza di isolamento del singolo guasto `< 1 . 00 M `.
> *   Per effetto della natura aleatoria di questi guasti si raccomanda di eseguire le misure in condizioni ambientali simili a quelle in cui è stato segnalato il guasto.

1.  Posizionare il cursore sulla voce `GFL` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a lato. L’indicazione “`Rp`” indica il parallelo delle resistenze di isolamento dei poli positivo (+) e negativo (-) della stringa in prova.

```
G F L   15/10   –   18:04
R p   -   -   -   M   
V P N   V P E   V N E
0 V   0 V   0 V
10   1 0 00V   0. 23 M 
NMOD   Vtest.   Lim.
```

<!-- Chunk: Pages 33-64 -->
2. Usare i tasti freccia **** o **** selezionando la posizione “**NMOD**” per impostare il numero di moduli della stringa in prova
3. Usare i tasti freccia (****, ****) per selezionare un numero di moduli compreso tra: 4 **÷** 60

```
G F L   1 5 / 1 0   –   1 8 : 0 4
R p   -   -   -   M   
V P N   V P E   V N E
0 V   0 V   0 V
10   1 0 00V   0. 23 M 
NMOD   Vtest.   Lim.
```

4. Usare i tasti freccia **** o **** selezionando la posizione “**Vtest**” per impostare la tensione di prova
5. Usare i tasti freccia (****, ****) per selezionare una delle seguenti tensioni di prova (Vnom): 250, 500, 1000DC. In accordo a quanto previsto dalla IEC/EN62446-1 si consiglia di impostare la tensione di prova `Vtest ≥ Vnom` dell’impianto

```
G F L   1 5 / 1 0   –   1 8 : 0 4
R p   -   -   -   M   
V P N   V P E   V N E
0 V   0 V   0 V
10   1000V   0.23M 
NMOD   Vtest.   Lim.
```

6. Usare i tasti freccia **** o **** selezionando la posizione “**Lim.**”. A display appare la videata a lato.
7. Utilizzando i tasti freccia (****, ****) impostare la soglia limite minima di riferimento per la misura di isolamento selezionabile tra i valori: `0.05MΩ`, `0.1MΩ`, `0.23MΩ`, `0.25MΩ`, `0.50MΩ`, `1.00MΩ`

```
G F L   1 5 / 1 0   –   1 8 : 0 4
R p   -   -   -   M   
V P N   V P E   V N E
0 V   0 V   0 V
10   1000V   0.23M 
NMOD   Vtest.   Lim.
```

8. Collegare lo strumento alla stringa FV in prova come mostrato in Fig. 9. Si ricorda che occorre sezionare anche eventuali scaricatori connessi ai cavi della stringa e che è consigliabile eseguire la misura a monte di eventuali diodi di blocco

Fig. 9: Collegamento strumento per misura di isolamento in modo GFL

---

**ATTENZIONE**
* Alla pressione del tasto **GO/STOP** lo strumento può fornire diversi messaggi di errore (vedere § 6.4.3) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test
* La funzione `GFL` deve essere usata **solo** dopo aver eseguito la misura di isolamento principale (test DUAL) su moduli e/o stringhe con esito negativo

9. Premere e tenere premuto il tasto **GO/STOP** per almeno 3s al fine di attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “Misura…” come mostrato nella videata a lato

```
G F L   1 5 / 1 0   –   1 8 : 0 4
R p   -   -   -   M   
V P N   V P E   V N E
0 V   0 V   0 V
Misura…
10   1000V   0.23M 
NMOD   Vtest.   Lim.
```

10. In assenza di condizioni di guasto (`Rp≥Lim`), l’indicazione lo strumento mostra la videata a lato e il messaggio “OK” è mostrato a display. La condizione di “OK” si può verificare anche in presenza di **più di un guasto** presente sulla stringa (evidenziata da un test fallito precedentemente eseguito con funzione DUAL), condizione che rende **inefficace** la funzione GFL

```
G F L   1   5 / 1 0   –   1 8 : 0 4
R p   > 1 0 0   M   
V P N   V P E   V N E
9   8 0 V   4 9 0   V   -   4 9   0 V
OK
14   1 0 00V   0. 23 M 
NMOD   Vtest.   Lim.
```

**ATTENZIONE**
In presenza di condizione di guasto verificata, la funzione `GFL` mostra:
* La posizione del modulo guasto con tolleranza `±1modulo` per `NMOD ≤ 34`
* La posizione del modulo guasto con tolleranza `±3moduli` per `NMOD > 34`
* E’ raccomandata la suddivisione della stringa in sotto-stringhe aventi un numero inferiore di moduli al fine di ottenere migliori risultati del test

11. In presenza di guasto (`Rp <Lim`) in posizione 0 (a monte del primo modulo), lo strumento mostra la videata a lato e il messaggio “`GND: Guasto (+)..1 ±N`” a display. Controllare lo stato dell’isolamento del conduttore (+) che proviene dalla stringa. Nel caso di figura, avendo `NMOD= 24 → Tolleranza = ±1`, il guasto può trovarsi prima o dopo il primo modulo

```
G F L   1 5 / 1 0   –   1 8 : 0 4
R p   0 .   2   0   M   
V P N   V P E   V N E
9 8 0 V   9   7   0 V   -   1   0 V
GND: Guasto (+)..1   ±1
2 4   1 0 00V   0. 23 M 
NMOD   Vtest.   Lim.
```

---

12. In presenza di guasto (`Rp <Lim`) in posizione `NMOD+1` (a valle dell’ultimo modulo), lo strumento mostra la videata a lato e il messaggio “`GND: Guasto NMOD..( - ) ±N`” a display. Controllare lo stato dell’isolamento del conduttore ( - ) che proviene dalla stringa. Nel caso di figura, avendo `NMOD= 24 → Tolleranza = ±1`, il guasto può trovarsi prima o dopo l’ultimo modulo

```
G F L   15/10   –   18:04
R p   0 .   2   0   M   
V P N   V P E   V N E
9 8 0 V   9   7   0 V   -   1   0 V
GND:   Guasto   2 4.. ( - )   ±1
2 4   1 0 00V   0. 23 M 
NMOD   Vtest.   Lim.
```

13. In presenza di guasto (`Rp<Lim`) in posizione 1 (tra il modulo 1 e il modulo 2), lo strumento mostra la videata a lato e il messaggio “`GND: Guasto 1..2 ±N`” a display. Controllare lo stato di isolamento delle scatole di giunzione dei moduli indicati (1 e 2 nell’esempio) e relativi cavi di collegamento. Nel caso di figura, avendo `NMOD= 24 → Tolleranza = ±1`, il guasto può trovarsi **prima del 1° modulo** oppure **tra il primo e il terzo modulo**

```
G F L   15/10   –   18:04
R p   0 .   2   0   M   
V P N   V P E   V N E
9 8 0 V   9   4   0 V   -   4 0 V
GND: Guasto 1..2   ±1
2 4   1 0 00V   0. 23 M 
NMOD   Vtest.   Lim.
```

14. In presenza di guasto (`Rp<Lim`) in posizione `NMOD` (tra il penultimo e l’ultimo modulo), lo strumento mostra la videata a lato e il messaggio “`GND: Guasto NMOD - 1..NMOD ±N`” a display. Controllare lo stato di isolamento delle scatole di giunzione dei moduli indicati e relativi cavi di collegamento. Nel caso di figura, avendo `NMOD= 24 → Tolleranza = ±1`, il guasto può trovarsi tra il **23° modulo** e dopo l’ultimo modulo

```
G F L   15/10   –   18:04
R p   0 .   2   0   M   
V P N   V P E   V N E
9 8 0 V   9   4   0 V   -   4 0 V
GND: Guasto   2 3.. 2 4   ±1
2 4   1 0 00V   0. 23 M 
NMOD   Vtest.   Lim.
```

15. In presenza di guasto (`Rp<Lim`) all’interno della stringa, lo strumento mostra la videata a lato e il messaggio (relativo all’esempio con `NMOD = 36`) “`GND: Guasto 8..9 ±N`” a display. Controllare lo stato di isolamento delle scatole di giunzione dei moduli indicati e relativi cavi di collegamento. Nel caso di figura, avendo `NMOD= 36 (>35) → Tolleranza = ±3`, il guasto può trovarsi tra il 5° modulo e il 12° modulo

```
G F L   15/10   –   18:04
R p   0   .   2 0   M   
V P N   V P E   V N E
9 8 0 V   4 9 0 V   -   4 9 0 V
GND: Guasto 8..9 ±3
3 6   1 0 00V   0.23M 
NMOD   Vtest.   Lim.
```

**ATTENZIONE**
I risultati della funzione `GFL` non sono salvabili nella memoria dello strumento

---

## 6.6. OPT – MISURA DI ISOLAMENTO CON OTTIMIZZATORI DI POTENZA

Lo scopo di questa misura è l’esecuzione delle misure di resistenza di isolamento dei conduttori attivi su stringhe FV in accordo alle prescrizioni delle normative IEC/EN62446-1 e IEC/EN61557-2 in presenza di `MLPE` (ottimizzatori di potenza, dispositivi di spegnimento rapido RSD) senza la necessità di scollegamento degli stessi dai moduli FV (vedere § 11.5)

**ATTENZIONE**
* Non toccare le masse dei moduli durante la misura in quanto potrebbero trovarsi a potenziale pericoloso anche ad impianto sezionato per effetto della tensione generata dallo strumento
* La misura potrebbe dare risultati non corretti se il riferimento di terra non è collegato correttamente all’ingresso **E**
* Si raccomanda una verifica preliminare di corretto funzionamento dello strumento prima di eseguire una misura, impostando la funzione `TMR` mettendo i terminali **N** ed **E** in cortocircuito verificando un valore di isolamento pressoché nullo e un valore fuori scala con terminali **N** ed **E** aperti

**ATTENZIONE**
* La misura di isolamento è eseguibile su un singolo modulo, su una stringa o su un impianto costituito da più stringhe connesse in parallelo
* Sezionare la stringa/impianto dall’inverter e da eventuali scaricatori
* Se il modulo/stringa/l’impianto ha un polo connesso a Terra, tale connessione va temporaneamente sezionata.
* La normativa IEC/EN62446-1 fissa `1MΩ` come valore limite minimo di resistenza di isolamento per impianti con tensione nominale superiore a `120V`
* È consigliabile eseguire la misura di isolamento direttamente sul modulo/stringa/campo a monte di eventuali diodi di blocco

Lo strumento esegue la misura di isolamento in presenza di ottimizzatori nei seguenti modi:
* Misure con ottimizzatori dotati di dispositivo di spegnimento rapido (RSD) **→** lo strumento esegue il test in conformità alla normativa USA `NEC 690.12` che regola le prescrizioni per questo tipo di dispositivi (`RSD = Rapid ShutDown`) (vedere § 11.5.1)
* Misure con ottimizzatori NON dotati di dispositivo di spegnimento rapido (RSD) **→** lo strumento esegue il test con modalità del tutto simile alla prova `DUAL` (vedere § 6.4.1)

In entrambe le modalità, il risultato è sempre costituito dal parametro `Rp = resistenza parallelo delle resistenze di isolamento tra il polo positivo e quello negativo della catena stringa + ottimizzatori in esame`. Tale valore è poi confrontato con il limite minimo impostato sullo strumento e da questo confronto si determina l’esito positivo o negativo del test.

**ATTENZIONE**
Fare sempre riferimento in maniera preliminare, alla scheda tecnica del costruttore sulla modalità di prova ed eventuali limitazioni del dispositivo `MLPE` in test

---

### 6.6.1. Misura di Isolamento con ottimizzatori aventi funzione RSD

1. Posizionare il cursore sulla voce `OPT` utilizzando i tasti freccia (****, ****) e confermare con **ENTER**. A display appare la videata a fianco. Il messaggio “`Ottimizzatore con Spegnimento rapido`” indica che la misura è eseguita su ottimizzatori dotati di funzione di “`spegnimento rapido (RSD = Rapid ShutDown)`”. I seguenti parametri sono mostrati:
    * `VTest` **→** tensione di prova nella misura di isolamento
    * `RLim` **→** limite minimo nella misura di isolamento
    * `OTT.N` **→** numero ottimizzatori presenti sulla stringa
    * `Vlim` **→** valore limite tensione in uscita da ogni ottimizzatore
    * Valori delle tensioni `VPN`, `VPE` e `VNE`

```
O P T   15/10   –   18:04
Rp   -   -   -   M 
O t t i m i z z a t o r e   c o n
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
0V   0V   0V
250V   0.6M    1 0   1.0V
VTest   RLim   OTT.N   Vlim
```

2. Usare i tasti freccia (****, ****) per accedere alla programmazione dei parametri di misura. La videata a lato è mostrata a display. Usare i tasti (****, ****) per impostare i valori. Le seguenti opzioni sono disponibili:
    * `Tens. prova` **→** impostare la tensione di prova nella misura di isolamento tra le opzioni: `100V`, `250V`, `500V`, `1000VDC`. Se il costruttore dell’`MLPE` (ottimizzatore) non indica una tensione di prova, si consiglia di impostare `100V`
    * `RLim` **→** impostare la soglia minima di riferimento nella misura di isolamento tra i valori: `0.25`, `0.50`, `0.60`, `1.00`, `50`, `100`, `200MΩ`
    * `Spegn. rapido` **→** impostare il tipo di ottimizzatori in esame con opzione: `ON` (funzione RSD presente)
    * `N. Ottimizz.` **→** impostare il numero degli ottimizzatori presenti sulla stringa in prova nel campo: `1 ÷ 60`

```
O P T   15/10   –   18:04
Tens. Prova   :      250      V
RLim   :      0.6      M 
Spegn. rapido   :      ON   
N. Ottimizz.   :      1 0   
Vlim   :      1.0      V

```

    * `Vlim` **→** impostare il valore della tensione di uscita di ogni ottimizzatore nel campo: `0.1V ÷ 2.0V` in passi da `0.1V`
3. Premere il tasto **SAVE** per salvare le impostazioni
4. Sezionare la stringa/stringhe in prova dalla combiner box/Inverter ed attendere **almeno 30s** (tempo massimo indicato dalla normativa USA `NEC 690.12` affinché tutti gli ottimizzatori siano effettivamente in stato di RSD attivato)
5. Collegare lo strumento all’uscita della serie di ottimizzatori associati alla stringa in prova come mostrato in Fig. 10. In particolare, collegare il polo Positivo in uscita dal **primo ottimizzatore** al terminale P, il polo Negativo in uscita **dall’ultimo ottimizzatore** al terminale N e il terminale E al nodo principale di terra dell’impianto

---

Fig. 10: Collegamento dello strumento per misura di isolamento con ottimizzatori

**ATTENZIONE**
Alla pressione del tasto **GO/STOP** lo strumento può fornire diversi messaggi di errore (vedere § 6.6.3) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test

6. Premere il tasto **GO/STOP** per attivare il test. In assenza di condizioni di errore, lo strumento esegue la misura della tensione tra i terminali P e N tra il primo e l’ultimo ottimizzatore, verificando che `VPN ≤ 30V` (in accordo alla normativa `NEC 690.12`) e, in caso positivo, visualizza il messaggio “`Misura…`” come mostrato nella videata a lato

```
O P T   15/10   –   18:04
Rp   -   -   -   M 
O t t i m i z z a t o r e   c o n
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
10V   5V   - 5V
M i s u r a …
250V   0.6M    1 0   1.0V
VTest   RLim   OTT.N   Vlim
```

7. Al termine della misura, il valore della resistenza di isolamento `Rp` ottenuta dal **parallelo delle resistenze della catena stringhe/ottimizzatori** è mostrata a display. Se tale valore è `≥ RLim` il messaggio “OK” è fornito in caso di esito positivo del test. Se tale valore è `<RLim` il test è fallito e il messaggio “NO OK” è mostrato a display

```
O P T   15/10   –   18:04
Rp   92   M 
O t t i m i z z a t o r e   c o n
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
10V   5V   - 5V
O K
250V   0.6M    1 0   1.0V
VTest   RLim   OTT.N   Vlim
```

**ATTENZIONE**
I risultati della funzione `OPT` non sono salvabili nella memoria dello strumento

---

### 6.6.2. Misura di Isolamento con ottimizzatori senza funzione RSD

1. Posizionare il cursore sulla voce `OPT` utilizzando i tasti freccia (****, ****) e confermare con **ENTER**. A display appare la videata a fianco. Il messaggio “`Ottimizzatore senza Spegnimento rapido`” indica che la misura è eseguita su ottimizzatori **non** dotati di funzione di “`spegnimento rapido (RSD = Rapid ShutDown)`”. I seguenti parametri sono mostrati:
    * `VTest` **→** tensione di prova nella misura di isolamento
    * `RLim` **→** limite minimo nella misura di isolamento
    * Valori delle tensioni `VPN`, `VPE` e `VNE`

```
O P T   15/10   –   18:04
R p   -   -   -   M 
O t t i m i z z a t o r e   s e n z a
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
0V   0V   0V
10 0V   1 . 0 M 
VTest   RLim
```

2. Usare i tasti freccia (****, ****) per accedere alla programmazione dei parametri di misura. La videata a lato è mostrata a display. Usare i tasti (****, ****) per impostare i valori. Le seguenti opzioni sono disponibili:
    * `Tens. prova` **→** per ragioni di sicurezza la tensione di prova è **fissata** a `100V DC`
    * `RLim` **→** impostare la soglia minima di riferimento nella misura di isolamento tra i valori: `0.25`, `0.50`, `0.60`, `1.00`, `50 MΩ`
    * `Spegn. rapido` **→** impostare il tipo di ottimizzatori in esame con opzione: `OFF` (funzione RSD non presente)

```
O P T   15/10   –   18:04
Tens. Prova   :      10 0      V
RLim   :      0.6      M 
Spegn. rapido   :      O FF   

```

3. Premere il tasto **SAVE** per salvare le impostazioni
4. Collegare lo strumento all’uscita della serie di ottimizzatori associati alla stringa in prova come mostrato in Fig. 10. In particolare, collegare il polo Positivo in uscita dal **primo ottimizzatore** al terminale P, il polo Negativo in uscita **dall’ultimo ottimizzatore** al terminale N e il terminale E al nodo principale di terra dell’impianto

**ATTENZIONE**
Alla pressione del tasto **GO/STOP** lo strumento può fornire diversi messaggi di errore (vedere § 6.6.3) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test

5. Premere il tasto **GO/STOP** per attivare il test. In assenza di condizioni di errore e con **tensione `VPN ≥ 15V`** presente tra i terminali P e N, visualizza il messaggio “`Misura…`” come mostrato nella videata a lato

```
O P T   15/10   –   18:04
Rp   -   -   -   M 
O t t i m i z z a t o r e   s e n z a
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
840 V   430 V   - 410 V
M i s u r a …
100V   1.0M 
VTest   RLim
```

---

6. Al termine della misura, il valore della resistenza di isolamento `Rp` ottenuta dal **parallelo delle resistenze della catena stringhe/ottimizzatori** è mostrato a display. Se tale valore è `≥ RLim` il messaggio “OK” è fornito in caso di esito positivo del test. Se tale valore è `<RLim` il test è fallito e il messaggio “NO OK” è mostrato a display

```
O P T   15/10   –   18:04
Rp   76   M 
O t t i m i z z a t o r e   s e n z a
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
840V   430V   - 410V
O K
100V   1.0M 
VTest   RLim
```

**ATTENZIONE**
I risultati della funzione `OPT` non sono salvabili nella memoria dello strumento

---

### 6.6.3. Situazioni anomale

1. In modo `Spegnimento rapido ON` qualora lo strumento alla pressione del tasto **GO/STOP** rilevi una tensione `VPN <0V` interrompe la misura, emette un suono prolungato e il messaggio “`Inverti P - N`” è mostrato a display. Controllare la polarità e i collegamenti dello strumento alla stringa+ottimizzatori

```
O P T   15/10   –   18:04
Rp   -   -   -   M 
O t t i m i z z a t o r e   c o n
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
- 10V   - 5V   5V
I n v e r t i P   -   N
250V   0.6M    1 0   1.0V
VTest   RLim   OTT.N   Vlim
```

2. In modo `Spegnimento rapido ON` qualora lo strumento alla pressione del tasto **GO/STOP** rilevi che il rapporto `VPN /N.Ott. >Vlim` interrompe la misura, emette un suono prolungato e il messaggio “`Tens.Ottimizz. > Vlim`” è mostrato a display. Controllare le impostazioni e le caratteristiche della tensione fornita in uscita da ogni ottimizzatore

```
O P T   15/10   –   18:04
Rp   -   -   -   M 
O t t i m i z z a t o r e   c o n
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
2 5V   11 V   - 1 4V
T e n s . Ot t i m i z z . > V l i m
250V   0.6M    1 0   1.0V
VTest   RLim   OTT.N   Vlim
```

3. In modo `Spegnimento rapido ON` qualora lo strumento alla pressione del tasto **GO/STOP** rilevi una tensione `VPN >30V` interrompe la misura, emette un suono prolungato e il messaggio “`V Tot . Ottimizz. > 30V`” è mostrato a display. Controllare le impostazioni e le caratteristiche della tensione fornita in uscita da ogni ottimizzatore

```
O P T   15/10   –   18:04
Rp   -   -   -   M 
O t t i m i z z a t o r e   c o n
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
65V   31V   - 34V
V   .   T o t   Ot t i m i z z . >   3 0 V
250V   0.6M    1 0   1.0V
VTest   RLim   OTT.N   Vlim
```

4. Qualora lo strumento alla pressione del tasto **GO/STOP** rilevi una delle seguenti condizioni sulle tensioni misurate:
   `||(AVG(VPN)| – RMS(VPN))/|AVG(VPN)|| < 0.05`
   `||(AVG(VPE)| – RMS(VPE))/|AVG(VPE)|| < 0.05`
   `||(AVG(VNE)| – RMS(VNE))/|AVG(VNE)|| < 0.05`
   Non soddisfatta (**presenza di componenti AC sulle tensioni di ingresso**) interrompe la misura, emette un suono prolungato e il messaggio “`VAC > LIM`” è mostrato a display. Controllare che la stringa sia scollegata dall’inverter e che i rispettivi cavi siano separati da altri di eventuali sorgenti di tensione AC ausiliarie

```
O P T   15/10   –   18:04
Rp   -   -   -   M 
O t t i m i z z a t o r e   c o n
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
0V   0V   0V
V A C > L I M
250V   0.6M    1 0   1.0V
VTest   RLim   OTT.N   Vlim
```

---

5. In modo `Spegnimento rapido ON` Qualora lo strumento alla pressione del tasto **GO/STOP** rilevi una **corrente di cortocircuito maggiore di 1A** interrompe la misura, emette un suono prolungato e il messaggio “`Isc > Ilim`” è mostrato a display. Controllare i collegamenti dello strumento alla stringa+ottimizzatori

```
O P T   15/10   –   18:04
Rp   -   -   -   M 
O t t i m i z z a t o r e   c o n
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
10V   5V   - 5V
I s c > I l i m
250V   0.6M    1 0   1.0V
VTest   RLim   OTT.N   Vlim
```

6. In modo `Spegnimento rapido OFF` qualora lo strumento alla pressione del tasto **GO/STOP** rilevi una tensione `VPN <15V` interrompe la misura, emette un suono prolungato e il messaggio “`V.Ingresso < 15VDC`” è mostrato a display. Controllare la tensione in uscita dalla stringa + ottimizzatori che deve essere `≥15V`

```
O P T   15/10   –   18:04
Rp   -   -   -   M 
O t t i m i z z a t o r e   s e n z a
S p e g n i m e n t o   r a p i d o
V P N   V P E   V N E
10 V   5 V   - 5 V
V . I n g r e s s o   <   1 5 V D C
100 V   1 . 0 M 
VTest   RLim
```

---

## 6.7. DB – GESTIONE DATABASE MODULI

Lo strumento permette la gestione **fino ad un massimo di 63 moduli FV** Monofacciali o Bifacciali oltre ad un modulo di DEFAULT (non modificabile né cancellabile) che può essere usato come riferimento qualora non si abbiamo informazioni sul tipo di modulo a disposizione.
I parametri, **riferiti a 1 modulo**, che possono essere impostati nella definizione sono riportati nella Tabella 1 seguente, insieme ai campi di misura, risoluzione e condizioni di validità:

Tabella 1: Parametri associati ad un modulo FV

| Voce      | Descrizione                       | Campo                      | Risoluzione  | Note                               |
| :-------- | :-------------------------------- | :------------------------- | :----------- | :--------------------------------- |
| `Prod`    | Nome costruttore modulo           | Max 15 caratteri           |              | Solo MAIUSCOLI                     |
| `Nome`    | Nome modulo                       | Max 15 caratteri           |              | Solo MAIUSCOLI                     |
| `Tipo`    | Tipo di modulo                    | Monofacciale Bifacciale    |              |                                    |
| `Voc`     | Tensione a vuoto                  | `15.00 ÷ 199.99V`          | `0.01V`      | `Voc ≥ Vmpp`                       |
| `Isc`     | Corrente di cortocircuito         | `0.50 ÷ 40.00A`            | `0.01A`      | `Isc ≥ Impp`                       |
| `Vmpp`    | Tensione punto di massima potenza | `15.00 ÷ 199.99V`          | `0.01V`      | `Voc ≥ Vmpp`                       |
| `Impp`    | Corrente punto di massima potenza | `0.50 ÷ 40.00A`            | `0.01A`      | `Isc ≥ Impp`                       |
| `Tmp.Isc (α)` | Coefficiente di temperatura Isc   | `-0.100 ÷ 0.100 %/°C`      | `0.001%/°C`  | `100*α / Isc ≤ 0.1`                |
| `Tmp.Isc (β)` | Coefficiente di temperatura Voc   | `-0.999 ÷ -0.001%/°C`      | `0.001 %/°C` | `100*β / Voc ≤ 0.999`              |
| `Coef. Bif.` | Coefficiente di bifaccialità (solo moduli Bifacciali) | `0.0 ÷ 100.0%` | `0.1 %`      |                                    |

### 6.7.1. Definizione di un nuovo modulo FV

1. Posizionare il cursore sulla voce `DB` utilizzando i tasti freccia (****, ****) e confermare con **ENTER**. A display appare la videata che riporta il tipo di modulo selezionato e i valori dei parametri associati al modulo

```
D B   15/10   –   18:04
P r o d .      S   E N E C   
N o m e :      M 4 2 0   
T i p o   :   Bifac ciale
V o c   :   3 8   .   0   0   V
I s c   :   1 3   .   9 9   A
T m p . I s c (      )   :   0 . 0   4 6   %/°C
Tmp.   Voc(  )   :   -   0 . 2 6 0   %/°C
C o e f . B i f .   :   9   0 . 0   %
3 7 /   6 4
Nuovo   Modif.   Canc.   Libero
```

2. Usare i tasti freccia (****, ****) per selezionare il costruttore del modulo (campo “`Prod.`”) e il nome del modulo (campo “`Nome`” scegli scorrendo le liste di quelli precedentemente definiti e salvati

```
D B   15/10   –   18:04
P r o d .      S E N E C   
N o m e :      M 4 2 0   
T i p o   :   B ifac ciale
V o c   :   3 8 . 0 0   V
I s c   :   1 3 . 9 9   A
T m p . I s c (      )   :   0 . 0 4 6   %/°C
Tmp.Voc(  )   :   -   0 . 2 6 0   %/°C
C o e f . B i f .   :   9 0 . 0   %
3 7 /   6 4
Nuovo   Modif.   Canc.   Libero
```

---

3. Selezionare il comando “`Nuovo`” (che consente di definire un nuovo modulo) e confermare con **ENTER**. Usare i tasti freccia sulla tastiera virtuale e definire il nome del produttore del modulo. Confermare con “`OK`”

```
SAVE   15/10   –   18:04
P r o d u t t o r e
S U N P O W E R _
0   1   2   3   4   5   6   7   8   9   0   (   )   %
Q   W   E   R   T   Y   U   I   O   P   < = >   #
A   S   D   F   G   H   J   K   L   +   -   *   /   &
Z   X   C   V   B   N   M   .   ,   ;   :   !   ?   _
Ä Ö Ü ß μ Ñ Ç Á Í Ó Ú Ü ¿ ¡
Á È É Ù Ç Ä Ë Ï Ö Ü Æ Ø Å
CANC   OK   NUOVO
```

4. Usare i tasti freccia sulla tastiera virtuale e definire il nome del modulo. Confermare con “`OK`”

```
SAVE   15/10   –   18:04
N o m e   M o d u l o
3 1 8 W T H _
0   1   2   3   4   5   6   7   8   9   0   (   )   %
Q   W   E   R   T   Y   U   I   O   P   < = >   #
A   S   D   F   G   H   J   K   L   +   -   *   /   &
Z   X   C   V   B   N   M   .   ,   ;   :   !   ?   _
Ä Ö Ü ß μ Ñ Ç Á Í Ó Ú Ü ¿ ¡
Á È É Ù Ç Ä Ë Ï Ö Ü Æ Ø Å
CANC   OK   NUOVO
```

5. Inserire il valore di ogni parametro (vedere Tabella 1) in funzione del datasheet eventuale del costruttore. Posizionare il cursore sul parametro da definire utilizzando i tasti freccia (****, ****) e impostare il valore utilizzando i tasti freccia (****, ****). Tenere premuto i tasti (****, ****) per eseguire una rapida impostazione dei valori.
6. Premere il tasto **SAVE** per salvare le impostazioni o **ESC/MENU** per uscire senza salvare

```
D B   15/10   –   18:04
P r o d .   SUNPOWER
N o m e :   3 1 8 W T H
T i p o   :      Monofacciale   
V o c   :      6 4 . 7 0      V
I s c   :      6 . 2 0      A
V m p p   :      5   4 . 7 0      V
I m p p   :      5   .   8 2      A
T m p . I s c (      )   :      0 . 0 5 7      %/°C
Tmp.Voc(  )   :      -   0 . 1 2 7      %/°C
```

**ATTENZIONE**
Alla pressione del tasto **SAVE** lo strumento controlla le condizioni riportate nella Tabella 1 e, nel caso in cui una o più di esse non sia verificata, fornisce a display uno dei messaggi di errore riportati nel § 6.9 e non salva la configurazione impostata finché le cause di errore non sono risolte

---

### 6.7.2. Modifica di un modulo FV esistente

1. Selezionare il modulo FV da modificare all’interno del database utilizzando i tasti freccia (****, ****)
2. Selezionare il comando “`Modif.`” usando il tasto freccia (****) e confermare con **ENTER**
3. Lo strumento presenta una tastiera virtuale interna in cui è possibile ridefinire il nome del modulo o lasciarlo inalterato usando tasti freccia (****, ****, ****, ****). Confermare con “`OK`” nella parte bassa della videata per accedere alla selezione dei parametri da modificare. La pressione del tasto **ENTER** consente l’inserimento di ogni carattere del nome digitato.
4. Premere il tasto **SAVE** per salvare le modifiche eseguite

```
D B   15/10   –   18:04
P r o d .      S E N E C   
N o m e :      M   4   3   0   
T i p o   :   Bifa cciale
V o c   :   3 8 . 0 0   V
I s c   :   1   4   .   3 3   A
V   m p p   :   3   1   .   8 0   V
I   m p p   :   1 3 .   5 3   A
T m p . I s c (      )   :   0 . 0 4 6   %/°C
Tmp.Voc(  )   :   - 0.260   %/°C
C o e f . B i f .   :   9 0 . 0   %
3 7 /   6 4
Nuovo   Modif.   Canc.   Libero
```

### 6.7.3. Cancellazione di un modulo FV esistente

1. Selezionare il modulo FV presente all’interno del database utilizzando i tasti freccia (****, ****)
2. Premere il tasto **ENTER** e selezionare il comando “`Canc.`” usando il tasto freccia (****) per cancellare il modulo selezionato
3. Confermare la selezione con **ENTER** oppure premere **ESC/MENU** per uscire dalla funzione
4. La posizione “`Libero`” indica il numero residuo di moduli ancora inseribili all’interno del DB in rapporto al numero massimo consentito (64 moduli)

```
D B   15/10   –   18:04
P r o d .      S E N E C   
N o m e :      M   4   3   0   
T i p o   :   B ifacciale
V o c   :   3 8 . 0 0   V
I s c   :   1 4 . 3 3   A
V   m p p   :   3 1 . 8 0   V
I   m p p   :   1 3 . 5 3   A
T m p . I s c (      )   :   0 . 0 4 6   %/°C
Tmp.Voc(  )   :   - 0.260   %/°C
C o e f . B i f .   :   9 0 . 0   %
3 7 /   6 4
Nuovo   Modif.   Canc.   Libero
```

**ATTENZIONE**
Se si cancella l’ultimo modulo presente nel DB, lo strumento genera automaticamente il modulo di `DEFAULT`

---

## 6.8. IVCK - TEST SU MODULI E STRINGHE FV

### 6.8.1. Introduzione

Questa funzione esegue una serie di test su **un modulo/stringa FV** misurando in sequenza:
* **Tensione a vuoto `Voc`** in accordo alle prescrizioni della norma IEC/EN62446-1 della stringa/modulo FV in prova misurata in condizione `OPC` (`OPerative Condition`) cioè nelle condizioni reali in cui si trova l’installazione, con o senza misura di irraggiamento e temperatura
* **Corrente di corto circuito `Isc`** in accordo alle prescrizioni della norma IEC/EN62446-1 della stringa/modulo FV in prova misurata in condizione `OPC` (`OPerative Condition`) cioè nelle condizioni reali in cui si trova l’installazione con o senza misura di irraggiamento e temperatura
* **Resistenza di isolamento** in modo `DUAL` con misura dei valori `R(+)`, `R(-)` e `Rp`
* **Continuità dei conduttori di protezione** con `200mA`

**ATTENZIONE**
NON eseguire misure IVCK su stringhe o moduli fotovoltaici che integrano `MLPE` (microinverter, ottimizzatori di potenza o dispositivi di sezionamento rapido – RSD). L’esecuzione di prove su tali configurazioni può danneggiare sia i dispositivi `MLPE` che lo strumento (vedere § 11.5.3)

**ATTENZIONE**
* Le opzioni di misura “`Resistenza di isolamento`” e “`Continuità dei conduttori di protezione`” nel test `IVCK` sono disabilitabili (vedere § 6.8.2)
* Con impostazione della misura di irraggiamento in modalità “`OFF`” (vedere § 5.1.4), le misure di `Voc` e `Isc` sono eseguite **SENZA** misura di irraggiamento e temperatura. In tal caso lo strumento visualizza solo i valori `OPC`, li confronta con i **valori medi** (media scorrevole ultime 10 misure) e visualizza esito per confronto valori medi
* Con impostazione della misura di irraggiamento in modalità “`Diretta`” (vedere § 5.1.4), essa può essere svolta **SOLO** su moduli Monofacciali
* Con impostazione della misura di irraggiamento in modalità “`U. Rem.`” (vedere § 5.1.4) essa è eseguita tramite una o più celle di riferimento `HT305` (nel caso di moduli Bifacciali) e con **eventuale** sonda di temperatura `PT305` collegate all’unità remota `SOLAR03` la quale comunica con lo strumento i dati in tempo reale **tramite collegamento Bluetooth**
* Nelle misure di `Voc` e `Isc` **CON** misura di irraggiamento e temperatura, i dati alle condizioni `OPC` sono “traslati” automaticamente dallo strumento alle condizioni `STC` (`Standard Test Condition` – Irraggiamento = `1000W/m²`, Temperatura modulo = `25°C`, distribuzione spettrale `AM=1.5`) al fine di eseguire il confronto con le caratteristiche dichiarate dal costruttore del modulo
* Le misure di irraggiamento e temperatura sono raccomandate qualora siano presenti condizioni di irraggiamento instabili o si abbia la necessità di confronto con i valori nominali del modulo dichiarati dal costruttore. In questo caso lo strumento fornisce direttamente i risultati delle misure `@ STC`

---

**ATTENZIONE**
* Nelle misure di irraggiamento eseguite con la/le cella/celle di riferimento `HT305` **non è necessaria** l’impostazione dei relativi valori di sensibilità e alpha che sono **automaticamente** letti dal `SOLAR03` dopo il collegamento di tali accessori all’unità remota
* Qualora la connessione Bluetooth fra strumento e unità remota risulti critica (distanza elevata o trasmissione attraverso pareti/ostacoli), è **raccomandato** eseguire le misure traslate alle condizioni `STC` attivando la **registrazione** dei valori di irraggiamento/temperatura letti dall’unità `SOLAR03` (vedere § 6.8.5)

**ATTENZIONE**
* La soglia di Irraggiamento minima consigliata è `700W/m²` **→** lo strumento esegue tutti i controlli previsti per la prova `I-V`, gestisce tutte le condizioni ed i messaggi di errore della prova `I-V` (num. Mod. errato, Temp. Fuori range, presenza cella, Irr. Min, ecc..) e calcola i valori a `STC` di `Voc` e `Isc`. Questa modalità è raccomandata qualora si intenda eseguire delle prove più approfondite sui moduli/stringhe in esame
* La pagina dei risultati conterrà in generale:
    * I valori di Irraggiamento e temperatura (se disponibili)
    * I valori medi di `Voc` e `Isc` calcolati come media dei corrispondenti valori a `OPC` sulle ultime 10 prove memorizzate e salvate. Se il numero delle prove è `< 10` la media viene calcolata sul numero delle prove disponibili. La prima prova visualizzerà trattini nel campo “valori medi” visto che non ci sono prove precedenti su cui calcolare la media.
    * I valori di `Voc` e `Isc` misurati a `OPC` e gli eventuali esiti parziali (presenti solo se i valori `STC` non sono disponibili) ottenuti per confronto con i valori medi.
    * I valori di `Voc` e `Isc` calcolati a `STC` (se disponibili) e gli eventuali esiti parziali ottenuti per confronto dei valori calcolati a `STC` con quelli nominali (inseriti nel DB moduli)
    * L’esito complessivo della prova (OK/NO) è calcolato sulla base degli esiti parziali ottenuti a `STC` (se questi sono disponibili) o sulla base degli esiti parziali a `OPC` (se i valori `STC` non sono disponibili)
    * Lo strumento non mostra esiti complessivi se non è disponibile nessun esito parziale

---

### 6.8.2. Test IVCK senza unità remota e senza misura di irraggiamento

**ATTENZIONE**
* La massima tensione tra gli ingressi P, N, E e C è `1000VDC`. Non misurare tensioni che eccedano i limiti espressi in questo manuale
* La corrente massima misurabile dallo strumento è `30A`
* Non eseguire prove su moduli o stringhe FV connessi **all’inverter**
* La norma IEC/EN62446-1 richiede di effettuare le misurazioni stringa per stringa. Anche se lo strumento è progettato per gestire la corrente di corto circuito per stringhe singole o in parallelo, si **raccomanda** di testare **una stringa per volta** in base alle prescrizioni della norma

1. Selezionare la modalità “`OFF`” nella sezione “`Irr.&Temp.`” (vedere § 5.1.4)
2. Posizionare il cursore sulla voce `IVCK` utilizzando i tasti freccia (****, ****) e confermare con **ENTER**. A display appare la videata a fianco. Il messaggio “`Mis. Irr. non attiva`” indica che nessuna misura di irraggiamento è prevista. I seguenti parametri sono mostrati:
    * `VTest` **→** tensione di prova nella misura di isolamento
    * `ISO` **→** limite minimo nella misura di isolamento
    * `RPE` **→** limite massimo nella misura di continuità
    * `><` **→** resistenza calibrazione cavi misura di continuità
    * Valori delle tensioni `VPN`, `VPE` e `VNE`

```
I V C K   15/10   –   18:04
M i s .   I r r .   n o n   a t t i v a
Modulo   318WTH
V P N   V P E   V N E
9 8 0 V   4 9 0 V   -   4 9 0 V
1000V   1.00M    2 
VTest   ISO   RPE   >  <
```

3. Usare i tasti freccia (****, ****) per accedere alla programmazione dei parametri di misura. La videata a lato è mostrata a display. Usare i tasti (****, ****) per impostare i valori. Le seguenti opzioni sono disponibili:
    * `Prod.` **→** Impostare il produttore del modulo presente nel DB interno
    * `Nome` **→** Impostare il modulo presente nel DB interno
    * `N. Mod x Str.` **→** impostare il numero dei moduli della stringa nel campo: `1 ÷ 60`
    * `N. Str. par.` **→** impostare il numero delle stringhe in parallelo nel campo: `1 ÷ 10`
    * `Mod. Temp` **→** impostare il modo di misura della temperatura dei moduli tra le opzioni:
        * `AUTO` **→** temperatura calcolata dallo strumento sulla base della misura di `Voc` (nessuna sonda collegata) – opzione raccomandata
        * `MIS` **→** temperatura misurata tramite sonda `PT305` collegata a unità remota
        * `MAN` **→** impostazione manuale temperatura modulo se nota a priori

```
I V C K   15/10   –   18:04
Prod.:      SUNPOWER   
Nome:      318WTH   
N.Mod. x Str.   :      12   
N.Str. par.   :      01   
Mod.Temp.   :      AUTO   
   -   -   -      °C
Tol. Voc   :      05      %
Tol.Isc   :      10      %
A vvia&Salva   :      MAN   
Avvia&Salva   :   RIAVVIO
Iso V.Test   :      1000      V
Iso R.Lim   :      1.00      M 
RPE lim   :      2      
Irr. & Temp.   :      OFF   
Irrag. Min. [W/m2]   :      700   
Valori Med.   :   RIPRISTINA
Voc Med   :   -   -   -   V
Isc Med   :   -   -   -   A

```

    * `Tol. Voc` **→** impostare la tolleranza percentuale nella misura della `Voc` nel campo: `1% ÷ 15%` (tipico 5%)
    * `Tol. Isc` **→** impostare la tolleranza percentuale nella misura della `Isc` nel campo: `1% ÷ 15%` (tipico 10%)

---

    * `Avvia&Salva` **→** impostare la modalità della funzione **avvio test automatico** tra le opzioni: `AUTO` (funzione attiva) o `MAN` (funzione non attiva)
    * `Avvia&Salva` **→** `RIAVVIO` **→** premere il tasto **SAVE** e confermare il riavvio del test solo se è già in corso una sequenza di `Auto Save` e si desidera modificare i marcatori a cui associare le **successive** misure da memorizzare
    * `Iso V. Test` **→** impostare la tensione di prova nella misura di isolamento tra le opzioni: `OFF` (esclusione misura), `250V`, `500V`, `1000VDC`
    * `Iso R.Lim` **→** impostare la soglia minima di riferimento nella misura di isolamento tra i valori: `0.05`, `0.10`, `0.23`, `0.25`, `0.50`, `1.00`, `50`, `100 MΩ`
    * `RPE Lim` **→** impostare il limite massimo nella misura di continuità tra i valori: `OFF` (esclusione misura), `1`, `2`, `3`, `4`, `5 Ω`
    * `Irr. & Temp.` **→** impostazione del tipo di misura di irraggiamento per la misura `IVCK` con opzione “`OFF`” (vedere § 5.1.4)
    * `Irrag. Min [W/m2]` **→** impostazione della soglia minima di irraggiamento (per modi “Diretta” e “U. Rem.”) (vedere § 5.1.4)
    * `Valori Med.` **→** la funzione “`RIPRISTINA`” consente di azzerare i valori medi di parametri `Voc` e `Isc` prima di avviare una nuova misura
    * `Voc Med, Isc Med` **→** valori medi di `Voc` e `Isc` nelle 10 prove precedentemente salvate
4. Premere il tasto **SAVE** per salvare le impostazioni
5. Se necessario, selezionare l’opzione “`><`” e confermare con **ENTER**. Eseguire l’eventuale operazione come riportato nel § 6.3.1
6. Collegare lo strumento al modulo/stringa in prova ed eventualmente al nodo principale di terra dell’impianto e alle masse metalliche messe a terra come mostrato in Fig. 11. In particolare, collegare il polo Negativo in uscita dal modulo/stringa al terminale N e il polo Positivo in uscita dal modulo/stringa al terminale P

Fig. 11: Collegamento per test IVCK senza unità remota e senza misura irraggiamento

---

**ATTENZIONE**
Alla pressione del tasto **GO/STOP** lo strumento può fornire diversi messaggi di errore (vedere § 6.9) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test

**ATTENZIONE**
Nel caso in cui si svolgano test su un **numero `N>1` di stringhe in parallelo**, la corrente massima gestibile dallo strumento risulta essere `30A/N`

7. Premere il tasto **GO/STOP** per attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura…`” e la misura della tensione a vuoto tra i terminali P e N e della corrente di cortocircuito (per valori di `Isc ≤ 30A`)

```
I V C K   15/10   –   18:04
Voc@OPC   -   -   -   V
Isc@OPC   -   -   -   A
Voc Med   -   -   -   V
Isc Med   -   -   -   A
Rp   -   -   -   M 
R+   -   -   -   R -   -   -   -   M 
RPE   -   -   -   
M i s u r a …
1000V   1.00M    2    -   -   -   
VTest   ISO   RPE   >  <
```

8. Al termine delle misure di `Voc@OPC` e `Isc@OPC` il messaggio “OK” è fornito in caso di esito positivo del test (**valori misurati entro le tolleranze impostate sullo strumento**).
9. Con misura di isolamento selezionata, lo strumento continua il test mantenendo in cortocircuito i terminali P e N ed eseguendo la prova tra questo punto e il terminale E per un tempo necessario ad ottenere un risultato stabile. Il valore della resistenza di isolamento è mostrato nel campo “`Rp`” (resistenza parallelo tra i valori R+ e R - ) e il messaggio “OK” in caso di esito positivo del test (**valore misurato superiore al limite minimo impostato sullo strumento**)
10. Con misura di continuità selezionata, lo strumento continua il test aprendo il cortocircuito ed eseguendo il test tra i terminali E e C. Il valore della resistenza nella prova di continuità è mostrato nel campo “`RPE`” e il messaggio “OK” in caso di esito positivo del test (**valore misurato inferiore al limite massimo impostato sullo strumento**)
11. Il messaggio “OK” è infine mostrato dallo strumento in caso di esito positivo di tutti i test eseguiti. Per l’interpretazione dei risultati vedere il § 6.8.7

```
I V C K   15/10   –   18:04
Voc@OPC   985   V   OK
Isc@OPC   11.25   A   OK
Voc Med   985   V
Isc Med   11.25   A
Rp   >100   M    OK
R+   >100   R -   >100   M    OK
RPE   1.1      OK
O K
1000V   1.00M    2    0.2   
VTest   ISO   RPE   >  <
```

12. Premere il tasto **SAVE** per salvare il risultato del test nella memoria dello strumento (vedere il § 7.1) o il tasto **ESC/MENU** per uscire dalla videata senza salvare e tornare alla videata principale di misura

---

**ATTENZIONE**
* Nella pagina dei risultati compaiono i valori medi di `Voc` e `Isc`. Tali valori contengono **i valori medi di `Voc` e `Isc` alle condizioni `OPC` calcolati come media scorrevole sulle ultime 10 prove precedentemente memorizzate**. Se l’utente ha eseguito e memorizzato un numero di prove `<10` oppure ha resettato i valori medi la media visualizzata nel corso della prova `N+1` saranno quelli calcolata su gli `N` valori disponibili
* In questa modalità di utilizzo dello strumento, i valori medi precedentemente calcolati assumono particolare importanza. Nel caso si inizi una nuova campagna di misura con variazioni significative di Irraggiamento o temperatura è **raccomandato azzerare (comando “`RIPRISTINA`” )** i valori medi di riferimento per poi farli ricalcolare sulle base di nuove misure. I valori medi sono azzerati **solo manualmente**

---

### 6.8.3. Test IVCK senza unità remota e misura di irraggiamento in modo diretto

**ATTENZIONE**
* La massima tensione tra gli ingressi P, N, E e C è `1000VDC`. Non misurare tensioni che eccedano i limiti espressi in questo manuale
* Non eseguire prove su moduli o stringhe FV connessi **all’inverter**
* La corrente massima misurabile dallo strumento è `30A`
* La norma IEC/EN62446-1 richiede di effettuare le misurazioni stringa per stringa. Anche se lo strumento è progettato per gestire la corrente di spunto per stringhe singole o in parallelo, si **raccomanda** di testare **una stringa per volta** in base alle prescrizioni della norma

**ATTENZIONE**
Questa modalità è **valida SOLO per moduli Monofacciali**

1. Selezionare la modalità “`Diretta`” nella sezione “`Irr.& Temperatura`” (vedere § 5.1.4)
2. Posizionare il cursore sulla voce `IVCK` utilizzando i tasti freccia (****, ****) e confermare con **ENTER**. A display appare la videata a fianco
    * `Irr.` **→** valori di irraggiamento misurato dalla cella `HT305` collegata all’ingresso “`IRR`” dello strumento
    * `Temp.` **→** valore di temperatura del modulo con sonda `PT305` collegata all’ingresso “`TEMP`” dello strumento oppure con misura di temperatura in modo “`AUTO`” o “`MAN`” senza sonda esterna collegata
    * `VTest` **→** valore della tensione di prova usata nella misura di isolamento
    * `ISO` **→** limite minimo nella misura di isolamento
    * `RPE` **→** limite massimo nella misura di continuità
    * `><` **→** valore calibrazione cavi nella misura `RPE`
    * Valori delle tensioni `VPN`, `VPE` e `VNE`

```
I V C K   15/10   –   18:04
Irr.   -   -   -   W/m2
Temp.   -   -   -   °C
Modulo   318WTH
V P N   V P E   V N E
9 8 0   V   4 9   0 V   -   4 9   0 V
1000V   1.00M    2    0.25 
VTest   ISO   RPE   >  <
```

3. Usare i tasti freccia (****, ****) per accedere alla programmazione dei parametri di misura. La videata a lato è mostrata a display. Usare i tasti (****, ****) per impostare i valori. Le seguenti opzioni sono disponibili
    * `Prod.` **→** Impostare nome costruttore del modulo (max 50) presente nel DB interno
    * `Nome` **→** Impostare il nome del modulo Monofacciale (max 50 caratteri) presente nel DB interno
    * `N. Mod x Str.` **→** impostare il numero dei moduli della stringa nel campo: `1 ÷ 60`
    * `N.Str.par.` **→** impostare il numero delle stringhe in parallelo nel campo: `1 ÷ 10`
    * `Mod. Temp` **→** impostare il modo di misura della temperatura dei moduli tra le opzioni:
        * `AUTO` **→** temperatura calcolata dallo strumento sulla base della misura di `Voc` (nessuna sonda collegata) – opzione raccomandata

```
I V C K   15/10   –   18:04
Prod.:      SUNPOWER   
Nome:      318WTH   
N.Mod. x Str.   :      12   
N.Str.par.   :      01   
Mod. Temp   :      AUTO   
:      -   -   -      °C
Tol. Voc   :      05      %
Tol.Isc   :      10      %
Avvia&Salva   :      MAN   
Avvia&Salva   :   RIAVVIO
Iso V.Test   :      1000      V
Iso R.Lim   :      1.00      M 
RPE lim   :      2      
Irr. & Temp.   :      Diretta   
Irrag. Min. [W/m2]   :      700   
Valori Med.   :   RIPRISTINA
Voc Med.   :   -   -   -
Isc Med.   :   -   -   -

```

        * `MIS` **→** temperatura misurata tramite sonda `PT305` collegata a unità remota
        * `MAN` **→** impostazione manuale temperatura modulo se nota a priori

---

    * `Tol. Voc` **→** impostare la tolleranza percentuale nella misura della `Voc` nel campo: `1% ÷ 15%` (tipico 5%)
    * `Tol. Isc` **→** impostare la tolleranza percentuale nella misura della `Isc` nel campo: `1% ÷ 15%` (tipico 10%)
    * `Avvia&Salva` **→** impostare la modalità della funzione avvio test tra le opzioni: `AUTO` (funzione attiva) o `MAN` (funzione non attiva)
    * `Avvia&Salva` **→** `RIAVVIO` **→** premere il tasto **SAVE** e confermare il riavvio del test solo se è già in corso una sequenza di `AutoSave` e si desidera modificare i marcatori a cui associare le successive misure da memorizzare
    * `Iso V. Test` **→** impostare la tensione di prova nella misura di isolamento tra le opzioni: `OFF` (esclusione misura), `250V`, `500V`, `1000VDC`
    * `Iso R.Lim` **→** impostare la soglia minima di riferimento nella misura di isolamento tra i valori: `0.05`, `0.10`, `0.23`, `0.25`, `0.50`, `1.00`, `50`, `100 MΩ`
    * `RPE Lim` **→** impostare il limite massimo nella misura di continuità tra i valori: `OFF` (esclusione misura), `1`, `2`, `3`, `4`, `5 Ω`
    * `Irr. & Temp.` **→** impostazione del tipo di misura di irraggiamento per la misura `IVCK` con opzione “`Diretta`” (vedere § 5.1.4)
    * `Irrag. Min [W/m2]` **→** impostazione della soglia minima di irraggiamento (per modi “Diretta” e “Unità Rem.”) (vedere § 5.1.4)
    * `Valori Med.` **→** la funzione “`RIPRISTINA`” consente di azzerare i valori medi dei parametri `Voc` e `Isc` prima di avviare una nuova misura
    * `Voc Med, Isc Med` **→** valori medi di `Voc` e `Isc` nelle 10 prove precedentemente salvate
4. Premere il tasto **SAVE** per salvare le impostazioni
5. Se necessario, selezionare l’opzione “`><`” e confermare con **ENTER**. Eseguire l’eventuale operazione come riportato nel § 6.3.1
6. Montare lo stelo sul disco dell’accessorio opzionale M304 e tenerlo appoggiato sul piano del modulo. Verificare che l’ombra dello stelo proiettata sul disco cada entro il “cerchio concentrico limite” interno al disco stesso (vedere figura a lato). In caso contrario l’angolo tra i raggi solari e la superficie del modulo è troppo elevato e pertanto le misure eseguite dallo strumento NON sono da ritenere attendibili. Ripetere le operazioni in altri momenti della giornata
7. Collegare lo strumento al modulo/stringa in prova ed eventualmente al nodo principale di terra dell’impianto e alle masse metalliche messe a terra come mostrato in Fig. 12. In particolare, collegare il polo Negativo in uscita dal modulo/stringa al terminale N, il polo Positivo in uscita dal modulo/stringa al terminale P, la cella di riferimento `HT305` sulla parte frontale del modulo e l’eventuale sonda di temperatura `PT305` nella parte posteriore del modulo

---

Fig. 12: Collegamento per test IVCK senza unità remota e misura irraggiamento diretta

**ATTENZIONE**
Alla pressione del tasto **GO/STOP** lo strumento può fornire diversi messaggi di errore (vedere § 6.9) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test

**ATTENZIONE**
Nel caso in cui si svolgano test su un **numero `N>1` di stringhe in parallelo**, la massima corrente di stringa gestibile dallo strumento risulta essere `30A/N`

8. Premere il tasto **GO/STOP** per attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura…`” e la misura della tensione a vuoto tra i terminali P e N e della corrente di cortocircuito (per valori di `Isc ≤ 30A`)

```
I V C K   15/10   –   18:04
Voc@STC   -   -   -   V
Isc@STC   -   -   -   A
Voc Nom   -   -   -   V
Isc Nom   -   -   -   A
Rp   -   -   -   M 
R+   -   -   -   R -   -   -   -   M 
RPE   -   -   -   
Misura…
1000V   1.00M    2    0.25 
VTest   ISO   RPE   >  <
```

9. Al termine delle misure di Voc e Isc il messaggio “OK” è fornito in caso di esito positivo del test (**valori misurati entro le tolleranze impostate sullo strumento**). I seguenti parametri sono mostrati:
    * Tensione `Voc` alle condizioni `STC` con relativo esito
    * Corrente `Isc` alle condizioni `STC` con relativo esito
    * Valore nominale della tensione `Voc@STC` usato come riferimento per l’esito
    * Valore nominale della corrente `Isc@STC` usato come riferimento per l’esito

```
I V C K   15/10   –   18:04
Voc@STC   985   V   OK
Isc@STC   11.25   A   OK
Voc Nom   985   V
Isc Nom   11.25   A
Rp   >100   M    OK
R+   >100   R -   >100   M    OK
RPE   1.1      OK
OK
1000V   1.00M    2    0.2   
VTest   ISO   RPE   >  <
```

---

10. Con misura di isolamento selezionata, lo strumento continua il test mantenendo in cortocircuito i terminali P e N ed eseguendo la prova tra questo punto e il terminale E per un tempo necessario ad ottenere un risultato stabile. Il valore della resistenza di isolamento è mostrato nel campo “`Rp`” (resistenza parallelo tra i valori R+ e R - ) e il messaggio “OK” in caso di esito positivo del test (**valore misurato superiore al limite minimo impostato sullo strumento**)
11. Con misura di continuità selezionata, lo strumento continua il test aprendo il cortocircuito ed eseguendo il test tra i terminali E e C. Il valore della resistenza nella prova di continuità è mostrato nel campo “`RPE`” e il messaggio “OK” in caso di esito positivo del test (**valore misurato inferiore al limite massimo impostato sullo strumento**)
12. Il messaggio “OK” è infine mostrato dallo strumento in caso di esito positivo di tutti i test eseguiti
13. Premere il tasto **SAVE** per salvare il risultato del test nella memoria dello strumento (vedere il § 7.1) o il tasto **ESC/MENU** per uscire dalla videata senza salvare e tornare alla videata principale di misura
14. Per l’interpretazione dei risultati vedere il § 6.8.7

---

### 6.8.4. Test IVCK con unità remota in connessione diretta

**ATTENZIONE**
* Verificare che sia correntemente attivata una unità remota. In caso contrario eseguire la procedura di connessione descritta al § 6.2
* La massima tensione tra gli ingressi P, N, E e C è `1000V DC`. Non misurare tensioni che eccedano i limiti espressi in questo manuale
* Non eseguire prove su moduli o stringhe FV connessi all’inverter
* La corrente massima misurabile dallo strumento è `30A`
* La norma IEC/EN62446-1 richiede di effettuare le misure su singole stringhe. Anche se lo strumento è progettato per gestire la corrente di spunto per stringhe singole o in parallelo, si **raccomanda** di testare **una stringa per volta** in base alle prescrizioni della normativa

1. Selezionare la modalità “`U. Rem.`” nella sezione “`Irrag. & Temperatura`” (vedere § 5.1.4)
2. Selezionare l’opzione `UREM` nel menu principale per associare e collegare l’unità remota `SOLAR03` tramite Bluetooth come mostrato nel § 6.2
3. Collegare lo strumento al modulo/stringa in prova ed eventualmente al nodo principale di terra dell’impianto e alle masse metalliche messe a terra come mostrato in Fig. 13. In particolare:
    * Collegare il polo Negativo in uscita dal modulo/stringa al terminale `N` e il polo Positivo in uscita dal modulo/stringa al terminale `P`
    * Nel caso di moduli Monofacciali **→** posizionare la cella di riferimento `HT305` sul piano frontale del modulo (F) e all’ingresso “`INP1`” ed **eventualmente** la sonda di temperatura `PT305` all’ingresso “`INP4`” dell’unità remota
    * Nel caso di moduli Bifacciali **→** posizionare le **3 celle di riferimento** `HT305` rispettivamente sul piano frontale (F), sulla parte posteriore superiore (BH = Back High) e sulla parte posteriore inferiore (BL = Back Low) del modulo. Collegare la cella di riferimento frontale (F) all’ingresso “`INP1`”, la cella di riferimento BH all’ingresso “`INP2`”, la cella di riferimento BL all’ingresso “`INP3`” ed **eventualmente** la sonda di temperatura `PT305` all’ingresso “`INP4`” dell’unità remota. In accordo alla normativa IEC/EN60904-1-2, lo strumento calcola il valore di Irraggiamento frontale equivalente (`Irreq`) che corrisponde all’Irraggiamento sul solo piano frontale producente gli stessi effetti dell’Irraggiamento rilevato su entrambe le facce tenendo conto del **coefficiente di bifaccialità** (`φ`) del modulo in base alla seguente relazione:
        `IrrEq = IrrF + φ × IrrR`
        In cui `IrrR = min (IrrBL, IrrBH)`
4. Se necessario, selezionare l’opzione “`><`” e confermare con **ENTER**. Eseguire l’eventuale operazione di calibrazione dei cavi come riportato nel § 6.3.1

---

Fig. 13: Uso con SOLAR03 in connessione diretta su moduli Mono/Bifacciali

5. Posizionare il cursore sulla voce `IVCK` utilizzando i tasti freccia (****, ****) e confermare con **ENTER**. A display appare la videata a fianco. I seguenti parametri sono mostrati in caso di **moduli Monofacciali**
    * `Irr.` **→** valori di irraggiamento misurato dalla cella `HT305` collegata all’unità remota
    * `Temp.` **→** valore di temperatura del modulo
    * `Unità remota` **→** indicazioni su numero di serie, stato di connessione “`✓`”
    * `VTest` **→** tensione di prova nella misura si isolamento
    * `ISO` **→** limite minimo nella misura di isolamento
    * `RPE` **→** limite massimo nella misura di continuità
    * `><` **→** valore della resistenza di calibrazione dei cavi nella misura di continuità
    * Valori delle tensioni `VPN`, `VPE` e `VNE`

```
I V C K   15/10   –   18:04
Irr.   720   W/m2
Temp.   45.3   °C
SOLAR03   23051203
Modulo:   318WTH
V P N   V P E   V N E
9 8 0 V   4 9 0 V   -   4 9 0 V
1000V   1.00M    2    0.25 
VTest   ISO   RPE   >  <
```

6. I seguenti parametri sono mostrati in caso di moduli **Bifacciali**
    * `Irr.` **→** valori di irraggiamento misurato dalle celle `HT305` collegate all’unità remota (`Front` = frontale, `Btop` = posteriore parte alta, `Bbot.` = posteriore parte bassa)
    * `Temp.` **→** valore di temperatura del modulo
    * `Unità remota` **→** indicazioni su numero di serie, stato di connessione “`✓`”
    * `VTest` **→** tensione di prova nella misura si isolamento
    * `ISO` **→** limite minimo nella misura di isolamento
    * `RPE` **→** limite massimo nella misura di continuità
    * `><` **→** valore della resistenza di calibrazione dei cavi nella misura di continuità
    * Valori delle tensioni `VPN`, `VPE` e `VNE`

```
I V C K   15/10   –   18:04
Front   Btop   Bbot.
Irr.   920   125   95   W/m2
Temp.   54.7   °C
SOLAR03   23051203
Modulo:   JKM575N - 72HL4 - BDV
V P N   V P E   V N E
9 8 0 V   4 9 0 V   -   4 9 0 V
1000V   1.00M    2    0.25 
VTest   ISO   RPE   >  <
```

---

7. Usare i tasti freccia (****, ****) per accedere alla programmazione dei parametri di misura. La videata a lato è mostrata a display. Usare i tasti (****, ****) per impostare i valori. Le seguenti opzioni sono disponibili
    * `Prod.` **→** Impostare il produttore del modulo presente nel DB interno
    * `Nome` **→** Impostare il modulo presente nel DB interno. Se in fase di inserimento nel database, il modulo è stato definito come “Bifacciale” lo strumento e l’unità remota provvederanno automaticamente a leggere 3 valori di irraggiamento
    * `N. Mod x Str.` **→** impostare il numero dei moduli della stringa nel campo: `1 ÷ 60`
    * `N. Str par.` **→** impostare il numero delle stringhe in parallelo nel campo: `1 ÷ 10`

```
I V C K   15/10   –   18:04
Prod.      SUNPOWER   
Nome:      318WTH   
N.Mod. x S tr.   :      1 2   
N.Str.par.   :      0 1   
Mod. Temp   :      AUTO   
:      -   -   -      °C
Tol. Voc   :      05      %
Tol.Isc   :      10      %
A vvia&Salva   :      MAN   
Avvia&Salva   :   RIAVVIO
Iso V.Test   :      1000      V
Iso R.Lim   :      1.00      M 
RPE lim   :      2      
Irr. & Temp.   :      U.Rem .   
Irrag. Min. [W/m2]   :      700   
Valori Med.   :   RIPRISTINA
Voc Med.   :   -   -   -   V
Isc Med.   :   -   -   -   A

```

    * `Mod. Temp` **→** impostare il modo di misura della temperatura dei moduli tra le opzioni:
        * `AUTO` **→** temperatura calcolata dallo strumento sulla base della misura di `Voc` (nessuna sonda collegata) – opzione raccomandata
        * `MIS` **→** temperatura misurata tramite sonda `PT305` collegata a unità remota
        * `MAN` **→** impostazione manuale della temperatura del modulo se nota nel campo successivo
    * `Tol. Voc` **→** impostare la tolleranza percentuale nella misura della `Voc` nel campo: `1% ÷ 15%` (tipico 5%)
    * `Tol. Isc` **→** impostare la tolleranza percentuale nella misura della `Isc` nel campo: `1% ÷ 15%` (tipico 10%)
    * `Avvia&Salva` **→** impostare la modalità della funzione avvio test tra le opzioni: `AUTO` (funzione attiva) o `MAN` (funzione non attiva)
    * `Avvia&Salva` **→** `RIAVVIO` **→** premere il tasto **SAVE** e confermare il riavvio del test solo se è già in corso una sequenza di `AutoSave` e si desidera modificare i marcatori a cui associare le successive misure da memorizzare
    * `Iso V.Test` **→** impostare la tensione di prova nella misura di isolamento tra le opzioni: `OFF` (esclusione misura), `250V`, `500V`, `1000VDC`
    * `Iso R.Lim` **→** impostare la soglia minima di riferimento nella misura di isolamento tra i valori: `0.05`, `0.10`, `0.23`, `0.25`, `0.50`, `1.00`, `50`, `100 MΩ`
    * `RPE Lim` **→** impostare il limite massimo nella misura di continuità tra i valori: `OFF` (esclusione misura), `1`, `2`, `3`, `4`, `5 Ω`
    * `Irr. & Temp.` **→** impostazione del tipo di misura di irraggiamento per la misura `IVCK` con opzione “`U. Rem.`” (vedere § 5.1.4)
    * `Irrag. Min [W/m2]` **→** impostazione della soglia minima di irraggiamento (per modi “Diretta” e “U. Rem.”) (vedere § 5.1.4)
    * `Valori Med.` **→** la funzione “`RIPRISTINA`” consente di azzerare i valori medi di parametri `Voc` e `Isc` prima di avviare una nuova misura
    * `Voc Med, Isc Med` **→** valori medi di `Voc` e `Isc` nelle 10 prove precedentemente salvate
8. Premere il tasto **SAVE** per salvare le impostazioni e tornare alla videata precedente

---

9. Montare lo stelo sul disco dell’accessorio opzionale M304 e tenerlo appoggiato sul piano del modulo. Verificare che l’ombra dello stelo proiettata sul disco cada entro il “cerchio concentrico limite” interno al disco stesso (vedere figura a lato). In caso contrario l’angolo tra i raggi solari e la superficie del modulo è troppo elevato e pertanto le misure eseguite dallo strumento NON sono da ritenere attendibili. Ripetere le operazioni in altri momenti della giornata

**ATTENZIONE**
* Alla pressione del tasto **GO/STOP** lo strumento può fornire diversi messaggi di errore (vedere § 6.9) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test
* Le impostazioni eseguite sui parametri di controllo dello strumento possono essere modificate in ogni momento anche con registrazione in corso

**ATTENZIONE**
Nel caso in cui si svolgano test su un **numero `N>1` di stringhe in parallelo**, la massima corrente di stringa gestibile dallo strumento risulta essere `30A/N`

10. Premere il tasto **GO/STOP** per attivare il test. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura…`” e la misura della tensione a vuoto tra i terminali P e N e della corrente di cortocircuito (per valori di `Isc ≤ 30A`)

```
I V C K   15/10   –   18:04
Voc@ STC   -   -   -   V
Isc@ STC   -   -   -   A
Voc   Nom   -   -   -   V
Isc   Nom   -   -   -   A
Rp   -   -   -   M 
R+   -   -   -   R -   -   -   -   M 
RPE   -   -   -   
Misura…
1000V   1.00M    2    0.25 
VTest   ISO   RPE   >  <
```

11. Al termine delle misure di Voc e Isc il messaggio “OK” è fornito in caso di esito positivo del test (**valori misurati entro le tolleranze impostate sullo strumento**). I seguenti parametri sono mostrati:
    * Tensione `Voc` alle condizioni `STC` con relativo esito
    * Corrente `Isc` alle condizioni `STC` con relativo esito
    * Valore nominale della tensione `Voc@STC` usato come riferimento per l’esito
    * Valore nominale della corrente `Isc@STC` usato come riferimento per l’esito

```
I V C K   15/10   –   18:04
Voc@ STC   9 85   V   OK
Isc@ STC   11.25   A   OK
Voc   Nom   9 85   V
Isc   Nom   11.25   A
Rp   >100   M    OK
R+   >100   R -   >100   M    OK
RPE   1.1      OK
OK
1000V   1.00M    2    0.2   
VTest   ISO   RPE   >  <
```

---

12. Con misura di isolamento selezionata, lo strumento continua il test mantenendo in cortocircuito i terminali P e N ed eseguendo la prova tra questo punto e il terminale E per un tempo necessario ad ottenere un risultato stabile. Il valore della resistenza di isolamento è mostrato nel campo “`Rp`” (resistenza parallelo tra i valori R+ e R - ) e il messaggio “OK” in caso di esito positivo del test (**valore misurato superiore al limite minimo impostato sullo strumento**)
13. Con misura di continuità selezionata, lo strumento continua il test aprendo il cortocircuito ed eseguendo il test tra i terminali E e C. Il valore della resistenza nella prova di continuità è mostrato nel campo “`RPE`” e il messaggio “OK” in caso di esito positivo del test (**valore misurato inferiore al limite massimo impostato sullo strumento**)
14. Il messaggio “OK” è infine mostrato dallo strumento in caso di esito positivo di tutti i test eseguiti
15. Premere il tasto **SAVE** per salvare il risultato del test nella memoria dello strumento (vedere il § 7.1) o il tasto **ESC/MENU** per uscire dalla videata senza salvare e tornare alla videata principale di misura
16. Per l’interpretazione dei risultati vedere il § 6.8.7

---

### 6.8.5. Test IVCK con unità remota in registrazione

In questa modalità, l’unità remota `SOLAR03` attiva **deve essere collegata in Bluetooth solo all’INIZIO e alla FINE delle operazioni** e **NON DURANTE** le reali misure di irraggiamento e temperatura. Lo strumento fornisce i risultati delle misure `@OPC` senza esito poi esegue la traslazione automatica e simultanea `@STC` solo dopo il trasferimento dei dati dall’unità remota al termine della registrazione e al successivo ricollegamento.

**ATTENZIONE**
* Verificare che sia correntemente attivata una unità remota. In caso contrario eseguire la procedura di connessione descritta al § 6.2
* La massima tensione tra gli ingressi P, N, E e C è `1000V DC`. Non misurare tensioni che eccedano i limiti espressi in questo manuale
* Non eseguire prove su moduli o stringhe FV connessi **all’inverter**
* La corrente massima misurabile dallo strumento è `30A`
* La norma IEC/EN62446-1 richiede di effettuare le misure su singole stringhe. Anche se lo strumento è progettato per gestire la corrente di spunto per stringhe singole o in parallelo, si **raccomanda** di testare **una stringa per volta** in base alle prescrizioni della normativa

1. Selezionare la modalità “`U. Rem.`” nella sezione “`Irrag. & Temperatura`” (vedere § 5.1.4)
2. Collegare lo strumento al modulo/stringa in prova ed eventualmente al nodo principale di terra dell’impianto e alle masse metalliche messe a terra come mostrato nelle Fig. 14 (moduli Monofacciali) o Fig. 15 (moduli Bifacciali). In particolare:
    * Collegare il polo Negativo in uscita dal modulo/stringa al terminale `N` e il polo Positivo in uscita dal modulo/stringa al terminale `P`
    * Nel caso di moduli Monofacciali **→** posizionare la cella di riferimento `HT305` rispettivamente sul piano frontale del modulo (F) e all’ingresso “`INP1`” ed **eventualmente** la sonda di temperatura `PT305` all’ingresso “`INP4`” dell’unità remota
    * Nel caso di moduli Bifacciali **→** posizionare le **3 celle di riferimento** `HT305` sul piano frontale del modulo (F), sulla parte posteriore superiore (`BH = Back High`) e sulla parte posteriore inferiore (`BL = Back Low`) del modulo. Collegare la cella di riferimento frontale (F) all’ingresso “`INP1`”, la cella di riferimento BH all’ingresso “`INP2`”, la cella di riferimento BL all’ingresso “`INP3`” ed **eventualmente** la sonda di temperatura `PT305` all’ingresso “`INP4`” dell’unità remota. In accordo alla normativa IEC/EN60904-1-2, lo strumento calcola il valore di Irraggiamento frontale equivalente (`Irreq`) che corrisponde all’Irraggiamento sul solo piano frontale producente gli stessi effetti dell’Irraggiamento rilevato su entrambe le facce tenendo conto del **coefficiente di bifaccialità** (`φ`) del modulo in base alla seguente relazione:
        `IrrEq = IrrF + φ × IrrR`
        In cui `IrrR = min (IrrBL, IrrBH)`
3. Se necessario, selezionare l’opzione “`><`” e confermare con **ENTER**. Eseguire l’eventuale operazione di calibrazione dei cavi come riportato nel § 6.3.1

---

Fig. 14: Uso con SOLAR03 in **registrazione** su moduli Monofacciali
Fig. 15: Uso con SOLAR03 in **registrazione** su moduli Bifacciali

**Fase 1**
4. Avvicinare l’unità remota `SOLAR03` allo strumento come mostrato nelle Fig. 14 o Fig. 15 – parte sinistra
5. Selezionare l’opzione `UREM` nel menu principale, associare e collegare l’unità remota `SOLAR03` in collegamento Bluetooth allo strumento come mostrato nel punto 6 del § 6.2
6. Usando i tasti freccia **** o **** selezionare la posizione “`Avvio`” per avviare la registrazione (con scansione di **1s** non modificabile) nell’unità remota da parte dello strumento. La videata a lato è mostrata a display. In questa condizione lo strumento invia la propria data/ora di sistema all’unità remota `SOLAR03` che quindi è con esso sincronizzata temporalmente. Il simbolo “`REC`” è mostrato a display e il messaggio “`REC`” appare a display dell’unità remota ad indicare la registrazione in corso

```
U R E M   15/10   –   18:04
SOLAR03   Att   Stato   Reg.
23051204   √
U . R e m .   C o l l e g a t a
Cerca   Disass.   Canc   Avvio
```

**Fase 2**
7. Portare l’unità remota in prossimità dei moduli e collegare le sonde di irraggiamento/temperatura come mostrato nelle Fig. 14 o Fig. 15 – parte centrale. Avendo già avviato la registrazione sulla unità remota `SOLAR03` **non è necessario il mantenimento della connessione Bluetooth**. Il mantenimento della connessione (se possibile) consentirà solamente il poter avere immediatamente l’esito della prova senza attendere la fine della campagna di misure

---

8. Posizionare il cursore sulla voce `IVCK` utilizzando i tasti freccia (****, ****) e confermare con **ENTER**. A display appare la videata a fianco. I seguenti parametri sono mostrati (caso moduli Monofacciali):
    * `Irr.` **→** valore di irraggiamento non indicato “`- - -`“ in quanto unità remota non connessa allo strumento
    * `Temp.` **→** valore di temperatura del modulo non indicato “`- - -`“ in quanto unità remota non connessa
    * `Unità remota` **→** indicazioni su numero di serie, stato di connessione “`✓`” e registrazione in corso “`REC`” dell’unità remota `SOLAR03` collegata e attiva
    * `VTest` **→** tensione di prova nella misura si isolamento
    * `ISO` **→** limite minimo nella misura di isolamento
    * `RPE` **→** limite massimo nella misura di continuità
    * `><` **→** valore della resistenza di calibrazione dei cavi nella misura di continuità
    * Valori delle tensioni `VPN`, `VPE` e `VNE`

```
I V C K   15/10   –   18:04
Irr.   -   -   -   W/m2
Temp.   -   -   -   °C
SOLAR03   23051203
Modulo:   318WTH
V P N   V P E   V N E
9 8 0 V   4 9 0 V   -   4 9 0 V
1000V   1.00M    2    0.25 
VTest   ISO   RPE   >  <
```

9. Usare i tasti freccia (****, ****) per accedere alla programmazione dei parametri di misura. La videata a lato è mostrata a display. Usare i tasti (****, ****) per impostare i valori. Le seguenti opzioni sono disponibili
    * `Prod.` **→** Impostare costruttore del modulo presente nel DB interno
    * `Nome` **→** Impostare il modulo presente nel DB interno
    * `N. Mod x Str.` **→** numero moduli stringa: `1 ÷ 60`
    * `N. Str par.` **→** stringhe in parallelo nel campo: `1 ÷ 10`
    * `Mod. Temp` **→** modo di misura temperatura con opzioni:
        * `AUTO` **→** temperatura calcolata sulla base della misura di `Voc` (nessuna sonda collegata) – opzione raccomandata
        * `MIS` **→** temperatura misurata tramite `PT305` collegata a unità remota

```
I V C K   15/10   –   18:04
Prod.      SUNPOWER   
Nome:      318WTH   
N.Mod. x Str.   :      12   
N.Str.in par.   :      01   
Mod. Temp   :      AUTO   
:      -   -   -      °C
Tol. Voc   :      05      %
Tol.Isc   :      10      %
Avvia&Salva   :      MAN   
Avvia&Salva   :   RIAVVIO
Iso V.Test   :      1000      V
Iso R.Lim   :      1.00      M 
RPE lim   :      2      
Irr. & Temp.   :      U.Rem.   
Irrag. Min. [W/m2]   :      700   
Valori Med.   :   RIPRISTINA
Voc Med.   :   -   -   -   V
Isc Med.   :   -   -   -   A

```

        * `MAN` **→** impostazione manuale della temperatura del modulo se nota
    * `Tol. Voc` **→** tolleranza % `Voc`: `1% ÷ 15%` (tipico 5%)
    * `Tol. Isc` **→** tolleranza % `Isc`: `1% ÷ 15%` (tipico 10%)
    * `Avvia&Salva` **→** impostare la modalità della funzione avvio test tra le opzioni: `AUTO` (funzione attiva) o `MAN` (funzione non attiva)
    * `Avvia&Salva` **→** `RIAVVIO` **→** premere il tasto **SAVE** e confermare il riavvio del test solo se è già in corso una sequenza di `AutoSave` e si desidera modificare i marcatori a cui associare le successive misure da memorizzare
    * `Iso V. Test` **→** tensione di prova isolamento tra: `OFF` (esclusione misura), `250V`, `500V`, `1000VDC`
    * `Iso R.Lim` **→** soglia minima isolamento tra: `0.05`, `0.10`, `0.23`, `0.25`, `0.50`, `1.00`, `50`, `100 MΩ`
    * `RPE Lim` **→** limite massimo continuità tra i valori: `OFF`, `1`, `2`, `3`, `4`, `5 Ω`
    * `Irr. & Temp.` **→** impostazione misura irraggiamento con opzione “`U. Rem.`”
    * `Irrag. Min [W/m2]` **→** impostazione soglia minima di irraggiamento (vedere § 5.1.4)
    * `Valori Med.` **→** la funzione “`RIPRISTINA`” consente di azzerare i valori medi di parametri `Voc` e `Isc` prima di avviare una nuova misura
    * `Voc Med, Isc Med` **→** valori medi di `Voc` e `Isc` nelle 10 prove salvate
10. Premere il tasto **SAVE** per salvare le impostazioni e tornare alla videata precedente

---

11. Montare lo stelo sul disco dell’accessorio opzionale M304 e tenerlo appoggiato sul piano del modulo. Verificare che l’ombra dello stelo proiettata sul disco cada entro il “cerchio concentrico limite” interno al disco stesso (vedere figura a lato). In caso contrario l’angolo tra i raggi solari e la superficie del modulo è troppo elevato e pertanto le misure eseguite dallo strumento NON sono da ritenere attendibili. Ripetere le operazioni in altri momenti della giornata

**ATTENZIONE**
* Alla pressione del tasto **GO/STOP** lo strumento può fornire diversi messaggi di errore (vedere § 6.9) e, per effetto di essi, non eseguire il test. Controllare ed eliminare, se possibile, le cause dei problemi prima di proseguire con il test
* Le impostazioni eseguite sui parametri di controllo dello strumento possono essere modificate in ogni momento anche con registrazione in corso

**ATTENZIONE**
Nel caso in cui si svolgano test su un **numero `N>1` di stringhe in parallelo**, la massima corrente di stringa gestibile dallo strumento risulta essere `30A/N`

12. Premere il tasto **GO/STOP** per attivare i test desiderati sulle stringhe in esame. In caso di assenza di condizioni di errore, lo strumento visualizza il messaggio “`Misura…`” e la misura della tensione a vuoto tra i terminali P e N e della corrente di cortocircuito (per valori di `Isc ≤ 30A`)

```
I V C K   15/10   –   18:04
Voc@STC   -   -   -   V
Isc@STC   -   -   -   A
Voc Nom   -   -   -   V
Isc Nom   -   -   -   A
Rp   -   -   -   M 
R+   -   -   -   R   -   -   -   M 
RPE   -   -   -   
Misura …
1000V   1.00M    2    0.25 
VTest   ISO   RPE   >  <
```

13. Al termine delle misure di `Voc` e `Isc` lo strumento visualizzerà **solo i valori misurati ad `OPC`** ed occorre attendere la fine della sessione di prove e **la successiva sincronizzazione** con l’unità remota `SOLAR03` per ottenere l’esito finale delle prove eseguite. I seguenti parametri sono mostrati:
    * Tensione `Voc` alle condizioni `OPC`
    * Corrente `Isc` alle condizioni `OPC`
    * Valore nominale della tensione `Voc@STC`
    * Valore nominale della corrente `Isc@STC`

```
I V C K   15/10   –   18:04
Voc@ OPC   9 85   V
Isc@ OPC   11.25   A
Voc Nom   9 85   V
Isc Nom   11.25   A
Rp   >100   M    OK
R+   >100   R -   >100   M    OK
RPE   1.1      OK
1000V   1.00M    2    0.2   
VTest   ISO   RPE   >  <
```

<!-- Chunk: Pages 65-96 -->
**PVCHECKs - ONE IT**

14. Con misura di isolamento selezionata, lo strumento continua il test mantenendo in cortocircuito i terminali P e N ed eseguendo la prova tra questo punto e il terminale E per un tempo necessario ad ottenere un risultato stabile. Il valore della resistenza di isolamento è mostrato nel campo “`Rp`” (resistenza parallelo tra i valori R+ e R-) e il messaggio “`OK`” in caso di esito positivo del test (valore misurato superiore al limite minimo impostato sullo strumento).
15. Con misura di continuità selezionata, lo strumento continua il test aprendo il cortocircuito ed eseguendo il test tra i terminali E e C. Il valore della resistenza nella prova di continuità è mostrato nel campo “`RPE`” e il messaggio “`OK`” in caso di esito positivo del test (valore misurato inferiore al limite massimo impostato sullo strumento).
16. Premere il tasto **SAVE** per salvare il risultato del test nella memoria dello strumento (vedere il § `7.1`) o il tasto **ESC/MENU** per uscire dalla videata senza salvare e tornare alla videata principale di misura.

### Fase 3

17. Al **termine della sessione di prove** scollegare l’unità remota SOLAR03, riportarla in prossimità dello strumento (vedere `Fig. 14` o `Fig. 15` – parte destra) e verificare che il collegamento con lo strumento sia nuovamente attivo (simbolo “` `” acceso in modo fisso a display dell’unità remota).
18. Entrare nella sezione `UREM` e, con i **tasti freccia** `` o ``, selezionare la posizione “`Stop`” per terminare la registrazione nell’unità remota da parte dello strumento. La videata a lato è mostrata a display. Il simbolo “` `” scompare a display e il messaggio “`REC`” scompare a display dell’unità remota.

    In questa fase l’unità remota scarica i valori di irraggiamento/temperatura registrati nella campagna di misura che sono usati dallo strumento per la conversione automatica dei valori di Voc e Isc alle condizioni STC.

    ```
    U R E M   15/10 – 18:04
    SOLAR03   Att   Stato   Reg.
    23051204   √
    U . R e m .   C o l l e g a t a
    Cerca   Disass.   Canc   Stop
    ```
19. I dati presenti delle misure precedentemente salvate in memoria saranno aggiornati con i valori calcolati alle condizioni STC e sarà conseguentemente disponibile il messaggio “`OK`” in caso di esito positivo di tutti i test eseguiti (valori misurati entro le tolleranze impostate sullo strumento).

    ```
    I V C K   15/10 – 18:04
    Voc@STC   985   V   OK
    Isc@STC   11.25   A   OK
    Voc   Nom   985   V
    Isc   Nom   11.25   A
    Rp   >100   MΩ   OK
    R+   >100   R -   >100   MΩ   OK
    RPE   1.1   Ω   OK
    O K
    1000V   1.00MΩ   2Ω   0.2Ω
    VTest   ISO   RPE   ><
    ```
20. Per l’interpretazione dei risultati vedere il § `6.8.7`.

**PVCHECKs - ONE IT**

**ATTENZIONE**
Lo strumento esegue la traslazione dei valori `@OPC` a quelli `@STC` al verificarsi delle seguenti condizioni:
* Tensione `Voc > Voc minima = 15V`
* Valori di irraggiamento frontale (valido anche per moduli Bifacciali) rilevati maggiori della soglia minima impostata sullo strumento (`>100W/m^2`) e stabili (variazione tra inizio e fine campagna di misura `±20 W/m^2`)
* Tensione a vuoto Voc misurata coerente con valore atteso indicato nel datasheet del modulo
* Valore di temperatura del modulo compreso nel campo `-40°C ÷ 100°C`
* Valore della corrente di cortocircuito `Isc > Iscmin = 0.2A`

### 6.8.6. Test IVCK con uso funzione Avvia&Salva

**ATTENZIONE**
* La massima tensione tra gli ingressi P, N, E e C è 1000VDC. Non misurare tensioni che eccedano i limiti espressi in questo manuale.
* Non eseguire prove su moduli o stringhe FV connessi all’inverter.
* La corrente massima misurabile dallo strumento è 30A.
* La norma IEC/EN62446-1 richiede di effettuare le misure su **singole stringhe**. Anche se lo strumento è progettato per gestire la corrente di spunto per stringhe singole o in parallelo, si **raccomanda** di testare **una stringa per volta** in base alle prescrizioni della normativa.

**ATTENZIONE**
* La funzione `Avvia&Salva` è utilizzabile in ogni configurazione di misura dei parametri ambientali di irraggiamento e temperatura.
* La funzione `Avvia&Salva` è disponibile **SOLO per test IVCK** e **non per test singoli di RPE, MΩ o GFL**.
* La funzione `Avvia&Salva` è **automaticamente disabilitata** all’uscita della funzione IVCK e/o in caso di spegnimento dello strumento.
* Lo scopo della funzione `Avvia&Salva` è quello di **minimizzare i tempi di esecuzione** del test IVCK in situazioni ripetitive e con circuiti tra loro ravvicinati come gli elementi a fusibile. È **fortemente sconsigliato** l’uso di tale funzione in assenza di fusibili di protezione di stringhe all’interno di quadri di campo e/o quadri combinatori FV.

1. Per semplicità, la seguente procedura è relativa al **test IVCK senza unità remota e senza misura di irraggiamento**. Considerazioni analoghe valgono per tutte le altre modalità.
2. Posizionare il cursore sulla voce `IVCK` utilizzando i tasti freccia (``, ``) e **confermare** con **ENTER**. I seguenti parametri sono mostrati:
    * `VTest` → tensione di prova nella misura di isolamento
    * `ISO` → limite minimo nella misura di isolamento
    * `RPE` → limite massimo nella misura di continuità
    * `><` → resistenza calibrazione cavi misura di continuità
    * Valori delle tensioni VPN, VPE e VNE

    ```
    I V C K   15/10 – 18:04   AS&S
    M i s .   I r r .   n o n   a t t i v a
    Modulo   318WTH
    V P N   V P E   V N E
    0 V   0 V   0 V
    1000V   1.00MΩ   2Ω
    VTest   ISO   RPE   ><
    ```

**PVCHECKs - ONE IT**

3. Usare i **tasti freccia** (``, ``) per accedere alla programmazione dei parametri di misura. La videata a lato è mostrata a display. Usare i tasti (``, ``) per impostare i valori. Le seguenti opzioni sono disponibili:
    * `Prod.` → Impostare il **costruttore del modulo** presente nel DB interno.
    * `Nome` → Impostare il **modulo** presente nel DB interno.
    * `N. Mod x Str.` → impostare il numero dei moduli della stringa nel campo: `1 ÷ 60`.
    * `N. Str par.` → impostare il numero delle stringhe in parallelo nel campo: `1 ÷ 10`.
    * `Mod.Temp.` → impostare il **modo misura della temperatura** dei moduli tra le opzioni:
        * `AUTO` → temperatura calcolata dallo strumento sulla base della misura di Voc (nessuna sonda collegata) – opzione raccomandata.
        * `MIS` → temperatura misurata tramite sonda PT305 collegata a unità remota.
        * `MAN` → impostazione manuale della temperatura del modulo se nota a priori.
    * `Tol. Voc` → impostare la tolleranza percentuale nella misura della Voc nel campo: `1% ÷ 15%` (tipico 5%).
    * `Tol. Isc` → impostare la tolleranza percentuale nella misura della Isc nel campo: `1% ÷ 15%` (tipico 10%).
    * `Avvia&Salva` → impostare modalità di avvio prova in modo `AUTO` (funzione attiva). Il simbolo “`AS&S`” è mostrato a display.
    * `Avvia&Salva` → `RIAVVIO` → premere il tasto **SAVE** e confermare il riavvio del test solo se è già in corso una sequenza di AutoSave e si desidera modificare i marcatori a cui associare le successive misure da memorizzare.
    * `Iso V. Test` → impostare la tensione di prova nella misura di isolamento tra le opzioni: `OFF` (esclusione misura), `250V`, `500V`, `1000VDC`.
    * `Iso R.Lim` → impostare la soglia minima di riferimento nella misura di isolamento tra i valori: `0.05`, `0.10`, `0.23`, `0.25`, `0.50`, `1.00`, `50`, `100 MΩ`.
    * `RPE Lim` → impostare il limite massimo nella misura di continuità tra i valori: `OFF` (esclusione misura), `1`, `2`, `3`, `4`, `5 Ω`.
    * `Irr. & Temp.` → impostazione del tipo di misura di irraggiamento per la misura IVCK (vedere § `5.1.4`).
    * `Irrag. Min [W/m2]` → impostazione della soglia minima di irraggiamento (per modi “Diretta” e “U. Rem.”) (vedere § `5.1.4`).
    * `Valori Med.` → la funzione “`RIPRISTINA`” consente di azzerare i valori medi di parametri Voc e Isc prima di avviare una nuova misura.
    * `Voc Med, Isc Med` → valori medi di Voc e Isc nelle 10 prove precedentemente salvate.

    ```
    I V C K   15/10 – 18:04   AS&S
    Prod.:      SUNPOWER   
    Nome:      318WTH   
    N.Mod. x Str.   :      12   
    N.Str. par.   :      01   
    Mod.Temp.   :      AUTO   
    :      - - -   
    Tol. Voc   :      05      %
    Tol.Isc   :      10      %
    Avvia&Salva   :      AUTO   
    Avvia&Salva   :   RIAVVIO
    Iso V.Test   :      1000      V
    Iso R.Lim   :      1.00      MΩ
    RPE lim   :      2      Ω
    Irr. & Temp.   :      OFF   
    Irrag. Min. [W/m2]   :      700   
    Valori Med.   :   RIPRISTINA
    Voc Med   :   - - -   V
    Isc Med   :   - - -   A
    
    ```
4. Premere il tasto **SAVE** per salvare le impostazioni.
5. Se necessario, selezionare l’opzione “`><`” e confermare con **ENTER** (vedere `§ 6.3.1`).
6. All’interno di un **quadro di campo FV** sezionare tutti i fusibili associati ai poli positivi delle stringhe. Sezionare per sicurezza i fusibili connessi su entrambi i poli.
7. Collegare lo strumento come mostrato in `Fig. 16`. In particolare, collegare il polo **Negativo** della barra all’ingresso **N** tramite collegamento fisso con terminale a coccodrillo, il polo **Positivo** della barra all’ingresso **P** tramite collegamento fisso con terminale a coccodrillo, il **nodo principale di terra** dell’impianto (per test MΩ e RPE) all’ingresso **E** ed eventualmente l’ingresso **C** alle masse metalliche (per test RPE).

**PVCHECKs - ONE IT**

`Fig. 16`: Collegamento strumento in test IVCK con uso di funzione Avvia&Salva

8. Ripristinare il fusibile associato alla **PRIMA** stringa in prova.
9. Avviare la sequenza del test IVCK (con eventuale MΩ e RPE) con il tasto **GO/STOP**.
10. Se la sequenza di test è conclusa correttamente, lo strumento presenta a display:
    * La pagina dell’esito per qualche secondo come mostrato nella videata seguente.
    * La pagina dell’area di memoria con la visualizzazione dei marcatori (vedere `§ 7.1`). Modificare i valori dei marcatori ed eventuale commento in maniera coerente alla posizione della misura appena effettuata.
    * Premere il tasto **SAVE** per salvare i risultati del test.

    ```
    I V C K   15/10 – 18:04   AS&S
    M i s .   I r r .   n o n   a t t i v a
    Modulo   318WTH
    V P N   V P E   V N E
    9 8 0 V   4 9 0 V   - 4 9 0 V
    Scollegare circuito
    1000V   1.00MΩ   2Ω
    VTest   ISO   RPE   ><
    ```
11. Dopo il salvataggio del test, lo strumento torna alla videata iniziale e mostra il messaggio “`Scollegare circuito`”.
12. Sezionare il fusibile della stringa appena testata.
13. Ripristinare il fusibile associato alla successiva stringa da testare.
14. Quando lo strumento rileva nuovamente una tensione `VPN` stabile `> 30 V`, avvia automaticamente la nuova sequenza del test IVCK al termine della quale provvederà automaticamente a salvare i risultati associandoli alla precedente configurazione di marcatori.

    ```
    I V C K   15/10 – 18:04   AS&S
    Voc@OPC   985   V   OK
    Isc@OPC   11.25   A   OK
    Voc Med   985   V
    Isc Med   11.25   A
    Rp   >100   MΩ   OK
    R+   >100   R -   >100   MΩ   OK
    RPE   1.1   Ω   OK
    O K
    1000V   1.00MΩ   2Ω   0.2Ω
    VTest   ISO   RPE   ><
    ```
15. Ripetere i passi indicati dal punto 12 al punto 14 per tutte le stringhe da testare.
16. Lo strumento esce automaticamente dalla sequenza di `Avvia&Salva` al verificarsi di una delle seguenti condizioni:
    * Uscita dalla funzione IVCK
    * Spegnimento dello strumento
    * Disabilitazione funzione `Avvia&Salva`
    * Raggiungimento numero massimo di prove salvate per ogni marcatore (`max 999`)
    * Eventuali condizioni errore `Hardware` durante una misura

**PVCHECKs - ONE IT**

### 6.8.7. Interpretazione risultati di misura

In generale l’esito di un test sulla misura di Voc e Isc è determinato dalle seguenti relazioni.

#### Misure senza unità remota (no irraggiamento e temperatura)

Noti i seguenti parametri:
* `VocMed` → valore medio tensione a vuoto calcolata nelle ultime 10 misure salvate
* `IscMed` → valore medio corrente di corto circuito calcolata nelle ultime 10 misure salvate
* `Voc (Tol+) = Tol % (+)Voc * VocMed` → Valore di tolleranza positivo sulla Voc
* `Voc (Tol-) = Tol%(-)Voc * VocMed` → Valore di tolleranza negativo sulla Voc
* `Isc (Tol+) = Tol%(+)Isc * IscMed` → Valore di tolleranza positivo sulla Isc
* `Isc (Tol-) = Tol%(-)Isc * IscMed` → Valore di tolleranza negativo sulla Isc
* `εStrum Voc` → Massimo errore strumentale dichiarato sulla Voc @OPC (vedere § `10.1`)
* `εStrum Isc` → Massimo errore strumentale dichiarato sulla Isc @OPC (vedere § `10.1`)

I seguenti parametri di controllo sono calcolati dallo strumento:
* `εMis Voc = Voc (@OPC) – VocMed` → Errore sulla misura di Voc @ OPC
* `εMis Isc = Isc (@OPC) – IscMed` → Errore sulla misura di Isc @ OPC

Le seguenti condizioni sui parametri sull’esito della misura sono gestite dallo strumento:

| N | CONDIZIONE | ESITO |
|---|---|---|
| 1 | `➢ - Voc (Tol-) + εStrum Voc ≤ εMis Voc ≤ Voc (Tol+) - εStrum Voc` <br> `➢ - Isc (Tol-) + εStrum Isc ≤ εMis Isc ≤ Isc (Tol+) - εStrum Isc` <br> `➢ Rp ≥ Rp Lim` → se misura `ISO` selezionata <br> `➢ RPEmis ≤ RPELim` → se misura `RPE` selezionata | OK |
| 2 | `➢ - Voc (Tol-) ≤ εMis Voc ≤ Voc (Tol+)` <br> `➢ - Isc (Tol-) ≤ εMis Isc ≤ Isc (Tol+)` <br> `➢ Rp ≥ Rp Lim` → se misura `ISO` selezionata <br> `➢ RPEmis ≤ RPELim` → se misura `RPE` selezionata | OK* |
| 3 | `➢ - Voc (Tol-) - εStrum Voc ≤ εMis Voc ≤ Voc (Tol+) + εStrum Voc` <br> `➢ - Isc (Tol-) - εStrum Isc ≤ εMis Isc ≤ Isc (Tol+) + εStrum Isc` <br> `➢ Rp ≥ Rp Lim` → se misura `ISO` selezionata <br> `➢ RPEmis ≤ RPELim` → se misura `RPE` selezionata | NO OK* |
| 4 | Le precedenti condizioni (1), (2) e (3) non sono verificate | NO OK |

**PVCHECKs - ONE IT**

#### Misure con unità remota (irraggiamento e temperatura)

Noti i seguenti parametri:
* `VocNom` → Valore nominale della tensione a vuoto Voc (dichiarate da costruttore)
* `IscNom` → Valore nominale della corrente di cortocircuito Isc (dichiarate da costruttore)
* `Voc (Tol+) = Tol%(+)Voc * VocNom` → Valore di tolleranza positivo sulla Voc
* `Voc (Tol-) = Tol%(-)Voc * VocNom` → Valore di tolleranza negativo sulla Voc
* `Isc (Tol+) = Tol%(+)Isc * IscNom` → Valore di tolleranza positivo sulla Isc
* `Isc (Tol-) = Tol%(-)Isc * IscNom` → Valore di tolleranza negativo sulla Isc
* `εStrum Voc` → Massimo errore strumentale dichiarato sulla Voc @STC (vedere § `10.1`)
* `εStrum Isc` → Massimo errore strumentale dichiarato sulla Isc @STC (vedere § `10.1`)

I seguenti parametri di controllo sono calcolati dallo strumento:
* `εMis Voc = Voc (@STC) – VocNom` → Errore sulla misura di Voc @ STC
* `εMis Isc = Isc (@STC) – IscNom` → Errore sulla misura di Isc @ STC

**NOTA**: i valori Voc (@STC) e Isc (@STC) sono ottenuti in accordo alla `IEC/EN60891`.

Le seguenti condizioni sui parametri sull’esito della misura sono gestite dallo strumento:

| N | CONDIZIONE | ESITO |
|---|---|---|
| 1 | `➢ - Voc (Tol-) + εStrum Voc ≤ εMis Voc ≤ Voc (Tol+) - εStrum Voc` <br> `➢ - Isc (Tol-) + εStrum Isc ≤ εMis Isc ≤ Isc (Tol+) - εStrum Isc` <br> `➢ Rp ≥ Rp Lim` → se misura `ISO` selezionata <br> `➢ RPEmis ≤ RPELim` → se misura `RPE` selezionata | OK |
| 2 | `➢ - Voc (Tol-) ≤ εMis Voc ≤ Voc (Tol+)` <br> `➢ - Isc (Tol-) ≤ εMis Isc ≤ Isc (Tol+)` <br> `➢ Rp ≥ Rp Lim` → se misura `ISO` selezionata <br> `➢ RPEmis ≤ RPELim` → se misura `RPE` selezionata | OK* |
| 3 | `➢ - Voc (Tol-) - εStrum Voc ≤ εMis Voc ≤ Voc (Tol+) + εStrum Voc` <br> `➢ - Isc (Tol-) - εStrum Isc ≤ εMis Isc ≤ Isc (Tol+) + εStrum Isc` <br> `➢ Rp ≥ Rp Lim` → se misura `ISO` selezionata <br> `➢ RPEmis ≤ RPELim` → se misura `RPE` selezionata | NO OK* |
| 4 | Le precedenti condizioni (1), (2) e (3) non sono verificate | NO OK |

**PVCHECKs - ONE IT**

#### Esempio di applicazione (misura con unità remota)

* `Nome modulo`: LR5-54HIH-410M (costruttore LONGI)
* `Tipo modulo`: Monofacciale
* `Tensione a vuoto nominale dichiarata (@STC)`: 37.3V
* `Corrente di cortocircuito nominale dichiarata (@STC)`: 13.88A
* `Tolleranza Voc`: ±5%
* `Tolleranza Isc`: ±10%
* `Irraggiamento frontale misurato`: 577 W/m^2
* `Temperatura modulo (@STC)`: 25°C
* `Tensione a vuoto Voc calcolata da strumento (@STC)`: 37.1V
* `Corrente di cortocircuito Isc calcolata da strumento (@STC)`: 10.53A

`Voc (Tol+) = Tol%(+)Voc * VocNom = 0.05 * 37.3V = 1.9V`
`Voc (Tol-) = Tol%(-)Voc * VocNom = 0.05 * 37.3V = 1.9V`
`Isc (Tol+) = Tol%(+)Isc * IscNom = 0.1 * 13.88 = 1.39A`
`Isc (Tol-) = Tol%(-)Isc * IscNom = 0.1 * 13.88 = 1.39A`
`εStrum Voc = ±( 37.1 * 0.04 + 0.2 ) = ± 1.7V`
`εStrum Isc = ±( 10.53 * 0.04 + 0.02 ) = ± 0.44A`
`εMis Voc = Voc (@STC) - VocNom = 37.1 - 37.3 = - 0.2V`
`εMis Isc = Isc (@STC) - IscNom = 10.53 - 13.88 = - 3.35A`

Condizioni di confronto:
`Tensione Voc` → `-1.9 + 1.7 ≤ -0.2 ≤ 1.9 – 1.7` → Verificata condizione 1 → Esito `OK`
`Corrente Isc` → `-1.39 + 0.44 ≤ -3.35 ≤ 1.39 – 0.44` → Condizione 1 NON verificata
`Corrente Isc` → `-1.39 ≤ -3.35 ≤ 1.39` → Condizione 2 NON verificata
`Corrente Isc` → `-1.39 - 0.44 ≤ -3.35 ≤ 1.39 + 0.44` → Condizione 3 NON verificata
`Corrente Isc` → Verificata condizione 4 → Esito `NO OK`

**PVCHECKs - ONE IT**

### 6.8.8. Situazioni anomale

1. Qualora lo strumento rilevi ai terminali P-N, P-E e N-E una tensione **superiore a 1000V DC** non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`V.Ingr. > 1000V DC`”.

    ```
    I V C K   15/10 – 18:04
    U .   R e m o t a   n o n   a t t i v a
    V P N   V P E   V N E
    0 V   0 V   0 V
    V . I n g r .   > 1000V DC
    1000V   1.00MΩ   2Ω   - - - Ω
    VTest   ISO   RPE   ><
    ```
2. Qualora lo strumento rilevi ai terminali P-N, una tensione **inferiore a -0.5VDC** non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`Inverti P-N`”.

    ```
    I V C K   15/10 – 18:04
    U .   R e m o t a   n o n   a t t i v a
    V P N   V P E   V N E
    0 V   0 V   0 V
    Inverti P - N
    1000V   1.00MΩ   2Ω   - - - Ω
    VTest   ISO   RPE   ><
    ```
3. Qualora lo strumento rilevi ai terminali P-N, una tensione `-0.5V ≤ VPN ≤ 15VDC` non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`V. Ingresso < 15VDC`”.

    ```
    I V C K   15/10 – 18:04
    U .   R e m o t a   n o n   a t t i v a
    V P N   V P E   V N E
    1 1 V   6 V   - 5 V
    V . I n g r e s s o   <   15VDC
    1000V   1.00MΩ   2Ω   - - - Ω
    VTest   ISO   RPE   ><
    ```
4. Qualora lo strumento rilevi ai terminali P-N, P-E e N-E, una tensione **AC superiore a 10V** non esegue la prova, emette un segnale acustico prolungato e visualizza il messaggio “`V. Ingresso > 10VAC`”.

    ```
    I V C K   15/10 – 18:04
    U .   R e m o t a   n o n   a t t i v a
    V P N   V P E   V N E
    1 1 V   6 V   - 5 V
    V . I n g r e s s o   >   10VAC
    1000V   1.00MΩ   2Ω   - - - Ω
    VTest   ISO   RPE   ><
    ```

**PVCHECKs - ONE IT**

5. Qualora lo strumento rilevi ai terminali E e C una **tensione >3V** non esegue la prova `RPE`, emette un segnale acustico prolungato e visualizza il messaggio “`V.Ingresso > 3V`”.

    ```
    I V C K   15/10 – 18:04
    U .   R e m o t a   n o n   a t t i v a
    V P N   V P E   V N E
    0 V   0 V   0 V
    V . I n g r e s s o   > 3V
    1000V   1.00MΩ   2Ω   - - - Ω
    VTest   ISO   RPE   ><
    ```
6. Qualora lo strumento durante la misura della corrente Isc rilevi una **corrente <0.1 A**, il messaggio a lato è mostrato a display. Controllare i collegamenti dello strumento con il circuito in prova.

    ```
    I V C K   15/10 – 18:04
    U .   R e m o t a   n o n   a t t i v a
    V P N   V P E   V N E
    0 V   0 V   0 V
    I s c   < 0.1A
    1000V   1.00MΩ   2Ω   - - - Ω
    VTest   ISO   RPE   ><
    ```
7. Qualora lo strumento durante la misura della corrente Isc rilevi la condizione di **fusibile interrotto** il messaggio a lato è mostrato a display. Contattare il servizio di assistenza HT.

    ```
    I V C K   15/10 – 18:04
    U .   R e m o t a   n o n   a t t i v a
    V P N   V P E   V N E
    0 V   0 V   0 V
    F u s i b i l e   r o t t o
    1000V   1.00MΩ   2Ω   - - - Ω
    VTest   ISO   RPE   ><
    ```
8. Nel caso in cui non sia stata attivata una registrazione sull’unità remota SOLAR03 il messaggio a lato è mostrato a display. Verificare lo stato dell’unità remota SOLAR03.

    ```
    I V C K   15/10 – 18:04
    Irr.   - - -   W/m2
    Temp.   - - -   °C
    SOLAR03   23051203
    Modulo:   318WTH
    V P N   V P E   V N E
    9 8 0 V   4 9 0 V   - 4 9 0 V
    U . R e m .   n o n c o   l l e g .
    1000V   1.00MΩ   2Ω   0.25Ω
    VTest   ISO   RPE   ><
    ```

**PVCHECKs - ONE IT**

9. Al termine delle misure di Voc e Isc il messaggio “`Attesa valori Irraggiamento`” è fornito nel caso in cui una unità remota SOLAR03 sia in registrazione ma non connessa allo strumento. Attendere il download dei dati da parte dell’unità remota per la visualizzazione dell’esito delle misure @STC.

    ```
    I V C K   15/10 – 18:04
    Voc @ STC   - - -   V
    Isc   @ STC   - - -   A
    Voc Nom   985   V
    Isc Nom   11.25   A
    Rp   >100   MΩ   OK
    R+   >100   R -
    >100   MΩ
    RPE   1.1   Ω   OK
    A t t e s a v a l o r i I r r a g g i a m e n t o
    1000V   1.00MΩ   2Ω   0.2Ω
    VTest   ISO   RPE   ><
    ```
10. Nel caso in cui sia stata attivata e connessa l’unità remota SOLAR03, ma il valore di irraggiamento non sia valido (ad esempio con sonde di irraggiamento non collegate all'unità remota), il messaggio a lato è mostrato a display. Verificare lo stato dell’unità remota.

    ```
    I V C K   15/10 – 18:04
    Irr.   - - -   W/m2
    Temp.   - - -   °C
    SOLAR03   23051203
    Modulo:   318WTH
    V P N   V P E   V N E
    9 8 0 V   4 9 0 V   - 4 9 0 V
    Cont r .   i ngr .   U.Rem .
    1000V   1.00MΩ   2Ω   0.25Ω
    VTest   ISO   RPE   ><
    ```
11. Nel caso si desideri eseguire misure senza unità remota (vedere § `6.8.2` e § `6.8.3`), ma lo strumento sia stato precedentemente associato ad una unità remota, il messaggio a lato è mostrato a display. Entrare nel menu di configurazione unità remota (vedere § `6.2`) ed eseguire il comando “`Disass.`” per disassociare l’unità remota.

    ```
    I V C K   15/10 – 18:04
    I rr .   - - -   W/m2
    Temp.   - - -   °C
    SOLAR0 3   23051203
    Modulo:   318WTH
    V P N   V P E   V N E
    9 8 0 V   4 9 0 V   - 4 9 0 V
    U.Rem.   n o n c o l l e g .
    1000V   1.00MΩ   2Ω   0.25Ω
    VTest   ISO   RPE   ><
    ```

**PVCHECKs - ONE IT**

### 6.9. ELENCO DEI MESSAGGI DI ERRORE A DISPLAY

| NUMERO | MESSAGGIO | DESCRIZIONE | AZIONI |
|---|---|---|---|
| 1 | `Errore EE ONE M` | Errore interno | Inviare strumento in assistenza |
| 2 | `Errore ADP5587` | Errore interno | Inviare strumento in assistenza |
| 3 | `Errore Init sistema` | Errore interno | Inviare strumento in assistenza |
| 4 | `Vtest non corretta` | Vtest non corretta in MΩ | Controllo Riso maggiore del limite impostato e possibile livello basso delle batterie |
| 5 | `Batteria bassa` | Livello di batteria bassa | Sostituire le batterie |
| 6 | `Inverti P-N` | Collegamenti scambiati nei poli P-N della stringa in test IVCK | Controllare collegamenti nel manuale d’uso |
| 7 | `Uscita Forzata` | Interruzione forzata del test con tasto `STOP` | Ripetere il test senza interrompere la misura |
| 8 | `V.Ingr. > 1000V DC` | Tensione troppo elevata tra ingressi P e N in test IVCK | Scollegare lo strumento e controllare la tensione tra i poli P e N della stringa |
| 9 | `V.Ingresso > 10VAC` | Rilevata tensione AC oltre i limiti tra gli ingressi P e N in test IVCK | Controllare se la stringa è scollegata dall’inverter. Controllare se i cavi di collegamento della stringa sono vicini a cavi in tensione presenti. In tal caso de-energizzare questi cavi e/o quadri di campo |
| 10 | `V.Ingresso < 15VDC` | Tensione minima per avvio test IVCK troppo bassa | Controllare se i moduli PV in prova soddisfano i requisiti minimi indicati nel manuale |
| 11 | `V.Ingresso > 3V` | Rilevata tensione oltre limite tra gli ingressi della funzione RPE | Controllare le connessioni come indicato nel manuale d’uso, controllare tensione tra gli ingressi E e C, aggiornare FW all’ultima versione |
| 12 | `Azzeramento NO OK` | Strumento non esegue la calibrazione dei puntali nella misura RPE | Controllare la continuità dei cavi, controllare che siano regolarmente cortocircuitati e che siano originali HT |
| 13 | `Riprova` | Dati misurati non affidabili | Ripetere la misura considerando manuale d’uso |
| 14 | `Att, Tens. Resid.` | Presenza di tensione tra i puntali al temine della prova ISO per effetto di capacità parassite elevate | Prestare attenzione durante lo scollegamento dei terminali di misura e seguire le avvertenze nel manuale d’uso |
| 15 | `Rcal > Rmis` | Procedura azzeramento resistenza cavi di prova in funzione RPE fallita | Controllare la continuità dei cavi, controllare che siano regolarmente cortocircuitati e che siano originali HT |
| 16 | `Errore Flash` | Errore interno | Inviare strumento in assistenza |
| 17 | `Temp.Alta` | Temperatura circuiti interni troppo alta | Attendere il raffreddamento dei circuiti prima di eseguire nuovi test |
| 18 | `Ibatt troppo alta` | Errore interno | Inviare strumento in assistenza |
| 19 | `VPN > Vtest` | Tensione di stringa maggiore della tensione di prova nel test ISO | Selezionare una tensione di prova maggiore nel test ISO |
| 20 | `Contr. collegamenti` | Rilevazione tensione incorretta nei terminali P-N-E | Controllare i collegamenti indicati nel manuale d’uso |
| 21 | `Errore WiFi` | Modulo WiFi non risponde ai comandi | Spegnere e riaccendere lo strumento e riprovare. Se errore persiste inviare strumento in assistenza |
| 22 | `BT non funziona` | Modulo Bluetooth non risponde ai comandi | |
| 23 | `Collegamento perso` | | |
| 24 | `IGBT danneggiato` | Errore interno | Inviare strumento in assistenza |
| 25 | `U.Rem: batteria scarica` | Livello basso batterie del SOLAR03 | Sostituire batterie del SOLAR03 con altre dello stesso tipo |
| 26 | `Picco Isc troppo alto` | Corrente di picco troppo alta per effetto delle capacità parassite elevate | Eseguire test sulla stringa dimezzata o test su singoli moduli |
| 27 | `Isc troppo alta` | Corrente Isc > 30A | Controllare i collegamenti dello strumento, scollegare eventuali stringhe in parallelo e verificare il non collegamento dello strumento all’inverter FV |
| 28 | `Picco Isc troppo lungo` | Corrente di picco mantenuta troppo a lungo | |
| 29 | `Contr. Ingr. U.Rem.` | Valori ricevuti da SOLAR03 non realistici | Controllare gli ingressi del SOLAR03 e la posizione delle celle di riferimento |
| 30 | `Isc <0.1A` | Valore misurato della Isc troppo basso (<0.1A) | Controllare i cavi di collegamento e le caratteristiche del modulo FV considerato |
| 31 | `Irragg. < Lim.` | Valori di irraggiamento misurati inferiori al limite impostato | Controllare il limite impostato e la posizione delle celle di riferimento |

**PVCHECKs - ONE IT**

### 7. MEMORIZZAZIONE RISULTATI

Lo strumento consente la memorizzazione di `max 999` risultati di misura. I dati possono essere richiamati a display e cancellati in ogni momento ed è possibile associare degli identificatori numerici di riferimento mnemonici relativi all’impianto (`max 3 livelli`), alla stringa e al modulo FV (`max 250`).

### 7.1. SALVATAGGIO DELLE MISURE

1. Premere il tasto **SAVE** con risultato di misura presente a display. Lo strumento presenta la videata mostrata a lato in cui sono mostrate le seguenti voci:
    * La prima locazione di memoria disponibile (“`Misura`”).
    * Il marcatore di 1° livello (ex: Area). Ad ogni marcatore possono essere assegnate fino a `20 etichette` liberamente personalizzabili. Selezionare il marcatore di livello desiderato con i **tasti freccia** (``, ``) e premere il tasto **ENTER** per la selezione di una delle etichette disponibili.
    * Il marcatore di 2° livello (ex: Stringa). Ad ogni marcatore possono essere assegnate fino a `20 etichette` liberamente personalizzabili. Selezionare il marcatore di livello desiderato con i **tasti freccia** ``, ``.
    * Il marcatore di 3° livello (ex: Modulo). Ad ogni marcatore possono essere assegnate fino a `20 etichette` liberamente personalizzabili. Selezionare il marcatore di livello desiderato con i **tasti freccia** ``, ``.
    * Il campo “`Commento`” in cui l’operatore può inserire una breve descrizione (`max 30 caratteri`) usando la tastiera virtuale interna. Il commento inserito è mostrato nella riga sottostante.

    ```
    M E M   15/10 – 18:04
    M i s u r a   :   001
    Ar e a   001
    Str i n g a   001
    Mo d u l o   - - -
    Co m m e n t o :
    Impianto Rossi
    ```

    **ATTENZIONE**
    * I nomi personalizzati delle etichette dei marcatori possono essere definiti con l’uso del software TopView e caricati sullo strumento tramite collegamento a PC (sezione “Collegamento PC - Strumento → Gestione marcatori”).
    * I nomi dei marcatori utilizzati nelle misure salvate in memoria, non si possono cancellare né modificare.
    * I nomi dei marcatori di default non sono eliminabili. La cancellazione dei nomi personalizzati può avvenire solo da software TopView.
2. Premere nuovamente il tasto **SAVE** per completare il salvataggio dei dati o **ESC/MENU** per uscire senza salvare.

**PVCHECKs - ONE IT**

### 7.2. RICHIAMO A DISPLAY E CANCELLAZIONE DATI SALVATI

1. Premere il tasto **ESC/MENU** per tornare al menu principale, selezionare la voce “`MEM`” e premere **ENTER** per entrare nella sezione di visualizzazione dei dati memorizzati. La videata di fianco è mostrata dallo strumento in cui è presente l’elenco delle prove salvate.
2. Usando i tasti freccia ``, `` selezionare la misura salvata che si desidera richiamare a display e con i tasti freccia ``, `` selezionare la voce “`Reg`”. Confermare con **ENTER**. La seguente videata è mostrata a display.

    ```
    M E M   15/10 – 18:04
    N.   D a t a   T i p o
    001   15/05/23   RPE
    002   15/05/23   MΩ
    003   15/05/23   IVCK
    004   12/04/23   RPE
    005   12/04/23   IVCK
    Tot: 5   Libera: 994
       
          Ult
    R e g   Pag   Canc
    ```
3. Per il test IVCK sono presenti i valori dei seguenti parametri:
    * Valore tensione Voc @STC con relativo esito
    * Valore corrente Isc @STC con relativo esito
    * Valore nominale della Voc
    * Valore nominale della Isc
    * Valore della Rp con relativo esito (se test selezionato) altrimenti indicazione “`- - -`“ se test non selezionato (OFF)
    * Valori di R+ e R- con relativi esiti (se test selezionato) altrimenti indicazione “`- - -`“ se test non selezionato (OFF)
    * Valore di RPE con relativo esito (se test selezionato) altrimenti indicazione “`- - -`“ se test non selezionato (OFF)

    ```
    I V C K   15/10 – 18:04
    Voc@STC   43.0   V   OK
    Isc@STC   1.76   A   OK
    Voc Nom   42.9   V
    Isc Nom   1.80   A
    Rp   - - -   MΩ
    R+   - - -   R -   - - -   MΩ
    RPE   - - -   Ω
       OK   
    OFF   OFF   OFF   - - -   Ω
    VTest   ISO   RPE   ><
    ```
4. Usare i tasti freccia ``, `` per selezionare i valori `@OPC`. La videata a lato è mostrata a display.

    ```
    I V C K   15/10 – 18:04
    Voc@OPC   985   V
    Isc@OPC   1.77   A
    VocMed   985   V
    IscMed   1.81   A
    Rp   - - -   MΩ
    R+   - - -   R -   - - -   MΩ
    RPE   - - -   Ω
       OK   
    OFF   OFF   OFF   - - -   Ω
    VTest   ISO   RPE   ><
    ```
5. Usare i tasti freccia ``, `` per selezionare i valori di `Irraggiamento` e `Temperatura` moduli. La videata a lato è mostrata a display.
6. Usare i tasti freccia ``, `` per passare velocemente alla misura successiva o precedente all’interno della lista delle misure salvate.

    ```
    I V C K   15/10 – 18:04
    Front   Btop   Bbot.
    Irr.   920   125   95   W/m2
    Temp   54.7   °C
    Rp   >100   MΩ   OK
    R+   >100   R -   >100   MΩ
    RPE   Ω
       OK   
    1000V   1.00MΩ   OFF   - - -   Ω
    VTest   ISO   RPE   ><
    ```

**PVCHECKs - ONE IT**

7. Per il test RPE sono presenti i valori dei seguenti parametri:
    * Soglia limite impostata per la misura di continuità
    * Valore della resistenza di calibrazione dei cavi di prova
    * Il valore della resistenza dell’oggetto in prova
    * Il valore reale della corrente di prova applicata
    * Esito della misura

    ```
    R P E   15/10 – 18:04
    R   0 . 0 2   Ω
    I t e s t   2 1 2   m A
    OK
    STD   2.00 Ω   0.06   Ω
    MODO   Lim.   ><
    ```
8. Usando i tasti freccia ``, `` selezionare la misura salvata che si desidera cancellare e con i tasti freccia ``, `` selezionare la voce “`Canc`”. Confermare con **ENTER**. La seguente videata è mostrata a display.

    ```
    M E M   15/10 – 18:04
    N.   D a t a   T i p o
    001   15/05/23   RPE
    002   15/05/23   MΩ
    003   15/05/23   IVCK
    004   12/04/23   RPE
    005   12/04/23   IVCK
    Tot: 5   Libera: 994
       
          Ult
    Richiama   Pag   Canc
    ```
9. Premere il tasto **ENTER** per confermare l’operazione o il tasto **ESC** per uscire senza confermare e tornare la menu principale. Lo strumento cancella sempre l’ultima misura salvata.

    ```
    M E M   15/10 – 18:04
    CANCELLA ULTIMA?
    ENTER / ESC
    ```

**PVCHECKs - ONE IT**

### 8. COLLEGAMENTO DELLO STRUMENTO A PC

La connessione fra PC e strumento avviene tramite porta seriale ottica (vedere `Fig. 3`) con uso del cavo ottico/USB C2006 o tramite collegamento WiFi. La scelta del tipo di collegamento va eseguita all’interno del software di gestione TopView scaricabile liberamente dal sito HT a partire dal link: `https://www.ht-instruments.it/it-it/product-download/`

**ATTENZIONE**
* Per effettuare il trasferimento dati verso un PC tramite cavo ottico/USB è necessario avere preventivamente installato nel PC stesso il SW di gestione.
* Prima di effettuare il collegamento è necessario selezionare a PC la porta utilizzata e il baud rate corretto (57600 bps). Per impostare questi parametri avviare il software di gestione in dotazione e consultare l’help in linea del programma.
* La porta selezionata non deve essere impegnata da altri dispositivi o applicazioni come mouse, modem, ecc. Chiudere eventualmente processi in esecuzione a partire dalla funzione Task Manager di Windows.
* La porta ottica emette radiazione LED invisibile. Non osservare direttamente con strumenti ottici. Apparecchio LED di classe 1M secondo IEC/EN60825-1.

Per trasferire i dati a PC attenersi alla seguente procedura:
1. Accendere lo strumento premendo il tasto **ON/OFF**.
2. Collegare lo strumento a PC utilizzando il cavo ottico/USB `C2006` in dotazione.
3. Selezionare con i tasti freccia (``, ``) la voce “`PC`” per entrare in modalità trasferimento dati e confermare con **SAVE/ENTER**.

    ```
    MENU   15/10 – 18:04
    S E T   :   I m p o s t a z i o n i
    M E M   :   D a t i   S a l v a t i
    P C   :   T r a s f e r i m   D a t i
    
    ```
4. Se occorre usare il collegamento WiFi attivare il modulo interno (vedere § `5.1.3`). In tal caso lo strumento fornisce la videata seguente:

    ```
    P C   15/10 – 18:04
    Connessione PC
    WiFi ON
    ```
6. Usare i comandi del software di gestione per attivare il trasferimento dati (consultare l’help in linea del programma).

**PVCHECKs - ONE IT**

### 9. MANUTENZIONE

#### 9.1. GENERALITÀ

Lo strumento da Lei acquistato è uno strumento di precisione. Durante l’utilizzo e l’immagazzinamento rispettare le raccomandazioni elencate in questo manuale per evitare possibili danni o pericoli durante l’utilizzo.
Non utilizzare lo strumento in ambienti caratterizzati da elevato tasso di umidità o temperatura elevata. Non esporre direttamente alla luce del sole.
Spegnere sempre lo strumento dopo l’utilizzo. Se si prevede di non utilizzarlo per un lungo periodo di tempo, rimuovere le batterie per evitare da parte di queste ultime fuoruscite di liquidi che possono danneggiare i circuiti interni dello strumento.

#### 9.2. SOSTITUZIONE BATTERIE

Quando sul display LCD appare il simbolo di batteria scarica “` `“ oppure quando durante una prova si ha il messaggio “batteria scarica” a display, sostituire le batterie interne.

**ATTENZIONE**
Solo tecnici qualificati possono effettuare questa operazione. Prima di effettuare questa operazione assicurarsi di aver rimosso tutti i cavi dai terminali di ingresso.

1. Spegnere lo strumento premendo a lungo il pulsante di accensione.
2. Rimuovere i cavi dai terminali di ingresso.
3. Svitare la vite di fissaggio del coperchio dal vano batterie e rimuovere lo stesso.
4. Rimuovere dal vano batterie tutte le batterie e sostituirle solo con batterie tutte nuove e tutte del tipo corretto (vedere § `10.2`) rispettando le polarità indicate.
5. Riposizionare il coperchio vano batterie e fissarlo con l'apposita vite.
6. Non disperdere nell’ambiente le batterie utilizzate. Usare gli appositi contenitori per lo smaltimento.

#### 9.3. PULIZIA DELLO STRUMENTO

Per la pulizia dello strumento utilizzare un panno morbido e asciutto. Non usare mai panni umidi, solventi, acqua, ecc.

#### 9.4. FINE VITA

**ATTENZIONE**: il simbolo riportato indica che l'apparecchiatura, i suoi accessori e le batterie interne devono essere raccolti separatamente e trattati in modo corretto.

**PVCHECKs - ONE IT**

### 10. SPECIFICHE TECNICHE

#### 10.1. CARATTERISTICHE TECNICHE

L’incertezza è indicata come `± [%lettura + (num.cifre*risoluzione)]` a `23°C±5°C`, `<80%RH`.

##### SICUREZZA ELETTRICA

**DMM – Tensione DC**

| Campo [V] | Risoluzione [V] | Incertezza |
|---|---|---|
| `3 ÷ 1000` | `1` | `± (1.0 % lettura + 2cifre)` |

**DMM – Tensione AC TRMS**

| Campo [V] | Risoluzione [V] | Incertezza |
|---|---|---|
| `3 ÷ 1000` | `1` | `± (1.0 % lettura + 3cifre)` |

Campo frequenza: `42.5 Hz ÷ 69Hz`; Tensione azzerate per valore misurato `<3V`.

**MΩ - Resistenza di isolamento R(+), R(-), Rp – Modo DUAL**

| Tensione di prova DC [V] | Campo [MΩ] | Risoluzione [MΩ] | Incertezza (*) |
|---|---|---|---|
| `250, 500, 1000` | `0.1 ÷ 0.99` | `0.01` | `± (5.0 % lettura + 5cifre)` |
| | `1.0 ÷ 19.9` | `0.1` | |
| | `20 ÷ 100` | `1` | |

(*) Incertezza dichiarata per `VPN≥240V`, `Rguasto≥10Ω`. Incertezza di Rp e R(+) non dichiarata se `R(+)≥0.2MΩ` e `R(-)<0.2MΩ`, Incertezza di Rp e R(-) non dichiarata se `R(+) < 0.2MΩ` e `R(-) ≥ 0.2MΩ`.
* Tensione a vuoto `<1.25 x tensione di prova nominale`
* Corrente di cortocircuito `<15mA` (picco) per ogni tensione di prova
* Corrente di misura nominale `>1mA` su `R = 1kΩ x Vnom` (con `VPN, VPE, VNE= 0`)
* Capacità `max` gestita per polo: `2μF`

**Resistenza di isolamento (MΩ) – Modo TMR**

| Tensione di prova DC [V] | Campo [MΩ] | Risoluzione [MΩ] | Incertezza |
|---|---|---|---|
| `250, 500, 1000` | `0.01 ÷ 9.99` | `0.01` | `± (5.0 % lettura + 5cifre)` |
| | `10.0 ÷ 99.9` | `0.1` | |
| | `100 ÷ 250` | `1` | |

* Tensione a vuoto `<1.25 x tensione di prova nominale`
* Corrente di cortocircuito `< 15mA` (picco) per ogni tensione di prova
* Corrente di misura nominale `> 1mA` su `R = 1kΩ x Vnom` (con `VPN, VPE, VNE= 0`)
* Timer impostabile: `3s ÷ 999s`

**Continuità conduttori di protezione (RPE)**

| Campo [Ω] | Risoluzione [Ω] | Incertezza |
|---|---|---|
| `0.00 ÷ 9.99` | `0.01` | `± (2.0 % lettura + 2cifre)` |
| `10.0 ÷ 99.9` | `0.1` | |
| `100 ÷ 1999` | `1` | |

* Corrente di prova: `>200mA DC` fino a `5Ω` (cavi inclusi), risoluzione `1mA`, incertezza `± (5.0%lettura + 5cifre)`
* Tensione a vuoto `4 < V0 < 10V`

**GFL – Ground Fault Locator**

| Tensione di prova DC [V] | Campo [MΩ] | Risoluzione [MΩ] | Incertezza Rp(*) | Incertezza posizione |
|---|---|---|---|---|
| `250,500,1000` | `0.1 ÷ 0.99` | `0.01` | `± (5.0 % lettura + 5cifre)` | `± 1modulo (NMOD ≤34)` <br> `± 3 moduli (NMOD >34)` |
| | `1.0 ÷ 19.9` | `0.1` | | |
| | `20 ÷ 100` | `1` | | |

(*) Incertezza dichiarata per `VPN≥240V`, `Rguasto≥10Ω`. Incertezza di Rp e R(+) non dichiarata se `R(+)≥0.2MΩ` e `R(-)<0.2MΩ`, Incertezza di Rp e R(-) non dichiarata se `R(+) < 0.2MΩ` e `R(-) ≥ 0.2MΩ`.
* Tensione a vuoto `<1.25 x tensione di prova nominale`
* Corrente di cortocircuito `<15mA` (picco) per ogni tensione di prova
* Corrente di misura nominale `>1mA` su `R = 1kΩ x Vnom` (con `VPN, VPE, VNE= 0`)
* Capacità max gestita per polo: `2μF`
* Limite di misura impostabile: `0.05MΩ`, `0.1MΩ`, `0.23MΩ`, `0.25MΩ`, `0.50MΩ`, `1.00MΩ`
* Numero moduli (`NMOD`): `4 ÷ 60`

La funzione GFL fornisce risultati corretti sotto le seguenti ipotesi:
* Test eseguito con `Vtest ≥ Vnom` su una **singola stringa** disconnessa dall’inverter, da eventuali scaricatori e da connessioni a terra.
* Test eseguito a monte di eventuali diodi di blocco.
* **Singolo guasto** di basso isolamento avvenuto in un qualunque punto della stringa.
* Resistenza di isolamento del singolo guasto: `< 1.00 MΩ`.
* Condizioni ambientali simili a quelle in cui è stato segnalato il guasto.

**PVCHECKs - ONE IT**

**OPT – Test isolamento con ottimizzatori e dispositivi MLPE**

| Tensione di prova DC [V] | Campo [MΩ] | Risoluzione [MΩ] | Incertezza Rp(*) |
|---|---|---|---|
| `100,250,500,1000` <br> (MLPE con RSD) | `0.1 ÷ 0.99` | `0.01` | `± (5.0 % lettura + 10cifre)` |
| | `1.0 ÷ 19.9` | `0.1` | |
| | `20 ÷ 250` | `1` | |
| `100` <br> (MLPE senza RSD) | `0.1 ÷ 0.99` | `0.01` | |
| | `1.0 ÷ 19.9` | `0.1` | |
| | `20 ÷ 100` | `1` | |

(*) Incertezza dichiarata per `VPN≥240V`, `Rguasto≥10Ω`. Incertezza di Rp e R(+) non dichiarata se `R(+)≥0.2MΩ` e `R(-)<0.2MΩ`, Incertezza di Rp e R(-) non dichiarata se `R(+) < 0.2MΩ` e `R(-) ≥ 0.2MΩ`.
* Tensione a vuoto `<1.25 x tensione di prova nominale`
* Corrente di cortocircuito `<15mA` (picco) per ogni tensione di prova
* Corrente di misura nominale `>1mA` su `R = 1kΩ x Vnom` (con `VPN, VPE, VNE= 0`)
* Capacità max gestita per polo: `2μF`
* Limite di misura impostabile: `0.10MΩ`, `0.25MΩ`, `0.60MΩ`, `1.00MΩ`, `100MΩ`, `200MΩ` (MLPE con RSD)
* `0.10MΩ`, `0.25MΩ`, `0.60MΩ`, `1.00MΩ`, `50MΩ` (MLPE senza RSD)
* Numero ottimizzatori: `1 ÷ 60`
* Corrente max in modo RSD: `1A`

##### FUNZIONE IVCK

L’incertezza è indicata come `± [%lettura + (num.cifre*risoluzione)]` a `23°C±5°C`, `<80%RH`.

**Tensione DC@ OPC**

| Campo [V] | Risoluzione [V] | Incertezza |
|---|---|---|
| `3.0 ÷ 1000.0` | `0.1` | `± (1.0 % lettura + 2cifre)` |

Tensione VPN minima per avviare la prova: `15V`; Con funzione `Avvia&Salva` attiva, la tensione VPN minima è `30V`.

**Corrente DC @ OPC**

| Campo [A] | Risoluzione [A] | Incertezza |
|---|---|---|
| `0.10 ÷ 30.00` | `0.01` | `± (1.0 % lettura + 2cifre)` |

**Tensione DC @ STC**

| Campo [V] | Risoluzione [V] | Incertezza |
|---|---|---|
| `3.0 ÷ 1000.0` | `0.1` | `± (4.0 % lettura + 2cifre)` |

**Corrente DC @ STC**

| Campo [A] | Risoluzione [A] | Incertezza |
|---|---|---|
| `0.10 ÷ 30.00` | `0.01` | `± (4.0 % lettura + 2cifre)` |

**Irraggiamento con collegamento a cella di riferimento HT305**

| Campo tensione [mV] | Risoluzione [mV] | Incertezza (*) |
|---|---|---|
| `0.00 ÷ 99.99` | `0.01` | `± (1.0 % lettura + 0.02mV)` |

| Campo misura [W/m^2] | Risoluzione [W/m^2] | Incertezza (*) |
|---|---|---|
| `0 ÷ 1400` | `1` | `± (1.0 % lettura + 1 cifra)` |

(*) Incertezza del solo strumento senza cella.

**Temperatura modulo con collegamento a sonda PT305**

| Campo resistenza [Ω] | Risoluzione [Ω] | Incertezza (*) |
|---|---|---|
| `846 ÷ 1385` | `0.385` | `± (1.0 % lettura + 3.85Ω)` |

| Campo misura [°C] | Risoluzione [°C] | Incertezza (*) |
|---|---|---|
| `-40.0 ÷ 99.9` | `0.1` | `± (1.0 % lettura + 1 °C)` |

(*) Incertezza del solo strumento senza sonda.

**PVCHECKs - ONE IT**

#### 10.2. CARATTERISTICHE GENERALI

##### Normative di riferimento

* `Sicurezza strumento`: IEC/EN61010-1, IEC/EN61010-2-030, IEC/EN61010-2-033, IEC/EN61010-2-034
* `EMC`: IEC/EN61326-1, IEC/EN61326-2-2
* `Sicurezza accessori di misura`: IEC/EN61010-031
* `Misure`: IEC/EN62446-1, IEC/EN60891 (IVCK), IEC/EN61557-1-10, IEC/EN61557-2 (MΩ), IEC/EN61557-4 (RPE)
* `Misure moduli bifacciali`: IEC/EN60904-1-2
* `Calcolo temperatura moduli`: IEC/EN60904-5
* `Ambiente EMC di utilizzo`: portatile, Classe A, Gruppo 1
* `Isolamento`: doppio isolamento
* `Grado di inquinamento`: 2
* `Categoria di misura`: CAT III 1000V verso terra
* `Max 1000VAC`, `1000V DC` tra gli ingressi

##### Radio

* `Conformità a direttive RED`: ETSI EN300328, ETSI EN301489-1, ETSI EN301489-17

##### Display, memoria e interfaccia PC

* `Tipo display`: LCD custom, 240x240pxl, retroilluminato
* `Dati memorizzabili`: max 999, 3 livelli di marcatori
* `Database interno`: max 64 moduli salvabili
* `Interfaccia PC`: ottica/USB e WiFi
* `Interfaccia con SOLAR03`: collegamento Bluetooth (fino a 100m in spazio libero)

##### Alimentazione

* `Tipo batterie`: 6x1.5V alcaline tipo AA LR06 oppure 6x1.2V batterie ricaricabili NiMH tipo AA LR06
* `Indicazione batteria scarica`: simbolo “` `“ mostrato a display
* `Durata batterie` (`@Temp = 20°C`): `RPE`: >500 Test (`RPE ≥ 0.1Ω`)
    * `GFL, MΩ`: >500 test (`Riso ≥ 1kΩ xVTest`)
    * `IVCK`: >500 test (no SOLAR03)
* `Autospegnimento`: dopo 5 minuti di non utilizzo

##### Caratteristiche meccaniche

* `Dimensioni` (L x La x H): `235 x 165 x 75mm`
* `Peso` (batterie incluse): `1.2kg`
* `Protezione meccanica`: `IP40`

**PVCHECKs - ONE IT**

### 10.3. CONDIZIONI AMBIENTALI DI UTILIZZO

* `Temperatura di riferimento`: `23°C ± 5°C`
* `Temperatura di utilizzo`: `-10°C ÷ 50°C`
* `Umidità relativa ammessa`: `<80%RH` (senza condensa)
* `Temperatura di conservazione`: `-10°C ÷ 60°C`
* `Umidità di immagazzinamento`: `<80%RH` (senza condensa)
* `Max altitudine di utilizzo`: `2000m`

Questo strumento è conforme ai requisiti della Direttiva Europea sulla bassa tensione `2014/35/EU (LVD)`, della Direttiva `2014/30/EU (EMC)` e della Direttiva `RED 2014/53/EU`.
Questo strumento è conforme ai requisiti della direttiva europea `2011/65/EU (RoHS)` e della direttiva europea `2012/19/EU (WEEE)`.

### 10.4. ACCESSORI

Vedere `packing list` allegata.

**ATTENZIONE**
Solo gli accessori forniti a corredo dello strumento garantiscono gli standard di sicurezza. Essi devono essere in buone condizioni e sostituiti, se necessario, con modelli identici.

**PVCHECKs - ONE IT**

### 11. APPENDICE – CENNI TEORICI

#### 11.1. MISURA INDICE DI POLARIZZAZIONE (PI)

Lo scopo di questo test diagnostico è quello di valutare l’influenza degli effetti di polarizzazione. All’applicazione di una tensione elevata ad un isolante, i dipoli elettrici distribuiti nell’isolante si allineano nella direzione del campo elettrico applicato. Questo fenomeno è chiamato **polarizzazione**. Per effetto delle molecole polarizzate si genera una corrente di polarizzazione (assorbimento) che abbassa il valore complessivo della resistenza di isolamento.
Il parametro `PI` consiste nel rapporto tra il valore di resistenza di isolamento misurata dopo 1 minuto e quella dopo 10 minuti. La tensione di prova è mantenuta per tutta la durata del test e al termine lo strumento fornisce il valore del rapporto:

`PI = R (10 min) / R (1 min)`

Alcuni valori di riferimento:

| Valore PI | Condizione dell’isolamento |
|---|---|
| `<1.0` | Non accettabile |
| `da 1.0 a 2.0` | Pericoloso |
| `da 2.0 a 4.0` | Buono |
| `> 4.0` | Eccellente |

#### 11.2. RAPPORTO DI ASSORBIMENTO DIELETTRICO (DAR)

Il parametro `DAR` consiste nel rapporto tra il valore di resistenza di isolamento misurata dopo 30s e quella dopo 1minuto. La tensione di prova è mantenuta per tutta la durata del test e al termine lo strumento fornisce il valore del rapporto:

`DAR = R (1 min) / R (30 s)`

Alcuni valori di riferimento:

| Valore DAR | Condizione dell’isolamento |
|---|---|
| `< 1.0` | Non accettabile |
| `da 1.0 a 1.25` | Pericoloso |
| `da 1.25 a 1.6` | Buono |
| `> 1.6` | Eccellente |

**PVCHECKs - ONE IT**

#### 11.3. FUNZIONE GFL – ASPETTI TEORICI E RIFERIMENTI NORMATIVI

La funzione GFL eseguita dallo strumento su una stringa di moduli FV (vedere § `6.5`) è in grado di:
* Individuare la presenza di **singolo guasto** sulla stringa disconnessa dall’inverter, da altre stringhe, da eventuali scaricatori e da connessioni funzionali a terra.
* Identificare la posizione di questo **singolo guasto** all’interno della stringa impostando un limite **minimo** nel controllo della resistenza di isolamento tra le opzioni: `0.05MΩ`, `0.1MΩ`, `0.23MΩ`, `0.25MΩ`, `0.50MΩ` o `1.00MΩ`.

Nell’ambito della misura di isolamento, esiste il “contrasto” tra le normative di verifica delle installazioni fotovoltaiche (`IEC/EN62446-1`) e le normative di prodotto con cui sono costruiti i moduli FV (`IEC 61646` e `IEC 61215`) che definiscono i seguenti limiti di verifica:
* `IEC/EN62446-1` → limite minimo isolamento = `1MΩ`
* `IEC 61646/IEC61215` → isolamento minimo di un singolo modulo pari a `40MΩ / m^2`, dunque, per un tipico modulo di circa 2m^2 → isolamento minimo di circa `20MΩ`. Pertanto, un singolo modulo FV con isolamento verso terra di `20MΩ` è da considerarsi come un modulo rispondente alle prove di tipo, ossia "non guasto".

Per fissare le idee sulla situazione presente in campo, si fa riferimento all’esempio della `Fig. 17`. Consideriamo una stringa composta da `31 moduli FV`, ciascuno con un isolamento verso terra di `20MΩ`. L'isolamento “complessivo" della stringa è dato quindi dal parallelo delle 31 resistenze ossia `20MΩ/31 = 0.64MΩ`.

`Fig. 17`: Esempio di utilizzo della funzione GFL

Questo valore di isolamento, misurato dallo strumento PVCHECKs-ONE sarebbe accettabile secondo le norme di prodotto dei moduli FV, ma è però in contrasto con la normativa di verifica `IEC/EN62446-1` che prevede come isolamento minimo `1MΩ`.
Questa "discordanza" normativa è nota ai costruttori di inverter che infatti rendono (normalmente) impostabile il valore minimo ammesso per l'isolamento e suggeriscono circa `100kΩ = 0.1MΩ` come valore sotto al quale l'inverter va in blocco (questo valore dipende dai costruttori, ad esempio SMA "suggerisce" `200kΩ`, Elettronica Santerno `150kΩ`).
Se si decidesse di accettare un valore limite minimo di `1MΩ`, questo renderebbe critica la localizzazione del guasto.

**PVCHECKs - ONE IT**

Infatti, nell'esempio precedentemente riportato in `Fig. 17`, siccome nessuno dei moduli FV è realmente guasto, i potenziali del polo positivo e negativo sono sostanzialmente simmetrici rispetto a terra (`+620V` e `-620V`) quindi lo strumento rileverebbe erroneamente “guasto" un modulo con resistenza di isolamento pari a `0.64MΩ`, la cui posizione è calcolata nel modo seguente (in accordo alle prescrizioni della `IEC/EN62446-1`):

`Posizione guasto = VT / Vmod`

In cui:
* `VT` = minimo valore tra VPE e VEN
* `Vmod` = tensione di un singolo modulo

Pertanto: `Pos. Guasto = 620 / 40 = 15.5` (in prossimità del 15° modulo della stringa).
Il suddetto modulo in realtà, per ipotesi non è affatto guasto e, testato singolarmente presenterebbe, come tutti gli altri moduli, un isolamento verso terra pari a `20MΩ`.
In questo caso, impostando ad esempio un limite di isolamento minimo pari a `230kΩ = 0.23MΩ`, esso può ritenersi un **valore ragionevole che consente di supporre la presenza di un effettivo SINGOLO guasto di isolamento verso terra** (che è l'ipotesi principale su cui si regge la procedura indicata dalla norma `IEC/EN62446` a cui è conforme la funzione GFL dello strumento PVCHECKs-ONE).

**PVCHECKs - ONE IT**

#### 11.4. FUNZIONI DUAL E TMR – APPROFONDIMENTI TECNICI

Le funzioni DUAL e TMR sono i due modi con cui lo strumento PVCHECKs-ONE realizza le misure di isolamento su installazioni FV. In particolare:
* **Modo DUAL** → permette di eseguire la misura di isolamento su singoli moduli, su singole stringhe, su stringhe in parallelo e su interi campi FV operando sui poli (+) e (-) degli stessi, **senza la necessità di collegarli in cortocircuito**. La funzione garantisce drastica riduzione dei tempi di prova, flessibilità, e immediato riscontro dello stato di isolamento di entrambe le polarità, ma per contro essa deve riconoscere sempre la presenza di una **tensione tra i poli positivo e negativo VPN > 15VDC** al fine di eseguire il test. Questa funzione **NON può essere usata in presenza di dispositivi MLPE** (a meno di scollegarli preventivamente). In tali condizioni usare il modo “OPT” (vedere § `6.6`).
* **Modo TMR** → permette di eseguire la “tipica” misura di isolamento **tra il polo (-) e/o il polo (+)** del modulo/stringa/campo FV **verso terra**, testare isolamento di cavi di collegamento, parti dell’inverter, sicurezza elettrica in generale secondo `IEC/EN62446-1` in modo continuo impostando un timer di misura nell’intervallo `3s ÷ 999s` senza alcun vincolo di tensione necessariamente presente tra i poli (come avviene invece nel modo DUAL) → Il metodo richiede di eseguire necessariamente **più di una misura** sulle stringhe.

##### 11.4.1. Aspetti normativi e teorici della misura di isolamento

La normativa `IEC/EN62446-1` indica che la misura di isolamento dei circuiti associati ad un impianto FV (singoli moduli, stringhe, campi FV, collegamenti, ecc...) debba essere eseguita, valutando sempre il valore minimo della resistenza, con uno dei seguenti metodi:
1. Misura resistenza di isolamento **verso terra** del polo positivo e del polo negativo di moduli/stringhe/campi FV (metodo usato nel **modo TMR** e più accuratamente nel **modo DUAL** di PVCHECKs-ONE, PVCHECKs-PRO e PV-ISOTEST).
2. Misura della resistenza di isolamento verso terra del polo positivo e negativo cortocircuitati preventivamente tra loro (metodo usato dal modello PVCHECKs).

###### Metodo 1

Anche se gli impianti FV nascono sostanzialmente come dei **sistemi IT** (quindi non aventi un sistema di terra fisicamente realizzato), tra i poli (+) / Terra e (-) / Terra sono sempre presenti tensioni aleatorie di disturbo dovute a parametri “parassiti” (tipicamente effetti ohmico capacitivi) indicate come `Vop` e `Von` nello schema di principio seguente (vedere `Fig. 18` - parte sinistra):

`Fig. 18`: Schema e circuito equivalente del Metodo 1

**PVCHECKs - ONE IT**

In cui:
* `Vtest` = tensione di prova del misuratore di isolamento
* `Itest` = corrente di prova erogata per effetto della tensione di prova applicata
* `Vdc` = tensione di stringa
* `Rp` = resistenza di isolamento del polo (+) verso terra
* `Rn` = resistenza di isolamento del polo (-) verso terra
* `Vop` = tensione aleatoria “parassita” del polo (+) verso terra
* `Von` = tensione aleatoria “parassita” del polo (-) verso terra

Le tensioni di disturbo `Vop` e `Von` sono dipendenti da diversi fattori tra cui la tensione di stringa, le condizioni ambientali e la presenza stessa dello strumento e possono significativamente influenzare la misura di isolamento.
Applicando la regola di semplificazione secondo Thévenin è possibile fare riferimento al circuito equivalente (vedere `Fig. 18` - parte destra), riferito ad esempio al polo (+) della stringa:

In cui:
`Re = Rp // Rn = (Rp * Rn) / (Rp + Rn)`
`Itest = (Vtest - Vop) / Re`
`Vop = Vdc * Rp / (Rp + Rn)`

Consideriamo il seguente esempio:
* `Vtest` = 500VDC
* `Rp` = 10MΩ → Isolamento supposto corretto (`>1MΩ`) sul polo (+)
* `Rn` = 0.1MΩ → Isolamento supposto incorretto (`< 1MΩ`) sul polo (-)
* `Vdc` = 490VDC
* `Vop` ≈ 490V
* `Re` ≈ 0.1MΩ
* `Itest` ≈ 100μA

Il misuratore di isolamento (modo TMR) misura `Vtest` e `Itest` e calcola invece la seguente resistenza di isolamento:
`Re EFF = Vtest / Itest = 500V / 100μA = 5MΩ`

Pertanto, per effetto della presenza di `Vop`, pur avendo un basso isolamento sul polo (-) lo strumento fornisce un valore **NON corretto** di buon isolamento nella misura eseguita sul polo (+) → la misura con **Metodo 1** può essere affetta quindi da un errore che dipende dall’entità delle tensioni di disturbo.
Il **modo DUAL** (allo stato attuale presente solo sugli strumenti HT) ricade sempre nella tipologia del Metodo 1 ma usa **equazioni di calcolo più complesse** (non basate sulla semplice Legge di Ohm) che tengono conto degli effetti delle tensioni di disturbo, **NON è affetto da questi errori** e fornisce sempre correttamente con unica misura le seguenti informazioni:
* Resistenza di isolamento del polo `R (+)` verso terra
* Resistenza di isolamento del polo `R (-)` verso terra
* Resistenza `Rp = R (+) // R (-)` del parallelo tra le resistenze di isolamento dei due poli che è usata come valore di riferimento per il confronto con il valore limite minimo (tipicamente `1MΩ`).

**PVCHECKs - ONE IT**

###### Metodo 2

Questo metodo (vedere `Fig. 19`) prevede la chiusura in corto circuito (tramite apposito dispositivo di sicurezza) dei due poli (+) e (-) allo scopo di **azzerare la tensione di disturbo Vo** per poi eseguire una misura di resistenza di isolamento «classica» fra il punto comune dei poli in cortocircuito e terra.

`Fig. 19`: Schema e circuito equivalente del Metodo 2

Gli svantaggi di questo metodo (usato dal modello PVCHECKs che esegue automaticamente il cortocircuito interno dei poli della stringa) sono i seguenti:
* Le resistenze di isolamento dei due poli sono in parallelo → lo strumento esegue sempre e fornisce solo la misura di tale `Rp`, dunque, **non è possibile** evidenziare il polo in cui sia presente un problema di basso isolamento.
* È possibile testare **SOLO una stringa per volta** al fine di non raggiungere valori di corrente di cortocircuito troppo elevati che potrebbero danneggiare lo strumento (`max 15A` per PVCHECKs).

**PVCHECKs - ONE IT**

#### 11.5. CARATTERISTICHE GENERALI MLPE (OTTIMIZZATORI E DISPOSITIVI RSD)

I dispositivi elettronici di potenza a livello di modulo (`MLPE`), inclusi microinverter, ottimizzatori DC e dispositivi di spegnimento rapido (`RSD`), sono progettati per migliorare sia la resa energetica che la sicurezza dei singoli moduli fotovoltaici. I microinverter e gli ottimizzatori DC disaccoppiano elettricamente ciascun modulo dalla stringa, consentendo un funzionamento completamente indipendente e massimizzando la produzione di energia in condizioni di irraggiamento non uniforme o di disallineamento. Questi dispositivi consentono inoltre un monitoraggio dettagliato a livello di modulo.

##### 11.5.1. Caratteristiche dei dispositivi RSD

I dispositivi di spegnimento rapido `RSD = Rapid ShutDown` sono principalmente componenti di sicurezza. Essi diseccitano i conduttori del modulo in caso di emergenza per soddisfare i requisiti dei sistemi antincendio e di spegnimento rapido in modo da fornire un valido supporto agli operatori del settore in caso di pericolo (ex: vigili del fuoco). Pur fungendo da sezionatori a livello di modulo, non offrono funzionalità di ottimizzazione delle prestazioni o di monitoraggio.

##### 11.5.2. Caratteristiche generali degli ottimizzatori di potenza

Nel settore fotovoltaico, lo scopo principale degli ottimizzatori di potenza è massimizzare la produzione energetica di ogni singolo modulo, indipendentemente dagli altri, mitigando gli effetti di ombreggiamento, mismatch e invecchiamento. Ciò si traduce in un aumento complessivo della resa energetica del sistema, una maggiore flessibilità di installazione e un miglioramento della gestione e della sicurezza del sistema. Ogni ottimizzatore è collegato a un singolo modulo (o a un piccolo gruppo di moduli) e gestisce autonomamente la propria potenza. Senza ottimizzatori, se un pannello subisce ombreggiamento o presenta prestazioni inferiori, limita la corrente dell'intera stringa collegata in serie. Con gli ottimizzatori, ogni pannello continua a funzionare al massimo potenziale anche quando gli altri moduli presentano problemi di prestazioni.
Per fissare le idee, se ad esempio si considera una serie di moduli FV e uno di questi è sottoperformante, si assiste alla **limitazione della corrente dell’intera stringa**. Facendo un’analogia idraulica, il modulo sottoperformante potrebbe essere considerato come la strozzatura di un tubo che limita il passaggio del flusso nella conduttura. Se su ogni modulo FV e in particolare su quello guasto sono installati anche gli ottimizzatori, la corrente che non può passare attraverso il modulo con prestazioni inferiori è by-passata dall'ottimizzatore. Ancora sul paragone idraulico è come se fosse presente un tubo di by-pass ausiliario in cui si convoglia il flusso che non può passare nella strozzatura del tubo principale. Sulla base della precedente descrizione, una stringa di moduli FV comprendente ottimizzatori può essere schematizzata elettricamente nel collegamento della `Fig. 20`.

`Fig. 20`: Collegamento di una stringa FV con presenza di ottimizzatori di potenza

**PVCHECKs - ONE IT**

##### 11.5.3. Test IVCK o curve I-V su dispositivi MLPE

Sulla base dei principi di funzionamento dei dispositivi MLPE, eseguire test IVCK o curve I-V su stringhe fotovoltaiche che incorporano microinverter o ottimizzatori DC non solo è **inutile, ma anche tecnicamente inappropriato**. Questi sistemi, infatti, disaccoppiano elettricamente ciascun modulo dalla stringa, impedendo qualsiasi caratterizzazione significativa di curve I-V o misura Isc a livello di stringa. Eseguire questi test può comportare il rischio di danneggiamento sia dei dispositivi MLPE che dello strumento di prova.

##### 11.5.4. Misura di isolamento su dispositivi MLPE (funzione OPT)

Facendo riferimento allo schema della `Fig. 20`, se un inverter connesso ad una stringa FV composta da una serie di ottimizzatori, va in blocco per basso isolamento verso terra, le cause possibili (escludendo problemi all’inverter) possono essere le seguenti:
1. Uno o più moduli FV ha una dispersione verso terra.
2. Uno o più ottimizzatori ha una dispersione verso terra.

In generale per un inverter connesso ad un quadro di campo in cui una delle stringhe (dotata di ottimizzatori) presenti problemi di basso isolamento, si può procedere con la misura stringa per stringa. Quando si è individuata la stringa avente il basso isolamento, si può procedere alla ricerca del/dei moduli + ottimizzatori con dispersione sezionandola in sotto parti.
Poiché uno dei due poli dell'ottimizzatore è elettricamente "passante", potrebbero verificarsi sia un basso isolamento all'interno dell'ottimizzatore stesso, sia un basso isolamento nel modulo fotovoltaico associato. Pertanto, per determinare se il guasto di isolamento abbia origine nel modulo fotovoltaico o nell'ottimizzatore, **è necessario scollegarli e testare ciascun componente separatamente**.

**PVCHECKs - ONE IT**

##### 11.5.5. Tipologie misure di isolamento con ottimizzatori di potenza

La misura di isolamento dipende sostanzialmente dal tipo di ottimizzatore installato. In particolare, si possono distinguere due famiglie di ottimizzatori:
* Ottimizzatori dotati di funzione “spegnimento rapido → `RSD = Rapid ShutDown`”.
* Ottimizzatori **NON** dotati di funzione RSD.

Gli ottimizzatori di potenza e il "rapid shutdown" (spegnimento rapido) sono due componenti essenziali degli impianti fotovoltaici moderni. Nei dispositivi dotati di questa funzione, essa riduce automaticamente la tensione in uscita fino ad un valore quasi nullo in particolari condizioni, fra cui la disconnessione della stringa dall’inverter. Questa combinazione migliora la sicurezza in caso di emergenza per i soccorritori (ad esempio i vigili del fuoco) in modo da garantire la conformità alle relative normative. I principali costruttori hanno ottimizzatori che includono la funzione RSD ed alcuni dispongono di modelli con/senza la funzione oppure attivabile solo dal relativo inverter.
La funzione RSD è regolamentata dalla normativa USA `NEC 690.12` la quale impone che la tensione totale ai capi della stringa costituita dagli ottimizzatori deve essere mantenuta **minore di 30V entro 30s** dalle varie condizioni di guasto incluso il caso della stringa disconnessa.
A livello di test di isolamento la presenza/assenza della funzione RSD modifica il tipo di prova eseguibile in quanto:
* Con dispositivi RSD presenti → in tal caso la tensione di uscita è praticamente nulla pertanto **è possibile eseguire il cortocircuito fra i poli di uscita della stringa di ottimizzatori**.
* Con dispositivi RSD non presenti → la tensione in uscita alla stringa di ottimizzatori è sostanzialmente pari alla tensione totale di stringa dei moduli FV → in tal caso **non si può fare un cortocircuito dei poli** per tutto il tempo necessario ad eseguire la misura di isolamento (circa `10sec`).

**PVCHECKs - ONE IT**

### 12. ASSISTENZA

#### 12.1. CONDIZIONI DI GARANZIA

Questo strumento è garantito contro ogni difetto di materiale e fabbricazione, in conformità con le condizioni generali di vendita. Durante il periodo di garanzia, le parti difettose possono essere sostituite, ma il costruttore si riserva il diritto di riparare ovvero sostituire il prodotto. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballo originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente. Il costruttore declina ogni responsabilità per danni causati a persone o oggetti.
La garanzia non è applicata nei seguenti casi:
* Riparazione e/o sostituzione accessori e batteria (non coperti da garanzia).
* Riparazioni che si rendono necessarie a causa di un errato utilizzo dello strumento o del suo utilizzo con apparecchiature non compatibili.
* Riparazioni che si rendono necessarie a causa di un imballaggio non adeguato.
* Riparazioni che si rendono necessarie a causa di interventi eseguiti da personale non autorizzato.
* Modifiche apportate allo strumento senza esplicita autorizzazione del costruttore.
* Utilizzo non contemplato nelle specifiche dello strumento o nel manuale d’uso.

Il contenuto del presente manuale non può essere riprodotto in alcuna forma senza l’autorizzazione del costruttore.
I nostri prodotti sono brevettati e i marchi depositati. Il costruttore si riserva il diritto di apportare modifiche alle specifiche ed ai prezzi se ciò è dovuto a miglioramenti tecnologici.

#### 12.2. ASSISTENZA

Se lo strumento non funziona correttamente, prima di contattare il servizio di assistenza, controllare lo stato delle batterie e dei cavi e sostituirli se necessario. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballaggio originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente.

---
**HT ITALIA SRL**  
Via della Boaria, 40  
48018 – Faenza (RA) – Italy  
T +39 0546 621002 | F +39 0546 621144  
M ht@ht-instruments.com | www.ht-instruments.it

**WHERE WE ARE**

**HT INSTRUMENTS SL**  
C/ Legalitat, 89  
08024 Barcelona – Spain  
T +34 934 081 777  
M sat@htinstruments.es | www.htinstruments.es

**HT INSTRUMENTS GmbH**  
Am Waldfriedhof 1b  
D-41352 Korschenbroich – Germany  
T +49 (0) 2161 564 581 | F +49 (0) 2161 564 583  
M info@ht-instruments.de | www.ht-instruments.de