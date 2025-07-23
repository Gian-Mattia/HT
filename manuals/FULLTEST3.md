# FULLTEST3

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-33 -->
© Copyright HT ITALIA 2024 Versione IT 3.0 1 - 02/12/2024 FULLTEST3 Manuale d'uso

FULLTEST3 IT - 1

## INDICE

1.  PRECAUZIONI E MISURE DI SICUREZZA
    1.1. Istruzioni preliminari
    1.2. Durante l’utilizzo
    1.3. Dopo l’utilizzo
    1.4. Definizione di categoria di misura (Sovratensione)
2.  DESCRIZIONE GENERALE
    2.1. Descrizione funzioni
    2.2. Apertura coperchio valigia
3.  PREPARAZIONE ALL'UTILIZZO
    3.1. Controlli iniziali
    3.2. Alimentazione
    3.3. Conservazione
4.  NOMENCLATURA
    4.1. Descrizione dello strumento
    4.2. Accensione dello strumento
    4.3. Selezione funzione di misura
5.  DESCRIZIONE MENU PRINCIPALE
    5.1. Menu Memory
    5.2. Menu Operator
    5.3. Menu Language
    5.4. Menu Info Tester
    5.5. Menu Setup
        5.5.1. Menu Reset
        5.5.2. Menu EN50191
    5.6. Menu Sound
    5.7. Menu Autotest
6.  ISTRUZIONI OPERATIVE
    6.1. Continuità conduttori di protezione – Metodo RPE - 2WIRE
        6.1.1. Calibrazione terminali di misura
        6.1.2. Impostazione valore limite sulla misura 25A
        6.1.3. Situazioni anomale
    6.2. Continuità conduttori di protezione – Metodo RPE - 4WIRE
        6.2.1. Impostazione valore limite sulla misura
        6.2.2. Situazioni anomale
    6.3. Resistenza di Isolamento (MΩ)
        6.3.1. Situazioni anomale
    6.4. Test Rigidità Dielettrica (DIELECTRIC)
        6.4.1. Modi di funzionamento
        6.4.2. Tipologia corrente di scarica
        6.4.3. Dispositivi di sicurezza
        6.4.4. Situazioni anomale
    6.5. Test su differenziali (RCD)
        6.5.1. Situazioni anomale
    6.6. Impedenza anello di guasto (LOOP)
        6.6.1. Impostazione valore limite sulla misura
        6.6.2. Calcolo della corrente di cortocircuito presunta
        6.6.3. Situazioni anomale
    6.7. Resistenza globale di terra/Tensione di contatto (RA)
        6.7.1. Impostazione valore limite sulla misura
        6.7.2. Situazioni anomale
    6.8. Misura Tensione Residua (URES)
        6.8.1. Modo Lineare
        6.8.2. Modo Non Lineare
        6.8.3. Condizioni di Trigger
        6.8.4. Situazioni anomale
    6.9. Test funzionali (POWER)

FULLTEST3 IT - 2

    6.9.1. Situazioni anomale
    6.10. Senso ciclico delle fasi (PHASESEQ)
        6.10.1. Situazioni anomale
    6.11. Misura di Corrente con uso di trasduttore a pinza (ICLAMP)
        6.11.1. Situazioni anomale
    6.12. Misura di Corrente di dispersione (ILEAK)
        6.12.1. Situazioni anomale
    6.13. Esecuzione di un Autotest
7.  OPERAZIONI CON MEMORIA
    7.1. Salvataggio misure
    7.2. Salvataggio Autotest
    7.3. Richiamo dei risultati a display
8.  USO DEGLI ACCESSORI OPZIONALI
    8.1. Uso tastiera esterna
    8.2. Uso lettore di codici a barre
        8.2.1. Configurazione lettore di codice a barre
9.  AGGIORNAMENTO FIRMWARE STRUMENTO
10. MANUTENZIONE
    10.1. Generalità
    10.2. Pulizia dello strumento
    10.3. Sostituzione fusibili
    10.4. Fine vita
11. SPECIFICHE TECNICHE
    11.1. Caratteristiche tecniche
    11.2. Caratteristiche generali
    11.3. Accessori
12. ASSISTENZA
    12.1. Condizioni di garanzia
    12.2. Assistenza

FULLTEST3 IT - 3

# 1. PRECAUZIONI E MISURE DI SICUREZZA

ATTENZIONE
Per la sicurezza dell'operatore e per evitare di danneggiare lo strumento, seguire le procedure descritte nel presente manuale e leggere con particolare attenzione tutte le note precedute da questo simbolo

Lo strumento è stato progettato in conformità alle normative IEC/EN61557 - 1 ed IEC/EN61010 - 1 relative agli strumenti di misura elettronici. Prima e durante l'esecuzione delle misure, attenersi scrupolosamente alle seguenti indicazioni:

*   Non eseguire misure di tensione o corrente in ambienti umidi. Assicurarsi che l'umidità rientri nei limiti specificati al § 11.2
*   Non eseguire misure in presenza di gas o materiali esplosivi, combustibili o in ambienti polverosi
*   Evitare contatti con il circuito in esame, parti metalliche esposte, terminali di misura inutilizzati, prese di corrente, elementi di fissaggio, ecc. anche se non si stanno effettuando misure
*   Non eseguire alcuna misura qualora si riscontrino anomalie nello strumento come deformazioni, rotture, fuoriuscite di sostanze, assenza o parziale visualizzazione sui display, ecc.

Nel presente manuale e sullo strumento sono utilizzati i seguenti simboli:

| Simbolo                                 | Descrizione                                                                  |
| :-------------------------------------- | :--------------------------------------------------------------------------- |
| ![Danger Symbol]                        | Pericolo potenziale, attenersi alle istruzioni del manuale.                  |
| ![High Voltage Symbol]                  | Attenzione, tensione pericolosa. Rischio di shock elettrici.                 |
| UUT                                     | Oggetto in esame (Unit Under Test)                                           |
| ![IEC 60417-5031 Symbol (Double Insulated)] | Strumento con doppio isolamento                                              |
| ![IEC 60417-5017 Symbol (Protective Earth)] | Riferimento di terra (GND). Terminale di terra. Terminale per collegamento a terra. |

FULLTEST3 IT - 4

## 1.1. ISTRUZIONI PRELIMINARI

ATTENZIONE
Lo strumento deve essere collegato a una presa di alimentazione con terminale PE messo a terra. Diversamente, lo strumento visualizzerà il messaggio “PE SCOLLEGATO, SPEGNERE ADESSO” e non eseguirà nessuna misura

*   Il presente manuale contiene le informazioni necessarie per un uso e una manutenzione sicura dello strumento. Prima di usare lo strumento attenersi scrupolosamente alle istruzioni indicate in ciascuna sezione
*   La mancata osservazione delle avvertenze e/o istruzioni contenute nel manuale può danneggiare lo strumento o essere fonte di pericolo per l'operatore
*   Al fine di evitare shock elettrici, attenersi scrupolosamente alle normative di sicurezza e nazionali applicabili in materia di alta tensione quando si lavora con tensioni superiori a 60VDC o 50V (25V)rms AC. Il valore tra parentesi è valido in campi di applicazione speciali (ad esempio in campo medico)
*   La invitiamo a seguire le normali regole di sicurezza orientate a proteggerla contro correnti pericolose e a proteggere lo strumento da uso improprio.
*   Lo strumento è stato progettato per un utilizzo in un ambiente con livello di inquinamento 2.
*   Lo strumento può essere utilizzato per verifiche su impianti elettrici in CAT III 300V (verso Terra).
*   Non eseguire misure su circuiti che superino il limite di tensione specificato
*   Proteggere lo strumento contro un utilizzo errato. Solo gli accessori forniti a corredo dello strumento garantiscono gli standard di sicurezza. Essi devono essere in buone condizioni e sostituiti, se necessario, con modelli identici
*   Non eseguire misure in condizioni ambientali al di fuori delle limitazioni indicate nel presente manuale.
*   Prima di collegare i terminali di misura al circuito in esame, controllare che sia selezionata la funzione corretta.
*   Usare lo strumento esclusivamente in ambienti asciutti e puliti. Lo sporco e l'umidità riducono la resistenza di isolamento e ciò potrebbe comportare rischio di shock elettrici, in particolare in presenza di alta tensione.
*   Non usare mai lo strumento in caso di maltempo, ad esempio in presenza di rugiada o in caso di pioggia. Non usare lo strumento in caso di condensa dovuta a sbalzi di temperatura.
*   Iniziare qualsiasi serie di test con la misura della resistenza di terra
*   Alla resistenza di terra, la resistenza di isolamento e gli oggetti di misurazioni dielettriche non devono essere sotto tensione. Se necessario, controllare che l'oggetto non sia sotto tensione, ad esempio utilizzando un apposito tester.
*   Modificando lo strumento, la sicurezza operativa non è più garantita.

FULLTEST3 IT - 5

## 1.2. DURANTE L’UTILIZZO

ATTENZIONE
Un uso improprio può danneggiare lo strumento e/o i suoi componenti o essere fonte di pericolo per l'operatore

*   Lo strumento deve essere utilizzato solo da personale specializzato a conoscenza dei possibili rischi connessi all'uso di tensioni pericolose.
*   Collegare lo strumento solamente alla tensione di rete indicata sulla targhetta di omologazione.
*   Usare lo strumento entro gli intervalli operativi indicati nelle specifiche tecniche.
*   Scollegare i terminali dal circuito in esame prima di selezionare qualsiasi funzione.
*   Toccare esclusivamente l'apposita maniglia dei terminali e delle sonde. Non toccare mai le sonde direttamente.
*   Non toccare i terminali inutilizzati quando lo strumento è collegato a un circuito.
*   Evitare la misura di resistenza in presenza di tensioni esterne; anche se lo strumento è protetto, una tensione eccessiva potrebbe causare malfunzionamenti dello strumento.
*   Non aprire mai lo strumento! All'interno sono presenti tensioni pericolose!
*   È proibito collegare un terminale all'oggetto in esame lavorando al contempo con una sonda o tenere entrambe le sonde in una sola mano.
*   Usare le sonde di sicurezza esclusivamente servendosi della protezione contro il contatto o maneggiandole con entrambe le mani. Tenere sempre una sola sonda in una mano.
*   È proibito toccare l'oggetto in esame durante il test. Se necessario, prendere ulteriori precauzioni (ad es. copertura creata con tappetini isolanti) per proteggere l'operatore che esegue il test dal contatto involontario con l'oggetto in esame.

## 1.3. DOPO L’UTILIZZO

Scollegare tutti i terminali dal circuito in esame prima di spegnere lo strumento

FULLTEST3 IT - 6

## 1.4. DEFINIZIONE DI CATEGORIA DI MISURA (SOVRATENSIONE)

La normativa IEC/EN61010 - 1 "Prescrizioni di sicurezza per apparecchi elettrici di misura, controllo e per utilizzo in laboratorio, Parte 1: Prescrizioni generali", definisce cosa si intenda per categoria di misura, comunemente chiamata categoria di sovratensione. Al § 6.7.4: Circuiti di misura, essa recita:

I circuiti sono suddivisi nelle seguenti categorie di misura:

*   La Categoria di misura **IV** serve per le misure effettuate su una sorgente di un'installazione a bassa tensione.
    Esempi sono costituiti da contatori elettrici e da misure sui dispositivi primari di protezione dalle sovracorrenti e sulle unità di regolazione dell'ondulazione.
*   La Categoria di misura **III** serve per le misure effettuate in installazioni all'interno di edifici.
    Esempi sono costituiti da misure su pannelli di distribuzione, disgiuntori, cablaggi, compresi i cavi, le barre, le scatole di giunzione, gli interruttori, le prese di installazioni fisse e gli apparecchi destinati all'impiego industriale e altre apparecchiature, per esempio i motori fissi con collegamento ad impianto fisso.
*   La Categoria di misura **II** serve per le misure effettuate su circuiti collegati direttamente all'installazione a bassa tensione.
    Esempi sono costituiti da misure su apparecchiature per uso domestico, utensili portatili ed apparecchi similari.
*   La Categoria di misura **I** serve per le misure effettuate su circuiti non collegati direttamente alla RETE DI DISTRIBUZIONE.
    Esempi sono costituiti da misure su non derivati dalla RETE e derivati dalla RETE ma con protezione particolare (interna). In quest'ultimo caso le sollecitazioni da transitori sono variabili, per questo motivo la norma richiede che l'utente conosca la capacità di tenuta ai transitori dell'apparecchiatura.

FULLTEST3 IT - 7

# 2. DESCRIZIONE GENERALE

FULLTEST3 è uno strumento in grado di eseguire le verifiche di sicurezza elettrica delle componenti elettriche di macchine, stanze di controllo, quadri elettrici e per altri dispositivi in accordo alle normative IEC/EN60204 - 1 e IEC/EN61439 - 1. Le successive istruzioni operative sono riferite alla norma IEC/EN60204 - 1.

## 2.1. DESCRIZIONE FUNZIONI

*   **Continuità del Conduttore di Protezione**
    *   Metodo di misura a 2 o 4 fili
    *   Compensazione dei terminali di misura in caso di misura a 2 fili
    *   Tensione di prova a vuoto circa 6V AC
    *   Corrente di prova 200mA e 25 A AC
    *   Valore limite regolabile, segnale visivo e acustico in caso di superamento del valore.

    EN61557 - 4
    EN61439 - 1 - §10.5.2
    EN60204 - 1 - §18.2.2
    EN60598 - 1
    EN60335 - 1 - §27.5
    EN60335 - 1 - §A.1
    EN50106
    EN60950
    CEI 64 - 8/7 - CEI64/13

*   **Resistenza di Isolamento** (MΩ)
    *   Tensione di prova 100V, 250V, 500V e 1000V DC
    *   Modalità MAN, TIMER, AUTO
    *   Valore limite regolabile, segnale visivo e acustico in caso di superamento del valore

    EN61557 - 2
    CEI64 - 8
    CEI23 - 51
    CEI64 - 8/7 - CEI64/13
    EN61439 - 1 - §11.9
    EN60204 - 1
    EN60598 - 1

*   **Rigidità dielettrica** (Tensione applicata)
    *   Tensione di prova regolabile 250 V ÷ 5100V AC
    *   Corrente di scarica regolabile 1 mA ÷ 110 mA
    *   Segnale visivo e acustico in caso di superamento del valore limite
    *   Visualizzazione e intervento in base alla corrente reale o apparente
    *   Modo di misura MANUALE
    *   Modo di misura RAMPA 75% (aumento automatico predefinito della tensione di prova)
    *   Modo di misura RAMPA 50% (aumento automatico predefinito della tensione di prova)
    *   Modo di misura BURN
    *   Modo di misura PULSE
    *   Protezione contro l'uso non autorizzato (misura di sicurezza)
    *   Connettore spia rossa (misura di sicurezza).
    *   Connettore di ingresso di sicurezza (misura di sicurezza).

    EN61439 - 1 - §9.1
    EN60204 - 1 - §18.4
    EN60598 - 1
    EN60335 - 1 - §13.3
    EN60335 - 1 - §A.2
    EN50191

*   **Impedenza di anello di guasto** (LOOP)
    *   Misura di ZL/N, ZL/L e ZL/PE
    *   Campo di misura tensione 100 V ÷ 460V
    *   Calcolo IPSC
    *   Valore limite regolabile, segnale visivo e acustico in caso di superamento del valore.

    EN60204 - 1 - §18.2
    EN61557 - 3

*   **Senso ciclico delle fasi**
    *   Tensioni di rete UL1/2, UL2/3, UL3/1 visualizzate

    EN61557 - 7

FULLTEST3 IT - 8

*   **Prova differenziali** (RCD)
    *   Selezione RCD tipo AC, A e B
    *   RCD Generali, Selettivi e Ritardati
    *   IΔN = 10,30,100,300,500,650,1000mA
    *   Campo misura tensione 100 V ÷ 265V
    *   Tensione di contatto limite 25 o 50V
    *   Tempo di intervento a IΔN/2 (tipo AC, A e B).
    *   Tempo di intervento a IΔN (tipo AC, A e B).
    *   Tempo di intervento a 2IΔN (tipo AC, A e B).
    *   Tempo di intervento a 5IΔN (tipo AC e A) o a 4IΔN (tipo B)
    *   Prova rampa (tipo AC, A e B)
    *   Prova AUTO (tipo AC, A e B)
    *   Segnale visivo e acustico in caso di superamento del valore limite.

    EN61557 - 6

*   **Resistenza globale di terra senza intervento RCD**
    *   Corrente di prova selezionabile rispetto al differenziale in uso
    *   IΔN = 10,30,100,300,500,650, 1000 mA
    *   Misura con IΔN/2 (senza intervento del differenziale)
    *   Campo di misura tensione 100 V ÷ 265V
    *   Tensione di contatto UC rilevata durante la misura.
    *   Valore limite (RA) fissato a 25 o 50 V/IΔN
    *   Segnale visivo o acustico in caso di superamento del valore.

*   **Tensione residua** (tempo di scarica)
    *   Misura alla spina di corrente (metodo a 2 fili)
    *   Misura sui componenti interni (metodo a 4 fili)
    *   Tempo limite di scarica 1s o 5s
    *   Modo LINEARE o NON LINEARE
    *   Segnale visivo e acustico in caso di superamento del valore limite.

    EN60204 - 1 - §18.5

*   **Test funzionali** (su presa di prova)
    *   Potenza apparente PAPP
    *   Potenza attiva reale P
    *   Tensione di rete UL/N
    *   Corrente di carica IL
    *   Fattore di potenza PF
    *   Corrente di dispersione IPE (metodo differenziale).
    *   Scambio di posizione fasi interne.
    *   Valore limite (potenza apparente) regolabile, segnale visivo e acustico in caso di superamento del valore.

*   **Misura Corrente AC con pinza esterna** (opzionale)
    *   Misura in combinazione con la pinza di corrente HT96U
    *   Campi misura: 1A,100 A, 1000 A
    *   Valore limite regolabile, segnale visivo e acustico in caso di superamento del valore.

FULLTEST3 IT - 9

*   **Misura Corrente di dispersione**
    *   Misura della corrente IPE sulla presa di test (metodo differenziale)
    *   Misura con pinza di corrente tipo HT96U
    *   Valore limite regolabile, segnale visivo e acustico in caso di superamento del valore

*   **Caratteristiche Generali**
    *   Sistema operativo WINDOWS EMBEDDED COMPACT 7 supporta qualsiasi tipo di misura e operazione
    *   Funzionamento semplice ed intuitivo
    *   Misure TRMS.
    *   Spazio in memoria con 999 locazioni, 3 livelli più Commento
    *   Funzione AUTOTEST
    *   Data/ora di sistema
    *   Interfaccia integrata (USB 2.0) per il trasferimento a PC dei risultati delle misure
    *   Interfaccia separata (USB 2.0) per il collegamento tramite porta USB di lettore di codici a barre, tastiera, chiavetta di memoria, stampante o misuratore di impedenza IMP57
    *   Touch - screen grafico a colori 102×60 mm, 480×272pxl
    *   Case compatto con borsa per accessori esterna.
    *   Schemi di collegamento disponibili su strumento
    *   Protezione a fusibile in ingresso
    *   Software di gestione in dotazione
    *   Kit di accessori di misura in dotazione
    *   Comunicazione Blue tooth
    *   Funzione START/STOP e SAVE disponibili in remoto.

## 2.2. APERTURA COPERCHIO VALIGIA

Lo strumento è alloggiato in una robusta valigia di plastica rigida che ne consente un agevole trasporto. Osservare le seguenti istruzioni per l'apertura dello strumento:

1.  Posizionare lo strumento su di una superficie solida e orizzontale
2.  Esercitare con la mano una pressione sul coperchio (vedere Fig. 1 – parte 1)
3.  La valigia è aperta sbloccando i due fermi (vedere Fig. 1 – parte 2)
4.  Portare il coperchio in posizione verticale

Fig. 1: Apertura del coperchio dello strumento

FULLTEST3 IT - 10

# 3. PREPARAZIONE ALL'UTILIZZO

## 3.1. CONTROLLI INIZIALI

Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili affinché lo strumento potesse essere consegnato senza danni. Tuttavia si consiglia, di controllarlo sommariamente per accertare eventuali danni subiti durante il trasporto. Se si dovessero riscontrare anomalie contattare immediatamente la società HT o il rivenditore. Si consiglia inoltre di controllare che l'imballaggio contenga tutti gli accessori standard indicati nella packing list allegata. Qualora fosse necessario restituire lo strumento, si prega di seguire le istruzioni riportate al § 12.

## 3.2. ALIMENTAZIONE

Lo strumento deve essere collegato ad una presa di corrente ove sia presente il collegamento di terra. Per evitare qualsiasi rischio, lo strumento non consente di eseguire misure ove tale collegamento sia assente (vedere § 4.2).

ATTENZIONE
Lo strumento include filtri EMC/EMI che possono far intervenire protezioni differenziali (RCD) con corrente nominale di 30mA. E’ quindi raccomandato di alimentare lo strumento da prese protette con differenziali da 100mA o superiori

## 3.3. CONSERVAZIONE

Per garantire misure precise, dopo un lungo periodo di conservazione in condizioni ambientali estreme, attendere che lo strumento ritorni alle condizioni normali di funzionamento (vedere il § 11.2)

FULLTEST3 IT - 11

# 4. NOMENCLATURA

## 4.1. DESCRIZIONE DELLO STRUMENTO

Fig. 2: Descrizione dello strumento

LEGENDA:

1.  Indicazioni per uso dello strumento
2.  Fusibile F3 – Protezione misure LOOP, Ra, RCD
3.  Fusibile F2 – Protezione misura POTENZA, RPE e RIGIDITÀ DIELETTRICA
4.  Fusibile F1 – Protezione POTENZA, RPE e RIGIDITÀ DIELETTRICA
5.  Tasto accensione ON/OFF
6.  Connettore per adattatore comando remoto START/SAVE (accessorio opzionale FT3RMTCT)
7.  Connettore SAFETY INPUT per collegamento interruttore di sicurezza esterno (accessorio opzionale FT3SFTSW). Disabilita la misura di RIGIDITÀ DIELETTRICA in caso l'interruttore sia aperto

FULLTEST3 IT - 12

8.  Connettore per collegamento di lampada di segnalazione esterna durante i test di RIGIDITÀ DIELETTRICA (accessorio opzionale FT3R - GLP)
9.  Connettore USB1 per collegamento con PC
10. Connettori USB2 e USB3 per collegamento di pen drive USB, lettore di codici a barre USB (accessorio opzionale FT3BARCR), stampante USB (accessorio opzionale FT3MPT2), tastiera USB (accessorio opzionale FT3KBDEN) o misuratore di impedenza LOOP ad alta risoluzione (accessorio opzionale IMP57)
11. Terminale negativo (-) per misura di Isolamento
12. Terminale negativo (+) per misura di Isolamento
13. Terminale RPE per misura 2 - fili
14. Terminale di tensione SENSE per test RPE 4 - fili
15. Fusibile F4 – Protezione misure RPE
16. Terminale di tensione SENSE per test RPE 4 - fili
17. Terminale RPE per misura 2 - fili
18. Tasto FUNC per selezione misure
19. Tasto SAVE per salvataggio risultati misure
20. Tasto START/STOP per avvio/arresto misure
21. Tasto RCL per richiamo a display risultati salvati
22. Tasto MENU per accesso al Menu Generale
23. Tasto EXIT
24. Display LCD TFT touch - screen
25. Presa di prova per misure di POTENZA e CORRENTE DISPERSA sulla spina
26. Connettore per misura corrente di dispersione con pinza esterna (accessorio opzionale HT96U)
27. Terminale di misura URES per misura tempo di scarica
28. Terminale di misura URES per misura tempo di scarica
29. Terminale L/TRIG/L1 per misure LOOP, RA, RCD, SENSO CICLICO e URES
30. Terminale PE/L3 per misure LOOP, RA, RCD e SENSO CICLICO
31. Terminale N/TRIG/L2 per misure LOOP, RCD, SENSO CICLICO e URES
32. Terminale per test RIGIDITÀ DIELETTRICA - Tensione di prova 2.51 ÷ 5.10kV
33. Terminale per test RIGIDITÀ DIELETTRICA - Tensione di prova 0.81 ÷ 2.50 kV
34. Terminale per test RIGIDITÀ DIELETTRICA – Tensione di prova 0.25 ÷ 0.80kV
35. Spia segnalazione test RIGIDITÀ DIELETTRICA
36. Terminale di prova COM per test RIGIDITÀ DIELETTRICA.

FULLTEST3 IT - 13

## 4.2. ACCENSIONE DELLO STRUMENTO

1.  Collegare lo strumento ad una presa di alimentazione 230V 50/60Hz dotata di terminale di terra
2.  Accendere lo strumento tramite il tasto ON/OFF (vedere Fig. 2 – parte 5)
3.  Lo strumento esegue il caricamento del Firmware (FW) (circa 30s) e mostra l'ultima videata di misura utilizzata. Un segnale acustico è emesso appena lo strumento è pronto per le misure

ATTENZIONE
Nel caso in cui nella presa di alimentazione non sia presente (o non collegato) il riferimento di terra il messaggio PE SCOLLEGATO sarà mostrato a display e lo strumento non eseguirà alcuna misura. In questo caso spegnere lo strumento e controllare la presa di alimentazione

## 4.3. SELEZIONE FUNZIONE DI MISURA

1.  Premere il tasto FUNC. Le seguenti videate sono mostrate a display:

Fig. 3: Videata selezione funzioni

2.  Toccare sul touch - screen la funzione desiderata. La videata corrispondente (ex: RPE - 2WIRE – vedere Fig. 3) è mostrata a display

Fig. 4: Videata base funzione RPE - 2WIRE

FULLTEST3 IT - 14

# 5. DESCRIZIONE MENU PRINCIPALE

Premere il tasto MENU per entrare nel MENU PRINCIPALE dello strumento. La seguente videata è mostrata a display

Fig. 5: Videata MENU PRINCIPALE

Premere il tasto virtuale del sottomenù desiderato per ulteriori impostazioni.

## 5.1. MENU MEMORY

In questa sezione sono presenti i seguenti comandi:

*   **INFO MEM** (MEM INFO) → Visualizzazione del numero delle locazioni di memoria occupate e totali. Ciascun risultato di misura salvato occupa una locazione di memoria

    Fig. 6: Menu MEMORIA

*   **CANCELLA** (CLEAR) → consente di eseguire la cancellazione dei dati salvati nella memoria. È possibile cancellare l'intera memoria (TOTAL), l'ultimo risultato salvato (LAST RESULT) oppure gli AUTOTEST inutilizzati (vedere § 6.13). Confermare la cancellazione premendo il tasto virtuale SÌ

    Fig. 7: Menu CANCELLA

*   **USB** → Per trasferire i dati salvati su di una chiavetta USB è necessario usare il menù USB. Inserire la chiavetta USB nella presa USB2 o USB3, quindi premere il tasto virtuale USB. Confermare il trasferimento premendo il tasto SI

FULLTEST3 IT - 15

## 5.2. MENU OPERATOR

In questa sezione è possibile definire il nome dell’operatore che sarà incluso all’interno del report delle prove scaricato a PC.

Fig. 8: Menu OPERATORE

*   Controllare la lista degli operatori disponibili utilizzando i tasti freccia virtuali ▼ e ▲ (se ci sono più di 4 operatori inseriti)
*   Selezionare l'operatore desiderato premendo il tasto virtuale corrispondente (es. Default). L'operatore individuato viene selezionato e verrà utilizzato durante le misure
*   Premere il tasto virtuale ENTER per confermare la selezione e per tornare al MENÙ PRINCIPALE

Per aggiungere un nuovo operatore:

1.  Aprire il menù OPERATORE e premere il tasto virtuale AGGIUNGI NUOVO (ADD NEW). La videata di Fig. 8 – parte destra è mostrata a display
2.  Digitare il nome dell’operatore usando la tastiera virtuale
3.  Confermare il nome inserito premendo il tasto virtuale ENTER. L'ultimo operatore inserito è mostrato a display

Per cancellare un operatore:

1.  Aprire il menù OPERATORE, selezionare l'operatore che si desidera cancellare e premere il tasto virtuale CANCELLA (DELETE). Confermare la cancellazione premendo il tasto virtuale SÌ

## 5.3. MENU LANGUAGE

In questa sezione è possibile definire la lingua di sistema tra quelle disponibili

Fig. 9: Menu LINGUA

FULLTEST3 IT - 16

## 5.4. MENU INFO TESTER

Il menù INFO TESTER mostra i dati di base dello strumento: versione Firmware, versione HW, numero di serie e nome modello

Fig. 10: Menu LINGUA *(NOTE: This Figure description is likely incorrect based on context, should be "Menu INFO TESTER")*

## 5.5. MENU SETUP

In questa sezione è possibile impostare il valore di parametri usati nelle misure eseguite dallo strumento. La seguente videata è mostrata a display

Fig. 11: Menu IMPOSTAZIONI

Le seguenti opzioni sono disponibili:

*   **LEVEL NAMES** → Sono disponibili 3 livelli quando si salvano i risultati dei test: LEVEL1, LEVEL2 e LEVEL3 i cui nomi sono liberamente modificabili (max 12 caratteri) usando la tastiera virtuale interna (vedere Fig. 12) e sono utilizzabili per il salvataggio dei dati delle misure eseguire con strumento alla pressione del tasto SAVE (vedere § 7.1)

    Fig. 12: Menu NOMI LIVELLI

FULLTEST3 IT - 17

*   **DATA/ORA** (DATE/TIME) → Usare il menù DATA/ORA per impostare la data e l'ora dello strumento (vedere Fig. 13). Inserire la data e l'ora correnti utilizzando i tasti , e 0 ... 9 . Confermare premendo il tasto virtuale ENTER

    Fig. 13: Menu DATA/ORA

*   **TENSIONE DI CONTATTO** (CONTACT VOL.) → Usare questo menù per selezionare la tensione di contatto limite utilizzata nelle misure RCD ed RA. Le opzioni possono essere 25V o 50V (vedere Fig. 14)

    Fig. 14: Menu TENSIONE DI CONTATTO

*   **TENSIONE NOMINALE** (NOMINAL VOL.) → Usare questo menù per selezionare la tensione nominale di rete utilizzata nelle misure LOOP e URES (vedere Fig. 15). Nelle misure LOOP è utilizzata per il calcolo della corrente di cortocircuito presunta (vedere § 6.6) In funzione URES (solo modalità lineare) la tensione nominale viene utilizzata per riferire i valori misurati (vedere § 6.8.1).

    Fig. 15: Menu TENSIONE NOMINALE

FULLTEST3 IT - 18

### 5.5.1. Menu Reset

Il menu RESET consente di ripristinare i parametri di default dello strumento. Confermare l’operazione premendo il pulsante virtuale SI o premere il tasto fisico EXIT per uscire da menu. Lo strumento deve essere spento e riacceso. Nelle seguenti tabelle sono riportati i valori dei parametri dopo l’operazione di Reset. L’operazione di Reset NON cancella i dati salvati nella memoria interna

| Funzione      | Parametro                                                                 | Valore                   |
| :------------ | :------------------------------------------------------------------------ | :----------------------- |
| **GENERAL**   | - OPERATORE                                                               | Default                  |
|               | - LINGUA                                                                  | ITALIAN                  |
|               | - TENSIONE DI CONTATTO                                                    | 50V                      |
|               | - TENSIONE NOMINALE                                                       | 230V                     |
|               | - INGRESSO SICUREZZA                                                      | ABILITATA                |
|               | - SUONO                                                                   | ON                       |
| **RPE - 2WIRE** | - Im NOM                                                                  | 200mA                    |
|               | - Valore limite (200 mA)                                                  | 0.30 Ω                   |
|               | - MODO                                                                    | MANUAL                   |
|               | - CAL(200 mA)                                                             | 0.00 Ω                   |
|               | - Valore limite 1 (200 mA)                                                | 0.30 Ω                   |
|               | - Valore limite 2 (200 mA)                                                | 1.00 Ω                   |
|               | - Valore limite 3 (200 mA A)                                              | 5.00 Ω                   |
|               | - Valore limite 4 (200 mA)                                                | 50.0 Ω                   |
|               | - Modalità limite (25 A)                                                  | STANDARD                 |
|               | - Valore limite (25 A, limite STANDARD)                                   | 0.30 Ω                   |
|               | - Valore limite 1 (25 A, limite STANDARD)                                 | 0.30 Ω                   |
|               | - Valore limite 2 (25 A, limite STANDARD)                                 | 1.00 Ω                   |
|               | - Valore limite 3 (25 A, limite STANDARD)                                 | 5.00 Ω                   |
|               | - Valore limite 4 (25 A, limite STANDARD)                                 | 10.0 Ω                   |
|               | - LUNGHEZZA                                                               | 2 m                      |
|               | - LUNGHEZZA 1                                                             | 2 m                      |
|               | - LUNGHEZZA 2                                                             | 3 m                      |
|               | - LUNGHEZZA 3                                                             | 10 m                     |
|               | - LUNGHEZZA 4                                                             | 100 m                    |
|               | - SEZIONE                                                                 | 1 mm²                    |
|               | - SEZIONE 1                                                               | 1 mm²                    |
|               | - SEZIONE 2                                                               | 2,5 mm²                  |
|               | - SEZIONE 3                                                               | 10 mm²                   |
|               | - SEZIONE 4                                                               | 35 mm²                   |
|               | - MAT.                                                                    | Cu                       |
|               | - ZLINEA                                                                  | 0.100 Ω                  |
|               | - ZLINEA 1                                                                | 0.100 Ω                  |
|               | - ZLINEA 2                                                                | 0.300 Ω                  |
|               | - ZLINEA 3                                                                | 0.500 Ω                  |
|               | - ZLINEA 4                                                                | 1.000 Ω                  |
|               | - PROTEZIONE                                                              | MCB B                    |
|               | - IN (qualsiasi protezione)                                               | 6 A                      |
|               | - IN (qualsiasi protezione) 1                                             | 6 A                      |
|               | - IN (qualsiasi protezione) 2                                             | 16 A                     |
|               | - IN (qualsiasi protezione) 3                                             | 25 A                     |
|               | - IN (qualsiasi protezione) 4                                             | 32 A                     |
|               | - TIMER                                                                   | 3 s                      |
|               | - TIMER 1                                                                 | 3 s                      |
|               | - TIMER 2                                                                 | 10 s                     |
|               | - TIMER 3                                                                 | 30 min                   |
|               | - TIMER 4                                                                 | 60 min                   |
|               | - CAL (25 A)                                                              | 0.000 Ω                  |

