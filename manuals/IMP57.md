# IMP57

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-20 -->
# Indice:
1.  PRECAUZIONE E MISURE DI SICUREZZA
    1.1. Istruzioni preliminari
    1.2. Durante l’utilizzo
    1.3. Dopo l’utilizzo
    1.4. Definizione di Categoria di misura (Sovratensione)
2.  DESCRIZIONE GENERALE
3.  PREPARAZIONE ALL’UTILIZZO
    3.1. Controlli iniziali
    3.2. Alimentazione dello strumento
    3.3. Taratura
    3.4. Immagazzinamento
4.  DESCRIZIONE DELLO STRUMENTO
    4.1. Descrizione dello Strumento
        4.1.1. LED STATUS
    4.2. Comandi dello strumento
5.  ISTRUZIONI OPERATIVE PER IMP57
    5.1. Misura dell'impedenza Fase-Fase e calcolo corrente di Corto Circuito presunta Fase-Fase e Trifase
    5.2. Misura dell'impedenza Fase-Neutro e calcolo della corrente di corto circuito presunta Fase-Neutro
    5.3. Misura dell'impedenza Fase-Pe e calcolo della corrente di corto circuito Presunta Fase-Pe
6.  ISTRUZIONI OPERATIVE PER STRUMENTO MASTER
    6.1. Istruzioni per Strumenti di TIPO 1
        6.1.1. Impostazione Strumento
        6.1.2. Calcolo delle Correnti di Corto Circuito
        6.1.3. Avvio della Prova
        6.1.4. Analisi risultati
        6.1.5. Situazioni anomale modalità "P-P", "P-N", "P-PE"
    6.2. Istruzioni per Strumenti di TIPO 2
        6.2.1. Impostazione Strumento
        6.2.2. Calcolo della Corrente di Corto Circuito
        6.2.3. Avvio della Prova
        6.2.4. Analisi Risultati
        6.2.5. Situazioni anomale modalità "P-P", "P-N", "P-PE"
    6.3. Istruzioni per Strumenti di TIPO 3
        6.3.1. Impostazione Strumento
        6.3.2. Calcolo delle Correnti di Corto Circuito
        6.3.3. Avvio della Prova
        6.3.4. Analisi risultati
        6.3.5. Situazioni anomale modalità "P-P", "P-N", "P-PE"
    6.4. Istruzioni per Strumenti di TIPO 4
        6.4.1. Impostazione Strumento
        6.4.2. Calcolo della Corrente di Corto Circuito
        6.4.3. Avvio della Prova
        6.4.4. Analisi risultati
        6.4.5. Situazioni anomale
    6.5. Istruzioni per Strumenti di TIPO 5
        6.5.1. Impostazione Strumento
        6.5.2. Calcolo della Corrente di Corto Circuito
        6.5.3. Avvio della Prova
        6.5.4. Analisi risultati
        6.5.5. Situazioni anomale
7.  TRASFERIMENTO DATI AD UN PC
8.  MANUTENZIONE
    8.1. Generalità
    8.2. Pulizia dello strumento
    8.3. Fine vita
9.  SPECIFICHE TECNICHE
    9.1. Caratteristiche Tecniche
        9.1.1. Norme di Sicurezza
        9.1.2. Normative
        9.1.3. Caratteristiche Generali
    9.2. Ambiente
        9.2.1. Condizioni Ambientali
    9.3. Accessori
10. ASSISTENZA
    10.1. Condizioni di Garanzia
    10.2. Assistenza

# 1 PRECAUZIONE E MISURE DI SICUREZZA
Lo strumento è stato progettato in conformità alle Normative IEC/EN61557 e IEC/EN61010 relative agli strumenti di misura elettronici. Per la Sua sicurezza e per evitare di danneggiare lo strumento, La preghiamo di seguire le procedure descritte nel presente manuale e di leggere con particolare attenzione tutte le note precedute dal simbolo.

> **ATTENZIONE**
> Qualora lo strumento fosse utilizzato in modo diverso da quanto specificato nel presente manuale d’uso, le protezioni per esso previste potrebbero essere compromesse. Prima e durante l’esecuzione delle misure attenersi scrupolosamente alle seguenti indicazioni:

*   Non effettuare misure in ambienti umidi.
*   Non effettuare misure in presenza di gas o materiali esplosivi, combustibili o in ambienti polverosi.
*   Evitare contatti con il circuito in esame se non si stanno effettuando misure.
*   Evitare contatti con parti metalliche esposte, con terminali di misura inutilizzati, circuiti, ecc.
*   Non effettuare alcuna misura qualora si riscontrino anomalie nello strumento come, deformazioni, rotture, fuoriuscite di sostanze, ecc.
*   Prestare particolare attenzione quando si effettuano misure di tensioni superiori a 20V in quanto è presente il rischio di shock elettrici.

Nel presente manuale sono utilizzati i seguenti simboli:
*   Attenzione: attenersi alle istruzioni riportate nel manuale; un uso improprio potrebbe causare danni allo strumento o ai suoi componenti.
*   Strumento con doppio isolamento.
*   Tensione o Corrente Alternata.

## 1.1 ISTRUZIONI PRELIMINARI
*   Questo strumento è stato progettato per un utilizzo in un ambiente con livello di inquinamento 2.
*   Può essere utilizzato per misure di Impedenza su impianti elettrici con categoria di sovratensione III fino a 240V nominali (Tensione verso Terra) e fino a 415V nominali (Tensione concatenata).
*   La invitiamo a seguire le normali regole di sicurezza orientate a:
    *   ProteggerLa contro tensioni e correnti pericolose.
    *   Proteggere lo strumento contro un utilizzo errato.
*   Solo gli accessori forniti a corredo dello strumento garantiscono gli standard di sicurezza. Essi devono essere in buone condizioni e sostituiti, se necessario, con modelli identici.
*   Non effettuare misure su circuiti che superano i limiti di tensione specificati.
*   Non effettuare misure in condizione ambientali al di fuori delle limitazioni indicate nel paragrafo 9.2.

## 1.2 DURANTE L’UTILIZZO
La preghiamo di leggere attentamente le raccomandazioni e le istruzioni seguenti:

> **ATTENZIONE**
> La mancata osservazione delle Avvertenze e/o Istruzioni può danneggiare lo strumento e/o i suoi componenti o essere fonte di pericolo per l’operatore.

*   Quando lo strumento è connesso al circuito in esame non toccare mai un qualunque terminale inutilizzato.
*   L'accensione in rosso lampeggiante del LED Status indica che lo strumento si è surriscaldato. Occorrerà attendere che il LED Status torni in verde per poter eseguire nuove prove.
*   Non eseguire mai più di 50 prove in un'ora.
*   L'accensione in rosso fisso del LED status indica una situazione potenzialmente pericolosa. Disconnettere immediatamente i coccodrilli dal circuito in esame.

## 1.3 DOPO L’UTILIZZO
*   Disconnettere sempre prima i coccodrilli dal circuito in esame e poi disinserire i terminali dei cavi stessi dagli ingressi dello strumento.

## 1.4 DEFINIZIONE DI CATEGORIA DI MISURA (SOVRATENSIONE)
La norma CEI 61010: Prescrizioni di sicurezza per apparecchi elettrici di misura, controllo e per utilizzo in laboratorio, Parte 1: Prescrizioni generali, definisce cosa si intenda per categoria di misura, comunemente chiamata categoria di sovratensione. Al paragrafo 6.7.4 - Circuiti di misura, la suddetta Norma definisce le Categorie di misura come segue: (OMISSIS)

*   **La categoria di misura IV** serve per le misure effettuate su una sorgente di un’installazione a bassa tensione.
    Esempi sono costituiti da contatori elettrici e da misure sui dispositivi primari di protezione dalle sovracorrenti e sulle unità di regolazione dell’ondulazione.
*   **La categoria di misura III** serve per le misure effettuate in installazioni all’interno di edifici.
    Esempi sono costituiti da misure su pannelli di distribuzione, disgiuntori, cablaggi, compresi i cavi, le barre, le scatole di giunzione, gli interruttori, le prese di installazioni fisse e gli apparecchi destinati all’impiego industriale e altre apparecchiature, per esempio i motori fissi con collegamento ad impianto fisso.
*   **La categoria di misura II** serve per le misure effettuate su circuiti collegati direttamente all’installazione a bassa tensione.
    Esempi sono costituiti da misure su apparecchiature per uso domestico, utensili portatili ed apparecchi similari.
*   **La categoria di misura I** serve per le misure effettuate su circuiti non collegati direttamente alla RETE DI DISTRIBUZIONE.
    Esempi sono costituiti da misure su non derivati dalla RETE e derivati dalla RETE ma con protezione particolare (interna). In quest’ultimo caso le sollecitazioni da transitori sono variabili, per questo motivo (OMISSIS) si richiede che l’utente conosca la capacità di tenuta ai transitori dell’apparecchiatura.

