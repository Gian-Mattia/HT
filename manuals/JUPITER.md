# JUPITER

<!-- Language: it -->
<!-- Version: 1.0 -->

<!-- Chunk: Pages 1-45 -->
Manuale d’uso

JUPITER IT - 1

INDICE
## 1. PRECAUZIONI E MISURE DI SICUREZZA
### 1.1. Istruzioni preliminari
### 1.2. Durante l’utilizzo
### 1.3. Dopo l’utilizzo
### 1.4. Definizione di Categoria di misura (Sovratensione)
## 2. DESCRIZIONE GENERALE
### 2.1. Strumenti di misura a Valore medio ed a Vero valore efficace
### 2.2. Definizione di Vero valore efficace e Fattore di cresta
## 3. PREPARAZIONE ALL’UTILIZZO
### 3.1. Controlli iniziali
### 3.2. Alimentazione dello strumento
### 3.3. Conservazione
## 4. NOMENCLATURA
### 4.1. Descrizione dello strumento
#### 4.1.1. Videata iniziale dello strumento
### 4.2. Descrizione dei tasti funzione
#### 4.2.1. Tasto GO/HOLD
#### 4.2.2. Tasto H/H%/H
#### 4.2.3. Tasto MODE/MXMNPK
#### 4.2.4. Tasti  / e 
#### 4.2.5. Tasto RCDI  N/
#### 4.2.6. Funzione LoZ
#### 4.2.7. Funzione AC+DC
#### 4.2.8. Funzione corrente di spunto (INRUSH)
#### 4.2.9. Disabilitazione funzione Autospegnimento
#### 4.2.10. Impostazione limite tensione di contatto
#### 4.2.11. Impostazione tensione nominale nelle misure Loop/Ra
#### 4.2.12. Impostazione fondo scala pinza flessibile
## 5. ISTRUZIONI OPERATIVE
### 5.1. Misura Tensione DC
### 5.2. Misura Tensione AC, AC+DC
### 5.3. Misura Tensione AC, DC, AC+DC con bassa impedenza (LoZ)
### 5.4. Misura Resistenza e Test Continuità
### 5.5. Senso ciclico e concordanza delle fasi a 1 terminale
### 5.6. Misura di Resistenza globale di terra senza intervento RCD
### 5.7. Misura Impedenza Linea/Loop
### 5.8. Test su interruttori differenziali tipo A ed AC
### 5.9. Misura Corrente DC, AC, AC+DC, INRUSH con trasduttori a pinza
## 6. MANUTENZIONE
### 6.1. Sostituzione batterie
### 6.2. Pulizia dello strumento
### 6.3. Fine vita
## 7. SPECIFICHE TECNICHE
### 7.1. Caratteristiche Tecniche
#### 7.1.1. Caratteristiche generali
### 7.2. Condizioni ambientali di utilizzo
### 7.3. Accessori
## 8. ASSISTENZA
### 8.1. Condizioni di garanzia
### 8.2. Assistenza
## 9. APPENDICI TEORICHE
### 9.1. Test su interruttori differenziali (RCD)
### 9.2. Misura della resistenza globale di terra negli impianti TT
### 9.3. Misura di Loop e calcolo corrente di cortocircuito presunta
### 9.4. Armoniche di tensione e corrente

---

© Copyright HT ITALIA 2024 Versione IT 2.01 - 13/12/24

ITALIANO
Manuale d’uso

## 1. PRECAUZIONI E MISURE DI SICUREZZA
Lo strumento è stato progettato in conformità alla direttiva IEC/EN61010-1, relativa agli strumenti di misura elettronici. Per la Sua sicurezza e per evitare di danneggiare lo strumento, La preghiamo di seguire le procedure descritte nel presente manuale e di leggere con particolare attenzione tutte le note precedute dal simbolo `!`.
Prima e **durante** l’esecuzione delle misure attenersi scrupolosamente alle seguenti indicazioni:
* Non effettuare misure in ambienti umidi.
* Non effettuare misure in presenza di gas o materiali esplosivi, combustibili o in ambienti polverosi.
* Evitare contatti con il circuito in esame se non si stanno effettuando misure.
* Evitare contatti con parti metalliche esposte, con terminali di misura inutilizzati, ecc.
* Non effettuare alcuna misura qualora si riscontrino anomalie nello strumento come, deformazioni, rotture, fuoriuscite di sostanze, mancate visualizzazioni a display, ecc.
* Prestare particolare attenzione quando si effettuano misure di tensioni superiori a 20V in quanto è presente il rischio di shock elettrici.

Nel presente manuale e sullo strumento sono utilizzati i seguenti simboli:
* **Attenzione**: attenersi alle istruzioni riportate nel manuale; un uso improprio potrebbe causare danni allo strumento o ai suoi componenti
* **Pericolo Alta Tensione**: rischi di shock elettrici
* **Strumento con doppio isolamento**
* **Tensione AC o Corrente AC**
* **Tensione o Corrente DC**
* **Riferimento di terra**

### 1.1. ISTRUZIONI PRELIMINARI
* Questo strumento è stato progettato per un utilizzo in un ambiente con livello di inquinamento 2.
* Può essere utilizzato per misure di **TENSIONE** e **CORRENTE** su installazioni in **CAT IV 600V**, **CAT III 690V** verso terra e tra gli ingressi
* La invitiamo a seguire le normali regole di sicurezza previste dalle procedure per i lavori sotto tensione ed a utilizzare i DPI previsti orientati alla protezione contro correnti pericolose e a proteggere lo strumento contro un utilizzo errato
* Nel caso in cui la mancata indicazione della presenza di tensione possa costituire rischio per l’operatore effettuare sempre una misura di continuità prima della misura in tensione per confermare il corretto collegamento e stato dei puntali
* Solo i puntali forniti a corredo dello strumento garantiscono gli standard di sicurezza. Essi devono essere in buone condizioni. Se necessario sostituirli utilizzare esclusivamente accessori originali HT
* Non effettuare misure su circuiti che superano i limiti di tensione specificati.
* Non effettuare misure in condizione ambientali diverse da quelle indicate nel § 6.2.1
* Controllare se la batteria è inserita correttamente
* Controllare che il display LCD e il selettore indichino la stessa funzione

## 1.2. DURANTE L’UTILIZZO
La preghiamo di leggere attentamente le raccomandazioni e le istruzioni seguenti:

> **ATTENZIONE**
> La mancata osservazione delle Avvertenze e/o Istruzioni può danneggiare lo strumento e/o i suoi componenti o essere fonte di pericolo per l’operatore.

* Prima di azionare il **selettore**, scollegare i puntali di misura dal circuito in esame.
* Quando lo strumento è connesso al circuito in esame non toccare mai un qualunque terminale inutilizzato
* Durante la misura di correnti, ogni altra corrente localizzata in prossimità delle pinze può influenzare la precisione della misura
* Durante la misura di corrente posizionare sempre il conduttore il più possibile al centro del toroide in modo da ottenere una lettura più accurata
* Evitare la misura di resistenza in presenza di tensioni esterne; anche se lo strumento è protetto, una tensione eccessiva potrebbe causare malfunzionamenti dello strumento
* Prima di effettuare qualunque misura di resistenza accertarsi che il circuito in esame non sia alimentato e che eventuali condensatori presenti siano scarichi
* Se, durante una misura, il valore o il segno della grandezza in esame rimangono costanti controllare se è attivata la funzione HOLD.

### 1.3. DOPO L’UTILIZZO
* Quando le misure sono terminate, posizionare il **selettore** su OFF in modo da spegnere lo strumento.
* Se si prevede di non utilizzare lo strumento per un lungo periodo rimuovere le batterie.

### 1.4. DEFINIZIONE DI CATEGORIA DI MISURA (SOVRATENSIONE)
La norma IEC/EN 61010-1: Prescrizioni di sicurezza per apparecchi elettrici di misura, controllo e per utilizzo in laboratorio, Parte 1: Prescrizioni generali, definisce cosa si intenda per categoria di misura, comunemente chiamata categoria di sovratensione. Al § 6.7.4 essa recita: **I circuiti sono suddivisi nelle seguenti categorie di misura:**
* La **Categoria di misura IV** serve per le misure effettuate su una sorgente di un’installazione a bassa tensione.
  Esempi sono costituiti da contatori elettrici e da misure sui dispositivi primari di protezione dalle sovracorrenti e sulle unità di regolazione dell’ondulazione.
* La **Categoria di misura III** serve per le misure effettuate in installazioni all’interno di edifici.
  Esempi sono costituiti da misure su pannelli di distribuzione, disgiuntori, cablaggi, compresi i cavi, le barre, le scatole di giunzione, gli interruttori, le prese di installazioni fisse e gli apparecchi destinati all’impiego industriale e altre apparecchiature, per esempio i motori fissi con collegamento ad impianto fisso.
* La **Categoria di misura II** serve per le misure effettuate su circuiti collegati direttamente all’installazione a bassa tensione.
  Esempi sono costituiti da misure su apparecchiature per uso domestico, utensili portatili ed apparecchi similari.
* La **Categoria di misura I** serve per le misure effettuate su circuiti non collegati direttamente alla RETE DI DISTRIBUZIONE.
  Esempi sono costituiti da misure su non derivati dalla RETE e derivati dalla RETE ma con protezione particolare (interna). In quest’ultimo caso le sollecitazioni da transitori sono variabili, per questo motivo (OMISSIS) si richiede che l’utente conosca la capacità di tenuta ai transitori dell’apparecchiatura.

## 2. DESCRIZIONE GENERALE
Lo strumento esegue le seguenti misure:
* Tensione DC / AC, AC+DC TRMS
* Tensione DC / AC / AC+DC TRMS con bassa impedenza (LoZ)
* Corrente DC / AC / AC+DC TRMS con trasduttore a pinza standard
* Corrente AC TRMS con trasduttori a pinza flessibili
* Riconoscimento automatico grandezze AC e DC
* Corrente di spunto (**Dynamic INRUSH - DIRC**)
* Armoniche di corrente/tensione fino al 25° ordine e calcolo THD%
* Resistenza e Test continuità
* Frequenza corrente e tensione
* Resistenza globale di terra senza intervento RCD
* Impedenza di Loop L-L, L-N e calcolo corrente di cortocircuito presunta
* Test su RCD Generali tipo A e AC
* Senso ciclico delle fasi a 1 terminale

Ciascuna di queste funzioni può essere selezionata tramite un apposito selettore. Sono inoltre presenti tasti funzione (vedere il § 4.2), bargraph analogico e retroilluminazione. Lo strumento è inoltre dotato della funzione di Auto Power OFF (**disabilitabile**) che provvede a spegnere automaticamente lo strumento trascorsi 15 minuti dall'ultima pressione dei tasti funzione o rotazione del selettore. Per riaccendere lo strumento ruotare il selettore.

