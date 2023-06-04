# APPUNTI e DOMANDE d'ESAME - INTERAZIONE UOMO MACCHINA

***Un prodotto che nessuno compra è un prodotto inutile***

## Appunti

### design

HMI

design prodotto

design esperienza

design interfaccia

### HCD

human centered design

sviluppo antropocentrico vs sviluppo tecno-centrico
schema ciclico HCD

- specificare il contesto d'uso
- specificare i requisiti
- progettare la soluzione
- testare e valutare

usabilità

### Progettazione delle interfacce

discoverability e understanding

design of useful things

incidente di three mile island

### Principi fondamentali dell'interazione

esperienza

affordance

significanti

mapping

feedback

modello concettuale

immagine di sistema

### Vincoli

classi di vincoli:

- vincoli fisici
- vincoli culturali
- vincoli semantici
- vincoli logici

funzioni obbliganti

- interlock
- lock-in
- lock-out
  
comandi centrati sulle attività

### Come le persone fanno le cose

golfi dell'esecuzione e della valutazione

i 7 stati dell'azione

- scopo

stati d'esecuzione:

- progettare
- specificare
- eseguire

stati di valutazione:

- percepire
- interpretare
- confrontare

i 7 principi fondamentali della progettazione

- cosa voglio ottenere?
- quali sono le sequenze d'azione alternative?
- quale azione posso fare ora?
- cosa è successo?
- cosa significa?
- va bene? ho realizzato il mio scopo?

feedforward e feedback in interaction

i 7 principi fondamentali del design

- visibilità
- feedback
- modello concettuale
- affordance
- significanti
- mapping
- vincoli
  
pensiero umano

conscio e subconscio

tipi di memoria:

- memoria dichiarativa
- memoria procedurale

emozioni e cognizione

processing del cervello:

- livello viscerale
- livello comportamentale
- livello riflessivo

### Errore Umano

root cause analysis

i 5 perché

definizione di errore

- lapsus o slips
  - di azione
  - di memoria
- mistakes
  - rule based
  - knowledge based
  - memory lapse

interruzioni

feedback sbagliati

prevenzione dell'errore

- comprendere le cause dell'errore
- controlli di sensibilità
- annunciare le azioni
- rendere più semplice la scoperta e comprensione degli errori
- aiutare l'utente a compiere correttamente le azioni

per la prevenzione dell'errore utilizzare:

- constraints
- undo
- messaggi di errore e di conferma
- aumentare il numero di controlli
- migliorare il modello concettuale dell'utente
- allertare l'operatore umano quando ci si avvicina a un errore

mitigazione dell'errore usando metafora formaggio svizzero:

- aumentare il numero di controlli (fette di formaggio)
- diminuire la probabilità di errore (buchi nel formaggio)
- allertare l'operatore umano quando ci si avvicina a un errore (buchi si sono allineati)

### Le interfacce utente

livelli di interfacce:

- Human Interface Device (HID)
- Human Machine Interface (HMI)
- Human Computer Interface (HCI)

classificazione delle interfacce:

- tactile UI
- visual UI
- auditory UI
- olfactory UI
- gustatory UI
- equilibrial UI

interfacce che utilizzano più di un senso:

- Composite User Interface (CUI) e  classificazione
  - macrocategorie
    - standard
    - virtual
    - augmented
  - classificazione per numero di sensi
- Graphical User Interface (GUI)
- Multimodal User Interface (MUI)

### Human Interface Design (HID)

protocollo HID

- identità:
  - device
  - host
- protocolli
  - bluetooth HID
  - serial HID
  - ZigBee HID
  - HID over I2C
  - HOGP
  
periferiche HID

- testi e caratteri
  - tastiere
    - layout fisico
    - layout virtuale
    - layout funzionale
  - lettore codici a barre
