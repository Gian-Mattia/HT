# MAXTEST2038

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-24 -->
**MAXTEST HT2038 INDICE:**
1.  INTRODUZIONE
2.  ELENCO DELLE FUNZIONI ESEGUIBILI CON LO STRUMENTO
3.  RIFERIMENTI NORMATIVI
4.  CARATTERISTICHE TECNICHE
    4.1. Funzioni
5.  DESCRIZIONE STRUMENTO
    5.1. Pannello frontale
    5.2. Pannello connessioni
    5.3. Sostituzione batterie e fusibili
    5.4. Disposizione display
    5.5. Pulizia dello strumento
    5.6. Fine vita
6.  ISTRUZIONI PER L’USO
    6.1. Prova PE
    6.2. Prova continuità dei conduttori di protezione, dei conduttori equipotenziali ecc. con una corrente di prova di 200 mA c
    6.3. Misura resistenza di isolamento con tensione di prova di 250V, 500V o 1000V
    6.4. Misura della resistenza di terra
    6.5. Resistività del terreno
    6.6. Senso ciclico delle fasi
    6.7. Impedenza di linea o dell’anello di guasto e corrente di corto-circuito presunta
    6.8. Parametri dei differenziali
        6.8.1. Principi teorici di funzionamento dei differenziali
        6.8.2. Misura della tensione di contatto U B
        6.8.3. Misura del tempo di intervento t FI
        6.8.4. Misura della corrente di intervento I ∆
        6.8.5. Analisi differenziali
    6.9. Misura della caduta di tensione
    6.10. Misura dell’impedenza ad elevata precisione
    6.11. Prova continuità del conduttore di protezione, del conduttore equipotenziale ecc. mediante corrente di prova di 10A b
    6.12. Misure mediante adattatore trifase
    6.13. Memorizzazione dei risultati
    6.14. Richiamo dei risultati
    6.15. Comunicazione RS232
        6.15.1. Connessioni
    6.16. Reset dello strumento
    6.17. Contrasto del display
    6.18. Impostazione orologio interno
7.  ACCESSORI IN DOTAZIONE

## 1. INTRODUZIONE

MAXTEST HT2038 è uno strumento professionale multifunzione portatile realizzato per verifiche di impianti elettrici con tensione standard di 127/230/400V nonché di qualsiasi impianto con tensione non standard compresa fra 100-400V. È caratterizzato da un’estrema semplicità d’uso e da un’ampia scelta di funzioni di misura. È dotato di circa 800 locazioni di memoria per salvare risultati delle verifiche, locazioni che possono essere successivamente trasferite ad un PC o stampate mediante stampante seriale. Ciascuna misura viene salvata con tutti i sottorisultati ed i parametri di prova e con un numero progressivo che consente di risalire al punto di prova. Un’adeguata progettazione elettrica e meccanica garantisce le necessarie condizioni di sicurezza per l’operatore e per lo strumento in caso di errate inserzioni o errato collegamento alla rete indipendentemente dalla funzione selezionata. Lo strumento è alimentato da quattro batterie alcaline da 1,5-V LR20. Un set di batterie permette un considerevole numero di misure. Lo strumento è realizzato in una valigetta di alluminio che lo protegge da eventuali urti.

Si raccomanda di rispettare i seguenti simboli che potrebbero comparire sul manuale e durante l’utilizzo dello strumento:

*   **Attenzione:** attenersi alle istruzioni riportate nel manuale; un uso improprio potrebbe causare danni allo strumento, ai suoi componenti o creare situazioni pericolose per l’operatore
*   **Tensione o Corrente AC**
*   **Tensione DC**
*   `p` **Spegnere lo strumento e scollegare tutti i cavi** - tensione pericolosa
*   `!` **Strumento con doppio isolamento**

## 2. ELENCO DELLE FUNZIONI ESEGUIBILI CON LO STRUMENTO

| Simbolo           | Posizione del selettore | Descrizione della funzione                                                                                                 |
| :---------------- | :---------------------- | :------------------------------------------------------------------------------------------------------------------------- |
| R LOW Ω 10A b     |                         | Misura della resistenza di conduttori di protezione, equipotenziali e armature cemento armato con una corrente di 10A ac. |
| ∆ U               |                         | Caduta tensione rapportata a 10A.                                                                                          |
| R LOW Ω 200mA c   |                         | Misura della continuità di conduttori di protezione, equipotenziali e supplementari.                                       |
| R E               | EARTH                   | Misura della resistenza di terra a due e tre fili.                                                                         |
| ρ                 |                         | Misura della resistività del terreno.                                                                                      |
| R ISO 250V        |                         | Misura della resistenza di isolamento di impianti elettrici con tensione di prova di 250V.                                |
| R ISO 500V        | R ISO                   | Misura della resistenza di isolamento di impianti elettrici e quadri elettrici ANS con tensione di prova di 500V.         |
| R ISO 1000V       |                         | Misura della resistenza di isolamento di impianti elettrici con tensione di prova di 1000V.                               |
| Z L-L/L-N         |                         | Impedenza di linea tra due fasi o tra fase e neutro.                                                                       |
| I K               |                         | Corrente di corto-circuito presunta.                                                                                       |
| i p               | Z LINE                  | Valore di picco della corrente di corto-circuito presunta.                                                                 |
| U L-L/L-N         |                         | Tensione di rete L-L o L-N.                                                                                                |
| f                 |                         | Frequenza della tensione L-L o L-N.                                                                                        |
| Z L-PE            |                         | Impedenza dell’anello di guasto fra fase e conduttore di protezione.                                                       |
| I K               |                         | Corrente di guasto presunta.                                                                                               |
| i p               | Z LOOP                  | Valore di picco della corrente di guasto presunta.                                                                         |
| U B               |                         | Tensione di contatto alla corrente di guasto presunta calcolata.                                                           |
| U L-PE            |                         | Tensione di rete tra fase e conduttore di protezione.                                                                      |
| f                 | RCD function            | Frequenza della tensione L-PE.                                                                                             |
|                   | PHASE ROTATION          | Senso ciclico delle fasi.                                                                                                  |
| U B               |                         | Tensione di contatto ad una volta o due volte (per i differenziali di tipo n) la corrente differenziale nominale.           |
| R E(L)            | RCD                     | Resistenza di terra, resistenza dell’anello.                                                                               |
| t                 | VOLTAGE UB TIME t       | Tempo di intervento.                                                                                                       |
| I ∆               |                         | Corrente di intervento.                                                                                                    |
| U B (I ∆ )        | RCD CURRENT             | Tensione di contatto alla corrente di intervento.                                                                          |
| t(I ∆ )           |                         | Tempo di intervento alla corrente di intervento.                                                                           |
|                   | RCD-Analysis            | Prova automatica di tutti i più importanti parametri del differenziale.                                                    |
| ∆ U               | VOLTAGE DROP            | Misura della caduta di tensione percentuale sui conduttori a causa del carico.                                             |
| Z                 |                         | Impedenza dell’anello di guasto o di linea ad elevata risoluzione tra due fasi, tra una fase e neutro, tra una fase e conduttore di protezione. |
| I K               |                         | Corrente di guasto o di corto-circuito presunta ad elevata risoluzione.                                                    |
| i p               | Z2 Ω Im=280Amax         | Corrente di guasto o di corto-circuito di picco ad elevata risoluzione                                                     |
| U B               |                         | Tensione di contatto ad elevata risoluzione alla corrente di guasto calcolata presunta.                                    |

## 3. RIFERIMENTI NORMATIVI

*   **EN 61010-1**: Norma sulla sicurezza degli strumenti
*   **EN 50081-1 1991 EN 50082-1 1991 classe C**: Normative EMC
*   **CEI 64.8 612.3, VDE 0413/1**: Resistenza di isolamento.
*   **CEI 64.8 612.6.3, VDE 0413/3**: Impedenza dell'anello di guasto, impedenza di linea e corrente di guasto o di corto-circuito presunta.
*   **IEC 781**: Calcolo delle correnti di guasto o di corto-circuito presunte.
*   **CEI 64.8 612.2, VDE 0413/4**: Continuità.
*   **CEI 64.8 cap. 61 app.D, VDE 0413/6**: Parametri dei differenziali.
*   **CEI 64.8 612.6.2, VDE 0413/7**: Resistenza di terra.
*   **VDE 0413/9**: Senso ciclico delle fasi.

## 4. CARATTERISTICHE TECNICHE
### 4.1. Funzioni

**♦ Prova continuità R (LOW Ω 200mA c)**

| Campo (Ω) | Risoluzione (Ω) | Precisione*              |
| :-------- | :-------------- | :----------------------- |
| 0 ÷ 20    | 0,01            | ± (2% lettura + 2 cifre) |

\* Si è tenuto conto della calibrazione automatica che elimina la resistenza del cavo. La misura viene effettuata con due prove a polarità invertita in modo automatico, il risultato è la media aritmetica delle due prove.

*   Corrente di misura visualizzata:
    *   Campo di misura: 0 ÷ 400 mA
    *   Risoluzione: 1 mA
    *   Precisione: ±(2% lettura + 2 mA)
*   Corrente di corto-circuito: Icc > 200 mA dc (con tensione batteria U BAT > 5 V)
*   Tensione a vuoto: Uo > 4.5 V (con tensione batteria U BAT > 5 V)

**♦ Prova resistenza del conduttore di protezione R (LOW Ω 10A b)**

| Campo (Ω) | Risoluzione (Ω) | Precisione               |
| :-------- | :-------------- | :----------------------- |
| 0 ÷ 0,5   | 0,001           | ±(2% lettura + 2 cifre) |

*   Corrente di misura: Im > 10 A b / 230 V alimentazione (6%, 10%)
*   Tensione a vuoto: Uo < 12 V b ( alla tensione di rete 240 V)
*   Tensione di misura visualizzata:
    *   Campo di misura: 0 ÷ 12 V
    *   Risoluzione: 0,01 V
    *   Precisione: ±(2% lettura + 2 cifre)
*   Sistema di misura: a 4 fili
*   Corrente di misura visualizzata:
    *   Campo di misura: 0 ÷ 30 A
    *   Risoluzione: 0,1 A
    *   Precisione: ±(2% lettura + 2 cifre)

**♦ Caduta di tensione fino a 10A b**
**CADUTA DI TENSIONE (LOW Ω 10A b)**

| Campo (V)* | Risoluzione (V) | Precisione               |
| :--------- | :-------------- | :----------------------- |
| 0 ÷ 12     | 0,01            | ±(2% lettura + 3 cifre) |

\*Il valore della caduta di tensione viene riportato a 10A. Vengono visualizzate la resistenza e la corrente di misura.

**♦ Misura della resistenza di terra a due e tre fili RE (EARTH)**

| Campo* (Ω) | Risoluzione (Ω) | Precisione               |
| :--------- | :-------------- | :----------------------- |
| 0 ÷ 19,99  | 0,01            | ±(2% lettura + 2 cifre) |
| 20,0 ÷ 199,9 | 0,1             | ±(2% lettura + 2 cifre) |
| 200 ÷ 1999 | 1               | ±(2% lettura + 2 cifre) |

\* Selezione automatica del campo

*   Frequenza di misura: 125 Hz ± 1 Hz
*   Corrente di misura: < 10 mAeff.
*   Tensione di misura a vuoto: < 65 Veff.
*   Forma della tensione di misura: Sinusoidale
*   Resistenza dei picchetti di corrente:
    *   Campo di misura: 0 ÷ 50 K Ω
    *   Risoluzione: 0,1 K Ω
    *   Precisione: ±(10% lettura + 0,5 K Ω)

**♦ Misura della resistività del terreno ρ (EARTH)**

