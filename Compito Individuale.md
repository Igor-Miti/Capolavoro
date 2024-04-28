# Documento di analisi del problema: Applicazione di noleggio per biciclette

- Introduzione: L'applicazione di noleggio per biciclette è progettata per fornire agli utenti un accesso facilitato alle biciclette per soddisfare le loro esigenze di mobilità urbana. Il sistema punta a garantire un processo semplice e sicuro per prenotare e utilizzare le biciclette, prevenendo furti e offrendo tariffe trasparenti e convenienti.

# Problema

- Congestione del Traffico: In città con elevata congestione del traffico, l'uso delle biciclette può offrire un'alternativa più veloce ed efficiente per gli spostamenti urbani. Riducendo il numero di veicoli in strada, si possono alleviare problemi legati al traffico e migliorare la mobilità.

- Inquinamento Atmosferico: L'utilizzo delle biciclette come mezzo di trasporto aiuta a ridurre l'inquinamento atmosferico. Le biciclette sono alimentate dalla forza umana e non emettono gas nocivi, contribuendo a una migliore qualità dell'aria nelle città.

- Salute e Benessere: L'uso delle biciclette promuove uno stile di vita attivo e sano. Gli utenti che scelgono di noleggiare una bicicletta anziché utilizzare mezzi di trasporto più passivi contribuiscono al miglioramento della loro salute cardiovascolare e generale.

- Parcheggi e Spazio Urbano: Le biciclette richiedono meno spazio di parcheggio rispetto alle auto. Un'app per il noleggio di biciclette può ridurre la necessità di grandi parcheggi e contribuire a liberare spazio nelle aree urbane.

## Funzionalità del sistema

- Registrazione degli utenti: Gli utenti devono poter creare un account nell'applicazione, fornendo le informazioni personali necessarie per la registrazione. Ciò consentirà loro di accedere alle funzionalità complete dell'applicazione.

- Noleggio e prenotazione delle biciclette: Gli utenti devono poter prenotare le biciclette attraverso l'applicazione, selezionando una bicicletta disponibile in base alla loro posizione o alle loro preferenze. Devono anche poter impostare la data e l'orario di inizio e fine noleggio.

- Sblocco e blocco delle biciclette: Il sistema deve fornire un metodo per sbloccare e bloccare le biciclette in modo sicuro. Ciò potrebbe includere l'utilizzo di un codice QR o di una chiave elettronica tramite l'applicazione.

- Gestione dei pagamenti: Il sistema deve consentire agli utenti di effettuare pagamenti in modo sicuro, utilizzando metodi di pagamento come carte di credito o portafogli digitali. Deve inoltre fornire un riepilogo delle tariffe applicate per ogni noleggio.

- Sistema di tracciamento e sicurezza: Il sistema dovrebbe utilizzare tecnologie come il GPS per tracciare e localizzare le biciclette noleggiate. In caso di furto o utilizzo non autorizzato, il sistema dovrebbe mettere in atto misure di sicurezza per localizzare e recuperare la bicicletta.

- Assistenza clienti: Il sistema dovrebbe fornire un supporto clienti dedicato per assistere gli utenti in caso di problemi tecnici o domande sul servizio.