- sistemi di puntamento
  - classificazione
    - tipo di input
      - diretto
      - indiretto
    - modo in cui il movimento viene mappato
      - assoluto
      - relativo
    - come i dispositivi producano il segnale
      - isotonico
      - isometrico
      - elastico
    - velocità in cui si fa avanzare il puntatore
      - position control
      - rate control
  - esempi
    - eye tracker
      - bright pupil
      - dark pupil
      - passive light  
    - gaze tracking
    - data glove
    - dispostivi aptici
    - smart papers
    - lavagne digitali
- dispositivi per il suono
  - microfono
  - array di microfoni
- sensori di immagini
  - 3D scanning
    - passivi
      - camere stereoscopiche
      - sistemi fotometrici
      - tecniche silhouette
    - attivi
      - time-of-flight
      - triangolazione
      - scanner 3D a luce strutturata
      - scanner 3D a luce modulata
- inertial measurement unit (IMU)
- dispositivi wearable
  - sensori PPG
  - EEG headset

### Natural User Interface (NUI)

per essere tale:

- apprendimento progressivo
- expertise instantanea
- interazione diretta
- basso carico cognitivo

una strategia per realizzare NUI è l'uso della Reality User Interface (RUI)

### Graphical User Interface (GUI)

struttura dell'interfaccia

- struttura gerarchica
- struttura sequenziale
- struttura matriciale
- struttura a database

architettura dell'informazione e natura degli utenti, contenuti e contesti

componenti principali:

- schemi o strutture organizzative
- sistemi di labelling
- sistemi di navigazione
- sistemi di ricerca

tipi di schemi organizzativi:

- esatti
  - schema alfabetico
  - schema cronologico
  - schema geografico  
- soggettivi
  - topic scheme
  - task scheme
  - audience scheme
  - metaphoric scheme

creare ibridi di schemi organizzativi

navigazione nelle interfacce, principi base di findability e discoverability

modelli di comportamento degli utenti per la ricerca di informazioni:

- quit
- narrow
- expand
- pearl growing
- pogosticking
- trashing
- berry picking

antipattern

design pattern:

- autocomplete
- autosuggest
- instat result
- did you mean
- autocorrect
- best first
- partial matches
- related seraches
- federated search
- faceted navigation
- advanced search
- scoped search
- personalization
- pagination
- actionable result
- comparing result
- unfied discovery

layout di interfacce e componenti
Document Object Model (DOM): cross-platform e interfaccia language-independent che permette ai programmi e agli script di accedere e aggiornare il contenuto, la struttura e lo stile dei documenti. Rappresenta il documento come un albero di nodi.
Quando una pagina web JavaScript è caricata, viene creato un Document Object Model (DOM) della pagina che è una rappresentazione object oriented del documento HTML che si interfaccia tra JavaScript e il documento dando la possibilità di:

- aggiungere, cambiare e rimuovere elementi HTML
- cambiare stili CSS
- reagire agli eventi
- creare nuovi eventi

gli elementi dell'interfaccia sono:

- elementi di input
- elementi di navigazione
- componenti informativi
- container

### UX design

identificare le personas mediante:

- task analysis
- feedback
- prototipazione

dipendentemente dai dati che abbiamo possiamo avere 3 tipi di personas:

- proto-personas
- qualitative personas
- statistical personas

principio di Pareto

tipi di informazioni di una personas:

- demografiche
- personali
- attitudinali e cognitivi
- obiettivi e motivazioni
- comportamentali

personas e archetipi

requirements

- funzionali
- non funzionali

user stories

è una breve dichiarazione o astrazione che identifica l'utente e il suo bisogno/obiettivo.
É un requisito espresso dalla prospettiva di un dell'obiettivo dell'utente.
aiutano a documentare informazioni pratiche riguardo gli utenti e aiutano gli sviluppatori a tracciare una roadmap.
struttura: As a 'role', I want 'feature' because 'reason'.
tutti possono scrivere user stories ad ogni livello di dettagli.
i dettagli possono essere aggiunti splittando le user stories in multiple user stories o aggiugendo condizioni di soddisfazione.

scenarios

uno scenario è una situazione che cattura come gli utenti interagiscono con un prodotto.

un buon scenario deve rispondere:

- chi è l'utente?
- motivazione e aspettativa dal prodotto?
- qual'è il suo obiettivo?

grazie agli scenarios possiamo determinare:

- i punti importanti durante progettazione per l'UX
- fasi del processo che richiedono ulteriore revisione e attenzione
- le principali esigenze e motivazioni dell'utente
  
modi per scrivere scenarios:

- goal o task orinentati agli scenarios
- elaborated scenarios
- full scale task scenarios

casi d'uso

è una descrizione scritta di come un utente interagisce con un sistema.
ogni caso d'uso è rappresentato come una sequenza di passaggi che iniziano con l'obiettivo dell'utente e terminano quando l'obiettivo è raggiunto.
un caso d'uso aggiunge valore perché aiuta a spiegare come il sistema dovrebbe comportarsi e forniscono una lista di obiettivi.

scenarios vs casi d'uso

uno scenario richiede una situazione che può avere uno o più attori che intraprendono una determinata funzionalità.
un caso d'uso coinvolge un attore e il flusso che un particolare attore prende in una determinata funzionalità o percorso..
la differenza principale è la prospettiva.

includono:

- l'utente
- cosa vuole fare
- il suo scopo
- step necessari per raggiungere lo scopo
- feedback
- trigger
- basic flow
- alternative flow
  
non includono:

- dettagli implementativi o di scelta tecnologica
- dettagli di UI

i passaggi da seguire per la creazione di un caso d'uso sono:

1. identificare le personas
2. sceglierne una per caso d'uso
3. identificare il suo scopo
4. discenderne i task principali da quelli secondari
5. considerare le sequenze alternative
6. accoppiare punti in comune tra in vari casi d'uso
7. ripetere per tutte le personas

### Front-end design Wireframing

wireframe: per trasmettere la tua idea alle altre persone, si creano progetti che aiutano la comuncazione tra designer e sviluppatori attraverso sketch basici che mostrano la struttura generale.

tipi di wireframe:

- low fidelity: semplici sketch che si concentrano sulla struttura
- high fidelity: rappresentazioni dettagliate con una basica interfaccia e icone.

contesto ha un importante ruolo nell'UX design per adattarci ai comportamenti e alle preferenze degli utenti.

adattibilità è la capacità di un sistema di adattarsi a diversi contesti senza cambiare la sua struttura e copre le nozioni di:

- responsive design
- accessibilità

il responsive design è un approccio di progettazione che permette ai siti web di adattarsi a diversi dispositivi e dimensioni dello schermo per avere una buona esperienza coerente con tuti i dispositivi.

tecniche di responsive design:

- flexible grid
- flexible images
- media queries & breakpoints

una filosofia di reposive design è mobile first che consiste nel progettare prima per i dispositivi mobili e poi per i desktop e ciò ci fa concentrare prima sulle funzionalità base.
Ciò si oppone alla degradazione in cui si sviluppa prima per i desktop per poi rimuovere alcune funzionalità per adattarsi ai dispositivi mobili perdendo però consistenza dei vari dispositivi.

altre best practise del responsive design:

- keep it simple : design minimal
- priorizzare il contenuto
- progettare per il touch : bottoni grandi
- ottimizzare tempi di caricamento : ridurre componenti pesanti come immagini
- testare su diversi dispositivi

Adaptive design è un altra alternativa al responsive design che consiste nel creare un interfaccia che si adatta automaticamente ai vari utenti in modo fluido e flessibile.
Solitamente realizzata creando più versioni del sito web per ogni dispositivo.

Adaptive UX ottiene informazione basiche tra i vari utenti e le usa per adattare l'interfaccia e consigliare ad ogni utente cosa è migliore per lui attraverso il collaborative filtering e il content based filtering.

Nell UX design è cruciale anche l'accessibilità che consiste nel rendere il prodotto accessibile a tutti gli utenti indipendentemente dalle loro capacità fisiche o cognitive in modo che ogni utente possa accedere a tutte le funzionalità del prodotto.
Alcuni problemi di accessibilità sono:

- visuale
- motoria
- uditiva
- convulsioni
- cognitive