FULLTEST3 IT - 19

| Funzione       | Parametro                                       | Valore           |
| :------------- | :---------------------------------------------- | :--------------- |
| **RPE - 4WIRE** | - Valore limite (limite STANDARD)               | 0.300 Ω          |
|                | - MODO                                          | MAN              |
|                | - Valore limite 1 (limite STANDARD)             | 0.300 Ω          |
|                | - Valore limite 2 (limite STANDARD)             | 1.000 Ω          |
|                | - Valore limite 3 (limite STANDARD)             | 5.00 Ω           |
|                | - Valore limite 4 (limite STANDARD)             | 10.00 Ω          |
|                | - LUNGHEZZA                                     | 2 m              |
|                | - LUNGHEZZA 1                                   | 2 m              |
|                | - LUNGHEZZA 2                                   | 3 m              |
|                | - LUNGHEZZA 3                                   | 10 m             |
|                | - LUNGHEZZA 4                                   | 100 m            |
|                | - SEZIONE                                       | 1 mm²            |
|                | - SEZIONE 1                                     | 1 mm²            |
|                | - SEZIONE 2                                     | 2.5 mm²          |
|                | - SEZIONE 3                                     | 10 mm²           |
|                | - SEZIONE 4                                     | 35 mm²           |
|                | - MAT.                                          | Cu               |
|                | - Z LINEA                                       | 0.100 Ω          |
|                | - Z LINEA 1                                     | 0.100 Ω          |
|                | - Z LINEA 2                                     | 0.300 Ω          |
|                | - Z LINEA 3                                     | 0.500 Ω          |
|                | - Z LINEA 4                                     | 1.000 Ω          |
|                | - PROTEZIONE                                    | MCB B            |
|                | - I N (qualsiasi protezione)                    | 6 A              |
|                | - I N (qualsiasi protezione) 1                  | 6 A              |
|                | - I N (qualsiasi protezione) 2                  | 16 A             |
|                | - I N (qualsiasi protezione) 3                  | 25 A             |
|                | - I N 4                                         | 32 A (35 A per protezione gM) |
|                | - TIMER                                         | 3 s              |
|                | - TIMER 1                                       | 3 s              |
|                | - TIMER 2                                       | 10 s             |
|                | - TIMER 3                                       | 30 min           |
|                | - TIMER 4                                       | 60 min           |
| **R ISO**      | - MODO                                          | MANUALE          |
|                | - Um NOM                                        | 500 V            |
|                | - Valore limite                                 | 0.25 M Ω         |
|                | - TIMER                                         | 5 s              |
|                | - TIMER 1                                       | 5 s              |
|                | - TIMER 2                                       | 10 s             |
|                | - TIMER 3                                       | 1 min            |
|                | - TIMER 4                                       | 10 min           |
|                | - Valore limite 1                               | 0.25 M Ω         |
|                | - Valore limite 2                               | 0.30 M Ω         |
|                | - Valore limite 3                               | 1.00 M Ω         |
|                | - Valore limite 4                               | 2.00 M Ω         |

FULLTEST3 IT - 20

| Funzione             | Parametro                                   | Valore             |
| :------------------- | :------------------------------------------ | :----------------- |
| **RIGIDITÀ DIELETTRICA** | - MODO                                      | MANUALE            |
|                      | - U TEST NOM                                | 250 V              |
|                      | - Valore limite                             | 1 mA               |
|                      | - CARATTERISTICA                            | IAPP               |
|                      | - U TEST NOM 1                              | 250 V              |
|                      | - U TEST NOM 2                              | 1000 V             |
|                      | - U TEST NOM 3                              | 2500 V             |
|                      | - U TEST NOM 4                              | 3500 V             |
|                      | - RAMP TIMER                                | 10 s               |
|                      | - RAMP TIMER 1                              | 10 s               |
|                      | - RAMP TIMER 2                              | 30 s               |
|                      | - RAMP TIMER 3                              | 1 min              |
|                      | - RAMP TIMER 4                              | 10 min             |
|                      | - Valore limite 1                           | 1 mA               |
|                      | - Valore limite 2                           | 10 mA              |
|                      | - Valore limite 3                           | 50 mA              |
|                      | - Valore limite 4                           | 100 mA             |
| **RCD**              | - TIPO                                      | AC GEN             |
|                      | - I Δ N                                     | 30 mA              |
|                      | - MISURA                                    | t/I Δ N            |
|                      | - POL                                       | POS                |
|                      | - RITARDO                                   | 100 ms             |
|                      | - RITARDO 1                                 | 100 ms             |
|                      | - RITARDO 2                                 | 200 ms             |
|                      | - RITARDO 3                                 | 300 ms             |
|                      | - RITARDO 4                                 | 700 ms             |
| **LOOP**             | - MODO                                      | LOOPL/N            |
|                      | - Modalità limite                           | STD                |
|                      | - Ib                                        | 1 kA               |
|                      | - Ib 1                                      | 1 kA               |
|                      | - Ib 2                                      | 3 kA               |
|                      | - Ib 3                                      | 6 kA               |
|                      | - Ib 4                                      | 25 kA              |
|                      | - PROTEZIONE                                | MCB B              |
|                      | - I N (qualsiasi protezione)                | 6 A                |
|                      | - I N (qualsiasi protezione) 1              | 6 A                |
|                      | - I N (qualsiasi protezione) 2              | 16 A               |
|                      | - I N (qualsiasi protezione) 3              | 25 A               |
|                      | - I N (qualsiasi protezione) 4              | 32 A               |
|                      | - WIRE                                      | Cu                 |
|                      | - ISOLANTE                                  | PVC                |
|                      | - SEZIONE                                   | 1 mm²              |
|                      | - SEZIONE 1                                 | 1 mm²              |
|                      | - SEZIONE 2                                 | 2.5 mm²            |
|                      | - SEZIONE 3                                 | 10 mm²             |
|                      | - SEZIONE 4                                 | 35 mm²             |
|                      | - N                                         | 1                  |
|                      | - N 1                                       | 1                  |
|                      | - N 2                                       | 10                 |
|                      | - N 3                                       | 50                 |
|                      | - N 4                                       | 75                 |
|                      | - T SET                                     | 0.2 s              |
| **R A**              | - Corrente differenziale nominale I Δ N     | 30 mA              |

FULLTEST3 IT - 21

| Funzione     | Parametro                                    | Valore         |
| :----------- | :------------------------------------------- | :------------- |
| **U RES**    | - MODO                                       | LINEARE        |
|              | - CON                                        | PLUG           |
|              | - Limit t                                    | 5 s            |
| **POTENZA**  | - TIMER                                      | 10 s           |
|              | - LIMITE potenza apparente                   | 6 VA           |
|              | - L POS                                      | DESTRA         |
|              | - TIMER 1                                    | 10 s           |
|              | - TIMER 2                                    | 30 s           |
|              | - TIMER 3                                    | 1 min          |
|              | - TIMER 4                                    | 10 min         |
|              | - LIMITE potenza apparente 1                 | 6 VA           |
|              | - LIMITE potenza apparente 2                 | 100 VA         |
|              | - LIMITE potenza apparente 3                 | 1.00 kVA       |
|              | - LIMITE potenza apparente 4                 | 5.06 kVA       |
| **ROTAZIONE FASI** | - Nessuna                                  |                |
| **I CLAMP**  | - RANGE                                      | 1000 mA        |
|              | - LIMITE valore (range 1000 mA)              | 3.5 mA         |
|              | - LIMITE valore 1 (range 1000 mA)            | 3.5 mA         |
|              | - LIMITE valore 2 (range 1000 mA)            | 10.0 mA        |
|              | - LIMITE valore 3 (range 1000 mA)            | 100 mA         |
|              | - LIMITE valore 4 (range 1000 mA)            | 1000 mA        |
|              | - LIMITE valore (range 100.0 A)              | 6.0 A          |
|              | - LIMITE valore 1 (range 100.0 A)            | 6.0 A          |
|              | - LIMITE valore 2 (range 100.0 A)            | 16.0 A         |
|              | - LIMITE valore 3 (range 100.0 A)            | 50.0 A         |
|              | - LIMITE valore 4 (range 100.0 A)            | 100.0 A        |
|              | - LIMITE valore (range 1000 A)               | 6 A            |
|              | - LIMITE valore 1 (range 1000 A)             | 6 A            |
|              | - LIMITE valore 2 (range 1000 A)             | 160 A          |
|              | - LIMITE valore 3 (range 1000 A)             | 500 A          |
|              | - LIMITE valore 4 (range 1000 A)             | 1000 A         |
| **I LEAK**   | - MODO                                       | PINZA          |
|              | - RANGE                                      | 1000 mA        |
|              | - LIMITE valore (range 1000 mA)              | 3.5 mA         |
|              | - LIMITE valore 1 (PINZA range 1000 mA)      | 3.5 mA         |
|              | - LIMITE valore 2 (PINZA range 1000 mA)      | 10.0 mA        |
|              | - LIMITE valore 3 (PINZA range 1000 mA)      | 100 mA         |
|              | - LIMITE valore 4 (PINZA range 1000 mA)      | 1000 mA        |
|              | - LIMITE valore (PINZA range 100.0 A)        | 6.0 A          |
|              | - LIMITE valore 1 (PINZA range 100.0 A)      | 6.0 A          |
|              | - LIMITE valore 2 (PINZA range 100.0 A)      | 16.0 A         |
|              | - LIMITE valore 3 (PINZA range 100.0 A)      | 50.0 A         |
|              | - LIMITE valore 4 (PINZA range 100.0 A)      | 100.0 A        |
|              | - LIMITE valore (PINZA range 1000 A)         | 6 A            |
|              | - LIMITE valore 1 (PINZA range 1000 A)       | 6 A            |
|              | - LIMITE valore 2 (PINZA range 1000 A)       | 160 A          |
|              | - LIMITE valore 3 (PINZA range 1000 A)       | 500 A          |
|              | - LIMITE valore 4 (PINZA range 1000 A)       | 1000 A         |
|              | - LIMITE valore (PRESA)                      | 3.50 mA        |
|              | - LIMITE valore 1 (PRESA)                    | 3.50 mA        |
|              | - LIMITE valore 2 (PRESA)                    | 10.00 mA       |
|              | - LIMITE valore 3 (PRESA)                    | 1.0 A          |
|              | - LIMITE valore 4 (PRESA)                    | 10.0 A         |

FULLTEST3 IT - 22

### 5.5.2. Menu EN50191

ATTENZIONE
Il menu “EN50191” è disponibile solo per strumenti con versione FW B30.Mxx.Vxx o superiore

La normativa EN50191 prevede l’introduzione di particolari procedure per garantire la sicurezza dell’operatore durante l’esecuzione di prove di rigidità dielettrica con corrente di prova superiore a 3mA. L’utente potrà abilitare o disabilitare l’applicazione dei vincoli di sicurezza previsti dalla norma EN50191 a seconda delle proprie esigenze e procedure di prova. Lo stato del suddetto parametro influenza solamente la funzione RIGIDITA.

DECLINAZIONE DI RESPONSABILITA

*   Considerando che lo strumento può essere utilizzato anche per eseguire prove che non obbligano la rispondenza ai requisiti imposti dalla norma EN50191, lo strumento viene pre - impostato in fabbrica con il parametro “EN50191” disabilitato
*   L’utente DEVE abilitare il suddetto parametro qualora le sue procedure di prova richiedano precauzione addizionali per la sicurezza (tipicamente se la corrente di prova delle misura di rigidità dielettrica è ≥3mA)
*   Il costruttore declina ogni responsabilità, diretta ed indiretta, derivante da
    *   Inosservanza delle istruzioni ed uso della macchina diverso da quello previsto nel manuale
    *   Uso da parte di personale che non abbia letto e compreso il contenuto del manuale
    *   Uso non conforme alle normative specifiche vigenti

Fig. 16: Menù INGRESSO DI SICUREZZA

Parametro “EN50191” **abilitato**: la funzione RIGIDITA è utilizzabile solo se l’operatore inserisce la password (non modificabile) `8314` e (per Tensioni di prova ≥ 1000V) il contatto di sicurezza “SAFETY INPUT” è chiuso. La password è richiesta solo all’atto dell’esecuzione della prima prova dielettrica dopo l’accensione dello strumento o dell’abilitazione del parametro EN50191

Parametro “EN50191” **disabilitato**: la funzione RIGIDITA è sempre utilizzabile senza ulteriori vincoli di sicurezza imposti (no password e contatto di sicurezza)

FULLTEST3 IT - 23

NOTA
La normativa EN50191 prevede anche, durante l’esecuzione di prove di rigidità dielettrica, la restrizione all’accesso della zona prove e l’utilizzo di lampade per la segnalazione delle condizioni di pericolo. A tale proposito sono disponibili i seguenti accessori opzionali:

*   **FT3SFTSW** → contatto di sicurezza (con connettore e cavo) da fissare alla porta della zona prove
*   **FT3R - GLP** → lampada rossa/verde per strumenti con versione HW 70 o superiore (dal S/N: 16101107)
*   **FT3REDLP** → lampada rossa per strumenti con versione precedente a HW 70

Usare il menù sicurezza per impostare lo stato dell'ingresso di sicurezza in funzione di misura di RIGIDITÀ DIELETTRICA. L'ingresso di sicurezza può essere abilitato o disabilitato. Ingresso di sicurezza **disabilitato**: La prova di rigidità DIELETTRICA è attiva indipendentemente dallo stato dell'ingresso di sicurezza (l'interruttore di sicurezza può essere aperto o chiuso o non collegato). Ingresso di sicurezza **abilitato**: La prova di RIGIDITÀ DIELETTRICA è attiva solo se lo stato dell'ingresso di sicurezza è sufficiente (l'interruttore di sicurezza deve essere chiuso). Questo stato dell'ingresso di sicurezza non influenza alcun'altra funzione ad eccezione della prova di RIGIDITÀ DIELETTRICA.

## 5.6. MENU SOUND

Usare il menù SUONO per attivare /disattivare il segnale acustico alla pressione dei tasti.

Fig. 17: Menù SUONO

FULLTEST3 IT - 24

## 5.7. MENU AUTOTEST

Il menù AUTO TEST permette di definire gruppi di test personalizzati (Autotest), dello stesso tipo o diversi (max 8 test per ogni Autotest), che possono essere attivate una dopo l’altra tramite il tasto START/STOP in modo sequenziale da parte dell’operatore senza la necessità di richiamare ogni volta la funzione di misura. E’ possibile definire un numero indefinito di Autotest fino al riempimento della memoria interna. I campi tipici di applicazione di questa funzione sono:

*   Esecuzione rapida di test ripetitivi dello stesso tipo
*   Controlli di fine linea su macchine

Come definire un Autotest

1.  Premere il tasto MENU e toccare l’icona AUTO TEST. La seguente videata è mostrata a display

    Fig. 18: Menù AUTOTEST

2.  Premere il tasto ADD NEW per aggiungere un nuovo Autotest. La seguente videata è mostrata a display

    Fig. 19: Menù AUTOTEST – Definizione nuovo Autotest

3.  Digitare il nome dell’Autotest (max 9 caratteri) usando la tastiera virtuale e confermare con tasto ENTER Il nuovo Autotest sarà inserito nella lista in modo sequenziale

Come includere test all’interno dell’Autotest

4.  Premere il tasto EDIT per aprire l’Autotest selezionato e includere l’insieme dei gruppi di test desiderato (max 8 test) oppure per modificarne uno esistente (vedere Fig. 20)

FULLTEST3 IT - 25

Fig. 20: Menù AUTOTEST – Inserimento misure nell’Autotest

5.  Premere il tasto ADD STEPS o toccare l’Autotest selezionato per aggiungere un test. Lo strumento propone la videata di Fig. 21 – parte sinistra

Fig. 21: Menù AUTOTEST – Selezione misure per aggiunta in Autotest

6.  Toccare il test da inserire (ex: RCD) notando la presenza del numero di test attualmente inclusi nell’Autotest (ex: 3). Lo strumento mostra la videata della funzione selezionata (vedere Fig. 21 – parte destra). Eseguire la programmazione desiderata e toccare il tasto ADD per aggiungere il test
7.  Ripetere le stesse operazioni per aggiungere max 8 test e toccare il tasto FINISH (vedere Fig. 21 – parte sinistra) per terminare l’inclusione. Notare l’aggiornamento dell’Autotest
8.  Toccare il tasto EDIT per modificare i parametri del test selezionato. La seguente videata è mostrata a display

Fig. 22: Menù AUTOTEST – Modifica test da aggiungere all’Autotest

9.  Eseguire le variazioni desiderate e toccare il tasto FINISH per tornare alla videata precedente
10. Toccare il tasto RENAME per rinominare il nome dell’Autotest
11. Toccare il tasto DELETE per cancellare il test selezionato all’interno dell’Autotest
12. Toccare il tasto USE per eseguire l’Autotest (vedere § 6.13)

FULLTEST3 IT - 26

Come copiare un Autotest

13. Selezionare un Autotest e toccare il tasto COPY (vedere Fig. 18). La seguente videata è mostrata a display

Fig. 23: Menù AUTOTEST – Copia Autotest

14. Rinominare l’Autotest e confermare con il tasto ENTER per aggiungere il nuovo all’elenco

Come includere un messaggio Visualizza

All’interno di una sequenza di Autotest è possibile includere un messaggio di “Visualizza” risultato finale dell’insieme di prove eseguite (test Passato/Fallito). Operare come segue:

15. Premere il tasto ADD STEPS o toccare l’Autotest selezionato per aggiungere un test. Lo strumento propone la videata di Fig. 21 – parte sinistra. Toccare il tasto VISUAL. La seguente videata è mostrata a display

Fig. 24: Menù AUTOTEST – Aggiunta messaggio Visualizza

16. Toccare il tasto ADD per aggiungere il messaggio OK (PASS) o NO OK (FAIL) all’interno dell’Autotest selezionato. Tale messaggio sarà presente al termine dell’esecuzione dell’Autotest (vedere § 6.13)

Come cancellare un Autotest

17. Selezionare un Autotest e toccare il tasto DELETE (vedere Fig. 18). Lo strumento fornisce un messaggio di conferma prima di eseguire la cancellazione

ATTENZIONE
Un Autotest può essere cancellato solo se NON esistono risultati salvati nella memoria dello strumento per effetto di una esecuzione dello stesso. Lo strumento fornisce in tal caso un messaggio a display

FULLTEST3 IT - 27

# 6. ISTRUZIONI OPERATIVE

## 6.1. CONTINUITÀ CONDUTTORI DI PROTEZIONE – METODO RPE - 2WIRE

In accordo alla normativa IEC/EN60204 - 1, la continuità del circuito di protezione tra il terminale PE e i punti corrispondenti del sistema di conduttori di protezione deve essere controllata immettendo una corrente di prova compresa tra circa 0.2A e 10A AC. Lo strumento permette di eseguire il test con corrente di prova di 200mA e 25A (per resistenza tra i terminali <0.1Ω) o 10A (per resistenza tra i terminali <0.5Ω) con riconoscimento automatico.

1.  Premere il tasto FUNC e selezionare la funzione RPE - 2WIRE. La seguente videata è mostrata a display

    Fig. 25: Videata iniziale funzione RPE - 2WIRE

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 1) ed eseguire la programmazione desiderata

    Tabella 1: Parametri impostabili per la funzione RPE - 2WIRE

    | Parametro        | Descrizione                                                                                                                                                                                                                           | Valore                                                                                                                                                                                                                                    |
    | :--------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | **Im NOM**       | Corrente di prova nominale                                                                                                                                                                                                            | 200mA o 25A AC (R<0.1 Ω) 200mA o 10A AC (R<0.5 Ω)                                                                                                                                                                                         |
    | **LIMIT**        | Soglia limite di riferimento                                                                                                                                                                                                          | STANDARD 0.01 Ω ÷ 200.0 Ω (200mA) 0.01 Ω ÷ 20.0 Ω (25A) 60204 SET L (25A) 60204 SET Z (25A)                                                                                                                                              |
    | **60204 SET L**  | Test con corrente di prova 25A (vedere § 6.1.2)                                                                                                                                                                                         | Lunghezza: 0.1m ÷ 999.9m Sezione: 1, 1.5, 2.5, 4, 6, 10, 16, 25, 35, 50, 70, 95, 120, 150, 185, 240, 300, 400, 500, 630 mm² Materiale: Cu (Rame) o Al (Alluminio)                                                                            |
    | **60204 SET Z**  |                                                                                                                                                                                                                                       | ZLine: 0.001 Ω ÷ 2.000 Ω Protezione MCB: B, C, D, K Protezione Fusibile: gG, aM Corrente nominale protezione (vedere § 6.1.2)                                                                                                           |
    | **MODE**         | Modo di misura                                                                                                                                                                                                                        | Manuale Timer (2s ÷ 60min) → Itest <25A Timer (2s ÷ 5min) → Itest = 25A                                                                                                                                                                    |
    | **CAL**          | Calibrazione terminali di misura fino a 5.00 Ω                                                                                                                                                                                          |                                                                                                                                                                                                                                           |

FULLTEST3 IT - 28

### 6.1.1. Calibrazione terminali di misura

Al fine di evitare che la resistenza dei terminali di misura non influenzi il risultato del test occorre eseguire la preliminare calibrazione (azzeramento) della stessa

ATTENZIONE

*   È necessario calibrare i cavi di misura per ciascuna corrente di prova separatamente (200mA e 25A)
*   La calibrazione deve essere ripetuta ogni volta che i cavi di misura sono cambiati (sostituiti, accorciati o prolungati)
*   La resistenza massima calibrabile è di 5 Ω
*   La calibrazione presente può essere annullata eseguendo una nuova calibrazione a terminali aperti

3.  Premere il tasto virtuale CAL. Il messaggio “CORTOCIRCUITARE I CAVI E PREMERE START PER CALIBRARE” è mostrato a display
4.  Collegare i terminali di misura alle boccole RPE e assicurarsi che due coccodrilli siano collegati il più vicino possibile l'uno all'altro e a una porzione di filo non isolato (vedere Fig. 26)

    Fig. 26: Calibrazione terminali di misura

5.  Premere il tasto START/STOP. Lo strumento esegue la misura e il valore senza calibrazione apparirà brevemente sul display per poi essere riportato a zero (0.00). Il messaggio “CAVI CALIBRATI” è mostrato a display
6.  I seguenti messaggi possono essere mostrati durante la calibrazione:

    | Messaggi                                    | Descrizione                                                                                                                                                                                                                                                                 |
    | :------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | CORTOCIRCUITARE I CAVI E PREMERE START PER CALIBRARE | La calibrazione è stata avviata (il tasto virtuale CAL è stato premuto). Cortocircuitare i cavi di misura e premere il tasto START                                                                                                                                           |
    | PUNTALI APERTI, CALIBRAZIONE ANNULLATA      | I terminali di misura vengono aperti e dopo viene premuto il tasto START. Premere il tasto SÌ … la calibrazione esistente è annullata! Premere il tasto NO … la calibrazione esistente è mantenuta                                                                                 |
    | RPE > 5 Ω CALIBRAZIONE FALLITA              | La resistenza collegata è superiore a 5 Ω e inferiore al campo di misura, è impossibile eseguire la calibrazione. La calibrazione esistente rimarrà invariata. Ridurre la resistenza esterna e ripetere la calibrazione                                                          |

FULLTEST3 IT - 29

### 6.1.2. Impostazione valore limite sulla misura 25 A

Con selezione corrente di prova 25A lo strumento permette di eseguire il test di continuità calcolando il limite di riferimento in funzione della lunghezza (nota a priori) del conduttore oppure in funzione dell’impedenza della sorgente di alimentazione della linea in accordo alle prescrizioni della normativa IEC/EN60204 - 1.

**Modo EN60204 SET L**

Il valore limite è calcolato sulla base della lunghezza, della sezione e del materiale del conduttore in prova. I parametri possono essere selezionati/regolati entro gli intervalli riportati nella Tabella 1

**Modo EN60204 SET Z**

Il valore limite è calcolato in base all'impedenza di linea immessa (Z LINE), al tipo di protezione presente, alla corrente nominale della protezione e alla sezione del conduttore in prova. I valor dei parametri selezionabili sono i seguenti:

*   Impedenza di linea: campo 0.001 Ω ÷ 2.000 Ω in passi da 0.001 Ω
*   Tipo di protezione MCB (Magnetotermica): curva B, C, D, K
*   Corrente nominale protezione MCB: 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A (curva B), 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A (curva C), 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32A (curve D, K)
*   Tipo di protezione Fusibile: gG, aM
*   Corrente nominale protezione Fusibile gG: 2, 4, 6, 10, 13, 16, 20, 25, 32, 35, 40, 50, 63, 80, 100, 125, 160, 200, 224, 250, 315, 355, 400, 500, 630A
*   Corrente nominale protezione Fusibile aM: 6, 10, 16, 20, 25, 32, 35, 40, 50, 63, 80, 100, 160, 224, 250, 315, 355, 400, 500, 630A
*   Materiale conduttore: Cu (Rame), Al (Alluminio)
*   Sezione conduttore: 1, 2.5, 4, 6, 10, 16, 25, 35, 50, 70, 95, 120, 150, 185, 240, 300, 400, 500, 630 mm²

7.  Controllare la modalità selezionata (MANUALE o TIMER) e modificarla, se necessario, premendo il tasto virtuale MODO. In modalità MANUALE, la misura è attivata/arrestata dalla pressione del tasto START/STOP. In modalità TIMER, la misura è attivata dalla pressione del tasto START/STOP ed è arrestata allo scadere del tempo di misura impostato o da una nuova pressione del tasto START/STOP
8.  Selezionare la schermata di misura premendo il tasto virtuale e controllare nuovamente tutte le impostazioni
9.  Collegare i terminali di misura come mostrato nella seguente Fig. 27

Fig. 27: Collegamento dei terminali di misura in funzione RPE - 2WIRE

FULLTEST3 IT - 30

ATTENZIONE
Prima di collegare i terminali di misura all’UUT è strettamente necessario verificare che non sia presente una tensione esterna superiore a 10V tra i punti di misura a cui i terminali sono collegati

10. Premere il tasto START/STOP per eseguire la misura. Il risultato del test è mostrato a display (vedere Fig. 28)

Fig. 28: Risultato misura test continuità RPE - 2WIRE

Significato simboli a display

| Riferimento | Descrizione                                                                                                                                                                                                                             |
| :---------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1           | Funzione selezionata                                                                                                                                                                                                                    |
| 2           | Barra di avanzamento durante la misura in modalità TIMER                                                                                                                                                                              |
| 3           | Sottorisultati – Corrente reale di prova applicata                                                                                                                                                                                      |
| 4           | Tasto virtuale della schermata di misura                                                                                                                                                                                                |
| 5           | Tasto virtuale Im NOM per selezione della corrente di prova. Il valore attualmente selezionato è visualizzato in basso sul pulsante                                                                                                       |
| 6           | Tasto virtuale LIMIT per selezionare il valore limite (misura 200mA) o modalità limite (misura 25A). Il valore attualmente selezionato (STANDARD) o CALC è visualizzato in basso sul pulsante. CALC indica che il valore è calcolato        |
| 7           | Tasto virtuale MODE per selezione modo di funzionamento (MANUALE o TIMER). Il modo attualmente selezionato è presente in basso sul pulsante. Il modo Timer è disponibile per la misura 200mA e 25A solo se è selezionato il valore limite STANDARD |
| 8           | Tasto virtuale CAL per eseguire la calibrazione dei terminali di misura. Il valore attualmente tarato è visualizzato in basso sul pulsante. Nel caso non sia presente alcuna calibrazione il valore 0.00 Ω appare visualizzato in rosso |
| 9           | Stato di calibrazione del terminale di misura (CAVI CALIBRATI o CAVI NON CALIBRATI)                                                                                                                                                      |
| 10          | Valore misurato (visualizzato in verde - risultato OK, in rosso - risultato NON OK)                                                                                                                                                     |

FULLTEST3 IT - 31

| Riferimento | Descrizione                                                                                                                                                 |
| :---------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 11          | Orologio di sistema (hh.mm.ss)                                                                                                                              |
| 12          | Unità di misura del risultato (Ω)                                                                                                                           |
| 13          | Tempo di misura impostato (solo in modo TIMER)                                                                                                              |
| 14          | Stato del risultato della misura (simbolo visualizzato in verde - risultato OK, simbolo visualizzato in rosso - risultato NON OK o simbolo visualizzato in giallo – risultato OK, ma corrente di misura troppo bassa) |

11. Il risultato di misura è mostrato in verde (valore minore o uguale al limite impostato) o in rosso (valore superiore al limite impostato) ed è accompagnato da un segnale acustico e dal simbolo (risultato OK) o da un segnale acustico prolungato e dal simbolo rosso e (risultato non OK). Il simbolo in giallo è mostrato per risultato OK, ma corrente di misura troppo bassa)
12. Salvare i risultati delle misure premendo il tasto SAVE (vedere § 7.1)

ATTENZIONE

*   La tensione esterna massima tra due terminali RPE o tra due terminali SENSE è di 10 VAC. Non applicare alcuna tensione DC esterna! In caso di tensione esterna superiore, il fusibile F4 potrebbe intervenire
*   Il tempo di misura in modalità MANUALE è limitato a 5min
*   Il tempo di misura può essere impostato da 2s a 60min indipendentemente dalla corrente di prova selezionata ad eccezione per la corrente di prova di 25A in cui il tempo è da 2s a 5min

FULLTEST3 IT - 32

### 6.1.3. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate                     | Descrizione                                                                                                                                                                                                                                                                                                                           |
| :-------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| VERIFICA CALIBRAZIONE                         | Il risultato della misura è negativo, probabilmente a causa di terminali in misura più corti di quelli calibrati (il valore negativo è superiore alle 5 cifre). Tarare nuovamente i terminali di misura!                                                                                                                            |
| TENSIONE ESTERNA                              | • Tra due terminali di misura RPE o tra due terminali di misura SENSE è applicata una tensione esterna superiore a 3V (mentre non è in corso alcuna misura) o superiore a 10V (mentre è in corso una misura). • Una tensione esterna superiore a 5 ÷ 30 V è applicata tra i terminali di misura RPE o SENSE e la terra GND. Eliminare la tensione esterna! |
| LIMITE FUORI RANGE                            | Il limite calcolato è <1 (Modo EN60204 SET Z)                                                                                                                                                                                                                                                                                         |
| FUSIBILE F4!                                  | Il fusibile F4 è saltato.                                                                                                                                                                                                                                                                                                             |
| ERROR1!                                       | Il fusibile interno potrebbe essere saltato! Il fusibile non è sostituibile dal cliente, inviare lo strumento al servizio assistenza.                                                                                                                                                                                                  |
| TEMPO MISURA > 5MIN CONTROLLARE TIMER         | Il Timer è impostato ad un valore maggiore di 5 minuti con test 25A selezionato. Il test con corrente di 25A permette l’impostazione del timer al massimo di 5 minuti                                                                                                                                                                   |

FULLTEST3 IT - 33

## 6.2. CONTINUITÀ CONDUTTORI DI PROTEZIONE – METODO RPE - 4WIRE

In accordo alla normativa IEC/EN60204 - 1, la continuità del circuito di protezione tra il terminale PE e i punti corrispondenti del sistema di conduttori di protezione deve essere controllata immettendo una corrente di prova compresa tra circa 0.2A e 10A AC. Lo strumento permette di eseguire il test con corrente di prova di 10A.
La misura con metodo a 4 fili (quattro terminali, due per iniezione corrente e due per misura tensione) permette di eliminare l’influenza della resistenza dei cavi di misura.

1.  Premere il tasto FUNC e selezionare la funzione RPE - 4WIRE. La seguente videata è mostrata a display

    Fig. 29: Videata iniziale funzione RPE - 4WIRE

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 2) ed eseguire la programmazione desiderata

    Tabella 2: Parametri impostabili per la funzione RPE - 4WIRE

    | Parametro       | Descrizione                                           | Valore                                                                                                                                                                                                                                 |
    | :-------------- | :---------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | **Im NOM**      | Corrente di prova nominale                            | 10A AC (R<0.5 Ω)                                                                                                                                                                                                                       |
    | **LIMIT**       | Soglia limite di riferimento                          | STANDARD 0.001 Ω ÷ 20.00 Ω 60204 SET L 60204 SET Z                                                                                                                                                                                        |
    | **60204 SET L** | Test con corrente di prova 10A (vedere § 6.2.1)       | Lunghezza: 0.1m ÷ 999.9m Sezione: 1, 1.5, 2.5, 4, 6, 10, 16, 25, 35, 50, 70, 95, 120, 150, 185, 240, 300, 400, 500, 630 mm² Materiale: Cu (Rame) o Al (Alluminio)                                                                           |
    | **60204 SET Z** |                                                       | ZLine: 0.001 Ω ÷ 2.000 Ω Protezione MCB: B, C, D, K Protezione Fusibile: gG, aM Corrente nominale protezione (vedere § 6.2.1)                                                                                                           |
    | **MODE**        | Modo di misura                                        | Manuale Timer (2s ÷ 60min)                                                                                                                                                                                                             |
    | **CAL**         | Calibrazione terminali di misura (vedere § 6.1.1)     | Non disponibile per test 4 fili                                                                                                                                                                                                        |

FULLTEST3 IT - 34

### 6.2.1. Impostazione valore limite sulla misura

Con selezione corrente di prova 10A lo strumento permette di eseguire il test di continuità calcolando il limite di riferimento in funzione della lunghezza (nota a priori) del conduttore oppure in funzione dell’impedenza della sorgente di alimentazione della linea in accordo alle prescrizioni della normativa IEC/EN60204 - 1.

**Modo EN60204 SET L**

Il valore limite è calcolato sulla base della lunghezza, della sezione e del materiale del conduttore in prova. I parametri possono essere selezionati/regolati entro gli intervalli riportati nella Tabella 2

**Modo EN60204 SET Z**

