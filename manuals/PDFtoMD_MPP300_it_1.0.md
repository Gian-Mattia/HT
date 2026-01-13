# MPP300

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-28 -->
# INDICE
1.  [PRECAUZIONI E MISURE DI SICUREZZA](#1-precauzioni-e-misure-di-sicurezza)
    1.1. [Istruzioni preliminari](#11-istruzioni-preliminari)
    1.2. [Durante l’utilizzo](#12-durante-lutilizzo)
    1.3. [Dopo l’utilizzo](#13-dopo-lutilizzo)
    1.4. [Definizione di categoria di misura (sovratensione)](#14-definizione-di-categoria-di-misura-sovratensione)
2.  [DESCRIZIONE GENERALE](#2-descrizione-generale)
    2.1. [Introduzione](#21-introduzione)
    2.2. [Funzionalità dello strumento](#22-funzionalità-dello-strumento)
3.  [PREPARAZIONE ALL’UTILIZZO](#3-preparazione-allutilizzo)
    3.1. [Controlli iniziali](#31-controlli-iniziali)
    3.2. [Alimentazione dello strumento](#32-alimentazione-dello-strumento)
    3.3. [Conservazione](#33-conservazione)
4.  [NOMENCLATURA](#4-nomenclatura)
    4.1. [Descrizione dello strumento](#41-descrizione-dello-strumento)
    4.2. [Descrizione LED Indicatori](#42-descrizione-led-indicatori)
    4.3. [Strumento MASTER](#43-strumento-master)
        4.3.1. [Visualizzazione stato MPP300 tramite strumenti MASTER di Tipo 1](#431-visualizzazione-stato-mpp300-tramite-strumenti-master-di-tipo-1)
        4.3.2. [Visualizzazione stato MPP300 tramite strumenti MASTER di Tipo 2](#432-visualizzazione-stato-mpp300-tramite-strumenti-master-di-tipo-2)
5.  [PROGRAMMAZIONE STRUMENTI MASTER](#5-programmazione-strumenti-master)
    5.1. [Strumenti MASTER di TIPO 1 – IMPOSTAZIONE UNITA REMOTA](#51-strumenti-master-di-tipo-1--impostazione-unita-remota)
    5.2. [Strumenti MASTER di TIPO 2 – IMPOSTAZIONE UNITA REMOTA](#52-strumenti-master-di-tipo-2--impostazione-unita-remota)
6.  [ISTRUZIONI OPERATIVE](#6-istruzioni-operative)
    6.1. [Collaudo Impianti FV per strumenti di Tipo 1 (SOLAR I-V)](#61-collaudo-impianti-fv-per-strumenti-di-tipo-1-solar-i-v)
        6.1.1. [Collaudo impianti FV con Inverter Mono/Multi MPPT - Uscita AC mono/trifase](#611-collaudo-impianti-fv-con-inverter-monomulti-mppt---uscita-ac-monotrifase)
    6.2. [Collaudo Impianti FV per strumenti di Tipo 2 (SOLAR300N)](#62-collaudo-impianti-fv-per-strumenti-di-tipo-2-solar300n)
        6.2.1. [Collaudo Impianti FV con Inverter Mono/Multi MPPT - Uscita AC mono/trifase](#621-collaudo-impianti-fv-con-inverter-monomulti-mppt---uscita-ac-monotrifase)
7.  [MANUTENZIONE](#7-manutenzione)
    7.1. [Generalità](#71-generalità)
    7.2. [Stato delle batterie interne ricaricabili](#72-stato-delle-batterie-interne-ricaricabili)
    7.3. [Pulizia dello strumento](#73-pulizia-dello-strumento)
    7.4. [Fine vita](#74-fine-vita)
8.  [SPECIFICHE TECNICHE](#8-specifiche-tecniche)
    8.1. [Caratteristiche tecniche collaudo impianti FV](#81-caratteristiche-tecniche-collaudo-impianti-fv)
    8.2. [Norme di riferimento](#82-norme-di-riferimento)
    8.3. [Caratteristiche generali](#83-caratteristiche-generali)
    8.4. [Condizioni ambientali di utilizzo](#84-condizioni-ambientali-di-utilizzo)
    8.5. [Accessori](#85-accessori)
9.  [APPENDICE – CENNI TEORICI](#9-appendice--cenni-teorici)
    9.1. [Collaudo degli impianti FV](#91-collaudo-degli-impianti-fv)
    9.2. [Cenni su MPPT (Maximum Power Point Tracker)](#92-cenni-su-mppt-maximum-power-point-tracker)
10. [ASSISTENZA](#10-assistenza)
    10.1. [Condizioni di garanzia](#101-condizioni-di-garanzia)
    10.2. [Assistenza](#102-assistenza)

---

# 1. PRECAUZIONI E MISURE DI SICUREZZA

Lo strumento è stato progettato in conformità alla direttiva IEC/EN61010-1 relativa agli strumenti di misura elettronici. Prima e durante l’esecuzione delle misure attenersi alle seguenti indicazioni e leggere con particolare attenzione tutte le note precedute dal simbolo

> **ATTENZIONE**
> Qualora lo strumento fosse utilizzato in modo diverso da quanto specificato nel presente manuale d’uso, le protezioni per esso previste potrebbero essere compromesse

*   Non effettuare misure di tensione o corrente in ambienti umidi
*   Non effettuare misure in presenza di gas o materiali esplosivi, combustibili o in ambienti polverosi
*   Evitare contatti con il circuito in esame se non si stanno effettuando misure
*   Evitare contatti con parti metalliche esposte, con terminali di misura inutilizzati, circuiti, ecc
*   Non effettuare alcuna misura qualora si riscontrino anomalie nello strumento come, deformazioni, rotture, fuoriuscite di sostanze, assenza di visualizzazione sul display, ecc
*   Prestare particolare attenzione quando si effettuano misure di tensioni superiori a 20V in quanto è presente il rischio di shock elettrici
*   Utilizzare solo gli accessori originali

Nel presente manuale e sullo strumento sono utilizzati i seguenti simboli:

*   **Attenzione:** attenersi alle istruzioni riportate nel manuale; un uso improprio potrebbe causare danni allo strumento o ai suoi componenti
*   **Pericolo alta tensione:** rischi di shock elettrici
*   **Doppio isolamento**
*   **Tensione o corrente DC**
*   **Tensione o corrente AC**
*   **Riferimento di terra**

## 1.1. ISTRUZIONI PRELIMINARI

*   Questo strumento è stato progettato per l’utilizzo in un ambiente con livello di inquinamento 2 ed in condizioni ambientali specificate al § 8.4. Non operare in condizioni ambientali differenti
*   La invitiamo a seguire le normali regole di sicurezza orientate alla protezione dell’operatore contro correnti pericolose e lo strumento contro un utilizzo errato
*   Lo strumento può essere utilizzato per misure di **TENSIONE** in CAT III 1000V DC o CAT IV 300V AC verso terra. Non operare su circuiti che superino i limiti specificati al § 8.1
*   Lo strumento può essere utilizzato per misure di **CORRENTE** tramite trasduttori a pinza esterni
*   Solo gli accessori originali garantiscono gli standard di sicurezza. Essi devono essere in buone condizioni e sostituiti, se necessario, con modelli identici
*   Prima di collegare i cavi di misura al circuito in esame, controllare che lo strumento sia stato correttamente impostato

## 1.2. DURANTE L’UTILIZZO

La preghiamo di leggere attentamente le raccomandazioni e le istruzioni seguenti:

> **ATTENZIONE**
> *   La mancata osservazione delle avvertenze e/o istruzioni può danneggiare lo **strumento** e/o i suoi componenti o essere fonte di pericolo per l’operatore
> *   Il LED “POWER“ rosso intermittente indica che le batterie interne ricaricabili sono quasi scariche. In questo connettere l’alimentatore esterno in accordo a quanto descritto nel § 7.2
> *   I connettori di ingresso dello strumento IDC1, IDC2, IDC3 sono del tipo a 4 poli. Utilizzare solo pinze con connettore a 4 poli o interporre l’adattatore ACON3F4M fra il connettore della pinza e l’ingresso dello strumento.
> *   Lo strumento è in grado di mantenere i dati memorizzati anche in condizioni di batterie scariche
> *   Il dispositivo presenta particolare suscettibilità alle ESD in prossimità e sulla porta USB mentre è operativo, si consiglia la connessione della cavetteria alla presa USB ad apparecchio spento

## 1.3. DOPO L’UTILIZZO

Quando le misure sono terminate, spegnere lo strumento mantenendo premuto il tasto ON/OFF per alcuni secondi. Se si prevede di non utilizzare lo strumento per un lungo periodo attenersi a quanto specificato nel § 3.3

## 1.4. DEFINIZIONE DI CATEGORIA DI MISURA (SOVRATENSIONE)

La norma "IEC/EN61010-1: Prescrizioni di sicurezza per apparecchi elettrici di misura, controllo e per utilizzo in laboratorio, Parte 1: Prescrizioni generali", definisce cosa si intenda per categoria di misura, comunemente chiamata categoria di sovratensione. Al § 6.7.4: Circuiti di misura, essa recita:

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

Gentile Cliente, La ringraziamo per aver scelto uno strumento del nostro programma di vendita. Lo strumento da Lei appena acquistato, se utilizzato secondo quanto descritto nel presente manuale, Le garantirà misure accurate ed affidabili. Lo strumento è realizzato in modo da offrire la massima sicurezza grazie ad uno sviluppo di nuova concezione che assicura il doppio isolamento e il raggiungimento della categoria di sovratensione CAT III 1000VDC e CAT IV 300V AC (verso Terra) Lo strumento è stato progettato come accessorio di una unità nel seguito denominata “**MASTER**” (vedere § 4.3) per potere eseguire le operazioni di collaudo su installazioni FV Monofase e Trifase in accordo alle prescrizioni della Guida CEI 82-25 L’accessorio MPP300 in abbinamento ad uno strumento MASTER è la soluzione ideale per il controllo e l’analisi di possibili problemi legati ad eventuali bassi valori di efficienza delle installazioni fotovoltaiche

## 2.2. FUNZIONALITÀ DELLO STRUMENTO

Le seguenti caratteristiche sono disponibili:

*   Misura 3 tensioni e 3 correnti DC
*   Misura potenze stringhe DC e totale DC
*   Misura 3 tensioni e 3 correnti AC TRMS
*   Misura potenza totale AC
*   Misura irraggiamento `[W/m 2]` tramite cella di riferimento connessa a unità SOLAR-02
*   Misura temperatura pannelli e ambiente tramite sonda PT300N connessa a SOLAR-02
*   Collaudo/registrazione parametri di un impianto FV con `PI` programmabile da 5s a 60min su inverter Mono/Multi MPPT, uscita Mono/Trifase
*   Memoria interna per salvataggio dati
*   Interfaccia RF/USB per trasferimento dati a strumento MASTER

# 3. PREPARAZIONE ALL’UTILIZZO

## 3.1. CONTROLLI INIZIALI

Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili affinché lo strumento potesse essere consegnato senza danni. Tuttavia si consiglia di controllarlo per accertare eventuali danni subiti durante il trasporto. Qualora si dovessero riscontrare anomalie contattare immediatamente il rivenditore. Si consiglia inoltre di controllare che l’imballaggio contenga tutte le parti indicate al § 8.5. In caso di discrepanze contattare il rivenditore. Qualora fosse necessario restituire lo strumento si prega di seguire le istruzioni riportate al § 10.

## 3.2. ALIMENTAZIONE DELLO STRUMENTO

Lo strumento funziona con una batteria ricaricabile Li-ION (3.7V, 1900mAh) alloggiata all’interno dello strumento stesso. Utilizzare l’alimentatore esterno in dotazione per la ricarica della batteria. Per le indicazioni sullo stato della batteria vedere quanto descritto nel § 7.2
Lo strumento è in grado di mantenere i dati memorizzati anche con le batteria completamente scarica

## 3.3. CONSERVAZIONE

Per garantire misure precise, dopo un lungo periodo di permanenza in magazzino in condizioni ambientali estreme, attendere che lo strumento ritorni alle condizioni normali (vedere § 8.4)

# 4. NOMENCLATURA

## 4.1. DESCRIZIONE DELLO STRUMENTO

LEGENDA:

1.  Ingressi Tensioni DC
2.  Ingressi Correnti DC
3.  Ingressi Tensioni AC
4.  Ingressi Correnti AC
5.  LED indicatori
6.  Connettore **USB** (solo per strumenti **MASTER** Tipo 2, vedere § 4.3)
7.  Tasto **ON/OFF**
8.  Ingresso per adattatore esterno

Fig. 1: Descrizione pannello frontale dello strumento

## 4.2. DESCRIZIONE LED INDICATORI

| Nome LED | Stato               | Descrizione                                                                |
| :------- | :------------------ | :------------------------------------------------------------------------- |
| POWER    | **VERDE fisso**     | MPP300 alimentato tramite alimentatore esterno                             |
|          | **VERDE Intermittente** | MPP330 alimentato a batterie interne                                       |
|          | **ROSSO intermittente** | Batterie MPP300 quasi scariche                                             |
| STATUS   | **VERDE fisso**     | MPP300 in fase di sincronizzazione prima d’avvio registrazione             |
|          | **VERDE Intermittente** | MPP300 in fase di registrazione                                            |
|          | **ROSSO intermittente** | Memoria MPP300 esaurita                                                    |
|          | **ROSSO fisso**     | Errore interno a MPP300 (vedere § 4.3.1) e tabella dei messaggi nel manuale d’uso dello strumento MASTER |
| MASTER   | **VERDE Intermittente** | MPP300 è in collegamento con l’unità MASTER                                |
|          | **SPENTO**          | MPP300 NON è in collegamento con l’unità MASTER                            |
| REMOTE   | **VERDE Intermittente** | MPP300 è in collegamento con l’unità SOLAR-02                              |
|          | **SPENTO**          | MPP300 NON è in collegamento con l’unità SOLAR-02                          |

Tabella 1: Descrizione LED indicatori presenti su MPP300

## 4.3. STRUMENTO MASTER

MPP300 può essere controllato **solo** dai seguenti strumenti MASTER:

| Strumento MASTER | Tipo Strumento       | Firmware         | Aggiornamento Fw      |
| :--------------- | :------------------- | :--------------- | :-------------------- |
| SOLAR I-V        | 1 (collegamento RF)  | 5.02 o superiore | Eseguibile dall'utente |
| SOLAR300N        | 2 (collegamento USB) | 1.27 o superiore | Eseguibile dall'utente |

Tabella 2: Caratteristiche degli strumenti MASTER

> **ATTENZIONE**
> *   Tutti i comandi sono inviati allo strumento tramite comunicazione **radio frequenza** (**RF**) (strumento **MASTER** Tipo 1) o tramite porta **USB** (strumento MASTER tipo 2)
> *   Si raccomanda di verificare che la versione del **Firmware** presente sullo strumento **MASTER** a cui si desidera collegare MPP300 sia coerente con quanto indicato nella precedente **Tabella 2**. Tale informazione è presente nella videata iniziale visualizzata all'atto dell'accensione dello strumento MASTER. I risultati delle misure eseguite dall'MPP300 sono inviati allo strumento MASTER a cui esso è connesso e visualizzati sul display di quest'ultimo. Tutte le prove archiviate nella memoria dello strumento MASTER sono successivamente richiamabili a display e trasferibili ad un PC

### 4.3.1. Visualizzazione stato MPP300 tramite strumenti MASTER di Tipo 1

Qualora lo strumento MASTER si trovi in prossimità dell’MPP300, si possono visualizzare i parametri generali ed avere informazioni circa un’eventuale stato di errore dell’MPP300 (LED STATUS rosso fisso). Per la descrizione delle condizioni di errore consultare il manuale d’uso dello strumento MASTER.

1.  Posizionare il cursore sulla voce `CLD` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata a fianco che indica i parametri globali dell’impianto

    ```
    15/05/10   15:34:26
    PRp   -   -   -
    Irr   -   -   -   W / m 2
    Pnom   1 5 0 . 0   k W
    Tc   -   -   -   ° C
    Te   -   -   -   ° C
    Pdc   -   -   -   k W
    Pac   -   -   -   k W
    ndc   -   -   -
    nac   -   -   -
      G O   p e r   A v v i a r e
    Selezione   M P P
    ```

2.  Premere il tasto `ENTER`. Lo strumento mostra le opzioni: `Stato MPP`, `Par. Impianto` e `Imp. Strumento`
3.  Usare i tasti freccia (``, ``) per selezionare la voce “`Stato MPP`” e confermare con `ENTER`. Lo strumento mostra la videata a lato con indicati i principali parametri generali dello strumento

    ```
    15/05/10   15:34:26
    Alimentazione   Batt
    Batteria   In   uso
    Carica   9 9 %
    Connessione   Solar   SI
    Versione   1 . 0 1
    SN   1 1 0 1 0 0 3 0
    Stato MPP
    Par . Impianto
    Imp   .   Strumento
    Selezione   M E N U
    ```

### 4.3.2. Visualizzazione stato MPP300 tramite strumenti MASTER di Tipo 2

Qualora lo strumento MASTER si trovi in collegamento con l’MPP300 tramite il cavo USB, si possono visualizzare i parametri generali ed avere informazioni circa un’eventuale stato di errore dell’MPP300 (LED STATUS rosso fisso). Per la descrizione delle condizioni di errore consultare il manuale d’uso dello strumento MASTER. Nel `MENU GENERALE` selezionare il pulsante “`Informazioni Strumento`” e premere il tasto `ENTER`. Lo strumento presenta la videata seguente:

```
12/09/2006 – 16:55:10
INFORMAZIONI STRUMENTO
Modello: MPP300
SN: xxxxxxxx
Hw: xx
Fw: 1.xx
```

Premere il tasto `ESC` (o la smart icon `[icona]`) per tornare alla videata del MENU GENERALE.

# 5. PROGRAMMAZIONE STRUMENTI MASTER

Le istruzioni sono date in base alla tipologia di strumenti classificati secondo la Tabella 2. Nel seguito è fornita una descrizione minima delle impostazioni dello strumento MASTER per uso in abbinamento a MPP300. Per la descrizione completa dei comandi e funzionalità dello strumento MASTER si veda il manuale d’uso dello strumento stesso

## 5.1. STRUMENTI MASTER DI TIPO 1 – IMPOSTAZIONE UNITA REMOTA

Accendere lo strumento, premere il tasto `MENU`, posizionare il cursore sulla voce `SET` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`. A display appare la videata che elenca le varie impostazioni dello strumento.

1.  Posizionare il cursore sulla voce `Unità Remota` utilizzando i tasti freccia (``, ``) e confermare con `ENTER`
2.  Nel parametro “`Unità r.`” impostare `MPP300`
3.  Premere `SAVE` per confermare

    ```
    15/05/10   15:34:26
    Unità   r . C L D :      M P P 3 0 0   
    Unità   r .   I - V :   N O
    S e n s .   :      3 1 . 0      m V / k W / m 2
    A l p h a   :   0 . 0 6 0   % / ° C
    S A V E   p e r   s a l v a r e
    I M P O S T
    ```

## 5.2. STRUMENTI MASTER DI TIPO 2 – IMPOSTAZIONE UNITA REMOTA

Nel `MENU GENERALE` selezionare il pulsante `IMPOSTAZIONE ANALIZZATORE`, premere il tasto `F2` o toccare la voce “`AVANZATE`” a display. Lo strumento presenta una delle seguenti videate:

Selezione U. rem. SOLAR-01
Selezione U. rem. SOLAR-02
Selezione U. remota MPP300

1.  Usando i tasti `F3` o `F4` (oppure le voci `MOD(+)` o `MOD(-)` a display) selezionare l’unità remota `MPP300`

    > **ATTENZIONE**
    > La selezione dell’unità remota `MPP300` comporta la disabilitazione del campo “Piranometro” in quanto la sensibilità della sonda di irraggiamento utilizzata (piranometro o cella di riferimento) è programmabile sull’unità SOLAR-02 (vedere manuale d’uso unità SOLAR-02). La selezione del tipo di sistema MPP-1 o MPP-3 forzerà automaticamente MPP300 come tipo di unità remota.

2.  Premere i tasti `SAVE` o `ENTER` (o la smart icon `[icona]`) per salvare l’impostazione selezionata confermando con “Ok”. Le impostazioni effettuate rimarranno in tal caso valide anche dopo lo spegnimento dello strumento
3.  Per abbandonare le modifiche effettuate o per uscire senza salvare, premere il tasto `ESC` (o la smart icon `[icona]`)

# 6. ISTRUZIONI OPERATIVE

Nel seguito verrà fornita una descrizione minima dell’utilizzo di MPP300 in abbinamento allo strumento MASTER. Per la descrizione completa dei comandi e funzionalità dello strumento MASTER consultare il manuale d’uso dello stesso. Per semplicità si adotterà nel seguito il termine “**stringa**” anche se spesso il termine “**campo fotovoltaico**” sarebbe più opportuno. Dal punto vista dello strumento la gestione di una sola stringa o di più stringhe in parallelo fra loro (campo fotovoltaico) è identica. Si indicherà inoltre con l’acronimo **MPPT** (Multiple Power Point Tracker) la caratteristica del convertitore DC/AC (inverter) in grado di massimizzare la potenza DC prelevabile dal campo fotovoltaico e con l’acronimo **PRp** il Perfomance ratio (valutato sulla base delle potenza attive). Vedere il § 9.2 per ulteriori dettagli

> **ATTENZIONE**
> Ai fini della valutazione del solo **PRp**, la misura delle grandezze DC (tensione e corrente) NON è strettamente necessaria. E’ viceversa necessaria se si desidera valutare anche le prestazione della sezione fotovoltaica (`ndc`) e della sezione di conversione DC/AC (`nac`)

## 6.1. COLLAUDO IMPIANTI FV PER STRUMENTI DI TIPO 1 (SOLAR I-V)

### 6.1.1. Collaudo impianti FV con Inverter Mono/Multi MPPT - Uscita AC mono/trifase

Lo strumento `SOLAR I-V` abbinato alle unità remote `SOLAR-02` e `MPP300` consente di eseguire collaudi su installazioni FV caratterizzate da 1 o più stringhe (aventi lo stesso orientamento ed inclinazione) ed uscita Monofase o Trifase. L’unità remota `MPP300` è in grado di comunicare con il `SOLAR I-V` (per la gestione delle operazioni di sincronizzazione e scaricamento dei dati) e con l’unità remota `SOLAR-02` (dedicata alla registrazione dei valori di Irraggiamento e temperatura) attraverso un collegamento wireless a radiofrequenza (`RF`) attivo fino ad una distanza massima di circa **1m** tra di esse

Fig. 2: Collegamento dell’MPP300 per collaudo di un impianto FV Monofase

Fig. 3: Collegamento dell’MPP300 per collaudo di un impianto FV Trifase

> **ATTENZIONE**
> *   Quando il `SOLAR I-V` è impostato in modo da utilizzare `MPP300` come unità remota tutti i collegamenti relativi a grandezze elettriche (tensioni e correnti) vanno eseguiti sull’unità `MPP300`. Il `SOLAR I-V` non deve avere **nessuna tensione o corrente** collegata a propri ingressi
> *   La massima tensione per gli ingressi di `MPP300` è **1000VDC** tra gli ingressi VDC1,VDC2, VDC3 e **600VAC** fra gli ingressi VAC1, VAC2, VAC3. Non misurare tensioni che eccedano i limiti espressi in questo manuale. Il superamento di tali limiti potrebbe causare shock elettrici all’utilizzatore e danni allo strumento
> *   Per garantire la sicurezza dell’operatore, durante la fase dei collegamenti mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter)

1.  Controllare ed eventualmente impostare sul `SOLAR-02` la sensibilità della cella di riferimento coerentemente con il tipo di moduli FV che si andrà ad esaminare (vedere manuale d’uso del `SOLAR-02`)
2.  Si raccomanda di eseguire una valutazione preliminare del valore dell’Irraggiamento sul piano dei moduli FV in esame tramite l’unità `SOLAR-02` (in funzionamento indipendente) e la cella di riferimento. Si ricorda che in accordo alla Guida CEI 82-25 l’irraggiamento minimo per eseguire una verifica di efficienza su un impianto fotovoltaico è pari a `600W/m 2`
3.  Accendere il `SOLAR I-V` e controllare ed eventualmente modificare le impostazioni relativamente al tipo di unità remota, alla soglia minima di irraggiamento, al fondo scala delle pinze AC e DC, al periodo di integrazione e i parametri del sistema in esame (vedere Manuale d’uso del `SOLAR I-V`)
4.  Per garantire la sicurezza dell’operatore mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter)
5.  Avvicinare fra loro (max 1 m circa) il `SOLAR I-V`, il `SOLAR-02` e l’unità `MPP300`. **Tutti gli strumenti devono essere accesi** (vedere i manuali d’uso di `SOLAR-2` e `MPP300` per ulteriori dettagli)
6.  Su `SOLAR I-V` premere il tasto `MENU`, selezionare la funzione `CLD` e premere `ENTER` ed attendere che le tre unità inizino a comunicare fra loro. Questa condizione è evidenziata dalla presenza simultanea dei seguenti indicatori:
    *   Simbolo `[icona]` fisso (non intermittente) sul display del `SOLAR I-V`
    *   Simbolo `[icona]` fisso (non intermittente) sul display del `SOLAR-02`
    *   Lampeggio verde dei LED `MASTER` e `REMOTE` sull’unità `MPP300`
7.  Collegare gli ingressi `VDC1(+)` e `VDC1(-)` dell’unità `MPP300` ai terminali di uscita della stringa rispettando le polarità ed i colori indicati in Fig. 2 o Fig. 3
8.  Ripetere l’operazione indicata al punto sopra per altri eventuali inseguitori di potenza DC da monitorare utilizzando gli ingressi `VDC2` e `VDC3` in accordo al numero di ingressi DC impostato (vedi manuale d’uso del `SOLAR I-V`)
9.  Collegare il connettore di uscita della pinza DC all’ingresso `IDC1` dell’unità `MPP300`

    > **ATTENZIONE**
    > PRIMA DI COLLEGARE LE PINZE DC SUI CONDUTTORI Accendere la pinza, controllare il LED indicante lo stato delle batterie interne della pinza (se presenti), selezionare la portata corretta, premere il tasto `ZERO` sulla pinza DC e verificare sul display del `SOLAR I-V` l’effettivo azzeramento del valore `Idc` corrispondente (valori fino a `0.02A` sono comunque accettabili)

10. Inserire la pinza di corrente DC sul conduttore positivo in uscita dalla stringa **rispettando il verso della freccia** presente sulla pinza stessa come indicato in Fig. 2 o Fig. 3. Posizionare il toroide della pinza il più lontano possibile dall’inverter e dal conduttore negativo in uscita dalla stringa stessa
11. Ripetere le operazioni indicate ai due punti sopra per altri eventuali inseguitori di potenza DC da monitorare utilizzando gli ingressi `IDC2` e `IDC3` in accordo al numero di ingressi DC impostato (vedi manuale d’uso del `SOLAR I-V`)
12. Collegare gli ingressi `VAC1` ed `N` dell’unità `MPP300` rispettivamente ai conduttori di Fase e Neutro rispettando le polarità ed i colori indicati in Fig. 2 o Fig. 3. Nel caso di impianti trifase in cui il conduttore di Neutro non sia disponibile, collegare l’ingresso `N` a Terra
13. Nel caso di inverter con uscita Trifase (vedi manuale d’uso `SOLAR I-V`), ripetere l’operazione indicata al punto sopra per le restanti fasi utilizzando gli ingressi `VAC2` e `VAC3` dell’MPP300
14. Collegare la pinza AC sul conduttore di Fase L1 **rispettando il verso della freccia** presente sulla pinza stessa come indicato in Fig. 2. o e Fig. 3.Posizionare il toroide della pinza il più lontano possibile dall’inverter e dal conduttore Neutro. Collegare l’uscita della pinza all’ingresso `IAC1` dell’MPP300
15. Nel caso di inverter con uscita Trifase (vedi manuale d’uso `SOLAR I-V`), ripetere l’operazione indicata al punto sopra per le restanti fasi utilizzando gli ingressi `IAC2` e `IAC3` dell’MPP300
16. Rimettere nuovamente in servizio il sistema elettrico in esame
17. A display del `SOLAR I-V` saranno visualizzati i valori dei parametri elettrici **complessivi** del sistema in esame. In particolare in questa videata:
    `Pdc` = Potenza dc complessiva (somma delle potenze di stringa)
    `Pac` = Potenza ac (se monofase) o somma delle potenze ac (se trifase)

    Si consiglia di controllare che i valori dei parametri elettrici (`Pnom`, `Pdc`, `Pac`) e che il valore del rendimento ac (`ac`) siano coerenti con il sistema in esame (Esempio: `ac > 1` non è fisicamente accettabile)

    ```
    15/05/10   15:34:26
    PRp   -   -   -
    Irr   -   -   -   W / m 2
    Pnom   3 . 5 0 0   k W
    Tc   -   -   -   ° C
    Te   -   -   -   ° C
    Pdc   3 . 1 2 5   k W
    Pac   2 . 9 6 0   k W
    ndc   -   -   -
    nac   0   .   9   5
      G O   p e r   A v v i a r e
    Selezione   M P P
    ```

18. Su `SOLAR I-V` premere il tasto (``) per accedere alla seconda videata che riporta i valori dei parametri DC in uscita alle stringhe in accordo al numero di ingressi DC impostato (vedi manuale d’uso `SOLAR I-V`) In particolare in questa videata:
    `Vdcx`=Tensione dc della stringa x.
    `Idcx`=Corrente dc della stringa x.
    `Pdx` = Potenza dc della stringa x.

    Si consiglia di controllare che i valori dei parametri elettrici (`Vdc`, `Idc`, `Pdc`) e siano coerenti con il sistema in esame

    ```
    15/05/10   15:34:26
      V d c 1   4 6 0 . 1   k W
    V d c 2   4 6 1 . 4   V
    V d c 3   4 6 2 . 5   A
    I d c 1   2 . 2 5   A
    I d c 2   2 . 3 1   A
    I d c 3   2 . 2 1   A
    P d c 1   1 . 0 3 5   k W
    P d c 2   1 . 0 6 6   k W
    P d c 3   1 . 0 2 4   k W
      G O   p e r   A v v i a r e
    Selezione   M P P
    ```

19. Su `SOLAR I-V` premere il tasto (``) per accedere alla terza videata che riporta i valori dei parametri elettrici sul lato AC dell’inverter coerentemente con le impostazioni effettuate (vedi manuale d’uso del `SOLAR I-V` - monofase, trifase 4 fili) In particolare in questa videata:
    `Vacxy`=Tensione ac fra fase e Neutro (se monofase) o fra le fasi x e y (se trifase)
    `Idcx`=Corrente ac della fase x
    `Pacx` = Potenza ac della fase x

    Si consiglia di controllare che i valori dei parametri elettrici (`Vac`, `Iac`, `Pac`) e siano coerenti con il sistema

    ```
    15/05/10   15:34:26
      V a c 1 2   4 0 1 . 4   V
    V a c 2 3   4 0 1 . 1   V
    V a c 3 1   4 0 0 . 1   V
    I a c 1   4 . 2 6   A
    I a c 2   4 . 2 6   A
    I a c 3   4 . 2 7   A
    P a c 1   9 8 7   W
    P a c 2   9 8 6   W
    P a c 3   9 8 5   W
      G O   p e r   A v v i a r e
    Selezione   M P P
    ```

    Esempio di videata per sistemi FV con uscita trifase

20. Mantenendo sempre i tre strumenti in prossimità fra loro (max 1m circa), premere il tasto `GO/STOP` sul `SOLAR I-V` per attivare il collaudo. Conseguentemente:
    *   Sul display di `SOLAR I-V` appare il messaggio “`reg. in attesa`”
    *   Sul display di `SOLAR-02` appare il messaggio “`HOLD`” e l’indicazione del tempo in secondi rimanenti prima dell’avvio registrazione
    *   Su `MPP300` si accende in verde (non lampeggiante) il LED `STATUS`

    ```
    15/05/10   15:34:26
    PRp   -   -   -
    Irr   -   -   -   W / m 2
    Pnom   3 . 5 0 0   k W
    Tc   -   -   -   ° C
    Te   -   -   -   ° C
    Pdc   3 . 1 2 5   k W
    Pac   2 . 9 6 0   k W
    ndc   -   -   -
    nac   0   .   9   5
      r e g .   i n   a t t e s a
    Selezione   M P P
    ```

21. Al raggiungimento dell’istante ”00” successivo alla pressione del tasto `GO/STOP` il collaudo ha inizio e le tre unità sono tra loro sincronizzate. In tali condizioni:
    *   Sul display di `SOLAR I-V` appare il messaggio “`reg. in corso`”
    *   Sul display di `SOLAR-02` appare il messaggio “`Recording…`”
    *   Su `MPP300` si lampeggia in verde il LED `STATUS`

    ```
    15/05/10   15:35:00
    PRp   -   -   -
    Irr   -   -   -   W / m 2
    Pnom   3 . 5 0 0   k W
    Tc   -   -   -   ° C
    Te   -   -   -   ° C
    Pdc   3 . 1 2 5   k W
    Pac   2 . 9 6 0   k W
    ndc   -   -   -
    nac   0   .   9   5
    r e g .   i n   c o r s o
    Selezione   M P P
    ```

22. In qualunque momento sarà possibile analizzare lo stato attuale della registrazione tramite pressione del tasto `MENU`. Verranno visualizzati:
    *   data ed ora di inizio registrazione
    *   Il valore impostato del periodo di integrazione
    *   Il numero di Periodi trascorsi dall’inizio registrazione
    *   La capacità di memoria residua di registrazione

    Premere il tasto `ESC` per uscire dalla videata

    ```
    15/05/10   15:35:00
    Start  1 4 / 0 2 / 0 0   1 7 : 1 8 : 0 0
    Periodo :   5 s
    Numero   IP   6 1
    Autonomia   0 d   1 h
    Reg. in corso
    r e g .   i n   c o r s o
    Selezione   M P P
    ```

23. A questo punto è possibile portare l’unità `SOLAR-02` in prossimità delle stringhe FV per effettuare le misure di irraggiamento e temperatura tramite le rispettive sonde. Quando la distanza tra l’unità `SOLAR-02` e `MPP 300` è tale da non consentire il collegamento RF, sul display del `SOLAR-02`, il simbolo “`[icona]`” lampeggia per circa 30s poi scompare. L’unità `MPP300` resta invece sempre in ricerca del collegamento RF con l’unità `SOLAR-02`
24. Posizionare la cella di riferimento sul piano dei moduli FV. Fare riferimento al relativo manuale d’uso per un corretto montaggio
25. Posizionare il sensore di temperatura a contatto con il retro del pannello fissandolo con nastro e evitando di toccarlo con le dita (azione che potrebbe falsare la misura)
26. Attendere qualche secondo per consentire alle sonde di raggiungere una misura stabile e poi collegare la sonda di Irraggiamento all’ingresso `PYRA/CELL` e la sonda di temperatura all’ingresso `TEMP` dell’unità `SOLAR-02`
27. Attendere il messaggio “`READY`” a display del `SOLAR-02` ad indicare che l’unità ha rilevato dei dati con Irraggiamento solare > soglia minima impostata (vedere manuale `SOLAR I-V`)
28. Con messaggio “`READY`” a display attendere per circa 1 minuto in modo da raccogliere un certo numero di campioni
29. Scollegare le sonde di Irraggiamento e temperatura dall’unità `SOLAR-02`, e avvicinarla all’unità `MPP300`. Avvicinare inoltre l’unità principale `SOLAR I-V` all’`MPP300`. Le tre unità deve essere vicine fra loro (max 1m)
30. L’unità principale `SOLAR I-V` deve essere in modalità `CLD`, se è assente il simbolo “`[icona]`” lampeggiante, premere il tasto `` per riattivare la ricerca del collegamento RF
31. Premere il tasto `` sul `SOLAR-02` per riattivare il collegamento RF. Conseguentemente sull’unità principale verrà visualizzato il messaggio “`connessione radio attiva`”
32. Per arrestare il collaudo premere il tasto `GO/STOP` sullo strumento `SOLAR I-V` e confermare con `ENTER` alla richiesta di arresto della registrazione
33. Sul display del `SOLAR I-V` sarà visualizzato il messaggio Il messaggio “`SCARICO DATI`” ad indicare il trasferimento dei dati verso l’unità principale nelle sue varie fasi
34. Dopo la fase automatica di trasferimento dati, sullo strumento saranno automaticamente visualizzati i valori di massima prestazione. Nella barra del titolo della finestra sarà visualizzato:
    *   `ESITO SI`: se esiste almeno 1 valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
    *   `ESITO NO`: se NON esiste nessun valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
    *   `Impossibile effettuare l’analisi`: se l’irraggiamento non ha mai raggiunto un valore alla soglia minima impostata oppure se non esiste nessun valore valido durante tutto l’arco della registrazione (PRp > 1.15)
    *   Non visualizzerà nessun esito (SI o NO) se se lo strumento è stato impostato con correzione di temperatura tipo “`nDC`” (v. manuale d’uso `SOLAR I-V`)
35. Premere `SAVE` per salvare i risultati ottenuti o `ESC` per uscire dalla videata dei risultati e tornare alla videata iniziale

    ```
    15/05/10   15:35:00
      P R p   0   .   8 2
    I r r   9   7   1   W / m 2
    P n o m   3 . 5 0 0   k W
    T c   4 5 .   1   ° C
    T e   3 0   . 5   ° C
    P d c   3 . 1 2 5   k W
    P a c   2 . 9 6 0   k W
    n d c   0 . 8 6
    n a c   0   .   9   5
    E S I T O   S I
    Selezione   C L D
    ```

## 6.2. COLLAUDO IMPIANTI FV PER STRUMENTI DI TIPO 2 (SOLAR300N)

### 6.2.1. Collaudo Impianti FV con Inverter Mono/Multi MPPT - Uscita AC mono/trifase

Lo strumento `SOLAR300N` abbinato alle unità remote `SOLAR-02` e `MPP300` (opzionale) consente di eseguire collaudi su installazioni FV caratterizzate da 1 o più campi FV (aventi lo stesso orientamento ed inclinazione) ciascuno connesso ad un MPPT dell’inverter (vedere § 9.2) ed uscita Monofase o Trifase. L’unità remota `MPP300` è in grado di comunicare con il `SOLAR300N` tramite cavo `USB` (per la gestione delle operazioni di sincronizzazione e scaricamento dei dati) e con l’unità remota `SOLAR-02` (dedicata alla registrazione dei valori di Irraggiamento e temperatura) attraverso un collegamento wireless a radiofrequenza (`RF`) attivo fino ad una distanza massima di circa **1m** tra di esse.

Fig. 4: Collegamento dell’MPP300 per collaudo di un impianto FV Monofase

Fig. 5: Collegamento dell’MPP300 per collaudo di un impianto FV Trifase

> **ATTENZIONE**
> *   Quando il `SOLAR300N` è impostato in modo da utilizzare `MPP300` come unità remota TUTTI i collegamenti relativi a grandezze elettriche (Tensioni e correnti) vanno eseguiti sull’unità `MPP300`. Il `SOLAR300N` non deve avere **nessuna tensione o corrente** collegata a propri ingressi.
> *   La massima tensione per gli ingressi di `MPP300` è **1000VDC** tra gli ingressi VDC1,VDC2, VDC3 e **600VAC** fra gli ingressi VAC1, VAC2, VAC3. Non misurare tensioni che eccedano i limiti espressi in questo manuale. Il superamento di tali limiti potrebbe causare shock elettrici all’utilizzatore e danni allo strumento
> *   Per garantire la sicurezza dell’operatore, durante la fase dei collegamenti mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter).

1.  Controllare ed eventualmente impostare sul `SOLAR-02` la sensibilità della cella di riferimento coerentemente con il tipo di moduli FV che si andrà ad esaminare (vedere manuale d’uso del `SOLAR-02`).
2.  Si raccomanda di eseguire una valutazione preliminare del valore dell’Irraggiamento sul piano dei moduli FV in esame tramite l’unità `SOLAR-02` (in funzionamento indipendente) e la cella di riferimento. Si ricorda che in accordo alla Guida CEI 82-25 l’irraggiamento minimo per eseguire una verifica di efficienza su un impianto fotovoltaico è pari a `600W/m 2`
3.  Accendere il `SOLAR300N` e controllare ed eventualmente modificare le impostazioni relativamente al tipo di unità remota, alla soglia minima di irraggiamento, al fondo scala delle pinze AC e DC e i parametri del sistema in esame (vedere manuale d’uso `SOLAR300N`).
4.  Per garantire la sicurezza dell’operatore mettere fuori servizio il sistema in esame agendo sugli interruttori/sezionatori a monte ed a valle del convertitore DC/AC (inverter).
5.  Collegare prima il `SOLAR300N` all’unità `MPP300` tramite il cavo USB e quindi avvicinare fra loro (max 1 m circa) il `SOLAR-02` e l’unità `MPP300`. **Tutti gli strumenti devono essere accesi** (vedere i manuali d’uso di `SOLAR-2` e `MPP300` per ulteriori dettagli). Sul display del `SOLAR300N` deve venire visualizzato (per 5 secondi) il messaggio “`Connesso MPP300`”.
6.  Su `SOLAR300N` accedere al `MENU GENERALE`, selezionare la funzione `Visualizzazione Misure` e premere `ENTER` ed attendere che le tre unità inizino a comunicare fra loro. Questa condizione è evidenziata dalla presenza simultanea dei seguenti indicatori:
    a. Simbolo `[icona]` fisso (non intermittente) sul display del `SOLAR-02`
    b. Lampeggio verde dei LED `MASTER` e `REMOTE` sull’unità `MPP300`
7.  Collegare gli ingressi `VDC1(+)` e `VDC1(-)` dell’unità `MPP300` ai terminali di uscita della stringa rispettando le polarità ed i colori indicati in Fig. 2 o Fig. 3
8.  Ripetere l’operazione indicata al punto sopra per altri eventuali inseguitori di potenza DC da monitorare utilizzando gli ingressi `VDC2` e `VDC3` in accordo al numero di ingressi DC impostato (vedere manuale d’uso `SOLAR300N`). Collegare il connettore di uscita della pinza DC all’ingresso `IDC1` dell’unità `MPP300`.
9.  Collegare il connettore di uscita della pinza DC all’ingresso `IDC1` dell’unità `MPP300`.

    > **ATTENZIONE**
    > PRIMA DI COLLEGARE LE PINZE DC SUI CONDUTTORI Accendere la pinza, controllare il LED indicante lo stato delle batterie interne della pinza (se presenti), selezionare la portata corretta, premere il tasto `ZERO` sulla pinza DC e verificare sul display del `SOLAR300N` l’effettivo azzeramento del valore `Idc` corrispondente (valori fino a `0.02A` sono comunque accettabili).

10. Inserire la pinza di corrente DC sul conduttore positivo in uscita dalla stringa **rispettando il verso della freccia** presente sulla pinza stessa come indicato in Fig. 2 o Fig. 3. Posizionare il toroide della pinza il più lontano possibile dall’inverter e dal conduttore negativo in uscita dalla stringa stessa.
11. Ripetere le operazioni indicate ai due punti sopra per altri eventuali inseguitori di potenza DC da monitorare utilizzando gli ingressi `IDC2` e `IDC3` in accordo al numero di ingressi DC impostato (vedere manuale d’uso `SOLAR300N`).
12. Collegare gli ingressi `VAC1` ed `N` dell’unità `MPP300` rispettivamente ai conduttori di Fase e Neutro rispettando le polarità ed i colori indicati in Fig. 2 o Fig. 3. Nel caso di impianti trifase in cui il conduttore di Neutro non sia disponibile, collegare l’ingresso `N` a Terra.
13. Nel caso di inverter con uscita Trifase (vedere manuale d’uso `SOLAR300N`), ripetere l’operazione indicata al punto sopra per le restanti fasi utilizzando gli ingressi `VAC2` e `VAC3` dell’`MPP300`.
14. Collegare la pinza AC sul conduttore di Fase L1 **rispettando il verso della freccia** presente sulla pinza stessa come indicato in Fig. 2. o e Fig. 3.Posizionare il toroide della pinza il più lontano possibile dall’inverter e dal conduttore Neutro. Collegare l’uscita della pinza all’ingresso `IAC1` dell’`MPP300`.
15. Nel caso di inverter con uscita Trifase (vedere manuale d’uso `SOLAR300N`), ripetere l’operazione indicata al punto sopra per le restanti fasi utilizzando gli ingressi `IAC2` e `IAC3` dell’`MPP300`.
16. Rimettere nuovamente in servizio il sistema elettrico in esame.
17. A display del `SOLAR300N` saranno visualizzati i valori dei parametri elettrici **complessivi** del sistema in esame. In particolare in questa videata:
    `Pdc` = Potenza dc complessiva (somma delle potenze di stringa)
    `Pac` = Potenza ac (se monofase) o somma delle potenze ac (se trifase)

    Si consiglia di controllare che i valori dei parametri elettrici (`Pnom`, `Pdc`, `Pac`) e che il valore del rendimento ac (`ac`) siano coerenti con il sistema in esame (Esempio: `ac > 1` non è fisicamente accettabile).

18. Su `SOLAR300N` premere il tasto `F3` per accedere alla **seconda videata** che riporta i valori dei parametri DC in uscita alle stringhe in accordo al numero di ingressi DC impostato (vedere manuale d’uso `SOLAR300N`). In particolare in questa videata:
    `Vdcx`=Tensione dc della stringa x.
    `Idcx`=Corrente dc della stringa x.
    `Pdx` = Potenza dc della stringa x.

    Si consiglia di controllare che i valori dei parametri elettrici (`Vdc`, `Idc`, `Pdc`) e siano coerenti con il sistema in esame.

    Esempio di videata DC per sistemi FV con 3 MPPT

19. Su `SOLAR300N` premere il tasto `F4` per accedere alla terza videata che riporta i valori dei parametri elettrici sul lato AC dell’inverter coerentemente con le impostazioni effettuate (vedere manuale d’uso `SOLAR300N` - monofase, trifase 4 fili). In particolare in questa videata:
    `Vacxy`=Tensione ac fra fase e Neutro (se monofase) o fra le fasi x e y (se trifase)
    `Iacx`=Corrente ac della fase x
    `Pacx` = Potenza ac della fase x

    Si consiglia di controllare che i valori dei parametri elettrici (`Vac`, `Iac`, `Pac`) e siano coerenti con il sistema.

    Esempio di videata AC per sistemi FV con uscita trifase

20. Mantenendo sempre i tre strumenti in collegamento, premere il tasto `F1` sul `SOLAR300N` per avviare il collaudo. Conseguentemente:
    a. Sul display di `SOLAR300N` apparirà l’icona `[icona]`.
    b. Sul display di `SOLAR-02` appare il messaggio “`HOLD`” e l’indicazione del tempo in secondi rimanenti prima dell’avvio registrazione
    c. Su `MPP300` si accende in verde (non lampeggiante) il LED `STATUS`
21. Al raggiungimento dell’istante ”00” successivo alla pressione del tasto `F1` il collaudo ha inizio e le tre unità sono tra loro sincronizzate. In tali condizioni:
    a. Sul display di `SOLAR300N` appare l’icona `[icona]`.
    b. Sul display di `SOLAR-02` appare il messaggio “`Recording…`”
    c. Su `MPP300` si lampeggia in verde il LED `STATUS`
22. In qualunque momento della registrazione sarà possibile analizzare lo stato attuale della stessa selezionando nel `MENU GENERALE` il pulsante `Gestione Dati memorizzati`.Verranno visualizzati:
    a. data ed ora di inizio registrazione
    b. Il valore impostato del periodo di integrazione
    c. Il numero di Periodi trascorsi dall’inizio registrazione
    d. La capacità di memoria residua di registrazione.

    Premere il tasto `ESC` per uscire dalla videata

23. A questo punto è possibile portare l’unità `SOLAR-02` in prossimità delle stringhe FV per effettuare le misure di irraggiamento e temperatura tramite le rispettive sonde. Quando la distanza tra l’unità `SOLAR-02` e `MPP 300` è tale da non consentire il collegamento RF, sul display del `SOLAR-02`, il simbolo “`[icona]`” lampeggia per circa 30s poi scompare. L’unità `MPP300` resta invece sempre in ricerca del collegamento RF con l’unità `SOLAR-02`.
24. Posizionare la cella di riferimento sul piano dei moduli FV. Fare riferimento al relativo manuale d’uso per un corretto montaggio
25. Posizionare il sensore di temperatura a contatto con il retro del modulo fissandolo con nastro e evitando di toccarlo con le dita (azione che potrebbe falsare la misura).
26. Attendere qualche secondo per consentire alle sonde di raggiungere una misura stabile e poi collegare la sonda di Irraggiamento all’ingresso `PYRA/CELL` e la sonda di temperatura all’ingresso `TEMP` dell’unità `SOLAR-02`
27. Attendere il messaggio “`READY`” a display del `SOLAR-02` ad indicare che l’unità ha rilevato dei dati con Irraggiamento solare > soglia minima impostata (vedere manuale d’uso `SOLAR300N`)
28. Con messaggio “`READY`” a display attendere per circa 1 minuto in modo da raccogliere un numero significativo di campioni
29. Scollegare le sonde di Irraggiamento e temperatura dall’unità `SOLAR-02`, e avvicinarla all’unità `MPP300`. Le due unità deve essere vicine fra loro (max 1m).
30. Ricollegare (se era stata scollegata) l’unità `SOLAR300N` all’`MPP300`. Il LED `MASTER` deve essere lampeggiante ad indicar il collegamento fra `SOLAR300N` e `MPP300`.
31. Premere il tasto `` sul `SOLAR-02` per riattivare il collegamento RF. Conseguentemente sull’unità `MPP300` il LED `REMOTE` inizierà a lampeggiare.
32. Per arrestare il collaudo premere il tasto `F1` sullo strumento `SOLAR300N` e confermare con `ENTER` alla richiesta di arresto della registrazione
33. Sul display del `SOLAR300N` saranno visualizzati vari messaggi indicativi delle varie fasi del trasferimento dei dati verso l’unità principale.
34. Dopo la fase automatica di trasferimento dati, sullo strumento saranno automaticamente visualizzati i valori di massima prestazione. Nella barra del titolo della finestra sarà visualizzato:
    *   `ESITO SI`: se esiste almeno 1 valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
    *   `ESITO NO`: se NON esiste nessun valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
    *   `Impossibile effettuare l’analisi`: se l’irraggiamento non ha mai raggiunto un valore stabile superiore alla soglia minima impostata oppure se non esiste nessun valore valido durante tutto l’arco della registrazione (PRp > 1.15).
    *   Non visualizzerà nessun esito (SI o NO) se se lo strumento è stato impostato con correzione di temperatura tipo “`nDC`” (vedere manuale d’uso `SOLAR300N`).
35. Premere `SAVE` per salvare i risultati ottenuti. La pressione del tasto comporterà la visualizzazione della `tastiera virtuale` per l’inserimento di eventuali commenti. L’ulteriore pressione del tasto `SAVE` archivierà la misura ed i commenti inseriti e tornerà alla maschera iniziale pronto per un nuovo rilievo.

Esempio di esito in abbinamento a MPP300

# 7. MANUTENZIONE

## 7.1. GENERALITÀ

Lo strumento da Lei acquistato è uno strumento di precisione. Durante l’utilizzo e l’immagazzinamento rispettare le raccomandazioni elencate in questo manuale per evitare possibili danni o pericoli durante l’utilizzo. Non utilizzare lo strumento in ambienti caratterizzati da elevato tasso di umidità o temperatura elevata. Non esporre direttamente alla luce del sole. Spegnere sempre lo strumento dopo l’utilizzo.

## 7.2. STATO DELLE BATTERIE INTERNE RICARICABILI

Lo stato del LED POWER fornisce indicazioni circa lo stato di funzionamento/carica delle batterie ricaricabili interne allo strumento

*   **POWER**:
    *   **VERDE fisso**: MPP300 alimentato tramite alimentatore esterno
    *   **VERDE Intermittente**: MPP330 alimentato a batterie interne
    *   **ROSSO intermittente**: Batterie MPP300 quasi scariche

> **ATTENZIONE**
> *   Qualora il LED status indichi la condizione di batterie quasi scariche è opportuno collegare allo strumento l’alimentatore esterno fornito in dotazione. Non è necessario interrompere le eventuali prove in corso per connettere l’alimentatore
> *   Se lo strumento rileva una tensione di batteria troppo bassa, arresta le eventuali registrazioni incorso e si spegne
> *   Lo strumento è in grado di mantenere i dati memorizzati anche in condizioni di batterie scariche

## 7.3. PULIZIA DELLO STRUMENTO

Per la pulizia dello strumento utilizzare un panno morbido e asciutto. Non usare mai panni umidi, solventi, acqua, ecc

## 7.4. FINE VITA

> **ATTENZIONE**: il simbolo riportato indica che l'apparecchiatura, i suoi accessori e le batterie interne devono essere raccolti separatamente e trattati in modo corretto

# 8. SPECIFICHE TECNICHE

## 8.1. CARATTERISTICHE TECNICHE COLLAUDO IMPIANTI FV

L’incertezza è indicata come `[%lettura + (num. cifre) * risoluzione]` a 23°C ± 5°C, <80%HR

**Tensione DC**

| Campo [V]        | Risoluzione [V] | Incertezza                  |
| :--------------- | :-------------- | :-------------------------- |
| 10.0 `` 999.9   | 0.1             | ` (0.5 % lettura + 2cifre)` |

**Tensione AC TRMS Fase - Neutro**

| Campo [V]        | Frequenza            | Risoluzione [V] | Incertezza                  |
| :--------------- | :------------------- | :-------------- | :-------------------------- |
| 10.0 `` 300.0   | 42.5 `` 69.0Hz      | 0.1             | ` (0.5 % lettura + 2cifre)` |

Max fattore di cresta: 1,5

**Tensione AC TRMS Fase - Fase**

| Campo [V]        | Frequenza            | Risoluzione [V] | Incertezza                  |
| :--------------- | :------------------- | :-------------- | :-------------------------- |
| 50.0 `` 594.0   | 42.5 `` 69.0Hz      | 0.1             | ` (0.7 % lettura + 2cifre)` |

Max fattore di cresta: 1,5

**Corrente DC (tramite trasduttore a pinza esterno)**

| Campo                | Risoluzione | Incertezza                     | Protezione contro i sovraccarichi |
| :------------------- | :---------- | :----------------------------- | :-------------------------------- |
| 5.0mV `` 319.9mV    | 0.1mV       | ` (0.5 % lettura+ 0.06%FS)`   | 10V                               |
| 320.0mV `` 999.9mV  |             | ` (0.5 % lettura)`            |                                   |

Valore di corrente corrispondenti ad una tensione < 5mV vengono azzerati

**Corrente AC TRMS (tramite trasduttore a pinza esterno tipo STD)**

| Campo                 | Frequenza           | Risoluzione | Incertezza                     | Protezione contro sovraccarichi |
| :-------------------- | :------------------ | :---------- | :----------------------------- | :------------------------------ |
| 5.0mV `` 219.9mV     | 42.5 `` 69.0Hz     | 0.1mV       | ` (0.5 % lettura+ 0.06%FS)`   | 10V                             |
| 220.0mV `` 999.9mV   |                     |             | ` (0.5 % lettura)`            |                                 |

Fattore di Cresta <= 1.5 .Valore di corrente corrispondenti ad una tensione < 5mV vengono azzerati.

**Corrente AC TRMS (tramite trasduttore a pinza esterno tipo FLEX 8.5uV/A – FS 100A)**

| Campo                 | Frequenza           | Risoluzione | Incertezza                     | Protezione contro sovraccarichi |
| :-------------------- | :------------------ | :---------- | :----------------------------- | :------------------------------ |
| 0.008 `` 8.50mV      | 42.5 `` 69.0Hz     | 0.001mV     | ` (0.5%lettura+ 7cifre)`      | 10V                             |

Fattore di Cresta <= 1.5 .Valore di corrente < 1A vengono azzerati.

**Corrente AC TRMS (tramite trasduttore a pinza esterno tipo FLEX 8.5uV/A – FS 1000A)**

| Campo                 | Frequenza           | Risoluzione | Incertezza                       | Protezione contro sovraccarichi |
| :-------------------- | :------------------ | :---------- | :------------------------------- | :------------------------------ |
| 0.085 `` 85.0mV      | 42.5 `` 69.0Hz     | 0.01mV      | ` (0.5%lettura + 15cifre)`      | 10V                             |

Fattore di Cresta <= 1.5 .Valore di corrente < 5A vengono azzerati.

**Potenza DC (Vmis > 150V) ; Potenza AC (Vmis > 200V, PF=1)**

| FS pinza [A]   | Campo [W]                  | Risoluzione [W] | Incertezza                                      |
| :------------- | :------------------------- | :-------------- | :---------------------------------------------- |
| 1< FS `` 10   | 0.000k `` 9.999k          | 0.001k          | ` (0.7 % lettura + 3 cifre) (Imis < 10%FS)`  |
|                | 10.00k `` 99.99k          | 0.01k           |                                                 |
| 10< FS `` 100 | 0.00k `` 99.99k           | 0.01k           | ` (0.7 % lettura) (Imis %geq% 10%FS)`          |
|                | 100.0k `` 999.9k          | 0.1k            |                                                 |
| 100< FS `` 1000 | 0.0k `` 999.9k          | 0.1k            |                                                 |
|                | 1000k `` 9999k          | 1k              |                                                 |

Vmis = tensione a cui è misura la potenza ; Imis = corrente misurata

## 8.2. NORME DI RIFERIMENTO

*   **Sicurezza strumento**: IEC/EN61010-1
*   **Sicurezza accessori di misura**: IEC/EN61010-031
*   **Documentazione tecnica**: IEC/EN61187
*   **Misure**: Guida CEI 82-25 – Variante V1
*   **Isolamento**: doppio isolamento
*   **Protezione meccanica**: IP 40
*   **Grado di inquinamento**: 2
*   **Categoria di misura**: CAT III 1000V DC, Max 1000V tra gli ingressi DC CAT IV 300V AC verso terra, Max 600V tra gli ingr. AC

## 8.3. CARATTERISTICHE GENERALI

**Memoria**

*   Capacità di memoria: 2Mbyte
*   Periodo di integrazione: 5,10,30,60,120,300,600,900,1800,3600s
*   Autonomia (in abb. a SOLAR-02): circa 1.5 ore (`@ PI = 5s`) circa 8 gg (`@ PI = 600s`)

**Caratteristiche modulo radio**

*   Campo di frequenza: 2.400 `` 2.4835GHz
*   Categoria R&TTE: Classe 1
*   Potenza max di trasmissione: 30 ``W
*   Distanza max collegamento RF: 1m

**Alimentazione**

*   Alimentazione interna: Batteria interna ricaricabile Li-ION (3.7V, 1900mAh) Autonomia >3 ore
*   Alimentazione esterna: Alimentatore AC/DC100 `` 240VAC / 50-60Hz – 5VDC

**Caratteristiche meccaniche**

*   Dimensioni (L x La x H): 300 x 265 x 140mm
*   Peso (batterie incluse): 1.2kg

## 8.4. CONDIZIONI AMBIENTALI DI UTILIZZO

*   Temperatura di riferimento: 23°C ± 5°C
*   Temperatura di utilizzo: 0°C ÷ 40°C
*   Umidità relativa ammessa: <80%RH
*   Temperatura di conservazione: -10°C ÷ 60°C
*   Umidità di immagazzinamento: <80%RH
*   Max altitudine di utilizzo: 2000m (*)

> **ATTENZIONE**
> (*) Prescrizioni per uso dello strumento ad altitudini comprese tra 2000 e 5000m
>
> Lo strumento, relativamente agli ingressi è da considerarsi declassato a categoria di sovratensione CAT II 1000V DC e CAT III 300V verso Terra max 1000V tra gli ingressi AC. Le marcature e i simboli riportati sullo strumento sono da considerarsi valide solo con uso dello strumento ad altitudine <2000m
>
> Questo strumento è conforme ai requisiti della Direttiva Europea sulla bassa tensione 2014/35/EU (LVD) e della direttiva EMC 2014/30/EU
>
> Questo strumento è conforme ai requisiti della direttiva europea 2011/65/EU (RoHS) e della direttiva europea 2012/19/EU (WEEE)

## 8.5. ACCESSORI

Vedere packing list allegata

# 9. APPENDICE – CENNI TEORICI

## 9.1. COLLAUDO DEGLI IMPIANTI FV

In accordo con quanto previsto dalla normativa vigente, l’esito del collaudo su una installazione FV monofase sarà funzione del tipo di correzione adottato per compensare gli effetti della temperatura e della relazione matematica utilizzata per calcolare il `PRp` (vedere impostazioni strumento MASTER)

| Corr. | Valore di Tcel                                                     | Relazione matematica per calcolo PRp                                       | Norma      | Esito    |
| :---- | :----------------------------------------------------------------- | :------------------------------------------------------------------------- | :--------- | :------- |
| Tmod  | Tcel = Valore della Temp. moduli misurata                          | `PRp = (Pca / (P STC * (G p / G STC))) * (Rfv)`                            | CEI 82-25  | OK/NO    |
| Tamb o Tenv | Tcel = Val. della Temp. moduli calcolata : `Tcel = Tamb + ((G p / 800) * (NOCT - 20))` | `PRp = (Pca / (P STC * (G p / G STC))) * (Rfv)`                            |            |          |
| nDC   | Tcel = Valore della Temperatura moduli misurata                    | `PRp = (Pca / P n) * (1 + ( / 100) * (Tcel - 25)) * (G STC / G p)`      | \-         | \-       |

dove:

| Simbolo  | Descrizione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | U.di misura           |
| :------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------- |
| `G p`    | Irraggiamento misurato sul piano dei moduli                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | `[W/m 2]`             |
| `G STC`  | Irraggiamento in condizione Standard = 1000                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | `[W/m 2]`             |
| `P n`    | Potenza nominale = somma delle Pmax dei moduli FV facenti parte della sezione dell’impianto in esame                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | `[kW]`                |
| `P inv`  | Potenza nominale della tipologia dell’inverter facente parte della sezione dell’impianto in esame                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | `[kW]`                |
| `P ca`   | Potenza in ca complessiva misurata all’uscita del/degli inverter facenti parti della sezione dell’impianto in esame                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | `[kW]`                |
| `Rfv`    | Coefficiente correttivo funzione della Temperatura delle Celle FV (Tcel) misurata o calcolata in accordo al tipo di relazione di correzione selezionata `Rfv = { 1 se (Tcel <= 40 °C) ; (1 - (Tcel - 40) / 100) se (Tcel > 40 °C) }`                                                                                                                                                                                                                                                                                                                                                                                                                                 | `[icona]`             |
| ``      | Valore assoluto del coef. Termico della Pmax dei moduli FV facenti parte della sezione dell’impianto in esame.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | `[%/°C]`              |
| `NOCT`   | (Normal Operating Cell Temperature) = Temperatura a cui si portano le celle in condizioni di rif (800W/m 2, 20°C, AM=1.5, vel. Aria =1m/s).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | `[%/°C]`              |

In generale l’esito potrà essere:

*   `Impossibile effettuare l’analisi`: se l’irraggiamento non ha mai raggiunto un valore stabile (vedere manuale d’uso strumento Master) superiore alla soglia minima impostata oppure se non esiste nessun valore valido durante tutto l’arco della registrazione (PRp > 1.15).
*   `ESITO SI` (correz. “Tmod” o “Tamb”): se esiste almeno 1 valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
*   `ESITO NO` (correz. “Tmod” o “Tamb”): se NON esiste nessun valore fra quelli rilevati che soddisfa le relazioni imposte dalla normativa vigente
*   Non visualizzerà nessun esito (SI o NO) se se lo strumento è stato impostato con correzione di temperatura tipo “`nDC`” (manuale d’uso strumento MASTER).

**Esito visualizzato SI (correz. “Tmod” o “Tamb”)**

Lo strumento fornisce un esito complessivo positivo in accordo alla Guida CEI 82-25, se, nell’insieme dei campioni rilevati durante il collaudo, ne esiste almeno uno **valido** per cui sono soddisfatte le seguenti relazioni:

`PRp = (Pca / (P STC * (G p / G STC))) * (Rfv)`
`PRp >= { 0.78 se P inv <= 20kW ; 0.80 se P inv > 20kW }`

(per il significato delle definizioni e dei simboli si veda il paragrafo precedente) Se esistono più campioni che soddisfano tutte le condizioni precedenti, lo strumento visualizza automaticamente quello corrispondente al massimo valore di PRp

**Esito visualizzato NO (correz. “Tmod” o “Tamb”)**

Lo strumento fornisce un esito complessivo negativo in accordo alla Guida CEI 82-25, se, nell’insieme dei campioni rilevati durante il collaudo, NON ne esiste nemmeno uno **valido** per cui sono soddisfatte le seguenti relazioni:

`PRp = (Pca / (P STC * (G p / G STC))) * (Rfv)`
`PRp >= { 0.78 se P inv <= 20kW ; 0.80 se P inv > 20kW }`

(per il significato delle definizioni e dei simboli si veda il paragrafo precedente) In questo caso lo strumento visualizza comunque i valori corrispondenti al massimo valore di PRp raggiunto.

**Nessun esito (correzione “nDC”)**

Lo strumento fornisce come risultato i valori corrispondenti al punto di massimo PRp calcolato come:

`PRp = (Pca / P n) * (1 + ( / 100) * (Tcel - 25)) * (G STC / G p)`

(per il significato delle definizioni e dei simboli si veda il paragrafo precedente)

## 9.2. CENNI SU MPPT (MAXIMUM POWER POINT TRACKER)

L’irraggiamento solare su una superficie quale può essere quelle di un impianto fotovoltaico ha caratteristiche fortemente variabili, essendo dipendente dalla posizione del sole rispetto a detta superficie e dalle caratteristiche dell’atmosfera (tipicamente dalla presenza di nuvole). Un modulo fotovoltaico presenta, per vari valori dell’irraggiamento solare, e per vari valori della temperatura, una famiglia di curve caratteristiche del tipo indicato nelle seguente figura. In particolare in essa sono rappresentate tre curve `I-V` (in grassetto) corrispondenti a tre valori (1000, 800, 600W/m2) di irraggiamento solare.

(Figure 1 is referenced here but not provided in the text chunk.)

Su ogni curva caratteristica esiste uno ed un solo punto tale per cui è massimizzato il trasferimento di potenza verso un ipotetico carico alimentato dal modulo fotovoltaico. Il punto di massima potenza corrisponde alla coppia tensione-corrente tale per cui è massimo il prodotto `V*I`, dove V è il valore della tensione ai morsetti del modulo e I è la corrente che circola nel circuito ottenuto chiudendo il modulo su un ipotetico carico. Sempre con riferimento alla figura precedente, il prodotto `V*I` è rappresentato per i tre valori dell’irraggiamento solare di cui sopra, tramite le tre curve a tratto più sottile. Come si vede, in accordo con quanto detto precedentemente tali curve esibiscono un solo massimo (ex: per 1000W/m2, il punto di massima potenza corrisponde ad un valore di tensione pari a circa 36V e corrente di circa 5.5A). Chiaramente, se si riesce a massimizzare la potenza erogata dall'impianto, si riesce a sfruttarlo al meglio, sia che questo sia connesso alla rete, sia stand-alone. L’ `MPPT` è un dispositivo integrato negli inverter che, tipicamente, ad ogni istante legge i valori di tensione e corrente, ne calcola il prodotto (cioè la potenza in Watt) e, provocando piccole variazioni nei parametri di conversione (duty cycle), è in grado di stabilire per confronto se il modulo fotovoltaico sta lavorando in condizioni di massima potenza oppure no. A seconda del “responso” agisce ancora sul circuito per portare l’impianto in tale condizione ottimale. Il motivo per cui gli MPPT sono utilizzati è semplice: un impianto fotovoltaico senza MPPT può funzionare comunque, ma a parità di irraggiamento solare fornisce meno energia.

# 10. ASSISTENZA

## 10.1. CONDIZIONI DI GARANZIA

Questo strumento è garantito contro ogni difetto di materiale e fabbricazione, in conformità con le condizioni generali di vendita. Durante il periodo di garanzia, le parti difettose possono essere sostituite, ma il costruttore si riserva il diritto di riparare ovvero sostituire il prodotto. Qualora lo strumento debba essere restituito al servizio post - vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballo originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente. Il costruttore declina ogni responsabilità per danni causati a persone o oggetti. La garanzia non è applicata nei seguenti casi:

*   Riparazione e/o sostituzione accessori (non coperti da garanzia)
*   Riparazioni che si rendono necessarie a causa di un errato utilizzo dello strumento o del suo utilizzo con apparecchiature non compatibili
*   Riparazioni che si rendono necessarie a causa di un imballaggio non adeguato
*   Riparazioni che si rendono necessarie a causa di interventi eseguiti da personale non autorizzato
*   Modifiche apportate allo strumento senza esplicita autorizzazione del costruttore
*   Utilizzo non contemplato nelle specifiche dello strumento o nel manuale d’uso

Il contenuto del presente manuale non può essere riprodotto in alcuna forma senza l’autorizzazione del costruttore

I nostri prodotti sono brevettati e i marchi depositati. Il costruttore si riserva il diritto di apportare modifiche alle specifiche ed ai prezzi se ciò è dovuto a miglioramenti tecnologici.

## 10.2. ASSISTENZA

Se lo strumento non funziona correttamente, prima di contattare il servizio di assistenza, controllare lo stato della batteria e dei cavi. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballaggio originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente