# EASYTEST

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-22 -->
```markdown
EASYTEST HT5040 Manuale d’uso

EASYTEST
Indice:
1. INTRODUZIONE
2. ELENCO DELLE FUNZIONI ESEGUIBILI CON LO STRUMENTO
3. RIFERIMENTI NORMATIVI
4. CARATTERISTICHE TECNICHE
    4.1.Funzioni
    4.2.Caratteristiche generali
5. DESCRIZIONE DELLO STRUMENTO
    5.1.Pannello frontale
    5.2.Lato connessioni
    5.3.Lato inferiore dello strumento
    5.4.Accessori in dotazione
    5.5.Accessori opzionali fornibili a richiesta
6. ISTRUZIONI PER L'USO
    6.1.Procedure di misura
        6.1.1.Prova continuità dei conduttori di protezione o equipotenziali
        6.1.2.Misura delle resistenze di terra a due o tre fili
        6.1.3.Misure della resistività del terreno
        6.1.4.Misura della resistenza di isolamento di impianti elettrici con tensione di 250V,500V o 1000V
        6.1.5.Impedenza linea/anello tra fase e neutro Z PN , conduttori bifase Z PP o tra fase e conduttore di protezione Z PE e calcolo della corrente di corto circuito I K
        6.1.6.Senso ciclico delle fasi
        6.1.7.Misura del tempo di intervento t ∆ di interruttori differenziali standard, selettivi, tensione di contatto U B e resistenza di terra R E mediante corrente di prova alternata o a impulsi
        6.1.8.Misura della corrente AC mediante la pinza
    6.2.Comandi memoria
    6.3.Comunicazione RS232
    6.4.Lingua di stampa, selezione
    6.5.Reset dello strumento
    6.6.Sostituzione batterie
    6.7.Sostituzione fusibile
    6.8.Simboli e messaggi sul display

# 1. INTRODUZIONE

Lo strumento portatile a microprocessore EASYTEST HT5040 è in grado di verificare i più comuni parametri di impianti elettrici con tensione standard di 230/400V. È caratterizzato da un’estrema semplicità d’uso e da un’ampia scelta di funzioni di misura. È dotato di circa 500 locazioni di memoria per salvare i risultati delle verifiche che possono essere successivamente trasferiti ad un PC o stampati mediante uscita seriale RS232. Un’adeguata progettazione elettrica e meccanica garantisce le necessarie condizioni di sicurezza per l’operatore e per lo strumento in caso di errate inserzioni o errato collegamento alla rete indipendentemente dalla funzione selezionata. Lo strumento è alimentato da 4 batterie LR14 da 1,5V. Durante il funzionamento può essere tenuto in posizione orizzontale o verticale. Lo strumento è contenuto in una borsa insieme agli accessori di misura risultando protetto da eventuali urti durante il trasporto.

# 2. ELENCO DELLE FUNZIONI ESEGUIBILI CON LO STRUMENTO

*   `LOW Ω`: Misura della continuità a due fili di conduttori di protezione ed equipotenziali.
*   `EARTH`: Misura della resistenza di terra a due, tre e quattro fili (resistività del terreno).
*   `LINE Z / IK`
    *   Misura dell’impedenza di linea tra fase e neutro o tra conduttori di fase e calcolo della corrente di corto circuito.
    *   Misura di tensione tra fase e neutro o tra due conduttori di fase.
    *   Misura di frequenza.
*   `LOOP Z / IK`
    *   Misura dell’impedenza dell’anello di guasto tra fase e conduttore di protezione e calcolo della corrente di corto circuito. Corrente AC mediante pinza.
    *   Misura di tensione tra fase e conduttore di protezione.
    *   Misura di frequenza.
*   `RCD`
    *   Tempo di intervento t ∆ di interruttori differenziali standard e selettivi (RCD) mediante corrente di prova AC.
    *   Tensione di contatto U B di interruttori differenziali standard e selettivi.
    *   Resistenza di terra.
    *   Corrente di intervento I ∆ di interruttori differenziali standard mediante corrente di prova AC.
*   `RCD`
    *   Tempo di intervento t ∆ di interruttori differenziali standard e selettivi mediante corrente di prova pulsante.
    *   Tensione di contatto U B di interruttori differenziali standard e selettivi.
    *   Resistenza di terra.
    *   Corrente di intervento I ∆ di interruttori differenziali standard mediante corrente di prova pulsante.
*   `M Ω 250 V`: Misura della resistenza di isolamento di impianti elettrici con tensione di prova di 250V.
*   `M Ω 500 V`: Misura della resistenza di isolamento di impianti elettrici con tensione di prova di 500V.
*   `M Ω 1000 V`: Misura della resistenza di isolamento di impianti elettrici con tensione di prova di 1000V.
*   Senso ciclico delle fasi.

# 3. RIFERIMENTI NORMATIVI

*   EN 61010-1 norma di sicurezza
*   EN 50081-1 1991
*   EN 50082-1 1991 } norme EMC
*   CEI 64.8 612.3 e VDE 0413/1 .........................resistenza di isolamento
*   CEI 64.8 612.6.3 e VDE 0413/3 ..........................impedenza dell’anello/linea e corrente di corto circuito presunta
*   CEI 64.8 612.2 e VDE 0413/4 .........................continuità
*   CEI 64.8 app. D parte 61 e VDE 0413/6 ..........................parametri di differenziali
*   CEI 64.8 612.6.2 e VDE 0413/7 ..........................resistenza di terra
*   VDE 0413/9 .........................senso ciclico delle fasi

# 4. CARATTERISTICHE TECNICHE

## 4.1. Funzioni

*   Misura della continuità a due fili dei conduttori di protezione o equipotenziali `LOW Ω`

| Campo (Ω) | Risoluzione (Ω) | Precisione*         |
| :-------- | :-------------- | :------------------ |
| 0 ÷ 20    | 0,01            | ± (2% lettura + 2 cifre) |

\* Si è tenuto conto della calibrazione automatica che elimina la resistenza del cavo. La misura viene effettuata con inversione di polarità automatica e viene visualizzata la media aritmetica delle due misure.
Corrente di misura Im > 200 mA d.c. (alla tensione batteria UBAT > 5V)
Tensione a circuito aperto > 4.5V (alla tensione batteria UBAT > 5V)

*   Misura della resistenza di terra a 2 e a 3 fili e della resistività del terreno a 4 fili. `EARTH 2, 3, 4`

| Campo* (Ω) | Risoluzione (Ω) | Precisione         |
| :--------- | :-------------- | :----------------- |
| 0 ÷ 19,99  | 0,01            | ± (2% lettura + 2 cifre) |
| 20,0 ÷ 199,9 | 0,1             | ± (2% lettura + 2 cifre) |
| 200 ÷ 1999 | 1               | ± (2% lettura + 2 cifre) |

\* Selezione automatica del campo
Frequenza di misura: 125 Hz ± 1 Hz.
Corrente di misura: < 10 mA.
Tensione di misura a vuoto: < 80 Vp.
Forma della tensione di misura: onda sinusoidale.
Immunità ai disturbi: Una tensione di disturbo di 20 Vpp / 50 Hz nel circuito ha effetto max. di ± 15 cifre
Resistenza max. del circuito di corrente: Resistenza dei picchetti di corrente Rc che introduce un ulteriore errore del 3%: Rc = (4k Ω + 100RE) ≤ 50k Ω
Rc = Rc1 + Rc2 (sistema a 4 fili)
Resistenza max. del circuito di tensione: Resistenza dei picchetti di tensione Rp che introduce un ulteriore errore del 3%: Rp = (4k Ω + 100RE) ≤ 50k Ω
Rp = Rp1 + Rp2 (sistema a 4 fili)

*   Misura della resistenza di isolamento di impianti elettrici con tensione di prova di 250V `M Ω 250V`

| Campo* (M Ω) | Risoluzione (k Ω) | Precisione         |
| :----------- | :---------------- | :----------------- |
| 0 ÷ 1,999    | 1                 | ± (2% lettura + 2 cifre) |
| 2,00 ÷ 19,99 | 10                | ± (2% lettura + 2 cifre) |
| 20,0 ÷ 199,9 | 100               | ± (2% lettura + 2 cifre) |

\* Selezione automatica del campo
Tensione a vuoto: 1,3 Tensione di prova max.
Tensione di prova: 250V + 6%, -0% con carico di 250k Ω.
Corrente di corto circuito: 1,4 mA (max.).
Corrente di prova: 1 mA (min) con carico di 250k Ω.

*   Misura della resistenza di isolamento di impianti elettrici con tensione di prova di 500V `M Ω 500V`

| Campo* (M Ω) | Risoluzione (k Ω) | Precisione         |
| :----------- | :---------------- | :----------------- |
| 0 ÷ 1,999    | 1                 | ± (2% lettura + 2 cifre) |
| 2,00 ÷ 19,99 | 10                | ± (2% lettura + 2 cifre) |
| 20,0 ÷ 199,9 | 100               | ± (2% lettura + 2 cifre) |

\* Selezione automatica del campo
Tensione a vuoto: 1,3 Tensione di prova max.
Tensione di prova: 500V + 6%, -0% con carico di 230k Ω.
Corrente di corto circuito: 2,55 mA (max.).
Corrente di prova: 1 mA (min) con carico di 500k Ω.

*   Misura della resistenza di isolamento di impianti elettrici con tensione di prova di 1000V `M Ω 1000V`

| Campo* (M Ω) | Risoluzione (k Ω) | Precisione         |
| :----------- | :---------------- | :----------------- |
| 0 ÷ 1.999    | 1                 | ± (2% lettura + 2 cifre) |
| 2,00 ÷ 19,99 | 10                | ± (2% lettura + 2 cifre) |
| 20,0 ÷ 199,9 | 100               | ± (2% lettura + 2 cifre) |

\* Selezione automatica del campo
Tensione a vuoto: 1,3 Tensione di prova max.
Tensione di prova: 1000V + 6%, -0% con carico di 1000k Ω.
Corrente di corto circuito: 1,4 mA (max.).
Corrente di prova: 1 mA (min) con carico di 1000k Ω.

*   Misura del valore efficace (r.m.s.) della tensione a.c. `LINE Z/IK`; `LOOP Z/IK`

| Campo (V) | Risoluzione (V) | Precisione         |
| :-------- | :-------------- | :----------------- |
| 0 ÷ 499   | 1               | ± (2% lettura + 2 cifre) |

*   Misura di frequenza `LINE Z/IK`; `LOOP Z/IK`

| Campo (Hz) | Risoluzione (Hz) | Precisione          |
| :--------- | :--------------- | :------------------ |
| 15,3 ÷ 99,9 | 0,1              | ± (0,1% lettura + 1 cifre) |
| 100 ÷ 499  | 1                | ± (0,1% lettura + 1 cifre) |

*   Misura dell’impedenza di linea tra fase e neutro o tra conduttori di fase e calcolo della corrente di corto circuito `LINE Z/IK`

| Campo* (Ω) | Risoluzione (Ω) | Precisione**       |
| :--------- | :-------------- | :----------------- |
| 0 ÷ 19,99  | 0,01            | ± (2% lettura + 2 cifre) |
| 20,0 ÷ 199,9 | 0,1             | ± (2% lettura + 2 cifre) |
| 200 ÷ 1999 | 1               | ± (2% lettura + 2 cifre) |

\* Selezione automatica del campo
\*\* Si è tenuto conto della calibrazione automatica che elimina la resistenza del cavo.
Corrente di prova Im = 23A ± 10% (10 ms) alla tensione di rete di 230V
Calcolo della corrente di corto circuito IK:

```
I K PP = V / Z PP < V / 400 ≤ U V PP
I K PN = V / Z PN ≤ V / 230 ≤ U V PN
I K PN = V / Z PN ≤ V / 127 < U V PN
```

Precisione di IK: la stessa di ZPN
Campo di misura IK (400V): 0,20A ÷ 40,0 kA.
Campo di misura IK (230V): 0,11A ÷ 23,0 kA.
Campo di misura IK (127V): 0,06A ÷ 12,7 kA.
Risoluzione IK:
0,06 ÷ 19,99 A
20,0 ÷ 199,9 A
2,00 ÷ 19,99 kA
20,0 ÷ 199,9 kA
200 ÷ 400 kA

*   Misura dell’impedenza dell’anello di guasto tra fase e conduttori di protezione e calcolo della corrente di corto circuito `LOOP Z/IK`

| Campo* (Ω) | Risoluzione (Ω) | Precisione**       |
| :--------- | :-------------- | :----------------- |
| 0 ÷ 19,99  | 0,01            | ± (2% lettura + 2 cifre) |
| 20,0 ÷ 199,9 | 0,1             | ± (2% lettura + 2 cifre) |
| 200 ÷ 1999 | 1               | ± (2% lettura + 2 cifre) |

\* Selezione automatica del campo
\*\* Si è tenuto conto della calibrazione automatica che elimina la resistenza del cavo.
Corrente di misura Im = 23A ± 10% alla tensione di rete di 230V
Calcolo della corrente di corto circuito IK:

```
I K PE = V / Z PE ≤ V / 230 ≤ U V PE
I K PE = V / Z PE ≤ V / 127 < U V PE
```

Precisione di IK: la stessa di ZPE
Campo di misura IK (230V): 0,11A ÷ 23,0 kA
Campo di misura IK (127V): 0,06A ÷ 12,7 kA
Risoluzione IK:
0,06 ÷ 19,99 A
20,0 ÷ 199,9 A
200 ÷ 1999 A
2,00 ÷ 19,99 kA
20,0 ÷ 23,0 kA

*   Sequenza trifase: L1, L2, L3 or L2, L1, L3

*   Misura del tempo di intervento t ∆N di differenziali standard e selettivi, tensione di contatto U B e resistenza di terra R E con una corrente di prova a.c. o pulsante `RCD`; `RCD`

Tempo di intervento t ∆N:

| Campo t ∆N (ms)         | Risoluzione (ms) | Precisione         |
| :---------------------- | :--------------- | :----------------- |
| 0 ÷ 50 (5 I ∆N, RCD)    | 0,1              | ± (2% lettura + 2 ms) |
| 0 ÷ 150 (5 I ∆N, RCD S) | 0,1              | ± (2% lettura + 2 ms) |
| 0 ÷ 199,9 (2 I ∆N, )    | 0,1              | ± (2% lettura + 2 ms) |
| 0 ÷ 1999 ( I ∆N ,½ I ∆N ) | 0,1\*            | ± (2% lettura + 2 ms) |

\* Se il risultato è maggiore o uguale a 200 ms, la risoluzione è 1 ms.

Tabella dei valori efficaci (r.m.s.) (20 ms) di correnti differenziali secondo IEC 1009:

| Moltiplicatore selezionato | I ∆N (mA) | x ½ (mA) | x 1 (mA) | x 2 (mA) | x 5 (mA) |
| :------------------------- | :-------- | :------- | :------- | :------- | :------- |
|                            | 10        | 5        | 3,5      | 10       | 20.0     |
|                            | 30        | 15       | 10,5     | 30       | 60       |
|                            | 60        | 60       | 120      | 250      | 353,6    |
|                            | 100       | 50       | 35       | 100      | 200      |
|                            | 300       | 150      | 105      | 300      | 600      |
|                            | 500       | 250      | 175      | 500      | 1000     |
|                            | 1000      | 500      | 350      | 1000     | 2000     |

|                    |      |      |      | 600      | 1200  | 1500  | 2121  |
| :----------------- | :--- | :--- | :--- | :------- | :---- | :---- | :---- |
|                    |      |      |      | 1000     | 2000  | 2500  | /     |
|                    |      |      |      | 2000     | /     | /     | /     |

Precisione di correnti differenziali: ± 5%

Tensione di contatto U B :

| Campo U B (V) | Risoluzione (V) | Precisione             |
| :------------ | :-------------- | :--------------------- |
| 0 ÷ 100       | 0,01            | (+10% / -0%) ± 0,2 V |

UBlim: 25V o 50V

Le caratteristiche riportate nella suddetta tabella sono valide alle seguenti condizioni:
- la tensione di rete deve essere stabile durante la misura,
- il conduttore di protezione deve essere immune da tensioni di disturbo.

> **ATTENZIONE**
> • La misura U B viene effettuata con impulsi di corrente 0,5 I ∆N, il valore U B è calcolato alle seguenti correnti:
> Tipo standard, AC ................................................a I ∆N
> Tipo standard, A...................................................a I ∆N x 2 ( I ∆N = 10 mA) a I ∆N x 2 ( I ∆N > 10 mA)
> Tipo Selettivo, AC ...............................................a 2 x I ∆N
> Tipo Selettivo, A ..................................................a 2 x I ∆N x 2 ( I ∆N = 10 mA) a 2 x I ∆N x 2 ( I ∆N > 10 mA)

Resistenza di terra R E :

| I ∆N (mA) | Campo R E (Ω) | Risoluzione (Ω) | Precisione               |
| :-------- | :------------ | :-------------- | :----------------------- |
| 10        | 10 ÷ 10,00k   | 1               |                          |
| 30        | 3,3 ÷ 3,33k   | 0,33            |                          |
| 100       | 1 ÷ 1000      | 0,1             | + 10% - 0% ± 0,2 V / I ∆N |
| 300       | 0,33 ÷ 333    | 0,03            |                          |
| 500       | 0,2 ÷ 200     | 0,02            |                          |
| 1000      | 0,1 ÷ 100     | 0,01            |                          |

Corrente di misura: 0,5 I ∆N

*   Misura della corrente di intervento I ∆ , tempo di intervento t ∆ alla corrente di intervento e tensione di contatto U B alla corrente di intervento `RCD`; `RCD`

Corrente di intervento I ∆ :

| Campo I ∆ (mA)   | Risoluzione (mA) | Precisione     |
| :--------------- | :--------------- | :------------- |
| (0,50 ÷ 1.40) I ∆N | 0,1 I ∆N         | ± 0,15 I ∆N |

Tempo di intervento t ∆ alla corrente di intervento:

| Campo t ∆ (ms) | Risoluzione (ms) | Precisione         |
| :------------- | :--------------- | :----------------- |
| 0 ÷ 500        | 0,1\*            | ± (2% lettura + 2 ms) |

\* Se il risultato è maggiore o uguale a 200 ms, la risoluzione è 1 ms.

tensione di contatto U B alla corrente di intervento:

| Campo U B (V) | Risoluzione (V) | Precisione             |
| :------------ | :-------------- | :--------------------- |
| 0 ÷ 100       | 0,1             | +10% / -0% (di UBlim ) |

UBlim: 25V o 50V
Le caratteristiche riportate nella suddetta tabella sono valide alle seguenti condizioni:
- la tensione di rete deve essere stabile durante la misura,
- il conduttore di protezione deve essere immune da tensioni di disturbo.

*   Misura della corrente AC (misura con pinza)

Campo tensione di ingresso: 0 ÷ 200 mV, risoluzione 0,1 mV, precisione ± (2% di lettura + 2 cifre)
La lettura è tramite la pinza modello HT97 e risulta come segue:

| Campo di corrente | Posizione commutatore pinza | Risoluzione | Precisione totale             |
| :---------------- | :------------------------ | :---------- | :---------------------------- |
| 0 ÷ 200 mA        | 1000 mV/A                 | 0,1 mA      | ± (5 % di lettura + 1,2 mA); 0 ÷ 30 mA |
|                   |                           |             | ± (3% di lettura + 1,2 mA); 30 ÷ 200 mA |
| 0 ÷ 2000 mA       | 100 mV/A                  | 1 mA        | ± (2,5 % di lettura + 4 mA); 0.1 ÷ 1 A |
|                   |                           |             | ± (2,5 % di lettura + 2 mA); 1 ÷ 2 A |
| 0 ÷ 20 A          | 10 mV/A                   | 10 mA       | ± (2,5 % di lettura + 22 mA); 1 ÷ 10 A |
|                   |                           |             | ± (2,2 % di lettura + 20 mA); 10 ÷ 20 A |
| 0 ÷ 200 A         | 1 mV/A                    | 100 mA      | ± (3% di lettura + 0,4 A) |

Resistenza di ingresso voltmetro: >1 M Ω

## 4.2. Caratteristiche generali

*   Tensione di rete nominale ............................................................................ 127 / 220V, 50 Hz. 230 / 400V, 50 Hz.
*   Display ...........................................................3 1 / 2 LCD, altezza carattere 19 mm, con simboli.
*   Alimentazione ..........................................................................4 x 1,5 V IEC LR14 batterie.
*   Interfaccia RS232......................................................formato: 1 start bit, 8 data bits, 1 stop bit, no parità, baud rate 2400, X ON /X OF.
*   Dimensioni memoria....................................................................ca. 500 posizioni di memoria.
*   Dimensioni (W x H x L) ............................................................................ 220 x 85 x 230 mm.
*   Peso (comprese batterie) ............................................................................................. 1.8 kg ca.
*   Peso (set standard) ..........................................................................................................5 kg ca.
*   Protezione..................................................................................................... doppio isolamento.
*   Categoria inquinamento ........................................................................................................... 2.
*   Categoria sovratensione .......................................................................................................... II.
*   Categoria sovratensione (Solo mis. Impedenza).................................................................... III.
*   Tensione max. a terra .................................................................................................. 400 V.
*   Tensione max. tra i terminali di misura ...................................................................... 440 V.
*   Antipolvere e umidità.........................................................................................................IP 50.
*   Campo temperatura di funzionamento ........................................................................ 0 ÷ 40 0 C.
*   Campo temperatura nominale ..................................................................................... 5 ÷ 35 0 C.
*   Campo temperatura di immagazzinamento..............................................................-10 ÷ 60 0 C.
*   Umidità max. di funzionamento............................................................... 85 % UR (0 ÷ 40 0 C).
*   Umidità max. di immagazzinamento .................................................... 90 % UR (-10 ÷ 40 0 C). 80 % UR (40 ÷ 60 0 C).

# 5. DESCRIZIONE DELLO STRUMENTO

## 5.1. Pannello frontale

<!-- Fig. 1. Pannello frontale - Image not available -->

Legenda:
1. Display a cristalli liquidi.
2. Selettore funzioni.
3. Tasto `START` per esecuzione misure.
4. Tasto `DISPLAY` per visualizzare subrisultati e parametri.
5. Tasto per selezionare differenziali standard e selettivi.
6. Foro passante per cintura.
7. Tasto `I ∆N` per selezionare il valore nominale della corrente differenziale.
8. Tasto `FUNC` per selezionare:
    *   Collegamento a 2, 3 o 4 punti nella funzione `EARTH` (pos.12).
    *   Unità (mA o A) nella misura con pinza (pos.3).
    *   Tensione di contatto, tempo di intervento a ½ I ∆N, I ∆N, 2 I ∆N, 5 I ∆N, corrente di intervento o funzione AUTO in `RCD` o funzione `RCD` (pos.4 e 5).
    *   Compensazione puntali nella funzione `LOW Ω` (pos.11).
9. Tasto `PRINT` per stampare i risultati memorizzati nello strumento (attivo solo nel modo RS232 pos. 6 del selettore).
10. Tasto `SAVE` per:
    *   Salvare i risultati.
    *   Selezionare il modo di inserimento L (posizione) e P (luogo ).
    *   Incrementare il codice L o P.
11. Tasto `RCL` per:
    *   Richiamare i risultati.
    *   Ridurre il codice L o P.
12. Tasto `CLR` per cancellare i risultati memorizzati.

## 5.2. Lato connessioni

<!-- Fig. 2. Lato connessioni - Image not available -->

Legenda:
1. Pannello frontale.
2. Commutatore ON/OFF.
3. Presa banana `S` per misura della resistenza di terra.
4. Coperchio protezione connettori (9-pin connettore interfaccia RS232 sotto il Coperchio).
5. Presa banana `E/P`.
6. Presa banana `ES/PE`.
7. Presa banana `H/N`.

## 5.3. Lato inferiore dello strumento

<!-- Fig. 3. Lato inferiore dello strumento - Image not available -->

Legenda:
1. Pannello frontale.
2. Piedini in gomma.
3. Etichetta con istruzioni e avvertenze.
4. Vite di fissaggio coperchio vano batteria.
5. Coperchio vano batteria.
6. Etichetta con brevi avvertenze.

## 5.4. Accessori in dotazione

*   **Codice:** HT5040. **Articolo:** HV005040. **Descrizione:** Strumento a microprocessore per la verifica di impianti elettrici.
*   **Codice:** C2033. **Articolo:** HA002033. **Descrizione:** Cavo Spina shuko/3x cavi con spinotto protetto, nero, verde, blu 1,2m.
*   **Codice:** KIT5004F. **Articolo:** HA500410.
    *   **Descrizione:** Cavo spinotto protetto/spinotto protetto, blu 2m.
    *   **Descrizione:** Cavo spinotto protetto/spinotto protetto, nero 2m.
    *   **Descrizione:** Cavo spinotto protetto/spinotto protetto, verde 2m.
*   **Codice:** KITF IS0020. **Articolo:** HV000020. **Descrizione:** Set puntali di misura, 2x.
*   **Codice:** COC3. **Articolo:** HA000003. **Descrizione:** Set di coccodrilli protetti, 3x.
*   **Codice:** WP1984I. **Articolo:** HA198400.
    *   **Descrizione:** Borsa soffice per accessori e strumento.
    *   **Descrizione:** Manuale d'uso.
    *   **Descrizione:** Certificato di calibrazione ISO9000.
    *   **Descrizione:** Certificato di conformità.

## 5.5. Accessori opzionali fornibili a richiesta

*   **Codice:** WP1985. **Articolo:** HA198500. **Descrizione:** Borsa soffice per accessori misure di terra.
*   **Codice:** C203809. **Articolo:** HA002089.
    *   **Descrizione:** Cavo spinotto protetto/ spinotto protetto blu 30m con avvolgicavo.
    *   **Descrizione:** Cavo spinotto protetto/ spinotto protetto rosso 15m con avvolgicavo.
    *   **Descrizione:** Cavo spinotto protetto/ spinotto protetto verde 6m con avvolgicavo.
    *   **Descrizione:** Cavo spinotto protetto/ spinotto protetto nero 6m con avvolgicavo.
*   **Codice:** 4R10. **Articolo:** HA100012. **Descrizione:** Picchetti di terra, 4x.
*   **Codice:** COC4. **Articolo:** HA000004. **Descrizione:** Set di coccodrilli protetti, 4x.
*   **Codice:** EUROLINK. **Articolo:** HA000001. **Descrizione:** Programma gestione dati con cavo seriale RS232.
*   **Codice:** HT24N. **Articolo:** HA000024. **Descrizione:** Stampante portatile con cavo seriale RS232.
*   **Codice:** HT97. **Articolo:** HP000097. **Descrizione:** Pinza di corrente 1 mV/A, 1 V/A.

# 6. ISTRUZIONI PER L’USO

## 6.1. Procedure di misura

### 6.1.1. Prova continuità dei conduttori di protezione o equipotenziali `LOW Ω`

> **ATTENZIONE**
> • Prima di iniziare le misure, accertarsi che non vi sia tensione presente tra i punti in esame, in caso contrario i risultati delle prove potrebbero risultare non corretti o lo strumento potrebbe risultare danneggiato

**Compensazione puntali di misura:**
- Collegare i puntali allo strumento come indicato nella figura di seguito e metterli in corto.
<!-- Fig. 5. Collegamento - Image not available -->
- Posizionare il selettore su `LOW Ω` e premere il tasto `FUNC` ⇒ la lettera `K` (costante) sarà visualizzata.
- Premere il tasto `START`; verrà prima visualizzato un valore indipendentemente dalla compensazione e successivamente comparirà `0.00`. Lo strumento è compensato, è possibile eseguire ora una misura standard.
<!-- Fig. 6. Risultato visualizzato - Image not available -->

Lo strumento resta compensato finché le batterie si saranno scaricate o verranno sostituite. Il valore massimo che lo strumento può compensare è pari a 5 Ω, se il valore è maggiore, allora verrà rispettato 0 Ω quale valore di compensazione (strumento non compensato).

**Come eseguire la misura?**
- Collegare i puntali allo strumento o all’oggetto in esame come illustrato nella figura sopra.
- Posizionare il selettore su `LOW Ω`.
- Premere il tasto `START` ed effettuare la lettura che può essere, se necessario, salvato in memoria premendo il tasto `SAVE`.

La misura viene effettuata in due fasi (con entrambe le polarità della batteria), in cui la polarità viene invertita automaticamente. Viene visualizzata la media aritmetica di entrambi i risultati parziali.

> **ATTENZIONE**
> • Se tra i punti di misura è presente una tensione maggiore di 10V (r.m.s.), lo strumento visualizzerà quel valore e non darà luogo alcuna misura di `LOW Ω`.

### 6.1.2. Misura della resistenza di terra a due o tre fili `EARTH 2,3,4`

**Sistema a due fili:**
<!-- Fig. 7. Collegamento in caso il terminale a terra sia accessibile - Image not available -->
<!-- Fig. 8. Risultato visualizzato - Image not available -->

**Sistema a tre fili:**
<!-- Fig. 9. Collegamento standard - Image not available -->

**Come effettuare la misura?**
- Collegare i puntali allo strumento e all’oggetto in esame come illustrato in una delle due figure sopra.
- Posizionare il selettore su `EARTH 2,3,4`, viene visualizzato il numero `2`, `3` o `4` ad indicare che il sistema di misura selezionato è a 2-, 3- o 4 fili. Il sistema adeguato può essere selezionato mediante il tasto `FUNC`. L’impostazione corretta del sistema è importante solo per identificare risultati di prova corretti nel caso vengano salvati in memoria e successivamente richiamati.
- Premere il tasto `START` ed effettuare la lettura che può essere, se necessario, salvato in memoria premendo il tasto `SAVE`.

> **ATTENZIONE**
> • Se tra i punti di misura è presente una tensione maggiore di 30V (r.m.s.), lo strumento visualizzerà quel valore e non darà luogo alcuna misura di Terra.

### 6.1.3. Misura della resistività del terreno `EARTH 2,3,4`

Per progettare il sistema di protezione di terra, deve essere noto il valore della resistività del terreno. Questo è il parametro di base che consentirà al progettista di determinare le dimensioni meccaniche del sistema di terra nonché la profondità dell'impianto, motivo per cui la resistività del terreno deve essere misurata a diverse profondità. Maggiore è la distanza `a`, più profondo sarà lo strato di terreno da considerare.
<!-- Fig. 10. Collegamento - Image not available -->
<!-- Fig. 11. Risultato visualizzato - Image not available -->

Il risultato visualizzato presenta la resistenza di terra tra i terminali ES e S. Calcolare la resistenza di terra specifica (resistività del terreno) in base alla seguente formula:

```
ρ = 2 π aR E
```
R E ....risultato visualizzato

### 6.1.4. Misura della resistenza di isolamento di impianti elettrici con tensione di 250V, 500V o 1000V `M Ω 250 V`; `M Ω 500 V`; `M Ω 1000 V`

<!-- Fig. 12. Collegamento per la misura della resistenza di isolamento - Image not available -->
<!-- Fig. 13. Risultato visualizzato - Image not available -->
<!-- Fig. 14. Collegamento per la misura della resistenza di isolamento nei locali ad uso medico (peso non incluso). - Image not available -->
<!-- Fig. 15. Collegamento per la misura della resistenza di isolamento per pavimenti e pareti (pesi non inclusi). - Image not available -->

**Come effettuare la misura?**
- Collegare i puntali allo strumento e all'oggetto in esame come indicato in una delle figure sopra.
- Posizionare il selettore su `M Ω 250V`, `M Ω 500V` o `M Ω 1000V`.
- Premere il tasto `START` ed effettuare la lettura che può essere, se necessario, salvato in memoria premendo il tasto `SAVE`.

> **ATTENZIONE**
> • Se il risultato sul display non è stabile ma in continuo aumento è segno che si è in presenza di una capacità, per cui per avere un risultato esatto bisogna tenere premuto il tasto `START` finché il risultato sul display non è stabile a meno del 5%.
> • Non scollegare i puntali dall’oggetto in esame mentre la misura è in corso, poiché l’oggetto in esame resta caricato ad una tensione pericolosa.
> • La scarica dell’oggetto in esame viene effettuata automaticamente al termine della misura.

### 6.1.5. Impedenza linea/anello tra fase e neutro Z PN , conduttori bifase Z PP o tra fase e conduttore di protezione Z PE e calcolo della corrente di corto circuito I K `LINE Z/ Ik`; `LOOP Z/ Ik`

<!-- Fig. 16. Schema equivalente di un impianto - Image not available -->

Perché verificare l’impedenza della linea o dell’anello di guasto e la corrente di corto circuito presunta?
- Verificare la rispondenza dei fusibili utilizzati (corrente nominale e capacità di rottura).
- Dimensionare il sistema di protezione.
- Verificare la capacità della sorgente di potenza.
- Eliminare i cattivi contatti (la misura è effettuata mediante impulso di corrente elevata).

Perché misurare l’impedenza anziché la resistenza?
```
Impedenza Z = √(R 2 + XL 2)
Resistenza R = ...
```
(The text seems to stop here in the provided chunk for this section)
```