# 2 DESCRIZIONE GENERALE
Gentile Cliente, La ringraziamo per aver scelto uno strumento del nostro programma di vendita. Lo strumento da Lei appena acquistato, se utilizzato secondo quanto descritto nel presente manuale, Le garantirà misure accurate ed affidabili. Lo strumento è realizzato in modo da garantirLe la massima sicurezza grazie ad uno sviluppo di nuova concezione che assicura il doppio isolamento e il raggiungimento della categoria di sovratensione III 240V (verso Terra). Lo strumento può effettuare la Misura della Impedenza di Linea **Fase-Fase**, **Fase-Neutro** e dell'Anello di guasto ad elevata risoluzione con calcolo della corrente di Corto Circuito presunta (in accordo con quanto previsto dalla CEI 64-8/6, CEI EN 60909-0). Poiché la misura viene effettuata con il metodo Volt-Amperometrico a 4 fili, la rilevazione non è influenzata dal valore della resistenza dei cavi di misura e pertanto non è necessario effettuare nessuna calibrazione preventiva dei cavi utilizzati per la misura. I Terminali dei cavi forniti in dotazione con lo strumento sono coccodrilli speciali introdotti per semplificare al massimo le operazioni preliminari alla misura. Infatti tali coccodrilli presentano al loro interno due contatti distinti: la parte rossa realizza il contatto per il circuito amperometrico (C1 o C2) mentre la parte nera costituisce il contatto per il circuito di misura voltmetrico (P1 o P2). Lo strumento è direttamente alimentato dai cavi di misura e non dispone di Tastiera in quanto tutti comandi sono inviati allo strumento tramite l'interfaccia seriale dallo strumento denominato MASTER. Per ulteriori dettagli si veda il paragrafo 4.2.

# 3 PREPARAZIONE ALL’UTILIZZO
## 3.1 CONTROLLI INIZIALI
Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili affinché lo strumento potesse essere consegnato senza danni. Tuttavia si consiglia, comunque, di controllare sommariamente lo strumento per accertare eventuali danni subiti durante il trasporto. Se si dovessero riscontrare anomalie contattare immediatamente la società HT Italia. Si consiglia inoltre di controllare che l’imballaggio contenga tutte le parti indicate al paragrafo 9.3. In caso di discrepanze contattare il rivenditore. Qualora fosse necessario restituire lo strumento, si prega di seguire le istruzioni riportate al paragrafo 10.

## 3.2 ALIMENTAZIONE DELLO STRUMENTO
Lo strumento si alimenta direttamente dalla rete in cui si intende effettuare la misura tramite i terminali P1 e P2. La tensione deve essere nel range 220 – 415V nominali, la frequenza di rete 50Hz +/- 5%.

## 3.3 TARATURA
Lo strumento rispecchia le caratteristiche tecniche riportate nel presente manuale. Le prestazioni dello strumento sono garantite per due anni dalla data di acquisto dello strumento.

## 3.4 IMMAGAZZINAMENTO
Per garantire misure precise, dopo un lungo periodo di immagazzinamento in condizioni ambientali estreme, attendere che lo strumento ritorni alle condizioni normali (vedi le specifiche ambientali elencate al paragrafo 9.2).

# 4 DESCRIZIONE DELLO STRUMENTO
## 4.1 DESCRIZIONE DELLO STRUMENTO

```
P1   C1   C2   P2 CAT III
Input max: 415V~ between Inputs
240V~ P-P connection   P-PE connection P-N connection
High resolution Line/Loop Impedance tester
Un:   220-415V~ Freq: 50Hz
I   :   200A test Max Reading ~
Z:   4.0mΩ  - 1999mΩ
Z:   0.1mΩ  - 1999mΩ
Ik   :   1A - 1999kA
P .Supply   : 220-415V~ Freq supply: 50Hz
Power:   Max 10VA
W   W W   W  Reading (P1-P2 ) ±6 % ±6 %
```
```
P1   C1   C2   P2   P1   C1   C2   P2   P1   C1   C2   P2
1    2    3    N    PE   1    2    3    N    PE   1    2    3
```

**LEGENDA:**
1.  Terminali C1, P1, C2, P2 per le Prove di Misura di Impedenza.
2.  LED STATUS.
3.  Connettore Interfaccia Seriale RS232.

*Fig. 1: Descrizione dello strumento*

### 4.1.1 LED STATUS
Il led multicolore STATUS assume una colorazione corrispondente ad uno dei seguenti stati:

*   **Spento:** Strumento non alimentato (assenza di Tensione fra i terminali P1 e P2).
*   **Verde:** Strumento Alimentato e pronto per eseguire la prova.
*   **Arancio:** Prova in corso.
*   **Rosso lampeggiante:** Strumento surriscaldato. Occorrerà attendere che il LED Status torni in verde per poter eseguire nuove prove.
*   **Rosso fisso:** Disconnettere lo strumento dalla rete in esame. Verificare che la Tensione Nominale fra i punti di Prova sia nel range 220 – 415V e la frequenza nel range 47.5 – 52.5Hz. Controllare anche le situazioni anomale descritte nei paragrafi 6.1.5, 6.2.5, 6.3.5, 6.4.5 e 6.5.5.

## 4.2 COMANDI DELLO STRUMENTO

```
1     2
```
**LEGENDA:**
1.  Strumento MASTER.
2.  Cavo seriale: C2001 o C232NG1.

*Fig. 2: Connessione dell'IMP57 allo strumento MASTER*

Tutti comandi sono inviati allo strumento tramite l'interfaccia seriale. L'IMP57 può essere controllato solo dai seguenti strumenti MASTER:

| Strumento MASTER          | Tipo Strumento | Firmware     | Aggiornamento           |
| :------------------------ | :------------- | :----------- | :---------------------- |
| GSC57, GSC53, GENIUS5080E, GSC59, SIRIUS89, SIRIUS89N, ZG47 | 1              | 1.37 o superiore | Eseguibile dall'utente (*)|
| MACROTEST 5035, SIRIUS 87 | 2              | 1.16 o superiore | Eseguibile dall'utente (*)|
| COMBITEST 2019            |                | 1.33 o superiore | Inviare lo strumento ad HT |
| COMBI420, COMBI419, SPEED418, SOLAR200 | 3              | 1.02 o superiore | Contattare HT Italia    |
| FULLTEST4058              | 4              | 2.00 o superiore | Inviare lo strumento ad HT |
| FULLTEST4050              | 5              | A3.0 o superiore | Inviare lo strumento ad HT |

*Tabella 1: caratteristiche degli strumenti MASTER*

(*)Nel caso in cui la versione del Firmware dello strumento MASTER sia antecedente alla versione indicata, eseguire la procedura di aggiornamento descritta nel file " `Readme_Leggimi.pdf` " incluso nel CD-ROM fornito in dotazione con IMP57. Si raccomanda all'utilizzatore di verificare che la Versione del Programma (Firmware) presente sullo strumento MASTER a cui si desidera interconnettere l'IMP57 sia coerente con quanto indicato nella precedente Tabella 1. Tale informazione è presente nella videata iniziale visualizzata all'atto dell'accensione dello strumento MASTER. I risultati delle misure eseguite dall'IMP57 sono inviati allo strumento MASTER a cui esso è connesso e visualizzati sul display di quest'ultimo. Tutte le prove archiviate nella memoria dello strumento MASTER sono richiamabili a display e trasferibili ad un Personal Computer.

# 5 ISTRUZIONI OPERATIVE PER IMP57
## 5.1 MISURA DELL'IMPEDENZA FASE-FASE E CALCOLO CORRENTE DI CORTO CIRCUITO PRESUNTA FASE-FASE E TRIFASE

> **ATTENZIONE**
> *   Non utilizzare lo strumento in impianti con Tensione Fase-Fase superiore a 415V nominali o con Tensione Fase-Neutro Fase-Terra superiore a 240V nominali.
> *   La misura dell'impedenza Fase - Fase comporta la circolazione di una corrente massima di circa 200A fra i suddetti conduttori che può causare l'intervento di protezioni magnetotermiche presenti a monte del punto di misura. Nel caso eseguire la misura a monte della protezione stessa.
> *   Se possibile scollegare tutti i carichi a bassa impedenza allacciati a valle del punto in cui si intende effettuare la prova in quanto l'impedenza dei suddetti carichi risulta in parallelo alla impedenza di linea che si intende misurare.
> *   Accertarsi sempre che la lamina superiore e quella inferiore dei coccodrilli siano in buon contatto con i conduttori del circuito in esame.
> *   Non scollegare i terminali dello strumento durante l'esecuzione della prova.

```
P1   C1   C2   P2
1    2    3    N    PE
```
*Fig. 3: Collegamento strumento per Misura dell'impedenza Fase-Fase*

1.  Connettere l'interfaccia seriale dell'IMP57 allo strumento MASTER tramite il Cavo seriale apposito (vedere paragrafo 4.2).
2.  Collegare i coccodrilli alla rete elettrica in esame (vedere Fig. 3).
3.  Inserire le coppie di cavi nero-rosso dei cavi C7000 nei rispettivi terminali di ingresso dello strumento **seguendo la sequenza di inserimento P1, P2, C2, C1** (vedere connessione in Fig. 3).
4.  Verificare che il LED STATUS sia acceso e di colore Verde.
5.  Accendere lo strumento MASTER, selezionare su quest'ultimo la funzione "Misura di Impedenza ad alta Risoluzione Fase – Fase" ed avviare la prova (vedere capitolo 6). Per la descrizione dei valori, dei simboli visualizzati, la memorizzazione dei risultati e l'invio dei dati ad un PC, si rimanda al capitolo 6.

