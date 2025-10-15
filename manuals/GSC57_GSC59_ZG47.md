# GSC57 - GSC59 - ZG47

<!-- Language: it -->
<!-- Version: 1.1 -->

<!-- Chunk: Pages 1-32 -->
# 1. PRECAUZIONE E MISURE DI SICUREZZA
## 1.1. GENERALITÀ
Lo strumento è stato progettato in conformità alle direttive EN61557 ed EN 61010-1 relative agli strumenti di misura elettronici.

> **ATTENZIONE**
> Per la Sua sicurezza e per evitare di danneggiare lo strumento, La preghiamo di seguire le procedure descritte nel presente manuale e di leggere con particolare attenzione tutte le note precedute dal simbolo ⚠.
> Prima e durante l’esecuzione delle misure attenersi scrupolosamente alle seguenti indicazioni:

* Non effettuare misure di tensione o corrente in ambienti umidi.
* Non effettuare misure in presenza di gas o materiali esplosivi, combustibili o in ambienti polverosi.
* Evitare contatti con il circuito in esame se non si stanno effettuando misure.
* Evitare contatti con parti metalliche esposte, con terminali di misura inutilizzati, circuiti, ecc.
* Non effettuare alcuna misura qualora si riscontrino anomalie nello strumento come, deformazioni, rotture, fuoriuscite di sostanze, assenza di visualizzazione sul display, ecc.
* Non utilizzare l'alimentatore esterno (codice A0050; opzionale per `GSC57`) qualora si riscontrino deformazioni o rotture nella scatola o danneggiamenti del cavo o della spina.
* Prestare particolare attenzione quando si effettuano misure di tensioni superiori a 25V in ambienti particolari (cantieri, piscine, ..) e 50V in ambienti ordinari in quanto si è in presenza di rischio di shock elettrici.
* Utilizzare solo gli accessori originali HT Italia.

Nel presente manuale sono utilizzati i seguenti simboli:
> ⚠ **Attenzione:** attenersi alle istruzioni riportate nel manuale; un uso improprio potrebbe causare danni allo strumento, ai suoi componenti o creare situazioni pericolose per l’operatore.
>
> **∼** Tensione o Corrente AC.
>
> **⎓** Tensione o Corrente pulsante unidirezionale.
>
> **⏚** Selettore dello strumento.

## 1.2. ISTRUZIONI PRELIMINARI
* Questo strumento è stato progettato per un utilizzo in ambiente con livello di inquinamento 2 fino a 2000m di altitudine.
* Può essere utilizzato per Misure e Prove di Verifica della Sicurezza degli su impianti elettrici con Categoria di Sovratensione III 300V (verso Terra) o Categoria II 350V (verso Terra)
* La invitiamo a seguire le normali regole di sicurezza orientate a:
    * ProteggerLa contro correnti pericolose.
    * Proteggere lo strumento contro un utilizzo errato.

## 1.3. DURANTE L’UTILIZZO
La preghiamo di leggere attentamente le raccomandazioni e le istruzioni seguenti:

> **ATTENZIONE**
> La mancata osservazione delle avvertenze e/o istruzioni può danneggiare lo strumento e/o i suoi componenti o essere fonte di pericolo per l’operatore.

* Prima di azionare il selettore scollegare i puntali di misura dal circuito in esame.
* Quando lo strumento è connesso al circuito in esame non toccare mai alcun terminale, anche se inutilizzato.
* Evitare la misura di resistenza in presenza di tensioni esterne; anche se lo strumento è protetto una tensione eccessiva potrebbe causarne danneggiamenti.
* Durante la misura di corrente, distanziare il più possibile il toroide della pinza dai conduttori non coinvolti dalla misura in quanto il campo magnetico da essi prodotto potrebbe inficiare la misura.
* Durante la misura di corrente posizionare il conduttore il più possibile al centro del toroide in modo da massimizzare la precisione.
* Durante una misura di tensione, corrente ecc. se il valore della grandezza in esame rimane inalterato controllare ed eventuale disabilitare la funzione `HOLD`.

> **ATTENZIONE**
> Il simbolo "⚠" indica il livello di carica. Quando questo è completamente "nero" le batterie sono completamente cariche; il diminuire della zona nera "⚠" indica invece che le batterie sono quasi scariche. In questo caso interrompere le prove e procedere alla sostituzione delle batterie in accordo a quanto descritto nel paragrafo `14.2`. Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie. Le impostazioni di data e ora restano invece inalterate solo se la sostituzione delle batterie viene effettuate entro circa 24 ore.

## 1.4. DOPO L’UTILIZZO
* Quando le misure sono terminate, spegnere lo strumento mantenendo premuto il tasto `ON/OFF` per alcuni secondi.
* Se si prevede di non utilizzare lo strumento per un lungo periodo rimuovere le batterie ed attenersi a quanto specificato nel paragrafo `14.2`.

# 2. DESCRIZIONE GENERALE
## 2.1. INTRODUZIONE
Gentile Cliente, La ringraziamo per aver scelto uno strumento del nostro programma di vendita. Lo strumento da Lei appena acquistato, se utilizzato secondo quanto descritto nel presente manuale, Le garantirà misure accurate ed affidabili. Lo strumento è realizzato in modo da garantirLe la massima sicurezza grazie ad uno sviluppo di nuova concezione che assicura il doppio isolamento e il raggiungimento della categoria di sovratensione III.

Questo manuale si riferisce a due prodotti: `GSC57` e `GSC59`.
Le differenze tra le caratteristiche dei due modelli sono le seguenti:

* Funzione `LOW  10A` eseguibile dal **solo modello `GSC57`**.
* Uso di pinze con toroide flessibile `HTFLEX33` 1000A/3000A, prive di elettronica di controllo propria, disponibili con il **solo modello `GSC59`**.

Dove non espressamente indicato le caratteristiche sono da intendersi identiche per i due modelli.

## 2.2. FUNZIONALITÀ DELLO STRUMENTO
Lo strumento può eseguire le seguenti prove:

* `LOW `: Prova di continuità dei conduttori di terra, di protezione ed equipotenziali con corrente di prova superiore a 200mA e tensione a vuoto compresa tra 4V e 24V.
* `M `: Misura della resistenza di isolamento con tensione continua di prova 50V, 100V, 250V, 500V o 1000V.
* `RCD`: Misura su differenziali generali e/o selettivi di tipo A (~) ed AC (⎓) dei seguenti parametri:
    * Tempo di intervento.
    * Corrente di intervento.
    * Tensione di contatto (`U_t`).
    * Resistenza globale di terra (`R_A`). In questa modalità lo strumento può essere utilizzato per misurare la resistenza globale di terra senza far intervenire l’interruttore differenziale.
* `LOOP`: Misura della impedenza di linea e dell'anello di guasto con calcolo della corrente di cortocircuito presunta. Misura della resistenza globale di terra senza causare l'intervento delle protezioni differenziali (funzione `R_A`).
* `EARTH`: Misura della resistenza di terra e della resistività del terreno tramite picchetti ausiliari.
* `LOW  10A`: Prova di continuità dei conduttore di protezione con una corrente di prova di 10A (solo per `GSC57`).
* `AUX`: Misura e registrazione della corrente di dispersione e dei parametri ambientali (temperatura, umidità, velocità dell'aria, illuminamento e misura di rumore).
* `ANALYZER`: Lo strumento consente le seguenti operazioni:
    * La visualizzazione in tempo reale dei valori delle grandezze elettriche di un impianto monofase e trifase con e senza neutro e dell'analisi armonica della tensione e della corrente.
    * La misurazione nel tempo dei valori dell'energia attiva e reattiva intendendo con misurazione il rilievo in tempo reale (senza possibilità di memorizzazione) dei valori dell'energia. I valori della misura sono disponibili direttamente sul display dello strumento.
    * L’archiviazione nella memoria dello strumento (tramite pressione del tasto `SAVE`) di un record di tipo "Smp" contenente i valori istantanei della tensione e corrente presenti agli ingressi dello strumento. L'analisi dei risultati sarà possibile SOLO trasferendo i dati memorizzati ad un PC.
    * La registrazione (tramite opportuna impostazione) nel tempo dei valori delle tensioni e delle correnti, dei valori delle rispettive armoniche, delle anomalie di tensione con risoluzione 10ms, dei valori delle potenze attive, reattive e apparenti, dei fattori di potenza e `cos `, dei valori delle energie attive e reattive intendendo con registrazione la memorizzazione nella memoria dello strumento dei valori assunti dalle grandezze elettriche nel tempo. L'analisi dei risultati sarà possibile SOLO trasferendo i dati memorizzati ad un PC.
    * La registrazione dei parametri di rete elettrica con utilizzo di configurazioni predefinite allo scopo di aiutare l’operatore nella risoluzione di classici problemi che si verificano negli ambienti industriali (vedere il paragrafo `10.2`) L'analisi dei risultati sarà possibile SOLO trasferendo i dati memorizzati ad un PC.

> **ATTENZIONE**
> Si raccomanda di focalizzare fin d'ora la differenza fra il salvataggio dei risultati visualizzati a display (tramite pressione del tasto `SAVE`) ed una registrazione (che presuppone la memorizzazione automatica da parte dello strumento dei parametri selezionati anche per tempi lunghi).

# 3. PREPARAZIONE ALL’UTILIZZO
## 3.1. CONTROLLI INIZIALI
Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili affinché lo strumento potesse essere consegnato senza danni. Tuttavia si consiglia di controllarlo sommariamente per accertare eventuali danni subiti durante il trasporto. Se si dovessero riscontrare anomalie contattare immediatamente la società HT ITALIA o il rivenditore. Si consiglia inoltre di controllare che l’imballaggio contenga tutte le parti indicate al paragrafo `15.5`. In caso di discrepanze contattare il rivenditore. Qualora fosse necessario restituire lo strumento si prega di seguire le istruzioni riportate al paragrafo `16`.

## 3.2. ALIMENTAZIONE DELLO STRUMENTO
Lo strumento può essere alimentato tramite:
* 6 batterie modello 1.5V – LR6 – AA – AM3 – MN 1500 non incluse dalla confezione. Per l’autonomia delle batterie vedi paragrafo `14.3`.
* L'Alimentatore esterno (codice A0050; opzionale per `GSC57`) utilizzabile solo per le funzioni `AUX` e `ANALYZER`. Si raccomanda di utilizzare solo l'alimentatore originale.

Per salvaguardare la sicurezza dell'operatore è stato inserito un blocco software nelle funzioni di Verifica degli Impianti elettrici (posizioni `LOW `, `M `, `RCD`, `LOOP`, `EARTH` e `LOW  10A`) che impedisce l'avvio della misura qualora venga rilevata la connessione dell'Alimentatore Esterno allo strumento.

La presa di Alimentazione `230V~` presente nel modello `GSC57` va unicamente utilizzata durante le prove di Continuità con corrente di 10A (posizione `LOW  10A`) in quanto le batterie non sarebbero in grado di generare una corrente sufficiente. Per tale funzione è comunque richiesta la presenza delle batterie.

Per l’inserimento delle batterie seguire le indicazioni del paragrafo `14.2`. Il simbolo "⚠" indica il livello di carica. Quando questo è completamente "nero" le batterie sono completamente cariche; il diminuire della zona nera "⚠" indica invece che le batterie sono quasi scariche. In questo caso interrompere le prove e procedere alla sostituzione delle batterie seguendo la procedura descritta nel paragrafo `14.2`. Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie. Le impostazioni di Data e ora restano invece inalterate solo se la sostituzione delle batterie viene effettuate entro circa 24 ore.

> **ATTENZIONE**
> Durante l'esecuzione di una Registrazione in modalità `AUX` o `ANALYZER` si raccomanda di utilizzare sempre l'Alimentatore Esterno (codice A0050; opzionale per `GSC57`) (anche se lo strumento consente l'esecuzione di Registrazioni utilizzando le sole Batterie). Infatti se durante una Registrazione le Batterie dovessero esaurirsi, la registrazione verrebbe terminata (pur non perdendo i Valori memorizzati fino a quel momento). Se viceversa dovesse venire mancare Tensione all'Alimentatore Esterno, lo strumento potrà proseguire la registrazione utilizzando le Batterie. Per questo si raccomanda di inserire sempre un set di Batterie nuove prima dell'inizio di una nuova campagna di registrazioni.

Lo strumento dispone di sofisticati algoritmi per aumentare al massimo l'autonomia delle Batterie. In particolare:
* Lo strumento spegne AUTOMATICAMENTE la retroilluminazione del display dopo circa 5 secondi.
* Al fine di aumentare la durata delle batterie, qualora la Tensione di queste ultime risulti troppo bassa, lo strumento disabilita la funzione di retroilluminazione del display.
* Se lo strumento è in fase di sola Visualizzazione in tempo reale (e non è collegato l'alimentatore esterno), trascorsi circa 5 minuti dall'ultima pressione del tasto o rotazione del commutatore, lo strumento avvierà la procedura di auto-spegnimento ("`AUTOPOWER OFF`").
* Se lo strumento è in fase di Registrazione o di Misura di energia (e non è collegato l'alimentatore esterno), trascorsi circa 5 minuti dall'ultima pressione del tasto o rotazione del commutatore, lo strumento avvierà la procedura di risparmio Batterie ("`ECONOMY MODE`") ovvero verrà spento il display mentre lo strumento continuerà a registrare.

## 3.3. TARATURA
Lo strumento rispecchia le caratteristiche tecniche riportate nel presente manuale. Le sue prestazioni sono garantite per un anno dalla data di acquisto.

## 3.4. IMMAGAZZINAMENTO
Per garantire misure precise, dopo un lungo periodo di permanenza in magazzino in condizioni ambientali estreme, attendere che lo strumento ritorni alle condizioni normali (vedi specifiche ambientali elencate al paragrafo `15.4`).

# 4. DESCRIZIONE DELLO STRUMENTO

```
SAVE F1 F3 F4 F2 HOLD ENTER MENU ESC START STOP
1 2 3
LEGENDA:
1. Display
2. Tasti Funzione
3. Selettore Rotativo
```

* Tasti Multifunzione.
* Tasto `ON/OFF` e `Backlight`. Mantenere premuto il tasto per alcuni secondi per spegnere lo strumento. Premere questo tasto brevemente per attivare il `Backlight`.
* Questo tasto Avvia (ed eventualmente Arresta) le misure.
* Questo tasto consente la memorizzazione dei risultati visualizzati.
* Questo tasto abilita la funzione `HOLD`. Il medesimo tasto all'interno della modalità Menu consente la conferma dei Parametri inseriti.
* Questo tasto consente l'accesso al Menu di configurazione dello strumento.
* Questo tasto consente di Uscire dalla modalità selezionata.

```
F1 START STOP
HOLD ENTER MENU
F2 F4 F3 ON/OFF SAVE ESC
```

## 4.1. DESCRIZIONE DEL DISPLAY
Il display é un modulo grafico con risoluzione 128 x 128 punti. Nella prima riga del display viene visualizzata la data e ora dello strumento. Se non è corretta si veda la procedura per l'impostazione riportata nel paragrafo `5.2`. Nell'angolo alto-destra del display è sempre visualizzato l'indicatore dello stato batterie od il simbolo della presenza dell'alimentatore esterno.

```
LOW  05.06.02 27.09.02 17:35:12
---- 
R+ R- ----  ---- 
---mA ---mA AUTO 0.11 
TENSIONE V1 = 230.2 V V2 = 230.5 V V3 = 230.6 V
V12 = 384.2 V V23 = 385.4 V V31 = 383.7 V
freq = 50.0 Hz Phseq = 123
FUNZ CAL HARM WAVE PG- PG+
```
Per brevità tali simboli saranno omessi nelle successive videate illustrate nel presente manuale.

## 4.2. VIDEATA INIZIALE
Accendendo lo strumento tramite il tasto `ON/OFF` lo strumento visualizza per qualche secondo una delle seguenti videate (a seconda del modello):

```
GSC 53N HT ITALIA SN:00000000 V: X.XX Baud Rate 57600 DATA DI CALIBRAZIONE 01.01.02
GSC 57 HT ITALIA SN:00000000 V: X.XX Baud Rate 57600 DATA DI CALIBRAZIONE 01.01.02
ZG 47 HT ITALIA SN:00000000 V: X.XX Baud Rate 57600 DATA DI CALIBRAZIONE 01.01.02
```
In essa sono visualizzati (oltre al costruttore ed al modello dello strumento):
* Il numero di Serie dello strumento (`SN:`).
* La versione del Software presente nella memoria dello strumento (`V:`).
* La data in cui è avvenuta la calibrazione (`DATA DI CALIBRAZIONE:`).
* La velocità di Trasmissione tramite seriale (`Baud Rate`).
Premere `ESC` per uscire da questa videata.

## 4.3. RETROILLUMINAZIONE
Durante il funzionamento dello strumento una ulteriore breve pressione del tasto `ON` accende la retroilluminazione del display (se il livello della Tensione delle Batterie è sufficientemente alto). Al fine di salvaguardare l’efficienza delle batterie la retroilluminazione si spegne automaticamente dopo circa 5 secondi. L'utilizzo sistematico della retroilluminazione diminuisce l'Autonomia delle Batterie.

# 5. IMPOSTAZIONI INIZIALI
Premendo il tasto `MENU` (quando lo strumento non è in fase di registrazione) appare la seguente videata:

```
MENU GENERALE
MEMORIA SAFETY TEST
MEMORIA ANALYZER
RESET
CONFIG ANALYZER
CONFIG RECORDER
CONTRASTO
DATA&ORA
LINGUA
 
```
Non è possibile accedere a questa videata durante una registrazione. La pressione del tasto `MENU` durante una registrazione attiva la visualizzazione dei principali parametri di registrazione (vedi paragrafo `10.3.1`).

## 5.1. REGOLAZIONE DEL CONTRASTO
Posizionare il cursore sulla voce corrispondente utilizzando i tasti `F1` e `F2` e, premere `ENTER`. Impostare il valore desiderato. Valori elevati corrispondono ad un contrasto più elevato mentre valori bassi corrispondono ad un minor contrasto. Per memorizzare le impostazioni effettuate premere il tasto `ENTER`. Le impostazioni effettuate rimarranno valide anche dopo lo spegnimento dello strumento. Per abbandonare le modifiche effettuate premere il tasto `ESC`.

## 5.2. REGOLAZIONE DATA E ORA
Posizionare il cursore sul simbolo corrispondente utilizzando i tasti `F1` e `F2` e premere il tasto `ENTER`. Per aggiornare la Data corrente posizionare il cursore sulla cifra da modificare e premere `F3` / `F4` per cambiare il valore della cifra. L’ora è espressa nel formato: `hh:mm` (2 cifre per l’ora, 2 cifre per i minuti) Per memorizzare le impostazioni effettuate premere il tasto `ENTER`. Le impostazioni effettuate rimarranno valide anche dopo lo spegnimento dello strumento. Per abbandonare le modifiche effettuate premere il tasto `ESC`.

## 5.3. IMPOSTAZIONE DELLA LINGUA
Posizionare il cursore sulla voce corrispondente utilizzando i tasti `F1` e `F2` e, confermare con `ENTER`. Selezionare poi la lingua desiderata tramite i tasti `F1` e `F2`. Per memorizzare le impostazioni effettuate premere il tasto `ENTER`. Le impostazioni effettuate rimarranno valide anche dopo lo spegnimento dello strumento. Per abbandonare le modifiche effettuate premere il tasto `ESC`.

## 5.4. RESET
Questa funzione ripristina le impostazioni iniziali dello strumento per la funzione `ANALYZER`. Questa configurazione consente all’operatore di inserire nello strumento una tipica situazione generalmente in grado di soddisfare le richieste per un’analisi di rete. Il comando `RESET` ripristina il valore limite per la misura di isolamento (vedere paragrafo `6.2`) a `0.5M` e la tensione di prova a `500V`. Le voci “non modificato” non sono interessate dal comando `RESET`. Le impostazioni della configurazione sono le seguenti:

* `CONFIG ANALYZER`:
    * Sistema: 4 fili
    * Frequenza: non modificata
    * Fondo scala delle Pinze: non modificato
    * Tipo Pinze: non modificato
    * Rapporto di Trasformatori Voltmetrici: 1
    * Password: `OFF`
* `CONFIG RECORDER`:
    * Start: `MANU` (la registrazione si avvia all’inizio del minuto successivo alla pressione del tasto `START/STOP`)
    * Stop: `MANU`
    * Periodo di Integrazione: 15min
    * Registrazione delle Armoniche: `ON`
    * Registrazione delle anomalie di Tensione: `ON`
    * Tensione di Riferimento per le Anomalie di Tensione: 230V
    * Limite superiore per le anomalie di Tensione: 6%
    * Limite Inferiore per le anomalie di Tensione: 10%
    * Tensioni selezionate: V1, V2, V3
    * Armoniche di Tensione : `THD`, 01, 03, 05, 07
    * Correnti selezionate: I1, I2, I3, IN
    * Armoniche di corrente: `THD`, 01, 03, 05, 07
    * `CO-GENERAZIONE`: `OFF`
    * Potenze, Pf e `cos `:: Pt, P1, P2, P3 Qti, Q1i, Q2i, Q3i Qtc, Q1c, Q2c, Q3c St, S1, S2, S3 Pft, Pf1, Pf2, Pf3 dpft, dpf1, dpf2, dpf3
    * Energie: Eat, Ea1, Ea2, Ea3 Erit, Eri1, Eri2, Eri3 Erct, Erc1, Erc2, Erc3

Il comando di `RESET` NON cancella il contenuto della MEMORIA dello strumento.

# 6. PROVE DI VERIFICA DEGLI IMPIANTI ELETTRICI
## 6.1. `LOW `: VERIFICA DELLA CONTINUITÀ DEI CONDUTTORI DI PROTEZIONE CON UNA CORRENTE DI PROVA DI 200mA
La misura viene eseguita secondo le norme CEI 64.8 61.3.2 e VDE 0413 parte 4.

> **ATTENZIONE**
> Prima di effettuare la prova di Continuità accertarsi che non ci sia tensione ai capi del conduttore da analizzare.
> Ruotare il selettore in posizione `LOW `. Con il tasto `F1` è possibile selezionare una delle seguenti modalità di misura (che si presentano ciclicamente alla pressione del tasto):

* Modalità “`AUTO`” (lo strumento effettua due misure a polarità invertita e visualizza il valor medio tra le due). Modalità consigliata per la prova di continuità.
* Modalità “`RT+`” (misura con polarità positiva e con la possibilità di impostare un tempo di durata della prova). In questo caso l’operatore può impostare un tempo di misura sufficientemente lungo per poter muovere i conduttori di protezione mentre lo strumento sta eseguendo la prova al fine di poter individuare una eventuale cattiva connessione.
* Modalità “`RT-`” (misura con polarità negativa e con la possibilità di impostare un tempo di durata della prova). In questo caso l’operatore può impostare un tempo di misura sufficientemente lungo per poter muovere i conduttori di protezione mentre lo strumento sta eseguendo la prova al fine di poter individuare una eventuale cattiva connessione.
Con il tasto `F2` è possibile selezionare la Modalità “`CAL`” (compensazione della resistenza dei cavi utilizzati per la misura).

> **ATTENZIONE**
> La prova di continuità è eseguita erogando una corrente superiore a 200mA nel caso in cui la resistenza sia non superiore a `5 ` (compresa la resistenza dei cavi di misura memorizzata come offset nello strumento dopo aver eseguito la procedura di calibrazione). Per valori di resistenza superiori lo strumento esegue la prova con una corrente inferiore a 200mA.

### 6.1.1. Modalità "`CAL`"
1. Inserire il cavo Nero ed il cavo Blu nei rispettivi terminali di ingresso `B1` e `B4` dello strumento:
   ```
   B2 B3 B4 B1
   ```
   Connessione dei terminali dello strumento durante la procedura di calibrazione.
2. Se, ai fini della misura da effettuare, la lunghezza dei cavi in dotazione fosse insufficiente prolungare il cavo blu.
3. Inserire due coccodrilli nelle terminazioni dei cavi.
4. Cortocircuitare le terminazioni dei cavi di misura avendo cura che le parti conduttrici dei coccodrilli effettuino un buon contatto reciproco (vedi figura precedente).
5. Premere il tasto `F2`. Lo strumento esegue la calibrazione.

> **ATTENZIONE**
> Non scollegare mai i terminali dai punti di misura quando lo strumento visualizza il messaggio "`MISURA…`".

```
LOW  05.06.02
---- 
R+ R- ----  ---- 
---mA ---mA AUTO 0.11 
Questo valore Numerico indica che la Calibrazione è stata effettuata.
FUNZ CAL
```
6. Al termine della misura lo strumento emette un doppio segnale acustico ad indicare che la calibrazione è avvenuta correttamente. Il valore della Calibrazione viene aggiornato e visualizzato sopra il tasto `F2`. Tale valore rimarrà memorizzato anche in caso di spegnimento dello strumento.

**Nota**: lo strumento effettua la calibrazione dei cavi di misura solo se la resistenza di questi ultimi è inferiore a `5 `.

**CAVI UTILIZZATI PER LA MISURA**
Accertarsi sempre, prima di ogni misura, che la calibrazione sia riferita ai cavi utilizzati al momento. In una misura di continuità se il valore di resistenza depurato dalla calibrazione (cioè valore della resistenza meno il valore dell'offset della calibrazione) risultasse **negativo**, verrebbe visualizzato il simbolo `` e il simbolo `CAL` lampeggiante (vedi quinta videata paragrafo `6.1.5`). Probabilmente la calibrazione memorizzata nello strumento è riferita a cavi diversi da quelli in uso, pertanto deve essere eseguita una nuova calibrazione.

#### 6.1.1.1. Procedura per Cancellare il Parametro di Calibrazione ed il Simbolo Cal
* Per cancellare il parametro di calibrazione occorre effettuare una procedura di calibrazione con una resistenza ai puntali superiore a `5 ` (ad esempio con i puntali aperti). Quando si esegue una cancellazione viene visualizzata la videata a lato.

```
LOW  05.06.02
Messaggio >99.9 : indica che lo strumento ha rilevato una resistenza superiore a 99.9  ( e quindi superiore anche a 5  ).
 > 99.9 
R+ R- ----  ---- 
---mA ---mA AUTO 0.11 
FUNZ CAL
```

### 6.1.2. Procedura di misura
1. Selezionare con il tasto `F1` la modalità che interessa.
2. Inserire il cavo Nero ed il cavo Blu nei rispettivi terminali di ingresso `B1` ed `B4` dello strumento:
   ```
   B2 B3 B4 B1
   ```
   Connessione dei terminali dello strumento prova `LOW `.
3. Se ai fini della misura da effettuare la lunghezza dei cavi in dotazione è insufficiente prolungare il cavo blu.
4. Inserire due coccodrilli nelle terminazioni dei cavi.
5. Cortocircuitare le terminazioni dei cavi di misura avendo cura che le parti conduttrici dei coccodrilli effettuino un buon contatto reciproco. Premere il tasto `START`. Se lo strumento visualizza un valore di resistenza diverso da 0,00 ripetere la calibrazione dello strumento (vedi paragrafo `6.1.1`).
6. Collegare i terminali dello strumento ai capi del conduttore di cui si desidera effettuare la prova di continuità (vedi figura sopra).
7. Se è stata selezionata la modalità "`RT+`" o "`RT-`" utilizzare i tasti `F3`, `F4` per selezionare il Tempo di Prova.
8. Premere il tasto `START`. Lo strumento esegue la misura. In modalità "`RT+`" o "`RT-`" premere nuovamente il tasto `START` per arrestare la prova.

> **ATTENZIONE**
> La visualizzazione del messaggio "`MISURA…`" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.
> ```
> START STOP
> ```

### 6.1.3. Risultati modalità "`AUTO`"
* Al termine della prova, nel caso in cui il valore medio della resistenza `Ravg` rilevata risulti inferiore a `5 `, lo strumento emette un doppio segnale acustico che segnala l'esito positivo della prova e visualizza una videata tipo quella a fianco.

```
LOW  05.06.02
Valor medio della resistenza Ravg.
1.05 
R+ R- 1.07  1.03 
219mA 219mA AUTO 0.11 
Valore della corrente di prova.
FUNZ CAL
```
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE` (vedi paragrafo `9.1`).

### 6.1.4. Modalità "`RT+`" o “`RT-`"
* Durante la prova lo strumento emette un segnale acustico qualora il valore della resistenza sia superiore a 99.9. Se, al termine della prova, il valore massimo della Resistenza `RT+` o `RT-` è inferiore a `5 `, lo strumento, emette un doppio segnale acustico che segnala l’esito positivo della prova e visualizza una videata tipo quella a fianco.

```
LOW  05.06.02
Valore Massimo della Resistenza misurato rilevato durante la prova.
1.07 
219mA RT+ 0.11  TIME: 10s
Corrente di Prova Durata della Prova
FUNZ CAL  
```
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE` (vedi paragrafo `9.1`).

### 6.1.5. Situazioni anomale modalità "`AUTO`", "`RT+`", "`RT-`"
* Se alla pressione del tasto `START`, lo strumento rileva la connessione all'alimentatore esterno, visualizza il messaggio indicato a lato.

```
LOW  05.06.02
-.- - 
R+ R- ---  --- 
---mA ---mA
 TOGLI ALIM. AUTO 0.11 
Per motivi di sicurezza, lo strumento non esegue le prove di Verifica qualora sia collegato l'alimentatore esterno. Per eseguire la prova disconnettere l'alimentatore
FUNZ CAL
```

* Se lo strumento rileva la presenza di una Tensione superiore a circa 15V presente ai terminali di ingresso, visualizza il messaggio indicato a lato.

```
LOW  05.06.02
-.- - 
R+ R- -.--  -.-- 
---mA ---mA
 VOLT IN INGRESSO AUTO 0.11 
La prova non può essere eseguita perché è stata rilevata una Tensione agli Ingressi dello strumento.
FUNZ CAL
```

* Se lo strumento rileva che: `R CALIBRAZIONE > R MISURATA` viene visualizzato il messaggio a lato.

```
LOW  05.06.02
 0.00 
R+ R- 0.00  0.00 
219mA 219mA
 CAL > RES AUTO 0.11 
```
> **ATTENZIONE:**
> `R CALIBRAZIONE >R MISURATA`
> I PRECEDENTI RISULTATI NON POSSONO ESSERE MEMORIZZATI.

* Nel caso in cui sia stata rilevata una Resistenza superiore o uguale a `5 ` ma inferiore a `99,9 `, lo strumento, a fine prova, emette un segnale acustico prolungato e visualizza una videata tipo quella a fianco.

```
LOW  05.06.02
 5.17 
R+ R- 5.17  5.17 
209mA 209mA AUTO 0.11 
Resistenza superiore a 5 
Corrente di Prova
FUNZ CAL
```
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE` (vedi paragrafo `9.1`).

* Nel caso in cui sia stata rilevata una Resistenza superiore a `99,9 `, lo strumento, a fine prova, emette un segnale acustico prolungato e visualizza una videata tipo quella a fianco.

```
LOW  05.06.02
Resistenza di Valore Superiore a 99.9 
 > 99.9 
R+ R- -.--  -.-- 
---mA ---mA AUTO 0.11 
ATTENZIONE: Valore di Resistenza fuori Range
FUNZ CAL
```
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE` (vedi paragrafo `9.1`).

## 6.2. `M `: MISURA DELLA RESISTENZA DI ISOLAMENTO CON TENSIONE DI PROVA 50V, 100V, 250V, 500V o 1000V
La misura viene eseguita secondo le norme CEI 64.8 61.3.3 e VDE 0413 parte 1.

> **ATTENZIONE**
> Prima di effettuare la prova di isolamento accertarsi che il circuito in esame non sia alimentato e che tutti i carichi da esso derivati siano scollegati.
> Ruotare il selettore in posizione `M `. Con il tasto `F1` è possibile selezionare una delle seguenti modalità di misura (che si presentano ciclicamente alla pressione del tasto):

* Modalità “`MAN` “ (tempo di prova determinato dalla durata della pressione del tasto `START`). Prova consigliata.
* Modalità “`TIMER`” (durata della prova che dipende dall'intervallo selezionato (da 10 a 999 secondi). Questa prova può essere eseguita nel caso in cui venga richiesto un tempo minimo di misura.

### 6.2.1. Procedura di misura
1. Selezionare con il tasto `F1` la modalità desiderata.
2. Inserire i cavi di misura nei terminali di ingresso `B1` e `B4` dello strumento:
   ```
   M B2 B3 B4 B1 I1 I2 I3
   ```
   Esempio di utilizzo dello strumento per la verifica di isolamento fra fase e terra in un impianto elettrico utilizzando i cavi separati
   ```
   B2 B3 B4 B1 I1 I2 I3
   ```
   Esempio di utilizzo dello strumento per la verifica di isolamento fra fase e terra in un impianto elettrico utilizzando il cavo `C2033`
3. Se ai fini della misura da effettuare la lunghezza dei cavi in dotazione fosse insufficiente prolungare il cavo blu.
4. Collegare i terminali dello strumento sull’oggetto su cui si intende effettuare la prova di isolamento avendo preventivamente scollegato dall'alimentazione il circuito in esame e tutti gli eventuali carichi derivati da esso (vedi figure precedenti).
5. Selezionare con `F2` la tensione di prova adeguata al tipo di prova che si deve eseguire (vedi Tabella 1). I valori che si possono selezionare sono:
    * 50V (prove su sistemi per telecomunicazioni)
    * 500V
    * 100V
    * 1000V
    * 250V

| Normativa | Breve Descrizione | Tensione di Prova | Valore Minimo Ammesso |
| :-------- | :---------------- | :---------------- | :-------------------- |
| CEI 64-8/6 | Sistemi SELV o PELV | 250VDC | > 0.250 M |
|           | Sistemi fino a 500V (Imp. Civili) | 500VDC | > 0.500 M |
|           | Sistemi oltre i 500V | 1000VDC | > 1.00 M |
| CEI 64-8/4 | Isol. Pav. e pareti Imp. Civili | 500VDC | > 0.05 M (se V < 500V) |
|           | Isol. Pav. e pareti in sistemi oltre 500V | 1000VDC | > 0.1 M (se V > 500V) |
| EN60439   | Quadri Elettrici 230/400V | 500VDC | > 0.23 M |
| EN60204   | Equipaggiamento Elettrico delle Macchine | 500VDC | > 1.00 M |

Tabella 1: Tabella riassuntiva dei valori delle tensioni di prova e relativi valori limite ammessi per le tipologie di prova più comuni.

| Tensione Nominale Selezionata per la prova | `R MAX` = valore massimo di resistenza misurabile |
| :----------------------------------------- | :--------------------------------------------- |
| 50VDC | 99,9M |
| 100VDC | 199,9M |
| 250VDC | 499M |
| 500VDC | 999M |
| 1000VDC | 1999M |

Tabella 2: Tabella dei valori massimi di resistenza che lo strumento misura in modo `M ` in funzione della tensione nominale selezionata.
6. Utilizzando i tasti `F3`, `F4` selezionare il limite minimo per l’isolamento tra i seguenti valori: `0.05M`, `0.1M`, `0.23M`, `0.25M`, `0.50M`, `1.00M`, `100M` in accordo a quanto indicato nella Tabella 1.

> **ATTENZIONE**
> Il valore limite impostato nella modalità “`MAN`” è usato anche nella modalità “`TIMER`” sebbene non sia presente il messaggio “`LIM`” a display.
7. Se è stata selezionata la modalità "`TIMER`" utilizzare i tasti `F3`, `F4` per impostare il tempo di durata della prova:

> **ATTENZIONE**
> La visualizzazione del messaggio "`MISURA…`" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento dal punto di misura in quanto il circuito in esame potrebbe rimanere carico ad una tensione pericolosa a causa delle capacità parassite dell’impianto. Qualunque sia il modo di funzionamento selezionato, lo strumento, nella parte finale di ogni prova, inserisce una resistenza ai terminali di uscita per effettuare la scarica delle capacità parassite presenti nel circuito.
8. Premere il tasto the `START`. Lo strumento avvierà la prova:
    * Modalità `MAN`: La prova dura al Massimo 4 secondi. Per prolungare la durata della stessa mantenere premuto il tasto `START` per il tempo desiderato.
    * Modalità `TMR`: La prova verrà eseguita per il tempo impostato. Per interromperla premere nuovamente il tasto `START`.
    ```
    START STOP
    ```

### 6.2.2. Modalità "`MAN`"
* Al termine della prova, se il valore della resistenza rilevata risulta inferiore a `R MAX` (che dipende dalla tensione selezionata vedi Tabella 2), superiore al valore limite impostato e la prova viene eseguita alla tensione nominale impostata, lo strumento emette un doppio segnale acustico e il messaggio “`OK`” che segnala che la prova è stata eseguita correttamente e visualizza una videata simile a quella a fianco.

```
M  05.06.02
Resistenza di Isolamento
1.07 M 
514V 15s
Tensione di Prova applicata Durata della Prova Modalità di Prova
OK
MAN 500V LIM: 0.50M
Limite di misura impostato
FUNZ VNOM  
Tensione di Prova Nominale
```
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE` (vedi paragrafo `9.1`).

* Nel caso in cui sia stata rilevata una Resistenza superiore alla `R MAX` misurabile dallo strumento (che dipende dalla tensione selezionata, vedi Tabella 2) lo strumento, a fine prova, emette un doppio segnale acustico e il messaggio “`OK`” che segnala l'esito positivo della stessa e visualizza una videata simile a quella di fianco.

```
M  05.06.02
Resistenza di Isolamento. Il simbolo ">" indica che la resistenza di Isolamento è superiore al Valore Massimo misurabile (vedi Tabella 2).
> 999 M 
523V 15s Durata del Test
OK
MAN 500V LIM: 0.50M
FUNZ VNOM  
```
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE` (vedi paragrafo `9.1`).

### 6.2.3. Modalità "`TMR`" (Timer)
* Al termine della prova, se il valore della resistenza rilevata risulta inferiore a `R MAX` (che dipende dalla tensione selezionata, vedi Tabella 2), superiore al valore limite impostato e la prova viene eseguita alla tensione nominale impostata, lo strumento emette un doppio segnale acustico e il messaggio “`OK`” che segnala che la prova è stata eseguita correttamente e visualizza una videata tipo quella a fianco.

```
M  05.06.02
Resistenza di Isolamento
1.07 M 
514V 60s
Tensione di Prova Applicata Durata del Test Modalità di Prova
OK
TMR 500V TIME:60s
FUNZ VNOM  
Tempo di Prova impostato
```
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE` (vedi paragrafo `9.1`).

* Nel caso in cui sia stata rilevata una Resistenza superiore alla `R MAX` misurabile dallo strumento (che dipende dalla tensione selezionata, vedi Tabella 2), lo strumento a fine prova emette un doppio segnale acustico e il messaggio “`OK`” che segnala l'esito positivo della stessa e visualizza una videata tipo quella a fianco.

```
M  05.06.02
Resistenza di Isolamento. Il simbolo ">" indica che la resistenza di Isolamento è superiore al Valore Massimo misurabile (vedi Tabella 2).
> 999 M 
523V 60s
Durata del Test
OK
TMR 500V TIME:60s
FUNZ VNOM  
```
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE` (vedi paragrafo `9.1`).

### 6.2.4. Situazioni anomale modalità "`MAN`", "`TMR`"
* Se alla pressione del tasto `START` lo strumento rileva la connessione all'alimentatore esterno, visualizza il messaggio indicato a lato.

```
M  05.06.02
-.- - M 
---V 15s
 TOGLI ALIM MAN 500V LIM:0.50M
Per motivi di sicurezza, lo strumento non esegue le prove di Verifica qualora sia collegato l'alimentatore esterno. Per eseguire la prova disconnettere l'alimentatore.
FUNZ VNOM  
```

* Se lo strumento rileva una Tensione presente ai terminali di ingresso superiore a circa 15V, visualizza il messaggio indicato a lato.

```
M  05.06.02
-.- - M 
---V 15s
 VOLT IN INPUT MAN 500V LIM:0.50M
La prova non può essere eseguita perché è stata rilevata una Tensione agli Ingressi dello strumento.
FUNC VNOM  
```
I PRECEDENTI RISULTATI NON POSSONO ESSERE MEMORIZZATI.

* Nel caso in cui sia stata eseguita la prova ad una tensione inferiore a quella nominale impostata lo strumento a fine prova emette un segnale acustico prolungato e il messaggio “`NON CORRETTO`” e visualizza una videata tipo quella a fianco.

```
M  05.06.02
Resistenza di Isolamento
 1.17 M 
107V 15s
Il simbolo Attenzione segnala che la prova è stata effettuata ad una Tensione inferiore al Valore Nominale Impostato.
Tempo di Prova
NON CORRETTO
MAN 500V LIM:0.50M
FUNC VNOM  
```

* Nel caso in cui sia stata eseguita la prova ad una tensione superiore a quella nominale impostata e il valore misurato sia inferiore al limite minimo impostato lo strumento a fine prova emette un segnale acustico prolungato e il messaggio “`NON CORRETTO`” e visualizza una videata tipo quella a fianco.

```
M  05.06.02
Resistenza di Isolamento
0.22 M 
504V 15s Tempo di Prova
NON CORRETTO Limite di misura impostato
MAN 500V LIM:0.50M
FUNC VNOM  
```
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE` (vedi paragrafo `9.1`).

## 6.3. `RCD`: PROVE SU INTERRUTTORI DIFFERENZIALI DI TIPO A E AC
La prova viene eseguita secondo le norme CEI 64.8 61.3.6.1, EN61008, EN61009, EN60947-2 punto B 4.2.4.1 e VDE 0413 parte 6.

> **ATTENZIONE**
> La verifica di un interruttore differenziale comporta l'intervento della Protezione stessa. Verificare pertanto che a valle della protezione differenziale in esame NON siano allacciate utenze o carichi che possano risentire dalla messa fuori servizio dell'impianto. Se possibile, scollegare tutti i carichi allacciati a valle dell'interruttore differenziale in quanto potrebbero introdurre correnti di dispersione aggiuntive a quelle fatte circolare dallo strumento, invalidando così i risultati della prova.
> Ruotare il selettore in posizione `RCD`. Con il tasto `F1` è possibile selezionare una delle seguenti modalità di misura (che si presentano ciclicamente alla pressione del tasto):

* Modalità “`AUTO`” (lo strumento effettua in automatico la prova con corrente di dispersione pari a metà, a una volta, a cinque volte il valore della corrente nominale impostata). Modalità consigliata per la prova dei differenziali.
* Modalità “`x ½`” (lo strumento effettua la prova con corrente di dispersione pari a metà del valore della corrente nominale impostata).
* Modalità “`x 1`” (lo strumento effettua la prova con corrente di dispersione pari a una volta il valore della corrente nominale impostata).
* Modalità “`x 2`” (lo strumento effettua la prova con corrente di dispersione pari a due volte il valore della corrente nominale impostata).
* Modalità “`x 5`” (lo strumento effettua la prova con corrente di dispersione pari a cinque volte il valore della corrente nominale impostata).
* Modalità “`⎓`” (lo strumento effettua la prova con corrente di dispersione crescente. Questa prova deve essere utilizzata quando si vuole determinare l’effettiva corrente di intervento dell’interruttore differenziale).
* Modalità "`R_A`" (lo strumento effettua la prova con corrente di dispersione pari a metà del valore della corrente nominale impostata al fine di non fare intervenire l’interruttore differenziale e misurando la tensione di contatto e la resistenza di Globale di Terra).

N.B. Lo strumento è in grado di generare una corrente avente forma d'onda del tipo "0°" o del tipo "180°" (ossia con fase iniziale di 0° e 180° rispettivamente.

| Tipo RCD | Forma d'onda "0°" | Forma d'onda "180°" |
| :------- | :---------------- | :------------------ |
| AC       | (simbolo ⎓)       |                     |
| A        | (simbolo ~)       |                     |

La pratica suggerisce di effettuare la prova del differenziale sia a 0° che a 180° al fine di individuare il tempo di intervento più elevato, ossia il caso peggiore. Se poi il differenziale in esame è di tipo A (ossia sensibile a correnti di dispersione sia alternate che unidirezionali pulsanti) è opportuno eseguire la prova sia con corrente sinusoidale che con corrente unidirezionale pulsante a 0° e 180°. La modalità `AUTO` esegue la prova del differenziale alternando ad una corrente del tipo "0°" una corrente del tipo "180°".
Con il tasto `F2` è possibile selezionare una delle seguenti correnti nominali di intervento dell'interruttore differenziale (che si presentano ciclicamente alla pressione del tasto):

* 10mA.
* 30mA.
* 100mA.
* 300mA.
* 500mA.
Con il tasto `F3` è possibile selezionare il tipo di differenziale in esame:

* "``": RCD Generale tipo AC (correnti disperse sinusoidali)
* "``": RCD Selettivo tipo AC (correnti disperse sinusoidali)
* "``": RCD Generale tipo A (correnti disperse unidirezionali-pulsanti)
* "``": RCD Selettivo tipo A (correnti disperse unidirezionali-pulsanti)

N.B. In accordo con la normativa EN61008 la prova per interruttori differenziali selettivi comporta un intervallo fra le prove di 60 secondi (30 secondi nel caso di prove a `½ In`). Sul display dello strumento viene visualizzato un timer che indica il tempo da attendere prima che lo strumento possa effettuare automaticamente la prova.

N.B. Selezionando la modalità "`Selettivi` ``" NON sono disponibili le modalità di prova a Rampa “`⎓`” e "`R_A`".
Esempio: prova `AUTO` su un interruttore differenziale con corrente nominale `In` 30mA.
a) lo strumento esegue la prova a `½ In` 0°. Se il differenziale supera la prova compare il valore “>999ms” e il differenziale non interviene.
b) lo strumento esegue la prova a `½ In` 180°. Se il differenziale supera la prova compare il valore “>999ms” e il differenziale non interviene. Se il differenziale in esame è un Selettivo viene visualizzato un Timer che fa trascorrere 30 secondi prima che di eseguire la prova successiva.
c) lo strumento esegue la prova a `In` 0°. Il differenziale deve intervenire e lo strumento visualizza il valore del tempo di intervento ed il messaggio "`RIARMO RCD`". Se il differenziale in esame è un Selettivo viene visualizzato un Timer che farà trascorrere 60 secondi prima di eseguire la prova successiva.
d) lo strumento esegue la prova a `In` 180°. Eseguire la stessa procedura descritta al passo c).
e) lo strumento esegue la prova a `5In` 0°. Eseguire la stessa procedura descritta al passo c).
f) lo strumento esegue la prova a `5In` 180°. Eseguire la stessa procedura descritta al passo c). La prova è terminata.
Con il tasto `F4` è possibile selezionare uno dei seguenti valori limite per la tensione di contatto (che si presentano ciclicamente alla pressione del tasto):

* 50V (default)
* 25V

> **ATTENZIONE**
> La visualizzazione del messaggio "`MISURA…`" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

### 6.3.1. Tempi di intervento per gli interruttori di tipo generale e selettivo
* Tabella dei tempi di intervento per le prove `IN x1`, `IN x2`, `IN x5` e `AUTO`.
Se i parametri impostati sullo strumento sono coerenti con il tipo di protezione differenziale in esame (e se quest'ultima funziona correttamente) la prova con corrente di dispersione `IN x1`, `IN x2`, `IN x5` DEVE causare l'intervento dell'interruttore differenziale entro i tempi prefissati, descritti nella seguente tabella:

| Tipo differenziale | `IN x 1` | `IN x 2` | `IN x 5` | Descrizione                       |
| :----------------- | :-------- | :-------- | :-------- | :-------------------------------- |
| Generale           | 0,3s      | 0,15s     | 0,04s     | Tempo di intervento max in secondi |
| Selettivo S        | 0,5s      | 0,20s     | 0,15s     | Tempo di intervento max in secondi |
|                    | 0,13s     | 0,05s     | 0,05s     | Tempo di non intervento min in secondi |

Per valori nominali `IN  30mA` la corrente di prova a 5 volte è 0,25A. Per correnti pari a `½ IN` il differenziale non deve intervenire in nessun caso.
Tabella 3: Tabella dei tempi di intervento per prove con correnti di dispersione `IN x1`, `IN x2`, `IN x5` e `AUTO`.

* Prove a Rampa "`⎓`".
Questa prova non viene di solito eseguita per confrontare il tempo di intervento dell’interruttore con i limiti normativi. Lo strumento in questa modalità rileva l’esatta corrente e il tempo di intervento del differenziale alla corrente di intervento, invece la normativa fa riferimento a tempi massimi di intervento nel caso in cui il differenziale sia provato con una corrente di dispersione pari alla corrente nominale. Il valore limite della corrente di Intervento del Dispositivo Differenziale è riportato nella seguente Tabella:

| Tipo differenziale | `IN  z` | `IN > 10mA` |
| :----------------- | :-------- | :----------- |
| A                  | 2,0 x `IN` | 1,4 x `IN`  |
| AC                 | `IN`     | `IN`        |

Tabella 4: Valore limite della corrente di intervento per la Prova a "`Rampa`".

### 6.3.2. Procedura di misura
1. Selezionare i parametri desiderati tramite il tasti `F1`, `F2`, `F3`, `F4`.
2. Inserire i 3 connettori Verde, Blu e Nero del cavo shuko a tre terminali o dei cavi separati nei corrispondenti terminali di ingresso dello strumento `B1`, `B3`, `B4` (vedi possibili connessioni nelle figure seguenti). Nel caso di utilizzo dei cavi separati inserire all'estremità dei cavi rimasta libera i coccodrilli.
   ```
   P B2 B3 B4 B1 I1 I2 I3
   ```
   Collegamento strumento per Verifica Differenziale Monofase o Bifase 230V
   ```
   B2 B3 B4 B1 I1 I2 I3 1 3 N
   ```
   Collegamento strumento per Verifica Differenziale Trifase 400V + N + PE
   ```
   B2 B3 B4 B1 I1 I2 I3 1 3 N
   ```
   Collegamento strumento per Verifica Differenziale Trifase 400V + N (no PE) non utilizzare per RCD tipo A
   ```
   B2 B3 B4 B1 I1 I2 I3 1 3
   ```
   Collegamento strumento per Verifica Differenziale Trifase 400V + PE (no N)
3. Inserire la spina Shuko in una presa 230V 50Hz o i coccodrilli sui Terminali della protezione del differenziale del sistema trifase (vedi figure precedenti).

### 6.3.2.1. Modalità "`x ½`"
4. Premere **una volta** il tasto `START`. Lo strumento esegue la prova facendo circolare una corrente di tipo "`0°`".
oppure
Premere **due volte** il tasto `START` prima che scompaiano i trattini. Lo strumento esegue la prova facendo circolare una corrente di tipo "`180°`".

> **ATTENZIONE**
> La visualizzazione del messaggio "`MISURA…`" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

* Se il differenziale NON interviene lo strumento emette un doppio segnale acustico che segnala l’esito positivo della prova e visualizza una videata tipo quella a fianco.

```
RCD 05.06.02
Il simbolo ">" indica che l'RCD non è intervenuto
> 999 ms
FRQ=50.0Hz Ut= 1V VP-N=231V VP-PE=231V RCD OK x1/2 30mA 50V
Valore della Tensione di Contatto riferita alla Corrente Nominale del Differenziale "RCD OK" indica che il Test è superato
FUNZ IdN RCD UL Tensione di Contatto Limite Modalità di funzionamento Corrente Nominale Tipo RCD
```
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto `SAVE` (vedi paragrafo `9.1`).

<!-- Chunk: Pages 33-64 -->
### 6.3.2.2. Modalità "x1, x2, x5"

4.  Premere **una volta** il tasto **START**. Lo strumento esegue la prova facendo circolare una corrente di tipo "0°".
    oppure
    Premere **due volte** il tasto **START** prima che scompaiano i trattini. Lo strumento esegue la prova facendo circolare una corrente di tipo "0°".

> **ATTENZIONE**
> La visualizzazione del messaggio "MISURA…" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

>  Quando il differenziale interviene a sezionare il circuito, se il tempo di intervento rientra nei limiti riportati in Tabella 3 la prova è superata con esito positivo. Lo strumento emette un **doppio segnale acustico** che segnala l’esito positivo della prova e poi visualizza una videata tipo quella a fianco.

```
RCD       05.02.09
Tempo di intervento (espresso in ms)
            49ms
FRQ=50.0Hz  Ut= 2V
VP-N=231V   VP-PE=231V
RCD OK
x1   30mA  ~  50V
Valore della Tensione di Contatto
riferita alla Corrente Nominale
del Differenziale
"RCD OK" indica che il Test è superato
FUNZ   IdN   RCD   UL
Tensione di Contatto Limite
Corrente Nominale Tipo RCD
```

I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

**START STOP**

### 6.3.2.3. Modalità "AUTO"

4.  Premere il tasto **START**. Lo strumento esegue le 6 seguenti prove:
    *   I`Δ`n x ½ con fase 0° (il differenziale non deve intervenire).
    *   I`Δ`n x ½ con fase 180° (il differenziale non deve intervenire).
    *   I`Δ`n x 1 con fase 0° (il differenziale interviene, riarmare l'interruttore).
    *   I`Δ`n x 1 con fase 180° (il differenziale interviene, riarmare l'interruttore).
    *   I`Δ`n x 5 con fase 0° (il differenziale interviene, riarmare l'interruttore).
    *   I`Δ`n x 5 con fase 180° (il differenziale interviene, fine prova).
    La prova ha esito positivo se tutti i tempi di intervento sono conformi a quanto indicato in Tabella 3. La prova termina con esito negativo non appena uno dei valori risulti fuori limite.

> **ATTENZIONE**
> La visualizzazione del messaggio "MISURA…" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

>  Al termine della prova, nel caso in cui **tutte le sei** prove abbiano dato **risultato positivo**, lo strumento visualizza una videata tipo quella a fianco relativa all'ultima misura eseguita.

```
RCD       05.02.09
Tempi di intervento (espressi in ms)
0°        180°
x1/2   >999ms   >999ms
x1      55ms     65ms
x5      20ms     30ms
FRQ=50.0Hz  Ut= 1V
VP-N=231V   VP-PE=231V
RCD OK
AUTO 30mA  ~  50V
Valore della Tensione di Contatto
riferita alla Corrente Nominale
del Differenziale
"RCD OK" indica che il Test è superato
FUNZ   IdN   RCD   UL
Tensione di Contatto Limite
Modalità di Prova Corrente Nominale Tipo RCD
```

I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

**START STOP**

### 6.3.2.4. Modalità "(Rampa)"

4.  Premere **una volta** il tasto **START**. Lo strumento esegue la prova facendo circolare una corrente di tipo "0°".
    oppure
    Premere **due volte** il tasto **START** prima che scompaiano i trattini. Lo strumento esegue la prova facendo circolare una corrente di tipo "180°".
    Lo strumento genera una corrente di dispersione crescente a gradini per un certo intervallo di tempo.

> **ATTENZIONE**
> La visualizzazione del messaggio "MISURA…" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

>  Al termine della prova, se la corrente a cui è intervenuto l’interruttore differenziale è inferiore a 1I`Δ`n impostata (Tipo AC) o 1,4I`Δ`n (Tipo A con I`Δ`n >10mA) o 2I`Δ`n (Tipo A con I`Δ`n `≤` 10mA), lo strumento emette un **doppio segnale acustico** che segnala l’esito positivo della prova e visualizza una videata tipo quella a fianco.

```
RCD       05.02.09
Corrente di Intervento
            27mA
Tempo di Intervento
            35ms
FRQ=50.0Hz  Ut= 1V
VP-N=231V   VP-PE=231V
RCD OK
     30mA  ~  50V
Valore della Tensione di Contatto
riferita alla Corrente Nominale
del Differenziale
"RCD OK" indica che il Test è superato
FUNZ   IdN   RCD   UL
Tensione di Contatto Limite
Corrente Nominale Tipo RCD
```

I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

**START STOP**

### 6.3.2.5. Modalità "R A"

4.  Premere il tasto **START**. Lo strumento esegue la prova.

> **ATTENZIONE**
> La visualizzazione del messaggio "MISURA…" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

>  A fine prova lo strumento emette un **doppio segnale acustico** che segnala l’esito positivo della prova e visualizza una videata tipo quella a fianco.

```
RCD       05.02.09
Valore della Resistenza Globale di Terra
            ---- 
Valore della Tensione di Contatto
riferita alla Corrente Nominale
del Differenziale.
FRQ= 0.0Hz  Ut= ---V
VP-N= 0V    VP-PE= 0V
RA   30mA  ~  50V
"Ut OK" indica una Tensione di Contatto
Tensione di Contatto
FUNZ   IdN   RCD   UL
Tipo RCD
Modalità di Funzionamento
Corrente Nominale
```

I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

**START STOP**

## 6.3.3. Situazioni anomale

### 6.3.3.1. Problemi di collegamento

>  Se, alla pressione del tasto **START**, lo strumento rileva la connessione all'alimentatore esterno, viene visualizzato il messaggio indicato a lato.
>
> ```
> RCD       05.06.02
>             - - - ms
> FRQ=50.0Hz  Ut= ---V
> VP-N=230V   Vp-PE=230V
>  TOGLI ALIM
> x1   30mA       50V
> Per motivi di sicurezza, lo strumento non esegue le prove di verifica qualora sia collegato l'alimentatore esterno. Per eseguire la prova disconnettere l'alimentatore.
> FUNZ   IdN   RCD   UL
> ```

>  Se lo strumento rileva una Tensione Fase-Neutro e una Tensione Fase-Terra minore di 100V, viene visualizzato il messaggio a lato. Controllare che l'impianto in esame sia alimentato.
>
> ```
> RCD       05.06.02
>             - - - ms
> FRQ=50.0Hz  Ut= ---V
> VP-N= 0V    Vp-PE= 0V
>  TENSIONE BASSA
> x1   30mA       50V
> Tensione insufficiente
> FUNZ   IdN   RCD   UL
> ```

>  Se lo strumento rileva una Tensione Fase-Neutro o Fase-Terra superiore a 265V, viene visualizzato il messaggio a lato. Controllare che lo strumento non sia collegato fra Fase e Fase.
>
> ```
> RCD       05.06.02
>             - - - ms
> FRQ=50.0Hz  Ut= ---V
> VP-N=401V   VP-PE= 230V
>  TENSIONE ALTA
> x1   30mA       50V
> Rilevata una Tensione >250V
> FUNZ   IdN   RCD   UL
> ```

>  Se lo strumento rileva che i terminali Fase e Neutro sono scambiati visualizza il messaggio a lato. Ruotare la spina Shuko o controllare il collegamento dei cavi separati.
>
> ```
> RCD       05.06.02
>             - - - ms
> FRQ=50.0Hz  Ut= ---V
> VP-N=231V   VP-PE= 0V
>  INVERTIRE P-N
> x1   30mA       50V
> I conduttori di Fase e Neutro sono scambiati.
> FUNZ   IdN   RCD   UL
> ```

>  Se lo strumento rileva che i terminali Fase e Terra sono scambiati visualizza il messaggio a lato. Ruotare la spina Shuko o controllare il collegamento dei cavi separati.
>
> ```
> RCD       05.06.02
>             - - - ms
> FRQ=50.0Hz  Ut= ---V
> VP-N= 2V    VP-PE= 230V
>  INVERTIRE P-PE
> x1   30mA       50V
> I conduttori di Fase e Terra sono scambiati.
> FUNZ   IdN   RCD   UL
> ```

>  Se in un sistema 230V Fase-Fase, lo strumento rileva che i terminali B3 e B4 sono scambiati visualizza il messaggio a lato. Controllare il collegamento dei cavi separati.
>
> ```
> RCD       05.06.02
>             - - - ms
> FRQ=50.0Hz  Ut= ---V
> VP-N=130V   VP-PE= 227V
>  INVERTIRE P-PE
> x1   30mA       50V
> I terminali B3 e B4 sono scambiati.
> FUNZ   IdN   RCD   UL
> ```

>  Se lo strumento rileva che qualora si effettuasse la prova nell'impianto in esame si localizzerebbe una Tensione di Contatto superiore al limite impostato, non effettua la prova e visualizza il messaggio a lato. Controllare l'efficienza del conduttore di Protezione e dell'impianto di Terra.
>
> ```
> RCD       05.06.02
>             - - - ms
> FRQ=50.0Hz  Ut= ---V
> VP-N=234V   VP-PE= 234V
>  UT PERICOLOSA
> x1   30mA       50V
> Lo strumento rileva una Tensione di Contatto pericolosa
> FUNZ   IdN   RCD   UL
> ```

>  Se lo strumento rileva una resistenza di Terra estremamente elevata, tale da ritenere assente il conduttore di Terra o l'impianto di Terra stesso, visualizza il messaggio a lato. Controllare l'efficienza del conduttore di Protezione e dell'impianto di Terra.
>
> ```
> RCD       05.06.02
>             - - - ms
> FRQ=50.0Hz  Ut= ---V
> VP-N=234V   VP-PE= 34V
>  NO PE
> x1   30mA       50V
> Impianto di Terra non Efficiente
> FUNZ   IdN   RCD   UL
> ```

>  Se, in seguito a ripetute prove, lo strumento si è surriscaldato, viene visualizzato il messaggio a lato. Attendere che tale messaggio scompaia prima di eseguire altre prove.
>
> ```
> RCD       05.06.02
>             - - - ms
> FRQ=50.0Hz  Ut= ---V
> VP-N=231V   VP-PE= 230V
>  ALTA TEMP
> x1   500mA      50V
> Strumento surriscaldato
> FUNZ   IdN   RCD   UL
> ```
>
I PRECEDENTI RISULTATI NON POSSONO ESSERE MEMORIZZATI.

>  Utilizzando la modalità "R A" se lo strumento rileva una Tensione di contatto superiore al limite impostato, visualizza il messaggio a lato. Controllare l'efficienza del conduttore di Protezione e dell'impianto di Terra.
>
> ```
> RCD       05.02.09
>             1800 
> FRQ=50.0Hz  Ut= 54V
> VP-N=234V   VP-PE= 34V
> UT NON OK
> R A  30mA  ~  50V
> Lo strumento rileva una Tensione di Contatto pericolosa.
> FUNZ   IdN   RCD   UL
> ```
>
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

### 6.3.3.2. Problemi relativi all'intervento del differenziale

>  Se l'RCD interviene durante l'esecuzione dei controlli preliminari (eseguiti in maniera automatica dallo strumento prima di procedere alla prova selezionata) lo strumento visualizza il messaggio a lato. Controllare che tutti i carichi connessi a valle dell'RCD in esame siano scollegati.
>
> ```
> RCD       05.06.02
>             - - - ms
> FRQ=50.0Hz  Ut= ---V
> VP-N=231V   VP-PE= 230V
>  RCD INTERVENUTO
> x1   30mA       50V
> RCD intervenuto durante i controlli preliminari
> FUNZ   IdN   RCD   UL
> ```
>
I PRECEDENTI RISULTATI NON POSSONO ESSERE MEMORIZZATI.

>  Se l'RCD interviene in un tempo non conforme a quanto indicato nella Tabella 3, lo strumento emette un segnale acustico prolungato e visualizza il messaggio a lato. Controllare che il tipo di RCD impostato corrisponda al tipo di RCD in esame.
>
> ```
> RCD       05.06.02
>            487 ms
> FRQ=50.0Hz  Ut= 1V
> VP-N=231V   VP-PE= 230V
>  TEMPO NON OK
> x1   30mA       50V
> Tempo di Intervento
> il Tempo di Intervento non è conforme alla Tabella 3
> FUNZ   IdN   RCD   UL
> ```

>  Se il tempo di Intervento non rispetta i limiti fissati dalla Tabella 3 ed eccede la durata massima per la Prova (vedi Tabella 5) lo strumento visualizza il messaggio a lato.
>
> ```
> RCD       05.06.02
>            >999 ms
> FRQ=50.0Hz  Ut= 1V
> VP-N=231V   VP-PE= 230V
>  TEMPO NON OK
> x1   30mA       50V
> Il Simbolo ">" indica che l'RCD non è intervenuto entro la durata massima prevista per la prova selezionata
> Tempo non conforme alla Tabella 3
> FUNZ   IdN   RCD   UL
> ```
>
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1). La durata massima dipende dal tipo di prova eseguita:

| Tipo prova          | Interruttore generale | Interruttore selettivo |
| :------------------ | :-------------------- | :--------------------- |
| Prova MAN x1        | 999ms                 | 999ms                  |
| Prova MAN x2        | 200ms                 | 250ms                  |
| Prova MAN x5        | 50ms                  | 160ms                  |
| Prova "(Rampa)"     | 300ms                 |                        |

Tabella 5: Durata massima nelle Varie Modalità di Prova

>  Se, durante una prova in modalità "Rampa", l'RCD interviene con un tempo superiore alla massima durata pervista per la prova (vedi Tabella 5), lo strumento visualizza il messaggio a lato.
>
> ```
> RCD       05.06.02
> Corrente di Intervento
>             27 mA
>             >300ms
> Freq=50.0Hz Ut= 1V
> VP-N=231V   Vp-PE=230V
>  TEMPO NON OK
>      30mA       50V
> FUNZ   IdN   RCD   UL
> Il tempo di Intervento supera la massima durata ammessa
> ```
>
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

>  Se, durante una prova in modalità "Rampa", l'RCD non interviene entro il valore massimo previsto per la prova, lo strumento visualizza il messaggio a lato.
>
> ```
> RCD       05.06.02
> Il simbolo ">" indica che l'RCD non è intervenuto pur applicando la corrente massima prevista per la prova e per il tipo di RCD selezionato
>            > 42 mA
>             >300ms
> FRQ=50.0Hz  Ut= 1V
> VP-N=231V   VP-PE=230V
>  CORRENTE NON OK
>      30mA       50V
> Il valore della corrente di Intervento non è conforme a quanto indicato nella Tabella 4
> FUNZ   IdN   RCD   UL
> ```
>
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

## 6.4. LOOP: MISURA DELL’IMPEDENZA DI LINEA, DELL’IMPEDENZA DELL’ANELLO DI GUASTO, CALCOLO DELLA CORRENTE DI CORTOCIRCUITO E DI GUASTO PRESUNTA ED INDICAZIONE DEL SENSO CICLICO DELLE FASI

Ruotare il **selettore** in posizione **LOOP Z S /I K**. Con il tasto **F1** è possibile selezionare una delle seguenti modalità di misura (che si presentano ciclicamente alla pressione del tasto):

*   Modalità “**P-N**" (lo strumento misura l'impedenza fra il conduttore di Fase e il conduttore di Neutro e calcola la corrente di corto circuito presunta Fase-Neutro. Questa prova viene di solito eseguita per valutare se il potere di interruzione degli interruttori è superiore alla corrente di cortocircuito nel punto di installazione).
*   Modalità “**P-P**" (lo strumento misura l'impedenza fra due conduttori di Fase e calcola la corrente di corto circuito presunta Fase-Fase. Questa prova viene di solito eseguita per valutare se il potere di interruzione degli interruttori è superiore alla corrente di cortocircuito nel punto di installazione).
*   Modalità “**P-PE**" (lo strumento misura la resistenza Globale di Terra e calcola la corrente di corto circuito presunta Fase-Terra. Questa prova viene di solito eseguita per valutare il coordinamento delle protezioni contro i contatti indiretti mediante interruzione automatica dell’alimentazione e per misurare il valore della Resistenza di Terra).
*   Modalità "**R A**" (lo strumento misura la resistenza Globale di Terra e calcola la corrente di corto circuito presunta Fase-Terra. Questa prova viene di solito eseguita per valutare il coordinamento delle protezioni contro i contatti indiretti mediante interruzione automatica dell’alimentazione e per misurare il valore della Resistenza di Terra. Questa prova ha una minore risoluzione della prova "P-PE" ma presenta il vantaggio che può essere eseguita senza fare intervenire una eventuale protezione differenziale posta a monte del punto di misura).
*   Modalità "**(Rotazione Fasi)**" (lo strumento rileva il senso ciclico delle fasi)

> **ATTENZIONE**
> La visualizzazione del messaggio "MISURA…" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

### 6.4.1. Misura di Impedenza ad alta risoluzione (0.1 m `Ω`)

Gli strumenti GSC57 e GSC59 consentono di eseguire misure di Impedenza ad Alta Risoluzione nelle immediate vicinanze di un trasformatore MT/BT con l’uso dell’accessorio (opzionale) **IMP57**. La misura è selezionabile nei modi **LOOP P-P**, **P-N**, **P-PE** utilizzando il tasto **F2 (Z2 `Ω`)**. In caso di selezione della misura di Impedenza ad Alta Risoluzione senza il collegamento dell’accessorio IMP57, lo strumento mostra una schermata come la seguente (ex: Loop P-N):

```
LOOP      05.02.09
Z=-----  R=-----  X=----- 
IkSTD=----A
V1-2= 0V FRQ= 0.0Hz
NO IMP57
P-N Z2 
FUNZ   ZSTD   ICAL   RMT
```

Per ogni dettaglio relativo all’uso e alle caratteristiche tecniche dell’accessorio IMP57 fare riferimento al relativo manuale d’uso oppure consultare il sito Web http://www.ht-instruments.com.

### 6.4.2. Modalità "P-N": procedura di misura e risultati

1.  Selezionare con il tasto **F1** la modalità **P-N**.
2.  Inserire i 3 connettori Nero, Verde, Blu del cavo shuko a tre terminali o dei cavi separati nei corrispondenti terminali di ingresso dello strumento **B1**, **B3**, **B4** (vedi possibili connessioni nelle figure seguenti). Nel caso di utilizzo dei cavi sciolti inserire all'estremità dei cavi rimasta libera i coccodrilli.
    ```
    P B2   B3   B4
    B1 I1   I2   I3
    ```
    Collegamento strumento per Misura dell'impedenza di Linea Monofase o Bifase 230V
    ```
    B2   B3   B4
    B1 I1   I2   I3
    1 3 N
    ```
    Collegamento strumento per Misura dell'impedenza di Linea in un sistema Trifase 400V
3.  Inserire la spina Shuko in una presa 230V 50Hz o i coccodrilli sui conduttori del sistema trifase (vedi figure precedenti).
4.  Scollegare, quando possibile tutti i carichi connessi a valle del punto di misura in quanto l'impedenza dei suddetti utilizzatore potrebbe falsare i risultati della prova.
5.  Premere il tasto **START**. Lo strumento fa partire la prova.

> **ATTENZIONE**
> la seguente prova comporta la circolazione di una corrente massima di circa 6A tra fase e neutro. Questo potrebbe comportare l’intervento di eventuali protezioni magnetotermiche con correnti di intervento inferiori. Nel caso, eseguire la misura a monte delle protezioni stesse.

> **ATTENZIONE**
> La visualizzazione del messaggio "MISURA…" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

>  Lo strumento, a fine prova, emette un **doppio segnale acustico** che segnala che la prova è stata eseguita correttamente e visualizza una videata simile a quella a fianco.

```
LOOP      05.02.09
0°
            ---- 
            ----A
FRQ= 0HZ    VP-N= 0V
VP-PE= 0V   P-PE  50V
Valore dell'impedenza di Linea Fase-Neutro
espressa in Ohm
Valore della corrente presunta di cortocircuito
Fase-Neutro calcolata utilizzando la formula sotto indicata
FUNZ   Z2    UL
```

Formula utilizzata per il calcolo corrente presunta di cortocircuito:

```
          UN
ICC = ————
          ZPN
```

dove U`N` =tensione Fase-Neutro
```
127 se Vmis ≤ 150
230 se 150V< Vmis ≤ 260
```
Z`PN` =impedenza misurata Fase-Neutro
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

**START STOP**

### 6.4.3. Modalità "P-P": procedura di misura e risultati

1.  Selezionare con il tasto **F1** la modalità **P-P**.
2.  Inserire i 3 connettori Nero, Verde, Blu dei cavi separati nei corrispondenti terminali di ingresso dello strumento **B1**, **B3**, **B4**.
    ```
    B2   B3   B4
    B1 I1   I2   I3
    1 3 N
    ```
    Collegamento strumento per Misura dell'impedenza Fase-Fase
3.  Inserire i coccodrilli sui conduttori del sistema trifase (vedi figura precedente).
4.  Scollegare, quando possibile, tutti i carichi connessi a valle del punto di misura in quanto l'impedenza dei suddetti utilizzatori potrebbe falsare i risultati della prova.
5.  Premere il tasto **START**. Lo strumento esegue la prova:

> **ATTENZIONE**
> La seguente prova comporta la circolazione di una corrente massima di circa **12A** (su 400V) tra fase e fase. Questo potrebbe comportare l’intervento di eventuali protezioni magnetotermiche con correnti di intervento inferiori. Nel caso eseguire la misura a monte delle protezioni stesse.

>  Lo strumento a fine prova emette un **doppio segnale acustico** che segnala che la prova è stata eseguita correttamente e poi visualizza una videata simile a quella a fianco.

```
LOOP      05.02.09
Valore dell'impedenza di Linea Fase-Fase espressa in Ohm
            1.07 
            215A
FRQ=50.0HZ  VP-N=231V
VP-PE=231V  P-N
Valore della corrente presunta di cortocircuito
Fase-Fase calcolata utilizzando la formula sotto indicata.
Modalità di Funzionamento
FUNZ   Z2 
```

**START STOP**

> **ATTENZIONE**
> La visualizzazione del messaggio "MISURA…" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

Formula calcolo corrente presunta di cortocircuito:

```
          UN
ICC = ————
          ZPP
```

dove U`N` = tensione Fase-Fase
```
127 se Vmis ≤ 150
230 se 150V< Vmis ≤ 260
400 se Vmis > 260
```
Z`PP` = impedenza misurata Fase-Fase
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

### 6.4.4. Modalità "P-PE": procedura di misura e risultati

1.  Selezionare con il tasto **F1** la modalità **P-PE**.
2.  Inserire i 3 connettori Nero, Verde e Blu del cavo shuko o dei cavi sciolti nei corrispondenti terminali di ingresso dello strumento **B1**, **B3**, **B4** (vedi possibili connessioni nelle figure seguenti). Nel caso di utilizzo dei cavi separati inserire all'estremità dei cavi rimasta libera i coccodrilli.
    ```
    P B2   B3   B4
    B1 I1   I2   I3
    ```
    Collegamento strumento per Misura dell'impedenza dell’anello di guasto in un sistema Monofase o Bifase 230V
    ```
    B2   B3   B4
    B1 I1   I2   I3
    1 3 N
    ```
    Collegamento strumento per Misura dell'impedenza dell’anello di guasto in un sistema Trifase 400V con neutro
    ```
    B2   B3   B4
    B1 I1   I2   I3
    1 3
    ```
    Misura dell'impedenza dell’anello di guasto in un sistema Trifase 230 o 400V senza Neutro
3.  Inserire la spina Shuko in una presa 230V 50Hz o i coccodrilli sui conduttori del sistema trifase (vedi figure precedenti).
4.  Il tasto **F4** permette di impostare il Valore limite della Tensione di Contatto. Lo strumento esegue la prova controllando che la tensione di contatto presente sulle masse dell’impianto, relativamente alla corrente effettiva erogata, non superi il valore limite impostato. E' possibile selezionare uno dei due possibili valori:
    *   50V (default).
    *   25V.
5.  Premere **una volta** il tasto **START**. Lo strumento esegue la prova facendo circolare una corrente di tipo "0°".
    oppure
    Premere **due volte** il tasto **START** prima che scompaiano i trattini. Lo strumento esegue la prova facendo circolare una corrente di tipo "180°".

**START STOP**

> **ATTENZIONE**
> La seguente prova comporta la circolazione di una corrente di circa 6A tra fase e terra. Questo può comportare l’intervento di eventuali protezioni magnetotermiche o Differenziali. Nel caso eseguire la misura a monte della protezione. Nel caso di Protezioni differenziali di tipo AC si può cercare di individuare quale forma d'onda (tipo **0°** o tipo **180°**) non causa l'intervento della protezione stessa.

> **ATTENZIONE**
> La visualizzazione del messaggio "MISURA…" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

>  Lo strumento a fine prova emette un **doppio segnale acustico** che segnala che la prova è stata eseguita correttamente e poi visualizza una videata simile a quella a fianco.

```
LOOP      05.06.02
Valore dell'impedenza Fase-Terra espressa in .
            1.07 
            215A
Freq=50.0HZ VP-N=231V
Vp-PE=231V  P-PE  50V
Valore della corrente presunta di cortocircuito
Fase-Fase calcolata utilizzando la formula sotto indicata.
FUNZ   Z2    UL
Modalità di Funzionamento
```

**N.B.:** Nei Sistemi TT il valore dell'impedenza misurata dallo strumento può essere attribuito al solo valore della Resistenza Globale di Terra. Pertanto, in accordo con quanto specificato dalla CEI64-8, il valore misurato può essere assunto come valore per la resistenza di Terra dell'impianto.
Formula per il calcolo della corrente presunta di cortocircuito:

```
          UN
ICC = ————
          ZPE
```

dove U`N` =tensione Fase-Terra
```
127 se 100< Vmis ≤ 150
230 se 150V< Vmis ≤ 260
```
dove Z`PE` =impedenza misurata Fase-Terra
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

### 6.4.5. Modalità "R A": procedura di misura e risultati

1.  Selezionare con il tasto **F1** la modalità **R A**.
2.  Inserire i 3 connettori Nero, Verde e Blu del cavo shuko o dei cavi sciolti nei corrispondenti terminali di ingresso dello strumento **B1**, **B3**, **B4** (vedi possibili connessioni nelle figure seguenti). Nel caso di utilizzo dei cavi separati inserire all'estremità dei cavi rimasta libera i coccodrilli.
    ```
    P B2   B3   B4
    B1 I1   I2   I3
    ```
    Collegamento strumento per Misura della resistenza dell’anello di guasto in un sistema Monofase o Bifase 230V
    ```
    B2   B3   B4
    B1 I1   I2   I3
    1 3 N
    ```
    Collegamento strumento per Misura della resistenza dell’anello di guasto in un sistema Trifase 400V con neutro
    ```
    B2   B3   B4
    B1 I1   I2   I3
    1 3
    ```
    Misura della resistenza dell’anello di guasto in un sistema Trifase 230 o 400V senza Neutro
3.  Inserire la spina Shuko in una presa 230V 50Hz o i coccodrilli sui conduttori del sistema trifase (vedi figure precedenti).
4.  Il tasto **F4** permette di impostare il Valore limite della Tensione di Contatto: Lo strumento esegue la prova controllando che la tensione di contatto presente sulle masse dell’impianto relativa alla corrente effettiva erogata dallo strumento non superi il valore della tensione di contatto limite impostata. E' possibile selezionare uno dei due possibili valori:
    *   50V (default).
    *   25V.
6.  Premere **una volta** il tasto **START**. Lo strumento esegue la prova facendo circolare una corrente di tipo "0°".
    oppure
    Premere **due volte** il tasto **START** prima che scompaiano i trattini. Lo strumento esegue la prova facendo circolare una corrente di tipo "180°".

**START STOP**

> **ATTENZIONE**
> La seguente prova comporta la circolazione di una corrente di circa 15mA tra fase e terra. Questo comporta l’intervento di eventuali Differenziali con corrente nominale 10mA. Nel caso, eseguire la misura a monte della protezione.

> **ATTENZIONE**
> La visualizzazione del messaggio "MISURA…" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

>  Lo strumento a fine prova emette un **doppio segnale acustico** che segnala che la prova è stata eseguita correttamente e visualizza una videata simile a quella a fianco.

```
LOOP      05.02.09
Valore dell'impedenza Fase-Terra espressa in 
            ---- 
            ----A
Freq= 0.0HZ VP-N= 0V
VP-PE= 0V   R A  50V
Valore della corrente presunta di cortocircuito
Fase-Fase calcolata utilizzando la formula sotto indicata
Modalità di Funzionamento
FUNZ   UL
```

**N.B.:** Nei Sistemi TT il valore della Resistenza Globale di Terra, può essere assimilato al valore dell'impedenza dell’anello di guasto Fase-Terra, misurata dallo strumento. Pertanto, in accordo con quanto specificato dalla CEI64-8, quanto misurato può essere assunto come valore della resistenza di Terra dell'impianto.
Formula per il calcolo della corrente presunta di cortocircuito:

```
          UN
ICC = ————
          ZPE
```

dove U`N` =tensione Fase-Terra
```
127 se 100< Vmis ≤ 150
230 se 150V< Vmis ≤ 260
```
dove Z`PE` =impedenza misurata Fase-Terra
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

### 6.4.6. Modalità "(Rotazione Fasi)": procedura di misura e risultati

1.  Selezionare con il tasto **F1** la modalità "(Rotazione Fasi)".
2.  Inserire i 3 connettori Nero, Rosso, Verde dei cavi separati nei corrispondenti terminali di ingresso dello strumento **B1**, **B2**, **B3**.
    ```
    B2   B3   B4
    B1 I1   I2   I3
    1 3
    ```
    Collegamento strumento per Misura dell'impedenza Fase-Fase (Nota: Il diagramma mostrato è generico e potrebbe non corrispondere al collegamento per la rotazione di fase descritto).
3.  Inserire i coccodrilli sui conduttori del sistema trifase (vedi figura precedente).
4.  Premere il tasto **START**. Lo strumento esegue la prova.

> **ATTENZIONE**
> La visualizzazione del messaggio "MISURA…" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

>  Lo strumento a fine prova emette un **doppio segnale acustico** che segnala che la prova è stata eseguita correttamente e visualizza una videata simile a quella a fianco.

```
LOOP      05.02.09
Indicazione Senso Ciclico RST
RST
FRQ=50.0HZ  VR-S=391V
VS-T=401V   VT-R=399V
OK
ROTAZIONE FASI
Valori delle Tensioni Fase-Fase
Senso ciclico corretto
FUNZ
Modalità di Funzionamento
```

**N.B.:** Il messaggio RST **NON** significa che l'Ingresso B1 sia connesso alla Fase R, l'Ingresso B2 sia connesso alla Fase S e l'Ingresso B3 sia connesso alla Fase T, bensì indica solamente che le fasi del sistema elettrico in esame rispettano la giusta sequenza.
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

**START STOP**

### 6.4.7. Situazioni anomale modalità "P-P", "P-N", "P-PE","R A", "(Rotazione Fasi)"

>  Se alla pressione del tasto **START** lo strumento rileva la connessione all'alimentatore esterno, viene visualizzato il messaggio indicato a lato.
>
> ```
> LOOP      05.06.02
>             - - - 
>             ---A
> FRQ=50.0HZ  VP-N=231V
> VP-PE=230V   TOGLI ALIM.
> P-N
> Per motivi di sicurezza, lo strumento non esegue le prove di Verifica qualora sia collegato l'alimentatore esterno. Per eseguire la prova disconnettere l'alimentatore
> FUNZ   Z2 
> ```

>  Se lo strumento rileva una Tensione Fase-Neutro e una Tensione Fase-Terra minore di 100V, visualizza il messaggio a lato. Controllare che l'impianto in esame sia alimentato.
>
> ```
> LOOP      05.06.02
>             - - - 
>             ---A
> FRQ=50.0HZ  VP-N= 1V
> VP-PE= 0V    TENSIONE BASSA
> P-PE   50V
> Tensione insufficiente
> FUNZ   Z2    UL
> ```

>  Se lo strumento rileva una Tensione Fase-Neutro o Fase-Terra superiore a 250V, o una Tensione Fase-Fase superiore a 440V visualizza il messaggio a lato. Controllare che lo strumento non sia collegato fra Fase e Fase.
>
> ```
> LOOP      05.06.02
>             - - - 
>             ---A
> Freq=50.0HZ VP-N=401V
> VP-PE=230V   TENSIONE ALTA
> P-PE   50V
> Tensione troppo elevata
> FUNZ   Z2    UL
> ```

>  Se lo strumento rileva che i terminali Fase e Neutro sono scambiati visualizza il messaggio a lato. Ruotare la spina Shuko o controllare il collegamento dei cavi separati.
>
> ```
> LOOP      05.06.02
>             - - - 
>             ---A
> FRQ=50.0HZ  VP-N=231V
> VP-PE= 0V   INVERTIRE P-N
> P-PE   50V
> FUNZ   Z2    UL
> I conduttori di Fase e Neutro sono scambiati.
> ```

>  Se lo strumento rileva che i terminali Fase e Terra sono scambiati visualizza il messaggio a lato. Ruotare la spina Shuko o controllare il collegamento dei cavi separati.
>
> ```
> LOOP      05.06.02
>             - - - 
>             ---A
> FRQ=50.0HZ  VP-N= 1V
> VP-PE= 230V INVERTIRE P-PE
> P-N
> FUNZ   Z2 
> I conduttori di Fase e Terra sono scambiati
> ```

>  Se in un sistema 230V Fase-Fase, lo strumento rileva che i terminali B3 e B4 sono scambiati visualizza il messaggio a lato. Controllare il collegamento dei cavi separati.
>
> ```
> LOOP      05.06.02
>             - - - 
>             ---A
> FRQ=50.0HZ  VP-N=131V
> VP-PE= 227V INVERTIRE N-PE
> P-N
> FUNZ   Z2 
> I conduttori di Fase e Terra sono scambiati
> ```

>  Se lo strumento rileva che, qualora effettuasse la prova nell'impianto in esame si localizzerebbe una Tensione di Contatto superiore al limite impostato, non effettua la prova e visualizza il messaggio a lato. Controllare l'efficienza del conduttore di Protezione e dell'impianto di Terra.
>
> ```
> LOOP      05.06.02
>             - - - 
>             ---A
> FRQ=50.0HZ  VP-N= 1V
> Vp-PE= 0V   Ut PERICOLOSA
> R A   50V
> FUNZ   UL
> Lo strumento rileva una Tensione di Contatto pericolosa
> ```

>  Se lo strumento rileva una resistenza di Terra estremamente elevata, tale da ritenere assente il conduttore di Terra o l'impianto di Terra stesso, visualizza il messaggio a lato. Controllare l'efficienza del conduttore di Protezione e dell'impianto di Terra.
>
> ```
> LOOP      05.06.02
>             - - - 
>             ---A
> FRQ=50.0HZ  VP-N=231V
> Vp-PE= 40V  NO PE
> P-PE   50V
> Impianto di Terra non efficiente
> FUNZ   Z2    UL
> ```

>  Se, in seguito a ripetute prove, lo strumento si è surriscaldato, viene visualizzato il messaggio a lato. Attendere che tale messaggio scompaia prima di eseguire altre prove.
>
> ```
> LOOP      05.06.02
>             - - - 
>             ---A
> FRQ=50.0HZ  VP-N=231V
> Vp-PE= 40V  ALTA TEMP
> P-PE   50V
> FUNZ   Z2    UL
> Lo strumento si è surriscaldato
> ```

>  In modalità "(Rotazione Fasi)", se una delle Tensioni Fase-Fase non raggiunge la soglia minima di 100V lo strumento non esegue la prova e visualizza la videata a lato. Controllare che tutte le fasi del sistema elettrico in esame siano in tensione.
>
> ```
> LOOP      05.06.02
>             - - -
> FRQ =50.0HZ VR-S=391V
> VS-T= 0 V   VT-R= 0V
>  BASSA TENSIONE T
> ROTAZIONE FASI
> La Fase "T" non raggiunge la Tensione minima
> FUNC
> ```

>  Utilizzando la modalità "(Rotazione Fasi)" se due fasi del sistema elettrico risultano coincidenti lo strumento non esegue la prova e visualizza la videata a lato. Controllare che tutte le fasi del sistema elettrico in esame siano in tensione.
>
> ```
> LOOP      05.06.02
>             - - -
> FRQ =50.0HZ VR-S=407V
> VS-T= 0 V   VT-R=407V
>  FASE DOPPIA
> ROTAZIONE FASI
> Due fasi del sistema Trifase in esame sono collegate assieme
> FUNC
> ```
>
I PRECEDENTI RISULTATI NON POSSONO ESSERE MEMORIZZATI.

>  Utilizzando le modalità "P-P", "P-N" se lo strumento rileva una impedenza maggiore di 199.9 `Ω` visualizza la videata a lato.
>
> ```
> LOOP      05.06.02
> Il simbolo">" indica che il valore dell'impedenza è maggiore del valore Massimo misurabile
> >199.9 
>             ---A
> FRQ =50.0HZ VP-N= 1V
> VP-PE= 0V   P-N
> FUNZ   Z2 
> ```
>
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

>  Utilizzando le modalità "P-PE", "R A" se lo strumento rileva una impedenza maggiore di 1999 `Ω` visualizza la videata a lato.
>
> ```
> LOOP      05.06.02
> Il simbolo">" indica che il valore dell'impedenza è maggiore del valore Massimo misurabile
> >1999 
>             ---A
> FRQ =50.0HZ VP-N= 1V
> VP-PE= 0V   R A  50V
> FUNZ   UL
> ```
>
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

>  Utilizzando la modalità "(Rotazione Fasi)" se il senso ciclico delle fasi non è corretto viene visualizzato il simbolo "RTS". Scambiare fra loro due fasi del sistema elettrico in esame e ripetere la prova.
>
> ```
> LOOP      05.06.02
> Questo simbolo NON indica che l'Ingresso B1 è connesso alla fase R, l'ingresso B2 è connesso alla Fase T, l'ingresso B3 è connesso alla Fase S bensì indica SOLO che la sequenza delle fasi rilevata non è corretta
> RTS
> FRQ=50.0HZ  VR-S= 391V
> VS-T= 392V VT-R= 398V
>  NON CORRETTO
> ROTAZIONE FASI
> Sequenza non Corretta
> FUNZ
> ```
>
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

## 6.5. EARTH: MISURA DELLA RESISTENZA DI TERRA E DELLA RESISTIVITÀ DEL TERRENO

Selezionare la posizione del commutatore **EARTH**. Il tasto **F1** permette di selezionare una delle seguenti modalità (che si presentano in ordine ciclico):

*   Modalità "**2-F**" (lo strumento effettua la misura della Resistenza fra 2 punti).
*   Modalità "**3-F**" (lo strumento effettua la misura della Resistenza utilizzando 3 punti di misura).
*   Modalità "**`ρ`**" (lo strumento misura la resistività del Terreno tramite una misura a 4 punti).
Al termine di ogni prova lo strumento visualizza automaticamente il valore medio della Resistenza di Terra o della Resistività del Terreno calcolato sulla base dei valori misurati sino a quel momento. il tasto **F2** azzera il valore medio della Resistenza di Terra o della Resistività del Terreno ed il contatore del numero delle misure di Resistenza effettuate.

> **ATTENZIONE**
> La visualizzazione del messaggio "MISURA…" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

### 6.5.1. Modalità "2-F" e "3-F": procedura di misura e risultati

1.  Utilizzando il tasto **F1** selezionare la modalità "**2-F**" o "**3-F**".
2.  Infiggere nel terreno i picchetti ausiliari in accordo con quanto indicato al paragrafo 17.4.
3.  Collegare i terminali dei cavi Nero, Rosso, Verde e Blu ai rispettivi terminali di Ingresso **B1**, **B2**, **B3**, **B4** (vedi possibili connessioni seguenti).
    ```
    B2   B3   B4
    B1 I1   I2   I3
    1 3 N
    ```
    Collegamento per la misura a 3 punti
    ```
    B2   B3   B4
    B1 I1   I2   I3
    1   1 3   3 N   N
    Transf
    ```
    Collegamento per la misura a 2 punti
    ```
    B2   B3   B4
    B1 I1   I2   I3
    1 3 N
    ```
    Collegamento per la misura a della resistenza verso terra di una massa conduttiva
4.  Premere il tasto **START**. Lo strumento avvia la prova.

**START STOP**

>  Lo strumento a fine prova emette un **doppio segnale acustico** che segnala che la prova è stata eseguita correttamente e visualizza una videata simile a quella a fianco.

```
EARTH     05.02.09
Valore della Resistenza espressa in 
            0.77 
Vd= 1V      Test:04
RAVG=0.74 
3-F
Valore della Tensione di Rumore espresso in Volt
Numero di Prove eseguite
Valore Medio della Resistenza di Terra
FUNZ   CANC
Modalità di Funzionamento
```

5.  Lo strumento visualizza automaticamente il valore medio della Resistenza calcolato sulla base dei valori delle Resistenze misurate fino a quel momento.
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

### 6.5.2. Modalità "`ρ`": procedura di misura e risultati

1.  Utilizzando il tasto **F1** selezionare la modalità "**`ρ`**".
2.  Infiggere nel terreno i picchetti ausiliari equidistanziati a **d** metri.
3.  Utilizzando i tasti **F3**, **F4** impostare sullo strumento il valore della distanza **d** fra i picchetti.
4.  Collegare i terminali dei cavi Nero, Rosso, Verde e Blu ai rispettivi terminali di Ingresso **B1**, **B2**, **B3**, **B4** (vedi possibili connessioni seguenti).
    ```
    B2   B3   B4
    B1 I1   I2   I3
    d d   d   d
    ```
    Collegamento dello strumento per misure di resistività
5.  Premere il tasto **START**. Lo strumento avvia la prova.

>  Lo strumento a fine prova emette un **doppio segnale acustico** che segnala che la prova è stata eseguita correttamente e visualizza una videata simile a quella a fianco.

```
EARTH     05.06.02
Valore della Resistività espressa in 
            ----  m
Vd= 0V      Test:00
 AVG=----  m
  DIST= 1m
Valore della Tensione di Rumore espresso in Volt
Numero di Prove eseguite
Valore Medio della Resistività
FUNZ   CANC      
Modalità di Funzionamento
```

6.  Lo strumento visualizza automaticamente il valore medio della Resistenza calcolato sulla base dei valori delle Resistenze misurate fino a quel momento.
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

**START STOP**

### 6.5.3. Situazioni anomale modalità "2-F", "3-F" e "`ρ`"

>  Se alla pressione del tasto **START** lo strumento rileva la connessione all'alimentatore esterno, visualizza il messaggio indicato a lato.
>
> ```
> EARTH     05.06.02
> Per motivi di sicurezza, lo strumento non esegue le prove di Verifica qualora sia collegato l'alimentatore esterno. Per eseguire la prova disconnettere l'alimentatore
>             - - - 
> Vd= ---V    Test:04
> RAVG=0.74 
>  TOGLI ALIM
> 3-F
> FUNZ   CANC
> ```

>  Se lo strumento rileva la presenza di una Tensione superiore a circa 15V presente ai terminali di ingresso, visualizza il messaggio indicato a lato.
>
> ```
> EARTH     05.06.02
> Il simbolo "" indica la presenza di Tensione in Ingresso
>            - - - 
> Vd= 230V    Test:04
> RAVG=0.74 
>  VOLT IN INPGRESSO
> 3-F
> FUNZ   CANC
> ```

>  Il messaggio "**Rc TROPPO ALTA**" indica che lo strumento non riesce a far circolare la corrente minima necessaria per la misura. Controllare che i coccodrilli effettuino un buon contatto con i picchetti ausiliari. Nel caso di terreno arido o poco conduttivo connettere più picchetti (connessi in parallelo fra loro) al terminale B4.
>
> ```
> EARTH     05.06.02
>             - - - 
> Vd= 1V      Test:04
> RAVG=0.74 
>  Rc TROPPO ALTA
> 3-F
> Resistenza del Circuito amperometrico (B1-B4) elevata
> FUNZ   CANC
> ```

>  Il messaggio "**Rp TROPPO ALTA**" indica che lo strumento non riesce a misurare correttamente la Tensione ai capi della Resistenza di Terra. Controllare che i coccodrilli effettuino un buon contatto con i picchetti ausiliari. Nel caso di terreno arido o poco conduttivo connettere più picchetti (collegatii in parallelo fra loro) al terminale B2.
>
> ```
> EARTH     05.06.02
>             - - - 
> Vd= 1V      Test:04
> RAVG=0.74 
>  Rp TROPPO ALTA
> 3-F
> FUNZ   CANC
> Resistenza del Circuito Voltmetrico (B2-B3) elevata
> ```

>  Il messaggio "**Rp e Rc TROPPO ALTA**" indica che lo strumento rileva una Resistenza elevata sia nel circuito di generazione della corrente che nel circuito di misura della Tensione. Controllare tutti i collegamenti ed eventualmente connettere più picchetti ai terminali B2 e B4 rispettivamente.
>
> ```
> EARTH     05.02.09
>             --- 
> Vd= 1V      Test:04
> RAVG=0.74 
> Rc e Rp ALTE
> 3-F
> Resistenza del Circuito Voltmetrico (B2-B3) e del Circuito Amperometrica (B1–B4) elevate
> FUNZ   CANC
> ```
>
I PRECEDENTI RISULTATI NON POSSONO ESSERE MEMORIZZATI.

>  Se la resistenza misurata è superiore a 1999 `Ω` lo strumento visualizza la videata a lato. Controllare i collegamenti.
>
> ```
> EARTH     05.06.02
> Il simbolo ">" indica che il valore della Resistenza è superiore al valore massimo misurabile
> > 1999 
> Vd= 1V      Test:04
> RAVG=0.74 
> 3-F
> FUNZ   CANC
> ```
>
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

>  Se la resistività misurata è superiore a 1999k `Ω`m lo strumento visualizza la videata a lato. Controllare i collegamenti.
>
> ```
> EARTH     05.06.02
> Il simbolo ">" indica che il valore della Resistenza è superiore al valore massimo misurabile
> > 1999 k  m
> Vd= 1V      Test:04
>  AVG=0.74k  m
>   DIST=5m
> FUNZ   CANC      
> ```
>
I risultati visualizzati sono memorizzabili premendo **due volte** il tasto **SAVE** (vedi paragrafo 9.1).

## 6.6. LOW10A: PROVA DI CONTINUITÀ DEL CONDUTTORE DI PROTEZIONE CON UNA CORRENTE DI PROVA DI 10A (SOLO GSC57)

La misura è effettuata in accordo con le Normative EN60349-1 e EN60204-1.

> **ATTENZIONE**
> Prima di effettuare la prova di Continuità accertarsi che non ci sia tensione ai capi del conduttore da analizzare.
>
Selezionare la posizione **LOW `Ω` 10A**
La pressione di questo tasto consente di selezionare una delle due seguenti modalità di funzionamento:

*   Modalità "**RMIS**": lo strumento effettua la misura della Resistenza del Conduttore di Protezione in accordo con la Normativa EN60439-1 Quadri di Protezione e di Manovra in Bassa Tensione.
*   Modalità "**VCAD**": lo strumento misura la Caduta di Tensione ai capi del Conduttore di Protezione in accordo con la Normativa EN60204-1 ("Equipaggiamento Elettrico delle Macchine")

> **ATTENZIONE**
> Lo strumento effettua la prova con una corrente `≥` 10A solo se la resistenza è inferiore a circa 0.45 `Ω`.

<!-- Chunk: Pages 65-96 -->
### 6.6.1. Modalità "RMIS": procedura di misura e risultati

1.  Premendo il tasto `F1` selezionare la modalità "RMIS".
2.  Collegare i connettori dei cavi di misura ai terminali di ingresso dello strumento `B1`, `B2`, `B3`, `B4` come indicato nella seguente figura:

    ```
    B2   B3   B4
    B1 I1   I2   I3
    230V~ 50Hz 1.3A
    ```

    *Collegamento dello strumento per la modalità "RMIS"*
3.  Collegare i coccodrilli ai capi del conduttore in esame.
4.  Impostare il valore limite della resistenza tramite i tasti `F3` e `F4`.
5.  Collegare il cavo `C5700` allo strumento e ad una presa `230V~ 50Hz`.
6.  Premere il tasto `START`. Lo strumento avvierà la prova.

> **ATTENZIONE**
> La visualizzazione del messaggio "`MISURA…`" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali dello strumento.

>  Lo strumento a fine prova emette un doppio segnale acustico ad indicare che la prova è stata eseguita correttamente e visualizza una videata simile a quella a fianco.

```
LOW  10A   05.06.02
      0.107 
      13.4A
RMIS  RLIM:0.100 
Resistenza misurata
Corrente di Prova
Modalità di Funzionamento
FUNZ  
```

I risultati visualizzati sono memorizzabili premendo `due volte` il tasto `SAVE` (vedi paragrafo 9.1).

`START STOP`

### 6.6.2. Modalità "VCAD": procedura di misura e risultati

1.  Premendo il tasto `F1` selezionare la modalità "VCAD".
2.  Collegare i connettori dei cavi di misura ai terminali di ingresso dello strumento `B1`, `B2`, `B3`, `B4` come indicato nella seguente figura:

    ```
    B2   B3   B4
    B1 I1   I2   I3
    230V~ 50Hz 1.3A
    ```

    *Collegamento dello strumento per la modalità "VCAD"*
3.  Collegare i coccodrilli ai capi del conduttore in esame.
4.  Impostare il valore della Sezione del Conduttore tramite i tasti `F3` e `F4`.
5.  Collegare il cavo `C5700` allo strumento e ad una presa `230V~ 50Hz`.
6.  Premere il tasto `START`. Lo strumento avvierà la prova.

> **ATTENZIONE**
> La visualizzazione del messaggio "`MISURA…`" indica che lo strumento sta eseguendo la prova. Durante questa fase non scollegare i puntali.

>  Lo strumento a fine prova emette un doppio segnale acustico che segnala che la prova è stata eseguita correttamente e che la caduta di Tensione rientra nei limiti indicati nella Tabella 6, quindi visualizza una videata simile a quella a fianco.

```
LOW  10A   05.06.02
Caduta di Tensione ai capi del Conduttore riferita ad una Corrente di 10A
      1.07 v
      13.4A
      0.107 
VCAD  SEZIONE:0.5
Resistenza Misurata
Corrente di Prova
Modalità di Funzionamento
FUNZ  
```

I risultati visualizzati sono memorizzabili premendo `due volte` il tasto `SAVE` (vedi paragrafo 9.1).

| Sezione (mm²) | Massima Caduta di Tensione (V) | Normativa |
| :------------ | :----------------------------- | :-------- |
| 0,5           | 5                              | ---       |
| 0,7           | 5                              |           |
| 1,0           | 3,3                            | EN 60204-1 |
| 1,5           | 2,6                            |           |
| 2,5           | 1,9                            |           |
| 4,0           | 1,4                            |           |
| 6,0           | 1,0                            |           |

Tabella 6: Valori limite per la caduta di tensione su di un conduttore equipotenziale in funzione della sezione.

`START STOP`

### 6.6.3. Situazioni anomale

>  Se lo strumento non rileva la presenza di alimentazione al connettore "`230V 50Hz`" visualizza il messaggio indicato a lato.

```
LOW  10A   05.06.02
- - - 
----A
 NO ALIMENTAZIONE
RMIS  RLIM=0.100 
FUNZ  
Modalità di Funzionamento
```

>  Se alla pressione del tasto `START` lo strumento rileva la connessione all'alimentatore esterno, visualizza il messaggio indicato a lato.

```
LOW  10A   05.06.02
Per motivi di sicurezza, lo strumento non esegue le prove di Verifica qualora sia collegato l'alimentatore esterno. Per eseguire la prova disconnettere l'alimentatore
- - - 
----A
 TOGLI ALIM.
RMIS  RLIM=0.100 
FUNZ  
I PRECEDENTI RISULTATI NON POSSONO ESSERE MEMORIZZATI.
```

>  Utilizzando la modalità `RMIS`, se lo strumento rileva una Resistenza superiore al limite impostato emette un segnale acustico prolungato e visualizza una schermata del tipo a lato.

```
LOW  10A   05.06.02
Il simbolo  indica una resistenza superiore al limite impostato
 0.323 
9.12A
RMIS  RLIM=0.100 
Corrente di Prova
FUNZ  
```

I risultati visualizzati sono memorizzabili premendo `due volte` il tasto `SAVE` (vedi paragrafo 9.1).

>  Utilizzando la modalità `RMIS`, se lo strumento rileva una Resistenza superiore al massimo valore misurabile emette un segnale acustico prolungato e visualizza una schermata del tipo a lato.

```
LOW  10A   05.06.02
il simbolo">" indica una Resistenza superiore al valore massimo misurabile
 >0.999 
9.12A
RMIS  RLIM=0.100 
corrente di Prova
FUNZ  
```

I risultati visualizzati sono memorizzabili premendo `due volte` il tasto `SAVE` (vedi paragrafo 9.1).

>  Utilizzando la modalità `VCAD`, se lo strumento rileva una Resistenza superiore al limite impostato emette un segnale acustico prolungato e visualizza una schermata del tipo a lato.

```
LOW  10A   05.06.02
 3.50 V
14.0A 0.350 
VCAD  SEZIONE:2.5
Caduta di Tensione
Corrente di Prova
Resistenza misurata
FUNC  
```

I risultati visualizzati sono memorizzabili premendo `due volte` il tasto `SAVE` (vedi paragrafo 9.1).

>  Utilizzando la modalità `VCAD`, se lo strumento rileva una Caduta di Tensione superiore al massimo valore misurabile emette un segnale acustico prolungato e visualizza una schermata del tipo a lato.

```
LOW  10A   05.06.02
il simbolo">" indica una Caduta di Tensione superiore al valore massimo misurabile
 >9.99 V
----A >0.999 
VCAD  SEZIONE:2.5
FUNZ  
```

I risultati visualizzati sono memorizzabili premendo `due volte` il tasto `SAVE` (vedi paragrafo 9.1).

## 7. AUX: MISURA CON SONDE AUSILIARIE

Selezionare la posizione del commutatore `AUX`.

>  La pressione del tasto `F4` consente di accedere ad una delle seguenti modalità di Funzionamento (che si presentano in ordine ciclico):
>
> *   `AUX`: Misura di Parametri Ambientali e Correnti di Dispersione (`mA`, `°C`, `°F`, `HR%`, `m/s`, `mV`, `Lux`)
> *   `SOUND`: Rilevazioni Fonometriche

La modalità "`AUX: Misura di Parametri Ambientali e Correnti di Dispersione`" consente:

*   Visualizzare in `Tempo reale` i valori provenienti da sonde esterne o pinze.
*   `Memorizzare` i valori visualizzati a display (tramite pressione del tasto `SAVE`).
*   `Registrare` (tramite pressione del tasto `START`, previa opportuna impostazione dello strumento) fino a 3 segnali in ingresso simultaneamente proveniente da sonde esterne (non necessariamente dello stesso tipo). I valori Registrati saranno analizzabili solo tramite trasferimento dei dati medesimi ad un PC.
*   `Registrare` (tramite pressione del tasto `START`) il segnale di ingresso con uso di “`Configurazioni Tipiche`” i cui parametri sono predefiniti sullo strumento (vedere il paragrafo 7.2.2). I valori Registrati saranno analizzabili solo tramite trasferimento dei dati medesimi ad un PC.

> **ATTENZIONE**
> Si invita l'operatore a focalizzare fin d'ora la sostanziale differenza fra "`memorizzare i valori visualizzati`" e "`registrare i valori di un segnale`". Il termine "`memorizzare i valori visualizzati`" lascia intendere che vengono archiviati in memoria solo i valori visualizzati sul display al momento della pressione del Tasto `SAVE`. Il termine "`registrare i valori di un segnale`" sottintende invece il monitoraggio del segnale stesso con archiviazione periodica ed automatica dei dati rilevati da parte dello strumento per un tempo solitamente lungo.

### 7.1. MISURA IN TEMPO REALE DI PARAMETRI AMBIENTALI E CORRENTE DI DISPERSIONE

Questa modalità consente di eseguire misure in tempo reale e registrazioni di parametri ambientali e corrente di dispersione.

1.  Premere `F4` fino ad accedere alla modalità "`AUX`".
2.  La pressione ciclica dei Tasti Funzione `F1`, `F2`, `F3` consente di selezionare il tipo di sonda connessa agli ingressi `I1`, `I2`, `I3` rispettivamente. In particolare:

    *   `- - -` (Ingresso Disabilitato)
    *   `mA` (Misura della Corrente di Dispersione)
    *   `°C` (Misura di Temperatura espressa in `°C`)
    *   `°F` (Misura di Temperatura espressa in `°F`)
    *   `HR%` (Umidità Relativa)
    *   `m/s` (Velocità dell'Aria)
    *   `mV` (Tensione)
    *   `LUX (20)` (Illuminamento: Fondo Scala 20Lux)
    *   `LUX (2k)` (Illuminamento: Fondo Scala 2kLux)
    *   `LUX (20k)` (Illuminamento: Fondo Scala 20kLux)
3.  Collegare la/le sonde agli ingressi dello strumento facendo attenzione alla corrispondenza fra ingresso collegato ed unità di misura impostata.
4.  Controllare se l'eventuale selettore presente sulle sonde o sulle pinze sia correttamente impostato. Il fondo scala impostato sulla sonda deve sempre corrispondere al fondo scala impostato sullo strumento.

    ```
    B1   B2   B3   B4
    I3 I2 I1
    ```

    *Esempio di collegamento di sonde esterne.*

> **ATTENZIONE**
> La posizione `OFF` del Selettore di alcune sonde porta ai terminali di uscita della sonda stessa il valore attuale della Tensione delle Batterie (circa 9V). Questa tensione (molto maggiore del Fondo scala di 1V previsto) potrebbe influenzare la lettura sugli altri ingressi. Pertanto NON lasciare collegate allo strumento sonde con il selettore in posizione `OFF`.

```
B1   B2   B3   B4
I3 I2 I1
Fase Neutro PE (Conduttore di Protezione)
Impianto o Carico Monofase
Eventuali pinze Addizionali
```

*Misura Indiretta della corrente di dispersione in sistemi monofase*

```
B1   B2   B3   B4
I3 I2 I1
R S T N PE (Conduttore di Protezioner)
Sistema o carico TRIFASE
Eventuali Pinze Aggiuntive
```

*Misura Indiretta della corrente di dispersione in sistemi trifase*

```
B1   B2   B3   B4
I3 I2 I1
Fase Neutro PE (Conduttore di Protezione)
Impianto o Carico Monofase
Eventuali pinze aggiuntive
X
Scollegare eventuali connessioni di Terra aggiuntive
```

*Misura diretta della corrente di dispersione in sistemi monofase*

```
B1   B2   B3   B4
I3 I2 I1
R S T N PE (Conduttore di Protezione)
Sistema o Carico TRIFASE
Eventuali Pinze Aggiuntive
X
Scollegare eventuali connessioni di Terra aggiuntive
```

*Misura diretta della corrente di dispersione in sistemi trifase*

5.  Lo strumento visualizza in tempo reale il valore degli ingressi NON Disabilitati.

    >  Esempio di Videata
    ```
    05.06.02   11:43:04
    AUX
    In1= 23°C   Esempio Temperatura
    In2= 23mA   Esempio di Corrente di Dispersione
    In3= - - -   Esempio di Canale disabilitato
    In1   In2   In3   PG+
    ```
6.  Premere questo tasto per abilitare/disabilitare la Funzione `HOLD` (i valori visualizzati sul display verranno bloccati). L'attivazione della funzione `HOLD` è indicata da messaggio `HOLD` visualizzato sul display.
7.  I risultati visualizzati sono memorizzabili premendo `due volte` il tasto `SAVE` (vedi paragrafo 9.1).

### 7.2. REGISTRAZIONE DI PARAMETRI AMBIENTALI E CORRENTE DI DISPERSIONE

Prima di avviare una Registrazione si raccomanda di controllare l'indicazione in tempo reale secondo quanto descritto al paragrafo 7.1. È inoltre fondamentale controllare che l'impostazione dello strumento corrisponda alle sonde e/o pinze effettivamente connesse agli ingressi dello strumento. A questo scopo premere il tasto `MENU` e controllare la voce `CONFIG RECORDER` secondo quanto descritto nel prossimo paragrafo.

#### 7.2.1. CONFIG RECORDER: impostazioni di base per registrazione AUX

Selezionare la posizione `AUX`, premere il tasto `MENU` ed utilizzando il tasto `F1` o `F2` selezionare la voce `CONFIG RECORDER`. Premere `ENTER`.

> **ATTENZIONE**
> Non è possibile accedere al `MENU` durante una registrazione in corso.

```
MENU GENERALE
MEMORIA SAFETY TEST
MEMORIA ANALYZER
RESET CONFIG ANALYZER
CONFIG RECORDER
CONTRASTO
DATA&ORA
LINGUA
   
```

La Voce `CONFIG RECODER` consente di controllare ed eventualmente modificare i parametri di Registrazione e gli ingressi da Registrare (fino ad un Massimo di 3). Il MENU `CONFIG RECORDER` è diviso in 2 sotto-pagine:

*   **1^ pagina**: Questa pagina permette di impostare la modalità di Avvio Registrazione (`AUTO` o `MANUALE`), la Data di Avvio/Arresto (per la modalità `AUTO`) ed il `Periodo di Integrazione`. Premere `ENTER` per confermare le impostazioni e passare alla pagina successiva o `ESC` per abbandonare le modifiche effettuate ed uscire dal `MENU CONFIG RECORDER`.
*   **2^ pagina**: Questa pagina consente la selezione degli Ingressi da Registrare. Posizionare la freccia in corrispondenza di un ingresso (`IN1`, `IN2` o `IN3`) attraverso la pressione dei tasti `F1` / `F2`. Selezionare l’ingresso premendo il tasto `F3` o deselezionarlo premendo il tasto `F4`. Gli ingressi selezionati sono riportati in scritte bianche in campo nero. Premere `ENTER` per confermare le impostazioni e passare alla pagina successiva o `ESC` per abbandonare le modifiche effettuate e tornare alla pagina precedente.

Le pagine del MENU `CONFIG RECORDER` possono essere schematizzate come segue:

```
CONFIG RECORDER                     CONFIG RECORDER
START MANU                          INGRESSI AUSILIARI:
STOP MANU                           IN1
INT. PERIOD: 15min                  IN2
      +   - ENTER                 IN3
                                         +   -
Utilizzare i tasti F1/F2 per posizionare il cursore sulla
voce desiderata ed utilizzare i tasti F3/F4 per modificarne
il valore. Premere ENTER per confermare i valori impostati
e passare alla 2a Pagina mantenendo le impostazioni
effettuate. Premere ESC per uscire dalla modalità "MENU"
senza salvare le impostazioni effettuate.
MENU
 Per selezionare la modalità di Avvio registrazione
MANUALE/AUTOMATICA posizionare il cursore su MANU o AUTO
tramite i tasti F1 o F2 e selezionare l'impostazione
desiderata tramite i tasti F3 e F4. Premere ENTER per
confermare la selezione ed uscire. Premere ESC per uscire
da questa videata senza salvare le impostazioni effettuate.
Premendo ESC si esce dalla modalità CONFIG RECORDER
perdendo le modifiche apportate sia in questa videata, sia
in quella precedente.
Utilizzare i tasti multifunzione F1 / F2 per posizionare il
cursore sulla Grandezza desiderata ed utilizzare i tasti
multifunzione F3 / F4 per selezionare/deselezionare
(marcata in nero = selezionata).
```

*1^ Pagina del MENU CONFIG RECORDER* (left screenshot description)
*2^ Pagina del MENU CONFIG RECORDER* (right screenshot description)

NOTA: gli ingressi selezionati nella precedente videata devono corrispondere agli ingressi effettivamente abilitati per la misura in Tempo Reale. Se per esempio l'ingresso `IN3` fosse disabilitato nella misura in Tempo reale (vedi paragrafo 7.1) ma selezionato per la Registrazione, alla pressione del tasto `START` lo strumento visualizza il messaggio "`Errore selezione`".

| Simbolo        | Descrizione                                                                                                                                                                                                                                                                                                                           | Impostazioni consigliate |
| :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :----------------------- |
| `START:MAN`    | La registrazione di tutte le Grandezze selezionate verrà avviata all'inizio del primo minuto successivo alla pressione del tasto `START/STOP` da parte dell'operatore.                                                                                                                                                                    |                         |
| `STOP:MAN`     | La registrazione di tutte le Grandezze selezionate verrà arrestata `Manualmente` dall'operatore previa pressione del tasto `START/STOP`.                                                                                                                                                                                                |                         |
| `START:AUTO` `STOP:AUTO` | La registrazione di tutte le Grandezze selezionate verrà avviata/arrestata alla Data e Ora impostate. Per avviare la registrazione l'operatore dovrà comunque premere il tasto `START/STOP` per impostare lo strumento in Stand-By in attesa del raggiungimento della Data e Ora di Avvio impostate.                                   |                          |
| `PERIODO INT`  | Il valore di questo parametro determina ogni quanti secondi verranno archiviati nella memoria dello strumento i valori di tutte le Grandezze selezionate (vedi paragrafo 17.13.1). Valori disponibili: 5s,10s,30s,1min,2min,5min,10min,15min,30min,60min.                                                                            |  `15min`                |
| `IN1`, `IN2`, `IN3` | Valore dei 3 ingressi `IN1`, `IN2`, `IN3`.                                                                                                                                                                                                                                                                                            |  `IN1`, `IN2`, `IN3`    |

Per gli eventuali messaggi visualizzati sul display dello strumento si veda Appendice 1 – Messaggi del DISPLAY

#### 7.2.2. REGISTRAZIONI: utilizzo delle configurazioni tipiche

Lo scopo di questa funzione è quello di selezionare alcune registrazioni tipiche con parametri `predefiniti`, allo scopo di consentire all’operatore un utilizzo semplice e immediato dello strumento. Sono disponibili le seguenti possibilità:

| Configurazione tipica | Descrizione                                                                                                                |
| :-------------------- | :------------------------------------------------------------------------------------------------------------------------- |
| `DISPERSIONE (I1)`  | Impostazione del modo di misura e registrazione della `Corrente di Dispersione` sul canale `I1`.                             |
| `TEMP. °C(I1)`      | Impostazione del modo di misura e registrazione della `Temperatura in °C` sul canale `I1`.                                   |
| `UMIDITA %HR(I1)`   | Impostazione del modo di misura e registrazione della `Umidità Relativa %HR` sul canale `I1`.                                |

Per l’attivazione delle configurazioni operare come segue:

1.  Selezionare la posizione “`AUX`” del selettore.
2.  Premere il tasto `MENU`. Lo strumento mostra il “Menù Generale” seguente:

    ```
    MENU GENERALE
    MEMORIA SAFETY TEST
    MEMORIA ANALYZER
    RESET CONFIG ANALYZER
    CONFIG RECORDER
    CONTRASTO
    DATA&ORA
    LINGUA
       
    ```
3.  Premere nuovamente il tasto `MENU`. Lo strumento mostra la schermata presente nella parte sinistra della figura seguente in cui è possibile selezionare con i tasti freccia `F1` o `F2` la configurazione desiderata sul canale `I1` dello strumento:

    ```
    CONFIG. TIPICHE                   CONFIG. TIPICHE
    DISPERSIONE(I1)                   DISPERSIONE(I1)
    TEMP.°C(I1)                       TEMP.°C(I1)
    UMIDITA %HR(I1)                   UMIDITA %HR(I1)
                                    Dati salvati
    Selezione Configurazione             
    Conferma configurazione scelta
    ```
4.  Premere il tasto `ENTER`. Lo strumento presenta per alcuni secondi il messaggio “`Dati salvati`” che conferma la configurazione scelta, come mostrato nella parte destra della figura soprastante. Lo strumento si riporta quindi nella schermata iniziale di misura.

## 8. ANALYZER: ANALIZZATORE DI RETE

### 8.1. IMPOSTAZIONI DI BASE: CONFIG ANALYZER

Posizionare il selettore nella posizione `ANALYZER`, premere il tasto `MENU` e utilizzando i tasti `F1` / `F2` selezionare la voce `CONFIG ANALYZER`, premere `ENTER`. Il display dello strumento visualizzerà la seguente pagina:

```
CONFIG ANALYZER
SISTEMA   :3FILI
FREQUENZA:50HZ
FS CORRENTE:1000A
PINZA TIPO: FlexINT
RAPP TV:0001
PASSWORD:ON
      +   -
```

Per modificare le impostazioni attenersi a quanto riportato nei seguenti paragrafi. Al termine premere `ENTER` per confermare le impostazioni o `ESC` per abbandonare le modifiche effettuate ed uscire dal `MENU CONFIG ANALYZER`. Le impostazioni effettuate rimarranno valide anche dopo lo spegnimento dello strumento.

#### 8.1.1. SISTEMA

Questo parametro consente di selezionare il tipo di sistema elettrico che si sta analizzando. In particolare sono disponibili le seguenti configurazioni:

*   Sistema monofase
*   Sistema "`a 3 fili`" (Sistema Trifase senza Neutro) (vedi Paragrafo 17.12.2)
*   Sistema "`a 4 fili`" (Sistema Trifase con Neutro)

Le connessioni agli ingressi dello strumento dovranno essere coerenti con il tipo di sistema selezionato. Posizionare il cursore sulla voce in oggetto utilizzando i tasti `F1` e `F2` e, tramite i tasti `F3` e `F4`, impostare il valore desiderato.

#### 8.1.2. FREQUENZA

Posizionare il cursore sulla voce corrispondente utilizzando i tasti `F1` e `F2` e, tramite i tasti `F3` e `F4`, selezionare la frequenza di rete fra i due possibili valori `50Hz` e `60Hz`. Questo parametro è rilevante SOLO se il valore della Tensione in ingresso non è sufficiente per il riconoscimento del valore della frequenza (Es.: sono collegate solo le pinze per la misura della corrente). In questo caso lo strumento genera un sincronismo interno pari al valore della frequenza impostata.

#### 8.1.3. FS CORRENTE

Il valore di questo parametro `deve essere sempre uguale al fondo scala delle pinze` di corrente utilizzate per la misura. Nel caso di utilizzo di pinze multiscala, questo parametro deve assumere lo stesso valore del fondo scala selezionato sulle pinze stesse. Posizionare il cursore sulla voce corrispondente utilizzando i tasti `F1` e `F2` e, tramite i tasti `F3` e `F4`, impostare il valore desiderato.

#### 8.1.4. PINZA TIPO

Il valore di questo parametro `deve essere sempre uguale al tipo di pinza utilizzata`. Le pinze sono state suddivise in due categorie:

*   `STD`: pinza con Nucleo in materiale ferromagnetico o Trasformatore di corrente.
*   `FlexEXT`: pinza con Toroide flessibile con elettronica di controllo esterna.
*   `FlexINT`: pinza con Toroide flessibile priva di elettronica di controllo propria (solo per il modello GSC59).

Posizionare il cursore sulla voce corrispondente utilizzando i tasti `F1` e `F2` e, tramite i tasti `F3` e `F4`, impostare il valore desiderato. Per memorizzare le impostazioni effettuate premere il tasto `ENTER`. Le impostazioni effettuate rimarranno valide anche dopo lo spegnimento dello strumento. Per abbandonare le modifiche effettuate premere il tasto `ESC`.

> **ATTENZIONE**
> Qualora si selezioni l’opzione “`FlexINT`” (`solo per il modello GSC59`) il fondo scala della corrente è impostabile solo a 1000A o 3000A.

#### 8.1.5. RAPP. TV

Lo strumento consente l'interfacciamento anche con eventuali Trasformatori di Tensione (`TV`) presenti nell'impianto in esame visualizzando il valore delle Tensioni presenti sul primario dei Trasformatori stessi. A tal fine è necessario impostare il valore del rapporto di trasformazione dei Trasformatori Voltmetrici presenti. Posizionare il cursore sulla voce corrispondente utilizzando i tasti `F1` e `F2` e, tramite i tasti `F3` e `F4`, impostare il valore desiderato.

#### 8.1.6. PASSWORD

Lo strumento è dotato di una routine di protezione per evitare che, durante una registrazione o una misura dell'Energia, lo strumento possa essere manomesso o la misurazione interrotta. Se si è avviata una registrazione o misura diretta dell'Energia (con l'opzione `PASSWORD` abilitata), trascorsi circa 3 minuti dall'ultima pressione di un tasto o rotazione del commutatore, qualora venga premuto il tasto `START/STOP` (se è in corso una registrazione) o `F2` (se è in corso una misura diretta dell'Energia) lo strumento non arresterà la registrazione bensì richiederà l'inserimento della `PASSWORD`. L'inserimento della password (non modificabile) comporta la pressione in sequenza dei seguenti tasti (entro 10 secondi):

`F1`, `F4`, `F3`, `F2`

Se viene inserita una password errata o se si impiega più di 10 secondi per inserirla verrà visualizzato il messaggio "`Password Errata`". Per abilitare/disabilitare questa opzione posizionare il cursore sulla voce corrispondente utilizzando i tasti `F1` e `F2` e, tramite i tasti `F3` e `F4`, `ABILITARE/DISABILITARE` l'opzione della password.

### 8.2. IMPOSTAZIONI DI BASE: CONFIG RECORDER

Questa modalità consente di visualizzare, ed eventualmente modificare, i parametri di registrazione e le grandezze da registrare (fino ad un massimo di 63). Se il numero dei parametri selezionati eccede il valore massimo viene visualizzato il messaggio “`Troppi Par sel`”. La modalità “`CONFIG RECORDER`” è suddivisa in 4 sotto-pagine:

*   **1^ Pagina**: Questa pagina consente l’impostazione della modalità di Avvio o Arresto della Registrazione e della relativa data (se impostata), del Periodo di Integrazione (vedi paragrafo 17.13.1), l’abilitazione/disabilitazione dell’analisi delle anomalie di Tensione (vedi paragrafo 17.10), l’abilitazione/disabilitazione dell’analisi delle Armoniche (vedi paragrafo 17.11). Premere il tasto `ENTER` per confermare le impostazioni e passare alla pagina successiva. Premere il tasto `ESC` per uscire dal Menu senza modificare le impostazioni.
*   **2^ Pagina**: Pagina dedicata alle impostazioni relative alla registrazione della Tensione e delle Anomalie di Tensione. Premere il tasto `ENTER` per confermare le impostazioni e passare alla pagina successiva. Premere il tasto `ESC` per uscire dal `MENU` senza modificare le impostazioni. Da questa Pagina si può accedere alla sotto-Pagina "`ARMONICHE TENSIONE`" che consente di selezionare le Armoniche di Tensione che si intende registrare. Per entrare nella sotto-pagina delle Armoniche, posizionare il cursore su `Pg` e premere il tasto `F3`. Premere il tasto `ENTER` per confermare la selezione delle Armoniche e tornare alla 2^ Pagina del `MENU`. Premere il tasto `ESC` per uscire dal "`Menu Armoniche`" senza modificare le impostazioni.
*   **3^ Pagina**: Pagina dedicata alle impostazioni relative alla registrazione della Corrente. Premere il tasto `ENTER` per confermare le impostazioni e passare alla pagina successiva. Premere il tasto `ESC` per uscire dal `MENU` senza modificare le impostazioni. Da questa Pagina si può accedere alla sotto-Pagina "`ARMONICHE CORRENTE`" che consente di selezionare le Armoniche di Corrente che si intendono registrare. Per entrare nella sotto-pagina delle Armoniche, posizionare il cursore su `Pg` e premere il tasto `F3`. Premere il tasto `ENTER` per confermare la selezione delle Armoniche e tornare alla 3^ Pagina del `MENU`. Premere il tasto `ESC` per uscire dal "`Menu Armoniche`" senza modificare le impostazioni. Questa pagina consente la selezione/deselezione del parametro “`COGENERAZIONE`”. Selezionarlo solo quando all’interno dell’impianto in esame sono presenti dei generatori. Premere il tasto `ENTER` per confermare le impostazioni e passare alla pagina successiva. Premere il tasto `ESC` per uscire dal `MENU` senza modificare le impostazioni.
*   **4^ Pagina**: Questa pagina consente la selezione/deselezione del parametro “`COGENERAZIONE`”. Selezionarlo solo quando all’interno dell’impianto in esame sono presenti dei generatori. Premere il tasto `ENTER` per confermare le impostazioni e passare alla pagina successiva. Premere il tasto `ESC` per uscire dal `MENU` senza modificare le impostazioni. Da questa pagina si può accedere alle due sotto-pagine dedicate alla selezione delle Potenze ed Energie che si intendono registrare. Per entrare nelle rispettive sotto-pagine posizionare il cursore su `POTENZA` o `ENERGIA` e premere il tasto `F3`. Selezionando/deselezionando i simboli corrispondenti alle Potenze vengono automaticamente selezionate/deselezionate anche le corrispondenti Energie. Premere il tasto `ENTER` per confermare la selezione effettuata nella sotto-pagina delle Potenze o Energie e tornare alla 4^ Pagina del `MENU`. Premere il tasto `ESC` per uscire dalla sotto-pagina `POTENZA` o `ENERGIA` senza modificare le impostazioni.

*Esempio di Videata della 1^ Pagina del "MENU"*

```
CONFIG RECORDER
START MANU
STOP MANU
PERIODO INT: 15min
REG.HARM: ON
REG ANOM: ON
      +   -
MENU
 Utilizzare i tasti F1/F2 per posizionare il cursore sulla voce desiderata
ed utilizzare i tasti F3/F4 per modificarne il valore. Premere ENTER per
confermare i valori impostati nelle Pagine del MENU e passare alla 2a
Pagina mantenendo le impostazioni effettuate. Premere ESC per uscire
dalla modalità "MENU" senza salvare le impostazioni effettuate. Se il
flag REG.ANOM è OFF nella 2a pagina non compariranno la Vref e le
relative soglie per l’analisi delle Anomalie di Tensione.
```

*Esempio di 2^ Pagina del "MENU" in modalità Monofase con Flag “REG ANOM” selezionato*

```
CONFIG RECORDER
TENSIONI: V1
REG HARM: Pg (ON)
Vref P-N: 230V
LIM +: 06% (243.8V)
LIM -: 10% (207.0V)
      +   -
ENTER
 Utilizzare i tasti multifunzione F1 / F2 per posizionare il cursore
sull'Armonica di Tensione desiderata ed utilizzare i tasti multifunzione
F3 / F4 per selezionarne/deselezionarne la registrazione (marcata in
nero = selezionata). Premere ENTER per confermare le modifiche e
tornare alla 2a pagina. Premere ESC per uscire da questa videata senza
salvare le impostazioni effettuate.
Per selezionare la modalità di Avvio registrazione MANUALE/AUTOMATICA
posizionare il cursore su MANU o AUTO tramite i tasti F1 o F2 e
selezionare l'impostazione desiderata tramite i tasti F3 e F4. Se si
desidera modificare la selezione delle Armoniche posizionare il
cursore su Pg premere F3. Utilizzare i tasti F1 / F2 per posizionare
il cursore sulla Grandezza desiderata ed utilizzare i tasti F3 / F4
per selezionare/deselezionare (marcata in nero = selezionata). Premere
ENTER per confermare la selezione effettuata e passare alla 2a pagina.
Premere ESC per uscire da questa videata senza salvare le
impostazioni effettuate. Lo strumento registrerà nel tempo i valori
delle Armoniche Selezionate corrispondenti alle Tensioni selezionate
nella 2a pagina del Menu precedentemente illustrato.
```

*Esempio di 2^ Pagina del "MENU" in modalità Trifase 3 fili con Flag “REG ANOM” selezionato*

```
CONFIG RECORDER
TENSIONI: V12 V32 V31
REG HARM: Pg (ON)
Vref P-P: 400V
LIM +: 06% (424.0V)
LIM -: 10% (360.0V)
      +   -
```

*Esempio di 2^ Pagina del "MENU" in modalità Trifase 4 fili con Flag “REG ANOM” selezionato*

```
CONFIG RECORDER
TENSIONI: V1 V2 V3 V12 V32 V31
REG HARM: Pg (ON)
Vref P-N: 230V
LIM +: 06% (243.8V)
LIM -: 10% (207.0V)
      +   -
```

*Esempio di Videata del "Menu Armoniche"*

```
CONFIG RECORDER
ARMONICHE:TENSIONE
Thd DC 01 02 03
04 05 06 07 08 09
10 11 12 13 14 15
16 17 18 19 20 21
22 23 24 25 26 27
28 29 30 31 32 33
34 35 36 37 38 39
40 41 42 43 44 45
46 47 48 49
      +   -
```

*Dalla 2^ Pagina del MENU*

```
Utilizzare i tasti F1 / F2 per posizionare il cursore sulla voce desiderata ed utilizzare i tasti F3 / F4 per modificarne il valore o selezionare/deselezionare (marcata in nero = selezionata) la Grandezze desiderata. Premere ENTER per confermare i valori impostati nelle Pagine del MENU ed uscirne mantenendo le impostazioni effettuate. Premere ESC per uscire e tornare alla 1^ pagina del "MENU" senza salvare le impostazioni effettuate.
```

*Esempio di Videata della 3^ Pagina in modalità Monofase*

```
CONFIG RECORDER
CORRENTI: I1
REG HARM: Pg (ON)
      +   -
```

*Esempio di Videata della 3^ Pagina in modalità Trifase 3 fili*

```
CONFIG RECORDER
CORRENTI: I1 I2 I3
REG HARM: Pg (ON)
      +   -
```

*Esempio di Videata della 3^ Pagina in modalità Trifase 4 fili*

```
CONFIG RECORDER
CORRENTI: I1 I2 I3 IN
REG HARM: Pg (ON)
      +   -
```

*Esempio di Videata del "Menu Armoniche"*

```
CONFIG RECORDER
ARMONICHE:CORRENTE
Thd DC 01 02 03
04 05 06 07 08 09
10 11 12 13 14 15
16 17 18 19 20 21
22 23 24 25 26 27
28 29 30 31 32 33
34 35 36 37 38 39
40 41 42 43 44 45
46 47 48 49
      +   -
ENTER
 Utilizzare i tasti F1 / F2 per posizionare il cursore sull'Armonica di Corrente desiderata ed utilizzare i tasti F3 / F4 per selezionare/deselezionare (marcata in nero = selezionata) la grandezza selezionata. Premere ENTER per confermare la selezione effettuata. Premere ESC per uscire da questa videata senza salvare le impostazioni effettuate. Lo strumento registrerà nel tempo i valori delle Armoniche Selezionate corrispondenti alle Correnti selezionate nella 2a pagine del Menu precedentemente illustrato. Se si desidera modificare la selezione delle Armoniche posizionare il cursore su ON o OFF premere F3.
```

*Esempio di Videata della 4^ Pagina del "MENU"*

```
CONFIG RECORDER
COGENERAZIONE: ON
POTENZA: Pg
ENERGIA: Pg
      +   -
```

> **ATTENZIONE**
> Selezionando per la registrazione le Potenze Attive sono automaticamente selezionate anche le corrispondenti Energie Attive. Analogamente selezionando per la registrazione le Potenze Reattive sono automaticamente selezionate anche le corrispondenti Energie Reattive.

*Esempio di Videata della Sotto-Pagina del MENU POTENZA in modalità Monofase*

```
CONFIG RECORDER
POTENZA P1 Q1i Q1c S1 Pf1 dPf1
      +   -
```

*Esempio di Videata della Sotto-Pagina del MENU POTENZA in modalità Trifase 3 fili*

```
CONFIG RECORDER
POTENZA Pt P12 P32
Qti Q12i Q32i
Qtc Q12c Q32c
St S12 S32
Pft dPft
      +   -
```

*Esempio di Videata della Sotto-Pagina del MENU POTENZA in modalità Trifase 4 fili*

```
CONFIG RECORDER
POTENZA Pt P1 P2 P3
Qti Q1i Q2i Q3i
Qtc Q1c Q2c Q3c
St S1 S2 S3
Pfi Pf1 Pf2 Pf3
dPfi dPf1 dPf2 dPf3
      +   -
Per selezionare le Potenze da Registrare utilizzare i tasti F1/F2
e posizionare il Cursore su POTENZA: Pg
ENTER
 Per selezionare le Energie da Registrare utilizzare i tasti F1/F2
e posizionare il Cursore su ENERGIA: Pg (vedi pagina successiva)
Se si desidera modificare la selezione delle Potenze posizionare il Cursore
sul simbolo "Pg" a fianco di "POTENZA" e premere F3.
```

*Dalla 3^ Pagina del MENU*

*Esempio di Videata della Sotto-Pagina del MENU ENERGIE in modalità Monofase*

```
CONFIG RECORDER
ENERGIA Ea1 Eri1 Erc1 Es1
      +   -
```

*Esempio di Videata della Sotto-Pagina del MENU ENERGIE in modalità Trifase 3 fili*

```
CONFIG RECORDER
ENERGIA Eat Erit Erct Est
      +   -
```

*Esempio di Videata della Sotto-Pagina del MENU ENERGIE in modalità Trifase 4 fili*

```
CONFIG RECORDER
ENERGIA Eat Ea1 Ea2 Ea3
Erit Eri1 Eri2 Eri3
Erct Erc1 Erc2 Erc3
      +   -
ENTER
 Se si desidera modificare la selezione delle Energie posizionare il Cursore sul simbolo "Pg" a fianco di "ENERGIA" e premere F3.
```

> **ATTENZIONE**
> Selezionando per la registrazione le Energie Attive sono automaticamente selezionate anche le corrispondenti Potenze Attive. Analogamente selezionando per la registrazione le Energie Reattive sono automaticamente selezionate anche le corrispondenti Potenze Reattive.

*Dalla 3^ Pagina del MENU*

| Simbolo                      | Descrizione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Impostazioni consigliate  |
| :--------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------ |
| `START:MANU`                 | La registrazione di tutte le grandezze selezionate verrà avviata all'inizio del primo minuto successivo alla pressione del tasto `START/STOP` (vedi cap. 10.1).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |                          |
| `STOP:MANU`                  | La registrazione di tutte le Grandezze selezionate verrà arrestata `Manualmente` dall'operatore previa pressione del tasto `START/STOP` (vedi Capitolo 10.4).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |                          |
| `START:AUTO` `STOP:AUTO`     | La registrazione di tutte le Grandezze selezionate verrà avviata/arrestata alla data e ora impostate. Per avviare la registrazione l'operatore dovrà comunque premere il tasto `START/STOP` per impostare lo strumento in stand-by in attesa del raggiungimento della data e ora di avvio impostate (vedi cap. 10.1).                                                                                                                                                                                                                                                                                                                                            |                           |
| `PERIODO INT`                | Il valore di questo parametro determina ogni quanti secondi verranno archiviati nella memoria dello strumento i valori di tutte le Grandezze selezionate (vedi Paragrafo 17.13). Valori disponibili: 5s,10s,30s,1min,2min,5min,10min,15min,30min,60min.                                                                                                                                                                                                                                                                                                                                                                                                           |  `15min`                 |
| `REG HARM`                   | `ON` = lo strumento registrerà nel tempo i valori delle Armoniche Selezionate nelle Pagine successive corrispondenti alle Tensioni e Correnti selezionate.<br/>Esempio: Se sono state selezionate solo:<br/>a) le Tensioni di Fase 1 e 2, il THD e le Armoniche 1,3,5<br/>b) le Correnti di Fase 2 e 3, il THD e le Armoniche 3,5,7<br/>lo strumento registrerà:<br/>a) le Tensioni di Fase 1 e 2, il THD e le Armoniche 1,3,5 per le Tensioni 1 e 2 mentre non registrerà alcuna valore né armonica per la fase 3<br/>b) le Correnti di Fase 2 e 3, il THD e le Armoniche 3,5,7 per le Correnti 2 e 3 mentre non registrerà alcuna valore né armonica per la fase 1<br/>`OFF` = lo strumento non registrerà nel tempo `nessuna` delle Armoniche di Tensione o Corrente selezionate. |                          |
| `REG ANOM`                   | `ON` = Lo strumento registrerà le anomalie di tensione (vedi par. 17.10)<br/>`OFF` = Lo strumento NON registrerà le Anomalie di Tensione.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |                          |
| `V1`, `V2`, `V3` `V12`, `V23` o `V32`, `V31` | Valore Efficace rispettivamente della Tensione di Fase 1, Fase 2, Fase 3, Valori delle Tensione concatenate 1-2, 2-3 o 3-2 e 3-1.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |  Monofase: `V1`<br/>3 fili: `V12 V32 V31`<br/>4 fili: `V1`, `V2`, `V3` |
| `THD`, `DC`, `01..49`        | Distorsione Armonica Totale, Componente Continua, Armonica dalla prima alla 49-esima.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |  `THD`, `01`, `03`, `05`, `07` |
| `Vref` (solo se il flag `REG. ANOM` è settato `ON`) | Valore `RMS` di riferimento per l’analisi delle Anomalie di Tensione. Tale valore è:<br/>a) tensione fase-neutro per i sistemi monofase e trifase 4 fili<br/>b) tensione fase-fase per i sistemi trifase 3 fili.                                                                                                                                                                                                                                                                                                                                                                                                                     |  Monofase: `230V`<br/>3 fili: `400V`<br/>4 fili: `230V` |
| `LIM +`, `LIM -` (solo se il flag `REG ANOM` è settato `ON`) | Valore limite percentuale superiore ed inferiore utilizzati per la rilevazione delle anomalie di Tensione. Esempio: Sistema Trifase 4 fili. `Vref` = 230V, `LIM+=` 6%, `LIM-`=10% => Limite Superiore = 243,08V, Limite inferiore = 207,0V. Lo strumento rileverà una anomalia di Tensione qualora il valore `RMS` della Tensione (calcolato ogni 10ms) ecceda i limiti sopra indicati (vedi paragrafo 17.10). |  `LIM +` = 6% `LIM -` = 10% |
| `I1`, `I2`, `I3`, `IN`       | Valore Efficace rispettivamente della corrente di Fase 1, Fase 2, Fase 3 e di Neutro.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |  Monofase: `I1`<br/>3 fili: `I1`, `I2`, `I3`<br/>4 fili: `I1`, `I2`, `I3`, `IN` |

| Simbolo                       | Descrizione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Impostazioni consigliate |
| :---------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------- |
| `THD`, `DC`, `01..49`         | Distorsione Armonica Totale, Componente Continua, Armonica dalla prima alla 49-esima.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |  `THD`, `01`, `03`, `05`, `07` |
| `COGENERAZIONE`               | `ON` = lo strumento viene predisposto per gestire le situazioni di `CO-GENERAZIONE` negli impianti elettrici (ovvero l'utenza in esame è in grado di generare Energia oltre che assorbirla) e pertanto lo strumento registrerà nel tempo le Potenze ed Energie sia Assorbite che Generate (vedi paragrafo 17.12.1). In questo caso il numero massimo delle grandezze selezionabili diventa 38 (anziché 63)<br/>`OFF` = lo strumento registrerà nel tempo SOLO le Potenze ed Energie Assorbite.                                                                                                                                        |                         |
| `Pt`, `P1`, `P2`, `P3`, `P12`, `P32` | Valori della potenza attiva totale, della fase1, fase 2, fase 3 (solo per modalità 3 fili) valore della potenza misurata dal wattmetro 1-2 e 3-2 rispettivamente.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |  Monofase: `P1`<br/>3 fili: `Pt`<br/>4 fili: `Pt`, `P1`, `P2`, `P3` |
| `Qti`, `Q1i`, `Q2i`, `Q3i`, `Q12i`, `Q32i` | Valori della Potenza Reattiva Induttiva Totale, della Fase1, Fase 2, Fase 3 (solo per modalità 3 fili) Valore della Potenza Induttiva Reattiva misurata dai VARmetri 1-2 e 3-2 rispettivamente.                                                                                                                                                                                                                                                                                                                                                                                                                    |  Monofase: `Q1i Q1c`<br/>3 fili: `Qti Qtc`<br/>4 fili: `Qti Q1i Q2i`, `Q3i Qtc Q1c Q2c`, `Q3c` |
| `Qtc`, `Q1c`, `Q2c`, `Q3c`, `Q12c`, `Q32c` | Valori della Potenza Reattiva Capacitiva Totale, della Fase1, Fase 2, Fase 3 (solo per modalità 3 fili) Valore della Potenza Capacitiva Reattiva misurata dai VARmetri 1-2 e 3-2 rispettivamente.                                                                                                                                                                                                                                                                                                                                                                                                                |                          |
| `St`, `S1`, `S2`, `S3`, `S12`, `S32` | Valori della Potenza Apparente Totale, della Fase1, Fase 2, Fase 3 (solo per modalità 3 fili) Valore della Potenza misurata dal VAmetri 1-2 e 3-2 rispettivamente.                                                                                                                                                                                                                                                                                                                                                                                                                                                    |  Monofase: `S1`<br/>3 fili: `St`<br/>4 fili: `St`, `S1`, `S2`, `S3` |
| `Pft`, `pf1`, `pf2`, `pf3`    | Valori dei Fattori di Potenza totale, della Fase 1, Fase 2, Fase 3 rispettivamente.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |  Monofase: `Pf1 dPf1`<br/>3 fili: `Pft dPft`<br/>4 fili: `Pft Pf1 Pf2 Pf3 dPft dPf1 dPf2 dPf3` |
| `dPft`, `dpf1`, `dpf2`, `dpf3` | Valori del cos `` totale, della Fase 1, Fase 2, Fase 3 rispettivamente.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                          |
| `Eat`, `Ea1`, `Ea2`, `Ea3`    | Valori della Energia Attiva Totale, della Fase1, Fase 2, Fase 3.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |  Monofase: `Ea1`<br/>3 fili: `Eat`<br/>4 fili: `Eat Ea1 Ea2 Ea3` |
| `Erit`, `Eri1`, `Eri2`, `Eri3` | Valori della Energia Reattiva Induttiva Totale, della Fase1, Fase 2, Fase 3.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |  Monofase: `Eri1 Erc1`<br/>3 fili: `Erit Erct`<br/>4 fili: `Erit Eri1 Eri2 Eri3 Erct Erc1 Erc2 Erc3` |
| `Erct`, `Erc1`, `Erc2`, `Erc3` | Valori della Energia Reattiva Capacitiva Totale, della Fase1, Fase 2, Fase 3.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |                          |

Il valore della Frequenza di rete è automaticamente selezionato qualora siano selezionate almeno una Tensione di Fase (per la modalità Monofase o Trifase 4 fili) o almeno una Tensione Concatenata (per la modalità Trifase 3 fili). I simboli "`i`" e "`c`" indicano Potenze Reattive (`Q`), Fattori di Potenza (`Pf`) e cos `` (`dpf`) rispettivamente Induttivi e Capacitivi. Abilitando alla registrazione un Fattore di potenza (`Pf`) o un cos `` (`dPf`) ne verranno automaticamente registrati separatamente il valore induttivo ed il valore capacitivo. Per gli eventuali messaggi visualizzati sul display dello strumento si veda Appendice 1 – Messaggi del DISPLAY.

### 8.3. FUNZIONI ANALYZER

Al fine di massimizzare la semplicità d'uso si sono rese accessibili, tramite semplice pressione dei tasti `F3` e `F4`, le principali funzioni dello strumento:

*    Funzione "`TENSIONE`": Posizione da utilizzare qualora si intendano visualizzare i valori della tensione e relative armoniche (vedi paragrafo 17.11).
*    Funzione "`CORRENTE`": Posizione da utilizzare qualora si intendano visualizzare i valori della corrente e relative armoniche (vedi paragrafo 17.11).
*    Funzione "`POTENZA`": Posizione che consente di visualizzare i valori di tutte le grandezze rilevabili dallo strumento ovvero valori di tensione, corrente, potenza attiva, reattiva e apparente, fattori di potenza, cos `` ed energia (vedi paragrafo 17.12).
*    Funzione "`ENERGIA`": Posizione da utilizzare qualora si intendano visualizzare i valori della potenza attiva, reattiva e apparente, fattori di potenza, cos `` ed energia (vedi paragrafo 17.12).

Ai fini pratici una procedura per un utilizzo corretto ed efficace dello strumento può essere schematizzata come segue:

1.  Controllare ed eventualmente modificare le impostazioni di base dello strumento (`CONFIG ANALYZER`).
2.  Tramite i tasti `F3` e/o `F4` selezionare la funzione corrispondente al tipo di analisi che si intende effettuare.
3.  Collegare lo strumento al sistema elettrico in esame.
4.  Valutare i valori delle grandezze elettriche in esame.
5.  Nel caso si intenda effettuare una registrazione:
    a) Decidere quali grandezze registrare.
    b) Controllare che i parametri impostati in `CONFIG RECODER` corrispondano alle esigenze.
    c) Considerare eventualmente le registrazioni predefinite (vedere il paragrafo 10.2).
6.  Collegare l’alimentatore esterno (opzionale per `GSC57`) se necessario.
7.  Avviare la registrazione premendo il tasto `START/STOP`.

### 8.4. FUNZIONE "TENSIONE"

Funzione per la visualizzazione in tempo reale del Valore Efficace (`RMS`) della Tensione `AC/DC`, Valore di Picco e `Thd` delle tre Tensioni di fase, la visualizzazione della forma d'onda e dello spettro armonico delle 3 tensioni di fase.

#### 8.4.1. Simbolismo

La Funzione `TENSIONE` contempla 3 modalità di funzionamento:

*   `METER`
*   `HARM`
*   `WAVE`

Queste modalità saranno descritte dettagliatamente nei paragrafi successivi. I simboli utilizzati sono descritti nella seguente tabella.

Tab. 1: Simboli Utilizzati nella Funzione `TENSIONE`

| Simbolo                       | Descrizione                                                                                                                                |
| :---------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------- |
| `V1`, `V2`, `V3`              | Valore Efficace della Tensione di Fase 1, Fase 2, Fase 3 rispettivamente.                                                                  |
| `V12`, `V23` o `V32`, `V31`   | Valore Efficace delle tensioni concatenate.                                                                                                |
| `Vpk1`, `Vpk2`, `Vpk3`, `Vpk12`, `Vpk32` | Valore di picco della tensione di Fase 1, Fase 2, Fase 3 e della Tensione concatenata 12 e 32 rispettivamente.                           |
| `h01` `` `h49`             | Armonica 01 `` Armonica 49.                                                                                                               |
| `ThdV`                        | Fattore di Distorsione Armonica Totale della tensione (vedi paragrafo 17.10).                                                              |
| `freq`                        | Frequenza di Rete.                                                                                                                         |
| `Phseq`                       | Indicatore del Senso ciclico delle fasi: "`123`" `` Corretto "`132`" `` Invertito "`023`" `` Tensione Nulla sul filo Rosso "`103`" `` Tensione Nulla sul filo Verde "`120`" `` Tensione Nulla sul filo Nero "`100`" `` Tensioni Nulle sui fili Verde e Nero "`020`" `` Tensioni Nulle sui fili Rosso e Nero "`003`" `` Tensioni Nulle sui fili Rosso e Verde |

#### 8.4.2. Modalità "METER"

Selezionando questa posizione del commutatore lo strumento seleziona automaticamente la modalità denominata `METER` a cui corrisponde una delle seguenti videate a seconda delle impostazioni effettuate al paragrafo 8.1.1.

*Esempio di Videata in modalità Monofase*

```
27.09.02   17:35:12
TENSIONE MONOFASE
V1   = 230.2 V
Vpk1 = 325.5 V
ThdV = 0.0 %
freq = 50.0 Hz
HARM   WAVE   PG-   PG+
```

*Esempio di Videata in modalità Trifase "3 fili"*

```
27.09.02   17:35:12
TENSIONE
V12 = 384.2 V
V32 = 385.4 V
V31 = 383.7 V
freq = 50.0 Hz
HARM   WAVE   PG-   PG+
```

*Esempio di Videata in modalità Trifase "4 fili"*

```
27.09.02   17:35:12
TENSIONE
V1   = 230.2 V
V2   = 230.5 V
V3   = 230.6 V
V12  = 384.2 V
V23  = 385.4 V
V31  = 383.7 V
freq = 50.0 Hz
Phseq = 123
HARM   WAVE   PG-   PG+
```

I simboli utilizzati sono descritti in Tab. 1. Per gli eventuali messaggi visualizzati sul display dello strumento si veda Appendice 1 – Messaggi del DISPLAY. Sono attivi i seguenti tasti:

*    `F1`: passa alla modalità "`HARMONIC`" (vedi paragrafo 8.4.3).
*    `F2`: passa alla modalità "`WAVE`" (vedi paragrafo 8.4.4).
*    `F3/F4` per accedere alla modalità precedente/successiva.
*    `ENTER/HOLD`: Attiva/Disattiva la funzione di `HOLD` (arresto dell'aggiornamento) dei dati visualizzati. Tutte le precedenti funzioni rimangono comunque accessibili. L'attivazione della funzione `HOLD` comporta la visualizzazione del messaggio `HOLD`. Quando questa funzione è attiva non è possibile avviare una Registrazione o una Misura diretta dell'energia. La funzione `HOLD` non è disponibile durante una Registrazione o durante una misura dell'Energia.
*    `SAVE`: Archivia nella memoria dello strumento un Record di tipo "`Smp`" (vedi Paragrafo 9.2) contenente i valori istantanei della Tensione e Corrente presenti agli ingressi dello strumento. La funzione `SAVE` non è disponibile durante una Registrazione.
*    `MENU`: Attiva la visualizzazione dei parametri di registrazione (vedi paragrafi 8.1 e 8.2). Non è possibile accedere al Menu di configurazione durante una registrazione o durante una Misura di Energia.
*    `START/STOP`: Attiva la Registrazione dei Parametri selezionati secondo le impostazioni correnti (vedi capitolo 8.2).

#### 8.4.3. Modalità "HARM"

In questa modalità di funzionamento, a seconda delle impostazioni effettuate al paragrafo 8.1.1, apparirà una delle seguenti videate che illustrano il contenuto delle Armoniche (vedi paragrafo 17.11) della tensione di fase o concatenata.

*Esempio di Videata in modalità Monofase*

```
27.09.02   17:35:12
V1   = 230.2 V
h03  = 10.2 V
h03  = 4.3 %
ThdV = 11.0 %
h49      
```

*Esempio di Videata in modalità Trifase "3 fili"*

```
27.09.02   17:35:12
V12  = 400.2 V
h03  = 14.2 V
h03  = 3.5 %
ThdV = 11.0 %
ChgP   h49      
```

*Esempio di Videata in modalità Trifase "4 fili"*

```
27.09.02   17:35:12
V1   = 230.2 V
h03  = 10.2 V
h03  = 4.3 %
ThdV = 11.0 %
ChgP   h49      
```

I simboli utilizzati sono descritti in Tab. 1. Per gli eventuali messaggi visualizzati sul display dello strumento si veda Appendice 1 – Messaggi del DISPLAY. Gli istogrammi visualizzati sono rappresentativi del contenuto armonico della Tensione in esame. Il valore della prima armonica `h01` (fondamentale a 50Hz) non è rappresentata in scala con le altre armoniche al fine di massimizzare la visualizzazione di queste ultime. Qualora siano connessi agli ingressi dello strumento sia la Tensione che la Corrente, eventuali valori negativi delle Armoniche (con rappresentazione quindi sotto l'asse orizzontale) indicano che tali armoniche di Tensione sono "`generate`" dal carico. Sono attivi i seguenti tasti:

*    `F3`, `F4`: Sposta il cursore dell'armonica selezionata rispettivamente verso Sinistra e verso Destra. Conseguentemente sono aggiornati i valori relativi all'ordine dell'armonica selezionata ed i valori assoluto e relativo (calcolato rispetto alla fondamentale) della tensione.
*    `F1` (solo per modalità Trifase) Visualizza i valori delle Armoniche delle altre Tensioni disponibili.
*    `F2`: Visualizza la pagina delle Armoniche `h01` `` `h24` oppure `h25` `` `h49`.
*    `ESC`: Torna alla modalità `METER` (vedi paragrafo 8.4.2).
*    `ENTER/HOLD`: Attiva/Disattiva la funzione di `HOLD` (arresto dell'aggiornamento) dei dati visualizzati. Tutte le precedenti funzioni rimangono comunque accessibili. Quando questa funzione è attiva viene visualizzato il messaggio `HOLD` e non è possibile avviare una Registrazione o una Misura diretta dell'energia. La funzione `HOLD` non è disponibile durante una Registrazione o durante una Misura dell'Energia.
*    `SAVE`: Archivia in memoria un Record di tipo "`Smp`" (par. 9.2) contenente i valori istantanei della Tensione e Corrente presenti agli ingressi. Questa funzione non è disponibile durante una Registrazione.
*    `MENU`: Attiva la visualizzazione dei parametri di registrazione (vedi paragrafi 8.1 e 8.2). Non è possibile accedere al Menu di configurazione durante una Registrazione o durante una Misura di Energia.
*    `START/STOP`: Attiva la Registrazione dei Parametri selezionati secondo le impostazioni correnti (vedi capitolo 8.2).

#### 8.4.4. Modalità "WAVE"

In questa modalità di funzionamento, a seconda delle impostazioni effettuate al paragrafo 8.1.1, apparirà una delle seguenti videate che illustrano la forma d'onda della tensione di fase o concatenata.

*Esempio di Videata in modalità Monofase*

```
27.09.02   17:35:12
V1   = 230.2 V
Vpk1 = 325.5 V
freq = 50.0 Hz
```

*Esempio di Videata in modalità Trifase "3 fili"*

```
27.09.02   17:35:12
5:12
V12  = 400.2 V
Vpk12= 565.5 V
freq = 50.0 Hz
ChgP
```

*Esempio di Videata in modalità Trifase "4 fili"*

```
27.09.02   17:35:12
V1   = 230.2 V
Vpk1 = 325.5 V
freq = 50.0 Hz
ChgP
```

I simboli utilizzati sono descritti in Tab. 1. Per gli eventuali messaggi visualizzati sul display dello strumento si veda Appendice 1 – Messaggi del DISPLAY. Sono attivi i seguenti tasti:

*    `F1`: (solo per modalità Trifase) Visualizza i valori relativi alla fase successiva.
*    `ESC`: Torna alla modalità `METER` (vedi paragrafo 8.4.2).
*    `ENTER/HOLD`: Attiva/Disattiva la funzione di `HOLD` (arresto dell'aggiornamento) dei dati visualizzati. Tutte le precedenti funzioni rimangono comunque accessibili. L'attivazione della funzione `HOLD` comporta la visualizzazione del messaggio `HOLD`. Quando questa funzione è attiva non è possibile avviare una Registrazione o una Misura diretta dell'energia. La funzione `HOLD` non è disponibile durante una Registrazione o durante una Misura dell'Energia.
*    `SAVE`: Archivia nella memoria dello strumento un Record di tipo "`Smp`" (vedi Paragrafo 9.2) contenente i valori istantanei della Tensione e Corrente presenti agli ingressi dello strumento. La funzione `SAVE` non è disponibile durante una Registrazione.
*    `MENU`: Attiva la visualizzazione dei parametri di registrazione (vedi paragrafi 8.1 e 8.2). Non è possibile accedere al Menu di configurazione durante una registrazione o durante una Misura di Energia.
*    `START/STOP`: Attiva la Registrazione dei Parametri selezionati secondo le impostazioni correnti (vedi capitolo 8.2).

### 8.5. FUNZIONE "CORRENTE"

Funzione per la visualizzazione in tempo reale del Valore Efficace (`RMS`) delle Correnti `AC/DC`, Valore di Picco e `ThdI` delle tre Correnti di fase, la visualizzazione della forma d'onda e dello spettro armonico delle 3 correnti di fase.

#### 8.5.1. Simbolismo

La Funzione `CORRENTE` contempla 3 modalità di funzionamento:

*   `METER`
*   `WAVE`
*   `HARM`

Queste modalità saranno descritte dettagliatamente nei paragrafi successivi. I simboli utilizzati sono descritti nella seguente tabella.

Tab. 2: Simboli Utilizzati nella Funzione `CORRENTE`

| Simbolo                     | Descrizione                                                              |
| :-------------------------- | :----------------------------------------------------------------------- |
| `I1`, `I2`, `I3`            | Valore Efficace della Corrente di Fase 1, Fase 2, Fase 3 rispettivamente. |
| `IN`                        | Valore Efficace della Corrente di Neutro.                                |
| `Ipk1`, `Ipk2`, `Ipk3`      | Valore di Picco della Corrente di Fase 1, Fase 2 e Fase 3 rispettivamente. |
| `h01` `` `h49`           | Armonica 01 `` Armonica 49.                                           |
| `ThdI`                      | Fattore di Distorsione Armonica Totale della Corrente (vedi paragrafo 17.10). |
| `freq`                      | Frequenza di Rete.                                                       |

#### 8.5.2. Modalità "METER"

Selezionando questa posizione del commutatore lo strumento seleziona automaticamente la modalità denominata `METER` a cui corrisponde una delle seguenti videate a seconda delle impostazioni effettuate al paragrafo 8.1.1.

*Esempio di Videata in modalità Monofase*

```
27.09.02   17:35:12
CORRENTE MONOFASE
I1   = 30.21 A
Ipk1 = 49.53 A
ThdI = 23.06 %
freq = 50.0 Hz
PINZA TIPO: STD
HARM   WAVE   PG-   PG+
```

*Esempio di Videata in modalità Trifase "3 fili"*

```
27.09.02   17:35:12
CORRENTE
I1   = 30.21 A
I2   = 23.53 A
I3   = 23.06 A
freq = 50.0 Hz
PINZA TIPO: STD
HARM   WAVE   PG-   PG+
```

*Esempio di Videata in modalità Trifase "4 fili"*

```
27.09.02   17:35:12
CORRENTE
I1   = 30.21 A
I2   = 23.53 A
I3   = 23.06 A
IN   = 8.4 A
freq = 50.0 Hz
PINZA TIPO: STD
HARM   WAVE   PG-   PG+
```

Per gli eventuali messaggi visualizzati sul display dello strumento si veda Appendice 1 – Messaggi del DISPLAY. I simboli utilizzati sono descritti in Tab. 2. Sono attivi i seguenti tasti:

*    `F1`: passa alla modalità "`HARMONIC`" (vedi paragrafo 8.5.3).
*    `F2`: passa alla modalità "`WAVE`" (vedi paragrafo 8.5.4).
*    `F3/F4` per accedere alla modalità precedente/successiva.
*    `ENTER/HOLD`: Attiva/Disattiva la funzione di `HOLD` (arresto dell'aggiornamento) dei dati visualizzati. Tutte le precedenti funzioni rimangono comunque accessibili. L'attivazione della funzione `HOLD` comporta la visualizzazione del messaggio `HOLD`. Quando questa funzione è attiva non è possibile avviare una Registrazione o una Misura diretta dell'energia. La `HOLD` funzione non è disponibile durante una Registrazione o durante una Misura dell'Energia.
*    `SAVE`: Archivia nella memoria dello strumento un Record di tipo "`Smp`" (vedi Paragrafo 9.2) contenente i valori istantanei della Tensione e Corrente presenti agli ingressi dello strumento. La funzione `SAVE` non è disponibile durante una Registrazione.
*    `MENU`: Attiva la visualizzazione dei parametri di registrazione (vedi paragrafi 8.1 e 8.2). Non è possibile accedere al Menu di configurazione durante una registrazione o durante una Misura di Energia.
*    `START/STOP`: Attiva la Registrazione dei Parametri selezionati secondo le impostazioni correnti (vedi capitolo 8.2).

#### 8.5.3. Modalità "HARM"

Questa modalità consente la visualizzazione delle Armoniche (par. 17.11) delle correnti di Fase. Come da impostazioni effettuate al par. 8.1.1 apparirà una delle seguenti videate.

*Esempio di Videata in modalità Monofase*

```
27.09.02   17:35:12
I1   = 230.2 A
h03  = 10.2 A
h03  = 4.3 %
ThdI = 11.0 %
h49      
```

*Esempio di Videata in modalità Trifase "3 fili" o "4 fili"*

```
27.09.02   17:35:12
I1   = 230.2 A
h03  = 10.2 A
h03  = 4.3 %
ThdI = 11.0 %
ChgP   h49      
```

I simboli utilizzati sono descritti in Tab. 2. Per gli eventuali messaggi visualizzati sul display dello strumento si veda Appendice 1 – Messaggi del DISPLAY. Gli istogrammi visualizzati sono rappresentativi del contenuto armonico della Corrente in esame. Il valore della prima armonica `h01` (fondamentale a 50Hz) non è rappresentata in scala con le altre armoniche al fine di massimizzare la visualizzazione di queste ultime. Qualora siano connessi agli ingressi dello strumento sia la Tensione che la Corrente, eventuali valori negativi delle Armoniche (con rappresentazione quindi sotto l'asse orizzontale) indicano che tali armoniche di Corrente sono "`generate`" dal carico. Sono attivi i seguenti tasti:

*    `F3`, `F4`: Sposta il cursore dell'armonica selezionata rispettivamente verso Sinistra e verso Destra. Conseguentemente sono aggiornati i valori relativi all'ordine dell'armonica selezionata ed ai corrispondenti valori assoluto e relativo (calcolato rispetto alla fondamentale) della corrente.
*    `F1` (solo per modalità Trifase) Visualizza i valori delle Armoniche delle Fasi successive.
*    `F2`: Visualizza le pagine delle Armoniche `h01` `` `h24` oppure `h25` `` `h49`.
*    `ESC`: Torna alla modalità "`METER`" (vedi paragrafo 8.5.2).
*    `ENTER/HOLD`: Attiva/Disattiva la funzione di `HOLD` (arresto dell'aggiornamento) dei dati visualizzati. Tutte le precedenti funzioni rimangono comunque accessibili. Quando questa funzione è attiva viene visualizzato il messaggio `HOLD` e non è possibile avviare una Registrazione o una Misura diretta dell'energia. La funzione `HOLD` non è disponibile durante una Registrazione o durante una Misura dell'Energia.
*    `SAVE`: Archivia nella memoria dello strumento un Record di tipo "`Smp`" (vedi Paragrafo 9.2) contenente i valori istantanei della Tensione e Corrente presenti agli ingressi dello strumento. La funzione `SAVE` non è disponibile durante una Registrazione.
*    `MENU`: Attiva la visualizzazione dei parametri di registrazione (vedi paragrafi 8.1 e 8.2). Non è possibile accedere al Menu di configurazione durante una registrazione o durante una Misura di Energia.
*    `START/STOP`: Attiva la Registrazione dei Parametri selezionati secondo le impostazioni correnti (vedi capitolo 8.2).

#### 8.5.4. Modalità "WAVE"

In questa modalità di funzionamento lo strumento consente la visualizzazione della forma delle Correnti di fase. A seconda delle impostazioni effettuate al paragrafo 8.1.1 apparirà una delle seguenti videate.

*Esempio di Videata in modalità Monofase*

```
27.09.02   17:35:12
I1   = 230.2 A
Ipk1 = 325.5 A
freq = 50.0 Hz
```

*Esempio di Videata in modalità Trifase "3 fili" o "4 fili"*

```
27.09.02   17:35:12
I2   = 400.2 A
Ipk2 = 565.5 A
freq = 50.0 Hz
ChgP
```

I simboli utilizzati sono descritti in Tab. 2. Per gli eventuali messaggi visualizzati sul display dello strumento si veda Appendice 1 – Messaggi del DISPLAY. Sono attivi i seguenti tasti:

*    `F1`: (solo per modalità Trifase) Visualizza i valori relativi alla fase successiva.
*    `ESC`: Torna alla modalità "`METER`" (vedi paragrafo 8.5.2).
*    `ENTER/HOLD`: Attiva/Disattiva la funzione di `HOLD` (arresto dell'aggiornamento) dei dati visualizzati. Tutte le precedenti funzioni rimangono comunque accessibili. L'attivazione della funzione `HOLD` comporta la visualizzazione del messaggio `HOLD`. Quando questa funzione è attiva non è possibile avviare una Registrazione o una Misura diretta dell'energia. La funzione `HOLD` non è disponibile durante una Registrazione o durante una Misura dell'Energia.
*    `SAVE`: Archivia nella memoria dello strumento un Record di tipo "`Smp`" (vedi Paragrafo 9.2) contenente i valori istantanei della Tensione e Corrente presenti agli ingressi dello strumento. La funzione `SAVE` non è disponibile durante una Registrazione.
*    `MENU`: Attiva la visualizzazione dei parametri di registrazione (vedi paragrafi 8.1 e 8.2). Non è possibile accedere al Menu di configurazione durante una registrazione o durante una Misura di Energia.
*    `START/STOP`: Attiva la Registrazione dei Parametri selezionati secondo le impostazioni correnti (vedi capitolo 8.2).

### 8.6. FUNZIONE "POTENZA"

Funzione per la visualizzazione in tempo reale del Valore Efficace (`RMS`) e forma d'onda delle 3 tensioni di fase, la visualizzazione in tempo reale del Valore Efficace (`RMS`) e forma d'onda delle 3 correnti di fase. Lo strumento calcola e visualizza inoltre i Valori delle Potenze Attive, delle Potenze Reattive Induttive e Capacitive, Fattori di Potenza e cos `` sia Totali sia relativi ad ogni singola fase.

#### 8.6.1. Simbolismo

La Funzione `POTENZA` contempla 2 modalità di funzionamento:

*   `METER`
*   `WAVE`

Queste modalità saranno descritte dettagliatamente nei paragrafi successivi. I simboli utilizzati sono descritti nella seguente tabella.

Tab. 3: Simboli Utilizzati nella Funzione `POTENZA`

| Simbolo                       | Descrizione                                                                                                                                                                             |
| :---------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `V1`, `V2`, `V3`              | Valore Efficace della Tensione di Fase 1, Fase 2, Fase 3 rispettivamente.                                                                                                               |
| `V12`, `V23` o `V32`, `V31`   | Valore Efficace delle tensioni concatenate.                                                                                                                                             |
| `freq`                        | Frequenza di Rete.                                                                                                                                                                      |
| `Phseq`                       | Indicatore del Senso ciclico delle fasi: "`123`" `` Corretto "`132`" `` Invertito "`023`" `` Tensione Nulla sul filo Rosso "`103`" `` Tensione Nulla sul filo Verde "`120`" `` Tensione Nulla sul filo Nero "`100`" `` Tensioni Nulle sui fili Verde e Nero "`020`" `` Tensioni Nulle sui fili Rosso e Nero "`003`" `` Tensioni Nulle sui fili Rosso e Verde |
| `I1`, `I2`, `I3`              | Valore Efficace della Corrente di Fase 1, Fase 2, Fase 3 rispettivamente.                                                                                                               |
| `IN`                          | Valore Efficace della corrente del Neutro.                                                                                                                                              |
| `Pt`, `P1`, `P2`, `P3`        | Valori della Potenza Attiva Totale, della Fase1, Fase 2, Fase 3 rispettivamente.                                                                                                        |
| `P12`, `P32`                  | (solo per modalità 3 fili) Valore della Potenza misurata dal Wattmetro 1-2 e 3-2 rispettivamente (vedi Paragrafo 17.12.2).                                                               |
| `Qt`, `Q1`, `Q2`, `Q3`        | Valori della Potenza Reattiva Totale, della Fase1, Fase 2, Fase 3 rispettivamente.                                                                                                      |
| `Q12`, `Q32`                  | (solo per modalità 3 fili) Valore della Potenza misurata dal VARmetro 1-2 e 3-2 rispettivamente (vedi Paragrafo 17.12.2).                                                               |
| `St`, `S1`, `S2`, `S3`        | Valori della Potenza Apparente Totale, della Fase1, Fase 2, Fase 3 rispettivamente.                                                                                                     |
| `S12`, `S32`                  | (solo per modalità 3 fili) Valore della Potenza misurata dal VAmetri 1-2 e 3-2 rispettivamente (vedi Paragrafo 17.12.2).                                                               |
| `Pft`, `Pf1`, `Pf2`, `Pf3`    | Valori dei Fattori di Potenza totale, della Fase 1, Fase 2, Fase 3 rispettivamente.                                                                                                     |
| `dPft`, `dpf1`, `dpf2`, `dpf3` | Valori del cos `` totale, della Fase 1, Fase 2, Fase 3 rispettivamente.                                                                                                                |
| `Pd`, `Ed`                    | Valori della Potenza attiva Disponibile e della corrispondente Energia.                                                                                                                 |

I simboli "`i`" e "`c`" indicano Potenze Reattive (`Q`), Fattori di Potenza (`Pf`) e cos `` (`dpf`) rispettivamente Induttivi e Capacitivi.

#### 8.6.2. Modalità "METER"

In questa modalità di funzionamento, a seconda delle impostazioni effettuate al paragrafo 8.1.1.

*Esempio di Videata in modalità Monofase*

```
27.09.02   17:35:12
MONOFASE POTENZA
V1   = 230.0 V
I1   = 145.3 A
P1   = 32.91 kW
Q1   = 5.767 kVAR
S1   = 33.41 kVA
pf1  = 0.99 i
dpf1 = 0.99 i
WAVE   PG-   PG+
```

*Esempio di Videata in modalità Trifase "3 fili"*

```
27.09.02   17:35:12
POTENZA TRE FILI
Pt   = 64.19 kW
Qt   = 10.99 kVAR
St   = 65.12 kVA
pft  = 0.99 i
dpft = 1.00 i
ChgP   WAVE   PG-   PG+
```

*Esempio di Videata in modalità Trifase "4 fili"*

```
27.09.02   17:35:12
POTENZA TRIFASE
Pt   = 135.8 kW
Qt   = 24.59 kVAR
St   = 138.0 kVA
pft  = 0.98 i
dpft = 1.00 i
Phseq= 123
ChgP   WAVE   PG-   PG+
```

I simboli utilizzati sono descritti in Tab. 3. Per gli eventuali messaggi visualizzati sul display dello strumento si veda Appendice 1 – Messaggi del DISPLAY. Sono attivi i seguenti tasti:

*    `F2`: passa alla modalità "`WAVE`" (vedi paragrafo 8.6.3).
*    `F1`: (solo per trifase) visualizza la videata successiva. A seconda delle impostazioni effettuate al paragrafo 8.1.1 vengono visualizzate le seguenti videate in ordine ciclico:
    *   Trifase 3 fili: Valori Trifase totali, Valori Wattmetri 1-2 e 3-2, Potenza disponibile
    *   Trifase 4 fili: Valori Trifase totali, Valori Fase1, Fase2, Fase3, Potenza disponibile
*    `F3/F4` Per accedere alla modalità precedente/successiva.
*    `ENTER/HOLD`: Attiva/Disattiva la funzione di `HOLD` (arresto dell'aggiornamento) dei dati visualizzati. Tutte le precedenti funzioni rimangono comunque accessibili. L'attivazione della funzione `HOLD` comporta la visualizzazione del messaggio `HOLD`. Quando questa funzione è attiva non è possibile avviare una Registrazione o una Misura diretta dell'energia. Questa funzione non è disponibile durante una Registrazione o durante una misura dell'Energia.
*    `SAVE`: Archivia nella memoria dello strumento un Record di tipo "`Smp`" (vedi Paragrafo 9.2) contenente i valori istantanei della Tensione e Corrente presenti agli ingressi dello strumento. La funzione `SAVE` non è disponibile durante una Registrazione.
*    `MENU`: Attiva la visualizzazione dei parametri di registrazione (vedi paragrafi 8.1 e 8.2). Non è possibile accedere al Menu di configurazione durante una registrazione o durante una Misura di Energia.
*    `START/STOP`: Attiva la Registrazione dei Parametri selezionati secondo le impostazioni correnti (vedi capitolo 8.2).

##### 8.6.2.1. Pagina “Potenza Massima Trifase”

All’interno delle funzionalità della posizione `POWER`, se si è impostato un sistema trifase (vedi paragrafo 8.1.1) premendo ripetutamente il tasto `F1` si raggiunge la modalità denominata “`POTENZA MASSIMA`”. Questa modalità visualizza i valori relativi alla registrazione in corso o, qualora non sia in corso ancora registrazione, all’ultima eseguita. In particolare visualizza:

*   il valore Massimo raggiunto dal valore medio della Potenza Attiva (integrata in un intervallo di tempo pari al Periodo di Integrazione) durante la registrazione ed il valore della corrispondente Energia. Viene inoltre visualizzata la Data e Ora in cui si è rilevato tale massimo.

*Esempio della Videata “POTENZA MASSIMA”*

```
27.09.02   17:35:12
POTENZA MASSIMA TRIFASE
Ed = 98.36 kWh
Pd = 24.59 kW
Data Massimo
25.09.02   17:00
Periodo Int:15min
Reg n: 06
ChgP   PG-   PG+
```

*    `F1`: visualizza la videata successiva. A seconda delle impostazioni effettuate al paragrafo 8.1.1 sono mostrate le seguenti videata in ordine ciclico:
    *   Trifase 3 fili: Valori Trifase totali, Valori Wattmetri 1-2 e 3-2, Potenza disponibile
    *   Trifase 4 fili: Valori Trifase totali, Valori Fase1, Fase2, Fase3, Potenza disponibile
*    `F3/F4` per accedere alla modalità precedente/successiva.
*    `ENTER/HOLD`: Attiva/Disattiva la funzione di `HOLD` (arresto dell'aggiornamento) dei dati visualizzati. Tutte le precedenti funzioni rimangono comunque accessibili. L'attivazione della funzione `HOLD` comporta la visualizzazione del messaggio `HOLD`. Quando questa funzione è attiva non è possibile avviare una Registrazione o una Misura diretta dell'energia. Questa funzione non è disponibile durante una Registrazione o durante una misura dell'Energia.
*    `SAVE`: Archivia nella memoria dello strumento un Record di tipo "`Smp`" (vedi Paragrafo 9.2) contenente i valori istantanei della Tensione e Corrente presenti agli ingressi dello strumento. La funzione `SAVE` non è disponibile durante una Registrazione.
*    `MENU`: Attiva la visualizzazione dei parametri di registrazione (vedi paragrafi 8.1 e 8.2). Non è possibile accedere al Menu di configurazione durante una registrazione o durante una Misura di Energia.
*    `START/STOP`: Attiva la Registrazione dei Parametri selezionati secondo le impostazioni correnti (vedi capitolo 8.2).

#### 8.6.3. Modalità "WAVE"

In questa modalità di funzionamento, a seconda delle impostazioni effettuate al paragrafo 8.1.1, apparirà una delle seguenti videate che illustrano la forma d'onda della tensione di fase o concatenata e della corrente di Fase.

*Esempio di Videata in modalità Monofase*

```
27.09.02   17:35:12
V1   = 229.7 V
I1   = 132.0 A
pf1  = 0.98 i
```

*Esempio di Videata in modalità Trifase "3 fili"*

```
27.09.02   17:35:12
V12  = 379.9 V
I1   = 132.0 A
ChgP
```

*Esempio di Videata in modalità Trifase "4 fili"*

```
27.09.02   17:35:12
V1   = 229.7 V
I1   = 132.0 A
pf1  = 0.98 i
ChgP
```

I simboli utilizzati sono descritti in Tab. 3. Per gli eventuali messaggi visualizzati sul display dello strumento si veda Appendice 1 – Messaggi del DISPLAY. Sono attivi i seguenti tasti:

*    `F1`: (solo per trifase) visualizzano la videata successiva. A seconda delle impostazioni effettuate al paragrafo 8.1.1 vengono visualizzate le seguenti videata in ordine ciclico:
    *   Trifase 3 fili: Valori Wattmetro 1-2, Valori Wattmetro 2-3
    *   Trifase 4 fili: Valori Fase1, Valori Fase 2, Valori Fase 3
*    `ESC`: Torna alla modalità "`METER`" (vedi paragrafo 8.6.2).
*    `ENTER/HOLD`: Attiva/Disattiva la funzione di `HOLD` (arresto dell'aggiornamento) dei dati visualizzati. Tutte le precedenti funzioni rimangono comunque accessibili. L'attivazione della funzione `HOLD` comporta la visualizzazione del messaggio `HOLD`. Quando questa funzione è attiva non è possibile avviare una Registrazione o una Misura diretta dell'energia. La funzione `HOLD` non è disponibile durante una Registrazione o durante una Misura dell'Energia.
*    `SAVE`: Archivia nella memoria dello strumento un Record di tipo "`Smp`" (vedi Paragrafo 9.2) contenente i valori istantanei della Tensione e Corrente presenti agli ingressi dello strumento. La funzione `SAVE` non è disponibile durante una Registrazione.
*    `MENU`: Attiva la visualizzazione dei parametri di registrazione (vedi paragrafi 8.1 e 8.2). Non è possibile accedere al Menu di configurazione durante una registrazione o durante una Misura di Energia.
*    `START/STOP`: Attiva la Registrazione dei Parametri selezionati secondo le impostazioni correnti (vedi capitolo 8.2).

<!-- Chunk: Pages 97-128 -->
### 8.7. FUNZIONE "ENERGIA"

Funzione per la visualizzazione in tempo reale dei Valori delle Potenze Attive di Fase e Totali, il Valore delle Potenze Reattive Induttive e Capacitive di Fase e Totali, valori dei Fattori di Potenza e cos φ di Fase e Totali. Lo strumento permette inoltre la Misura diretta (vedi Paragrafo 8.7.2) dei Valori delle Energie Attive di Fase e Totali, dei Valori delle Energie Reattive Induttive e Capacitive di Fase e Totali.

#### 8.7.1. Simbolismo

La Funzione ENERGIA contempla una sola modalità di funzionamento:
*   METER

Per le armoniche di Tensione e Corrente si vedano rispettivamente i paragrafi 8.4 e 8.5. Queste modalità saranno descritte dettagliatamente nei paragrafi successivi. I simboli utilizzati sono descritti nella seguente tabella.

| Simbolo | Descrizione |
| :------ | :---------- |
| `Pt, P1, P2, P3` | Valori della Potenza Attiva Totale, della Fase1, Fase 2, Fase 3 rispettivamente |
| `P12, P32` | (solo per modalità 3 fili) Valore della Potenza misurata dal Wattmetro 1-2 e 3-2 rispettivamente (vedi paragrafo 17.12.2). |
| `Qt, Q1, Q2, Q3` | Valori della Potenza Reattiva Totale, della Fase1, Fase 2, Fase 3 rispettivamente |
| `Q12, Q32` | (solo per modalità 3 fili) Valore della Potenza misurata dal VARmetro 1-2 e 3-2 rispettivamente (vedi paragrafo 17.12.2). |
| `St, S1, S2, S3` | Valori della Potenza Apparente Totale, della Fase1, Fase 2, Fase 3 rispettivamente |
| `S12, S32` | (solo per modalità 3 fili) Valore della Potenza misurata dal VAmetro 1-2 e 3-2 rispettivamente (vedi paragrafo 17.12.2). |
| `Pft, pf1, pf2, pf3` | Valori dei Fattori di Potenza totale, della Fase 1, Fase 2, Fase 3 rispettivamente |
| `dPft, dpf1, dpf2, dpf3` | Valori del cos φ totale, della Fase 1, Fase 2, Fase 3 rispettivamente |
| `Eat, Ea1, Ea2, Ea3` | Valori della Energia Attiva Totale, della Fase1, Fase 2, Fase 3 rispettivamente |
| `Erct, Erc1, Erc2, Erc3` | Valori della Energia Reattiva Capacitiva Totale, della Fase1, Fase 2, Fase 3 rispettivamente |
| `Erit, Eri1, Eri2, Eri3` | Valori della Energia Reattiva Induttiva Totale, della Fase1, Fase 2, Fase 3 rispettivamente |

*Tab. 4: Simboli Utilizzati nella Posizione ENERGY*

I simboli " i " e " c " indicano Potenze Reattive (Q), Fattori di Potenza (Pf) e cos φ (dpf) rispettivamente Induttivi e Capacitivi.

#### 8.7.2. Modalità "METER"

In questa modalità di funzionamento, a seconda delle impostazioni effettuate al paragrafo 8.1.1, apparirà una delle seguenti videate.

```
27.09.02   17:35:12
MONOFASE ENERGIA
Ea1   =   0.000   Wh
Erc1   =   0.000   VARh
Eri1   =   0.000   VARh
P1   =   36.38   kW
Q1   =   6.375   kVAR
S1   =   36.94   kVA
Tempo   Mis:   00:00:00
MEAS   PG-   PG+
```
Esempio di Videata in modalità Monofase

```
27.09.02   17:35:12
ENERGIA TRIFASE
Eat   =   0.000   Wh
Erct   =   0.000   VARh
Erit   =   0.000   VARh
Pt   =   36.38   kW
Qt   =   6.375   kVAR
St   =   36.94   kVA
Tempo   Mis:   00:00:00
MEAS   PG-   PG+   ChgP
```
Esempio di Videata in modalità Trifase "3 fili"

```
27.09.02   17:35:12
ENERGIA TRIFASE
Eat   =   0.000   Wh
Erct   =   0.000   VARh
Erit   =   0.000   VARh
Pt   =   167.7   kW
Qt   =   30.47   kVAR
St   =   170.4   kVA
Tempo   Mis:   00:00:00
MEAS   PG-   PG+
```
Esempio di Videata in modalità Trifase "4 fili"

I simboli utilizzati sono descritti in Tab. 4. Per gli eventuali messaggi visualizzati sul display dello strumento si veda Appendice 1 – Messaggi del DISPLAY. Sono attivi i seguenti tasti:

*   **F2**: Avvio/Arresto immediato di una Misurazione diretta dell'Energia. I contatori di Energia inizieranno ad incrementare in maniera proporzionale alla Potenza Attiva assorbita dal carico.
    I risultati ottenuti non sono memorizzabili. Se la Potenza Attiva è negativa i contatori non incrementeranno.
*   **ENTER/HOLD**: Attiva/Disattiva la funzione di HOLD (arresto dell'aggiornamento) dei dati visualizzati. Tutte le precedenti funzioni rimangono comunque accessibili. L'attivazione della funzione HOLD comporta la visualizzazione del messaggio HOLD. Quando questa funzione è attiva non è possibile avviare una Registrazione o una Misura diretta dell'energia. Questa funzione non è disponibile durante una registrazione o durante una Misura di energia.
*   **SAVE**: Archivia nella memoria dello strumento un Record di tipo "Smp" (vedi Paragrafo 9.2) contenente i valori istantanei della Tensione e Corrente presenti agli ingressi dello strumento. La funzione SAVE non è disponibile durante una Registrazione.
*   **MENU**: Attiva la visualizzazione dei parametri di registrazione (vedi paragrafi 8.1 e 8.2). Non è possibile accedere al Menu di configurazione durante una registrazione o durante una Misura di Energia.
*   **START/STOP**: Attiva la Registrazione dei Parametri selezionati secondo le impostazioni correnti (vedi capitolo 8.2).

### 8.8. PROCEDURE DI MISURA

#### 8.8.1. Utilizzo dello strumento in un sistema monofase

> **ATTENZIONE**
> La massima tensione fra gli ingressi B1 e B4 è 600V~ (CATII) / 350V~ verso terra oppure 600V~ (CATIII) / 300V~ verso terra. Non misurare tensioni che eccedano i limiti indicati in questo manuale. Il superamento dei limiti di tensione potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.

![Collegamento dello strumento in un sistema monofase.](image_monofase_connection.png)
*Collegamento dello strumento in un sistema monofase.*

> **ATTENZIONE**
> Ove possibile togliere alimentazione al sistema elettrico in esame prima di effettuare il collegamento dello strumento. Adottare tutte le misure di sicurezza previste prima di operare sull’impianto.

1.  Controllare ed eventualmente modificare le impostazioni di base dello strumento (vedi par. 8.1). In particolare occorrerà impostare la modalità `MONO` (monofase).
2.  Selezionare la funzione corrispondente al tipo di Analisi desiderata. In caso di dubbio selezionare la funzione `POTENZA` (vedi par. 8.6).
3.  Collegare i fili della tensione di fase e neutro rispettando le connessioni indicate in figura.
4.  Qualora il sistema elettrico in esame fosse stato messo momentaneamente fuori servizio per il collegamento dello strumento, ripristinare la tensione.
5.  Se si intende effettuare rilevazioni di Corrente e Potenza, collegare la pinza amperometrica sul conduttore di fase rispettando il verso indicato sulla pinza e le connessioni indicate in figura. In caso di dubbio selezionare la funzione `POTENZA` e controllare che la potenza attiva `P1` sia positiva. Qualora fosse negativa ruotare la pinza amperometrica.
6.  I valori delle grandezze elettriche disponibili saranno visualizzati sul display dello strumento. Per maggiori dettagli si veda il paragrafo relativo alla funzione selezionata.
7.  Se si intende salvare i valori visualizzati sul display premere il tasto `SAVE` (vedi 9.2).
8.  Eventualmente si può utilizzare il tasto `HOLD` per arrestare l’aggiornamento in tempo reale dei valori delle grandezze visualizzate. Quando questa funzione è attiva non è possibile avviare una Registrazione o una Misura diretta dell'energia.
9.  Se si intende effettuare una registrazione:
    a)  Controllare ed eventualmente modificare i valori dei parametri di base (vedi par. 8.1).
    b)  Controllare ed eventualmente modificare i parametri di registrazione (vedi par.8.2).
    c)  Per avviare la registrazione premere il tasto `START` (vedi Capitolo 10.1). Per eventuali messaggi si veda Appendice 1 – Messaggi del DISPLAY.

#### 8.8.2. Utilizzo dello strumento in un sistema trifase con neutro

> **ATTENZIONE**
> La massima tensione fra gli ingressi B1, B2, B3, B4 è 600V~ (CATII) / 350V~ verso terra oppure 600V~ (CATIII) / 300V~ verso terra. Non misurare tensioni che eccedano i limiti indicati in questo manuale. Il superamento dei limiti di tensione potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.

![Collegamento dello strumento in un sistema trifase a 4 fili.](image_trifase_4_fili_connection.png)
*Collegamento dello strumento in un sistema trifase a 4 fili.*

> **ATTENZIONE**
> Ove possibile togliere alimentazione al sistema elettrico in esame prima di effettuare il collegamento dello strumento. Adottare tutte le misure di sicurezza previste prima di operare sull’impianto.

1.  Controllare ed eventualmente modificare le impostazioni di base dello strumento (vedi paragrafo 8.1). In particolare occorrerà sicuramente impostare la modalità `4FILI`.
2.  Selezionare la funzione corrispondente al tipo di analisi desiderata. In caso di dubbio selezionare la funzione `POTENZA` (vedi paragrafo 8.6).
3.  Collegare i fili delle tensioni di fase e neutro rispettando le connessioni indicate in figura.
4.  Qualora il sistema elettrico in esame fosse stato messo momentaneamente fuori servizio ripristinare la tensione.
5.  Se si intende effettuare rilevazioni di corrente e potenza collegare le pinze amperometriche sui conduttori di fase rispettando il verso indicato sulla pinza e le connessioni indicate in figura. In caso di dubbio selezionare la funzione `POTENZA` e, collegando una pinza amperometrica alla volta, controllare che:
    a) il senso ciclico delle fasi sia corretto (vedi paragrafo 8.6.1).
    b) La potenza attiva P di ogni fase sia positiva. Se fosse negativa occorre girare la pinza della Fase in esame.
    c) il valore del Pf di ogni Fase non sia eccessivamente basso (tipicamente non è inferiore a 0.4). Nel caso il Pf sia inferiore a 0,4 controllare se alla tensione di fase sia stata associata la giusta pinza amperometrica (es. la tensione di fase 1 va associata alla pinza amperometrica 1).
6.  I valori delle Grandezze elettriche disponibili saranno visualizzati sul display dello strumento. Per maggiori dettagli si veda il paragrafo relativo alla posizione del commutatore selezionata.
7.  Se si intende memorizzare i valori visualizzati sul display premere il tasto `SAVE` (vedi paragrafo 9.2).
8.  Eventualmente si può utilizzare il tasto `HOLD` per arrestare l’aggiornamento in tempo reale dei valori delle grandezze visualizzate. Quando questa funzione è attiva non è possibile avviare una registrazione o una misura diretta dell'energia.
9.  Se si intende effettuare una registrazione:
    a) Controllare ed eventualmente modificare i valori dei parametri di base (vedi paragrafo 8.1).
    b) Controllare ed eventualmente modificare i parametri di registrazione (vedi par.8.2).
    c) Per avviare la registrazione premere il tasto `START` (vedi Capitolo10.1). Per eventuali messaggi si veda Appendice 1 – Messaggi del DISPLAY.

#### 8.8.3. Utilizzo dello strumento in un sistema trifase senza neutro (Aron)

> **ATTENZIONE**
> La massima tensione fra gli ingressi B1, B2, B3, B4 è 600V~ (CATII) / 350V~ verso terra oppure 600V~ (CATIII) / 300V~ verso Terra. Non misurare tensioni che eccedano i limiti indicati in questo manuale. Il superamento dei limiti di tensione potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.

![Collegamento dello strumento in un sistema trifase a 3 fili.](image_trifase_3_fili_connection.png)
*Collegamento dello strumento in un sistema trifase a 3 fili.*

> **ATTENZIONE**
> Si noti che in questo caso il filo Blu (Neutro) viene connesso con il filo Rosso sulla fase 2.

> **ATTENZIONE**
> Ove possibile togliere alimentazione al sistema elettrico in esame prima di effettuare il collegamento dello strumento. Adottare tutte le misure di sicurezza previste prima di operare sull’impianto.

1.  Controllare ed eventualmente modificare le impostazioni di base dello strumento (vedi paragrafo 8.1). In particolare occorrerà sicuramente impostare la modalità `3FILI`.
2.  Selezionare la funzione corrispondente al tipo di analisi desiderata. In caso di dubbio selezionare la funzione `POTENZA` (vedi paragrafo 8.6).
3.  Collegare i fili delle tensioni di fase e neutro rispettando le connessioni indicate in figura.
4.  Se si intende effettuare rilevazioni di corrente e potenza collegare le pinze amperometriche sui conduttori di fase rispettando il verso indicato sulla pinza e le connessioni indicate in figura. In caso di dubbio impostare temporaneamente la modalità `4FILI`, selezionare poi la funzione `POTENZA`, collegare il filo blu dello strumento ad un morsetto di terra dell'impianto e, collegando una pinza amperometrica alla volta, controllare che:
    a) il senso ciclico delle Fasi sia corretto (vedi paragrafo 8.6.1).
    b) La potenza attiva P di ogni fase sia positiva. Se fosse negativa occorrerebbe girare la pinza della Fase in esame.
    c) il valore del Pf di ogni Fase non sia una valore eccessivamente basso (tipicamente non inferiore a 0.4). Nel caso il Pf sia inferiore a 0,4 controllare che la tensione di fase sia stata associata alla giusta pinza amperometrica (es. la tensione di fase 1 va associata alla pinza amperometrica 1).
    d) Controllata, ed eventualmente modificata la connessione dello strumento all'impianto, reimpostare la modalità `3FILI` e le connessioni indicate in figura.
5.  Qualora il sistema elettrico in esame fosse stato messo momentaneamente fuori servizio ripristinare la tensione.
6.  I valori delle grandezze elettriche disponibili saranno visualizzati sul display dello strumento. Per maggiori dettagli si veda il paragrafo relativo alla posizione del commutatore selezionata.
7.  Se si intende memorizzare i valori visualizzati sul display premere il tasto `SAVE` (vedi paragrafo 9.2).
8.  Eventualmente si può utilizzare il tasto `HOLD` per arrestare l’aggiornamento in tempo reale dei valori delle grandezze visualizzate. Quando questa funzione è attiva non è possibile avviare una registrazione o una misura diretta dell'energia.
9.  Se si intende effettuare una registrazione:
    a) Controllare ed eventualmente modificare i valori dei parametri di base (vedi paragrafo 8.1).
    b) Controllare ed eventualmente modificare i parametri di registrazione (vedi par.8.2).
    c) Per avviare la registrazione premere il tasto `START` (vedi Capitolo10.1). Per eventuali messaggi si veda Appendice 1 – Messaggi del DISPLAY.

## 9. MEMORIZZAZIONE RISULTATI

Il tasto `SAVE` consente l'archiviazione in memoria dei valori visualizzati a display. In funzione della posizione del commutatore si possono individuare due tipi diversi di dati memorizzati:

*   `PROVE DI VERIFICA` (`LOW Ω`, `M Ω`, `RCD`, `LOOP`, `EARTH`, `LOW Ω 10A`) e posizione `AUX`: la pressione del tasto `SAVE` comporta l'archiviazione in memoria dei risultati ottenuti dalla prova effettuata. Conseguentemente nella MEMORIA SAFETY TEST dello strumento verrà creato un record (vedi paragrafo 11.1).
*   Posizione `ANALYZER`: la pressione del tasto `SAVE` archivia in MEMORIA ANALYZER i valori visualizzati generando un record di tipo "Smp" (vedi paragrafo 11.2).

Si ricorda inoltre che una memorizzazione di risultati (pressione del tasto SAVE) non è una registrazione (vedi Capitolo 10).

### 9.1. MEMORIZZAZIONE DEI RISULTATI DI PROVE DI VERIFICA (SAFETY TEST)

Dopo una prova di verifica (posizioni `LOW Ω`, `M Ω`, `RCD`, `LOOP`, `EARTH` e `LOW Ω 10A`) o una misura in tempo reale in posizione `AUX`, l'operatore può premere il tasto `SAVE` per memorizzare i risultati acquisiti. Dopo la prima pressione del tasto `SAVE` viene visualizzata la seguente videata:

*   Il parametro "PLACE" può essere utilizzato per aiutare l'operatore ad individuare il punto in cui è stata effettuata una misura. Il valore di tale parametro è Liberamente modificabile e non è in nessun modo vincolato alla locazione di memoria in cui verranno memorizzati i risultati e che aumenta progressivamente.

```
05.06.02
SALVA   IN   LOC.   006
OK?   (SALVA/ESCI)
ULTIMO   PLACE:009

Locazione di memoria
Parametro mnemonico
```
*Esempio di videata per la memorizzazione di un Safety Test*

Sono attivi i seguenti tasti:

*   **F3**, **F4**: Per impostare il valore del parametro "PLACE".
*   **SAVE**: Per memorizzare i risultati ottenuti nella locazione di memoria indicata associandogli il valore del parametro "PLACE" visualizzato.
*   **ESC**: Per uscire da questa modalità senza salvare.

### 9.2. MEMORIZZAZIONE DEI VALORI VISUALIZZATI IN FUNZIONE ANALYZER

Durante una misura in tempo reale in posizione `ANALYZER` l'operatore può salvare la videata di valori presenti sul display premendo il tasto SAVE. Il corrispondente record creato nella MEMORIA ANALYZER conterrà i valori delle tensioni, correnti, potenze, armoniche, Pf, cos φ, ecc.. rilevati dallo strumento al momento della pressione del tasto.

## 10. REGISTRAZIONI

Si sottolinea ancora una volta la differenza fra la "memorizzazione" dei risultati visualizzati a display ed una "Registrazione":

*   la prima voce intende l'effettuazione di una "fotografia" istantanea ai valori presenti sul display dello strumento al momento della pressione del tasto `SAVE`.
*   la seconda voce presuppone la memorizzazione automatica da parte dello strumento dei parametri selezionati anche per tempi lunghi.

### 10.1. AVVIO DI UNA REGISTRAZIONE

L'avvio di una Registrazione può essere impostato MANUALE o AUTOMATICO (vedi paragrafi 7.2.1 e 8.2). Terminate la fase di impostazione, ed usciti quindi dalla modalità Menu lo strumento avvierà le registrazioni seguendo la logica di seguito illustrata:

*   **MANUALE**: La registrazione si avvierà all'inizio del minuto successivo alla pressione del tasto START/STOP.
*   **AUTO**: Qualora l'operatore abbia premuto il tasto START/STOP lo strumento rimarrà in stato di attesa fino al raggiungimento dalla data e ora impostate per poi avviare la Registrazione (che verrà terminata alla data e ora stabilita). Se l'operatore non preme il tasto START/STOP invece la Registrazione non si avvierà mai.

In attesa di raggiungere l'ora e la data di avvio lo strumento visualizza il messaggio "Attendere".

> **ATTENZIONE**
> Se si intende effettuare una registrazione si consiglia di utilizzare SEMPRE l'alimentatore esterno (codice A0050, opzionale per GSC57) Avviando una Registrazione senza che sia collegato l'alimentatore lo strumento visualizza il messaggio "no Alim esterna". Per avviare comunque la registrazione premere nuovamente il tasto `START/STOP`. Nel caso in cui venisse a mancare Tensione dall’Alimentatore Esterno, o l'operatore avesse inavvertitamente avviato una registrazione senza utilizzare l'alimentatore esterno, questa potrà prolungarsi fino all'esaurimento delle batterie. Per questo motivo si suggerisce di inserire sempre un pacco batterie nuovo prima di iniziare una registrazione prolungata. I dati memorizzati fino al momento del definitivo spegnimento non andranno comunque persi.

Lo strumento dispone di sofisticati algoritmi per aumentare al massimo l'autonomia delle Batterie. In particolare:

*   Lo strumento spegne AUTOMATICAMENTE la retroilluminazione del display dopo circa 5 secondi.
*   Al fine di aumentare la durata delle batterie, qualora la tensione di queste ultime risulti troppo bassa, lo strumento disabilita la funzione di retroilluminazione del display.
*   Se lo strumento è in fase di sola visualizzazione in tempo reale (e non è collegato l'alimentatore esterno), trascorsi circa 5 minuti dall'ultima pressione del tasto o rotazione del commutatore, lo strumento avvierà la procedura di auto-spegnimento ("AUTOPOWER OFF").
*   Se lo strumento è in fase di registrazione o di misura di energia (e non è collegato l'alimentatore esterno), trascorsi circa 5 minuti dall'ultima pressione del tasto o rotazione del commutatore lo strumento avvierà la procedura di economizzazione batterie ("ECONOMY MODE") ovvero verrà spento il display mentre lo strumento continuerà a registrare.

### 10.2. IMPOSTAZIONE DI REGISTRAZIONI TIPICHE

Prima di effettuare registrazioni l'operatore dovrebbe effettuare una valutazione preliminare in tempo reale della situazione dell'impianto, decidere cosa registrare ed impostare coerentemente lo strumento. Per agevolare l'utente nelle fasi di impostazione sono previste sullo strumento due distinte modalità di registrazione predefinite:

1.  **Configurazione standard (default di fabbrica)**: comprende la maggior parte dei casi di utilizzo dello strumento.
2.  **Configurazioni tipiche**: consentono di definire in dettaglio le registrazioni per le seguenti situazioni:
    *   **EN50160**: Impostazione dei parametri per la qualità di rete secondo la EN 50160 (vedere il paragrafo 17.11.2).
    *   **ANOM. TENSIONE**: Impostazione dei parametri per la rilevazione delle Anomalie sulla tensione di rete (buchi, picchi, interruzioni, ecc…) (vedere il paragrafo 17.10).
    *   **ARMONICHE**: Impostazione dei parametri di Analisi Armonica per tensione e corrente (vedere il paragrafo 17.11).
    *   **AVVIO MACCH.**: Impostazione dei parametri relativi all’avvio di motori e macchine elettriche.
    *   **POTENZA & ENERGIA**: Impostazione dei parametri relativi alla misura di Potenza e Energia (vedere il paragrafo 17.12).

#### 10.2.1. Configurazione standard

La configurazione in cui è predefinito lo strumento (default di fabbrica) è la seguente:

*   **CONFIG ANALYZER:**
    *   Sistema: `4 fili`
    *   Frequenza: `50Hz`
    *   Fondo scala delle Pinze: `1000A`
    *   Tipo Pinze: `FlexEXT (GSC57), FlexINT(GSC59)`
    *   Rapporto di Trasformatori Voltmetrici: `1`
    *   Password: `OFF`
*   **CONFIG RECORDER:**
    *   Start: `MAN` (la registrazione si avvia all’inizio del minuto successivo alla pressione del tasto `START`)
    *   Stop: `MAN`
    *   Periodo di Integrazione: `15min`
    *   Registrazione delle Armoniche: `ON`
    *   Registrazione delle anomalie di Tensione: `ON`
    *   Tensione di Riferimento per le Anomalie di Tensione: `230V`
    *   Limite superiore per le anomalie di Tensione: `6%`
    *   Limite Inferiore per le anomalie di Tensione: `10%`
    *   Tensioni selezionate: `V1, V2, V3`
    *   Armoniche di Tensione: `THD, 01, 03, 05, 07`
    *   Correnti selezionate: `I1, I2, I3, IN`
    *   Armoniche di corrente: `THD, 01, 03, 05, 07`
    *   CO-GENERAZIONE: `OFF`
    *   Potenze, Pf e cos φ:
        *   `Pt, P1, P2, P3`
        *   `Qti, Q1i, Q2i, Q3i`
        *   `Qtc, Q1c, Q2c, Q3c`
        *   `St, S1, S2, S3`
        *   `Pft, Pf1, Pf2, Pf3`
        *   `dpft, dpf1, dpf2, dpf3`
    *   Energie:
        *   `Eat, Ea1, Ea2, Ea3`
        *   `Erit, Eri1, Eri2, Eri3`
        *   `Erct, Erc1, Erc2, Erc3`

La pressione del tasto `START/STOP` avvia la registrazione delle grandezze selezionate secondo le modalità impostate nel menu (vedi paragrafi 8.1 e 8.2). La posizione del commutatore NON influenza la selezione dei parametri effettuati. Poiché il valore di default del periodo di integrazione è impostato a 15min, lo strumento accumulerà internamente dati nella memoria temporanea per tale tempo. Trascorso tale periodo di tempo lo strumento elaborerà i risultati memorizzati nella memoria temporanea e salverà nella memoria definitiva dello strumento la prima serie di valori relativi alla registrazione. Pertanto, supponendo di aver impostato un periodo di integrazione di 15min, la durata della registrazione dovrà essere almeno di 15 minuti per produrre una serie di valori registrati e quindi trasferibili al PC. Interrompendo invece la registrazione prima che il Periodo di integrazione selezionato sia totalmente trascorso i dati accumulati nella memoria temporanea non verranno elaborati e la serie di dati ad essi relativi non saranno posti nella memoria definitiva.

#### 10.2.2. Configurazioni tipiche

Per l’attivazione delle configurazioni tipiche operare nel modo seguente:
1.  Selezionare la posizione `ANALYZER` del selettore.
2.  Premere il tasto `MENU`. Lo strumento mostra il “Menù Generale” seguente:

    ```
    MENU GENERALE

    MEMORIA   SAFETY   TEST
    MEMORIA   ANALYZER
    RESET CONFIG   ANALYZER
    CONFIG   RECORDER
    CONTRASTO
    DATA&ORA
    LINGUA
    ```
3.  Premere nuovamente il tasto `MENU`. Lo strumento presenta la schermata riportata nella parte sinistra della figura seguente, in cui è possibile selezionare con i tasti freccia `F1` o `F2` la configurazione desiderata:

    ```
    CONFIG. TIPICHE      CONFIG. TIPICHE
    EN50160              EN50160
    ANOM.   TENSIONE     ANOM.   TENSIONE
    ARMONICHE            ARMONICHE
    AVVIO   MACCH.       AVVIO   MACCH.
    POTENZA   &   ENERGIA  POTENZA   &   ENERGIA
                         Dati   salvati
    ```
    *Selezione Configurazione / Conferma configurazione scelta*
4.  Premere il tasto `ENTER`. Lo strumento presenta per alcuni secondi il messaggio “`Dati salvati`” che conferma la configurazione scelta, come mostrato nella parte destra della figura soprastante. Lo strumento si riporta quindi nella schermata iniziale di misura.

Di seguito sono riportati i parametri per ognuna delle 5 configurazioni tipiche:

**EN50160**

*   **CONFIG ANALYZER:**
    *   Sistema: `non modificato`
    *   Frequenza: `non modificata`
    *   Fondo scala delle Pinze: `non modificato`
    *   Tipo Pinze: `non modificato`
    *   Rapporto dei Trasformatori Voltmetrici: `non modificato`
    *   Password: `non modificata`
*   **CONFIG RECORDER:**
    *   Start: `MANU`
    *   Stop: `MANU`
    *   Periodo di Integrazione: `10min`
    *   Registrazione delle Armoniche: `ON`
    *   Registrazione delle anomalie di Tensione: `ON`
    *   Tensione di Riferimento per le Anomalie di Tensione: `230V(mono, 4-fili); 400V(3-fili)`
    *   Limite superiore per le anomalie di Tensione: `6%`
    *   Limite Inferiore per le anomalie di Tensione: `10%`
    *   Tensione selezionata: `V1(mono); V12,V32,V31(3-fili); V1,V2,V3 (4-fili)`
    *   Armoniche di Tensione: `THD,DC,01,02,03,04,05, … 25 (mono,3-fili); THD, 01,02,03,04,05,06,07,08,09,10,11,13,15,17,19,21,23,25 (4-fili)`
    *   COGENERAZIONE: `OFF`

**ANOM. TENSIONE**

*   **CONFIG ANALYZER:**
    *   Sistema: `non modificato`
    *   Frequenza: `non modificata`
    *   Fondo scala delle Pinze: `non modificato`
    *   Tipo Pinze: `non modificato`
    *   Rapporto dei Trasformatori Voltmetrici: `non modificato`
    *   Password: `non modificata`
*   **CONFIG RECORDER:**
    *   Start: `MANU`
    *   Stop: `MANU`
    *   Periodo di Integrazione: `1min`
    *   Registrazione delle Armoniche: `OFF`
    *   Registrazione delle anomalie di Tensione: `ON`
    *   Tensione di Riferimento per le Anomalie di Tensione: `230V(mono, 4-fili); 400V(3-fili)`
    *   Limite superiore per le anomalie di Tensione: `6%`
    *   Limite Inferiore per le anomalie di Tensione: `10%`
    *   Tensione selezionata: `V1(mono); V12,V32,V31(3-fili); V1,V2,V3,V12,V32,V31(4-fili)`
    *   Corrente selezionata: `I1 (mono); I1,I2,I3 (3-fili, 4-fili)`
    *   COGENERAZIONE: `OFF`

**ARMONICHE**

*   **CONFIG ANALYZER:**
    *   Tipo di sistema elettrico: `non modificato`
    *   Frequenza: `non modificata`
    *   Fondo scala delle Pinze: `non modificato`
    *   Tipo Pinze: `non modificato`
    *   Rapporto dei Trasformatori Voltmetrici: `non modificato`
    *   Password: `non modificata`
*   **CONFIG RECORDER:**
    *   Start: `MANU`
    *   Stop: `MANU`
    *   Periodo di Integrazione: `10min`
    *   Registrazione delle Armoniche: `ON`
    *   Registrazione delle anomalie di Tensione: `OFF`
    *   Tensione selezionata: `V1(mono); V12,V32,V31(3-fili); V1,V2,V3 (4-fili)`
    *   Arm.Tensione: `THD,DC,01,03…25 (mono); THD,DC,01,03,…17 (3-fili); THD,DC,01,03,…13 (4-fili)`
    *   Corrente selezionata: `I1 (mono); I1,I2,I3 (3-fili); I1,I2,I3,In (4-fili)`
    *   Arm. Corrente: `THD,DC,01,03,…25 (mono); THD,DC,01,03,…17 (3-fili); THD,DC,01,03,…13 (4-fili)`
    *   COGENERAZIONE: `OFF`

**AVVIO MACCH.**

*   **CONFIG ANALYZER:**
    *   Tipo di sistema elettrico: `non modificato`
    *   Frequenza: `non modificata`
    *   Fondo scala delle Pinze: `non modificato`
    *   Tipo Pinze: `non modificato`
    *   Rapporto dei Trasformatori Voltmetrici: `non modificato`
    *   Password: `non modificata`
*   **CONFIG RECORDER:**
    *   Start: `MANU`
    *   Stop: `MANU`
    *   Periodo di Integrazione: `5sec`
    *   Registrazione delle Armoniche: `ON`
    *   Registrazione delle anomalie di Tensione: `ON`
    *   Tensione di Riferimento per le Anomalie di Tensione: `230V(mono, 4-fili); 400V(3-fili)`
    *   Limite superiore per le anomalie di Tensione: `6%`
    *   Limite Inferiore per le anomalie di Tensione: `10%`
    *   Tensione selezionata: `V1(mono); V12,V32,V31(3-fili); V1,V2,V3 (4-fili)`
    *   Arm. Tensione: `THD,01,03,…15 (mono, 3-fili); THD,01,03,…11 (4-fili)`
    *   Corrente selezionata: `I1 (mono); I1,I2,I3 (3-fili); I1,I2,I3,In (4-fili)`
    *   Arm. Corrente: `THD,01,03,…15 (mono, 3-fili); THD,01,03,…11 (4-fili)`
    *   COGENERAZIONE: `OFF`
    *   Potenza, Pf e cos φ: `P1,Q1i,Q1c,S1,Pf1,DPf1(mono); Pt,Qti,Qtc,St,Pft,DPft (3-fili) Pt,P1,P2,P3,Qti,Qtc,St,Pft,DPft(4-fili)`
    *   Energia: `Ea1,Eri1,Erc1(mono); Eat,Erit,Erct (3-fili); Eat,Ea1,Ea2,Ea3,Erit,Erct (4-fili)`

**POTENZA & ENERGIA**

*   **CONFIG ANALYZER:**
    *   Tipo di sistema elettrico: `non modificato`
    *   Frequenza: `non modificata`
    *   Fondo scala delle Pinze: `non modificato`
    *   Tipo Pinze: `non modificato`
    *   Rapporto dei Trasformatori Voltmetrici: `non modificato`
    *   Password: `non modificata`
*   **CONFIG RECORDER:**
    *   Start: `MANU`
    *   Stop: `MANU`
    *   Periodo di Integrazione: `15min`
    *   Registrazione delle Armoniche: `OFF`
    *   Registrazione delle anomalie di Tensione: `OFF`
    *   Tensione selezionata: `V1(mono); V12,V32,V31(3-fili); V1,V2,V3,V12,V32,V31 (4-fili)`
    *   Corrente selezionata: `I1 (mono); I1,I2,I3 (3-fili); I1,I2,I3,In (4-fili)`
    *   COGENERAZIONE: `ON`
    *   Potenza, Pf e cos φ: `P1,Q1i,Q1c,S1,Pf1,DPf1(mono); Pt,P12,P23,Qti,Q12i,Q23i,Qtc,Q12c,Q23c,St,S12,S23,Pft,DPft (3-fili); Pt,P1,P2,P3,Qti,Q1i,Q2i,Q3i,Qtc,Q1c,Q2c,Q3ct,S1,S2,S3,Pft,Pf1,Pf2;Pf3,DPft,DPf1,DPf2,DPf3 (4-fili)`
    *   Energia: `Ea1,Eri1,Erc1(mono); Eat,Erit,Erct (3-fili); Eat,Ea1,Ea2,Ea3,Erit,Eri1,Eri2,Eri3,Erct,Erc1,Erc2,Erc3 (4-fili)`

La pressione del tasto `START/STOP` avvia la registrazione delle grandezze selezionate secondo le modalità impostate per ogni registrazione tipica. La posizione del commutatore NON influenza la selezione dei parametri effettuati.

### 10.3. DURANTE UNA REGISTRAZIONE

Nel caso in cui venisse a mancare tensione dall’alimentatore esterno, o l'operatore avesse inavvertitamente avviato una registrazione senza utilizzare l'alimentatore esterno, questa potrà prolungarsi fino all'esaurimento delle batterie. Per questo motivo si suggerisce di inserire sempre un `pacco batterie nuovo` prima di iniziare una registrazione prolungata. I dati memorizzati fino al momento del definitivo spegnimento non andranno comunque persi. Al fine di massimizzare la vita delle batterie, durante una registrazione senza l'alimentatore esterno viene automaticamente attivata la routine di ECONOMY MODE (spegnimento del solo display) trascorsi circa 5 minuti dall'ultima pressione del tasto o rotazione del commutatore. Durante una registrazione vengono disattivati:

*   Routine di `AUTOPOWER OFF`
*   Tasto `ON/OFF`
*   Tasto `HOLD`
*   Tasto `SAVE`

#### 10.3.1. Tasto MENU

Premendo il tasto `MENU` durante una registrazione appare la seguente videata che visualizza i principali di registrazione:

```
INFO REG n 01

START 09.18.01   11:35
STOP 10.10.02   10.00
PERIODO   INT:   900s
PERIODI   REG:00004
AUTONOM:139d.02h
REG.   HARM:   (ON)
REG.   ANOM:   (ON)
N   ANOMALIE:   00000
Reg   in   corso
```

Questa pagina include:
1.  Data e ora di avvio della registrazione
2.  Data e ora di arresto della registrazione
3.  Valore del periodo di integrazione
4.  Numeri di periodi di integrazione trascorsi
5.  Autonomia di registrazione espressa in giorni (d) / ore(h)
6.  Abilitazione/disabilitazione della registrazione delle armoniche
7.  Abilitazione/disabilitazione della registrazione delle anomalie di tensione
8.  Numero delle anomalie di tensione rilevate

#### 10.3.2. Commutatore rotativo

Qualora, in attesa della partenza di una registrazione, si ruoti il commutatore rotativo su una diversa posizione, comparirà la seguente videata:

```
Attendere
```
Lo strumento darà comunque inizio alla registrazione alla data ed ora impostate. Qualora, durante il corso di una registrazione, si ruoti il commutatore rotativo su una diversa posizione, comparirà la seguente videata:

```
Reg   in   corso
```
Lo strumento continuerà comunque a registrare.

### 10.4. ARRESTO DI UNA REGISTRAZIONE O DI UNA MISURA DI ENERGIA

Lo strumento è dotato di una routine di protezione per evitare che durante una registrazione o una misura dell'energia lo strumento possa essere manomesso o la misurazione interrotta. Se l'opzione `PASSWORD` è abilitata e si è avviata una registrazione o una misura diretta dell'energia, vedi Paragrafo 8.7.2, trascorsi circa 3 minuti dall'ultima pressione di un tasto o rotazione del commutatore, qualora venga premuto il tasto `START/STOP` (per una Registrazione) o il tasto `F2` (per una Misura di energia), lo strumento non arresterà la registrazione bensì richiederà l'inserimento della PASSWORD. L'inserimento della password (non modificabile) comporta la pressione in sequenza dei seguenti tasti (entro 10 secondi):

`F1`, `F4`, `F3`, `F2`

Per abilitare/disabilitare questa opzione si veda il paragrafo 8.1.6. Qualora si inserisca una password errata lo strumento visualizzerà una messaggio di errore sul display e tornerà a visualizzare la richiesta. Se non si preme nessun tasto dopo circa 10 secondi lo strumento tornerà alla videata originale.

## 11. MEMORIA DELLO STRUMENTO

La pressione del tasto `MENU` visualizza la seguente videata:

```
MENU GENERALE

MEMORIA   SAFETY   TEST
MEMORIA   ANALYZER
RESET CONFIG   ANALYZER
CONFIG   RECORDER
CONTRASTO
DATA&ORA
LINGUA
```
Non è possibile accedere al MENU durante una registrazione o una misura diretta dell'Energia.

### 11.1. MEMORIA SAFETY TEST

Selezionando la voce MEMORIA SAFETY TEST viene visualizzato l'elenco delle prove di verifica archiviate nella memoria dello strumento.

```
MEMORIA SAFETY TEST

MEM   TIPO   PLACE
001   LOW Ω   003
002   EARTH   003
003   LOW Ω 10A   004
004   M Ω   004
005   RCD   004
TOT:005   LIBERA:994
```
*Esempio di videata della MEMORIA SAFETY TEST*

*   **MEM**: Locazione di memoria in cui sono stati memorizzati i valori della prova di verifica
*   **TIPO**: Tipo di MISURA (corrispondente alla posizione del Commutatore)
*   **PLACE**: Valore del parametro mnemonico "PLACE" associato alla misura
*   **TOT**: Numero totale prove di verifica Archiviate
*   **LIBERA**: Numero di locazioni libere per altre memorizzazioni

Sono attivi i seguenti tasti:

*   **F1**, **F2**: Per selezionare una misura
*   **ENTER**: Per visualizzare i risultati della Prova selezionata
*   **F3**: Per cancellare l'ultima misura archiviata.
*   **F4**: Per cancellare TUTTE le prove di verifica archiviate (la MEMORIA ANALYZER non verrà cancellata).
*   **ESC**: per uscire dalla modalità MEMORIA SAFETY TEST

### 11.2. MEMORIA ANALYZER

Selezionando questa modalità è possibile visualizzare:

*   Il contenuto attuale della memoria dello strumento
*   La dimensione dei dati attualmente memorizzati
*   L'Autonomia residua di spazio in memoria per future registrazioni (espressa in giorni e ore).

Tutti i dati memorizzati sono visualizzabili solo tramite trasferimento dati ad un PC tramite il software di Gestione.

Selezionando questa funzione viene visualizzata una videata del tipo:

```
MEMORIA ANALYZER

01   Smp   02.01   01:23
02   Reg   02.01-02.01
03   R&a   02.01-02.01
04   Reg   02.01-02.01
05   R&a   02.01-02.01
06   Reg   04.01-05.01
DIM   DATI:0.11Mb
AUTONOM:   0d/06h
```
*Esempio di Videata della MEMORIA ANALYZER*

In essa sono indicate con:

*   **Reg**: Registrazioni effettuate con relativa data di start e stop nel formato "giorno.mese" (start) – "giorno.mese" (stop) senza analisi delle anomalie di tensione.
*   **R&a**: Registrazioni effettuate con relativa data di start e stop nel formato "giorno.mese" (start) – "giorno.mese" (stop) con analisi delle anomalie di tensione
*   **Smp**: La data e l’ora in cui i valori dei Campioni di tensione e corrente sono stati archiviati tramite pressione del tasto SAVE.
*   **DIM DATI**: Dimensioni dei dati contenuti in memoria. La dimensione massima è circa 2Mb.
*   **AUTONOM**: L'autonomia residua (espressa in giorni(d) / ore(h)) per effettuare registrazione calcolata sulla base delle impostazioni correnti. Il numero massimo di Reg + R&a + Smp contenibili dallo strumento è `35`.

Sono attivi i seguenti tasti:

*   **F1**, **F2**: (solo se il numero Reg+R&a+Smp è superiore a 7) Scorre tutte le registrazioni presenti in memoria.
*   **F3**: Cancella l'ultima registrazione effettuata.
*   **F4**: Cancella tutte le registrazioni effettuate.

## 12. COLLEGAMENTO DELLO STRUMENTO AD UN PC

Il collegamento dello strumento ad un PC avviene tramite il Cavo C2001 (Accoppiatore Ottico-Seriale RS232). Sono disponibili le seguenti velocità di Trasmissione: 9600, 19200, 57600 (Valore di Default) Il valore della velocità di trasmissione (baud rate) è visualizzato nella videata iniziale dello strumento (vedi paragrafo 4.2). Il valore della velocità di trasmissione può essere modificato solo tramite il programma di gestione per PC. La procedura per il trasferimento dei dati memorizzati ad un PC (dopo aver installato il SW di gestione dati) può essere schematizzato come segue:

1.  Accendere lo strumento ed attendere che la videata iniziale scompaia (la posizione del commutatore non è rilevante). Assicurarsi che lo strumento sia in una qualsiasi videata di misura ad eccezione della schermata “Z2 Ω” di attivazione comunicazione con l’accessorio IMP57 (vedere il paragrafo 6.4.1).
2.  Collegare il connettore ottico del cavo C2001 allo strumento ed il connettore RS232 ad una porta COM del PC.
3.  Avviare il programma di gestione dati sul PC
4.  Selezionare il comando "Download" per avviare la procedura di trasferimento.

## 13. COLLEGAMENTO CON PROTOCOLLO BLUETOOTH

> **WARNING**
> Tale connessione richiede un PC dotato di protocollo Bluetooth.

Lo strumento consente di trasferire i dati memorizzati in maniera "wireless" (con parametri tipici del protocollo Bluetooth). Procedere come segue:
1.  Collegare lo strumento di unità remota (opzionale c2008 accessorio) tramite USB / cavo ottico C2006. Controllare il LED "USB" si accende.
2.  Selezionare la velocità di trasferimento dati pari a 57600 baud usando i tasti freccia su c2008 (controllare che tale valore è impostato sullo strumento).
3.  Effettuare la ricerca per il dispositivo c2008 (per ulteriori dettagli consultare il manuale utente c2008's) fino a quando lo strumento che identifica.
4.  Avviare il software Topview seguendo la procedura (guardare l'help in linea per ulteriori dettagli) per avviare il trasferimento di dati.

## 14. MANUTENZIONE

### 14.1. GENERALITÀ

1.  Lo strumento da Lei acquistato è uno strumento di precisione. Durante l’utilizzo e l’immagazzinamento rispettare le raccomandazioni elencate in questo manuale per evitare possibili danni o pericoli durante l’utilizzo.
2.  Non utilizzare lo strumento in ambienti caratterizzati da elevato tasso di umidità o temperatura elevata. Non esporre direttamente alla luce del sole.
3.  Spegnere sempre lo strumento dopo l’utilizzo. Se si prevede di non utilizzarlo per lungo tempo rimuovere le batterie per evitare fuoruscite di liquidi che possano danneggiare i circuiti interni dello strumento.

### 14.2. SOSTITUZIONE BATTERIE

Il simbolo "`_`" indica il livello di carica. Quando questo è completamente "nero" le batterie sono completamente cariche; il diminuire della zona nera "`_`" indica invece che le batterie sono quasi scariche. In questo caso interrompere le prove e procedere alla sostituzione delle batterie in accordo a quanto descritto nel presente paragrafo. Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie. Le impostazioni di data e ora restano invece inalterate solo se la sostituzione delle batterie viene effettuate entro circa 24 ore.

> **ATTENZIONE**
> Solo tecnici qualificati possono effettuare questa operazione. Prima di effettuare questa operazione assicurarsi di aver rimosso tutti i cavi dai terminali di ingresso.

Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie.

1.  Spegnere lo strumento tramite il tasto ON/OFF
2.  Rimuovere tutti i cavi dai terminali di ingresso.
3.  Svitare la vite di fissaggio del coperchio al vano a batterie e rimuovere lo stesso.
4.  Rimuovere tutte le batterie sostituendole con sei nuove dello stesso tipo (1.5V – LR6 – AA – AM3 – MN 1500) rispettando le polarità indicate.
5.  Riposizionare la copertura del vano a batterie e fissarla con l'apposita vite.

### 14.3. PULIZIA DELLO STRUMENTO

Per la pulizia dello strumento utilizzare un panno morbido e asciutto. Non usare mai panni umidi, solventi, acqua, ecc.

> **FINE VITA**
> Attenzione: il simbolo riportato indica che l'apparecchiatura ed i suoi accessori deve essere raccolta separatamente e trattata in modo corretto.

## 15. SPECIFICHE TECNICHE

### 15.1. CARATTERISTICHE TECNICHE

La precisione è indicata come [% della lettura + numero di cifre]. Essa è riferita alle seguenti condizioni atmosferiche: temperatura 23°C ± 5°C, umidità relativa < 60%.

#### 15.1.1. Prove di verifica

*   **MISURA DELLA CONTINUITÀ DEI CONDUTTORI DI PROTEZIONE ED EQUIPOTENZIALI (Modalità AUTO, RT+, RT-)**

| Portata [Ω] | Risoluzione [Ω] | Precisione (*) |
| :---------- | :-------------- | :------------- |
| 0.01 ÷ 9.99 | 0.01            |                |
| 10.0 ÷ 99.9 | 0.1             | ± (2% lettura + 2 cifre) |

(*) Considerando la calibrazione che elimina la resistenza del cavo

*   Corrente di prova: > 200mA DC per R ≤ 5 Ω (inclusa la calibrazione)
*   Risoluzione misura della corrente: 1mA
*   Tensione a vuoto: 4V ≤ V 0 ≤ 24V

*   **MISURA DELLA RESISTENZA DI ISOLAMENTO (Mod. MAN, TIMER)**

| Tensione di prova [V] | Portata [MΩ]   | Risoluzione [MΩ] | Precisione                        |
| :-------------------- | :------------- | :--------------- | :-------------------------------- |
| 50                    | 0.01 ÷ 9.99    | 0.01             | ± (2% lettura + 2 cifre) se V/R>1 µA |
|                       | 10.0 ÷ 49.9    | 0.1              |                                   |
|                       | 50.0 ÷ 99.9    | 0.1              | ± (5% lettura + 2 cifre) se V/R ≤ 1 µA |
| 100                   | 0.01 ÷ 9.99    | 0.01             | ± (2% lettura + 2 cifre) se V/R>1 µA |
|                       | 10.0 ÷ 99.9    | 0.1              |                                   |
|                       | 100.0 ÷ 199.9  | 0.1              | ± (5% lettura + 2 cifre) se V/R ≤ 1 µA |
| 250                   | 0.01 ÷ 9.99    | 0.01             | ± (2% lettura + 2 cifre) se V/R>1 µA |
|                       | 10.0 ÷ 199.9   | 0.1              |                                   |
|                       | 200 ÷ 249      | 1                |                                   |
|                       | 250 ÷ 499      | 1                | ± (5% lettura + 2 cifre) se V/R ≤ 1 µA |
| 500                   | 0.01 ÷ 9.99    | 0.01             | ± (2% lettura + 2 cifre) se V/R>1 µA |
|                       | 10.0 ÷ 199.9   | 0.1              |                                   |
|                       | 200 ÷ 499      | 1                |                                   |
|                       | 500 ÷ 999      | 1                | ± (5% lettura + 2 cifre) se V/R ≤ 1 µA |
| 1000                  | 0.01 ÷ 9.99    | 0.01             | ± (2% lettura + 2 cifre) se V/R>1 µA |
|                       | 10.0 ÷ 199.9   | 0.1              |                                   |
|                       | 200 ÷ 999      | 1                |                                   |
|                       | 1000 ÷ 1999    | 1                | ± (5% lettura + 2 cifre) se V/R ≤ 1 µA |

*   Tensione a vuoto: <1.3 x Tensione di Prova nominale
*   Corrente di cortocircuito: <6.0mA a 500V impostati
*   Corrente di misura nominale: >2.2mA su 230kΩ (500V) >1mA su 1kΩ per Vnom (altre tensioni di prova)
*   Limiti di misura impostabili: 0.05, 0.10, 0.23, 0.25, 0.50, 1.00, 100MΩ

*   **PROVE DI INTERVENTO DIFFERENZIALI (RCD)**
    *   Correnti di intervento nominali (IΔN): 10mA, 30mA, 100mA, 300mA, 500mA
    *   Tipo di Differenziale: AC, A Generali e Selettivi
    *   Tensione fase-terra: 100V ÷ 265V
    *   Frequenza: 50Hz ± 0.5Hz

    **Tempo di intervento tΔN**

    | Portata [ms] | Risoluzione [ms] | Precisione           |
    | :----------- | :--------------- | :------------------- |
    | ½ IΔN, IΔN   | 1 ÷ 999          | 1                    |
    | 2 IΔN        | 1 ÷ 200 generali | 1 ÷ 250 selettivi    | ± (2% lettura+2 cifre) |
    | 5 IΔN        | 1 ÷ 50 generali  | 1 ÷ 160 selettivi    |                      |

    **Tensione di Contatto Ut**

    | Portata [V]    | Risoluzione [V] | Precisione                  |
    | :------------- | :-------------- | :-------------------------- |
    | 0 ÷ 2Ut lim    | 0.1             | - 0%, +(10% lettura + 3 cifre) |

    Ut LIM (UL): 25V o 50V

    **Resistenza di terra RA senza intervento del differenziale**

    | Portata [Ω] | Risoluzione [Ω] | Precisione          |
    | :---------- | :-------------- | :------------------ |
    | 1 ÷ 1999    | 1               | ± (5% lettura + 3 cifre) |

    Corrente di prova: 0.5 IΔN impostata nella prova Ut 15mA nella prova Ra 15mA

    **Misura della Corrente di Intervento**

    | Tipo RCD | IΔN       | Portata IΔN [mA] | Risoluzione [mA] | Precisione IΔN |
    | :------- | :-------- | :--------------- | :--------------- | :------------- |
    | AC       | IΔN ≤ 10mA | (0.5 ÷ 1.4) IΔN  | 0.1 IΔN          | - 0%, +10% IΔN |
    | A        |           | (0.5 ÷ 2.4) IΔN  | 0.1 IΔN          | - 0%, +10% IΔN |
    | AC       | IΔN > 10mA | (0.5 ÷ 1.4) IΔN  | 0.1 IΔN          | - 0%, +10% IΔN |
    | A        |           | (0.5 ÷ 2) IΔN    | 0.1 IΔN          | - 0%, +10% IΔN |

*   **MISURA DELLA FREQUENZA**

| Portata [Hz] | Risoluzione [Hz] | Precisione             |
| :----------- | :--------------- | :--------------------- |
| 47.0 ÷ 63.6  | 0.1              | ± (0.1% lettura+1 cifra) |

Le misure di RCD e LOOP sono attive solo per 50Hz ± 0.5Hz

*   **MISURA DI TENSIONE (RCD, LOOP, SENSO CICLICO)**

| Portata [V] | Risoluzione [V] | Precisione          |
| :---------- | :-------------- | :------------------ |
| 30 ÷ 460V   | 1               | ± (3% lettura + 2 cifre) |

*   **MISURA DELL’IMPEDENZA DI LINEA (fase-fase, fase-neutro)**

| Portata [Ω] | Risoluzione [Ω] | Precisione (*)    |
| :---------- | :-------------- | :---------------- |
| 0.01 ÷ 9.99 | 0.01            |                   |
| 10.0 ÷ 199.9 | 0.1             | ± (5% lettura + 3 cifre) |

(*) 0.1 mΩ nella portata 0.0 ÷ 199.9 mΩ (con IMP57)

*   Corrente di picco massima alla tensione di prova:
    *   127V 3.65A
    *   230V 6.64A
    *   400V 11.5A
*   Tensione di prova fase-neutro/fase-fase: 100 ÷ 265/100 ÷ 460V 50Hz
*   Frequenza: 50Hz ± 0.5Hz

*   **MISURA IMPEDENZA DELL’ANELLO DI GUASTO (fase-terra)**

| Portata [Ω] | Risoluzione [Ω] | Precisione (*)    |
| :---------- | :-------------- | :---------------- |
| 0.01 ÷ 19.99 | 0.01            |                   |
| 20.0 ÷ 199.9 | 0.1             |                   |
| 200 ÷ 1999  | 1               | ± (5% lettura + 3 cifre) |

(*) 0.1 mΩ nella portata 0.0 ÷ 199.9 mΩ (con IMP57)

*   Corrente di picco massima alla tensione di prova:
    *   127V 3.65A
    *   230V 6.64A
*   Tensione di prova fase-terra: 100 ÷ 265V 50Hz
*   Frequenza: 50Hz ± 0.5Hz

*   **MISURA RESISTENZA DELL’ANELLO DI GUASTO SENZA INTERVENTO DEL DIFFERENZIALE (fase-terra RA 15mA)**

| Portata [Ω] | Risoluzione [Ω] | Precisione          |
| :---------- | :-------------- | :------------------ |
| 1 ÷ 1999    | 1               | ± (5% lettura + 3 cifre) |

*   Corrente di prova: 15mA
*   Tensione di prova fase-terra: 100 ÷ 265V 50Hz
*   Frequenza: 50Hz ± 0.5Hz

*   **MISURA DELLA RESISTENZA DI TERRA TRAMITE PICCHETTI**

| Campo RE [Ω] | Risoluzione [Ω] | Precisione          |
| :----------- | :-------------- | :------------------ |
| 0.01 ÷ 19.99 | 0.01            |                   |
| 20.0 ÷ 199.9 | 0.1             |                   |
| 200 ÷ 1999  | 1               | ± (5% lettura + 3 cifre) |

*   Corrente di prova: <10mA – 77.5Hz
*   Tensione a vuoto: <20V RMS

*   **MISURA DELLA RESISTIVITA’ DEL TERRENO**

| Campo ρ (*)          | Risoluzione     | Precisione          |
| :------------------- | :-------------- | :------------------ |
| 0.60 ÷ 19.99 Ωm      | 0.01 Ωm         |                   |
| 20.0 ÷ 199.9 Ωm      | 0.1 Ωm          |                   |
| 200 ÷ 1999 Ωm       | 1 Ωm            |                   |
| 2.00 ÷ 99.99k Ωm     | 0.01 kΩm        |                   |
| 100.0 ÷ 125.6k Ωm    | 0.1 kΩm         | ± (5% lettura + 3 cifre) |

(*) con distanza = 10m

*   Campo di impostazione distanza: d: 1 ÷ 10m
*   Corrente di prova: <10mA – 77.5Hz
*   Tensione a vuoto: <20V RMS

*   **MISURA DELLA CONTINUITA’ 10A SECONDO CEI 64-8/7 (solo GSC57)**

| Portata [Ω]     | Risoluzione [Ω] | Precisione          |
| :-------------- | :-------------- | :------------------ |
| 0.001 ÷ 0.999   | 0.001           | ± (1% lettura + 2 cifre) |

*   Corrente di prova: > 10A AC per R ≤ 0.45 Ω
*   Risoluzione misura della corrente: 0.1A
*   Tensione a vuoto: Compresa fra 6 e 12V~
*   Alimentazione: 230V~ 50Hz

*   **MISURA DELLA CONTINUITA SECONDO EN60204-1 / CEI 44-5 (solo GSC57)**

| Portata [V] | Risoluzione [V] | Precisione          |
| :---------- | :-------------- | :------------------ |
| 0.01 ÷ 9.99 | 0.01            | ± (1% lettura + 2 cifre) |

*   Corrente di prova: > 10A AC per R ≤ 0.45 Ω
*   Risoluzione misura della corrente: 0.1A
*   Tensione a vuoto: Minore di 12V~
*   Alimentazione: 230V~ 50Hz

#### 15.1.2. Funzioni ANALYZER e AUX

*   **MISURA DI TENSIONE – SISTEMI MONOFASE E TRIFASE (AUTORANGE)**

| Portata [V] | Risoluzione [V] | Precisione          | Impedenza d’ingresso   |
| :---------- | :-------------- | :------------------ | :--------------------- |
| 15 ÷ 310    | 0.2             | ± (0.5% lettura + 2 cifre) | 300kΩ (Fase-Neutro)    |
| 310 ÷ 600   | 0.4             |                     | 300kΩ (Fase-Fase)      |

Per tensione DC aggiungere 0.5%lettura alla precisione. Frequenza 45..65Hz

*   **MISURA DI ANOMALIE DI TENSIONE – SISTEMI MONOFASE E TRIFASE (selezione MANUALE della PORTATA)**

| Portata [V] | Risoluzione (Tensione) | Risoluzione (Tempo) | Precisione (Tensione) | Precisione (rif. 50Hz) (Tempo) | Impedenza d’ingresso   |
| :---------- | :--------------------- | :------------------ | :-------------------- | :----------------------------- | :--------------------- |
| 15 ÷ 310    | 0.2V                   | 10ms                | ± (1.0% lettura + 2 cifre) | ± 10ms                         | 300kΩ (Fase-Neutro)    |
| 30 ÷ 600    | 0.4V                   |                     |                       |                                | 300kΩ (Fase-Fase)      |

Frequenza 45..65Hz

*   **MISURA DI CORRENTE TRAMITE PINZE FlexEXT e STD – SISTEMI MONOFASE E TRIFASE**

| Fondo scala (*)   | Risoluzione [mV] | Precisione          | Impedenza d’ingresso | Protezione contro sovraccarichi |
| :---------------- | :--------------- | :------------------ | :------------------- | :------------------------------ |
| 0.005 ÷ 0.26V     | 0.1              | ± (0.5% lettura + 2 cifre) | 200kΩ (GSC57)        | 5V                              |
| 0.26 ÷ 1V         | 0.4              |                     | 400kΩ (GSC59)        |                                 |

(*): Esempio: utilizzando una pinza con fondo scala pari a 1000A/1V, lo strumento misura correnti superiori a 5A

*   **MISURA DI CORRENTE TRAMITE PINZA FlexINT (solo GSC59), portata 1000A – SISTEMI MONOFASE E TRIFASE**

| Fondo scala (A) | Ingresso tensione             | Risoluzione | Precisione                       |
| :-------------- | :---------------------------- | :---------- | :------------------------------- |
| 10.0 ÷ 19.9     | 950.0 µV ÷ 1.691mV            | 8.5 µV      | ± (4.0 % lettura+8.5 µV)       |
| 20.0 ÷ 99.9     | 1.7mV ÷ 8.491mV               |             | ± (1.0 % lettura+8.5 µV)       |
| 100.0 ÷ 999.9   | 8.5mV ÷ 84.99mV               |             | ± (1.0 % lettura+85 µV)        |

1A = 85 µV ; Rinput = 400kΩ , Frequenza 45..65Hz

*   **MISURA DI CORRENTE TRAMITE PINZA FlexINT (solo GSC59), portata 3000A – SISTEMI MONOFASE E TRIFASE**

| Fondo scala (A) | Ingresso tensione             | Risoluzione | Precisione                       |
| :-------------- | :---------------------------- | :---------- | :------------------------------- |
| 30.0 ÷ 999.9    | 2.55mV ÷ 84.99mV              | 8.5 µV      | ± (1.0 % lettura+17 µV)        |
| 1000 ÷ 3000     | 85.0mV ÷ 255mV                | 85 µV       | ± (0.5 % lettura+85 µV)        |

1A = 85 µV ; Rinput = 400kΩ , Frequenza 45..65Hz

*   **MISURA DI POTENZA E ENERGIA – SISTEMI MONOFASE E TRIFASE**

| Tipo Misura       | Portata          | Precisione              | Risoluzione   |
| :---------------- | :--------------- | :---------------------- | :------------ |
| POTENZA ATTIVA    | 100.0 ÷ 999.9W   | ± (1.0% lettura + 2 cifre) | 0.1W          |
|                   | 1.000 ÷ 9.999kW  |                         | 0.001kW       |
|                   | 10.00 ÷ 99.99kW  |                         | 0.01kW        |
|                   | 100.0 ÷ 999.9kW  |                         | 0.1kW         |
|                   | 1.000 ÷ 9.999MW  |                         | 0.001MW       |
|                   | 10.00 ÷ 99.99MW  |                         | 0.01MW        |
|                   | 100.0 ÷ 999.9MW  |                         | 0.1MW         |
| POTENZA REATTIVA  | 100.0 ÷ 999.9VAR |                         | 0.1VAR        |
|                   | 1.000 ÷ 9.999kVAR |                         | 0.001kVAR     |
|                   | 10.00 ÷ 99.99kVAR |                         | 0.01kVAR      |
|                   | 100.0 ÷ 999.9kVAR |                         | 0.1kVAR       |
|                   | 1.000 ÷ 9.999MVAR |                         | 0.001MVAR     |
|                   | 10.00 ÷ 99.99MVAR |                         | 0.01MVAR      |
|                   | 100.0 ÷ 999.9MVAR |                         | 0.1MVAR       |
| POTENZA APPARENTE | 100.0 ÷ 999.9VA  |                         | 0.1VA         |
|                   | 1.000 ÷ 9.999kVA |                         | 0.001kVA      |
|                   | 10.00 ÷ 99.99kVA |                         | 0.01kVA       |
|                   | 100.0 ÷ 999.9kVA |                         | 0.1kVA        |
|                   | 1.000 ÷ 9.999MVA |                         | 0.001MVA      |
|                   | 10.00 ÷ 99.99MVA |                         | 0.01MVA       |
|                   | 100.0 ÷ 999.9MVA |                         | 0.1MVA        |
| ENERGIA ATTIVA (Classe2 EN61036) | 100.0 ÷ 999.9Wh  |                         | 0.1Wh         |
|                   | 1.000 ÷ 9.999kWh |                         | 0.001kWh      |
|                   | 10.00 ÷ 99.99kWh |                         | 0.01kWh       |
|                   | 100.0 ÷ 999.9kWh |                         | 0.1kWh        |
|                   | 1.000 ÷ 9.999MWh |                         | 0.001MWh      |
|                   | 10.00 ÷ 99.99MWh |                         | 0.01MWh       |
|                   | 100.0 ÷ 999.9MWh |                         | 0.1MWh        |
| ENERGIA REATTIVA (Classe3 IEC1268) | 100.0 ÷ 999.9VARh |                         | 0.1VARh       |
|                   | 1.000 ÷ 9.999kVARh |                         | 0.001kVARh    |
|                   | 10.00 ÷ 99.99kVARh |                         | 0.01kVARh     |
|                   | 100.0 ÷ 999.9kVARh |                         | 0.1kVARh      |
|                   | 1.000 ÷ 9.999MVARh |                         | 0.001MVARh    |
|                   | 10.00 ÷ 99.99MVARh |                         | 0.01MVARh     |
|                   | 100.0 ÷ 999.9MVARh |                         | 0.1MVARh      |

Precisione garantita per V>100V, I>10%FS, cosphi>0.5, frequenza 45..65Hz

*   **MISURE DI Cos φ – SISTEMI MONOFASE E TRIFASE**

| Cos φ       | Risoluzione | Precisione [°] |
| :---------- | :---------- | :------------- |
| 0.20 ÷ 0.50 | 0.01        | 1.0            |
| 0.50 ÷ 0.80 |             | 0.7            |
| 0.80 ÷ 1.00 |             | 0.6            |

Frequenza 45..65Hz

*   **MISURE DI ARMONICHE – SISTEMI MONOFASE E TRIFASE**

| Portata | Precisione di base         | Risoluzione Massima |
| :------ | :------------------------- | :------------------ |
| DC ÷ 25H | ± ( 5% lettura + 2 cifre) | 0.1V / 0.1A         |
| 26H ÷ 33H | ± ( 10% lettura + 2 cifre) |                     |
| 34H ÷ 49H | ± ( 15% lettura + 2 cifre) |                     |

Le armoniche vengono azzerate sotto le seguenti soglie:
*   DC: se <2% della 1ª armonica o se < 0,2% del Fondo Scala delle Pinze
*   1ª armonica: se <0,2% del Fondo Scala delle Pinze
*   2ª ÷ 49ª: se <2% della 1ª armonica o se < 0,2% del Fondo Scala delle Pinze

Frequenza 45..65Hz, l’impostazione `FLEX` disabilita la misura delle Componenti DC

*   **MISURE DEI PARAMETRI AMBIENTALI (Funzione AUX)**

| Portata               | Precisione              | Risoluzione      |
| :-------------------- | :---------------------- | :--------------- |
| -20°C ÷ 80 °C         | ± (2% lettura + 2 cifre) | 0.1 °C           |
| 0 ÷ 100% UR           |                         | 0.1% UR          |
| 0.001Lux ÷ 20.00 Lux (*) | 0.001 ÷ 0.02 Lux        |                  |
| 0.1Lux ÷ 2000 Lux (*) | 0.1 ÷ 2 Lux             |                  |
| 1Lux ÷ 20 kLux (*)    | 1 ÷ 20 Lux              |                  |

(*) La precisione per la sonda luxmetrica HT53 è conforme alla classe AA

*   **MISURA DI CORRENTE DI DISPERSIONE (tramite Pinza opzionale)**

| Portata [mA] (*) | Risoluzione [mA] | Precisione             | Impedenza d’ingresso | Protezione contro sovraccarichi |
| :--------------- | :--------------- | :--------------------- | :------------------- | :------------------------------ |
| 0.5 ÷ 999.9      | 0.1              | ± (5% lettura + 2digit) | 200kΩ                | 5V                              |

(*): Durante la registrazione lo strumento memorizza solo valori di corrente > 5mA con risoluzione 1mA
Il valore massimo registrato è il valore di picco valutato con tempo di risposta di 1ms

### 15.2. RIFERIMENTI NORMATIVI

#### 15.2.1. Generali

*   Sicurezza strumenti di misura: EN 61010-1
*   Isolamento: classe 2
*   Livello inquinamento: 2
*   Categoria di sovratensione: CAT II 600VAC (ingressi) / 350VAC verso terra; CAT III 600VAC (ingressi) / 300VAC verso terra
*   Categoria di sovratensione: Utilizzo in interni; altitudine max: 2000m

#### 15.2.2. EMC

Questo strumento è conforme ai requisiti della Direttiva Europea sulla bassa tensione 2006/95/CE (LVD) e della direttiva EMC 2004/108/CE.

#### 15.2.3. Riferimenti normativi delle misure di verifica

*   LOW Ω (200mA): IEC 61557-4
*   M Ω: IEC 61557-2
*   RCD: IEC 61557-6
*   LOOP P-P, P-N, P-PE: IEC 61557-3
*   PHASE SEQUENCE: IEC 61557-7
*   EARTH: IEC 61557-5
*   LOW Ω 10A: EN60439-1, EN60204-1

#### 15.2.4. Riferimenti normativi per le misure di potenza

*   Caratteristiche della tensione fornita dalle reti pubbliche: EN50160
*   Contatori elettrici statici di energia attiva per corrente alternata: EN61036 (Classe 2)
*   Contatori elettrici statici di energia reattiva per corrente alternata: IEC1268 (Classe 3)

### 15.3. CARATTERISTICHE GENERALI

**Caratteristiche meccaniche**

*   Dimensioni: 225(Lu) x 165(La) x 105 (H) mm
*   Peso GSC57 (batterie incluse): circa 1,7kg
*   Peso GSC59 (batterie incluse): circa 1,2kg

**Alimentazione**

*   Batterie: 6 batterie 1.5-LR6-AA-AM3-MN 1500
*   Autonomia batterie:
    *   LOW Ω: > 800 test
    *   M Ω: > 500 test
    *   RCD: > 1000 test
    *   LOOP P-P, P-N, P-PE: > 1000 test
    *   Ra: > 1000 test
    *   EARTH: > 1000 test
    *   LOW Ω 10A: > 1000 test
    *   PHASE SEQUENCE: > 1000 test
    *   AUX (Mis. in Tempo Reale): > 20 ore
    *   AUX (Registrazione): > 20 ore
    *   ANALYZER (Mis. in Tempo Reale): > 20 ore
    *   ANALYZER (Registrazione): > 20 ore
*   Alimentatore Esterno: Cod. A0050 (opzionale per GSC57; solo per funzioni AUX e ANALYZER)
*   Tensione di Rete: 230VAC 50Hz (solo per funzione LOW Ω 10A)

**Display**

*   Caratteristiche: Modulo grafico a matrice di punti retroilluminato
*   Risoluzione: 128x128
*   Area visibile: 73mmx73mm

**Memoria**

*   Memoria: 2Mbyte
*   Prove di verifica: max 999 misure
*   Registrazioni AUX e ANALYZER: Vedi paragrafo 11.2

**Interfaccia**

*   Interfaccia: Porta seriale RS232 optoisolata per trasferire su PC i risultati delle misure

### 15.4. CONDIZIONI AMBIENTALI

*   Temperatura di riferimento: 23° ± 5°C
*   Temperatura di utilizzo: 0° ÷ 40°C
*   Umidità relativa di Utilizzo: < 80%
*   Temperatura di Immagazzinamento: -10 ÷ 60°C
*   Umidità di Immagazzinamento: < 80%

### 15.5. ACCESSORI

**GSC57 – Accessori standard**

| Descrizione                                       | Codice      |
| :------------------------------------------------ | :---------- |
| Cavo con spina Shuko con 3 terminali a sicurezza  | C2033X      |
| Set di 4 cavi (2m), 4 coccodrilli, 2 puntali      | KITGSC5     |
| Set di 4 cavi banana-banana e 4 picchetti         | KITTERRNE   |
| Cavo di alimentazione per la funzione LOW Ω 10A   | C5700       |
| Software di gestione in ambiente Windows          | TOPVIEW     |
| Cavo di collegamento ottico-USB                   | C2006       |
| Borsa di trasporto                                | BORSA2051   |
| Certificato di calibrazione                       | ISO9000     |
| Manuale d'uso                                     |             |

**GSC57 – Accessori opzionali**

| Descrizione                                                     | Codice       |
| :-------------------------------------------------------------- | :----------- |
| Alimentatore esterno a rete 230V/50Hz                           | A0050        |
| Set di 4 cavi, 5m con coccodrilli per prova LOW Ω 10A           | C7000/05     |
| Set di 4 cavi, 10m con coccodrilli per prova LOW Ω 10A          | C7000/10     |
| Set di cinghia e prese per uso strumento a tracolla             | CN0050       |
| Sonda di temperatura ed umidità                                 | HT52/05      |
| Sonda per illuminamento 20-2000-20000Lux/2V                     | HT53/05      |
| Set di 3 pinze flessibili 300-3000A/1V – Diametro 174 mm        | HTFLEX3003   |
| Pinza per corrente AC 200-2000A/1V – Diametro 70 mm             | HP30C2       |
| Pinza per corrente AC 3000A/1V – Diametro 70 mm                 | HP30C3       |
| Pinza per correnti di dispersione 1-100-1000A/1V – Diametro 54 mm | HT96U        |
| Pinza per corrente AC 10-100-1000A/1V – Diametro 54 mm          | HT97U        |
| Cassetta 3x1-5A/1V per collegamento con TA esterni              | HT903        |
| Accessorio per misure di Impedenza di Loop ad alta risoluzione  | IMP57        |

**GSC59 – Accessori Standard**

| Descrizione                                       | Codice       |
| :------------------------------------------------ | :----------- |
| Cavo con spina Shuko con 3 terminali a sicurezza  | C2033X       |
| Set di 4 cavi (2m), 4 coccodrilli, 2 puntali      | KITGSC5      |
| Set di 4 cavi banana-banana e 4 picchetti         | KITTERRNE    |
| Alimentatore esterno a rete 230V/50Hz             | A0050        |
| Set di 3 pinze flessibili 1000/3000A – Diametro 174 mm | HTFLEX33     |
| Software di gestione in ambiente Windows          | TOPVIEW      |
| Cavo di collegamento ottico-USB                   | C2006        |
| Borsa di trasporto                                | BORSA2051    |
| Certificato di calibrazione                       | ISO9000      |
| Manuale d'uso                                     |              |

**GSC59 – Accessori Opzionali**

| Descrizione                                                     | Codice       |
| :-------------------------------------------------------------- | :----------- |
| Set di cinghia e prese per uso strumento a tracolla             | CN0050       |
| Sonda di temperatura ed umidità                                 | HT52/05      |
| Sonda per illuminamento 20-2000-20000Lux/2V                     | HT53/05      |
| Pinza per correnti di dispersione 1-100-1000A/1V – Diametro 54 mm | HT96U        |
| Pinza per corrente AC 10-100-1000A/1V – Diametro 54 mm          | HT97U        |
| Pinza per corrente AC 200-2000A/1V – Diametro 70 mm             | HP30C2       |
| Pinza per corrente AC 3000A/1V – Diametro 70 mm                 | HP30C3       |
| Cassetta 3x1-5A/1V per collegamento con TA esterni              | HT903        |
| Accessorio per misure di Impedenza di Loop ad alta risoluzione  | IMP57        |

## 16. ASSISTENZA

### 16.1. CONDIZIONI DI GARANZIA

Questo strumento è garantito contro ogni difetto di materiale e fabbricazione, in conformità con le condizioni generali di vendita. Durante il periodo di garanzia, le parti difettose possono essere sostituite, ma il costruttore si riserva il diritto di riparare ovvero sostituire il prodotto. Qualora lo strumento debba essere restituito al servizio post - vendita o ad un rivenditore, il trasporto sarà a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballo originale, ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente. Il costruttore declina ogni responsabilità per danni causati a persone o oggetti. La garanzia non è applicata nei seguenti casi:

*   Riparazioni che si rendano necessarie a causa di un errato utilizzo dello strumento o del suo utilizzo con apparecchiature non compatibili.
*   Riparazioni che si rendano necessarie a causa di un imballaggio non adeguato.
*   Riparazioni che si rendano necessarie a causa di interventi eseguiti da personale non autorizzato.
*   Modifiche apportate allo strumento senza esplicita autorizzazione del costruttore.
*   Utilizzo non contemplato nelle specifiche dello strumento o nel manuale d’uso.

Il contenuto del presente manuale non può essere riprodotto in alcuna forma senza l’autorizzazione del costruttore.

> **NOTA:** I nostri prodotti sono brevettati e i marchi depositati. Il costruttore si riserva il diritto di apportare modifiche alle specifiche ed ai prezzi se ciò è dovuto a miglioramenti tecnologici.

### 16.2. ASSISTENZA

Se lo strumento non funziona correttamente, prima di contattare il Servizio di Assistenza, controllare lo stato delle batterie e dei cavi e sostituirli se necessario. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post - vendita o ad un rivenditore, il trasporto sarà a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballaggio originale, ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente.

## 17. SCHEDE PRATICHE PER LE VERICHE ELETTRICHE

### 17.1. MISURA DELLA CONTINUITÀ DEI CONDUTTORI DI PROTEZIONE

**Scopo della prova**

Accertare la continuità dei:
*   conduttori di protezione (PE), conduttori equipotenziali principali (EQP), conduttori equipotenziali secondari (EQS) nei sistemi TT e TN-S.
*   conduttori di neutro con funzione di conduttori di protezione (PEN) nei sistemi TN-C.

> **NOTA:** Questa prova strumentale va ovviamente preceduta da un esame a vista che accerti l'esistenza dei conduttori di protezione ed equipotenziali di colore giallo-verde e che le sezioni utilizzate siano conformi a quanto prescritto dalle Norme.

**Parti di impianto da verificare Esempi di misure di continuità dei conduttori**

*   Collegare uno dei puntali alla massa estranea (in questo caso è il tubo dell'acqua) e l’altro all’impianto di terra utilizzando ad esempio il conduttore di protezione presente nella presa FM più vicina.
*   Collegare uno dei puntali al conduttore di protezione della presa FM e l’altro al nodo equipotenziale dell’impianto di terra.

Verificare la continuità tra:
a) Poli di terra di tutte le prese a spina e collettore o nodo di terra.
b) Morsetti di terra degli apparecchi di classe I (boiler ecc.) e collettore o nodo di terra.
c) Masse estranee principali (tubi acqua, gas, ecc.) e collettore o nodo di terra.
d) Masse estranee supplementari fra loro e verso morsetto terra.

**Valori ammissibili**

Le Norme CEI 64-8/6 non danno indicazioni sui valori massimi di resistenza che non debbono essere superati per poter dichiarare positivo il risultato della prova di continuità. La CEI 64-8/6 richiede semplicemente allo strumento di misura che si utilizza di segnalare all'operatore se la prova non è stata eseguita con una corrente di almeno 0,2 A e una tensione a vuoto compresa tra 4 V e 24 V. I valori di resistenza si possono calcolare in base alle sezioni ed alle lunghezze dei conduttori in esame, in ogni modo normalmente se si rilevano con lo strumento valori intorno a qualche ohm la prova si può ritenere superata.

### 17.2. MISURA DELLA RESISTENZA DI ISOLAMENTO DELL’IMPIANTO ELETTRICO (250VDC, 500VDC, 1000VDC)

*   **ESEMPIO DI MISURA DI ISOLAMENTO SU UN IMPIANTO**

![Misure di isolamento su un impianto.](image_isolamento_impianto.png)
*Misure di isolamento su un impianto.*

*   Interruttore A
*   Interruttore B
*   Interruttore C
*   Interruttore E posizionato vicino alla lavatrice con la funzione di sezionare questa dall’impianto.
*   Presa FM
*   Contatore Enel
*   Interruttore D posizionato vicino al boiler con la funzione di sezionare questo dall’impianto.

<!-- Chunk: Pages 129-156 -->
## Scopo della prova

Verificare che la resistenza di isolamento dell'impianto sia conforme a quanto previsto dalle Norme CEI 64-8/6.

**NOTA:** Questa prova strumentale va effettuata con il circuito in esame non alimentato e con gli eventuali carichi che esso alimenta disinseriti.

### PARTI DI IMPIANTO DA VERIFICARE

a) tra ogni conduttore attivo e la terra (il conduttore di neutro è considerato un conduttore attivo tranne nel caso di sistemi di alimentazione di tipo TN-C dove è considerato parte della terra (PEN)). Durante questa misura tutti i conduttori attivi possono essere connessi fra loro, qualora il risultato della misura non rientrasse nei limiti normativi occorre ripetere la prova separatamente per ogni singolo conduttore.
b) tra conduttori attivi La norma CEI 64-8/6 raccomanda di verificare anche l'isolamento tra i conduttori attivi quando ciò è possibile (ATTENZIONE).

Una procedura indicativa di come eseguire la misura della resistenza di isolamento su un impianto è riportata nella tabella seguente:

Procedura di misura della resistenza di isolamento riferita alla figura precedente:

| Situazione interruttori               | Punto in cui si esegue la misura | Risultato della misura                 | Giudizio sull'impianto  |
| :------------------------------------ | :------------------------------- | :------------------------------------- | :---------------------- |
| 1 Aprire l'interruttore A, l’interruttore D e l’interruttore E | Eseguire la misura sull'interruttore A   | Se `R &#x2265; R LIMITE` | `&#x263A;` OK (fine verifica) |
|                                       |                                  | Se `R < R LIMITE`                      | Proseguire `&#x21F8;` |
| 2 Aprire l'interruttore B             | Eseguire la misura sull'interruttore A   | Se `R &#x2265; R LIMITE` | Proseguire `&#x21F8;` |
|                                       |                                  | Se `R < R LIMITE`                      | `&#x2639;` IMPIANTO NON A NORMA |
| 3                                     | Eseguire la misura sull'interruttore B   | Se `R &#x2265; R LIMITE` | `&#x263A;` OK (fine verifica) |
|                                       |                                  | Se `R < R LIMITE`                      | Proseguire `&#x21F8;` |
| 4 Aprire l'interruttore C             | Eseguire la misura sull'interruttore B   | Se `R &#x2265; R LIMITE` | Proseguire `&#x21F8;` |
|                                       |                                  | Se `R < R LIMITE`                      | `&#x2639;` IMPIANTO NON A NORMA |
| 5                                     | Eseguire la misura sull'interruttore C   | Se `R &#x2265; R LIMITE` | `&#x263A;` OK (fine verifica) |
|                                       |                                  | Se `R < R LIMITE`                      | `&#x2639;` IMPIANTO NON A NORMA |

Tabella 7: Tabella con i passi della procedura per la misura di isolamento riferiti all’impianto riportato nella figura precedente.

**N.B.** Gli interruttori D ed E sono gli interruttori installati vicino al carico che hanno la funzione di sezionare quest’ultimo dall’impianto. Qualora non esistano tali interruttori occorre scollegare gli utilizzatori dall’impianto prima di effettuare la prova di resistenza di isolamento.

**ATTENZIONE**
Se l'impianto comprende dispositivi elettronici occorre scollegarli dall'impianto. Qualora ciò non fosse possibile si deve eseguire solo la prova "a" cioè tra conduttori attivi (in questo caso DEVONO essere collegati insieme) e la terra.

## Valori ammissibili

I valori della tensione di misura e della resistenza minima di isolamento possono essere ricavati dalla tabella seguente (CEI64-8/6 Tab. 6A):

| Tensione nominale del circuito (V) | Tensione di prova (V) | Resistenza di isolamento (M`&#x2126;`) |
| :--------------------------------- | :-------------------- | :------------------------------------ |
| SELV e PELV\*                      | 250                   | `&#x2265; 0.50`                      |
| Fino a 500 V compreso              | 500                   | `&#x2265; 1.00`                      |
| Oltre i 500 V                      | 1000                  | `&#x2265; 1.00`                      |

\* I termini SELV e PELV sostituiscono nella nuova stesura della normativa le vecchie definizioni "Bassissima tensione di sicurezza" o "funzionale".

Tabella 8: Tabella riassuntiva dei valori delle tensioni di prova e relativi valori limite ammessi per le tipologie di prova più comuni.

**NOTE:**

*   `&#x21F8;` Se si è in presenza di un circuito molto esteso, i conduttori che corrono affiancati costituiscono una capacità che lo strumento deve caricare per poter effettuare una misura corretta in questo caso è consigliabile mantenere il tasto `GO` premuto (nel caso in cui si esegua una prova in modalità manuale) finché il risultato non si stabilizzi.
*   `&#x21F8;` L'indicazione `>999M &#x2126;` o `o.r.` (fuori campo) segnala che la resistenza di isolamento misurata dallo strumento è superiore al limite massimo di resistenza misurabile (vedi specifiche tecniche), ovviamente tale risultato è ampiamente superiore ai limiti minimi della tabella normativa di cui sopra pertanto, se durante una prova dovesse comparire questo simbolo, l'isolamento in quel punto sarebbe da ritenersi a norma.

**ATTENZIONE**
Quando si eseguono delle misure fra i conduttori attivi è indispensabile scollegare tutti gli utilizzatori (lampade spia, trasformatori citofonici, boiler etc) altrimenti lo strumento misurerà la loro resistenza invece dell'isolamento dell'impianto. Inoltre una eventuale prova di resistenza di isolamento tra i conduttori attivi potrebbe portare a un loro danneggiamento.

## 17.3. VERIFICA DELLA SEPARAZIONE DEI CIRCUITI

### Scopo della prova

La prova, da effettuare nel caso in cui la protezione sia attuata mediante separazione (64-8/6 61.3.4, SELV o PELV o Separazione Elettrica), deve verificare che la resistenza di isolamento misurata come descritto di seguito (a seconda del tipo di separazione) sia conforme ai limiti riportati nella tabella relativa alle misure di isolamento.

### PARTI DI IMPIANTO DA VERIFICARE

*   **Sistema SELV** (Safety Extra Low Voltage):
    *   misurare la resistenza tra le parti attive del circuito in prova (separato) e le parti attive degli altri circuiti.
    *   misurare la resistenza tra le parti attive del circuito in prova (separato) e la terra. La resistenza deve risultare non inferiore a `0,25M &#x2126;` con una tensione di prova di 250VDC.
*   **Sistema PELV** (Protective Extra Low Voltage):
    *   misurare la resistenza tra le parti attive del circuito in prova (separato) e le parti attive degli altri circuiti. La resistenza deve risultare non inferiore a `0,25M &#x2126;` con una tensione di prova di 250VDC.
*   **Separazione Elettrica**:
    *   misurare la resistenza tra le parti attive del circuito in prova (separato) e le parti attive degli altri circuiti.
    *   misurare la resistenza tra le parti attive del circuito in prova (separato) e la terra. La resistenza deve risultare non inferiore a `0,5M &#x2126;` con una tensione di prova di 500VDC e `1M &#x2126;` con tensione di prova di 1000VDC.

### ESEMPIO DI VERIFICA DI SEPARAZIONE TRA CIRCUITI ELETTRICI

> ...e quelle di altri circuiti ...l’ impianto di terra Tra le parti attive del circuito separato...
> Misure di separazione tra circuiti in un impianto

Trasformatore di isolamento o di sicurezza che effettua la separazione tra i circuiti.

| Prova tra le parti attive.                                                                         | Prova tra le parti attive e la terra.                                                                                                                                                                             |
| :------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| collegare un puntale dello strumento su uno dei due conduttori del circuito separato e l’altro su uno dei conduttori di un circuito non separato. | Collegare un puntale dello strumento su uno dei due conduttori del circuito separato e l’altro sul nodo equipotenziale. Questa prova va eseguita solo per circuiti SELV o con separazione elettrica. |

## Valori ammissibili

La prova ha esito positivo quando la resistenza di isolamento presenta valori superiori o uguali a quelli indicati nella tabella riportata nella sezione relativa alle prove di isolamento.

### Osservazioni:

*   **Sistema SELV**: è un sistema di categoria zero o sistema a bassissima tensione di sicurezza caratterizzato da:
    *   Alimentazione: sorgente autonoma (es. batterie di pile, piccolo gruppo elettrogeno) o di sicurezza (es. trasformatore di sicurezza).
    *   Separazione di protezione verso altri sistemi elettrici (isolamento doppio o rinforzato oppure uno schermo metallico collegato a terra).
    *   Non presenta punti messi a terra (isolato da terra).
*   **Sistema PELV**: è un sistema di categoria zero o sistema a bassissima tensione di protezione caratterizzato da:
    *   Alimentazione: sorgente autonoma (es. batterie di pile, piccolo gruppo elettrogeno) o di sicurezza (es. trasformatore di sicurezza).
    *   Separazione di protezione verso altri sistemi elettrici (isolamento doppio o rinforzato oppure uno schermo metallico collegato a terra).
    *   Presenta punti messi a terra (non isolato da terra).
*   **Separazione Elettrica**: è un sistema caratterizzato da:
    *   Alimentazione: trasformatore di isolamento o sorgente autonoma con caratteristiche equivalenti (es. gruppo motore generatore).
    *   Presenta una separazione di protezione verso altri sistemi elettrici (isolamento non inferiore a quello del trasformatore di isolamento).
    *   Presenta una separazione di protezione verso terra (isolamento non inferiore a quello del trasformatore di isolamento).

## 17.4. MISURA DELLA RESISTENZA DI TERRA NEGLI IMPIANTI TT

### SCOPO DELLA PROVA

Verificare che il dispositivo di protezione sia coordinato con il valore della resistenza di terra. Non si può assumere a priori un valore di resistenza di terra limite di riferimento (ad esempio `20 &#x2126;` come dall’art. 326 del DPR 547/55) al quale fare riferimento nel controllo del risultato della misura, ma è necessario di volta in volta controllare che sia rispettato il coordinamento previsto dalla normativa.

### PARTI DI IMPIANTO DA VERIFICARE

L'impianto di terra nelle condizioni di esercizio. La verifica deve essere eseguita senza scollegare i dispersori.

### Valori ammissibili

Il valore della resistenza di terra comunque misurato deve soddisfare la seguente relazione:

`R A < 50 / I a`

dove:
`R A` = Resistenza misurata dell'impianto di terra, il valore può essere determinato con le seguenti misure:
- Resistenza di terra con metodo voltamperometrico a tre fili.
- Impedenza dell'anello di guasto (vedi (*))
- Resistenza di terra a due fili (vedi (**))
- Resistenza di terra a due fili nella presa (vedi (**))
- Resistenza di terra data dalla misura della tensione di contatto `U t`
- Resistenza di terra data dalla misura della prova del tempo di intervento degli interruttori differenziali RCD (A, AC), RCD S (A, AC).

`I a` = Corrente di intervento in 5s dell'interruttore automatico, corrente nominale di intervento del differenziale (nel caso di `RCD S 2 I &#x2206; n`).

`50` = Tensione limite di sicurezza (ridotta a 25V in ambienti particolari).

(\*) Se a protezione dell'impianto si trova un interruttore differenziale la misura deve essere effettuata a monte del differenziale stesso o a valle cortocircuitando lo stesso per evitare che questo intervenga.
(\*\*) Questi metodi, pur se non attualmente previsti dalle norme CEI 64.8, forniscono valori che innumerevoli prove di confronto con il metodo a tre fili hanno dimostrato essere indicativi della resistenza di terra.

### ESEMPIO DI VERIFICA DI RESISTENZA DI TERRA

Ci troviamo di fronte ad un impianto protetto da un differenziale da 30 mA. Misuriamo la resistenza di terra utilizzando uno dei metodi sopra citati. Per capire se la resistenza dell'impianto sia da considerarsi a norma moltiplicare il valore trovato per 0.03A (30 mA). Se il risultato è inferiore a 50V (o 25V per ambienti particolari) l'impianto è da ritenersi coordinato perché rispetta la relazione indicata sopra. Quando siamo in presenza di differenziali da 30 mA (la quasi totalità degli impianti civili) la resistenza di terra massima ammessa è `50/0.03=1666 &#x2126;` questo consente di utilizzare anche i metodi semplificati indicati che, pur non fornendo un valore estremamente preciso forniscono, un valore sufficientemente approssimato per il calcolo del coordinamento.

### METODO VOLTAMPEROMETRICO

#### Tecnica per dispersori di piccole dimensioni

Si fa circolare una corrente tra il dispersore di terra in esame e una sonda di corrente posizionata ad una distanza dal contorno dell’impianto di terra pari a 5 volte la diagonale dell’area che delimita l’impianto di terra (vedi Fig. 1). Posizionare la sonda di tensione circa a metà tra il dispersore di terra e la sonda di corrente, infine misurare la tensione tra i due.

> Nero Verde Blu Rosso
> Fig. 1: misura resistenza di terra con metodo voltamperometrico per dispersori con piccole dimensioni

Utilizzare più picchetti in parallelo e bagnare il terreno circostante qualora lo strumento non riesca ad erogare la corrente necessaria per eseguire la prova a causa di una elevata resistenza del terreno.

#### Tecnica per dispersori di grandi dimensioni

Questa tecnica si basa sempre sul metodo voltamperometrico ma si utilizza qualora risulti difficoltoso posizionare il dispersore ausiliario di corrente ad una distanza pari a 5 volte la diagonale dell’area dell’impianto di terra. Posizionare la sonda di corrente ad una distanza pari a una volta la diagonale dell’impianto di terra (vedi Fig. 2). Per accertare che la sonda di tensione sia situata fuori dalle zone di influenza del dispersore in prova eseguire più misure partendo con la sonda di tensione posizionata nel punto intermedio tra dispersore e sonda di corrente e successivamente spostando la sonda sia verso il dispersore di terra che verso la sonda di corrente.

> Nero Verde Rosso Blu
> Fig. 2: misura resistenza di terra con metodo voltamperometrico per dispersori con grandi dimensioni

Utilizzare più picchetti in parallelo e bagnare il terreno circostante qualora lo strumento non riesca ad erogare la corrente necessaria per eseguire la prova a causa di una elevata resistenza del terreno.

## 17.5. MISURA DELLA RESISTIVITÀ DEL TERRENO

### Scopo della prova

Analizzare il valore della resistività del terreno per definire, in fase di progettazione, la tipologia dei dispersori di terra da utilizzare nell'impianto.

### Valori ammissibili

Per la misura di resistività non esistono valori ammissibili, i vari valori ottenuti utilizzando distanze fra i picchetti “a” crescenti devono essere riportati in un grafico dal quale poi, in funzione della curva ottenuta, si stabilisce il tipo di dispersori da utilizzare. Poiché il risultato di misura può essere falsato da parti metalliche interrate quali tubazioni, cavi, altri dispersori a nastro, in caso di dubbio eseguire una seconda misura con uguale distanza "a", ma con l'asse dei picchetti ruotato di 90°.

> Nero Nero Blu Blu Verde Verde Rosso Rosso
> a a a a a a
> 90°

Il valore di resistività è dato dalla seguente relazione:

`&#x03C1; =2 &#x03C0; a R`

dove:
`&#x03C1;` = Resistività specifica del terreno
`a` = Distanza delle sonde (m)
`R` = Resistenza misurata dallo strumento (`&#x2126;`)

> 2° Misura: I picchetti sono ruotati di 90° rispetto alla misura precedente.
> 1° Misura: I picchetti sono posizionati ad una distanza reciproca pari ad “a”.

Il metodo di misura consente di rilevare la resistività specifica fino alla profondità corrispondente circa alla distanza “a“ fra due picchetti. Se si aumenta “a“ possono essere rilevati strati di terreno più profondi, pertanto è possibile controllare l'omogeneità del terreno. Attraverso varie misure di `&#x03C1;`, con “a“ crescenti, si può tracciare un profilo come quelli seguenti dal quale è possibile stabilire l'impiego del dispersore più idoneo.

*   **Curva 1**: poiché `&#x03C1;` diminuisce solo in profondità è possibile utilizzare solo un dispersore in profondità.
*   **Curva 2**: poiché `&#x03C1;` diminuisce solo fino alla profondità A, l'aumento della profondità dei dispersori oltre A non porta alcun vantaggio.
*   **Curva 3**: con l’aumento della profondità non si ottiene alcuna diminuzione di `&#x03C1;`. Pertanto il tipo di dispersore da utilizzare è il dispersore ad anello.

### VALUTAZIONE APPROSSIMATIVA DEL CONTRIBUTO DI DISPERSORI INTENZIONALI (64-12 2.4.1)

In prima approssimazione la resistenza di un dispersore Rd può essere calcolata con le seguenti formule (`&#x03C1;` resistività media del terreno).

a) Resistenza di un dispersore verticale
`Rd = &#x03C1; / L`
`L` = lunghezza dell'elemento a contatto con il terreno

b) Resistenza di un dispersore orizzontale
`Rd = 2 &#x03C1; / L`
`L` = lunghezza dell'elemento a contatto con il terreno

c) Resistenza di un sistema di elementi magliati
Com'è noto la resistenza di un sistema complesso con più elementi in parallelo è sempre più elevata di quella che risulterebbe da un semplice calcolo di elementi in parallelo. Ciò è tanto più vero quanto più vicini, e quindi interagenti, risultino gli elementi. Per questo motivo l'utilizzazione della formula sottoesposta nell'ipotesi di un sistema magliato è più rapida ed efficace del calcolo dei singoli elementi orizzontali e verticali:
`Rd = &#x03C1; / 4r`
`r` = raggio del cerchio che circoscrive la maglia

## 17.6. PROVA DI FUNZIONAMENTO DEI DISPOSITIVI DI PROTEZIONE A CORRENTE DIFFERENZIALE

### Scopo della prova

Verificare se i dispositivi di protezione differenziale generali e selettivi siano stati installati e regolati correttamente e se conservino nel tempo le proprie caratteristiche. La verifica deve accertare che l’interruttore differenziale intervenga ad una corrente `I &#x2206;` non superiore alla sua corrente nominale di funzionamento `I &#x2206; n` e che il tempo di intervento soddisfi, a seconda del caso, le seguenti condizioni:

*   non superi il tempo massimo dettato dalla normativa nel caso di interruttori differenziali di tipo generale (secondo quanto descritto nella Tabella 5).
*   sia compreso tra il tempo di intervento minimo e quello massimo nel caso di interruttori differenziali di tipo selettivo (secondo quanto descritto nella Tabella 5).

La prova dell’interruttore differenziale effettuata con il tasto di prova serve per far si che “l’effetto colla” non comprometta il funzionamento del dispositivo rimasto inattivo per lungo tempo. Tale prova viene eseguita solo per accertare la funzionalità meccanica del dispositivo e non è sufficiente per poter dichiarare la conformità alla normativa del dispositivo a corrente differenziale. Da un’indagine statistica risulta che la verifica con tasto di prova degli interruttori effettuata una volta al mese riduce della metà il tasso di guasto di questi, però tale prova individua solo il 24% degli interruttori differenziali difettosi.

### PARTI DI IMPIANTO DA VERIFICARE

Tutti i differenziali devono essere testati quando vengono installati. Negli impianti a bassa tensione si consiglia di eseguire questa prova che risulta fondamentale al fine di garantire un giusto livello di sicurezza. Relativamente ai locali ad uso medico tale verifica deve essere eseguita periodicamente ogni sei mesi su tutti i differenziali come riportato dalle Norme CEI 64-4 5.2.01 e CEI 64-13.

**N.B.** Nel caso non sia disponibile l’impianto di terra, effettuare la prova collegando lo strumento con un terminale su un conduttore a valle del dispositivo differenziale ed un terminale sull'altro conduttore a monte del dispositivo stesso.

### Valori ammissibili

Per il confronto delle misure fare riferimento alla Tabella 3 che riporta i limiti per i tempi di intervento. Su ogni differenziale devono essere eseguite due prove: una con corrente di dispersione che inizi in fase con la semionda positiva della tensione (0°) e una con corrente di dispersione che inizi in fase con la semionda negativa della tensione (180°). Il risultato indicativo è il tempo più alto. La prova a `&#xBD;I &#x2206; n` NON DEVE IN NESSUN CASO causare l'intervento del differenziale.

### NOTE:

*   Prima di effettuare la prova alla corrente nominale dell’interruttore lo strumento effettua una prova a `&#xBD;I &#x2206; n` per misurare la tensione di contatto e la resistenza globale di terra. Se durante tale prova l’interruttore differenziale dovesse intervenire viene visualizzata l'indicazione `"rcd"`. Due possono essere i motivi per i quali il differenziale interviene durante tale misura:
    a) La corrente a cui interviene il differenziale è inferiore a `&#xBD;I &#x2206; n`.
    b) Sull'impianto è già presente una dispersione verso terra che, sommandosi a quella generata dallo strumento, causa l'intervento del differenziale.
*   Se durante la misura della tensione di contatto lo strumento rileva una tensione superiore al valore di sicurezza (50V o 25V) la prova viene interrotta. Proseguire la prova in tali condizioni significherebbe lasciare la tensione di contatto applicata a tutte le masse metalliche collegate alla terra per un tempo tale da essere pericolosa.
*   Fra i risultati della prova del tempo di intervento dei differenziali viene visualizzata anche il valore della resistenza di terra `R a` in `&#x2126;`, tale valore per gli impianti TN ed IT non è da tenere in considerazione mentre per gli impianti TT è puramente indicativo.

## 17.7. MISURA DELLA CORRENTE DI INTERVENTO DELLE PROTEZIONI DIFFERENZIALI

### Scopo della prova

Verificare la reale corrente di intervento dei differenziali generali (non si applica ai differenziali selettivi).

### PARTI DI IMPIANTO DA VERIFICARE

In presenza di interruttori differenziali con corrente di intervento che può essere selezionata è utile effettuare questa prova per verificare la reale corrente di intervento del differenziale. Per i differenziali con corrente differenziale fissa questa prova può essere eseguita per rilevare eventuali dispersioni di utilizzatori collegati all’impianto. Nel caso non sia disponibile l’impianto di terra effettuare la prova collegando lo strumento con un terminale su un conduttore a valle del dispositivo differenziale ed un terminale sull'altro conduttore a monte del dispositivo stesso.

### Valori ammissibili

La corrente di intervento deve essere compresa fra `&#xBD;I &#x2206; n` ed `I &#x2206; n`.

### NOTE:

*   Fare riferimento alle note del capitolo precedente.
*   Per verificare se sull'impianto sono presenti delle correnti di dispersione significative operare come segue:
    a) Dopo aver disattivato tutti i carichi effettuare la misura della corrente di intervento ed annotarsi il valore.
    b) Riattivare i carichi ed effettuare una nuova misura della corrente di intervento. Se il differenziale interviene con una corrente inferiore la dispersione dell'impianto è la differenza fra le due correnti di intervento. Se durante la prova lo strumento indica `"rcd"` la corrente di dispersione dell'impianto sommata alla corrente per la misura della tensione di contatto (`&#xBD;I &#x2206; n`) causa l'intervento del dispositivo.