<!-- Chunk: Pages 23-43 -->
## EASYTEST HT5040

Se la misura viene effettuata vicino al trasformatore di potenza, o una certa induttanza è collegata in serie al trasformatore di potenza, allora la parte induttiva dell’impedenza ha già un’influenza significativa per la corrente di corto circuito presunta. Per questo motivo l’impedenza è il parametro corretto per il calcolo della corrente di corto circuito. La corrente di corto circuito viene calcolata ad una valore nominale di tensione di rete.

*   Fig. 17. Collegamento per la misura di `Z PN` o `Z PE`
*   Fig. 18. Risultato visualizzato
*   Fig. 19. Collegamento per la misura di `Z PP`, `Z PN` o `Z PE`

**Come effettuare la misura?**

1.  Collegare i puntali allo strumento o all’oggetto in esame come illustrato in una delle due figure sopra riportate.
2.  Posizionare il selettore su `LINE Z / IK` o `LOOP Z / IK` e leggere la tensione presente tra i terminali P e N (posizione LINE) o tra i terminali P ed E (posizione LOOP).
3.  Premere il tasto `DISPLAY` per controllare la frequenza della tensione di rete.
4.  Premere il tasto `START` ed effettuare la lettura che può essere, se necessario, salvato in memoria premendo il tasto `SAVE`.
5.  Premere il tasto `DISPLAY` per controllare anche la corrente di corto circuito presunta.