| Campo ρ* (Ωm) | Risoluzione (Ωm) | Precisione                                                                  |
| :------------ | :--------------- | :-------------------------------------------------------------------------- |
| 0 ÷ 19,99     | 0,01             | ±(2% lettura + 2 π a ⋅ 0,02 Ω ); ρ π 2 a ≤ 19,99 Ω                          |
| 20,0 ÷ 199,9  | 0,1              |                                                                             |
| 200 ÷ 1999    | 1                | ±(2% lettura + 2 π a ⋅ 0,2 Ω ); 19,99 Ω < ρ π 2 a ≤ 199,9 Ω               |
| 2,00k ÷ 19,99k | 10               |                                                                             |
| 20,0k ÷ 199,9k | 100              | ±(2% lettura + 2 π a ⋅ 2 Ω ); 199,9 Ω < ρ π 2 a                           |
| 200k ÷ 377k   | 1000             |                                                                             |

\* Selezione automatica del campo

È possibile selezionare la distanza fra due picchetti da 1 fino a 30 m, tuttavia è possibile raggiungere a max = 8 m utilizzando i cavi in dotazione.

`ρ = 2 π aR E`

*   ρ ...... Resistività del terreno
*   a ...... Distanza tra due picchetti
*   R E .... Resistenza di terra tra i picchetti S ed ES
*   Frequenza di misura: 125 Hz ± 1 Hz
*   Corrente di misura: < 10 mAeff.
*   Tensione di misura a vuoto: < 65 Veff.
*   Forma della tensione di misura: sinusoidale
*   Resistenza dei picchetti di corrente:
    *   Campo di misura 0 ÷ 50 K Ω
    *   Risoluzione 0,1 K Ω
    *   Precisione ± (10 % lettura + 0,5 K Ω)
*   Interferenza (valida per prove di resistenza di terra e resistività del terreno): Una tensione di disturbo di 20 Vpp / 50Hz sul circuito di tensione ha l’effetto max di ± 0,1 Ω.
*   Resistenza massima dei picchetti di corrente Rc max:
    *   La resistenza massima dei picchetti Rcmax che non introdurrà un ulteriore errore max di 10 cifre (resistività del terreno) o errore max di 2 cifre (resistenza di terra) è la seguente:
    *   `Rc max = (4 k Ω + 100 RE) but ≤ 50 k Ω`
    *   `Rc = Rc1 + Rc2` (misura della resistività del terreno vedi fig. 2)
    *   `Rc = Rc2` (misura della resistenza di terra vedi fig. 1)
*   Fig.1. Circuito equivalente per la misura della resistenza di terra
*   Fig.2. Circuito equivalente per la misura della resistività del terreno
*   Resistenza massima potenziale dei picchetti Rp max:
    *   La resistenza massima dei picchetti Rpmax che non introdurrà un ulteriore errore max di 10 cifre (resistività del terreno) o errore max di 2 cifre (resistenza di terra) è la seguente:
    *   `Rp = (4 k Ω + 100 RE) ma ≤ 50 k Ω`
    *   `Rp = Rp1 + Rp2` (misura della resistività del terreno vedi fig. 2).
    *   `Rp = Rp2` (misura della resistenza di terra vedi fig. 1).

**♦ Misura della resistenza di isolamento di impianti elettrici con tensione di prova di 250V R ISO /250V (R ISO)**

| Campo* (MΩ) | Risoluzione (kΩ) | Precisione               |
| :---------- | :--------------- | :----------------------- |
| 0 ÷ 1,999   | 1                | ± (2% lettura + 2 cifre) |
| 2,00 ÷ 19,99 | 10               | ± (2% lettura + 2 cifre) |
| 20,0 ÷ 199,9 | 100              | ± (2% lettura + 2 cifre) |

\* Selezione automatica del campo

*   Campo di visualizzazione: 0÷ 1G Ω
*   Tensione di misura: 250 Vdc, +10 % / -0 %
*   Tensione di misura visualizzata:
    *   Campo: 0 ÷ 325 V
    *   Risoluzione: 1 V
    *   Precisione ±(2% lettura + 2 V)
*   Corrente di misura: 1 mA (min) a 250 k Ω di carico
*   Corrente di corto-circuito: 1,4 mA (max)

**♦ Misura della resistenza di isolamento di impianti elettrici o quadri ANS con tensione di prova di 500V R ISO /500V (R ISO)**

| Campo* (MΩ) | Risoluzione (kΩ) | Precisione               |
| :---------- | :--------------- | :----------------------- |
| 0 ÷ 1,999   | 1                | ± (2% lettura + 2 cifre) |
| 2,00 ÷ 19,99 | 10               | ± (2% lettura + 2 cifre) |
| 20,0 ÷ 199,9 | 100              | ± (2% lettura + 2 cifre) |

\* Selezione automatica del campo

*   Campo di visualizzazione: 0÷ 1G Ω
*   Tensione di misura: 500 Vdc, +10 % / -0 %
*   Tensione di misura visualizzata:
    *   Campo: 0 ÷ 650 V
    *   Risoluzione: 1 V
    *   Precisione ±(2% lettura + 2 V)
*   Corrente di misura: 2,2 mA (min) a 230 k Ω di carico
*   Corrente di corto-circuito: 2,6 mA (max)

**♦ Misura della resistenza di isolamento di impianti elettrici con tensione di prova di 1000V R ISO /1000V (R ISO)**

| Campo* (MΩ) | Risoluzione (kΩ) | Precisione               |
| :---------- | :--------------- | :----------------------- |
| 0 ÷ 1,999   | 1                | ± (2% lettura + 2 cifre) |
| 2,00 ÷ 19,99 | 10               | ± (2% lettura + 2 cifre) |
| 20,0 ÷ 199,9 | 100              | ± (2% lettura + 2 cifre) |

\* Selezione automatica del campo

*   Campo di visualizzazione: 0÷ 1G Ω
*   Tensione di misura: 1000 Vdc, +10 % / -0 %
*   Tensione di misura visualizzata:
    *   Campo: 0 ÷ 1300 V
    *   Risoluzione: 1 V
    *   Precisione ±(2% lettura + 2 V)
*   Corrente di misura: 1 mA (min) a 1000 k Ω di carico
*   Corrente di corto-circuito: 1,4 mA (max)

**♦ Misura del valore efficace (rms) della tensione ac U L-L/L-N/L-PE ( funzioni Z, PHASE ROTATION, funzioni RCD, VOLTAGE DROP)**

| Campo (V) | Risoluzione (V) | Precisione               |
| :-------- | :-------------- | :----------------------- |
| 0 ÷ 440   | 1               | ± (2% lettura + 2 cifre) |

**♦ Misura della frequenza f ( funzioni Z , PHASE ROTATION, funzioni RCD, VOLTAGE DROP)**

| Campo (Hz) | Risoluzione (Hz) | Precisione                |
| :--------- | :--------------- | :------------------------ |
| 45,0 ÷ 65,0 | 0,1              | ±(0,1% lettura + 1 cifra) |

**♦ Misura dell'impedenza dell'anello di corto-circuito fase-fase o fase-neutro Z L-L/L-N , R, X l \*\* (Z LINE)**

| Campo* (Ω) | Risoluzione (Ω) | Precisione               |
| :--------- | :-------------- | :----------------------- |
| 0 ÷ 19,99  | 0,01            | ± (2% lettura + 2 cifre) |
| 20,0 ÷ 199,9 | 0,1             | ± (2% lettura + 2 cifre) |
| 200 ÷ 1999 | 1               | ± (2% lettura + 2 cifre) |

\* Selezione automatica del campo
\*\* Ulteriore errore per X l : `0,001 ⋅ (10 Ω + R)`

*   Tensione nominale: 100 ÷ 440 V
*   Frequenza nominale: 45 ÷ 65 Hz

**♦ Corrente di corto-circuito presunta I K - valore standard (Z LINE)**

Calcolo della corrente di corto-circuito I K :
*   `I K = U L / Z L` (400V ± 15%)
*   `I K = U N / Z N` (230V ± 15%)
*   `I K = U / Z` (Altre tensioni)

*   Precisione di I K: Tenere in considerazione la precisione di Z LINE
*   Campo di visualizzazione I K (400 V): 0,20 A ÷ 40 kA
*   Campo di visualizzazione I K (230 V): 0,11 A ÷ 23 kA
*   Risoluzione I K:
    *   0,06 ÷ 19,99 A.....0,01 A
    *   20,0 ÷ 199,9 A.....0,1 A
    *   200 ÷ 1999 A.......1A
    *   2,00 ÷ 19,99 kA...10A
    *   20,0 ÷ 40,0 kA.....100A

**♦ Corrente di corto-circuito presunta I K - altri valori (Z LINE)**

*   `I K MAX 3ph = C N ⋅ U L-L / (√3 ⋅ Z MAX L-L)`
*   `I K MIN 3ph = C N ⋅ U L-L / (√3 ⋅ Z HOT L-L)`
*   `I K MAX 2ph = C N ⋅ U L-L / Z MAX L-L`
*   `I K MIN 2ph = C N ⋅ U L-L / Z HOT L-L`
*   `I K MAX L-N = C N ⋅ U L-N / Z MAX L-N`
*   `I K MIN L-N = C N ⋅ U L-N / Z HOT L-N`
*   `i p = √2 ⋅ I K MAX ⋅ χ`

dove: `χ = 1,02 + 0,98 ⋅ e^(-3 ⋅ R/X L)`
dove: `Z HOT L = √( (1,5 ⋅ R)^2 + X L^2 )`

Tabella per la determinazione del coefficiente C

| UN=230/400 V | UN ≠ 230/400 V |
| :----------- | :------------- |
| C MAX 1,00   | 1,05           |
| C MIN 0,95   | 1,00           |

**♦ Misura dell’impedenza dell’anello di guasto fase-conduttore di protezione PE Z L-PE , R, X l \*\* (Z LOOP )**

| Campo* (Ω) | Risoluzione (Ω) | Precisione               |
| :--------- | :-------------- | :----------------------- |
| 0 ÷ 19,99  | 0,01            | ± (2% lettura + 2 cifre) |
| 20,0 ÷199,9 | 0,1             | ± (2% lettura + 2 cifre) |
| 200 ÷ 1999 | 1               | ± (2% lettura + 2 cifre) |

\* Selezione automatica del campo
\*\* Ulteriore errore per X l : `0,001 ⋅ (10 Ω + R)`

**♦ Tensione di contatto alla corrente di corto-circuito U B / I K (Z LOOP, Z2 Ω Im=280 A max)**

| Campo (V) | Risoluzione (V) | Precisione                                                                                                                                                                          |
| :-------- | :-------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 0 ÷199,9  | 0,1             | Tenere in considerazione la precisione di I K e R con Z LOOP , precisione di R con : ±(2% della lettura interna + 0,05 Ω )                                                            |
| 200 ÷ 500 | 1               | Z2 Ω Im=280 A max, precisione di R con : ±2% della lettura interna + 0,002 Ω ) |

*   Tensione nominale: 100 ÷ 250 V
*   Frequenza nominale: 45 ÷ 65 Hz

**♦ Corrente di guasto presunta I K - valore standard (Z LOOP )**

Calcolo della corrente di guasto I K :
*   `I K = U N / Z N` (230V ± 15%)
*   `I K = U / Z` (Altre tensioni)

*   Precisione di I K: Tenere in considerazione la precisione di Z LOOP
*   Campo di visualizzazione I K (230 V): 0,11 A ÷ 23 kA
*   Risoluzione I K:
    *   0,06 ÷ 19,99 A.....0,01 A
    *   20,0 ÷ 199,9 A.....0,1 A
    *   200 ÷ 1999 A.......1A
    *   2,00 ÷ 19,99 kA...10A
    *   20,0 ÷ 23,0 kA.....100A

**♦ Corrente di corto-circuito presunta I K - altri valori (Z LOOP )**

