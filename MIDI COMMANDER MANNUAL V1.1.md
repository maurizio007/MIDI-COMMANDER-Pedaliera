CHE COSA E' MIDI CONTROL ?

Il nome completo Di Midi Control è MUSiCAL INSTRUMENT DIGITAL INTERFACE. Rispetto al Midi Control, concetto di musica per computer Midi puo' essere piu' familiare alla maggior parte dei musicisti e produttori. In sostanza, sia il Midi Control che i toni Midi trasferiscono piccoli dati su computer o dispositivi mobili, quindi traducono i dati ricevuti in note musicali o controllano il messaggio per apportare una modifica preimpostata. Se è una nota Midi, verrà, sintetizzata dal computer per riprodurre musica. Se si tratta di un messaggio di controllo, l' Host ricevuto esegurà l'azione predefinita, come il cambio di patch. Il vantaggio del formato Midi è la sua piccola dimensione dei dati. Un canto è prodotto da Midi e la dimensione dei dati è generalmente nell' intervallo di diversi kilobyte che sono quasi 1/100 delle dimensioni di un normale file MP3. Quindi è conveniente realizzare la comunicazione in tempo reale. Quello che segue è una breve introduzione di diversi concetti di base sul Midi Controller e utilizzarlo rapidamente.



CANALE MIDI

La comunicazione Midi si verifica nell'invio (con interfaccia MIDI OUT) e nella ricezione (con interfaccia MIDI IN). Tutti i dispositivi devono essere impostati nello stesso canale Midi da CH1 a CH6 prima della della comunicazione, altrimenti non risponderanno al segnale Midi. E possono anche ricevere ed eseguire azioni sul segnale Midi se impostato per ricevere tutti i segnali del canale (1-16). Suggerimenti: il canale predefinito della maggior parte dei dispositivi Midi è il canale 1.



CONNESSIONE MIDI

Come accennato in precedenza i dispositivi supportano Midi sempre dotati di Midi Connector. Generalmente, il cavo Midi è un cavo da maschio a maschio a 5 Pin, collegato al dispositivo e tramite presa. MINI IN e OUT utilizzano lo stesso calzino in modo che possano essere distinti semplicemente identificando il calzino. Il principio di connessione è quello di collegare Midi Out del dispositivo di invio al Midi In del dispositivo di ricezione. A volte è presente una presa Midi per la trasmissione dei dati ricevuti ad altri dispositivi.



COMANDI MIDI

E' la sezione più importante. Le istruzioni / comandi Midi sono un insieme di dati con parametri in formato fisso. E dovremmo conoscere la classificazione e la struttura logica. Come introdotto sopra, la maggior parte dei dati Midi sono note Midi per la riproduzione di musica Midi, inclusa l'intensità e il volume delle note. Ci preoccupiamo di più della trasmissione e della funzione dei comandi di controllo Midi. I comandi inviati dal Controller Midi sono immessi con uno schema particolare, che includeva principalmente comandi PC (PC sta per Program Change) e comandi di CC (CC sta per Continuous Controller). In termini semplici, il comando PC includeva un numero indice compreso tra 0(zero) e 127. L'Host cambierà il numero attuale corrispondente al numero PC ricevuto. Le istruzioni Midi PC sono supportate nella maggior parte dei sintetizzatori soft e delle tastiere Midi. Un comando CC viene normalmente utilizzato per controllare altri parametri, come ON/OFF di un modulo effetto, la posizione di un pedale di espressione (EXP). Il comando CC includeva principalmente due numeri. IL primo è il numero indice CC (0-127) e il secondo è il sotto-parametro (0-127). Il numero indice è un'etichetta per determinare diverse istruzioni, mentre il  sotto-parametro è il contenuto effettivo. In generale gli oggetti controllati si verificano regolarmente, come il volume, Wah, stato ON/OFF e interruttore modulo. Il valore di sotto-parametro, rappresenta gli stati. Ad esempio, nel controllo volume, i dati 0-127 corrispondono al volume. Per alcuni stati ON/OFF, 0-63 rappresenta lo stato OFF mentre 64-127 lo stato ON. 



IMPARA MIDI

Non esiste uno standard rigoroso nella funzione dei comandi CC e varia a seconda dei dispositivi e produttori. Dobbiamo fare alcune semplici impostazioni per recuperare dispositivi o controller per archiviare la funzione di controllo. C'è un modo chiamato apprendimento Midi. Apri la modalità di apprendimento Midi nel dispositivo di ricezione quando impostata e entra in uno stato di attesa. Quindi il controller invia un comando CC al dispositivo ricevente che registrerà quindi il comando CC e lo assegnerà all'azione corrente. La funzione di apprendimento Midi è supportata da apparecchiature o App Host e fornisce un modo per mappare CC# alle azioni senza conoscere il contenuto dettagliato del comando.