| U     | I K PP | I K PN | I K PE |
| :---- | :----- | :----- | :----- |
| 400 V | <      | ≤      | ≤      |
| 230 V | ≤      | ≤      | <      |
| 127 V | ≤      | <      | <      |

---

## EASYTEST HT5040 - 22 -

**ATTENZIONE** o •
*   Se il valore di tensione presente ai terminali è inferiore a 100V o maggiore di 440V premendo il tasto `START`, il valore visualizzato inizia a lampeggiare, in caso contrario viene effettuata la misura.
*   Usare solo cavi di misura originali, poiché lo strumento è stato calibrato con questi.

### 6.1.6. Senso ciclico delle fasi

La misura viene effettuata secondo le norme VDE0413 parte 9. Per determinare se il senso di rotazione è a destra o a sinistra, occorre realizzare il seguente collegamento.

*   Fig. 20. Collegamento
*   Fig. 21. Risultato visualizzato

**Come verificare il senso ciclico delle fasi?**

1.  Collegare i puntali all’impianto come illustrato sopra.
2.  Posizionare il selettore su `.
3.  Premere il tasto `START` ed effettuare la lettura che può essere, se necessario, salvato in memoria premendo il tasto `SAVE`.

Significato delle letture visualizzate:
*   `L1` - non tutte le tensioni interfase sono presenti ai terminali di prova
*   `L1.2.3` - sono presenti tutte tre le tensioni interfase, collegamento fase secondo il disegno sopra
*   `L3.2.1` - sono presenti tutte tre le tensioni interfase, collegamento fase non secondo il disegno sopra

---

## EASYTEST HT5040 - 23 -

### 6.1.7. Misura del tempo di intervento t∆ di interruttori differenziali standard o selettivi, tensione di contatto U B e R di terra R E mediante corrente di prova alternata o a impulsi RCD~ RCD…

Elenco di tutti i parametri e subparametri che possono essere provati nel selettore a due posizioni:

a) Tensione di contatto U B alla corrente nominale (tipo standard) o al doppio della corrente nominale (tipo selettivo).
*   Fig. 22. Display quando viene selezionata questa funzione
    Subparametri che possono essere controllati mediante il tasto `DISPLAY`:
    - Resistenza di terra R E.

b) Tempo di intervento t∆ a metà della corrente nominale.
*   Fig. 23. Display quando viene selezionata questa funzione
    Subparametri che possono essere controllati mediante il tasto `DISPLAY`:
    - Tensione di contatto U B alla corrente nominale (tipo standard) o al doppio della corrente nominale (tipo selettivo).
    - Resistenza di terra R E.

c) Tempo di intervento t∆ alla corrente nominale.
*   Fig. 24. Display quando viene selezionata questa funzione
    Subparametri che possono essere controllati mediante il tasto `DISPLAY`:
    - Tensione di contatto U B alla corrente nominale (tipo standard) o al doppio della corrente nominale (tipo selettivo).
    - Resistenza di terra R E.

---

## EASYTEST HT5040 - 24 -

d) Tempo di intervento t∆ al doppio della corrente nominale.
*   Fig. 25. Display quando viene selezionata questa funzione
    Subparametri che possono essere controllati mediante il tasto `DISPLAY`:
    - Tensione di contatto U B alla corrente nominale (tipo standard) o al doppio della corrente nominale (tipo selettivo).
    - Resistenza di terra R E.

e) Tempo di intervento t∆ a cinque volte la corrente nominale.
*   Fig. 26. Display quando viene selezionata questa funzione
    Subparametri che possono essere controllati mediante il tasto `DISPLAY`:
    - Tensione di contatto U B alla corrente nominale (tipo standard) o al doppio della corrente nominale (tipo selettivo).
    - Resistenza di terra R E.

f) Corrente di intervento I∆.
*   Fig. 27. Display quando viene selezionata questa funzione
    Subparametri che possono essere controllati mediante il tasto `DISPLAY`:
    - Tensione di contatto U B alla corrente nominale (tipo standard) o al doppio della corrente nominale (tipo selettivo).
    - Tempo di intervento alla corrente di intervento.

g) Prova AUTOMATICA dei differenziali. La prova consiste nelle seguenti prove parziali:
*   Fig. 28. Display quando viene selezionata questa funzione
    Subparametri che possono essere controllati mediante il tasto `DISPLAY`:
    - Tensione di contatto U B alla corrente nominale (tipo standard) o al doppio della corrente nominale (tipo selettivo).

---

## EASYTEST HT5040 - 25 -

- Tempo di intervento a 5 volte la corrente nominale, impulso di inizio positivo (fase di inizio 0 0 ).
- Tempo di intervento a 5 volte la corrente nominale, impulso di inizio negativo (fase di inizio 180 0 ).

**Come effettuare la misura della tensione di contatto U B e la resistenza di terra su sistemi TT senza far saltare il differenziale.**

1.  Collegare i puntali allo strumento ed all’impianto in esame come illustrato in una delle figure di seguito.
    *   Fig. 29. Collegamento dello strumento alla presa di corrente
    *   Fig. 30. Collegamento dello strumento all’impianto mediante cavi separati
2.  Posizionare il selettore su RCD~ o RCD….
3.  Selezionare la funzione tensione di contatto mediante tasto `FUNC` (vedi descrizione della funzione suddetta).
4.  Selezionare la corrente di prova nominale adeguata mediante il tasto `I∆N` (vedi eventuali correnti di prova al capitolo “Caratteristiche tecniche”). Selezionare la stessa corrente nominale indicata sul differenziale in esame.
5.  Selezionare il tipo selettivo (`S` visualizzato) o tipo standard (simbolo `S` cancellato) mediante il tasto `S`. Selezionare lo stesso tipo che appartiene al differenziale in esame.
6.  Premere il tasto `START` ed attendere la visualizzazione del risultato. Salvarlo in memoria se necessario premendo il tasto `SAVE`.
7.  Utilizzare il tasto `DISPLAY` per verificare i subparametri (vedi descrizione della funzione suddetta).

**ATTENZIONE** o •
*   Se la tensione presente ai terminali di misura premendo il tasto `START` è fuori dal campo 100 ÷ 250 V, il suo valore inizia a lampeggiare e non verrà effettuata alcuna misura.
*   Se la tensione di contatto visualizzata come risultato della misura è maggiore di U B lim (vedi istruzioni relative a come impostare U B lim alla fine del capitolo) comparirà il simbolo `B`.

---

## EASYTEST HT5040 - 26 -

**Come effettuare la misura del tempo di intervento t∆?**

1.  Collegare i puntali allo strumento ed all’impianto in esame come indicato in figura 29 o 30.
2.  Posizionare il selettore su RCD~ o RCD…, a seconda della forma onda indicata sul differenziale in esame.
3.  Selezionare la funzione tempo di intervento a 1/2 I∆N, I∆N, 2 I∆N o 5 I∆N, mediante il tasto `FUNC` (vedi descrizione della funzione all’inizio di questo capitolo).
4.  Selezionare la corrente di prova nominale adeguata mediante il tasto `I∆N`. Selezionare la stessa corrente nominale indicata sul differenziale in esame.
5.  Premere il tasto `START` una volta per impulso di inizio positivo (fase di inizio 0 0 ) o due volte in successione per impulso di inizio negativo (fase di inizio 180 0 ) ed attendere che venga visualizzato il risultato. Salvarlo in memoria, se necessario, premendo il tasto `SAVE`.
6.  Utilizzare il tasto `DISPLAY` per verificare i subparametri (vedi descrizione della funzione all’inizio di questo capitolo).

**ATTENZIONE** o •
*   Se la tensione presente ai terminali di misura premendo il tasto `START` è fuori dal campo 100 ÷ 250 V, il suo valore inizia a lampeggiare e non verrà effettuata alcuna misura.
*   Se si seleziona il differenziale di tipo selettivo, allora viene introdotto un ritardo di 30s tra la misura della tensione di contatto (prima parte della prova) la misura del tempo di intervento (seconda parte della prova) presentata a display come conto alla rovescia da 30 a 0.
*   Se la tensione di contatto alla corrente nominale (tipo standard) o al doppio della corrente nominale (tipo selettivo) è maggiore del valore preimpostato U B lim (vedi istruzioni relative a come impostare U B lim alla fine di questo capitolo) comparirà il simbolo `B` insieme alla tensione visualizzata e non avrà luogo alcuna misura del tempo di intervento.
*   Se il tempo di intervento visualizzato quale risultato della misura non è conforme alla tabella di seguito riportata, il risultato sarà accompagnato dal simbolo `X`.

**Tabella dei tempi di intervento massimi secondo le IEC 1009-1**

| Tipo differenziale | I∆N | 2I∆N | 5I∆N | * Note                      |
| :----------------- | :-- | :--- | :--- | :-------------------------- |
| standard           | 0,3 | 0,15 | 0,04 | tempo di intervento max.    |
| selettivo          | 0,5 | 0,2  | 0,15 | tempo di intervento max.    |
|                    | 0,13| 0,06 | 0,05 | tempo min. ritardo di intervento |

* Per valori nominali I∆N ≤ 30mA la corrente di prova a 5 volte è 0.25A.

---

## EASYTEST HT5040 - 27 -

**Come effettuare la misura della corrente di intervento I∆?**

1.  Collegare i puntali allo strumento ed all’impianto in esame come illustrato in figura 29 o 30.
2.  Posizionare il selettore su RCD~ o RCD…, a seconda della forma onda indicata sul differenziale in esame.
3.  Selezionare la funzione corrente di intervento mediante il tasto `FUNC` (vedi descrizione della funzione all’inizio di questo capitolo).
4.  Selezionare la corrente di prova nominale adeguata mediante il tasto `I∆N`. Selezionare la stessa corrente nominale indicata sul differenziale in esame.
5.  Premere il tasto `START` una volta per impulso di inizio positivo (fase di inizio 0 0 ) o due volte in successione per impulso di inizio negativo (fase di inizio 180 0 ) ed attendere che venga visualizzato il risultato. La prova inizia a 0,5 I∆N e viene incrementata a passi di 0,1 I∆N fino a 1,4 I∆N, se il differenziale non interviene prima. Salvare il risultato in memoria, se necessario, premendo il tasto `SAVE`.
6.  Utilizzare il tasto `DISPLAY` per verificare i subparametri (vedi descrizione della funzione all’inizio di questo capitolo).

**ATTENZIONE** o •
*   Se la tensione presente ai terminali di misura premendo il tasto `START` è fuori dal campo 100 ÷ 250 V, il suo valore inizia a lampeggiare e non verrà effettuata alcuna misura.
*   Il differenziale di tipo selettivo non può essere selezionato in questa funzione e vice versa.
*   Se la tensione di contatto U B alla corrente di prova reale è maggiore di U B lim (vedi istruzioni relative a come impostare U B lim alla fine di questo capitolo) allora viene visualizzata la tensione accompagnata dal simbolo `B` e la misura della corrente di intervento non inizia o viene interrotta.

---

## EASYTEST HT5040 - 28 -

**Come eseguire la funzione AUTO?**

1.  Collegare i puntali allo strumento e all’impianto in esame come illustrato in figura 29 o 30.
2.  posizionare il selettore su RCD~ o RCD…, a seconda della forma onda indicata sul differenziale in esame.
3.  Selezionare la funzione AUTO mediante il tasto `FUNC` (vedi descrizione della funzione all’inizio di questo capitolo).
4.  selezionare la corrente di prova nominale adeguata mediante il tasto `I∆N`. Selezionare la stessa corrente nominale indicata sul differenziale in esame.
5.  Premere il tasto `START`, verrà eseguita la seguente procedura:

    a) Differenziale di tipo standard
    *   (prova 1) U B /I∆N ; tempo di intervento a 1/2 I∆N, 0 0 → il differenziale non deve intervenire
    *   (prova 2) U B /I∆N ; tempo di intervento a 1/2 I∆N,180 0 → il differenziale non deve intervenire
    *   (prova 3) U B /I∆N ; tempo di intervento a I∆N, 0 0 → il differenziale deve intervenire, viene visualizzato `RCD` (lampeggiante), utilizzare il tasto `DISPLAY` per verificare i subparametri: riarmare il differenziale
    *   (prova 4) U B /I∆N ; tempo di intervento a I∆N, 180 0 → il differenziale deve intervenire, viene visualizzato `RCD` (lampeggiante), utilizzare il tasto `DISPLAY` per verificare i subparametri: riarmare il differenziale

---

## EASYTEST HT5040 - 29 -

*   (prova 5) U B /I∆N ; tempo di intervento a 5 I∆N, 0 0 → il differenziale deve intervenire, viene visualizzato `RCD` (lampeggiante), utilizzare il tasto `DISPLAY` per verificare i subparametri: riarmare il differenziale
*   (prova 6) U B /I∆N ; tempo di intervento a 5 I∆N, 180 0 → il differenziale deve intervenire, tempo di intervento a 5 I∆N, viene visualizzato 180 0 , utilizzare il tasto `DISPLAY` per verificare tutti i risultati parziali come segue: riarmare il differenziale

    b) Differenziale di tipo selettivo
    *   (prova 1) U B /2I∆N ; attesa di 30 s (conto alla rovescia a display); tempo di intervento a 1/2 I∆N, 0 0 → il differenziale non deve intervenire
    *   (prova 2) U B /2I∆N ; attesa di 30 s (conto alla rovescia a display); tempo di intervento a 1/2 I∆N 180 0 → il differenziale non deve intervenire

---

## EASYTEST HT5040 - 30 -

*   (prova 3) U B /2I∆N ; attesa di 30 s (conto alla rovescia a display); tempo di intervento at I∆N, 0 0 → il differenziale deve intervenire, viene visualizzato `RCD` (lampeggiante), usare il tasto `DISPLAY` per controllare i subparametri: riarmare il differenziale
*   (prova 4) U B /2I∆N ; attesa di 60 s (conto alla rovescia a display); tempo di intervento a I∆N, 180 0 → il differenziale deve intervenire, viene visualizzato `RCD` (lampeggiante), usare il tasto `DISPLAY` per controllare i subparametri: riarmare il differenziale
*   (prova 5) U B /2I∆N ; attesa di 60 s (conto alla rovescia a display); tempo di intervento a 5I∆N, 0 0 → il differenziale deve intervenire, viene visualizzato `RCD` (lampeggiante), usare il tasto `DISPLAY` per controllare i subparametri: riarmare il differenziale

---

## EASYTEST HT5040 - 31 -

*   (prova 6) U B /2I∆N ; attesa di 60 s (conto alla rovescia a display); tempo di intervento a I∆N, 180 0 → il differenziale deve intervenire, viene visualizzato `RCD` (lampeggiante), usare il tasto `DISPLAY` per controllare i subparametri: riarmare il differenziale

**ATTENZIONE** o •
*   Se la tensione presente ai terminali di misura premendo il tasto `START` è fuori dal campo 100 ÷ 250 V, il suo valore inizia a lampeggiare e non viene effettuata alcuna misura.
*   Se un risultato parziale (tempo di intervento o tensione di contatto U B ) supera i limiti ammessi, allora la misura viene bloccata ed il risultato memorizzato and displayed result è accompagnato dal simbolo `X`.

**Come impostare la tensione di contatto massima U B lim?**

1.  Posizionare il selettore su RCD~ o RCD….
2.  Premere due volte in successione il tasto `PRINT` ⇒ viene visualizzato `U Blim` poi `AC` e poi `50` o `25`.
3.  Selezionare 25 o 50 V mediante il tasto `RCL ↓` e confermarlo premendo il tasto `↑ SAVE`. Procedere con le misure.

---

## EASYTEST HT5040 - 32 -

### 6.1.8. Misura della corrente AC mediante la pinza

L’ingresso dello strumento è adatto per la pinza per la misura di corrente HT97. Sono disponibili 4 campi di misura disponibili sulla pinza e precisamente:

*   -1000 mV/A (campo di misura 0÷200 mA AC)
*   -100 mV/A (campo di misura 0÷2000 mA AC)
*   -10 mV/A (campo di misura 0÷20 A AC)
*   -1 mV/A (campo di misura 0÷200 A AC)

*   Fig. 31. Collegamento
*   Fig. 32. Risultato visualizzato (1000 mV/A campo)

**Come effettuare la misura?**

1.  Collegare la pinza allo strumento ed all’oggetto in esame come illustrato nella figura sopra.
2.  Posizionare il selettore su `; viene visualizzato `1000` o `100` o `10` o `1` (ultimo campo di misura impostato). Tramite il tasto `FUNC` è possibile scorrere le varie posizioni, per effettuare una giusta misura premere tante volte il tasto `FUNC` finché sul display non compare il numero corrispondente alla posizione del campo di misura della pinza e precisamente:
    | Pos Pinza   | Display |
    | :---------- | :------ |
    | 1000mV/A    | 1000    |
    | 100mV/A     | 100     |
    | 10mV/A      | 10      |
    | 1mV/A       | 1       |