**N.B.** Questa prova non viene di solito eseguita per confrontare il tempo di intervento dell’interruttore con i limiti normativi. Lo strumento in questa modalità rileva l’esatta corrente e il tempo di intervento del differenziale alla corrente di intervento, invece la normativa fa riferimento a tempi massimi di intervento nel caso in cui il differenziale sia provato con una corrente di dispersione pari alla corrente nominale.

## 17.8. MISURA DELL’IMPEDENZA DELL’ANELLO DI CORTOCIRCUITO

### Scopo della prova

Verificare che il potere di interruzione del dispositivo di protezione sia superiore alla massima corrente di guasto possibile sull'impianto.

### PARTI DI IMPIANTO DA VERIFICARE

La prova deve essere effettuata nel punto in cui si può avere la massima corrente di corto circuito, normalmente immediatamente a valle della protezione da controllare. La prova deve essere effettuata fra fase e fase (`Z pp`) negli impianti trifase e fra fase e neutro (`Z pn`) negli impianti monofase.

### VALORI AMMISSIBILI

Impianti trifase: `Pi Zpp > 400 &#x221A;3 *`
Impianti monofase: `Pi Zpn > 230`

dove:
`P i` = Potere di interruzione della protezione
`Z pp` = Impedenza misurata fra fase e fase
`Z pn` = Impedenza misurata fra fase e neutro

