#SINTESI

La tecnologia anti-contraffazione ha attirato notevole attenzione con lo sviluppo economico. Sono stati prodotti molti prodotti contraffatti difficili da identificare, che danneggiano gravemente gli interessi dei consumatori. L'atteggiamento del pubblico di cercare il piccolo risparmio e il basso costo ha incoraggiato produttori privi di scrupoli ad approfittarne, offrendo prodotti contraffatti a basso costo, comprimendo i profitti dei produttori legittimi e facendo perdere fiducia nel pubblico sulla qualità dei prodotti. Attualmente, il sistema anti-contraffazione più diffuso si basa su codici QR o tag RFID disponibili sul mercato, ma questi sistemi spesso fanno affidamento su database centralizzati, introducendo punti unici di fallimento e necessità di fiducia nell'ente gestore.

Questo progetto propone un sistema radicalmente **trustless** (che non richiede fiducia in intermediari) basato su tecnologia blockchain e token NFT (Non-Fungible Token). Il sistema **non si limita** a fornire tracciabilità, ma certifica in modo immutabile e verificabile pubblicamente sia l'autenticità che la **proprietà** del bene. Il **Produttore**, dotato di identità digitale, per ogni singolo prodotto emette un **certificato digitale** firmato digitalmente, contenente dati di produzione, caratteristiche, termini d'uso e garanzia. L'hash crittografico di questo certificato viene incorporato in un **token NFT** che rappresenta il prodotto stesso.

Il possesso di questo token NFT equivale al titolo di proprietà digitale del bene fisico. Il trasferimento della proprietà avviene mediante trasferimento del token NFT tra wallet digitali, registrato in modo immutabile sulla blockchain. Un codice QR o un tag RFID sul prodotto contiene esclusivamente l'**hash del certificato** o un identificativo univoco del token NFT, fungendo da semplice **link fisico** per accedere al sistema di verifica. Scansionando il codice, chiunque può, in modo anonimo e senza richiedere account, verificare l'autenticità del prodotto confrontando gli hash e consultare la **chiave pubblica** del wallet che detiene legalmente il token NFT (e quindi il bene), garantendo che il venditore sia effettivamente il legittimo proprietario prima dell'acquisto. Questo approccio elimina la necessità di fidarsi di enti centrali, riduce drasticamente i costi di certificazione e garantisce una verifica dell'autenticità e della proprietà incontrovertibile, decentralizzata e permanente.

**Parole chiave:** Tecnologia anti-contraffazione, Blockchain, NFT (Token Non Fungibile), Firma digitale, Certificato digitale, Tracciabilità, Proprietà digitale, Sistema Trustless, QR Code, RFID

#INTRODUZIONE

La contraffazione consiste nella produzione, importazione, esportazione, distribuzione e vendita di beni di consumo non autentici ma progettati e marchiati per apparire identici ai prodotti originali. Viene effettuata per ingannare i consumatori, convincendoli della loro autenticità. La contraffazione include anche l'apposizione del marchio o del logo di un noto brand consumer su un prodotto, sebbene quest'ultimo non sia effettivamente realizzato o autorizzato da quel marchio. In termini semplici, i prodotti contraffatti sono imitazioni di prodotti reali fabbricati senza l'approvazione del proprietario del marchio. I prodotti contraffatti sono generalmente di qualità sostanzialmente inferiore rispetto ai beni autentici e possono persino essere pericolosi, poiché spesso sono realizzati in modo scadente o utilizzando sostanze chimiche e materiali pericolosi o tossici. I prodotti contraffatti spaziano da beni di lusso di alta gamma come orologi, profumi o pelletteria, a prodotti business-to-business come macchinari, prodotti chimici o ricambi, fino a comuni prodotti di consumo come giocattoli, farmaci, cosmetici e alimenti. In effetti, qualsiasi prodotto protetto da proprietà intellettuale può essere contraffatto. Sfortunatamente, molte aziende note e di successo, in quasi tutti i settori, sono vittime della contraffazione.

##Storia della Blockchain

La blockchain non è solo un database, ma una nuova stack tecnologica con "fiducia digitale" che sta rivoluzionando il modo in cui scambiamo valore e informazioni attraverso Internet, eliminando le "figure intermediarie" dal processo. Il primo protocollo simile a una blockchain fu proposto dal crittografo David Chaum nel 1982. Successivamente, nel 1991, Stuart Haber e W. Scott Stornetta scrissero del loro lavoro sui Consortium. Ma fue Satoshi Nakamoto (presunto pseudonimo di una persona o gruppo di persone) a inventare e implementare la prima rete blockchain dopo aver distribuito la prima valuta digitale al mondo, il Bitcoin. Poiché la tecnologia blockchain è la tecnologia sottostante, non può essere posseduta. È come Internet. Ma chiunque può utilizzare la tecnologia per eseguire e possedere le proprie blockchain.

##Dichiarazione del Problema