L'azienda W3C ha posto degli standard e delel linee guida per l'accssibilità chiamate Web Content Accessibility Guidelines (WCAG) e consigliano:

- alternative testuali per contenuti non testuali come immagini e grafici
- sottotioli o altre alternative per contenuti multimediali
- diversi modi per usufruire dei contentuti
- contenuti facili da vedere e da ascoltare
- utenti possono usare altre modalità di input oltre la tastiera
- struttura facile da navigare e da capire

Oltre ai wireframes che ci aiutano a comunicare le nostre idee, abbiamo bisogno di uno schema di navigazione che ci aiuti a capire come gli utenti possono navigare nel nostro sito web.
Lo facciamo attraverso gli user flows che sono una rappresentazione visuale di come gli utenti possono navigare nel nostro sito web. I più comuni sono:

- flowchart è un diagramma di flusso che mostra le varie possibili scelte che un utente può fare e le conseguenze di queste scelte.
- wireflows esprimono un diagramma di flusso usando wireframe invece di descrizioni astratte

### Metodi e strumenti per l'innovazione

Un innovazione è qualcosa di originale e utile che entra nel mercato e che cambia il modo in cui le persone vivono e lavorano. Spesso è legata al mondo delle invenzioni ma non necessariamente.

sustaining innovation cioè migliorare un prodotto esistente:

- step by step
- basso rischio
- bassa velocità
- non cambia organizzazione aziendale
- non ha bisogno di nuove competenze da parte degli utenti
- basse probabilità di scalare il mercato
- target di mercato stabile

disruptive innovation, usato per creare nuovi mercati cerca di non basarsi sulle tecnologie esistenti per raggiungere utenti che non sono serviti dai prodotti esistenti

human centered desing process cerca di sviluppare un sistema che sia utile e utilizzabile concentrandosi sugli utenti cercando di migliorare l'efficacia e l'efficienza.

Il product management si occupa del cosa mantre il product development si occupa del come. Lavorano insieme, il product development team prende le specifiche dal product manager e le implementa in un prodotto funzionante.

Ideo ha sviluppato un processo di innovazione human centered che si basa su 3 fasi:

1. ispirazione : approfondisce i bisogni e le richieste degli utenti per migliorare uno strumento, osservando come viene usato.
2. ideazione : si cerca di interpretare le conoscenze assunte per arrivare a qualcosa di più tangibile tramite la creazione di un semplice prototipo. non definitivo e neacnhe perfetto ma utile come punto di partenza per continuare a testare e fare considerazioni.
3. implementazione : si cerca di capire come il prodotto può essere implementato nel mondo reale e come può essere scalato.

Ciascuna di queste fase è svolta dal team con un approccio a fisarmonica, seguendo uno schema detto "Double Diamond" in cui all'inizio si lavora per produrre idee e soluzioni in quantità (divergenza) per poi concentrarsi su quelle più promettenti (convergenza).

Design thinking è un approccio all'innovazione che poggia le sue fondamenta sulla capacià di risolvere problemi complessi utilizzando una visione e una gestione del progetto basata sulla creatività.
Si basa su un processo iterativo che cerca di capire l'utente facendo delle assunzioni.

obiettivi:

- avvicinarsi al cliente
- favorire la creatività e generare idee
- sperimenare le idee con prototipi

fasi principali:

1. empatizzare : identificare il problema e l'obiettivo, scrivendo le personas
2. definire : delineare i bisogni degli utenti e le varie categorie di utenti, facendo user stories
3. ideare : ricercare una soluzione al problema, facendo brainstorming
4. prototipare : realizzare i primi prototipi
5. testare : testare i prototipi sul campo e raccogliere feedback dagli utenti

Lo Human centered desing è un mindset, un modo di pensare e di approcciarsi allo sviluppo di prodotti, il Design thinking invece è un vero e proprio metodo di lavoro organizzato per fasi che consente di sviluppare prodotti centrati sull'utenze grazie alle tecniche orientate alla stimolazione della creatività e alla produzione di idee.
Human centered design e Design thinking sono compatibili e combinabili in un metodo detto Social Enterprise Thinking