*   `I K MAX L-PE = C N ⋅ U L-PE / Z MAX L-PE`
*   `I K MIN L-PE = C N ⋅ U L-PE / Z HOT L-PE`
*   `i p = √2 ⋅ I K MAX ⋅ χ`

dove: `χ = 1,02 + 0,98 ⋅ e^(-3 ⋅ R/X L)`
dove: `Z HOT L = √( (1,5 ⋅ R)^2 + X L^2 )`

**♦ Senso ciclico delle fasi: ( SENSO CICLICO DELLE FASI)**
L1, L2, L3 or L2, L1, L3

*   Tensione nominale: 100 ÷ 440 V
*   Frequenza nominale: 45 ÷ 65 Hz

**♦ Tensione di contatto U B :**
**U B (RCD VOLTAGE/TIME)**

| Campo di misura (V) | Campo di visualizzazione | Risoluzione | Precisione               |
| :------------------ | :----------------------- | :---------- | :----------------------- |
| 10 ÷ 50 (U BLIM =25V) | 0 ÷ 100 V                | 0,1         | +10 % / -0 % (lettura) |
| 10 ÷ 100 (U BLIM =50V) |                          |             |                          |

U Blim : selezionabile: 25 V o 50 V
Le caratteristiche della suddetta tabella sono valide alle seguenti condizioni:

*   Instabilità max della tensione di linea durante la misura ± 1 %,
*   Conduttore di protezione è libero da tensioni di disturbo.

La misura di U B viene effettuata con la corrente di ½I ∆ N , e poi riportata alla corrente differenziale nominale I ∆ N (RCD tipo generale f. d'onda: b , lc ) o al doppio della corrente differenziale 2 I ∆ N (RCD tipo selettivo n , RCD tipo generale f. d'onda: c ).

*   Tensione nominale: 100 ÷ 250 V
*   Frequenza nominale: 45 ÷ 65 Hz

**♦ Resistenza di terra R E , resistenza dell’anello R l :**
**R E , , R l ( funzioni RCD)**

| I ∆ N (mA) | Campo R E (Ω) | Risoluzione (Ω) | Precisione                       |
| :--------- | :------------ | :-------------- | :------------------------------- |
| 10         | 0 ÷ 1999      | 1               | +10 %, -0 % (lettura) ± 20 Ω   |
| 30         | 0 ÷ 1999      | 1               | +10 %, -0 % (lettura) ± 7 Ω    |
| 100        | 0 ÷ 999       | 0,1             | +10 %, -0 % (lettura) ± 2 Ω    |
| 300        | 0 ÷ 199,9     | 0,1             | +10 %, -0 % (lettura) ± 0,7 Ω  |
|            | 200 ÷ 333     | 0,1             |                                  |
| 500        | 0 ÷ 199,9     | 0,1             | +10 %, -0 % (lettura) ± 0,4 Ω  |
| 1000       | 0 ÷ 100,0     | 0,1             | +10 %, -0 % (lettura) ± 0,2 Ω  |

*   Corrente di misura: 0.4 I ∆ N
*   Tensione nominale: 100 ÷ 250 V
*   Frequenza nominale: 45 ÷ 65 Hz

**♦ Misura del tempo di intervento t ∆ N di differenziali generali o selettivi**
**t (RCD VOLTAGE/TIME)**

| Campo t ∆ N (ms) tipo generale | Campo t ∆ N (ms) tipo selettivo | Risoluzione (ms) | Precisione              |
| :----------------------------- | :------------------------------ | :--------------- | :---------------------- |
| 0 ÷ 1000 (1/2 I ∆ N , I ∆ N )    | 0 ÷ 1000 (1/2 I ∆ N , I ∆ N )     | 1                | ± (2 % lettura +2 ms) |
| 0 ÷ 200 (2 I ∆ N )             | 0 ÷ 200 (2 I ∆ N )              |                  |                         |
| 0 ÷ 50 (5 I ∆ N )              | 0 ÷ 150 (5 I ∆ N )              |                  |                         |

Tabella dei valori efficaci (r.m.s.) (10ms) delle correnti differenziali:

| 1/2 I ∆ N (mA) | I ∆ N (mA)    | 2 I ∆ N (mA) | 5 I ∆ N (mA)   |
| :------------- | :------------ | :----------- | :------------- |
| b l c          | b l c         | b l c        | b l c          |
| 5 3,5 5        | 10 20 20      | 20 28,3 40   | 250 353,6 100  |
| 15 10,5 15     | 30 42,4 60    | 60 84,9 120  | 250 353,6 300  |
| 50 35 50       | 100 141,4 200 | 200 283 400  | 500 707,1 -/-  |
| 150 105 150    | 300 424,3 600 | 600 849 -/-  | 1500 2121 -/-  |
| 250 175 250    | 500 707,1 -/- | 1000 1414 -/- | 2500 3535 -/-  |
| 500 354 500    | 1000 1414 -/- | 2000 2828 -/- | -/- -/- -/-    |

*   Precisione delle correnti differenziali: ±5 %
*   Tensione nominale: 100 ÷ 250 V
*   Frequenza nominale: 45 ÷ 65 Hz

**♦ Misura della corrente di intervento I ∆**
**I ∆ (RCD CURRENT F. d'onda: b , l)**

| Campo I ∆ N (mA) | Risoluzione (mA) | Precisione   |
| :--------------- | :--------------- | :----------- |
| (0,4 ÷ 1,4) I ∆ N | 0,1 I ∆ N        | ± 0,15 I ∆ N |

**I ∆ (RCD CURRENT F. d'onda: c)**

| Campo I ∆ N (mA) | Risoluzione (mA) | Precisione   |
| :--------------- | :--------------- | :----------- |
| (0,4 ÷ 2,1) I ∆ N | 0,1 I ∆ N        | ± 0,15 I ∆ N |

**♦ Tensione di contatto U B alla corrente di intervento (F. d'onda: b , l) o a due volte la corrente di intervento (F. d'onda: c)**
**U B (I ∆ ) (RCD CURRENT)**

| Campo di misura (V) | Campo di visualizzazione | Risoluzione | Precisione               |
| :------------------ | :----------------------- | :---------- | :----------------------- |
| 10 ÷ 50 (U BLIM =25V) | 0 ÷ 100 V                | 0.1         | +10 % / -0 % (lettura) |
| 10 ÷ 100 (U BLIM =50V) |                          |             |                          |

U Blim : selezionabile: 25 V o 50 V
Le caratteristiche della suddetta tabella sono valide alle seguenti condizioni:

*   Instabilità max della tensione di linea durante la misura ± 1 %,
*   Conduttore di protezione è libero da tensioni di disturbo.

*   Tensione nominale: 100 ÷ 250 V
*   Frequenza nominale: 45 ÷ 65 Hz

**♦ Tempo di intervento t ∆ alla corrente di intervento**
**t(I ∆ ) (RCD CURRENT)**

| Campo (ms) | Risoluzione (ms) | Precisione              |
| :--------- | :--------------- | :---------------------- |
| 0 ÷ 500    | 1                | ± (2 % lettura + 2 ms) |

**♦ Caduta di tensione ∆ U (VOLTAGE DROP)**

| Campo ∆ U (%) | Risoluzione (%) | Precisione |
| :------------ | :-------------- | :--------- |
| 0 ÷ 20        | 0,1             | ± 1 cifra  |

| Campo U 1 , U 2 (V) | Risoluzione U 1 , U 2 (V) | Precisione               |
| :------------------ | :------------------------ | :----------------------- |
| 100 ÷ 440           | 0,1                       | ± (2 % lettura + 2 cifre) |

*   Tensione nominale: 100 ÷ 440 V
*   Frequenza nominale: 45 ÷ 65 Hz

**♦ Impedenza ad elevata precisione Z, R, X L * (Z2 Ω Im=280A max )**

| Campo (mΩ) | Risoluzione (mΩ) | Precisione               |
| :--------- | :--------------- | :----------------------- |
| 0 ÷ 199,9  | 0,1              | ± (2 % lettura + 2 mΩ) |
| 200 ÷ 1999 | 1                | ± 2 % lettura            |

\* Ulteriore errore per X L : `0,001 ⋅ (1,5 Ω +R)`

*   Tensione nominale: 100 ÷ 440 V
*   Frequenza nominale: 45 ÷ 65 Hz

**♦ Corrente di corto-circuito presunta ad elevata risoluzione I K - valore standard (Z2 Ω Im=280A max)**

Calcolo della corrente di corto-circuito:
*   `I K = U L / Z L` (400V ± 15%)
*   `I K = U N / Z N` (230V ± 15%)
*   `I K = U / Z` (Altre tensioni)

*   Precisione di I K: tenere in considerazione la precisione di Z2 Ω
*   Campo di misura I K (400 V): 200 A ÷ 400 kA
*   Campo di misura I K (230 V): 115 A ÷ 230 kA
*   Risoluzione I K:
    *   63 ÷ 1999 A..............1 A
    *   2,00 ÷ 19,99 kA........10 A
    *   20,0 ÷ 400,0 kA.....100 A

**♦ Corrente di corto-circuito presunta ad elevata risoluzione I K - altri valori (Z2 Ω Im=280A max)**

Vedi altri valori di IK per le funzioni Z LINE e Z LOOP.

### 4.2. Caratteristiche generali

*   ALIMENTAZIONE: 4 batterie alcaline da 1,5 V IEC LR 20
*   DURATA BATTERIA: ca 300 ore
*   DISPLAY A CRISTALLI LIQUIDI: a matrice (127 x 34 mm) e (240 x 64 punti) retroilluminato
*   MEMORIA: ca. 800 posizioni di memoria
*   COMUNICAZIONE: RS 232; baud rate 4800 (formato: 1 start bit, 8 data bit, 1 stop bit)
*   PESO (comprese batterie): 8,5 kg
*   DIMENSIONI (L x H x L): 450 mm x 350 mm x 130 mm
*   Categoria sovratensione (funzione Z2 Ω): III
*   Categoria sovratensione (altre funzioni): II
*   Grado di inquinamento: 2
*   Classe di protezione: doppio isolamento t
*   Tensione MAX verso terra: 230V b
*   Tensione MAX ingresso: 440V b
*   Campo temperatura nominale: 5 ÷ 35 ° C
*   Campo temperatura di funzionamento: 0 ÷ 40 ° C
*   Campo temperatura di immagazzinamento: -10 ÷ 60 ° C

## 5. DESCRIZIONE STRUMENTO
### 5.1. Pannello frontale

Fig. 4. Pannello frontale

Legenda:
1.  .......Etichetta con istruzioni di collegamento sotto il coperchio.
2.  .......Coperchio strumento.
3.  .......Dissipatore metallico (fare attenzione ad eventuali aumenti di temperatura durante la misura dell’impedenza ad elevata precisione - funzione Z2 Ω !).
4.  .......Tasto **ON/OFF** key - spegnimento automatico dopo 10 minuti dall’ultima operazione.
5.  .......Tasto **8/ ↑** come parte del tastierino numerico ( 8 ) o per incrementare alcuni parametri in modo continuo ( ↑ ).
6.  .......Tastiera numerica.
7.  .......Tasto **2/ ↓** come parte del tastierino numerico ( 2 ) o per decrementare alcuni parametri in modo continuo ( ↓ ).
8.  .......Tasto **CE** per cancellare i parametri inseriti per errore.
9.  .......Tasto **MENU** per selezionare una delle due funzioni dei tasti F1 ÷ F6:
    *   Set di comandi funzionali
    *   Set di comandi di funzionamento della memoria
10. .....Tasto **LIGHT** per accendere o spegnere la retroilluminazione del display. È opportuno usare la luce display solo quando necessario dato il suo elevato assorbimento.
11. .....Tasto **START** per iniziare una misura.
12. .....Elettrodo di prova **PE** per verificare la presenza di eventuale tensione di fase al terminale di protezione di terra o l'assenza di collegamento del terminale PE.
13. .....Tasti **F1** a **F6**. Il significato di ciascun tasto è indicato sul display. Dipende dalla funzione impostata e dal MENU selezionato.
14. .....Commutatore rotativo per la scelta della funzione di misura.
15. .....Maniglia di trasporto.
16. .....Display a cristalli liquidi a matrice.
17. .....Coperchio vano batterie e fusibili.
18. .....Vite del coperchio vano batterie.
19. .....Pannello connessioni, verificare l'utilizzo di ciascuno dei tre connettori con la relativa figura riportata sul coperchio del vano batterie.
20. .....Connettore di misura 1.
21. .....Connettore di alimentazione per la funzione LOW Ω 10A b.
22. .....Presa **PROBE** per la misura della tensione di contatto alla corrente di corto-circuito presunta o per la misura della resistenza (R E) (funzione RCD).
23. .....Catenella per bloccare il coperchio in posizione di apertura. Sganciare il coperchio dal lato del dissipatore metallico per staccarlo.

### 5.2. Pannello connessioni

a) Funzioni:
*   LOW Ω 200mA (L, N)
*   RISO (L, N)
*   EARTH (E, H, S, ES)
*   PHASE ROTATION (L1, L2, L3)
*   Z LINE (L, N)
*   Z LOOP (L, PE)
*   RCD Tensione UB/Tempo t (L, N, PE)
*   RCD Corrente I ∆ (L, N, PE)
*   RCD Analisi (L, N, PE)
b) Funzioni:
*   Comunicazione RS 232
*   Stampa
    *   2...TxD
    *   3...RxD
    *   5...GND