3.  Premere il tasto `START` e tenerlo premuto finché il risultato visualizzato si stabilizza. Effettuare la lettura che può essere memorizzata, se necessario, premendo il tasto `SAVE`.

---

## EASYTEST HT5040 - 33 -

## 6.2. Comandi memoria

`↑ SAVE`
Qualsiasi risultato visualizzato eccetto tensione U PN, U PP, U PE o frequenza f nelle funzioni LINE Z/I K e LOOP Z/I K può essere salvato premendo il tasto `↑ SAVE`. Inoltre tutti i subrisultati o i parametri di una certa funzione saranno salvati. Ciascun risultato memorizzato è accompagnato dal codice del loop di misura (L) e del luogo di misura (P) consentendo all’operatore di distinguere a quale posizione di misura il risultato si riferisce. I codici del loop (L) e del luogo di misura (P) devono essere impostati prima che abbia luogo la misura.

**Quale è la procedura per salvare i risultati?**

a) Selezionare il codice L e P, dove saranno memorizzati ulteriori risultati.
1.  Ruotare il selettore a sinistra o a destra di una posizione (non è importante quale) per inizializzare il display.
2.  Premere il tasto `↑ SAVE`, verrà visualizzato l’ultimo codice impostato L o P.
3.  Impostare il codice L o P mediante i tasto `↑ SAVE` e `RCL ↓`, quindi premere display per selezionare l'altro codice (P o L) ed impostarlo allo stesso modo.
4.  Premere il tasto `START` per confermare i codici impostati o ruotare il selettore per abbandonare i codici impostati.
5.  Procedere con le misure.

