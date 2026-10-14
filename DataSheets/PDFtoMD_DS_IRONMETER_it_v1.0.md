# DS_IRONMETER

<!-- Document: DS_IRONMETER -->
<!-- Language: it | Version: 1.0 -->
<!-- Generated via High-Fidelity PDFtoMD Parser -->

<!-- Chunk: Pagine 1-3 (Intero Documento) -->
## 1. SPECIFICHE ELETTRICHE

Incertezza calcolata come $\pm [\% \text{lettura} + (\text{num cifre} \times \text{risoluzione})]$ a 18°C ÷ 28°C, <75%HR

### TENSIONE DC

| Campo | Risoluzione | Incertezza | Protezione da sovraccarico |
| :--- | :--- | :--- | :--- |
| 400.0mV | 0.1mV | ±(1.0% lettura+3cifre) | 600VDC/ACrms |
| 4.000V | 0.001V | ±(1.0% lettura+3cifre) | 600VDC/ACrms |
| 40.00V | 0.01V | ±(1.0% lettura+3cifre) | 600VDC/ACrms |
| 400.0V | 0.1V | ±(1.0% lettura+3cifre) | 600VDC/ACrms |
| 600V | 1V | ±(1.0% lettura+3cifre) | 600VDC/ACrms |

Impedenza di ingresso: 10MΩ

### TENSIONE AC TRMS

| Campo | Risoluzione | Incertezza (50 ÷ 60Hz) (*) | Protezione da sovraccarico |
| :--- | :--- | :--- | :--- |
| 4.000V | 0.001V | ±(1.0% lettura+3cifre) | 600VDC/ACrms |
| 40.00V | 0.01V | ±(1.0% lettura+3cifre) | 600VDC/ACrms |
| 400.0V | 0.1V | ±(1.0% lettura+3cifre) | 600VDC/ACrms |
| 600V | 1V | ±(1.0% lettura+3cifre) | 600VDC/ACrms |

(*) Incertezza specificata dal 5% al 100% del campo di misura, Impedenza di ingresso: 10MΩ  
Campo misura frequenza: 50Hz ÷ 60Hz (forma d’onda arbitraria), 45Hz ÷ 1kHz (forma d’onda sinusoidale)  
Fattore di cresta: ≤ 3 (fino a 300V), ≤ 1.5 (fino a 600V)

### CORRENTE DC

| Campo | Risoluzione | Incertezza | Protezione da sovraccarico |
| :--- | :--- | :--- | :--- |
| 400.0µA | 0.1µA | ±(1.0% lettura+3cifre) | Fusibile Fast 0.5A/600V (ingressi mA, µA) |
| 4000µA | 1µA | ±(1.0% lettura+3cifre) | Fusibile Fast 0.5A/600V (ingressi mA, µA) |
| 40.00mA | 0.01mA | ±(1.0% lettura+3cifre) | Fusibile Fast 0.5A/600V (ingressi mA, µA) |
| 400.0mA | 0.1mA | ±(1.0% lettura+3cifre) | Fusibile Fast 0.5A/600V (ingressi mA, µA) |
| 4.000A | 0.001A | ±(1.2% lettura+3cifre) | Fusibile Fast 10A/600V (ingresso 10A) |
| 10.00A (*) | 0.01A | ±(1.2% lettura+3cifre) | Fusibile Fast 10A/600V (ingresso 10A) |

(*) 20A per max 30s con incertezza non dichiarata

### CORRENTE AC TRMS

| Campo | Risoluzione | Incertezza (*) 50Hz ÷ 60Hz | Protezione da sovraccarico |
| :--- | :--- | :--- | :--- |
| 400.0µA | 0.1µA | ±(1.2% lettura+3cifre) | Fusibile Fast 0.5A/600V (ingressi mA, µA) |
| 4000µA | 1µA | ±(1.2% lettura+3cifre) | Fusibile Fast 0.5A/600V (ingressi mA, µA) |
| 40.00mA | 0.01mA | ±(1.2% lettura+3cifre) | Fusibile Fast 0.5A/600V (ingressi mA, µA) |
| 400.0mA | 0.1mA | ±(1.2% lettura+3cifre) | Fusibile Fast 0.5A/600V (ingressi mA, µA) |
| 6.000A | 0.001A | ±(1.8% lettura+5cifre) | Fusibile Fast 10A/600V (ingresso 10A) |
| 10.00A (**) | 0.01A | ±(1.8% lettura+5cifre) | Fusibile Fast 10A/600V (ingresso 10A) |