c) Funzioni:
*   LOW Ω 10A (C1, C2, P1, P2)
*   Z2 Ω Im=280A max (C1, C2, P1, P2)
*   VOLTAGE DROP (C1, C2, P1, P2)

Fig. 5. Connettori

<!-- Chunk: Pages 25-48 -->
## 5.3. Sostituzione batterie e fusibili

**o** Scollegare tutti i cavi (cavi di misura, cavo di alimentazione, o cavo RS232) prima di togliere il coperchio vano batteria!
**p** Tensione pericolosa sotto il coperchio vano batteria!

Se sul display compare il simbolo `BAT` significa che la tensione delle batterie è inferiore a 4,3 V, togliere quindi le batterie vecchie ed inserire le nuove. Sostituire tutte le batterie. In fig. 6 è indicato come inserirle. Usare batterie da 1,5V IEC LR20. E’ opportuno rimuovere tutte le batterie se lo strumento resta inutilizzato per un lungo periodo di tempo. In caso di malfunzionamento dello strumento o se viene visualizzato il simbolo `FUSE`, controllare che i fusibili siano ancora integri. Usare solo fusibili originali del tipo indicato di seguito per sostituire quelli bruciati.

| Componente              | Fusibile | Tipo                                 |
| :---------------------- | :------- | :----------------------------------- |
| **CONNETTORE DI PROVA 1** | F4       | T 0.315 A, 250 V / 5 mm x 20 mm      |
| Fusibile di ricambio    | RESERVE  | F4                                   |
|                         | F5       | T 4 A, 500 V, 10 KA / 10 mm x 38 mm  |
|                         | F6       | T 4 A, 500 V, 10 KA / 10 mm x 38 mm  |
| **CONNETTORE DI PROVA 2** | F1       | T 25 A, 500 V, 10 KA / 10 mm x 38 mm |
|                         | F2       | T 4 A, 500 V, 10 KA / 10 mm x 38 mm  |
|                         | F3       | T 4 A, 500 V, 10 KA / 10 mm x 38 mm  |

Fig. 6. Vano batteria

## 5.4. Disposizione display

In generale la stessa disposizione del display viene usata per tutte le funzioni, consentendo all’utente di trovare tutte le informazioni necessarie in modo semplice e veloce. Per la disposizione vedi la figura riportata qui di seguito:

Fig. 7. Disposizione del display

Legenda:
1.  .......Codice del punto di misura (P) nel modo funzionamento memoria.
2.  .......Codice della linea di misura (L) nel modo funzionamento memoria.
3.  .......Numero di serie della successiva posizione libera quando si memorizzano risultati o numero del codice di identificazione selezionato quando si richiamano i risultati memorizzati.
4.  .......6 x significato dei tasti funzione da `F1` a `F6`.
5.  .......Punto esclamativo, segnala una condizione anomala quando i risultati, i parametri o le condizioni di misura non rientrano nei limiti impostati.
6.  .......Spiegazione del punto esclamativo.

> **NOTA!**
>
> *   La disposizione del display descritta è valida per tutte le funzioni tranne che per l’analisi RCD. Fare riferimento al capitolo 6.7.5 per la disposizione di tale funzione.

## 5.5. Pulizia dello strumento

Per la pulizia dello strumento utilizzare un panno morbido e asciutto. Non usare mai panni umidi, solventi, acqua, ecc.

## 5.6. Fine vita

Attenzione: il simbolo riportato indica che l'apparecchiatura ed i suoi accessori deve essere raccolta separatamente e trattata in modo corretto.

# 6. ISTRUZIONI PER L’USO

## 6.1. Prova PE

Nel caso il conduttore PE risulti interrotto o collegato alla tensione di fase, la situazione potrebbe essere molto pericolosa. Per questo motivo le condizioni del terminale PE devono essere verificate prima di effettuare qualsiasi altra misura.

Come eseguire la prova?
*   Collegare i puntali come da figura di seguito riportata

**o** Usare solo il CONNETTORE DI PROVA 1!

Fig. 7b. Collegamento puntali

*   Toccare l’elettrodo PE su pannello frontale dello strumento.
*   Se viene visualizzato il messaggio "Tensione pericolosa PE presente al terminale PE!" accompagnato dal suono bip-bip.., significa che è presente una tensione pericolosa sul cavo di misura PE/L3 o sul terminale PE della spina shuko oppure che il terminale PE non è collegato.
*   **o** Prestare la massima attenzione nell’eliminazione della tensione pericolosa dal terminale PE.

> **NOTE!**
>
> *   Il `MAXTEST` deve essere acceso per verificare il terminale PE.
> *   Colui che prova il terminale PE deve essere collegato a terra (in piedi sul pavimento).
> *   La prova PE non è attiva nelle funzioni: `LOW Ω 10A`, `VOLTAGE DROP` e `PHASE ROTATION`!

## 6.2. Prova continuità dei conduttori di protezione, dei conduttori equipotenziali ecc. con una corrente di prova di 200 mA c

La misura viene eseguita secondo le norme VDE 0413 parte 4 e CEI 64.8 612.2. Due misure (due polarità) vengono effettuate per ciascun risultato visualizzato calcolato come valore medio di entrambi i risultati parziali. Prima di iniziare la misura è consigliabile cortocircuitare i puntali di misura e verificare se la resistenza dei puntali è compensata (valore 0). In caso negativo, effettuare la compensazione per eliminare la resistenza dei puntali e dei cavi di misura oltre che la resistenza interna dello strumento.

La procedura per la compensazione della resistenza dei puntali è la seguente:
*   Cortocircuitare i puntali di misura.
*   Posizionare il selettore su `LOW Ω 200mA c`.
*   Premere il tasto `F1` ⇒ viene prima visualizzato il valore della resistenza misurata e successivamente 0.00 a significare che lo strumento ha compensato il valore della resistenza del circuito di misura ed è pronto per le misure.

> **NOTA!**
>
> *   La compensazione è valida solo per la funzione `LOW Ω 200mA c`.

Come eseguire la misura?
*   Posizionare il selettore su `LOW Ω 200mA c`.
*   Collegare i puntali all’oggetto da misurare (vedi fig. 8).
*   Controllare il valore max HI e modificarlo se necessario (vedi procedura alla fine di questo paragrafo).
*   Premere il tasto `START` e tenerlo premuto finché il risultato si è stabilizzato.
*   Memorizzare il risultato per successive consultazioni (vedi procedura al paragrafo 6.13).

Fig.8 Collegamento puntali

Presentazione del risultato:

Fig.9. Presentazione del risultato LOW Ω 200mA c

*   `R+` ...... risultato parziale quando la polarità positiva della tensione di prova viene applicata al terminale L.
*   `R-` ....... risultato parziale quando la polarità negativa della tensione di prova viene applicata al terminale N.
*   `Im` ....... corrente di prova

> **NOTE!**
>
> *   Se ai puntali è presente una tensione superiore a 10V non verrà effettuata la misura `LOW Ω` dopo aver premuto il tasto `START` ma verrà visualizzato il simbolo "`o`".
> *   In caso di malfunzionamento dello strumento controllare il fusibile `F4` sotto il coperchio vano batteria (vedi capitolo 5.3).

Ciascun risultato visualizzato viene confrontato con il valore max preimpostato (HI) e nel caso che il risultato sia maggiore, viene visualizzato "`o > X`".
`X` ........ preimpostare il valore max HI

Come impostare il valore max HI?
*   Premere il tasto `F2`, viene presentato il valore precedente.

Fig.10. Presentazione dell’inserimento del valore max HI

*   Inserire quello nuovo mediante la tastiera numerica.
*   Premere il tasto `F1`.
*   Usare gli altri tasti `F2-F3` come segue:
    *   `F2` per annullare l’inserimento.
    *   `F3` per non inserire alcun valore max

## 6.3. Misura resistenza di isolamento con tensione di prova di 250V, 500V o 1000V

La misura viene eseguita secondo le norme VDE 0413 parte 1 e CEI 64.8 612.3. Prima di iniziare la misura, è consigliabile verificare l'assenza della tensione di rete nel circuito da esaminare. Al termine della prova lo strumento effettua la scarica automatica del circuito.

> **ATTENZIONE!**
> Non scollegare i puntali durante la misura, il circuito da misurare potrebbe rimanere carico causa della capacità parassita dell'impianto ⇒ tensione pericolosa.

Come eseguire la misura?
*   Posizionare il commutatore su `Riso`.
*   Collegare i puntali all’oggetto da misurare (vedi da fig.11 a fig.15).
*   Selezionare la tensione di prova adeguata mediante il tasto `F1`.
*   Verificare i valori min LO e max HI e modificarli se necessario (vedi procedura alla fine di questo paragrafo).
*   Premere il tasto `START` e tenerlo premuto finché il risultato non si è stabilizzato.
*   Memorizzare il risultato per successive consultazioni (vedi procedura al paragrafo 6.13).

Fig.11. Misura di isolamento di un cavo coassiale

Fig.12. Misura di isolamento di un impianto

Fig.13. Misura di isolamento di un quadro

Fig.14. Misura di isolamento di pavimenti di locali ad uso medico a maggior rischio di incendio

Fig.15. Misura di isolamento di luoghi non conduttori

Presentazione del risultato:

Fig.16. Presentazione del risultato Riso

*   `Um` ....... tensione di prova

> **NOTA!**
>
> *   Se ai puntali è presente una tensione superiore a 30V non verrà effettuata la misura `ISOLAMENTO` dopo aver premuto il tasto `START` ma verrà visualizzato il simbolo "`o`".

Ciascun risultato visualizzato viene confrontato con i valori preimpostati max (HI) e min (LO) e in caso il risultato sia fuori dai limiti prefissati, allora viene visualizzato il simbolo "`o > X`" o "`o < Y`".
`X` .......... valore max preimpostato HI
`Y` .......... valore minimo preimpostato LO

Come impostare i valori max HI e min LO?
*   Premere il tasto `F2`, viene presentato il valore precedente.

Fig.17. Presentazione dell’inserimento del valore HI o LO