## 5.2 MISURA DELL'IMPEDENZA FASE-NEUTRO E CALCOLO DELLA CORRENTE DI CORTO CIRCUITO PRESUNTA FASE-NEUTRO

> **ATTENZIONE**
> *   Non utilizzare lo strumento in impianti con Tensione Fase-Fase superiore a 415V nominali o con Tensione Fase-Neutro Fase-Terra superiore a 240V nominali.
> *   La misura dell'impedenza Fase - Neutro comporta la circolazione di una corrente massima di circa 116A fra i suddetti conduttori che può causare l'intervento di protezioni magnetotermiche presenti a monte del punto di misura. Nel caso eseguire la misura a monte della protezione stessa.
> *   Se possibile scollegare tutti i carichi a bassa impedenza allacciati a valle del punto in cui si intende effettuare la prova in quanto l'impedenza dei suddetti carichi risulta in parallelo alla impedenza di linea che si intende misurare.
> *   Accertarsi sempre che la lamina superiore e quella inferiore dei coccodrilli siano in buon contatto con i conduttori del circuito in esame.
> *   Non scollegare i terminali dello strumento durante l'esecuzione della prova.

```
P1   C1   C2   P2
1    2    3    N    PE
```
*Fig. 4: Collegamento strumento per Misura dell'impedenza Fase-Neutro*

1.  Connettere l'interfaccia seriale dell'IMP57 allo strumento MASTER tramite il Cavo seriale apposito (vedere paragrafo 4.2).
2.  Collegare i coccodrilli alla rete elettrica in esame (vedere Fig. 4).
3.  Inserire le coppie di cavi nero-rosso dei cavi C7000 nei rispettivi terminali di ingresso dello strumento **seguendo la sequenza di inserimento P1, P2, C2, C1** (vedere connessione in Fig. 4).
4.  Verificare che il LED STATUS sia acceso e di colore Verde.
5.  Accendere lo strumento MASTER, selezionare su quest'ultimo la funzione "Misura di Impedenza ad alta Risoluzione Fase – Neutro" ed avviare la prova (vedere capitolo 6). Per la descrizione dei valori, dei simboli visualizzati, la memorizzazione dei risultati e l'invio dei dati ad un PC, si rimanda al capitolo 6.

## 5.3 MISURA DELL'IMPEDENZA FASE-PE E CALCOLO DELLA CORRENTE DI CORTO CIRCUITO PRESUNTA FASE-PE

> **ATTENZIONE**
> *   Non utilizzare lo strumento in impianti con Tensione Fase-Fase superiore a 415V nominali o con Tensione Fase-Neutro Fase-Terra superiore a 240V nominali.
> *   La misura dell'impedenza Fase - PE comporta la circolazione di una corrente massima di circa 116A fra i suddetti conduttori che causa l'intervento di eventuali protezioni differenziali e può causare l'intervento di protezioni magnetotermiche presenti a monte del punto di misura. Nel caso eseguire la misura a monte della protezione stessa.
> *   Se possibile scollegare tutti i carichi a bassa impedenza allacciati a valle del punto in cui si intende effettuare la prova in quanto l'impedenza dei suddetti carichi risulta in parallelo alla impedenza di linea che si intende misurare.
> *   Accertarsi sempre che la lamina superiore e quella inferiore dei coccodrilli siano in buon contatto con i conduttori del circuito in esame.
> *   Non scollegare i terminali dello strumento durante l'esecuzione della prova.

```
P1   C1   C2   P2
1    2    3    N    PE
```
*Fig. 5: Collegamento strumento per Misura dell'impedenza Fase-PE*

1.  Connettere l'interfaccia seriale dell'IMP57 allo strumento MASTER tramite il Cavo seriale apposito (vedere paragrafo 4.2).
2.  Collegare i coccodrilli alla rete elettrica in esame (vedere Fig. 5).
3.  Inserire le coppie di cavi nero-rosso dei cavi C7000 nei rispettivi terminali di ingresso dello strumento **seguendo la sequenza di inserimento P1, P2, C2, C1** (vedere connessione in Fig. 5).
4.  Verificare che il LED STATUS sia acceso e di colore Verde.
5.  Accendere lo strumento MASTER, selezionare su quest'ultimo la funzione "Misura di Impedenza ad alta Risoluzione Fase – PE" ed avviare la prova (vedere capitolo 6). Per la descrizione dei valori, dei simboli visualizzati, la memorizzazione dei risultati e l'invio dei dati ad un PC, si rimanda al capitolo 6.

# 6 ISTRUZIONI OPERATIVE PER STRUMENTO MASTER
Le istruzioni sono date per Tipologia di strumenti classificati secondo la Tabella 1.

## 6.1 ISTRUZIONI PER STRUMENTI DI TIPO 1
### 6.1.1 Impostazione Strumento
Ruotare il **selettore** in posizione **LOOP**. Selezionare, tramite il tasto **F1**, una delle seguenti tipi di connessione " **P-P** ", " **P-N** ", " **P-PE** " disponibile fra le possibili modalità "P-P", "P-N", "P-PE", " R A ", " ". Premere il tasto **F2** per abilitare la modalità di Misura di Impedenza ad Alta Risoluzione **Z2 Ω**. Corrispondentemente nella parte bassa del display verrà visualizzato il simbolo "Z2 Ω". All'interno della modalità **Z2 Ω** è possibile selezionare, tramite il tasto **F1**, una delle seguenti tipi di connessione (che si presentano ciclicamente alla pressione del tasto):