## 17.9. MISURA DELL’IMPEDENZA DELL’ANELLO DI GUASTO

### Scopo della prova

Per anello di guasto si intende il circuito che viene percorso dalla corrente provocata da un guasto d’isolamento verso terra (guasto franco). L’anello di guasto comprende:

*   L’avvolgimento di fase del trasformatore.
*   Il conduttore di linea, fino al punto di guasto.
*   Il conduttore di protezione dal punto di guasto al centro stella del trasformatore.

Misurata l’impedenza è possibile determinare la corrente di guasto franco a terra e valutare se i dispositivi di protezione contro le sovracorrenti siano correttamente coordinati per la protezione contro i contatti indiretti.

**ATTENZIONE**
La risoluzione dello strumento nella misura dell’impedenza dell’anello di guasto è pari a `10m &#x2126;` quando il valore misurato è compreso tra `0,01 &#x2126;` e `19,99 &#x2126;`, pertanto la Teoria della Misura suggerisce di utilizzare lo strumento per eseguire misure di impedenze di valore almeno dieci volte superiore al valore della risoluzione in modo da minimizzare l’errore commesso. Per misure su impianti con correnti di cortocircuito superiori a 230 kA utilizzare lo strumento in abbinamento con l’accessorio (opzionale) `IMP57`.

