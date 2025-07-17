# M75L

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-49 -->
© Copyright HT ITALIA 2024 Versione IT 5-01 - 13/12/24 ITALIANO Manuale d’uso

# MULTITEST M7xE - M75L

## INDICE

1.  PRECAUZIONI E MISURE DI SICUREZZA...................................................... 2
    1.1. Istruzioni preliminari ..................................................................... 2
    1.2. Durante l’utilizzo ....................................................................... 3
    1.3. Dopo l’utilizzo ......................................................................... 3
    1.4. Definizione di Categoria di misura (Sovratensione) ...................................... 3
2.  DESCRIZIONE GENERALE ................................................................... 4
    2.1. Funzionalità dello strumento ............................................................. 4
    2.2. Strumenti di misura a valore medio e a vero valore efficace ................................ 5
    2.3. Definizione di vero valore efficace e fattore di cresta ..................................... 5
3.  PREPARAZIONE ALL’UTILIZZO ............................................................... 6
    3.1. Controlli iniziali ....................................................................... 6
    3.2. Alimentazione dello strumento .......................................................... 6
    3.3. Conservazione ......................................................................... 6
4.  ISTRUZIONI OPERATIVE .................................................................... 7
    4.1. Descrizione dello strumento ............................................................ 7
    4.2. Accensione ........................................................................... 8
    4.3. Disabilitazione Auto Power OFF ......................................................... 8
    4.4. Modifica fondo scala dei trasduttori a pinza ............................................ 8
    4.5. Impostazione soglia limite minima misura di isolamento ................................. 8
    4.6. Funzioni HOLD, MAX/MIN/AVG, PEAK± ................................................... 9
    4.6.1. HOLD .......................................................................... 9
    4.6.2. MAX/MIN/AVG ................................................................... 9
    4.6.3. PEAK± .......................................................................... 9
    4.7. Misura Tensione DC/AC e Frequenza ................................................. 10
    4.7.1. Situazioni anomale .............................................................. 12
    4.8. Misura Corrente DC/AC e Frequenza ................................................. 13
    4.8.1. Situazioni anomale .............................................................. 15
    4.9. Misura Resistenza e Test continuità ................................................... 16
    4.9.1. Modalità "CAL" ................................................................. 16
    4.9.2. Situazioni anomale .............................................................. 17
    4.10. Verifica del senso ciclico e della concordanza di fase .................................. 18
    4.10.1. Situazioni anomale .............................................................. 21
    4.11. Verifica della mappatura di un cavo LAN ............................................. 22
    4.11.1. Situazioni anomale .............................................................. 23
    4.11.2. Nota esplicativa sulla condizione di errore split pairs ............................... 23
    4.11.3. Errori di cablaggio rilevati ...................................................... 24
    4.12. Continuità dei conduttori di protezione .............................................. 25
    4.12.1. Modalità "CAL" ................................................................. 26
    4.12.2. Situazioni anomale .............................................................. 28
    4.13. Misura Resistenza di isolamento ..................................................... 29
    4.13.1. Situazioni anomale .............................................................. 30
    4.14. Test su differenziali (RCD) di tipo AC e di tipo A ...................................... 31
    4.14.1. Misura del tempo di intervento .................................................. 31
    4.14.2. Misura della corrente di intervento (solo 30mA) .................................. 32
    4.14.3. Situazioni anomale .............................................................. 34
    4.15. Misura Resistenza globale di terra ................................................... 36
    4.15.1. Situazioni anomale .............................................................. 38
    4.16. Ciclo automatico di misure (AUTO) ................................................... 40
5.  MANUTENZIONE .......................................................................... 43
    5.1. Sostituzione batterie ................................................................. 43
    5.2. Pulizia dello strumento ................................................................ 43
    5.3. Fine vita ............................................................................ 43
6.  SPECIFICHE TECNICHE ................................................................... 44
    6.1. Normative di riferimento .............................................................. 46
    6.2. Caratteristiche generali .............................................................. 46
    6.3. Condizioni ambientali di utilizzo ...................................................... 46
    6.4. Accessori ........................................................................... 46
7.  ASSISTENZA ............................................................................ 47
    7.1. Condizioni di garanzia ................................................................ 47
    7.2. Assistenza .......................................................................... 47

## 1. PRECAUZIONI E MISURE DI SICUREZZA

I modelli della famiglia MULTITEST (M72E, M73E, M74E, M75E e M75L) sono stati progettati in conformità alle normative IEC/EN61557-1 e IEC/EN61010-1 relative agli strumenti di misura elettronici.

> **ATTENZIONE**
> Per la sicurezza dell'operatore e per evitare di danneggiare lo strumento, seguire le procedure descritte nel presente manuale e leggere con particolare attenzione tutte le note precedute dal simbolo !.

Prima e durante l’esecuzione delle misure attenersi scrupolosamente alle seguenti indicazioni:
*   Non effettuare misure in ambienti umidi, in presenza di gas o materiali esplosivi, combustibili o in ambienti polverosi
*   Evitare contatti con il circuito in esame se non si stanno effettuando misure
*   Evitare contatti con parti metalliche esposte, con terminali di misura inutilizzati, ecc
*   Non effettuare alcuna misura qualora si riscontrino anomalie nello strumento come, deformazioni, fuoriuscite di sostanze, assenza di visualizzazione sul display, ecc
*   Prestare particolare attenzione quando si effettuano misure di tensioni superiori a 25V in ambienti particolari (cantieri, piscine, ..) e 50V in ambienti ordinari in quanto è presente il rischio di shock elettrici.

Nel presente manuale e sullo strumento sono utilizzati i seguenti simboli:

*   : ATTENZIONE: attenersi alle istruzioni riportate nel manuale. Un uso improprio potrebbe causare danni allo strumento e situazioni pericolose per l’operatore
*   : Pericolo tensioni pericolose: rischio di shock elettrici
*   DC/AC: Tensione o corrente DC o AC
*   : Strumento con doppio isolamento
*   : Riferimento di terra
*   : Il simbolo indica che lo strumento non deve essere connesso a sistemi con tensione nominale concatenata (Fase - Fase) superiore a 605V.

### 1.1. ISTRUZIONI PRELIMINARI

*   Questo strumento è stato progettato per un utilizzo in ambiente con livello di inquinamento 2
*   Può essere utilizzato per verifiche su impianti elettrici con CAT III e massima tensione nominale concatenata (e verso Terra) di 550V
*   Seguire le normali regole di sicurezza orientate a proteggere l'operatore da correnti pericolose e proteggere lo strumento contro un utilizzo errato
*   Solo gli accessori forniti a corredo dello strumento garantiscono gli standard di sicurezza. Essi devono essere in buone condizioni e sostituiti, se necessario, con modelli identici
*   Non effettuare misure su circuiti che superano il limite di corrente e tensione specificato
*   Non effettuare misure in condizione ambientali al di fuori delle limitazioni indicate nel presente manuale
*   Controllare che le batterie siano inserite correttamente
*   Prima di collegare i puntali al circuito in esame, controllare che sia selezionata la funzione corretta

### 1.2. DURANTE L’UTILIZZO

Leggere attentamente le raccomandazioni e le istruzioni seguenti:

> **ATTENZIONE**
> La mancata osservazione delle avvertenze e/o istruzioni può danneggiare lo strumento e/o i suoi componenti o essere fonte di pericolo per l’operatore.

*   Prima di selezionare una nuova funzione scollegare i puntali di misura dal circuito in esame
*   Quando lo strumento è connesso al circuito in esame non toccare mai un qualunque terminale inutilizzato
*   Evitare la misura di resistenza in presenza di tensioni esterne; anche se lo strumento è protetto, una tensione eccessiva potrebbe causare malfunzionamenti dello strumento.

> **ATTENZIONE**
> Se durante l'utilizzo compare il simbolo di batteria scarica sospendere le prove e sostituire le batterie secondo la procedura descritta al § 5.2

### 1.3. DOPO L’UTILIZZO

*   Quando le misure sono terminate spegnere lo strumento
*   Se si prevede di non utilizzare lo strumento per un lungo periodo rimuovere le batterie

### 1.4. DEFINIZIONE DI CATEGORIA DI MISURA (SOVRATENSIONE)

La norma "IEC/EN 61010-1: Prescrizioni di sicurezza per apparecchi elettrici di misura, controllo e per utilizzo in laboratorio, Parte 1: Prescrizioni generali", definisce cosa si intenda per categoria di misura, comunemente chiamata categoria di sovratensione. Al § 6.7.4: Circuiti di misura, essa recita:

I circuiti sono suddivisi nelle seguenti categorie di misura:
*   La Categoria di misura **IV** serve per le misure effettuate su una sorgente di un’installazione a bassa tensione.
    *   Esempi sono costituiti da contatori elettrici e da misure sui dispositivi primari di protezione dalle sovracorrenti e sulle unità di regolazione dell’ondulazione.
*   La Categoria di misura **III** serve per le misure effettuate in installazioni all’interno di edifici.
    *   Esempi sono costituiti da misure su pannelli di distribuzione, disgiuntori, cablaggi, compresi i cavi, le barre, le scatole di giunzione, gli interruttori, le prese di installazioni fisse e gli apparecchi destinati all’impiego industriale e altre apparecchiature, per esempio i motori fissi con collegamento ad impianto fisso.
*   La Categoria di misura **II** serve per le misure effettuate su circuiti collegati direttamente all’installazione a bassa tensione.
    *   Esempi sono costituiti da misure su apparecchiature per uso domestico, utensili portatili ed apparecchi similari.
*   La Categoria di misura **I** serve per le misure effettuate su circuiti non collegati direttamente alla RETE DI DISTRIBUZIONE.
    *   Esempi sono costituiti da misure su non derivati dalla RETE e derivati dalla RETE ma con protezione particolare (interna). In quest’ultimo caso le sollecitazioni da transitori sono variabili, per questo motivo (OMISSIS) si richiede che l’utente conosca la capacità di tenuta ai transitori dell’apparecchiatura.

## 2. DESCRIZIONE GENERALE

Questo manuale si riferisce ai modelli M72E, M73E, M74E, M75E e M75L. Le caratteristiche dei modelli sono elencate nella seguente Tabella 1. Nel seguito del manuale con la parola “strumento” si intende genericamente il modello M75E salvo notazione all’occorrenza indicata. Il modello M75L ha le stesse caratteristiche di M74E

**Tabella 1: Caratteristiche dei modelli**

| Simbolo   | Descrizione misura                  | M72E | M73E | M74E | M75E | M75L |
| :-------- | :---------------------------------- | :--- | :--- | :--- | :--- | :--- |
| AUTO      | Misura AUTO di Ra, RCD, M           | ✓    | ✓    | ✓    |      | ✓    |
|  0.2A    | Continuità con 200mA                | ✓    | ✓    | ✓    | ✓    | ✓    |
| M        | Isolamento con 250,500VDC           | ✓    | ✓    | ✓    | ✓    | ✓    |
| RCD       | Test su RCD di tipo A e AC Generali | ✓    | ✓    | ✓    | ✓    | ✓    |
| Ra        | Resistenza Globale di Terra         | ✓    | ✓    | ✓    | ✓    | ✓    |
|           | Senso ciclico delle fasi            | ✓    | ✓    | ✓    | ✓    | ✓    |
| LAN       | Verifica mappatura di cavi di reti LAN |      |      |      | ✓    |      |
| V,A,Hz,  | Funzioni multimetro                 | ✓    | ✓    | ✓    | ✓    | ✓    |

### 2.1. FUNZIONALITÀ DELLO STRUMENTO

*   **V Hz**: Misura di tensione DC e AC TRMS, misura di frequenza
*   **A Hz**: Misura di corrente AC e DC tramite trasduttore a pinza avente fondo scala massimo 1V, misura di frequenza corrente AC
*   ****: Misura di resistenza / continuità con cicalino
*   **: Senso ciclico delle fasi a 1 o 2 terminali
*   **LAN**: Verifica del cablaggio (wire mapping) per cavi UTP/STP in qualunque categoria con connettore RJ45
*   ** 0.2A**: Continuità dei conduttori di terra, di protezione ed equipotenziali con corrente di prova superiore a 200mA e tensione a vuoto compresa tra 4V e 24V
*   **M**: misura della resistenza di isolamento con tensione continua di prova 250, 500V
*   **RCD**: Tempo e corrente di intervento su RCD Generali tipo AC () e A ()
*   **Ra**: Resistenza globale di terra senza intervento RCD
*   **AUTO**: Misure in Ra, RCD e M in sequenza automatica

