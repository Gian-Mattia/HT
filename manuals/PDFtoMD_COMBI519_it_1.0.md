# COMBI519

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-39 -->
© Copyright HT ITALIA 2025 Versione IT 2.03 - 30/04/2025 EASYTEST - COMBI519 Manuale d’uso

EASYTEST - COMBI519 IT - 1

# INDICE

1.  PRECAUZIONI E MISURE DI SICUREZZA
    1.1. Istruzioni preliminari
    1.2. Durante l’uso
    1.3. Dopo l’uso
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
    4.2. Descrizione dei terminali di misura
    4.3. Descrizione della tastiera
    4.4. Descrizione del display
    4.5. Videata iniziale
5.  MENU GENERALE
    5.1. SET – impostazioni strumento
    5.1.1. Lingua
    5.1.2. Paese
    5.1.3. Sistema elettrico
    5.1.4. Impostazioni generali
    5.1.5. Funzione Auto Start
    5.1.6. Data e Ora
    5.1.7. Informazioni
    5.1.8. Nome operatore
6.  ISTRUZIONI OPERATIVE
    6.1. AUTO: Sequenza automatica prove (R~a~, RCD, M)
    6.1.1. Situazioni anomale
    6.2. DMM: Funzione multimetro digitale
    6.3. RPE: Continuità dei conduttori di protezione
    6.3.1. Modo TMR
    6.3.2. Modo ><
    6.3.3. Situazioni anomale
    6.4. Lo: Continuità dei conduttori di protezione con 10A
    6.4.1. Situazioni anomale
    6.5. M: Misura Resistenza di Isolamento
    6.5.1. Modo TMR
    6.5.2. Modo AUTO
    6.5.3. Situazioni anomale
    6.6. RCD: Test su interruttori differenziali
    6.6.1. Modo AUTO
    6.6.2. Modo AUTO
    6.6.3. Modi x ½, x1, x5
    6.6.4. Modo
    6.6.5. Modo DD
    6.6.6. Modo CCID (sistemi TN – Nazione USA)
    6.6.7. Situazioni anomale
    6.7. LOOP: Impedenza Linea/Loop e Resistenza globale di terra
    6.7.1. Modi di prova
    6.7.2. Calibrazione puntali di misura (ZEROLOOP)
    6.7.3. Modo STD – Test generico
    6.7.4. Modo Br.Cap – Verifica potere di interruzione del dispositivo di protezione
    6.7.5. TripT – Verifica del coordinamento delle protezioni

EASYTEST - COMBI519 IT - 2

6.7.6. Test R~a~ 2-fili – Verifica della protezione dai contatti indiretti
6.7.7. Test R~a~ 3-fili - Verifica della protezione dai contatti indiretti
6.7.8. Verifica della protezione contro contatti indiretti (sistemi IT)
6.7.9. Verifica della protezione contro contatti indiretti (sistemi TT)
6.7.10. Verifica della protezione contro contatti indiretti (sistemi TN)
6.7.11. Situazioni anomale
6.8. LoZ: Impedenza Linea/loop ad alta risoluzione
6.9. 1,2,3: Senso ciclico e concordanza delle fasi
6.9.1. Situazioni anomale
6.10. V%: Caduta di tensione sulle linee
6.10.1. Situazioni anomale
7.  MEMORIZZAZIONE RISULTATI
    7.1. Salvataggio delle misure
    7.2. Richiamo dei dati a display e cancellazione memoria
8.  COLLEGAMENTO DELLO STRUMENTO A PC
9.  MANUTENZIONE
    9.1. Generalità
    9.2. Sostituzione batterie
    9.3. Pulizia dello strumento
    9.4. Fine vita
10. SPECIFICHE TECNICHE
    10.1. Caratteristiche tecniche
    10.2. Caratteristiche generali
    10.3. Condizioni ambientali di utilizzo
    10.4. Accessori
11. ASSISTENZA
    11.1. Condizioni di garanzia
    11.2. Assitenza
12. APPENDICI TEORICHE
    12.1. Continuità dei conduttori di protezione
    12.2. Resistenza di isolamento
    12.2.1. Misura Indice di Polarizzazione (PI)
    12.2.2. Rapporto di Assorbimento Dielettrico (DAR)
    12.3. Verifica della separazione dei circuiti
    12.4. Test su interruttori differenziali (RCD)
    12.5. Verifica del potere di interruzione della protezione
    12.6. Verifica protezione contro contatti indiretti nei sistemi TN
    12.7. Test R~a~ nei sistemi TN
    12.8. Verifica protezione contro contatti indiretti nei sistemi TT
    12.9. Verifica protezione contro contatti indiretti nei sistemi IT
    12.10. Verifica coordinamento delle protezioni L - L, L - N e L - PE
    12.11. Verifica della caduta di tensione su linee di distribuzione

EASYTEST - COMBI519 IT - 3

# 1. PRECAUZIONI E MISURE DI SICUREZZA

Lo strumento è stato progettato in conformità alle direttive IEC/EN61557 e IEC/EN61010, relative agli strumenti di misura elettronici. Prima e durante l’esecuzione delle misure attenersi scrupolosamente alle seguenti indicazioni:

*   Non effettuare misure di tensione o corrente in ambienti umidi.
*   Non effettuare misure in presenza di gas o materiali esplosivi, combustibili o in ambienti polverosi.
*   Evitare contatti con il circuito in esame se non si stanno effettuando misure.
*   Evitare contatti con parti metalliche esposte, con terminali di misura inutilizzati, ecc.
*   Non effettuare alcuna misura qualora si riscontrino anomalie nello strumento come, deformazioni, rotture, fuoriuscite di sostanze, assenza di visualizzazione, ecc
*   Prestare particolare attenzione quando si effettuano misure di tensioni superiori a 25V in ambienti particolari (cantieri, piscine, ...) e 50V in ambienti ordinari in quanto si è in presenza di rischio di shock elettrici.
*   Utilizzare solo gli accessori originali

Nel presente manuale sono utilizzati i seguenti simboli:

> **Attenzione:** attenersi alle istruzioni riportate nel manuale; un uso improprio potrebbe causare danni allo strumento, ai suoi componenti o creare situazioni pericolose per l’operatore.

> **Pericolo alta tensione:** rischi di shock elettrici.

> Doppio isolamento

> Tensione o corrente AC

> Tensione o corrente DC

> Riferimento di terra

> Il simbolo indica che lo strumento non deve essere utilizzato in sistemi di distribuzione con tensione superiore a 460V

## 1.1. Istruzioni preliminari

*   Questo strumento è stato progettato per l’utilizzo in condizioni ambientali specificate al § 10.3 Non operare in condizioni ambientali differenti.
*   Può essere utilizzato per misure e prove di verifica della sicurezza su impianti elettrici. Non operare su circuiti che superino i limiti specificati al § 10.1
*   La invitiamo a seguire le normali regole di sicurezza orientate a proteggerLa contro correnti pericolose e proteggere lo strumento contro un utilizzo errato.
*   Solo gli accessori forniti a corredo dello strumento garantiscono gli standard di sicurezza. Essi devono essere in buone condizioni e sostituiti, se necessario, con modelli identici.
*   Controllare che le batterie siano inserite correttamente.
*   Prima di collegare i puntali al circuito in esame, controllare che sia stata selezionata la funzione desiderata

EASYTEST - COMBI519 IT - 4

## 1.2. Durante l’uso

La preghiamo di leggere attentamente le raccomandazioni e le istruzioni seguenti:

> **ATTENZIONE**
> La mancata osservazione delle avvertenze e/o istruzioni può danneggiare lo strumento e/o i suoi componenti o essere fonte di pericolo per l’operatore.

*   Prima di cambiare funzione scollegare i puntali di misura dal circuito in esame.
*   Quando lo strumento è connesso al circuito in esame non toccare mai alcun terminale, anche se inutilizzato
*   Evitare la misura di resistenza in presenza di tensioni esterne; anche se lo strumento è protetto una tensione eccessiva potrebbe causarne danneggiamenti

## 1.3. Dopo l’uso

Quando le misure sono terminate, spegnere lo strumento mantenendo premuto il tasto **ON/OFF** per alcuni secondi. Se si prevede di non utilizzare lo strumento per un lungo periodo rimuovere le batterie ed attenersi a quanto specificato nel § 3.3

## 1.4. Definizione di categoria di misura (sovratensione)

La norma "IEC/EN61010 - 1: Prescrizioni di sicurezza per apparecchi elettrici di misura, controllo e per utilizzo in laboratorio, Parte 1: Prescrizioni generali", definisce cosa si intenda per categoria di misura, comunemente chiamata categoria di sovratensione. Al § 6.7.4: Circuiti di misura, essa recita: i circuiti sono suddivisi nelle seguenti categorie di misura:

*   La **Categoria di misura IV** serve per le misure effettuate su una sorgente di un’installazione a bassa tensione.
    Esempi sono costituiti da contatori elettrici e da misure sui dispositivi primari di protezione dalle sovracorrenti e sulle unità di regolazione dell’ondulazione.
*   La **Categoria di misura III** serve per le misure effettuate in installazioni all’interno di edifici.
    Esempi sono costituiti da misure su pannelli di distribuzione, disgiuntori, cablaggi, compresi i cavi, le barre, le scatole di giunzione, gli interruttori, le prese di installazioni fisse e gli apparecchi destinati all’impiego industriale e altre apparecchiature, per esempio i motori fissi con collegamento ad impianto fisso.
*   La **Categoria di misura II** serve per le misure effettuate su circuiti collegati direttamente all’installazione a bassa tensione.
    Esempi sono costituiti da misure su apparecchiature per uso domestico, utensili portatili ed apparecchi similari.
*   La **Categoria di misura I** serve per le misure effettuate su circuiti non collegati direttamente alla RETE DI DISTRIBUZIONE.
    Esempi sono costituiti da misure su non derivati dalla RETE e derivati dalla RETE ma con protezione particolare (interna). In quest’ultimo caso le sollecitazioni da transitori sono variabili, per questo motivo (OMISSIS) si richiede che l’utente conosca la capacità di tenuta ai transitori dell’apparecchiatura

EASYTEST - COMBI519 IT - 5

# 2. DESCRIZIONE GENERALE

## 2.1. Introduzione

Questo manuale si riferisce ai modelli **EASYTEST** e **COMBI519**. Salvo notazione esplicita, per “strumento” è inteso il modello COMBI519. Le caratteristiche dei modelli sono elencate nella seguente **Tabella 1**:

| Nome   | Descrizione misura                                                                                                                    | EASYTEST   | COMBI519   |
| :----- | :------------------------------------------------------------------------------------------------------------------------------------ | :--------- | :--------- |
| AUTO   | Misura AUTO di R~a~, RCD, M in sequenza                                                                                                | ✓          | ✓          |
| DMM    | Funzione multimetro (Tensione AC, Frequenza                                                                                            | ✓          | ✓          |
| RPE    | Prova di continuità dei conduttori di terra, di protezione ed equipotenziali con 200mA                                                 | ✓          | ✓          |
| Lo    | Prova di continuità dei conduttori di terra, di protezione ed equipotenziali con 10A con relativo accessorio opzionale EQUITEST        | ✓          | ✓          |
| M     | Misura della resistenza di isolamento (modi L - PE, N - PE, L - N)                                                                     | ✓          | ✓          |
| RCD    | Test su differenziali scatolato AC, A/F, B/B+ DD e CCID Generali e Selettivi fino a 1000mA                                                | ✓ (A/F, AC) | ✓ (A/F, AC, B/B+, DD, CCID) |
| LOOP   | Misure della Resistenza Globale di Terra (R~a~) e misura della impedenza di linea e dell'anello di guasto (Loop P - N, P - P, P - PE) con calcolo della corrente di cortocircuito presunta | ✓          | ✓          |
| LoZ    | Misure della impedenza di linea e dell'anello di guasto (Loop P - N, P - P, P - PE) ad alta risoluzione con calcolo della corrente di cortocircuito presunta (con accessorio opzionale IMP57) |            | ✓          |
| 1,2,3  | Rilevazione del senso ciclico e concordanza delle fasi a 1 terminale                                                                 | ✓          | ✓          |
| ΔV%    | Misura della caduta di tensione percentuale su linee di distribuzione                                                                  | ✓          | ✓          |

**Tabella 1:** Descrizione dei modelli

EASYTEST - COMBI519 IT - 6

## 2.2. Funzionalità dello strumento

Lo strumento può eseguire le seguenti prove:

*   **RPE** Continuità dei conduttori di terra, di protezione ed equipotenziali con corrente di prova superiore a 200mA e tensione a vuoto compresa tra 4 e 24V
*   **M** Misura della resistenza di isolamento con tensione continua di prova 50V, 100V, 250V, 500V o 1000V DC
*   **LOOP** Misura dell’impedenza di Linea/Loop P - N, P - P, P - E con calcolo della corrente di cortocircuito presunta, resistenza globale di terra senza intervento RCD (R~A~), verifica del potere di interruzione di protezioni magnetotermiche (MCB) e fusibili, verifica delle protezioni in caso di contatti indiretti con collegamento a 2 fili e 3 fili
*   **LoZ** Misura dell’impedenza di Linea/Loop P - N, P - P, P - E con calcolo della corrente di cortocircuito presunta anche con risoluzione elevata (0.1m) (con accessorio opzionale IMP57)
*   **ΔV%** Misura della caduta di tensione percentuale sulle linee
*   **Lo** Continuità dei conduttori di terra, di protezione ed equipotenziali con corrente di prova superiore a 10A (con accessorio opzionale EQUITEST)
*   **RCD** Test su differenziali di tipo scatolato (Standard - STD) Generali (G), e Selettivi (S) di tipo A/F ( ), AC ( ), B/B+ ( ), DD e CCID ( , ) (nazione USA) dei seguenti parametri: tempo di intervento, corrente di intervento, tensione di contatto
*   **AUTO** Misura in sequenza automatica delle funzioni R~A~, RCD, M con collegamento a 3 fili
*   **1,2,3** Indicazione del senso ciclico delle fasi con metodo a 1 terminale
*   **DMM** Funzione multimetro per misura tensione Fase - Neutro, Fase - Fase o Fase - PE e frequenza

EASYTEST - COMBI519 IT - 7

# 3. PREPARAZIONE ALL’UTILIZZO

## 3.1. Controlli iniziali

Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili affinché lo strumento potesse essere consegnato senza danni. Tuttavia si consiglia di controllarlo per accertare eventuali danni subiti durante il trasporto. Qualora si dovessero riscontrare anomalie contattare immediatamente il rivenditore. Si consiglia inoltre di controllare che l’imballaggio contenga tutte le parti indicate al § 10.4. In caso di discrepanze contattare il rivenditore. Qualora fosse necessario restituire lo strumento si prega di seguire le istruzioni riportate al § 11.

## 3.2. Alimentazione dello strumento

Lo strumento è alimentato tramite 6x1.5V batterie alcaline tipo AA LR06 fornite in dotazione. Il simbolo “ ” indica il livello di carica delle batterie. Per la sostituzione delle batterie vedere il § 9.2.
Lo strumento è in grado di mantenere i dati memorizzati anche in assenza di batterie.
Lo strumento dispone di una funzione di autospegnimento (disabilitabile) dopo 10 minuti di non utilizzo.

## 3.3. Conservazione

Per garantire misure precise, dopo un lungo periodo di permanenza in magazzino in condizioni ambientali estreme, attendere che lo strumento ritorni alle condizioni normali (vedere § 10.3).

EASYTEST - COMBI519 IT - 8

# 4. NOMENCLATURA

## 4.1. Descrizione dello strumento

LEGENDA:
1. Ingressi
2. Display LCD
3. Tasti , , , , SAVE/ENTER
4. Vano connettore cavo ottico/USB
5. Tasti GO/STOP
6. Tasto HELP/
7. Tasto ESC/MENU
8. Tasto ON/OFF

Fig. 1: Descrizione parte frontale dello strumento

LEGENDA:
1. Connettore per puntale remoto
2. Ingressi B1, B3, B4

Fig. 2: Descrizione parte superiore dello strumento

> **ATTENZIONE**
> Lo strumento esegue il controllo della tensione su PE confrontando la tensione sull’ingresso B4 e il potenziale di terra indotto sulle parti laterali dello stesso per mezzo della mano dell’operatore pertanto al fine di eseguire un controllo corretto della tensione su PE è necessario tenere impugnato lo strumento nella parte laterale destra o nella parte laterale sinistra

## 4.2. Descrizione dei terminali di misura

LEGENDA:
1. Barriera paramano
2. Zona di sicurezza

Fig. 3: Descrizione dei terminali di misura

EASYTEST - COMBI519 IT - 9

## 4.3. Descrizione della tastiera

La tastiera è costituita dai seguenti tasti:

*   Tasto **ON/OFF** per accendere e spegnere lo strumento
*   Tasto **ESC** per uscire dal menu selezionato senza confermare le modifiche
*   Tasto **MENU** per tornare al menu generale dello strumento in ogni momento
*   Tasti **   ** per spostare il cursore all’interno delle varie schermate allo scopo di selezionare i parametri di programmazione
*   Tasto **SAVE/ENTER** per il salvataggio dei parametric interni (SAVE) e per selezionare le funzioni desiderate dal menu (ENTER)
*   Tasto **GO** per avviare la misurazione
*   Tasto **STOP** per terminare la misurazione
*   Tasto **HELP** per accedere all’help on line visualizzando, per ciascuna funzione selezionata, le possibili connessioni tra strumento ed impianto
*   Tasto (pressione continua) per la regolazione della retroilluminazione

## 4.4. Descrizione del display

Il display è un modulo COG LCD, 128x128 punti. La prima linea del display indica il tipo di misura attiva, la data/ora e l’indicazione sul livello di carica della batteria.

```
R P E   115/10 – 18:04
R     = --- 
Itest = --- mA
Misura …
STD   2.00    0.12 
MODE   Lim   ><
```

## 4.5. Videata iniziale

All’accensione dello strumento viene visualizzata per qualche secondo la videata iniziale. In essa sono visualizzati:

*   Il modello dello strumento
*   Il costruttore dello strumento
*   Il numero di serie dello strumento (SN:)
*   La versione dell’Hardware (HW:) e del Firmware (FW:) interno dello strumento
*   La data di ultima calibrazione dello strumento

```
COMBI519
HT ITALIA
SN: 25100100
HW: 02
FW: 2.14
Data calibrazione:
15/04/2025
```

Dopo alcuni istanti lo strumento passa al menu generale

EASYTEST - COMBI519 IT - 10

# 5. MENU GENERALE

La pressione del tasto **HOME**, in qualunque condizione si trovi lo strumento, consente di tornare al menu generale da cui è possibile impostare i parametri interni e selezionare la misura desiderata.

```
MENU 15/10 – 18:04
AUTO : Ra, RCD, M
DMM : Multimetro.
RPE : Continuità
Lo : RPE.Test 10A
M : Isolamento
RCD : Differenziali
LOOP : ZLinea, , Isc

```

```
MENU 15/10 – 18:04
LoZ : Z alta precisione
1,2,3 : Seq. Fasi
V% : Caduta Tens.
SET : Impostazioni
MEM : Dati memorizzati
PC : Trasferimento dati

```

Selezionare spostando il cursore una delle misure presenti e confermare con il tasto **ENTER**. Lo strumento mostra la misura desiderata a display.

## 5.1. SET – impostazioni strumento

Spostare il cursore su **SET** usando i tasti freccia (****, ****) e confermare con **ENTER**. Lo strumento mostra la videata che permette l’accesso alle impostazioni interne.
Le impostazioni vengono mantenute anche dopo lo spegnimento dello strumento.

```
SET 15/10 – 18:04
Lingua
Paese
Sistema elettrico
Impostazioni generali
Data e Ora
Informazioni
Nome Operatore
```

### 5.1.1. Lingua

Spostare il cursore su **Lingua** usando i tasti freccia (****, ****) e confermare con **ENTER**. Lo strumento mostra la videata che permette l’impostazione della lingua di sistema.
Selezionare l’opzione desiderata usando i tasti freccia (****, ****). Premere il tasto **ENTER** per confermare o il tasto **ESC** per tornare alla videata precedente.

```
SET 15/10 – 18:04
English
Italian
Español
Deutsch
Français
Portugues
```

EASYTEST - COMBI519 IT - 11

### 5.1.2. Paese

Spostare il cursore su **Paese** usando i tasti freccia (****, ****) e confermare con **ENTER** per la selezione della nazione di riferimento. Questa scelta ha effetto sulle misure di LOOP, e R~a~. Selezionare l’opzione desiderata usando i tasti freccia (****, ****). Premere il tasto **ENTER** per confermare o il tasto **ESC** per tornare alla videata precedente.

```
SET 15/10 – 18:04
Europa
Extra Europa
Germania
Regno Unito
Norvegia
USA
Australia/Nuova Zelanda
```

### 5.1.3. Sistema elettrico

Spostare il cursore su **Sistema elettrico** usando i tasti freccia (****, ****) e confermare con **ENTER**. I seguenti parametri sono impostabili sullo strumento:

*   **Vnom** → la tensione nominale Fase - Neutro o Fase - PE (110V,115V,120V,127V,133V,220V,230V,240V) da usare nel calcolo della corrente di cortocircuito presunta nella misura di LOOP/RCD per sistemi Trifase L1,L2,L3,N (sistema L - N - PE) oppure la tensione nominale tra Fase - Fase nella misura di LOOP/RCD per sistemi Bifase L1,L2,PE (sistema L - L - PE)
*   **Frequenza** → la frequenza di sistema (50Hz, 60Hz)
*   **Sistema** → il tipo di collegamento nelle funzioni RCD e LOOP (L - N - PE o L - L - PE)
*   **Distribuzione** → il tipo di sistema elettrico (TT, TN o IT)

```
SET 15/10 – 18:04
Vnom.     :  230V 
Frequenza   :  50Hz  
Sistema     :  L-N-PE 
Distribuzione :  TN  
V. Contatto :  50V  
IRCD      :  Nom.  
Tipo di RCD :  RCD   
Fattore Isc :  1.00  
```

*   **V.Contatto** → limite sulla tensione di contatto (25V, 50V)
*   **I RCD** → il tipo di visualizzazione della corrente di intervento durante la prova a Rampa (Reale, Nom). Con l’opzione “Nom” lo strumento visualizza il valore della corrente di intervento normalizzata (cioè riferita alla corrente nominale. Esempio: per RCD Tipo A con Idn=30mA, il valore efficace della corrente di intervento normalizzata può arrivare a 30mA. Con l’opzione “Reale” lo strumento visualizza il valore efficace della corrente di intervento applicando i coefficienti indicati nelle normative IEC/EN61008 e IEC/EN61009 (1.414 RCD tipo A/F, 1 RCD tipo AC, 2 RCD tipo B/B+) Esempio: per RCD Tipo A/F con Idn=30mA, il valore della corrente di può arrivare a 30mA * 1.414 = 42mA
*   **Tipo di RCD** → le seguenti opzioni sono disponibili:
    *   **RCD** → lo strumento esegue la misura del tempo di intervento con tutti i moltiplicatori nelle normali condizioni
    *   **RCCB** → solo per RCD da 30mA, lo strumento esegue la misura del tempo di intervento con moltiplicatore x5 su RCD di tipo AC con corrente di prova 250mA e su RCD di tipo A/F con corrente di prova 350mA
    *   **RCDHiS** → lo strumento esegue la misura del tempo di intervento con tutti i moltiplicatori nelle normali condizioni e le misure “Ut” e “R~a~” con corrente di prova Itest  0.65 I~N~/2. Opzione da usare con RCD ad alta sensibilità
*   **Fattore Isc** → (solo per paese Norvegia) possibilità di impostare il valore del fattore ISC (0.01 ÷ 1.00) da usare nel calcolo della corrente di cortocircuito presunta

Selezionare l’opzione desiderata usando i tasti freccia (****, ****). Premere il tasto **ENTER** per confermare o il tasto **ESC** per tornare alla videata precedente.

EASYTEST - COMBI519 IT - 12

### 5.1.4. Impostazioni generali

Spostare il cursore su **impostazioni generali** usando i tasti freccia (****, ****) e confermare con **ENTER**. Lo strumento mostra la videata in cui è possibile regolare il contrasto del display, abilitare/disabilitare l’**auto power off**, il suono associate alla pressione dei tasti e la funzione di **Auto Start** (avvio automatico) nelle funzioni RCD e LOOP (vedere § 5.1.5).
Selezionare l’opzione desiderata usando i tasti freccia (****, ****). Premere il tasto **ENTER** per confermare o il tasto **ESC** per tornare alla videata precedente

```
SET 15/10 – 18:04
Contrasto     :  80   
Auto Power Off :  OFF  
Beep Tastiera  :  OFF  
AutoStart      :  OFF  
(RCD/LOOP)
```

### 5.1.5. Funzione Auto Start

La funzione AutoStart permette di attivare automaticamente le misure RCD e LOOP. Per eseguire correttamente la funzione AutoStart è NECESSARIO eseguire il PRIMO test premendo il tasto **GO/STOP** sullo strumento o il tasto START sul puntale remoto. Al termine del primo test, non appena lo strumento riconosce una tensione stabile sugli ingressi all’interno del campo di misura, esegue il test senza la necessità di premere il tasto **GO/STOP** o il tasto **START** sul puntale remoto.

### 5.1.6. Data e Ora

Spostare il cursore su **Data e Ora** usando i tasti freccia (****, ****) e confermare con **ENTER**. Successivamente la videata a lato è mostrata a display in modo da impostare la data/ora di sistema. Selezionare il campo “Formato” per impostare il sistema Europeo (formato “DD/MM/YY, hh:mm” EU) oppure Americano (formato “MM/DD/YY hh:mm” USA)
Selezionare l’opzione desiderata usando i tasti freccia (****, ****) e (****, ****). Premere il tasto **ENTER** per confermare o il tasto **ESC** per tornare alla videata precedente.

```
SET 15/10 – 18:04
Formato :  EU   
Anno    :  19   
Mese    :  10   
Giorno  :  14   
Ora     :  17.  
Minuto  :  38   
```

### 5.1.7. Informazioni

Spostare il cursore su **Informazioni** usando i tasti freccia (****, ****) e confermare con **ENTER**. Successivamente la videata iniziale a lato è mostrata a display
Premeree **ESC** per tornare al menu generale

```
SET 15/10 – 18:04
COMBI519
HT ITALIA
SN: 25100100
HW: 02
FW: 2.14
Data calibrazione:
15/04/2025
```

EASYTEST - COMBI519 IT - 13

### 5.1.8. Nome operatore

Questa opzione consente di includere il nome dell’operatore che esegue le misure con lo strumento (max 12 caratteri). Tale nome sarà incluso nei report creati con uso del software di gestione.

1.  Usare i tasti freccia **** o **** per spostare il cursore sul carattere selezionare e premere il tasto **SAVE/ENTER** per l’inserimento
2.  Muovere il cursore nella posizione “CANC” e premere il tasto **SAVE/ENTER** per cancellare il carattere selezionato
3.  Muovere il cursore nella posizione “FINE” e premere il tasto **SAVE/ENTER** per confermare il nome scritto e tornare alla videata precedente.

```
SAVE 15/10 – 18:04
Tastiera
OPERATORE_
0 1 2 3 4 5 6 7 8 9 0 ( ) %
Q W E R T Y U I O P < = > #
A S D F G H J K L + - * / &
Z X C V B N M . , ; : ! ? _
Ä Ö Ü ß μ Ñ Ç Á Í Ó Ú Ü ¿ ¡
Á È É Ù Ç Ä Ë Ï Ö Ü Æ Ø Å
CANC FINE
```

EASYTEST - COMBI519 IT - 14

# 6. ISTRUZIONI OPERATIVE

## 6.1. AUTO: SEQUENZA AUTOMATICA PROVE (R~A~, RCD, M)

Questa funzione consente l’esecuzione in sequenza automatica delle seguenti misure:

*   Resistenza globale di terra senza intervento RCD (R~a~)
*   Tempo e corrente di intervento degli interruttori differenziali scatolati Generali tipo A/F ( ), AC ( ) o B/B+ ( )
*   Resistenza di isolamento con tensione di prova 50,100,250,500,1000VDC

> **ATTENZIONE**
> Alcune combinazioni dei parametri di prova potrebbero essere non disponibili in accordo alle specifiche tecniche dello strumento e le tabelle RCD (vedere § 10.1 - Le celle vuote delle tabelle RCD indicano situazioni non disponibili)

> **ATTENZIONE**
> La verifica del tempo di intervento di un interruttore differenziale comporta l'intervento della protezione stessa. Verificare pertanto che a valle della protezione differenziale in esame NON siano allacciate utenze o carichi che possano risentire dalla messa fuori servizio dell'impianto. Scollegare tutti i carichi allacciati a valle dell'interruttore differenziale in quanto potrebbero introdurre correnti di dispersione aggiuntive a quelle fatte circolare dallo strumento invalidando così i risultati della prova.

Fig. 4: Collegamento in sistema Monofase L - N - PE tramite spina shuko

Fig. 5: Collegamento in sistema Monofase L - N - PE con cavi singoli e puntale remoto

EASYTEST - COMBI519 IT - 15

Fig. 6: Collegamento in sistema Bifase L - L - PE tramite spina shuko

Fig. 7: Collegamento in sistema Bifase L - L - PE con cavi singoli e puntale remoto

### Sistemi TN

1.  Premere il tasto **MENU**, muovere il cursore su **AUTO** tramite i tasti freccia (****, ****) e confermare con **ENTER**. Successivamente lo strumento mostra a display una videata come quella a lato in caso di sistema elettrico Monofase L - N - PE selezionato (vedere § 5.1.3). Per sistemi Bifase L - L - PE le tensioni indicate cambiano in VL1 - PE e VL1 - L2. Selezionare la nazione di riferimento (vedere § 5.1.2), l’opzione “TN” “25 o 50V”, “50Hz o 60Hz” e la tensione di riferimento nelle impostazioni generali dello strumento (vedere § 5.1.3)

    ```
    AUTO 15/10 – 18:04
    TN ><
    Isc = --- A ZL-N = --- 
    Ifc = --- A ZL-PE = --- 
    Trcd= --- ms Ircd= --- mA
    FREQ= 0.00 Hz Ut = --- V
    VL-PE= 0V VL-N = 0V
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

2.  Usare I tasti freccia ****, **** per selezionare il parametro da modificare e i tasti freccia ****, **** per modificare il valore del parametro
    *   **In** → Il tasto virtuale permette l’impostazione del valore nominale della corrente di intervento dell’RCD tra I valori: 6mA, 10mA, 30mA
    *   **Tipo** → Il tasto virtuale permette la selezione del tipo di RCD tra le opzioni: A/F ( ), AC ( ) o B/B+ ( )
    *   **Vtest** → Questo tasto permette l’impostazione della tensione di prova DC generate durante la prova di isolamento. I seguenti valori sono disponibili: 50V, 100V, 250V, 500V, 1000V
    *   **Lim** → Questo tasto permette l’impostazione della soglia minima in modo da considerare corretta la misura di isolamento. I seguenti valori sono disponibili: 0.05M, 0.10M, 0.23M, 0.25M, 0.50M, 1.00M, 100M

EASYTEST - COMBI519 IT - 16

> **ATTENZIONE**
> *   Assicurarsi di selezionare il valore corretto della corrente di intervento dell’RCD. Selezionando un valore maggiore di quella nominale del dispositivo in prova, l’RCD sarebbe testato ad una corrente maggiore di quella corretta rendendo non attendibile il risultato
> *   Il simbolo “ ” indica che i cavi di misura o il cavo con spina Shuko sono stati calibrati nella sezione LOOP (vedere § 6.7.2). La funzione AUTO è riferita a questo valore

3.  Inserire i connettori verde, blu e nero del cavo shuko a tre terminali nei corrispondenti terminali di ingresso dello strumento B1, B3 e B4. In alternativa utilizzare i cavi singoli ed inserire all'estremità dei cavi rimasta libera i corrispondenti coccodrilli. Eventualmente utilizzare il puntale remoto inserendone il connettore multipolare nel terminale di ingresso B1. Connettere la spina shuko, i coccodrilli od il puntale remoto alla rete elettrica in accordo alle Fig. 4, Fig. 5, Fig. 6 o Fig. 7
4.  Notare la presenza dei valori di tensione corretti tra L - N e L - PE come mostrato nella videata a fianco

    ```
    AUTO 15/10 – 18:04
    TN ><
    Isc = --- A ZL-N = --- 
    Ifc = --- A ZL-PE = --- 
    Trcd= --- ms Ircd= --- mA
    FREQ= 50.00 Hz Ut = --- V
    VL-PE= 231V VL-N = 232V
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

5.  Premere il tasto **GO/STOP** oppure il tasto **START** sul puntale remoto per attivare la sequenza di prove

    > **ATTENZIONE**
    > Il messaggio “Misura…” appare a display ad indicare che lo strumento sta eseguendo la misura. Durante tutta questa fase non scollegare i terminali di misura dello strumento dall’impianto in esame

6.  Il test R~a~ è avviato e la videata a lato è mostrata a display. Dopo circa 20s la misura R~a~ termina e I valori di Z~L-N~, Z~L-PE~, I~SCMin~, I~FCMin~ sono mostrati a display. In caso di risultato positivo del test R~a~ (Z~L-N~ e Z~L-PE~ <199 ) lo strumento procede con l’esecuzione della misura del tempo e della corrente di intervento dell’RCD

    ```
    AUTO 15/10 – 18:04
    TN ><
    Isc = 1437 A ZL-N = 0.16 
    Ifc = 1277 A ZL-PE = 0.18 
    Trcd= --- ms Ircd= --- mA
    FREQ= 50.00 Hz Ut = --- V
    VL-PE= 231V VL-N = 232V
    Misura...
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

EASYTEST - COMBI519 IT - 17

7.  Il test RCD è avviato e la videata a lato è mostrata a display. I valori della corrente e del tempo di intervento sono mostrati a display.
    In caso di risultato positivo del test (valori di Trcd e Ircd coerenti con quelli indicati nel § 12.4) lo strumento procede con l’esecuzione della misura di isolamento tra i conduttori L - PE, L - N e N - PE

    ```
    AUTO 15/10 – 18:04
    TN ><
    Isc = 1437 A ZL-N = 0.16 
    Ifc = 1277 A ZL-PE = 0.18 
    Trcd= 25 ms Ircd= 27.0 mA
    FREQ= 50.00 Hz Ut = 1.5 V
    VL-PE= 231V VL-N = 232V
    Misura...
    30mA Tipo Vtest Lim
    ```

8.  La misura di isolamento si attiva e la videata a lato è mostrata a display. I valori delle R~L-N~, R~L-PE~ e R~N-PE~ sono mostrati a display.
    In caso di risultato positivo del test (resistenza di isolamento > soglia minima impostata) lo strumento fornisce il messaggio “OK” ad indicare l’esito globale del test come mostrato nella videata a lato
    Premere i tasti (****, ****) per visualizzare I valori presenti nella seconda pagina disponibile

    ```
    AUTO 15/10 – 18:04
    TN ><
    RL-N > 999 M Vt = 523 V
    RL-PE > 999 M Vt = 524 V
    RN-PE > 999 M Vt = 522 V
    FREQ= 50.00 Hz Ut = 1.5 V
    VL-PE= 0 V VL-N = 0 V
     OK 
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

9.  In caso di esito negativo del test R~a~ (Z~L-N~ e/o Z~L-PE~ > 199 ), il test auto è automaticamente bloccato e il messaggio “NO OK” è mostrato a display come nella videata a lato.

    ```
    AUTO 15/10 – 18:04
    TN ><
    Isc = 1437 A ZL-N = 0.16 
    Ifc = --- A ZL-PE > 199 
    Trcd= --- ms Ircd= --- mA
    FREQ= 50.00 Hz Ut = --- V
    VL-PE= 231V VL-N = 232V
     NO OK  ...
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

10. In caso di esito negativo del test RCD (Trcd >300ms o Ircd > 33.0mA) il test auto è automaticamente bloccato e il messaggio “NO OK” è mostrato a display come nella videata a lato.

    ```
    AUTO 15/10 – 18:04
    TN ><
    Isc = 1437 A ZL-N = 0.16 
    Ifc = 1277 A ZL-PE = 0.18 
    Trcd= >300 ms Ircd > 33.0 mA
    FREQ= 50.00 Hz Ut = 1.5 V
    VL-N = 232V VL-PE = 231V
     NO OK 
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

EASYTEST - COMBI519 IT - 18

11. In caso di esito negativo del test Isolamento (resistenza di isolamento < soglia minima impostata) il test auto è automaticamente bloccato e il messaggio “NO OK” è mostrato a display come nella videata a lato

    ```
    AUTO 15/10 – 18:04
    TN ><
    RL-N > 999 M Vt = 523 V
    RL-PE = 0.03 M Vt = 57 V
    RN-PE > 999 M Vt = 522 V
    FREQ= 50.00 Hz Ut = 1.5 V
    VL-PE= 0 V VL-N = 0 V
     NO OK 
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

12. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### Sistemi TT

1.  Premere il tasto **MENU**, muovere il cursore su **AUTO** tramite i tasti freccia (****, ****) e confermare con **ENTER**. Successivamente lo strumento mostra a display una videata come quella a lato in caso di sistema elettrico Monofase L - N - PE selezionato (vedere § 5.1.3). Per sistemi Bifase L - L - PE le tensioni indicate cambiano in VL1 - PE e VL1 - L2. Selezionare la nazione di riferimento (vedere § 5.1.2), l’opzione “TT” “25 o 50V”, “50Hz o 60Hz” e la tensione di riferimento nelle impostazioni generali dello strumento (vedere § 5.1.3

    ```
    AUTO 15/10 – 18:04
    TT ><
    RA = ---  Ut = --- V
    Trcd= --- ms Ircd= --- mA
    FREQ= 0.00 Hz
    VL-PE= 0V VL-N = 0V
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

2.  Usare I tasti freccia ****, **** per selezionare il parametro da modificare e i tasti freccia ****, **** per modificare il valore del parametro
    *   **In** → Il tasto virtuale permette l’impostazione del valore nominale della corrente di intervento dell’RCD tra I valori: 6mA, 10mA, 30mA
    *   **Tipo** → Il tasto virtuale permette la selezione del tipo di RCD tra le opzioni: A/F ( ), AC ( ) o B/B+ ( )
    *   **Vtest** → Questo tasto permette l’impostazione della tensione di prova DC generate durante la prova di isolamento. I seguenti valori sono disponibili: 50V, 100V, 250V, 500V, 1000V
    *   **Lim** → Questo tasto permette l’impostazione della soglia minima in modo da considerare corretta la misura di isolamento. I seguenti valori sono disponibili: 0.05M, 0.10M, 0.23M, 0.25M, 0.50M, 1.00M, 100M

> **ATTENZIONE**
> *   Assicurarsi di selezionare il valore corretto della corrente di intervento dell’RCD. Selezionando un valore maggiore di quella nominale del dispositivo in prova, l’RCD sarebbe testato ad una corrente maggiore di quella corretta rendendo non attendibile il risultato
> *   Il simbolo “ ” indica che i cavi di misura o il cavo con spina Shuko sono stati calibrati nella sezione LOOP (vedere § 6.7.2). La funzione AUTO è riferita a questo valore

EASYTEST - COMBI519 IT - 19

3.  Inserire i connettori verde, blu e nero del cavo shuko a tre terminali nei corrispondenti terminali di ingresso dello strumento B1, B3 e B4. In alternativa utilizzare i cavi singoli ed inserire all'estremità dei cavi rimasta libera i corrispondenti coccodrilli. Eventualmente utilizzare il puntale remoto inserendone il connettore multipolare nel terminale di ingresso B1. Connettere la spina shuko, i coccodrilli od il puntale remoto alla rete elettrica in accordo alle Fig. 4, Fig. 5 Fig. 6 o Fig. 7
4.  Notare la presenza dei valori di tensione corretti tra L - N e L - PE come mostrato nella videata a fianco

    ```
    AUTO 15/10 – 18:04
    TT ><
    RA = ---  Ut = --- V
    Trcd= --- ms Ircd= --- mA
    FREQ= 50.00 Hz Ut = --- V
    VL-PE= 231V VL-N = 232V
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

5.  Premere il tasto **GO/STOP** oppure il tasto **START** sul puntale remoto per attivare la sequenza di prove.

    > **ATTENZIONE**
    > Il messaggio “Misura…” appare a display ad indicare che lo strumento sta eseguendo la misura. Durante tutta questa fase non scollegare i terminali di misura dello strumento dall’impianto in esame

6.  Il test R~a~ è avviato e la videata a lato è mostrata a display. Dopo circa 20s la misura R~a~ termina e I valori di R~A~ (resistenza globale di terra) e Ut (tensione di contatto) sono mostrati a display.
    In caso di risultato positivo del test R~a~ (vedere § 12.8) lo strumento procede con l’esecuzione della misura del tempo e della corrente di intervento dell’RCD

    ```
    AUTO 15/10 – 18:04
    TT ><
    RA = 48.8  Ut = 1.5 V
    Trcd= --- ms Ircd= --- mA
    FREQ= 50.00 Hz
    VL-PE= 231V VL-N = 232V
    Misura...
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

7.  Il test RCD è avviato e la videata a lato è mostrata a display. I valori della corrente e del tempo di intervento sono mostrati a display.
    In caso di risultato positivo del test (valori di Trcd e Ircd coerenti con quelli indicati nel § 12.4) lo strumento procede con l’esecuzione della misura di isolamento tra i conduttori L - PE, L - N e N - PE

    ```
    AUTO 15/10 – 18:04
    TT ><
    RA = 48.8  Ut = 1.5 V
    Trcd= 25 ms Ircd= 27.0 mA
    FREQ= 50.00 Hz
    VL-PE= 231V VL-N = 232V
    Misura...
    30mA Tipo Vtest Lim
    ```

EASYTEST - COMBI519 IT - 20

8.  La misura di isolamento si attiva e la videata a lato è mostrata a display. I valori delle R~L-N~, R~L-PE~ e R~N-PE~ sono mostrati a display.
    In caso di risultato positivo del test (resistenza di isolamento > soglia minima impostata) lo strumento fornisce il messaggio “OK” ad indicare l’esito globale del test come mostrato nella videata a lato
    Premere i tasti (****, ****) per visualizzare I valori presenti nella seconda pagina disponibile

    ```
    AUTO 15/10 – 18:04
    TT ><
    RL-N > 999 M Vt = 523 V
    RL-PE > 999 M Vt = 524 V
    RN-PE > 999 M Vt = 522 V
    FREQ= 50.00 Hz
    VL-PE= 0 V VL-N = 0 V
     OK 
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

9.  In caso di esito negativo del test R~a~ (vedere § 12.8), il test auto è automaticamente bloccato e il messaggio “NO OK” è mostrato a display come nella videata a lato

    ```
    AUTO 15/10 – 18:04
    TT ><
    RA = 1824  Ut = 54.7 V
    Trcd= --- ms Ircd= --- mA
    FREQ= 50.00 Hz
    VL-PE= 231V VL-N = 232V
     NO OK  ...
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

10. In caso di esito negativo del test RCD (Trcd >300ms o Ircd > 33.0mA) il test auto è automaticamente bloccato e il messaggio “NO OK” è mostrato a display come nella videata a lato

    ```
    AUTO 15/10 – 18:04
    TT ><
    RA = 48.8  Ut = 1.5 V
    Trcd= >300 ms Ircd > 33.0 mA
    FREQ= 50.00 Hz
    VL-PE= 231V VL-N = 232V
     NO OK 
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

11. In caso di esito negativo del test Isolamento (resistenza di isolamento < soglia minima impostata) il test auto è automaticamente bloccato e il messaggio “NO OK” è mostrato a display come nella videata a lato

    ```
    AUTO 15/10 – 18:04
    TT ><
    RL-N > 999 M Vt = 523 V
    RL-PE = 0.03 M Vt = 57 V
    RN-PE > 999 M Vt = 522 V
    FREQ= 50.00 Hz Ut = 1.5 V
    VL-PE= 0 V VL-N = 0 V
     NO OK 
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

12. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

EASYTEST - COMBI519 IT - 21

### 6.1.1. Situazioni anomale

1.  Qualora venga rilevata una tensione L - N o L - PE superiore al limite massimo (265V) lo strumento non effettua la prova, visualizzando una videata come quella a fianco. Controllare il collegamento dei cavi di misura

    ```
    AUTO 15/10 – 18:04
    TN
    Isc = --- A ZL-N = --- 
    Ifc = --- A ZL-PE = --- 
    Trcd= --- ms Ircd= --- mA
    FREQ= 50.00 Hz Ut = --- V
    VL-PE= 270V VL-N = 272V
    Tensione > 265V
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

2.  Qualora venga rilevata una tensione L - N o L - PE inferore al limite minimo (100V) lo strumento non effettua la prova, visualizzando una videata come quella a fianco. Controllare che l’impianto in esame sia alimentato

    ```
    AUTO 15/10 – 18:04
    TN
    Isc = --- A ZL-N = --- 
    Ifc = --- A ZL-PE = --- 
    Trcd= --- ms Ircd= --- mA
    FREQ= 50.00 Hz Ut = --- V
    VL-PE= 15V VL-N = 15V
    Tensione < 100V
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

3.  Qualora venga rilevato lo scambio tra i terminali di fase e neutro lo strumento non effettua la prova e visualizza una videata come quella a fianco. Ruotare la spina shuko o controllare il collegamento dei cavi di misura

    ```
    AUTO 15/10 – 18:04
    TN
    Isc = --- A ZL-N = --- 
    Ifc = --- A ZL-PE = --- 
    Trcd= --- ms Ircd= --- mA
    FREQ= --- Hz Ut = --- V
    VL-PE= --- V VL-N = --- V
    Invertire L - N
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

4.  Se lo strumento rileva un potenziale pericoloso sul conduttore PE blocca la prova e visualizza il messaggio a lato. Controllare l’efficienza del conduttore PE e dell’impianto di terra

    ```
    AUTO 15/10 – 18:04
    TN
    Isc = --- A ZL-N = --- 
    Ifc = --- A ZL-PE = --- 
    Trcd= --- ms Ircd= --- mA
    FREQ= --- Hz Ut = --- V
    VL-PE= --- V VL-N = --- V
    Tensione su PE
    30mA 500V 1.00M
    In Tipo Vtest Lim
    ```

EASYTEST - COMBI519 IT - 22

## 6.2. DMM: FUNZIONE MULTIMETRO DIGITALE

Questa funzione permette di leggere i valori TRMS in tempo reale di Tensione P - N, Tensione P - PE, Tensione N - PE e Frequenza (@ ingressi P - N) quando lo strumento è collegato ad un impianto.

Fig. 8: Collegamento dello strumento tramite cavo con spina Shuko

Fig. 9: Collegamento allo strumento tramite cavi singoli e puntale remoto

1.  Premere il tasto **MENU**, spostare il cursore su **DMM** nel menu principale tramite i tasti freccia (****, ****) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato

    ```
    DMM 15/10 – 18:04
    FREQ. = 0.00 Hz
    VL-N = 0 V
    VL-PE = 0 V
    VN-PE = 0 V
    ```

2.  Inserire i connettori verde, blu e nero del cavo shuko a tre pin nei corrispondenti terminali di ingresso B1, B3 e B4 dello strumento. In alternativa, utilizzare i singoli cavi e applicare le relative clip a coccodrillo alle estremità libere dei cavi. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel terminale di ingresso B1. Collegare la spina shuko, i morsetti a coccodrillo o il puntale remoto alla rete elettrica secondo la Fig. 8 o Fig. 9

EASYTEST - COMBI519 IT - 23

3.  I valori TRMS di tensione L - N, tensione L - PE, tensione N - PE e la frequenza della tensione L - N sono mostrati a display.
    Premere il tasto **GO/STOP** per abilitare/disabilitare la funzione “HOLD” in modo da fissare il valore a display.

    ```
    DMM 15/10 – 18:04
    FREQ. = 50.00 Hz
    VL-N = 230 V
    VL-PE = 230 V
    VN-PE = 2 V
    HOLD
    ```

> **ATTENZIONE**
> Questo dato non è salvabile nella memoria interna

EASYTEST - COMBI519 IT - 24

## 6.3. RPE: CONTINUITÀ DEI CONDUTTORI DI PROTEZIONE

Questa funzione viene eseguita secondo le norme CEI 64.8 612.2, IEC/EN61557 - 4, BS7671 17th edition e consente la misura della resistenza dei conduttori di protezione ed equipotenziali.

> **ATTENZIONE**
> *   Lo strumento può essere usato per misure su installazioni con categoria di sovratensione CAT IV 300V verso terra e max 415V tra gli ingressi
> *   Si raccomanda di impugnare il coccodrillo rispettando la zona di sicurezza individuata dalla barriera paramano (vedere § 4.2).
> *   Verificare l’assenza di tensione ai capi dell’oggetto in prova prima di eseguire la misura di continuità
> *   Il risultato delle misure può essere influenzato dalla presenza di circuiti ausiliari collegati in parallelo all’oggetto in prova o per effetto di correnti transitorie

Sono disponibili le seguenti modalità di funzionamento:

*   **STD** Il test è attivato premendo il tasto **GO/STOP** (o il tasto START sul puntale remoto). Modo raccomandato
*   **TMR** Lo strumento esegue la misurazione con la possibilità di impostare il tempo di durata della prova. L’operatore può impostare un tempo sufficientemente lungo per poter muovere i conduttori di protezione mentre lo strumento sta eseguendo la prova al fine di poter individuare un’eventuale cattiva connessione. Per l’intera durata della misura lo strumento emette un segnale acustico ogni 3 secondi. L’operatore può toccare le parti metalliche in prova mentre lo strumento suona. Se, durante la misura, un risultato assume un valore maggiore della soglia limite impostata lo strumento emette un segnale acustico continuo. Premere il tasto **GO/STOP** o il tasto **START** sul puntale remoto per terminare la prova
*   **><** Compensazione della resistenza dei cavi utilizzati per la misurazione, lo strumento sottrae automaticamente il valore della resistenza dei cavi al valore di resistenza misurato. E’ pertanto necessario che tale valore venga misurato ogni volta che i cavi di misura vengono cambiati o prolungati

> **ATTENZIONE**
> La prova di continuità è eseguita erogando una corrente superiore a 200mA per resistenze non superiori a circa 5  (compresa la resistenza dei cavi di misura). Per valori di resistenza superiori lo strumento esegue la prova con una corrente inferiore a 200mA

Fig. 10: Prova di continuità tramite cavi singoli

EASYTEST - COMBI519 IT - 25

Fig. 11: Prova di continuità tramite puntale remoto

1.  Premere il tasto **MENU**, muovere il cursore su **RPE** tramite i tasti freccia (****, ****) e confermare con **ENTER**. Successivamente lo strumento mostra a display una videata come quella a lato

    ```
    RPE 15/10 – 18:04
    R = --- 
    Itest = --- mA
    STD 2.00  --- 
    MODE Lim ><
    ```

2.  Usare I tasti freccia ****, **** per selezionare il parametro da modificare e i tasti freccia ****, **** per modificare il valore del parametro
    *   **MODE** → Il tasto virtuale permette l’impostazione dei modi di misura. Le seguenti opzioni sono possibili: STD, TMR
    *   **Lim** → Questo tasto virtuale permette l’impostazione della soglia limite massima in modo da considerare corretta la misura di continuità. E’ possibile impostare un valore compreso nel campo: 0.01  ÷ 9.99  in passi da 0.01 
    *   **Time (modo TMR)** → Questo tasto virtuale permette di impostare la durata della misura nel campo: 3s ÷ 99s in passi da 3s
3.  Inserire i connettori blu e nero dei cavi singoli nei corrispondenti terminali di ingresso B4 e B1 dello strumento. Collegare i corrispondenti coccodrilli all’estremità dei cavi rimasta libera. Eventualmente utilizzare il puntale remoto inserendone il connettore multipolare nel terminale di ingresso B1
4.  Se la lunghezza dei cavi in dotazione è insufficiente per eseguire la misura, estendere normalmente il cavo blu
5.  Selezionare il modo **><** per eseguire la compensazione della resistenza dei terminali di misura come indicato nel § 6.3.2

> **ATTENZIONE**
> Accertarsi che ai capi del conduttore in esame non sia presente tensione prima di connettervi i terminali di misura.

6.  Connettere i puntali e/o il puntale remoto al conduttore in esame in accordo alle Fig. 10 o Fig. 11

EASYTEST - COMBI519 IT - 26

> **ATTENZIONE**
> Accertarsi sempre, prima di ogni misurazione, che il valore di resistenza di compensazione sia riferita ai cavi effettivamente utilizzati. In caso di dubbio ripetere la procedura di calibrazione indicata nel § 6.3.2

7.  Premere il tasto **GO/STOP** sullo strumento od il tasto **START** sul puntale remoto. Lo strumento avvia la misura

    > **ATTENZIONE**
    > Il messaggio “Misura…” appare a display ad indicare che lo strumento sta eseguendo la misura. Durante tutta questa fase non scollegare i terminali di misura dello strumento dall’impianto in esame

8.  Alla fine della misura lo strumento mostra a display il messaggio “OK” in caso di risultato positivo (valore inferiore alla soglia limite impostata) o "NO OK" in caso di risultato negativo (valore superiore alla soglia limite impostata)

    ```
    RPE 15/10 – 18:04
    R = 0.22 
    Itest = 212 mA
    OK
    STD 2.00  0.21 
    MODE Lim ><
    ```

9.  Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.3.1. Modo TMR

1.  Usare I tasti freccia (****, ****) e selezionare l’opzione "TMR" nella sezione "MODE". Lo strumento mostra a display una videata come quella a lato. Impostare la durata della misura nella sezione "Tempo" e seguire i passi dal punto 2 al punto 6 del § 6.2

    ```
    RPE 15/10 – 18:04
    R = --- 
    Itest = --- mA
    T = --- s
    TMR 2.00  12s --- 
    MODE Lim Tempo ><
    ```

2.  Premere il tasto **GO/STOP** oppure il tasto **START** sul puntale remoto per attivare la prova. Lo strumento inizia una serie di misure continue per l’intera durata della misura impostata mostrando un conto alla rovescia e un breve suono ogni 3 secondi alternando i messaggi "Misura…" e "Attendi…”

    ```
    RPE 15/10 – 18:04
    R = 0.23 
    Itest = 209 mA
    T = 11 s
    Attendi …
    TMR 2.00  12s 0.01 
    MODE Lim Tempo ><
    ```

EASYTEST - COMBI519 IT - 27

3.  Alla fine del tempo di misura impostato lo strumento mostra a display il valore massimo delle misure parziali eseguite e il messaggio "OK" in caso di esito positivo (valore inferiore alla soglia limite impostata) o "NO OK" in caso di esito negativo (valore superiore alla soglia limite impostata)

    ```
    RPE 15/10 – 18:04
    R = 0.54 
    Itest = 209 mA
    T = 0 s
    OK
    TMR 2.00  12s 0.01 
    MODE Lim Tempo ><
    ```

4.  Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.3.2. Modo ><

Fig. 12: Compensazione della resistenza dei cavi singoli e del puntale remoto

1.  Usare I tasti ****, **** per selezionare il tasto virtuale **><**
2.  Connettere i coccodrilli e/o i puntali e/o il puntale remoto al conduttore in esame in accordo alla Fig. 12.
3.  Premere il tasto **GO/STOP** sullo strumento od il tasto **START** sul puntale remoto. Lo strumento inizia la procedura di calibrazione dei cavi seguita immediatamente dalla verifica del valore compensato

    > **ATTENZIONE**
    > Se il messaggio “Misura…” appare a display ciò indica che lo strumento sta eseguendo la misura. Se il messaggio “Verifica” appare a display, lo strumento sta verificando il valore calibrato. Durante l’intero processo non scollegare i puntali tra loro e dallo strumento

4.  Appena la calibrazione è terminata, nel caso in cui il valore rilevato sia inferiore a 5 , lo strumento emette un doppio segnale acustico ad indicare il risultato positivo del test e mostra una videata come quella presente a lato

    ```
    RPE 15/10 – 18:04
    R = --- 
    Itest = --- mA
    STD 2.00  0.01 
    MODE Lim ><
    ```

5.  Per cancellare il valore della resistenza di compensazione dei cavi, è necessario eseguire una procedura di calibrazione del cavo con una resistenza maggiore di 5  ai puntali (es. con puntali aperti)

EASYTEST - COMBI519 IT - 28

### 6.3.3. Situazioni anomale

1.  Nel caso in cui il valore rilevato sia superiore al limite impostato, lo strumento emette un lungo segnale acustico e visualizza una videata simile a quella qui riportata a lato

    ```
    RPE 15/10 – 18:04
    R = 4.54 
    Itest = 212 mA
    NO OK
    STD 2.00  0.01 
    MODE Lim ><
    ```

2.  Se lo strumento rileva una resistenza superiore al fondo scala emette un segnale acustico prolungato e visualizza una videata come quella a lato

    ```
    RPE 15/10 – 18:04
    R = >1999 
    Itest = --- mA
    NO OK
    STD 2.00  0.01 
    MODE Lim ><
    ```

3.  Utilizzando il modo **><**, nel caso in cui lo strumento rilevi un reset della calibrazione (operazione eseguita a terminali aperti), emette un suono lungo e visualizza una videata come quella a lato

    ```
    RPE 15/10 – 18:04
    R = --- 
    Itest = --- mA
    Reset Calib.
    STD 2.00  --- 
    MODE Lim ><
    ```

4.  Utilizzando il modo **><**, se lo strumento rileva ai suoi terminali una resistenza maggiore di 5  emette un segnale acustico prolungato, azzera il valore compensato e visualizza una videata come quella a lato

    ```
    RPE 15/10 – 18:04
    R = --- 
    Itest = --- mA
    Calib. non OK
    STD 2.00  --- 
    MODE Lim ><
    ```

5.  Se lo strumento rileva ai suoi terminali una tensione superiore a 3V non esegue il test, emette un segnale acustico prolungato e visualizza una videata come quella a lato

    ```
    RPE 15/10 – 18:04
    R = --- 
    Itest = --- mA
    Vin > 3V
    STD 2.00  --- 
    MODE Lim ><
    ```

EASYTEST - COMBI519 IT - 29

## 6.4. LO: CONTINUITÀ DEI CONDUTTORI DI PROTEZIONE CON 10A

Questa funzione permette di misurare la resistenza di conduttori di protezione ed equipotenziali con una corrente di prova >10A utilizzando l'accessorio opzionale **EQUITEST** collegato allo strumento tramite il cavo C2050. L’accessorio **EQUITEST** deve essere alimentato direttamente dalla rete su cui vengono effettuate le misurazioni. Per informazioni dettagliate, fare riferimento al manuale utente dell'accessorio **EQUITEST**.

> **ATTENZIONE**
> *   Lo strumento può essere usato per misure su installazioni con categoria di sovratensione CAT IV 300V verso terra e max 415V tra gli ingressi
> *   Si raccomanda di impugnare il coccodrillo rispettando la zona di sicurezza individuata dalla barriera paramano (vedere § 4.2).
> *   Verificare l’assenza di tensione ai capi dell’oggetto in prova prima di eseguire la misura di continuità
> *   I risultati possono essere influenzati dalla presenza di circuiti ausiliari collegati in parallelo l’oggetto della misura o da correnti transitorie
> *   Il test di continuità viene effettuato fornendo una corrente superiore a 10A nel caso la resistenza non superi ca. 0.7  (inclusa la resistenza dei cavi di prova). Il metodo a 4 fili consente di estendere i puntali senza alcuna calibrazione preliminare

1.  Premere il tasto **MENU**, spostare il cursore su **Lo** nel menu principale tramite i tasti freccia (****, ****) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato

    ```
    Lo 15/10 – 18:04
    R     = --- 
    Itest = --- A
    0.500  MAN
    Lim. INFO MODE
    ```

2.  Usare I tasti freccia ****, **** per selezionare il parametro da modificare e i tasti freccia ****, **** per modificare il valore del parametro:
    *   **Lim** → questo tasto virtuale permette la selezione del limite massimo per considerare corretto il valore misurato. È possibile impostare un limite compreso nel campo: 0.003  ÷ 0.500  in passi di 0.001
    *   **MODE** → Il tasto virtuale permette l’impostazione dei modi di misura. Le seguenti opzioni sono possibili: MAN (la misura è attivata manualmente tramite il tasto GO/STOP), AUTO (la misura è automaticamente avviata dopo il collegamento dell’accessorio EQUITEST al cavo in prova senza pressione del tasto GO/STOP)
3.  Collegare l'accessorio **EQUITEST** all'alimentazione principale (230/240V - 50/60Hz) e notare l'accensione del LED verde. Collegare l'accessorio allo strumento tramite il cavo C2050. Successivamente il messaggio "Conn." è mostrato a display ad indicare il corretto riconoscimento da parte dello strumento

    ```
    Lo 15/10 – 18:04
    R     = --- 
    Itest = --- A
    0.500  Conn. MAN
    Lim. INFO MODE
    ```

EASYTEST - COMBI519 IT - 30

4.  Utilizzare i tasti ****, **** per selezionare la voce “INFO”. La videata a lato è mostrata sul display indicando le informazioni relative all'accessorio **EQUITEST**

    ```
    Lo 15/10 – 18:04
    EQUITEST
    SN : 210600023
    FW : 1.00
    HW : 1.00
    Data Cal : 30/11/21
    Stato : Connesso
    0.500  Conn. MAN
    Lim. INFO MODE
    ```

5.  Collegare i terminali a coccodrillo al conduttore da testare (per ogni dettaglio vedere il manuale d’uso dell’accessorio **EQUITEST**)
6.  Premere il tasto **GO/STOP** sullo strumento per attivare la misura (in caso di selezione modo MAN) oppure eseguire la misura automatica (in caso di selezione modo AUTO). Al termine della misura il messaggio "OK" è mostrato a display in caso di risultato positivo (valore inferiore alla soglia limite impostata) o "NO OK" in caso di risultato negativo (valore superiore alla soggia limite impostata

    ```
    Lo 15/10 – 18:04
    R     = 0.328 
    Itest = 14.76 A
    OK
    0.500  Conn. MAN
    Lim. INFO MODE
    ```

7.  Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

EASYTEST - COMBI519 IT - 31

### 6.4.1. Situazioni anomale

1.  Se lo strumento rileva ai suoi terminali una tensione superiore a 3V non esegue il test, emette un segnale acustico prolungato e visualizza una videata come quella a lato

    ```
    Lo 15/10 – 18:04
    R     = --- 
    Itest = --- A
    Vin > 3V
    0.500  Conn. MAN
    Lim. INFO MODE
    ```

2.  Se lo strumento non rileva l'accessorio **EQUITEST** visualizza una videata come quella a lato. Verificare i collegamenti con l'accessorio

    ```
    Lo 15/10 – 18:04
    R     = --- 
    Itest = --- A
    Accessorio non rilevato
    0.500  Conn. MAN
    Lim. INFO MODE
    ```

3.  Lo strumento visualizza sul display la scritta "NON OK" in caso di esito positivo (valore inferiore alla soglia limite impostata) ma con corrente di prova inferiore a 10A come indicato nella videata come quella a lato

    ```
    Lo 15/10 – 18:04
    R     = 0.119 
    Itest = 8.05 A
    NON OK
    0.500  Conn. MAN
    Lim. INFO MODE
    ```

EASYTEST - COMBI519 IT - 32

## 6.5. M: MISURA RESISTENZA DI ISOLAMENTO

Questa funzione viene eseguita secondo le norme CEI 64.8 612.3, IEC/EN61557 - 2, BS7671 17th edition, AS/NZS 3000, AS/NZS 3017 e consente la misura della resistenza di isolamento tra i conduttori attivi e tra ogni conduttore attivo e la terra. Sono disponibili le seguenti modalità di funzionamento:

*   **MAN** Il test è eseguito tra i conduttori L - N, L - PE o N - PE e ha una durata fissa di 3s quando si preme il tasto **GO/STOP** sullo strumento (o START sul puntale remoto). Modalità consigliata
*   **TMR** il test viene effettuato tra i conduttori L - PE ed ha una durata programmabile nel campo 3s ÷ 999s in passi da 1s alla pressione del tasto **GO/STOP** sullo strumento (o START del puntale remoto). È possibile eseguire il test di durata DAR (Rapporto di Scarica Dielettrca) per un tempo di test >60s e PI (Indice di polarizzazione) per un tempo di test > 600s (10 min) (vedere § 12.2.1 e § 12.2.2)
*   **AUTO** Lo strumento esegue un test di sequenza automatico tra i conduttori L - N, L - PE e N - PE alla pressione del tasto **GO/STOP** sullo strumento (o START del puntale remoto)

Fig. 13: Isolamento tra L - N - PE tramite cavi singoli (modi MAN e AUTO)

Fig. 14: Isolamento tra L - N - PE tramite cavi singoli e puntale remoto (modi MAN e AUTO)

EASYTEST - COMBI519 IT - 33

Fig. 15: Isolamento tra L - N - PE tramite cavo con spina Shuko (modi MAN e AUTO)

Fig. 16: Isolamento tra L - PE tramite cavo con spina Shuko (modo TMR)

Fig. 17: Isolamento tra L - PE tramite cavi singoli (modo TMR)

EASYTEST - COMBI519 IT - 34

Fig. 18: Isolamento tra L - PE tramite cavi singoli e puntale remoto (modo TMR)

1.  Premere il tasto **MENU**, spostare il cursore su **M** nel menu principale tramite i tasti freccia (****, ****) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato

    ```
    M 15/10 – 18:04
    R  = --- M
    Vt = --- V
    T  = --- s
    MAN 500V 1.00M L-PE
    MODE Vtest Lim. FUNZ
    ```

2.  Utilizzare i tasti ****, **** per selezionare il parametro da modificare e i tasti ****, **** per modificare il valore del parametro:
    *   **MODE** → Questo tasto permette di impostare il tipo di test. Sono disponibili le seguenti opzioni: MAN, TMR, AUTO
    *   **Vtest** → Questo tasto permette di selezionare la tensione di prova DC generata durante la misura. Sono disponibili i seguenti valori: 50V, 100V, 250V, 500V, 1000V
    *   **Lim** → Questo tasto permette la selezione della soglia limite minima per considerare corretta la misura. Sono disponibili i seguenti valori: 0.05M, 0.10M, 0.23M, 0.25M, 0.50M, 1.00M, 100M
    *   **FUNZ** → Questo tasto permette di impostare il tipo di connessione L - N, L - PE o N - PE nel modo MAN
    *   **Temp** → solo in modalità TMR, questo tasto virtuale permette di impostare la durata del test nel campo: 3s ÷ 999s
3.  Si consiglia di impostare il valore della tensione fornita durante la misura e il limite minimo per considerare la misura corretta secondo le prescrizioni della normativa di riferimento (vedere § 12.2)
4.  Inserire i connettori verde e nero dei singoli cavi nei corrispondenti terminali di ingresso B1, B3, B4 (modi MAN e AUTO) o B1, B3 (modo TMR) dello strumento. Applicare i terminali a coccodrillo alle estremità libere dei cavi. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel terminale di ingresso B1. Se la lunghezza dei cavi forniti non è sufficiente per la misura da effettuare, allungare il cavo verde

EASYTEST - COMBI519 IT - 35

> **ATTENZIONE**
> *   Scollegare ogni cavo non strettamente coinvolto nella misura
> *   Prima di collegare i puntali, assicurarsi che non ci sia tensione alle estremità dei conduttori da testare

5.  Collegare i cavi di misura e il puntale remoto alle estremità dei conduttori da testare come mostrato in Fig. 13, Fig. 14, Fig. 15, Fig. 16, Fig. 17, o Fig. 18
6.  Premere il tasto **GO/STOP** sullo strumento o il tasto **START** sul puntale remoto. Lo strumento inizierà la misura

    > **ATTENZIONE**
    > Se sul display appare il messaggio "Misura ...", lo strumento sta eseguendo il test. Durante tutta questa fase non scollegare i puntali dello strumento dai conduttori in prova, in quanto il circuito potrebbe rimanere affetto da una tensione pericolosa dovuta alle capacità parassite del sistema

7.  Indipendentemente dalla modalità di funzionamento selezionata, lo strumento, al termine di ogni prova, applica una resistenza ai conduttori di uscita per scaricare le capacità parassite nel circuito
8.  Al termine della misura (durata fissa 3s) lo strumento visualizza sul display il messaggio "OK" in caso di risultato positivo (valore superiore alla soglia limite minima impostata) o "NO OK" in caso di risultato negativo (valore inferiore alla soglia limite minima impostata). L'indicazione ">999M" indica il fuori scala dello strumento che, normalmente, risulta essere il miglior risultato possibile

    ```
    M 15/10 – 18:04
    R  = > 999 M
    Vt = 512 V
    T  = 3 s
    OK
    MAN 500V 1.00M L-PE
    MODE Vtest Lim. FUNZ
    ```

9.  Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

EASYTEST - COMBI519 IT - 36

### 6.5.1. Modo TMR

1.  Con i tasti freccia (****, ****) selezionare l'opzione "TMR" nella sezione "MODE". Lo strumento visualizza una schermata come quella mostrata a lato. Impostare la durata della misura nella sezione "Tempo" e seguire i passaggi dal punto 2 al punto 5 del § 6.5

    ```
    M 15/10 – 18:04
    R = --- M
    Vt = --- V T = --- s
    PI = --- DAR = ---
    TMR 500V 1.00M 10s
    MODE Vtest Lim. Tempo
    ```

2.  Premere il tasto **GO/STOP** sullo strumento o il tasto START sul puntale remoto. Lo strumento avvia la misura per tutta la durata impostata visualizzando il messaggio "Misura...". Lo strumento visualizza il messaggio "OK" sul display in caso di risultato positivo (valore superiore alla soglia minima impostata) o "NO OK" in caso di risultato negativo (valore inferiore al limite minimo impostato

    ```
    M 15/10 – 18:04
    R = 102 M
    Vt = 523 V T = 10 s
    PI = --- DAR = ---
    OK
    TMR 500V 1.00M 10s
    MODE Vtest Lim. Tempo
    ```

3.  Con una durata della misura ≥ 60s lo strumento mostra l'indicazione del parametro DAR (Rapporto di Assorbimento Dielettrico) come mostrato nella videata a lato

    ```
    M 15/10 – 18:04
    R = 102 M
    Vt = 523V T = 60 s
    PI = --- DAR = 1.03
    OK
    TMR 500V 1.00M 60s
    MODE Vtest Lim. Tempo
    ```

4.  Con una durata della misura ≥ 600s lo strumento mostra l'indicazione del parametro PI (Indice di Polarizzazione) come mostrato nella videata a lato

    ```
    M 15/10 – 18:04
    R = 102 M
    Vt = 523V T = 600 s
    PI = 1.00 DAR = 1.03
    OK
    TMR 500V 1.00M 600s
    MODE Vtest Lim. Tempo
    ```

5.  Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere §) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

EASYTEST - COMBI519 IT - 37

### 6.5.2. Modo AUTO

1.  Con i tasti freccia (****, ****) selezionare l'opzione "AUTO" nella sezione "MODE". Lo strumento visualizza una schermata come quella mostrata a lato
    Lo strumento esegue il test di isolamento tra: L - N, L - PE e N - PE. Poiché alcuni carichi potrebbero essere ancora collegati tra L - N, lo strumento esegue un test preliminare utilizzando 50V come tensione di prova. Se R~L-N~ è superiore a 50k, viene eseguito un nuovo test di isolamento tra L - N utilizzando il valore Vtest. Infine lo strumento esegue il test di isolamento L - PE e N - PE

    ```
    M 15/10 – 18:04
    RL-N = --- M Vt = --- V
    RL-PE = --- M Vt = --- V
    RN-PE = --- M Vt = --- V
    AUTO 500V 1.00M
    MODE Vtest Lim.
    ```

2.  Premere il tasto **GO/STOP** sullo strumento o il tasto START sul puntale remoto. Lo strumento avvia la misura sequenziale automatica della resistenza di isolamento tra L - N, L - PE e N - PE rispettivamente visualizzando il messaggio "Misura...". Lo strumento visualizza sul display il messaggio "OK" in caso di esito positivo di ogni prova (valore superiore alla soglia limite minima impostata) o "NO OK" in caso di esito negativo di almeno un test (valore inferiore al soglia limite minima

    ```
    M 15/10 – 18:04
    RL-N > 999 M Vt = 523 V
    RL-PE = 250 M Vt = 525 V
    RN-PE > 999 M Vt = 524 V
    OK
    AUTO 500V 1.00M
    MODE Vtest Lim.
    ```

3.  Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

EASYTEST - COMBI519 IT - 38

### 6.5.3. Situazioni anomale

1.  Se lo strumento non riesce a generare la tensione nominale, emette un lungo segnale acustico per indicare l'esito negativo del test e visualizza una videata come quella a lato

    ```
    M 15/10 – 18:04
    R  = 0.01 M
    Vt = 0 V
    T  = 3 s
    NO OK
    MAN 500V 1.00M L-PE
    MODE Vtest Lim. FUNC
    ```

2.  Al termine della prova, se il valore di resistenza misurato è inferiore al limite impostato, lo strumento emette un lungo segnale acustico per indicare l'esito negativo del test e visualizza una videata come quella a lato

    ```
    M 15/10 – 18:04
    R  = 0.29 M
    Vt = 534 V
    T  = 3 s
    NO OK
    MAN 500V 1.00M L-PE
    MODE Vtest Lim. FUNC
    ```

3.  In modo AUTO se la misura di isolamento LN è <50k = 0.05M tutti i test sono completati o se è stato premuto il tasto **STOP**, se R~L-PE~ e R~N-PE~> Lim e Vt> Vnom lo strumento mostra la schermata come quello a lato. Scollegare i carichi e riprendere il test

    ```
    M 15/10 – 18:04
    RL-N = 0.01M Vt = 15 V
    RL-PE > 999 M Vt = 525 V
    RN-PE > 999 M Vt = 524 V
    NO OK – Ver. Utilizzatori
    AUTO 500V 1.00M
    MODE Vtest Lim.
    ```

4.  Al termine della prova, se il valore della tensione di prova è inferiore al valore nominale, lo strumento visualizza una videata come quella a lato

    ```
    M 15/10 – 18:04
    R  = 0.12 M
    Vt = 485 V
    T  = 3 s
    Vtest non corretta
    MAN 500V 1.00M L-PE
    MODE Vtest Lim. FUNC
    ```

<!-- Chunk: Pages 40-78 -->
5. Se lo strumento rileva ai suoi terminali una tensione superiore a 30V non esegue il test, emette un segnale acustico prolungato e visualizza una videata come quella a lato

```
M    15/10 – 18:04
R = - - - M 
V = - - - V
t = - - - s
Vin > 30V
MAN 500V 1.00M L - PE MOD E Vtest Lim. FUNC
```

## 6.6. RCD: TEST SU INTERRUTTORI DIFFERENZIALI

Questa funzione viene svolta in conformità alla norma IEC/EN61557 - 6, BS7671 17/18a edizione e permette di misurare il tempo di intervento e la corrente di interruttori differenziali scatolati di tipo A/F ( ), AC ( ), B/B+ ( ) , DD ( ), e CCID ( , ) , Generali (G) e Selettivi (S).

**ATTENZIONE**
Lo strumento esegue il controllo della tensione su PE confrontando la tensione all'ingresso B4 e il potenziale di terra indotto lato strumento dalla mano dell'utente, quindi per controllare la tensione su PE è obbligatorio tenere stretto lo strumento nel lato sinistro oppure nel lato destro

**ATTENZIONE**
*   Alcune combinazioni di parametri di prova possono non essere disponibili in conformità con le specifiche tecniche dello strumento e le tabelle RCD (vedere § 10.1 - le celle vuote delle tabelle RCD indicano situazioni non disponibili)
*   La selezione RCD - DD non è inclusa nella funzione sequenza AUTO

I seguenti modi di misura sono disponibili:

*   **AUTO**: Lo strumento esegue automaticamente la misura del tempo di intervento con una corrente di prova pari alla metà, una o cinque volte il valore impostato di corrente nominale e con una corrente di prova in fase con la semionda positiva della tensione di rete. Modo raccomandato
*   **AUTO** : Lo strumento esegue automaticamente la misura del tempo di intervento con una corrente di prova pari alla metà, una o cinque volte il valore di corrente nominale impostato, con una corrente di prova in fase con la semionda positiva (↑) e negativa (↓) della tensione di rete e anche corrente reale di intervento
*   **x ½**: Lo strumento esegue automaticamente la misura del tempo di intervento con una corrente di prova pari alla metà del valore di corrente nominale impostato, con una corrente di prova in fase con la semionda positiva (↑) e negativa (↓) della tensione di rete
*   **x1**: Lo strumento esegue automaticamente la misura del tempo di intervento con una corrente di prova uguale al valore di corrente nominale impostato, con una corrente di prova in fase con la semionda positiva (↑) e negativa (↓) della tensione di rete
*   **x5**: Lo strumento esegue automaticamente la misura del tempo di intervento con una corrente di prova cinque volte il valore di corrente nominale impostato, con una corrente di prova in fase con la semionda positiva (↑) e negativa (↓) della tensione di rete
*   ****: Lo strumento esegue la misura con una corrente di prova crescente. Questo test può essere eseguito per determinare la reale corrente di intervento dell'RCD con la semionda positiva (↑) e negativa (↓) della tensione di rete

**ATTENZIONE**
La verifica del tempo di intervento di un interruttore differenziale comporta l'intervento della protezione stessa. Verificare pertanto che a valle della protezione differenziale in esame NON siano allacciate utenze o carichi che possano risentire dalla messa fuori servizio dell'impianto.
Scollegare tutti i carichi allacciati a valle dell'interruttore differenziale in quanto potrebbero introdurre correnti di dispersione aggiuntive a quelle fatte circolare dallo strumento invalidando così i risultati della prova.

Fig. 19: Collegamento per sistema Monofase L - N - PE tramite cavo con spina Shuko
Fig. 20: Collegamento per sistema Monofase L - N - PE con cavi singoli e puntale remoto
Fig. 21: Collegamento per sistema Trifase L1 - L2 - L3 - N tramite cavi singoli e puntale remoto
Fig. 22: Collegamento per sistema Bifase L1 - L2 - PE tramite cavi singoli e puntale
Fig. 23: Collegamento per un sistema Trifase L1 - L2 - L3 - N (no PE) mediante cavi singoli e puntale remoto
Fig. 24: Collegamento per un sistema Trifase L1 - L2 - L3 - PE con cavi e puntale remoto

1. Premere il tasto **MENU**, spostare il cursore su **RCD** nel menu principale tramite i tasti freccia (, ) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato in caso di sistema elettrico Monofase L - N - PE selezionato (vedere § 5.1.3). Per sistemi Bifase L - L - PE le tensioni indicate cambiano in VL1 - PE e VL1 - L2. Selezionare il paese (vedere § 5.1.2), le opzioni “TT, TN o IT”, “25 o 50V”, “50Hz o 60Hz” e la tensione di riferimento nelle impostazioni generali dello strumento (vedere § 5.1.3).

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 0.00Hz
VL - PE=0V VL - N =0V
X1 30mA ↑ MODE In Tipo Ut
```

2. Utilizzare i tasti ,  per selezionare il parametro da modificare e i tasti ,  per modificare il valore del parametro:
    *   **MODE** → Il tasto virtuale permette di impostare la modalità di misura dello strumento, che può essere: AUTO, x ½, x1, x5, , AUTO
    *   **In** → Il tasto virtuale consente di impostare il valore nominale della corrente di intervento dell'RCD, che può essere: 5mA, 6mA, 10mA, 20mA, 30mA, 100mA, 300mA, 500mA, 650mA, 1000mA
    *   **Tipo** → Il tasto virtuale consente la selezione del tipo di RCD, che può essere: A/F ( - Generale), A/F ( S - Selettivo), AC ( - Generale), AC ( S - Selettivo), B/B+ ( ), DD e CCID , CCID (nazione USA) con polarità positiva 0° (↑) o negativa 180° (↓)
    *   **Ut** → Il tasto virtuale permette di impostare l'eventuale visualizzazione del valore della tensione di contatto a fine misura. Opzioni: Ut o NoUt

3. Inserire i connettori verde, blu e nero del cavo shuko a tre pin nei corrispondenti terminali di ingresso B3, B4 e B1 dello strumento. In alternativa, utilizzare i singoli cavi e applicare i terminali a coccodrillo alle estremità libere dei cavi. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel terminale di ingresso B1. Collegare la spina shuko, i coccodrilli o il puntale remoto alla rete elettrica in accordo alle Fig. 19, Fig. 20, Fig. 21, Fig. 22, Fig. 23, Fig. 24.

4. Notare i corretti valori di tensione tra L - N e L - PE come mostrato nella videata a lato

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 50.00Hz
VL - PE=232V VL - N=231V
X1 30mA ↑ MODE In Tipo Ut
```

### 6.6.1. Modo AUTO

5. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizia la misura

```
AUTO 15/10 – 18:04
TT
0° 180°
X1 38ms - - - ms
X5 - - - ms - - - ms
X½ - - - ms - - - ms
FREQ = 50.00Hz Ut = - - - V
VL - N = 232V VL - PE = 231V
Misura . . .
AUTO 30mA MODE In Tipo Ut
```

**ATTENZIONE**
Se sul display viene visualizzato il messaggio "Misura...", lo strumento sta eseguendo la misurazione. Durante tutta questa fase non scollegare i puntali dello strumento dalla rete.

6. Il modo AUTO prevede l'esecuzione automatica di 6 misure in sequenza:
    *   IdN x 1 con fase 0° (l'RCD deve scattare, resettare l'interruttore, messaggio "Riarma differenziale”)
    *   IdN x 1 con fase 180° (l'RCD deve scattare, resettare l'interruttore, messaggio "Riarma differenziale”)
    *   IdN x 5 con fase 0° (l'RCD deve scattare, resettare l'interruttore, messaggio "Riarma differenziale”)
    *   IdN x 5 con fase 180° (l'RCD deve scattare, resettare l'interruttore, messaggio "Riarma differenziale”)
    *   IdN x½ con fase 0° (l'RCD non deve scattare)
    *   IdN x½ con fase 180° (l'RCD non deve scattare, fine test)

```
AUTO 15/10 – 18:04
TT
0° 180°
X1 38ms - - - ms
X5 - - - ms - - - ms
X½ - - - ms - - - ms
FREQ = 50.00Hz Ut = - - - V
VL - N = 232V VL - PE = 231V
Riarma differenziale
AUTO 30mA MODE In Tipo Ut
```

7. In caso di esito positivo (tutti i tempi di intervento rispettano quanto indicato nel § 12.4) di tutti i test eseguiti in sequenza viene visualizzato il messaggio “OK” e la videata a lato viene visualizzata dallo strumento

```
AUTO 15/10 – 18:04
TN
0° 180°
X1 38ms 35ms
X5 22ms 27ms
X½ >999ms >999ms
FREQ = 50.00Hz Ut = 0.0V
VL - N = 232V VL - PE = 231V
OK
AUTO 30mA MODE In Tipo Ut
```

8. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.6.2. Modo AUTO

5. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizia la misura

```
RCD 15/10 – 18:04
TT
0° 180°
- - - mA - - - mA
X1 - - - ms - - - ms
X5 - - - ms - - - ms
X½ - - - ms - - - ms
FREQ. = 50.0Hz Ut = - - - V
VL - PE = 231V VL - N = 232V
Misura . . .
AUTO 30mA MODE In Tipo Ut
```

**ATTENZIONE**
Se sul display viene visualizzato il messaggio "Misura...", lo strumento sta eseguendo la misurazione. Durante tutta questa fase non scollegare i puntali dello strumento dalla rete.

6. Il modo AUTO prevede l'esecuzione automatica di 8 misure in sequenza:
    *   (Rampa) con fase 0° (RCD deve scattare, resettare RCD, messaggio "Riarma differenziale”)
    *   (Rampa) con fase 180° (l'RCD deve scattare, resettare RCD, messaggio "Riarma differenziale”)
    *   IdN x 1 con fase 0° (l'RCD deve scattare, resettare RCD, messaggio "Riarma differenziale”)
    *   IdN x 1 con fase 180° (l'RCD deve scattare, resettare RCD, messaggio "Riarma differenziale”)
    *   IdN x 5 con fase 0° (l'RCD deve scattare, resettare RCD, messaggio "Riarma differenziale”)
    *   IdN x 5 con fase 180° (l'RCD deve scattare, resettare RCD, messaggio "Riarma differenziale”)
    *   IdN x½ con fase 0° (l'RCD non deve scattare)
    *   IdN x½ con fase 180° (l'RCD non deve scattare, fine test)

```
RCD 15/10 – 18:04
TT
0° 180°
23mA - - - mA
X1 - - - ms - - - ms
X5 - - - ms - - - ms
X½ - - - ms - - - ms
FREQ. = 50.0Hz Ut = - - - V
VL - PE = 231V VL - N = 232V
Riarma differenziale .
AUTO 30mA MODE In Tipo Ut
```

7. In caso di esito positivo (tutti i tempi di intervento rispettano quanto indicato nel § 12.4) di tutti i test eseguiti in sequenza viene visualizzato il messaggio “OK” e la videata a lato viene visualizzata dallo strumento

```
RCD 15/10 – 18:04
TT
0° 180°
23mA 23mA
X1 23ms 23ms
X5 15ms 15ms
X½ >999ms >999ms
FREQ. = 50.0Hz Ut = 1V
VL - PE = 231V VL - N = 232V
OK .
AUTO 30mA MODE In Tipo Ut
```

8. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.6.3. Modi x ½, x1, x5

5. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizia la misura

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 0.00Hz
VL - PE=0V VL - N=0V
Misura ...
X1 30mA ↑ MODE In Tipo Ut
```

**ATTENZIONE**
Se sul display viene visualizzato il messaggio "Misura...", lo strumento sta eseguendo la misurazione. Durante tutta questa fase non scollegare i puntali dello strumento dalla rete.

6. Quando il differenziale interviene e separa il circuito, se il tempo di intervento rientra nei limiti riportati nel § 12.4, lo strumento emette un doppio segnale acustico che segnala la visualizzazione del messaggio “OK” e la visualizzazione della videata a lato dello strumento

```
RCD 15/10 – 18:04
TT
T = 38 ms
Ut = 1 V
FREQ. = 50.00Hz
VL - PE=231V VL - N=234V
OK
X1 30mA ↑ MODE In Tipo Ut
```

7. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.6.4. Modo

La normativa definisce i tempi di intervento degli RCD alla corrente nominale. Il modo è usato per rilevare il tempo di intervento alla corrente di intervento (che potrebbe anche essere inferiore alla tensione nominale).

5. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizia la misura.

```
RCD 15 /10 – 18:04
TT
I = - - - mA
T = - - - ms Ut = - - - V
FREQ. = 50.00Hz
VL - PE=231V VL - N=234V
Misura ...
30mA ↑ MODE In Tipo Ut
```

**ATTENZIONE**
Se sul display viene visualizzato il messaggio "Misura...", lo strumento sta eseguendo la misurazione. Durante tutta questa fase non scollegare i puntali dello strumento dalla rete.

6. In accordo alla norma EN61008, il test per RCD selettivi richiede un intervallo di 60 secondi tra i test. Il modo non è quindi disponibile per RCD selettivi di ogni tipo

7. Quando il differenziale interviene e separa il circuito, se il tempo di intervento e la corrente di intervento rientrano nei limiti riportati nel § 12.4, lo strumento emette un doppio segnale acustico che segnala la visualizzazione del messaggio “OK” e la visualizzazione della videata a lato dello strumento

```
RCD 15/10 – 18:04
TT
I = 24 mA
T = 38 ms Ut = 1 V
FREQ. = 50.00Hz
VL - PE=231V VL - N=234V
OK
30mA ↑ MODE In Tipo Ut
```

8. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.6.5. Modo DD

La normativa IEC62955 definisce il tempo e la corrente di intervento per gli RCD - DD (Detecting Devices) alla corrente nominale di 6mA. In questa modalità sono disponibili solo le opzioni x1 e.

5. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizia la misura.

```
RCD 15/10 – 18:04
TT
I = - - - mA
T = - - - ms Ut = - - - V
FREQ. = 50.00Hz
VL - PE=231V VL - N=234V
Misura...
6mA DD ↑ MODE In Tipo Ut
```

**ATTENZIONE**
Se sul display viene visualizzato il messaggio "Misura...", lo strumento sta eseguendo la misurazione. Durante tutta questa fase non scollegare i puntali dello strumento dalla rete.

6. Al termine della prova nel caso in cui la corrente di intervento sia compresa nei valori previsti nel § 10.1, lo strumento emette un doppio segnale acustico che segnala la visualizzazione del messaggio “OK” e la visualizzazione della videata a lato dello strumento

```
RCD 15/10 – 18:04
TT
I = 4.5 mA
T = 219 ms Ut = 0 V
FREQ. = 50.00Hz
VL - PE=231V VL - N=234V
OK
6mA DD ↑ MODE In Tipo Ut
```

7. Al termine della prova nel caso in cui la corrente di intervento sia esterna ai valori previsti nel § 10.1, lo strumento emette un doppio segnale acustico che segnala la visualizzazione del messaggio “NO OK” e la visualizzazione della videata a lato dello strumento

```
RCD 15/10 – 18:04
TT
I = 1.2 mA
T = 462 ms Ut = 0 V
FREQ. = 50.00Hz
VL - PE=231V VL - N=234V
NO OK
6mA DD ↑ MODE In Tipo Ut
```

8. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.6.6. Modo CCID (sistemi TN – Nazione USA)

Lo strumento consente la misura del tempo e della corrente di intervento per gli RCD di tipo CCID (forma d’onda sinusoidale) o CCID (forma d’onda continua) alle correnti nominali di 5mA o 20mA. In questa modalità sono disponibili solo le opzioni x1 e .

5. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizia la misura.

```
RCD 15/10 – 18:04
TN
I = - - - mA
T = - - - ms Ut = - - - V
FREQ. = 60.00Hz
VL1 - PE=120V VL1 - L2=240V
Misura...
20mA CCID ↑ MODE In Tipo Ut
```

**ATTENZIONE**
Se sul display viene visualizzato il messaggio "Misura...", lo strumento sta eseguendo la misurazione. Durante tutta questa fase non scollegare i puntali dello strumento dalla rete.

6. Al termine della prova nel caso in cui la corrente di intervento sia compresa nei valori previsti nel § 10.1, lo strumento emette un doppio segnale acustico che segnala la visualizzazione del messaggio “OK” e la visualizzazione della videata a lato dello strumento

```
RCD 15/10 – 18:04
TN
I = 15 mA
T = 219 ms Ut = 0 V
FREQ. = 60.00Hz
VL1 - PE=120V VL1 - L2=240V
OK
20mA CCID ↑ MODE In Tipo Ut
```

7. Al termine della prova nel caso in cui la corrente di intervento sia esterna ai valori previsti nel § 10.1, lo strumento emette un doppio segnale acustico che segnala la visualizzazione del messaggio “NO OK” e la visualizzazione della videata a lato dello strumento

```
RCD 15/10 – 18:04
TN
I = 1.2 mA
T = 462 ms Ut = 0 V
FREQ. = 60.00Hz
VL1 - PE=120V VL1 - L2=240V
NO OK
20mA CCID ↑ MODE In Tipo Ut
```

8. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.6.7. Situazioni anomale

1. Se lo strumento rileva una frequenza superiore al limite massimo (63Hz), non esegue il test e visualizza una videata come quella a lato

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = >63Hz
VL - PE=231V VL - N=234V
Freq fuori range
X1 30mA ↑ MODE In Tipo Ut
```

2. Se lo strumento rileva una tensione L - N o L - PE inferiore al limite minimo (100V), non esegue il test e visualizza una videata come quella a lato. Verificare che il sistema in prova sia alimentato

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 0.00 Hz
VL - PE <100 V VL - N= <100 V
Tensione <100V
X1 30mA ↑ MODE In Tipo Ut
```

3. Se lo strumento rileva una tensione L - N o L - PE superiore al limite massimo (265V), non esegue il test e visualizza una videata come quella a lato. Verificare il collegamento dei cavi di misura

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 50.00 Hz
VL PE= >265 V VL - N= >265 V
Tensione >265V
X1 30mA ↑ MODE In Tipo Ut
```

4. Se lo strumento rileva una tensione pericolosa sul conduttore PE fornisce la schermata di avvertenza mostrata a lato e blocca l'esecuzione dei test. Verificare l'efficienza del conduttore PE e dell'impianto di terra

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 0.00Hz
VL - PE= - - - V VL - N= - - - V
Tensione su PE
X1 30mA ↑ MODE In Tipo Ut
```

5. Se lo strumento rileva che i conduttori di fase L e neutro N sono invertiti, non esegue il test e viene visualizzata una schermata simile a quella riportata a lato. Ruotare la spina Shuko o controllare il collegamento dei cavi di misura

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 50.00Hz
VL - PE= 1 V VL - N= 231 V
Invertire L - N
X1 30mA ↑ MODE In Tipo Ut
```

6. Se lo strumento rileva che i conduttori di fase e PE sono invertiti, non esegue il test e viene visualizzata una schermata simile a quella riportata a lato. Verificare il collegamento dei cavi di misura

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 50.00Hz
VL - PE= 231 V VL - N= 1 V
Invertire L - PE
X1 30mA ↑ MODE In Tipo Ut
```

7. Se lo strumento rileva l'assenza del segnale al morsetto B3 (conduttore PE), fornisce la schermata di avviso mostrata a lato e blocca l'esecuzione dei test

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 50.00Hz
VL - PE= 114 V VL - N= 231 V
Manca PE
X1 30mA ↑ MODE In Tipo Ut
```

8. Se lo strumento rileva l'assenza del segnale al morsetto B4 (conduttore neutro), fornisce la schermata di avviso riportata a lato e blocca l'esecuzione dei test

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 50.00 Hz
VL - PE= 231V VL - N=115V
Manca N
X1 30mA ↑ MODE In Tipo Ut
```

9. Se lo strumento rileva l'assenza del segnale al morsetto B1 (conduttore di fase), fornisce la schermata di avviso mostrata a lato e blocca l'esecuzione delle prove

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 50.00 Hz
VL - PE= 0V VL - N=0V
Manca P
X1 30mA Tipo Ut
```

10. Se lo strumento rileva una tensione di contatto dannosa Ut (oltre il limite impostato di 25V o 50V) nel pre - test iniziale, fornisce la schermata di avviso mostrata a lato e blocca l'esecuzione delle prove. Verificare l'efficienza del conduttore PE e dell'impianto di terra

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 50.00 Hz
VL - PE= 231V VL - N=232V
Tensione contatto > Lim
X1 30mA ↑ MODE In Tipo Ut
```

11. Se l’RCD non interviene entro la durata massima del test, lo strumento emette un lungo segnale acustico che segnala l'esito negativo del test e quindi visualizza una videata simile a quella qui riportata a lato. Verificare che il tipo di RCD impostato corrisponda al tipo da testare

```
RCD 15/10 – 18:04
TT
T = >999 ms
Ut = 1 V
FREQ. = 50.00 Hz
VL - PE= 231V VL - N=232V
NO OK
X1 30mA ↑ MODE In Tipo Ut
```

12. Se lo strumento rileva nei terminali di ingresso un'impedenza esterna troppo elevata tale da non poter fornire la corrente nominale, fornisce la schermata di avviso mostrata a lato e blocca il test. Scollegare i possibili carichi a valle dell’RCD prima di eseguire il test

```
RCD 15/10 – 18:04
TT
T = - - - ms
Ut = - - - V
FREQ. = 50.00 Hz
VL - PE= 231V VL - N=232V
R esterna troppo alta
X1 30mA ↑ MODE In Tipo Ut
```

## 6.7. LOOP: IMPEDENZA LINEA / LOOP E RESISTENZA GLOBALE DI TERRA

Questa funzione viene svolta in conformità alla norma IEC/EN61557 - 3, BS7671 17th/18th edizione e consente di misurare l'impedenza di linea, l'impedenza dell'anello di guasto e la corrente di cortocircuito presunta.

**ATTENZIONE**
In funzione del sistema elettrico selezionato (TT, TN o IT) alcuni tipi di connessione e modi di funzionamento sono disabilitati dallo strumento (vedere Tabella 2).

I seguenti modi di funzionamento sono disponibili:

*   **L - N**: Misura standard (STD) dell'impedenza di linea tra il conduttore di fase e il conduttore di neutro e calcolo della corrente di cortocircuito da fase a neutro presunta per sistemi L - N - PE e L - L - PE
*   **L - L**: Misura standard (STD) dell'impedenza di linea tra due conduttori di fase e calcolo della corrente di cortocircuito da fase a neutro presunta per sistemi L - N - PE e L - L - PE
*   **L - PE**: Misura standard (STD) dell'impedenza dell'anello di guasto tra il conduttore di fase e il conduttore di terra e calcolo della corrente di cortocircuito fase - terra presunta per sistemi L - N - PE e L - L - PE
*   **Ra**: Impedenza di loop senza provocare l'intervento delle protezioni nei sistemi TN (vedere § 12.7) e Resistenza globale di terra (sistemi TT) con neutro (3 - fili) e senza neutro (2 - fili) (vedere § 12.8) per sistemi L - N - PE e L - L - PE
*   **L1 - L2**: Misura standard (STD) dell'impedenza di linea tra i due conduttori di fase L1 e L2 di un sistema Bifase e calcolo della corrente di cortocircuito presunta per sistemi L - L - PE
*   **L1 - PE**: Misura standard (STD) dell'impedenza dell'anello di guasto tra il conduttore di fase e il conduttore di terra di un sistema Bifase e calcolo della corrente di cortocircuito fase - terra presunta per sistemi L - L - PE

**ATTENZIONE**
Lo strumento esegue il controllo della tensione su PE confrontando la tensione sull’ingresso B4 e il potenziale di terra indotto sulle parti laterali dello stesso per mezzo della mano dell’operatore pertanto al fine di eseguire un controllo corretto della tensione su PE è necessario tenere impugnato lo strumento nella parte laterale destra o nella parte laterale sinistra.

**ATTENZIONE**
La misura dell'impedenza di linea o dell'impedenza del loop di guasto comporta la circolazione di una corrente massima secondo le specifiche tecniche dello strumento (vedere § 10.1). Ciò potrebbe causare l'intervento di eventuali protezioni magnetotermiche o differenziali a correnti di intervento inferiori.

Fig. 25: Test L - N/L1 - PE per sistemi Monofase/Bifase con spina Shuko
Fig. 26: Test L - N/L1 - PE per sistemi Monofase/Bifase con cavi e puntale remoto
Fig. 27: Test L - N/L1 - PE per sistemi Trifase con cavi singoli e puntale remoto
Fig. 28: Test L1 - L2 per sistemi Trifase con cavi singoli e puntale remoto
Fig. 29: Test L - PE/L1 - PE per sistemi Trifase (no N) mediante cavi singoli e puntale remoto
Fig. 30: Test L1 - PE per sistemi IT mediante cavi singoli e puntale remoto
Fig. 31: Test L1 - PE 2 fili per Sistemi Monofase/Bifase con spina Shuko
Fig. 32: Test 2 fili L1 - PE per sistemi Monofase/Bifase con cavi e puntale remoto
Fig. 33: Test L1 - PE a 2 fili per sistemi Trifase con cavi singoli e puntale remoto
Fig. 34: Test L1 - L2 a 3 fili per sistemi Bifase con cavi singoli e puntale remoto

### 6.7.1. Modi di prova

La protezione delle linee elettriche è parte essenziale di un progetto per garantirne la corretta funzionalità ed evitare danni a persone o cose. A tal fine, le linee guida di sicurezza impongono ai progettisti elettrici anche di progettare l'impianto elettrico in modo da raggiungere:

1.  La protezione dai cortocircuiti, ovvero il potere di interruzione del dispositivo di protezione non deve essere inferiore alla presunta corrente di cortocircuito nel punto in cui il dispositivo è installato
2.  La protezione dai contatti indiretti

Per verificare le condizioni sopra riportate lo strumento dispone delle seguenti funzioni:

*   **Ra (Ut)**: Verifica della protezione dai contatti indiretti – In base al tipo di sistema di distribuzione (TT, TN, IT) impostato dall'utente, lo strumento esegue la misura e verifica la condizione imposta dalle linee guida. Qualora venga raggiunto, lo strumento fornisce esito positivo (vedere § 12.6, § 12.8 e § 12.9)
*   **Br.Cap**: Verifica del potere di interruzione della protezione – Lo strumento rileva il valore dell'impedenza di linea a monte del punto di misura, calcola il valore massimo della corrente di cortocircuito e dà esito positivo se il valore è inferiore al limite impostato dall'utente (vedere § 12.5)
*   **TripT**: Controllo del coordinamento delle protezioni – Lo strumento rileva il valore dell'impedenza di linea a monte del punto di misura, calcola il valore minimo della corrente di cortocircuito e il corrispondente valore del tempo di intervento (t) del dispositivo di protezione e fornisce esito positivo se il valore è inferiore rispetto al limite impostato dall'utente (vedere § 12.10)
*   **STD**: Test generico

La tabella seguente riassume le possibili misure eseguibili a seconda del tipo di impianto (TT, TN e IT), delle modalità selezionate e delle relazioni che definiscono i valori limite

| Modo          | TT                                      | TN                                        | IT                                      |
| :------------ | :-------------------------------------- | :---------------------------------------- | :-------------------------------------- |
| **L - L**     |                                         |                                           |                                         |
| **L1 - L2**   |                                         |                                           |                                         |
| STD           | Nessun esito                            | Nessun esito                              | Nessun esito                            |
| Br.Cap        | Isc L - L max < BC                      | Isc L - L max < BC                        | Isc L - L max < BC                      |
|               | Isc L1 - L2 max < BC                    | Isc L1 - L2 max < BC                      | Isc L1 - L2 max < BC                    |
| TripT         | (IscL - Lmin 2P) → Tmax → Tmax < Tlim   | (IscL - L min 2P) → Tmax → Tmax < Tlim    | (IscL - Lmin 2F) → Tmax → Tmax< Tlim    |
|               | (IscL1 - L2min 2P) → Tmax → Tmax < Tlim | (IscL1 - L2 min 2P) → Tmax → Tmax < Tlim  | (IscL1 - L2min 2F) → Tmax → Tmax< Tlim  |
| Ut            |                                         |                                           |                                         |
| **L - N**     |                                         |                                           |                                         |
| STD           | Nessun esito                            | Nessun esito                              | Nessun esito                            |
| Br.Cap        | Isc L - N max < BC                      | Isc L - N max < BC                        | Isc L - N max < BC                      |
| TripT         | (Isc L - N min) → Tmax → Tmax < Tlim    | (Isc L - N min) → Tmax → Tmax < Tlim      | (Isc L - N min) → Tmax → Tmax < Tlim    |
| Ut            |                                         |                                           |                                         |
| **L - PE**    |                                         |                                           |                                         |
| **L1 - PE**   |                                         |                                           |                                         |
| STD           | Nessun esito                            |                                           |                                         |
| Br.Cap        | Isc L - PE max< BC                      | Isc L - PE max< BC                        |                                         |
|               | Isc L1 - PE max< BC                     | Isc L1 - PE max< BC                       |                                         |
| TripT         | (Ipfc L - PE min) → Tmax → Tmax < Tlim  | (Ipfc L - PE min) → Tmax → Tmax < Tlim    |                                         |
|               | (Ipfc L1 - PE min) → Tmax → Tmax < Tlim | (Ipfc L1 - PE min) → Tmax → Tmax < Tlim   |                                         |
| Ut            |                                         | ZL - PE < ZLimt (UK)                      | Utmeas < Utlim                          |
|               |                                         | ZL1 - PE < ZLimt (USA)                    |                                         |
| Ra            | Utlim/Ra meas = Isc L - PE MIN > Idn (RCD) | ZLPEmis < ZLIM (UK, AUS/NZ)               |                                         |
|               |                                         | ZL1PEmis < ZLIM (USA)                     |                                         |
| **2Fili**     | Ra mis x Idn < Ut lim (altre Nazioni)   | Ra mis x Idn < Ut lim (altre Nazioni)     |                                         |
| Ut            |                                         |                                           |                                         |
| **3Fili**     | ZLPEmeas < ZLIM (UK, AUS/NZ)            | ZLPEmeas < ZLIM (UK, AUS/NZ)              |                                         |
|               | ZL1PEmeas < ZLIM (USA)                  | ZL1PEmeas < ZLIM (USA)                    |                                         |
|               | Ra meas x Idn < Ut lim (altre Nazioni)  | Ra meas x Idn < Ut lim (altre Nazioni)    |                                         |

Tabella 2: Condizioni di esito OK in funzione dei vari parametri di prova

In cui:

*   **Cella vuota**: Modo non disponibile per quella particolare combinazione di sistema elettrico
*   **Isc L - L_Min2P**: Corrente di cortocircuito presunta minima bifase L - L (sistema L - N - PE)
*   **Isc L1 - L2_Min2P**: Corrente di cortocircuito presunta minima bifase L1 - L2 (sistema L - L - PE)
*   **Isc L - N_Max**: Corrente di cortocircuito presunta massima L - N (sistema L - N - PE)
*   **Isc L - N_Min**: Corrente di cortocircuito presunta minima L - N (sistema L - N - PE)
*   **Isc L - PE_Max**: Corrente di cortocircuito presunta massima L - PE (sistema L - N - PE)
*   **Isc L1 - PE_Max**: Corrente di cortocircuito presunta massima bifase L1 - PE (sistema L - L - PE)
*   **Isc L - PE_Min**: Corrente di cortocircuito presunta minima L - PE (sistema L - N - PE)
*   **Isc L1 - PE_Min**: Corrente di cortocircuito presunta minima bifase L1 - PE (sistema L - L - PE)
*   **BC**: Potere di interruzione del dispositivo di protezione - kA)
*   **Z Lim**: Massimo limite consentito dell'impedenza in base al tipo di protezione
*   **Tmax**: Tempo massimo di intervento del dispositivo di protezione
*   **Tlim**: Tempo limite di estinzione del guasto da parte della protezione impostata dall'utente
*   **Ut meas**: Tensione di contatto misurata
*   **Ut lim**: Tensione di contatto limite (25V o 50V)
*   **Ra meas**: Resistenza globale di terra misurata
*   **Idn**: Corrente di intervento nominale del dispositivo di protezione RCD
*   **Ipsc**: Corrente di cortocircuito presunta
*   **Ipfc**: Corrente di guasto presunta

### 6.7.2. Calibrazione puntali di misura (ZEROLOOP)

Per ottenere risultati migliori, si raccomanda di eseguire la calibrazione preliminare dei cavi di prova o del cavo con spina Shuko utilizzando l'accessorio ZEROLOOP prima di eseguire il test. In questo modo lo strumento sottrae automaticamente la resistenza dei cavi di test, fornendo il risultato effettivo a display. A titolo di esempio, la procedura per la modalità LOOP STD generica è descritta di seguito ed è estendibile a tutti gli altri casi.

1. Premere il tasto **MENU**, spostare il cursore su **LOOP** nel menu principale tramite i tasti freccia (, ) e confermare con **ENTER**. Selezionare la funzione “CAL”. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato

```
LOOP 15/10 – 18:04
TN
RL = - - - 
RN = - - - 
RPE = - - - 
FREQ. = 0.00Hz
VL - PE=0V VL - N=0V
CAL FUN Z
```

2. Inserire l'accessorio metallico ZEROLOOP nei tre connettori a banana dei cavi di misura (L - N - PE) o nei connettori metallici della spina Shuko (in modo diverso in base al paese di utilizzo) come mostrato nella seguente Tabella 3

| Cavi misura | Spina SHUKO | Spina UK | Spina ITA | Spina SWI | Spina DEN | Spina AUS/CHN | Spina USA |
| :---------- | :---------- | :------- | :-------- | :-------- | :-------- | :------------ | :-------- |
|             |             |          |           |           |           |               |           |

Tabella 3: Collegamento accessorio ZEROLOOP

3. Premere il tasto **GO/STOP** per avviare la calibrazione. Nei campi RL, RN e RPE è mostrata per pochi secondi la resistenza dei puntali. Questo valore sarà sottratto automaticamente dallo strumento alla fine della misura di Loop.
Lo strumento visualizza il simbolo “ ” ad indicare l’esito positivo della calibrazione dei cavi di misura (Rcal <1 ) e sul display compare la videata a lato
Tornare alla videata principale di misura. Notare il simbolo “ ” che indica la corretta calibrazione dei puntali e procedere con le misure descritte nei paragrafi successivi.

```
LOOP 15/10 – 18:04
TN
RL = 0.051 
RN = 0.013 
RPE = 0.068 
FREQ. = 0.00Hz
VL - PE=0V VL - N=0V
Calibrazione 5.1.3 OK
CAL FUN Z
```

4. Il valore della resistenza dei puntali/spina Shuko viene mantenuto dallo strumento fino all'operazione di reset eseguita dall'utente (ad esempio per l'inserimento di cavi di diversa lunghezza).
Per eseguire il reset del valore di calibrazione salvato, rimuovere l'accessorio ZEROLOOP e premere il tasto **GO/STOP**. Il simbolo “ ” è rimosso e la videata a lato compare sul display

```
LOOP 15/10 – 18:04
TN
RL = - - - 
RN = - - - 
RPE = - - - 
FREQ. = 0.00Hz
VL - PE=0V VL - N=0V
Reset Calib.
CAL FUN Z
```

### 6.7.3. Modo STD – Test generico

Questa modalità esegue la misura dell'impedenza e il calcolo della corrente di cortocircuito presunta senza applicare alcuna valutazione. Pertanto, al termine della prova, lo strumento non fornisce alcun esito.

1. Premere il tasto **MENU**, spostare il cursore su **LOOP** nel menu principale tramite i tasti freccia (, ) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato in caso di sistema elettrico Monofase L - N - PE selezionato (vedere § 5.1.3). Per sistemi Bifase L - L - PE le tensioni indicate cambiano in VL1 - PE e VL1 - L2. Selezionare il paese “Europa” (vedere § 5.1.2), le opzioni “TT, TN o IT”, “25 o 50V”, “50Hz o 60Hz”, il sistema “L - N - PE” o “L - L - PE” e la tensione di riferimento nelle impostazioni generali dello strumento (vedere § 5.1.3).

```
LOOP 15/10 – 18:04
TN
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 0.00Hz
VL - PE=0V VL - N=0V
L - PE STD FUNZ MODE
```

2. Usare i tasti ,  per selezionare il parametro da modificare e i tasti ,  per modificare il valore del parametro:
    *   **FUNZ** → il tasto virtuale permette di impostare la modalità di misura dello strumento, che può essere: L - N, L - L o L - PE (sistemi Monofase/Trifase) oppure L1 - PE, L1 - L2 (sistemi Bifase)
    *   **MODE** → il tasto virtuale permette di impostare la modalità di funzionamento dello strumento. Selezionare l'opzione STD

3. Se possibile, scollegare tutti i carichi collegati a valle del punto misurato in quanto l'impedenza di queste utenze potrebbe falsare i risultati del test. Eseguire la calibrazione preliminare dei puntali come descritto al § 6.7.2.

4. Inserire i connettori verde, blu e nero del cavo shuko a tre pin nei corrispondenti conduttori di ingresso B3, B4 e B1 dello strumento. In alternativa, utilizzare i singoli cavi e applicare le relative clip a coccodrillo alle estremità libere dei cavi. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel cavo di ingresso B1. Collegare la spina Shuko, i terminali a coccodrillo o il puntale remoto alla rete elettrica in accordo alle Fig. 25, Fig. 26, Fig. 27, Fig. 28, Fig. 29, Fig. 31, Fig. 32, Fig. 33 o Fig. 34.

5. Notare la presenza dei corretti valori di tensione tra L - N e L - PE corrispondenti alle selezioni effettuate in fase iniziale come mostrato nella videata a lato.

```
LOOP 15/10 – 18:04
TN
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE=231V VL - N=232V
L - PE STD FUNZ MODE
```

6. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizierà la misura e sul display apparirà il messaggio “Misura…”
Durante tutta questa fase non scollegare i cavi di misura dello strumento dal sistema in prova. La seguente videata appare a display

```
LOOP 15/10 – 18:04
TN
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE=231V VL - N=232V
Misura …
L - PE STD FUNZ MODE
```

7. Nella parte alta del display è mostrato il valore della corrente di cortocircuito presunta (Ipfc), mentre nella parte inferiore è mostrata l'impedenza Z L - PE di Linea/Loop.
La corrente di cortocircuito presunta standard (Std) (Isc) viene calcolata utilizzando le seguenti formule:
Z MEAS = Impedenza Loop L - L,L - N,L - PE misurata
U NOM = tensione nominale (in funzione del sistema)
$$I_{SCL-PE} = \frac{U_{NOM}}{Z_{MEAS}}$$
$$I_{SCL-N} = \frac{U_{NOM}}{Z_{MEAS}}$$
$$I_{SCL-L} = \frac{\sqrt{3} U_{NOM}}{Z_{MEAS}}$$

```
RCD 15/10 – 18:04
TN
Ipfc = 163 A
ZL - PE = 1.41 
FREQ. = 50.00Hz
VL - PE=231V VL - N=232V
L - PE STD FUNZ MODE
```

8. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.7.4. Modo Br.Cap – Verifica potere di interruzione del dispositivo di protezione

1. Premere il tasto **MENU**, spostare il cursore su **LOOP** nel menu principale tramite i tasti freccia (, ) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato in caso di sistema elettrico Monofase L - N - PE selezionato (vedere § 5.1.3). Per sistemi Bifase L - L - PE le tensioni indicate cambiano in VL1 - PE e VL1 - L2. Selezionare il paese “Europa” (vedere § 5.1.2), le opzioni “TT, TN o IT”, “25 o 50V”, “50Hz o 60Hz” e la tensione di riferimento nelle impostazioni generali dello strumento (vedere § 5.1.3).

```
LOOP 15/10 – 18:04
TN max
Ipsc = - - - A
ZL - L = - - - 
FREQ. = 50.00Hz
VL - PE=0V VL - L=0V
L - L Br.Cap 15kA FUNZ MODE Lim
```

2. Usare i tasti ,  per selezionare il parametro da modificare e i tasti ,  per modificare il valore del parametro:
    *   **FUNZ** → il tasto virtuale permette di impostare la modalità di misura dello strumento, che può essere: L - N, L - L o L - PE (sistemi Monofase/Trifase) oppure L1 - PE, L1 - L2 (sistemi Bifase)
    *   **MODE** → il tasto virtuale permette di impostare la modalità di funzionamento dello strumento. Selezionare l'opzione Br.Cap
    *   **Lim** → il tasto virtuale permette di impostare la massima corrente di intervento espressa in "kA" che la protezione deve interrompere nel campo: 0.1kA ÷ 999kA

3. Se possibile, scollegare tutti i carichi collegati a valle del punto misurato in quanto l'impedenza di queste utenze potrebbe falsare i risultati del test. Eseguire la calibrazione preliminare dei puntali come descritto al § 6.7.2.

4. Inserire i connettori verde, blu e nero del cavo shuko a tre pin nei corrispondenti conduttori di ingresso B3, B4 e B1 dello strumento. In alternativa, utilizzare i singoli cavi e applicare le relative clip a coccodrillo alle estremità libere dei cavi. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel cavo di ingresso B1. Collegare la spina Shuko, i terminali a coccodrillo o il puntale remoto alla rete elettrica in accordo alle Fig. 25, Fig. 26, Fig. 27, Fig. 28, Fig. 29, Fig. 31, Fig. 32, Fig. 33 o Fig. 34.

5. Notare la presenza dei corretti valori di tensione tra L - L e L - PE corrispondenti alle selezioni effettuate in fase iniziale come mostrato nella videata a lato

```
LOOP 15/10 – 18:04
TN max
Ipsc = - - - A
ZL - L = - - - 
FREQ. = 50.00Hz
VL - PE=223V VL - L=387V
L - L Br.Cap 15kA FUNZ MODE Lim
```

6. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizierà la misura e sul display apparirà il messaggio “Misura…”.
Durante tutta questa fase non scollegare i cavi di misura dello strumento dal sistema in prova. La seguente videata appare a display

```
LOOP 15/10 – 18:04
TN max
Ipsc = - - - A
ZL - L = - - - 
FREQ. = 50.00Hz
VL - PE=223V VL - L=387V
Misura …
L - L Br.Cap 15kA FUNZ MODE Lim
```

7. In caso di risultato positivo (IpscMAX<Lim) viene visualizzato a display il messaggio di esito “OK”

```
LOOP 15/10 – 18:04
TN max
Ipsc = 3019 A
ZL - L = 0.16 
FREQ. = 50.00Hz
VL - PE=223V VL - L=387V
OK
L - L Br.Cap 6.0 kA FUNZ MODE Lim
```

8. In caso di risultato negativo (IpscMAX>Lim) viene visualizzato a display il messaggio di esito “NO OK”

```
LOOP 15/10 – 18:04
TN max
Ipsc = 7236 A
ZL - L = 0.07 
FREQ. = 50.00Hz
VL - PE=223V VL - L=387V
NO OK
L - L Br.Cap 6.0kA FUNZ MODE Lim
```

9. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.7.5. TripT – Verifica del coordinamento delle protezioni

1. Premere il tasto **MENU**, spostare il cursore su **LOOP** nel menu principale tramite i tasti freccia (, ) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato in caso di sistema elettrico Monofase L - N - PE selezionato (vedere § 5.1.3). Per sistemi Bifase L - L - PE le tensioni indicate cambiano in VL1 - PE e VL1 - L2. Selezionare il paese “Europa” (vedere § 5.1.2), le opzioni “TT, TN o IT”, “25 o 50V”, “50Hz o 60Hz” e la tensione di riferimento nelle impostazioni generali dello strumento (vedere § 5.1.3).
NOTA: per paesi diversi da "Europa" i riferimenti su MCB e Fusibile disponibili possono cambiare

```
LOOP 15/10 – 18:04
TN min
Ipsc = - - - A
ZL - L = - - - 
FREQ. = 0.00Hz
VL - PE=0V VL - L=0V
L - L TripT 16A 0.2s FUNZ MODE MCB - C Tempo
```

2. Usare i tasti ,  per selezionare il parametro da modificare e i tasti ,  per modificare il valore del parametro:
    *   **FUNZ** → il tasto virtuale permette di impostare la modalità di misura dello strumento, che può essere: L - N, L - L o L - PE (sistemi Monofase/Trifase) oppure L1 - PE, L1 - L2 (sistemi Bifase)
    *   **MODE** → il tasto virtuale permette di impostare la modalità di funzionamento dello strumento. Selezionare l'opzione TripT
    *   **Tipo di protezione** → il tasto virtuale permette di impostare il tipo di protezione (Fusibile di tipo gG, aM o magnetotermico MCB curve B, C, D, K) e le rispettive correnti nominali considerando i seguenti valori disponibili:
        *   MCB curva B → 3A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A ,160A,200A
        *   MCB curva C → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 50A, 63A, 80A,100A,125A,160A,200A
        *   MCB curve D, K → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
        *   Fusibile gG → 2A, 4A, 6A, 8A, 10A, 12A, 13A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A, 800A, 1000A, 1250A
        *   Fusibile aM → 2A, 4A, 6A, 10A, 12A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A
    *   **Tempo** → il tasto virtuale permette di impostare il tempo di intervento della protezione tra le opzioni: 0.1s, 0.2s, 0.4s, 1s, 5s
    premere il tasto **SALVA** per salvare i parametri selezionati e tornare alla videata di misura

3. Se possibile, scollegare tutti i carichi collegati a valle del punto misurato in quanto l'impedenza di queste utenze potrebbe falsare i risultati del test. Eseguire la calibrazione preliminare dei puntali come descritto al § 6.7.2.

4. Inserire i connettori verde, blu e nero del cavo shuko a tre pin nei corrispondenti conduttori di ingresso B3, B4 e B1 dello strumento. In alternativa, utilizzare i singoli cavi e applicare le relative clip a coccodrillo alle estremità libere dei cavi. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel cavo di ingresso B1. Collegare la spina Shuko, i terminali a coccodrillo o il puntale remoto alla rete elettrica in accordo alle Fig. 25, Fig. 26, Fig. 27, Fig. 28 Fig. 29, Fig. 31, Fig. 32, Fig. 33 o Fig. 34.

5. Notare la presenza dei corretti valori di tensione tra L - L e L - PE corrispondenti alle selezioni effettuate in fase iniziale come mostrato nella videata a lato

```
LOOP 15/10 – 18:04
TN min
Ipsc = - - - A
ZL - L = - - - 
FREQ. = 50.00Hz
VL - PE= 223 V VL - L=387V
L - L TripT 16 A 0.2 s FUNZ MODE MCB - C Tempo
```

6. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizierà la misura e sul display apparirà il messaggio “Misura…”.
Durante tutta questa fase non scollegare i cavi di misura dello strumento dal sistema in prova. La seguente videata appare a display

```
LOOP 15/10 – 18:04
TN min
Ipsc = - - - A
ZL - L = - - - 
FREQ. = 50.00Hz
VL - PE=223V VL - L=387V
Misura …
L - L TripT 16A 0.2s FUNZ MODE MCB - C Tempo
```

7. In caso di esito positivo (corrente di cortocircuito minima interrotta dal dispositivo di protezione entro il tempo indicato dalle selezioni effettuate), lo strumento visualizza il messaggio “OK” e la videata a lato

```
LOOP 15/10 – 18:04
TN min
Ipsc = 212 A
ZL - L = 1.03 
FREQ. = 50.00Hz
VL - PE=223V VL - L=387V
OK
L - L TripT 16A 0.2s FUNZ MODE MCB - C Tempo
```

8. In caso di esito negativo (corrente di cortocircuito minima NON interrotta dal dispositivo di protezione entro il tempo indicato dalle selezioni effettuate), lo strumento visualizza il messaggio “NON OK” e la videata a lato

```
LOOP 15/10 – 18:04
TN min
Ipsc = 1681 A
ZL - L = 0.13 
FREQ. = 50.00Hz
VL - PE=223V VL - L=387V
NON OK
L - L TripT 16A 0.2s FUNZ MODE MCB - C Tempo
```

9. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.7.6. Test Ra 2-fili – Verifica della protezione dai contatti indiretti

1. Premere il tasto **MENU**, spostare il cursore su **LOOP** nel menu principale tramite i tasti freccia (, ) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato in caso di sistema elettrico Monofase L - N - PE selezionato (vedere § 5.1.3). Per sistemi Bifase L - L - PE le tensioni indicate cambiano in VL1 - PE e VL1 - L2. Selezionare il paese “Europa” (vedere § 5.1.2), le opzioni “TN”, “25 o 50V”, “50Hz o 60Hz” e la tensione di riferimento nelle impostazioni generali dello strumento (vedere § 5.1.3). NOTA: per paesi diversi da "Europa" i riferimenti su MCB e Fusibile disponibili possono cambiare

```
LOOP 15/10 – 18:04
TN min
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 0.00Hz
VL - PE=0V
Ra 2Fili 16A 0.2s FUNZ MODE MCB - C Tempo
```

2. Usare i tasti ,  per selezionare il parametro da modificare e i tasti ,  per modificare il valore del parametro:
    *   **FUNZ** → il tasto virtuale permette di impostare la modalità di misura dello strumento, che può essere: Ra
    *   **MODE** → il tasto virtuale permette di impostare la modalità di funzionamento dello strumento. Selezionare l'opzione 2 Fili
    *   **Tipo di protezione** → il tasto virtuale permette di impostare il tipo di protezione (Fusibile di tipo gG, aM o magnetotermico MCB curve B, C, D, K) e le rispettive correnti nominali considerando i seguenti valori disponibili:
        *   MCB curva B → 3A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
        *   MCB curva C → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 50A, 63A, 80A,100A,125A,160A,200A
        *   MCB curve D, K → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
        *   Fusibile gG → 2A, 4A, 6A, 8A, 10A, 12A, 13A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A, 800A, 1000A, 1250A
        *   Fusibile aM → 2A, 4A, 6A, 10A, 12A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A
    *   **Tempo** → il tasto virtuale permette di impostare il tempo di intervento della protezione tra le opzioni: 0.1s, 0.2s, 0.4s, 1s, 5s
    premere il tasto **SALVA** per salvare i parametri selezionati e tornare alla videata di misura

3. Se possibile, scollegare tutti i carichi collegati a valle del punto misurato in quanto l'impedenza di queste utenze potrebbe falsare i risultati del test. Eseguire la calibrazione preliminare dei puntali come descritto al § 6.7.2.

4. Inserire i connettori verde, blu e nero del cavo shuko a tre pin nei corrispondenti conduttori di ingresso B3, B4 e B1 dello strumento. In alternativa, utilizzare i singoli cavi e applicare le relative clip a coccodrillo alle estremità libere dei cavi. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel cavo di ingresso B1. Collegare la spina Shuko, i terminali a coccodrillo o il puntale remoto alla rete elettrica in accordo alle Fig. 31, Fig. 32 o Fig. 33.

5. Notare la presenza dei corretti valori di tensione tra L - PE corrispondente alle selezioni effettuate in fase iniziale come mostrato nella videata a lato

```
LOOP 15/10 – 18:04
TN min
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE=223V
Ra 2 Fili 16A 0.2s FUNZ MODE MCB - C Tempo
```

6. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizierà la misura e sul display apparirà il messaggio “Misura…”.
Durante tutta questa fase non scollegare i cavi di misura dello strumento dal sistema in prova. La seguente videata appare a display

```
LOOP 15/10 – 18:04
TN min
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE=223V
Misura …
Ra 2 Fili 16A 0.2s FUNZ MODE MCB - C Tempo
```

7. In caso di esito positivo (Z L - PE ≤ impedenza limite relativa al dispositivo di protezione entro il tempo specificato - vedere § 12.10), lo strumento visualizza il messaggio “OK” e la videata a lato

```
LOOP 15/10 – 18:04
TN min
Ipfc = 1213 A
ZL - PE = 0.18 
FREQ. = 50.00Hz
VL - PE=223V
OK
Ra 2 Fili 16A 0.2s FUNZ MODE MCB - C Tempo
```

8. In caso di esito negativo (Z L - PE > impedenza limite relativa al dispositivo di protezione entro il tempo specificato - vedere § 12.10), lo strumento visualizza il messaggio “NO OK” e la videata a lato

```
LOOP 15/10 – 18:04
TN min
Ipfc = 88 A
ZL - PE = 2 . 0 8 
FREQ. = 50.00Hz
VL - PE=223V
NO OK
Ra 2 Fili 16A 0.2s FUNZ MODE MCB - C Tempo
```

9. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.7.7. Test Ra 3-fili - Verifica della protezione dai contatti indiretti

1. Premere il tasto **MENU**, spostare il cursore su **LOOP** nel menu principale tramite i tasti freccia (, ) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato in caso di sistema elettrico Monofase L - N - PE selezionato (vedere § 5.1.3). Per sistemi Bifase L - L - PE le tensioni indicate cambiano in VL1 - PE e VL1 - L2. Selezionare il paese “Europa” (vedere § 5.1.2), le opzioni “TN”, “25 o 50V”, “50Hz o 60Hz” e la tensione di riferimento nelle impostazioni generali dello strumento (vedere § 5.1.3). NOTA: per paesi diversi da "Europa" i riferimenti su MCB e Fusibile disponibili possono cambiare

```
LOOP 15/10 – 18:04
TN
Isc = - - - A ZL - N = - - - 
Ifc = - - - A ZL - PE = - - - 
FREQ = 0.00Hz
VL - N = 0V VL - PE = 0V
Ra 3Fili 16A 0.2s FUNZ MODE MCB - C Tempo
```

2. Usare i tasti ,  per selezionare il parametro da modificare e i tasti ,  per modificare il valore del parametro
    *   **FUNZ** → il tasto virtuale permette di impostare la modalità di misura dello strumento, che può essere: Ra
    *   **MODE** → il tasto virtuale permette di impostare la modalità di funzionamento dello strumento. Selezionare l'opzione 3 Fili
    *   **Tipo di protezione** → il tasto virtuale permette di impostare il tipo di protezione (Fusibile di tipo gG, aM o magnetotermico MCB curve B, C, D, K) e le rispettive correnti nominali considerando i seguenti valori disponibili:
        *   MCB curva B → 3A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
        *   MCB curva C → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 50A, 63A, 80A,100A,125A,160A,200A
        *   MCB curve D, K → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
        *   Fusibile gG → 2A, 4A, 6A, 8A, 10A, 12A, 13A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A, 800A, 1000A, 1250A
        *   Fusibile aM → 2A, 4A, 6A, 10A, 12A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A
    *   **Tempo** → il tasto virtuale permette di impostare il tempo di intervento della protezione tra le opzioni: 0.1s, 0.2s, 0.4s, 1s, 5s
    premere il tasto **SALVA** per salvare i parametri selezionati e tornare alla videata di misura

3. Se possibile, scollegare tutti i carichi collegati a valle del punto misurato in quanto l'impedenza di queste utenze potrebbe falsare i risultati del test. Eseguire la calibrazione preliminare dei puntali come descritto al § 6.7.2.

4. Inserire i connettori verde, blu e nero del cavo shuko a tre pin nei corrispondenti conduttori di ingresso B3, B4 e B1 dello strumento. In alternativa, utilizzare i singoli cavi e applicare le relative clip a coccodrillo alle estremità libere dei cavi. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel cavo di ingresso B1. Collegare la spina Shuko, i terminali a coccodrillo o il puntale remoto alla rete elettrica in accordo alle Fig. 25, Fig. 26, Fig. 27, Fig. 28 o Fig. 29.

5. Notare la presenza dei corretti valori di tensione tra L - PE e L - N corrispondenti alle selezioni effettuate in fase iniziale come mostrato nella videata a lato

```
AUTO 15/10 – 18:04
TN
Isc = - - - A ZL - N = - - - 
Ifc = - - - A ZL - PE = - - - 
FREQ = 50.00Hz
VL - N = 232V VL - PE = 231V
Ra 3 Fili 16A 0.2s FUNZ MODE MCB - C Tempo
```

6. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizierà la misura e sul display apparirà il messaggio “Misura…”.
Durante tutta questa fase non scollegare i cavi di misura dello strumento dal sistema in prova. La seguente videata appare a display

```
AUTO 15/10 – 18:04
TN
Isc = - - - A ZL - N = - - - 
Ifc = - - - A ZL - PE = - - - 
FREQ = 50.00Hz
VL - N = 232V VL - PE = 231V
Misura ...
Ra 3 Fili 16A 0.2s FUNZ MODE MCB - C Tempo
```

7. In caso di esito positivo (Z L - PE ≤ impedenza limite relativa al dispositivo di protezione entro il tempo specificato - vedere § 12.10), lo strumento visualizza il messaggio “OK” e la videata a lato

```
AUTO 15/10 – 18:04
TN
Isc = 1365 A ZL - N = 0.16 
Ifc = 1213 A ZL - PE = 0.18 
FREQ = 50.00Hz
VL - N = 232V VL - PE = 231V
OK
Ra 3 Fili 16A 0.2s FUNZ MODE MCB - C Tempo
```

8. In caso di esito negativo (Z L - PE > impedenza limite relativa al dispositivo di protezione entro il tempo specificato - vedere § 12.10), lo strumento visualizza il messaggio “NON OK” e la videata a lato

```
AUTO 15/10 – 18:04
TN
Isc = 89 A ZL - N = 2.06 
Ifc = 88 A ZL - PE = 2.08 
FREQ = 50.00Hz
VL - N = 232V VL - PE = 231V
NON OK
Ra 3 Fili 16A 0.2s FUNZ MODE MCB - C Tempo
```

9. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.7.8. Verifica della protezione contro contatti indiretti (sistemi IT)

1. Premere il tasto **MENU**, spostare il cursore su **LOOP** nel menu principale tramite i tasti freccia (, ) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato in caso di sistema elettrico Monofase L - N - PE selezionato (vedere § 5.1.3). Per sistemi Bifase L - L - PE le tensioni indicate cambiano in VL1 - PE e VL1 - L2. Selezionare il paese “Europa” (vedere § 5.1.2), le opzioni “IT”, “25 o 50V”, “50Hz o 60Hz” e la tensione di riferimento nelle impostazioni generali dello strumento (vedere § 5.1.3).

```
LOOP 15/10 – 18:04
IT
Ipfc = - - - mA
Ut = - - - V
FREQ. = 0.00Hz
VL - PE=0V VL - N=0V
L - PE Ut FUNZ MODE
```

2. Usare i tasti ,  per selezionare il parametro da modificare e i tasti ,  per modificare il valore del parametro:
    *   **FUNZ** → il tasto virtuale permette di impostare la modalità di misura dello strumento, che può essere: L - PE (sistemi Monofase/Trifase) oppure L1 - PE (sistemi Bifase)
    *   **MODE** → il tasto virtuale permette di impostare la tensione di contatto limite Ut (vedere § 5.1.3)
    premere il tasto **SALVA** per salvare i parametri e tornare alla videata di misura

3. Se possibile, scollegare tutti i carichi collegati a valle del punto misurato in quanto l'impedenza di queste utenze potrebbe falsare i risultati del test. Eseguire la calibrazione preliminare dei puntali come descritto al § 6.7.2.

4. Inserire i connettori verde, blu e nero del cavo shuko a tre pin nei corrispondenti conduttori di ingresso B3, B4 e B1 dello strumento. In alternativa, utilizzare i singoli cavi e applicare le relative clip a coccodrillo alle estremità libere dei cavi. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel cavo di ingresso B1. Collegare la spina Shuko, i terminali a coccodrillo o il puntale remoto alla rete elettrica in accordo alla Fig. 30.

5. Notare la presenza dei corretti valori di tensione tra L - PE e L - N come mostrato nella videata a lato

```
LOOP 15/10 – 18:04
IT
Ipfc = - - - mA
Ut = - - - V
FREQ. = 50.00Hz
VL - PE=232V VL - N=234V
L - PE Ut FUNZ MODE
```

6. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizierà la misura e sul display apparirà il messaggio “Misura…”.
Durante tutta questa fase non scollegare i cavi di misura dello strumento dal sistema in prova. La seguente videata appare a display

```
LOOP 15/10 – 18:04
IT
Ipfc = - - - mA
Ut = - - - V
FREQ. = 50.00Hz
VL - PE=232V VL - N=234V
Misura …
L - PE Ut FUNZ MODE
```

7. In caso di esito positivo (tensione di contatto nel punto <50V o <25V), lo strumento visualizza il messaggio “OK” e la videata a lato che contiene il valore della corrente di primo guasto misurata, espressa in mA (vedere § 12.9)

```
LOOP 15/10 – 18:04
IT
Ipfc = 83 mA
Ut = 1 V
FREQ. = 50.00Hz
VL - PE=232V VL - N=234V
OK
L - PE Ut FUNZ MODE
```

8. In caso di esito negativo (tensione di contatto nel punto >50V o >25V), lo strumento visualizza il messaggio “NO OK” e la videata a lato

```
LOOP 15/10 – 18:04
IT
Ipfc = >999 mA
Ut = >50 V
FREQ. = 50.00Hz
VL - PE=232V VL - N=234V
NO OK
L - PE Ut FUNZ MODE
```

9. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.7.9. Verifica della protezione contro contatti indiretti (sistemi TT)

1. Premere il tasto **MENU**, spostare il cursore su **LOOP** nel menu principale tramite i tasti freccia (, ) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato in caso di sistema elettrico Monofase L - N - PE selezionato (vedere § 5.1.3). Per sistemi Bifase L - L - PE le tensioni indicate cambiano in VL1 - PE e VL1 - L2. Selezionare il paese “Europa” (vedere § 5.1.2), le opzioni “TT”, “25 o 50V”, “50Hz o 60Hz” e la tensione di riferimento nelle impostazioni generali dello strumento (vedere § 5.1.3).

```
LOOP 15/10 – 18:04
TT
RA = - - - 
Ut = - - - V
FREQ. = 0.00Hz
VL - PE=0V
Ra 2 Fili 30mA FUNZ MODE In
```

2. Usare i tasti ,  per selezionare il parametro da modificare e i tasti ,  per modificare il valore del parametro:
    *   **FUNZ** → il tasto virtuale permette di impostare la modalità di misura dello strumento, che può essere Ra
    *   **MODE** → Modo 2 - Wire fisso
    *   **In** → Il tasto virtuale consente di impostare il valore nominale della corrente di intervento dell'RCD, che può essere: 6mA, 10mA, 30mA, 100mA, 300mA, 500mA, 650mA, 1000mA
    premere il tasto **SALVA** per salvare i parametri selezionati e tornare alla videata di misura

3. Se possibile, scollegare tutti i carichi collegati a valle del punto misurato in quanto l'impedenza di queste utenze potrebbe falsare i risultati del test. Eseguire la calibrazione preliminare dei puntali come descritto al § 6.7.2.

4. Inserire i connettori verde, blu e nero del cavo shuko a tre pin nei corrispondenti conduttori di ingresso B3, B4 e B1 dello strumento. In alternativa, utilizzare i singoli cavi e applicare le relative clip a coccodrillo alle estremità libere dei cavi. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel cavo di ingresso B1. Collegare la spina Shuko, i terminali a coccodrillo o il puntale remoto alla rete elettrica in accordo alle Fig. 31, Fig. 32 o Fig. 33.

5. Notare la presenza dei corretti valori di tensione tra L - PE come mostrato nella videata a lato

```
LOOP 15/10 – 18:04
TT
RA = - - - 
Ut = - - - V
FREQ. = 50.00Hz
VL - PE=232V
Ra 2 Fili 30mA FUNZ MODE In
```

6. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizierà la misura e sul display apparirà il messaggio “Misura…”.
Durante tutta questa fase non scollegare i cavi di misura dello strumento dal sistema in prova. La seguente videata appare a display

```
LOOP 15/10 – 18:04
TT
RA = - - - 
Ut = - - - V
FREQ. = 50.00Hz
VL - PE=232V
Misura …
Ra 2 Fili 30mA FUNZ MODE In
```

7. In caso di esito positivo (resistenza globale di terra RA <(Utlim / In), lo strumento visualizza il messaggio “OK” e la videata a lato che contiene il valore della tensione di contatto nel display secondario

```
LOOP 15/10 – 18:04
TT
RA = 346 
Ut = 10.4 V
FREQ. = 50.00Hz
VL - PE=232V
OK
Ra 2 Fili 30mA FUNZ MODE In
```

8. In caso di esito positivo (resistenza globale di terra RA >(Utlim / In), lo strumento visualizza il messaggio “NO OK” e la videata a lato che contiene il valore della tensione di contatto nel display secondario

```
LOOP 15/10 – 18:04
TT
RA = 1765 
Ut = >50 V
FREQ. = 50.00Hz
VL - PE=232V
NO OK
Ra 2 Fili 30mA FUNZ MODE In
```

9. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.7.10. Verifica della protezione contro contatti indiretti (sistemi TN)

1. Premere il tasto **MENU**, spostare il cursore su **LOOP** nel menu principale tramite i tasti freccia (, ) e confermare con **ENTER**. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato in caso di sistema elettrico Monofase L - N - PE selezionato (vedere § 5.1.3). Per sistemi Bifase L - L - PE le tensioni indicate cambiano in VL1 - PE e VL1 - L2. Selezionare il paese “Europa” (vedere § 5.1.2), le opzioni “TN”, “25 o 50V”, “50Hz o 60Hz” e la tensione di riferimento nelle impostazioni generali dello strumento (vedere § 5.1.3). NOTA: per paesi diversi da "Europa" i riferimenti su MCB e Fusibile disponibili possono cambiare

```
LOOP 15/10 – 18:04
TN min
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 0.00Hz
VL - PE=0V VL - N=0V
L - PE Ut 16A 0.2s FUNZ MODE MCB - C Tempo
```

2. Usare i tasti ,  per selezionare il parametro da modificare e i tasti ,  per modificare il valore del parametro
    *   **FUNC** → il tasto virtuale permette di impostare la modalità di misura dello strumento, che può essere L - PE (sistemi Monofase/Trifase) oppure L1 - PE (sistemi Bifase)
    *   **MODE** → il tasto virtuale permette di impostare la modalità di funzionamento dello strumento. Selezionare l'opzione Ut
    *   **Tipo di protezione** → il tasto virtuale permette di impostare il tipo di protezione (Fusibile di tipo gG, aM o magnetotermico MCB curve B, C, D, K) e le rispettive correnti nominali considerando i seguenti valori disponibili:
        *   MCB curva B → 3A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
        *   MCB curva C → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 50A, 63A, 80A,100A,125A,160A,200A
        *   MCB curve D, K → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
        *   Fusibile gG → 2A, 4A, 6A, 8A, 10A, 12A, 13A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A, 800A, 1000A, 1250A
        *   Fusibile aM → 2A, 4A, 6A, 10A, 12A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A
    *   **Tempo** → il tasto virtuale permette di impostare il tempo di intervento della protezione tra le opzioni: 0.1s, 0.2s, 0.4s, 1s, 5s
    premere il tasto **SALVA** per salvare i parametri selezionati e tornare alla videata di misura

3. Se possibile, scollegare tutti i carichi collegati a valle del punto misurato in quanto l'impedenza di queste utenze potrebbe falsare i risultati del test. Eseguire la calibrazione preliminare dei puntali come descritto al § 6.7.2.

4. Inserire i connettori verde, blu e nero del cavo shuko a tre pin nei corrispondenti conduttori di ingresso B3, B4 e B1 dello strumento. In alternativa, utilizzare i singoli cavi e applicare le relative clip a coccodrillo alle estremità libere dei cavi. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel cavo di ingresso B1. Collegare la spina Shuko, i terminali a coccodrillo o il puntale remoto alla rete elettrica in accordo alle Fig. 25, Fig. 26, Fig. 27, Fig. 28 o Fig. 29.

5. Notare la presenza dei corretti valori di tensione tra L - PE e L - N come mostrato nella videata a lato

```
LOOP 15/10 – 18:04
TN min
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE=232 V VL - N= 231 V
L - PE Ut 16A 0.2s FUNZ MODE MCB - C Tempo
```

6. Premere il tasto **GO/STOP** sullo strumento, il tasto **START** sul puntale remoto o la funzione AutoStart (vedere § 5.1.5). Lo strumento inizierà la misura e sul display apparirà il messaggio “Misura…”.
Durante tutta questa fase non scollegare i cavi di misura dello strumento dal sistema in prova. La seguente videata appare a display

```
LOOP 15/10 – 18:04
TN min
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE=232 V VL - N = 231 V
Misura …
L - PE Ut 16A 0.2s FUNZ MODE MCB - C Tempo
```

7. In caso di esito positivo (corrente di cortocircuito minima calcolata SUPERIORE alla corrente di intervento del dispositivo di protezione entro il tempo specificato - vedere § 12.6), lo strumento visualizza il messaggio “OK” e la videata a lato

```
LOOP 15/10 – 18:04
TN min
Ipfc = 214 A
ZL - PE = 1.03 
FREQ. = 50.00Hz
VL - PE=232 V VL - N = 231 V
OK
L - PE Ut 16A 0.2s FUNZ MODE MCB - C Tempo
```

8. In caso di esito negativo (corrente di cortocircuito minima calcolata INFERIORE alla corrente di intervento del dispositivo di protezione entro il tempo specificato - vedere § 12.6), lo strumento visualizza il messaggio “NO OK” e la videata a lato

```
LOOP 15/10 – 18:04
TN min
Ipfc = 1695 A
ZL - PE = 0.13 
FREQ. = 50.00Hz
VL - PE=232 V VL - N = 231 V
NO OK
L - PE Ut 16A 0.2s FUNZ MODE MCB - C Tempo
```

9. Premere il tasto **SAVE** per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto **ESC/MENU** per uscire dalla schermata senza salvare e tornare al menu principale

### 6.7.11. Situazioni anomale

1. Se lo strumento rileva una frequenza superiore al limite massimo (63Hz), non esegue il test e visualizza una videata come quella a lato

```
LOOP 15/10 – 18:04
TN
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = >63Hz
VL - PE=0V VL - N=0V
Frequenza fuori range
L - PE STD FUNZ MODE
```

2. Se lo strumento rileva una tensione L - N o L - PE inferiore al limite minimo (100V), non esegue il test e visualizza una videata come quella a lato. Verificare che il sistema in prova sia alimentato

```
LOOP 15/10 – 18:04
TN
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE=<100V VL - N=<100V
Tensione <100V
L - PE STD FUNZ MODE
```

3. Se lo strumento rileva una tensione L - N o L - PE superiore al limite massimo (265V), non esegue il test e visualizza una videata come quella a lato. Verificare il collegamento dei cavi di misura

```
LOOP 15/10 – 18:04
TN
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE=>265V VL - N=>265V
Tensione >265V
L - PE STD FUNZ MODE
```

4. Se lo strumento rileva una tensione L - L superiore al limite massimo (460V), non esegue il test e visualizza una videata come quella a lato. Verificare il collegamento dei cavi di misura

```
LOOP 15/10 – 18:04
TN
Ipfc = - - - A
ZL - L = - - - 
FREQ. = 50.00Hz
VL - PE=>265V VL - L=>460V
Tensione >460V
L - L STD FUNZ MODE
```

5. Se lo strumento rileva una tensione pericolosa sul conduttore PE fornisce la schermata di avviso mostrata a lato e blocca l'esecuzione delle prove. Verificare l'efficienza del conduttore PE e dell'impianto di terra

```
LOOP 15/10 – 18:04
TN
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE= 231V VL - N= 234V
Tensione su PE
L - PE STD FUNZ MODE
```

6. Se lo strumento rileva l'assenza del segnale al morsetto B4 (conduttore neutro), fornisce la schermata di avviso riportata a lato e blocca l'esecuzione delle prove

```
LOOP 15/10 – 18:04
TN
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE= 231V VL - N= 115V
Manca N
L - PE STD FUNZ MODE
```

7. Se lo strumento rileva l'assenza del segnale al morsetto B3 (conduttore PE), fornisce la schermata di avviso riportata a lato e blocca l'esecuzione delle prove

```
LOOP 15/10 – 18:04
TN
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE= 115V VL - N= 231V
Manca PE
L - PE STD FUNZ MODE
```

8. Se lo strumento rileva l'assenza del segnale al morsetto B1 (conduttore di fase), fornisce la schermata di avviso mostrata a lato e blocca l'esecuzione delle prove

```
LOOP 15/10 – 18:04
TN
Ipfc = - - - A
ZL - PE = - - - 
FREQ. = 50.00Hz
VL - PE= 0V VL - N= 0V
Manca L
L - PE STD FUNZ MODE
```

<!-- Chunk: Pages 79-116 -->
9. Se lo strumento rileva che i conduttori di fase L e neutro N sono invertiti, non esegue il test e viene visualizzata una schermata simile a quella riportata a lato. Ruotare la spina di rete o controllare il collegamento dei cavi di misurazione

```
L O O P   15/10   –   18:04
TN
Ipfc         =   -   -   -   A
ZL - PE      =   -   -   -   
FREQ. = 50.00Hz  VL - PE= 1V   VL - N= 231V
Invertire   L - N
L - PE   STD
FUNZ   MODE
```

10. Se lo strumento rileva che i conduttori di fase e PE sono invertiti, non esegue il test e viene visualizzata una schermata simile a quella riportata a lato. Verificare il collegamento dei cavi di misura

```
L O O P   15/10   –   18:04
TN
Ipfc         =   -   -   -   A
ZL - PE      =   -   -   -   
FREQ. = 50.00Hz  VL - PE= 231V   VL - N= 1V
Invertire   L - PE
L - PE   STD
FUNZ   MODE
```

11. Se lo strumento rileva una tensione di contatto dannosa Ut (oltre il limite impostato 25V o 50V) nel pre-test iniziale, fornisce la schermata di avviso mostrata a lato e blocca l'esecuzione dei test. Verificare l'efficienza del conduttore PE e dell'impianto di terra

```
L O O P   15/10   –   18:04
TT
R A          =   -   -   -   
Ut           =   -   -   -   V
FREQ. = 50.00Hz  VL - PE= 231V
Tensione contatto . > Lim
Ra   2Wire   30mA
FUNC   MODE   I  n
```

12. Se il rumore elettrico tra i conduttori N e PE è così elevato tale da compromettere l’incertezza sul risultato di misura, il simbolo ! è mostrato. Si raccomanda di scollegare tutte leutenze allacciate alla linea e riprovare la misura

```
L O O P   15/10   –   18:04
TT
R A          =   2.54 
Ut           =   0.1  V
FREQ. = 50.00Hz  VL - PE=234V
OK
Ra   2Fili   30mA
FUNZ   MODE   I  n
```

## 6.8. LoZ: IMPEDENZA LINEA/LOOP AD ALTA RISOLUZIONE

Le misure di impedenza di Linea/Loop ad alta risoluzione (0.1mΩ) sono eseguite utilizzando l'accessorio opzionale IMP57 collegato all'unità Master tramite il cavo ottico/RS-232 C2001 fornito con lo stesso accessorio. L'IMP57 deve essere alimentato direttamente dalla rete su cui vengono effettuate le misure. Per informazioni dettagliate, fare riferimento al manuale d’uso dell'accessorio IMP57

Di seguito è riportata la procedura per la misura dell'impedenza STD L-L nei sistemi TN. Le stesse procedure possono essere applicate a qualsiasi altro caso considerando quanto riportato nel § 6.7

1.  Premere il tasto `MENU`, spostare il cursore su `LoZ` nel menu principale tramite i tasti freccia (``, ``) e confermare con `ENTER`. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato in caso di sistema elettrico Monofase L-N-PE selezionato (vedere § 5.1.3). Per sistemi Bifase L-L-PE le tensioni indicate cambiano in VL1-PE e VL1-L2

    Il messaggio **“IMP57 non connesso”** indica che l'accessorio IMP57 non è collegato allo strumento o non è alimentato direttamente dalla rete

    ```
    L o Z   15/10   –   18:04
    TN
    Ipsc         =   -   -   -   A
    ZL - L       =   -   -   -   m
    R =   -   -   -   m   X =   -   -   -   m
    FREQ. =   -   -   - Hz  VL - L=   -   -   - V
    IMP57 non connesso
    L - L   STD
    FUNZ   MODE
    ```

2.  Collegare l'IMP57 allo strumento tramite il cavo C2001 e al sistema alimentato tramite i morsetti di ingresso `C1`, `C2` e `P1`, `P2` posti su di esso (vedere manuale d’uso IMP57). La videata come quella a lato è mostrata a display

    ```
    L o Z   15/10   –   18:04
    TN
    Ipsc         =   -   -   -   A
    ZL - L       =   -   -   -   m
    R =   -   -   -   m   X =   -   -   -   m
    FREQ. = 50.0Hz  VL - L= 384V
    L - L   STD
    FUNZ   MODE
    ```

3.  Premere il tasto `GO/STOP` sullo strumento per avviare il test. La seguente videata è mostrata a display (in caso di misura L-L in modo STD)

    Sul display viene visualizzata la corrente di cortocircuito presunta standard (STD). Nella parte centrale del display sono visualizzati i valori dell'impedenza di loop L-L, oltre alle sue componenti resistive e reattive, espresse in mΩ

    ```
    L o Z   15/10   –   18:04
    TN
    Ipsc         =   15.3  kA
    ZL - L       =   15.0  m
    R = 13.2 m   X = 7.5 m
    FREQ. = 50.0Hz  VL - L= 384V
    L - L   STD
    FUNZ   MODE
    ```

4.  Premere il tasto `SAVE` per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto `ESC/MENU` per uscire dalla schermata senza salvare e tornare al menu principale

## 6.9. 1, 2, 3: SENSO CICLICO E CONCORDANZA DELLE FASI

Questa funzione consente di testare la sequenza e la concordanza delle fasi con il metodo a 1 terminale mediante contatto diretto con parti in tensione (**non su cavi con guaina isolante**)

Fig. 35: Controllo sequenza fasi con cavo di misura
Fig. 36: Controllo sequenza fasi con puntale remoto

1.  Premere il tasto `MENU`, spostare il cursore su `1,2,3` nel menu principale tramite i tasti freccia (``, ``) e confermare con `ENTER`. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato

    ```
    1 2 3   15/10   –   18:04
    TN
    -   -   -
    1T
    MODE
    ```

2.  Inserire il connettore del cavo nero nel corrispondente cavo di ingresso B1 dello strumento. In alternativa, utilizzare il singolo cavo e applicare la relativa clip a coccodrillo all’estremità libera del cavo. È anche possibile utilizzare il puntale remoto inserendo il suo connettore multipolare nel cavo di ingresso B1. Collegare i morsetti a coccodrillo o il puntale remoto alla rete elettrica in base alle Fig. 35 o Fig. 36

    **ATTENZIONE**
    *   Occorre necessariamente impugnare lo strumento prima di eseguire la prova in modo da avere corretti riferimenti di massa e di frequenza della tensione
    *   De-energizzare eventuali sorgenti di tensione adiacenti alla linea in prova prima di eseguire il test

3.  Premere il tasto `GO/STOP` sullo strumento o il tasto `START` sul puntale remoto. Lo strumento inizia il test

    Il messaggio "Tocca L1" è mostrato a display ad indicare l'attesa che lo strumento sia connesso alla fase L1 del sistema in prova

    Toccare la parte attiva della fase L1

    ```
    1 2 3   15/10   –   18:04
    TN
    -   -   -
    Tocca   L1
    1T
    MODE
    ```

4.  Premere il tasto `GO/STOP` sullo strumento o il tasto `START` sul puntale remoto. Lo strumento inizia il test

    Il messaggio "Tocca L1" è mostrato a display ad indicare l'attesa che lo strumento sia connesso alla fase L1 del sistema in prova

    Toccare la parte attiva della fase L1

    ```
    1 2 3   15/10   –   18:04
    TN
    -   -   -
    Tocca   L1
    1T
    MODE
    ```

5.  Lo strumento emette un suono lungo fino a quando non è presente la tensione di ingresso. Al termine dell'acquisizione della fase L1, lo strumento è in attesa del segnale sulla fase L2 e mostra il simbolo di "Rilascia L1" come mostrato nella videata a lato

    ```
    1 2 3   15/10   –   18:04
    TN
    -   -   -
    Rilascia   L1
    1T
    MODE
    ```

6.  In queste condizioni, collegare il terminale a coccodrillo, o il puntale remoto alla fase L2 come mostrato nelle Fig. 35 o Fig. 36.

    Sul display viene visualizzato il messaggio "Tocca L2" ad indicare l'attesa che lo strumento sia connesso alla fase L2 del sistema in prova.

    Toccare la parte attiva della fase L2

    ```
    1 2 3   15/10   –   18:04
    TN
    -   -   -
    Tocca   L 2
    1T
    MODE
    ```

7.  Lo strumento emette un suono lungo fino a quando non è presente la tensione di ingresso. Al termine del test, se la sequenza delle fasi rilevata è **corretta**, lo strumento visualizza una videata come quella a lato (risultato "123") e il messaggio "OK”

    ```
    1 2 3   15/10   –   18:04
    TN
    1 2 3
    OK
    1T
    MODE
    ```

8.  Al termine del test, se la sequenza delle fasi rilevata è **incorretta**, lo strumento visualizza una videata come quella a lato (risultato "213") e il messaggio "NO OK”

    ```
    1 2 3   15/10   –   18:04
    TN
    2 1 3
    NO OK
    1T
    MODE
    ```

9.  Al termine del test, se le due tensioni rilevate sono in fase (**concordanza di fase tra due distinti sistemi trifase**), lo strumento visualizza una videata come quella a lato (risultato "11 -") e il messaggio “OK”

    ```
    1 2 3   15/10   –   18:04
    TN
    1 1   -
    OK
    1T
    MODE
    ```

10. Premere il tasto `SAVE` per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto `ESC/MENU` per uscire dalla schermata senza salvare e tornare al menu principale

### 6.9.1. Situazioni anomale

1.  Se lo strumento rileva una frequenza superiore al limite massimo non esegue il test e visualizza una videata come quella a lato

    ```
    1 2 3   15/10   –   18:04
    TN
    -   -   -
    Frequenza fuori   range
    1T
    MODE
    ```

2.  Se lo strumento rileva una tensione in ingresso L-PE superiore a 265V, visualizza una videata come quella a lato

    ```
    1 2 3   15/10   –   18:04
    TN
    -   -   -
    Tensione   > 265V
    1T
    MODE
    ```

3.  Se tra l'inizio della prova e l'acquisizione della prima tensione o tra l'acquisizione della prima e della seconda tensione è trascorso un tempo superiore a circa 10s, lo strumento visualizza una videata come quella a lato. È necessario ripetere il test

    ```
    1 2 3   15/10   –   18:04
    TN
    -   -   -
    Tempo scaduto
    1T
    MODE
    ```

## 6.10. ΔV%: CADUTA DI TENSIONE SULLE LINEE

Questa funzione consente di valutare il valore percentuale della caduta di tensione tra due punti di una linea di distribuzione in cui sia presente un dispositivo di protezione e confrontarlo con eventuali limiti di normativa. Sono disponibili le seguenti modalità di funzionamento

*   **L-N** Misura dell'impedenza di linea fra il conduttore di fase e il conduttore di neutro. La misura è svolta anche con risoluzione alta (0.1mΩ) con accessorio opzionale IMP57
*   **L-L** Misura dell'impedenza di linea fra due conduttori di fase (L1-L2 per sistemi Bifase). La misura è svolta anche con risoluzione alta (0.1mΩ) con accessorio opzionale IMP57

**ATTENZIONE**
La misurazione dell'impedenza di linea o dell’anello di guasto comporta la circolazione di una corrente massima come da caratteristiche tecniche dello strumento (vedere § 12.11). Questo potrebbe comportare l’intervento di eventuali protezioni magnetotermiche con correnti di intervento inferiori

Fig. 37: Collegamento strumento per misura caduta di tensione in modo L-N
Fig. 38: Collegamento strumento per misura caduta di tensione in modo L-L

1.  Premere il tasto `MENU`, spostare il cursore su `ΔV%` nel menu principale tramite i tasti freccia (``, ``) e confermare con `ENTER`. Successivamente lo strumento visualizza una videata simile a quella qui riportata a lato

    ```
       V %   15/10   –   18:04
     V%
    ZL - N       =   -   -   -   %
                 =   -   -   -   
    FREQ. = 0.00 Hz  VL - PE= 0 V   VL - N= 0 V
    L - N   16A   4%   0.00 
    MODE   Inom   Lim.   Z >    <
    ```

2.  Utilizzare i tasti ``, `` per selezionare il parametro da modificare e i tasti ``, `` per modificare il valore del parametro:
    ➢   `MODE` → Il tasto virtuale permette di impostare la modalità di misura dello strumento, che può essere: `L-N`, `L-L`, `L1-L2`, `CAL`
    ➢   `Inom` → il tasto virtuale permette di impostare il valore della corrente nominale del dispositivo di protezione nel campo: `1A ÷ 999A` in passi da `1A`
    ➢   `Lim` → il tasto virtuale permette di impostare il valore limite massimo consentito della caduta di tensione (ΔV%) per la linea principale in prova
    ➢   `Z>φ<` → questa posizione permette di eseguire la prima misura di impedenza Z1 (Offset). In questo caso lo strumento misurerà l'impedenza a monte come punto iniziale della linea principale in prova prendendola come riferimento di partenza

3.  Selezionare la modalità `CAL` tramite i tasti freccia ``, `` ed eseguire la calibrazione dei cavi di prova o del cavo con spina Shuko utilizzando l'accessorio `ZEROLOOP` prima di eseguire il test (vedere § 6.7.2)

4.  Collegare lo strumento al punto iniziale della linea principale in prova (tipicamente a valle di un dispositivo di protezione) in base alla Fig. 37 o Fig. 38 per effettuare la prima misura di impedenza Z1 (Offset). In questo caso lo strumento misurerà l'impedenza a monte del punto iniziale della linea principale in prova prendendola come riferimento di partenza. La schermata seguente (riferita alla misura L-L) è mostrata a display

5.  Usare i tasti ``, `` e spostare il cursore nella posizione "`Z>φ<`". Premere il tasto `GO/STOP` sullo strumento per avviare il test. La seguente videata è mostrata a display

    ```
       V %   15/10   –   18:04
     V%
    ZL - L       =   -   -   -   %
                 =   -   -   -   
    FREQ. = 50.00 Hz  VL - PE= 223V   VL - L= 387V
    L - L   16A   4%   0.00 
    MODE   Inom   Lim.   Z >    <
    ```

6.  Usare i tasti ``, `` e spostare il cursore nella posizione "`Z>φ<`". Premere il tasto `GO/STOP` sullo strumento per avviare il test. Il risultato della misurazione Z1 (offset) è mostrata a display sopra la posizione "`Z>φ<`". Se il valore di Z1 (offset) è <10 Ω il risultato “OK” è mostrata a display e salvato automaticamente nel buffer interno

    ```
       V %   15/10   –   18:04
     V%
    ZL - L       =   -   -   -   %
                 =   -   -   -   
    FREQ. = 50.00 Hz  VL - PE= 223V   VL - L= 387V
    OK
    L - L   16A   4%   1.48 
    MODE   Inom   Lim.   Z >    <
    ```

7.  Collegare lo strumento al punto finale della linea principale in prova in accordo alle Fig. 37 o Fig. 38 per misurare l'impedenza Z2 a fine linea. Notare il il valore Z1 (Offset) precedentemente misurato mostrato a display

8.  Utilizzare i tasti ``, `` e spostare il cursore in qualsiasi posizione tranne "`Z>φ<`". Premere il tasto `GO/STOP` sullo strumento per misurare l'impedenza Z2 e completare la misura della caduta di tensione ΔV%. Durante tutta questa fase non scollegare i cavi di misura dello strumento dal sistema in prova.

    In caso di esito positivo (valore percentuale massimo della caduta di tensione calcolata secondo § 12.11 <valore limite impostato), lo strumento visualizza l'esito “OK” e la videata a lato che contiene il valore dell'impedenza di fine linea Z2 insieme al valore Z1 (Offset)

    ```
       V %   15/10   –   18:04
     V%
    ZL - L       =   0.4  %
                 =   1.57 
    FREQ. = 50.00 Hz  VL - PE= 223V   VL - L= 387V
    OK
    L - L   16A   4%   1.48 
    MODE   Inom   Lim.   Z>    <
    ```

9.  In caso di esito positivo (valore percentuale massimo della caduta di tensione calcolata secondo § 12.11 > valore limite impostato), lo strumento visualizza l'esito “NO OK” e la videata a lato che contiene il valore dell'impedenza di fine linea Z2 insieme al valore Z1 (Offset)

    ```
       V %   15/10   –   18:04
     V%
    ZL - L       =   19.5 %
                 =   5.97 
    FREQ. = 50.00 Hz  VL - PE= 223V   VL - L= 387V
    NO OK
    L - L   16A   4%   1.48 
    MODE   Inom   Lim.   Z>    <
    ```

10. Premere il tasto `SAVE` per memorizzare il risultato del test nella memoria dello strumento (vedere § 7.1) oppure il tasto `ESC/MENU` per uscire dalla schermata senza salvare e tornare al menu principale

### 6.10.1. Situazioni anomale

1.  Se lo strumento rileva una frequenza superiore al limite massimo (63Hz), non esegue il test e visualizza una videata come quella a lato.

    ```
       V %   15/10   –   18:04
     V%
    ZL - N       =   -   -   -   %
                 =   -   -   -   
    FREQ. >63 Hz  VL - PE= 232V   VL - N= 232V
    Frequenza fuori range
    L - N   16A   4%   0.12 
    MODE   Inom   Lim.   Z>    <
    ```

2.  Se lo strumento rileva una tensione L-N o L-PE inferiore al limite minimo (100V), non esegue il test e visualizza una videata come quella a lato. Verificare che il sistema in prova sia alimentato.

    ```
       V %   15/10   –   18:04
     V%
    ZL - N       =   -   -   -   %
                 =   -   -   -   
    FREQ.= 50.00 Hz  VL - PE <100V   VL - N<100V
    Tensione   <100V
    L - N   16A   4%   0.12 
    MODE   Inom   Lim.   Z>    <
    ```

3.  Se lo strumento rileva una tensione L-L superiore al limite massimo (460V), non esegue il test e visualizza una videata come quella a lato. Verificare il collegamento dei cavi di misura.

    ```
       V %   15/10   –   18:04
     V%
    ZL - N       =   -   -   -   %
                 =   -   -   -   
    FREQ.= 50.00 Hz  VL - PE= 242V   VL - L >460V
    Tensione   >460V
    L - L   16A   4%   0.12 
    MODE   Inom   Lim.   Z>    <
    ```

4.  Se lo strumento rileva una tensione L-N o L-PE superiore al limite massimo (265V), non esegue il test e visualizza una videata come quella a lato. Verificare il collegamento dei cavi di misura.

    ```
       V %   15/10   –   18:04
     V%
    ZL - N       =   -   -   -   %
                 =   -   -   -   
    FREQ.= 50.00 Hz  VL - PE >265V   VL - N >265V
    Tensione   >265V
    L - N   16A   4%   0.12 
    MODE   Inom   Lim.   Z>    <
    ```

5.  Se lo strumento rileva una tensione pericolosa sul conduttore PE fornisce la schermata di avviso mostrata a lato e blocca l'esecuzione delle prove. Verificare l'efficienza del conduttore PE e dell'impianto di terra

    ```
       V %   15/10   –   18:04
     V%
    ZL - N       =   -   -   -   %
                 =   -   -   -   
    FREQ.= 50.00Hz  VL - PE= 232V   VL - N= 232V
    Tensione su PE
    L - N   16A   4%   0.12 
    MODE   Inom   Lim.   Z>    <
    ```

6.  Se lo strumento rileva l'assenza del segnale al morsetto B1 (conduttore di fase), fornisce la schermata di avviso mostrata a lato e blocca l'esecuzione delle prove

    ```
       V %   15/10   –   18:04
     V%
    ZL - N       =   -   -   -   %
                 =   -   -   -   
    FREQ.= 50.00Hz  VL - PE= 0V   VL - N= 0V
    Manca   L
    L - N   16A   4%   0.12 
    MODE   Inom   Lim.   Z>    <
    ```

7.  Se lo strumento rileva l'assenza del segnale al morsetto B4 (conduttore neutro), fornisce la schermata di avviso riportata a lato e blocca l'esecuzione delle prove

    ```
       V %   15/10   –   18:04
     V%
    ZL - N       =   -   -   -   %
                 =   -   -   -   
    FREQ.= 50.00Hz  VL - PE= 232V   VL - N= 115V
    Manca   N
    L - N   16A   4%   0.12 
    MODE   Inom   Lim.   Z>    <
    ```

8.  Se lo strumento rileva l'assenza del segnale al morsetto B3 (conduttore PE), fornisce la schermata di avviso riportata a lato e blocca l'esecuzione delle prove

    ```
       V %   15/10   –   18:04
     V%
    ZL - N       =   -   -   -   %
                 =   -   -   -   
    FREQ.= 50.00Hz  VL - PE= 115V   VL - N= 232V
    Manca   PE
    L - N   16A   4%   0.12 
    MODE   Inom   Lim.   Z>    <
    ```

9.  Se lo strumento rileva che i conduttori di fase L e neutro N sono invertiti, non esegue il test e viene visualizzata una schermata simile a quella riportata a lato. Ruotare la spina di rete o controllare il collegamento dei cavi di misurazione

    ```
       V %   15/10   –   18:04
     V%
    ZL - N       =   -   -   -   %
                 =   -   -   -   
    FREQ.= 50.00Hz  VL - PE= 1V   VL - N= 232V
    Invertire   L - N
    L - N   16A   4%   0.12 
    MODE   Inom   Lim.   Z>    <
    ```

10. Se lo strumento rileva che i conduttori di fase e PE sono invertiti, non esegue il test e viene visualizzata una schermata simile a quella riportata a lato. Verificare il collegamento dei cavi di misura

    ```
       V %   15/10   –   18:04
     V%
    ZL - N       =   -   -   -   %
                 =   -   -   -   
    FREQ.= 50.00Hz  VL - PE= 232V   VL - N= 1V
    Invertire   L - PE
    L - N   16A   4%   0.12 
    MODE   Inom   Lim.   Z>    <
    ```

11. Se lo strumento rileva un VL-PE, VL-N o VN-PE >5V durante l'operazione di calibrazione dei puntali non esegue il test e viene visualizzata una schermata simile a quella riportata a lato. Verificare il collegamento dei cavi di misurazione

    ```
       V %   15/10   –   18:04
    RL           =   -   -   -   
    RN           =   -   -   -   
    RPE          =   -   -   -   
    FREQ.= 50.00Hz  VL - PE= 232V   VL - N= 231V
    Tensione ingresso   > 5V
    CAL
    MODE
    ```

## 7. MEMORIZZAZIONE RISULTATI

Lo strumento consente la memorizzazione di max 999 risultati di misura. I dati possono essere richiamati a display e cancellati in ogni momento ed è possibile associare in fase di salvataggio fino ad un massimo di 3 livelli di marcatori numerici di riferimento mnemonici relativi all’impianto, alla stringa e al modulo FV (con valore max 250). Per ogni livello sono disponibili 20 nomi di marcatori eventualmente personalizzabili dall’utente tramite collegamento a PC con software di gestione in dotazione. E’ inoltre possibile inserire un commento associato ad ogni misura.

### 7.1. SALVATAGGIO DELLE MISURE

4.  Premere il tasto `SAVE/ENTER` con risultato di misura presente a display. La videata a lato è mostrata. In essa sono presenti:
    ➢   La voce “Misura” che identifica la prima locazione di memoria disponibile
    ➢   Il primo marcatore (es: “Impianto”) a cui è possibile associare un valore numerico compreso tra 1 ÷ 250
    ➢   Il secondo marcatore (es: “Stringa”) a cui è possibile associare un valore numerico compreso tra 0 (- - -) ÷ 250
    ➢   Il terzo marcatore (es: “Modulo”) a cui è possibile associare un valore numerico compreso tra 0 (- - -) ÷ 250
    ➢   La voce “Commento” associato alla misura in cui è possibile inserire un testo di max 30 caratteri.

    ```
    SAVE   15/10   –   18:04
    M i s u r a   0 0 3
    I m p i a n t o   0 0 1
    S t r i n g a   - - -
    M o d u l o   - - -
    C o m m e n t o :   m a x   3 0
    c a r a t t e r i
    ```

5.  Usare i tasti freccia `` o `` per selezionare il marcatore e i tasti freccia (``, ``) per modificare l’etichetta del valore numerico associato (ex: “Area”) tra quelli disponibili o personalizzabili dall’utente (max 20 nomi)

6.  Selezionare la voce “Commento” e premere il tasto `SAVE/ENTER` per inserire il testo desiderato. La seguente videata con tastiera virtuale è mostrata a display:

    ```
    SAVE   15/10   –   18:04
    M i s u r a   0 0 3
    A r e a   0 0 1
    S t r i n g a   - - -
    M o d u l o   - - -
    C o m m e n t o   :   m a x   3 0   c a r a t t e r
    ```

7.  Usare i tasti freccia `` o `` per spostare il cursore sul carattere selezionare e premere il tasto `SAVE/ENTER` per l’inserimento

8.  Muovere il cursore nella posizione “CANC” e premere il tasto `SAVE/ENTER` per cancellare il carattere selezionato

9.  Muovere il cursore nella posizione “FINE” e premere il tasto `SAVE/ENTER` per confermare il commento scritto e tornare alla videata precedente.

    ```
    SAVE   15/10   –   18:04
    T a s t i e r a
    C O M M E N T O
    0   1   2   3   4   5   6   7   8   9   0   (   )   %
    Q   W   E   R   T   Y   U   I   O   P   < = >   #
    A   S   D   F   G   H   J   K   L   +   -   *   /   &
    Z   X   C   V   B   N   M   .   ,   ;   :   !   ?   _
    Ä Ö Ü ß μ Ñ Ç Á Í Ó Ú Ü ¿ ¡
    Á È É Ù Ç Ä Ë Ï Ö Ü Æ Ø Å
    CANC   FINE
    ```

10. Premere il tasto `SAVE/ENTER` per confermare il salvataggio della misura o `ESC/MENU` per uscire senza salvare

### 7.2. RICHIAMO DEI DATI A DISPLAY E CANCELLAZIONE MEMORIA

1.  Posizionare il cursore sulla voce `MEM` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. La videata a lato è mostrata a display. Nella videata sono presenti:
    ➢   Il numero della locazione di memoria in cui è salvata la misura
    ➢   La data in cui è stata salvata la misura
    ➢   Il tipo di misura salvata
    ➢   Il totale delle misure salvate per ogni schermata e la memoria residua disponibile

    ```
    MEM   15/10   –   18:04
    N .   D a t a   T i p o
    0 0 1   1 4 / 0 1 / 2 1   R P E
    0 0 2   1 5 / 0 1 / 2 1   M   
    0 0 3   1 5 / 0 1 / 2 1   L o   
    0 0 4   1 5 / 0 1 / 2 1   L o Z
    0 0 5   1 6 / 0 1 / 2 1   A u t o
    0 0 6   1 7 / 0 1 / 2 1   L o o p
    0 0 7   1 9 / 0 1 / 2 1      V %
    Tot: 007   Libera: 992
            All
    Rec   Pag   CANC
    ```

2.  Usare i tasti freccia (``, ``) per selezionare la misura da richiamare a display

3.  Premere il tasto `SAVE/ENTER` per visualizzare la misura salvata a display. Premere il tasto `ESC/MENU` per tornare alla videata precedente

4.  Usare i tasti freccia `` o `` per selezionare l’opzione “Pag” e passare alla videata successiva

5.  Selezionare l’opzione “CANC” per cancellare l’intero contenuto della memoria. La seguente videata è mostrata:

    ```
    MEM   15/02   –   18:04
    N .   D a t a   T i p o
    0 0 1   1 4 / 0 1 / 2 1   R P E
    0 0 2   1 5 / 0 1 / 2 1   M   
    0 0 3   1 5 / 0 1 / 2 1   L o   
    0 0 4   1 5 / 0 1 / 2 1   L o Z
    0 0 5   1 6 / 0 1 / 2 1   A u t o
    0 0 6   1 7 / 0 1 / 2 1   L o o p
    0 0 7   1 9 / 0 1 / 2 1      V %
    Tot: 007   Libera: 992
            All
    Rec   Pag   CANC
    ```

6.  Premere il tasto `SAVE/ENTER` per confermare la cancellazione dei dati. Il messaggio “Memoria vuota” è mostrato a display

7.  Premere il tasto `MENU/ESC` per uscire e tornare al menu generale.

    ```
    MEM   15/10   –   18:04
    C A N C E L L A   T U T T O   ?
    E N T E R   /   E S C
    ```

## 8. COLLEGAMENTO DELLO STRUMENTO A PC

**ATTENZIONE**
*   La connessione tra PC e strumento avviene tramite il cavo C2006
*   Per effettuare il trasferimento dati verso un PC è necessario avere preventivamente installato nel PC stesso sia il SW di gestione
*   Prima di effettuare il collegamento è necessario selezionare a PC la porta utilizzata e il baud rate corretto (57600 bps). Per impostare questi parametri avviare il software di gestione in dotazione e consultare l’help in linea del programma
*   La porta selezionata non deve essere impegnata da altri dispositivi o applicazioni come mouse, modem, ecc. Chiudere eventualmente processi in esecuzione a partire dalla funzione Task Manager di Windows
*   La porta ottica emette radiazione LED invisibile. Non osservare direttamente con strumenti ottici. Apparecchio LED di classe 1M secondo IEC/EN60825-1

Per trasferire i dati a PC attenersi alla seguente procedura:

1.  Accendere lo strumento premendo il tasto `ON/OFF`
2.  Collegare lo strumento a PC utilizzando il cavo ottico/USB `C2006` in dotazione
3.  Premere il tasto `ESC/MENU` per aprire il menu principale
4.  Selezionare con i tasti freccia (``, ``) la voce “PC” per entrare in modalità trasferimento dati e confermare con `SAVE/ENTER`

    ```
    MENU   15/10   –   18:04
    L o Z   :   Z   a l t a   p r e c i s i o n e
    1 , 2 , 3   :   S e q .   F a s i
       V %   :   C a d u t a   T e n s .
    S E T   :   I m p o s t a z i o n i
    M E M   :   D a t i   m e m o r i z z a t i
    P C   :   T r a s f e r i m e n t o   d a t i
    
    ```

5.  Lo strumento fornisce la videata seguente:

    ```
    P C   15/10   –   18:04
    CONNESSIONE PC
    ```

6.  Usare i comandi del software di gestione per attivare il trasferimento dati (consultare l’help in linea del programma)

## 9. MANUTENZIONE

### 9.1. GENERALITÀ

*   Durante l’utilizzo e l’immagazzinamento rispettare le raccomandazioni elencate in questo manuale per evitare possibili danni o pericoli durante l’utilizzo
*   Non utilizzare lo strumento in ambienti caratterizzati da elevato tasso di umidità o temperatura elevata. Non esporre direttamente alla luce del sole
*   Se si prevede di non utilizzarlo per un lungo periodo di tempo, rimuovere le batterie per evitare da parte di queste ultime fuoruscite di liquidi che possono danneggiare i circuiti interni dello strumento

### 9.2. SOSTITUZIONE BATTERIE

Quando sul display LCD appare il simbolo di batteria scarica “!” sostituire le batterie interne.

**ATTENZIONE**
Solo tecnici qualificati possono effettuare questa operazione. Prima di effettuare questa operazione assicurarsi di aver rimosso tutti i cavi dai terminali di ingresso.

1.  Spegnere lo strumento premendo a lungo il pulsante di accensione
2.  Rimuovere i cavi dai terminali di ingresso
3.  Svitare la vite di fissaggio del coperchio dal vano batterie e rimuovere lo stesso
4.  Rimuovere dal vano batterie tutte le batterie e sostituirle solo con batterie tutte nuove e tutte del tipo corretto (vedere § 10.2) rispettando le polarità indicate
5.  Riposizionare il coperchio vano batterie e fissarlo con l'apposita vite
6.  Non disperdere nell’ambiente le batterie utilizzate. Usare gli appositi contenitori per lo smaltimento

### 9.3. PULIZIA DELLO STRUMENTO

Per la pulizia dello strumento utilizzare un panno morbido e asciutto. Non usare mai panni umidi, solventi, acqua, ecc.

### 9.4. FINE VITA

**ATTENZIONE**: il simbolo riportato indica che l'apparecchiatura, i suoi accessori e le batterie interne devono essere raccolti separatamente e trattati in modo corretto

## 10. SPECIFICHE TECNICHE

Incertezza indicata come ± [%lettura + (num. cifre) * risoluzione] a 23°C ± 5°C, <80%RH

### 10.1. CARATTERISTICHE TECNICHE

**Tensione AC TRMS**

| Campo [V]    | Risoluzione [V] | Incertezza           |
| :----------- | :-------------- | :------------------- |
| 15 ÷ 460     | 1               | ± (3% lettura + 2 cifre) |

**Frequenza**

| Campo [Hz]            | Risoluzione [Hz] | Incertezza              |
| :-------------------- | :--------------- | :---------------------- |
| 47.50 ÷ 52.50 / 57.00 ÷ 63.00 | 0.01             | ± (0.1%lettura+1 cifre) |

**Continuità conduttore di protezione (RPE)**

| Campo [Ω]   | Risoluzione [Ω] | Incertezza              |
| :---------- | :-------------- | :---------------------- |
| 0.00 ÷ 9.99 | 0.01            | ± (5.0 % lettura + 3 cifre) |
| 10.0 ÷ 99.9 | 0.1             |                         |
| 100 ÷ 1999  | 1               |                         |

Corrente di prova: >200mA DC fino a 5 Ω (inclusi puntali di misura)
Corrente di prova generata: risoluzione 1mA, campo 0 ÷ 250mA
Tensione a vuoto: 4 < V₀ < 24V DC
Protezione sugli ingressi: messaggio errore per tensione sugli ingressi >10V

**Resistenza di Isolamento (MΩ)**

| Tensione di prova [V] | Campo [MΩ]      | Risoluzione [MΩ] | Incertezza           |
| :-------------------- | :-------------- | :--------------- | :------------------- |
| 50                    | 0.01 ÷ 9.99     | 0.01             | ± (2.0 % lett + 2 cifre) |
|                       | 10.0 ÷ 49.9     | 0.1              |                      |
|                       | 50.0 ÷ 99.9     |                  | ± (5.0 % lett + 2 cifre) |
| 100                   | 0.01 ÷ 9.99     | 0.01             | ± (2.0 % lett + 2 cifre) |
|                       | 10.0 ÷ 99.9     | 0.1              |                      |
|                       | 100 ÷ 199       | 1                | ± (5.0 % lett + 2 cifre) |
| 250                   | 0.01 ÷ 9.99     | 0.01             | ± (2.0 % lett + 2 cifre) |
|                       | 10.0 ÷ 199.9    | 0.1              |                      |
|                       | 200 ÷ 249       | 1                |                      |
|                       | 250 ÷ 499       |                  | ± (5.0 % lett + 2 cifre) |
| 500                   | 0.01 ÷ 9.99     | 0.01             | ± (2.0 % lett + 2 cifre) |
|                       | 10.0 ÷ 199.9    | 0.1              |                      |
|                       | 200 ÷ 499       | 1                |                      |
|                       | 500 ÷ 999       |                  | ± (5.0 % lett + 2 cifre) |
| 1000                  | 0.01 ÷ 9.99     | 0.01             | ± (2.0 % lett + 2 cifre) |
|                       | 10.0 ÷ 199.9    | 0.1              |                      |
|                       | 200 ÷ 1999    | 1                |                      |

Tensione circuito aperto: tensione di prova nominale -0% +10%
Corrente di misura nominale: >1mA su 1kΩ x Vnom (50V, 100V, 250V, 1000V), >2.2mA con 230kΩ @ 500V
Corrente di corto circuito: <6.0mA per ogni tensione di prova
Protezione sugli ingressi: messaggio errore per tensione sugli ingressi > 30V

**Impedenza Linea/Loop (Fase-Fase, Fase-Neutro, Fase-PE)**

| Campo [Ω]    | Risoluzione [Ω] | Incertezza (*)            |
| :----------- | :-------------- | :------------------------ |
| 0.01 ÷ 9.99  | 0.01            | ± (5% lettura + 3 cifre)  |
| 10.0 ÷ 199.9 | 0.1             |                           |

(*) 0.1mΩ nel campo 0.1 ÷ 199.9mΩ (con accessorio opzionale IMP57)
Massima corrente di prova: 3.31A (@ 265V); 5.71 A (@ 457V)
Tensione di prova P-N/P-P: (100V ÷ 265V) / (100V ÷ 460V); 50/60Hz ±5%
Tipi di protezione: MCB (B, C, D, K), Fusibili (aM, gG, BS882-2, BS88-3, BS3036, BS1362)

**Corrente di primo guasto – Sistemi IT**

| Campo [mA]   | Risoluzione [mA] | Incertezza            |
| :----------- | :--------------- | :-------------------- |
| 0.1 ÷ 0.9    | 0.1              | ± (5 % lettura +1 cifra) |
| 1 ÷ 999      | 1                | ± (5 % lettura + 3 cifre) |

Tensione di contatto limite (ULIM): 25V, 50V

**Verifica protezioni differenziali (RCD) di tipo scatolato**

Tipo di differenziale (RCD): AC (~), A/F (![](./images/typeA.png)), B/B+ (![](./images/typeB.png)), CCID (![](./images/typeCCID.png), nazione USA), Generale (G), Selettivo (S)
Sistemi Monofase (L-N-PE)
Campo tensione L-PE, L-N: 100V ÷ 265V RCD tipo AC, A/F, B/B+ e CCID (IΔN ≤100mA)
190V ÷ 265V RCD tipo B/B+ (IΔN = 300mA)
Campo tensione N-PE: <10V
Sistemi Bifase (ritardo fase VL1-PE, VL2-PE = 180° o ritardo fase VL1-PE, VL2-PE = 120°)
Campo tensione L1-PE, L1-L2: 100V ÷ 265V RCD tipo AC, A/F, B/B+ e CCID (IΔN ≤100mA)
Campo tensione L2-PE: 0V ÷ min[(VL1-PE - 100V) e (VL1-L2 - 100V), RCD tipo B/B+ (IΔN ≤100mA)
Corrente di intervento (IΔN): 5mA 6mA,10mA, 20mA, 30mA, 100mA, 300mA, 500mA, 650mA, 1000mA
Frequenza: 50/60Hz ± 5%

**Corrente di Intervento differenziali di tipo scatolato - (solo per RCD tipo Generale)**

| Tipo RCD     | IΔN              | Campo IΔN [mA] | Risoluzione [mA] | Incertezza          |
| :----------- | :--------------- | :------------- | :--------------- | :------------------ |
| CCID         | 5mA, 20mA        | (0.2 ÷ 1.3) IΔN  | ≤ 0.1IΔN         | - 0%, +10%IΔN       |
| AC, A/F, B/B+ | 6mA,10mA        | (0.2 ÷ 1.1) IΔN  |                  |                     |
| AC, A/F, B/B+ | 30mA ≤ IΔN ≤ 300mA |                |                  | - 0%, +5%IΔN        |
| AC, A/F      | 500mA ≤ IΔN ≤ 650mA |                |                  |                     |

**Durata misura tempo di intervento RCD scatolati – Sistemi TT/TN**

| \         | x 1/2   | x 1     | x 5     | AUTO    | AUTO+   |
| :-------- | :------ | :------ | :------ | :------ | :------ |
|           | G   S   | G   S   | G   S   | G   S   | G   S   |
| 5mA CCID  | 999 310 |         |         |         |         |
| 6mA AC    | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 6mA A/F   | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 6mA B/B+  | 999 999 | 999 999 |     310 |         |         |
| 6mA CCID  | 999 310 |         |         |         |         |
| 10mA AC   | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 10mA A/F  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 10mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 10mA CCID | 999 310 |         |         |         |         |
| 20mA CCID | 999 310 |         |         |         |         |
| 30mA AC   | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 30mA A/F  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 30mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 30mA CCID | 999 310 |         |         |         |         |
| 100mA AC  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 100mA A/F | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 100mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 100mA CCID | 999 310 |         |         |         |         |
| 300mA AC  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 300mA A/F | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 300mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 300mA CCID | 999 310 |         |         |         |         |
| 500mA AC  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 500mA A/F | 999 999 | 999 999 | 50  150 |         | 310     |
| 500mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 500mA CCID | 999 310 |         |         |         |         |
| 650mA AC  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 650mA A/F | 999 999 | 999 999 | 50  150 |         | 310     |
| 650mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 650mA CCID | 999 310 |         |         |         |         |
| 1000mA AC | 999     | 999     | 999     |         |         |
| 1000mA A/F | 999     | 999     | 999     |         |         |
| 1000mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 1000mA CCID | 999 310 |         |         |         |         |

Tabella di durata della misura del tempo di intervento [ms] - Risoluzione:1ms, Precisione: ±(2.0 %lettura + 2cifre)
NOTA: RCD tipo CCID disponibili solo per nazione = USA e sistemi TN

**Durata misura tempo di intervento RCD scatolati – Sistemi IT**

| \         | x 1/2   | x 1     | x 5     | AUTO    | AUTO+   |
| :-------- | :------ | :------ | :------ | :------ | :------ |
|           | G   S   | G   S   | G   S   | G   S   | G   S   |
| 6mA AC    | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 6mA A/F   | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 6mA B/B+  | 999 999 | 999 999 |     310 |         |         |
| 10mA AC   | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 10mA A/F  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 10mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 30mA AC   | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 30mA A/F  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310 ✓   |
| 30mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 100mA AC  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 100mA A/F | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 100mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 300mA AC  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 300mA A/F | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 300mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 500mA AC  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 500mA A/F | 999 999 | 999 999 | 50  150 | ✓       | 310     |
| 500mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 650mA AC  | 999 999 | 999 999 | 50  150 | ✓   ✓   | 310     |
| 650mA A/F | 999 999 | 999 999 | 50  150 | ✓       | 310     |
| 650mA B/B+ | 999 999 | 999 999 |     310 |         |         |
| 1000mA AC | 999     | 999     | 999     |         |         |
| 1000mA A/F | 999     | 999     | 999     |         |         |
| 1000mA B/B+ | 999 999 | 999 999 |     310 |         |         |

Tabella di durata della misura del tempo di intervento [ms] - Risoluzione:1ms, Precisione: ±(2.0 %lettura + 2cifre)

**RCD – Verifica su protezioni differenziali tipo DD**

Tipo di Differenziale (RCD): Tipo DD (in accordo allo standard IEC62955), Generali (G)
Sistemi Monofase (L-N-PE)
Campo tensione L-PE, L-N: 100V ÷ 265V
Campo tensione N-PE: <10V
Sistemi Bifase (ritardo fase VL1-PE, VL2-PE = 180° o ritardo fase VL1-PE, VL2-PE = 120°)
Campo tensione L1-PE, L1-L2: 100V ÷ 265V
Campo tensione L2-PE: 0V ÷ min[(VL1-PE - 100V) e (VL1-L2 - 100V)]
Correnti di intervento nominali (IΔN): 6mA
Frequenza: 50/60Hz ± 5%

**RCD tipo DD corrente di intervento - (solo RCD tipo Generale)**

| Tipo RCD | IΔN | Campo [mA]   | Risoluzione [mA] | Incertezza          |
| :------- | :-- | :----------- | :--------------- | :------------------ |
| DD       | 6mA | (0.2 ÷ 1.1) IΔN | ≤ 0.1IΔN         | - 0%, +10%IΔN       |

**RCD tipo DD tempo di intervento x1 - (solo RCD tipo Generale)**

| Tipo RCD | IΔN | Campo [ms] | Risoluzione [ms] | Incertezza           |
| :------- | :-- | :--------- | :--------------- | :------------------- |
| DD       | 6mA | 10000      | 1                | ± (2%lettura + 2cifre) |

**Resistenza globale di terra senza intervento RCD (Ra)**

Campo tensione L-PE, L-N: 100 ÷ 265V
Campo tensione N-PE: <10V
Frequenza: 50/60Hz ± 5%

**Resistenza globale di terra in sistemi con Neutro (3-fili) – (RCD 30mA o superiore)**

| Campo [Ω]    | Risoluzione [Ω] | Incertezza            |
| :----------- | :-------------- | :-------------------- |
| 0.05 ÷ 9.99  | 0.01            | ± (5 % lettura + 8 cifre) |
| 10.0 ÷ 199.9 | 0.1             |                       |

**Resistenza globale di terra in sistemi con Neutro (3-fili) – (RCD 6mA e 10mA)**

| Campo [Ω]    | Risoluzione [Ω] | Incertezza             |
| :----------- | :-------------- | :--------------------- |
| 0.05 ÷ 9.99  | 0.01            | ± (5 % lettura +30 cifre) |
| 10.0 ÷ 199.9 | 0.1             |                        |

**Resistenza globale di terra in sistemi senza Neutro (2-fili) – (RCD 30mA o superiore)**

| Campo [Ω]   | Risoluzione [Ω] | Incertezza            |
| :---------- | :-------------- | :-------------------- |
| 0.05 ÷ 9.99 | 0.01            | ± (5 % lettura +8 cifre) |
| 10.0 ÷ 99.9 | 0.1             |                       |
| 100 ÷ 1999  | 1               |                       |

**Resistenza globale di terra in sistemi senza Neutro (2-fili) – (RCD 6mA e 10mA)**

| Campo [Ω]   | Risoluzione [Ω] | Incertezza             |
| :---------- | :-------------- | :--------------------- |
| 0.05 ÷ 9.99 | 0.01            | ± (5 % lettura + 30 cifre) |
| 10.0 ÷ 99.9 | 0.1             |                        |
| 100 ÷ 1999  | 1               |                        |

**Tensione di contatto (misurata durante test RCD Ra)**

| Campo [V] | Risoluzione [V] | Incertezza              |
| :-------- | :-------------- | :---------------------- |
| 0 ÷ Ut LIM | 0.1             | - 0%, +(5.0 % lettura + 3V) |

**Senso ciclico delle fasi a 1 terminale**

| Campo tensione P-N, P-PE[V] | Campo frequenza   |
| :-------------------------- | :---------------- |
| 100 ÷ 265                   | 50Hz/60Hz ± 5%    |

La misura avviene solo per contatto diretto con parti metalliche in tensione (non su guaina isolante)

### 10.2. CARATTERISTICHE GENERALI

**Normative di riferimento**

Sicurezza: IEC/EN61010-1, IEC/EN61010-2-030, IEC/EN61010-2-033, IEC/EN61010-2-034, IEC/EN61557-1
EMC: IEC/EN61326-1, IEC/EN61326-2-2
Documentazione tecnica: IEC/EN61187
Sicurezza accessori di misura: IEC/EN61010-031
Ambiente EMC di utilizzo: portatile, Classe B, Gruppo 1
Isolamento: doppio isolamento
Grado di inquinamento: 2
Max altitudine di utilizzo: 2000m
Categoria di misura: CAT IV 300V verso terra, max 415V fra gli ingressi
RPE: IEC/EN61557-4, BS7671 17th ed., AS/NZS3000/3017
MΩ: IEC/EN61557-2, BS7671 17th ed., AS/NZS3000/3017
RCD: IEC/EN61557-6 (solo su sistemi Fase-Neutro-Terra)
RCD-DD: IEC62955
RCD CCID: UL2231-2
LOOP P-P, P-N, P-PE: IEC/EN61557-3, BS7671 17th ed., AS/NZS3000/3017
Multifunzione: IEC/EN61557-10, BS7671 17th ed., AS/NZS3000/3017
Corrente di cortocircuito: EN60909-0

**Caratteristiche meccaniche**

Dimensioni (L x La x H): 225 x 165 x 75mm
Peso (batterie incluse): 1.2kg
Protezione meccanica: IP40

**Alimentazione**

Tipo batteria: 6x1.5 V alcaline tipo AA IEC LR06 MN1500 oppure 6 x1.2V ricaricabili NiMH tipo AA
Indicazione batteria scarica: simbolo “!” a display
Durata batterie: > 500 prove per ogni funzione
Auto Power OFF: dopo 10 minuti di non utilizzo (se attivato)

**Varie**

Display: COG Bianco/nero grafico LCD, 320x240pxl
Memoria: 999 locazioni di memoria, 3 livelli di marcatori
Connessione a PC: porta ottica/USB

### 10.3. CONDIZIONI AMBIENTALI DI UTILIZZO

Temperatura di riferimento: 23°C ± 5°C
Temperatura di utilizzo: 0°C ÷ 40°C
Umidità relativa ammessa: <80%RH
Temp. di conservazione: -10°C ÷ 60°C
Umidità di conservazione: <80%RH

Questo strumento è conforme ai requisiti della Direttiva Europea sulla bassa tensione 2014/35/EU (LVD) e della direttiva EMC 2014/30/EU
Questo strumento è conforme ai requisiti della direttiva europea 2011/65/EU (RoHS) e della direttiva europea 2012/19/EU (WEEE)

### 10.4. ACCESSORI

Vedere packing list

## 11. ASSISTENZA

### 11.1. CONDIZIONI DI GARANZIA

Questo strumento è garantito contro ogni difetto di materiale e fabbricazione, in conformità con le condizioni generali di vendita. Durante il periodo di garanzia, le parti difettose possono essere sostituite, ma il costruttore si riserva il diritto di riparare ovvero sostituire il prodotto. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballo originale. Ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente. Il costruttore declina ogni responsabilità per danni causati a persone o oggetti.

La garanzia non è applicata nei seguenti casi:

*   Riparazione e/o sostituzione accessori e batteria (non coperti da garanzia)
*   Riparazioni che si rendono necessarie a causa di un errato utilizzo dello strumento o del suo utilizzo con apparecchiature non compatibili
*   Riparazioni che si rendono necessarie a causa di un imballaggio non adeguato
*   Riparazioni che si rendono necessarie a causa di interventi eseguiti da personale non autorizzato
*   Modifiche apportate allo strumento senza esplicita autorizzazione del costruttore
*   Utilizzo non contemplato nelle specifiche dello strumento o nel manuale d’uso.

Il contenuto del presente manuale non può essere riprodotto in alcuna forma senza l’autorizzazione del costruttore.
I nostri prodotti sono brevettati e i marchi depositati. Il costruttore si riserva il diritto di apportare modifiche alle specifiche ed ai prezzi se ciò è dovuto a miglioramenti tecnologici

### 11.2. ASSITENZA

Se lo strumento non funziona correttamente, prima di contattare il servizio di assistenza, controllare lo stato delle batterie e dei cavi e sostituirli se necessario. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballaggio originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente.

## 12. APPENDICI TEORICHE

### 12.1. CONTINUITÀ DEI CONDUTTORI DI PROTEZIONE

**Scopo della prova**

Accertare la continuità dei:

*   Conduttori di protezione (PE), conduttori equipotenziali principali (EQP), conduttori equipotenziali secondari (EQS) nei sistemi TT e TN-S
*   Conduttori di neutro con funzione di conduttori di protezione (PEN) nei sistemi TN-C.

Questa prova strumentale va preceduta da un esame a vista che accerti l'esistenza dei conduttori di protezione ed equipotenziali di colore giallo-verde e che le sezioni utilizzate siano conformi a quanto prescritto dalle norme.

**Parti dell’impianto da verificare**

```
Collegare uno dei puntali al
conduttore di protezione della presa
forza motrice e l’altro al nodo
equipotenziale dell’impianto di terra.

Collegare uno dei puntali alla massa
estranea (in questo caso è il tubo
dell'acqua) e l’altro all’impianto di
terra utilizzando ad esempio il
conduttore di protezione presente
nella presa forza motrice più vicina.
```

Fig. 39: Esempi di misure di continuità dei conduttori

Verificare la continuità tra:

*   Poli di terra di tutte le prese a spina e collettore o nodo di terra
*   Morsetti di terra degli apparecchi di classe I (boiler ecc.) e collettore o nodo di terra
*   Masse estranee principali (tubi acqua, gas, ecc.) e collettore o nodo di terra
*   Masse estranee supplementari fra loro e verso morsetto terra.

**Valori ammissibili**

Le norme non richiedono la misurazione della resistenza di continuità e la comparazione di quanto misurato con valori limite. Viene richiesta una prova della continuità e prescritto che lo strumento di misura segnali all'operatore se la prova non viene eseguita con una corrente di almeno 200mA ed una tensione a vuoto compresa tra 4 e 24V. I valori di resistenza possono essere calcolati in base alle sezioni ed alle lunghezze dei conduttori in esame. In generale, per valori intorno a qualche ohm, la prova si può ritenere superata

### 12.2. RESISTENZA DI ISOLAMENTO

**Scopo della prova**

Verificare che la resistenza di isolamento dell'impianto sia conforme a quanto previsto dalla norma applicabile (ad esempio CEI 64-8/6 negli impianti elettrici fino a 500V). Questa prova deve essere effettuata con il circuito in esame non alimentato e disinserendo gli eventuali carichi che esso alimenta.

**Valori ammissibili**

I valori della tensione di misura e della resistenza minima di isolamento possono essere ricavati dalla tabella seguente (CEI 64-8/6 Tab. 61A):

Tabella 4: Tipologie di prova più comuni, misurazione della resistenza di isolamento

| Tensione nominale del circuito [V] | Tensione di prova [V] | Resistenza di isolamento [MΩ] |
| :--------------------------------- | :-------------------- | :---------------------------- |
| SELV e PELV \*                     | 250                   | ≥ 0.250                       |
| fino a 500 V compresi, esclusi i circuiti sopra | 500                   | ≥ 1.000                       |
| oltre i 500 V                      | 1000                  | ≥ 1.000                       |

\* I termini SELV e PELV sostituiscono nella nuova stesura della normativa le vecchie definizioni "bassissima tensione di sicurezza" o "funzionale"

**Parti dell’impianto da verificare**

Verificare la resistenza di isolamento tra:

*   Ogni conduttore attivo e la terra (il conduttore di neutro è considerato un conduttore attivo tranne nel caso di sistemi di alimentazione di tipo TN-C ove è considerato parte della terra (PEN)). Durante questa misura tutti i conduttori attivi possono essere connessi fra loro, qualora il risultato della misura non dovesse rientrare nei limiti normativi occorrerà ripetere la prova separatamente per ogni singolo conduttore
*   I conduttori attivi. La norma CEI 64-8/6 raccomanda di verificare anche l'isolamento tra i conduttori attivi quando ciò è possibile.

Qualora l'impianto comprenda dispositivi elettronici occorre scollegarli dall'impianto stesso per evitarne il danneggiamento. Se ciò non fosse possibile, eseguire solo la prova tra conduttori attivi (che in questo caso devono essere collegati insieme) e la terra.

In presenza di un circuito molto esteso i conduttori che corrono affiancati costituiscono una capacità che lo strumento deve caricare per poter ottenere una misura corretta, in questo caso è consigliabile mantenere premuto il tasto di avvio della misurazione (nel caso in cui si esegua la prova in modalità manuale) finché il risultato non si stabilizzi.
L'indicazione "> fondo scala" segnala che la resistenza di isolamento misurata dallo strumento è superiore al limite massimo di resistenza misurabile, ovviamente tale risultato è ampiamente superiore ai limiti minimi della tabella normativa di cui sopra pertanto l'isolamento in quel punto sarebbe da ritenersi a norma.

### 12.2.1. Misura Indice di Polarizzazione (PI)

Lo scopo di questo test diagnostico è quello di valutare l’influenza degli effetti di polarizzazione. All’applicazione di una tensione elevata ad un isolante, i dipoli elettrici distribuiti nell’isolante si allineano nella direzione del campo elettrico applicato. Questo fenomeno è chiamato **polarizzazione**. Per effetto delle molecole polarizzate si genera una corrente di polarizzazione (assorbimento) che abbassa il valore complessivo della resistenza di isolamento.

Il parametro **PI** consiste nel rapporto tra il valore di resistenza di isolamento misurata dopo 1 minuto e quella dopo 10 minuti. La tensione di prova è mantenuta per tutta la durata del test e al termine lo strumento fornisce il valore del rapporto:
`PI = RI(10min) / RI(1min)`

Alcuni valori di riferimento:

| Valore PI   | Condizione dell’isolamento |
| :---------- | :------------------------- |
| <1.0        | Non accettabile            |
| da 1.0 a 2.0 | Pericoloso                 |
| da 2.0 a 4.0 | Buono                      |
| > 4.0       | Eccellente                 |

### 12.2.2. Rapporto di Assorbimento Dielettrico (DAR)

Il parametro **DAR** consiste nel rapporto tra il valore di resistenza di isolamento misurata dopo 30s e quella dopo 1minuto. La tensione di prova è mantenuta per tutta la durata del test e al termine lo strumento fornisce il valore del rapporto:
`DAR = RI(1min) / RI(30s)`

Alcuni valori di riferimento:

| Valore DAR    | Condizione dell’isolamento |
| :------------ | :------------------------- |
| < 1.0         | Non accettabile            |
| da 1.0 a 1.25 | Pericoloso                 |
| da 1.25 a 1.6 | Buono                      |
| > 1.6         | Eccellente                 |

### 12.3. VERIFICA DELLA SEPARAZIONE DEI CIRCUITI

**Definizioni**

Un sistema **SELV** è un sistema di categoria zero o sistema a bassissima tensione di sicurezza caratterizzato da alimentazione da sorgente autonoma (es. batterie di pile, piccolo gruppo elettrogeno) o di sicurezza (es. trasformatore di sicurezza), separazione di protezione verso altri sistemi elettrici (isolamento doppio o rinforzato oppure uno schermo metallico collegato a terra) ed assenza di punti messi a terra (isolato da terra).

Un sistema **PELV** è un sistema di categoria zero o sistema a bassissima tensione di protezione caratterizzato da alimentazione da sorgente autonoma (es. batterie di pile, piccolo gruppo elettrogeno) o di sicurezza (es. trasformatore di sicurezza), separazione di protezione verso altri sistemi elettrici (isolamento doppio o rinforzato oppure uno schermo metallico collegato a terra) e, a differenza dei sistemi SELV, presenza di punti messi a terra (non isolato da terra).

Un sistema con **separazione elettrica** è un sistema caratterizzato da alimentazione da trasformatore di isolamento o sorgente autonoma con caratteristiche equivalenti (es. gruppo motore generatore), separazione di protezione verso altri sistemi elettrici (isolamento non inferiore a quello del trasformatore di isolamento), separazione di protezione verso terra (isolamento non inferiore a quello del trasformatore di isolamento).

**Scopo della prova**

La prova, da effettuare nel caso in cui la protezione sia attuata mediante separazione (64-8/6 612.4, SELV o PELV o separazione elettrica), deve verificare che la resistenza di isolamento misurata come descritto di seguito (a seconda del tipo di separazione) sia conforme ai limiti riportati nella tabella relativa alle misure di isolamento.

**Parti dell’impianto da verificare**

*   Sistema **SELV** (Safety Extra Low Voltage):
    ✓   Misurare la resistenza tra le parti attive del circuito in prova (separato) e le parti attive degli altri circuiti
    ✓   Misurare la resistenza tra le parti attive del circuito in prova (separato) e la terra.
*   Sistema **PELV** (Protective Extra Low Voltage):
    ✓   Misurare la resistenza tra le parti attive del circuito in prova (separato) e le parti attive degli altri circuiti.
*   **Separazione elettrica**:
    ✓   Misurare la resistenza tra le parti attive del circuito in prova (separato) e le parti attive degli altri circuiti
    ✓   Misurare la resistenza tra le parti attive del circuito in prova (separato) e la terra.

**Valori ammissibili**

La prova ha esito positivo quando la resistenza di isolamento presenta valori superiori o uguali a quelli indicati in Tabella 4.

**ESEMPIO DI VERIFICA DI SEPARAZIONE TRA CIRCUITI ELETTRICI**

```
Trasformatore
di isolamento o di
sicurezza che effettua la
separazione tra i circuiti
```

```
PROVA TRA LE PARTI ATTIVE
Collegare un puntale dello
strumento su uno dei due
conduttori del circuito separato e
l’altro su uno dei conduttori di un
circuito non separato
```

```
PROVA TRA LE PARTI ATTIVE E
LA TERRA
Collegare un puntale dello
strumento su uno dei due
conduttori del circuito separato e
l'altro sul nodo equipotenziale.
Questa prova va eseguita solo per
circuiti SELV o con separazione
elettrica.
```

```
Nodo equipotenziale
```

Fig. 40: Misure di separazione tra circuiti in un impianto

### 12.4. TEST SU INTERRUTTORI DIFFERENZIALI (RCD)

**Scopo della prova**

Verificare (CEI 64-8 612.9, CEI 64-14 2.3.2.2) che i dispositivi di protezione differenziale Generali (G), Selettivi (S) siano stati installati e regolati correttamente e che conservino nel tempo le proprie caratteristiche. La verifica deve accertare che l’interruttore differenziale intervenga ad una corrente non superiore alla sua corrente nominale di funzionamento IdN e che il tempo di intervento soddisfi, a seconda del caso, le seguenti condizioni:

*   Non superi il tempo massimo dettato dalla normativa nel caso di interruttori differenziali di tipo Generale (secondo quanto descritto nella Tabella 5)
*   Sia compreso tra il tempo di intervento minimo e quello massimo nel caso di interruttori differenziali di tipo Selettivo (secondo quanto descritto nella Tabella 5)

La prova dell’interruttore differenziale effettuata con il tasto di prova serve per far sì che “l’effetto colla” non comprometta il funzionamento del dispositivo rimasto inattivo per lungo tempo. Tale prova viene eseguita solo per accertare la funzionalità meccanica del dispositivo e non è sufficiente per poter dichiarare la conformità alla normativa del dispositivo a corrente differenziale. Da un’indagine statistica risulta che la verifica con tasto di prova degli interruttori effettuata una volta al mese riduce della metà il tasso di guasto di questi, però tale prova individua solo il 24% degli interruttori differenziali difettosi.

**Parti dell’impianto da verificare**

Tutti i differenziali devono essere testati quando vengono installati. Negli impianti a bassa tensione si consiglia di eseguire questa prova, fondamentale al fine di garantire un giusto livello di sicurezza. Nei locali ad uso medico tale verifica deve essere eseguita periodicamente su tutti i differenziali come imposto dalle norme CEI 64-8/7 e CEI 64-13.

**Valori ammissibili**

Su ogni RCD di tipo scatolato (STD) devono essere eseguite due prove: una con corrente di dispersione che inizi in fase con la semionda positiva della tensione (0°) e una con corrente di dispersione che inizi in fase con la semi onda negativa della tensione (180°). Il risultato indicativo è il tempo più alto. La prova a ½IdN non deve in nessun caso causare l'intervento del differenziale.

Tabella 5: Tempi di intervento per interruttori RCD di tipo scatolato Generali e Selettivi

| Tipo differenziale | IdN   | x 1   | x 2    | x 5    | Descrizione                       |
| :----------------- | :---- | :---- | :----- | :----- | :-------------------------------- |
| Generale           | 0.3s  | 0.15s | 0.04s  |        | Tempo di intervento massimo in secondi |
| Selettivo S        | 0.13s | 0.05s | 0.05s  |        | Tempo di intervento minimo in secondi |
|                    | 0.5s  | 0.20s | 0.15s  |        | Tempo di intervento massimo in secondi |

Tempi di intervento in accordo a normativa AS/NZS 3017 (\*\*)

Tabella 6: Tempi di intervento per RCD Generali e Selettivi in nazione AUS/NZ

| Tipo RCD | IdN [mA]        | ½ IΔn (*) | IΔn   | 5 x IΔn | tΔ [ms] | Note                       |
| :------- | :-------------- | :-------- | :---- | :------ | :------ | :------------------------- |
| I        | ≤ 10            | >999ms    | 40    |         |         | Tempo di intervento massimo |
| II       | >10 ≤ 30        |           | 300   | 40      |         |                            |
| III      | > 30            |           |       |         |         |                            |
| IV [S]   | > 30            |           | 500   | 150     |         |                            |
|          |                 |           |       |         | 130     | Tempo di intervento minimo |
|          |                 |           |       |         | 50      |                            |

(\*) Corrente di intervento ½ IΔn, RCD non deve intervenire
(\*\*) Corrente di prova e incertezze in accordo a normativa AS/NZS 3017

**Misura della corrente di intervento delle protezioni differenziali**

*   Scopo della prova è verificare la reale corrente di intervento dei differenziali generali (**non si applica ai differenziali selettivi**)
*   In presenza di interruttori differenziali con corrente di intervento che può essere selezionata è utile effettuare questa prova per verificare la reale corrente di intervento del differenziale. Per i differenziali con corrente differenziale fissa questa prova può essere eseguita per rilevare eventuali dispersioni di utilizzatori collegati all’impianto
*   Nel caso non sia disponibile l’impianto di terra effettuare la prova collegando lo strumento con un terminale su un conduttore a valle del dispositivo differenziale ed un terminale sull'altro conduttore a monte del dispositivo stesso
*   La corrente di intervento deve essere compresa fra ½ IdN e IdN.

### 12.5. VERIFICA DEL POTERE DI INTERRUZIONE DELLA PROTEZIONE

**Scopo della prova**

Verificare che il potere di interruzione del dispositivo di protezione sia superiore alla massima corrente di guasto possibile sull'impianto.

**Parti dell’impianto da verificare**

La prova deve essere effettuata nel punto in cui si può avere la massima corrente di corto circuito, normalmente immediatamente a valle della protezione da controllare.

La prova deve essere effettuata fra fase e fase (ZLL) negli impianti trifase e fra fase e neutro (ZLN) negli impianti monofase.

**Valori ammissibili**

Lo strumento esegue il confronto tra il valore misurato e il valore calcolato in accordo alle seguenti relazioni derivate dalla normativa EN60909-0:

Impianti Trifase: `I sc L - L_MAX = C MAX * U NOM / Z L - L > BC`
Impianti Monofase: `I sc N L_MAX = C MAX * U NOM / Z L - N > BC`

ove:
`BC` = potere di interruzione della protezione (Breaking Capacity)
`Z L-L` = impedenza misurata fra fase e fase
`Z L-N` = impedenza misurata fra fase e neutro

| Tensione Misurata                      | UNOM    | CMAX |
| :------------------------------------- | :------ | :--- |
| 230V - 10% < Vmisurata < 230V+ 10%   | 230V    | 1,05 |
| 230V+10% < Vmisurata < 400V - 10%   | Vmisurata | 1,10 |
| 400V - 10% < Vmisurata < 400V+ 10%   | 400V    | 1,05 |

### 12.6. VERIFICA PROTEZIONE CONTRO CONTATTI INDIRETTI NEI SISTEMI TN

**Scopo della prova**

La protezione dai contatti indiretti nei sistemi TN deve essere garantita mediante un dispositivo di protezione contro le sovracorrenti (tipicamente magnetotermico o fusibile) che interrompa l’alimentazione al circuito o all’equipaggiamento in caso di guasto tra una parte attiva e una massa o un conduttore di protezione entro una durata **non superiore a 5s**, sufficiente per le macchine, oppure in accordo ai tempi riportati nella seguente Tabella 7. Per altre nazioni fare riferimento alle rispettive regolamentazioni

Tabella 7: Tempi di interruzione della protezione (fonte CEI 64-8/4)

| Uo [V]   | Tempo di interruzione della protezione [s] |
| :------- | :----------------------------------------- |
| 50 ÷ 120 | 0.8                                        |
| 120 ÷ 230 | 0.4                                        |
| 230 ÷ 400 | 0.2                                        |
| >400     | 0.1                                        |

Uo = Tensione nominale AC verso terra dell’impianto

Tale prescrizione è soddisfatta dalla condizione:
`Zs * Ia <= Uo`

dove:
`Zs` = Impedenza di anello di guasto P-PE che comprende l’avvolgimento di fase del trasformatore, il conduttore di linea, fino al punto di guasto e il conduttore di protezione dal punto di guasto al centro stella del trasformatore
`Ia` = Corrente che provoca l’interruzione automatica della protezione entro il tempo indicato nella Tabella 7
`Uo` = Tensione nominale AC verso terra

**ATTENZIONE**
Lo strumento deve essere utilizzato per eseguire misure dell’impedenza dell’anello di guasto di valore almeno 10 volte superiore alla della risoluzione dello strumento in modo da minimizzare l’errore commesso.

**Parti dell’impianto da verificare**

La prova deve essere effettuata obbligatoriamente nei sistemi TN **non protetti con dispositivi differenziali**.

**Valori ammissibili**

L’obiettivo della misura eseguita dallo strumento è quello di verificare che in ogni punto dell’impianto sia verificata la relazione, derivata dalla normativa EN60909-0:

`I sc PE L_MIN = C MIN * U NOM / Z PE L > Ia`

| Tensione Misurata                      | UNOM    | CMIN |
| :------------------------------------- | :------ | :--- |
| 230V - 10% < Vmisurata < 230V+ 10%   | 230V    | 0,95 |
| 230V+10% < Vmisurata < 400V - 10%   | Vmisurata | 1,00 |
| 400V - 10% < Vmisurata < 400V+ 10%   | 400V    | 0,95 |

Lo strumento, in funzione del valore di tensione P-PE nominale impostato (vedere § 5.1.3) e del valore misurato dell’impedenza di anello di guasto, calcola il **valore minimo** della corrente di cortocircuito presunta che deve essere interrotta dal dispositivo di protezione. Tale valore, per un corretto coordinamento, DEVE essere sempre superiore o uguale al valore **Ia** della corrente di intervento dal tipo di protezione considerata come caso peggiore

Il valore di riferimento **Ia** (vedere Fig. 41) è funzione di:
➢ Tipo di protezione (curve B, C, D, K)
➢ Corrente nominale della protezione In
➢ Tempo di estinzione del guasto da parte della protezione

Tipicamente: Ia = 3÷5In (curva B), Ia = 5÷10In (curva C), Ia = 10÷20In (curve D,K)

Fig. 41: Curve di intervento protezioni magnetotermiche (MCB)

Lo strumento consente la selezione (\*) dei seguenti parametri:
➢   MCB curva B → 3A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
➢   MCB curva C → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 50A, 63A, 80A,100A,125A,160A,200A
➢   MCB curve D, K → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
➢   Fusibile gG → 2A, 4A, 6A, 8A, 10A, 12A, 13A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A, 800A, 1000A, 1250A
➢   Fusibile aM → 2A, 4A, 6A, 10A, 12A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A
➢   Tempo di estinzione del guasto da parte della protezione selezionabile tra i valori: 0.1s, 0.2s, 0.4s, 1s, 5s

(\*) Valori soggetti a variazioni

### 12.7. TEST RA NEI SISTEMI TN

La protezione dai contatti indiretti nei sistemi TN deve essere garantita mediante un dispositivo di protezione contro le sovracorrenti (tipicamente magnetotermico o fusibile) che interrompa l’alimentazione al circuito o all’equipaggiamento in caso di guasto tra una parte attiva e una massa o un conduttore di protezione entro una durata **non superiore a 5s**, sufficiente per le macchine.

**Parti dell’impianto da verificare**

La prova deve essere effettuata nel punto in cui si può avere la minima corrente di corto circuito, normalmente al termine della linea controllata dalla protezione nelle normali condizioni di funzionamento. La prova deve essere effettuata fra Fase-PE (Z L-PE) e tra Fase-Neutro (Z L-N) negli impianti monofase.

**Valori ammissibili**

Il valore della impedenza comunque misurato deve soddisfare le seguenti relazioni:

`Z L-PE ≤ Z LIM` (1)
`Z L-N ≤ Z LIM` (2)

dove:
`Z L-PE` = Impedenza misurata tra Fase e PE
`Z L-N` = Impedenza misurata tra Fase e Neutro
`Z LIM` = Valore limite Massimo dell’impedenza funzione del tipo di protezione (Magnetotermico o Fusibile) e dal tempo di intervento della protezione (valore dipendente dalla Nazione di riferimento)

Lo strumento consente la selezione (\*) dei seguenti parametri:
➢   MCB curva B → 3A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
➢   MCB curva C → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 50A, 63A, 80A,100A,125A,160A,200A
➢   MCB curve D, K → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
➢   Fusibile gG → 2A, 4A, 6A, 8A, 10A, 12A, 13A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A, 800A, 1000A, 1250A
➢   Fusibile aM → 2A, 4A, 6A, 10A, 12A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A
➢   Tempo di estinzione del guasto da parte della protezione selezionabile tra i valori: 0.1s, 0.2s, 0.4s, 1s, 5s

(\*) Valori soggetti a variazioni

### 12.8. VERIFICA PROTEZIONE CONTRO CONTATTI INDIRETTI NEI SISTEMI TT

**Scopo della prova**

Verificare che il dispositivo di protezione sia coordinato con il valore della resistenza di terra. Non si può assumere a priori un valore di resistenza di terra limite al quale fare riferimento nel controllo del risultato della misura, ma è necessario di volta in volta controllare che sia rispettato il coordinamento previsto dalla normativa.

**Parti dell’impianto da verificare**

L'impianto di terra nelle condizioni di esercizio. La verifica deve essere eseguita senza scollegare i dispersori.

**Valori ammissibili**

Il valore della resistenza di terra comunque misurato deve soddisfare la seguente relazione:
`R A < 50 / I a`

ove:
`R A` = resistenza misurata dell'impianto di terra il cui valore può essere determinato con le seguenti misurazioni:
*   Resistenza di terra con metodo voltamperometrico a tre fili
*   Impedenza dell'anello di guasto (\*)
*   Resistenza di terra a due fili (\*\*)
*   Resistenza di terra a due fili nella presa (\*\*)
*   Resistenza di terra data dalla misura della tensione di contatto U t (\*\*)
*   Resistenza di terra data dalla misura della prova del tempo di intervento degli interruttori differenziali RCD (A, AC, B), RCD S (A, AC) (\*\*)
`I a` = corrente di intervento dell'interruttore automatico o corrente nominale di intervento del differenziale (nel caso di RCD S 2 IdN) espressa in A
`50` = tensione limite di sicurezza (ridotta a 25V in ambienti particolari)

(\*) Se a protezione dell'impianto si trova un interruttore differenziale la misura deve essere effettuata a monte del differenziale stesso o a valle cortocircuitando lo stesso per evitare che questo intervenga
(\*\*) Questi metodi, pur se non attualmente previsti dalle norme CEI 64.8, forniscono valori che innumerevoli prove di confronto con il metodo a tre fili hanno dimostrato essere indicativi della resistenza di terra.

**ESEMPIO DI VERIFICA DI RESISTENZA DI TERRA**
Impianto protetto da un differenziale da 30mA
➢   Misura della resistenza di terra utilizzando uno dei metodi sopra citati
➢   Per capire se la resistenza dell'impianto sia da considerarsi a norma moltiplicare il valore trovato per 0.03A (30mA)
➢   Se il risultato è inferiore a 50V (o 25V per ambienti particolari) l'impianto è da ritenersi coordinato perché rispetta la relazione indicata sopra
Quando siamo in presenza di differenziali da 30mA (la quasi totalità degli impianti civili) la resistenza di terra massima ammessa è 50/0.03=1666 Ω questo consente di utilizzare anche i metodi semplificati indicati che pur non fornendo un valore estremamente preciso, forniscono un valore sufficientemente approssimato per il calcolo del coordinamento

### 12.9. VERIFICA PROTEZIONE CONTRO CONTATTI INDIRETTI NEI SISTEMI IT

Nei sistemi IT le parti attive devono essere isolate da terra oppure essere collegate a terra attraverso un’impedenza di valore sufficientemente elevato. Nel caso di un singolo guasto a terra la corrente di primo guasto è quindi debole e non è necessario interrompere il circuito. Questo collegamento può essere effettuato al punto neutro del sistema oppure ad un punto neutro artificiale. Se non esiste alcun punto neutro, si può collegare a terra attraverso un’impedenza un conduttore di linea. Si devono tuttavia prendere precauzioni per evitare il rischio di effetti fisiologici dannosi su persone in contatto con parti conduttrici simultaneamente accessibili nel caso di doppio guasto a terra.

**Scopo della prova**

Verificare che l’impedenza del dispersore a cui sono collegate le masse soddisfi la relazione:
`Id * Z E <= U L`

dove:
`Z E` = Impedenza L-PE del dispersore a cui sono collegate le masse
`Id` = Corrente di primo guasto L-PE (tipicamente espressa in mA)
`U L` = Tensione di contatto limite 25V oppure 50V

**Parti dell’impianto da verificare**

L'impianto di terra nelle condizioni di esercizio. La verifica deve essere eseguita senza scollegare i dispersori.

### 12.10. VERIFICA COORDINAMENTO DELLE PROTEZIONI L-L, L-N E L-PE

**Scopo della prova**

Eseguire la verifica del coordinamento delle protezioni (tipicamente magnetotermica o fusibile) presenti in un’installazione Monofase o Trifase in funzione del tempo limite di intervento impostato e del valore calcolato della corrente di cortocircuito.

**Parti dell’impianto da verificare**

La prova deve essere effettuata nel punto in cui si può avere la minima corrente di corto circuito, normalmente al termine della linea controllata dalla protezione nelle normali condizioni di funzionamento. La prova deve essere effettuata fra Fase-Fase negli impianti trifase e fra Fase-Neutro o Fase-PE negli impianti monofase

**Valori ammissibili**

Lo strumento esegue il confronto tra il valore calcolato della corrente di cortocircuito presunta e la corrente **Ia** che provoca l’interruzione automatica della protezione entro il tempo specificato in accordo alle seguenti relazioni:

Sistema Trifase → Impedenza Loop F-F: `I sc L - L_Min2 F > I a`
Sistema Monofase → Impedenza Loop F-N: `I sc N L_Min > I a`
Sistema Monofase → Impedenza Loop F-PE: `I sc PE L_Min > I a`

In cui:
`Isc L-L_Min2F` = Corrente di cortocircuito presunta minima bifase Fase-Fase
`Isc L-N_Min` = Corrente di cortocircuito presunta minima Fase-Neutro
`Isc L-PE_Min` = Corrente di cortocircuito presunta minima Fase-PE

Il calcolo della corrente di cortocircuito presunta è eseguito dallo strumento sulla base della misura dell’impedenza di anello di guasto in accordo alle seguenti relazioni derivate dalla normativa EN60909-0:

Fase – Fase: `I sc L - L_MIN = C MIN * U NOM / Z L - L`
Fase – Neutro: `I sc N L_MI N = C MIN * U NOM / Z L - N`
Fase – PE: `I sc PE L_MIN = C MIN * U NOM / Z L - PE`

| Tensione Misurata                      | UNOM    | CMIN |
| :------------------------------------- | :------ | :--- |
| 230V - 10% < Vmisurata < 230V+ 10%   | 230V    | 0,95 |
| 230V+10% < Vmisurata < 400V - 10%   | Vmisurata | 1,00 |
| 400V - 10% < Vmisurata < 400V+ 10%   | 400V    | 0,95 |

dove:
`U L-L` = Tensione fase – fase nominale
`U L-N` = Tensione fase – neutro nominale
`U L-PE` = Tensione fase – PE nominale
`Z L-L` = Impedenza misurata fra fase e fase
`Z L-N` = Impedenza misurata fra fase e neutro
`Z L-PE` = Impedenza misurata fra fase e PE

**ATTENZIONE**
Lo strumento deve essere utilizzato per eseguire misure dell’impedenza dell’anello di guasto di valore almeno 10 volte superiore alla della risoluzione dello strumento in modo da minimizzare l’errore commesso.

Lo strumento, in funzione del valore di tensione nominale impostato (vedere § 5.1.3) e del valore misurato dell’impedenza di anello di guasto, calcola il **valore minimo** della corrente di cortocircuito presunta che deve essere interrotta dal dispositivo di protezione. Tale valore, per un corretto coordinamento, DEVE essere sempre superiore o uguale al valore Ia della corrente di intervento del tipo di protezione considerata.

Il valore di riferimento Ia è funzione di:
➢ Tipo di protezione (curva)
➢ Corrente nominale della protezione
➢ Tempo di estinzione del guasto da parte della protezione

Lo strumento consente la selezione (\*) dei seguenti parametri:
➢   MCB curva B → 3A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
➢   MCB curva C → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 50A, 63A, 80A,100A,125A,160A,200A
➢   MCB curves D, K → 0.5A, 1A, 1.6A, 2A, 3A, 4A, 6A, 10A, 13A, 15A, 16A, 20A, 25A, 32A, 40A, 45A, 50A, 63A, 80A,100A,125A,160A,200A
➢   Fusibile gG → 2A, 4A, 6A, 8A, 10A, 12A, 13A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A, 800A, 1000A, 1250A
➢   Fusibile aM → 2A, 4A, 6A, 10A, 12A, 16A, 20A, 25A, 32A, 35A, 40A, 50A, 63A, 80A, 100A, 125A,160A, 200A, 250A, 315A, 400A, 500A, 630A
➢   Tempo di estinzione del guasto da parte della protezione selezionabile tra i valori: 0.1s, 0.2s, 0.4s, 1s, 5s

(\*) Valori soggetti a variazioni

### 12.11. VERIFICA DELLA CADUTA DI TENSIONE SU LINEE DI DISTRIBUZIONE

La misura della caduta di tensione come conseguenza del flusso di corrente attraverso un impianto o una parte di esso può essere molto importante se occorre:
➢   Verificare la capacità di alimentare un carico da parte dell’impianto esistente
➢   Dimensionare un nuovo impianto
➢   Ricercare possibili cause di malfunzionamenti su apparecchiature, utilizzatori, ecc.. collegati ad una linea elettrica

**Scopo della prova**

Eseguire la misura del valore massimo della caduta di tensione percentuale tra due punti di una linea di distribuzione

**Parti dell’impianto da verificare**

La prova deve essere effettuata eseguendo due misure sequenziali di impedenza di linea nei punti iniziale (tipicamente a valle di un dispositivo di protezione) e finale della linea stessa.

**Valori ammissibili**

Lo strumento esegue il confronto tra il valore calcolato della caduta di tensione massima ΔV% e il limite impostato (tipicamente 4% in accordo alla normativa CEI 64-8) in base alla seguente relazione:
`ΔV% = 100 * I NOM * (Z 2 - Z 1) / V NOM`

dove:
`Z 2` = Impedenza finale della linea in esame
`Z 1` = Impedenza iniziale (Offset) della linea in esame (Z 2 > Z 1)
`I NOM` = Corrente nominale del dispositivo di protezione sulla linea in esame
`V NOM` = Tensione nominale Fase-Neutro o Fase-Terra della linea in esame

HT ITALIA SRL
Via della Boaria, 40
48018 – Faenza (RA) – Italy
T +39 0546 621002 | F +39 0546 621144
M info@ht-instrumnents.com | www. ht-instruments.it

HT INSTRUMENTS SL
C/ Legalitat, 89
08024 Barcelona – Spain
T +34 93 408 17 77 | F +34 93 408 36 30
M info@htinstruments.es | www. ht-instruments.com/es-es/

HT INSTRUMENTS GmbH
Am Waldfriedhof 1b
D-41352 Korschenbroich – Germany
T +49 (0) 2161 564 581 | F +49 (0) 2161 564 583
M info@ht-instruments.de | www. ht-instruments.de

WHERE WE ARE