*   Inserire quello nuovo mediante la tastiera numerica.
*   Premere il tasto `F1`.
*   Usare gli altri tasti `F2-F3` come segue:
    *   `F2` per annullare l’inserimento.
    *   `F3` per non inserire massimi e minimi.

## 6.4. Misura della resistenza di terra

La misura viene eseguita secondo le norme VDE 0413 parte 7 e CEI 64.8 612.6.2 utilizzando un generatore interno. La tensione di misura del generatore interno è di forma sinusoidale, la corrente di misura è inferiore a 10mA. Secondo il sistema a quattro fili, possono essere eseguiti collegamenti diversi ai circuiti di misura, inoltre è possibile misurare la resistività del terreno. Di seguito sono riportati alcuni dei collegamenti più frequenti per la misura della resistenza di terra.

Fig.18. Metodo a due picchetti per la misura della resistenza di terra

Fig.19. Metodo a due fili per la misura della resistenza di terra tra i terminali N e PE direttamente nella presa

Fig.20. Metodo a due fili per la misura della resistenza di terra tra i terminali N e PE

Fig.21. Metodo a tre picchetti per la misura della resistenza di terra

Procedura per eseguire la misura della resistenza di terra:
*   Posizionare il selettore su `EARTH`.
*   Realizzare uno degli schemi visti sopra.
*   Selezionare la funzione `EARTH R` mediante il tasto `F1`.
*   Selezionare il sistema a 2, 3 picchetti mediante il tasto `F2`, l'indicazione del metodo di misura non influenza comunque il risultato della stessa, serve solo a scopo documentale.
*   Controllare il valore max HI ed modificarlo se necessario (vedi procedura alla fine di questo paragrafo).
*   Premere il tasto `START` e tenerlo premuto finché il risultato si è stabilizzato.
*   Memorizzare il risultato per successive consultazioni (vedi procedura al paragrafo 6.13).

Presentazione del risultato:

Fig.22. Presentazione del risultato EARTH R

*   `Rc` ......... Resistenza dei picchetti di corrente (vedi caratteristiche tecniche).
*   `Rp` ........ Resistenza dei picchetti di tensione (vedi caratteristiche tecniche).

> **NOTA!**
>
> *   Se ai terminali E, H è presente una tensione superiore a 30V non verrà effettuata la misura `EARTH R` dopo aver premuto il tasto `START` ma verrà visualizzato il simbolo "`o`".

Ciascun risultato visualizzato è confrontato con il valore max preimpostato (HI) ed in caso il risultato sia maggiore viene visualizzato "`o > X`".
`X` .......... Valore max preimpostato HI

Come impostare il valore max HI?
*   Premere il tasto `F3`, viene presentato il valore precedente.

Fig.23. Presentazione dell’inserimento del valore max HI

*   Inserire quello nuovo mediante la tastiera numerica.
*   Premere il tasto `F1`.
*   Usare gli altri tasti `F2-F3` come segue:
    *   `F2` per annullare l’inserimento
    *   `F3` per non inserire massimi e minimi

## 6.5. Resistività del terreno

Per progettare un sistema di protezione di terra, si deve conoscere prima la resistività del terreno. Questo è un parametro base che aiuta il progettista a determinare le dimensioni del sistema di terra e la sua profondità di realizzazione, per questo motivo la resistività del terreno deve essere misurata tenendo in considerazione diverse profondità. Maggiore è la distanza `a`, più profondo è lo strato del terreno che viene preso in considerazione.

Fig.24. Misura della resistività del terreno

Procedura per eseguire la misura della resistività del terreno:
*   Posizionare il selettore su `EARTH`.
*   Realizzare il collegamento superiore.
*   Selezionare la funzione `EARTH ρ` mediante il tasto `F1`.
*   Selezionare la distanza tra i due picchetti di terra "a" mediante il tasto `F2`, che può essere impostato da 1 fino a 30m.
*   Premere il tasto `START` e tenerlo premuto finché il risultato si è stabilizzato.
*   Memorizzare il risultato per successive consultazioni (vedi procedura al paragrafo 6.13).

Presentazione del risultato:

Fig.25. Presentazione del risultato EARTH ρ

*   `3m` ........ Distanza "a" tra due picchetti.
*   `Rc` ......... Resistenza dei picchetti di corrente (vedi caratteristiche tecniche).
*   `Rp` ........ Resistenza potenziale dei picchetti (vedi caratteristiche tecniche).

> **NOTA!**
>
> *   Se ai terminali E, H è presente una tensione superiore a 30V non verrà effettuata la misura `EARTH ρ` dopo aver premuto il tasto `START` ma verrà visualizzato il simbolo "`o`".

## 6.6. Senso ciclico delle fasi

La misura viene eseguita secondo le norme VDE 0413 parte 9. La misura consente di determinare se le fasi provocano una rotazione oraria (e quindi corretta) o antioraria di un eventuale motore ad esse connesso. Per effettuare la misura occorre realizzare il collegamento della figura seguente.

Fig.26. Collegamento per la verifica del senso ciclico delle fasi

*   Posizionare il selettore su `PHASE ROTATION`
*   Realizzare il collegamento della figura sopra.
*   Premere il tasto `START`.
*   Memorizzare il risultato per successive consultazioni (vedi procedura al paragrafo 6.13).

La rotazione delle fasi è in accordo con la marcatura dei cavi di misura (corretta).
La rotazione delle fasi non è in accordo con la marcatura misura (errata).
Fasi non corrispondenti ad un sistema trifase o assenza di una (o due) fasi.

Presentazione del risultato:

Fig.27. Presentazione del risultato PHASE ROTATION

*   `U1-2` .......... tensione di rete tra fase 1 e 2
*   `U2-3` .......... tensione di rete tra fase 2 e 3
*   `U3-1` .......... tensione di rete tra fase 3 e 1

## 6.7. Impedenza di linea o dell’anello di guasto e corrente di corto-circuito presunta

La misura viene effettuata secondo le norme VDE 0413 parte 3, IEC 781 e CEI 64.8 612.6.3.

Perché misurare l’impedenza di linea o dell’anello di guasto e la corrente di corto-circuito presunta?
*   Per verificare l'adeguatezza dei dispositivi di intervento (fusibili, magneto/termici) usati (corrente nominale e potere di interruzione della corrente di corto-circuito).
*   Per dimensionare il dispositivo di protezione.
*   Per verificare il dimensionamento dei cavi di alimentazione.
*   Per eliminare contatti difettosi (la misura viene eseguita mediante impulso ad alta corrente)

Perché misurare l’impedenza anziché la resistenza?

Fig.28. Circuito equivalente di un impianto monofase

Se la misura viene effettuata vicino al trasformatore, o una certa induttanza è collegata in serie al trasformatore, la componente reattiva dell’impedenza ha un valore non trascurabile e modifica in modo significativo il valore dell'impedenza e conseguentemente la corrente di corto-circuito presunta che da essa viene calcolata. Ecco perché l’impedenza rappresenta il parametro corretto per il calcolo della corrente di corto-circuito. La corrente di corto-circuito viene calcolata al valore nominale della tensione di rete, o al valore inserito manualmente se lo strumento rileva un valore di tensione non standard.

Come eseguire la misura?
*   Posizionare il selettore su `Z LINE` (L-N, L-L) o `Z LOOP` (L-PE)
*   Collegare i puntali come segue:

Fig.29a. Collegamento con puntali per misure Z LINE (LN) o Z LOOP

Fig.29b. Collegamento con puntali per misure Z LINE (LL)

Fig.30. Collegamento cavo a spina per misure di Z LINE o Z LOOP

*   Qualora sia necessario misurare la tensione di contatto fra una massa estranea e la massa del punto di misura utilizzare la funzione `Z LOOP` ed il collegamento di Fig.31.

Fig.31.Tensione di contatto alla corrente di corto-circuito (solo per la funzione Z LOOP)

*   Impostare il collegamento appropriato L-N o L-L mediante il tasto `F1` (solo per la funzione `Z LINE`).
*   Selezionare la polarità adeguata dell’impulso di prova (solo per la funzione `Z LOOP`) mediante il tasto `F1` per evitare l’intervento del differenziale se esso è sensibile ad una sola polarità (solo per differenziali di tipo AC).
*   Premere il tasto `START` e leggere il risultato, se è stato collegato il terminale `PROBE` (fig. 31) compare anche la tensione di contatto `Ub/Ik`.
*   Memorizzare il risultato per successive consultazioni (vedi procedura al paragrafo 6.13).

Presentazione del risultato:

Fig.32. Presentazione del risultato Z LINE

Fig.33. Presentazione del risultato Z LOOP

*   `I K` .......... Corrente di corto-circuito presunta (standard, massima o minima)
*   `i p` ........... Valore di picco della corrente di corto-circuito presunta (visualizzata solo se viene selezionata la corrente di corto-circuito presunta massima)
*   `R` .......... Parte resistiva dell’impedenza visualizzata
*   `X L` ......... Parte induttiva dell’impedenza visualizzata
*   `U B *` ....... Tensione di contatto alla corrente di corto-circuito presunta selezionata - viene visualizzata se il terminale `PROBE` è collegato (funzione `Z LOOP` fig. 31).
*   `Um` ....... Tensione di rete misurata.
*   `f` ............ Frequenza della tensione di rete misurata.

\* La misura di `U B` viene eseguita automaticamente e riportata al valore della `Ik` visualizzata nel caso il cavo di misura sia opportunamente collegato alla boccola `PROBE` (cfr fig.31). Sia prima che dopo aver effettuato la misura è possibile selezionare la corrente di corto - circuito presunta da visualizzare e salvare mediante i tasti `F2 - F6`. I calcoli per tutti i tipi di `I K` sono descritti al capitolo 4.1 (Funzioni).

Le abbreviazioni sul display hanno il seguente significato:
*   `STD`................Corrente di corto-circuito/guasto presunta standard
*   `MAX` ..............Corrente di corto-circuito/guasto presunta massima monofase
*   `MIN` ...............Corrente di corto-circuito/guasto presunta minima monofase
*   `MAX-3ph` ......Corrente di corto-circuito presunta massima trifase
*   `MAX-2ph` ......Corrente di corto-circuito presunta massima bifase
*   `MIN-3ph` ........Corrente di corto-circuito presunta minima trifase
*   `MIN-2ph` ........Corrente di corto-circuito presunta minima bifase

> **NOTA!**
>
> *   Se il differenziale interviene durante una misura di `Z LOOP`, viene visualizzato il messaggio: "`o RCD APERTO`".

## 6.8. Parametri dei differenziali

### 6.8.1. Principi teorici di funzionamento dei differenziali

Fig. 34.Collegamento sistema TT

*   `R N` ......... resistenza di terra del trasformatore
*   `R T` ......... resistenza del secondario del trasformatore

Se una porzione della corrente di fase si disperde attraverso un cattivo isolamento verso la carcassa di un apparecchio e da qui a terra, può comparire una tensione di contatto `U B` pericolosa attraverso la resistenza di terra `R E`. Poiché le forme della corrente di dispersione possono essere molteplici, per es. alternata, ad impulsi (con tensioni a semionda ed onda intera raddrizzata), continua (con tensione trifase raddrizzata) ecc., il `MAXTEST` ha la possibilità di selezionare varie forme della corrente, oltre a consentire di impostare la polarità della corrente di guasto (positiva o negativa).

### 6.8.2. Misura della tensione di contatto U B

Per ottemperare alle norme di sicurezza, la misura della tensione di contatto `U B` deve essere eseguita come misura indipendente o come funzione ausiliaria prima della misura del tempo di intervento o della corrente di intervento. Due diversi valori di `U B` sono riconosciuti come limite di sicurezza:
*   50 V ... generale
*   25 V ... ospedali, impianti zootecnici, piscine ecc.