### 2.2. STRUMENTI DI MISURA A VALORE MEDIO E A VERO VALORE EFFICACE

Gli strumenti di misura di grandezze alternate si dividono in due grandi famiglie:

*   Strumenti a **VALORE MEDIO**: strumenti che misurano il valore della sola onda alla frequenza fondamentale (50 o 60 Hz).
*   Strumenti a **VERO VALORE EFFICACE** anche detti TRMS (True Root Mean Square value): strumenti che misurano il vero valore efficace della grandezza in esame.

Gli strumenti a valore medio forniscono il valore efficace della sola onda fondamentale, gli strumenti TRMS forniscono invece il valore efficace dell’intera onda, armoniche comprese (entro la banda passante dello strumento). Pertanto i valori ottenuti sono identici solo se l’onda è puramente sinusoidale, con onde distorte gli strumenti a vero valore efficace forniscono valori corretti mentre le letture di strumenti a valore medio risultano errate.

### 2.3. DEFINIZIONE DI VERO VALORE EFFICACE E FATTORE DI CRESTA

Il valore efficace per la corrente è così definito: "In un tempo pari ad un periodo, una corrente alternata con valore efficace della intensità di 1A, circolando su di un resistore, dissipa la stessa energia che sarebbe dissipata, nello stesso tempo, da una corrente continua con intensità di 1A". Da questa definizione discende l’espressione numerica:

G=  + T t t dt t g T 0 0 ) ( 1 2

Il valore efficace viene indicato come RMS (root mean square value)

Il Fattore di Cresta è definito come il rapporto fra il Valore di Picco di un segnale ed il suo Valore Efficace: CF (G)= RMS p G G

Questo valore varia con la forma d'onda del segnale, per un’onda puramente sinusoidale esso vale 2 =1.41. In presenza di distorsioni il Fattore di Cresta assume valori tanto maggiori quanto più è elevata la distorsione dell’onda.

## 3. PREPARAZIONE ALL’UTILIZZO

### 3.1. CONTROLLI INIZIALI

Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili affinché lo strumento potesse essere consegnato senza danni. Si consiglia in ogni caso di controllarlo sommariamente per accertare eventuali danni subiti durante il trasporto. Se si dovessero riscontrare anomalie contattare immediatamente il rivenditore. Si consiglia inoltre di controllare che l’imballaggio contenga tutte le parti indicate al § 6.4. In caso di discrepanze contattare il rivenditore. Qualora fosse necessario restituire lo strumento, si prega di seguire le istruzioni riportate al § 7.

### 3.2. ALIMENTAZIONE DELLO STRUMENTO

Lo strumento è alimentato con 4x1.5V batterie alcaline tipo AA LR06. Quando le batterie sono scariche, il simbolo di batteria scarica " " viene indicato. Per la sostituzione delle batterie seguire le istruzioni indicate al § 5.2.

### 3.3. CONSERVAZIONE

Per garantire misure precise, dopo un lungo periodo di conservazione in condizioni ambientali estreme, attendere che lo strumento ritorni alle condizioni normali (vedere § 6.3).

## 4. ISTRUZIONI OPERATIVE

### 4.1. DESCRIZIONE DELLO STRUMENTO

LEGENDA:
1.  Ingressi
2.  Display LCD
3.  Tasto ON/OFF
4.  Tasto MODE/ PEAK
5.  Tasti freccia
6.  Tasto FUNC/ HOLD
7.  Tasto GO
8.  Unità remote #1 e #2 per la verifica dei cablaggi LAN (M75E)

**Fig. 1**: Descrizione dello strumento

LEGENDA:
1.  Terminale di ingresso B2
2.  Terminale di ingresso B1
3.  Slitta scorrevole per inserimento connettori RJ45 di reti LAN (M75E)

**Fig. 2**: Descrizione degli ingressi dello strumento

**Tabella 2: Descrizione dei tasti funzione dello strumento**

| Tasto        | Descrizione                                                                 |
| :----------- | :-------------------------------------------------------------------------- |
| ON/OFF       | per accendere e spegnere lo strumento                                       |
| GO           | per avviare l’esecuzione di una misura                                     |
| MODE/PEAK    | per selezionare la modalità di funzionamento e la misura di picco           |
| Tasti freccia | per selezionare la misura                                                 |
| FUNC/HOLD    | per selezionare le funzioni interne e per bloccare l’aggiornamento del display |

### 4.2. ACCENSIONE

All’accensione lo strumento emette un breve segnale acustico e per circa un secondo visualizza tutti i segmenti del display. Successivamente mostra il modello e la versione del firmware caricata (vedere esempio a fianco relativo a M75E), quindi si pone nell’ultima modalità di misurazione selezionata prima dello spegnimento.

### 4.3. DISABILITAZIONE AUTO POWER OFF

Lo strumento si spegne dopo circa 10 minuti di non utilizzo. Per riattivare lo strumento occorre riaccenderlo premendo l’apposito tasto. Per permettere l’esecuzione di misurazioni protratte nel tempo può essere utile disattivare la funzione. In tal caso lo strumento resterà sempre acceso e potrà essere spento dall’operatore solo premendo l’apposito tasto. Per disattivare l’autospegnimento operare come segue:
1.  Mantenendo premuto il tasto FUNC/HOLD accendere lo strumento con il tasto ON/OFF. Il simbolo “” scompare a display
2.  Alla successiva accensione la funzione sarà automaticamente attivata e il simbolo “” riappare a display

### 4.4. MODIFICA FONDO SCALA DEI TRASDUTTORI A PINZA

Lo strumento esegue la misura della corrente AC o DC tramite trasduttori a pinza collegati ai terminali d’ingresso. A differenza dei tradizionali multimetri quindi non è necessario interrompere il circuito di corrente per inserire il dispositivo di misura, inoltre si possono utilizzare pinze con fondo scala diverso, adatto alle correnti che si vogliono misurare di volta in volta. Per una misura corretta di corrente è necessario impostare sullo strumento lo stesso fondo scala impostato sulla pinza. Per impostare il fondo scala della pinza operare come segue:
1.  Mantenendo premuto il tasto MODE/PEAK accendere lo strumento con il tasto ON/OFF. Lo strumento visualizza il messaggio “SET” e il valore del fondo scala impostato
2.  Premere i tasti freccia fino a selezionare il fondo scala desiderato (valori possibili sono 1, 10, 20, 30, 100, 200, 300, 400, 1000, 2000, 3000A)
3.  Premere il tasto MODE/PEAK due volte per salvare e uscire dalla funzione

### 4.5. IMPOSTAZIONE SOGLIA LIMITE MINIMA MISURA DI ISOLAMENTO

Per impostare il limite minimo riconosciuto dallo strumento nella misura di isolamento (vedere § 4.13) operare come segue:
1.  Mantenendo premuto il tasto MODE/PEAK accendere lo strumento con il tasto ON/OFF. Lo strumento visualizza il messaggio “SET” e il valore del fondo scala della pinza impostato
2.  Premere il tasto MODE/PEAK per visualizzare il valore della soglia limite impostato
3.  Premere i tasti freccia fino a selezionare il valore desiderato (valori possibili sono 0.25, 0.50, 1.00M)
4.  Premere il tasto MODE/PEAK per uscire dalla funzione

### 4.6. FUNZIONI HOLD, MAX/MIN/AVG, PEAK±

Nelle misurazioni di tensione AC/DC, corrente AC/DC, frequenza e resistenza sono disponibili alcune tra le funzioni di seguito descritte.

#### 4.6.1. HOLD

Durante la misurazione delle grandezze: tensione AC/DC, corrente AC/DC, frequenza e resistenza premere il tasto FUNC/HOLD per bloccare la visualizzazione del valore misurato della grandezza in esame. Sul display compare il simbolo HOLD indicante che la funzione è stata attivata. Per uscire dalla funzione HOLD premere nuovamente il tasto FUNC/HOLD oppure i tasti freccia. Questa funzione non è disponibile qualora sia attiva la funzione MAX/MIN/AVG o PEAK±.

#### 4.6.2. MAX/MIN/AVG

Durante la misurazione delle grandezze: tensione AC/DC, corrente AC/DC, frequenza e resistenza premere il tasto FUNC/HOLD per 2 secondi per entrare nella funzione di misurazione e visualizzazione dei valori massimo (MAX), minimo (MIN) e medio (AVG) della grandezza in esame che si presentano ciclicamente ad ogni successiva pressione del tasto FUNC/HOLD. Sul display viene riportato il simbolo relativo al valore visualizzato. Le rilevazioni dei valori massimo, minimo e medio partono dal momento nel quale si entra in questa funzione e vengono costantemente aggiornati anche se non sono visualizzati. Ciò significa che, mentre si visualizza ad esempio il valore medio della corrente AC, i valori minimo e massimo della medesima grandezza vengono costantemente aggiornati. Per uscire dalla funzione MAX/MIN/AVG premere nuovamente il tasto FUNC/HOLD per 2 secondi oppure i tasti freccia. La funzione MAX/MIN/AVG non è disponibile qualora sia attiva la funzione HOLD o PEAK±.

#### 4.6.3. PEAK±

Durante la misurazione delle grandezze: tensione AC/DC e corrente AC/DC premere il tasto MODE/PEAK per 2 secondi per entrare nella funzione di misurazione e visualizzazione dei valori di picco massimo (PEAK+) e minimo (PEAK-), con risoluzione 1ms, della grandezza in esame che si presentano ciclicamente ad ogni successiva pressione del tasto MODE/PEAK. Sul display viene riportato il simbolo relativo al valore visualizzato. Le rilevazioni dei valori di picco massimo e minimo partono dal momento nel quale si entra in questa funzione e vengono costantemente aggiornati anche se non sono visualizzati. Ciò significa che, mentre si visualizza ad esempio il valore di picco massimo della corrente AC, il valore di picco minimo della medesima grandezza viene costantemente aggiornato. Nelle visualizzazioni dei valori di picco massimo e minimo non viene visualizzato se la grandezza fosse AC o DC in quanto il valore di picco prescinde da tale informazione. Per uscire dalla funzione PEAK± premere nuovamente il tasto MODE/PEAK per 2 secondi oppure i tasti freccia. Le funzioni HOLD e MAX/MIN/AVG non sono disponibili in modalità PEAK±.

### 4.7. MISURA TENSIONE DC/ AC E FREQUENZA

> **ATTENZIONE**
> La massima tensione ammissibile in ingresso è 550+10%V. Non misurare tensioni che eccedano i limiti indicati in questo manuale. Il superamento di tali limiti potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.

**Fig. 3**: Connessione dei terminali dello strumento

1.  Accendere lo strumento con il tasto ON/OFF
2.  Usare i tasti freccia per selezionare la funzione V Hz
3.  Inserire il cavo nero ed il cavo verde nei rispettivi terminali di ingresso dello strumento
4.  Se necessario innestare i coccodrilli sui puntali di misura
5.  Collegare i terminali dello strumento nei punti desiderati del circuito in esame (si veda la Fig. 3), i valori di tensione e frequenza verranno visualizzati sul display con selezione automatica della portata
6.  Lo strumento commuta automaticamente tra la lettura di tensione AC e la lettura di tensione DC in base al segnale applicato ai terminali di misura
7.  Esempio di visualizzazione dei valori di tensione AC e frequenza rilevati. Si noti che il limite minimo della lettura di tensione AC è 1mV, qualora il valore in ingresso fosse inferiore a tale limite lo strumento segnalerà 0.0V in ingresso
    *   Valore misurato della tensione
    *   Valore misurato della frequenza
8.  Esempio di visualizzazione del valore di tensione DC rilevato. Si noti che il limite minimo della lettura di tensione DC è 1mV, qualora il valore in ingresso fosse inferiore a tale limite lo strumento segnalerà 0.0V in ingresso
    *   Valore misurato della tensione
9.  Premere il tasto MODE/PEAK per passare alla misurazione della frequenza (solo per misure in AC)
10. Premere il tasto MODE/PEAK per 2 secondi per attivare la rilevazione del valore di picco di tensione (vedere § 4.6.3)
11. Premere il tasto FUNC/HOLD per bloccare i valori letti (vedere § 4.6.1)
12. Premere il tasto FUNC/HOLD per 2 secondi per attivare la rilevazione del valore massimo, minimo e medio di tensione (vedere § 4.6.2)

Misura della frequenza
1.  Per potere effettuare le rilevazioni dei valori minimo, medio, massimo e di picco della frequenza è necessario passare alla misurazione di tale parametro
2.  Dalla funzione di misurazione della tensione premendo il tasto MODE/PEAK per meno di un secondo si passa alla funzione di misurazione della frequenza
3.  Esempio di visualizzazione del valore di frequenza rilevato. Si noti che il limite minimo della lettura di frequenza è 30.0Hz, qualora il valore in ingresso fosse inferiore a tale limite lo strumento segnalerà <30.0Hz
    *   Valore misurato della frequenza
4.  Premere il tasto MODE/PEAK per ritornare alla misurazione della tensione
5.  Premere il tasto MODE/PEAK per 2 secondi per attivare la rilevazione del valore di picco di frequenza (vedere § 4.6.3)
6.  Premere il tasto FUNC/HOLD per bloccare il valore di frequenza letto (vedere § 4.6.1)
7.  Premere il tasto FUNC/HOLD per 2 secondi per attivare la rilevazione del valore massimo, minimo e medio di frequenza (vedere § 4.6.2)

#### 4.7.1. Situazioni anomale

1.  Qualora il valore di tensione misurato ecceda i 550+10%V TRMS lo strumento visualizza la videata accanto. Scollegare immediatamente lo strumento dal circuito in esame per prevenire shock elettrici all’utilizzatore e danni allo strumento. La massima tensione assoluta ammissibile in ingresso è 605V
    *(Immagine/Icona non disponibile nel testo originale)*
2.  Qualora durante una misurazione di tensione il valore di frequenza misurato ecceda i 400Hz lo strumento visualizza la videata accanto
    *(Immagine/Icona non disponibile nel testo originale)*
3.  Qualora, effettuando una misurazione di frequenza, il valore misurato ecceda i 400Hz lo strumento visualizza la videata accanto
    *(Immagine/Icona non disponibile nel testo originale)*
4.  Qualora, effettuando una misurazione di frequenza, il valore misurato non raggiunga i 30.0Hz lo strumento visualizza la videata accanto
    *(Immagine/Icona non disponibile nel testo originale)*

### 4.8. MISURA CORRENTE DC/ AC E FREQUENZA

**Fig. 4**: Connessione dei terminali dello strumento

1.  Accendere lo strumento con il tasto ON/OFF
2.  Usare i tasti freccia per selezionare la funzione A Hz
3.  Inserire i connettori a banana del trasduttore a pinza nei rispettivi terminali di ingresso dello strumento (nero con nero, verde o rosso con verde). Per trasduttori dotati di connettore FRB Hypertac è necessario l’accessorio opzionale NOCANBA
4.  Assicurarsi che il fondo scala della pinza in uso e quello impostato sullo strumento coincidano. Diversamente la misura fornita dallo strumento risulterà errata. Per la procedura di impostazione del fondo scala della pinza vedere il § 4.4
5.  Aprire il toroide ed inserire il cavo al centro del medesimo (vedere Fig. 4), i valori della corrente e della frequenza verranno visualizzati sul display
6.  Lo strumento commuta automaticamente tra la lettura di corrente AC e la lettura di corrente DC in base al segnale applicato ai terminali di misura
7.  Esempio di visualizzazione del valore di corrente DC rilevato. Si noti che il limite minimo della lettura di tensione DC è 1.0mV, qualora il valore in ingresso fosse inferiore a tale limite lo strumento segnalerà 0.0A in ingresso
    *   Valore misurato della corrente
    *(Immagine/Icona non disponibile nel testo originale)*
8.  Esempio di visualizzazione dei valori di corrente AC e frequenza rilevati. Si noti che il limite minimo della lettura di tensione AC è 1.0mV, qualora il valore in ingresso fosse inferiore a tale limite lo strumento segnalerà 0.0A in ingresso
    *   Valore misurato della corrente
    *   Valore misurato della frequenza
    *(Immagine/Icona non disponibile nel testo originale)*

Si noti che il limite minimo della lettura di corrente AC e DC è dato dalla relazione:
1mV x costante di trasduzione della pinza
pertanto, con una pinza 400A/400mV, la minima corrente misurabile è 1.0A. Qualora il valore in ingresso fosse inferiore a tale limite lo strumento segnalerà 0.0A in ingresso

9.  Premere il tasto MODE/PEAK per passare alla misurazione della frequenza (solo per misure in AC, vedere § 0)
10. Premere il tasto MODE/PEAK per 2 secondi per attivare la rilevazione del valore di picco di corrente (vedere § 4.6.3)
11. Premere il tasto FUNC/HOLD per bloccare i valori letti (vedere § 4.6.1)
12. Premere il tasto FUNC/HOLD per 2 secondi per attivare la rilevazione del valore massimo, minimo e medio di corrente (vedere § 4.6.2)

Misurazione della frequenza attraverso il toroide
1.  Per potere effettuare le rilevazioni dei valori minimo, medio, massimo e di picco della frequenza è necessario passare alla misurazione di tale parametro
2.  Dalla funzione di misurazione della corrente premendo il tasto MODE/PEAK si passa alla funzione di misurazione della frequenza
3.  Esempio di visualizzazione del valore di frequenza rilevato. Si noti che il limite minimo della lettura di frequenza è 30.0Hz, qualora il valore in ingresso fosse inferiore a tale limite lo strumento segnalerà <30.0Hz
    *   Valore misurato della frequenza
    *(Immagine/Icona non disponibile nel testo originale)*
4.  Premere il tasto MODE/PEAK per ritornare alla misurazione della corrente
5.  Premere il tasto MODE/PEAK per 2 secondi per attivare la rilevazione del valore di picco della frequenza (vedere § 4.6.3)
6.  Premere il tasto FUNC/HOLD per bloccare il valore di frequenza letto (vedere § 4.6.1)
7.  Premere il tasto FUNC/HOLD per 2 secondi per attivare la rilevazione del valore massimo, minimo e medio della frequenza (vedere § 4.6.2)

#### 4.8.1. Situazioni anomale

1.  Qualora il valore di corrente misurato ecceda il fondo scala della pinza lo strumento visualizza la videata accanto. Scollegare immediatamente la pinza dal circuito in esame per prevenire shock elettrici all’utilizzatore e danni allo strumento. Lo strumento è sovraccaricabile del 20% rispetto al fondo scala della pinza
    Esempio con fondo scala della pinza impostato a 400A AC
    *(Immagine/Icona non disponibile nel testo originale)*
2.  Qualora durante una misurazione di corrente il valore di frequenza misurato ecceda i 400Hz lo strumento visualizza la videata accanto
    *(Immagine/Icona non disponibile nel testo originale)*
3.  Qualora, effettuando una misurazione di frequenza, il valore misurato ecceda i 400Hz lo strumento visualizza la videata accanto
    *(Immagine/Icona non disponibile nel testo originale)*
4.  Qualora, effettuando una misurazione di frequenza, il valore misurato non raggiunga i 30.0Hz lo strumento visualizza la videata accanto
    *(Immagine/Icona non disponibile nel testo originale)*

### 4.9. MISURA RESISTENZA E TEST CONTINUITÀ

> **ATTENZIONE**
> Prima di effettuare una qualunque misura di resistenza accertarsi che il circuito non sia alimentato e che eventuali capacità presenti siano scariche, quindi eseguire la procedura di calibrazione dei cavi descritta di seguito.

**Fig. 5**: Connessione dei terminali dello strumento

1.  Accendere lo strumento con il tasto ON/OFF
2.  Usare i tasti freccia e selezionare la funzione 
3.  Qualora i cavi di misura in uso non siano stati calibrati in precedenza, effettuarne la calibrazione come descritto al § 4.9.1
4.  Inserire il cavo nero ed il cavo verde nei rispettivi terminali di ingresso dello strumento
    *   Valore misurato della resistenza
    *(Immagine/Icona non disponibile nel testo originale)*
5.  Posizionare i puntali nei punti desiderati del circuito in esame (vedere Fig. 5)
6.  Esempio di visualizzazione del valore di resistenza rilevato. Qualora tale valore sia < 40  lo strumento emette un segnale acustico
7.  Premere il tasto FUNC/HOLD per bloccare il valore letto (vedere § 4.6.1)
8.  Premere il tasto FUNC/HOLD per 2 secondo per attivare la rilevazione del valore massimo, minimo e medio (vedere § 4.6.2)
9.  Qualora sia applicata una tensione in ingresso la misura risulta inattendibile

#### 4.9.1. Modalità "CAL"

1.  Lo strumento deve essere nelle medesime condizioni operative nelle quali sarà durante le fasi di misurazione. Pertanto ogni aggiunta o sostituzione di cavi, prolunghe e coccodrilli invalidano la calibrazione precedente ed implicano una nuova calibrazione prima di effettuare ulteriori misurazioni
2.  Cortocircuitare tra di loro le estremità dei cavi di misura (vedere Fig. 6) prestando attenzione che le parti metalliche dei puntali o dei coccodrilli facciano ben contatto
    **Fig. 6**: Connessione dei terminali durante la procedura di calibrazione
3.  Premere il tasto MODE/PEAK per 2 secondi. Lo strumento azzera la resistenza dei cavi ed il simbolo CAL viene visualizzato sul display

> **ATTENZIONE**
> Contestualmente alla pressione del tasto MODE/PEAK lo strumento esegue la misura. Durante questa fase non scollegare i puntali dello strumento.

4.  Possono essere calibrati cavi che presentino una resistenza fino a 5 
5.  Al termine della calibrazione il valore misurato viene memorizzato dallo strumento e utilizzato come OFFSET (cioè viene sottratto da tutte le misure di continuità che si eseguono) per tutte le misure successive fino ad una nuova calibrazione
6.  Qualora il valore misurato durante la fase di calibrazione sia superiore a 5  (ex: terminali aperti) lo strumento rimuove il valore dell’offset precedentemente adottato e non visualizza il simbolo CAL fino alla successiva calibrazione effettuata con successo.
    Nota: questo metodo è utilizzabile per annullare l’ultima calibrazione effettuata
7.  Ad ogni spegnimento, e successiva riaccensione dello strumento, il valore calibrato viene annullato

#### 4.9.2. Situazioni anomale

1.  Il fondo scala dello strumento è 39.99k . Qualora il valore della resistenza misurata fosse superiore a tale limite, oppure in caso di puntali aperti od interrotti, lo strumento visualizza la videata a fianco
    *(Immagine/Icona non disponibile nel testo originale)*

### 4.10. VERIFICA DEL SENSO CICLICO E DELLA CONCORDANZA DI FASE

> **ATTENZIONE**
> La massima tensione ammissibile in ingresso è 550+10%V. Non misurare tensioni che eccedano i limiti indicati in questo manuale. Il superamento di tali limiti potrebbe causare shock elettrici all’utilizzatore e danni allo strumento. Non utilizzare lo strumento in impianti con tensione nominale concatenata maggiore di 550V.

**Fig. 7**: Connessione dei terminali dello strumento in prova

1.  Accendere lo strumento con il tasto ON/OFF
2.  Usare i tasti freccia per selezionare la funzione
3.  Premendo il tasto MODE/PEAK selezionare la funzione “1W”, misura ad un singolo terminale, o “2W”, misura a due terminali

> **ATTENZIONE**
> La modalità di misura 1W richiede che l'operatore tocchi il tasto di misura (senza guanti), che l'operatore sia al potenziale di terra e che il centro stella del sistema in esame sia al potenziale di terra. Solo soddisfacendo queste condizioni la modalità 1W fornisce risultati corretti. Qualora anche solo una delle condizioni sopra riportate non fosse verificata (operatore con guanti di protezione oppure su una scala, sistemi IT, ecc.) selezionare la modalità 2W.

4.  Inserire il cavo nero nel corrispondente terminale di ingresso dello strumento. Se necessario innestare il coccodrillo sul puntale di misura
5.  Qualora sia stata selezionata la misura a due terminali (modalità 2W) inserire il cavo verde nel corrispondente terminale di ingresso dello strumento e collegare puntale di misura al cavo di neutro od al cavo di protezione dell'impianto in esame (vedere Fig. 7). Se necessario innestare il coccodrillo sul puntale di misura
6.  Sul display compaiono i messaggi:
    "MEASURING…" ad indicare che lo strumento è pronto ad effettuare la rilevazione della prima tensione di fase
    "PH1" sul display secondario che invita l'operatore a collegare il cavo di misura al cavo della fase L1 (vedere Fig. 7)

> **ATTENZIONE**
> Per il corretto funzionamento della modalità 1W è necessario che il centro stella della terna trifase in esame sia al potenziale di terra.
> Negli impianti con neutro isolato come gli impianti IT (spesso presenti in ospedali, aeroporti, ecc.) è necessario selezionare la modalità 2W e collegare il puntale verde al conduttore di neutro (non al conduttore di protezione). In questo genere di impianti la modalità 1W potrebbe non dare risultati corretti.

7.  Solo per modalità 1W premere e mantenere premuto il tasto GO, o semplicemente toccare la superficie del tasto, per l'intera durata della misura. Collegare il puntale di misura alla fase L1 della terna trifase da verificare
8.  Quando viene rilevata una tensione superiore a 100V sul display principale viene visualizzato il simbolo "PH" ed il buzzer emette un suono prolungato

> **ATTENZIONE**
> Durante l’esecuzione della misura:
> *   Il tasto GO deve sempre essere mantenuto premuto o ne deve sempre essere toccata la superficie (solo per modalità 1W).
> *   Il puntale di misura, ad eccezione del cavo di fase in esame, non deve essere a contatto od in prossimità di qualunque sorgente di tensione che, per effetto della sensibilità dello strumento, potrebbe bloccare la misura.
> *   Il puntale di misura deve essere mantenuto a contatto col cavo di fase.

9.  Al termine della misura scompaiono i simboli "MEASURING…" e "PH1", il buzzer emette un suono intermittente fino alla disconnessione del puntale di misura dal cavo di fase
10. Scollegare il puntale di misura dal cavo della prima tensione di fase, sul display scompare il simbolo "PH" presente solo quando è rilevata tensione in ingresso
11. Solo per modalità 1W mantenere premuto il tasto GO, o semplicemente toccare la superficie del tasto, per l'intera durata della misura. Un eventuale rilascio e nuova pressione del tasto comporta l'azzeramento delle misurazioni effettuate, in tal caso ripetere le operazioni precedenti dal punto 6
12. Sul display compaiono i messaggi:
    "MEASURING…" ad indicare che lo strumento è pronto ad effettuare la rilevazione della seconda tensione di fase
    "PH2" sul display secondario che invita l'operatore a collegare il cavo di misura al cavo della fase L2 (vedere Fig. 7)

> **ATTENZIONE**
> Lasciando trascorrere oltre 10 secondi tra la prima e la seconda misura lo strumento presenta a display il messaggio "t.out" ed occorre ripetere l’intera procedura. Premere il tasto GO, quindi ripartire dal punto 6.

13. Solo per modalità 1W mantenere premuto il tasto GO, o semplicemente toccare la superficie del tasto, per tutta la durata della misura. Collegare il puntale di misura alla fase L2 della terna trifase da verificare
14. Quando viene rilevata una tensione superiore a 100V sul display principale viene visualizzato il simbolo "PH" ed il buzzer emette un suono prolungato

> **ATTENZIONE**
> Durante l’esecuzione della misura:
> *   Il tasto GO deve sempre essere mantenuto premuto o ne deve sempre essere toccata la superficie (solo per modalità 1W).
> *   Il puntale di misura, ad eccezione del cavo di fase in esame, non deve essere a contatto od in prossimità di qualunque sorgente di tensione che, per effetto della sensibilità dello strumento, potrebbe bloccare la misura.
> *   Il puntale di misura deve essere mantenuto a contatto col cavo di fase.

15. Al termine della prova, nel caso in cui i due cavi testati siano nella corretta sequenza delle fasi, lo strumento emette un doppio segnale acustico che segnala l'esito positivo della prova e visualizza una videata come quella a fianco
    *   Senso ciclico corretto
    *   Rotazione delle fasi
    *(Immagine/Icona non disponibile nel testo originale)*
16. Al termine della prova, nel caso in cui i due cavi appartengano alla stessa fase, lo strumento emette un doppio segnale acustico che segnala l'esito positivo della prova e visualizza una videata come quella a fianco
    *   Cavi appartenenti alla stessa fase
    *   Conformità tra un cavo e l'altro
    *(Immagine/Icona non disponibile nel testo originale)*
17. Al termine della prova, nel caso in cui i due cavi testati non siano nella corretta sequenza delle fasi, lo strumento emette un segnale acustico prolungato che segnala l'esito negativo della prova e visualizza una videata come quella a fianco
    *   Senso ciclico errato
    *   Rotazione delle fasi
    *(Immagine/Icona non disponibile nel testo originale)*
18. Per effettuare una nuova misurazione ripremere GO, quindi ripartire dal punto 6

> **ATTENZIONE**
> Individuare che due cavi sono in sequenza non implica che il terzo cavo sia anch'esso in sequenza. Per errore potrebbe essere stato eseguito un cablaggio con un cavo di fase ripetuto. Eseguire sempre almeno due misurazioni verificando i cavi due a due (esempio L1 e L2, poi L2 e L3) per avere certezza della presenza della terna trifase.

#### 4.10.1. Situazioni anomale

1.  Qualora si lasci trascorrere oltre 10 secondi tra la prima e la seconda misura lo strumento emette un segnale acustico prolungato che segnala l'esito negativo della prova e visualizza una videata come quella a fianco. Occorre ripetere l’intera procedura di misurazione, premere il tasto GO, quindi ripartire dal punto 6
    *(Immagine/Icona non disponibile nel testo originale)*
2.  Qualora sia selezionata la modalità 1W e lo strumento rilevi la connessione del secondo puntale come in modalità 2W viene visualizzata la videata a fianco e viene emesso un segnale acustico prolungato fino a che la condizione di errore non venga rimossa
    *(Immagine/Icona non disponibile nel testo originale)*
3.  Qualora sia selezionata la modalità 2W e lo strumento rilevi una tensione in ingresso (tra le due boccole) maggiore di 605V, viene visualizzata la videata a fianco e viene emesso un segnale acustico prolungato fino a che la condizione di errore non venga rimossa. Scollegare prontamente lo strumento
    *(Immagine/Icona non disponibile nel testo originale)*

### 4.11. VERIFICA DELLA MAPPATURA DI UN CAVO LAN

> **ATTENZIONE**
> Prima di effettuare una qualunque verifica del cablaggio accertarsi che il circuito in esame non sia alimentato. Collegamenti a linee telefoniche o reti dati attive potrebbero danneggiare lo strumento.

**Fig. 8**: Connessione dei terminali dello strumento in prova LAN

1.  Accendere lo strumento con il tasto ON/OFF
2.  Usare i tasti freccia per selezionare la funzione LAN
3.  Con il tasto MODE/PEAK selezionare il tipo di cavo in esame impostando STP se schermato, UTP se non schermato
4.  Connettere ad un’estremità del cavo in esame lo strumento ed all’altra estremità una delle unità remote (#1 o #2) utilizzando, se necessario, i cavetti in dotazione (vedere Fig. 8)

> **ATTENZIONE**
> La connessione dell’unità remota è necessaria ai fini dell’esecuzione delle misure.

5.  Premere il tasto GO, lo strumento esegue le prove in accordo al tipo di cavo impostato
6.  Al termine della prova, per cavi UTP/STP, qualora il cablaggio sia corretto, viene visualizzata una videata come quella riportata a fianco ove viene evidenziato il corretto cablaggio ed il numero identificativo dell’unità remota presente all’altro capo del cavo testato
    *   Numero identificativo dell’unità remota individuata
    *(Immagine/Icona non disponibile nel testo originale)*
7.  Qualora vengano rilevati cavi non conformi, al termine della misura verrà visualizzata una videata come quella riportata a fianco ove viene evidenziato il numero totale degli errori rilevati ed il numero dell’errore visualizzato. Premendo il tasto FUNC/HOLD è possibile scorrere tra le videate di visualizzazione degli errori di cablaggio riscontrati. Il numero dell'unità remota potrebbe non essere visualizzato
    *   Numero identificativo dell’unità remota qualora essa venga individuata
    *   Numero dell’errore visualizzato / numero degli errori riscontrati
    *(Immagine/Icona non disponibile nel testo originale)*

> **ATTENZIONE**
> Qualora si imposti il tipo di cavo UTP e si eseguano verifiche su cavi STP, i risultati forniti dallo strumento potranno essere non attendibili o a causa della presenza perturbatrice dello schermo all’interno del cavo in esame.

#### 4.11.1. Situazioni anomale

Qualora, all’atto della misura, la tensione presente al terminale fosse maggiore di 0.2V, lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco
*(Immagine/Icona non disponibile nel testo originale)*

> **ATTENZIONE**
> Prima di effettuare una qualunque verifica del cablaggio accertarsi che il circuito in esame non sia alimentato. Collegamenti a linee telefoniche o reti dati attive potrebbero danneggiare lo strumento.

#### 4.11.2. Nota esplicativa sulla condizione di errore split pairs

All’interno dei cavi di rete gli otto conduttori sono ritorti (twistati) due a due formando così quattro coppie: 1-2, 3-6, 4-5, 7-8, questo assicura le prestazioni dichiarate dal costruttore. La condizione di errore “SPLIT PAIRS” è data dallo scambio di due conduttori appartenenti a coppie diverse effettuato in entrambe le attestazioni del cavo in esame. La corrispondenza pin a pin è mantenuta, ma fisicamente i cavi delle due coppie sono incrociati. Le due coppie così incrociate si influenzano l’un l’altra rendendo difficoltoso, se non addirittura impossibile, lo scambio di dati ad alta frequenza/velocità

> **ATTENZIONE**
> La condizione di errore “SPLIT PAIRS” viene verificata solo dopo che sono state riscontrate come corrette tutte le altre condizioni. Per la corretta rilevazione di tale condizione d’errore è necessario che il cavo in esame sia lungo almeno 1m.

#### 4.11.3. Errori di cablaggio rilevati

**Tabella 3: Possibili errori di cablaggio rilevati**

| Errore di cablaggio       | Descrizione                                                                                             | Visualizzazione                                                                                                    | Schema (rappresentato nel testo originale come diagrammi pin-to-pin) |
| :------------------------ | :------------------------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------- |
| OPEN PAIR                 | COPPIA APERTA Uno od entrambi i cavi appartenenti alla coppia (ex: 1-2) sono interrotti                  | *(Visualizzazione non disponibile nel testo)*                                                                      | *(Schema non disponibile nel testo)*                                 |
| REVERSED PAIR             | COPPIA ROVESCIATA I cavi appartenenti alla stessa coppia (ex: 1-2) sono scambiati                       | *(Visualizzazione non disponibile nel testo)*                                                                      | *(Schema non disponibile nel testo)*                                 |
| SHORTED CABLES            | CAVI CORTOCIRCUITATI Due cavi (ex: 1-8) sono in cortocircuito tra di loro                               | *(Visualizzazione non disponibile nel testo)*                                                                      | *(Schema non disponibile nel testo)*                                 |
| TRANSPOSED (CROSSED) PAIRS | COPPIE SCAMBIATE Due coppie (ex: 1-2 e 7-8) sono scambiate                                             | *(Visualizzazione non disponibile nel testo)*                                                                      | *(Schema non disponibile nel testo)*                                 |
| MISWIRE                   | ERRORE DI CABLAGGIO Errore generico di cablaggio, come ad esempio due cavi appartenenti a coppie diverse sono scambiati | *(Visualizzazione non disponibile nel testo)*                                                                      | *(Schema non disponibile nel testo)*                                 |
| SPLIT PAIRS               | COPPIE INCROCIATE La corrispondenza pin a pin è mantenuta, ma fisicamente i cavi delle due coppie sono incrociati | *(Visualizzazione non disponibile nel testo)*                                                                      | *(Schema non disponibile nel testo)*                                 |

### 4.12. CONTINUITÀ DEI CONDUTTORI DI PROTEZIONE

La misura viene eseguita con corrente di prova maggiore di 200mA (per R<5 Ω) e tensione a vuoto compresa tra 4 e 24 V DC secondo le norme CEI 64.8 612.2 e IEC/EN61557-4

> **ATTENZIONE**
> Pur essendo lo strumento protetto dalle tensioni in ingresso, è buona norma accertarsi che non ci sia tensione ai capi del conduttore da analizzare prima di effettuare la prova di continuità.

**Fig. 9**: Connessione dei terminali dello strumento

1.  Accendere lo strumento con il tasto ON/OFF
2.  Usare i tasti freccia per selezionare la funzione  0.2A
3.  Inserire il cavo nero ed il cavo verde nei rispettivi terminali di ingresso dello strumento
4.  Qualora, ai fini della misura da effettuare, la lunghezza dei cavi in dotazione fosse insufficiente, prolungare il cavo nero
5.  Se necessario innestare i coccodrilli sui puntali di misura
6.  Qualora i cavi di misura in uso non siano stati calibrati in precedenza, effettuarne la calibrazione come descritto al § 4.12.1
7.  Collegare i terminali dello strumento ai capi del conduttore di cui si desidera effettuare la prova di continuità (vedere Fig. 9)
8.  Premere il tasto GO, lo strumento esegue la misurazione

> **ATTENZIONE**
> Quando sul display compare “Measuring” lo strumento sta eseguendo la misura. Durante questa fase non scollegare i puntali dello strumento. Collegare lo strumento solo PRIMA della misura e non cambiare il collegamento mentre è presente la scritta “Measuring”.

9.  La prova di continuità viene eseguita erogando una corrente superiore a 200mA nel caso in cui la resistenza sia inferiore a 5  (compresa la resistenza dei cavi di misura memorizzata come offset nello strumento dopo aver eseguito la procedura di calibrazione). Per valori di resistenza superiori lo strumento esegue la prova con una corrente decrescente
10. Al termine della prova, nel caso in cui sia stato possibile generare almeno 200mA (valore di resistenza non particolarmente elevato), lo strumento emette un doppio segnale acustico che segnala l'esito positivo della prova e visualizza una videata come quella a fianco
    *   Valore misurato della resistenza
    *   Valore della corrente di prova
    *(Immagine/Icona non disponibile nel testo originale)*
11. Al termine della prova, nel caso in cui non sia stato possibile generare 200mA a causa dell'elevato valore di resistenza, lo strumento emette un segnale acustico prolungato che segnala l'esito negativo della prova e visualizza una videata come quella a fianco
    *   Valore misurato della resistenza
    *   Valore della corrente di prova
    *(Immagine/Icona non disponibile nel testo originale)*

#### 4.12.1. Modalità "CAL"

**Fig. 10**: Connessione dei terminali durante la procedura di calibrazione

1.  Con il tasto MODE/PEAK selezionare la modalità CAL
2.  Lo strumento deve essere nelle medesime condizioni operative nelle quali sarà durante le fasi di misurazione. Pertanto ogni aggiunta o sostituzione di cavi, prolunghe e coccodrilli invalidano la calibrazione precedente ed implicano una nuova calibrazione prima di effettuare ulteriori misurazioni
3.  Cortocircuitare tra di loro le estremità dei cavi di misura (vedere Fig. 10) prestando attenzione che le parti metalliche dei puntali o dei coccodrilli facciano ben contatto tra di loro
4.  Premere il tasto GO, lo strumento esegue la calibrazione

> **ATTENZIONE**
> Quando sul display compare “Measuring” lo strumento sta eseguendo la misura. Durante questa fase non scollegare i puntali dello strumento.

5.  Possono essere calibrati cavi che presentino una resistenza fino a 5 
6.  Al termine della prova il valore misurato viene memorizzato dallo strumento e utilizzato come OFFSET (cioè viene sottratto da tutte le misure di continuità che si eseguono) per tutte le misure successive fino ad una nuova calibrazione. Lo strumento emette un doppio segnale acustico che segnala l'esito positivo della calibrazione e visualizza una videata simile a quella a fianco per 2 secondi, quindi visualizza la videata di default relativa alla prova  0.2A.
    *   Messaggio CAL: indica che lo strumento è stato calibrato; questo simbolo rimane visualizzato per ogni successiva misura anche se lo strumento viene spento e riacceso
    *   Corrente erogata dallo strumento durante la procedura di calibrazione
    *(Immagine/Icona non disponibile nel testo originale)*
7.  Qualora il valore misurato durante la fase di calibrazione sia superiore a 5  lo strumento interrompe la procedura di calibrazione, rimuove il valore dell’offset precedentemente adottato e non visualizza il simbolo CAL fino alla successiva calibrazione effettuata con successo. Lo strumento emette un segnale acustico prolungato che segnala l'esito negativo della calibrazione e visualizza una videata simile a quella a fianco per 2 secondi, quindi visualizza la videata di default relativa alla prova  0.2A.
    Nota: questo metodo è utilizzabile per annullare l’ultima calibrazione effettuata
    *(Immagine/Icona non disponibile nel testo originale)*

#### 4.12.2. Situazioni anomale

1.  Nel caso in cui si verifichi la condizione: R MISURATA - R CALIBRAZIONE < - 0.02  lo strumento visualizza la videata a fianco ed emette un segnale acustico prolungato a segnalare la situazione anomala
    *(Immagine/Icona non disponibile nel testo originale)*
2.  Se, all’atto della misura, la tensione presente ai terminali è > 10V, lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 s, trascorsi i quali lo strumento visualizza la videata di default relativa alla prova  0.2A
    *   Valore della tensione rilevata in ingresso
    *(Immagine/Icona non disponibile nel testo originale)*
3.  Qualora il valore misurato di resistenza sia superiore al fondo scala, lo strumento emette un segnale acustico prolungato a segnalare la situazione anomala e visualizza una videata simile a quella a fianco. La medesima segnalazione può significare anche che i cavi di misura siano scollegati od aperti
    *(Immagine/Icona non disponibile nel testo originale)*
4.  Il simbolo di attenzione con messaggio “OK” si verifica quando:
    *   Lo strumento sta operando in situazione critica, come ad esempio in presenza di sovratensioni
    *   Lo strumento non può garantire l’incertezza di misura inferiore al 30% della lettura, in accordo con la IEC/EN61557-1
    *(Immagine/Icona non disponibile nel testo originale)*

### 4.13. MISURA RESISTENZA DI ISOLAMENTO

La misura viene eseguita secondo le norme CEI 64.8 612.3 e IEC/EN61557-2

> **ATTENZIONE**
> *   Pur essendo lo strumento protetto dalle tensioni in ingresso, è buona norma accertarsi che non ci sia tensione ai capi del conduttore da analizzare prima di effettuare la prova di isolamento.
> *   La misura di isolamento richiede particolare perizia ed attenzione onde non fornire risultati errati a danno della sicurezza e per non arrecare danni a terzi.
> *   Durante tutta la prova accertarsi che la tensione applicata non sia accessibile a terzi e predisporre adeguatamente l’impianto scollegando ciò che non deve essere coinvolto nella prova.
> *   Una misura con un cavo erroneamente scollegato darebbe risultato buono pur in presenza di isolamento difettoso. Occorre evitare scrupolosamente questa circostanza. Una volta preparato l’impianto e connessi i cavi di misura, accertarsi del loro corretto collegamento. Nel dubbio, prima della misura di isolamento, effettuare una misura  0.2A cortocircuitando i cavi sotto test in un punto dell’impianto più lontano possibile dai morsetti di misura. Rimuovere il corto circuito prima di effettuare la misura.

**Fig. 11**: Connessione dei terminali dello strumento

1.  Accendere lo strumento con il tasto ON/OFF
2.  Premendo i tasti freccia selezionare la funzione M. Selezionare la tensione di prova con il tasto MODE/PEAK scegliendo tra i valori 250 o 500V DC. Impostare il valore di soglia limite minima sulla misura (vedere § 4.5) in funzione della normativa considerata (ex: CEI 64-8 prevede il valore di 1M con tensione di prova 500VDC)
3.  Inserire il cavo nero ed il cavo verde nei rispettivi terminali di ingresso dello strumento. Qualora, ai fini della misura da effettuare, la lunghezza dei cavi in dotazione fosse insufficiente, prolungare il cavo nero. L'eventuale prolunga deve essere adeguatamente isolata in quanto il suo isolamento è in parallelo alla resistenza da misurare. Essa deve essere sospesa e non appoggiata a terra ed i sostegni devono essere in materiale isolante
4.  Se necessario innestare i coccodrilli sui puntali di misura
5.  Scollegare dall’alimentazione il circuito o la parte di impianto in esame e tutti gli eventuali carichi derivati da esso
6.  Collegare i terminali dello strumento ai capi dei conduttori dei quali si desidera misurare l’isolamento reciproco (vedere Fig. 11)
7.  Premere il tasto GO, lo strumento esegue la misurazione

> **ATTENZIONE**
> Quando sul display compare “Measuring” lo strumento sta eseguendo la misura o scaricando le eventuali capacità parassite presenti tra i conduttori. Durante questa fase non scollegare e non toccare i puntali di misura

8.  Al termine della prova, prima di fornire il risultato della misura, lo strumento provvede in automatico a scaricare gli eventuali condensatori e capacità parassite presenti tra i conduttori coinvolti nella misura
9.  Al termine della prova, nel caso in cui il valore della resistenza rilevata risulti superiore alla soglia limite minima impostata (vedere § 4.5) lo strumento emette un doppio segnale acustico che segnala l'esito positivo della prova e visualizza una videata come quella a fianco
    *   Valore misurato della resistenza
    *   Valore della tensione di prova
    *(Immagine/Icona non disponibile nel testo originale)*
10. Al termine della prova, nel caso in cui il valore della resistenza rilevata risulti superiore a 999M, cioè al fondo scala, lo strumento emette un doppio segnale acustico che segnala l'esito positivo della prova e visualizza una videata come quella a fianco.
    Si noti come un valore di isolamento superiore a 999M sia un ottimo valore di isolamento, in genere molto maggiore dei requisiti minimi imposti dalle norme
    *   Valore misurato della resistenza
    *   Valore della tensione di prova
    *(Immagine/Icona non disponibile nel testo originale)*
11. Al termine della prova, nel caso in cui il valore della resistenza rilevata risulti inferiore alla soglia limite minima impostata (vedere § 4.5) lo strumento emette un segnale acustico prolungato che segnala l'esito negativo della prova e visualizza una videata come quella a fianco
    *   Valore misurato della resistenza
    *   Valore della tensione di prova
    *(Immagine/Icona non disponibile nel testo originale)*

#### 4.13.1. Situazioni anomale

Se, all’atto della misura, la tensione presente ai terminali è maggiore di 10V, lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 secondi, trascorsi i quali lo strumento visualizza la videata di default relativa alla prova M
*   Valore della tensione rilevata in ingresso.
*(Immagine/Icona non disponibile nel testo originale)*

### 4.14. TEST SU DIFFERENZIALI (RCD) DI TIPO AC E DI TIPO A

La prova viene eseguita secondo le norme CEI 64.8 612.9, CEI 64.8/6 appendice D, EN61008, EN61009, EN 60947-2 punto B 4.2.4.1 e IEC/EN61557-6.

> **ATTENZIONE**
> *   La verifica di un interruttore differenziale comporta l'intervento della protezione stessa. Verificare pertanto che a valle della protezione differenziale in esame NON siano allacciate utenze o carichi che possano risentire dalla messa fuori servizio dell'impianto
> *   Scollegare tutti i carichi allacciati a valle dell'interruttore differenziale in quanto potrebbero introdurre correnti di dispersione aggiuntive a quelle fatte circolare dallo strumento invalidando così i risultati della prova.

**Fig. 12**: Connessione dei terminali dello strumento

#### 4.14.1. Misura del tempo di intervento

1.  Accendere lo strumento con il tasto ON/OFF
2.  Usare i tasti freccia per selezionare la funzione RCD
3.  Con il tasto MODE/PEAK selezionare la corrente di prova tra i valori 30mA, 30mAx5, 100mA, 300mA che si presentano ciclicamente ad ogni pressione del tasto
4.  Con il tasto FUNC HOLD selezionare il tipo di differenziale tra le opzioni AC () o A () (solo 30mA)

> **ATTENZIONE**
> Prestare attenzione nell’impostazione della corrente di prova dell’interruttore differenziale accertandosi di selezionarne il valore corretto. Qualora si imposti una corrente superiore a quella nominale del dispositivo in esame, l’interruttore differenziale verrebbe testato ad una corrente maggiore di quella corretta favorendo un intervento più rapido dell’interruttore stesso.

In alternativa:
5.  Inserire il cavo nero ed il cavo verde nei rispettivi terminali di ingresso dello strumento. Se necessario innestare i coccodrilli sui puntali di misura
6.  Collegare il terminale verde dello strumento al conduttore di protezione (terra) ed il conduttore nero al cavo di fase a valle del differenziale da testare (vedere Fig. 12)
Oppure:
5.  Inserire il cavo shuko nei terminali di ingresso dello strumento
6.  Inserire il cavo shuko in una presa di corrente a valle del differenziale da testare
7.  Mantenere premuto il tasto GO per almeno un secondo per eseguire la misurazione con corrente di dispersione in fase con la semionda positiva della tensione di rete (0°), oppure mantenere premuto il tasto GO per almeno un secondo e, quando i trattini sul display iniziano a scomparire, premere nuovamente il tasto GO per eseguire la misurazione con corrente di dispersione in fase con la semionda negativa della tensione di rete (180°)

> **ATTENZIONE**
> Quando sul display compare “Measuring” lo strumento sta eseguendo la misura. Durante questa fase non scollegare i puntali dello strumento.

8.  Al termine della prova, nel caso in cui il valore del tempo di intervento rilevato risulti inferiore a 300ms (40ms per I∆n =30mA x5), lo strumento emette un doppio segnale acustico che segnala l'esito positivo della prova e visualizza una videata come quella a fianco
    *   Valore misurato del tempo di intervento
    *   Valore della corrente di prova
    *(Immagine/Icona non disponibile nel testo originale)*
9.  Al termine della prova, nel caso in cui il valore del tempo di intervento rilevato risulti superiore a 300ms (40ms per I∆n =30mA x5), oppure nel caso in cui l’interruttore differenziale non intervenga, lo strumento emette un segnale acustico prolungato che segnala l'esito negativo della prova e visualizza una videata come quella a fianco
    *   Tempo di intervento superiore al limite
    *   Valore della corrente di prova
    *(Immagine/Icona non disponibile nel testo originale)*

#### 4.14.2. Misura della corrente di intervento (solo 30mA)

1.  Accendere lo strumento con il tasto ON/OFF
2.  Usare i tasti freccia per selezionare la funzione RCD
3.  Con il tasto FUNC HOLD selezionare il tipo di differenziale tra le opzioni AC () o A () (solo 30mA) e la misura della corrente di intervento (simbolo “→” a display)
4.  La videata iniziale a fianco è mostrata a display
    *   Valore iniziale nullo della tensione Fase - Terra
    *   Valore della corrente di prova
    *(Immagine/Icona non disponibile nel testo originale)*

In alternativa:
5.  Inserire il cavo nero ed il cavo verde nei rispettivi terminali di ingresso dello strumento. Se necessario innestare i coccodrilli sui puntali di misura
6.  Collegare il terminale verde dello strumento al conduttore di protezione (terra) ed il conduttore nero al cavo di fase a valle del differenziale da testare (vedere Fig. 12)
Oppure:
5.  Inserire il cavo shuko nei terminali di ingresso dello strumento
6.  Inserire il cavo shuko in una presa di corrente a valle del differenziale da testare
7.  Mantenere premuto il tasto GO per almeno un secondo per eseguire la misurazione con corrente di dispersione in fase con la semionda positiva della tensione di rete (0°), oppure mantenere premuto il tasto GO per almeno un secondo e, quando i trattini sul display iniziano a scomparire, premere nuovamente il tasto GO per eseguire la misurazione con corrente di dispersione in fase con la semionda negativa della tensione di rete (180°). Esauriti tutti i trattini lo strumento inizia ad generare la corrente progressivamente crescente mantenendo sotto controllo il valore della tensione di contatto

> **ATTENZIONE**
> Quando sul display compare “Measuring” lo strumento sta eseguendo la misura. Durante questa fase non scollegare i puntali dello strumento.

8.  Al termine della prova, nel caso in cui il valore della corrente di intervento rilevato risulti inferiore a 30mA, lo strumento emette un doppio segnale acustico che segnala l'esito positivo della prova e visualizza una videata come quella a fianco
    *   Valore corretto della corrente di intervento
    *   Valore della corrente di prova
    *(Immagine/Icona non disponibile nel testo originale)*
9.  Al termine della prova, nel caso in cui il valore della corrente di intervento rilevato risulti superiore a 33mA, oppure nel caso in cui l’interruttore differenziale non intervenga, lo strumento emette un segnale acustico prolungato che segnala l'esito negativo della prova e visualizza una videata come quella a fianco
    *   Valore incorretto della corrente di intervento
    *   Valore della corrente di prova
    *(Immagine/Icona non disponibile nel testo originale)*
10. A prova terminata lo strumento visualizza alternativamente ogni 2s le videata con il valore della corrente di intervento e del tempo di intervento rilevato nella misura come mostrato nella videata a fianco
    *(Immagine/Icona non disponibile nel testo originale)*

#### 4.14.3. Situazioni anomale

1.  Qualora all’atto della misurazione sia rilevata una tensione in ingresso superiore a 265V (esempio: entrambi i cavi collegati a conduttori di fase di un impianto trifase 400V) lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 secondi trascorsi i quali lo strumento visualizza la videata di default relativa alla prova RCD
    *(Immagine/Icona non disponibile nel testo originale)*
2.  Qualora all’atto della misurazione sia rilevata una tensione in ingresso inferiore a 100V lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 secondi, trascorsi i quali lo strumento visualizza la videata di default relativa alla prova RCD
    Questa condizione può verificarsi, a titolo di esempio, qualora il cavo nero venga collegato erroneamente al conduttore di neutro anziché al conduttore di fase. Se si utilizza il cavo shuko ruotare la spina e ripetere la prova
    *(Immagine/Icona non disponibile nel testo originale)*
3.  Qualora all’atto della misurazione venga rilevato che il puntale verde è collegato al cavo di fase ed il puntale nero al conduttore di protezione, lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 secondi trascorsi i quali lo strumento visualizza la videata di default relativa alla prova RCD
    *(Immagine/Icona non disponibile nel testo originale)*
4.  Qualora all’atto della misurazione sia rilevata una tensione di contatto troppo elevata tale da superari il limite normativo di 50V, lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 secondi trascorsi i quali lo strumento visualizza la videata di default relativa alla prova RCD
    *(Immagine/Icona non disponibile nel testo originale)*
5.  Con corrente nominale 30mAx5, qualora all’atto della misurazione sia rilevata una resistenza di terra troppo elevata, tale da impedire allo strumento la generazione della corrente di prova, lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 secondi trascorsi i quali lo strumento visualizza la videata di default relativa alla prova RCD
    *(Immagine/Icona non disponibile nel testo originale)*

### 4.15. MISURA RESISTENZA GLOBALE DI TERRA

> **ATTENZIONE**
> *   Scollegare tutti i carichi allacciati a valle dell'interruttore differenziale in quanto potrebbero introdurre correnti di dispersione aggiuntive a quelle fatte circolare dallo strumento tali da invalidare i risultati della prova
> *   È possibile eseguire misure in sistemi fino a 265V fase - terra. Non utilizzare lo strumento in impianti con tensione nominale concatenata maggiore di 550V

**Fig. 13**: Connessione dei terminali dello strumento in prova

1.  Accendere lo strumento con il tasto ON/OFF
2.  Usare i tasti freccia per selezionare la funzione Ra
3.  Con il tasto MODE/PEAK selezionare la corrente di prova tra i valori 15mA e 100mA che si presentano ciclicamente ad ogni pressione del tasto

> **ATTENZIONE**
> Qualora nell'impianto fosse presente un interruttore differenziale, selezionare un valore della corrente di misura (15mA oppure 100mA) inferiore al valore di corrente nominale del dispositivo. In caso contrario, durante l'esecuzione della misura, l’interruttore differenziale potrebbe intervenire impedendo l'esecuzione della misura stessa.

4.  Selezionando la corrente di prova di 100mA viene fornito anche il valore della corrente di corto circuito fase terra presunta, calcolato secondo la formula ICC = PE N Z U dove:
    ZPE è il valore della resistenza globale di terra
    UN è la tensione fase – terra nominale il cui valore è:
    127V se 100V ≤ V misurata < 150V
    230V se 150V ≤ V misurata < 265V
In alternativa:
5.  Inserire il cavo nero ed il cavo verde nei rispettivi terminali di ingresso dello strumento. Se necessario innestare i coccodrilli sui puntali di misura
6.  Collegare il terminale verde dello strumento al conduttore di protezione (terra) ed il conduttore nero al cavo di fase
Oppure:
5.  Inserire il cavo shuko nei terminali di ingresso dello strumento
6.  Inserire il cavo shuko in una presa di corrente (vedere Fig. 13). Nella figura è rappresentato il collegamento alla presa
7.  Mantenere premuto il tasto GO per almeno un secondo, lo strumento esegue la misurazione

> **ATTENZIONE**
> Quando sul display compare “Measuring” lo strumento sta eseguendo la misura. Durante questa fase non scollegare i puntali dello strumento dal punto di misura.

8.  Al termine della prova, nel caso in cui il valore della resistenza di terra risulti inferiore a 1999 , lo strumento emette un doppio segnale acustico e visualizza una videata come quella a fianco dove sono riportati i valori della resistenza globale di terra misurata e della corrente con la quale è stata effettuata la misurazione
    *   Valore misurato della resistenza globale di terra
    *   Il simbolo "HOLD" rimane acceso fino a quando non è permesso effettuare una nuova misura
    *   Corrente utilizzata durante la misura
    *(Immagine/Icona non disponibile nel testo originale)*
9.  Qualora sia stata selezionata la corrente di prova 100mA ed il valore di resistenza di terra risulti inferiore a 1999 , premendo il tasto FUNC/HOLD sono visualizzati alternativamente i valori della resistenza globale di terra e della corrente di corto circuito presunta fase terra. Lo strumento inoltre visualizza la corrente con la quale è stata effettuata la misurazione
    *   Valore misurato della resistenza globale di terra
    *   Il simbolo "HOLD" rimane acceso fino a quando non è permesso effettuare una nuova misura
    *   Corrente utilizzata durante la misura
    *(Immagine/Icona non disponibile nel testo originale)*
10. Al termine della prova, nel caso in cui il valore della resistenza di terra risulti superiore a 1999 , lo strumento emette un doppio segnale acustico e visualizza una videata come quella a fianco
    *   Valore della resistenza globale di terra superiore al valore di fondo scala
    *   Il simbolo "HOLD" rimane acceso fino a quando non è permesso effettuare una nuova misura
    *(Immagine/Icona non disponibile nel testo originale)*

> **ATTENZIONE**
> Al fine di garantire la correttezza delle misure effettuate è necessario un certo intervallo di tempo tra una misura e la successiva. Durante questo periodo, sul display dello strumento, compare il simbolo “HOLD” è non è possibile effettuare nuove misure. Quando il simbolo “HOLD” scompare dal display, lo strumento è pronto per effettuare una nuova misura.

#### 4.15.1. Situazioni anomale

1.  Qualora all’atto della misurazione l’interruttore differenziale che protegge la linea intervenga, lo strumento interrompe la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 secondi trascorsi i quali lo strumento visualizza la videata di default relativa alla prova Ra
    *(Immagine/Icona non disponibile nel testo originale)*
2.  Qualora all’atto della misurazione sia rilevata una tensione in ingresso superiore a 265V (esempio: entrambi i cavi collegati a conduttori di fase di un impianto trifase 400V) lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 secondi trascorsi i quali lo strumento visualizza la videata di default relativa alla prova Ra
    *(Immagine/Icona non disponibile nel testo originale)*
3.  Qualora all’atto della misurazione sia rilevata una tensione in ingresso inferiore a 100V lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 secondi, trascorsi i quali lo strumento visualizza la videata di default relativa alla prova Ra
    Questa condizione può verificarsi, a titolo di esempio, qualora il cavo nero venga collegato erroneamente al conduttore di neutro anziché al conduttore di fase. Se si utilizza il cavo shuko ruotare la spina e ripetere la prova
    *(Immagine/Icona non disponibile nel testo originale)*
4.  Qualora all’atto della misurazione sia rilevata una tensione di contatto troppo elevata tale da superari il limite normativo di 50V, lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 secondi trascorsi i quali lo strumento visualizza la videata di default relativa alla prova Ra
    *(Immagine/Icona non disponibile nel testo originale)*
5.  Il simbolo di attenzione con risultato positivo si verifica quando:
    *   Lo strumento sta operando in situazione critica, come ad esempio in presenza di sovratensioni
    *   Lo strumento non può garantire l’incertezza di misura inferiore al 30% della lettura, in accordo con la IEC/EN61557-1
    *(Immagine/Icona non disponibile nel testo originale)*
6.  Qualora all’atto della misurazione venga rilevato che il puntale verde è collegato al cavo di fase ed il puntale nero al conduttore di protezione, lo strumento non effettua la prova. Viene emesso un segnale acustico prolungato a segnalare la situazione anomala e viene visualizzata la videata a fianco per 5 secondi trascorsi i quali lo strumento visualizza la videata di default relativa alla prova Ra. Questa condizione può verificarsi anche qualora l'errore di collegamento sia presente all'interno della presa di corrente
    *(Immagine/Icona non disponibile nel testo originale)*
7.  Qualora, in seguito a ripetute prove, lo strumento si surriscaldi è visualizzata una videata come quella a fianco. Attendere che tale messaggio scompaia prima di eseguire altre prove. Se il messaggio persiste contattare il servizio di assistenza
    *(Immagine/Icona non disponibile nel testo originale)*

### 4.16. CICLO AUTOMATICO DI MISURE (AUTO)

Questa funzione permette di effettuare la verifica di un impianto elettrico in modo completamente automatico non richiedendo alcun intervento da parte dell’operatore.

> **ATTENZIONE**
> *   La verifica di un interruttore differenziale comporta l'intervento della protezione stessa. Verificare pertanto che a valle della protezione differenziale in esame NON siano allacciate utenze o carichi che possano risentire dalla messa fuori servizio dell'impianto
> *   Scollegare tutti i carichi allacciati a valle dell'interruttore differenziale in quanto potrebbero introdurre correnti di dispersione aggiuntive a quelle fatte circolare dallo strumento invalidando così i risultati della prova.

**Fig. 14**: Connessione dei terminali dello strumento in prova AUTO

1.  Accendere lo strumento con il tasto ON/OFF
2.  Usare i tasti freccia per selezionare la funzione AUTO
3.  I tasti MODE PEAK e FUNC HOLD non sono attivi per l’impostazione dei parametri di questa funzione. Per il limite minimo della resistenza di isolamento e per la selezione della misura del tempo o della corrente di intervento lo strumento considera sempre le opzioni presenti nelle funzioni M (vedere § 4.13) e RCD (vedere § 4.14)

> **ATTENZIONE**
> Prestare attenzione nell’impostazione della corrente di prova dell’interruttore differenziale accertandosi di selezionarne il valore corretto. Qualora si imposti una corrente superiore a quella nominale del dispositivo in esame, l’interruttore differenziale verrebbe testato ad una corrente maggiore di quella corretta favorendo un intervento più rapido dell’interruttore stesso.

4.  Inserire il cavo nero ed il cavo verde nei rispettivi terminali di ingresso dello strumento. Se necessario innestare i coccodrilli sui puntali di misura oppure utilizzare il cavo shuko
5.  Collegare il terminale verde dello strumento al conduttore di protezione (terra) ed il conduttore nero al cavo di fase (vedere Fig. 14) o inserire la spina shuko nella presa
6.  Mantenere premuto il tasto GO per almeno un secondo, lo strumento esegue in sequenza e senza la necessità di intervento da parte dell’operatore le seguenti misurazioni: Ra (15mA), RCD (tempo o corrente di intervento), M (fra fase e terra)

> **ATTENZIONE**
> Quando sul display compare “Measuring” lo strumento sta eseguendo la misura. Durante questa fase non scollegare i puntali dello strumento.

7.  Durante l’esecuzione delle misurazioni, al termine di ogni prova, vengono visualizzate per 5 secondi le videate dei risultati parziali, quindi lo strumento passa all’esecuzione della misurazione successiva
8.  Al termine della prova Ra, nel caso in cui il valore della resistenza di terra risulti inferiore a 50V/I∆n lo strumento visualizza per 5 secondi una videata come quella a fianco, quindi passa all’esecuzione della misurazione successiva. Si veda il § 4.15 per maggiori dettagli o per informazioni riguardo l’eventuale esito negativo della prova o situazioni anomale
    *   Valore misurato della resistenza globale di terra
    *(Immagine/Icona non disponibile nel testo originale)*
9.  Al termine della prova, nel caso in cui sia stata selezionata la misura del tempo di intervento, il valore rilevato risulti inferiore al massimo valore ammissibile, lo strumento visualizza per 5 secondi una videata come quella a fianco, quindi passa alla videata successiva. Per maggiori dettagli, per informazioni riguardo l’eventuale esito negativo della prova o situazioni anomale, si veda il § 4.14
    *   Valore misurato del tempo di intervento
    *   Valore della corrente di prova
    *(Immagine/Icona non disponibile nel testo originale)*
10. Al termine della prova, nel caso in cui sia stata selezionata la misura della corrente di intervento, il valore rilevato risulti inferiore a 30mA, lo strumento visualizza per 5 secondi una videata come quella a fianco, quindi passa alla videata successiva. Per maggiori dettagli, per informazioni riguardo l’eventuale esito negativo della prova o situazioni anomale, si veda il § 4.14
    *   Valore misurato della corrente di intervento
    *   Valore della corrente di prova
    *(Immagine/Icona non disponibile nel testo originale)*
11. Al termine della prova M, nel caso in cui il valore della resistenza rilevata risulti superiore alla soglia limite minima impostata (vedere § 4.5) lo strumento visualizza per 5 secondi una videata come quella a fianco, quindi passa alla videata successiva. Per maggiori dettagli, per informazioni riguardo l’eventuale esito negativo della prova o situazioni anomale, si veda il § 4.13
    *   Valore misurato della resistenza
    *   Valore della tensione di prova
    *(Immagine/Icona non disponibile nel testo originale)*
12. Al termine della prova AUTO, nel caso in cui tutte le prove abbiano dato esito positivo, lo strumento emette un doppio segnale acustico a segnalare l'esito positivo e visualizza una videata come quella a fianco. Per visualizzare i risultati parziali premere il tasto FUNC HOLD, gli esiti delle singole prove si presentano ciclicamente ad ogni nuova pressione del medesimo tasto. Nella misura della corrente di intervento lo strumento visualizza alternativamente ogni 2s le videata con il valore della corrente di intervento e del tempo di intervento rilevato nella misura
    *(Immagine/Icona non disponibile nel testo originale)*
13. Durante la prova AUTO, nel caso in cui il test sulla resistenza globale di terra abbia dato esito negativo, lo strumento visualizza una videata come quella a fianco. Premere i tasti freccia per uscire dalla videata
    *(Immagine/Icona non disponibile nel testo originale)*
14. Durante la prova AUTO, nel caso in cui il test su RCD abbia dato esito negativo, lo strumento visualizza una videata come quella a fianco. Premere i tasti freccia per uscire dalla videata
    *(Immagine/Icona non disponibile nel testo originale)*
15. Durante la prova AUTO, nel caso in cui il test sulla misura di isolamento abbia dato esito negativo, lo strumento visualizza una videata come quella a fianco. Premere i tasti freccia per uscire dalla videata
    *(Immagine/Icona non disponibile nel testo originale)*

## 5. MANUTENZIONE

Durante l’utilizzo e l’immagazzinamento rispettare le raccomandazioni elencate in questo manuale per evitare possibili danni o pericoli durante l’utilizzo. Non utilizzare lo strumento in ambienti caratterizzati da elevato tasso di umidità o temperatura elevata. Non esporre direttamente alla luce del sole. Spegnere sempre lo strumento dopo l’utilizzo. Se si prevede di non utilizzarlo per un lungo periodo di tempo, rimuovere le batterie per evitare da parte di queste ultime fuoruscite di liquidi che possono danneggiare i circuiti interni dello strumento.

### 5.1. SOSTITUZIONE BATTERIE

Quando a display appare il simbolo di batteria scarica "" occorre sostituire le batterie.

> **ATTENZIONE**
> Solo tecnici qualificati possono effettuare questa operazione. Prima di effettuare questa operazione assicurarsi di aver rimosso tutti i cavi dai terminali di ingresso.

1.  Spegnere lo strumento premendo a lungo il tasto ON/OFF
2.  Rimuovere i cavi dai terminali di ingresso
3.  Rimuovere il coperchio vano batterie
4.  Rimuovere dal pacco batterie tutte le batterie, sostituirle solo con batterie tutte nuove e tutte dello stesso tipo (vedere § 6.2) rispettando le polarità indicate
5.  Riposizionare il pacco batterie avendo cura che la parte da cui escono i fili rosso e nero sia rivolta verso il fondo del vano batterie
6.  Qualora il pacco batterie fosse riposizionato non correttamente, la chiusura del vano batterie risulterebbe impossibile. Non forzare le parti plastiche, ma ruotare il pacco batterie nella posizione corretta
7.  Fissare nuovamente il coperchio vano batterie
8.  Non disperdere nell’ambiente le batterie utilizzate. Usare gli appositi contenitori per lo smaltimento

### 5.2. PULIZIA DELLO STRUMENTO

Per la pulizia dello strumento utilizzare un panno morbido e asciutto. Non usare mai panni umidi, solventi, acqua, ecc.

### 5.3. FINE VITA

Attenzione: il simbolo riportato indica che l'apparecchiatura ed i suoi accessori deve essere raccolta separatamente e trattata in modo corretto
*(Simbolo WEEE non disponibile nel testo)*

## 6. SPECIFICHE TECNICHE

Incertezza indicata come: ± [%lettura + (num. cifre * risoluzione)] a 23°C, <70%RH. Fare riferimento alla Tabella 1 per la corrispondenza fra modello e funzioni disponibili

**Tensione DC/ AC TRMS**

| Campo         | Risoluzione   | Incertezza DC          | Incertezza (30 ÷ 70Hz) | Incertezza (71 ÷ 400Hz) | Impedenza d’ingresso |
| :------------ | :------------ | :--------------------- | :--------------------- | :---------------------- | :------------------- |
| 1.0 ÷ 999.9mV | 0.1mV         | (0.5% lett. +2 cifre) | (1.0% lett. +2cifre)  | (2.0% lett. +2 cifre)  | 1M                  |
| 1.000 ÷ 9.999V | 0.001V        |                        |                        |                         |                      |
| 10.00 ÷ 99.99V | 0.01V         |                        |                        |                         |                      |
| 100.0 ÷ 605.0V | 0.1V          |                        |                        |                         |                      |

MAX, MIN, AVG, PEAK, precisione: (5.0% lettura + 10 cifre); tempo di risposta: 500ms (MAX, MIN, AVG),1ms (PEAK)
Massimo fattore di cresta: 3.0 per V< 1.0V; 1.5 per V ≥1.0V

**Corrente DC / AC TRMS (tramite trasduttore esterno)**

| Campo         | Risoluzione   | Incertezza DC        | Incertezza (30 ÷ 70Hz) | Incertezza (71 ÷ 400Hz) | Impedenza d’ingresso | Protezione contro i sovraccarichi |
| :------------ | :------------ | :------------------- | :--------------------- | :---------------------- | :------------------- | :-------------------------------- |
| 1.0 ÷ 999.9mV | 0.1mV         | (0.5% lettura+2cifre) | (1.0% lett. +2 cifre) | (2.0% lett. +2 cifre)  | 1M                  | 605V AC max RMS                   |
| 1.000 ÷ 1.200V | 0.001V        |                      |                        |                         |                      |                                   |

Nota: la precisione riportata non tiene conto della precisione del trasduttore, fare riferimento al relativo manuale d'uso
MAX, MIN, AVG, PEAK, precisione: (5.0% rdg + 10 dgt); tempo di risposta: 500ms (MAX, MIN, AVG),1ms (PEAK)
Minima corrente in ingresso rilevabile 1mV x costante di trasduzione della pinza
Massimo fattore di cresta: 3.0 per V< 1.0V; 1.5 per V ≥1.0V

**Frequenza tensione tramite puntali**

| Campo         | Risoluzione   | Incertezza             | Impedenza d’ingresso |
| :------------ | :------------ | :--------------------- | :------------------- |
| 30.0 ÷ 199.9Hz | 0.1Hz         | (0.5% lettura + 2 cifre) | 1M                  |
| 200 ÷ 400Hz   | 1Hz           |                        |                      |

Valore di tensione in ingresso: 1mV ÷ 605.0 V

**Frequenza corrente AC tramite trasduttore**

| Campo         | Risoluzione   | Incertezza             | Protezione contro i sovraccarichi |
| :------------ | :------------ | :--------------------- | :-------------------------------- |
| 30.0 ÷ 199.9Hz | 0.1Hz         | (0.5% lettura + 2 cifre) | 605V AC max RMS                   |
| 200 ÷ 400Hz   | 1Hz           |                        |                                   |

Valore di tensione in ingresso: 1mV ÷ 1 V

**Resistenza e Test continuità**

| Campo         | Risoluzione   | Incertezza             | Buzzer    | Protezione contro i sovraccarichi |
| :------------ | :------------ | :--------------------- | :-------- | :-------------------------------- |
| 0.00 ÷ 39.99  | 0.01         | (1%lettura + 5 cifre)  | R<40     | 605V AC max RMS per 1 minuto      |
| 40.0 ÷ 399.9  | 0.1          |                        |           |                                   |
| 400 ÷ 3999   | 1            |                        |           |                                   |
| 4.00 ÷ 39.99k | 10           |                        |           |                                   |

**Test del senso ciclico delle fasi e della concordanza di fase**

| Tipo misura        | Tensione d'esercizio (V) | Tipo di sistema                                                 |
| :----------------- | :----------------------- | :-------------------------------------------------------------- |
| 1 terminale (1W)   | 90 ÷ 315 (Fase - Terra)  | fino a 315 V (Fase – Terra) fino a 550V (Fase – Fase)           |
| 2 terminali (2W)   | 110 ÷ 315 (Fase - Neutro) | fino a 315 V (Fase – Neutro) fino a 550V (Fase – Fase) ( * )    |

Massimo fattore di cresta 1.5; Campo di frequenza 45 ÷ 65Hz
(*) Misura a 2 fili è eseguibile anche Fase – Fase in impianti senza neutro, anche se con una fase a Terra, ma sempre con tensione Fase - Fase fino a 550V

** 0.2A: Continuità con 200mA**

| Campo        | Risoluzione   | Incertezza            | Protezione contro i sovraccarichi |
| :----------- | :------------ | :-------------------- | :-------------------------------- |
| 0.00 ÷ 19.99  | 0.01         | (5.0% lettura + 3 cifre) | 605V max RMS                      |
| 20.0 ÷ 99.9   | 0.1           |                       |                                   |

Corrente di Prova: >200mA DC fino a 5  (resistenza dei cavi di misura compresa); Risoluzione misura corrente: 1mA
Tensione a Vuoto: 4 < V0 < 24V

**M: Resistenza di isolamento 250, 500VDC**

| Campo         | Risoluzione   | Incertezza             | Protezione contro i sovraccarichi |
| :------------ | :------------ | :--------------------- | :-------------------------------- |
| 0.00 ÷ 19.99M | 0.01M        | (5.0% lettura + 2 cifre) | 605V max RMS                      |
| 20.0 ÷ 199.9M | 0.1M         | (5.0%lettura + 2 cifre) |                                   |
| 200 ÷ 999M (*) | 1M           | (10.0%lettura + 2 cifre) |                                   |

(*) Per tensione di prova 500VDC. Per tensione di prova 250V il campo è: 200 ÷ 499M
Selezione automatica dei campi di misura per la resistenza
Tensione a vuoto: <1.3 x V0
Precisione tensione di prova nominale: – 0% +10%
Corrente di corto Circuito: <3.0mA
Corrente di misura nominale: 1mA @ 1K x V (1mA @ 500K)

**RCD: Tempo di intervento dei differenziali AC e A**

| Campo        | Risoluzione   | Incertezza            | Protezione contro i sovraccarichi |
| :----------- | :------------ | :-------------------- | :-------------------------------- |
| 2 ÷ 300ms    | 1ms           | (2.0% lettura + 2 cifre) | 605V max RMS                      |

Tipo differenziale: AC (), A (),Generali (G)
Tensione Fase – Terra / Fase – Neutro: 100 ÷ 265V
Correnti di prova: 30mA, 30mA x 5, 100mA, 300mA (Tipo AC), 30mA (Tipo A)
Frequenza: 50Hz  0.5Hz / 60Hz  0.5Hz

**RCD: Corrente di intervento dei differenziali**

| Tipo RCD         | IN   | Campo IN [mA] | Risoluzione   | Incertezza      |
| :--------------- | :---- | :------------- | :------------ | :-------------- |
| AC, A (Generali) | 30mA  | 6.0 ÷ 33.0     | 0.5mA         | - 0%, +10%IN   |

Tensione Fase – Terra / Fase – Neutro: 100 ÷ 265V
Frequenza: 50Hz  0.5Hz / 60Hz  0.5Hz

**Ra: Misura della resistenza globale di terra**

| Corrente di prova | Campo         | Risoluzione   | Incertezza            | Protezione contro i sovraccarichi |
| :---------------- | :------------ | :------------ | :-------------------- | :-------------------------------- |
| 15mA              | 1 ÷ 1999     | 1            | (5% lettura + 2 cifre) | 605V max RMS                      |
| 100mA             | 0.1 ÷ 199.9  | 0.1          | (5% lettura + 3 cifre) |                                   |

Tensione fase – terra: 100 ÷ 265V; Frequenza: 50Hz  0.5Hz / 60Hz  0.5Hz
Tensione nominale utilizzata per il calcolo della corrente di corto circuito presunta:
127V se 100V ≤ V misurata < 150V
230V se 150V ≤ V misurata < 265V

**Wire mapping**

| Campo                                 | Valore                           |
| :------------------------------------ | :------------------------------- |
| Lunghezza del cavo                    | 1 ÷ 100m                         |
| Numero di unità remote              | max 8 unità                      |
| Errori riscontrati                  | OPEN Pairs, REVERSED pairs, SHORT pairs, SPLIT pairs, CROSSED pairs, MISWIRING |
| In accordo con la norma             | TIA 568B                         |

### 6.1. NORMATIVE DI RIFERIMENTO

*   **Sicurezza**: IEC/EN61010-1, IEC/EN61557-1-2-3-4-6-7
*   **EMC**: IEC/EN61326-1
*   **Isolamento**: doppio isolamento
*   **Livello di inquinamento**: 2
*   **Categoria di misura**: CAT III 550V (fase – terra e fase – fase)
*   **Max altitudine di utilizzo**: 2000m
*   **LAN test**: TIA568B

### 6.2. CARATTERISTICHE GENERALI

**Caratteristiche elettriche**

| Caratteristica          | Descrizione                                   |
| :---------------------- | :-------------------------------------------- |
| Conversione             | ADC 16 bit, TRMS – Vero valore efficace       |
| Frequenza di campionamento | 64 campioni a periodo                         |
| Frequenza di aggiornamento display | 2 volte al secondo                          |

**Caratteristiche meccaniche**

| Caratteristica          | Valore                        |
| :---------------------- | :---------------------------- |
| Dimensioni (L x La x H) | 240 x 100 x 45mm              |
| Peso (batterie incluse) | 630g                          |
| Protezione meccanica    | IPXX                          |

**Alimentazione**

| Caratteristica          | Descrizione                                                                 |
| :---------------------- | :-------------------------------------------------------------------------- |
| Tipo batteria           | 4x 1.5V batterie alcaline tipo AA LR6 MN1500                                |
| Indicazione batteria scarica | simbolo " " a display                                                      |
| Durata batterie         | Multimetro: Circa 90 ore                                                    |
|                         | : > 1000 prove                                                              |
|                         | LAN: > 1000 prove                                                           |
|                         |  0.2A: > 1000 prove @ 1                                                   |
|                         | M: > 1000 prove @ 480k (500VCC)                                           |
|                         | RCD: > 1000 prove                                                           |
|                         | Ra: > 1000 prove                                                            |
|                         | AUTO: > 1000 prove                                                          |
| Auto Power OFF          | dopo 10 minuti di inattività (disabilitabile)                               |

**Display**

| Caratteristica | Descrizione                                                             |
| :------------- | :---------------------------------------------------------------------- |
| Caratteristiche | Doppio LCD 4 cifre entrambi con lettura massima 9999 punti più segno e punto decimale |

### 6.3. CONDIZIONI AMBIENTALI DI UTILIZZO

*   **Temperatura di riferimento**: 23°C ± 5°C
*   **Temperatura di utilizzo**: 0 °C ÷ 40°C
*   **Umidità relativa ammessa**: <70% RH
*   **Temperatura di conservazione**: -10 °C ÷ 60°C
*   **Umidità di conservazione**: <70% RH

Questo strumento è conforme ai requisiti della direttiva europea sulla bassa tensione 2014/35/EU (LVD) e della direttiva 2014/30/EU (EMC)
Questo strumento è conforme ai requisiti della direttiva europea 2011/65/CE (RoHS) e della direttiva europea 2012/19/CE (WEEE)

### 6.4. ACCESSORI

Vedi packing list allegata.

## 7. ASSISTENZA

### 7.1. CONDIZIONI DI GARANZIA

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

### 7.2. ASSISTENZA

Se lo strumento non funziona correttamente, prima di contattare il Servizio di Assistenza, controllare lo stato della batteria e dei cavi e sostituirli se necessario. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballaggio originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente.

**WHERE WE ARE**

HT ITALIA SRL
Via della Boaria, 40
48018 – Faenza (RA) – Italy
T +39 0546 621002 | F +39 0546 621144
M info@ht-instruments.com | www.ht-instruments.it

HT INSTRUMENTS SL
C/ Legalitat, 89
08024 Barcelona – Spain
T +34 93 408 17 77 | F +34 93 408 36 30
M info@htinstruments.es | www.ht-instruments.com/es-es/

HT INSTRUMENTS GmbH
Am Waldfriedhof 1b
D-41352 Korschenbroich – Germany
T +49 (0) 2161 564 581 | F +49 (0) 2161 564 583
M info@htinstruments.de | www.ht-instruments.de