(*) Incertezza specificata dal 5% al 100% del campo di misura  
(**) 20A per max 30s con incertezza non dichiarata

### PROVA DIODI

| Funzione | Corrente di prova | Tensione a vuoto |
| :--- | :--- | :--- |
| [Diodo ⯈|] | <0.35mA | 3VDC |

### RESISTENZA E TEST CONTINUITA’

| Campo | Risoluzione | Incertezza | Buzzer [•\|))] | Protezione da sovraccarico |
| :--- | :--- | :--- | :--- | :--- |
| 400.0Ω | 0.1Ω | ±(1.5% lettura+5cifre) | <50Ω | 600VDC/ACrms |
| 4.000kΩ | 0.001kΩ | ±(1.5% lettura+5cifre) | <50Ω | 600VDC/ACrms |
| 40.00kΩ | 0.01kΩ | ±(1.5% lettura+5cifre) | <50Ω | 600VDC/ACrms |
| 400.0kΩ | 0.1kΩ | ±(1.5% lettura+5cifre) | <50Ω | 600VDC/ACrms |
| 4.000MΩ | 0.001MΩ | ±(1.5% lettura+5cifre) | <50Ω | 600VDC/ACrms |
| 40.00MΩ | 0.01MΩ | ±(2.5% lettura+20cifre) | <50Ω | 600VDC/ACrms |

### FREQUENZA (Circuiti elettronici)

| Campo | Risoluzione | Incertezza | Sensibilità |
| :--- | :--- | :--- | :--- |
| 10.00Hz ÷ 10kHz | 0.01Hz | ±(1.2% lettura) | 15Vrms |

### DUTY CYCLE

| Campo | Risoluzione | Incertezza |
| :--- | :--- | :--- |
| 0.1 – 99.9% | 0.1% | ±(1.2%lettura + 2cifre) |

Campo frequenza impulso: 5Hz ÷ 150kHz, Ampiezza impulso: 100µs ÷ 100ms

### CAPACITA’

| Campo | Risoluzione | Incertezza | Protezione da sovraccarico |
| :--- | :--- | :--- | :--- |
| 40.00nF | 0.01nF | ±(4.5% lettura+10cifre) | 600VDC/ACrms |
| 400.0nF | 0.1nF | ±(4.5% lettura+10cifre) | 600VDC/ACrms |
| 4.000µF | 0.001µF | ±(3.0% lettura+5cifre) | 600VDC/ACrms |
| 40.00µF | 0.01µF | ±(3.0% lettura+5cifre) | 600VDC/ACrms |
| 400.0µF | 0.1µF | ±(3.0% lettura+5cifre) | 600VDC/ACrms |
| 4000µF | 1µF | ±(5.0% lettura+5cifre) | 600VDC/ACrms |

---

## 2. SPECIFICHE GENERALI

**Display:**
• Display LCD, 4 cifre con lettura massima 4000 punti più segno e punto decimale  
• Indicazione automatica polarità  
• Retroilluminazione  
• Indicazione fuori scala “OL”  
• Frequenza campionamento: 3volte/s  

**Funzioni:**
• Data HOLD  
• MAX/MIN  
• Torcia integrata  
• Auto Power OFF dopo 15 minuti di non utilizzo  

**Indicazione batteria scarica:**
• Il simbolo "[Batteria Scarica]" appare quando la tensione della batteria è troppo bassa  

**Temperatura di esercizio:**
• 5°C ÷ 50°C, <80%HR  

**Temperatura di conservazione:**
• -20°C ÷ 60°C, <80%HR  

**Informazioni generali:**
• Altitudine max: 2000m  
• Grado di inquinamento: 2  
• Isolamento: doppio isolamento ⧈  

**Alimentazione:**
• 2 x 1.5V batterie tipo AAA LR03  

**Dimensioni (L x W x H)**
• 120 x 65 x 45 mm  

**Peso (batterie incluse)**
• 200 g  

**Normative di riferimento:**
• Sicurezza: IEC/EN61010-1, CAT III 600V  
• EMC: IEC/EN61326-1  

Questo strumento è conforme ai requisiti della Direttiva Europea sulla bassa tensione 2006/95/CE e della direttiva EMC 2004/108/CE  

Questo strumento è conforme ai requisiti della direttiva europea 2011/65/EU (RoHS) e della direttiva europea 2012/19/EU (WEEE)