La contraffazione non è un crimine senza vittime. I contraffattori spesso approfittano del desiderio dei consumatori per prezzi bassi. Acquistare prodotti contraffatti può sembrare un'opzione economica rispetto all'originale, ma quel prezzo basso ha un costo elevato per sé stessi e per gli altri. Le organizzazioni manifatturiere che operano in conformità alla legge sono minacciate dalla contraffazione perché causa perdite di ricavi. La contraffazione può avvenire sia con prodotti locali che di marca. I prodotti contraffatti e di bassa qualità ignorano la sicurezza dei consumatori. I prodotti contraffatti degradano l'economia. Un portale di verifica dei prodotti basato su vendor presenta diverse limitazioni, tra cui violazioni della sicurezza e inaccessibilità a lungo termine. La necessità è quindi di un sistema decentralizzato, immutabile e verificabile pubblicamente che certifichi l'origine e la proprietà di un bene.

##Sistema Esistente

La maggior parte delle aziende che valorizzano il proprio marchio e business dispone di meccanismi di tracciamento e controllo per scoraggiare, se non eliminare, la produzione e distribuzione di contraffatti. Ciò include adesivi ologrammi, filigrane, comunicazione di massa, controlli a sorpresa, sistemi di distribuzione controllati e implementazioni robuste di sistemi ERP.
*   **Identificazione di contraffatti tramite codice QR su smartphone:** La soluzione prevede una semplice identificazione basata su codice QR che può aiutare l'utente finale e il venditore dell'azienda a scansionare e identificare l'autenticità del prodotto utilizzando uno smartphone.
*   **Soluzioni anti-contraffazione basate sulla tecnologia NFC:** Il cliente può utilizzare smartphone con funzionalità NFC per avvicinare e leggere i dati sul chip NFC applicato sul prodotto per verificarne l'autenticità.
*   **Soluzione di Tracciamento e Rintracciamento Anti-Contraffazione basata su RFID:** L'identificazione a radiofrequenza avviene utilizzando minuscoli chip che emettono campi elettromagnetici per identificare e tracciare automaticamente i tag applicati agli oggetti.
*   **Metodo anti-contraffazione basato su etichetta elettronica RFID:** Secondo il metodo, viene effettuato un binding tra un'etichetta elettronica a ultra alta frequenza e un prodotto che necessita di un processo anti-contraffazione.
Questi sistemi, sebbene utili, spesso rimangono centralizzati o isolati, limitandone l'efficacia e la fiducia complessiva.

##Sistema Proposto

Nel sistema anti-contraffazione basato su Blockchain proposto, ciascun **soggetto coinvolto nella filiera** (ad esempio, fornitori, produttori, fabbriche, operatori logistici, rivenditori e consumatori) partecipa come nodo della Blockchain per effettuare transazioni e contribuire a mantenere la Blockchain aggiornata. Unendosi alla Blockchain, a ciascun nodo viene assegnata una coppia di chiavi pubblica/privata per eseguire operazioni crittografiche sicure secondo l'architettura Blockchain.

**Innovazione Fondamentale: Sistema Trustless di Autenticità e Proprietà**
A differenza di sistemi analoghi che utilizzano QR code o RFID semplicemente per collegarsi a un database centralizzato (creando un punto unico di fallimento e richiedendo fiducia nel gestore del database), il sistema qui proposto è completamente **trustless** e decentralizzato.

Il **Produttore**, dotato di un'**identità digitale**, per ogni singolo prodotto emette un **certificato digitale** firmato digitalmente. Questo certificato, consultabile pubblicamente, contiene dati salienti come dati di produzione, caratteristiche del prodotto, termini e condizioni d'uso, avvertenze e dettagli sulla garanzia.

L'**hash crittografico** univoco e immutabile di questo certificato viene incorporato nella fase di creazione in un **token NFT (Non-Fungible Token)** che rappresenta digitalmente il prodotto. Inizialmente, questo token è posseduto dal produttore e certifica l'autenticità e l'origine. Dal momento della prima vendita, il token NFT diventa rappresentativo della **proprietà** del bene fisico. Il trasferimento di proprietà del bene avviene esclusivamente attraverso il trasferimento del token NFT dal wallet del venditore a quello dell'acquirente sulla blockchain, operazione registrata in modo permanente e immutabile.

**Ruolo del QR Code / RFID: Un semplice link, non un database**
Il codice QR o il tag RFID applicato fisicamente sul prodotto **non contiene dati sensibili** e non è il vettore primario di autenticità. Esso contiene esclusivamente l'**hash del certificato** o l'**identificativo univoco del token NFT**. La sua funzione è puramente quella di essere un **punto di accesso**, un link fisico che reindirizza chi lo scansiona (tramite app o web app) al sistema telematico decentralizzato per la verifica.