*   Modalità " **P-N** " (lo strumento effettua la misura ad alta risoluzione dell'impedenza fra il conduttore di Fase e il conduttore di Neutro e calcola la corrente di corto circuito presunta Fase-Neutro selezionata. Questa prova viene di solito eseguita per valutare se il potere di interruzione degli interruttori è superiore alla corrente di cortocircuito nel punto di installazione).
*   Modalità " **P-P** " (lo strumento effettua la misura ad alta risoluzione dell'impedenza fra due conduttori di Fase e calcola la corrente di corto circuito presunta Fase-Fase selezionata. Questa prova viene di solito eseguita per valutare se il potere di interruzione degli interruttori è superiore alla corrente di cortocircuito nel punto di installazione).
*   Modalità " **P-PE** " (lo strumento effettua la misura ad alta risoluzione dell'impedenza Globale verso Terra e calcola la corrente di corto circuito presunta Fase-Terra selezionata. Questa prova viene di solito eseguita per valutare il coordinamento delle protezioni contro i contatti indiretti mediante interruzione automatica dell’alimentazione).

La pressione del tasto **F3** consente di selezionare il tipo di Corrente di Corto circuito presunta che lo strumento calcolerà in accordo con le formule indicate al paragrafo 6.1.2. La pressione del tasto **F4** fornisce le informazioni relative al Numero di Serie dell'IMP57, la relativa Versione e la data di calibrazione. Per uscire da questa videata premere ESC. Per uscire dalla modalità **Z2 Ω** e tornare alla modalità standard premere nuovamente il tasto **F2**.

### 6.1.2 Calcolo delle Correnti di Corto Circuito

| Collegamento                         | Formula                                                                                                                                                                                                                                                                                                            |
| :----------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Fase – Fase (P-P)                    | ```
                                    2 3
                                    3   HOT P P NOM P P MIN ph MIN
                                    Z U C I
                                       
                                    ```
                                    Corrente presunta di CortoCircuito Minima Trifase
                                    ```
                                    2 3
                                    3  P P NOM P P MAX ph MAX
                                    Z U C I
                                       
                                    ```
                                    Corrente presunta di CortoCircuito Massima Trifase
                                    ```
                                    HOT P P NOM P P MIN ph MIN
                                    Z U C I
                                        2
                                    ```
                                    Corrente presunta di CortoCircuito Minima Fase-Fase
                                    ```
                                    P P NOM P P MAX ph MAX
                                    Z U C I
                                        2
                                    ```
                                    Corrente presunta di CortoCircuito Massima Fase-Fase |
| Fase – Neutro (P-N)                  | ```
                                    HOT N P NOM N P MIN N P MIN
                                    Z U C I
                                          
                                    ```
                                    Corrente presunta di CortoCircuito Minima Fase-Neutro
                                    ```
                                    N P NOM N P MAX N P MAX
                                    Z U C I
                                          
                                    ```
                                    Corrente presunta di CortoCircuito Massima Fase-Neutro |
| Fase- conduttore di Protezione (P-PE) | ```
                                    HOT PE P NOM PE P MIN PE P MIN
                                    Z U C I
                                          
                                    ```
                                    Corrente presunta di CortoCircuito Minima Fase-PE
                                    ```
                                    PE P NOM PE P MAX PE P MAX
                                    Z U C I
                                          
                                    ```
                                    Corrente presunta di CortoCircuito Massima Fase-PE |
| Generico                             | ```
                                    MIS NOM STD
                                    Z U I
                                    
                                    ```
                                    Corrente presunta di CortoCircuito Standard           |

dove:
```
2 2
) 5 . 1 (   X P X P HOT X P
X R Z
       
```
X= P, N, PE

e

| Tensione Misurata                    | U NOM     | C MIN | C MAX |
| :----------------------------------- | :-------- | :---- | :---- |
| 230V-10% < Vmisurata < 230V+ 10%    | 230V      | 0,95  | 1,05  |
| 230V+10% < Vmisurata < 400V- 10%    | Vmisurata | 1,00  | 1,10  |
| 400V-10% < Vmisurata < 400V+ 10%    | 400V      | 0,95  | 1,05  |

### 6.1.3 Avvio della Prova
Eseguito il collegamento dello strumento alla rete elettrica secondo quanto descritto al paragrafo 5 e terminata la fase di Impostazione descritta ai paragrafi 6.1.1 e 6.1.2, per avviare la prova è sufficiente premere il tasto **START**. Il LED STATUS assumerà il colore arancio per tutta la durata della prova ed al termine della stessa verranno visualizzati i risultati sul display.

### 6.1.4 Analisi risultati
#### Modalità "P-P"
In seguito alla prova lo strumento visualizza una videata del tipo sotto indicato:

```
LOOP   05.06.02   Impedenza Fase Fase (mΩ)
Z= 35.3   mΩ
R=9.1mΩ   X=34.1mΩ
IkMax3Ph=14kA V1-2=394V   FRQ=50.0HZ
P-P   Z2Ω
Resistenza Fase Fase (mΩ)
Tensione Misurata
Reattanza Fase Fase (mΩ)
Frequenza
Corrente   di   Corto   Circuito presunta
FUNZ   ZSTD   ICAL   RMT
```
Il Calcolo della corrente circuito presunta è ottenuto da una delle relazioni elencate al paragrafo 6.1.2 per la connessione Fase- Fase. I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE**.

#### Modalità "P-N"
In seguito alla prova lo strumento visualizza una videata del tipo sotto indicato:

```
LOOP   05.06.02   Impedenza Fase Neutro (mΩ)
Z= 27.0   mΩ
R=5.3mΩ   X=26.4mΩ
IkMaxP-N=8.9kA V1-2=226V   FRQ=50.0HZ
P-N   Z2Ω
Resistenza Fase Neutro (mΩ)
Tensione Misurata
Reattanza Fase Neutro (mΩ)
Frequenza
Corrente   di   Corto   Circuito presunta
FUNZ   ZSTD   ICAL   RMT
```
Il Calcolo della corrente circuito presunta è ottenuto da una delle relazioni elencate al paragrafo 6.1.2 per la connessione Fase- Neutro. I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE**.

#### Modalità "P-PE"
In seguito alla prova lo strumento visualizza una videata del tipo sotto indicato:

```
LOOP   05.06.02   Impedenza Fase Neutro (mΩ)
Z= 27.0   mΩ
R=5.3mΩ   X=26.4mΩ
IkMaxP-N=8.5kA V1-2=226V   FRQ=50.0HZ
P-PE   Z2Ω
Resistenza Fase Neutro (mΩ)
Tensione Misurata
Reattanza Fase Neutro (mΩ)
Frequenza
Corrente   di   Corto   Circuito presunta
FUNZ   ZSTD   ICAL   RMT
```
Il Calcolo della corrente circuito presunta è ottenuto da una delle relazioni elencate al paragrafo 6.1.2 per la connessione Fase- Conduttore di Protezione. I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE**.

### 6.1.5 Situazioni anomale modalità "P-P", "P-N", "P-PE"

```
LOOP   05.06.02
Z= - - - - -   Ω
R=----- Ω   X=----- Ω
IkSTD=----A V1-2=231V   FRQ=50.0HZ
NO IMP57
P-N   Z2Ω
FUNZ   ZSTD   ICAL   RMT
```
La visualizzazione del Messaggio " **NO IMP57**" indica che l'IMP57 non sta rispondendo ai comandi inviati dallo strumento MASTER tramite l'interfaccia seriale. In questo caso verificare:
1.  Che lo strumento MASTER sia connesso all'IMP57 tramite il cavo C2001.
2.  Che l'IMP57 sia alimentato (LED status Verde).

*   Se, in seguito alla pressione del tasto START, lo strumento rileva la connessione all'alimentatore esterno, viene visualizzato il messaggio indicato a lato.
    ```
    LOOP   05.06.02
    Z= - - - - -   Ω
    R=----- Ω   X=----- Ω
    IkSTD=----A V1-2=231V   FRQ=50.0HZ
       TOGLI ALIM.
    P-N   Z2Ω
    Per motivi di sicurezza, lo strumento   non   esegue   le prove   di   Verifica   qualora sia collegato l'alimentatore esterno. Per   eseguire   la   prova disconnettere l'alimentatore
    FUNZ   ZSTD   ICAL   RMT
    ```

*   Se, in seguito alla pressione del Tasto START, lo strumento rileva una Tensione fra P1 e P2 minore di 190V, visualizza il messaggio a lato.
    ```
    LOOP   05.06.02
    Z= - - - - -   Ω
    R=----- Ω   X=----- Ω
    IkSTD=----A V1-2=181V   FRQ=50.0HZ
       TENSIONE BASSA
    P-N   Z2Ω
    Tensione insufficiente
    FUNZ   ZSTD   ICAL   RMT
    ```

*   Se, in seguito alla pressione del Tasto START, lo strumento rileva una Tensione fra P1 e P2 > 460V (415V+10%) visualizza il messaggio a lato.
    ```
    LOOP   05.06.02
    Z= - - - - -   Ω
    R=----- Ω   X=----- Ω
    IkSTD=----A V1-2=461V   FRQ=50.0HZ
       TENSIONE ALTA
    P-P   Z2Ω
    Tensione troppo elevata
    FUNZ   ZSTD   ICAL   RMT
    ```

*   Se, in seguito alla pressione del tasto START, lo strumento rileva che la corrente circolante è inferiore a 10A visualizza la videata a lato. Controllare che i coccodrilli facciano un buon contatto con i conduttore del circuito in esame.
    ```
    LOOP   05.06.02
    Z= - - - - -   Ω
    R=----- Ω   X=----- Ω
    IkSTD=----A V1-2=461V   FRQ=50.0HZ
    CORRENTE NON OK
    P-P   Z2Ω
    FUNZ   ZSTD   ICAL   RMT
    ```

*   Se, in seguito a ripetute prove, lo strumento si è surriscaldato, viene visualizzato il messaggio a lato. Attendere che tale messaggio scompaia prima di eseguire altre prove.
    ```
    LOOP   05.06.02
    Z= - - - - -   Ω
    R=----- Ω   X=----- Ω
    IkSTD=----A V1-2=461V   FRQ=50.0HZ
    ALTA TEMP
    P-P   Z2Ω
    FUNZ   ZSTD   ICAL   RMT
    Lo   strumento   si   è surriscaldato
    ```

*   Se, in seguito alla pressione del tasto START, lo strumento visualizza il messaggio a lato contattare il Servizio di Assistenza HT Italia.
    ```
    LOOP   05.06.02
    Z= - - - - -   Ω
    R=----- Ω   X=----- Ω
    IkSTD=----A V1-2=461V   FRQ=50.0HZ
    Errore 5
    P-P   Z2Ω
    FUNZ   ZSTD   ICAL   RMT
    ```
    I PRECEDENTI RISULTATI NON POSSONO ESSERE MEMORIZZATI.

*   Se lo strumento rileva una impedenza maggiore di 1999mΩ visualizza la videata a lato. Disconnettere l'IMP57 dalla rete elletrica ed utilizzare la funzione Loop presente nello strumento MASTER disabilitando la modalità **Z2 Ω**.
    ```
    LOOP   05.06.02   Il simbolo">" indica che il valore   dell'impedenza   è maggiore   del   valore Massimo misurabile
    Z> 1999 mΩ
    R>1999mΩ   X>1999mΩ
    IkSTD=----A V1-2=461V   FRQ=50.0HZ
    P-P   Z2Ω
    FUNZ   ZSTD   ICAL   RMT
    ```
    I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE**.

## 6.2 ISTRUZIONI PER STRUMENTI DI TIPO 2
Per la definizione degli Strumenti di Tipo 2 vedere Tabella 1.

### 6.2.1 Impostazione Strumento
Ruotare il **selettore** in posizione **LOOP**. Selezionare, tramite il tasto **FUNC**, una delle seguenti tipi di connessione " **P-P** ", " **P-N** ", " **P-PE** ". disponibile fra le possibili modalità "P-P", "P-N", "P-PE", " R A ", " ". Premere il tasto **Un/I Δ n** per abilitare la modalità di Misura di Impedenza ad Alta Risoluzione **Z2 Ω**. Corrispondentemente nella parte alta del display verranno visualizzati i simboli "LOW Ω" e "LOOP". All'interno della modalità **Z2 Ω** è possibile selezionare, tramite il tasto **FUNC**, una delle seguenti tipi di connessione (che si presentano ciclicamente alla pressione del tasto):

*   Modalità " **P-N** " (lo strumento effettua la misura ad alta risoluzione dell'impedenza fra il conduttore di Fase e il conduttore di Neutro e calcola la corrente di corto circuito presunta. Questa prova viene di solito eseguita per valutare se il potere di interruzione degli interruttori è superiore alla corrente di cortocircuito nel punto di installazione).
*   Modalità " **P-P** " (lo strumento effettua la misura ad alta risoluzione dell'impedenza fra due conduttori di Fase e calcola la corrente di corto circuito presunta. Questa prova viene di solito eseguita per valutare se il potere di interruzione degli interruttori è superiore alla corrente di cortocircuito nel punto di installazione).
*   Modalità " **P-PE** " (lo strumento effettua la misura ad alta risoluzione dell'impedenza Globale verso Terra e calcola la corrente di corto circuito presunta. Questa prova viene di solito eseguita per valutare il coordinamento delle protezioni contro i contatti indiretti mediante interruzione automatica dell’alimentazione).

Per uscire dalla modalità **Z2 Ω** e tornare alla modalità standard premere nuovamente il tasto **Un/I Δ n**.

### 6.2.2 Calcolo della Corrente di Corto Circuito
Indipendentemente dalla connessione selezionata lo strumento calcola la corrente di corto circuito come:
```
MIS NOM STD
Z U I

```
Corrente presunta di CortoCircuito Standard

dove:

| Tensione Misurata                    | U NOM     |
| :----------------------------------- | :-------- |
| 230V-10% < Vmisurata < 230V+ 10%    | 230V      |
| 230V+10% < Vmisurata < 400V- 10%    | Vmisurata |
| 400V-10% < Vmisurata < 400V+ 10%    | 400V      |

### 6.2.3 Avvio della Prova
Eseguito il collegamento dello strumento alla rete elettrica secondo quanto descritto al paragrafo 5 e terminata la fase di Impostazione descritta ai paragrafi 6.2.1 e 6.2.2, per avviare la prova è sufficiente premere il tasto **START**. Il LED STATUS assumerà il colore arancio per tutta la durata della prova ed al termine della stessa verranno visualizzati i risultati sul display.

### 6.2.4 Analisi Risultati
#### Modalità "P-P"
In seguito alla prova lo strumento visualizza una videata del tipo sotto indicato:

```
LOW Ω   LOOP
100.0   mΩ
P-P
392 V   4.0   kA
```
Impedenza Fase Fase espressa in mΩ
Tensione Misurata
Corrente   di   Corto   Circuito presunta
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE**.

#### Modalità "P-N"
In seguito alla prova lo strumento visualizza una videata del tipo sotto indicato:

```
LOW Ω   LOOP
100.0   mΩ
P-N
232 V   2.3   kA
```
Impedenza Fase Neutro in mΩ
Tensione Misurata
Corrente   di   Corto   Circuito presunta
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE**.

<!-- Chunk: Pages 21-39 -->
## Modalità "P-PE"

In seguito alla prova lo strumento visualizza una videata del tipo sotto indicato:

```
LOW Ω   LOOP
100.0   mΩ   P-PE
232 V   2.3   kA
```

Impedenza Fase PE in mΩ
Tensione Misurata
Corrente di Corto Circuito presunta

I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE`.

### 6.2.5 Situazioni anomale modalità "P-P", "P-N", "P-PE"

```
LOW Ω   LOOP
         no  ins   con
```

La visualizzazione del Messaggio "` no con inS`" (no connected instrument) indica che l'IMP57 **non** sta **rispondendo** ai **comandi** inviati dallo strumento **MASTER** tramite l'interfaccia seriale. In questo caso verificare:

1.  Che lo strumento MASTER sia connesso all'IMP57 tramite il cavo `C2001`.
2.  Che l'IMP57 sia alimentato (LED status Verde).

> Se, in seguito alla pressione del tasto `START`, lo strumento rileva una Tensione fra `P1` e `P2` minore di `190V`, visualizza il messaggio a lato.

```
LOW Ω   LOOP
       Lo  UOL   tAG
```

> Se, in seguito alla pressione del tasto `START`, lo strumento rileva una Tensione fra `P1` e `P2` maggiore di `460V`, visualizza il messaggio a lato.

```
LOW Ω   LOOP
     Hi  UOL   tAG
```

> Se, in seguito alla pressione del tasto `START`, lo strumento rileva che la corrente circolante è inferiore a `10A`. Controllare che i coccodrilli facciano un buon contatto con i conduttori del circuito in esame.

```
LOW Ω   LOOP
  Lo  cur
```

> Se, in seguito a ripetute prove, lo strumento si è surriscaldato, viene visualizzato il messaggio a lato. Attendere che tale messaggio scompaia prima di eseguire altre prove.

```
LOW Ω   LOOP
      hot
```

> Se, in seguito alla pressione del tasto `START`, lo strumento visualizza il messaggio a lato contattare il Servizio di Assistenza HT Italia.

```
LOW Ω   LOOP
   ntc
```

I PRECEDENTI RISULTATI NON POSSONO ESSERE MEMORIZZATI.

> Se lo strumento rileva una impedenza maggiore di `1999mΩ` visualizza la videata a lato. Disconnettere l'IMP57 dalla rete elettrica ed utilizzare la funzione Loop presente nello strumento MASTER disabilitando la modalità `Z2Ω`.

```
LOW Ω   LOOP
 >1999   mΩ   P-PE
232 V   - - -   A
```

Il simbolo ">" indica che il valore dell'impedenza è maggiore del valore Massimo misurabile.
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE`.

## 6.3 ISTRUZIONI PER STRUMENTI DI TIPO 3

Per la definizione degli Strumenti di Tipo 3 vedere Tabella 1.

### 6.3.1 Impostazione Strumento

Premere il tasto `MENU`, posizionare il cursore sulla voce `LOOP` del menù principale utilizzando i tasti freccia ``, `` e confermare con `ENTER`.

**Mod.**
Selezionare con i tasti freccia ``, `` il tasto virtuale `Mod.` e con i tasti freccia ``, `` la modalità di funzionamento `Z2Ω`. Lo strumento mostra una schermata come la seguente:

```
L O O P
Z = - - - - -   Ω
R = - - - - -   Ω   X = - - - - -   Ω
I k S T D = - - - - A V1-2 =230V   FRQ =50Hz
P-N   Z2Ω
Funz   Mod.   ICAL   RMT
```

**Funz**
Selezionare con i tasti freccia ``, `` il tasto virtuale `Funz` e con i tasti freccia ``, `` la modalità di funzionamento che potrà essere:

*   **Modalità “P-N”** (lo strumento misura l'impedenza fra il conduttore di Fase e il conduttore di Neutro e calcola la corrente di corto circuito presunta Fase-Neutro. Questa prova viene di solito eseguita negli impianti Monofase per valutare se il potere di interruzione degli interruttori è superiore alla corrente di cortocircuito nel punto di installazione).
*   **Modalità “P-P”** (lo strumento misura l'impedenza fra due conduttori di Fase e calcola la corrente di corto circuito presunta Fase-Fase. Questa prova viene di solito eseguita negli impianti Trifase per valutare se il potere di interruzione degli interruttori è superiore alla corrente di cortocircuito nel punto di installazione).
*   **Modalità “P-PE”** (lo strumento misura la resistenza Globale di Terra e calcola la corrente di corto circuito presunta Fase-Terra. Questa prova viene di solito eseguita per valutare il coordinamento delle protezioni contro i contatti indiretti mediante interruzione automatica dell’alimentazione e per misurare il valore della Resistenza di Terra).

**ICAL**
Selezionare con i tasti freccia ``, `` il tasto virtuale `ICAL` e con i tasti freccia ``, `` selezionare il tipo di Corrente di Corto circuito presunta che lo strumento calcolerà in accordo con le formule indicate al paragrafo 6.3.2.

*   `IkSTD`, `IkMax3Ph`, `IkMin3Ph`, `IkMax2Ph`, `IkMin2Ph` se col tasto `Funz` è stata selezionata la funzione `P-P`.
*   `IkSTD`, `IkMaxP-N`, `IkMinP-N` se col tasto `Funz` è stata selezionata la funzione `P-N`.
*   `IkSTD`, `IkMaxP-PE`, `IkMinP-PE` se col tasto `Funz` è stata selezionata la funzione `P-PE`.

**RMT:**
Selezionare con i tasti freccia ``, `` il tasto virtuale `RMT` e lo strumento visualizzerà i seguenti dati dell'unità remota IMP57:

*   Numero di serie.
*   Versione FW.
*   Data di calibrazione.

### 6.3.2 Calcolo delle Correnti di Corto Circuito

**Collegamento Fase – Fase (P-P)**

Corrente presunta di CortoCircuito Minima Trifase
$I_{MIN3ph} = \frac{C_{MIN} \cdot U_{NOM}}{\sqrt{3} \cdot Z_{HOT\_P\_P}}$

Corrente presunta di CortoCircuito Massima Trifase
$I_{MAX3ph} = \frac{C_{MAX} \cdot U_{NOM}}{\sqrt{3} \cdot Z_{P\_P}}$

Corrente presunta di CortoCircuito Minima Fase-Fase
$I_{MIN\_P\_P} = \frac{C_{MIN} \cdot U_{NOM}}{\sqrt{2} \cdot Z_{HOT\_P\_P}}$

Corrente presunta di CortoCircuito Massima Fase-Fase
$I_{MAX\_P\_P} = \frac{C_{MAX} \cdot U_{NOM}}{\sqrt{2} \cdot Z_{P\_P}}$

**Fase – Neutro (P-N)**

Corrente presunta di CortoCircuito Minima Fase-Neutro
$I_{MIN\_P\_N} = \frac{C_{MIN} \cdot U_{NOM}}{Z_{HOT\_P\_N}}$

Corrente presunta di CortoCircuito Massima Fase-Neutro
$I_{MAX\_P\_N} = \frac{C_{MAX} \cdot U_{NOM}}{Z_{P\_N}}$

**Fase-conduttore di Protezione (P-PE)**

Corrente presunta di CortoCircuito Minima Fase-PE
$I_{MIN\_P\_PE} = \frac{C_{MIN} \cdot U_{NOM}}{Z_{HOT\_P\_PE}}$

Corrente presunta di CortoCircuito Massima Fase-PE
$I_{MAX\_P\_PE} = \frac{C_{MAX} \cdot U_{NOM}}{Z_{P\_PE}}$

**Generico**

Corrente presunta di CortoCircuito Standard
$I_{STD} = \frac{U_{NOM}}{Z_{MIS}}$

dove:
$Z_{HOT\_X\_P} = \sqrt{R_{X\_P}^2 + (1.5 \cdot X_{X\_P})^2}$
X= P, N, PE

e

| Tensione Misurata                    | U_NOM  | C_MIN | C_MAX |
| :----------------------------------- | :----- | :---- | :---- |
| 230V-10% < Vmisurata < 230V+ 10%   | 230V   | 0,95  | 1,05  |
| 230V+10% < Vmisurata < 400V- 10%   | Vmisurata | 1,00  | 1,10  |
| 400V-10% < Vmisurata < 400V+ 10%   | 400V   | 0,95  | 1,05  |

### 6.3.3 Avvio della Prova

Eseguito il collegamento dello strumento alla rete elettrica secondo quanto descritto al paragrafo 5 e terminata la fase di Impostazione descritta ai paragrafi 6.3.1 e 6.3.2, per avviare la prova è sufficiente premere il tasto `GO/STOP`. Il LED STATUS assumerà il colore arancio per tutta la durata della prova ed al termine della stessa verranno visualizzati i risultati sul display.

### 6.3.4 Analisi risultati Modalità "P-P"

> Lo strumento, a fine prova, emette un doppio segnale acustico che segnala che la prova è stata eseguita correttamente e visualizza una videata simile a quella a fianco.

```
L O O P
Z = 1 4 . 3 m   Ω
R=138.0m Ω   X=38.9m Ω
I k S T D = 2 . 8 k A V1-2 =394V   FRQ =50Hz
Impedenza Fase-Fase (mΩ)
Resistenza Fase-Fase (mΩ)
Reattanza Fase-Fase (mΩ)
Corrente presunta di c.c.
P-P   Z2Ω
Funz   Mod.   ICAL   RMT
Tensione misurata
```

Il Calcolo della corrente circuito presunta è ottenuto da una delle relazioni elencate al paragrafo 6.3.2 per la connessione Fase - Fase.

**Modalità "P-N"**

> Lo strumento, a fine prova, emette un doppio segnale acustico che segnala che la prova è stata eseguita correttamente e visualizza una videata simile a quella a fianco.

```
L O O P
Z = 1 4 . 4 m   Ω
R=138.9m Ω   X=39.3m Ω
I k S T D = 1 5 9 2 A V1-2 =230V   FRQ =50Hz
Impedenza Fase-Neutro (mΩ)
Resistenza Fase-Neutro (mΩ)
Reattanza Fase-Neutro (mΩ)
Corrente presunta di c.c.
P-N   Z2Ω
Funz   Mod.   ICAL   RMT
Tensione misurata
```

Il Calcolo della corrente circuito presunta è ottenuto da una delle relazioni elencate al paragrafo 6.3.2 per la connessione Fase - Neutro.

**Modalità "P-PE"**

> Lo strumento, a fine prova, emette un doppio segnale acustico che segnala che la prova è stata eseguita correttamente e visualizza una videata simile a quella a fianco.

```
L O O P
Z = 1 4 . 3 m   Ω
R=137.8m Ω   X=38.3m Ω
I k S T D = 1 6 0 7 A V1-2 =230V   FRQ =50Hz
Impedenza Fase-Terra (mΩ)
Resistenza Fase-Terra (mΩ)
Reattanza Fase-Terra (mΩ)
Corrente presunta di c.c.
P-PE   Z2Ω
Funz   Mod.   ICAL   RMT
Tensione misurata
```

Il Calcolo della corrente circuito presunta è ottenuto da una delle relazioni elencate al paragrafo 6.3.2 per la connessione Fase - Terra.

> Tutti i risultati visualizzati sono memorizzabili premendo il tasto `SAVE` (**2 volte**) oppure `SAVE` e successivamente il tasto `ENTER`.

### 6.3.5 Situazioni anomale modalità "P-P", "P-N", "P-PE"

> La visualizzazione del messaggio "`NO IMP57`" indica che l'IMP57 non sta rispondendo ai comandi inviati dallo strumento MASTER tramite l'interfaccia seriale. In questo caso verificare che lo strumento MASTER sia connesso all'IMP57 tramite il cavo seriale apposito e che l'IMP57 sia alimentato (LED status Verde).

```
L O O P
Z = - - - - -   Ω
R = - - - - -   Ω   X = - - - - -   Ω
I k S T D = - - - - A V 1- 2=   0 V   FR Q=0 .0Hz
NO IMP57
P-PE   Z2Ω
Funz   Mod.   ICAL   RMT
```

> Se, in seguito alla pressione del Tasto `GO/STOP`, lo strumento rileva una Tensione fra `P1` e `P2` minore di `190V`, visualizza il messaggio a lato.

```
L O O P
Z = - - - - -   Ω
R = - - - - -   Ω   X = - - - - -   Ω
I k S T D = - - - - A V1-2 =180V   FRQ =50Hz
Tensione insufficiente
Tensione bassa
P-N   Z2Ω
Funz   Mod.   ICAL   RMT
```

> Se, in seguito alla pressione del Tasto `GO/STOP`, lo strumento rileva una Tensione fra `P1` e `P2` > `460V` (`415V+10%`) visualizza il messaggio a lato.

```
L O O P
Z = - - - - -   Ω
R = - - - - -   Ω   X = - - - - -   Ω
I k S T D = - - - - A V1-2 =481V   FRQ =50Hz
Rilevata una tensione alta
Tensione alta
P-P   Z2Ω
Funz   Mod.   ICAL   RMT
```

> Se, in seguito alla pressione del tasto `START`, lo strumento rileva che la corrente circolante è inferiore a `10A` visualizza la videata a lato. Controllare che i coccodrilli facciano un buon contatto con i conduttori del circuito in esame.

```
L O O P
Z = - - - - -   Ω
R = - - - - -   Ω   X = - - - - -   Ω
I k S T D = - - - - A V1-2 =460V   FRQ =50Hz
Corrente NON OK
P-P   Z2Ω
Funz   Mod.   ICAL   RMT
```

> Se, in seguito alla pressione del tasto `START`, lo strumento rileva che la frequenza di rete non rientra nei limiti impostati visualizza la videata a lato.

```
L O O P
Z = - - - - -   Ω
R = - - - - -   Ω   X = - - - - -   Ω
I k S T D = - - - - A V1-2 =460V   FRQ =54Hz
ERR.: SINC
P-P   Z2Ω
Funz   Mod.   ICAL   RMT
```

> Se, in seguito alla pressione del tasto `START`, lo strumento visualizza il messaggio a lato contattare il Servizio di Assistenza HT Italia.

```
L O O P
Z = - - - - -   Ω
R = - - - - -   Ω   X = - - - - -   Ω
I k S T D = - - - - A V1-2 =460V   FRQ =50Hz
ERR.: NTC
P-P   Z2Ω
Funz   Mod.   ICAL   RMT
```

> Se, in seguito a ripetute prove, lo strumento si è surriscaldato, viene visualizzato il messaggio a lato. Attendere che tale messaggio scompaia prima di eseguire altre prove.

```
L O O P
Z = - - - - -   Ω
R = - - - - -   Ω   X = - - - - -   Ω
I k S T D = - - - - A V1-2 =280V   FRQ =50Hz
Strumento surriscaldato
Alta temperatura
P-N   Z2Ω
Funz   Mod.   ICAL   RMT
```

> I precedenti risultati **NON** possono essere memorizzati.

> Utilizzando le modalità “`P-P`”, “`P-N`”, “`P-PE`” se lo strumento rileva un’impedenza maggiore di `1999mΩ` visualizza a fine prova la videata a lato ed emette un segnale acustico prolungato. Disconnettere l'IMP57 dalla rete elettrica ed utilizzare la funzione Loop presente nello strumento MASTER disabilitando la modalità `Z2Ω`.

```
L O O P
Il simbolo “>” indica che il valore dell’impedenza
è maggiore del valore massimo misurabile
Z > 1 9 9 9 m   Ω
R>1999m Ω   X>1999m Ω
I k S T D = - - - - A V1-2 =230V   FRQ =50Hz
P-N   Z2Ω
Funz   Mod.   ICAL   RMT
```

> I risultati visualizzati sono memorizzabili premendo il tasto `SAVE` (**2 volte**) oppure `SAVE` e successivamente il tasto `ENTER`.

## 6.4 ISTRUZIONI PER STRUMENTI DI TIPO 4

Per la definizione degli Strumenti di Tipo 4 vedere Tabella 1.

### 6.4.1 Impostazione Strumento

1.  Premere il tasto di accensione dello strumento.
2.  Premendo il tasto `FUNC` selezionare la funzione `CONTINUITY`.
3.  Premendo il tasto `MODE` selezionare la modalità `EXT`. Lo strumento mostrerà una videata quella a lato.

    ```
    m   Ω
    A   V
    ```

4.  Premendo il tasto `SET DISPLAY`, lo strumento si pone nella modalità di impostazione del valore della corrente nominale `In` della protezione magnetotermica. Con i tasti freccia selezionare il valore della corrente nominale.

    ```
    A
    ```

5.  Premendo il tasto `SET DISPLAY` nuovamente, lo strumento si pone nella modalità di impostazione del tipo di protezione. Con i tasti freccia selezionare il tipo di protezione (curva `B` o curva `C`).
    Premere il tasto `SAVE` per confermare le modifiche.
6.  OPPURE
    Premere il tasto `ESC RECALL` per uscire senza confermare le modifiche.

### 6.4.2 Calcolo della Corrente di Corto Circuito

Lo strumento calcola la corrente di corto circuito come:

Corrente presunta di CortoCircuito Minima Fase-PE
$I_{MIN\_P\_PE} = \frac{C_{MIN} \cdot U_{NOM}}{Z_{HOT\_PE\_P}}$

dove:
$Z_{HOT\_PE\_P} = \sqrt{R_{PE\_P}^2 + (1.5 \cdot X_{PE\_P})^2}$

e

| Tensione Misurata                    | U_NOM  | C_MIN |
| :----------------------------------- | :----- | :---- |
| 230V-10% < Vmisurata < 230V+ 10%   | 230V   | 0,95  |
| 230V+10% < Vmisurata < 400V- 10%   | Vmisurata | 1,00  |
| 400V-10% < Vmisurata < 400V+ 10%   | 400V   | 0,95  |

### 6.4.3 Avvio della Prova

Eseguito il collegamento dello strumento alla rete elettrica secondo quanto descritto al paragrafo 5 e terminata la fase di impostazione descritta ai paragrafi 6.4.1 e 6.4.2, per avviare la prova è sufficiente premere il tasto `START/STOP`. Il LED STATUS assumerà il colore arancio per tutta la durata della prova ed al termine della stessa verranno visualizzati i risultati sul display.

### 6.4.4 Analisi risultati

In seguito alla prova lo strumento visualizza una videata del tipo sotto indicato:

```
m   Ω
V A
```

Valore di Impedenza misurata `Z_mis`
Valore della corrente `I_min_P-PE`
Valore della tensione misurata
Esito positivo della prova

> Premere il tasto `SAVE` **2 volte** per salvare il valore misurato.

### 6.4.5 Situazioni anomale

> La visualizzazione del messaggio "`NOT READY`" indica che l'IMP57 non sta rispondendo ai comandi inviati dallo strumento MASTER tramite l'interfaccia seriale. In questo caso verificare che lo strumento MASTER sia connesso all'IMP57 tramite il cavo `C232NG1` e che l'IMP57 sia alimentato (LED status Verde).

```
V
m   Ω
A
```

> Se in seguito alla pressione del tasto `START/STOP` viene visualizzato il messaggio a lato, significa che la tensione rilevata dall’IMP57 non raggiunge il limite minimo prefissato.

```
V
```

> Se in seguito alla pressione del tasto `START/STOP` viene visualizzato il messaggio a lato, significa che la tensione rilevata dall’IMP57 supera il limite prefissato.

```
V
```

> Se in seguito alla pressione del tasto `START/STOP` viene visualizzato il messaggio a lato, significa che lo strumento rileva che la corrente circolante è inferiore a `10A`.

> Se in seguito alla pressione del tasto `START/STOP` viene visualizzato il messaggio a lato, significa che lo strumento rileva che la sonda di temperatura ha raggiunto una temperatura troppo elevata.

> Se in seguito alla pressione del tasto `START/STOP` viene visualizzato il messaggio a lato, significa che lo strumento rileva un errore di codifica dati dall’IMP57.

> Tutti i precedenti risultati non possono essere memorizzati.

> Se in seguito alla prova lo strumento visualizza una videata del tipo a lato indicato, significa che la prova ha dato esito negativo.

```
m   Ω
V A
```

> Se in seguito alla prova lo strumento visualizza una videata del tipo a lato indicato, indica che l’impedenza misurata è maggiore dell’impedenza massima misurabile.

```
V A
m   Ω
```

> Premere il tasto `SAVE` **2 volte** per salvare il valore misurato.

## 6.5 ISTRUZIONI PER STRUMENTI DI TIPO 5

Per la definizione degli Strumenti di Tipo 5 vedere Tabella 1.

### 6.5.1 Impostazione Strumento

1.  Utilizzando i tasti freccia (``) selezionare la funzione `CONTINUITA' 12V/>10A~`.
2.  Premendo il tasto `SET LIMIT/TIME` **2 volte** in rapida successione e successivamente il tasto `CLR` è possibile impostare la modalità di misura `LOOP`.
3.  Premere il tasto `SET LIMIT/TIME`. Lo strumento si pone nella modalità di impostazione del Tipo di Protezione magnetotermica, che potrà essere `Tipo B` o `Tipo C`.
4.  Utilizzando i tasti freccia (``) selezionare il Tipo di Protezione magnetotermica.
5.  Premere il tasto `SET LIMIT/TIME`. Lo strumento memorizza l’impostazione corrente del Tipo di Protezione magnetotermica e si pone nella modalità di impostazione della Corrente Nominale del dispositivo di protezione magnetotermica, che potrà assumere i seguenti valori: `6, 10, 16, 20, 25, 32, 50, 63 A`.
6.  Utilizzando i tasti freccia (``) selezionare la Corrente Nominale del dispositivo di protezione magnetotermica.
7.  Premere il tasto `SET LIMIT/TIME`. Lo strumento memorizza l’impostazione corrente della Corrente Nominale del dispositivo di protezione magnetotermica e si pone nella condizione di avvio della prova.

### 6.5.2 Calcolo della Corrente di Corto Circuito

Lo strumento calcola la corrente di corto circuito come:

Corrente presunta di CortoCircuito Minima Fase-PE
$I_{MIN\_P\_PE} = \frac{C_{MIN} \cdot U_{NOM}}{Z_{HOT\_PE\_P}}$

dove:
$Z_{HOT\_PE\_P} = \sqrt{R_{PE\_P}^2 + (1.5 \cdot X_{PE\_P})^2}$

e

| Tensione Misurata                    | U_NOM  | C_MIN |
| :----------------------------------- | :----- | :---- |
| 230V-10% < Vmisurata < 230V+ 10%   | 230V   | 0,95  |
| 230V+10% < Vmisurata < 400V- 10%   | Vmisurata | 1,00  |
| 400V-10% < Vmisurata < 400V+ 10%   | 400V   | 0,95  |

### 6.5.3 Avvio della Prova

Eseguito il collegamento dello strumento alla rete elettrica secondo quanto descritto al paragrafo 5.3 e terminata la fase di impostazione descritta ai paragrafi 6.5.1 e 6.5.2, per avviare la prova è sufficiente premere il tasto `START`. La spia `TEST` si accende ad indicare che l’IMP57 sta eseguendo la prova. Il LED STATUS assumerà il colore arancio per tutta la durata della prova ed al termine della stessa verranno visualizzati i risultati sul display. Se necessario, salvare il risultato premendo il tasto `SAVE`.

### 6.5.4 Analisi risultati

Lo strumento effettua la misurazione dell’impedenza di linea Fase - Terra tra i due punti ai quali sono collegati i coccodrilli dell’IMP57. Il risultato è considerato buono (evidenziato da un **breve** segnale sonoro bip - bip dopo aver completato la misura) o non buono (evidenziato da un suono prolungato che si arresta solo alla pressione del tasto `STOP`) se il valore della corrente di corto circuito presunta minima fase e terra è maggiore o minore del valore di soglia della corrente limite `Ilim`. Il valore di `Ilim` dipende dai valori impostati della Corrente Nominale della protezione magnetotermica e del Tipo di protezione magnetotermica (vedi par. 6.5.1).

### 6.5.5 Situazioni anomale

1.  La visualizzazione del messaggio "`not rdy`" indica che l'IMP57 non sta rispondendo ai comandi inviati dal `FULLTEST4050` tramite l'interfaccia seriale. Verificare che il `FULLTEST4050` sia connesso all'IMP57 tramite il cavo `C232NG1` e che l'IMP57 sia alimentato (LED status Verde).
2.  Se in seguito alla pressione del tasto `START`, viene visualizzato il messaggio “`180 Err.`” ed emesso un beep per 3 secondi, significa che la tensione rilevata dall’IMP57 non raggiunge il limite minimo prefissato.
3.  Se in seguito alla pressione del tasto `START`, viene visualizzato il messaggio “`480 Err.`” ed emesso un beep per 3 secondi, significa che la tensione rilevata dall’IMP57 supera il limite prefissato.
4.  Se in seguito alla pressione del tasto `START`, viene visualizzato il messaggio “`HOT`” ed emesso un beep per 3 secondi, significa che lo strumento rileva che la sonda di temperatura ha raggiunto una temperatura troppo elevata.
5.  Se in seguito alla pressione del tasto `START`, viene visualizzato il messaggio “`Curr. Err.`” ed emesso un beep per 3 secondi, significa che lo strumento rileva che la corrente circolante è inferiore a `10A`.
6.  Se in seguito alla pressione del tasto `START`, viene visualizzato il messaggio “`Err. 5`” ed emesso un beep per 3 secondi, significa che lo strumento rileva un errore di codifica dati dall’IMP57.
7.  Se in seguito alla pressione del tasto `START`, lo strumento visualizza “`O.r.`” ed emette un beep prolungato, che si arresta solo alla pressione del tasto `STOP`, indica che l’impedenza misurata è maggiore dell’impedenza massima misurabile.

## 7 TRASFERIMENTO DATI AD UN PC

Per il trasferimento dati al PC si rimanda a quanto indicato nel manuale d'uso degli strumenti MASTER. Uscire sempre dalla modalità `Z2Ω` prima di mettere in comunicazione PC e strumento MASTER.

## 8 MANUTENZIONE

### 8.1 GENERALITÀ

*   Lo strumento da Lei acquistato è uno strumento di precisione. Durante l’utilizzo e l’immagazzinamento rispettare le raccomandazioni elencate in questo manuale per evitare possibili danni o pericoli durante l’utilizzo.
*   Non utilizzare lo strumento in ambienti caratterizzati da elevato tasso di umidità o temperatura elevata. Non esporre direttamente alla luce del sole.

### 8.2 PULIZIA DELLO STRUMENTO

Per la pulizia dello strumento utilizzare un panno morbido e asciutto. Non usare mai panni umidi, solventi, acqua, ecc.

### 8.3 FINE VITA

**ATTENZIONE**: il simbolo riportato sullo strumento indica che l'apparecchiatura ed i suoi accessori devono essere raccolti separatamente e trattati in modo corretto.

## 9 SPECIFICHE TECNICHE

### 9.1 CARATTERISTICHE TECNICHE

La precisione è indicata come [% della lettura + numero di cifre]. Essa è riferita alle seguenti condizioni atmosferiche: temperatura `23°C ± 5°C` con umidità relativa `< 60%RH`.

*   **MISURA DI IMPEDENZA**

| Portata                  | Risoluzione  | Precisione                 |
| :----------------------- | :----------- | :------------------------- |
| `0.0 ÷ 199.9mΩ`          | `0.1mΩ`      | `± (5.0 % lettura+1mΩ)`    |
| `200 ÷ 1999mΩ`           | `1mΩ`        |                            |

Corrente di prova max = `202A`

*   **MISURA DI RESISTENZA E REATTANZA** (solo per strumenti Tipo 1 e Tipo 3 - vedi Tabella 1 pag. 8)

| Portata                  | Risoluzione  | Precisione                 |
| :----------------------- | :----------- | :------------------------- |
| `0.0 ÷ 199.9mΩ`          | `0.1mΩ`      | `± (10 % lettura+2mΩ)`     |
| `200 ÷ 1999mΩ`           | `1mΩ`        |                            |

Corrente di prova max = `202A`

*   **CORRENTE DI CORTO CIRCUITO PRESUNTA**

| Portata          | Risoluzione | Precisione                                                                    |
| :--------------- | :---------- | :---------------------------------------------------------------------------- |
| `0 ÷ 1999A`      | `1A`        | determinata dalla precisione di Z secondo le formule indicate ai paragrafi 6.1.2 o 6.2.2 o 6.3.2 o 6.4.2 |
| `2.0 ÷ 9.9kA`    | `0.1kA`     |                                                                               |
| `10 ÷ 1999kA`    | `1kA`       |                                                                               |

*   **MISURA DELLA TENSIONE**

| Portata (`50Hz ± 5%`) | Risoluzione | Precisione                   |
| :-------------------- | :---------- | :--------------------------- |
| `190 ÷ 460V`          | `1V`        | `± (1.0 % lettura+2digit)` |

*   **MISURA DELLA FREQUENZA**

| Portata         | Risoluzione | Precisione   |
| :-------------- | :---------- | :----------- |
| `47.5 – 52.5Hz` | `0.1Hz`     | `± 0.2Hz`    |

#### 9.1.1 Norme di Sicurezza

*   Lo strumento è conforme alle norme: `IEC / EN61010-1`, `IEC / EN61557-1`
*   Isolamento: Classe 2, Doppio Isolamento
*   Livello di Inquinamento: 2
*   Altezza massima: `2000m`
*   Categoria di Sovratensione: `CAT III 240V` (verso Terra) `CAT III 415V` (tra gli ingressi `P1`, `C1`, `P2`, `C2`)

#### 9.1.2 Normative

Lo strumento esegue le misure in accordo con le seguenti normative:

*   `CEI 64.8 612.6.3`, `IEC / EN61557-3`, `EN60909-0`, `VDE 0413`.

#### 9.1.3 Caratteristiche Generali

*   Dimensioni: `340mm (L) x 300mm (La) mm x 150mm (H)`
*   Peso: circa `4100g` (senza accessori)

**Alimentazione**

*   Tensione: `220 ÷ 415V` nominali (fra gli ingressi `P1` e `P2`)
*   Frequenza: `50Hz ± 5%`

## 9.2 AMBIENTE

### 9.2.1 Condizioni Ambientali

Temperatura di riferimento: `23°C ± 5°C`
Temperatura di utilizzo: `0°C ÷ 40°C`
Umidità relativa ammessa: `<80%RH`
Temperatura di immagazzinamento: `-10°C ÷ 60°C`
Umidità di immagazzinamento: `<80%RH`

Questo strumento è conforme ai requisiti della Direttiva Europea sulla bassa tensione `2006/95/CE` (LVD) e della direttiva `EMC 2004/108/CE`.

### 9.3 ACCESSORI

*   `C7000`: coppia di cavi (`L=3m`) con coccodrilli integrati
*   `C2001`: cavo ottico/RS-232
*   `B80N`: borsa soffice per accessori
*   Certificato di calibrazione `ISO9000`
*   CD-ROM per aggiornamento Firmware dello strumento MASTER
*   Manuale d'uso

## 10 ASSISTENZA

### 10.1 CONDIZIONI DI GARANZIA

Questo strumento è garantito contro ogni difetto di materiale e fabbricazione, in conformità con le condizioni generali di vendita. Durante il periodo di garanzia, le parti difettose possono essere sostituite, ma il costruttore si riserva il diritto di riparare ovvero sostituire il prodotto. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il **trasporto è a carico del Cliente**. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballo originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente. Il costruttore declina ogni responsabilità per danni causati a persone o oggetti. La garanzia non è applicata nei seguenti casi:

*   Riparazione e/o sostituzione accessori (non coperti da garanzia).
*   Riparazioni che si rendono necessarie a causa di un errato utilizzo dello strumento o del suo utilizzo con apparecchiature non compatibili.
*   Riparazioni che si rendono necessarie a causa di un imballaggio non adeguato.
*   Riparazioni che si rendono necessarie a causa di interventi eseguiti da personale non autorizzato.
*   Modifiche apportate allo strumento senza esplicita autorizzazione del costruttore.
*   Utilizzo non contemplato nelle specifiche dello strumento o nel manuale d’uso.

Il contenuto del presente manuale non può essere riprodotto in alcuna forma senza l’autorizzazione del costruttore.

I nostri prodotti sono brevettati e i marchi depositati. Il costruttore si riserva il diritto di apportare modifiche alle specifiche ed ai prezzi se ciò è dovuto a miglioramenti tecnologici.

### 10.2 ASSISTENZA

Se lo strumento non funziona correttamente, prima di contattare il Servizio di Assistenza, controllare lo stato dei cavi e sostituirli se necessario. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il **trasporto è a carico del Cliente**. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballaggio originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente.