### 2.1. STRUMENTI DI MISURA A VALORE MEDIO ED A VERO VALORE EFFICACE
Gli strumenti di misura di grandezze alternate si dividono in due grandi famiglie:
* **Strumenti a VALORE MEDIO**: strumenti che misurano il valore della sola onda alla frequenza fondamentale (50 o 60 HZ).
* **Strumenti a VERO VALORE EFFICACE** anche detti TRMS (True Root Mean Square value): strumenti che misurano il vero valore efficace della grandezza in esame.

In presenza di un’onda perfettamente sinusoidale le due famiglie di strumenti forniscono risultati identici. In presenza di onde distorte invece le letture differiscono. Gli strumenti a valore medio forniscono il valore efficace della sola onda fondamentale, gli strumenti a vero valore efficace forniscono invece il valore efficace dell’intera onda, armoniche comprese (entro la banda passante dello strumento). Pertanto, misurando la medesima grandezza con strumenti di entrambe le famiglie, i valori ottenuti sono identici solo se l’onda è puramente sinusoidale, qualora invece essa fosse distorta, gli strumenti a vero valore efficace forniscono valori maggiori rispetto alle letture di strumenti a valore medio.

### 2.2. DEFINIZIONE DI VERO VALORE EFFICACE E FATTORE DI CRESTA
Il valore efficace per la corrente è così definito: "In un tempo pari ad un periodo, una corrente alternata con valore efficace della intensità di 1A, circolando su di un resistore, dissipa la stessa energia che sarebbe dissipata, nello stesso tempo, da una corrente continua con intensità di 1A". Da questa definizione discende l’espressione numerica:

```
G = (1/T) ∫[0 to T] g(t)² dt
```

Il valore efficace viene indicato come RMS (root mean square value)
Il Fattore di Cresta è definito come il rapporto fra il Valore di Picco di un segnale ed il suo Valore Efficace:
`CF (G) = Gp / RMS`
Questo valore varia con la forma d'onda del segnale, per un’onda puramente sinusoidale esso vale `√2 = 1.41`. In presenza di distorsioni il Fattore di Cresta assume valori tanto maggiori quanto più è elevata la distorsione dell’onda

## 3. PREPARAZIONE ALL’UTILIZZO
### 3.1. CONTROLLI INIZIALI
Lo strumento, prima di essere spedito, è stato controllato dal punto di vista elettrico e meccanico. Sono state prese tutte le precauzioni possibili affinché lo strumento potesse essere consegnato senza danni.
Tuttavia si consiglia, comunque, di controllare sommariamente lo strumento per accertare eventuali danni subiti durante il trasporto. Se si dovessero riscontrare anomalie contattare immediatamente lo spedizioniere.
Si consiglia inoltre di controllare che l’imballaggio contenga tutte le parti indicate al § 6.3.1. In caso di discrepanze contattare il rivenditore.
Qualora fosse necessario restituire lo strumento, si prega di seguire le istruzioni riportate al § 7.

### 3.2. ALIMENTAZIONE DELLO STRUMENTO
Lo strumento è alimentato con **4 x 1.5V batterie alcaline tipo AAA IEC LR03** incluse nella confezione. Quando le batterie sono scariche il simbolo “**🔋**” è mostrato a display. Per sostituire le batterie vedere il § 6.1.

### 3.3. CONSERVAZIONE
Per garantire misure precise, dopo un lungo periodo di **conservazione**, attendere che lo strumento ritorni alle condizioni normali (vedere il § 6.2.1).

## 4. NOMENCLATURA
### 4.1. DESCRIZIONE DELLO STRUMENTO
LEGENDA:
1. Display LCD
2. Tasto freccia 
3. Tasto  /
4. Tasto MODE/MXMNPK
5. Tasto H/H%/H
6. Tasto RCDI  N/
7. Tasto GO/HOLD
8. Selettore funzioni
9. Terminale di ingresso COM/E/N
10. Terminale di ingresso V Ω L

Fig. 1: Descrizione dello strumento

#### 4.1.1. Videata iniziale dello strumento
1. Ruotare il selettore in qualunque posizione per accendere lo strumento. La seguente videata iniziale è mostrata a display per alcuni secondi ad identificare la versione interna di Hardware e Firmware.

Fig. 2: Videata inziale dello strumento

2. Ruotare il selettore nella posizione **OFF** per spegnere lo strumento

### 4.2. DESCRIZIONE DEI TASTI FUNZIONE
#### 4.2.1. Tasto GO/HOLD
La pressione del tasto **GO/HOLD** (per le funzioni V, LoZV, Ω e) attiva il mantenimento del valore della grandezza visualizzata a display. Il messaggio "**HOLD**" appare a display. Premere nuovamente il tasto per uscire dalla funzione. La pressione del tasto **GO/HOLD** (per le funzioni RCD, Ra Loop, , IRC) attiva la corrispondente misurazione.

#### 4.2.2. Tasto H/H%/H
Il tasto **H/H%/H** (attivo nelle posizioni V, LoZV e) consente le seguenti operazioni:
* Pressione semplice del tasto per visualizzazione ampiezze delle armoniche di tensione e corrente fino al 25° ordine (**Hdc, H01… H25**) in formato assoluto o percentuale in rapporto alle fondamentali dei segnali in ingresso (per valori di tensione VAC >0.5V e corrente AC > 0.5A e frequenza compresa tra 42.5Hz ÷ 69Hz) e il valore percentuale del parametro **THD%** (vedere § 9.4) come mostrato in Fig. 3. Usare i tasti  e  / per aumentare/diminuire l’ordine dell’armonica

Fig. 3: Visualizzazione ampiezze analisi armonica

* Pressione prolungata del tasto (almeno 2s) per attivare la funzione **H₂O (Higher Harmonic Ordering)** di ordinamento dell’ampiezza delle armoniche. In tali condizioni, la funzione “HOLD” è automaticamente attivata, il simbolo “**H**” è presente a display, la barra grafica è disabilitata e lo strumento mostra il valore delle ampiezza di tutte le armoniche comprese tra l’ordine 2 e il 25, in ordine decrescente a partire dall’armonica di ampiezza maggiore come mostrato in Fig. 4

Fig. 4: Visualizzazione ordinamento ampiezze analisi armonica

Nell’esempio di Fig. 4 l’armonica di ampiezza maggiore corrisponde all’ordine 7. Premere il tasto  per osservare le ampiezze delle restanti armoniche e premere nuovamente il tasto **H/H%/H** per passare dalla visualizzazione in valori assoluti o percentuali. Ruotare il selettore per uscire dalla funzione

#### 4.2.3. Tasto MODE/MXMNPK
La pressione semplice del tasto **MODE/MXMNPK** consente le seguenti operazioni:
* Selezione dei modi di misura “AUTO”, “AC”, “DC”, “AC+DC” e “FREQ” nelle posizioni V, LoZV
* Selezione dei modi di misura “AUTO”, “AC”, “DC” e “AC+DC”, “FREQ” e “IRC” (vedere § 4.2.8) nella posizione
* Selezione tipo di trasduttore a pinza nella misura di corrente tra le opzioni “**P**” (pinza standard opzionale) e “**F**” (pinza flessibile opzionale) nella posizione
* Selezione misure di Resistenza globale di terra senza intervento RCD (**RCD Ra**), Resistenza globale di terra L-PE (100mA) e Impedenza di Loop L-L, L-N nella posizione Ra Loop
* Selezione misure di tempo di intervento a “½I  n”, “I  n”, “5x  In” e corrente di intervento “**I**” del differenziale (RCD) nella posizione RCD
* Selezione misura di Resistenza “Ω” o test continuità “**Ω**” nella posizione Ω

La pressione prolungata (>2s) del tasto **MODE/MXMNPK** consente l’attivazione/disattivazione della rilevazione continua dei valori massimo (MAX), minimo (MIN), picco positivo (Pk+), picco negativo (Pk-) della grandezza (tensione o corrente) in esame. I valori sono continuamente aggiornati e si presentano in maniera ciclica ad ogni nuova pressione del medesimo tasto. Questa funzione non è attiva nella posizione. Premere a lungo il tasto **MODE/MXMNPK** (>2s) o agire sul selettore per uscire dalla funzione.

#### 4.2.4. Tasti  / e 
La pressione semplice dei tasti  / e  consente le seguenti operazioni:
* Impostazione del fondo scala del trasduttore a pinza flessibile (accessorio opzionale - opzione “**F**”) nella posizione tra i valori: **30A, 300A, 3000A** per misura di corrente AC
* Impostazione del fondo scala del trasduttore a pinza standard (opzione “**P**”) nella posizione tra i valori: **1A, 10A, 30A, 40A, 100A, 200A, 300A, 400A, 1000A, 2000A, 3000A** per misura di corrente AC e DC
* Selezione ordine dell’armonica “DC ÷ 25°” nelle posizioni V, LoZV e
* Selezione del tempo di calcolo del valore RMS nella funzione DIRC (vedere § 4.2.8)
* Selezione del limite sulla tensione di contatto considerato nelle posizioni Ra Loop e RCD tra le opzioni: **25V, 50V** (vedere § 4.2.10)
* Azzeramento della resistenza dei cavi nella posizione Ω (vedere § 5.4)

La pressione prolungata (>2s) del tasto  / permette di attivare/disattivare la retroilluminazione del display. Questa funzione è attiva in ogni posizione del selettore e si disattiva automaticamente dopo circa 2 minuti di completa inattività.