### PARTI DI IMPIANTO DA VERIFICARE

La prova deve essere effettuata obbligatoriamente nei sistemi TN e IT non protetti con dispositivi differenziali.

### VALORI AMMISSIBILI

`Z S &#x2264; U o / I a`

dove:
`U o` = Tensione fase – terra.
`Z S` = Impedenza misurata fra fase e terra.
`I a` = corrente di intervento del dispositivo automatico di protezione del circuito di distribuzione entro 5s.

## 17.10. ANOMALIE DI TENSIONE

Lo strumento cataloga come anomalie di tensione tutti quei valori efficaci, calcolati ogni 10ms, al di fuori delle soglie impostate in fase di programmazione da `&#xB1; 3%` a `&#xB1; 30 %` rispetto ad un valore fissato come riferimento con passo dello 1%. Questi limiti restano invariati durante tutto il periodo di registrazione. Il valore della Tensione di riferimento va impostato come:

*   **Tensione Nominale Fase-Neutro**: per sistemi monofase e trifase 4 fili
*   **Tensione Nominale Fase-Fase**: per sistemi trifase 3 fili

**Esempio1:** Sistema Trifase 3 fili. `Vref = 400V, LIM+= 6%, LIM-=10% => Lim Sup= 400 x (1+6/100) = 424,0V Lim Inf = 400 x (1-10/100) = 360`
**Esempio2:** Sistema Trifase 4 fili. `Vref = 230V, LIM+= 6%, LIM-=10% => Lim Sup= 230 x (1+6/100) = 243,08V Lim Inf = 230 x (1-10/100) = 207,0V`