Questo è il motivo per cui tutti i risultati di `U B` sono confrontati con il valore di riferimento (25 o 50 V) di `U B` preselezionato. La prova di `U B` viene effettuata secondo le norme VDE 0413 parte 6 e CEI 64.8 capitolo 61, appendice D. Il differenziale non interviene durante a prova perché la misura viene effettuata al 40% della corrente di guasto nominale, mentre il risultato visualizzato viene calcolato al valore nominale di corrente di guasto (differenziale di tipo generale), o al doppio della corrente nominale (differenziale di tipo selettivo n). Il valore visualizzato viene misurato rispetto alla terra del trasformatore se il terminale `PROBE` non viene usato o rispetto al terminale `PROBE` se esso è collegato secondo la fig. 35.

Come eseguire la misura?
*   Posizionare il selettore su `RCD Voltage UB /Time t`.
*   Collegare i puntali secondo la figura di seguito indicata. Se il terminale `PROBE` dello strumento è collegato a terra mediante il picchetto ausiliario, `U B` viene misurata rispetto a quel picchetto e si raggiunge una maggiore precisione del risultato, in caso contrario, la tensione di contatto viene misurata rispetto alla terra del neutro del trasformatore mediante il terminale di fase.

Fig.35. Collegamento cavi per la misura di Ub con il terminale PROBE

*   Selezionare la funzione `RCD U B` mediante il tasto `F1`.
*   Selezionata la corrente di guasto nominale adeguata mediante il tasto `F2`.
*   Selezionare il differenziale di tipo generale o selettivo mediante il tasto `F3`.
*   Selezionare il valore adeguato di `U B lim` mediante il tasto `F4`.
*   Premere il tasto `START`.
*   Memorizzare il risultato per successive consultazioni (vedi istruzioni al paragrafo 6.13).

Presentazione del risultato:

Fig.36. Presentazione del risultato RCD U B

*   `R E` ......... Resistenza di terra (se viene usato il terminale PROBE)
    *   `R E` (sistema TT) = `R E`
    *   `R L` (sistema TN) = `R NEUTRO`

*   `R L` ......... Resistenza dell’anello (se non viene usato il terminale PROBE)
    *   `R L` (sistema TT) = `R N` + `R T` + `R FASE` + `R E`
    *   `R N` + `R T` + `R FASE` << `R E` ⇒ `R L` ≅ `R E`
    *   `R L` (sistema TN) = `R T` + `R FASE` + `R NEUTRO`.
*   `R N` ......... resistenza di terra del trasformatore.
*   `R T` ......... resistenza del secondario del trasformatore.
*   `R PHASE` ... resistenza del conduttore di fase.
*   `R E` ......... resistenza di terra dell’oggetto in esame.
*   `Um` ....... Tensione di rete.
*   `f` ............ Frequenza della tensione di rete.

> **NOTE!**
>
> *   I parametri impostati vengono memorizzati e sono validi anche per le altre funzioni differenziali dove richiesto.
> *   Se le tensioni L-N e L-PE non rientrano nei limiti di tolleranza 100 ÷ 250V o se la frequenza di rete è fuori dal campo 45 ÷ 65Hz verrà visualizzato il simbolo "`o`"
> *   Se il terminale PE non è collegato quando si preme il tasto `START`, viene visualizzato il messaggio "`o PE assente`".

### 6.8.3. Misura del tempo di intervento t FI

La prova dovrà essere effettuata a metà, a una volta e a 5 volte la corrente nominale. I tempi di intervento devono corrispondere alla tabella riportata di seguito, tratta dalla tabella 2 della norma IEC 1009-1.

Come eseguire la misura?
*   Posizionare il selettore su `RCD Voltage UB /Time t`.
*   Selezionare la funzione `RCD t` mediante il tasto `F1`.
*   Selezionare la corrente di guasto nominale opportuna mediante il tasto `F2`.
*   Selezionare il moltiplicatore della corrente di guasto nominale opportuno mediante il tasto `F3`.
*   Selezionare la forma adeguata della corrente di guasto mediante il tasto `F4`, vedi fig.38 per le diverse forme della corrente di guasto.
*   Selezionare il tipo di differenziale, generale o selettivo, mediante il tasto `F5`.
*   Controllare il valore `U Blim` impostato e modificarlo se necessario mediante il tasto `F6`.
*   Collegare i cavi secondo la fig.35.
*   Premere il tasto `START`.
*   Memorizzare il risultato per successive consultazioni (vedi istruzioni al paragrafo 6.13).

Tabella dei tempi di intervento massimi secondo la tabella 2 delle IEC 1009-1

| Tipo differenziale | I ∆ N | 2I ∆ N | 5I ∆ N | Osservazioni                     |
| :----------------- | :---- | :----- | :----- | :------------------------------- |
| Generale           | 0,3   | 0,15   | 0,04   | Tempo di intervento max          |
| Selettivo          | 0,5   | 0,2    | 0,15   | Tempo di intervento max          |
|                    | 0,13  | 0,06   | 0,05   | Tempo di ritardo di intervento min |

\* Per valori nominali `I ∆ N` ≤ 30mA la corrente di prova a 5 volte è 0,25A. A ½`I ∆ N` il differenziale non deve intervenire in nessun caso.

Presentazione del risultato:

Fig.37. Presentazione del risultato RCD t del tempo di intervento

*   `U B` ........... Tensione di contatto misurata rispetto alla terra del trasformatore se il terminale `PROBE` non viene usato o rispetto al terminale `PROBE` se esso è collegato secondo la fig. 36.
*   `R E` ........... Resistenza di terra (vedi legenda fig. 36)
*   `R L` ........... Loop resistance (vedi legenda fig. 36)
*   `Um` ......... Tensione di rete
*   `f` ............... Frequenza della tensione di rete

> **NOTES!**
>
> *   Per avviare la corrente di guasto con polarità negativa premere il tasto `START` due volte in successione.
> *   Il differenziale selettivo contiene un circuito di integrazione della corrente di dispersione per consentirgli di intervenire in ritardo, per questo motivo la norma prescrive che debba trascorrere un tempo di 60s fra due prove (ridotto a 30s nel caso di prove a ½ `I ∆ N`). Ecco perché il `MaxTest` deve attendere 30 s prima di raggiungere il risultato finale eliminando l’influenza della corrente di prova per la misura della tensione di contatto.
> *   Se il terminale PE non è collegato quando si preme il tasto `START`, viene visualizzato il messaggio "`o PE assente`".

Di seguito sono raffigurate le varie forme d'onda della corrente di guasto disponibili sul `MaxTest`.

a) Forma alternata (fase iniziale 0°)

Fig. 38a. Corrente di guasto alternata (fase iniziale 0°)

b) Forma alternata (fase iniziale 180°)

Fig. 38b. Corrente di guasto alternata (fase iniziale 180°)

c) Forma ad impulsi (fase 0°)

Fig. 38c. Corrente di guasto ad impulsi (fase 0°)

d) Forma ad impulsi (fase 180°)

Fig. 38d. Corrente di guasto ad impulsi (fase 180°)

e) Forma continua pura (fase 0°)

Fig. 38e. Corrente di guasto pura continua (fase 0°)

f) Forma continua pura (fase 180°)

Fig. 38f. Corrente di guasto pura continua (fase 180°)

<!-- Chunk: Pages 49-72 -->
### 6.8.4. Misura della corrente di intervento I ∆
La misura della corrente di intervento è possibile solo nei differenziali di tipo generale.

#### Come eseguire la misura?
- Posizionare il selettore su RCD Current I ∆.
- Selezionare la corrente di guasto nominale adeguata mediante il tasto F1.
- Selezionare la forma adeguata della corrente di guasto mediante il tasto F2, vedi fig. 38 per diverse forme di corrente di guasto.
- Selezionare il valore U Blim adeguato mediante il tasto F3.
- Collegare i puntali secondo la fig. 35.
- Premere il tasto **START**.
- Memorizzare il risultato per successive consultazioni (vedi istruzioni al paragrafo 6.13).

#### Presentazione del risultato:
*Fig.39. Presentazione del risultato della corrente di intervento I ∆, t*
- **t** ............ Tempo di intervento alla corrente di intervento visualizzata
- **U B/I** ...... Tensione di contatto alla corrente di intervento visualizzata (vedi legenda fig. 37)
- **R E** ......... Resistenza di terra (vedi legenda fig. 36)
- **R L** ......... Resistenza dell’anello (vedi legenda fig. 36)

**NOTA!**
- Per attivare la corrente di guasto alla polarità negativa premere il tasto START due volte in successione (vedi fig. 38 per le diverse forme e polarità della corrente di guasto).
- Se il terminale PE non è collegato quando si preme il tasto START, viene visualizzato il messaggio "o PE assente".

### 6.8.5. Analisi differenziali
Per provare automaticamente tutti i più importanti parametri dei differenziali (scopi ispettivi) in un unica soluzione è possibile utilizzare la funzione analisi differenziali.

#### Come eseguire la prova?
- Posizionare il selettore su **RCD Analysis**.
- Selezionare la corrente di guasto nominale adeguata mediante il tasto **F1**.
- Selezionare la forma adeguata della corrente di guasto mediante il tasto **F2**, vedi fig. 38 per forme diverse di corrente di guasto.
- Selezionare il tipo di differenziale generale o selettivo mediante il tasto **F3**.
- Verificare il valore U Blim impostato e modificarlo se necessario mediante il tasto **F4**.
- Collegare il cavo di prova secondo la fig. 35.
- Premere il tasto **START** e successivamente seguire le istruzioni a display cioè riarmare il differenziale quando richiesto.
- Verificare il risultato al termine della procedura e memorizzarlo per successive consultazioni (vedi istruzioni al paragrafo 6.13).

#### Presentazione del risultato:
*Fig.40. Presentazione del risultato di analisi differenziali*
- **U B/I** ................Tensione di contatto (vedi legenda fig. 37)
- **R E** ...................Resistenza di terra (vedi legenda fig. 36)
- **R L** ...................Resistenza dell’anello (vedi legenda fig. 36)
- **x 1/2, 1, 5** .......Moltiplicatori della corrente nominale
- .............Forma e fase iniziale della corrente di guasto

**NOTE!**
- La funzione Analisi Differenziali, nel caso di prove con forma d'onda **c**, è attiva solo per I ∆ N = 10 mA e I ∆ N = 30 mA.
- Se il terminale PE non è collegato quando si preme il tasto START, viene visualizzato il messaggio "o PE assente".

### 6.9. Misura della caduta di tensione
La caduta di tensione come conseguenza del flusso di corrente attraverso un impianto o una parte dell’impianto o installazione può essere molto importante se si desidera:
- Verificare la capacità dell’impianto esistente di alimentare un certo carico,
- Dimensionare un nuovo impianto,
- Trovare il motivo di malfunzionamenti su dispositivi elettrici, attrezzature, macchine ecc.

#### Come eseguire la misura?
- Collegare i puntali secondo la figura di seguito riportata:
*Fig.41. Collegamento puntali*
- Posizionare il commutatore su **VOLTAGE DROP**.
- Premere il tasto **START**.
- Leggere il risultato e memorizzarlo per successive consultazioni (vedi istruzioni al paragrafo 6.13).

#### Presentazione del risultato:
*Fig.42. Presentazione del risultato di VOLTAGE DROP*
- **U 1** ......... Tensione tra i terminali C1, C2 (terminali ES, E)
- **U 2** ......... Tensione tra i terminali P1, P2 (terminali S, H)

**NOTE!**
- Se i terminali di fase e neutro sono scambiati all’ingresso o all’uscita, viene visualizzato "o CONNECTION".
- Se le tensioni U1, U2 o entrambe sono inferiori a 100V, viene visualizzato "o Uin < 100V".

Ciascun risultato visualizzato viene confrontato con il valore max preimpostato (HI) e nel caso il risultato sia maggiore,viene visualizzato "o > X".
**X** .......... valore max preimpostato HI