**Verifica Trustless dell'Autenticità e della Proprietà**
Un consumatore che scansiona il codice su un prodotto in negozio attiva il seguente processo trustless:
1.  Il sistema recupera l'hash o l'ID dal codice.
2.  Interrogando la blockchain (lettura pubblica, senza necessità di login), recupera:
    *   L'hash del certificato originale memorizzato nel metadata del token NFT.
    *   L'indirizzo del wallet (chiave pubblica) che è attualmente il proprietario del token NFT.
3.  Recupera indipendentemente il certificato digitale originale dal repository pubblico del produttore (usando l'hash o l'ID come riferimento).
4.  Calcola l'hash del certificato appena recuperato.
5.  **Confronto di Autenticità:** Se l'hash calcolato corrisponde ESATTAMENTE all'hash memorizzato sulla blockchain, il prodotto è autentico. Qualsiasi discrepanza indica una contraffazione.
6.  **Verifica della Proprietà:** Il sistema visualizza la **chiave pubblica** del proprietario corrente del token NFT. In un contesto di vendita al dettaglio, il consumatore può verificare che questa chiave pubblica corrisponda a quella resa pubblica dall'esercente stesso, confermando che il venditore è il legittimo proprietario del bene che sta vendendo.

**Trasferimento di Proprietà**
Al momento dell'acquisto, l'acquirente riceve nel proprio wallet digitale il token NFT tramite una transazione sulla blockchain. Questo trasferimento aggiorna irrevocabilmente la proprietà del bene. Da quel momento, una nuova scansione del codice mostrerà la chiave pubblica del nuovo proprietario, dimostrando il passaggio di proprietà in modo trasparente e incontrovertibile.

Questo sistema elimina completamente la necessità di fidarsi di un ente centrale per la verifica dell'autenticità o della titolarità del bene. La verifica si basa su matematica crittografica e sul consenso decentralizzato della blockchain, rendendo il sistema immune a manomissioni e contraffazioni.

**2. SPECIFICHE DEI REQUISITI**

**2.1 Requisiti Software**

*   **Lato Server:** Python 3.7.4 (64-bit) o (32-bit)
*   **Lato Client:** HTML, CSS, JavaScript, Bootstrap (o framework frontend simile)
*   **Framework Backend:** Flask 1.1.1 (o Django per gestione utenti più complessa)
*   **Back end Database:** MySQL 5 (per dati off-chain e cache)
*   **Blockchain & Smart Contract:** Solidity (o Vyper), Web3.py libreria, Node.js, Truffle Suite/Hardhat (per sviluppo e testing)
*   **Infrastruttura Blockchain:** Rete Ethereum, Polygon, o altra EVM-compatible per NFT e smart contract (o una blockchain permissioned basata su Geth/Besu).
*   **Gestione Wallet:** Integrazione con MetaMask o librerie simili (es: Web3Modal) per la gestione dei wallet utente.
*   **Firme Digitali:** Librerie crittografiche (es: OpenSSL integrato, `cryptography` in Python) per la generazione e verifica delle firme dei certificati digitali (il processo principale avverrà comunque on-chain per i trasferimenti NFT).
*   **Server:** WampServer 2i (o stack LAMP/MAMP equivalente)
*   **Altri strumenti:** Node Package Manager (npm), Virtualenv, Ganache (per sviluppo locale), IPFS (opzionale, per memorizzare metadati NFT o certificati off-chain).

**2.2 Requisiti Hardware**

*   **Processori:** Intel® Core™ i5 processor 4300M a 2.60 GHz o 2.59 GHz (1 socket, 2 core, 2 thread per core), 8 GB de RAM (si consigliano 16 GB per un nodo blockchain completo locale)
*   **Spazio su disco:** 320 GB (lo spazio necessario per un nodo blockchain completo può essere significativamente maggiore, a seconda della blockchain scelta)
*   **Sistemi operativi:** Windows® 10, macOS*, e Linux* (Linux è spesso preferito per nodi server)

**3. METODOLOGIA**

**3.1 Architettura del Sistema**
Un'architettura di sistema è il modello concettuale che definisce la struttura, il comportamento e altre viste di un sistema. Una descrizione architetturale è una descrizione e rappresentazione formale di un sistema, organizzata in modo da supportare il ragionamento sulle strutture e sui comportamenti del sistema.