Per ogni fenomeno lo strumento registra i seguenti dati:

*   Il numero corrispondente alla fase in cui si è verificata l’anomalia.
*   La “direzione” dell’anomalia: “UP” e “DN” identificano rispettivamente picchi e buchi di tensione.
*   La data e l'ora di inizio del fenomeno nella forma giorno, mese, anno, ore, minuti, secondi, centesimi di secondo.
*   La durata del fenomeno, in secondi con con risoluzione pari a 10ms.
*   Il valore estremo raggiunto (o massimo) della tensione durante il fenomeno.

## 17.11. ARMONICHE DI TENSIONE E CORRENTE

### 17.11.1. Teoria

Qualsiasi onda periodica non sinusoidale può essere rappresentata tramite una somma di onde sinusoidali ciascuna con frequenza multipla intera della fondamentale secondo la relazione:

`v(t) = V 0 + &#x2211; &#x221E; k=1 V k sin(k &#x3C9; t + &#x3C6; k) (1)`

dove:
`V 0` = Valore medio di v(t)
`V 1` = Ampiezza della fondamentale di v(t)
`V k` = Ampiezza della k-esima armonica di v(t)

### LEGENDA:

1.  Fondamentale
2.  Terza armonica
3.  Onda distorta somma delle due componenti precedenti