#### 4.2.5. Tasto RCDI  N/
La pressione semplice del tasto **RCDI  N/** consente le seguenti operazioni:
* Selezione della corrente di intervento nominale dell’RCD tra le opzioni; **30mA, 100mA, 300mA** nella posizione RCD

La pressione prolungata (>2s) del tasto **RCDI  N/** consente le seguenti operazioni:
* Selezione del tipo di differenziale (RCD) tra le opzioni: “**A**” (tipo AC), “**~**” (tipo A) nella posizione RCD

#### 4.2.6. Funzione LoZ
Questo modo permette di eseguire la misura della tensione AC/DC con una bassa impedenza di ingresso in modo da eliminare le letture errate dovute a tensioni parassite per accoppiamenti di tipo capacitivo.

> **ATTENZIONE**
> Inserendo lo strumento tra i conduttori di fase e terra, per effetto della bassa impedenza dello strumento nella misura, le protezioni a differenziale (RCD) possono intervenire durante l’esecuzione della prova. Se si deve eseguire questo test, eseguire preliminarmente una misura di almeno 5s fra fase e neutro in presenza di tensione

#### 4.2.7. Funzione AC+DC
Lo strumento è in grado di misurare l’eventuale presenza di componenti alternate sovrapposte ad una generica tensione o corrente continua. Ciò può essere di utilità nella misurazione dei segnali impulsivi tipici di carichi non lineari (ex: saldatrici, forni, ecc..).

#### 4.2.8. Funzione corrente di spunto (INRUSH)
La misura della corrente di spunto (vedere § 5.9) è intesa come riconoscimento di un evento rilevato al superamento di una soglia di trigger. Se il valore istantaneo supera tale soglia (fissa pari allo 1%FS pinza) lo strumento mostra a display il valore di Picco massimo (calcolato in 1ms) e il valore massimo RMS calcolato con tempo selezionabile tra: **16.7ms, 20ms, 50ms, 100ms (default), 150ms, 175ms** e **200ms**.

#### 4.2.9. Disabilitazione funzione Autospegnimento
Al fine di preservare le batterie interne, lo strumento si spegne automaticamente dopo circa 15 minuti di non utilizzo. Premere il tasto **MODE/MXMNPK** o ruotare il selettore dalla posizione **OFF** per accendere nuovamente lo strumento. Per disattivare l’autospegnimento operare come segue:
* Spegnere lo strumento (**OFF**)
* Tenendo premuto  accendere lo strumento. Il simbolo “**⚬**” scompare a display
* Spegnere e riaccendere lo strumento per abilitare nuovamente la funzione

#### 4.2.10. Impostazione limite tensione di contatto
Per impostare il limite sulla tensione di contatto Ut, utilizzata nelle posizioni Ra Loop e RCD, procedere come segue:
1. Spegnere lo strumento (**OFF**)
2. Tenendo premuto il tasto  / accendere lo strumento ruotando il selettore. La videata di Fig. 5 – parte sinistra appare a display con simbolo “Set” lampeggiante

Fig. 5: Impostazione limite sulla tensione di contatto

3. Premere i tasti  / o  per selezionare i valori limite **50V** o **25V**
4. Premere il tasto **GO/HOLD** per confermare e tornare alla videata di misura

#### 4.2.11. Impostazione tensione nominale nelle misure Loop/Ra
Per impostare il valore della tensione nominale necessario allo strumento per il calcolo della corrente di cortocircuito presunta nella posizione Ra Loop, procedere come segue:
1. Selezionare la posizione Ra Loop
2. Tenere premuto a lungo (>2s) il tasto **MODE/MXMNPK**. La videata seguente appare a display con simbolo “Set” lampeggiante

Fig. 6: Impostazione tensione nominale nelle misure di Loop

3. Premere i tasti  / o  per impostare il valore della tensione nominale (Fase - Terra, Fase - Neutro o Fase - Fase) nel campo **100V ÷ 690V**. Mantenere premuto i tasti  / o  per una impostazione veloce del valore desiderato
4. Premere il tasto **GO/HOLD** per confermare e tornare alla videata di misura

#### 4.2.12. Impostazione fondo scala pinza flessibile
Lo strumento può essere utilizzato con trasduttore a pinza flessibile (accessorio opzionale). Per una corretta misura di corrente è necessario impostare il fondo scala di tensione della pinza utilizzata (fare riferimento al manuale d’uso del trasduttore stesso per il valore corretto di fondo scala da impostare). Procedere come segue:
1. Spegnere lo strumento (**OFF**)
2. Tenendo premuto il tasto **MODE/MXMNPK** accendere lo strumento ruotando il selettore. La seguente videata appare a display:

Fig. 7: Impostazione fondo scala pinza flessibile

3. Premere i tasti  / o  per impostare il valore del fondo scala della pinza utilizzata tra le opzioni: **3VAC** (modello F3000U) o **1VAC** (altri modelli)
4. Premere il tasto **GO/HOLD** per confermare e tornare alla videata di misura
5. Le impostazione effettuate sono mantenute ad ogni riaccensione

## 5. ISTRUZIONI OPERATIVE
### 5.1. MISURA TENSIONE DC

> **ATTENZIONE**
> La massima tensione DC in ingresso è **690V**. Non misurare tensioni che eccedono i limiti indicati in questo manuale. Il superamento dei limiti di tensione potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.

Fig. 8: Uso dello strumento per misura di Tensione DC

1. Selezionare la posizione V
2. Inserire il cavo rosso nel terminale di ingresso **V Ω L** e il cavo nero nel terminale di ingresso **COM/E/N**
3. Posizionare il puntale rosso ed il puntale nero rispettivamente nei punti a potenziale positivo e negativo del circuito in esame (vedere Fig. 8). Il valore della tensione è mostrato a display
4. Se sul display è visualizzato il messaggio "**>690V**" (vedere Fig. 8) si è raggiunto il fondo scala dello strumento
5. La visualizzazione del simbolo "**-**" sul display dello strumento indica che la tensione ha verso opposto rispetto alla connessione di Fig. 8.
6. Per l’uso delle funzioni **HOLD, MAX / MIN /PK** vedere il § 4.2

### 5.2. MISURA TENSIONE AC, AC+DC

> **ATTENZIONE**
> La massima tensione AC in ingresso è **690V** verso terra. Non misurare tensioni che eccedono i limiti indicati in questo manuale. Il superamento dei limiti di tensione potrebbe causare shock elettrici all’utilizzatore e danni allo strumento.

Fig. 9: Uso dello strumento per misura di Tensione AC

1. Selezionare la posizione V
2. Premere il tasto **MODE/MXMNPK** per visualizzare il simbolo “**AC**” o “**AC+DC**” a display. Lo strumento dispone del riconoscimento automatico segnali AC o DC
3. Inserire il cavo rosso nel terminale di ingresso **V Ω L** e il cavo nero nel terminale di ingresso **COM/E/N**
4. Posizionare il puntale rosso ed il puntale nero rispettivamente nei punti del circuito in esame (vedere Fig. 9). Il valore della tensione è mostrato a display. Nella parte alta destra del display è mostrato il valore della frequenza della tensione. Premere il tasto **MODE/MXMNPK** per visualizzare il valore della frequenza con maggior risoluzione
5. Se sul display è visualizzato il messaggio "**>690V**" (vedere Fig. 9) si è raggiunto il fondo scala dello strumento
6. Se sul display sono visualizzati i messaggi "**<32Hz**" o “**>1000Hz**” (vedere Fig. 9) il valore della frequenza è esterno all’intervallo di misura **32Hz ÷ 1000Hz**
7. Per l’uso delle funzioni **HOLD, MAX/MIN/PK, H/H%/H** vedere il § 4.2

### 5.3. MISURA TENSIONE AC, DC, AC+DC CON BASSA IMPEDENZA (LOZ)

> **ATTENZIONE**
> La massima tensione AC/DC in ingresso è **690V** verso terra. Non misurare tensioni che eccedono i limiti indicati in questo manuale. Il superamento dei limiti di tensione potrebbe causare shock elettrici all’utilizzatore e danni allo strumento

Fig. 10: Uso dello strumento per misura di Tensione AC /DC con funzione LoZ

1. Selezionare la posizione LoZ V. I simboli “LoZ” e “DC” appaiono a display
2. Premere il tasto **MODE/MXMNPK** per selezionare eventualmente la misura “AC” o “AC+DC”. Lo strumento dispone in ogni caso del riconoscimento automatico segnali AC o DC
3. Inserire il cavo rosso nel terminale di ingresso **V Ω L** e il cavo nero nel terminale di ingresso **COM/E/N**
4. Posizionare il puntale rosso ed il puntale nero rispettivamente nei punti del circuito in esame (vedere Fig. 10) per misura di tensione AC oppure nei punti a potenziale positivo e negativo del circuito in esame (vedere Fig. 8) per misura di tensione DC. Il valore della tensione è mostrato a display. Nella parte alta destra del display è mostrato il valore della frequenza della tensione. Premere il tasto **MODE/MXMNPK** per visualizzare il valore della frequenza con maggior risoluzione
5. Se sul display sono visualizzati i messaggi "**<32Hz**" o “**>1000Hz**” (vedere Fig. 10) il valore della frequenza è esterno all’intervallo di misura **32Hz ÷ 1000Hz**
6. La visualizzazione del simbolo "**-**" sul display dello strumento indica che la tensione ha verso opposto rispetto alla connessione di Fig. 8
7. Per l’uso delle funzioni **HOLD, MAX/MIN/PK, H/H%/H** vedere il § 4.2

### 5.4. MISURA RESISTENZA E TEST CONTINUITÀ

> **ATTENZIONE**
> Prima di effettuare qualunque misura di resistenza accertarsi che il circuito in esame non sia alimentato e che eventuali condensatori presenti siano scarichi.

Fig. 11: Uso dello strumento per misura di Resistenza e Test Continuità

1. Selezionare la posizione Ω
2. Inserire il cavo rosso nel terminale di ingresso **V Ω L** e il cavo nero nel terminale di ingresso **COM/E/N**
3. Cortocircuitare eventualmente i puntali di misura e premere il tasto  per azzerare la resistenza dei cavi di misura. Il simbolo “ZERO” appare a display
4. Posizionare i puntali nei punti desiderati del circuito in esame (vedere Fig. 11). Il valore della resistenza è visualizzato a display
5. Se sul display è visualizzato il messaggio "**>2000 Ω**" (vedere Fig. 11) si è raggiunto il fondo scala dello strumento
6. Premere il tasto **MODE/MXMNPK** per selezionare la misura “**Ω**” relativa al test continuità e posizionare i puntali nei punti desiderati del circuito in esame
7. Il valore della resistenza (solo indicativo) è visualizzato sul display espresso in **Ω** e lo strumento emette un segnale acustico qualora il valore della resistenza risulti **< 30 Ω**
8. Per l’uso delle funzioni **HOLD, MAX/MIN, H/H%/H** vedere il § 4.2

### 5.5. SENSO CICLICO E CONCORDANZA DELLE FASI A 1 TERMINALE

> **ATTENZIONE**
> * La tensione AC in ingresso per eseguire questo test deve essere compresa nell’intervallo **130V ÷ 690V** con frequenza compresa nell’intervallo **42.5Hz ÷ 69Hz**
> * Il test può essere svolto solo toccando le parti metalliche dei conduttori

Fig. 12: Uso dello strumento per test di senso ciclico e concordanza delle fasi

1. Selezionare la posizione. Il messaggio “**PH 1**” è lampeggiante a display
2. Inserire il cavo rosso nel terminale di ingresso **V Ω L**
3. Posizionare il puntale rosso sulla fase **L1** del sistema trifase in esame (vedere Fig. 12). I seguenti messaggi possono essere mostrati a display (vedere Fig. 13) a identificare la presenza di un segnale di tensione con frequenza esterna all’intervallo **42.5Hz ÷ 69Hz**. In tali condizioni lo strumento non esegue il test

Fig. 13: Segnalazione di tensione con frequenza errata

4. In condizioni corrette di tensione e frequenza, lo strumento mostra il messaggio “**HOLD**”, i simboli e “**PH1**” ed emette un suono continuo in attesa del riconoscimento di un valore stabile di tensione sulla fase L1 (vedere Fig. 14 – parte sinistra)

Fig. 14: Riconoscimento fase L1 e attesa per fase L2

5. Non rimuovere il puntale dalla fase L1 fino alla visualizzazione del messaggio “**PH 2**” lampeggiante a display (vedere Fig. 14 – parte destra)

Fig. 15: Riconoscimento fase L1 e attesa per fase L2

6. Posizionare il puntale rosso sulla fase **L2** del sistema trifase in esame (vedere Fig. 12). Nel caso in cui il passaggio tra la fase L1 e la fase L2 avvenga in un tempo maggiore di **10s** lo strumento mostra il messaggio “**t.out**” a display (vedere Fig. 15 – parte sinistra). In condizioni corrette di tensione e frequenza, lo strumento mostra il messaggio “**HOLD**”, i simboli e “**PH2**” ed emette un suono continuo in attesa del riconoscimento di un valore stabile di tensione sulla fase L2 (vedere Fig. 15 – parte destra)
7. Al riconoscimento del valore stabile di tensione sulla fase L2 lo strumento mostra automaticamente il messaggio “**1.2.3.**” (test OK) o il messaggio “**2.1.3**” (test NOT OK) come mostrato nella Fig. 16

Fig. 16: Esiti del test di sequenza e concordanza delle fasi

8. Nel caso in cui occorra verificare la concordanza delle fasi tra due sistemi trifase in parallelo, dopo il riconoscimento della fase L1 del primo sistema, posizionare il puntale sulla fase L1 del secondo sistema. Il risultato finale corretto è il messaggio “**1.1 -**“ (vedere Fig. 16 – parte destra)

### 5.6. MISURA DI RESISTENZA GLOBALE DI TERRA SENZA INTERVENTO RCD
Questa funzione è eseguita secondo le norme IEC/EN61557-6 e consente la misura dell’impedenza dell’anello di guasto, assimilabile negli impianti TT alla resistenza globale di terra (vedere § 9.2).

> **ATTENZIONE**
> * La massima tensione AC in ingresso è 690V verso terra e tra gli ingressi. Non misurare tensioni che eccedono i limiti indicati in questo manuale. Il superamento dei limiti di tensione potrebbe causare shock elettrici all’utilizzatore e danni allo strumento
> * La misurazione della resistenza globale di terra comporta la circolazione di una corrente di circa **15mA** tra fase e terra come da specifiche tecniche dello strumento (vedere § 7.1). Questo potrebbe comportare l’intervento di eventuali protezioni con correnti di intervento inferiori

Fig. 17: Uso dello strumento per misura resistenza globale di terra con cavo Schuko

Fig. 18: Uso dello strumento per misura resistenza globale di terra con puntali

1. Impostare il valore della tensione nominale Fase - Terra (vedere § 4.2.11)
2. Impostare il valore limite della tensione di contatto (vedere § 4.2.10)
3. Selezionare la posizione Ra Loop.
4. Premere il tasto **MODE/MXMNPK** e selezionare l’opzione “**RCD Ra**”
5. In caso di uso del cavo con spina shuko inserire il conduttore rosso nel terminale di ingresso **V Ω L** e il conduttore verde nel terminale di ingresso **COM/E/N** e collegare lo strumento all’impianto in esame (vedere Fig. 17). Il valore della tensione Fase - Terra è mostrato a display
6. In caso di uso dei puntali di misura inserire il conduttore rosso nel terminale di ingresso **V Ω L** e il conduttore nero nel terminale di ingresso **COM/E/N** e collegare lo strumento all’impianto in esame (vedere Fig. 18). Il valore della tensione Fase - Terra è mostrato a display
7. Premere il tasto **GO/HOLD** per attivare la prova. Le seguenti videate possono essere mostrate a display per alcuni secondi a segnalare condizioni anomale in cui lo strumento non esegue il test:

Fig. 19: Situazioni anomale alla pressione del tasto GO/HOLD – Videate 1

Fig. 20: Situazioni anomale alla pressione del tasto GO/HOLD – Videate 2

Fig. 21: Situazioni anomale alla pressione del tasto GO/HOLD – Videate 3

* **L-PE**: Ruotare la spina Schuko nella presa in prova
* **< 100V**: Tensione in ingresso < 100V. Controllare la rete elettrica
* **> 690V**: Tensione in ingresso > 690V. Controllare la rete elettrica
* **< 42.5Hz**: Frequenza tensione in ingresso < 42.5Hz. Controllare la rete elettrica
* **> 69.0Hz**: Frequenza tensione in ingresso > 69.0Hz. Controllare la rete elettrica
* **> 50V**: Tensione pericolosa su conduttore PE > 50V. Controllare circuito di terra
* **rcd**: RCD intervenuto. Controllare possibili dispersioni di corrente verso terra e scollegare le utenze dalla linea in prova
* **Ut**: Tensione di contatto oltre limite (25V/50V). Controllare circuito di terra e scollegare le utenze dalla linea in prova

8. In assenza di condizioni anomale lo strumento esegue il test e il simbolo `↯` lampeggia a display. Al termine della prova le seguenti videate sono mostrate a display

Fig. 22: Risultati della misura di resistenza globale di terra

9. Nella videata di Fig. 22 – parte sinistra è presente il valore della resistenza globale di terra. Premere i tasti  / o  per visualizzare il valore della corrente di cortocircuito presunta **Isc** (vedere § 9.3)

### 5.7. MISURA IMPEDENZA LINEA/LOOP
Questa funzione viene eseguita secondo le norme CEI 64-8 612.6.3, IEC/EN61557-3 e consente la misura dell’impedenza di linea, dell’anello di guasto e la corrente di cortocircuito presunta (vedere § 9.3). Sono disponibili le seguenti modalità di funzionamento:
* **L-N** misurazione dell'impedenza di linea fra il conduttore di fase e il conduttore di neutro e calcolo della corrente di corto circuito presunta fase – neutro
* **L-L** misurazione dell'impedenza di linea fra due conduttori di fase e calcolo della corrente di corto circuito presunta fase – fase
* **L-PE** misurazione dell'impedenza dell’anello di guasto fra il conduttore di fase e il conduttore di terra Ra e calcolo della corrente di corto circuito presunta fase – terra)

> **ATTENZIONE**
> * La massima tensione AC in ingresso è 690V verso terra e tra gli ingressi. Non misurare tensioni che eccedono i limiti indicati in questo manuale. Il superamento dei limiti di tensione potrebbe causare shock elettrici all’utilizzatore e danni allo strumento
> * La misurazione della resistenza globale di terra comporta la circolazione di una corrente di circa **100mA** tra fase e terra come da specifiche tecniche dello strumento (vedere § 7.1). Questo potrebbe comportare l’intervento di eventuali protezioni con correnti di intervento inferiori

Fig. 23: Uso dello strumento per misura impedenza Loop L - PE con cavo a spina Schuko

Fig. 24: Uso dello strumento per misura impedenza Loop L - PE con puntali

Fig. 25: Uso dello strumento per misura impedenza Loop L - N con cavo a spina Schuko

Fig. 26: Uso dello strumento per misura impedenza Loop L - N con puntali

Fig. 27: Uso dello strumento per misura impedenza Loop L - L con puntali

1. Impostare il valore della tensione nominale Fase - Terra, Fase - Neutro o Fase - Fase (vedere § 4.2.11)
2. Impostare il valore limite della tensione di contatto (vedere § 4.2.10)
3. Selezionare la posizione Ra Loop.
4. Premere il tasto **MODE/MXMNPK** e selezionare una tra le opzioni “**Ra**” , “Ln” o “LL”
5. Per misura di Loop L-PE in caso di uso del cavo con spina shuko inserire il conduttore rosso nel terminale di ingresso **V Ω L** e il conduttore verde nel terminale di ingresso **COM/E/N** e collegare lo strumento all’impianto in esame (vedere Fig. 23). Il valore della tensione Fase - Terra è mostrato a display
6. Per misura di Loop L-PE in caso di uso dei puntali di misura inserire il conduttore rosso nel terminale di ingresso **V Ω L** e il conduttore nero nel terminale di ingresso **COM/E/N** e collegare lo strumento all’impianto in esame (vedere Fig. 24). Il valore della tensione Fase - Terra è mostrato a display
7. Per misura di Loop L-N in caso di uso del cavo con spina shuko inserire il conduttore rosso nel terminale di ingresso **V Ω L** e il conduttore nero nel terminale di ingresso **COM/E/N** e collegare lo strumento all’impianto in esame (vedere Fig. 25). Il valore della tensione Fase - Neutro è mostrato a display
8. Per misura di Loop L-N in caso di uso dei puntali di misura inserire il conduttore rosso nel terminale di ingresso **V Ω L** e il conduttore nero nel terminale di ingresso **COM/E/N** e collegare lo strumento all’impianto in esame (vedere Fig. 26). Il valore della tensione Fase - Neutro è mostrato a display
9. Per misura di Loop L-L in caso di uso dei puntali di misura inserire il conduttore rosso nel terminale di ingresso **V Ω L** e il conduttore nero nel terminale di ingresso **COM/E/N** e collegare lo strumento all’impianto in esame (vedere Fig. 27). Il valore della tensione Fase - Fase è mostrato a display
10. Premere il tasto **GO/HOLD** per attivare la prova. Le videate relative alle Fig. 19, Fig. 20 e Fig. 21 possono essere mostrate a display per alcuni secondi a segnalare condizioni anomale in cui lo strumento non esegue il test
11. In assenza di condizioni anomale, lo strumento esegue il test e il simbolo `↯` lampeggia a display. Al termine della prova le seguenti videate (ad esempio relative alla misura Loop L-L) sono mostrate a display

Fig. 28: Risultati della misura di impedenza Loop L - L

12. Nella videata di Fig. 28 – parte sinistra è presente il valore della impedenza di Loop L-L. Premere i tasti  / o  per visualizzare il valore della corrente di cortocircuito presunta **Isc** (vedere § 9.3)

### 5.8. TEST SU INTERRUTTORI DIFFERENZIALI TIPO A ED AC
Questa funzione viene eseguita secondo le norme CEI 64-8 612.9 e appendice D, IEC/EN61557-6 e consente la misura del tempo di intervento e della corrente degli interruttori differenziali (RCD) di tipo Generale istantaneo dell’impianto (vedere § 9.1). Sono disponibili le seguenti modalità di funzionamento:
* **AUTO** esecuzione automatica di una sequenza di sei prove con correnti di dispersione pari a metà, una volta e cinque volte il valore della corrente nominale impostata e con corrente di dispersione in fase con la semionda positiva e negativa della tensione di rete. Modalità consigliata
* **x ½** prova con corrente di dispersione pari a metà del valore della corrente nominale impostata
* **x1** prova con corrente di dispersione pari a una volta del valore della corrente nominale impostata
* **x5** prova con corrente di dispersione pari a cinque volte del valore della corrente nominale impostata
* **I** prova con corrente di dispersione crescente. Modalità consigliata per determinare l’effettiva corrente di intervento dell’interruttore differenziale

> **ATTENZIONE**
> * La massima tensione AC in ingresso è 690V verso terra e tra gli ingressi. Non misurare tensioni che eccedono i limiti indicati in questo manuale. Il superamento dei limiti di tensione potrebbe causare shock elettrici all’utilizzatore e danni allo strumento
> * La verifica del tempo di intervento di un interruttore differenziale comporta l'intervento della protezione stessa. Verificare pertanto che a valle della protezione differenziale in esame NON siano allacciate utenze o carichi che possano risentire dalla messa fuori servizio dell'impianto. Scollegare tutti i carichi allacciati a valle dell'interruttore differenziale in quanto potrebbero introdurre correnti di dispersione aggiuntive a quelle fatte circolare dallo strumento invalidando così i risultati della prova

Fig. 29: Uso dello strumento per test RCD su sistema Monofase con cavo a spina Schuko

Fig. 30: Uso dello strumento per test RCD su sistema Monofase con puntali di misura

Fig. 31: Uso dello strumento per test RCD su sistema Trifase con puntali di misura

1. Impostare il valore limite della tensione di contatto (vedere § 4.2.10)
2. Selezionare la posizione RCD
3. Premere il tasto **MODE/MXMNPK** e selezionare una tra le seguenti opzioni:
    * Modo **AUTO RCD T** → Misura tempo di intervento RCD in sequenza automatica con correnti di prova nell’ordine **I  n, 5xI  n, ½I  n** e polarità **0°** e **180°**. Vedere Tabella 1 in § 7.1 per identificare le combinazioni possibili
    * Modo **RCD T ½I  n** → Misura tempo di intervento manuale con corrente di prova ½I  n e polarità **0°** e **180°**. Vedere Tabella 1 in § 7.1 per identificare le combinazioni possibili
    * Modo **RCD T I  n** → Misura tempo di intervento manuale con corrente di prova I  n e polarità **0°** e **180°**
    * Modo **RCD T 5xI  n** → Misura tempo di intervento manuale con corrente di prova 5xI  n e polarità **0°** e **180°**. Vedere Tabella 1 in § 7.1 per identificare le combinazioni possibili
    * Modo **RCD I** → Misura corrente di intervento con metodo “a rampa” crescente e polarità **0°** e **180°** (solo RCD tipo AC e A con 30mA)
4. Premere il tasto **RCDI  N/** per impostare la corrente nominale di intervento dell’RCD tra opzioni: **30mA, 100mA, 300mA**. Vedere Tabella 1 in § 7.1 per identificare le combinazioni possibili
5. Premere a lungo (>2s) il tasto **RCDI  N/** per impostare il tipo di RCD tra le opzioni: **~** (tipo AC) e **A** (tipo A). Vedere Tabella 1 in § 7.1 per identificare le combinazioni possibili
6. In caso di uso del cavo con spina shuko inserire il conduttore rosso nel terminale di ingresso **V Ω L** e il conduttore verde nel terminale di ingresso **COM/E/N** e collegare lo strumento all’impianto in esame (vedere Fig. 29). La presenza della tensione Fase - Terra è mostrata nella barra grafica
7. In caso di uso dei puntali di misura inserire il conduttore rosso nel terminale di ingresso **V Ω L** e il conduttore nero nel terminale di ingresso **COM/E/N** e collegare lo strumento all’impianto in esame (vedere Fig. 30 o Fig. 31). La presenza della tensione Fase - Terra è mostrata nella barra grafica
8. Premere il tasto **GO/HOLD** per attivare la prova con polarità **0°**. Premere nuovamente il tasto **GO/HOLD** con simbolo `↯` lampeggiante per attivare la polarità **180°**. Le videate relative alle Fig. 19, Fig. 20 e Fig. 21 possono essere mostrate a display per alcuni secondi a segnalare condizioni anomale in cui lo strumento non esegue il test
9. In assenza di condizioni anomale lo strumento esegue il test e il simbolo `↯` lampeggia a display. Durante e al termine della prova le seguenti videate sono mostrate a display:

**Tempo di intervento in modo automatico (AUTO) (6 test in sequenza)**
Fig. 32: Tempo di intervento in modo AUTO – Videate 1

10. Il primo test eseguito è quello con corrente di prova **I  n** e polarità **0°**. Il risultato della misura parziale è mostrato a display con indicazione “OK” o “NOT OK” (vedere Fig. 32 – parte sinistra). Il simbolo “**⚬**” lampeggiante indica che occorre riarmare l’RCD
11. Il secondo test eseguito è quello con corrente di prova **I  n** e polarità **180°**. Il risultato della misura parziale è mostrato a display con indicazione “OK” o “NOT OK” (vedere Fig. 32 – parte centrale). Il simbolo “**⚬**” lampeggiante indica che occorre riarmare l’RCD
12. Il terzo test eseguito è quello con corrente di prova **5xI  n** e polarità **0°**. Il risultato della misura parziale è mostrato a display con indicazione “OK” o “NOT OK” (vedere Fig. 32 – parte destra). Il simbolo “**⚬**” lampeggiante indica che occorre riarmare l’RCD

Fig. 33: Tempo di intervento in modo AUTO – Videate 2

13. Il quarto test eseguito è quello con corrente di prova **5xI  n** e polarità **180°**. Il risultato della misura parziale è mostrato a display con indicazione “OK” o “NOT OK” (vedere Fig. 33 – parte destra). Il simbolo “**⚬**” lampeggiante indica che occorre riarmare l’RCD
14. Il quinto test eseguito è quello con corrente di prova **½I  n** e polarità **0°**. Il risultato della misura parziale è mostrato a display con indicazione “OK” o “NOT OK” (vedere Fig. 33 – parte centrale). Il messaggio “**>300ms**” indica il fuori scala dello strumento ad indicare il corretto non intervento dell’RCD in tale situazione. Il simbolo “**⚬**” lampeggiante indica che occorre riarmare l’RCD
15. Il sesto e ultimo test eseguito è quello con corrente di prova **½I  n** e polarità **180°**. Il risultato della misura parziale è mostrato a display (vedere Fig. 33 – parte destra). Il messaggio “**>300ms**” indica il fuori scala dello strumento ad indicare il corretto non intervento dell’RCD in tale situazione
16. L’indicazione “**ALL OK**” di Fig. 34 indica il risultato finale corretto del test.

Fig. 34: Videata esito finale test AUTO

**Tempo di intervento in modo manuale (corrente di prova I  n)**
Fig. 35: Tempo di intervento in modo manuale a I  n

10. Il risultato della misura corretto è mostrato a display (vedere Fig. 35 – parte sinistra) con indicazione “OK”
11. Il risultato della misura incorretto è mostrato a display (vedere Fig. 35 – parte destra) con indicazione “NOT OK”. Un breve suono continuo è emesso dallo strumento

**Tempo di intervento in modo manuale (corrente di prova 5xI  n)**
Fig. 36: Tempo di intervento in modo manuale a 5x I  n

10. Il risultato della misura corretto è mostrato a display (vedere Fig. 36 – parte sinistra) con indicazione “OK”
11. Il risultato della misura incorretto (tempo di intervento > 40ms) è mostrato a display (vedere Fig. 36 – parte destra) con indicazione “NOT OK”. Un breve suono continuo è emesso dallo strumento

**Corrente di intervento RCD**
Fig. 37: Corrente di intervento RCD

10. Il risultato della misura corretto è mostrato a display (vedere Fig. 36 – parte sinistra) con indicazione “OK”. Notare la presenza del tempo di intervento nella parte alta destra del display
11. Il risultato della misura incorretto è mostrato a display (vedere Fig. 36 – parte destra) con indicazione “NOT OK” (corrente di intervento > 33mA). Un breve suono continuo è emesso dallo strumento

### 5.9. MISURA CORRENTE DC, AC, AC+DC, INRUSH CON TRASDUTTORI A PINZA

> **ATTENZIONE**
> * La massima corrente misurabile in questa funzione è 3000A AC o 1000A DC. Non misurare correnti che eccedono i limiti indicati in questo manuale
> * Lo strumento esegue la misura sia con trasduttori a pinza flessibili (accessori opzionali) sia con altri trasduttori a pinza standard della famiglia HT (accessori opzionali). Con trasduttori aventi il connettore di uscita Hypertac è necessario l’adattatore opzionale NOCANBA per eseguire il collegamento

Fig. 38: Uso dello strumento per misura di corrente con trasduttori a pinza

1. Selezionare la posizione
2. Premere il tasto **MODE/MXMNPK** per selezionare il tipo di trasduttore a pinza tra le opzioni: “**F**” (trasduttore a pinza flessibile – solo AC) o “**P**” (trasduttore a pinza standard – AC o DC)
3. Premere i tasti  / o  e selezionare sullo strumento la stessa portata impostata sulla pinza tra le opzioni: **30A, 300A, 3000A** (misura di corrente AC con pinza flessibile) oppure: **1A, 10A, 30A, 40A, 100A, 200A, 300A, 400A, 1000A, 2000A, 3000A** per misura di corrente AC, DC, AC+DC con pinza standard)
4. Per trasduttori a pinza flessibile impostare il relativo fondo scala di tensione (vedere § 4.2.12)
5. Premere il tasto **GO/HOLD** per confermare le impostazioni

6. Per trasduttori a pinza standard premere il tasto **MODE/MXMNPK** per selezionare la misura “AC”, “DC” o “AC+DC”. Lo strumento dispone in ogni caso della funzione di riconoscimento automatico delle grandezze AC o DC
7. Inserire il cavo rosso nel terminale di ingresso **V Ω L** e il cavo nero nel terminale di ingresso **COM/E/N**. Per modelli di trasduttori standard con connettore Hypertac usare l’adattatore opzionale NOCANBA. Per informazioni sull’uso dei trasduttori a pinza fare riferimento al relativo manuale d’uso
8. Inserire il cavo al centro del toroide (vedere Fig. 38). Il valore della corrente è mostrato nella Fig. 39

Fig. 39: Risultato misura di corrente AC con pinza standard e flessibile

9. Premere il tasto **MODE/MXMNPK** per visualizzare il valore della frequenza della corrente AC con risoluzione elevata (vedere Fig. 40)

Fig. 40: Risultato misura di frequenza con pinza standard e flessibile

10. Le seguenti videate possono essere mostrate a display

Fig. 41: Situazioni anomale sulla misura di corrente con trasduttori a pinza

11. Il messaggio “**>300A**” indica che il valore della corrente misurata è maggiore del fondo scala impostato (300A nel caso della Fig. 41). Se sul display sono visualizzati i messaggi "**<32.00Hz**" o “**>1000Hz**” Il valore della frequenza della corrente misurata è esterno all’intervallo di misura **32Hz ÷ 1000Hz**
12. Per l’uso delle funzioni **HOLD, MAX/MIN/PK, H/H%/H** vedere il § 4.2

**Misura della corrente di spunto (DIRC)**

> **ATTENZIONE**
> * La massima corrente misurabile in questa funzione è 3000A AC o 1000A DC. Non misurare correnti che eccedono i limiti indicati in questo manuale
> * Lo strumento esegue la misura sia con trasduttori a pinza flessibili (accessori opzionali) sia con altri trasduttori a pinza standard della famiglia HT (accessori opzionali). Per spunti di corrente che contengono un’elevata componente DC è raccomandato l’uso di pinze AC/DC. Con trasduttori aventi il connettore di uscita Hypertac è necessario l’adattatore opzionale NOCANBA per eseguire il collegamento

1. Selezionare la posizione
2. Premere il tasto **MODE/MXMNPK** per selezionare il tipo di trasduttore a pinza tra le opzioni: “**F**” (trasduttore a pinza flessibile – solo AC) o “**P**” (trasduttore a pinza standard – AC o DC)
3. Premere i tasti  / o  selezionare sullo strumento la stessa portata impostata sulla pinza tra le opzioni: **30A, 300A, 3000A** (misura di corrente AC con pinza flessibile) oppure: **1A, 10A, 30A, 40A, 100A, 200A, 300A, 400A, 1000A, 2000A, 3000A** per misura di corrente AC o AC+DC con pinza standard
4. Per trasduttori a pinza flessibile impostare il relativo fondo scala (vedere § 4.2.12)
5. Premere il tasto **GO/HOLD** per confermare le impostazioni
6. Premere il tasto **MODE/MXMNPK** per selezionare la misura “IRC”. Le seguenti videate sono mostrate a display in funzione del tipo di pinza utilizzata:

Fig. 42: Videate iniziali misura corrente di spunto

7. Eseguire i collegamenti delle pinze all’impianto in esame come indicato nel § 5.9
8. Premere il tasto **GO/HOLD** per attivare la funzione. Lo strumento si pone in attesa del riconoscimento dell’evento (valore misurato superiore alla soglia fissa di trigger pari all’ 1%FS pinza: ex 30A per FS = 3000A) mostrando il simbolo “**I**” a display (vedere Fig. 43 – parte sinistra) con emissione di un suono intermittente ogni 2s

Fig. 43: Riconoscimento evento corrente di spunto

9. Al riconoscimento dell’evento la misura si arresta automaticamente e lo strumento mostra nel display principale il valore **Max RMS** calcolato sul tempo di valutazione di **100ms** (default) riportato nel display secondario (vedere Fig. 43 – parte destra), con emissione di un doppio suono
10. Premere i tasti  / o  per selezionare la visualizzazione dei seguenti parametri:
    * Valore di picco “Pk” calcolato in un **1ms** (vedere Fig. 44 – parte sinistra)
    * Max valore RMS calcolato in **16.7ms**
    * Max valore RMS calcolato in **20ms**
    * Max valore RMS calcolato in **50ms**
    * Max valore RMS calcolato in **100ms**
    * Max valore RMS calcolato in **150ms**
    * Max valore RMS calcolato in **175ms**
    * Max valore RMS calcolato in **200ms**

Fig. 44: Esempi di visualizzazioni della corrente di spunto

11. Se la corrente misurata è maggiore del FS della pinza impostato, il messaggio come quello riportato nella Fig. 44 – parte destra (relativo a FS = 3000A) è mostrato a display
12. Premere il tasto **GO/HOLD** per avviare una nuova misura o ruotare il selettore per uscire dalla funzione

## 6. MANUTENZIONE

> **ATTENZIONE**
> * Solo tecnici qualificati possono effettuare le operazioni di manutenzione. Prima di effettuare la manutenzione rimuovere tutti i cavi dai terminali di ingresso
> * Non utilizzare lo strumento in ambienti caratterizzati da elevato tasso di umidità o temperatura elevata. Non esporre direttamente alla luce del sole
> * Spegnere sempre lo strumento dopo l’utilizzo. Se si prevede di non utilizzarlo per un lungo periodo rimuovere la batteria per evitare fuoruscite di liquidi da parte di quest’ultima che possano danneggiare i circuiti interni dello strumento

### 6.1. SOSTITUZIONE BATTERIE
Quando sul display LCD appare il simbolo "**🔋**" e l’indicazione “**bAtt**” (vedere Fig. 45) occorre sostituire le batterie, operando come segue:

Fig. 45: Videata con indicazione batteria scarica

1. Posizionare il selettore in posizione **OFF** e rimuovere i cavi dai terminali di ingresso
2. Ruotare la vite di fissaggio del vano batterie dalla posizione “**🔒**” alla posizione “**🔓**” e rimuovere lo stesso
3. Rimuovere la batteria e inserire nel vano la nuova batteria dello stesso tipo (vedere § 7.1.1) rispettando le polarità indicate
4. Riposizionare il vano batterie e ruotare la vite di fissaggio del vano batterie dalla posizione “**🔓**” alla posizione “**🔒**”
5. Non disperdere nell’ambiente le batterie utilizzate. Usare gli appositi contenitori per lo smaltimento

### 6.2. PULIZIA DELLO STRUMENTO
Per la pulizia dello strumento utilizzare un panno morbido e asciutto. Non usare mai panni umidi, solventi, acqua, ecc.

### 6.3. FINE VITA
> **ATTENZIONE**: il simbolo riportato sullo strumento indica che l'apparecchiatura ed i suoi accessori devono essere raccolti separatamente e trattati in modo corretto.

## 7. SPECIFICHE TECNICHE
### 7.1. CARATTERISTICHE TECNICHE
Incertezza calcolata come `[%lettura + (num. cifre *risoluzione)]` a 23°C ± 5°C, < 80%RH

**Tensione DC (Autorange)**

| Campo [V] | Risoluzione [V] | Incertezza | Impedenza di ingresso | Protezione contro i sovraccarichi |
| :-------- | :-------------- | :--------- | :-------------------- | :-------------------------------- |
| 0.0 ÷ 690.0 | 0.1             | ±(0.5%lettura + 2cifre) | 1M Ω                  | 690VDC/ACrms                      |

**Tensione AC, AC+DC, Loz TRMS (Autorange)**

| Campo [V] | Risoluzione [V] | Frequenza     | Incertezza              | Protezione contro i sovraccarichi |
| :-------- | :-------------- | :------------ | :---------------------- | :-------------------------------- |
| 0.5 ÷ 690.0 | 0.1             | 32Hz ÷ 1kHz   | ±(0.5%lettura + 2cifre) | 690VDC/ACrms                      |

Impedenza di ingresso funzione VAC: 1M Ω, Impedenza di ingresso funzione LoZ: 3.5k Ω per 10s (@ 110V/50Hz), 4.5s (@ 230V/50Hz), 1s (@ 400V/50Hz). Per valori di tensione superiori, l’impedenza di ingresso si alza oltre i 10k Ω. **ATTENZIONE: non lasciare collegato lo strumento per più di 1min**
Seleziona automatica modo DC, Max fattore di cresta: 1.5

**Frequenza corrente e tensione (Autorange)**

| Campo [Hz] | Risoluzione [Hz] | Incertezza            |
| :--------- | :--------------- | :-------------------- |
| 33.00 ÷ 99.99 | 0.01             | ±(0.1%lettura+1cifra) |
| 100.0 ÷ 999.9 | 0.1              |                       |

Campo tensione: 0.5V ÷ 690V, Campo corrente: 0.5A ÷ 3000A (Pinze Flex F300U), 1mV ÷ 1000mV (Pinze STD)

**Corrente AC TRMS (Pinza flessibile F3000U) – (Autorange)**

| Campo [mV] | Risoluzione [mV] | Incertezza (*)          |
| :--------- | :--------------- | :---------------------- |
| 1 ÷ 3000   | 1                | ±(0.5%lettura + 2cifre) |

(*) Per frequenza >100Hz l’incertezza è: `±(1.5%lettura + 5cifre)`
Max fattore di cresta: 3, Banda di frequenza: 1kHz

**Corrente AC TRMS (Pinza flessibile FS 1V) e DC, AC, AC+DC (Pinza STD) – (Autorange)**

| Campo [mV] | Risoluzione [mV] | Incertezza (*)          |
| :--------- | :--------------- | :---------------------- |
| 1 ÷ 1000   | 1                | ±(0.5%lettura + 2cifre) |

(*) Per frequenza >100Hz l’incertezza è: `±(1.5%lettura + 5cifre)`
Max fattore di cresta: 3, Banda di frequenza: 1kHz

**Corrente di spunto AC TRMS (Pinza flessibile F3000U)**

| Campo [mV] | Risoluzione [mV] | Incertezza (*)          |
| :--------- | :--------------- | :---------------------- |
| 1 ÷ 3000   | 1                | ±(2%lettura + 2cifre)   |

(*) Incertezza dichiarata per frequenza: DC, 42.5 ÷ 69Hz
Max fattore di cresta: 3, Frequenza campionamento: 4kHz; Soglia di rilevazione: 1%FS [A] fissa
Tempo di risposta: 1ms (Picco), 16.7ms, 20ms, 50ms, 100ms, 150ms, 175ms, 200ms (max RMS)

**Corrente di spunto AC TRMS (Pinza flessibile 1V) e DC, AC, AC+DC TRMS (Pinza STD)**

| Campo [mV] | Risoluzione [mV] | Incertezza (*)          |
| :--------- | :--------------- | :---------------------- |
| 1 ÷ 1000   | 1                | ±(2%lettura + 2cifre)   |

(*) Incertezza dichiarata per frequenza: DC, 42.5 ÷ 69Hz
Max fattore di cresta: 3, Frequenza campionamento: 4kHz; Soglia di rilevazione: 1%FS [A] fissa
Tempo di risposta: 1ms (Picco), 16.7ms, 20ms, 50ms, 100ms, 150ms, 175ms, 200ms (max RMS)

**Resistenza e Test Continuità (Autorange)**

| Campo [Ω]   | Risoluzione [Ω] | Incertezza              | Buzzer |
| :---------- | :-------------- | :---------------------- | :----- |
| 0.0 ÷ 199.9 | 0.1             | ±(1.0%lettura + 5cifre) | <30 Ω  |
| 200 ÷ 1999  | 1               |                         |        |

**Tensione e corrente armonica (Autorange)**

| Ordine armonica | Frequenza fondamentale | Risoluzione       | Incertezza (*) (valori non azzerati) |
| :-------------- | :--------------------- | :---------------- | :----------------------------------- |
| DC              | 42.5Hz ÷ 69Hz          | 0.1V / 0.1A /0.1% | ±(5.0 % lettura+20cifre)             |
| 1 ÷ 25          |                        |                   | ±(5.0 % lettura+10cifre)             |
| THD%            |                        | 0.1%              | ±(10.0 % lettura+10cifre)            |

L’incertezza dell’ampiezza delle armoniche espressa in % è valutata considerando l’incertezza del rapporto dei parametri
(*) Le tensioni armoniche sono azzerate nelle seguenti condizioni:
* 1a armonica: valore <0.5V
* DC, 2a a 25a armonica: valore armonica <0.5% valore fondamentale o valore <0.5V
(*) Le correnti armoniche sono azzerate nelle seguenti condizioni:
* 1a armonica: valore <0.5%FS pinza [A]
* DC, 2a a 25a armonica: valore armonica <0.5% valore fondamentale o valore <0.5%FS pinza [A]

**Impedenza Loop L-N, L-L, Ra, Ra RCD (no intervento RCD)**
Tensione L-PE, L-N, L-L: 100V ÷ 690V, 42.5 ÷ 69Hz
Corrente di prova: (vedere tabella seguente)

| Test    | Corrente di prova | Campo [Ω]   | Risoluzione [Ω] | Incertezza                       |
| :------ | :---------------- | :---------- | :-------------- | :------------------------------- |
| Ra RCD  | 15mA              | 1 ÷ 1999    | 1               | - 0%,+(5.0 % lettura + 3 Ω)      |
| L-N, L-L, Ra | 100mA             | 0.1 ÷ 199.9 | 0.1             | - 0%,+(5.0 % lettura + 0.3 Ω)    |

**Test su RCD (tipo scatolato istantaneo)**
Tipo di differenziale (RCD): AC (~), A (A),Generale (G)
Tensione L-PE, L-N: 100V ÷ 690V, 42.5 ÷ 69Hz
Correnti di intervento (IΔN): 30mA, 100mA, 300mA (vedere Tabella 1)
Tempo di intervento: risoluzione: 1ms, incertezza: `±(2.0 % lettura + 2cifre)`

**Tabella 1: Combinazioni possibili e durata tempo di intervento [ms]**
Tempi di intervento per differenziali RCD tipo scatolato (n.d. = funzione non disponibile)

|        | x 1/2 | x 1 | x 5 | AUTO                                       |
| :----- | :---- | :-- | :-- | :----------------------------------------- |
| G      | G     | G   | G   | G                                          |
| **30mA** | AC    | 300 | 310 | 40                                         |
|        | A     | 300 | 310 | 40                                         |
| **100mA**| AC    | 300 | 310 | n.d.                                       |
|        | A     | 300 | 310 | n.d.                                       |
| **300mA**| AC    | 300 | 310 | n.d.                                       |
|        | A     | 300 | 310 | n.d.                                       |

*AUTO column continues for 30mA AC/A with `x1 x5 x½` for each.
The actual table formatting in the PDF for AUTO is weird, it seems to imply the available sub-tests within AUTO, rather than a duration. I'll format as best as possible from the provided text, but it looks like the original PDF table might be malformed for the 'AUTO' column.*
For 30mA AC: `x1 x5 x½`
For 30mA A: `x1 x5 x½`
For 100mA AC: `x1 x½`
For 100mA A: `x1 x½`
For 300mA AC: `x1 x½`
For 300mA A: `x1 x½`
Considering the structure, it appears the "AUTO" column should indicate available tests, not durations. I will put them as `x1, x5, x½`.

|        | x 1/2 | x 1 | x 5 | AUTO               |
| :----- | :---- | :-- | :-- | :----------------- |
| G      | G     | G   | G   | G                  |
| **30mA** | AC    | 300 | 310 | 40                 | `x1, x5, x½` |
|        | A     | 300 | 310 | 40                 | `x1, x5, x½` |
| **100mA**| AC    | 300 | 310 | n.d.               | `x1, x½`     |
|        | A     | 300 | 310 | n.d.               | `x1, x½`     |
| **300mA**| AC    | 300 | 310 | n.d.               | `x1, x½`     |
|        | A     | 300 | 310 | n.d.               | `x1, x½`     |

**Corrente di intervento (Rampa I)**

| Tipo | I  N | Rampe [LCD]                 | Valore corrente [mA RMS @20ms] | Incertezza      |
| :--- | :---- | :-------------------------- | :----------------------------- | :-------------- |
| AC   | 30mA  | 6.0, 6.5, 7.0 .. 32.5, 33.3 | 6.0, 6.5, 7.0 .. 32.5, 33.0    | - 0%, +5%I  N |
| A    |       | 6.0, 6.5, 7.0 .. 32.5, 33.3 | 8.5, 9.2, 9.9 .. 46, 46.7      | - 0%, +5%I  N |

**Senso ciclico delle fasi a 1 terminale (*)**

| Campo tensione L-N, L-PE, L-L [V] | Campo frequenza |
| :-------------------------------- | :-------------- |
| 130 ÷ 690                         | 42.5 ÷ 69Hz     |

(*) Misura possibile con contatto diretto sulle parti metalliche dei conduttori (non su guaina isolante)

**Normative di riferimento**
*   **Sicurezza strumento**: IEC/EN61010-1, IEC/EN61010-2-030, IEC/EN61010-2-033
*   **EMC**: IEC/EN 61326-1
*   **Test RCD**: IEC/EN61557-6
*   **Test LOOP P-P, P-N, P-PE, Ra**: IEC/EN61557-3
*   **Senso ciclico delle fasi**: IEC /EN 61557-7
*   **Isolamento**: doppio isolamento
*   **Livello di inquinamento**: 2
*   **Categoria di misura**: CAT IV 600V, CAT III 690V verso terra e tra gli ingressi

#### 7.1.1. Caratteristiche generali
**Caratteristiche meccaniche**
*   **Dimensioni (L x La x H)**: 175 x 85 x 55mm (7 x 3 x 2in)
*   **Peso (batterie incluse)**: 420 g (15ounces)
*   **Protezione meccanica**: IP40

**Alimentazione**
*   **Tipo batteria**: 4 x 1.5V batterie tipo AAA IEC LR03
*   **Indicazione batteria scarica**: simbolo "**🔋**" a display
*   **Autonomia batterie**:
    *   V, A, Ω, → circa 132h (backlight OFF)
    *   V, A, Ω, → circa 68h (backlight ON)
    *   Ra (15mA) → circa 5400 test (backlight ON)
    *   Ra (100mA) → circa 13k test (backlight ON)
    *   RCD → circa 8600 test (backlight ON)
    *   RCD T → circa 160k test (backlight ON)
*   **Autospegnimento**: dopo 15min di non utilizzo (disabilitabile)

**Display**
*   **Tipo display**: 4 LCD, max 9999 punti, segno, punto decimale backlight e bargraph, indicazione polarità
*   **Frequenza campionamento**: 2 volte/s
*   **Conversione**: RMS

### 7.2. CONDIZIONI AMBIENTALI DI UTILIZZO
*   **Temperatura di riferimento**: 23 °C ± 5 °C (73°F ± 41°F)
*   **Temperatura di utilizzo**: 5 ° C ÷ 40 °C (41°F ÷ 104°F)
*   **Umidità relativa ammessa**: <80% RH
*   **Temperatura di conservazione**: -20 ° C ÷ 60 °C (-4°F ÷ 140°F)
*   **Umidità di conservazione**: <80% RH
*   **Altitudine max di utilizzo**: 2000m (6562ft)

Questo strumento è conforme ai requisiti della Direttiva Europea sulla bassa tensione 2014/35/EU (LVD) e della direttiva EMC 2014/30/EU
Questo strumento è conforme ai requisiti della direttiva europea 2011/65/CE (RoHS) e della direttiva europea 2012/19/CE (WEEE)

### 7.3. ACCESSORI
Vedere packing list allegata

## 8. ASSISTENZA
### 8.1. CONDIZIONI DI GARANZIA
Questo strumento è garantito contro ogni difetto di materiale e fabbricazione, in conformità con le condizioni generali di vendita. Durante il periodo di garanzia, le parti difettose possono essere sostituite, ma il costruttore si riserva il diritto di riparare ovvero sostituire il prodotto. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballo originale. Ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente. Il costruttore declina ogni responsabilità per danni causati a persone o oggetti.
La garanzia non è applicata nei seguenti casi:
* Riparazione e/o sostituzione accessori e batteria (non coperti da garanzia).
* Riparazioni che si rendono necessarie a causa di un errato utilizzo dello strumento o del suo utilizzo con apparecchiature non compatibili.
* Riparazioni che si rendono necessarie a causa di un imballaggio non adeguato.
* Riparazioni che si rendono necessarie a causa di interventi eseguiti da personale non autorizzato.
* Modifiche apportate allo strumento senza esplicita autorizzazione del costruttore.
* Utilizzo non contemplato nelle specifiche dello strumento o nel manuale d’uso.

Il contenuto del presente manuale non può essere riprodotto in alcuna forma senza l’autorizzazione del costruttore.
I nostri prodotti sono brevettati e i marchi depositati. Il costruttore si riserva il diritto di apportare modifiche alle specifiche ed ai prezzi se ciò è dovuto a miglioramenti tecnologici.

### 8.2. ASSISTENZA
Se lo strumento non funziona correttamente, prima di contattare il Servizio di Assistenza, controllare lo stato della batteria e dei cavi e sostituirli se necessario. Se lo strumento continua a manifestare malfunzionamenti controllare se la procedura di utilizzo dello stesso è conforme a quanto indicato nel presente manuale. Qualora lo strumento debba essere restituito al servizio post-vendita o ad un rivenditore, il trasporto è a carico del Cliente. La spedizione dovrà, in ogni caso, essere preventivamente concordata. Allegata alla spedizione deve essere sempre inserita una nota esplicativa circa le motivazioni dell’invio dello strumento. Per la spedizione utilizzare solo l’imballaggio originale; ogni danno causato dall’utilizzo di imballaggi non originali verrà addebitato al Cliente.

## 9. APPENDICI TEORICHE
### 9.1. TEST SU INTERRUTTORI DIFFERENZIALI (RCD)
**Scopo della prova**
Verificare (CEI 64-8 612.9, CEI 64-14 2.3.2.2) che i dispositivi di protezione differenziale Generali (G) siano stati installati e regolati correttamente e che conservino nel tempo le proprie caratteristiche. La verifica deve accertare che l’interruttore differenziale intervenga ad una corrente non superiore alla sua corrente nominale di funzionamento IdN e che il tempo di intervento non superi il tempo massimo dettato dalla normativa nel caso di interruttori differenziali di tipo Generale (secondo quanto descritto nella Tabella 2).
La prova dell’interruttore differenziale effettuata con il tasto di prova serve per far sì che “l’effetto colla” non comprometta il funzionamento del dispositivo rimasto inattivo per lungo tempo. Tale prova viene eseguita solo per accertare la funzionalità meccanica del dispositivo e non è sufficiente per poter dichiarare la conformità alla normativa del dispositivo a corrente differenziale. Da un’indagine statistica risulta che la verifica con tasto di prova degli interruttori effettuata una volta al mese riduce della metà il tasso di guasto di questi, però tale prova individua solo il 24% degli interruttori differenziali difettosi.

**Parti dell’impianto da verificare**
Tutti i differenziali devono essere testati quando vengono installati. Negli impianti a bassa tensione si consiglia di eseguire questa prova, fondamentale al fine di garantire un giusto livello di sicurezza. Nei locali ad uso medico tale verifica deve essere eseguita periodicamente su tutti i differenziali come imposto dalle norme CEI 64-8/7 e CEI 64-13.

**Valori ammissibili**
Su ogni RCD di tipo scatolato devono essere eseguite due prove: una con corrente di dispersione che inizi in fase con la semionda positiva della tensione (0°) e una con corrente di dispersione che inizi in fase con la semi onda negativa della tensione (180°). Il risultato indicativo è il tempo più alto. La prova a ½IdN non deve in nessun caso causare l'intervento del differenziale.

**Tabella 2: Tempi di intervento per interruttori RCD di tipo scatolato Generali**

| Tipo differenziale | IdN   | x 1   | x 5   | Descrizione                            |
| :----------------- | :---- | :---- | :---- | :------------------------------------- |
| Generale           | 0.3s  | 0.04s |       | Tempo di intervento massimo in secondi |

**Misura della corrente di intervento delle protezioni differenziali**
* Scopo della prova è verificare la reale corrente di intervento dei differenziali generali (**non si applica ai differenziali selettivi**)
* Per i differenziali con corrente differenziale fissa questa prova può essere eseguita per rilevare eventuali dispersioni di utilizzatori collegati all’impianto
* Nel caso non sia disponibile l’impianto di terra effettuare la prova collegando lo strumento con un terminale su un conduttore a valle del dispositivo differenziale ed un terminale sull'altro conduttore a monte del dispositivo stesso
* La corrente di intervento deve essere compresa fra ½I  N e I  N.

### 9.2. MISURA DELLA RESISTENZA GLOBALE DI TERRA NEGLI IMPIANTI TT
**Scopo della prova**
Verificare che il dispositivo di protezione sia coordinato con il valore della resistenza di terra. Non si può assumere a priori un valore di resistenza di terra limite di riferimento (ad esempio 20 Ω come dall’art. 326 del DPR 547/55) al quale fare riferimento nel controllo del risultato della misura, ma è necessario di volta in volta controllare che sia rispettato il coordinamento previsto dalla normativa.

**Parti dell’impianto da verificare**
L'impianto di terra nelle condizioni di esercizio. La verifica deve essere eseguita senza scollegare i dispersori.

**Valori ammissibili**
Il valore della resistenza globale di terra comunque misurato deve soddisfare la seguente relazione:
`R_A < 50 / I_a`
dove:
* `I_a` = corrente di intervento dell'interruttore automatico o corrente nominale di intervento del differenziale I  n espressa in A
* `50` = tensione di contatto limite di sicurezza (ridotta a 25V in ambienti particolari)

**ESEMPIO DI VERIFICA DI RESISTENZA DI TERRA**
Impianto protetto da un differenziale da 30mA
* Misura della resistenza globale di terra
* Per capire se la resistenza dell'impianto sia da considerarsi a norma moltiplicare il valore trovato per 0.03A (30mA)
* Se il risultato è inferiore a 50V (o 25V per ambienti particolari) l'impianto è da ritenersi coordinato perché rispetta la relazione indicata sopra

Quando si è in presenza di differenziali da 30mA (la quasi totalità degli impianti civili) la resistenza di terra massima ammessa è `50/0.03=1666 Ω` questo consente di utilizzare anche i metodi semplificati indicati che pur non fornendo un valore estremamente preciso, forniscono un valore sufficientemente approssimato per il calcolo del coordinamento.

### 9.3. MISURA DI LOOP E CALCOLO CORRENTE DI CORTOCIRCUITO PRESUNTA
**Scopo della prova**
Per anello di guasto (Loop) si intende il circuito che viene percorso dalla corrente provocata da un guasto d’isolamento verso terra (guasto franco). L’anello di guasto comprende:
* L’avvolgimento di fase del trasformatore
* Il conduttore di linea, fino al punto di guasto
* Il conduttore di protezione dal punto di guasto al centro stella del trasformatore.

Misurata l’impedenza è possibile determinare la corrente di guasto franco a terra (corrente di cortocircuito presunta **Isc**) e valutare se i dispositivi di protezione contro le sovracorrenti sono correttamente coordinate con per la protezione contro i contatti indiretti.

**Parti dell’impianto da verificare**
La prova deve essere effettuata obbligatoriamente nei sistemi TN e IT non protetti con dispositivi differenziali.

**Valori ammissibili**
L’obiettivo della misura è quello di verificare che la corrente di intervento del dispositivo automatico di protezione `Ia` soddisfi una delle seguenti relazioni:
* Per misura di impedenza di Linea/Loop L-PE: `Isc = U_L-PE / Z_LPE <= I_a`
* Per misura di impedenza di Linea/Loop L-N: `Isc = U_L-N / Z_LN <= I_a`
* Per misura di impedenza di Linea/Loop L-L: `Isc = U_L-L / Z_L <= I_a`

dove:
* `U_L-PE` = Tensione nominale L-PE impostata sullo strumento (vedere § 4.2.11)
* `U_L-N` = Tensione nominale L-N impostata sullo strumento (vedere § 4.2.11)
* `U_L-L` = Tensione nominale L-L impostata sullo strumento (vedere § 4.2.11)
* `Z_LPE` = Impedenza di Loop L-PE misurata dallo strumento
* `Z_LN` = Impedenza di Loop L-N misurata dallo strumento
* `Z_L` = Impedenza di Loop L-L misurata dallo strumento
* `I_SC` = Corrente di cortocircuito presunta misurata dallo strumento

### 9.4. ARMONICHE DI TENSIONE E CORRENTE
Qualsiasi onda periodica non sinusoidale può essere rappresentata tramite una somma di onde sinusoidali ciascuna con frequenza multipla intera della fondamentale secondo la relazione:
```
v(t) = V₀ + Σ[k=1 to ∞] Vk sin(kωt + φk)
```
ove:
* `V₀` = valore medio di v(t)
* `V₁` = ampiezza della fondamentale di v(t)
* `Vk` = ampiezza della k-esima armonica di v(t)

LEGENDA:
1. Fondamentale
2. Terza armonica
3. Onda distorta somma delle due componenti

Fig. 46: Effetto della sovrapposizione di due frequenze multiple l’una dell’altra

Nel caso della tensione di rete la fondamentale ha frequenza 50Hz, la seconda armonica ha frequenza 100 Hz, la terza armonica ha frequenza 150Hz e così via. La distorsione armonica è un problema costante e non deve essere confuso con fenomeni di breve durata quali picchi, diminuzioni o fluttuazioni. Si può osservare come dalla (1) discenda che ogni segnale è composto dalla sommatoria di infinite armoniche, esiste tuttavia un numero d’ordine oltre il quale il valore delle armoniche può essere considerato trascurabile. La normativa EN50160 suggerisce di troncare la sommatoria nell’espressione (1) alla 40a armonica. Un indice fondamentale per rilevare la presenza di armoniche è il parametro THD% (Distorsione armonica totale) definito come:
```
THD% = 100 x √( Σ[h=2 to 40] Vh² / V₁² )
```
Tale indice tiene conto della presenza di tutte le armoniche ed è tanto più elevato quanto più è distorta la forma d'onda.

**Valori limite per le armoniche**
La normativa EN50160 fissa i limiti per le tensioni armoniche che l'ente fornitore può immettere nella rete. In condizioni normali di esercizio, durante qualsiasi periodo di una settimana, il 95% dei valori efficaci di ogni tensione armonica, mediati sui 10 minuti, dovrà essere minore o uguale rispetto ai valori indicati in Tabella 3. La distorsione armonica globale (THD%) della tensione di alimentazione (includendo tutte le armoniche fino al 40° ordine) deve essere minore o uguale all’8%

**Tabella 3: Limiti per le tensioni armoniche che l'ente fornitore può immettere nella rete**

| Armoniche dispari Non multiple di 3 | Armoniche pari |
| :---------------------------------- | :------------- |
| Ordine h | Tensione relativa %Max | Ordine h | Tensione relativa % Max | Ordine h | Tensione relativa % Max |
| 5        | 6                      | 3        | 5                       | 2        | 2                       |
| 7        | 5                      | 9        | 1,5                     | 4        | 1                       |
| 11       | 3,5                    | 15       | 0,5                     | 6..24    | 0,5                     |
| 13       | 3                      | 21       | 0,5                     |          |                         |
| 17       | 2                      |          |                         |          |                         |
| 19       | 1,5                    |          |                         |          |                         |
| 23       | 1,5                    |          |                         |          |                         |
| 25       | 1,5                    |          |                         |          |                         |

Questi limiti, teoricamente applicabili solamente agli enti fornitori di energia elettrica, forniscono comunque una serie di valori di riferimento entro cui contenere anche le armoniche immesse in rete dagli utilizzatori.

---
HT ITALIA SRL
Via della Boaria, 40
48018 – Faenza (RA) – Italy
T +39 0546 621002 | F +39 0546 621144
M info@ht-instrumnents.com | www.ht-instruments.it

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

WHERE WE ARE
