
### Tipi di dato primitivi in Java (2024)

I **tipi di dato primitivi** rappresentano i costituenti fondamentali in Java. Essi forniscono le basi per la dichiarazione delle variabili e la gestione dei dati semplici, come numeri, caratteri e valori booleani. A differenza dei tipi di dato complessi, i tipi primitivi **non sono oggetti** e non possiedono metodi. Con l'evoluzione di Java fino al 2024, il loro ruolo rimane cruciale, specialmente per le operazioni di basso livello che richiedono efficienza e semplicità.

---

![Types](img/PrimitiveVsReference.png)

---

### 1. **byte:**
   - **Dimensione:** 8 bit
   - **Intervallo:** -128 a 127
   - Utilizzato principalmente per risparmiare memoria in grandi array, soprattutto in file binari.

### 2. **short:**
   - **Dimensione:** 16 bit
   - **Intervallo:** -32,768 a 32,767
   - Spesso utilizzato quando lo spazio in memoria è limitato, come per rappresentare numeri in applicazioni embedded.

### 3. **int:**
   - **Dimensione:** 32 bit
   - **Intervallo:** -2,147,483,648 a 2,147,483,647
   - Il tipo più comunemente utilizzato per rappresentare numeri interi.

### 4. **long:**
   - **Dimensione:** 64 bit
   - **Intervallo:** -9,223,372,036,854,775,808 a 9,223,372,036,854,775,807
   - Usato per numeri interi che superano l'intervallo dell'`int`.

---

### 5. **float:**
   - **Dimensione:** 32 bit
   - **Precisione:** Circa 7 cifre decimali
   - Utilizzato per i numeri decimali quando la precisione richiesta non è molto elevata (come per i calcoli grafici o scientifici).

### 6. **double:**
   - **Dimensione:** 64 bit
   - **Precisione:** Circa 15 cifre decimali
   - Il tipo preferito per rappresentare numeri decimali in applicazioni di calcolo più complesse.

### 7. **char:**
   - **Dimensione:** 16 bit
   - **Intervallo:** 0 a 65,535 (rappresenta un singolo carattere Unicode)
   - Utilizzato per memorizzare caratteri singoli, tra cui simboli speciali e lettere in lingue diverse.

### 8. **boolean:**
   - **Dimensione:** non specificata (generalmente 1 bit)
   - Può assumere solo i valori `true` o `false`
   - Utilizzato principalmente per controllare il flusso dei programmi tramite condizioni logiche.

---