> Effetto della somma di 2 frequenze multiple.

Nel caso della tensione di rete la fondamentale ha frequenza 50 Hz, la seconda armonica ha frequenza 100 Hz, la terza armonica ha frequenza 150 Hz e così via. La distorsione armonica è un problema costante e non deve essere confuso con fenomeni di breve durata quali picchi, diminuzioni o fluttuazioni. Si può osservare come dalla (1) discenda che ogni segnale è composto dalla sommatoria di infinite armoniche, esiste tuttavia un numero d’ordine oltre il quale il valore delle armoniche può essere considerato trascurabile. La normativa EN 50160 suggerisce di troncare la sommatoria nell’espressione (1) alla 40a armonica. Un indice fondamentale per rilevare la presenza di armoniche è il THD definito come:

`THDv = &#x221A;( &#x2211; 40 h=2 Vh^2 ) / V1^2`

Tale indice tiene conto della presenza di tutte le armoniche ed è tanto più elevato quanto più è distorta la forma d'onda.

### 17.11.2. Valori limite per le armoniche

La Normativa EN-50160 fissa i limiti per le tensioni Armoniche che l'Ente fornitore può immettere nella rete. In condizioni normali di esercizio, durante qualsiasi periodo di una settimana, il 95% dei valori efficaci di ogni tensione armonica, mediati sui 10 minuti, dovrà essere minore o uguale rispetto ai valori indicati in nella seguente Tabella. La distorsione armonica globale (THD) della tensione di alimentazione (includendo tutte le armoniche fino al 40° ordine) deve essere minore o uguale all’8%.

| Armoniche Dispari Non multiple di 3 | Armoniche Dispari Multiple di 3 | Armoniche Pari |
| :---------------------------------- | :------------------------------ | :------------- |
| Ordine h | Tensione relativa %Max | Ordine h | Tensione relativa % Max | Ordine h | Tensione relativa % Max |
| 5        | 6                      | 3        | 5                       | 2        | 2                       |
| 7        | 5                      | 9        | 1,5                     | 4        | 1                       |
| 11       | 3,5                    | 15       | 0,5                     | 6..24    | 0,5                     |
| 13       | 3                      | 21       | 0,5                     |          |                         |
| 17       | 2                      |          |                         |          |                         |
| 19       | 1,5                    |          |                         |          |                         |
| 23       | 1,5                    |          |                         |          |                         |
| 25       | 1,5                    |          |                         |          |                         |

Questi limiti, teoricamente applicabili solo per gli Enti fornitori di energia elettrica, forniscono comunque una serie di valori di riferimento entro cui contenere anche le armoniche immesse in rete dagli utilizzatori.

### 17.11.3. Cause della presenza di armoniche

Qualsiasi apparecchiatura che alteri l'onda sinusoidale o usi soltanto una parte di detta onda causa distorsioni alla sinusoide e quindi armoniche. Tutti i segnali di corrente risultano in qualche modo virtualmente distorti. La più comune è la distorsione armonica causata da carichi non lineari quali elettrodomestici, personal computer o regolatori di velocità per motori. La distorsione armonica genera correnti significative a frequenze che sono multipli interi della frequenza di rete. Le correnti armoniche hanno un notevole effetto sui conduttori di neutro degli impianti elettrici. Nella maggior parte dei paesi la tensione di rete in uso è trifase 50/60Hz erogata da un trasformatore con primario collegato a triangolo e secondario collegato a stella. Il secondario generalmente produce 230V AC tra fase e neutro e 400V AC fase e fase. Equilibrare i carichi per ciascuna fase ha sempre rappresentato un rompicapo per i progettisti di impianti elettrici. Fino a qualche decina di anni or sono, in un sistema ben equilibrato, la somma vettoriale delle correnti nel neutro era zero o comunque piuttosto bassa (data la difficoltà di raggiungere l’equilibrio perfetto). Le apparecchiature collegate erano lampade a incandescenza, piccoli motori ed altri dispositivi che presentavano carichi lineari. Il risultato era una corrente essenzialmente sinusoidale in ciascuna fase ed una corrente con valore di neutro basso ad una frequenza di 50/60Hz. Dispositivi “moderni” quali televisori, lampade fluorescenti, apparecchi video e forni a microonde normalmente assorbono corrente solo per una frazione di ciascun ciclo causando carichi non lineari e di conseguenza correnti non lineari. Ciò genera strane armoniche della frequenza di linea di 50/60Hz. Per questo motivo, allo stato odierno, la corrente nei trasformatori delle cabine di distribuzione contiene non solo una componente 50Hz (o 60Hz) ma anche una componente 150Hz (o 180Hz), una componente 250Hz (o 300Hz) e altre componenti significative di armonica fino a 750Hz (o 900Hz) ed oltre. Il valore della somma vettoriale delle correnti in un sistema correttamente bilanciato che alimenta carichi non lineari può essere ancora piuttosto basso. Tuttavia la somma non elimina tutte le correnti armoniche. I multipli dispari della terza armonica (chiamati i “TRIPLENS”) si sommano algebricamente nel neutro e quindi possono causare surriscaldamenti del medesimo anche con carichi bilanciati.

### 17.11.4. Conseguenza della presenza di armoniche

In generale le armoniche d'ordine pari, `2a`, `4a` ecc. non sono causa di problemi. Le armoniche triple, multipli dispari di tre, si sommano sul neutro (invece di annullarsi) creando così una situazione di surriscaldamento del conduttore stesso potenzialmente pericolosa. I progettisti devono considerare i tre punti di seguito elencati nella progettazione di un sistema di distribuzione di energia contenente correnti di armoniche:

*   Il conduttore del neutro deve essere sufficientemente dimensionato.
*   Il trasformatore di distribuzione deve avere un sistema di raffreddamento ausiliario per continuare il funzionamento alla sua capacità nominale se non è adatto alle armoniche. Ciò è necessario perché la corrente armonica nel neutro del circuito secondario circola nel primario collegato a triangolo. Questa corrente di armonica in circolazione porta ad un surriscaldamento del trasformatore.
*   Le correnti armoniche della fase vengono riflesse sul circuito primario e ritornano alla fonte. Ciò può causare distorsione dell’onda di tensione in modo tale che qualsiasi condensatore di rifasamento sulla linea può essere facilmente sovraccaricato.

La `5a` e l'`11a` armonica si oppongono al flusso della corrente attraverso i motori rendendone più difficile il funzionamento e abbrevviandone la vita media. In generale più è elevato il numero d'ordine della armonica e minore è la sua energia e quindi minore l'impatto che avrà sulle apparecchiature (fatta eccezione per i trasformatori).

## 17.12. DEFINIZIONI DI POTENZA E FATTORE DI POTENZA

In un generico sistema elettrico, alimentato da una terna di tensioni sinusoidali, si definiscono:

Potenza Attiva di fase: (n=1,2,3) `P n = V nN &#x22C5; I n &#x22C5; cos(&#x3C6; n)`
Potenza Apparente di fase: (n=1,2,3) `S n = V nN &#x22C5; I n`
Potenza Reattiva di fase: (n=1,2,3) `Q n = &#x221A;(S n^2 - P n^2)`
Fattore di Potenza di fase: (n=1,2,3) `PF n = P n / S n`
Potenza Attiva Totale: `P TOT = P 1 + P 2 + P 3`
Potenza Reattiva totale: `Q TOT = Q 1 + Q 2 + Q 3`
Potenza Apparente Totale: `S TOT = &#x221A;(P TOT^2 + Q TOT^2)`
Fattore di Potenza Totale: `PF TOT = P TOT / S TOT`

dove:
`V nN` = Valore efficace della tensione fra la fase n ed il neutro.
`I n` = Valore efficace della corrente della fase n.
`&#x3C6; n` = Angolo di sfasamento tra la tensione e la corrente della fase n.

In presenza di tensioni e correnti distorte le precedenti relazioni si modificano come segue:

Potenza Attiva di fase: (n=1,2,3) `P n = &#x2211; &#x221E; k=0 V kn &#x22C5; I kn &#x22C5; cos(&#x3C6; kn)`
Potenza Apparente di fase: (n=1,2,3) `S n = V nN &#x22C5; I n`
Potenza Reattiva di fase: (n=1,2,3) `Q n = &#x221A;(S n^2 - P n^2)`
Fattore di Potenza di fase: (n=1,2,3) `PF n = P n / S n`
Fattore di Potenza distorto (n=1,2,3) `dPF n = cos &#x3C6; 1n` = sfasamento fra le fondamentali di tensione e corrente della fase n
Potenza Attiva Totale: `P TOT = P 1 + P 2 + P 3`
Potenza Reattiva Totale: `Q TOT = Q 1 + Q 2 + Q 3`
Potenza Apparente Totale: `S TOT = &#x221A;(P TOT^2 + Q TOT^2)`
Fattore di Potenza Totale: `PF TOT = P TOT / S TOT`

dove:
`V kn` = Valore efficace della k-esima armonica di tensione fra la fase n ed il neutro.
`I kn` = Valore efficace della k-esima armonica di corrente della fase n.
`&#x3C6; kn` = Angolo di sfasamento tra la k-esima armonica di tensione e la k-esima armonica di corrente della fase n.

**Nota:**
Va osservato che, a rigore, l’espressione della potenza reattiva di fase in regime non sinusoidale non sarebbe corretta. Per intuire il perché può essere utile pensare che sia la presenza di armoniche che la presenza di potenza reattiva producono, tra i vari effetti, un incremento delle perdite di potenza in linea dovuto all’aumentare del valore efficace della corrente. Con la relazione sopra il termine di incremento di perdite di potenza dovuto alle armoniche viene sommato algebricamente a quello introdotto dalla presenza di potenza reattiva. In realtà, anche se i due fenomeni concorrono a causare un aumento di perdite in linea, non è affatto vero in generale che queste cause di perdita di potenza siano in fase fra loro e quindi sommabili algebricamente. La relazione sopra è giustificata dalla relativa semplicità di calcolo della stessa e dalla relativa discrepanza fra il valore ottenuto utilizzando questa relazione ed il valore reale. Va osservato inoltre come nel caso di sistema elettrico con armoniche, venga individuato l’ulteriore parametro denominato fattore di potenza distorto (dPF). In pratica questo parametro rappresenta il valore limite teorico raggiungibile dal fattore di potenza qualora si riuscissero ad eliminare completamente tutte le armoniche dal sistema elettrico.

### 17.12.1. Convenzioni sulle potenze e fattori di potenza

Per quanto riguarda il riconoscimento del tipo di potenza reattiva, del tipo di fattore di potenza e del verso della potenza attiva si applicano le convenzioni riportate nel seguente schema dove gli angoli indicati sono quelli di sfasamento della corrente rispetto alla tensione (es nel primo quadrante la corrente è in anticipo da 0° a 90° rispetto alla tensione):

```
Utente = Generatore Induttivo   <--   -->   Utente = Carico Capacitivo
          90°   180°
P+   = 0                       P -   =   P
Pfc+ = -1                      Pfc - =   -1
Pfi+ = -1                      Pfi - =   Pf
Qc+ = 0                        Qc- =   0
Qi+   = 0                        Qi - =   Q

P+   =   P                      P -   = 0
Pfc+ =   Pf                     Pfc - = -1
Pfi+ = -1                      Pfi - = -1
Qc+ =   Q                      Qc- =   0
Qi+ =   0                        Qi - =   0
          0°

P+   = 0                        P -   =   P
Pfc+ = -1                      Pfc - =   Pf
Pfi+ = -1                      Pfi - =   -1
Qc+ = 0                        Qc- =   Q
Qi+   = 0                        Qi - =   0

P+   =   P                      P -   = 0
Pfc+ =   -1                     Pfc - = -1
Pfi+ =   Pf                     Pfi - = -1
Qc+ =   0                      Qc- =   0
Qi+ =   Q                        Qi - =   0
          270°
Utente = Generatore Capacitivo   <--   -->   Utente = Carico Induttivo
```

Il significato dei simboli utilizzati e dei valori da essi assunti nello schema sopra rappresentato è riportato nelle seguenti tabelle:

| Simbolo | Significato                            | Note                             |
| :------ | :------------------------------------- | :------------------------------- |
| `P+`    | Valore della potenza attiva +          | Grandezze positive (utente utilizzatore) |
| `Pfc+`  | Fattore di potenza capacitivo +        |                                  |
| `Pfi+`  | Fattore di potenza induttivo +         |                                  |
| `Qc+`   | Valore della potenza reattiva capacitiva + |                                  |
| `Qi+`   | Valore della potenza reattiva induttiva +  |                                  |
| `P-`    | Valore della potenza attiva -          | Grandezze negative (utente generatore)   |
| `Pfc-`  | Fattore di potenza capacitivo -        |                                  |
| `Pfi-`  | Fattore di potenza induttivo -         |                                  |
| `Qc-`   | Valore della potenza reattiva capacitiva - |                                  |
| `Qi-`   | Valore della potenza reattiva induttiva -  |                                  |

| Valore | Significato                                                                                                                                                                                                                                                                                                                           |
| :----- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `P`    | La potenza attiva (positiva o negativa) relativa è definita nel quadrante in esame e pertanto assume il valore della potenza attiva in quell’istante.                                                                                                                                                                                 |
| `Q`    | La potenza reattiva (induttiva o capacitiva, positiva o negativa) relativa è definita nel quadrante in esame e pertanto assume il valore della potenza reattiva in quell’istante.                                                                                                                                                   |
| `Pf`   | Il fattore di potenza (induttivo o capacitivo, positivo o negativo) relativo è definito nel quadrante in esame e pertanto assume il valore del fattore di potenza in quell’istante.                                                                                                                                                  |
| `0`    | La potenza attiva (positiva o negativa) o la potenza reattiva (induttiva o capacitiva, positiva o negativa) relativa NON è definita nel quadrante in esame e pertanto assume valore nullo.                                                                                                                                            |
| `-1`   | Il fattore di potenza (induttivo o capacitivo, positivo o negativo) relativo NON è definito nel quadrante in esame.                                                                                                                                                                                                                 |

### 17.12.2. Inserzione ARON

Nei sistemi elettrici distribuiti senza neutro perdono di significato le tensioni di fase, i fattori di potenza e `cos &#x3C6;` di fase, rimangono definite solo le tensioni concatenate, le correnti di fase e le potenze totali.

> Fase 1 Fase 2 Fase 3
> W 1-2 VAR 1-2
> W 3-2 VAR 3-2
> Utenza Trifase

In questo caso si assume come potenziale di riferimento il potenziale di uno delle tre fasi (ad esempio la fase 2) e si esprimono i valori della potenza attiva, reattiva e apparente totali come somma delle indicazioni delle coppie di wattmetri, VARmetri e VAmetri.

`S TOT = &#x221A;(P TOT^2 + Q TOT^2) = &#x221A;( (W 1-2 + W 3-2)^2 + (VAR 1-2 + VAR 3-2)^2 )`

## 17.13. CENNI SUL METODO DI MISURA

Lo strumento è in grado di misurare: tensioni, correnti, potenze attive, potenze reattive capacitive ed induttive, potenze apparenti, fattori di potenza capacitivi ed induttivi grandezze analogiche ed a impulsi. Tutte queste grandezze sono analizzate in maniera totalmente digitale: di ogni fase (tensione e corrente), vengono acquisiti 128 campioni su un modulo di 20ms, ripetendo poi tale operazione per 16 periodi consecutivi.

### 17.13.1. Periodo di integrazione

L'immagazzinamento di tutti i dati, richiederebbe una capacità di memoria notevolissima. Si è pertanto cercato un metodo di memorizzazione che, pur fornendo dati significativi, permettesse la compressione delle informazioni da memorizzare. Il metodo scelto è stato quello della integrazione: trascorso un periodo di tempo denominato PERIODO DI INTEGRAZIONE, impostabile in fase di programmazione da 5 secondi a 60 minuti, lo strumento estrae dai valori campionati di ogni grandezza da memorizzare i seguenti valori:

*   Valore minimo della grandezza nel periodo d’integrazione (armoniche escluse).
*   Valore medio della grandezza (inteso come media aritmetica di tutti i valori registrati nel periodo di integrazione).
*   Valore massimo della grandezza nel periodo di integrazione (armoniche escluse).

Solamente queste tre informazioni (ripetute per ogni grandezza da memorizzare) vengono salvate in memoria insieme all'ora e alla data di inizio del periodo. Una volta memorizzati questi dati lo strumento ricomincia ad acquisire misure per un nuovo periodo.

### 17.13.2. Calcolo del fattore di potenza

Il fattore di potenza medio, secondo le specifiche, non può essere calcolato come media dei fattori di potenza istantanei, deve invece essere ricavato dai valori medi di potenza attiva e reattiva. Ogni singolo fattore di potenza medio, di fase o totale, viene quindi calcolato, alla fine di ogni periodo di integrazione, dal valore medio delle relative potenze indipendentemente dal fatto che queste debbano essere registrate oppure no. Inoltre per poter meglio analizzare il tipo di carico presente sulla linea ed avere dei termini di riscontro nell'analisi della fatturazione del "basso `cos &#x3C6;` da parte degli enti erogatori i valori di `cos &#x3C6;` induttivo e di `cos &#x3C6;` capacitivo vengono trattati come due grandezze indipendenti.

## 18. APPENDICE 1 – MESSAGGI DEL DISPLAY

| Messaggio               | Descrizione                                                                                                                                  | Suggerimenti                                                                                                                                                                                                                                                                                            |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `&#x263A;` Password:   | E' stata avviata una registrazione e sono trascorsi almeno 5 minuti dall'ultima attività dello strumento (vedi Paragrafo 0).                   | Inserire Password: F1, F4, F3, F2                                                                                                                                                                                                                                                                       |
| `PASSWORD ERRATA`       | La password inserita è sbagliata (vedi Paragrafo 0).                                                                                         | Controllare Password                                                                                                                                                                                                                                                                                    |
| `PASSWORD OK`           | La password inserita è corretta                                                                                                              |                                                                                                                                                                                                                                                                                                         |
| `Reg in corso`          | Strumento in registrazione (vedi Paragrafo 10)                                                                                               |                                                                                                                                                                                                                                                                                                         |
| `Attendere`             | Strumento in attesa dell'avvio della registrazione (vedi Paragrafo 10)                                                                       |                                                                                                                                                                                                                                                                                                         |
| `Nessuna Fase Selezionata` | Si sono selezionate delle armoniche di tensione e/o corrente ed abilitato il relativo flag (ARMONICHE ON) ma non si è selezionata nessuna tensione o corrente di fase | Selezionare almeno una tensione e/o corrente di fase.                                                                                                                                                                                                                                   |
| `troppi par. selez`     | Si sono selezionate più di 64 grandezze (armoniche incluse)                                                                                  | Deselezionare qualche grandezza                                                                                                                                                                                                                                                                         |
| `Memoria Piena`         | La memoria dello strumento è esaurita.                                                                                                       | Cancellare delle registrazioni dopo averle trasferite su PC.                                                                                                                                                                                                                                            |
| `Dati memorizzati`      | I dati sono stati archiviati                                                                                                                 |                                                                                                                                                                                                                                                                                                         |
| `Troppe Registr`        | Il numero di Dati Reg+ R&a+Smp eccede il numero massimo (35)                                                                                 | Cancellare delle Registrazione dopo averle trasferite su PC.                                                                                                                                                                                                                                            |
| `HOLD`                  | Si è attivata la funzione HOLD tramite il tasto corrispondente.                                                                              | Premere nuovamente il tasto HOLD per disattivare la funzione                                                                                                                                                                                                                                            |
| `nessun par. selez`     | Si è avviata una registrazione senza avere selezionata alcuna grandezza.                                                                     | Premere il tasto START/STOP e selezionare almeno una grandezza accedendo alla modalità MENU.                                                                                                                                                                                                        |
| `misura Energia`        | Misura dell'energia in corso                                                                                                                 | Premere F1 per arrestarla                                                                                                                                                                                                                                                                               |
| `no Alim esterna!`      | Si è avviata una registrazione senza aver connesso l'alimentatore esterno.                                                                   | Verificare se davvero si vuole avviare una registrazione senza l'ausilio dell'alimentatore esterno. in caso affermativo premere nuovamente il tasto START.                                                                                                                                          |
| `Data Errata`           | La data inserita non è corretta.                                                                                                             | Verificare la data inserita                                                                                                                                                                                                                                                                             |
| `CANC ULT? (Enter)`     | Si sta cercando di cancellare l'ultima registrazione effettuata.                                                                             | Premere ESC per non cancellare l'ultima registrazione, premere ENTER per conferma.                                                                                                                                                                                                                      |
| `CANC TOT? (Enter)`     | Si sta cercando di cancellare tutte le registrazioni effettuate.                                                                             | Premere ESC per non cancellare tutta la memoria, premere ENTER per conferma.                                                                                                                                                                                                                            |
| `ERR: SEQ`              | Il senso ciclico delle fasi non è corretto.                                                                                                  | controllare la connessione degli ingressi voltmetrici.                                                                                                                                                                                                                                                  |
| `ERR: P-`               | Lo strumento ha rilevato una potenza attiva negativa                                                                                         | Se non si è in una situazione di CO-GENERAZIONE controllare il senso delle pinze amperometriche                                                                                                                                                                                                        |
| `ERR: SEQ & P-`         | Il senso ciclico delle fasi non è corretto e lo strumento ha rilevato una potenza attiva negativa                                            | Vedere i due punti precedenti                                                                                                                                                                                                                                                                           |
| `ERR: SYNC`             | Lo strumento ha rilevato una frequenza di rete al di fuori del range ammesso                                                                 | Controllare la frequenza di rete                                                                                                                                                                                                                                                                        |
| `Errore Selezione`      | Lo strumento ha rilevato una NON coerenza fra i parametri AUX abilitati e quelli selezionati per la Registrazione                            | Controllare i parametri AUX selezionati e quelli abilitati.                                                                                                                                                                                                                                             |
| `Errata inserzione`     | Lo strumento ha rilevato una connessione errata sugli ingressi voltmetrici                                                                   | Controllare la tensione e la connessione degli ingressi voltmetrici (paragrafo 8.8)                                                                                                                                                                                                                     |
| `Vref Errata`           | L’utente ha impostato una tensione di riferimento non coerente con la connessione dello strumento                                            | Controllare il valore della tensione di riferimento impostata                                                                                                                                                                                                                                           |
| `Errore 1, 2,3,4,5`     | Contattare HT Italia                                                                                                                         | Contattare HT Italia                                                                                                                                                                                                                                                                                    |

## 19. APPENDICE 2 –SIMBOLI DELLE GRANDEZZE REGISTRABILI

| Simbolo        | Descrizione                                                                                                                                                                                 |
| :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `V1, V2, V3`   | Valore efficace della tensione di fase 1, fase 2, fase 3 rispettivamente.                                                                                                                   |
| `V12, V23 V31` | Valore delle tensioni concatenate.                                                                                                                                                          |
| `I1, I2, I3`   | Valore efficace della corrente di fase 1, fase 2, fase 3 rispettivamente.                                                                                                                   |
| `IN`           | Valore efficace della corrente del neutro.                                                                                                                                                  |
| `DC`           | Componente continua di tensione o corrente                                                                                                                                                  |
| `h01 &#x2202; h49` | Armonica 01 `&#x2202;` armonica 49 di tensione o corrente                                                                                                                                  |
| `ThdV`         | Fattore di distorsione armonica totale della tensione (vedi paragrafo 17.10).                                                                                                               |
| `ThdI`         | Fattore di distorsione armonica totale della corrente (vedi paragrafo 17.10).                                                                                                               |
| `Pt, P1, P2, P3` | Valori della potenza attiva totale, della fase1, fase 2, fase 3 rispettivamente.                                                                                                          |
| `P12, P32`     | (solo per modalità 3 fili) Valore della potenza misurata dal wattmetro 1-2 e 3-2 rispettivamente (vedi Paragrafo 17.12.2).                                                                  |
| `Qit, Qi1, Qi2, Qi3` | Valori della potenza reattiva induttiva totale fase1, fase 2, fase 3                                                                                                                       |
| `Qct, Qc1, Qc2, Qc3` | Valori della potenza reattiva capacitiva totale, fase1, fase 2, fase 3                                                                                                                      |
| `Q12, Q32`     | (solo per modalità 3 fili) Valore della potenza misurata dal VARmetro 1-2 e 3-2 rispettivamente (vedi Paragrafo 17.12.2).                                                                  |
| `St, S1, S2, S3` | Valori della potenza apparente totale, della fase1, fase 2, fase 3 rispettivamente.                                                                                                       |
| `S12, S32`     | (solo per modalità 3 fili) Valore della potenza misurata dal VAmetro 1-2 e 3-2 rispettivamente (vedi Paragrafo 17.12.2).                                                                  |
| `Pft, pf1, pf2, pf3` | Valori dei fattori di potenza totale, della fase 1, fase 2, fase 3 rispettivamente.                                                                                                     |
| `dPft, dpf1, dpf2, dpf3` | Valori del `cos &#x3C6;` totale, della fase 1, fase 2, fase 3 rispettivamente.                                                                                                             |
| `Eat, Ea1, Ea2, Ea3` | Valori della energia attiva totale, della fase1, fase 2, fase 3                                                                                                                           |
| `Erit, Eri1, Eri2, Eri3` | Valori della energia reattiva induttiva totale fase1, fase 2, fase 3                                                                                                                       |
| `Erct, Erc1, Erc2, Erc3` | Valori della energia reattiva capacitiva totale, fase1, fase 2, fase 3                                                                                                                      |