### Metodi di sviluppo per prodotti innovativi

agile, scrum e devops

modello waterfall è un metodologia lineare per lo sviluppo di progetti in cui ogni fase ricasca sulla successiva ed è strutturato in 5 parti:

1. analisi dei requisiti
2. progettazione
3. svilluppo
4. collaudo
5. manutenzione

Il modello agile è un metodo di sviluppo software che si basa sul creare e rispondere al cambiamento e pone le fondamenta sui 12 principi del manifesto per sviluppo software agile
Una cosa che contraddistingue agile è il fatto di concentrarsi sulle persone che fanno il loro lavoro e come lavorano insieme.
Le soluzioni vengono raggiunte attraverso la collaborazione tra team multidisciplinari e auto-organizzati.

Il modello scrum è una sottocategoria agile

modello devops : sottocategoria agile per cloud

### Prototipazione di interfacce

pretotipo

thoughtland

actionland

pretotype vs prototype

obiettivi del pretotyping sono aiutare a:

- identificare funzionalià chiave
- decidere le funzionalità da implemtare nel mockup
- test sui mockup e collezione dei feedback e dati
- analisi dei dati e determinare il prossimo passo

i 7 pilasti del pretotyping:

- obbedire alla legge del fallimento del mercato
- assicurarsi di star costruendo il prodotto giusto
- non perdersi in chiacchere, idee o opinioni
- fidarsi solo dei propri dati
- fare pretotyping
- parlare con i numeri e con i fatti
- pensa globalmente, testa localmente

Flusso del pretotyping

1. isolare l'assunzione chiave
2. scegliere un tipo di pretotype
3. fare ipotesi di mercato (ipotesi XYZ)
4. testare il pretotype
5. imparare, rifinire, hyperzoom

tipi di pretotyping

- fake door
- mechanical turk
- impersonator

minimum viable product

### Industria 4.0

internet

internet of things (IoT)

story of industry

digital twin

prodotti e servizi smart

nuovi principi del design

- UX per IoT
- device specializzati con differenti capacità
- far interagire i dispositivi tra loro
- controllo remoto
- design per network
- design per risparmio d'energia

## Domande orale

1. differenza tra design thinking e human centered design
2. esempio di mapping
3. cos'è uno scenarios? da cosa parto per definirli?
4. cos'è un prototipo? gradi di fedeltà?
5. cos'è la ppg?
6. cos'è lo scanner time-of-flight?
7. user behavior pattern? *
8. come deve essere un feedback?
9. differenza tra mockup e prototipo? *mockup
10. cos'è una imu?
11. cos'è un sistema di eyetracking e quali tecnologie conosciamo?
12. cosa sono l'euristiche di newtan? *
13. quali sono gli errori umani?
14. prese x persone. quale sarà il numero y che fa le z cose? *
15. cos'è lo human center design process?
16. cos'è il test qualitativo? *
17. scanner 3d a luce strutturata
18. cosa sono lapsus d'azione
19. modello concettuale fa parte del sistema?
20. cos'è il paradigma?
21. cos'è una nui?
22. come si scrivono le user stories?
23. cos'è l'immagine di un sistema
24. quali sono i sette stadi dell'azione?
25. cos'è un wireframe?
26. cos'è un modello a doppio diamante?
27. cos'è un dispositivo aptico?
28. differenza affordance significativa?
29. tipi di test?
30. quali sono i principi fondamentali dell'interazione?
31. cos'è l'HID protocol?
32. differenza tra user stories e requirements?
33. parlami dei vincoli
34. come devono essere i feedback?
35. struttura interallacciata *
36. la regola dei 5 perché?
37. discoverability e understanding
38. differenza tra prototipo e pretotipo
39. livelli mentali dell'essere umano
40. i 7 stadi dell'azione
41. come si dividono i sistemi di puntamento?
42. distruptive innovation
43. 6 caratteristiche principali del prototipo *