Il valore limite è calcolato in base all'impedenza di linea immessa (Z LINE), al tipo di protezione presente, alla corrente nominale della protezione e alla sezione del conduttore in prova. I valor dei parametri selezionabili sono i seguenti:

*   Impedenza di linea: campo 0.001 Ω ÷ 2.000 Ω in passi da 0.001 Ω
*   Tipo di protezione MCB (Magnetotermica): curva B, C, D, K
*   Corrente nominale protezione MCB: 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A (curva B), 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A (curva C), 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32A (curve D, K)
*   Tipo di protezione Fusibile: gG, aM
*   Corrente nominale protezione Fusibile gG: 2, 4, 6, 10, 13, 16, 20, 25, 32, 35, 40, 50, 63, 80, 100, 125, 160, 200, 224, 250, 315, 355, 400, 500, 630A
*   Corrente nominale protezione Fusibile aM: 6, 10, 16, 20, 25, 32, 35, 40, 50, 63, 80, 100, 160, 224, 250, 315, 355, 400, 500, 630A
*   Materiale conduttore: Cu (Rame), Al (Alluminio)
*   Sezione conduttore: 1, 2.5, 4, 6, 10, 16, 25, 35, 50, 70, 95, 120, 150, 185, 240, 300, 400, 500, 630 mm²

3.  Controllare la modalità selezionata (MANUALE o TIMER) e modificarla, se necessario, premendo il tasto virtuale MODO. In modalità MANUALE, la misura è attivata/arrestata dalla pressione del tasto START/STOP. In modalità TIMER, la misura è attivata dalla pressione del tasto START/STOP ed è arrestata allo scadere del tempo di misura impostato o da una nuova pressione del tasto START/STOP
4.  Selezionare la schermata di misura premendo il tasto virtuale e controllare nuovamente tutte le impostazioni
5.  Collegare i terminali di misura come mostrato nella seguente Fig. 30

Fig. 30: Collegamento dei terminali di misura in funzione RPE - 4WIRE

FULLTEST3 IT - 35

ATTENZIONE
Prima di collegare i terminali di misura all’UUT è strettamente necessario verificare che non sia presente una tensione esterna superiore a 10V tra i punti di misura a cui i terminali sono collegati

6.  Premere il tasto START/STOP per eseguire la misura. Il risultato del test è mostrato a display (vedere Fig. 31)

Fig. 31: Risultato misura test continuità RPE - 4WIRE

Significato simboli a display

| Riferimento | Descrizione                                                                                                                                                                                                 |
| :---------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1           | Funzione selezionata                                                                                                                                                                                        |
| 2           | Barra di avanzamento durante la misura in modalità TIMER                                                                                                                                                    |
| 3           | Sottorisultati – Corrente reale di prova applicata                                                                                                                                                          |
| 4           | Tasto virtuale della schermata di misura                                                                                                                                                                    |
| 5           | Tasto virtuale Im NOM per selezione della corrente di prova (10A). Il valore attualmente selezionato è visualizzato in basso sul pulsante                                                                      |
| 6           | Tasto virtuale LIMIT per selezionare il valore limite o modalità limite. Il valore attualmente selezionato (STANDARD) o CALC è visualizzato in basso sul pulsante. CALC indica che il valore è calcolato        |
| 7           | Tasto virtuale MODE per selezione modo di funzionamento (MANUALE o TIMER). Il modo attualmente selezionato è presente in basso sul pulsante.                                                                  |
| 8           | Tasto virtuale CAL per eseguire la calibrazione dei terminali di misura (NON DISPONIBILE). La scritta “Non Disp.” è visualizzata                                                                             |
| 9           | Stato di calibrazione del terminale di misura (NON DISPONIBILE)                                                                                                                                             |
| 10          | Valore misurato (visualizzato in verde - risultato OK, in rosso - risultato NON OK)                                                                                                                         |
| 11          | Orologio di sistema (hh.mm.ss)                                                                                                                                                                              |
| 12          | Unità di misura del risultato (Ω)                                                                                                                                                                           |
| 13          | Tempo di misura impostato (solo in modo TIMER)                                                                                                                                                              |
| 14          | Stato del risultato della misura (simbolo visualizzato in verde - risultato OK, simbolo visualizzato in rosso - risultato NON OK o simbolo visualizzato in giallo – risultato OK, ma corrente di misura troppo bassa) |

FULLTEST3 IT - 36

7.  Il risultato di misura è mostrato in verde (valore minore o uguale al limite impostato) o in rosso (valore superiore al limite impostato) ed è accompagnato da un segnale acustico e dal simbolo (risultato OK) o da un segnale acustico prolungato e dal simbolo rosso e (risultato non OK). Il simbolo in giallo è mostrato per risultato OK, ma corrente di misura troppo bassa)
8.  Salvare i risultati delle misure premendo il tasto SAVE (vedere § 7.1)

ATTENZIONE

*   La tensione esterna massima tra due terminali RPE o tra due terminali SENSE è di 10 VAC. Non applicare alcuna tensione DC esterna! In caso di tensione esterna superiore, il fusibile F4 potrebbe intervenire
*   Il tempo di misura in modalità MANUALE è limitato a 5min
*   La calibrazione terminali di misura non è disponibile in questa funzione

### 6.2.2. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate                                  | Descrizione                                                                                                                                                                                                                                                                                                                           |
| :--------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| VERIFICA COLLEGAMENTO SENSE                                | La tensione ai terminali SENSE è troppo bassa, verificare il collegamento dei terminali SENSE e/o la continuità del conduttore sotto test                                                                                                                                                                                              |
| TENSIONE ESTERNA                                           | • Tra due terminali di misura RPE o tra due terminali di misura SENSE è applicata una tensione esterna superiore a 3V (mentre non è in corso alcuna misura) o superiore a 10V (mentre è in corso una misura). • Una tensione esterna superiore a 5 ÷ 30 V è applicata tra i terminali di misura RPE o SENSE e la terra GND. Eliminare la tensione esterna! |
| LIMITE FUORI RANGE                                         | Il limite calcolato è <1 (Modo EN60204 SET Z)                                                                                                                                                                                                                                                                                         |
| FUSIBILE F4!                                               | Il fusibile F4 è saltato.                                                                                                                                                                                                                                                                                                             |
| ERROR1!                                                    | Il fusibile interno potrebbe essere saltato! Il fusibile non è sostituibile dal cliente, inviare lo strumento al servizio assistenza.                                                                                                                                                                                                  |
| TEMPO MISURA > 5MIN CONTROLLARE TIMER                      | Il Timer è impostato ad un valore maggiore di 5 minuti. Il test con corrente di 10A permette l’impostazione del timer al massimo di 60 minuti (ma è consigliabile limitarlo a 5 minuti per non scaldare eccessivamente il conduttore)                                                                                                  |

FULLTEST3 IT - 37

## 6.3. RESISTENZA DI ISOLAMENTO (MΩ)

Lo strumento permette di eseguire il test di resistenza di isolamento in accordo alla normativa IEC/EN60204 - 1 § 18.3 (prima dell’esecuzione del test occorre scollegare tutti i cavi allacciati alla rete di alimentazione) e in accordo alle normative CEI 64 - 8 e CEI 23 - 51.

1.  Premere il tasto FUNC e selezionare la funzione RISO. La seguente videata è mostrata a display

    Fig. 32: Videata iniziale funzione R ISO

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 3) ed eseguire la programmazione desiderata

    Tabella 3: Parametri impostabili per la funzione R ISO

    | Parametro   | Descrizione                                                                                                                                                                                                                                                           | Valore                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
    | :---------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | **Um NOM**  | Tensione nominale di prova                                                                                                                                                                                                                                            | 100V, 250V, 500V, 1000V DC                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
    | **LIMIT**   | Soglia limite di riferimento                                                                                                                                                                                                                                          | STANDARD 0.01 M Ω ÷ 1000 M Ω                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
    | **MODE**    | Modo di misura                                                                                                                                                                                                                                                        | MANUALE AUTO (misura continua) TIMER (2s ÷ 10min)                                                                                                                                                                                                                                                                                                                                                                                                                                            |
    | **TIMER**   | Tempo di misura (solo in modo TIMER)                                                                                                                                                                                                                                  | 2s ÷ 10min                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

3.  Controllare la modalità selezionata (MANUALE, AUTO o TIMER) e modificarla, se necessario, premendo il tasto virtuale MODO. In modalità MANUALE, la misura è attivata/arrestata dalla pressione del tasto START/STOP. In modalità TIMER, la misura è attivata dalla pressione del tasto START/STOP ed è arrestata allo scadere del tempo di misura impostato o da una nuova pressione del tasto START/STOP. In modalità AUTO, la misura è attivata/arrestata dalla pressione del tasto START/STOP.
4.  Selezionare la schermata di misura premendo il tasto virtuale e controllare nuovamente tutte le impostazioni
5.  Collegare i terminali di misura come mostrato nella seguente Fig. 33.

Fig. 33: Collegamento dei terminali di misura in funzione R ISO

FULLTEST3 IT - 38

ATTENZIONE
Prima di coll egare i terminali di misura all’UUT   è   strettamente  necessario   verificare che non sia presente una tensione esterna  superiore a   10V   tra i   punti   di misura a   cui i terminali   sono  collegati

6.  Premere il tasto START/STOP per eseguire la misura. Il risultato del test è mostrato a display (vedere Fig. 34)

Fig. 34: Risultato misura test resistenza di isolamento

Significato simboli a display

| Riferimento | Descrizione                                                                                                                                                                                                                                                                                                                                 |
| :---------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1           | Funzione selezionata                                                                                                                                                                                                                                                                                                                        |
| 2           | Barra di avanzamento durante la misura in modalità TIMER                                                                                                                                                                                                                                                                                    |
| 3           | Sottorisultati – Tensione di prova reale applicata                                                                                                                                                                                                                                                                                          |
| 4           | Tasto virtuale della schermata di misura                                                                                                                                                                                                                                                                                                    |
| 5           | Tasto virtuale Um NOM per selezione della tensione di prova. Il valore attualmente selezionato è visualizzato in basso sul pulsante                                                                                                                                                                                                          |
| 6           | Tasto virtuale LIMIT per selezionare il valore limite. Il valore attualmente selezionato (STANDARD) è visualizzato in basso sul pulsante.                                                                                                                                                                                                    |
| 7           | Tasto virtuale MODE per selezione modo di funzionamento (MANUALE, AUTO o TIMER). Il modo attualmente selezionato è presente in basso sul pulsante. Il modo AUTO permette una misurazione continua fino a quando il tasto START/STOP viene rilasciato oppure fino a quando la tensione di prova non è rimossa dall’oggetto in esame.        |
| 8           | Tasto virtuale TIMER per impostazione tempo di misura (solo in modo TIMER). Il tempo attualmente impostato è visualizzato in basso sul pulsante.                                                                                                                                                                                            |
| 9           | Simbolo lampeggiante in presenza di tensione >10V ai terminali di misura                                                                                                                                                                                                                                                                   |
| 10          | Valore misurato (visualizzato in verde - risultato OK, in rosso - risultato NON OK)                                                                                                                                                                                                                                                         |
| 11          | Orologio di sistema (hh.mm.ss)                                                                                                                                                                                                                                                                                                              |
| 12          | Unità di misura del risultato (MΩ)                                                                                                                                                                                                                                                                                                          |
| 13          | Tempo di misura impostato (solo in modo TIMER)                                                                                                                                                                                                                                                                                              |
| 14          | Stato del risultato della misura (simbolo visualizzato in verde - risultato OK, simbolo visualizzato in rosso - risultato NON OK o simbolo visualizzato in giallo – risultato OK, ma tensione di misura troppo bassa) *(NOTE: The yellow symbol condition is unlikely for Insulation test)* |

FULLTEST3 IT - 39

7.  Il risultato di misura è mostrato in verde (valore maggiore o uguale al limite impostato) o in rosso (valore inferiore al limite impostato) ed è accompagnato da un segnale acustico e dal simbolo (risultato OK) o da un segnale acustico prolungato e dal simbolo rosso e (risultato non OK).
8.  Salvare i risultati delle misure premendo il tasto SAVE (vedere § 7.1)

ATTENZIONE

*   La tensione esterna massima tra due terminali è di 10 VAC. Non applicare alcuna tensione DC esterna! In caso di tensione esterna superiore, il fusibile F2 potrebbe intervenire
*   Il tempo di misura in modalità MANUALE e AUTO è limitato a 5min

### 6.3.1. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate   | Descrizione                                                                                                                                                                                                                                                                                                            |
| :-------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TENSIONE ESTERNA            | Tra i terminali di misura è applicata una tensione esterna superiore a 10V. Rimuovere la tensione esterna per poter eseguire la misura.                                                                                                                                                                                   |
| ERROR1!                     | Il fusibile interno potrebbe essere saltato! Il fusibile non è sostituibile dal cliente, inviare lo strumento al servizio assistenza.                                                                                                                                                                                   |
| ER R OR2!                   | Il fusibile interno potrebbe essere saltato! Il fusibile non è sostituibile dal cliente, inviare lo strumento al servizio assistenza.                                                                                                                                                                                   |
| TEMPO MISURA > 5MIN CONTROLLARE TIMER | Il Timer è impostato ad un valore maggiore di 5 minuti in modalità AUTO o MANUALE. Impostare il Timer ad un valore inferiore.                                                                                                                                                                              |

FULLTEST3 IT - 40

## 6.4. TEST RIGIDITÀ DIELETTRICA (DIELECTRIC)

Lo strumento permette di eseguire il test di rigidità dielettrica (Hi - Pot Test) in accordo alle normative IEC/EN60204 - 1 § 18.4 (prima dell’esecuzione del test occorre scollegare tutti i cavi allacciati alla rete di alimentazione).

1.  Premere il tasto FUNC e selezionare la funzione DIELECTRIC. La seguente videata è mostrata a display

    Fig. 35: Videata iniziale funzione DIELECTRIC

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 4) ed eseguire la programmazione desiderata

    Tabella 4: Parametri impostabili per la funzione DIELECTRIC

    | Parametro    | Descrizione                                                                                                                                                                                                                                           | Valore                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
    | :----------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | **U TEST NOM** | Tensione nominale di prova                                                                                                                                                                                                                            | 250V ÷ 5100V AC                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
    | **LIMIT**    | Soglia limite di riferimento                                                                                                                                                                                                                                          | 1 mA ÷ 110 mA                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
    | **MODE**     | Modo di misura                                                                                                                                                                                                                                                        | MANUALE RAMPA 75% RAMPA 50% BURN PULSE                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
    | **CARATTERISTICA** | Tipologia corrente di scarica                                                                                                                                                                                                                         | IAPP (corrente apparente) I REAL (corrente reale) (vedere § 6.4.2)                                                                                                                                                                                                                                                                                                                                                                                                                           |
    | **RAMP TIMER** | Tempo di salita della rampa (solo in modo RAMPA)                                                                                                                                                                                                      | 2s ÷ 10min                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

FULLTEST3 IT - 41

### 6.4.1. Modi di funzionamento

| Modo         | Descrizione                                                                                                                                                                                                                                                                                                            |
| :----------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **MANUALE**  | La tensione di prova aumenta in modo proporzionale al tempo di pressione del tasto START/STOP fino al raggiungimento del valore nominale impostato o fino al valore massimo consentito (se il valore nominale impostato è maggiore del massimo). Rilasciando il tasto START/STOP, la tensione di prova viene interrotta e il test è considerato Fallito se la corrente di perdita ha superato il valore limite impostato. |
| **RAMPA 75%** | La tensione di prova aumenta automaticamente fino al raggiungimento del 75% del valore nominale impostato (tempo di salita impostabile tramite il parametro RAMP TIMER). Quindi, la tensione di prova aumenta in modo proporzionale al tempo di pressione del tasto START/STOP fino al raggiungimento del valore nominale impostato o fino al valore massimo consentito (se il valore nominale impostato è maggiore del massimo). Rilasciando il tasto START/STOP, la tensione di prova viene interrotta e il test è considerato Fallito se la corrente di perdita ha superato il valore limite impostato. |
| **RAMPA 50%** | La tensione di prova aumenta automaticamente fino al raggiungimento del 50% del valore nominale impostato (tempo di salita impostabile tramite il parametro RAMP TIMER). Quindi, la tensione di prova aumenta in modo proporzionale al tempo di pressione del tasto START/STOP fino al raggiungimento del valore nominale impostato o fino al valore massimo consentito (se il valore nominale impostato è maggiore del massimo). Rilasciando il tasto START/STOP, la tensione di prova viene interrotta e il test è considerato Fallito se la corrente di perdita ha superato il valore limite impostato. |
| **BURN**     | La tensione di prova aumenta in modo proporzionale al tempo di pressione del tasto START/STOP fino al raggiungimento del valore nominale impostato o fino al valore massimo consentito (se il valore nominale impostato è maggiore del massimo). Una volta raggiunta la tensione nominale, questa viene mantenuta fino al rilascio del tasto START/STOP o fino al superamento della corrente di perdita limite impostata. In questo modo è possibile “bruciare” i punti di innesco di scarica. |
| **PULSE**    | La tensione di prova aumenta in modo proporzionale al tempo di pressione del tasto START/STOP fino al raggiungimento del valore nominale impostato o fino al valore massimo consentito (se il valore nominale impostato è maggiore del massimo). Una volta raggiunta la tensione nominale, questa viene mantenuta per un brevissimo tempo (qualche ms) per poi essere immediatamente interrotta. Questo modo è utile per verificare la presenza di scariche parziali. |

3.  Controllare la modalità selezionata (MANUALE, RAMPA 75%, RAMPA 50%, BURN, PULSE) e modificarla, se necessario, premendo il tasto virtuale MODO.
4.  Selezionare la schermata di misura premendo il tasto virtuale e controllare nuovamente tutte le impostazioni
5.  Collegare i terminali di misura come mostrato nella seguente Fig. 36.

Fig. 36: Collegamento dei terminali di misura in funzione DIELECTRIC

FULLTEST3 IT - 42

### 6.4.2. Tipologia corrente di scarica

| Caratteristica | Descrizione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **IAPP**       | La misura della corrente di perdita viene eseguita sul valore apparente della corrente (considerando la corrente totale che attraversa l’oggetto in esame, compresa la corrente capacitiva) e il test è considerato Fallito se la corrente di perdita supera il valore limite impostato. Questo modo di misura è utile per verificare che l’oggetto in esame non presenti cortocircuiti o bassi valori di impedenza che potrebbero generare correnti di perdita elevate.                                  |
| **I REAL**     | La misura della corrente di perdita viene eseguita sul valore reale della corrente (considerando solo la componente resistiva della corrente che attraversa l’oggetto in esame, escludendo la corrente capacitiva). Il test è considerato Fallito se la corrente di perdita supera il valore limite impostato. Questo modo di misura è utile per verificare che l’oggetto in esame non presenti dispersioni verso terra dovute a bassi valori di isolamento.                                     |

6.  Controllare la tipologia corrente di scarica selezionata (IAPP o I REAL) e modificarla, se necessario, premendo il tasto virtuale CARATTERISTICA.
7.  Premere il tasto START/STOP per eseguire la misura. Il risultato del test è mostrato a display (vedere Fig. 37)

Fig. 37: Risultato misura test rigidità dielettrica

Significato simboli a display

| Riferimento | Descrizione                                                                                                                                                                                                                                                                                                                                                           |
| :---------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1           | Funzione selezionata                                                                                                                                                                                                                                                                                                                                                  |
| 2           | Barra di avanzamento durante la misura in modalità RAMPA                                                                                                                                                                                                                                                                                                              |
| 3           | Sottorisultati – Tensione di prova reale applicata                                                                                                                                                                                                                                                                                                                    |
| 4           | Tasto virtuale della schermata di misura                                                                                                                                                                                                                                                                                                                              |
| 5           | Tasto virtuale U TEST NOM per selezione della tensione di prova. Il valore attualmente selezionato è visualizzato in basso sul pulsante                                                                                                                                                                                                                                |
| 6           | Tasto virtuale LIMIT per selezionare il valore limite. Il valore attualmente selezionato è visualizzato in basso sul pulsante.                                                                                                                                                                                                                                      |
| 7           | Tasto virtuale MODE per selezione modo di funzionamento (MANUALE, RAMPA 75%, RAMPA 50%, BURN, PULSE). Il modo attualmente selezionato è presente in basso sul pulsante.                                                                                                                                                                                                 |
| 8           | Tasto virtuale CARATTERISTICA per selezione tipologia corrente di scarica (IAPP o I REAL). Il modo attualmente selezionato è presente in basso sul pulsante.                                                                                                                                                                                                            |
| 9           | Tasto virtuale RAMP TIMER per impostazione tempo di salita della rampa (solo in modo RAMPA). Il tempo attualmente impostato è visualizzato in basso sul pulsante.                                                                                                                                                                                                    |

FULLTEST3 IT - 43

| Riferimento | Descrizione                                                                                                                                                                                                                                                                                                                                                                  |
| :---------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 10          | Valore misurato (visualizzato in verde - risultato OK, in rosso - risultato NON OK)                                                                                                                                                                                                                                                                                          |
| 11          | Orologio di sistema (hh.mm.ss)                                                                                                                                                                                                                                                                                                                                               |
| 12          | Unità di misura del risultato (mA)                                                                                                                                                                                                                                                                                                                                           |
| 13          | Tempo di misura (solo in modo TIMER - NON DISPONIBILE PER QUESTO TEST)                                                                                                                                                                                                                                                                                                       |
| 14          | Stato del risultato della misura (simbolo visualizzato in verde - risultato OK, simbolo visualizzato in rosso - risultato NON OK o simbolo visualizzato in giallo – risultato OK, ma tensione di misura troppo bassa) *(NOTE: The yellow symbol condition is unlikely for Dielectric Strength test)* |
| 15          | Spia gialla lampeggiante per segnalazione misurazione in corso di rigidità dielettrica                                                                                                                                                                                                                                                                                       |

ATTENZIONE

*   Questo test può generare tensioni molto elevate e potenzialmente pericolose. Attenersi scrupolosamente alle normative di sicurezza vigenti e alle istruzioni di questo manuale.
*   Prima di coll egare i terminali di misura all’UUT   è   strettamente  necessario   verificare che non sia presente una tensione esterna  superiore a   10V   tra i   punti   di misura a   cui i terminali   sono  collegati
*   La tensione esterna massima tra due terminali è di 10 VAC. Non applicare alcuna tensione DC esterna! In caso di tensione esterna superiore, il fusibile F2 potrebbe intervenire
*   Il test di rigidità dielettrica NON deve essere eseguito su oggetti in esame che contengono condensatori di grande capacità.
*   La funzione RIGIDITA DIELETTRICA è una misura di sicurezza che richiede particolari precauzioni. Fare riferimento al § 5.5.2 per maggiori informazioni.

8.  Il risultato di misura è mostrato in verde (valore inferiore o uguale al limite impostato) o in rosso (valore superiore al limite impostato) ed è accompagnato da un segnale acustico e dal simbolo (risultato OK) o da un segnale acustico prolungato e dal simbolo rosso e (risultato non OK).
9.  Salvare i risultati delle misure premendo il tasto SAVE (vedere § 7.1)

FULLTEST3 IT - 44

ATTENZIONE

*   Durante l’esecuzione della prova di rigidità dielettrica la spia gialla lampeggiante (vedere Fig. 2 – parte 35) e la spia rossa esterna (se collegata – accessorio opzionale FT3R - GLP o FT3REDLP) si accendono per segnalare la potenziale presenza di alta tensione ai terminali di uscita.
*   La pressione del tasto START/STOP attiva l’emissione di tensione di prova. Il rilascio del tasto START/STOP interrompe l’emissione di tensione e il test è considerato Fallito se la corrente di perdita ha superato il valore limite impostato.

ATTENZIONE

*   La funzione RIGIDITA DIELETTRICA è una misura di sicurezza che richiede particolari precauzioni. Fare riferimento al § 5.5.2 per maggiori informazioni.
*   Durante l’esecuzione della prova di rigidità dielettrica è necessario che l’oggetto in esame sia isolato da terra e da qualsiasi altra parte a potenziale pericoloso.

FULLTEST3 IT - 45

### 6.4.3. Dispositivi di sicurezza

Lo strumento è dotato dei seguenti dispositivi di sicurezza:

*   **Doppio pulsante START/STOP:** La pressione contemporanea dei due pulsanti (interno ed esterno - accessorio opzionale FT3RMTCT) è necessaria per avviare la misura di rigidità dielettrica. Il rilascio di uno dei due pulsanti interrompe la misura. Questo dispositivo previene l’avvio involontario della misura.
*   **Ingresso di sicurezza SAFETY INPUT:** Se abilitato nel menù SETUP (§ 5.5.2), la misura di rigidità dielettrica è possibile solo se il contatto esterno collegato a questo ingresso è chiuso (accessorio opzionale FT3SFTSW). Questo dispositivo permette di bloccare l’esecuzione della misura se la zona di prova non è sicura (ad esempio, la porta di accesso alla zona di prova è aperta).
*   **Spia di segnalazione:** La spia gialla lampeggiante sullo strumento e la lampada rossa esterna (accessorio opzionale FT3R - GLP o FT3REDLP) si accendono durante l’esecuzione della misura di rigidità dielettrica per segnalare la presenza di alta tensione.
*   **Protezione contro sovratensione esterna:** Lo strumento è protetto contro l’applicazione accidentale di tensioni esterne sui terminali di misura.

### 6.4.4. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate                 | Descrizione                                                                                                                                                                                                                                                                                                                           |
| :---------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| TENSIONE ESTERNA                          | Tra i terminali di misura è applicata una tensione esterna superiore a 10V. Rimuovere la tensione esterna per poter eseguire la misura.                                                                                                                                                                                                  |
| ERROR1!                                   | Il fusibile interno potrebbe essere saltato! Il fusibile non è sostituibile dal cliente, inviare lo strumento al servizio assistenza.                                                                                                                                                                                                  |
| ER R OR2!                                 | Il fusibile interno potrebbe essere saltato! Il fusibile non è sostituibile dal cliente, inviare lo strumento al servizio assistenza.                                                                                                                                                                                                  |
| SAFETY INPUT APERTO                       | Il contatto di sicurezza esterno è aperto (solo se l'ingresso di sicurezza è abilitato nel menù SETUP § 5.5.2). Chiudere il contatto di sicurezza per poter eseguire la misura.                                                                                                                                                         |
| MISURA NON CONSENTITA SENZA PASSWORD      | È stata richiesta l’esecuzione della misura di rigidità dielettrica con corrente di prova ≥3mA e il parametro EN50191 è abilitato nel menù SETUP (§ 5.5.2) senza aver inserito la password. Inserire la password `8314` prima di avviare la misura.                                                                                        |
| TEMPO MISURA > 10MIN CONTROLLARE TIMER    | Il Timer è impostato ad un valore maggiore di 10 minuti in modalità RAMPA. Impostare il Timer ad un valore inferiore.                                                                                                                                                                                                                  |

FULLTEST3 IT - 46

## 6.5. TEST SU DIFFERENZIALI (RCD)

Lo strumento permette di eseguire i test funzionali e a tempo di intervento sui dispositivi differenziali (RCD) di tipo AC, A e B, generali, selettivi e ritardati, in accordo alle normative IEC/EN61557 - 6, CEI 64 - 8.

1.  Premere il tasto FUNC e selezionare la funzione RCD. La seguente videata è mostrata a display

    Fig. 38: Videata iniziale funzione RCD

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 5) ed eseguire la programmazione desiderata

    Tabella 5: Parametri impostabili per la funzione RCD

    | Parametro   | Descrizione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Valore                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
    | :---------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | **TIPO**    | Tipo di RCD da testare                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | AC GEN, AC SEL, AC RIT, A GEN, A SEL, A RIT, B GEN, B SEL, B RIT                                                                                                                                                                                                                                                                                                                                                                                                                             |
    | **I Δ N**   | Corrente differenziale nominale dell’RCD                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 10, 30, 100, 300, 500, 650, 1000 mA                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
    | **MISURA**  | Tipologia di test                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | t/I Δ N (test a tempo di intervento con corrente di prova IΔN, 2IΔN o 5IΔN) Rampa (test a rampa di corrente) AUTO (test automatico con tutte le correnti di prova)                                                                                                                                                                                                                                                                                                                              |
    | **POL**     | Polarità della corrente di prova (solo per RCD tipo A e B)                                                                                                                                                                                                                                                                                                                                                                                                                                              | POS (polarità positiva) NEG (polarità negativa) AUTO (alternanza automatica delle polarità)                                                                                                                                                                                                                                                                                                                                                                                                    |
    | **RITARDO** | Tempo di ritardo di intervento (solo per RCD tipo SEL e RIT)                                                                                                                                                                                                                                                                                                                                                                                                                                          | 100 ms, 200 ms, 300 ms, 700 ms                                                                                                                                                                                                                                                                                                                                                                                                                                                               |

3.  Controllare la tipologia di RCD (TIPO), la corrente differenziale nominale (IΔN), la tipologia di test (MISURA) e, se necessario, la polarità della corrente di prova (POL) e il tempo di ritardo di intervento (RITARDO). Modificarli, se necessario, premendo i tasti virtuali corrispondenti.
4.  Selezionare la schermata di misura premendo il tasto virtuale e controllare nuovamente tutte le impostazioni
5.  Collegare i terminali di misura come mostrato nella seguente Fig. 39.

Fig. 39: Collegamento dei terminali di misura in funzione RCD

FULLTEST3 IT - 47

ATTENZIONE
Prima di coll egare i terminali di misura all’UUT   è   strettamente  necessario   verificare che non sia presente una tensione esterna  superiore a   10V   tra i   punti   di misura a   cui i terminali   sono  collegati

6.  Premere il tasto START/STOP per eseguire la misura. Il risultato del test è mostrato a display (vedere Fig. 40)

Fig. 40: Risultato misura test su differenziali

Significato simboli a display

| Riferimento | Descrizione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| :---------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1           | Funzione selezionata                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| 2           | Barra di avanzamento durante la misura (non presente in tutti i modi)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 3           | Sottorisultati – Corrente di prova reale applicata (solo in test Rampa)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| 4           | Tasto virtuale della schermata di misura                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| 5           | Tasto virtuale TIPO per selezione del tipo di RCD. Il valore attualmente selezionato è visualizzato in basso sul pulsante.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| 6           | Tasto virtuale I Δ N per selezione della corrente differenziale nominale. Il valore attualmente selezionato è visualizzato in basso sul pulsante.                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 7           | Tasto virtuale MISURA per selezione della tipologia di test. Il modo attualmente selezionato è presente in basso sul pulsante.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| 8           | Tasto virtuale POL per selezione della polarità della corrente di prova (solo per RCD tipo A e B). Il modo attualmente selezionato è presente in basso sul pulsante.                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 9           | Tasto virtuale RITARDO per impostazione tempo di ritardo di intervento (solo per RCD tipo SEL e RIT). Il tempo attualmente impostato è visualizzato in basso sul pulsante.                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| 10          | Valore misurato (visualizzato in verde - risultato OK, in rosso - risultato NON OK). Per test a tempo, viene visualizzato il tempo di intervento. Per test Rampa, viene visualizzata la corrente di intervento. Per test AUTO, viene visualizzato l’esito complessivo.                                                                                                                                                                                                                                                                                                                                        |
| 11          | Orologio di sistema (hh.mm.ss)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| 12          | Unità di misura del risultato (ms per test a tempo, mA per test Rampa)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| 13          | Tensione di contatto UC rilevata durante il test (solo in test a tempo e Rampa)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| 14          | Stato del risultato della misura (simbolo visualizzato in verde - risultato OK, simbolo visualizzato in rosso - risultato NON OK)                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

FULLTEST3 IT - 48

ATTENZIONE

*   La tensione esterna massima tra i terminali L/TRIG/L1, N/TRIG/L2 e PE/L3 è di 265 VAC. Non applicare alcuna tensione DC esterna! In caso di tensione esterna superiore, il fusibile F3 potrebbe intervenire
*   Durante l’esecuzione del test RCD, lo strumento eroga una corrente differenziale. Assicurarsi che l’oggetto in esame non sia sotto tensione durante il test.

7.  Il risultato di misura è mostrato in verde (risultato OK) o in rosso (risultato non OK) ed è accompagnato da un segnale acustico e dal simbolo (risultato OK) o da un segnale acustico prolungato e dal simbolo rosso e (risultato non OK).
8.  Salvare i risultati delle misure premendo il tasto SAVE (vedere § 7.1)

FULLTEST3 IT - 49

### 6.5.1. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate   | Descrizione                                                                                                                                                                                                                                                                                                                                                                                                         |
| :-------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| TENSIONE ESTERNA            | Tra i terminali di misura L/TRIG/L1, N/TRIG/L2 o PE/L3 è applicata una tensione esterna superiore a 265V. Rimuovere la tensione esterna per poter eseguire la misura.                                                                                                                                                                                                                                              |
| ERROR1!                     | Il fusibile interno potrebbe essere saltato! Il fusibile non è sostituibile dal cliente, inviare lo strumento al servizio assistenza.                                                                                                                                                                                                                                                                                 |
| ER R OR3!                   | Il fusibile interno potrebbe essere saltato! Il fusibile non è sostituibile dal cliente, inviare lo strumento al servizio assistenza.                                                                                                                                                                                                                                                                                 |
| NESSUNA TENSIONE DI RETE    | Lo strumento non rileva una tensione di rete valida (>100V) tra i terminali L/TRIG/L1 e N/TRIG/L2. Verificare il collegamento alla rete di alimentazione.                                                                                                                                                                                                                                                        |
| PE SCOLLEGATO               | Lo strumento non rileva il collegamento del terminale PE. Verificare il collegamento a terra dello strumento.                                                                                                                                                                                                                                                                                                       |
| RCD NON SCATTATO            | Durante il test RCD a tempo o AUTO, il dispositivo differenziale non è intervenuto entro il tempo limite. Verificare il corretto funzionamento dell’RCD e/o le impostazioni di test.                                                                                                                                                                                                                              |
| CORRENTE DI PERDITA ELEVATA | Durante il test RCD Rampa, la corrente di perdita ha superato il valore limite impostato. Verificare l’isolamento dell’oggetto in esame.                                                                                                                                                                                                                                                                           |
| UC > LIMITE                 | Durante il test RCD a tempo o Rampa, la tensione di contatto UC ha superato il limite impostato (25V o 50V). Verificare la resistenza di terra e/o la presenza di tensioni pericolose.                                                                                                                                                                                                                             |