b) Effettuare la misura richiesta.
1.  Una volta visualizzato il risultato, memorizzarlo premendo il tasto `↑ SAVE`. Viene visualizzata per un po’ la nuova posizione di memoria consentendo all’operatore di seguire il numero totale dei risultati memorizzati, quindi la lettura torna al risultato.

`RCL ↓`
Ci sono due sistemi possibili per richiamare i risultati memorizzati:

a) Richiamare solo i risultati salvati in un certo codice di loop di misura (L) e luogo di misura (P).
1.  Premere il tasto `RCL ↓`, viene visualizzato l’ultimo codice di loop di misura (L) impostato o luogo di misura (P). Impostare quello adeguato mediante il tasto `RCL ↓` e `↑ SAVE`.
2.  Selezionare un altro codice (P or L) premendo il tasto `DISPLAY` ed impostarlo allo stesso modo.
    Nota: Tre sono le fasi premendo il tasto `DISPLAY`: codice visualizzato L, codice visualizzato P, indicazione `MEM` visualizzata
    L’operatore deve premere il tasto `START` quando viene visualizzato il codice L o P altrimenti viene selezionato il secondo sistema di richiamo.
3.  Premere il tasto `START` per confermare i codici L e P impostati, viene visualizzato per un po’ il numero di serie dell’ultimo risultato memorizzato per impostare il codice L e P e poi il risultato corrispondente.
4.  Usare i tasti `RCL ↓` e `↑ SAVE` per richiamare anche altri risultati memorizzati con codici L e P.