PANORAMICA DEL MIDI COMMANDER

Midi Commander è un dispositivo di controllo unico sul mercato ed è un pedale di controllo molto speciale nella serie THONE SHIFFER. E' conveniente per i chitarristi controllare e cambiare il tono usando usando l'interruttore a pedale quando usano il dispositivo di fascia alta (come effetti software, multi-effetto avanzato, equipaggiamento rack e amplificatori valvolari con controllo Midi). Oltre alla maggior parte delle App.-software di registrazione/effetti, è possibile controllare anche la maggior parte degli ingranaggi hardware con Jack MIDI IN. Midi Commander organizza normali funzioni di controllo basate su Host diversi (software o attrezzatura che ricevono i comandi) e predefiniti come modalità di Host. Inoltre, ha anche due Host personalizzabili che viene utilizzato per organizzare la mappatura della funzione di controllo Midi definita dall'utente con interruttori a pedale. Ha anche due ingressi per pedali di espressione (EXP1 -EXP2) che controllano Volume e Wah per aiutare la flessibilità e la creatività del suonare. Può essere alimentato da 2 batterie serie AAA o USB e ha anche la funzione di ricarica automatica per batterie ricaricabili (richiede un'attivazione speciale per evitare la carica accidentale o corrente alta). Questo design del pedale archivia dimensioni e peso minimi pur mantenendo il suo uso. Può essere utilizza insieme ad altre interfacce audio o dispositivi hardware per spettacoli dal vivo e registrazioni.



CARATTERISTICHE CHIAVE

* Compatibile con controllo USB-MIDI standard.
* Con 10 interruttori a pedale, aumenta la libertà di controllo.
* 2 connettori di ingresso per pedale di espressione analogica (EXP1-EXP2) individuale con display che mostra le posizioni del pedale.
* 6 modelli host predefiniti incluso JAMUP, BIAS FX, KPA, etc......
* 2 modalità host personalizzate.
* Peso 0,95Kg.
* Dimensioni 286x110x65mm.



CONNETTORI / BOTTONI

L'immagine seguente mostra che l'interfaccia hardware di MIDI COMMANDER è composta da 10 interruttori a pedale in metallo; sulla dimensione della parte superiore, ci sono l'interruttore di alimentazione, USB, interfaccia di input del pedale di espressione di uscita Midi; sul retro c'è una casa-batteria per 2 batterie serie AAA. Al centro dello schermo, puoi vedere tutti i parametri di controllo relativi e le informazioni principali. E' stato facile disattivare lo schermo del computer o del dispositivo mobile quando si utilizzano effetti software.

![](C:\Users\B M\Desktop\5000\OK BENE.jpg)



CONNESSIONE

La sezione seguente mostra le possibili connessioni dell'utilizzo del MIDI COMMANDER con altri dispositivi.

° Utilizzando il cavo USB collegare direttamente il PC con Windows / Mac OS e può essere identificato dal sistema driver.

°Sul retro è presente un vano batteria, è possibile inserire 2 batterie serie AAA. Va bene con batterie normali o batterie ricaricabili. Si prega di notare se inserito con batterie normali di NON utilizzare la funzione di ricarica per ricaricare le batterie.

° L'interfaccia del pedale di espressione viene utilizzata per collegare il pedale di controllo dell'espressione analogica standard ( esempi di pedali disponibili allegati).

![](C:\Users\B M\Desktop\5000\Immagine pedali.jpg)

° Adozione del cavo MIDI OUT ad altri dispositivi Porta Midi. E' necessario solo il collegamento USB quando si controllano gli effetti software o altri software ricorrenti.

° E' necessario il cavo LIGHTNING OTG per collegare un dispositivo mobile iOS, ad esmpio il nome ufficiale di PHONE / iPAD è LIGHTNING per adattare fotocamera USB. Il cavo OTG con ricarica su i DEVICE è un buon modo per rendere possibile la riproduzione a lungo.



FUNZIONI

1) Passa a diverse modalità HOST.

Premi diversi pulsanti tieni premuto e accendi l'alimentatore, puoi passare a diverse modalità Host. Fare riferimento alla seguente tabella di spiegazioni per le diverse modalità HOST 