FULLTEST3 IT - 50

## 6.6. IMPEDENZA ANELLO DI GUASTO (LOOP)

Lo strumento permette di eseguire la misura dell’impedenza dell’anello di guasto (LOOP) e del calcolo della presunta corrente di cortocircuito (IPSC) in accordo alle normative IEC/EN61557 - 3, CEI 64 - 8.

1.  Premere il tasto FUNC e selezionare la funzione LOOP. La seguente videata è mostrata a display

    Fig. 41: Videata iniziale funzione LOOP

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 6) ed eseguire la programmazione desiderata

    Tabella 6: Parametri impostabili per la funzione LOOP

    | Parametro     | Descrizione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Valore                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
    | :------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | **MODO**      | Modo di misura                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | LOOP L/N (misura impedenza anello di guasto fase-neutro) LOOP L/L (misura impedenza anello di guasto fase-fase) LOOP L/PE (misura impedenza anello di guasto fase-terra)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
    | **LIMIT**     | Soglia limite di riferimento                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | STANDARD 0.01 Ω ÷ 1000 Ω CALC (limite calcolato in base alla protezione) (vedere § 6.6.1)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
    | **PROTEZIONE** | Tipo di protezione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | MCB (Magnetotermica) FUSIBILE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
    | **IN**        | Corrente nominale della protezione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Varia in base al tipo di protezione selezionata (vedere § 6.6.1)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

FULLTEST3 IT - 51

### 6.6.1. Impostazione valore limite sulla misura

Con selezione della modalità limite CALC lo strumento permette di calcolare la massima impedenza di anello di guasto consentita in accordo alle prescrizioni della normativa CEI 64 - 8 in funzione del tipo di protezione presente e della sua corrente nominale.

**Modo Calcolato (CALC)**

Il valore limite è calcolato in base al tipo di protezione presente e alla sua corrente nominale. I valori dei parametri selezionabili sono i seguenti:

*   Tipo di protezione MCB (Magnetotermica): curva B, C, D, K, Z, A
*   Corrente nominale protezione MCB:
    *   Curva B: 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A
    *   Curva C: 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A
    *   Curva D: 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32A
    *   Curva K: 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32A
    *   Curva Z: 1, 1.6, 2, 3, 4, 6, 10, 13, 16, 20, 25, 32A
    *   Curva A: 1, 1.6, 2, 3, 4, 6, 10, 13, 16, 20, 25, 32A
*   Tipo di protezione Fusibile: gG, aM
*   Corrente nominale protezione Fusibile gG: 2, 4, 6, 10, 13, 16, 20, 25, 32, 35, 40, 50, 63, 80, 100, 125, 160, 200, 224, 250, 315, 355, 400, 500, 630A
*   Corrente nominale protezione Fusibile aM: 6, 10, 16, 20, 25, 32, 35, 40, 50, 63, 80, 100, 160, 224, 250, 315, 355, 400, 500, 630A

3.  Controllare la modalità di misura (MODO) e la modalità limite (LIMIT). Modificarli, se necessario, premendo i tasti virtuali corrispondenti.
4.  Se la modalità limite è CALC, selezionare il tipo di protezione (PROTEZIONE) e la sua corrente nominale (IN). Modificarli, se necessario, premendo i tasti virtuali corrispondenti.
5.  Selezionare la schermata di misura premendo il tasto virtuale e controllare nuovamente tutte le impostazioni
6.  Collegare i terminali di misura come mostrato nella seguente Fig. 42 (per LOOP L/N e LOOP L/PE) o Fig. 43 (per LOOP L/L).

Fig. 42: Collegamento dei terminali di misura in funzione LOOP L/N e LOOP L/PE

FULLTEST3 IT - 52

Fig. 43: Collegamento dei terminali di misura in funzione LOOP L/L

ATTENZIONE
Prima di coll egare i terminali di misura all’UUT   è   strettamente  necessario   verificare che non sia presente una tensione esterna  superiore a   10V   tra i   punti   di misura a   cui i terminali   sono  collegati

7.  Premere il tasto START/STOP per eseguire la misura. Il risultato del test è mostrato a display (vedere Fig. 44)

Fig. 44: Risultato misura test impedenza anello di guasto

Significato simboli a display

| Riferimento | Descrizione                                                                                                                                                                                                                                                                                                        |
| :---------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1           | Funzione selezionata                                                                                                                                                                                                                                                                                               |
| 2           | Sottorisultati – Tensione di rete rilevata durante la misura                                                                                                                                                                                                                                                       |
| 3           | Tasto virtuale della schermata di misura                                                                                                                                                                                                                                                                           |
| 4           | Tasto virtuale MODO per selezione del modo di misura. Il modo attualmente selezionato è visualizzato in basso sul pulsante.                                                                                                                                                                                        |
| 5           | Tasto virtuale LIMIT per selezionare il valore limite o modalità limite. Il valore attualmente selezionato (STANDARD o CALC) è visualizzato in basso sul pulsante. CALC indica che il valore è calcolato.                                                                                                       |
| 6           | Tasto virtuale PROTEZIONE per selezione del tipo di protezione (solo in modalità limite CALC). Il tipo attualmente selezionato è presente in basso sul pulsante.                                                                                                                                                   |
| 7           | Tasto virtuale IN per selezione della corrente nominale della protezione (solo in modalità limite CALC). Il valore attualmente selezionato è presente in basso sul pulsante.                                                                                                                                        |
| 8           | Valore misurato dell’impedenza dell’anello di guasto (visualizzato in verde - risultato OK, in rosso - risultato NON OK)                                                                                                                                                                                          |
| 9           | Valore calcolato della presunta corrente di cortocircuito (IPSC) (visualizzato in verde - risultato OK, in rosso - risultato NON OK)                                                                                                                                                                                |
| 10          | Orologio di sistema (hh.mm.ss)                                                                                                                                                                                                                                                                                   |
| 11          | Unità di misura del risultato (Ω per impedenza, kA per corrente di cortocircuito)                                                                                                                                                                                                                               |
| 12          | Valore limite impostato (se in modalità STANDARD) o calcolato (se in modalità CALC) per l’impedenza                                                                                                                                                                                                                |
| 13          | Valore limite per la presunta corrente di cortocircuito (solo se in modalità limite CALC). Viene calcolato come U NOM / Z LIMIT.                                                                                                                                                                                   |
| 14          | Stato del risultato della misura (simbolo visualizzato in verde - risultato OK, simbolo visualizzato in rosso - risultato NON OK)                                                                                                                                                                                   |

FULLTEST3 IT - 53

### 6.6.2. Calcolo della corrente di cortocircuito presunta

La presunta corrente di cortocircuito (IPSC) è calcolata dallo strumento in base al valore di impedenza dell’anello di guasto misurato e alla tensione nominale di rete impostata nel menù SETUP (§ 5.5). La formula utilizzata è la seguente:

IPSC = U NOM / Z misurata

Dove:

*   IPSC è la presunta corrente di cortocircuito (in A o kA)
*   U NOM è la tensione nominale di rete impostata (in V)
*   Z misurata è l’impedenza dell’anello di guasto misurata (in Ω)

ATTENZIONE
Il valore della presunta corrente di cortocircuito calcolato dallo strumento è una stima basata sul valore di impedenza misurato in quel preciso istante. Per una valutazione più accurata della corrente di cortocircuito reale, è necessario considerare altri fattori come la temperatura dei conduttori e la tolleranza dei dispositivi di protezione.

Esempio di calcolo del limite per IPSC in modalità limite CALC (CEI 64 - 8)

Secondo la normativa CEI 64 - 8, la massima impedenza dell’anello di guasto (Z LIMIT) deve essere tale da garantire che la corrente di guasto (IPSC) sia sufficiente a far intervenire la protezione entro un tempo prestabilito. La formula generale è:

Z LIMIT = (U rete x Fattore di correzione) / (k x IN)

Dove:

*   Z LIMIT è la massima impedenza dell’anello di guasto consentita (in Ω)
*   U rete è la tensione nominale di rete (ad esempio 230V)
*   Fattore di correzione: viene applicato un fattore di correzione (tipicamente 0.95) per tenere conto della caduta di tensione
*   k: fattore che dipende dal tipo di protezione (MCB o Fusibile) e dalla sua curva di intervento. Questo fattore rappresenta il multiplo della corrente nominale (IN) necessario per far intervenire la protezione entro il tempo prestabilito. Ad esempio, per un MCB curva B con tempo di intervento 0.1s, k è 5.
*   IN è la corrente nominale della protezione (in A)

Lo strumento calcola Z LIMIT e il corrispondente valore di IPSC = U NOM / Z LIMIT.

Esempio:

Misura LOOP L/PE

U NOM = 230V (impostato nel menù SETUP)

Protezione: MCB B, IN = 16A

Fattore di correzione = 0.95 (applicato internamente dallo strumento)

Tempo di intervento massimo = 0.4s (per circuiti terminali in locali ordinari)

Per un MCB curva B, con tempo di intervento 0.4s, il fattore k è approssimativamente 3.

Z LIMIT = (230V x 0.95) / (3 x 16A) = 218.5V / 48A = 4.55 Ω

IPSC limite = U NOM / Z LIMIT = 230V / 4.55 Ω = 50.55 A = 0.05 kA

In questo esempio, se la misura dell’impedenza LOOP L/PE è minore o uguale a 4.55 Ω, il risultato del test sull’impedenza sarà OK. Il valore della presunta corrente di cortocircuito misurata (IPSC) sarà visualizzato e confrontato con il valore limite calcolato (0.05 kA). Se IPSC misurata è maggiore o uguale a 0.05 kA, il risultato del test su IPSC sarà OK. Entrambi i risultati (Z e IPSC) devono essere OK affinché il risultato complessivo del test sia OK.

FULLTEST3 IT - 54

8.  Il risultato della misura dell’impedenza dell’anello di guasto (Z) e della presunta corrente di cortocircuito (IPSC) è mostrato in verde (risultato OK) o in rosso (risultato non OK). Entrambi i risultati sono accompagnati da un segnale acustico e dal simbolo (risultato OK) o da un segnale acustico prolungato e dal simbolo rosso e (risultato non OK).
9.  Salvare i risultati delle misure premendo il tasto SAVE (vedere § 7.1)

ATTENZIONE

*   La tensione esterna massima tra i terminali L/TRIG/L1, N/TRIG/L2 e PE/L3 è di 460 VAC. Non applicare alcuna tensione DC esterna! In caso di tensione esterna superiore, il fusibile F3 potrebbe intervenire
*   Durante l’esecuzione del test LOOP, lo strumento eroga una corrente di prova di circa 200mA per la misura veloce senza far intervenire RCD (modalità RCD NO TRIP) o una corrente maggiore per la misura standard (modalità STANDARD TRIP). Assicurarsi che l’oggetto in esame non sia sotto tensione durante il test STANDARD TRIP, in quanto potrebbe far intervenire il differenziale.

Fig. 45: Videata funzione LOOP – Modalità RCD NO TRIP

| Riferimento | Descrizione                                                                                                                                                                                                                                                                                                        |
| :---------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1           | Funzione selezionata                                                                                                                                                                                                                                                                                               |
| 2           | Sottorisultati – Tensione di rete rilevata durante la misura                                                                                                                                                                                                                                                       |
| 3           | Tasto virtuale della schermata di misura                                                                                                                                                                                                                                                                           |
| 4           | Tasto virtuale MODO per selezione del modo di misura. Il modo attualmente selezionato è visualizzato in basso sul pulsante.                                                                                                                                                                                        |
| 5           | Tasto virtuale LIMIT per selezionare il valore limite o modalità limite. Il valore attualmente selezionato (STANDARD o CALC) è visualizzato in basso sul pulsante. CALC indica che il valore è calcolato.                                                                                                       |
| 6           | Tasto virtuale PROTEZIONE per selezione del tipo di protezione (solo in modalità limite CALC). Il tipo attualmente selezionato è presente in basso sul pulsante.                                                                                                                                                   |
| 7           | Tasto virtuale IN per selezione della corrente nominale della protezione (solo in modalità limite CALC). Il valore attualmente selezionato è presente in basso sul pulsante.                                                                                                                                        |
| 8           | Valore misurato dell’impedenza dell’anello di guasto (visualizzato in verde - risultato OK, in rosso - risultato NON OK)                                                                                                                                                                                          |
| 9           | Valore calcolato della presunta corrente di cortocircuito (IPSC) (visualizzato in verde - risultato OK, in rosso - risultato NON OK)                                                                                                                                                                                |
| 10          | Orologio di sistema (hh.mm.ss)                                                                                                                                                                                                                                                                                   |
| 11          | Unità di misura del risultato (Ω per impedenza, kA per corrente di cortocircuito)                                                                                                                                                                                                                               |
| 12          | Valore limite impostato (se in modalità STANDARD) o calcolato (se in modalità CALC) per l’impedenza                                                                                                                                                                                                                |
| 13          | Valore limite per la presunta corrente di cortocircuito (solo se in modalità limite CALC). Viene calcolato come U NOM / Z LIMIT.                                                                                                                                                                                   |
| 14          | Stato del risultato della misura (simbolo visualizzato in verde - risultato OK, simbolo visualizzato in rosso - risultato NON OK). In modalità RCD NO TRIP, il simbolo può essere giallo se la corrente di misura è troppo bassa per garantire l'intervento dell'RCD.                                                    |

FULLTEST3 IT - 55

ATTENZIONE
La modalità RCD NO TRIP utilizza una corrente di prova molto bassa (circa 200mA) per evitare l’intervento degli RCD. Questo potrebbe comportare una minore precisione nella misura dell’impedenza rispetto alla modalità STANDARD TRIP. Utilizzare questa modalità solo quando è strettamente necessario evitare l’intervento degli RCD.

Per selezionare la modalità RCD NO TRIP (misura veloce senza intervento RCD):

1.  Premere il tasto virtuale e selezionare la schermata con la dicitura RCD NO TRIP (vedere Fig. 45)
2.  Controllare tutti i parametri e collegare i terminali di misura come mostrato nella Fig. 42.
3.  Premere il tasto START/STOP per eseguire la misura.

ATTENZIONE
In modalità RCD NO TRIP, il tempo di misura può essere più lungo rispetto alla modalità STANDARD TRIP a causa della minore corrente di prova utilizzata.

Per selezionare la modalità STANDARD TRIP (misura standard con intervento RCD):

1.  Premere il tasto virtuale e selezionare la schermata con la dicitura STANDARD TRIP (vedere Fig. 44)
2.  Controllare tutti i parametri e collegare i terminali di misura come mostrato nella Fig. 42 o Fig. 43.
3.  Premere il tasto START/STOP per eseguire la misura.

FULLTEST3 IT - 56

ATTENZIONE
La modalità STANDARD TRIP utilizza una corrente di prova sufficiente a far intervenire gli RCD. Assicurarsi che l’intervento dell’RCD non causi disagi o pericoli prima di eseguire il test in questa modalità.

Per selezionare la modalità con pinza esterna (accessorio opzionale IMP57):

Lo strumento FULLTEST3 può essere utilizzato in combinazione con il misuratore di impedenza ad alta risoluzione IMP57 (accessorio opzionale) per eseguire misure di impedenza anello di guasto con risoluzione elevata (0.1 mΩ) e corrente di prova elevata (fino a 200A). Fare riferimento al manuale d’uso dell’IMP57 per maggiori informazioni.

1.  Collegare l’IMP57 al FULLTEST3 tramite il connettore USB2 o USB3.
2.  Premere il tasto FUNC e selezionare la funzione LOOP.
3.  Selezionare la modalità con pinza esterna premendo il tasto virtuale e selezionando la schermata con la dicitura CLAMP (vedere Fig. 46).

Fig. 46: Videata funzione LOOP – Modalità CLAMP (con IMP57)

4.  Controllare tutti i parametri e collegare i terminali di misura come mostrato nel manuale d’uso dell’IMP57.
5.  Premere il tasto START/STOP per eseguire la misura.

FULLTEST3 IT - 57

### 6.6.3. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate                 | Descrizione                                                                                                                                                                                                                                                                                                                                                                                             |
| :---------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| TENSIONE ESTERNA                          | Tra i terminali di misura L/TRIG/L1, N/TRIG/L2 o PE/L3 è applicata una tensione esterna superiore a 460V. Rimuovere la tensione esterna per poter eseguire la misura.                                                                                                                                                                                                                                   |
| ERROR1!                                   | Il fusibile interno potrebbe essere saltato! Il fusibile non è sostituibile dal cliente, inviare lo strumento al servizio assistenza.                                                                                                                                                                                                                                                                   |
| ER R OR3!                                 | Il fusibile interno potrebbe essere saltato! Il fusibile non è sostituibile dal cliente, inviare lo strumento al servizio assistenza.                                                                                                                                                                                                                                                                   |
| NESSUNA TENSIONE DI RETE                  | Lo strumento non rileva una tensione di rete valida (>100V) tra i terminali L/TRIG/L1 e N/TRIG/L2 (o L/L per test LOOP L/L). Verificare il collegamento alla rete di alimentazione.                                                                                                                                                                                                                |
| PE SCOLLEGATO                             | Lo strumento non rileva il collegamento del terminale PE (solo per test LOOP L/PE). Verificare il collegamento a terra dello strumento e dell’oggetto in esame.                                                                                                                                                                                                                                       |
| CORRENTE DI PROVA TROPPO BASSA            | In modalità RCD NO TRIP, la corrente di prova generata è troppo bassa per garantire una misura affidabile. Verificare il collegamento e/o la resistenza dell’anello di guasto. Il risultato della misura potrebbe essere visualizzato in giallo.                                                                                                                                                            |
| IMPEDENZA TROPPO ELEVATA                  | L’impedenza misurata è superiore al limite impostato o calcolato. Il risultato della misura dell’impedenza sarà visualizzato in rosso.                                                                                                                                                                                                                                                                   |
| CORRENTE DI CORTO CIRCUITO TROPPO BASSA   | La presunta corrente di cortocircuito calcolata è inferiore al limite calcolato. Il risultato della misura della presunta corrente di cortocircuito sarà visualizzato in rosso.                                                                                                                                                                                                                         |
| LIMITE FUORI RANGE                        | Il limite calcolato è fuori range (ad esempio, limite calcolato <0.01 Ω o >1000 Ω). Verificare le impostazioni della protezione e/o la tensione nominale.                                                                                                                                                                                                                                             |
| IMP57 NON COLLEGATO                       | È stata selezionata la modalità con pinza esterna (CLAMP) ma l’accessorio IMP57 non è collegato o non è stato riconosciuto dallo strumento. Collegare l’IMP57 e riavviare la funzione.                                                                                                                                                                                                            |
| ER R OR IMP57                             | Si è verificato un errore durante la comunicazione con l’accessorio IMP57. Verificare il collegamento e/o riavviare lo strumento.                                                                                                                                                                                                                                                                      |

FULLTEST3 IT - 58

## 6.7. RESISTENZA GLOBALE DI TERRA/TENSIONE DI CONTATTO (RA)

Lo strumento permette di eseguire la misura della resistenza globale di terra (RA) e della tensione di contatto (UC) senza far intervenire i dispositivi differenziali (RCD), in accordo alle normative IEC/EN61557 - 6, CEI 64 - 8.

1.  Premere il tasto FUNC e selezionare la funzione RA. La seguente videata è mostrata a display

    Fig. 47: Videata iniziale funzione RA

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 7) ed eseguire la programmazione desiderata

    Tabella 7: Parametri impostabili per la funzione RA

    | Parametro   | Descrizione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Valore                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
    | :---------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | **I Δ N**   | Corrente differenziale nominale dell’RCD presente sull’impianto (utilizzata per il calcolo del limite di RA e UC)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 10, 30, 100, 300, 500, 650, 1000 mA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

### 6.7.1. Impostazione valore limite sulla misura

Il valore limite per la resistenza globale di terra (RA) e per la tensione di contatto (UC) è calcolato dallo strumento in base alla corrente differenziale nominale (IΔN) impostata e al limite di tensione di contatto impostato nel menù SETUP (§ 5.5). La formula generale è:

RA LIMIT = Tensione di contatto limite / I Δ N

UC LIMIT = Tensione di contatto limite

Dove:

*   RA LIMIT è la massima resistenza globale di terra consentita (in Ω)
*   Tensione di contatto limite è il valore impostato nel menù SETUP (25V o 50V)
*   I Δ N è la corrente differenziale nominale impostata (in A)
*   UC LIMIT è la massima tensione di contatto consentita (in V)

FULLTEST3 IT - 59

Esempio di calcolo del limite per RA e UC

I Δ N = 30 mA (impostato)

Tensione di contatto limite = 50 V (impostato nel menù SETUP)

RA LIMIT = 50V / 0.030A = 1666.67 Ω ≈ 1.67 kΩ

UC LIMIT = 50 V

In questo esempio, se la misura della resistenza globale di terra (RA) è minore o uguale a 1.67 kΩ E la misura della tensione di contatto (UC) è minore o uguale a 50V, il risultato del test sarà OK.

3.  Controllare la corrente differenziale nominale (IΔN) impostata. Modificarla, se necessario, premendo il tasto virtuale IΔN.
4.  Verificare il limite di tensione di contatto impostato nel menù SETUP (§ 5.5). Questo valore influenza il calcolo del limite di RA e UC.
5.  Selezionare la schermata di misura premendo il tasto virtuale e controllare nuovamente tutte le impostazioni
6.  Collegare i terminali di misura come mostrato nella seguente Fig. 48.

Fig. 48: Collegamento dei terminali di misura in funzione RA

ATTENZIONE
Prima di coll egare i terminali di misura all’UUT   è   strettamente  necessario   verificare che non sia presente una tensione esterna  superiore a   10V   tra i   punti   di misura a   cui i terminali   sono  collegati

7.  Premere il tasto START/STOP per eseguire la misura. Il risultato del test è mostrato a display (vedere Fig. 49)

Fig. 49: Risultato misura test resistenza globale di terra/tensione di contatto

FULLTEST3 IT - 60

Significato simboli a display

| Riferimento | Descrizione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                A technical report describes work that has been performed for the first time. It's important that enough information is included to allow the reader to reproduce the methodology and analysis performed. When writing a report there's a lot of things to include like an introduction, methodology, etc. I found that if I prepare a structure in markdown I can more quickly start writing the report.

In my day job, I produce scientific publications in a lab book format. The lab book entry needs to include a lot of metadata and I found that if I structure the metadata and content in a markdown format I can more quickly start writing the entry. In this article, I'll describe how I structure these lab book entries using markdown. The markdown file can then be converted to a PDF using pandoc. This is a great way to keep all your data and analysis in one place.

A template that I use for lab book entries:

```markdown
---
title: "TITLE"
author: "AUTHOR"
date: "YYYY-MM-DD"
layout: lab book
tag: tag1, tag2
project: project name
instrument: instrument name
instrument ID: instrument ID
instrument location: instrument location
software: software name
software version: software version
software location: software location
sample name: sample name
sample description: sample description
sample location: sample location
sample preparation: sample preparation
sample concentration: sample concentration
sample volume: sample volume
sample solvent: sample solvent
sample purity: sample purity
sample date: YYYY-MM-DD
sample reference: sample reference
notes: general notes on the sample preparation
purpose: What was the purpose of this experiment?
experiment setup: How was the experiment setup?
data analysis: How was the data analysed?
results: What are the results?
conclusions: What are the conclusions?
future work: What is the future work?
files: List of files that were generated during this experiment
```

Each field needs to be filled in with the appropriate information. The fields that are used are defined by the pandoc template that is used to convert the markdown file to a PDF. In this case, I'm using a custom template that I created. The template is based on the default pandoc LaTeX template.

The metadata fields are used to populate the header of the PDF document. The content fields are used to populate the body of the PDF document. I found that by using these fields I can quickly start writing the lab book entry without having to think about the structure of the document.

The markdown file can then be converted to a PDF using pandoc:

```bash
pandoc -o lab book.pdf lab book.md --template=lab book.tex
```

In this case, I'm using a custom LaTeX template that I created. The template is based on the default pandoc LaTeX template.

The template creates a PDF document with a header that includes the metadata fields and a body that includes the content fields. The content fields are formatted as sections with headings.

The markdown file can also be converted to other formats using pandoc. For example, the markdown file can be converted to HTML:

```bash
pandoc -o lab book.html lab book.md
```

This is useful if you want to share the lab book entry with others who don't have pandoc installed.

The markdown file can also be converted to a Word document:

```bash
pandoc -o lab book.docx lab book.md
```

This is useful if you need to share the lab book entry with others who prefer to work with Word documents.

The markdown file can also be converted to a JSON file:

```bash
pandoc -o lab book.json lab book.md
```

This is useful if you want to parse the lab book entry programmatically.

The markdown file can also be converted to a YAML file:

```bash
pandoc -o lab book.yaml lab book.md
```

This is useful if you want to parse the lab book entry programmatically.

The markdown file can also be converted to a CSV file:

```bash
pandoc -o lab book.csv lab book.md
```

This is useful if you want to import the lab book entry into a spreadsheet program.

The markdown file can also be converted to a TSV file:

```bash
pandoc -o lab book.tsv lab book.md
```

This is useful if you want to import the lab book entry into a spreadsheet program.

The markdown file can also be converted to a LibreOffice ODT file:

```bash
pandoc -o lab book.odt lab book.md
```

This is useful if you prefer to work with LibreOffice.

The markdown file can also be converted to an EPUB file:

```bash
pandoc -o lab book.epub lab book.md
```

This is useful if you want to read the lab book entry on an e-reader.

The markdown file can also be converted to a Texinfo file:

```bash
pandoc -o lab book.texinfo lab book.md
```

This is useful if you want to generate documentation for a software project.

The markdown file can also be converted to a ConTeXt file:

```bash
pandoc -o lab book.context lab book.md
```

This is useful if you prefer to work with ConTeXt.

The markdown file can also be converted to a DocBook file:

```bash
pandoc -o lab book.docbook lab book.md
```

This is useful if you want to generate documentation in DocBook format.

The markdown file can also be converted to a Textile file:

```bash
pandoc -o lab book.textile lab book.md
```

This is useful if you prefer to work with Textile.

The markdown file can also be converted to a reStructuredText file:

```bash
pandoc -o lab book.rst lab book.md
```

This is useful if you prefer to work with reStructuredText.

The markdown file can also be converted to a MediaWiki file:

```bash
pandoc -o lab book.mediawiki lab book.md
```

This is useful if you want to publish the lab book entry on a MediaWiki site.

The markdown file can also be converted to a DokuWiki file:

```bash
pandoc -o lab book.dokuwiki lab book.md
```

This is useful if you want to publish the lab book entry on a DokuWiki site.

The markdown file can also be converted to a TiddlyWiki file:

```bash
pandoc -o lab book.tiddlywiki lab book.md
```

This is useful if you want to publish the lab book entry on a TiddlyWiki site.

The markdown file can also be converted to a TWiki file:

```bash
pandoc -o lab book.twiki lab book.md
```

This is useful if you want to publish the lab book entry on a TWiki site.

The markdown file can also be converted to a Viki file:

```bash
pandoc -o lab book.viki lab book.md
```

This is useful if you want to publish the lab book entry on a Viki site.

The markdown file can also be converted to a ZimWiki file:

```bash
pandoc -o lab book.zimwiki lab book.md
```

This is useful if you prefer to work with ZimWiki.

The markdown file can also be converted to a Jira wiki file:

```bash
pandoc -o lab book.jira.wiki lab book.md
```

This is useful if you want to publish the lab book entry on a Jira wiki site.

The markdown file can also be converted to a Confluence wiki file:

```bash
pandoc -o lab book.confluence.wiki lab book.md
```

This is useful if you want to publish the lab book entry on a Confluence wiki site.

The markdown file can also be converted to a GitHub wiki file:

```bash
pandoc -o lab book.github.wiki lab book.md
```

This is useful if you want to publish the lab book entry on a GitHub wiki site.

The markdown file can also be converted to a GitLab wiki file:

```bash
pandoc -o lab book.gitlab.wiki lab book.md
```

This is useful if you want to publish the lab book entry on a GitLab wiki site.

The markdown file can also be converted to a MoinMoin wiki file:

```bash
pandoc -o lab book.moinmoin.wiki lab book.md
```

This is useful if you want to publish the lab book entry on a MoinMoin wiki site.

The markdown file can also be converted to a Creole wiki file:

```bash
pandoc -o lab book.creole.wiki lab book.md
```

This is useful if you prefer to work with Creole wiki.

The markdown file can also be converted to a HTML Slidy file:

```bash
pandoc -o lab book.slidy.html lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a HTML DZSlides file:

```bash
pandoc -o lab book.dzslides.html lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a HTML Reveal.js file:

```bash
pandoc -o lab book.revealjs.html lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a HTML Slideous file:

```bash
pandoc -o lab book.slideous.html lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a HTML S5 file:

```bash
pandoc -o lab book.s5.html lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -o lab book.plain.tex lab book.md
```

This is useful if you prefer to work with the Plain LaTeX class.

The markdown file can also be converted to a LaTeX Beamer file:

```bash
pandoc -o lab book.beamer.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX PowerPoint file:

```bash
pandoc -o lab book.powerpoint.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Prosper file:

```bash
pandoc -o lab book.prosper.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Xaringan file:

```bash
pandoc -o lab book.xaringan.tex lab book.md
```

This is useful if you want to create a presentation from the lab book entry.

The markdown file can also be converted to a LaTeX Tufte file:

```bash
pandoc -o lab book.tufte.tex lab book.md
```

This is useful if you prefer to work with the Tufte LaTeX class.

The markdown file can also be converted to a LaTeX Memoir file:

```bash
pandoc -o lab book.memoir.tex lab book.md
```

This is useful if you prefer to work with the Memoir LaTeX class.

The markdown file can also be converted to a LaTeX Book file:

```bash
pandoc -o lab book.book.tex lab book.md
```

This is useful if you prefer to work with the Book LaTeX class.

The markdown file can also be converted to a LaTeX Article file:

```bash
pandoc -o lab book.article.tex lab book.md
```

This is useful if you prefer to work with the Article LaTeX class.

The markdown file can also be converted to a LaTeX Report file:

```bash
pandoc -o lab book.report.tex lab book.md
```

This is useful if you prefer to work with the Report LaTeX class.

The markdown file can also be converted to a LaTeX Letter file:

```bash
pandoc -o lab book.letter.tex lab book.md
```

This is useful if you prefer to work with the Letter LaTeX class.

The markdown file can also be converted to a LaTeX Minimal file:

```bash
pandoc -o lab book.minimal.tex lab book.md
```

This is useful if you prefer to work with the Minimal LaTeX class.

The markdown file can also be converted to a LaTeX Plain file:

```bash
pandoc -

<!-- Chunk: Pages 34-66 -->
FULLTEST3 IT - 33

## 6.2. CONTINUITÀ CON CONDUTTORI DI PROTEZIONE – METODO RPE - 4WIRE

La misura di continuità eseguita con il metodo a 4-fili è disponibile solo con corrente di prova di 25A e, per la natura del metodo Kelvin utilizzato, non richiede nessuna calibrazione della resistenza dei cavi di prova. Ciò significa che è possibile prolungare (a coppie) i cavi di prova ed eseguire il test senza alterare il risultato di misura. Per il prolungamento di ogni cavo è raccomandato l’uso dei connettori opzionali **1066-IECN** (Nero) e **1066-IECR** (Rosso).

1.  Premere il tasto **FUNC** e selezionare la funzione **RPE-4WIRE**. La seguente videata è mostrata a display
    Fig. 29: Videata iniziale funzione RPE-4WIRE

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 2) ed eseguire la programmazione desiderata

    | Parametro     | Descrizione                                                              | Valore                                                                                                                                                                                                |
    | :------------ | :----------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | LIMIT         | Soglia limite di riferimento                                             | STANDARD: 0.01  ÷ 20.0 , 60204 SET L, 60204 SET Z                                                                                                                                                   |
    | 60204 SET L   | Test con impostazione lunghezza conduttore                               | Lunghezza: 0.1m ÷ 999.9m, Sezione: 1, 1.5, 2.5, 4, 6, 10, 16, 25, 35, 50, 70, 95, 120, 150, 185, 240, 300, 400, 500, 630 mm², Materiale: Cu (Rame) o Al (Alluminio)                                     |
    | 60204 SET Z   | Test con impostazione impedenza di linea                                 | ZLine: 0.001  ÷ 2.000 , Protezione MCB: B, C, D, K, Protezione Fusibile: gG, aM, Corrente nominale protezione (vedere § 6.2.1)                                                                       |
    | MODE          | Modo di misura                                                           | Manuale / Timer                                                                                                                                                                                       |
    | TIMER         | Tempo di misura                                                          | 00:02 ÷ 05:00 (2s ÷ 5 min)                                                                                                                                                                            |

    Tabella 2: Parametri impostabili per la funzione RPE - 4WIRE

FULLTEST3 IT - 34

### 6.2.1. Impostazione valore limite sulla misura

Lo strumento permette di eseguire il test di continuità calcolando il limite di riferimento in funzione della lunghezza (nota a priori) del conduttore oppure in funzione dell’impedenza della sorgente di alimentazione della linea in accordo alle prescrizioni della normativa IEC/EN60204-1.

**Modo EN60204 SET L**

Il valore limite è calcolato sulla base della lunghezza, della sezione e del materiale del conduttore in prova. I parametri possono essere selezionati/regolati entro gli intervalli seguenti. I valori dei parametri sono riportati nella Tabella 2

**Modo EN60204 SET Z**

Il valore limite è calcolato in base all'impedenza di linea immessa (Z LINE), al tipo di protezione presente, alla corrente nominale della protezione e alla sezione del conduttore in prova. I valor dei parametri selezionabili sono i seguenti:

*   Impedenza di linea: campo 0.001  ÷ 2.000  in passi da 0.001 
*   Tipo di protezione MCB (Magnetotermica): curva B, C, D, K
*   Corrente nominale protezione MCB: 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A (curva B), 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A (curva C), 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32A (curve D, K)
*   Tipo di protezione Fusibile: gG, aM
*   Corrente nominale protezione Fusibile gG: 2, 4, 6, 10, 13, 16, 20, 25, 32, 35, 40, 50, 63, 80, 100, 125, 160, 200, 224, 250, 315, 355, 400, 500, 630A
*   Corrente nominale protezione Fusibile aM: 6, 10, 16, 20, 25, 32, 35, 40, 50, 63, 80, 100, 160, 224, 250, 315, 355, 400, 500, 630A
*   Materiale conduttore: Cu (Rame), Al (Alluminio)
*   Sezione conduttore: 1, 2.5, 4, 6, 10, 16, 25, 35, 50, 70, 95, 120, 150, 185, 240, 300, 400, 500, 630 mm²

3.  Controllare la modalità selezionata (MANUALE o TIMER) e modificarla, se necessario, premendo il tasto virtuale **MODO**. In modalità MANUALE, la misura è attivata/arrestata dalla pressione del tasto **START/STOP**. In modalità TIMER, la misura è attivata dalla pressione del tasto **START/STOP** ed è arrestata allo scadere del tempo di misura impostato o da una nuova pressione del tasto **START/STOP**.
4.  Selezionare la schermata di misura premendo il tasto virtuale (icona di schermata) e controllare nuovamente tutte le impostazioni
5.  Collegare i terminali di misura come mostrato nella seguente Fig. 30
    Fig. 30: Collegamento dei terminali di misura in funzione RPE - 4WIRE

FULLTEST3 IT - 35

ATTENZIONE

Prima di collegare i terminali di misura all' UUT è strettamente necessario verificare che non sia presente una tensione esterna superiore a 10V tra i punti di misura a cui i terminali sono collegati

6.  Premere il tasto **START/STOP** per eseguire la misura. Il risultato del test è mostrato a display (vedere Fig. 31)
    Fig. 31: Risultato misura test continuità RPE - 4WIRE

    **Significato simboli a display**

    | Riferimento | Descrizione                                                                                                                                                                                                                                                         |
    | :---------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
    | 1           | Funzione selezionata                                                                                                                                                                                                                                                |
    | 2           | Barra di avanzamento durante la misura in modalità TIMER                                                                                                                                                                                                            |
    | 3           | Sottorisultati – Corrente reale di prova applicata                                                                                                                                                                                                                  |
    | 4           | Tasto virtuale della schermata di misura                                                                                                                                                                                                                            |
    | 5           | Tasto virtuale **LIMIT** per selezionare il valore limite di riferimento Il valore attualmente selezionato (STANDARD) o CALC è visualizzato in basso sul pulsante. CALC indica che il valore è calcolato                                                              |
    | 6           | Tasto virtuale **MODE** per selezione modo di funzionamento (MANUALE o TIMER). Il modo attualmente selezionato è presente in basso sul pulsante. Il modo Timer è disponibile solo se è selezionato il valore limite STANDARD                                         |
    | 7           | Valore misurato (visualizzato in verde - risultato OK, in rosso - risultato NON OK)                                                                                                                                                                                 |
    | 8           | Orologio di sistema (hh.mm.ss)                                                                                                                                                                                                                                      |
    | 9           | Unità di misura del risultato ()                                                                                                                                                                                                                                   |
    | 10          | Tempo di misura impostato (solo in modo TIMER)                                                                                                                                                                                                                      |
    | 11          | Stato del risultato della misura (simbolo (checkmark) visualizzato in verde - risultato OK, simbolo (cross) visualizzato in rosso - risultato NON OK o simbolo (triangle) visualizzato in giallo – risultato OK, ma corrente di misura troppo bassa)             |

7.  Il risultato di misura è mostrato in verde (valore minore o uguale al limite impostato) o in rosso (valore superiore al limite impostato) ed è accompagnato da un segnale acustico e dal simbolo (checkmark) (risultato OK) o da un segnale acustico prolungato e dal simbolo (cross) rosso e (risultato non OK). Il simbolo (triangle) in giallo è mostrato per risultato OK, ma corrente di misura troppo bassa)

FULLTEST3 IT - 36

8.  Salvare i risultati delle misure premendo il tasto **SAVE** (vedere § 7.1)

ATTENZIONE

*   La tensione esterna massima tra due terminali RPE o tra due terminali SENSE è di 10 VAC. Non applicare alcuna tensione DC esterna! In caso di tensione esterna superiore, il fusibile F4 potrebbe intervenire
*   Nel caso in cui non siano collegati terminali SENSE, il risultato della misura comprenderà anche la resistenza dei terminali di misura della corrente
*   Il tempo di misura in modalità MANUALE è limitato a 5min

### 6.2.2. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate       | Descrizione                                                                                                                                                                                                                                                             |
| :------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TENSIONE ESTERNA                | • Tra due terminali di misura RPE o tra due terminali di misura SENSE è applicata una tensione esterna superiore a 3 VAC (mentre non è in corso alcuna misura) o superiore a 10 VAC (mentre è in corso una misura). • Una tensione esterna superiore a 5 ÷ 30 V è applicata tra i terminali di misura RPE o SENSE e la terra GND. Eliminare la tensione esterna! |
| FUSIBILE F4!                    | Il fusibile F4 è saltato.                                                                                                                                                                                                                                               |
| ERRORE 1!                       | Il fusibile interno potrebbe essere saltato! Il fusibile non è sostituibile dal cliente, inviare lo strumento al servizio assistenza.                                                                                                                                     |
| TEMPO MISURA > 5MIN CONTROLLARE TIMER | Il Timer è impostato ad un valore maggiore di 5 minuti Il test con corrente di 25A permette l’impostazione del timer al massimo di 5minuti                                                                                                                            |

FULLTEST3 IT - 37

## 6.3. RESISTENZA DI ISOLAMENTO (M )

In accordo alle prescrizioni della normativa IEC/EN60204-1 la resistenza di isolamento tra i circuiti di potenza della macchina e il riferimento di terra deve essere controllata applicando una tensione di prova di 500VDC. Il valore limite minimo di riferimento è di 1M. Assicurarsi che tutti gli interruttori dell'oggetto in esame siano chiusi al fine di controllare tutti i suoi componenti. Per la misura, tutti i conduttori attivi (L1, L2, L3 e N) devono essere messi in cortocircuito. Scollegare o sezionare tutte parti/logiche di controllo della macchina che potrebbero essere danneggiate dalla tensione di prova.

1.  Premere il tasto **FUNC** e selezionare la funzione **M**. La seguente videata è mostrata a display
    Fig. 32: Videata iniziale funzione M

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 3) ed eseguire la programmazione desiderata

    | Parametro | Descrizione                       | Valore                        |
    | :-------- | :-------------------------------- | :---------------------------- |
    | Um NOM    | Tensione di prova nominale        | 100, 250, 500, 1000VDC        |
    | MODE      | Modo di misura                    | Manuale, Timer, Auto          |
    | TIMER     | Tempo di misura                   | 00:01 ÷ 60:00 (1s ÷ 60min)    |
    | LIMIT     | Soglia limite minima di riferimento | 0.01M  ÷ 100.0M           |

    Tabella 3: Parametri impostabili per la funzione M

3.  Controllare la modalità selezionata (MANUALE, TIMER o AUTO) e modificarla premendo il tasto virtuale **MODE**.
4.  Controllare il valore limite selezionato e modificarlo se necessario premendo il tasto virtuale **LIMIT**. Sono disponibili quattro valori limite preimpostati indipendenti per velocizzare le operazioni. Selezionare il valore più vicino a quello desiderato e modificarlo utilizzando i tasti virtuali **+** e **―**, se necessario
5.  Selezionare la schermata di misura premendo il tasto virtuale (icona di schermata) e controllare nuovamente tutte le impostazioni
6.  Collegare i terminali di misura come mostrato nella seguente Fig. 33

FULLTEST3 IT - 38

Fig. 33: Collegamento dei terminali per misura M

7.  Premere il tasto **START/STOP** per eseguire la misura. Il risultato del test è mostrato a display (vedere Fig. 34)
    Fig. 34: Risultato misura M

    **Significato simboli a display**

    | Riferimento | Descrizione                                                                                                     |
    | :---------- | :-------------------------------------------------------------------------------------------------------------- |
    | 1           | Funzione selezionata                                                                                            |
    | 2           | Barra di avanzamento durante la misura in modalità TIMER                                                        |
    | 3           | Tensione di prova applicata durante la misura                                                                   |
    | 4           | Tasto virtuale della schermata di misura                                                                        |
    | 5           | Tasto virtuale **Utest** per selezionare la tensione di prova nominale (100, 250, 500 o 1000VDC). Il valore attualmente selezionato è visualizzato in basso sul pulsante                                                                                                                                   |
    | 6           | Tasto virtuale **MODE** per selezionare la modalità di funzionamento (MANUALE, TIMER o AUTO). La modalità attualmente selezionata è visualizzata in basso sul pulsante                                                                                                                             |
    | 7           | Tasto virtuale **LIMIT** per selezionare la resistenza di isolamento limite minima. Il valore attualmente selezionato è visualizzato in basso sul pulsante                                                                                                                                           |
    | 8           | Valore misurato (visualizzato in verde - risultato OK, in rosso - risultato NON OK).                                                                                                                                                                                                                |
    | 9           | Orologio di sistema (hh.mm.ss)                                                                                                                                                                                                                                                                      |
    | 10          | Unità di misura del risultato (M)                                                                                                                                                                                                                                                                  |
    | 11          | Tempo di misura impostato (solo in modo TIMER)                                                                                                                                                                                                                                                      |
    | 12          | Stato del risultato della misura (simbolo (checkmark) visualizzato in verde - risultato OK, simbolo (cross) visualizzato in rosso - risultato NON OK)                                                                                                                                               |

FULLTEST3 IT - 39

8.  Il risultato della misura apparirà sul display in verde (risultato superiore o uguale al valore limite impostato) o in rosso (risultato inferiore al valore limite impostato). Il risultato finale sarà accompagnato dal simbolo (checkmark) verde e da un segnale acustico (risultato OK) o dal simbolo (cross) rosso e da un segnale acustico prolungato (risultato non OK)
9.  Salvare i risultati delle misure premendo il tasto **SAVE** (vedere § 7.1)

### 6.3.1. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate | Descrizione                                                                                                                                                                                                                                                              |
| :------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TENSIONE ESTERNA          | • Tra i terminali di misura positivi e negativi è applicata una tensione esterna superiore a 10 VAC (mentre non è in corso alcuna misura) o superiore a 50 VAC (mentre è in corso una misura). • Una tensione esterna negativa superiore a circa 10 VDC è applicata tra i terminali di misura positivi e negativi (mentre è in corso una misura). Eliminare la tensione esterna |
| SCARICA!                  | La capacità esterna (o interna) caricata durante la misura si sta scaricando. Attendere che il messaggio scompaia! Non scollegare i terminali di misura finché il messaggio non sarà sparito                                                                            |

FULLTEST3 IT - 40

## 6.4. TEST RIGIDITÀ DIELETTRICA (DIELECTRIC)

In accordo alle prescrizioni della normativa IEC/EN60204-1 i circuiti di potenza delle macchine elettriche devono resistere a un test di tensione tra i conduttori attivi in cortocircuito e l'impianto di terra per almeno 1s. Il test è eseguito a un valore doppio dell'alimentazione nominale (o 1000V AC scegliendo il più grande dei due valori) 50Hz. Scollegare o sezionare tutte parti/logiche di controllo della macchina che potrebbero essere danneggiate dalla tensione di prova.

ATTENZIONE

Lo strumento genera una tensione pericolosa. In base alla normativa EN50191 (vedere § 5.5.2) è necessario adottare le seguenti misure di sicurezza prima di procedere con il test:

*   Bloccare l'accesso all'area potenzialmente pericolosa
*   Apporre cartelli di segnalazione (Attenzione! Alta tensione, pericolo di morte)
*   Installare fari luminosi (verdi, rossi) per garantire alta visibilità (considerare l’accessorio opzionale **FT3R-GLP**)
*   Installare un interruttore di SPEGNIMENTO D'EMERGENZA nell'impianto di rete al di fuori della zona pericolosa (considerare l’accessorio opzionale **FT3SFTSW**)
*   Esecuzione del test solo da parte di personale qualificato sottoposto a regolare addestramento sotto la supervisione di uno specialista
*   Usare le sonde di sicurezza esclusivamente servendosi della protezione contro il contatto o maneggiandole con entrambe le mani. Tenere sempre una sola sonda in una mano
*   Non collegare un terminale di misura all' UUT lavorando contemporaneamente con una sonda o tenere entrambe le sonde in una sola mano
*   Non toccare l'oggetto in esame durante il test. Se necessario, prendere ulteriori precauzioni (ad es. copertura creata con tappetini isolanti) per proteggere l'operatore che esegue il test dal contatto involontario con l'oggetto in esame
*   Assicurarsi che tutti gli interruttori dell' UUT siano chiusi al fine di controllare tutti i suoi componenti. Per la misura, tutti i conduttori attivi (L1, L2, L3 e N) devono essere messi in cortocircuito

1.  Premere il tasto **FUNC** e selezionare la funzione **DIELECT**. La seguente videata è mostrata a display
    Fig. 35: Videata iniziale funzione DIELECTRIC

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 4) ed eseguire la programmazione desiderata

FULLTEST3 IT - 41

| Parametro   | Descrizione                       | Valore                              |
| :---------- | :-------------------------------- | :---------------------------------- |
| U test NOM  | Tensione di prova nominale        | 250 V ÷ 5100VAC                     |
| MODE        | Modo di misura                    | Manuale, Burn, Pulse, Rampa 75%, Rampa 50% |
| TIMER       | Tempo di misura (solo Rampa)      | 00:01 ÷ 10:00 (1s ÷ 10min)          |
| LIMIT       | Soglia limite della corrente di scarica | 1mA ÷ 110mA                       |
| CHAR        | Carattere della corrente di scarica | I APP o I REAL (vedere § 6.4.2)       |

Tabella 4: Parametri impostabili per la funzione DIELECTRIC

### 6.4.1. Modi di funzionamento

Lo strumento consente la selezione dei seguenti modi fi funzionamento:

*   Modo **Manuale** → La tensione di prova è mantenuta costantemente finché il tasto **START/STOP** resta premuto (vedere Fig. 36). La corrente di scarica misurata è confrontata con il valore limite impostato e il risultato è salvato in memoria
*   Modo **Burn** → La tensione di prova è mantenuta costantemente finché il tasto **START/STOP** resta premuto (vedere Fig. 36) ma il risultato NON è confrontato con alcun limite e NON è salvato in memoria (test funzionale)

    Fig. 36: Test Rigidità Dielettrica in modo Manuale o Burn

*   Modo **Rampa 75%** (rampa singola) → Alla pressione del tasto START/STOP la tensione di prova sale fino al 75% della tensione nominale poi impiega 5s per portarsi al valore nominale. Successivamente è mantenuta per un tempo definito da un Timer programmabile (vedere Fig. 37)

    Fig. 37: Test Rigidità Dielettrica in modo Rampa 75%

FULLTEST3 IT - 42

*   Modo **Rampa 50%** (doppia rampa) → Alla pressione del tasto **START/STOP** la tensione di prova sale fino al 50% della tensione nominale poi impiega 1s per portarsi al 75% del valore nominale quindi impiega altri 5s per portarsi al valore nominale. Successivamente è mantenuta per un tempo definito da un Timer programmabile (vedere Fig. 38)

    Fig. 38: Test Rigidità Dielettrica in modo Rampa 50%

*   Modo **Pulse** → il test effettivo ha una durata di 3 cicli di misura (60ms @50Hz, 50ms @60Hz) in accordo alla IEC/EN61439-1 3a edizione

### 6.4.2. Tipologia corrente di scarica

Lo strumento è in grado di misurare la corrente di scarica dielettrica nei due modi seguenti:

*   **IAPP** → misura il valore RMS totale della corrente di perdita dielettrica (comprensiva di componenti capacitive)
*   **IREAL** → misura solo la parte "reale" della corrente ossia la corrente in fase con la tensione e quindi associabile ad una perdita di tipo Resistiva (raccomandata nella maggior parte dei casi). Quest'ultima modalità serve ad "ignorare" la componente di corrente capacitiva introdotta tipicamente da filtri per la compatibilità elettromagnetica (la cui corrente non è ovviamente associabile a nessun tipo di perdita/rottura

3.  Controllare la modalità selezionata e modificarla se necessario premendo il tasto virtuale **MODE**. È possibile selezionare la modalità MANUALE, RAMPA, BURN o PULSE
4.  Controllare la tensione di prova selezionata (da 250 a 5100V) e modificarla se necessario premendo il tasto virtuale **Utest NOM**
5.  Controllare la corrente limite selezionata e modificarla se necessario premendo il tasto virtuale **LIMIT**. Sono disponibili quattro correnti limite preimpostate indipendenti per velocizzare le operazioni. Selezionare il valore più vicino a quello desiderato e modificarlo utilizzando i tasti virtuali **+** e **―**, se necessario
6.  Controllare il carattere selezionato della corrente visualizzata (I APP o I REAL) e modificarla se necessario, premendo il tasto virtuale **CHAR**
7.  Selezionare la schermata di misura premendo il tasto virtuale (icona di schermata) e controllare nuovamente tutte le impostazioni

FULLTEST3 IT - 43

8.  Inserire i terminali di misura tra le boccole **COM** e la boccola corrispondente alla tensione di prova programmata e collegare lo strumento come mostrato nella
9.  Collegare sempre il terminale **COM** alla terra GND se l'uscita OUT misurata è collegata a terra, altrimenti eventuali correnti di dispersione capacitive potrebbero scaricarsi a terra e disturbare la misura
    Fig. 39: Collegamento dei terminali per misura DIELECTRIC

10. Premere il tasto **START/STOP** per eseguire la misura. Il risultato del test è mostrato a display (vedere Fig. 34)
    Fig. 40: Risultato misura DIELECTRIC

    **Significato simboli a display**

    | Riferimento | Descrizione                                                                                                                                                                                                                                                                           |
    | :---------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
    | 1           | Funzione selezionata                                                                                                                                                                                                                                                                  |
    | 2           | Barra di avanzamento, segna il tempo durante la misura (solo in modalità RAMPA)                                                                                                                                                                                                        |
    | 3           | Tensione di prova applicata durante la misura                                                                                                                                                                                                                                         |
    | 4           | Tasto virtuale della schermata di misura                                                                                                                                                                                                                                              |
    | 5           | Tasto virtuale **MODE** per selezionare la modalità di funzionamento (MANUALE, BURN, PULSE, RAMPA 75% o RAMPA 50%). La modalità attualmente selezionata è visualizzata in basso sul pulsante                                                                                              |
    | 6           | Tasto virtuale **Utest NOM** per selezionare la tensione di prova nominale (da 250V a 5100VAC). Il valore attualmente selezionato è visualizzato in basso sul pulsante                                                                                                                      |
    | 7           | Tasto virtuale **LIMIT**. La corrente di dispersione limite (corrente di intervento) attualmente selezionata è visualizzata in basso sul pulsante.                                                                                                                                    |
    | 8           | Tasto virtuale **CHAR** (carattere) per selezionare il carattere della corrente visualizzata (I APP o I REAL). Il carattere attualmente selezionato è visualizzato in basso sul pulsante                                                                                                |

FULLTEST3 IT - 44

| Riferimento | Descrizione                                                                                                                                                                                                                                                                                                                                                                          |
| :---------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 9           | Corrente di dispersione, in verde se il risultato è inferiore o uguale al valore limite impostato. Nel caso in cui si verificasse un superamento durante il test, il valore limite sarà visualizzato in rosso                                                                                                                                                                          |
| 10          | Orologio in tempo reale (hh.mm.ss)                                                                                                                                                                                                                                                                                                                                                     |
| 11          | Unità di misura del risultato (mA)                                                                                                                                                                                                                                                                                                                                                     |
| 12          | Tempo di misura impostato (solo in modalità RAMPA)                                                                                                                                                                                                                                                                                                                                   |
| 13          | Stato del risultato della misura (simbolo (checkmark) verde - il risultato è inferiore o uguale al valore limite impostato, simbolo (cross) rosso - si è verificato un superamento durante il test o il risultato è superiore al valore limite impostato                                                                                                                             |

11. A display appariranno alcune avvertenze, insieme alla spiegazione di come collegare i terminali di misura in funzione della tensione di prova selezionata. Controllare la connessione, quindi confermare premendo il tasto virtuale **SI**: il messaggio “PRONTO” apparirà sullo schermo per 10 secondi. Il tasto **START/STOP** è attivo mentre lo schermo visualizza il messaggio “PRONTO”. Tenere premuto il tasto **START/STOP**; la tensione di prova sarà applicata ai terminali di misura. Il test avrà termine al rilascio del tasto **START/STOP** (modalità MANUALE o BURN) o allo scadere del tempo di prova impostato (modalità RAMPA). In modo PULSE mantenere premuto il tasto **START/STOP** per almeno 5s fino alla visualizzazione dell’esito a display
12. Il risultato della misura apparirà sul display in verde se inferiore o uguale al valore limite impostato. Il risultato finale sarà accompagnato dal simbolo (checkmark) verde e da un segnale acustico breve (risultato OK). Nel caso in cui si verificasse un superamento durante il test, il test sarà arrestato e il valore limite della corrente di prova sarà visualizzato in rosso, accompagnato dal simbolo (cross) rosso e da un segnale acustico prolungato
13. Salvare i risultati delle misure premendo il tasto **SAVE** (vedere § 7.1)

FULLTEST3 IT - 45

### 6.4.3. Dispositivi di sicurezza

**INGRESSO DI SICUREZZA** (SAFETY INPUT)

Al fine di ottenere un livello di sicurezza ancora più elevato è possibile installare il connettore **INGRESSO DI SICUREZZA** (accessorio opzionale **FT3SFTSW**). È possibile collegarvi l'interruttore di sicurezza di una barriera meccanica al fine di disabilitare la funzione DIELETTRICA in caso di apertura dell'interruttore di sicurezza. A tale scopo, selezionare la modalità INGRESSO DI SICUREZZA abilitato dal menù come segue:
Tasto **MENU** → tasto virtuale **IMPOSTAZIONI** → tasto virtuale **EN50191** (vedere § 5.5.2) → tasto virtuale **ABILITATO**.

**LAMPADA DI ATTENZIONE**

In accordo alla EN50191 il più alto livello di sicurezza deve essere effettuata quando si lavora con tensioni elevate, come quando si effettuano misure di rigidità dielettrica. Per questo scopo lo strumento offre un’uscita per pilotare l’accensione di una lampada di attenzione (accessorio opzionale **FT3R-GLP**). Usare solo le lampade originali del fornitore

ATTENZIONE

*   Collegare sempre il terminale **COM** alla terra GND se l' UUT misurato è collegato a terra, altrimenti eventuali correnti di dispersione capacitive potrebbero scaricarsi a terra e disturbare la misura
*   Il tempo di misura in modalità Manuale è limitato a 60min

### 6.4.4. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate | Descrizione                                                                                                |
| :------------------------ | :--------------------------------------------------------------------------------------------------------- |
| ERROR1!                   | Il fusibile interno potrebbe essere danneggiato Il fusibile non è sostituibile dal cliente, inviare lo strumento all’ufficio assistenza. |

FULLTEST3 IT - 46

## 6.5. TEST SU DIFFERENZIALI (RCD)

Lo strumento consente di eseguire misure di tempo e corrente di intervento (Rampa) su interruttori differenziali di tipo A, AC e B, Generali, Selettivi e Ritardati in accordo alle normative di riferimento IEC/EN61008 e IEC/EN61009.

1.  Premere il tasto **FUNC** e selezionare la funzione **RCD**. La seguente videata è mostrata a display
    Fig. 41: Videata iniziale funzione RCD

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 5) ed eseguire la programmazione desiderata

    | Parametro | Descrizione                       | Valore                                                    |
    | :-------- | :-------------------------------- | :-------------------------------------------------------- |
    | TYPE      | Tipologia RCD                     | AC, A, B, Generale, Selettivo, Ritardato                  |
    | I  N     | Corrente di intervento nominale RCD | 10, 30, 100, 300, 500, 650, 1000mA                       |
    | MEAS      | Tipo misura (tempo e corrente di intervento) | t/ ½ I  N, t/I  N, t/2I  N, t/5I  N, I  o AUTO       |
    | POL       | Polarità corrente di prova        | Positiva (0°), Negativa (180°)                            |
    | T DEL     | Tempo di ritardo RCD (Ritardati)  | 0ms ÷ 700ms                                               |

    Tabella 5: Parametri impostabili per la funzione RCD

3.  Controllare il tipo di RCD selezionato (AC, A o B) e la caratteristica selezionata (Generale, Selettivo o Ritardato) e modificarle se necessario premendo il tasto virtuale **TYPE**. Se è selezionato un RCD Ritardato la videata passa automaticamente all’impostazione del tempo di ritardo
4.  Selezionare la corrente differenziale nominale premendo il tasto virtuale **I  N**
5.  Selezionare il tipo di misura desiderata premendo il tasto virtuale **MEAS** (t/½I  N, t/I  N, t/2I  N, t/5I  N, I  o AUTO)
6.  Controllare la polarità selezionata e modificarla se necessario premendo il tasto virtuale **POL**
7.  Selezionare la schermata di misura premendo il tasto virtuale (icona di schermata) (4) e controllare nuovamente tutte le impostazioni
8.  Collegare i terminali di misura o il cavo con spina Schuko come mostrato nelle seguenti Fig. 42 e Fig. 43

FULLTEST3 IT - 47

Fig. 42: Collegamento dello strumento con cavo di prova con spina Schuko

Fig. 43: Collegamento dello strumento con terminali di misura

9.  Il messaggio READY apparirà appena lo strumento è collegato correttamente all’impianto e la tensione di rete è presente
10. Premere il tasto **START/STOP** per attivare la misura. La seguente videata è mostrata a display
    Fig. 44: Videata dei risultati delle prove RCD

    **Significato simboli a display**

    | Riferimento | Descrizione                                                                                                 |
    | :---------- | :---------------------------------------------------------------------------------------------------------- |
    | 1           | Funzione selezionata                                                                                        |
    | 2           | Tensione di contatto limite selezionata (25V o 50V). È possibile selezionarla in MENU → SETUP → TENS. CONTATTO |
    | 3           | Sottorisultati - tensioni di rete U L/N e U L/PE a cui è stato eseguito il test                               |

FULLTEST3 IT - 48

| Riferimento | Descrizione                                                                                                                                                                                                                                 |
| :---------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 4           | Tasto virtuale della schermata di misura                                                                                                                                                                                                    |
| 5           | Tasto virtuale **TYPE** per selezionare il tipo di RCD (AC, A o B) e la caratteristica (GENERALE, SELETTIVO o RITARDATO). Il valore e la caratteristica attualmente selezionati sono visualizzati in basso sul pulsante                        |
| 6           | Tasto virtuale **I  N** per selezionare la corrente differenziale nominale dell'RCD (10, 30, 100, 300, 500, 650 o 1000mA). Il valore attualmente selezionato è visualizzato in basso sul pulsante                                             |
| 7           | Tasto virtuale **MEAS** per selezionare la misura (t /1/2I  N, t /I  N, t /2I  N, t /5I  N, I  o AUTO). La misura attualmente selezionata è visualizzato in basso sul pulsante                                                               |
| 8           | Tasto virtuale **POL** per selezionare la polarità della corrente di prova (POS - positiva o NEG – negativa)                                                                                                                              |
| 9           | Risultato del test (visualizzato in verde - risultato OK, in rosso - risultato NON OK)                                                                                                                                                      |
| 10          | Orologio in tempo reale (hh.mm.ss)                                                                                                                                                                                                          |
| 11          | Unità di misura del risultato (ms o mA)                                                                                                                                                                                                     |
| 12          | Stato del risultato della misura (simbolo (checkmark) visualizzato in verde - risultato OK, simbolo (cross) visualizzato in rosso - risultato NON OK)                                                                                        |

11. Il risultato del test del tempo di intervento è mostrato in verde, accompagnato dal simbolo (checkmark) e da un segnale acustico breve se compreso entro il campo di misura stabilito dalle normative di settore IEC/EN61008 e IEC/EN61009 (vedere Tabella 6). Se il risultato è superiore ai valori presenti in Tabella 6 è visualizzato in rosso, accompagnato dal simbolo (cross) e da un segnale acustico prolungato

    | Tipo RCD / I  N | I  N/2 [ms] | I  N [ms]       | 2I  N [ms]      | 5I  N [ms]      |
    | :--------------- | :----------- | :--------------- | :--------------- | :--------------- |
    | Generale         | >1000        |  300            |  150            |  40             |
    | Selettivo        | >1000        | Tmin = 130 Tmax = 500 | Tmin=60 Tmax=200 | Tmin=50 Tmax=150 |
    | Ritardato        | >1000        | D ÷ (D + 300)    | -                | -                |

    D = Tempo di ritardo impostabile da 0 ÷ 700ms
    Tabella 6: Valori limite tempo di intervento RCD

    | Tempo di intervento       | Corrente di intervento         |
    | :------------------------ | :----------------------------- |
    | Tipo AC, polarità positiva  | Tipo AC, polarità negativa   |
    | Tipo A, polarità positiva   | Tipo A, polarità negativa    |
    | Tipo B, polarità positiva   | Tipo B, polarità negativa    |

    Tabella 7: Forme d’onda correnti di prova RCD

12. Salvare i risultati delle misure premendo il tasto **SAVE** (vedere § 7.1)

FULLTEST3 IT - 49

ATTENZIONE

*   Quando si seleziona il tipo RCD (**TYPE**), la corrente nominale differenziale (**I  N**) o la misura (**MEAS**) può accadere che il parametro non sia disponibile (vedere § 11.1). In questo caso l’impostazione di un altro parametro o degli altri due parametri riduce la scelta del primo
*   Nel caso in cui entrambe le tensioni U L/N e U L/PE entro l'intervallo prescritto di 100V ÷ 265V siano presenti ai terminali di prova L/N/PE (visualizzati) ma non sia visualizzato alcun messaggio di stato PRONTO, controllare che la presa di alimentazione sia correttamente collegata a terra

### 6.5.1. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate              | Descrizione                                                                                                                                                                |
| :------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TENSIONE FUORI DAI LIMITI              | Tensione di ingresso U L/N o U L/PE al di fuori dell'intervallo prescritto 100 V ÷ 265V dopo avere premuto il tasto **START**.                                                |
| MISURA FALLITA!                        | Tensione in ingresso mancata durante la misurazione (disconnessione dei cavi, fusibile installato saltato, ecc.)                                                           |
| TENSIONE DI CONTATTO!                  | Tensione di contatto superiore al valore limite impostato (25V o 50V)                                                                                                        |
| IMPEDENZA ESTERNA TROPPO ELEVATA!    | Impedenza eccessiva nel conduttore L, impossibile generare la corrente preimpostata.                                                                                        |
| FUSIBILE F3!                           | Il Fusibile F3 è saltato.                                                                                                                                                  |
| SURRISCALDATO! Attendere il raffreddamento | La circuiteria interna è surriscaldata. Attendere il raffreddamento                                                                                                        |

FULLTEST3 IT - 50

## 6.6. IMPEDENZA ANELLO DI GUASTO (LOOP)

In accordo a quanto prescritto dalla norma IEC/EN60204-1 le condizioni di protezione contro gli shock elettrici negli impianti a scollegamento automatico della tensione di rete sono:

*   Misura o stima dell'impedenza dell'anello di guasto e verifica del dispositivo di protezione da sovracorrente inserito nella linea
*   Valori limite mostrati nella Tabella 10 della normativa IEC/EN60204-1

1.  Premere il tasto **FUNC** e selezionare la funzione **LOOP**. La seguente videata è mostrata a display
    Fig. 45: Videata iniziale funzione LOOP

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 8) ed eseguire la programmazione desiderata

    | Parametro | Descrizione                                 | Valore                                                                                                                                                                                                                                                                                           |
    | :-------- | :------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | MODE      | Modo di misura standard                     | LOOPL/N, LOOPL/L, LOOPL/PE                                                                                                                                                                                                                                                                       |
    |           | Modo di misura con IMP57                    | IMP57L/N, IMP57L/L, IMP57L/PE                                                                                                                                                                                                                                                                    |
    | LIMIT     | Tipologia misura per calcolo valore limite (vedere § 6.6.1) | STD, kA, I²t, TRIP CURR., Ut                                                                                                                                                                                                                                                         |
    | PROT      | Tipo di protezione                          | Protezione MCB: B, C, D, K, Protezione Fusibile: gG, aM, Corrente nominale protezione (vedere § 6.6.1), Ib = potere di interruzione max 1, 1.5, 3, 4.5, 6, 10, 15, 16, 20, 25kA, Tset = tempo intervento max 0.1s, 0.2s, 0.4s, 5s                                                                      |
    | WIRE      | Tipo di conduttore                          | Cu (Rame), Al (Alluminio)                                                                                                                                                                                                                                                                        |
    |           | Isolamento conduttore                       | PVC, Gomma butilica, EPR/XLPE                                                                                                                                                                                                                                                                    |
    |           | Sezione conduttore                          | 1, 1.5, 2.5, 4, 6, 10, 16, 25, 35, 50, 70, 95, 120, 150, 185, 240, 300, 400, 500, 630 mm²                                                                                                                                                                                                         |
    |           | Numero conduttori in parallelo              | 1 ÷ 99                                                                                                                                                                                                                                                                                           |

    Tabella 8: Parametri impostabili per la funzione LOOP

FULLTEST3 IT - 51

### 6.6.1. Impostazione valore limite sulla misura

Lo strumento consente di eseguire la misura dell’impedenza di Loop e il calcolo della corrispondente corrente di cortocircuito presunta (Isc). Sono possibili i seguenti 5 modi di selezione della corrente di cortocircuito limite presunta I SC LIM che definiscono la base della valutazione finale:

**Modo STD (Standard)**

Lo strumento non esegue alcuna verifica. In questo caso, non viene considerato alcun limite, il risultato del test non viene valutato ed è sempre considerato neutro (mostrato in bianco).

**Modo kA (verifica potere di interruzione della protezione)**