---

## EASYTEST HT5040 - 34 -

5.  Usare il tasto `DISPLAY` per verificare eventuali subrisultati o parametri di una funzione nonché codice funzione, vedi fig. sotto.
    *   Fig.38. Etichetta pannello frontale con codici funzione

    Nota: Quando premendo il tasto `RCL ↓` si raggiunge il primo risultato memorizzato, in codici L e P definiti, questo è accompagnato per un po’ dal simbolo `<` e quando premendo il tasto `↑ SAVE` si raggiunge l’ultimo, questo è accompagnato per un po' dal simbolo `>`.

b) Richiamare tutti i risultati memorizzati indipendentemente dal codice del loop di misura (L) e dal codice del luogo di misura (P) usato quando si memorizza.
1.  Premere il tasto `RCL ↓` per confermare la selezione dei codici L e P.
2.  Usare il tasto `DISPLAY` per selezionare la lettura `MEM` a display e quindi premere il tasto `START`. Viene visualizzato per un po' il numero di serie dell’ultimo risultato memorizzato e quindi il risultato.
3.  Usare i tasti `RCL ↓` e `↑ SAVE` per controllare tutti gli altri risultati memorizzati.

---

## EASYTEST HT5040 - 35 -

4.  Usare il tasto `DISPLAY` per verificare eventuali subrisultati o parametri di ciascuna funzione e codice funzione, vedi fig. sopra.
    *   Fig. 39. Organizzazione memoria e relativo comando se viene usata la funzione `RCL` (caso b).