## WBS
![image](https://github.com/Igor-Miti/compito/assets/101175082/823d3219-1585-47c1-9da6-538479f43260)

## UML
https://yuml.me/diagram/usecase/[user]-(Sign%20In),%20[user]-(noleggio%20bici),[user]-(cerca%20bici),(noleggio%20bici)%20%3E(checkout),%20[user%20non%20registrato]%20-%20(noleggio%20bici),[user%20non%20registrato]%20-%20(cerca%20bici),(noleggio%20bici)%20%3E%20(checkout),[user%20non%20registrato]%20-%20(log%20in),[user%20non%20registrato]%20-%20(aggiungi%20metodo%20di%20pagamento)
## Value proposition

### Sostenibilità Ambientale:

- E' un app che tiene conto della sostenibilità ambientale. Le biciclette sono un mezzo di trasporto ecologico, contribuendo a ridurre l'impatto ambientale. Scegliere di noleggiare da noi significa aderire a uno stile di vita sostenibile.

### Tariffe Trasparenti e Competitive:

- L app garantisce tariffe trasparenti senza costi nascosti. Le nostre tariffe competitive assicurano che tu ottenga il massimo valore per il tuo denaro. Offriamo anche piani di noleggio flessibili per adattarci alle tue esigenze.

### Esperienza Utente Impeccabile:

- Forniamo un'esperienza utente intuitiva e di semplice comprendonio , rendendo il processo di noleggio rapido e privo di complicazioni. La nostra interfaccia è semplice e ti permette di prenotare, ritirare e restituire le biciclette con pochi tocchi sullo schermo.

### User story
- Nella capacità di creazione dell'account è possibile registrarsi rapidamente per accedere all'app e sfruttarne tutte le funzionalità(5 ore).

- Attraverso la funzione di ricerca avanzata è possibile filtrare le stazioni di noleggio bici per distanza, disponibilità e caratteristiche specifiche(6 ore).

- Con la raccomandazione personalizzata vengono fornite suggerimenti sulle biciclette in base alle preferenze e alle recensioni degli altri utenti(4 ore).

- Nella capacità di prenotazione è possibile completare rapidamente il processo di prenotazione, visualizzando chiaramente le opzioni e confermando la scelta selezionata(6 ore).

- Con la funzione di sblocco tramite l'app è possibile utilizzare la bicicletta senza l'uso di chiavi fisiche(5 ore).

- Attraverso il monitoraggio del tempo e del costo è possibile tenere traccia in tempo reale del tempo trascorso durante il noleggio e del costo associato(8 ore).

- Nella capacità di creazione dell'account è possibile registrarsi rapidamente per accedere all'app e sfruttarne tutte le funzionalità(4 ore).

## Gestione delle Partnership Internazionali e Multitenancy
### Partnership Internazionali:
- Per espandere la copertura del servizio di noleggio di biciclette, l'applicazione mira a stabilire partnership internazionali con altri paesi. Queste collaborazioni consentiranno l'installazione di nuove stazioni per biciclette in diverse città del mondo, ampliando così l'accesso e l'uso delle biciclette come alternativa di trasporto sostenibile.

### Implementazione del Multitenancy:
- Per gestire efficacemente le partnership internazionali e supportare l'installazione di stazioni per biciclette in diversi paesi, l'applicazione sarà riprogettata per implementare il concetto di multitenancy. Il multitenancy consente di ospitare più istanze dell'applicazione su un'unica infrastruttura, consentendo a ciascun paese di avere la propria configurazione e database separati.

### Gestione delle Istanze:
- Ogni paese partner avrà la propria istanza dell'applicazione, con un'interfaccia personalizzata per rispettare le specifiche locali e linguistiche.
### Isolamento dei Dati:
I dati relativi a ciascun paese saranno isolati e gestiti separatamente per garantire la conformità normativa e la sicurezza dei dati.
### Collaborazione con Paesi:
- Gli amministratori dell'applicazione collaboreranno attivamente con i rappresentanti dei paesi partner per pianificare e coordinare l'installazione delle nuove stazioni per biciclette, assicurandosi che siano integrate correttamente nell'ecosistema dell'applicazione.
## Benefici del Multitenancy e delle Partnership Internazionali:
### Espansione Globale:
- Grazie al multitenancy e alle partnership internazionali, l'applicazione potrà estendere la propria presenza globale, offrendo il servizio di noleggio di biciclette in un numero sempre maggiore di città e paesi.
Diversificazione Culturale: Le diverse istanze dell'applicazione saranno personalizzate per rispettare le esigenze culturali e linguistiche specifiche di ciascun paese, migliorando l'esperienza complessiva degli utenti.
### Impatto Ambientale:
- L'espansione del servizio di noleggio di biciclette contribuirà a promuovere uno stile di vita sostenibile e a ridurre l'impatto ambientale delle congestioni del traffico e dell'inquinamento atmosferico in molte città del mondo.



### Conclusione
- L'applicazione di noleggio per biciclette offre una soluzione per garantire un accesso facilitato alle biciclette, la sicurezza e una tariffazione trasparente. Implementando le funzionalità sopra descritte, il sistema sarà in grado di soddisfare le esigenze degli utenti e fornire un servizio affidabile ed efficiente.