#### Come impostare il valore max HI?
- Premere il tasto F1, viene presentato il valore precedente.
*Fig. 43. Presentazione dell’inserimento del valore max HI*
- Inserire quello nuovo mediante la tastiera numerica.
- Premere il tasto **F1**.
- Usare gli altri due tasti come segue **F2-F3**:
    - **F2** per annullare l’inserimento
    - **F3** per non inserire valori limite

### 6.10. Misura dell’impedenza ad elevata precisione
Quando è necessario un valore di impedenza ad elevata precisione o quando si ha un valore molto basso, deve essere utilizzata una corrente di prova elevata per garantire una considerevole caduta di tensione durante la prova.

#### Come eseguire la misura?
- Posizionare il selettore su Z2 Ω Im=280A max
- Collegare i puntali come da figura di seguito riportata:
- Selezionare il collegamento adeguato L-L, L-N o L-PE mediante il tasto F1.
- Nel caso di prova L-PE con terminale PROBE inserito è importante che siano effettivamente i cavi P2, C2 quelli connessi a terra altrimenti il risultato Ub/IK non verrebbe fornito. Per verificarlo dopo aver effettuato il collegamento toccare l'elettrodo PE, se lo strumento dovesse dare un avviso sonoro invertire le coppie di cavi.
*Fig. 45. Collegamento dei puntali*
*Fig. 46. Collegamento dei puntali*
- Premere il tasto **START** e attendere il tempo necessario ad effettuare 12 misure.
- Leggere il risultato e memorizzarlo per successive consultazioni (vedi istruzioni al paragrafo 6.13).

#### Presentazione del risultato:
*Fig.47. Presentazione del risultato di impedenza ad elevata precisione*
- **I K** .......... Corrente di corto-circuito presunta (standard, massima o minima)
- **i p** ........... Valore di picco della corrente di corto-circuito presunta(visualizzato se viene selezionata la corrente di corto-circuito presunta massima)
- **R** .......... Parte resistiva dell’impedenza
- **X L** ......... Parte induttiva dell’impedenza
- **U B** ......... Tensione di contatto alla corrente di corto-circuito presunta selezionata, viene visualizzata se è stato selezionato il collegamento L-PE ed il terminale **PROBE** è collegato come da fig. 46.
- **Um** ....... Tensione di rete
- **f** ............ Frequenza della tensione di rete

Selezionare sul display la corrente di corto-circuito presunta opportuna mediante i tasti da F2 a F6. Per le spiegazioni vedi capitolo 6.7 (Impedenza di linea e dell’anello di guasto).

### 6.11. Prova continuità del conduttore di protezione, del conduttore equipotenziale ecc. mediante corrente di prova di 10A b
La misura viene effettuata secondo le norme VDE 0113, VDE 0701, CEI 64.4, CEI EN 60204-1 e CEI 34-21 parte 7.2.3. Una corrente di prova AC 50 Hz viene usata per determinare sia la resistenza che la caduta di tensione. Sono disponibili due tipi di misura:
- Resistenza
- Caduta di tensione riferita a 10A e durata di prova automatica di 11s.

#### a) Resistenza
- Posizionare il selettore su LOW Ω **10A b**.
- Selezionare LOW Ω **10A b** - funzione R mediante il tasto F1.
- Collegare i puntali all’oggetto in esame secondo la figura di seguito riportata:
*Fig. 48. Collegamento puntali*
- Controllare il valore max Hi e modificarlo se necessario (vedi procedura alla fine di questo paragrafo).
- Premere il tasto **START**.
- Memorizzare il risultato per successive consultazioni (vedi istruzioni al paragrafo 6.13).

#### Presentazione del risultato:
*Fig. 49. Presentazione del risultato di LOW Ω 10A b -R*
- **Um** ....... tensione di prova
- **Im** ......... corrente di prova

**NOTA!**
- Se è presente una tensione maggiore di 10V ai terminali di prova P1, P2, la misura non verrà eseguita dopo aver premuto il tasto START ma sarà visualizzato "o Uin > 10V".

Ciascun risultato visualizzato viene confrontato con il valore max (HI) preimpostato e nel caso il risultato fosse maggiore, viene visualizzato "o > X".
**X** .......... valore max preimpostato HI

#### Come impostare il valore max HI?
- Premere ill tasto **F2**, viene presentato il valore precedente.
*Fig. 50. Presentazione dell’inserimento del valore max HI*
- Inserire quello nuovo mediante la tastiera numerica.
- Premere il tasto **F1**.

#### b) Caduta di tensione riferita a 10A con durata della prova automatica di 11s:
- Posizionare il selettore su LOW Ω **10A b**.
- Selezionare la funzione VOLTAGE DROP **10A b** mediante il tasto **F1**.
- Selezionare la sezione del cavo adeguata mediante il tasto **F2**.
- Collegare i puntali all’oggetto in esame come da figura di seguito riportata.
- Premere il tasto **START**, attendere 11s e leggere il risultato.
- Memorizzare il risultato per successive consultazioni (vedi procedura al pragrafo 6.13).
*F ig. 51. Collegamento puntali per la misura della caduta di tensione a 10A b*

#### Presentazione del risultato:
*Fig. 52. Presentazione del risultato VOLTAGE DROP 10A b*
- **R** ................. Resistenza di prova
- **Im** ................ Corrente di prova
- **1mm²/3.3V** .. Sezione inserita del cavo e caduta di tensione max secondo le norme CEI EN60204-1

**NOTE!**
- Se la tensione presente ai terminali P1, P2 è maggiore di 10V, la misura non verrà eseguita dopo aver premuto il tasto START ma sarà visualizzato "o Uin > 10V".
- Per interrompere la prova prima dello scadere degli 11 secondi ruotare il commutatore funzioni.

### 6.12. Misure mediante adattatore trifase
Per eseguire vari tipi di misura sul sistema trifase, può essere usato l’ADATTATORE TRIFASE. Nella tabella seguentesono elencate le funzioni che possono essere eseguite con l’adattatore.
*Fig. 53. Collegamento cavo di misura*

| Funzione               | Posizione del selettore del MAXTEST | Posizione del selettore dell’ADATTATORE |
| :--------------------- | :---------------------------------- | :-------------------------------------- |
| Z LINE                 | L1-N L2-N L3-N                      | Z LINE L1 N/PE L2 N/PE L3 N/PE          |
| Z LINE                 | L1-L2 L2-L3 L3-L1                   | Z LINE L1 L2 L2 L3 L3 L1                |
| Z LOOP                 | L1-PE L2-PE L3-PE                   | Z LOOP L1 N/PE L2 N/PE L3 N/PE          |
| R iso                  | L1-N L2-N L3-N                      | R iso L1 N/PE L2 N/PE L3 N/PE           |
| R iso                  | L1-L2 L2-L3 L3-L1                   | R iso L1 L2 L2 L3 L3 L1                 |
| Riso                   | N-PE                                | R iso N PE                              |
| RCD Tensione U B / Tempo t, RCD Corrente I ∆, RCD Analisi | L1-PE L2-PE L3-PE                   | L1 N/PE L2 N/PE L3 N/PE                 |
| Senso ciclico trifase  | PHASE ROTATION                      |                                         |

L’adattatore trifase è un accessorio opzionale che può essere ordinato separatamente (non essendo in dotazione allo strumento).

**NOTA!**
- Usare solo il CONNETTORE DI PROVA 1!

### 6.13. Memorizzazione dei risultati
Nel caso si rendesse necessario verificare diversi parametri di un impianto complesso con numerosi punti di misura sarebbe opportuno preparare uno schema preciso con la numerazione delle linee (L) e dei punti di misura (P) prima di effettuare le misure. Un esempio di tale schema può essere quello che segue:
*Fig. 54. Esempio di schema con punti di numerazione*

Ciascun risultato visualizzato può essere memorizzato mediante la seguente procedura:

**Visualizzazione del risultato di una misura**

1.  **Selezionare il funzionamento di memoria per i tasti F1 - F6** (vedi fig. 55).
2.  Viene presentato il numero della precedente linea di corrente.
3.  **Inserire il numero della linea di corrente desiderata mediante i tasti ↑ / ↓** (visualizzati) o mediante la tastiera numerica.
4.  Viene inserito il numero della nuova linea di corrente.
5.  Viene presentato il numero del precedente punto di misura.
6.  **Inserire il numero del punto di misura desiderato mediante i tasti ↑ / ↓** (visualizzati) o mediante la tastiera numerica.
7.  Viene inserito il numero del nuovo punto di misura.
8.  Il risultato visualizzato viene memorizzato, viene visualizzato il numero progressivo della posizione di memoria successiva da utilizzare per eventuali memorizzazioni. (Ciascun risultato può essere memorizzato una sola volta.)
*Fig. 55. Menu di gestione della memoria per i tasti F1- F6*
9.  **Richiamare il modo funzionale dei tasti funzione F1-F6** se la memorizzazione è terminata (o alcuni parametri della funzione devono essere cambiati.)

**NOTE!**
- Ι codici del punto di misura (P) e della linea di corrente (L) possono essere impostati da 1 fino a 255.
- Se non è necessario memorizzare i punti o le linee di misura, le fasi da 2 a 7 dell'esempio visto sopra possono essere omesse.
- Il numero progressivo del risultato memorizzato tiene in considerazione tutti i risultati indipendentemente dal codice del punto di misura e della linea di corrente.

#### Elenco dei risultati, subrisultati e parametri per ciascuna funzione che possono essere memorizzati e trasferiti al PC o alla stampante:

| Posizione del selettore | Risultato principale | Subrisultati e parametri ( • )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| RCD Voltage U B Time t | RCD U B |
|                        |         | Um                      |
|                        |         | f                       |
|                        |         | **•** Corrente di guasto nominale. |
|                        |         | U Blim                    |
|                        |         | **•** Tipo di differenziale selettivo o generale. |
| RCD Current I ∆        | I ∆     | t                       |
|                        |         | U B/I                   |
|                        |         | R E(L)                  |
|                        |         | Um                      |
|                        |         | f                       |
|                        |         | **•** Corrente di guasto nominale. |
|                        |         | U Blim                    |
|                        |         | **•** Forma della corrente di guasto. |
| RCD Analysis           | t/0.5 I ∆ N,pos | t/0.5 I ∆ N, neg        |
|                        |         | t/I ∆ N,pos             |
|                        |         | t/I ∆ N, neg            |
|                        |         | t/5 I ∆ N,pos           |
|                        |         | t/5 I ∆ N, neg          |
|                        |         | U B                     |
|                        |         | R E(L)                  |
|                        |         | **•** Corrente di guasto nominale RCD. |
|                        |         | **•** Forma della corrente di guasto. |
|                        |         | **•** Differenziale di tipo selettivo o generale. |
|                        |         | U Blim                    |
| VOLTAGE DROP           | ∆ U     | U 1                     |
|                        |         | U 2                     |
|                        |         | f                       |
|                        |         | ........(U 1 o U 2 , qualunque sia il più alto). |
| Z2 Ω Im=280A max       | Z L-N, Z L-PE o Z L-L | i p                     |
|                        |         | I K                     |
|                        |         | R                       |
|                        |         | X L                     |
|                        |         | U m                     |
|                        |         | U B                     |
|                        |         | f                       |
|                        |         | **•** Collegamento L-N, L-PE o L-L. |
| LOW Ω 10A b            | R       | U m                     |
|                        |         | I m                     |
|                        | U       | R                       |
|                        |         | Im                      |
|                        |         | **•** Sezione del cavo e caduta di tensione max. |

### 6.14. Richiamo dei risultati
Per richiamare i risultati memorizzati, seguire le seguenti istruzioni:

1.  **Selezionare il modo memoria per i tasti F1 - F6** (vedi fig. 55).
2.  Viene visualizzato il primo risultato della linea di corrente e del punto di misura usati l'ultima volta per richiamare i dati dalla memoria.
3.  **Premere L se si vuole modificare il numero della linea di corrente** → viene presentato l'ultimo numero della linea di corrente.
4.  **Inserire il numero della linea di corrente desiderata mediante i tasti ↑ / ↓** (visualizzati) o mediante la tastiera numerica.
5.  Viene inserito il nuovo numero della linea di corrente e viene visualizzata la posizione di memoria adeguata.
6.  **Premere se si desidera modificare il numero di posizione di misura** → viene presentato l'ultimo numero del punto di misura.
7.  **Inserire il numero del punto di misura desiderato mediante i tasti ↑ / ↓** (visualizzati) o mediante tastiera numerica.
8.  Viene inserito il nuovo numero del punto di misura e viene visualizzata la posizione di memoria adeguata.
9.  **Controllare gli altri risultati memorizzati con lo stesso numero di linea di corrente e punto di misura mediante i tasti ↑ / ↓** (visualizzati).
10. **Uscita dal modo RECALL**.

**NOTA!**
- Se il risultato memorizzato viene richiamato e visualizzato, il nome della funzione nell’angolo superiore sinistro del display non è in grassetto come nella funzione normale per evidenziare il fatto che si tratta di un valore richiamato dalla memoria.

### 6.15. Comunicazione RS232

#### 6.15.1. Connessioni
- 2. MAX TxD
- 3. MAX RxD
- 5. GND
*Fig. 56 Connettore RS232 MaXtest*
*Fig. 57a Cavo RS232 MaXtest - PC*
*Fig. 57b Cavo RS232 MaXtest - Stampante*
*Fig. 57c Cavo RS232 MaXtest - Stampante*

#### 6.15.2. Collegamento al PC
1.  Collegare il PC al Maxtest mediante il cavo RS232 vedi Fig.57a.
2.  Impostare sul programma di gestione del MaxTest sul PC i parametri di comunicazione come segue: Porta: COM1, COM2 (Selezionare quella impiegata). Velocità baud: Selezionare 4800.
3.  Accendere il Maxtest.
4.  Premere il tasto MENU, per far comparire il menu di gestione della memoria.
5.  Premere il tasto funzione corrispondente a RS232 (F6) → Lo strumento è pronto per ricevere i comandi dal PC.
6.  Premere il tasto funzione corrispondente a BACK (F1) per uscire dal modo comunicazione RS232.

#### 6.15.3. Collegamento a una stampante seriale.
Se si è in possesso di una stampante seriale o di un programma di comunicazione seriale sul PC (es. il programma TERMINALE di Windows - gruppo Accessori) è possibile stampare/ricevere direttamente i risultati utilizzando la seguente procedura:
1.  Collegare lo strumento al PC (cavo seriale fig.57a) o alla stampante (cavo seriale fig.57b).
2.  Impostare sul PC o sulla stampante i parametri di comunicazione: Baud **4800**, Bit **8**, Stop **1**, Parità **nessuna**, C. di flusso **XON/XOFF**
3.  Accendere il MaXtest.
4.  Premere il tasto **MENU**, per far comparire il menu di gestione della memoria.
5.  Premere il tasto funzione corrispondente a **PRT** (F2) per stampare tutta la memoria.
6.  Premere il tasto funzione corrispondente a **PRT L** (F3) per stampare i risultati di una linea (viene richiesto il numero della linea da stampare, inserirlo e confermare con ENTER - F1).
7.  Premere il tasto funzione corrispondente a **PRT LP** (F4) per stampare i risultati di un punto (viene richiesto il numero della linea e di uno dei suoi punti da stampare inserirli e confermare con **ENTER** - F1).

**Note:**
- La linea o il punto da stampare devono esistere!!
- Per abbandonare l'impostazione di un numero di linea o di punto di misura premere il tasto funzione corrispondente a **CANCEL**.
- Per cancellare un numero di linea o di punto di misura inseriti per errore premere il tasto **CE**.
- Durante la stampa nel riquadro corrispondente alla funzione 6 compare un asterisco (*) ad indicare che la stampa è in corso.
- Per arrestare una stampa in corso ruotare il commutatore funzioni.
8.  Premere il tasto funzione corrispondente a **BACK** (F1) per uscire dal modo comunicazione RS232.

### 6.16. Reset dello strumento
In caso di malfunzionamento del MAXTEST è opportuno eseguire la funzione di RESET. Questa azione reimposterà tutti i parametri ai loro valori di default elencati nella tabella seguente e cancellerà tutte le posizioni di memoria.

#### Come eseguire la funzione di reset?
- Spegnere lo strumento.
- Premere il tasto **CE** e tenerlo premuto mentre si accende lo strumento.
- Per un istante viene visualizzato ”RESET” poi la funzione selezionata dal commutatore viene presentata a display.
- Rilasciare i tasto **CE**.

#### Elenco dei parametri e loro valori di default:

| Funzione               | Parametro                                         | Valore di default               |
| :--------------------- | :------------------------------------------------ | :------------------------------ |
| LOW Ω 200mA c          | Limite HI                                         | 5.00 Ω                          |
|                        | Compensazione del cavo                            | Cancellata                      |
| R ISO                  | Limite LO (250V)                                  | 0.250 M Ω                       |
|                        | Limite LO (500V)                                  | 0.500 M Ω                       |
|                        | Limite LO (1000V)                                 | 1.000 M Ω                       |
|                        | Limite HI (250V)                                  | Nessun limite                   |
|                        | Limite HI (500V)                                  | Nessun limite                   |
|                        | Limite HI (1000V)                                 | Nessun limite                   |
|                        | U N                                               | 500V                            |
| EARTH                  | Metodo di collegamento                            | 2 -PUNTI                        |
|                        | Limite HI                                         | 1666 Ω                          |
|                        | Funzione                                          | ρ                               |
|                        | Distanza “a”                                      | 10 m                            |
| Z LINE                 | Collegamento                                      | L-N                             |
|                        | Tipo I PSC                                        | STANDARD (STD)                  |
| Z LOOP                 | Polarità                                          | **b**                           |
|                        | Tipo I PSC                                        | STANDARD (STD)                  |
| RCD Voltage U B Time t | I ∆ N                                             | 30 mA                           |
|                        | U Blim                                            | 50 V                            |
|                        | Tipo di differenziale                             | Generale                        |
|                        | Funzione                                          | RCD U B                         |
|                        | Moltiplicatore I ∆ N                              | x 1                             |
|                        | Forma della corrente di prova                     | **b**                           |
| RCD Current I ∆        | I ∆ N                                             | 30 mA                           |
|                        | Forma della corrente di prova                     | **b**                           |
|                        | U Blim                                            | 50 V                            |
| RCD Analysis           | I ∆ N                                             | 30 mA                           |
|                        | Forma della corrente di prova                     | **b**                           |
|                        | U Blim                                            | 50 V                            |
| VOLTAGE DROP           | HI limit                                          | 4.0 %                           |
| Z2 Ω Im=280A max       | Collegamento                                      | L-N                             |
|                        | I PSC type                                        | STANDARD (STD)                  |
| LOW Ω 10A b            | sezione del cavo / ∆ U max                        | 1 mm² / 3.3 V                   |
|                        | funzione                                          | LOW Ω 10 A **b**                |
|                        | limite HI                                         | 150 m Ω                         |
| intera posizione di memoria                                                                       | cancellata                      |
| numero del punto di misura                                                                        | 001                             |
| numero dell’anello di corrente                                                                    | 001                             |
| numero di serie del risultato memorizzato                                                         | 001                             |

**NOTE!**
- Se a causa di un qualunque problema (disturbo esterno, scarica della batteria tampone ecc.) lo strumento dovesse rilevare errori sui parametri della tabella sopra, tutti i parametri verrebbero reimpostati ai loro valori di default ed il messaggio "PARAMETRI DI DEFAULT" verrebbe visualizzato all'accensione ⇒ Reimpostare i parametri desiderati.
- Se a causa di un qualunque problema (disturbo esterno, scarica della batteria tampone ecc.) lo strumento dovesse rilevare errori sui dati memorizzati, tutta la memoria verrebbe cancellata ed il messaggio "MEMORIA CANCELLATA" verrebbe visualizzato all'accensione.
- Se a causa di un qualunque problema (disturbo esterno, danneggiamento del componente) lo strumento dovesse rilevare errori sui parametri di calibrazione dello strumento, tutti i parametri di calibrazione verrebbero reimpostati ai loro valori di fabbrica ed il messaggio "COSTANTI DI CALIBRAZIONE ALTERATE" verrebbe visualizzato all'accensione ⇒ Spedire lo strumento alla HT-ITALIA per la ricalibrazione.

### 6.17. Contrasto del display
Poiché il contrasto del display è una funzione della temperatura ambiente e dipende anche dall’angolo visivo, esiste la possibilità di regolarlo a proprio piacimento.

#### Come regolare il contrasto?
- Accendere lo strumento.
- Accertarsi che non sia stato selezionato il modo memoria per i tasti funzione F1 - F6.
- Usare i tasti 8/ ↑ e 2/ ↓ per regolare il contrasto.

### 6.18. Impostazione orologio interno
Per modificare data e ora impostate sullo strumento agire come segue:
- Premere il tasto punto decimale del tastierino numerico e contemporaneamente ruotare il selettore funzioni ⇒ viene visualizzata la seguente videata:
*Fig. 58. Videata per l'impostazione di data e ora*
- Utilizzando il tastierino numerico inserire prima la data (inclusi gli zeri non significativi) secondo il formato indicato (giorno, mese, anno) poi l'ora (inclusi gli zeri non significativi) anch'essa secondo il formato indicato (ora, minuti, secondi).
- Confermare i parametri inseriti utilizzando il tasto F1 o annullare l'inserimento tramite il tasto F2.

**NOTE!**
- Se viene inserita una data o un ora errate viene visualizzato il messaggio "Data errata" o "Ora errata" ⇒ utilizzare il tasto **CE** per cancellare il parametri errato.

## 7. ACCESSORI IN DOTAZIONE
- Strumento **MAXTEST HT2038** ........................................................................HV002038
  - Manuale d’uso
  - Cartolina di garanzia
  - Scatola di imballo
  - Certificato di calibrazione
- **B84** Borsa accessori ...............................................................................HA002088
- **C203805** Cavo di misura Shuko .....................................................................HA002085
- **C203804** Cavo di misura resistenza di terra .................................................. HA002084
- **C2034** Cavo di misura resistenza di terra N-PE ........................................ HA002034
- **KITTERRNE** Kit di cavi e picchetti composto da: ............................................... HA100001
  - Borsa per trasporto accessori
  - R10 Picchetto di terra (4Pezzi)
  - Set cavi x misure di terra e ∆ V%
- **C203802** Cavo di prova 4 fili x Z2 Ω ..............................................................HA002082
- **C5700** Cavo alimentazione LOW Ω 10A ....................................................HA005700
- **C203803** Cavo di misura a tre fili separati .....................................................HA002083
- **COC4-UK** Set coccodrilli a sicurezza (1rosso, 1verde, 1nero, 1blu) ...............HA0004UK
- **404-IECN** Puntale a sicurezza (1nero) ........................................................... HA40400N
- **404-IECB** Puntale a sicurezza (1blu) .............................................................. HA40400B
- **EUROLINK** Software di comunicazione con PC (CDROM, manuale, cavo seriale) ... HA000001

### Accessori a richiesta
- **C203807** Adattatore per misure trifase ...........................................................HA002087

Via della Boaria 40
48018 – Faenza (RA)- Italy
Tel: +39-0546-621002 (4 linee r.a.)
Fax: +39-0546-621144
email: ht@htitalia.it
http://www.ht-instruments.com