![](C:\Users\B M\Desktop\5000\Immagineeeee.jpg)



Attenzione la corrispondenza della modalità HOST con l' HOST reale non è obbligatoria. Può essere più flessibile nella scelta della modalità Host per soddisfare la domanda finale e il controllo è totalmente deciso dagli attuali comandi PC e CC. Non esiste uno standard rigoroso tra i produttori. Non possiamo garantire che tutte le istruzioni siano abbinate per tutte le funzioni di controllo attuali anche quando è abbinata la modalità HOST.

2)  Entrate nella modalità di ricarica.

Dopo aver inserito le 2 AAA BATTERIE NiMH e aver effettuato il collegamento con l' alimentazione USB, premere il pulsante "UP" e tenere premuto POWER, il dispositivo entra in modalità di ricarica. Il processo di ricarica è automatico e si interromperà quando sarà completamente carico. Come riferimento, per caricare la batteria da 800 mAh, il tempo è di circa 3 ore. Il processo di ricarica è controllato da un controller intelligente integrato. Si noti di NON caricare le batterie NON RICARICABILI. Le batterie e il suo cavo USB, possono essere presentati insieme. Quando è alimentato da USB, il pedale smetterà di ricevere corrente dalle batterie. La batteria NiMH non è adatta per essere mantenuta completamente in  carica di mantenimento a bassa corrente a lungo termine. Quindi, quando entra in modalità di ricarica, l'alimentatore USB non eseguirà alcuna ricarica delle batterie.

3)  Entra nella modalità di configurazione dell'Host personalizzata.

Premere i pulsante"GIU'  " per accendere ed accedere al menù della modalità di configurazione dell' Host personalizzata. Ci sono 3 sotto-menù, " Midi.CH ", " CUS- 1", "CUS- 2". E' possibile cambiare i menù premendo il pulsante 2 e il pulsante 3.

MIDI.CH viene utilizzato per impostare il canale MIDI di ciascuna modalità HOST. Sotto la modalità, premendo SU / GIU' è possibile scegliere diverse modalità HOST. Premendo i pulsanti B o C è possibile impostare il canale MIDI per questo HOST. Le impostazioni vengono mantenute anche dopo lo spegnimento.

Il menù CUS-1 serve per impostare tutti i  parametri personalizzati nelle modalità HOST CUS-1. Fare riferimento ai parametri e alle funzioni come indicato nella tabella seguente.

![](C:\Users\B M\Desktop\5000\TABELLA FINITA.jpg)

Ci sono alcuni conflitti che si verificano in determinate circostanze. Ad esempio per impostare 4 toni per un gruppo, i pulsanti da 1 a 4 non saranno disponibili per la modalità istruzione PC. Impostare 5 toni per un gruppo, i pulsanti 1 a 3 non saranno disponibili per la modalità istruzione PC. L'impostazione impostata non funzionerà. (seguire l'ordine di impostazione che inizia da #2 Bank Move alla fine).

Il menù CUS2 viene utilizzato per impostare tutti i parametri personalizzati in modalità HOST CUS2, poichè l'elenco dei parametri e le funzioni sono identiche a quelli del CUS1. Si noti che le impostazioni predefinite di CUS1e CUS2 sono reciprocamente indipendenti ed entrambe le configurazioni possono essere salvate automaticamente dopo le modifiche.



4)  Ripristinare le impostazioni predefinite di fabbrica.

Se disordinate le funzioni, e non volete modificarla una ad una, spegnetela e premete contemporaneamente il pulsante " SU" e " GIU' " , il dispositivo ripristinerà le impostazioni predefinite di fabbrica. Si noti che in questo processo non verrà visualizzato alcun suggerimento. E la modalità predefinita JAMP, tono 1A.

5)  Note aggiuntive.

In alto a sinistra sullo schermo ( vedi fig. 1 riferimento n° 11) mostra lo stato di connessione e lo stato delle batterie di USB MIDI. Notare che quando appare solo la parola " MIDI", la funzione USB-MIDI funzionerà normalmente. Significa anche che il dispositivo è riconosciuto dal sistema operativo. Possiamo anche collegare l'USB al caricabatterie o la porta di ricerca USB di una power BANK. Il comando può funzionare con qualsiasi alimentatore USB anche senza connessione USB e lo schermo mostra solo PWR, mentre non esiste un logo di connessione USB completo. Indipendentemente dal tipo di situazione, il commander può essere utilizzato come controller MIDI autonomo.









​    























 