`CLR`
Esistono due possibilità per cancellare la memoria.

a) Solo l’ultimo risultato memorizzato deve essere cancellato.
1.  Premere brevemente il tasto `CLR`, verrà visualizzato `CLA` per un po', quindi verrà proposto per la cancellazione l’ultimo risultato memorizzato.
2.  Premere il tasto `CLR` per cancellare il risultato in memoria, verrà visualizzato MEM per un po’ e poi la lettura iniziale della funzione. Il risultato salvato prima di quello cancellato viene ora considerato come ultimo.
3.  Ripetere la procedura per cancellare più risultati.

b) Tutte le posizioni di memoria devono essere cancellate
1.  Premere il tasto `CLR` e tenerlo premuto finché viene proposto a display `EM`.
2.  Premere di nuovo il tasto `CLR` per cancellare tutto il contenuto della memoria.

---

## EASYTEST HT5040 - 36 -

## 6.3. Comunicazione RS232

La comunicazione RS232 serve a trasmettere i risultati memorizzati alla stampante esterna o al PC (comunicazione monodirezionale) o per comunicazione con il PC mediante SW fornibile a richiesta. Con l’ausilio del SW è possibile chiamare i risultati memorizzati dall’EASYTEST, o visualizzare la lingua di stampa impostata. Fare riferimento al manuale d’uso del SW per ulteriori informazioni.

Connettore RS 232 su EASYTEST
2. Tx
3. Rx
5. GND

*   Fig. 40. Connettore RS232 (femmina) sullo strumento
*   Fig. 41. Collegamento cavo RS 232

**Come stampare i risultati memorizzati?**

1.  Collegare l’EASYTEST alla stampante seriale (fornibile a richiesta) mediante il cavo RS232.
2.  Impostare lo strumento nel modo RS232 portando il selettore rotativo sulla posizione `RS232`, viene visualizzato il messaggio `PC`.
3.  Premere il tasto `PRINT`, viene visualizzato `PRINT` finché tutti i dati in memoria sono trasferiti alla stampante. Premere di nuovo `PRINT` per interrompere il trasferimento dati alla stampante se necessario.