Lo strumento verifica che la corrente di cortocircuito sia inferiore al potere di interruzione della protezione BC (Breaking Capacity) espresso in kA cioè la capacità di rottura del dispositivo di protezione da sovracorrente inserito. Il valore I SC MAX misurato deve essere inferiore o uguale alla capacità di rottura Ib del dispositivo di protezione da sovracorrente inserito selezionabile tra i valori: 1, 1.5, 3, 4.5, 6, 10, 15, 16, 20, 25kA

**Modo I²t**

Lo strumento verifica che il dispositivo di protezione reagisca prima che i conduttori si surriscaldino e siano pertanto danneggiati. Sulla base dei valori I SC MAX misurati, del dispositivo di protezione inserito, della corrente nominale del dispositivo di protezione (In), lo strumento calcola il tempo di intervento del dispositivo di protezione (t) (vedere § 6.6.2). E’ possibile selezionare i parametri da inserire tra i seguenti valori

*   Tipo di protezione MCB (Magnetotermica): curva B, C, D, K
*   Corrente nominale protezione MCB: 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A (curva B), 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A (curva C), 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32A (curve D, K)
*   Tipo di protezione Fusibile: gG, aM
*   Corrente nominale protezione Fusibile gG: 2, 4, 6, 10, 13, 16, 20, 25, 32, 35, 40, 50, 63, 80, 100, 125, 160, 200, 224, 250, 315, 355, 400, 500, 630A
*   Corrente nominale protezione Fusibile aM: 6, 10, 16, 20, 25, 32, 35, 40, 50, 63, 80, 100, 160, 224, 250, 315, 355, 400, 500, 630A
*   Materiale conduttore: Cu (Rame), Al (Alluminio)
*   Rivestimento isolante del conduttore: PVC, Gomma Butilica, EPR/XLPE
*   Sezione conduttore: 1, 2.5, 4, 6, 10, 16, 25, 35, 50, 70, 95, 120, 150, 185, 240, 300, 400, 500, 630 mm²
*   Numero conduttori in parallelo: 1 ÷ 99

**Modo TRIP CURR (Corrente di intervento)**

Lo strumento verifica che il dispositivo di protezione intervenga entro il tempo stabilito alla corrente di cortocircuito misurata. Sulla base dei valori I SC MIN misurati, del dispositivo di protezione inserito e della corrente nominale del dispositivo di protezione (In) lo strumento calcola il tempo di intervento che deve essere inferiore o uguale al Tset inserito. È possibile selezionare i parametri da inserire tra i seguenti valori:

FULLTEST3 IT - 52

*   Tipo di protezione MCB (Magnetotermica): curva B, C, D, K
*   Corrente nominale protezione MCB: 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A (curva B), 0.5, 1, 1.6, 2, 4, 6, 10, 3, 16, 20, 25, 32, 40, 50, 63A (curva C), 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32A (curve D, K)
*   Tipo di protezione Fusibile: gG, aM
*   Corrente nominale protezione Fusibile gG: 2, 4, 6, 8, 10, 12, 16, 20, 25, 32, 40, 50, 63, 80, 100, 125, 160, 200, 250, 315, 400, 500, 630, 800, 1000, 1250A
*   Corrente nominale protezione Fusibile aM: 2, 4, 6, 8, 10, 12, 16, 20, 25, 32, 40, 50, 63, 80, 100, 125, 160, 200, 250, 315, 400, 500, 630A
*   Tset - Tempo di intervento massimo della protezione: 0.1s, 0.2s, 0.4s, 5s

**Modo Ut**

Lo strumento verifica che la corrente di cortocircuito sia tale che il dispositivo di protezione reagisca entro il tempo stabilito. Sulla base del dispositivo di protezione inserito, della corrente nominale del dispositivo di protezione (In) e del Tset lo strumento calcola la corrente di cortocircuito necessaria (Ia). Il valore I SC MIN misurato deve essere superiore o uguale alla corrente calcolata Ia. È possibile selezionare i parametri da inserire tra i seguenti valori:

*   Tipo di protezione MCB (Magnetotermica): curva B, C, D, K
*   Corrente nominale protezione MCB: 6, 10, 13, 16, 20, 25, 32, 40, 50, 63A (curva B), 0.5, 1, 1.6, 2, 4, 6, 10, 3, 16, 20, 25, 32, 40, 50, 63A (curva C), 0.5, 1, 1.6, 2, 4, 6, 10, 13, 16, 20, 25, 32A (curve D, K)
*   Tipo di protezione Fusibile: gG, aM
*   Corrente nominale protezione Fusibile gG: 2, 4, 6, 8, 10, 12, 16, 20, 25, 32, 40, 50, 63, 80, 100, 125, 160, 200, 250, 315, 400, 500, 630, 800, 1000, 1250A
*   Corrente nominale protezione Fusibile aM: 2, 4, 6, 8, 10, 12, 16, 20, 25, 32, 40, 50, 63, 80, 100, 125, 160, 200, 250, 315, 400, 500, 630A
*   Tset - Tempo di intervento massimo della protezione: 0.1s, 0.2s, 0.4s, 5s

FULLTEST3 IT - 53

### 6.6.2. Calcolo della corrente di cortocircuito presunta

| Modalità   | Sistema TT                                                                                                                                                                   | Condizione di valutazione                                                                                                                                                                                                                                                                                                                                                      | Sistema TN                                                                                                                                                                        | Condizione di valutazione                                                                                                                                                                                                                                                                                                                                        |
| :--------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| LIMITE     |                                                                                                                                                                              |                                                                                                                                                                                                                                                                                                                                                                                          |                                                                                                                                                                                             |                                                                                                                                                                                                                                                                                                                                                                |
| L/L        | STD                                                                                                                                                                          | Nessuna valutazione                                                                                                                                                                                                                                                                                                                                                            | Nessuna valutazione                                                                                                                                                                         | Nessuna valutazione                                                                                                                                                                                                                                                                                                                                            |
|            | kA                                                                                                                                                                           | ISC L/L MAX 3PH < BC                                                                                                                                                                                                                                                                                                                                                           | ISC L/L MAX 3PH < BC                                                                                                                                                                        | ISC L/L MAX 3PH < BC                                                                                                                                                                                                                                                                                                                                           |
|            | I²t                                                                                                                                                                          | (ISC L/L MAX 3PH)² × t < (K × N × S)²                                                                                                                                                                                                                                                                                                                                          | (ISC L/L MAX 3PH)² × t < (K × N × S)²                                                                                                                                                               | (ISC L/L MAX 3PH)² × t < (K × N × S)²                                                                                                                                                                                                                                                                                                                                          |
|            | TRIP CURR.                                                                                                                                                                   | ISC L/L MIN 2PH → Tmax, Tmax < Tlim                                                                                                                                                                                                                                                                                                                                            | ISC MIN 2PH → Tempo di intervento T, T < Tlim                                                                                                                                               | ISC MIN 2PH → Tempo di intervento T, T < Tlim                                                                                                                                                                                                                                                                                                                    |
|            | Ut                                                                                                                                                                           |                                                                                                                                                                                                                                                                                                                                                                                          |                                                                                                                                                                                             |                                                                                                                                                                                                                                                                                                                                                                |
| L/N        | STD                                                                                                                                                                          | Nessuna valutazione                                                                                                                                                                                                                                                                                                                                                            | Nessuna valutazione                                                                                                                                                                         | Nessuna valutazione                                                                                                                                                                                                                                                                                                                                            |
|            | kA                                                                                                                                                                           | ISC L/L MAX 3PH < BC                                                                                                                                                                                                                                                                                                                                                           | ISC L/L MAX 3PH < BC                                                                                                                                                                        | ISC L/L MAX 3PH < BC                                                                                                                                                                                                                                                                                                                                           |
|            | I²t                                                                                                                                                                          | (ISC L/N MAX)² × t < (K × N × S)²                                                                                                                                                                                                                                                                                                                                            | (ISC L/N MAX)² × t < (K × N × S)²                                                                                                                                                               | (ISC L/N MAX)² × t < (K × N × S)²                                                                                                                                                                                                                                                                                                                                          |
|            | TRIP CURR.                                                                                                                                                                   | ISC MIN 2PH → Tempo di intervento T, T < Tlim                                                                                                                                                                                                                                                                                                                                  | ISC MIN 2PH → Tempo di intervento T, T < Tlim                                                                                                                                               | ISC MIN 2PH → Tempo di intervento T, T < Tlim                                                                                                                                                                                                                                                                                                                    |
| Ut         |                                                                                                                                                                              |                                                                                                                                                                                                                                                                                                                                                                                          |                                                                                                                                                                                             |                                                                                                                                                                                                                                                                                                                                                                |
| L/N        | STD                                                                                                                                                                          | Nessuna valutazione                                                                                                                                                                                                                                                                                                                                                            | Nessuna valutazione                                                                                                                                                                         | Nessuna valutazione                                                                                                                                                                                                                                                                                                                                            |
|            | kA                                                                                                                                                                           | ISC MAX L/N < BC                                                                                                                                                                                                                                                                                                                                                             | ISC MAX L/N < BC                                                                                                                                                                            | ISC MAX L/N < BC                                                                                                                                                                                                                                                                                                                                               |
|            | I²t                                                                                                                                                                          | (ISC MAX L/N)² × T < (K × N × S)²                                                                                                                                                                                                                                                                                                                                            | (ISC MAX L/N)² × T < (K × N × S)²                                                                                                                                                               | (ISC MAX L/N)² × T < (K × N × S)²                                                                                                                                                                                                                                                                                                                                          |
|            | TRIP CURR.                                                                                                                                                                   | ISC MIN L/N → Tempo di intervento T, T < Tlim                                                                                                                                                                                                                                                                                                                                  | ISC MIN L/N → Tempo di intervento T, T < Tlim                                                                                                                                               | ISC MIN L/N → Tempo di intervento T, T < Tlim                                                                                                                                                                                                                                                                                                                    |
| L/PE       | STD                                                                                                                                                                          | Nessuna valutazione                                                                                                                                                                                                                                                                                                                                                            | Nessuna valutazione                                                                                                                                                                         | Nessuna valutazione                                                                                                                                                                                                                                                                                                                                            |
|            | kA                                                                                                                                                                           | ISC MAX L/PE < BC                                                                                                                                                                                                                                                                                                                                                            | ISC MAX L/PE < BC                                                                                                                                                                           | ISC MAX L/PE < BC                                                                                                                                                                                                                                                                                                                                              |
|            | I²t                                                                                                                                                                          | (ISC MAX L/PE)² × T < (K × N × S)²                                                                                                                                                                                                                                                                                                                                           | (ISC MAX L/PE)² × T < (K × N × S)²                                                                                                                                                              | (ISC MAX L/PE)² × T < (K × N × S)²                                                                                                                                                                                                                                                                                                                                         |
|            | TRIP CURR.                                                                                                                                                                   | ISC MIN L/PE → Tempo di intervento T, T < Tlim                                                                                                                                                                                                                                                                                                                                 | ISC MIN L/PE → Tempo di intervento T, T < Tlim                                                                                                                                              | ISC MIN L/PE → Tempo di intervento T, T < Tlim                                                                                                                                                                                                                                                                                                                   |
|            | Ut                                                                                                                                                                           | ISC MIN L/PE > N × In                                                                                                                                                                                                                                                                                                                                                        | ISC MIN L/PE > N × In                                                                                                                                                                       | ISC MIN L/PE > N × In                                                                                                                                                                                                                                                                                                                                          |

In cui:
BC = potere di interruzione della protezione
T = Tempo di intervento in funzione della caratteristica e della corrente nominale del dispositivo di protezione utilizzato
K = Vedere tabella sottostante

| Materiale/ Isolante       | PVC   | Gomma naturale / butilica | EPR/XLPE |
| :------------------------ | :---- | :------------------------ | :------- |
| Cu (Rame)                 | K = 115 | K = 135                   | K = 143  |
| Al (Alluminio)            | K = 76  | K = 87                    | K = 94   |

N = Numero di conduttori
S = Sezione di un conduttore

Per il calcolo della corrente di cortocircuito I SC è necessaria la tensione nominale Un dell'impianto di rete, pertanto è necessario selezionarla prima di eseguire le misure.
Selezione della tensione nominale Un: Premere i tasti virtuali **MENU** → **IMPOSTAZIONI** → **TENS. NOMINALE** (vedere § 5.5)

3.  Controllare la modalità di misura selezionata (LOOP L/N, LOOP L/L, LOOP L/PE, IMP57 L/N, IMP57 L/L o IMP57 L/PE) e modificarla, se necessario, premendo il tasto virtuale **MODE**

FULLTEST3 IT - 54

4.  In caso di misura con accessorio **IMP57** è necessario l’uso del cavo adattatore (accessorio opzionale **C2009AD**) per il collegamento alle porte USB2 o USB3 dello strumento. Per l’esecuzione della misura fare riferimento al manuale d’uso dell’accessorio IMP57
5.  Controllare la modalità limite selezionata (STD, kA, I²t, TRIP CUIRR. o Ut) e modificarla se necessario premendo il tasto virtuale **LIMIT**
6.  Controllare gli altri parametri (che dipendono dalla modalità limite selezionata) come tipo di protezione, corrente nominale, materiale del filo ecc. e modificarli se necessario premendo il tasto virtuale del parametro corrispondente (vedere § 6.6.1 e § 6.6.2)
7.  Selezionare la schermata di misura premendo il tasto virtuale (icona di schermata) (4) e controllare nuovamente tutte le impostazioni
8.  Collegare i terminali di misura o il cavo con spina Schuko come mostrato nelle seguenti
    Fig. 46: Collegamento con cavo con spina Schuko per misura LOOP L/N o LOOP L/PE

    Fig. 47: Collegamento dei terminali di prova per misura LOOP L/N

    Fig. 48: Collegamento dei terminali di prova per misura LOOP L/PE

FULLTEST3 IT - 55

Fig. 49: Collegamento dei terminali di prova per misura LOOP L/L

9.  Premere il tasto **START/STOP** per attivare la misura. La seguente videata è mostrata a display
    Fig. 50: Videata dei risultati delle prove LOOP

    **Significato simboli a display**

    | Riferimento | Descrizione                                                                                                                                                                                                                                                                                                                                           |
    | :---------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | 1           | Funzione selezionata                                                                                                                                                                                                                                                                                                                                  |
    | 2           | Tensione nominale selezionata necessaria per il calcolo della corrente di cortocircuito                                                                                                                                                                                                                                                             |
    | 3           | Messaggio READY (PRONTO). È visualizzato quando è presente tensione di rete U L/L, U L/N o U L/PE entro l'intervallo prescritto                                                                                                                                                                                                                         |
    | 4           | Sottorisultati - tensione di rete U L/PE o U L/PE o U L/L a cui la misura è stata effettuata e a cui è stata calcolata la corrente di cortocircuito presunta ISC                                                                                                                                                                                      |
    | 5           | Tasto virtuale della schermata di misura                                                                                                                                                                                                                                                                                                              |
    | 6           | Tasto virtuale **MODE** per selezionare la modalità di misura LOOP L/N, LOOP L/L, LOOP L/PE, IMP57 L/N, IMP57 L/L o IMP57 L/PE. La modalità attualmente selezionata è visualizzata in basso sul pulsante                                                                                                                                            |
    | 7           | Tasto virtuale **LIMIT** per selezionare la modalità limite (STD, kA, I²t, TRIP CURR. o Ut). La modalità attualmente selezionata è visualizzata in basso sul pulsante.                                                                                                                                                                              |
    | 8           | Tasto virtuale **PROT.** per selezionare il tipo di protezione (MCB B, MCB C, MCB D, MCB K, FUSIBILE gG o FUSIBILE aM) e la corrente nominale della protezione selezionata. Il tipo attualmente selezionato è visualizzato in basso sul pulsante                                                                                                     |

FULLTEST3 IT - 56

| Riferimento | Descrizione                                                                                                                                                                                                                                                                                         |
| :---------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 9           | Tasto virtuale **WIRE** per selezionare il materiale del filo selezionato (Cu o Al), il rivestimento (PVC, GOMMA BUTILICA o EPR/XLPE), la sezione (1, 1.5, 2.5, 4, 6, 10, 16, 25, 35, 50, 70, 95, 120, 150, 185, 240, 300, 400, 500 o 630 mm²) e il numero di conduttori (1 ÷ 99). Il materiale attualmente selezionato è visualizzato in basso sul pulsante |
| 10          | Risultato della misura (in verde - risultato OK, in rosso - risultato NON OK)                                                                                                                                                                                                                       |
| 11          | Orologio in tempo reale (hh.mm.ss)                                                                                                                                                                                                                                                                  |
| 12          | Unità di misura del risultato ()                                                                                                                                                                                                                                                                   |
| 13          | Stato del risultato della misura (simbolo (checkmark) visualizzato in verde - risultato OK, simbolo (cross) visualizzato in rosso - risultato NON OK)                                                                                                                                               |

10. Il messaggio PRONTO appare quando è presente una tensione di rete U L/N (LOOP L/N) o U L/PE (LOOP L/PE) nell'intervallo 100 ÷ 265 V o U L/L (LOOP L/L) nell'intervallo 100 ÷ 460 V. Eseguire la misura premendo il tasto **START/STOP**
11. Il risultato del test è visualizzato in verde, accompagnato dal simbolo (checkmark) e da un segnale acustico breve se il valore I SC misurato/calcolato corrisponde alla modalità limite e agli altri parametri inseriti. Nel caso in cui l'I SC misurato/calcolato non corrisponda ala modalità limite e agli altri parametri inseriti, il risultato sarà visualizzato in rosso, accompagnato dal simbolo (cross) e da un segnale acustico prolungato
12. Salvare i risultati delle misure premendo il tasto **SAVE** (vedere § 7.1)

ATTENZIONE

*   Nel caso in cui la tensione U L/N (misura LOOP L/N) o la tensione U L/PE (misura LOOP L/PE) sia entro l'intervallo 100V ÷ 265V, siano presenti ai terminali di prova L/N/PE (visualizzati) ma non sia visualizzato alcun messaggio di stato PRONTO, controllare se la presa di alimentazione sia correttamente collegata a terra
*   Nel caso in cui la tensione UL/L (misura LOOP L/L) sia entro l'intervallo prescritto di 100V ÷ 460V, siano presenti ai terminali di prova L/N (visualizzati) ma non sia visualizzato alcun messaggio di stato PRONTO, controllare se la presa di alimentazione sia correttamente collegata a terra
*   Nel caso in cui sia selezionata la modalità limite STD (il risultato non è valutato), il risultato sarà mostrato in bianco

FULLTEST3 IT - 57

### 6.6.3. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate         | Descrizione                                                                                                                                                                                        |
| :-------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TENSIONE FUORI DAI LIMITI         | Tensione di ingresso U L/N o U L/PE al di fuori dell'intervallo prescritto 100 V ÷ 265 V (misura L/N o L/PE) o al di fuori dell'intervallo prescritto 100V ÷ 460V (misura L/L) dopo avere premuto il tasto START/STOP |
| FUSIBILE F3!                      | Il Fusibile F3 è saltato.                                                                                                                                                                          |
| SURRISCALDATO! Attendere il raffreddamento! | La circuiteria interna è surriscaldata. Attendere il raffreddamento!                                                                                                                    |
| MISURA FALLITA!                   | Tensione in ingresso mancata durante la misurazione (disconnessione dei cavi, fusibile installato saltato, ecc.)                                                                                 |

FULLTEST3 IT - 58

## 6.7. RESISTENZA GLOBALE DI TERRA/TENSIONE DI CONTATTO (R A)

Lo strumento consente di eseguire la misura della resistenza globale di terra (misura tipicamente usata nei sistemi elettrici di tipo TT – impianti civili in alternativa alla misura di terra con il metodo voltamperometrico) applicando una corrente di prova pari a I  N/2 in cui I  N = corrente nominale di intervento del differenziale (RCD) e quindi, in assenza di dispersioni verso terra, senza causare l’intervento dell’RCD.

1.  Premere il tasto **FUNC** e selezionare la funzione **RA**. La seguente videata è mostrata a display
    Fig. 51: Videata iniziale funzione RA

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 9) ed eseguire la programmazione desiderata

    | Parametro | Descrizione                       | Valore                                 |
    | :-------- | :-------------------------------- | :------------------------------------- |
    | I  N     | Corrente di intervento nominale RCD | 10, 30, 100, 300, 500, 650, 1000mA     |

    Tabella 9: Parametri impostabili per la funzione RA

### 6.7.1. Impostazione valore limite sulla misura

In accordo alla normativa CEI 64/8 la resistenza globale di terra RA deve essere inferiore o uguale al rapporto U CLIM /I  N in cui la tensione di contatto limite UC LIM può essere impostata a 25V o 50V. Esempio: U CLIM selezionata = 50V, I  N = 30mA → RA LIM = 1667 .
Selezione della tensione di contatto limite U CLIM (vedere § 5.5). Premere i tasti virtuali **MENU** → **SETUP** → **TENS. NOMINALE** e selezionare 25V o 50V

3.  Controllare la corrente differenziale nominale selezionata e modificarla se necessario premendo il tasto virtuale **I  N**
4.  Selezionare la schermata di misura premendo il tasto virtuale (icona di schermata) e controllare nuovamente tutte le impostazioni
5.  Collegare i terminali di misura o il cavo con spina Schuko come mostrato nelle seguenti

FULLTEST3 IT - 59

Fig. 52: Collegamento dello strumento con cavo di prova con spina Schuko

Fig. 53: Collegamento dello strumento con terminali di misura

6.  Premere il tasto **START/STOP** per attivare la misura. La seguente videata è mostrata a display
    Fig. 54: Videata dei risultati delle prove RCD

    **Significato simboli a display**

    | Riferimento | Descrizione                                                                                                                    |
    | :---------- | :----------------------------------------------------------------------------------------------------------------------------- |
    | 1           | Funzione selezionata                                                                                                           |
    | 2           | Tensione di contatto limite selezionata (25 o 50 V)                                                                            |
    | 3           | Messaggio READY (PRONTO). Visualizzato quando è presente una tensione di rete U L/PE compresa tra 100V ÷265V                      |
    | 4           | Sottorisultati, tensione di rete U L/PE a cui è stata effettuata la misura e tensione di contatto U C alla corrente differenziale nominale |
    | 5           | Tasto virtuale della schermata di misura                                                                                       |

FULLTEST3 IT - 60

| Riferimento | Descrizione                                                                                                                                                                                                                           |
| :---------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 6           | Tasto virtuale **I  N** per selezionare la corrente differenziale nominale. Il valore attualmente selezionato è visualizzato in basso sul pulsante                                                                                      |
| 7           | Risultato della misura (in verde - risultato OK, in rosso - risultato NON OK).                                                                                                                                                        |
| 8           | Orologio in tempo reale (hh.mm.ss)                                                                                                                                                                                                    |
| 9           | Unità di misura del risultato ()                                                                                                                                                                                                     |
| 10          | Stato del risultato della misura (simbolo (checkmark) visualizzato in verde - risultato OK, simbolo (cross) visualizzato in rosso - risultato NON OK)                                                                                    |

7.  Al termine del tempo previsto per la misura, il risultato del test è visualizzato in verde, accompagnato dal simbolo (checkmark) e da un segnale acustico breve se inferiore o uguale al valore limite (vedere § [missing section reference]). Se il risultato è superiore al valore limite è visualizzato in rosso e accompagnato dal simbolo (cross) e da un segnale acustico prolungato
8.  Salvare i risultati delle misure premendo il tasto **SAVE** (vedere § 7.1)

ATTENZIONE

Nel caso in cui la tensione U L/PE sia entro l'intervallo 100V ÷ 265V, siano presenti ai terminali di prova L/N/PE (visualizzati) ma non sia visualizzato alcun messaggio di stato PRONTO, controllare se la presa di alimentazione sia correttamente collegata a terra

### 6.7.2. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate                  | Descrizione                                                                                                                                                                                                            |
| :----------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TENSIONE FUORI DAI LIMITI                  | Tensione di ingresso U L/PE al di fuori dell'intervallo prescritto 100 V ÷ 265V dopo avere premuto il tasto **START/STOP**                                                                                                |
| TENSIONE DI CONTATTO > 50 V oppure TENSIONE DI CONTATTO > 25 V | Tensione di contatto superiore al valore limite selezionato, probabilmente a causa di una resistenza dell'anello di guasto troppo elevata.                                                                  |
| MISURA FALLITA                             | La corrente di misura è stata interrotta a causa dello scollegamento dei terminali di misura o per via dell'aumento della resistenza dell'anello di guasto.                                                               |
| FUSIBILE F3!                               | Il Fusibile F3 è saltato.                                                                                                                                                                                              |
| SURRISCALDATO! Attendere il raffreddamento! | La circuiteria interna è surriscaldata. Attendere il raffreddamento!                                                                                                                                                   |

FULLTEST3 IT - 61

## 6.8. MISURA TENSIONE RESIDUA (URES)

Per tensione residua si intende la tensione che resta presente sulle parti accessibili di una macchina dopo lo spegnimento della stessa. Questo fenomeno può essere provocato ad esempio da capacità integrate o da generatori interni e deve essere contenuto entro opportuni valori per ragioni di sicurezza dell’operatore. In accordo alle prescrizioni della normativa IEC/EN60204-1, le parti sotto tensione accessibili collegate a tensioni pericolose devono scaricarsi entro 5s (macchine alimentate in modo permanente) o entro 1s (macchine collegate con spine, morsettiere, azionamenti, ecc..) fino a 60V. Ciò deve essere verificato mediante opportuni test di valutazione del tempo di scarica. In caso di non conformità, occorre prendere misure aggiuntive (dispositivi di scarica, informazioni di avvertimento, coperture, ecc..). La tensione residua deve essere misurata 1s o 5s dopo lo spegnimento della macchina testata. Lo strumento può eseguire la misura URES nei seguenti modi:

*   Modo **Lineare** su macchine alimentate a spina (**Plug**)
*   Modo **Lineare** su macchine collegate in modo permanente (**Interno**)
*   Modo **Non Lineare** su macchine alimentate a spina (**Plug**)
*   Modo **Non Lineare** su macchine collegate in modo permanente (**Interno**)

### 6.8.1. Modo Lineare

In modo **Lineare** si considera che i componenti interni della macchina siano di tipo esclusivamente “lineare” (resistenze, induttanze, capacità, ecc..) pertanto la caratteristica di scarica della tensione di alimentazione è tipicamente esponenziale inversa. In questo modo il risultato visualizzato è riferito al valore di picco della tensione di alimentazione in modo da valutare la situazione più critica (vedere Fig. 55)
Fig. 55: Scarica tensione di alimentazione in modo Lineare

Per il calcolo della tensione URES misurata è necessario conoscere il valore nominale della tensione di alimentazione Un Fase-Neutro o Fase-Terra pertanto è necessario selezionarla sullo strumento prima di eseguire le misure (vedere § 5.5). Lo strumento rileva automaticamente le seguenti tensioni di sistema standard (ex 230V/240V):

*   Tensione nominale selezionata Un = 230V
    230V → U IN = 230V ± 10%
    400V → U IN = 400V ± 10%
*   Tensione nominale selezionata Un = 240V
    240V → U IN = 240V ± 10%
    415V → U IN = 415V ± 10%

Per includere la sovratensione standard di rete, la tensione residua misurata è riferita al valore di picco della sovratensione di rete massima possibile, ovvero (considerando il caso peggiore +10%):

*   Tensione nominale selezionata Un = 230V

FULLTEST3 IT - 62

    Up = 230V × 1.1 × 2 = 358V → è rilevata una tensione di sistema di 230V
    Up = 400V × 1.1 × 2 = 620V → è rilevata una tensione di sistema di 400V

*   Tensione nominale selezionata Un = 240V
    Up = 240 V × 1.1 × 2 = 372V → è rilevata una tensione di sistema di 240V
    Up = 415 V × 1.1 × 2 = 644V → è rilevata una tensione di sistema di 415V

Se la tensione di rete reale devia dalla tensione nominale di sistema di più del ± 10% lo strumento riferisce il risultato al valore di picco della tensione di ingresso reale.
Esempio 1 (Un = 230V):
U IN = 173V (il valore devia di più del 10% da 230V), il risultato è riferito a 173V × 2 = 244V
Esempio 2 (Un = 230V):
U IN = 209V (il valore devia di meno del 10% da 230V), il risultato è riferito a 230V × 1.1 × 2 = 358V

### 6.8.2. Modo Non Lineare

In modo **Non Lineare**, si parte dal presupposto che siano coinvolti nel processo di scarica anche componenti "non lineari" (relè, lampade a gas, ecc.) e, pertanto, la caratteristica di scarica è non esponenziale o non è prevedibile (vedere Fig. 56)
Fig. 56: Scarica tensione di alimentazione in modo Non Lineare

In questo caso il risultato non può essere riferito al valore di picco, pertanto occorre assicurarsi che lo spegnimento avvenga alla tensione di ingresso massima, ovvero al valore di picco, altrimenti il risultato della misura non è rilevante. Il valore misurato è quindi registrato e valutato.

### 6.8.3. Condizioni di Trigger

Lo strumento rileva lo scollegamento della tensione di rete dall'ingresso TRIG (misura INT) o dall'ingresso U RES (misura PLUG) quando si verifica una delle due condizioni seguenti condizioni di trigger:

*   Il valore medio della tensione di ingresso (misurato su ciascun periodo) rettificato scende con una pendenza di almeno 25V/s. Il trigger viene attivato e la misura ha inizio (ciò si verifica ad esempio se la tensione di ingresso AC o DC inizia a diminuire)
*   Il valore temporaneo del semiperiodo della tensione è confrontato con il valore temporaneo del semiperiodo precedente (stessa polarità). Se la differenza è superiore al 10%, il trigger viene attivato e la misura ha inizio (ciò si verifica ad esempio se la tensione AC è modificata in DC
*   Le due condizioni descritte sopra sono attive su ingresso URES in modo **Plug** e su ingresso TRIG in modo **INT**

FULLTEST3 IT - 63

1.  Premere il tasto **FUNC** e selezionare la funzione **URES**. La seguente videata è mostrata a display
    Fig. 57: Videata iniziale funzione URES

2.  Selezionare i parametri di prova sullo strumento (vedere Tabella 10) ed eseguire la programmazione desiderata

    | Parametro | Descrizione                       | Valore                                       |
    | :-------- | :-------------------------------- | :------------------------------------------- |
    | MODE      | Modi di misura                    | LIN (Lineare), NONLIN (Non Lineare)          |
    | CON       | Tipo di collegamento              | INT (misura su componenti interni), PLUG (misura su spina 1Phase/3Phase) |
    | LIMIT t   | Tempo limite                      | 1s, 5s                                       |

    Tabella 10: Parametri impostabili per la funzione URES

3.  Controllare la modalità selezionata e modificarla se necessario premendo il tasto virtuale **MODE**
4.  Controllare il collegamento selezionato e modificarlo se necessario premendo il tasto virtuale **CON**
5.  Controllare il tempo limite selezionato e modificarlo se necessario premendo il tasto virtuale **LIMIT t**
6.  Selezionare la schermata di misura premendo il tasto virtuale (icona di schermata) e controllare nuovamente tutte le impostazioni
7.  Collegare i terminali di misura come illustrato in una delle figure sottostanti
    Fig. 58: Collegamento per misura URES INT su macchine collegate 1P/3P

FULLTEST3 IT - 64

Fig. 59: Collegamento per misura URES INT su macchine collegate in modo fisso t 1s RES <

Fig. 60: Collegamento dei terminali di misura nella misura URES PLUG

8.  Il messaggio PRONTO, SCOLLEGARE UUT appare quando è presente tensione U TRIG entro l'intervallo 100V ÷ 460VAC. Eseguire la misura scollegando l' UUT. La seguente videata è mostrata a display
    Fig. 61: Videata dei risultati della misura URES

    **Significato simboli a display**

    | Riferimento | Descrizione                                                                                                      |
    | :---------- | :--------------------------------------------------------------------------------------------------------------- |
    | 1           | Funzione selezionata                                                                                             |
    | 2           | Tensione in ingresso UIN e tensione di trigger UTRIG                                                             |
    | 3           | Tasto virtuale della schermata di misura                                                                         |
    | 4           | Tasto virtuale **MODE** per selezionare la modalità di misura (LINEARE o NON LINEARE).                          |

FULLTEST3 IT - 65

| Riferimento | Descrizione                                                                                                                                                                                                                                                        |
| :---------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 5           | Tasto virtuale **CON** (connessione) per selezionare il collegamento per la misura (INT o PLUG). Il collegamento attualmente selezionato è visualizzato in basso sul pulsante                                                                                        |
| 6           | Tasto virtuale **LIMIT t** per selezionare il tempo limite (1 s o 5 s), valido esclusivamente per misure interne. Il valore limite attualmente selezionato è visualizzato in basso sul pulsante                                                                     |
| 7           | Risultato della misura (in verde - risultato OK, in rosso - risultato NON OK).                                                                                                                                                                                     |
| 8           | Orologio in tempo reale (hh.mm.ss)                                                                                                                                                                                                                                 |
| 9           | Unità di misura del risultato                                                                                                                                                                                                                                      |
| 10          | Risultato del test visualizzato in verde, accompagnato dal simbolo (checkmark) verde e da un segnale acustico breve se inferiore o uguale a 60 VRMS (AC o DC, vedi unità). Se il risultato è superiore a 60 VRMS, sarà visualizzato in rosso e accompagnato dal simbolo (cross) rosso e da un segnale acustico prolungato ) |

9.  Salvare i risultati delle misure premendo il tasto **SAVE** (vedere § 7.1)

ATTENZIONE

Non usare il tasto **START/STOP** in questa misurazione in quanto non ha alcuna funzione