**Innovazione Trustless e Ruolo del Codice Fisico:**
Il sistema è progettato per essere **trustless**. Il codice QR o RFID sul prodotto (**Tag Fisico**) contiene solo un identificativo (es. l'hash del certificato o l'ID del token NFT). La sua unica funzione è di essere letto da uno scanner e **reindirizzare** il dispositivo alla **Piattaforma di Verifica Pubblica** (es. un sito web o un'app decentralizzata - dApp).

La Piattaforma di Verifica Pubblica, interagendo con la **Blockchain** e il **Repository Pubblico dei Certificati**, esegue le verifiche crittografiche in modo autonomo e trasparente per l'utente:
1.  Recupera i dati dalla blockchain (hash memorizzato, proprietario corrente).
2.  Recupera il certificato dal repository pubblico.
3.  Esegue il confronto crittografico degli hash.
4.  Visualizza all'utente il risultato dell'autenticità e la chiave pubblica del proprietario legittimo.

L'utente non deve fidarsi della piattaforma: può potenzialmente verificare in autonomia i dati sulla blockchain. La piattaforma è solo un'interfaccia che facilita questa verifica.

**Figura 1:** Architettura di Sistema del Sistema di Verifica dei Prodotti Autentici con integrazione NFT e Certificati Digitali.

**3.2 Flusso del Sistema**
I flussi di sistema sono modelli che show le attività e le decisioni che i sistemi eseguono. Sono utili per comprendere interazioni di sistema complesse perché mostrano visivamente le interazioni avanti e indietro tra i sistemi e i rami complessi.

**Flusso Principale: Autenticazione e Verifica Proprietà**
1.  **Consumatore:** Avvia verifica sul Portale Web (fornisce ID NFT o scansione codice).
2.  **Portale Web:** Invia richiesta alla Blockchain (leggere lo smart contract per ottenere l'hash memorizzato nel token NFT e la storia proprietari).
3.  **Blockchain / Smart Contract:** Restituisce l'hash del certificato e lo storico dei trasferimenti.
4.  **Portale Web:** Invia richiesta al Repository Pubblico dei Certificati (per ottenere il certificato originale basato sull'ID prodotto/nft).
5.  **Repository Certificati:** Restituisce il certificato digitale.
6.  **Portale Web:** Calcola localmente l'hash del certificato ricevuto.
7.  **Portale Web:** Confronta l'hash calcolato con l'hash recuperato dalla blockchain.
    *   Se **COINCIDONO** -> Prodotto Autentico + Mostra storico proprietà (se pubblico).
    *   Se **NON COINCIDONO** -> Possibile Contraffazione/Manomissione -> Avviso all'Utente e (opzionale) Alert al Produttore.
8.  **Portale Web:** Visualizza il risultato della verifica al Consumatore.

**Soggetti della Filiera (Produttore, Distributore, Rivenditore):** Interagiscono principalmente con il sistema attraverso i loro Wallet e il Portale Web per:
*   **Produttore:** Creare NFT e certificati, trasferire NFT.
*   **Distributore/Rivenditore:** Ricevere e trasferire NFT (accettando transazioni via wallet).
Tutte queste azioni generano transazioni sulla Blockchain.

**Figura 2:** Flusso di Sistema per il Sistema di Verifica dei Prodotti Autentici.

**3.3 Diagramma di Flusso (Flowchart)**
[Testo del flowchart]
**Start**
|
**Produttore (Login con Identità Digitale/Wallet)**
|-> Crea Prodotto -> Genera & Firma Certificato Digitale -> Pubblica Certificato
|-> Genera Hash Certificato -> Crea Token NFT con Hash -> [Blocco Creato su Blockchain]
|-> Aggiungi Distributore (Reg.)
|-> Trasferisci NFT al Distributore -> [Transazione su Blockchain]
|
**Distributore (Login con Wallet)**
|-> Riceve NFT -> (Verifica Opzionale)
|-> Aggiungi Rivenditore (Reg.)
|-> Trasferisci NFT al Rivenditore -> [Transazione su Blockchain]
|
**Rivenditore (Login con Wallet)**
|-> Riceve NFT -> (Verifica Opzionale)
|-> Vendi a Cliente -> Trasferisci NFT al Cliente -> [Transazione su Blockchain]
|
**Consumatore (Login con Wallet / Accesso Portale)**
|-> Possiede NFT nel Wallet
|-> **Verifica Prodotto (Portale Web):**
    |-> Inserisci ID NFT
    |-> Portale recupera Hash da Blockchain
    |-> Portale recupera Certificato da Repository Pubblico
    |-> Portale calcola Hash del Certificato
    |-> Hash Calcolato == Hash da Blockchain?
        |-> **Sì** -> Prodotto Autentico -> Visualizza Info (Storico?)
        |-> **No** -> Prodotto Potenzialmente Contraffatto -> Avviso Utente & Produttore
|-> (Opzionale: Trasferisci NFT ad altro Wallet per vendita)
|
**Stop**
(Tutti i trasferimenti e le creazioni avvengono tramite transazioni sulla **Blockchain** e interagiscono con il **Database** del portale per dati off-chain e cache)

**3.4 Descrizione del Funzionamento**

I sistemi basati su blockchain per l'anti-contraffazione sono realizzati sviluppando un portale dedicato integrato con smart contract per la gestione di NFT. Il sistema è utilizzato da produttori, distributori, rivenditori e clienti, ciascuno dotato di un wallet digitale.

Il **Produttore**, autenticato con la propria identità digitale, per ogni prodotto genera un **certificato digitale** dettagliato (dati produzione, caratteristiche, avvertenze, garanzia) e lo firma digitalmente. Questo certificato viene reso **pubblicamente consultabile**. Successivamente, calcola l'hash crittografico univoco di questo certificato e utilizza uno **smart contract** per creare un **token NFT** associato in modo univoco a quel prodotto, incorporando al suo interno questo hash immutabile. Il token NFT viene inizialmente custodito nel wallet del produttore.

Il trasferimento del prodotto fisico lungo la filiera (Produttore -> Distributore -> Rivenditore -> Consumatore) è accompagnato dal **trasferimento del token NFT** tra i wallet digitali delle parti coinvolte. Ogni trasferimento è una transazione sulla blockchain, registrata in modo permanente e immutabile. Il token NFT evolve quindi da certificato di autenticità e tracciabilità a **titolo di proprietà digitale** del bene fisico una volta che raggiunge il consumatore.

Il **portale web / dApp di verifica** è un'interfaccia pubblica e accessibile a tutti senza necessità di registrazione. Il suo unico scopo è interrogare la blockchain e il repository dei certificati per conto dell'utente e visualizzare i risultati delle verifiche crittografiche.

Quando un utente scansiona il **codice QR o RFID** sul prodotto:
1.  Il codice contiene un identificativo (es. `0x123abc...` hash del certificato o ID NFT).
2.  Il dispositivo viene reindirizzato alla Piattaforma di Verifica Pubblica, passando questo identificativo.
3.  La Piattaforma, **senza richiedere alcun login o dato personale**, interroga la blockchain per trovare il token NFT associato a quell'identificativo e recuperare:
    *   L'**hash del certificato** memorizzato nel token.
    *   La **chiave pubblica** del wallet che attualmente possiede il token (il proprietario legale).
4.  La Piattaforma recupera quindi il **certificato digitale originale** dal repository pubblico, utilizzando l'identificativo ricevuto.
5.  Calcola **localmente** l'hash SHA-256 del certificato recuperato.
6.  **Confronto Trustless:** Confronta l'hash appena calcolato con quello recuperato dalla blockchain.
    *   **Se coincidono:** La Piattaforma visualizza un messaggio di "**Prodotto Autentico**". Mostra inoltre la **chiave pubblica del proprietario corrente**. In un negozio, il cliente può confrontare questa chiave con quella esposta pubblicamente dal negozio (es. su un certificato di proprietà in sede) per verificarne la corrispondenza prima dell'acquisto.
    *   **Se non coincidono:** La Piattaforma visualizza un messaggio di "**Avviso: Possibile Contraffazione**". L'hash sul certificato pubblico non corrisponde a quello registrato sulla blockchain al momento della creazione del prodotto, indicando che il certificato è stato alterato o che il prodotto è falso.
7.  **Dopo l'acquisto,** il trasferimento del token NFT aggiorna la proprietà sulla blockchain. Una successiva scansione mostrerà la chiave pubblica del nuovo proprietario (l'acquirente), dimostrando il cambio di proprietà in modo trasparente e trustless.

Questo processo garantisce che la verifica dell'autenticità e della legittima proprietà sia completamente decentralizzata, basata su prove crittografiche e non richieda fiducia in alcuna delle parti involved o in un'autorità di certificazione centrale.

**3.5 Moduli**

**3.5.1 Portale Web / dApp di Verifica Pubblica Trustless**
Questo modulo è fondamentale per l'approccio trustless. È un'applicazione web decentralizzata (dApp) o un portale con le seguenti caratteristiche:
*   **Accesso Pubblico e Anonimo:** Non richiede registrazione, login o fornitura di dati personali per la verifica di base.
*   **Interfaccia di Verifica Semplice:** Un campo per inserire un codice o una funzionalità di scansione QR/RFID.
*   **Lettore Blockchain:** Si connette a un nodo blockchain per interrogare gli smart contract e leggere i dati dei token NFT (hash del certificato, proprietario corrente).
*   **Client per Repository Certificati:** Recupera i certificati digitali dal repository pubblico basandosi sull'identificativo ricevuto.
*   **Motore di Verifica Crittografica:** Esegue localmente nel browser dell'utente il calcolo dell'hash del certificato recuperato e il confronto con quello sulla blockchain.
*   **Visualizzazione Risultati Chiara:** Mostra in modo inequivocabile l'esito della verifica (Autentico/Non Autentico) e la chiave pubblica del proprietario legittimo, senza interpretazioni o necessità di fidarsi del portale stesso.

**3.5.2 Integrazione Blockchain e Smart Contract**
Questo modulo è fondamentale e ha diverse funzioni:
*   **Comunicazione con la Blockchain:** Interagisce con la rete blockchain (es: Ethereum) utilizzando librerie come Web3.js o Web3.py per leggere dati (hash, proprietari) e inviare transazioni (trasferimenti).
*   **Gestione degli Smart Contract:** Distribuisce e interagisce con gli smart contract che governano la creazione e il trasferimento dei token NFT.
*   **Scelta del Tipo di Nodo:** Fornisce opzioni per gli utenti per essere un nodo completo (che sincronizza tutta la blockchain) o un nodo leggero (che si affida a provider esterni per accedere ai dati). Per gli utenti finali, la modalità light è preferibile per ridurre i costi di manutenzione.

**3.5.3 Smart Contract**
Simile a un trasferimento di valore su una blockchain, la distribuzione di uno smart contract su una blockchain occurs inviando una transazione from a wallet for the blockchain. La transazione include il codice compilato per lo smart contract as well as a special receiver address. That transaction must then be included in a block that is added to the blockchain, at which point the smart contract’s code will execute to establish the initial state of the smart contract. Gli smart contract in questo sistema gestiscono:
*   La creazione dei Token NFT (con incorporazione hash certificato).
*   Le regole di trasferimento dei token tra wallet (proprietà).
*   Il mantenimento di un registro immutabile di tutti i trasferimenti.

**3.5.4 Modulo Utente Finale**

**3.5.4.1 Produttore**
Il produttore è l'entità che da vita al prodotto nel sistema digitale. Oltre ad acquistare materie prime e produrre il bene, ha il compito cruciale di:
*   Generare e firmare digitalmente il **Certificato Digitale** per ogni prodotto o lotto.
*   Pubblicare il certificato in un **Repository Pubblico**.
*   Utilizzare uno **smart contract** per coniare il **Token NFT** corrispondente, incorporando l'hash del certificato.
*   Trasferire il token NFT al primo soggetto della filiera (es. distributore).

**3.5.4.2 Distributori**
Come intermediario nella filiera, il distributore aggiorna la proprietà digitale ricevendo e trasferendo il token NFT, garantendo che la catena di custodia digitale rimanga intatta e verificabile.

**3.5.4.3 Retailers**
Il rivenditore è il punto di contatto finale prima del consumatore. Acquista prodotti (e token NFT) dal distributore e li trasferisce ai consumatori finali al momento della vendita. Ha un diretto interesse a verificare l'autenticità dei prodotti che acquista e a trasferire correttamente la proprietà per garantire la soddisfazione del cliente e la protezione del proprio brand.

**3.5.4.4 Consumers**
Il consumatore è il proprietario finale. Può scegliere di partecipare alla rete come nodo leggero, verificando l'autenticità e la proprietà interrogando la blockchain, o come nodo completo. Riceve il token NFT al momento dell'acquisto, diventando il proprietario registrato del bene.

**4. ANALISI DELLA SICUREZZA E ROBUSTEZZA DEL MODELLO**

Il sistema proposto introduce un paradigma radicalmente nuovo nella verifica dell'autenticità e nella gestione della proprietà. Per comprenderne appieno il valore, è necessario analizzarne la robustezza rispetto a potenziali attacchi e chiarire la filosofia pratica alla base del concetto di proprietà digitale.

**4.1 Immunità alla Clonazione del Puntatore Fisico**

Un'obiezione comune ai sistemi basati su QR code è la presunta facilità con cui un malintenzionato può clonare il codice da un prodotto autentico e apporlo su uno contraffatto. Tuttavia, questa vulnerabilità è tipica dei sistemi centralizzati dove il codice *è* la credenziale. Nel nostro sistema **decentralizzato e basato sulla proprietà del token**, il codice QR è un **mero puntatore** e la sua clonazione non conferisce alcun vantaggio reale al contraffattore, anzi, lo espone a rischi immediati.

Si considerino due scenari:

1.  **Clonazione da parte del Proprietario Legittimo:**
    *   Un rivenditore disonesto clona il QR code da un oggetto autentico in suo possesso e lo appone su un oggetto contraffatto.
    *   Vendendo il falso, dovrebbe cedere all'acquirente il token NFT associato all'oggetto autentico per superare la verifica.
    *   Il risultato sarebbe: l'acquirente del falso riceve un token autentico (ed è soddisfatto), ma il rivenditore perde la proprietà digitale dell'oggetto autentico originale.
    *   L'oggetto autentico originale, ora sprovvisto del suo token digitale (che è stato trasferito), risulterebbe **non verificabile** e quindi invendibile al pari di un contraffatto, distruggendo il valore del bene originale.
    *   **Conclusione:** Non esiste alcun incentivo economico per un proprietario legittimo a compiere questa azione, che equivale a distruggere il valore del proprio bene autentico per vendere un falso. L'unico scenario possibile è una frode su sé stessi, senza alcun guadagno.

2.  **Clonazione da parte di un Terzo Malintenzionato:**
    *   Un contraffattore clona il QR code da un prodotto autentico e lo appone su prodotti falsi.
    *   Tuttavia, non possiede il token NFT associato a quel codice, in quanto è custodito nel wallet del legittimo proprietario.
    *   Un acquirente che scansiona il codice sul falso vedrà che la proprietà del token è attribuita a un wallet che non appartiene al venditore (il contraffattore).
    *   Il sistema di verifica mostrerà immediatamente un **mismatch** tra il proprietario registrato (la chiave pubblica esposta dal vero proprietario) e l'identità del venditore, generando un immediato **allarme** di possibile frode.
    *   **Conclusione:** La clonazione del solo QR code senza il possesso del token corrispondente non solo non inganna il sistema, ma lo fa immediatamente scattare, proteggendo il consumatore.

Pertanto, l'utilizzo di QR code standard si rivela **sufficiente e sicuro** in questa architettura. La necessità di tag anti-clonazione costosi (ologrammi, NFC crittografici) viene meno, poiché la sicurezza non è affidata all'inviolabilità del tag fisico, ma alla **impossibilità di trasferire la proprietà digitale senza il consenso crittografico del proprietario** del token.

**4.2 Il Modello Pratico di Proprietà Digitale**

Il sistema opera su un **modello di proprietà pratica e consensuale** che, pur non sostituendo formalmente i contratti giuridici, stabilisce una prova di proprietà incontrovertibile e verificabile da tutte le parti coinvolte.

Il produttore del bene (tipicamente per oggetti di lusso, collezionismo o high-value) fornisce ai propri clienti un'applicazione mobile dedicata. Questa app assolve a tre funzioni fondamentali in modo semplice e intuitivo:
1.  **Wallet Semplicificato:** Custodisce in modo sicuro le chiavi private dell'utente e i token NFT posseduti, astraendo completamente la complessità tecnologica (nessuna gestione di seed phrase per l'utente finale, se non tramite backup semplificati e sicuri).
2.  **Verifica Istantanea:** Permette di verificare l'autenticità e la proprietà di un prodotto semplicemente inquadrando il suo QR code. L'app esegue automaticamente tutti i controlli crittografici e mostra un risultato chiaro e immediato (es. un segno di spunta verde e il nome del produttore).
3.  **Trasferimento Guidato:** Gestisce il trasferimento della proprietà in modo fluidissimo durante una vendita.

**Il Flusso di Vendita Semplificato:**

*   Il **venditore** (es. un negozio) ha il suo sistema di cassa integrato con un software che gestisce il wallet aziendale.
*   L'**acquirente** ha la app del produttore sul suo smartphone, con il proprio wallet già configurato.
*   All'atto dell'acquisto, il cassiere scansiona il QR code del prodotto. Il sistema recupera automaticamente i dettagli del token.
*   Contemporaneamente, l'acquirente apre la app e magari genera un QR code temporaneo per ricevere il token.
*   Il sistema di cassa del venditore, con un clic, avvia la transazione per trasferire il token NFT dal wallet del negozio al wallet dell'acquirente.
*   La transazione viene firmata digitalmente dal wallet del negozio (in modo trasparente per il cassiere) e broadcastata sulla blockchain.
*   Una volta confermata, la proprietà è trasferita. L'acquirente vede il nuovo token apparire magicamente nella sua app, a conferma dell'avvenuto passaggio.

In questo modello, tutte le parti conoscono e accettano le regole del "gioco": il possesso del token *equivale* alla proprietà del bene. Il venditore non avrebbe alcun interesse a vendere un prodotto falso e trasferire un token autentico, poiché distruggerebbe il valore del bene originale. Il cliente, ricevendo il token autentico direttamente nella propria app durante la vendita, ha la prova immediata e incontrovertibile di aver acquistato un prodotto genuino e di esserne il nuovo proprietario registrato.

Questo sistema si regge quindi non su un formale costrutto giuridico impositivo, ma su un **ecosistema di valore condiviso e su un meccanismo tecnologicamente enforced** che allinea perfettamente gli incentivi di tutte le parti, rendendo la frode non vantaggiosa e immediatamente rilevabile. La proprietà digitale diventa una convenzione pratica, estremamente robusta e utile, che vive affiancata al sistema giuridico tradizionale, fornendo uno strumento di verifica e trasferimento senza precedenti in termini di velocità, sicurezza e trasparenza.

**5. RISULTATI E DISCUSSIONE**

Il sistema proposto raggiunge un livello di **decentralizzazione e trustlessness** superiore alle soluzioni esistenti. L'utilizzo del token NFT come rappresentazione della proprietà legale, associato al meccanismo di verifica crittografica che sfrutta un semplice codice QR/RFID come semplice puntatore, elimina qualsiasi punto di fallimento centralizzato. I consumatori possono verificare in modo indipendente e senza bisogno di fidarsi del venditore o di un ente terzo sia l'autenticità del prodotto che la legittimità della sua proprietà prima di un acquisto, semplicemente scansionando un codice e confrontando chiavi pubbliche. Questo rappresenta un avanzamento significativo verso relazioni commerciali più trasparenti e sicure.

**6. CONCLUSIONI**

**6.1 Summary**

In questo progetto, è stato proposto un sistema di verifica dei prodotti autentici basato su tecnologia blockchain e token NFT, in cui tutte le storie di trasferimento della proprietà digitale sono registrate perpetualmente in un registro immutabile utilizzando smart contract. Il processo di registrazione del prodotto, trasferimento, tracciamento e verifica è realizzato attraverso la collaborazione di smart contract e un portale di verifica trustless. I consumatori possono unirsi alla rete come nodi leggeri per verificare l'autenticità e la proprietà. Il sistema ha caratteristiche **decentralizzate e trustless** evidenti, che eliminano la possibilità di manomissione privata dei dati e la necessità di fidarsi di un verificatore centrale. Il codice fisico sul prodotto (QR/RFID) assume il ruolo minimale e sicuro di semplice link al sistema di verifica, mentre la prova definitiva di autenticità e proprietà risiede nella matematica crittografica e nel consenso decentralizzato della blockchain. Attraverso un'analisi approfondita delle esigenze, abbiamo progettato un sistema decentralizzato basato su blockchain e rete KYPC/NFT. Per alleviare il problema dell'esplosione dei dati, utilizziamo una gestione collaborativa dei dati on-chain e off-chain. Per proteggere le informazioni commerciali sensibili, utilizziamo smart contract di livello aziendale invece dei tradizionali record transazionali.

**6.2 Raccomandazioni per progetti futuri**

Ottimizzare il sistema di tracciabilità proposto è il nostro futuro lavoro di ricerca: Realizzare il caricamento formattato dei dati utilizzando la tecnologia IoT, riducendo la possibilità di errori di inserimento manuale. Esplorare l'integrazione con sistemi di Identity Decentralizzata (DID) per una gestione dell'identità del produttore e del cliente ancora più robusta e privacy-oriented.

**7. RIFERIMENTI BIBLIOGRAFICI**

[1] S. A. H. S. Amiri, A. Zahedi, M. Kazemi, J. Soroor, and M. HajiaghaeiKeshteli, "Determination of the optimal sales level of perishable goods in a twoechelon supply chain network," Comput. Ind. Eng., vol. 139, Jan. 2020, Art. no. 106156, doi: 10.1016/j.cie.2019.106156.
[2] J. Sun, J. Tang, W. Fu, Z. Chen, and Y. Niu, "Construction of a multiechelon supply chain complex network evolution model and robustness analysis of cascading failure," Comput. Ind. Eng., vol. 144, Jun. 2020, Art. no. 106457, doi: 10.1016/j.cie.2020.106457.
[3] A. Batwa and A. Norrman, "A framework for exploring blockchain technology in supply chain management," Oper. Supply Chain Manage., Int. J., vol. 13, pp. 294-306, Apr. 2020, doi: 10.31387/OSCM020271.
[4] M. Abdirad and K. Krishnan, "Industry 4.0 in logistics and supply chain management: A systematic literature review," Eng. Manage. J., pp. 1-15, Jul. 2020, doi: 10.1080/10429247.2020.1783935.
[5] J. Yoon, S. Talluri, and C. Rosales, "Procurement decisions and information sharing under multi-tier disruption risk in a supply chain,"Int. J. Prod. Res., vol. 58, no. 5, pp. 1362-1383, Mar. 2020, doi: 10.1080/00207543.2019.1634296.
[6] D. Ivanov, "Predicting the impacts of epidemic outbreaks on global supply chains: A simulation-based analysis on the coronavirus outbreak (COVID-19/SARSCoV-2) case," Transp. Res. E, Logistics Transp. Rev., vol. 136, Apr. 2020, Art. no. 101922, doi: 10.1016/j.tre.2020.101922.
[7] T. Sawik, "Two-period vs. multi-period model for supply chain disruption management," Int. J. Prod. Res., vol. 57, no. 14, pp. 4502-4518, Jul. 2019, doi: 10.1080/00207543.2018.1504246.
[8] A. Alora and M. K. Barua, "An integrated structural modelling and MICMAC analysis for supply chain disruption risk classification and prioritization in 32 India," Int. J. Value Chain Manage., vol. 10, no. 1, p. 1, 2019.
[9] V. Ahlyvst, A. Norrman, and M. Jahre, "Supply chain risk governance: Towards a conceptual multi-level framework," Oper. Supply Chain Manage., Int. J., vol. 13, no. 4, pp. 382395, 2020, doi: 10.31387/oscm0430278.
[10] L. Luo, G. Q. Shen, G. Xu, Y. Liu, and Y. Wang, "Stakeholder-associated supply chain risks and their interactions in a prefabricated building project in Hong Kong," J. Manage. Eng., vol. 35, no. 2, Mar. 2019, Art. no. 05018015, doi: 10.1061/(ASCE)ME.1943-5479.0000675.