**Come comunicare con il PC?**

1.  Collegare l’EASYTEST al PC mediante il cavo RS232.
2.  Impostare lo strumento nel modo RS232 portando il selettore rotativo sulla posizione `RS232`, viene visualizzato il messaggio `PC`.
3.  Attivare il SW installato sul PC, vedi manuale d’uso del SW.
4.  Ruotare il selettore per abbandonare il modo RS232.

---

## EASYTEST HT5040 - 37 -

Parametri di comunicazione
*   **Formato:** 1 start bit, 8 data bit, 1 stop bit, nessuna parità.
*   **Baud rate:** 2400 Baud.
*   **Protocollo di trasferimento:** X ON / X OFF

## 6.4. Lingua di stampa, selezione

La lingua di stampa può essere impostata da tastiera. E’ possibile selezionare una delle seguenti lingue:
*   Italiano
*   Inglese
*   Tedesco
*   Spagnolo

**Come impostare la lingua da tastiera?**

1.  Spegnere lo strumento, premere il tasto `PRINT` e tenerlo premuto mentre si accende lo strumento. Di seguito visualizzazione delle abbreviazioni per ciascuna lingua selezionata:
    *   `It` per Italiano
    *   `En` per Inglese
    *   `GE` per Tedesco
    *   `SP` per Spagnolo
2.  Usare i tasti `↑ SAVE` e `RCL ↓` per selezionare la lingua di stampa e confermare premendo il tasto `START`. L’abbreviazione visualizzata inizia a lampeggiare.
3.  Confermare premendo di nuovo il tasto `START`. La lingua è così impostata, lo strumento torna automaticamente al modo normale.

## 6.5. Reset dello strumento

In caso si rilevino malfunzionamenti (strano comportamento dello strumento, risultati strani ecc) è consigliabile eseguire la funzione di reset. In questo modo l’operatore può ottenere quanto segue:
*   tutti i parametri preimpostabili sono impostati nelle loro posizioni iniziali (valori).
*   tutte le posizioni di memoria vengono cancellate

Elenco dei parametri iniziali:
*   Sistema di collegamento nella posizione EARTH ........................................................... 2 punti.
*   Compensazione del cavo in posizione LOW Ω ................................................Non compensato.
*   Tipo di RDC in posizione RCD~ e RCD… ......................................................... Generale.
*   Corrente nominale in posizione RCD~ e RCD… .....................................................10mA.
*   Funzione selezionata in posizione RCD~ e RCD… .................... Tensione di contatto U B.
*   Tensione di contatto limite U Blim in posizione RCD~ e RCD… ...................................50V.
*   Campo di misura corrente in posizione `A` ................... 0÷200A (`1` a display = 1mV/A sulla pinza HT97).
*   Codice loop di misura (L) per salvataggio dei risultati.............................................................. 1
*   Codice luogo di misura (P) per salvataggio dei risultati............................................................ 1

---

## EASYTEST HT5040 - 38 -

**Come eseguire la funzione reset?**

1.  Spegnere lo strumento, premere il tasto `CLR` e tenerlo premuto mentre si accende lo strumento.
2.  `CLr` viene visualizzato per un pò, poi `MEM` e quindi la lettura iniziale per la funzione selezionata. Lo strumento è quindi resettato. Dopo aver acceso lo strumento, viene effettuata la prova automatica delle posizioni di memoria oltre alla prova delle costanti di calibrazione e dei parametri. In caso vengano rilevate durante la prova posizioni di memoria contaminate, il display visualizzerà `MEM` per un pò e le posizioni di memoria vengono cancellate. In caso vengano rilevate durante la prova costanti di calibrazione contaminate, il display visualizzerà `C` ⇒ chiamare il servizio riparazione. In caso vengano rilevate durante la prova parametri di prova contaminati, il display visualizzerà `P` e tutti i parametri saranno impostati alla loro posizione iniziale (valori), vedi elenco dei parametri iniziali a pagina 37.

## 6.6. Sostituzione batterie

1.  Spegnere lo strumento.
2.  Scollegare tutti i cavi di misura dai connettori dello strumento.
3.  Svitare la vite sul coperchio vano batteria (pos. 4, Fig. 3).
4.  Togliere il coperchio e sostituire le batterie (sostituire tutte 4 le batterie).
5.  Riposizionare il coperchio e avvitare la vite.

**ATTENZIONE** o •
*   Se lo strumento è collegato alla rete attraverso i cavi di misura, i contatti delle batterie potrebbero essere al potenziale di fase, perciò accertarsi di scollegare i cavi prima di aprire il coperchio vano batterie.
*   Utilizzare le batterie da 1,5 V tipo IECLR14.
*   Quando le batterie sono scariche (tensione inferiore a ca. 4,3V), l’operatore è avvertito dal segnale `BAT` visualizzato dallo strumento. In quel caso lo strumento è ancora operativo, ma la precisione dei risultati di prova non è più garantita.

---

## EASYTEST HT5040 - 39 -

## 6.7. Sostituzione fusibile

C’è un solo fusibile (all’interno dello strumento) che serve a proteggere la funzione LOW Ω. Se viene visualizzato `FUSE` il fusibile deve essere controllato e sostituito se bruciato.

La sostituzione del fusibile deve essere effettuato esclusivamente da personale qualificato esperto di dispositivi elettronici quali il EASYTEST e a conoscenza dei rischi di shock elettrico!

**ATTENZIONE** o •
*   Prima di aprire lo strumento, spegnerlo e scollegare tutti i cavi di misura dai relativi connettori.
*   Sostituire il fusibile esclusivamente con uno originale: M 0,315 A / 250 V, 5 x 20 mm

## 6.8 Simboli e messaggi su display

I seguenti simboli e/o messaggi potrebbero essere visualizzati durante il funzionamento dello strumento:
*   `L1` - Tensione di rete presente (U PN +U PE ) ≥ 50V, potenziale di fase sul lato della spina shuko contrassegnato da un puntino rosso.
*   `L2` - Tensione di rete presente (U PN +U PE ) ≥ 50V, potenziale di fase sul lato opposto a quello contrassegnato dal puntino rosso.
*   `X` - Risultato visualizzato oltre i limiti ammessi.
*   `L` - Codice del loop di misura.
*   `P` - Codice del luogo di misura.
*   `UB` - Funzione tensione di contatto U B selezionata.
*   `t∆` - Funzione tempo di intervento t ∆ selezionata.
*   `I∆` - Funzione corrente di intervento I ∆ selezionata.
*   `AUTO` - Funzione prova AUTO RCD selezionata.
*   `180°` - Inizio negativo della corrente di prova (se viene cancellato 180°, significa inizio positivo della corrente di prova).
*   `S` - E’ stato selezionato un differenziale di tipo selettivo (se non compare `S`, significa che è stato selezionato un differenziale di tipo standard).
*   `BAT` - Batteria scarica.
*   `FUSE` - Fusibile bruciato M 0,315 A/250 V, 5 x 20 mm, vedi paragrafo 6.5.
*   `TEMP` - Circuito interno dello strumento surriscaldato ⇒ attendere.

---

## EASYTEST HT5040 - 40 -

*   `MEM` - Funzionamento memoria (richiamo, memorizzazione, cancellazione).
*   `>` - Ultimo risultato memorizzato.
*   `<` - Primo risultato memorizzato.
*   `B` - Differenziale intervenuto durante la misura di U B .
*   `RCD` (lampeggiante) - Differenziale intervenuto nella funzione AUTO ⇒ riarmarlo per continuare la misura automaticamente.
*   `EM` - Tutte le posizioni di memoria.
*   `no MEM` - Nessuna memoria.
*   `no fil` - Nessun filtro nella funzione richiamo (tutti i risultati sono accessibili indipendentemente dal codice L e P).
*   `PC` - Comunicazione seriale pronta.
*   `PRINT` - Stampa.
*   `LEAd` - Pronto per i cavi di misura nella funzione compensazione LOW Ω.
*   `2P` - Collegamento a 2 fili nella funzione EARTH (informazioni solo per memorizzazione).
*   `3P` - Collegamento a 3 fili nella funzione EARTH (informazioni solo per memorizzazione).
*   `4P` - Collegamento a 4 fili nella funzione EARTH (informazioni solo per memorizzazione).

Via Righi 126 - 48018 Faenza
Tel: (0546) 621002 (4 linee r.a.) Fax (0546) 621144
email: ht@htitalia.it http://www/htitalia.com