### 6.8.4. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Informazioni visualizzate                     | Descrizione                                                                                                                                                                                                                                                |
| :-------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TRIGGER DI TENSIONE BASSO RIPETERE            | La tensione di rete è stata scollegata ad una tensione temporanea troppo bassa (< 20% del valore di picco). Il messaggio potrebbe apparire solo in modalità LINEARE. Ripetere la misura (collegare e scollegare nuovamente l' UUT)                             |
| TENSIONE ALLO SPEGNIMENTO BASSA RIPETERE | La tensione di rete non è stata scollegata abbastanza vicino al valore di picco (fino a ± 5%), quindi il risultato sarebbe comunque irrilevante. Il messaggio potrebbe apparire solo in modalità NON LINEARE. Ripetere la misura (collegare e scollegare nuovamente l' UUT) |

<!-- Chunk: Pages 67-98 -->
## 6.9. TEST FUNZIONALI (POWER)

Lo strumento consente di eseguire test funzionali di routine su apparecchiature direttamente collegate alla presa di prova schuko presente sul pannello frontale (vedere **Fig. 2 – parte 25**). In tal caso lo strumento alimenta l’UUT e ne misura i parametri: tensione, corrente, potenza attiva, potenza apparente, fattore di potenza (PF) e corrente di dispersione sulla spina.

1. Premere il tasto **FUNC** e selezionare la funzione **POWER**. La seguente videata è mostrata a display **Fig. 62**: Videata iniziale funzione POWER
2. Selezionare i parametri di prova sullo strumento (vedere **Tabella 11**) ed eseguire la programmazione desiderata

**Tabella 11**: Parametri impostabili per la funzione POWER

| Parametro | Descrizione                                      | Valore                                    |
| :-------- | :----------------------------------------------- | :---------------------------------------- |
| TIMER     | Tempo di misura                                  | 5s ÷ 60min, risoluzione 1 s               |
| LIMIT     | Valore limite potenza apparente dell’UUT         | 6VA ÷ 5.06kVA                             |
| L POS     | Posizione terminale di Fase sulla presa schuko | LEFT (Sinistra) / RIGHT (Destra)          |

3. Controllare il tempo di misura e modificarlo se necessario premendo il tasto virtuale **TIMER**. Sono disponibili quattro tempi di misura preimpostati indipendenti per velocizzare le operazioni. Selezionare il valore più vicino a quello desiderato e modificarlo utilizzando i tasti virtuali **+** e **―**, se necessario
4. Controllare il valore limite della la potenza apparente modificarla se necessario premendo il tasto virtuale **LIMIT**. Sono disponibili quattro valori limite preimpostati indipendenti per velocizzare le operazioni. Selezionare il valore più vicino a quello desiderato e modificarlo utilizzando i tasti virtuali **+** e **―**, se necessario
5. Controllare la posizione selezionata del terminale di fase sulla presa schuko premendo il tasto virtuale **L POS**. Se è selezionata la posizione LEFT (Sinistra) il potenziale di fase è collegato al terminale di sinistra della presa schuko altrimenti RIGHT (Destra) il potenziale di fase è collegato al terminale di destra
6. Selezionare la schermata di misura premendo il tasto virtuale e controllare nuovamente tutte le impostazioni
7. Collegare l'UUT alla presa schuko come mostrato nella seguente **Fig. 63**

FULLTEST3 IT - 67

**Fig. 63**: Collegamento dell'UUT alla presa di prova schuko

8. Avviare la misura premendo il tasto **START/STOP** e terminarla premendo nuovamente il tasto **START/STOP** oppure allo scadere del tempo di misura impostato
9. Il risultato del test (potenza apparente) è mostrato **in verde** se inferiore o uguale al valore limite impostato oppure **in rosso** se superiore al valore limite impostato. Il risultato finale sarà accompagnato dal simbolo **verde** e da un segnale acustico breve (risultato OK) o dal simbolo **rosso** e da un segnale acustico prolungato (risultato non OK). La **Fig. 64** mostra un esempio di schermata con i risultati delle misure

**Fig. 64**: Schermata dei risultati delle prove di POWER

Significato simboli a display

| Riferimento | Descrizione                                                                                                                          |
| :---------- | :----------------------------------------------------------------------------------------------------------------------------------- |
| 1           | Funzione selezionata                                                                                                                 |
| 2           | Barra di avanzamento indicante il tempo di misura                                                                                    |
| 3           | Sotto - risultati di misura: tensione di rete U L/N, corrente di carico I L, potenza reale P, Fattore di potenza PF e corrente di dispersione I PE |
| 4           | Tasto virtuale della schermata di misura                                                                                             |
| 5           | Tasto virtuale **TIMER** per regolare il tempo della misura. Il tempo di misura attualmente selezionato è mostrato sopra la barra di avanzamento |
| 6           | Tasto virtuale **LIMITE** per selezionare la potenza apparente limite. Il valore attualmente selezionato è visualizzato in basso sul pulsante |

FULLTEST3 IT - 68

| Riferimento | Descrizione                                                                                                 |
| :---------- | :---------------------------------------------------------------------------------------------------------- |
| 7           | Tasto virtuale **L POS** per selezionare la posizione del terminale di fase sulla presa schuko durante la misura. La posizione attualmente selezionata è visualizzata in basso sul pulsante |
| 8           | Risultato della misura (**in verde** - risultato OK, **in rosso** - risultato NON OK)                         |
| 9           | Orologio in tempo reale (hh.mm.ss)                                                                          |
| 10          | Unità di misura del risultato                                                                               |
| 11          | Tempo di misura impostato                                                                                   |
| 12          | Stato del risultato della misura (simbolo visualizzato **in verde** - risultato OK, simbolo visualizzato **in rosso** - risultato NON OK) |

10. Salvare i risultati delle misure premendo il tasto **SAVE** (vedere **§ 7.1**)

> **ATTENZIONE**
> * Quando si misura la corrente di dispersione IPE occorre eseguire la misura in entrambe le posizioni di fase (fase al terminale sinistro e al terminale destro) e deve essere tenuto in considerazione il valore più alto
> * Accendere l'UUT per poter misurare la piena potenza dell'unità e la corrente di dispersione totale
> * In caso di sovraccarico della presa di prova, il fusibile F1 o F2 (entrambi T16A/250V) potrebbero intervenire
> * Non usare la presa di prova schuko per scopi diversi dalla misura

### 6.9.1. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Messaggio                        | Descrizione                                                                                                                                                              |
| :------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **I PE > 3.5mA**                 | La corrente di dispersione I PE è superiore a 3.5 mA, e ciò può essere pericoloso per l'operatore. Il messaggio apparirà sempre quando la corrente supera la soglia dei 3.5mA e sparirà automaticamente dopo 10s. Il messaggio è accompagnato da un segnale acustico |
| **CORRENTE I PE FUORI RANGE!** | Se la corrente I PE è superiore a 10A per 10s, la misura sarà arrestata e apparirà questo messaggio                                                                     |
| **CORRENTE I L FUORI RANGE!**  | Se la corrente I L è superiore a 16A per 10s, la misura sarà arrestata e apparirà questo messaggio                                                                     |

FULLTEST3 IT - 69

## 6.10. SENSO CICLICO DELLE FAS I (PHASESEQ)

Lo strumento consente di eseguire il test del senso ciclico delle fasi in un sistema trifase con il tradizionale metodo a 3 fili.

1. Premere il tasto **FUNC** e selezionare la funzione **PHASESEQ**. La seguente videata è mostrata a display **Fig. 65**: Videata iniziale funzione PHASESEQ
2. Collegare i cavi di misura alla presa/al cablaggio in prova come mostrato nella **Fig. 66**

**Fig. 66**: Collegamento cavi di misura nella funzione PHASESEQ

3. Eseguire la misura premendo il tasto **START/STOP**. La misura è eseguita e il risultato del test è mostrato **in verde** e da un segnale acustico breve se conforme alla direzione di riferimento (**indicazione 1.2.3.**). Se il risultato non è conforme alla direzione di riferimento (**indicazione 2.1.3.**) è visualizzato **in rosso** e da un segnale acustico prolungato. La seguente **Fig. 67** mostra un esempio di schermata con i risultati della misura

**Fig. 67**: Videata di misura della funzione PHASESEQ

FULLTEST3 IT - 70

Significato simboli a display

| Riferimento | Descrizione                                                                       |
| :---------- | :-------------------------------------------------------------------------------- |
| 1           | Funzione selezionata                                                              |
| 2           | Sotto - risultati di misura: tensione Fase - Fase U L1/2, tensione Fase - Fase U L2/3, Tensione Fase - Fase U L3/1 |
| 3           | Tasto virtuale della schermata di misura                                          |
| 4           | Risultato della misura (**in verde** - risultato OK, **in rosso** - risultato NON OK) |
| 5           | Orologio in tempo reale (hh.mm.ss).                                               |

4. Salvare i risultati delle misure premendo il tasto **SAVE** (vedere **§ 7.1**)

### 6.10.1. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Messaggio                   | Descrizione                                                                        |
| :-------------------------- | :--------------------------------------------------------------------------------- |
| **TENSIONE FUORI DAI LIMITI** | Una o più tensioni fase - fase sono fuori dal campo di misura: **360 V ÷ 460V**    |
| **1.1.X**                   | Almeno una delle fasi misurate è stata scollegata durante la misurazione. Collegare le tre fasi e ripetere la misurazione. |

FULLTEST3 IT - 71

## 6.11. MISURA DI CORRENTE CON USO DI TRASDUTTORE A PINZA (ICLAMP)

Lo strumento permette di eseguire la misura della corrente AC con uso di trasduttore a pinza (accessorio opzionale **HT96U**) collegato all’ingresso **ILEAK** (vedere **Fig. 2 – parte 26**).

1. Premere il tasto **FUNC** e selezionare la funzione **ICLAMP**. La seguente videata è mostrata a display **Fig. 68**: Videata iniziale funzione ICLAMP
2. Selezionare i parametri di prova sullo strumento (vedere **Tabella 12**) ed eseguire la programmazione desiderata

**Tabella 12**: Parametri impostabili per la funzione ICLAMP

| Parametro | Descrizione          | Valore                                                 |
| :-------- | :------------------- | :----------------------------------------------------- |
| RANGE     | Campo di misura      | 1000mA,100A,1000A                                      |
| LIMIT     | Valore limite di misura | 0.1mA ÷ 1000mA (1000mA)<br>0.1A ÷ 100.0A (100A)<br>1.0A ÷ 1000A (1000A) |

3. Impostare il campo di misura e modificarlo se necessario premendo il tasto virtuale **RANGE**
4. Controllare la corrente limite selezionata e modificarla se necessario premendo il tasto virtuale **LIMIT**. Sono disponibili quattro valori limite preimpostati indipendenti per velocizzare le operazioni. Selezionare il valore più vicino a quello desiderato e modificarlo utilizzando i tasti virtuali **+** e **―**, se necessario
5. Selezionare la schermata di misura premendo il tasto virtuale e controllare nuovamente tutte le impostazioni
6. Collegare la pinza di corrente al circuito in prova come mostrato nella **Fig. 69**

**Fig. 69**: Collegamento della pinza di corrente nella misura ICLAMP

FULLTEST3 IT - 72

7. Avviare la misura premendo il tasto **START/STOP**. La misura è avviata e arrestata da una nuova pressione del tasto **START/STOP**. Il risultato del test è visualizzato **in verde** se inferiore o uguale o **in rosso** se superiore al valore limite impostato. Il risultato finale sarà accompagnato dal simbolo **verde** e da un segnale acustico breve (risultato OK) o dal simbolo **rosso** e da un segnale acustico prolungato (risultato non OK). La seguente **Fig. 70** mostra un esempio di schermata con i risultati delle misure.

**Fig. 70**: Videata di misura della funzione ICLAMP

Significato simboli a display

| Riferimento | Descrizione                                                                                                 |
| :---------- | :---------------------------------------------------------------------------------------------------------- |
| 1           | Funzione selezionata                                                                                        |
| 2           | Tasto virtuale della schermata di misura                                                                    |
| 3           | Tasto virtuale **RANGE** per selezionare il campo di misura                                                  |
| 4           | Tasto virtuale **LIMIT** per selezionare il valore limite della corrente all'interno di ciascun campo di misura |
| 5           | Risultato della misura (**in verde** - risultato OK, **in rosso** - risultato NON OK)                         |
| 6           | Orologio in tempo reale (hh.mm.ss).                                                                         |
| 7           | Unità di misura del risultato                                                                               |
| 8           | Stato del risultato della misura (simbolo visualizzato **in verde** - risultato OK, simbolo visualizzato **in rosso** - risultato NON OK) |

8. Salvare i risultati delle misure premendo il tasto **SAVE** (vedere **§ 7.1**)

> **ATTENZIONE**
> * La tensione massima in ingresso è di 10V, un cavo è collegato a terra
> * Il tempo di misura è limitato a 60min

### 6.11.1. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Messaggio                         | Descrizione                                                                          |
| :-------------------------------- | :----------------------------------------------------------------------------------- |
| **CORRENTE DI CARICO OLTRE I LIMITI** | Se la corrente IL è superiore a 16A per 10s, la misura è arrestata e apparirà questo messaggio. |

FULLTEST3 IT - 73

## 6.12. MISURA DI CORRENTE DI DISPERSIONE (ILEAK)

Lo strumento permette di eseguire la misura della corrente di dispersione AC sia con uso di trasduttore a pinza (accessorio opzionale **HT96U**) collegato all’ingresso **ILEAK** (vedere **Fig. 2 – parte 26**) sia su apparecchiature direttamente collegate alla presa di prova schuko presente sul pannello frontale (vedere **Fig. 2 – parte 25**). In tal caso lo strumento alimenta l’UUT e ne misura la corrente di dispersione sulla spina.

1. Premere il tasto **FUNC** e selezionare la funzione **ILEAK**. La seguente videata è mostrata a display **Fig. 71**: Videata iniziale funzione ILEAK
2. Selezionare i parametri di prova sullo strumento (vedere **Tabella 13**) ed eseguire la programmazione desiderata

**Tabella 13**: Parametri impostabili per la funzione ILEAK

| Parametro | Descrizione                                      | Valore                                                                         |
| :-------- | :----------------------------------------------- | :----------------------------------------------------------------------------- |
| MODE      | Modo di misura                                   | Pinza (Clamp) o Presa (Socket)                                                 |
| RANGE     | Campo di misura della pinza                      | 1000mA,100A,1000A                                                              |
| LIMIT     | Valore limite di misura con pinza HT96U          | 0.1mA ÷ 1000mA (1000mA)<br>0.1A ÷ 100.0A (100A)<br>1.0A ÷ 1000A (1000A)         |
|           | Valore limite di misura con collegamento a presa | 0.25mA ÷ 10.0A                                                                 |
| L POS     | Posizione terminale di Fase sulla presa schuko | LEFT (Sinistra) / RIGHT (Destra)                                               |

### Uso del trasduttore a pinza HT96U

3. Selezionare la funzione **PINZA** premendo il tasto virtuale **MODE**
4. Controllare l'intervallo di misura selezionato e modificarlo se necessario premendo il tasto virtuale **RANGE**
5. Controllare la corrente di dispersione limite selezionata e modificarla se necessario premendo il tasto virtuale **LIMIT**. Sono disponibili quattro valori limite indipendenti per velocizzare le operazioni. Selezionare il valore più vicino a quello desiderato e modificarlo utilizzando i tasti virtuali **+** e **―**, se necessario
6. Selezionare la schermata di misura premendo il tasto virtuale e controllare nuovamente tutte le impostazioni
7. Collegare la pinza di corrente al circuito in prova come mostrato nella **Fig. 72**

FULLTEST3 IT - 74

**Fig. 72**: Collegamento della pinza di corrente nella misura ILEAK

8. Avviare la misura premendo il tasto **START/STOP**. La misura sarà avviata e sarà arrestata da una nuova pressione del tasto **START/STOP**. Il risultato del test sarà visualizzato **in verde** se inferiore o uguale o **in rosso** se superiore al valore limite impostato. Il risultato finale sarà accompagnato dal simbolo **verde** e da un segnale acustico breve (risultato OK) o dal simbolo **rosso** e da un segnale acustico prolungato (risultato non OK). La seguente **Fig. 73** mostra un esempio di schermata con i risultati delle misure

**Fig. 73**: Videata di misura della funzione ILEAK con pinza

Significato simboli a display

| Riferimento | Descrizione                                                                                                 |
| :---------- | :---------------------------------------------------------------------------------------------------------- |
| 1           | Funzione selezionata                                                                                        |
| 2           | Tasto virtuale della schermata di misura                                                                    |
| 3           | Tasto virtuale **MODE** per selezionare la modalità di misura PINZA (CLAMP)                                 |
| 4           | Tasto virtuale **RANGE** per selezionare il campo di misura                                                  |
| 5           | Tasto virtuale **LIMIT** per selezionare il valore limite della corrente all'interno di ciascun campo di misura |
| 6           | Risultato della misura (**in verde** - risultato OK, **in rosso** - risultato NON OK)                         |
| 7           | Orologio in tempo reale (hh.mm.ss).                                                                         |
| 8           | Unità di misura del risultato                                                                               |
| 9           | Stato del risultato della misura (simbolo visualizzato **in verde** - risultato OK, simbolo visualizzato **in rosso** - risultato NON OK) |

FULLTEST3 IT - 75

9. Salvare i risultati delle misure premendo il tasto **SAVE** (vedere **§ 7.1**)

### Uso della presa di prova

3. Selezionare la funzione **PRESA (SOCKET)** premendo il tasto virtuale **MODE**
4. Controllare la corrente di dispersione limite selezionata e modificarla se necessario premendo il tasto virtuale **LIMIT**. Sono disponibili quattro valori limite indipendenti per velocizzare le operazioni. Selezionare il valore più vicino a quello desiderato e modificarlo utilizzando i tasti virtuali **+** e **―**, se necessario
5. Controllare la posizione selezionata del terminale di fase sulla presa schuko premendo il tasto virtuale **L POS**. Se è selezionata la posizione **SINISTRA**, il potenziale di fase è collegato al terminale di sinistra della presa schuko e viceversa
6. Selezionare la schermata di misura premendo il tasto virtuale e controllare nuovamente tutte le impostazioni
7. Collegare l'UUT alla presa schuko come mostrato nella **Fig. 74**

**Fig. 74**: Collegamento dell'UUT in misura ILEAK, modo PRESA

8. Avviare la misura premendo il tasto **START/STOP**. La misura è avviata e terminata da una nuova pressione del tasto **START/STOP**. Il risultato del test è visualizzato **in verde** se inferiore o uguale o **in rosso** se superiore al valore limite impostato. Il risultato finale sarà accompagnato dal simbolo **verde** e da un segnale acustico breve (risultato OK) o dal simbolo **rosso** e da un segnale acustico prolungato (risultato non OK). La **Fig. 75** mostra un esempio di schermata con i risultati delle misure

**Fig. 75**: Videata dei risultati delle prove ILEAK in modo PRESA

FULLTEST3 IT - 76

Significato simboli a display

| Riferimento | Descrizione                                                                                                    |
| :---------- | :------------------------------------------------------------------------------------------------------------- |
| 1           | Funzione selezionata                                                                                           |
| 2           | Sottorisultati, tensione di rete U L/N                                                                         |
| 3           | Tasto virtuale della schermata di misura                                                                       |
| 4           | Tasto virtuale **MODE** per selezionare la modalità di misura PRESA (SOCKET)                                   |
| 5           | Tasto virtuale **LIMITE** per selezionare la corrente di dispersione limite. Il valore attualmente selezionato è visualizzato in basso sul pulsante |
| 6           | Tasto virtuale **L POS** per selezionare la posizione del terminale di fase sulla presa schuko durante la misura. La posizione attualmente selezionata è visualizzata in basso sul pulsante |
| 7           | Risultato della misura (**in verde** - risultato OK, **in rosso** - risultato NON OK)                          |
| 8           | Orologio in tempo reale (hh.mm.ss).                                                                            |
| 9           | Unità di misura del risultato                                                                                  |
| 10          | Stato del risultato della misura (simbolo visualizzato **in verde** - risultato OK, simbolo visualizzato **in rosso** - risultato NON OK) |

9. Salvare i risultati delle misure premendo il tasto **SAVE** (vedere **§ 7.1**)

> **ATTENZIONE**
> * Eseguire la misura in entrambe le posizioni del conduttore di fase (fase al terminale sinistro e al terminale destro) e considerare il valore più alto
> * Accendere l'UUT per poter misurare la corrente di dispersione totale
> * In caso di sovraccarico della presa di prova, i fusibili F1 o F2 (entrambi T16A/250V) potrebbero interrompersi
> * Non usare la presa di prova schuko per scopi diversi dalla misura
> * Il tempo di misura è limitato a 60min

### 6.12.1. Situazioni anomale

I seguenti messaggi potrebbero apparire a display durante la misura:

| Messaggio                           | Descrizione                                                                         |
| :---------------------------------- | :---------------------------------------------------------------------------------- |
| **CORRENTE DIFFERENZIALE OLTRE I LIMITI** | Se la corrente I PE è superiore a 10A per 10s, la misura è arrestata e apparirà questo messaggio. |

FULLTEST3 IT - 77

## 6.13. ESECUZIONE DI UN AUTOTEST

Lo strumento permette di eseguire sequenze di Autotest predefinite all’interno del **Menu principale** (vedere **§ 5.7**).

1. Premere il tasto **FUNC** e selezionare la funzione **AUTO TEST**. La videata di **Fig. 76 – parte sinistra** è mostrata a display

**Fig. 76**: Videata iniziale funzione AUTO TEST

2. Usare i tasti freccia **** o **** per selezionare l’Autotest desiderato (ex: misura di Isolamento con tensione di prova 500VDC e 3 test inclusi) e toccare il tasto **SELECT (SELEZIONA)** oppure direttamente la riga corrispondente. Il messaggio “0/X” in cui X=numero di test presenti nell’Autotest indica che nessun test interno è stato eseguito. La videata di **Fig. 76 – parte destra** è mostrata a display
3. Collegare lo strumento al primo circuito in prova (ex: considerare la misura di Isolamento del **§ 6.3**)
4. Premere due volte il tasto **START/STOP** per attivare il test “ **01** ” dell’Autotest
5. Premere nuovamente il tasto **START/STOP** per terminare il test “ **01** ”. Lo strumento salverà il primo risultato parziale dell’Autotest e si predispone automaticamente per l’esecuzione del test successivo “ **02** ” (vedere **Fig. 77**)
6. Premere il tasto **COMMENT (COMMENTO)** per inserire un eventuale commento al test 01

**Fig. 77**: Funzione AUTO TEST – Risultato parziale test 01

7. Collegare i cavi di misura al secondo circuito in prova
8. Premere due volte il tasto **START/STOP** per attivare il test “ **02** ” dell’Autotest
9. Premere nuovamente il tasto **START/STOP** per terminare il test “ **02** ”. Lo strumento salverà il secondo risultato parziale dell’Autotest e si predispone automaticamente per l’esecuzione del test successivo “ **03** ” (vedere **Fig. 78**)
10. Premere il tasto **COMMENT (COMMENTO)** per inserire un eventuale commento al test 02

FULLTEST3 IT - 78

**Fig. 78**: Funzione AUTO TEST – Risultato parziale test 02

11. Premere due volte il tasto **START/STOP** per attivare il test “ **03** ” dell’Autotest che nell’esempio considerato è la funzione **VISUAL (VISUALIZZA)** che indica l’esito Passato o Fallito del test inserito dall’operatore (vedere **Fig. 79 – parte sinistra**)
12. Premere il tasto **COMMENT (COMMENTO)** per inserire un eventuale commento al test 03

**Fig. 79**: Funzione AUTO TEST – Risultato finale Autotest

13. Al termine dell’Autotest lo strumento presenta una videata finale simile a quella mostrata in **Fig. 79 – parte destra**
14. Salvare i risultati dell’Autotest premendo il tasto **SAVE** (vedere **§ 7.2**)
15. Premere il tasto **RESET** per cancellare i risultati di misura ripristinando la configurazione inziale dell’Autotest in modo da poter ripetere eventualmente le operazioni

FULLTEST3 IT - 79

# 7. OPERAZIONI CON MEMORIA

Ogni locazione di memoria dispone di **3 livelli**: **LEVEL1 (LIVELLO 1)**, **LEVEL2 (LIVELLO2)** e **LEVEL3 (LIVELLO3)** i cui nomi possono essere definiti nel menu Impostazioni (vedere **§ 5.5**). Almeno il **LIVELLO1** deve essere inserito alla prima pressione del tasto **SAVE**. E’ possibile aggiungere un commento (**max 30 caratteri**) a ciascun risultato salvato. A salvataggio eseguito, il risultato di misura è assegnato automaticamente ad una locazione di memoria che si aggiorna progressivamente ad ogni operazione (max 999 locazioni). Al risultato sono aggiunti anche la data/ora e l’operatore che occorre definire in fase di programmazione (vedere **§ 5.2**).

## 7.1. SALVATAGGIO MISURE

Per salvare il risultato della misura operare come segue:

1. Eseguire la misura
2. Premere il tasto **SAVE**. La seguente videata appare a display

SAVE
CUSTOMER COMPANY A
LOCATION ROMA
MACHINE No PLASTIC INJECTION MACHINE 003
DEVICE SERVICED
COMMENT

**Fig. 80**: Videata iniziale menu SAVE

3. Inserire le informazioni nei 3 livelli ed eventualmente a includere un commento associato alla misura
4. Se occorre modificare e/o aggiungere il nome associato ad un livello (ex: LIVELLO1) toccare il campo corrispondente. La seguente videata appare a display

**Fig. 81**: Menu SALVA – Modifica LIVELLO1

5. Controllare la lista dei clienti disponibili utilizzando i tasti freccia virtuali **▼** e **▲** e selezionare il cliente desiderato premendo il tasto virtuale corrispondente (ex: **CLIENTE /CUSTOMER 4**)
6. Premere il tasto virtuale **AGGIUNGI NUOVO/ADD NEW** per aggiungere un nuovo cliente (vedere **Fig. 82**)

FULLTEST3 IT - 80

**Fig. 82**: Menu SALVA – Aggiunta CLIENTE

7. Premere il tasto virtuale **ENTER** per confermare la selezione
8. Ripetere l'operazione per gli altri due livelli e per il commento, se necessario, seguendo la stessa procedura

> **ATTENZIONE**
> Selezionando il **LIVELLO2** o il **LIVELLO3** lo strumento proporrà nomi già utilizzati o “VUOTI”, perché l’operatore possa scegliere uno dei nomi esistenti o direttamente il livello VUOTO (i livelli 2 e 3 non sono obbligatori)

9. Premere il tasto **SAVE** per confermare l'operazione di salvataggio avviata. Seguirà un segnale acustico a conferma che il salvataggio è stato completato con successo

> **ATTENZIONE**
> * Il **LIVELLO1** deve essere inserito obbligatoriamente quando si salva il risultato del test, mentre **LIVELLO 2**, **LIVELLO3** e **COMMENTI** non sono strettamente necessari
> * I livelli devono essere selezionati/impostati in ordine dalla cima (LIVELLO 1) al basso (COMMENTI). Non saltare livelli vuoti

FULLTEST3 IT - 81

## 7.2. SALVATAGGIO AUTOTEST

1. Eseguire l’**Autotest** selezionato
2. Premere il tasto **SAVE**. La seguente videata appare a display

**Fig. 83**: Salvataggio Autotest – Passo1

3. E’ possibile in questa fase modificare solo il valore associato al **LIVELLO1** (i valori associati a **LIVELLO2**, **LIVELLO3** e **COMMENTO** non sono modificabili). Toccare il campo del **LIVELLO1**. La videata di **Fig. 84 – parte sinistra** è mostrata a display

**Fig. 84**: Salvataggio Autotest – Modifica nome LIVELLO1

4. Premere il tasto virtuale **AGGIUNGI NUOVO (ADD NEW)** per aggiungere un nuovo riferimento e confermare con **ENTER**
5. Premere il tasto **SAVE** per confermare l'operazione di salvataggio avviata. Seguirà un segnale acustico a conferma che il salvataggio è stato completato con successo)

> **ATTENZIONE**
> Eventuali commenti alle misure possono essere inseriti solo all’interno dei singoli test inclusi nell’Autotest

FULLTEST3 IT - 82

## 7.3. RICHIAMO DEI RISULTATI A DISPLAY

1. Premere il tasto **RCL**. La seguente videata è mostrata a display

**Fig. 85**: Menu RECALL (RICHIAMA)

2. Controllare il cliente proposto e, se necessario, selezionarne un altro premendo il tasto virtuale **CLIENTE /CUSTOMER**. Sul display apparirà la seguente videata.

**Fig. 86**: Menu RICHIAMA - Modifica LIVELLO1

3. Controllare la lista dei clienti disponibili utilizzando i tasti freccia virtuali **▼** e **▲**
4. Selezionare il cliente desiderato premendo il tasto virtuale corrispondente (ex: . **CLIENTE 3**)
5. Confermare la selezione premendo il tasto virtuale **ENTER**; sul display apparirà il menù **RICHIAMA**. Se è presente una lista di molti clienti disponibili, usare il tasto virtuale **SEARCH** per selezionare rapidamente il cliente desiderato
6. Premere il tasto **PRINT (STAMPA)** per stampare la videata (con accessorio opzionale **FT3MPT2** collegato agli ingressi **USB2** o **USB3**)
7. Selezionare la misura desiderata utilizzando i tasti freccia **◄** e **►**.
8. Premere nuovamente il tasto **RCL**; il risultato salvato sarà visualizzato come segue.

**Fig. 87**: Menu RICHIAMA – Richiamo risultato

9. Premere nuovamente il tasto **RCL** per controllare le schermate successive
10. Premere il tasto **EXIT** per uscire e tornare alla videata principale

FULLTEST3 IT - 83

# 8. USO DEGLI ACCESSORI OPZIONALI

## 8.1. USO TASTIERA ESTERNA

La tastiera esterna USB (accessorio opzionale **FT3KBDEN**) è utilizzabile qualora occorra inserire dati nella memoria dello strumento (cliente, macchina, luogo e commenti) in modo semplice e rapido.

1. Collegare la tastiera USB agli ingressi **USB2** o **USB3** (vedere **Fig. 2 – parte 10**)
2. Lo strumento emette 3 segnali acustici a conferma del riconoscimento dell’accessorio

## 8.2. USO LETTORE DI CODICI A BARRE

Il lettore di codici a barre USB (accessorio opzionale **FT3BARCR**) è utilizzabile quando occorre inserire un nuovo cliente in memoria in modo da eseguire il lavoro in modo semplice e rapido.

1. Collegare il lettore di codici a barre USB agli ingressi **USB2** o **USB3** (vedere **Fig. 2 – parte 10**)
2. Lo strumento emette 3 segnali acustici a conferma del riconoscimento dell’accessorio
3. Eseguire la misura
4. Premere il tasto **SAVE**. La seguente videata è mostrata a display

SAVE
CUSTOMER COMPANY A
LOCATION ROMA
MACHINE No PLASTIC INJECTION MACHINE 003
DEVICE SERVICED
COMMENT

**Fig. 88**: Misura con lettore codici a barre – Salvataggio dato

5. Premere il tasto virtuale **CLIENTE /CUSTOMER**. La seguente videata è mostrata a display

**Fig. 89**: Misura con lettore codici a barre – Selezione cliente

6. Premere il tasto virtuale **AGGIUNGI NUOVO /ADD NEW** se occorre inserire un nuovo cliente. La videata di **Fig. 89 – parte destra** è mostrata a display

FULLTEST3 IT - 84

7. Eseguire la scansione dell’etichetta (barcode) del cliente utilizzando il lettore di codici a barre USB. Il nome cliente sarà inserito e il display tornerà al menu precedente
8. Modificare o inserire gli altri due livelli di salvataggio (LUOGO e MACCHINA) ed eventuali **COMMENTI** manualmente. Confermare il salvataggio premendo nuovamente il tasto **SAVE**

### 8.2.1. Configurazione lettore di codice a barre

Al primo utilizzo del lettore di codici a barre **Honeywell Voyager 1250G - 2USB - 1** (accessorio opzionale **FT3BARCR**) è necessario configurarlo come segue:

1. Collegare il lettore di codici a barre allo strumento
2. Accendere lo strumento per garantire un’adeguata alimentazione
3. Eseguire la configurazione iniziale del lettore di codici a barre eseguendo la scansione del seguente codice
4. Impostare il prefisso del lettore di codici a barre eseguendo la scansione del codice seguente.
5. Impostare il suffisso del lettore di codici a barre eseguendo la scansione del codice seguente
6. Terminare la configurazione del lettore di codice a barre eseguendo la scansione del codice seguente
7. Spegnere e riaccendere lo strumento dopo avere eseguito la scansione dei codici sopra riportati. Il lettore di codici a barre e lo strumento sono ora pronti per l’utilizzo

> **ATTENZIONE**
> Usare esclusivamente lettori di codici a barre Honeywell modello Voyager 1250G - 2USB - 1. Diversamente, lo strumento potrebbe non riconoscere il lettore

FULLTEST3 IT - 85

# 9. AGGIORNAMENTO FIRMWARE STRUMENTO

È possibile aggiornare il Firmware (**FW**) interno dello strumento tramite utilizzo di un pen drive **USB**. Operare come segue:

1. Aggiornare il software di gestione **TopView** in dotazione all’ultima versione disponibile
2. Inserire a PC un pen drive **USB** di dimensione **max 64GB** formattato **FAT32**
3. Scaricare dalla sezione “Collegamento PC → strumento” di **TopView** l’ultima versione disponibile del **FW**
4. Eseguire il file "**90550_PENDRIVE_FW_UPG_setup.exe**" scaricato che caricherà l’ultima versione del **FW** all’interno del pen drive **USB**
5. Estrarre il pen drive e collegarlo agli ingressi **USB2** o **USB3** dello strumento
6. Confermare il messaggio di richiesta aggiornamento **FW** mostrato a display
7. Attendere che il display dello strumento torni alla schermata iniziale ed estrarre il pen drive **USB**. Il nuovo **FW** è stato installato
8. Controllare la versione installata (vedere **§ 5.4**)

FULLTEST3 IT - 86

# 10. MANUTENZIONE

## 10.1. GENERALITÀ

1. Durante l’utilizzo e la conservazione rispettare le raccomandazioni elencate in questo manuale per evitare possibili danni o pericoli durante l’utilizzo
2. Non utilizzare lo strumento in ambienti caratterizzati da elevato tasso di umidità o temperatura elevata. Non esporre direttamente alla luce del sole. Spegnere sempre lo strumento dopo l’utilizzo

## 10.2. PULIZIA DELLO STRUMENTO

1. Nel caso in cui sia necessario pulire lo strumento dopo l'uso, è consigliabile usare un panno umido e detergente delicato. Non usare mai detergenti a base acida o solventi
2. Prima di procedere alla pulizia, scollegare lo strumento da qualsiasi circuito di misura e dalla rete. Dopo la pulizia, non usare lo strumento finché questo non sia completamente asciutto.

## 10.3. SOSTITUZIONE FUSIBILI

In caso di sostituzione dei fusibili interni operare come segue.

> **ATTENZIONE**
> * Solo tecnici esperti possono effettuare questa operazione. Prima di effettuare questa operazione assicurarsi di aver rimosso tutti i cavi dai terminali di ingresso e scollegare lo strumento dalla rete di alimentazione
> * Usare solo fusibili conformi a quanto riportato nel **§ 11.2**

### Sostituzione Fusibili F1 e F2

*   I fusibili **F1** e **F2** proteggono i circuiti interni dello strumento durante le misure di **POTENZA**, **RPE** e di **RIGIDITÀ DIELETTRICA**
*   Nel caso in cui la spia di segnalazione dell'interruttore di rete (vedere **Fig. 2 – parte 5**) non si accenda dopo avere collegato lo strumento all’alimentazione e il display LCD non mostri alcuna indicazione, controllare lo stato dei fusibili **F1** (vedere **Fig. 2 – parte 4**) o **F2** (vedere **Fig. 2 – parte 3**) e sostituirli se necessario.

1. Aprire i portafusibili **F1** e **F2** utilizzando un giravite
2. Rimuovere il fusibile difettoso e sostituirlo con uno nuovo (vedere **§ 11.2**)
3. Riposizionare i portafusibili

### Sostituzione Fusibile F3

*   Il fusibile **F3** protegge i circuiti interni dello strumento durante le misure di **LOOP**, **RA** o **RCD**
*   Il fusibile **F3** è danneggiato se il messaggio “**FUSIBILE F3**” appare a display nelle funzioni **LOOP**, **RA** o **RCD**

1. Aprire il portafusibili **F3** (vedere **Fig. 2 – parte 2**) utilizzando un giravite
2. Rimuovere il fusibile difettoso e sostituirlo con uno nuovo (vedere §)
3. Riposizionare i portafusibili

### Sostituzione Fusibile F4

*   Il fusibile **F4** è danneggiato se il messaggio “**FUSIBILE F4**” appare a display in funzione **RPE**

1. Aprire il portafusibili **F4** (vedere **Fig. 2 – parte 15**) utilizzando un giravite
2. Rimuovere il fusibile difettoso e sostituirlo con uno nuovo (vedere §)
3. Riposizionare i portafusibili

> **ATTENZIONE**
> Nel caso in cui un fusibile dovesse saltare più volte (ad esempio in caso di errore di funzionamento), lo strumento deve essere inviato al servizio assistenza

## 10.4. FINE VITA

> **ATTENZIONE**: il simbolo riportato indica che l'apparecchiatura e i suoi accessori devono essere raccolti separatamente e trattati in modo corretto

FULLTEST3 IT - 88

# 11. SPECIFICHE TECNICHE

## 11.1. CARATTERISTICHE TECNICHE

Incertezza calcolata come ±[%lettura + (num.cifre*risoluzione)] a 23°C ± 5°C, <60%RH

### CONTINUITÀ CONDUTTORI DI PROTEZIONE (RPE - 2 FILI, 200mA)

| Campo [Ω]   | Risoluzione [Ω] | Incertezza         | Protezione da sovraccarichi |
| :---------- | :-------------- | :----------------- | :-------------------------- |
| 0.00 ÷ 19.99 | 0.01            | ±(3%lettura + 3cifre) | CAT III 300V                |
| 20.0 ÷ 200.0 | 0.1             |                    |                             |

*   Tensione di prova a vuoto: Circa 4.5VAC
*   Corrente di prova di cortocircuito: <0.6A (terminali di misura standard)
*   Corrente di prova: >200mA con terminali di misura standard e resia esterna < 20 Ω
*   Intervallo corrente di prova: 10 mA ÷ 255mA
*   Incertezza corrente di prova: ± (3%lettura + 2cifre)
*   Valore limite misura: 0.01 Ω ÷ 200.0 Ω selezionabile
*   Timer sulla misura: 2s ÷ 60min programmabile
*   Principio di misura: collegamento 2-Fili
*   Calibrazione cavi di misura: fino a 5.00 Ω
*   Protezione: Fusibile **F4**
*   Rilevazione della tensione esterna: UEXT lim = 3VAC (ingressi RPE o ingressi SENSE)<br>UEXT lim = 10VAC (ingressi RPE o ingressi SENSE)<br>UEXT lim = 30VAC circa. (ingresso RPE/SENSE e GND)

### CONTINUITÀ CONDUTTORI DI PROTEZIONE (RPE - 2 FILI, 25A)

| Campo [Ω]   | Risoluzione [Ω] | Incertezza         | Protezione da sovraccarichi |
| :---------- | :-------------- | :----------------- | :-------------------------- |
| 0.000 ÷ 1.999 | 0,001           | ±(3%lettura +3 cifre) | CAT III 300 V               |
| 2.00 ÷ 20.00  | 0.01            |                    |                             |

*   Tensione di prova a vuoto: circa 4.5VAC
*   Corrente di prova di cortocircuito <30A (terminali di misura standard)
*   Corrente di prova (campo 25A): >25A (terminali di misura standard e resistenza esterna <0.1 Ω)<br>>10A (terminali di misura standard e resistenza esterna <0.5 Ω)
*   Intervallo corrente di prova: 0.2 ÷ 30.0 A
*   Incertezza corrente di prova: ±(3%lettura + 1cifra)
*   Valore limite misura: 0.01 Ω ÷ 20.00 Ω selezionabile OPPURE calcolo mediante l'impedenza dell'anello di guasto OPPURE calcolo mediante la lunghezza del cavo in prova
*   Timer sulla misura: 2s ÷ 60min programmabile (corrente >10A)<br>2s ÷ 5min programmabile (corrente >25A)
*   Principio di misura: collegamento 2-Fili
*   Calibrazione cavi di misura: fino a 5.00 Ω
*   Protezione:: Fusibile **F4**
*   Rilevazione della tensione esterna: Sì (vedere Continuità 200mA)

### CONTINUITÀ CONDUTTORI DI PROTEZIONE (RPE - 4FILI, 25A)

| Campo [Ω]   | Risoluzione [Ω] | Incertezza         | Protezione da sovraccarichi |
| :---------- | :-------------- | :----------------- | :-------------------------- |
| 0.000 ÷ 1.999 | 0.001           | ±(3%lettura +3cifre) | CAT III 300 V               |
| 2.00 ÷ 20.00  | 0.01            |                    |                             |

*   Tensione di prova a vuoto: Circa 4.5VAC
*   Corrente di prova di cortocircuito: <30A (terminali di misura standard)
*   Corrente di prova: >25A (terminali di misura standard e resistenza esterna < 0.1 Ω)<br>>10A (terminali di misura standard e resistenza esterna < 0.5 Ω)
*   Intervallo corrente di prova: 0.2 A ÷ 30.0A
*   Incertezza corrente di prova: ±(3%lettura +1cifra)
*   Valore limite misura: vedere Continuità 2-FILI 25A
*   Timer sulla misura: 2s ÷ 5min programmabile
*   Principio di misura: Collegamento 4-FILI
*   Protezione: Fusibile **F4**
*   Rilevazione della tensione esterna: Sì (vedere Continuità 200mA)

FULLTEST3 IT - 89

### RESISTENZA DI ISOLAMENTO (MΩ)

| Tensione di prova DC [V] | Campo misura [MΩ] | Risoluzione [MΩ] | Incertezza         | Protezione da sovraccarichi |
| :----------------------- | :---------------- | :--------------- | :----------------- | :-------------------------- |
| 100                      | 0.00 ÷ 9.99       | 0.01             | ±(3%lettura +3cifre) | CAT III 300 V               |
|                          | 10.0 ÷ 20.0       | 0.1              |                    |                             |
|                          | 20.0 ÷ 99.9       |                  | ±(5%lettura)       |                             |
| 250                      | 0.00 ÷ 9.99       | 0.01             | ±(3%lettura +3cifre) |                             |
|                          | 10.0 ÷ 20.0       | 0.1              |                    |                             |
|                          | 20.0 ÷ 99.9       |                  | ±(5%lettura)       |                             |
|                          | 100 ÷ 250         | 1                |                    |                             |
| 500                      | 0.00 ÷ 9.99       | 0.01             | ±(3%lettura +3 cifre) |                             |
|                          | 10.0 ÷ 20.0       | 0.1              |                    |                             |
|                          | 20.0 ÷ 99.9       |                  | ±(5%lettura)       |                             |
|                          | 100 ÷ 500         | 1                |                    |                             |
| 1000                     | 0.00 ÷ 9.99       | 0.01             | ±(3%lettura + 3 cifre) |                             |
|                          | 10.0 ÷ 20.0       | 0.1              |                    |                             |
|                          | 20.0 ÷ 99.9       |                  | ±(5%lettura)       |                             |
|                          | 100 ÷ 1000        | 1                |                    |                             |

*   Incertezza tensione di prova: (-0% ÷ +25%) di Un
*   Corrente di prova: >1mA (fino a Un/1mA)
*   Corrente di cortocircuito: <15mA
*   Scarica oggetto in prova: Resistenza interna di 2MΩ al termine della misura
*   Rilevazione della tensione esterna: UEXT lim = 10VAC (ingressi RINS+ e RINS-)<br>UEXT lim = 50VAC (RINS+ e RINS-)<br>UEXT lim = 50VAC circa (ingresso RINS e GND)<br>UEXT lim = 10VDC (ingressi RINS+ e RINS-)

### RIGIDITA’ DIELETTRICA (WITHSTANDING)

| Tensione di prova nominale U N [V] | Risoluzione [V] | Incertezza | Protezione da sovraccarichi |
| :--------------------------------- | :-------------- | :--------- | :-------------------------- |
| 250 ÷ 800                          | 10              | ±3%UN      | CAT III 300V                |
| 810 ÷ 2500                         |                 |            |                             |
| 2510 ÷ 5100                        |                 |            |                             |

*   Tensione di prova nominale UN: Regolabile 250 V ÷ 5100V, 50/60 Hz in passi da 10V
*   Distorsione tensione di prova: Fattore di cresta FC = 1.414 ± 5%
*   Modi di misura: MANUALE, RAMPA (timer), BURN, PULSE (durata 3 cicli di misura: 60ms@50Hz, 50ms@60Hz)
*   Potenza in uscita: 500VA (@ 5100V)

Corrente di scarica I APP

| Campo [mA] | Risoluzione [mA] | Incertezza        |
| :--------- | :--------------- | :---------------- |
| 0 ÷ 200    | 1                | ±(3%lettura + 2mA) |

Corrente di scarica I REAL

| Campo [mA] | Risoluzione [mA] | Incertezza        |
| :--------- | :--------------- | :---------------- |
| 0 ÷ 110    | 1                | ±(3%lettura + 4mA) |

*   Corrente di rottura nominale (IAPP o IREAL): Regolabile 1 mA ÷ 110mA in passi da 1mA
*   Corrente di cortocircuito: >200mA
*   Tempo di rottura: < 30ms

FULLTEST3 IT - 90

### TEST SU RCD (RCD)

*   Tipologia RCD: AC, A, B, Generali, Selettivi o Ritardati (Delayed)
*   Modi di misura: ½ IΔN, IΔN, 2IΔN, KIΔN (K = 4 tipo B, K=5 tipo AC, A)<br>IΔ (RAMPA), AUTO (sequenza: x ½ , x1, xK)
*   Corrente nominale IΔN: 10, 30, 100, 300, 500, 650, 1000 mA
*   Campo tempo di ritardo: 0ms ÷ 700ms regolabile
*   Incertezza correnti di prova (10mA): -10% / +0% (IΔN/2), +10% / -0% (IΔN, 2IΔN, KIΔN)
*   Incertezza correnti di prova (30 ÷ 1000mA): -5% / +0% (IΔN/2), +5% / -0% (IΔN, 2IΔN, KIΔN)
*   Campo tensione/frequenza: 100 V ÷ 265V/(50/60 Hz) ± 0.5 Hz
*   Tensione di contatto limite: 25V o 50V selezionabile
*   Polarità corrente di prova: 0° (Positiva) o 180° (Negativa)

Durata test [ms] – Sistema TT/TN

| IΔN [mA] |        | ×½     |        | ×1     |        | ×2     |        | ×K     |        | AUTO |        | RAMPA  |        |
| :------- | :----- | :----- | :----- | :----- | :----- | :----- | :----- | :----- | :----- | :--- | :----- | :----- | :----- |
|          |        | G, S, D | G, S, D | G      | S      | D      | G      | S      | D      | G    | S      | D      |        |
| 10       | AC     | 1000   | 1000   | 200    | 250    | X      | 50     | 150    | X      | X    | 320    | X      | X      |
|          | A      | 1000   | 1000   | 200    | 250    | X      | 50     | 150    | X      | X    | 320    | X      | X      |
|          | B      | 1000   | 1000   | X      | X      | X      | 200    | 250    | X      | X    | 320    | X      | X      |
| 300      | AC     | 1000   | 1000   | 200    | 250    | X      | 50     | 150    | X      | X    | 320    | X      | X      |
|          | A      | 1000   | 1000   | 200    | 250    | X      | 50     | 150    | X      | X    | 320    | X      | X      |
|          | B      | 1000   | 1000   | X      | X      | X      | X      | X      | X      | X    | 320    | X      | X      |
| 500      | AC     | 1000   | 1000   | 200    | 250    | X      | 50     | 150    | X      | X    | 320    | X      | X      |
|          | A      | 1000   | 1000   | 200    | 250    | X      | X      | X      | X      | X    | 320    | X      | X      |
|          | B      | 1000   | 1000   | X      | X      | X      | X      | X      | X      | X    | 320    | X      | X      |
| 650      | AC     | 1000   | 1000   | 200    | 250    | X      | 50     | 150    | X      | X    | 320    | X      | X      |
|          | A      | 1000   | 1000   | 200    | 250    | X      | X      | X      | X      | X    | 320    | X      | X      |
|          | B      | X      | X      | X      | X      | X      | X      | X      | X      | X    | X      | X      | X      |
| 1000     | AC     | 1000   | 1000   | 200    | 250    | X      | X      | X      | X      | X    | 320    | X      | X      |
|          | A      | 1000   | 1000   | X      | X      | X      | X      | X      | X      | X    | X      | X      | X      |
|          | B      | X      | X      | X      | X      | X      | X      | X      | X      | X    | X      | X      | X      |

*   Risoluzione: 1ms, Incertezza: ±(3%lettura + 2ms)
*   X = test non eseguibile
*   Tensione di rete UL/N, UL/PE
    *   Campo [V]: 100 V ÷ 265 V
    *   Risoluzione [V]: 1
    *   Incertezza: ±(3%lettura)
    *   Resistenza di ingresso (UL/N, UL/PE): 450kΩ
*   Test rampa: intervallo di corrente 10 % ÷ 110% IΔN in passi da 5%IΔN
*   Test AUTO: sequenza di test: t/IΔN/2 (0°), t/IΔN/2 (180°), t/IΔN (0°), t/IΔN (180°), t/5IΔN (0°), t/5IΔN (180°)

FULLTEST3 IT - 91

### IMPEDENZA ANELLO DI GUASTO (LOOP)

| Campo [Ω]   | Risoluzione [Ω] | Incertezza            | Protezione da sovraccarichi |
| :---------- | :-------------- | :-------------------- | :-------------------------- |
| 0.000 ÷ 2.000 (*) | 0.001           | ±(3%lett. + 3 cifre)  | CAT III 300 V               |
| 0.00 ÷ 9.99 | 0.01            |                       |                             |
| 10.0 ÷ 99.9 | 0.1             |                       |                             |
| 100 ÷ 200   | 1               |                       |                             |

*   (*) Con accessorio opzionale IMP57
*   Campo tensione di ingresso LOOP L/PE o L/N: 100 V ÷ 265V, 50/60 Hz
*   Campo tensione di ingresso LOOP L/L: 100 V ÷ 460V, 50/60 Hz
*   Tensione di rete nominale: 110V, 115V, 120V, 133V, 220V, 230V, 240V
*   Resistenza di carico: 10 Ω per 20ms (campo 0.00 Ω ÷ 30.0 Ω) e 180 Ω per 20ms (campo 30.0 Ω ÷ 200.0 Ω)

Corrente di cortocircuito presunta (ISC)

| Campo [A]       | Risoluzione [A] | Incertezza                  |
| :-------------- | :-------------- | :-------------------------- |
| 0.05 ÷ 0.99     | 0.01            | funzione di UL/PE e dell'incertezza Z |
| 1.0 ÷ 99.9      | 0.1             |                             |
| 100 ÷ 999       | 1               |                             |
| 1.00k ÷ 46.00k  | 10              |                             |

Tensione di rete UL/N, UL/PE

| Campo [V]   | Risoluzione [V] | Incertezza   |
| :---------- | :-------------- | :----------- |
| 100 ÷ 265   | 1               | ±(3%lettura) |

*   Resistenza di ingresso (UL/N, UL/PE): 450kΩ

Tensione di rete UL/L

| Campo [V]   | Risoluzione [V] | Incertezza   |
| :---------- | :-------------- | :----------- |
| 100 ÷ 460   | 1               | ±(3%lettura) |

*   Resistenza di ingresso (UL/N, UL/PE): 450 kΩ

FULLTEST3 IT - 92

### RESISTENZA GLOBALE DI TERRA SENZA INTERVENTO RCD (RA)

| IΔN [mA] | Campo [Ω]    | Risoluzione [Ω] | Incertezza (*)     | Protezione da sovraccarichi |
| :------- | :----------- | :-------------- | :----------------- | :-------------------------- |
| 10       | 0 ÷ 2000     | 1               | ±(3%lettura +1 Ω) | CAT III 300 V               |
| 30       | 0,0 ÷ 99,9   | 0.1             |                    |                             |
|          | 100 ÷ 2000   | 1               |                    |                             |
| 100      | 0.0 ÷ 99.9   | 0.1             | ±(3%lettura +3cifre) |                             |
|          | 100 ÷ 1000   | 1               |                    |                             |
| 300      | 0,0 ÷ 99,9   | 0.1             |                    |                             |
|          | 100 ÷ 300    | 1               |                    |                             |
| 500      | 0,0 ÷ 99,9   | 0.1             |                    |                             |
|          | 100 ÷ 200    | 1               |                    |                             |
| 650      | 0.0 ÷ 99.9   | 0.1             |                    |                             |
|          | 100 ÷ 150    | 1               |                    |                             |
| 1000     | 0.0 ÷ 100.0  | 0.1             |                    |                             |

*   (*) L’incertezza nel campo 10 Ω ÷ 2000 Ω può essere influenzata da una tensione di rete instabile
*   Corrente di prova: IΔN/2
*   Intervallo di tensione di ingresso: 100 V ÷ 265V, 50/60 Hz
*   Tensione di rete nominale: 110V, 115V, 120V, 133V, 220V, 230V, 240V

Tensione di rete UL/PE

| Campo [V]   | Risoluzione [V] | Incertezza   |
| :---------- | :-------------- | :----------- |
| 100 ÷ 265   | 1               | ±(3%lettura) |

*   Resistenza di ingresso (UL/PE): 450 kΩ

Tensione di contatto UC a IΔN

| Campo [V]         | Risoluzione [V] | Incertezza         |
| :---------------- | :-------------- | :----------------- |
| 0 ÷ 100 (UCLIM=50V) | 1               | ±(3%lettura + 3V) |
| 0 ÷ 50 (UCLIM=25V)  |                 |                    |

### TENSIONE RESIDUA TRMS (URES)

| Campo [V]      | Risoluzione [V] | Incertezza        | Protezione da sovraccarichi |
| :------------- | :-------------- | :---------------- | :-------------------------- |
| 10 ÷ 460 (AC)  | 1               | ±(3%lettura + 3V) | CAT III 300 V               |
| 10 ÷ 650 (DC)  |                 |                   |                             |

*   Tensione di ingresso (UTRIG): 0 V ÷ 460VAC
*   Tensione di rete nominale: 110V, 115V, 120V, 133V, 220V, 230V, 240V
*   Metodo di misura: 4-FILI (misura INTERNA, 1s o 5s)<br>2-FILI (misura PLUG, 1s)
*   Valore limite tensione residua: 60V RMS

Tensione di ingresso URES

| Campo [V]      | Risoluzione (V) | Incertezza        |
| :------------- | :-------------- | :---------------- |
| 10 ÷ 460 (AC)  | 1               | ±(2%lettura + 2V) |
| 10 ÷ 650 (DC)  |                 |                   |

*   Resistenza di ingresso (URES): 100MΩ

Tensione di ingresso UTRIG

| Campo [V]     | Risoluzione [V] | Incertezza        |
| :------------ | :-------------- | :---------------- |
| 10 ÷ 265 (AC) | 1               | ±(2%lettura + 2V) |

*   Resistenza di ingresso (UTRIG): 450kΩ

FULLTEST3 IT - 93

### TEST FUNZIONALI – MISURA CORRENTE TRMS SU PRESA

| Campo [A]   | Risoluzione [A] | Incertezza         | Protezione da sovraccarichi |
| :---------- | :-------------- | :----------------- | :-------------------------- |
| 0.00 ÷ 0.99 | 0.01            | ±(3%lettura + 3cifre) | CAT II 300V                 |
| 1.0 ÷ 16.0  | 0.1             |                    |                             |

*   Campo frequenza: 15 Hz ÷ 723Hz
*   Protezione: interruzione alimentazione 10s dopo il superamento dei 16A
*   Pre-test iniziale: controllo messa a terra conduttore PE della presa shuko

### TEST FUNZIONALI – MISURA TENSIONE TRMS SU PRESA

| Campo [V]   | Risoluzione [V] | Incertezza         | Protezione da sovraccarichi |
| :---------- | :-------------- | :----------------- | :-------------------------- |
| 195 ÷ 253   | 1               | ±(2%lettura + 2cifre) | CAT II 300V                 |

*   Campo frequenza: 15 Hz ÷ 723Hz

### TEST FUNZIONALI – POTENZA ATTIVA / POTENZA APPARENTE SU PRESA

| Campo [VA/W] | Risoluzione (VA/W) | Incertezza         | Protezione da sovraccarichi |
| :----------- | :----------------- | :----------------- | :-------------------------- |
| 0.0 ÷ 99.9   | 0,1                | ±(5%lettura + 10cifre) | CAT II 300 V                |
| 100 ÷ 999    | 1                  | ±(5%lettura + 3cifre) |                             |
| 1.00 ÷ 5.06k | 10                 |                    |                             |

*   Valore limite Papp: Regolabile 6 VA ÷ 999VA, 1.00kVA ÷ 5.06kVA

### TEST FUNZIONALI – MISURA FATTORE DI POTENZA SU PRESA

| Campo      | Risoluzione | Incertezza             | Protezione da sovraccarichi |
| :--------- | :---------- | :--------------------- | :-------------------------- |
| 0.00 ÷ 1.00 | 0.01        | In funzione di PAPP e PACT | CAT II 300V                 |

### TEST FUNZIONALI – MISURA CORRENTE DI DISPERSIONE SU PRESA

| Campo        | Risoluzione | Incertezza         | Protezione da sovraccarichi |
| :----------- | :---------- | :----------------- | :-------------------------- |
| 0.25 ÷ 19.99mA | 0.01mA      | ±(3%lettura + 3cifre) | CAT II 300V                 |
| 20.0 ÷ 49.9mA  | 0.1mA       |                    |                             |
| 0.05 ÷ 0.99A   | 0.01A       |                    |                             |
| 1.0 ÷ 10.0A    | 0.1A        |                    |                             |

*   Influenza corrente di carico: ± 0.01mA/A
*   Valore limite: 0.25mA ÷ 10.00 A (valore limite standard 3.50mA)
*   Campo frequenza: 40Hz ÷ 723Hz (in accordo a IEC /EN 61557-13)
*   Metodo di misura: corrente differenziale
*   Inversione polarità del cavo di rete: Si
*   Rete UUT sull'interruttore di prova: Sì (valore limite 25mA)
*   Limite fuori intervallo (IPE): Sì (misura interrotta dopo 10s al superamento dei 10A)
*   Limite fuori intervallo (IL): Sì (misura interrotta dopo 10s al superamento dei 16A)

### SENSO CICLICO DELLE FASI (PHSEQ)

| Campo [V]   | Risoluzione [V] | Incertezza         | Protezione da sovraccarichi |
| :---------- | :-------------- | :----------------- | :-------------------------- |
| 360 ÷ 460   | 1               | ±(2%lettura + 2cifre) | CAT III 300V                |

*   Visualizzazione del risultato del test: 1.2.3 (corretto), 2.1.3 (incorretto), 1.1.X (indefinito)

FULLTEST3 IT - 94

### CORRENTE AC TRMS CON TRASDUTTORE A PINZA HT96U (ICLAMP)

| Portata | Campo        | Risoluzione | Incertezza (*)     | Protezione da sovraccarichi             |
| :------ | :----------- | :---------- | :----------------- | :-------------------------------------- |
| 1A      | 0.0 ÷ 99.9mA | 0.1mA       | ±(3%lettura +3cifre) | Un terminale di misura collegato a terra |
|         | 100 ÷ 1000mA | 1mA         |                    |                                         |
| 100.0A  | 0.00 ÷ 9.99A | 0.01A       |                    |                                         |
|         | 10.0 ÷ 100.0A | 0.1A        |                    |                                         |
| 1000A   | 0.0 ÷ 99.9A  | 0.1A        |                    |                                         |
|         | 100 ÷ 1000A  | 1A          |                    |                                         |

*   (*) Incertezza del solo strumento senza pinza
*   Campo tensione di ingresso: 0 ÷ 1VAC
*   Resistenza di ingresso: 1MΩ
*   Campo frequenza: 40Hz ÷ 723Hz (in accordo a IEC /EN 61557-13)
*   Tipo pinza: HT96U (campi di misura 1A, 100A, 1000A)
*   Valore limite (campo 1000mA): 0.1 ÷ 99.9mA, 100 ÷ 1000mA selezionabile
*   Valore limite (campo 100.0A): 0.1 ÷ 100.0A selezionabile
*   Valore limite (campo 1000A): 1 ÷ 1000A selezionabile

### CORRENTE DI DISPERSIONE AC TRMS CON PINZA HT96U (ILEAK)

| Portata | Campo         | Risoluzione | Incertezza (*)    | Protezione da sovraccarichi             |
| :------ | :------------ | :---------- | :---------------- | :-------------------------------------- |
| 1A      | 0.0 ÷ 99.9mA  | 0.1mA       | ±(3%lettura+3 cifre) | Un terminale di misura collegato a terra |
|         | 100 ÷ 1000mA  | 1mA         |                   |                                         |
| 100.0 A | 0.0 ÷ 100.0A  | 0.1A        |                   |                                         |
| 1000A   | 0 ÷ 1000A     | 1A          |                   |                                         |

*   (*) Incertezza del solo strumento senza pinza
*   Campo tensione di ingresso: 0 ÷ 1VAC
*   Resistenza di ingresso: 1MΩ
*   Campo frequenza: 40Hz ÷ 723Hz (in accordo a IEC/EN61557-13)
*   Tipo pinza: HT96U (campi di misura 1A, 100A, 1000A)
*   Valore limite (campo 1000mA): 0.1 ÷ 99.9mA, 100 ÷ 1000mA selezionabile
*   Valore limite (campo 100.0A): 0.1 ÷ 100.0A selezionabile
*   Valore limite (campo 1000A): 1 ÷ 1000A selezionabile

### CORRENTE DI DISPERSIONE AC TRMS SU PRESA (ILEAK)

| Campo         | Risoluzione | Incertezza         | Protezione da sovraccarichi |
| :------------ | :---------- | :----------------- | :-------------------------- |
| 0.25 ÷ 49.99 mA | 0.01 mA     | ±(3%lettura + 3cifre) | CAT II 300V                 |
| 0.05 ÷ 0.99 A   | 0,01 A      |                    |                             |
| 1.0 ÷ 10.0 A    | 0.1 A       |                    |                             |

*   Influenza corrente di carico: ± 0.01mA/A
*   Valore limite: 0.25mA ÷ 10.00A (valore limite standard 3.50mA)
*   Campo frequenza: 40Hz ÷ 723Hz (in accordo a IEC/EN61557-13)
*   Metodo di misura: corrente differenziale
*   Inversione polarità del cavo di rete: Si
*   Rete UUT sull'interruttore di prova: Sì (valore limite 25mA)
*   Limite fuori intervallo (IPE): Sì (misura interrotta dopo 10s al superamento dei 10A)
*   Limite fuori intervallo (IL): Sì (misura interrotta dopo 10s al superamento dei 16A)
*   Pre-test iniziale: controllo messa a terra conduttore PE della presa shuko

FULLTEST3 IT - 95

## 11.2. CARATTERISTICHE GENERALI

### ALIMENTAZIONE

*   Tensione di rete: 207 V ÷ 253 V/50/60Hz ± 5%
*   Consumo di corrente: 16Amax

### CARATTERISTICHE MECCANICHE

*   Dimensioni (L x La x H): 400 x 300 x 170mm
*   Peso: 15kg
*   Protezione meccanica: IP40

### MEMORIA E INTERFACCE DI INGRESSO/USCITA

*   Memoria interna: 999 locazioni (struttura di memoria a 3 livelli)
*   Interfaccia PC: dispositivo USB 2.0, connettore tipo “B”
*   Tastiera e stampante USB: 2 x USB 2.0 tipo connettore “A”
*   barcode, pen drive USB: 2 x USB 2.0 tipo connettore “A”
*   Requisiti pen drive USB: FAT32 con dimensione max 64GB
*   Spia luminosa attivazione test dielettrico
*   Tastiera per controllo remoto: Si
*   Tasti START/STOP/SAVE: Sì
*   Collegamento Bluetooth: Sì

### CONDIZIONI AMBIENTALI DI UTILIZZO

*   Temperatura di riferimento: 23°C ± 5°C
*   Temperatura di lavoro: 0°C ÷ 40°C
*   Umidità di riferimento: <60%RH senza condensa
*   Umidità di lavoro: <80%RH senza condensa
*   Temperatura di conservazione: -10°C ÷ 60°C
*   Umidità di conservazione: <80%RH senza condensa

### NORMATIVE DI RIFERIMENTO

*   Sicurezza strumento: IEC/EN61010-1
*   EMC: IEC/EN61326-1
*   Verifiche di sicurezza: IEC/EN60204-1; IEC/EN61439-1; IEC/EN60335-1
*   Documentazione tecnica: IEC/EN61187
*   Strumento: IEC/EN61557-1-2-3-4-6-13-14
*   Sicurezza misure dielettriche: EN50191

### VARIE

*   Display: TFT LCD colori 4.3” con touch screen
*   Avvisi: allarme ottico e acustico nel caso di valori superati
*   Isolamento: classe I (conduttore di protezione)
*   Livello di inquinamento: 2
*   Categoria di misura: CAT II 300V (potenza), CAT III 300V (altri test)
*   Max altitudine di utilizzo: 2000m

Questo strumento è conforme ai requisiti della Direttiva Europea sulla bassa tensione 2014/35/EU (LVD) e della direttiva EMC 2014/30/EU

Questo strumento è conforme ai requisiti della direttiva europea 2011/65/CE (RoHS) e della direttiva europea 2012/19/CE (WEEE)

## 11.3. ACCESSORI

Vedere packing list allegata.

FULLTEST3 IT - 96

# 12. ASSISTENZA

## 12.1. CONDIZIONI DI GARANZIA

Questo strumento è garantito contro ogni difetto di materiale e fabbricazione, in conformità con le condizioni generali di vendita. Durante il periodo di garanzia il costruttore si riserva il diritto di riparare ovvero sostituire il prodotto. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell'invio dello strumento. Per la spedizione usare solo l'imballaggio originale. Ogni danno causato dall'utilizzo di imballaggi non originali verrà addebitato al Cliente. Il costruttore declina ogni responsabilità per danni causati a persone o oggetti. Accessori (non coperti da garanzia)
La garanzia non è applicata nei seguenti casi:

*   Riparazioni che si rendono necessarie a causa di un errato utilizzo dello strumento (compreso l'adattamento ad applicazioni particolari non previste nel presente manuale) o del suo utilizzo con apparecchiature non compatibili.
*   Riparazioni che si rendono necessarie a causa di un imballaggio non adeguato.
*   Riparazioni che si rendono necessarie a causa di interventi eseguiti da personale non autorizzato.
*   Modifiche apportate allo strumento senza esplicita autorizzazione del costruttore.
*   Il contenuto del presente manuale non può essere riprodotto in alcuna forma senza l'autorizzazione del costruttore.

I nostri prodotti sono brevettati e i marchi depositati. Il costruttore si riserva il diritto di apportare modifiche alle specifiche ed ai prezzi se ciò è dovuto a miglioramenti tecnologici.

## 12.2. ASSISTENZA

Se lo strumento non funziona correttamente, prima di contattare il Servizio di Assistenza, controllare lo stato della batteria e dei cavi e sostituirli se necessario. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell'invio dello strumento. Per la spedizione usare solo l'imballaggio originale. Ogni danno causato dall'utilizzo di imballaggi non originali verrà addebitato al Cliente. Il costruttore declina ogni responsabilità per danni causati a persone o oggetti. Il costruttore si riserva il diritto di apportare modifiche alle specifiche ed ai prezzi se ciò è dovuto a miglioramenti tecnologici.

**HT ITALIA SRL**
Via della Boaria, 40
48018 – Faenza (RA) – Italy
T +39 0546 621002 | F +39 0546 621144
M info@ht-instrumnents.com | www.ht-instruments.it

**HT INSTRUMENTS SL**
C/ Legalitat, 89
08024 Barcelona – Spain
T + 34 93 408 17 77 | F +34 93 408 36 30
M info@htinstruments.es | www.ht-instruments.com/es-es/

**HT INSTRUMENTS GmbH**
Am Waldfriedhof 1b
D-41352 Korschenbroich – Germany
T +49 (0) 2161 564 581 | F +49 (0) 2161 564 583
M info@htinstruments.de | www.ht-instruments.de

**WHERE WE ARE**
